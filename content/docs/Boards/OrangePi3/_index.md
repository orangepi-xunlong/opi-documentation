---
weight: 4
title: "Orange Pi 3"
---

<!-- Board Official Name -->
# Orange Pi 3

<!-- Image, prefer raw ones with no comments or marks -->

![Orange Pi 3](/images/opi3.jpg "Orange Pi 3")



<!-- Hardware description, taken from the OPI product page-->
## Hardware Specification
|Feature|Description|
|:--:|:-- |
|CPU | H6 Quad-core 64-bit 1.8GHZ ARM Cortex™-A53 |
|GPU | Mali-T720 GPU, OpenGL ES1.1/2.0/3.0/3.1, DX11, Supports ASTC(Adaptive Scalable Texture Compression)|
|Memory| 1GB or 2GB LPDDR3 |
| Storage | 8GB EMMC flash, MicroSD slot for up to 128GB  |
|Networking | Onboard WIFI + Bluetooth: AP6256 IEEE 802.11 a/b/g/n/ac, BT5.0<br> Ethernet: Realtek RTL8211E 10/100/1000Mbps|
|Audio | Output: 3.5mm Jack and HDMI2.0a,<br> Input: MIC|
|Video Outputs | HDMI 2.0a and CVBS|
|PCIe | Supports RC mode, Supports x1 Gen2(5.0Gbps) lane|
|USB | 4x USB 3.0 Host, 1x USB 2.0 Host, 1x USB OTG 2.0 |
|Debug UART | 3pins Debug UART |
|GPIO | GPIO1 26 pins|
|Buttons | Power(SW4)|
|Power Source | DC input，MicroUSB (OTG)|
|LED | Power LED, Status LED and USB3.0 LED|
|PCB | 8 Layer|
|Dimension| 90mm*64mm |


<!--  OEM data (must be coordinated/configrmed with Orange Pi)-->
## Product's Life Cycle

| Parameter | Status  |
|:--:|:--:|
| Production status: | In Production |
| Expected EOL: | Not available |
| Mainline Support:| Partial |

<!-- OS Support with links to the download page if possible -->
## Supported Operating Systems: 

- [Armbian](https://www.armbian.com/orange-pi-3/) linux, different Debian or Ubuntu flavours to pick, active develpment
- [Android](#)


Support Matrix: 

| Project |  Upstream Support | Downstream Support | Not Supported | 
|:--:|:--:|:--:|:--:|
| Linux Kernel | Yes | Yes | | 
|U-Boot| Yes | Yes||
| Yocto| | | X |
|Buildroot| | |X|

Defconfigs: 
    
Linux defconfig: 
U-Boot defconfig: 

<!-- Specific Library support (always with the link to the lib code) -->
## Sofware library support and variants
- [Opi_GPIO](https://github.com/user_/lib_)