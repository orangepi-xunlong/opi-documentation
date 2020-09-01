---
weight: 2
title: "Orange Pi 4B"
---

<!-- Board Official Name -->
# Orange Pi 4

<!-- Image, prefer raw ones with no comments or marks -->

![Orange Pi 4](/images/opi4b.jpg "Orange Pi 4")



<!-- Hardware description, taken from the OPI product page-->
## Hardware Specification
|Feature|Description|
|:--:|:-- |
|CPU | Rockchip RK3399 (2x Cortex-A72 @ up to 2.0GHz, 4x Cortex-A53 @ up to 1.5GHz) |
|GPU | Mali-T864 GPU, OpenGL ES1.1/2.0/3.0/3.1, OpenVG1.1, OpenCL, DX11, Supports AFBC (ARM Frame Buffer Compression)|
| NPU | SPR2801S, adopt MPE and APiM unique AI architecture. Typical calculation power 2.8Tops, with 9.3Tops/W ultra high performance |
|Memory| Dual 4GB LPDDR4 |
| Storage | 16GB EMMC flash, MicroSD slot for up to 128GB  |
|Networking | Onboard WIFI + Bluetooth: AP6256 IEEE 802.11 a/b/g/n/ac, BT5.0<br> Ethernet: Realtek RTL8211E 10/100/1000Mbps|
|Audio | Output: 3.5mm Jack and HDMI2.0a,<br> Input: MIC|
|Video Outputs | 1 x HDMI 2.0 ( Type-A ), Supports 4K@60fps output<br> 1 x DP 1.2 (Display Port) , Supports 4K@60fps output,<br> Supports Dual MIPI-DSI（4 lines per channel）|
|Camera | 2 x MIPI-CSI(MIPI_RX0, MIPI_TX1/RX1) |
|USB | 2 x USB2.0 HOST，1x USB3.0 Type-C|
|RTC | Support RTC, on-board battery backup interface |
|Debug UART | 3pins Debug UART |
|GPIO | GPIO1 40 pins,<br> 1 x I2S,<br> 2 x I2C,<br> 1 x SPI/UART,<br> 8 x GPIO,<br> GPIO2 24pin PCIE port|
|Buttons | Upgrade button & Reset button|
|Power Source | DC 5V/3A,<br> TYPE-C 5V/3A|
|LED | Power led & Status led|
|PCB | 8 Layer|
|Dimension| 91mm*56mm |


<!--  OEM data (must be coordinated/configrmed with Orange Pi)-->
## Product's Life Cycle

| Parameter | Status  |
|:--:|:--:|
| Production status: | In Production |
| Expected EOL: | Not available |
| Mainline Support:| Partial |

<!-- OS Support with links to the download page if possible -->
## Supported Operating Systems: 

- [Armbian](https://www.armbian.com/orange-pi-4/) linux, different Debian or Ubuntu flavours to pick, active develpment
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