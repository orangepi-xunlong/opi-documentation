---
bookFlatSection: true
weight: 2
title: "Connect to a Wi-Fi network"
---

# Add a Wi-Fi Connection

Their are several ways to add  a Wi-Fi Connection, depending on your preference. These ways are listed below:
All of these methods  assume that your board has Wi-Fi, and/or a USB Wi-Fi adapter
#

## Method 1: `nmtui`
The `nmtui` tool, or `NetworkManager Text User Interface`, is a component of NetworkManager, and can be used (in a TUI style) to add and select a Wi-Fi network.
Nmtui is, however, also capable of managing other types of networks, and depending on your circumstances may not be the best option. This leads is to...

## Method 2: `nmcli `
`nmcli`, like `nmtui`, is a component of networkmanager, and has the same features.

To connect to a wireless network, follow these instructions:

### 1: list wireless networks
To show a list of Wi-Fi networks, at a sudo-enabled terminal, enter:

```bash
 sudo nmcli device wifi list
```

The output should look like this:

```bash

*  SSID               MODE     CHAN     RATE          SIGNAL      BARS      SECURITY
*  Orange-Pi-wifi     Infra     11       54 Mbit/s      100         ▂▄▆█     --
   A13-Wifi           Infra      6       54 Mbit/s       30          ▂___    WPA1 WPA2
   2WIRE533           Infra     10       54 Mbit/s       44          ▂▄__    WPA1 WPA2


```

### Connect to network (without password)
If your network does *not* require a password (I.E. is not secure), you can connect to it with the following command:


```bash
 sudo nmcli device wifi connect 'WiFINetworkName' ifname wlan0
 ```

Give it a few seconds to connect, then verify your connectivity with:

```bash
 ip -br address show dev wlan0
 ```

### Connect to network (with password)
However, if your network does require a password (as most should), you may connect to it with the following command, replacing `WiFiNetworkName` and `WiFiNetworkPass` with your network name and password, respectively:



```bash
 sudo nmcli device wifi connect 'WiFiNetworkName' password 'WifiPass' ifname wlan0
 ```

Please do keep in mind that you will *not* receive feedback while typing the *password* component of the above command, for security reasons.

Once again, verify your connectivity with:

```bash
 ip -br address show dev wlan0
 ```
