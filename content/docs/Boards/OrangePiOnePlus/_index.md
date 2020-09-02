---
weight: 5
title: "Orange Pi One Plus"
---

<!-- Board Official Name -->
# Orange Pi One Plus

<!-- Image, prefer raw ones with no comments or marks -->

![Orange Pi One Plus](/images/opi1plus.jpg "Orange Pi One Plus")



<!-- Hardware description, taken from the OPI product page-->
## Hardware Specification
|Feature|Description|
|:--:|:-- |
|CPU | H6 Quad-core 64-bit 1.8GHZ ARM Cortex™-A53 |
|GPU | Mali-T720 GPU, OpenGL ES1.1/2.0/3.0/3.1, DX11, Supports ASTC(Adaptive Scalable Texture Compression)|
|Memory| 1GB LPDDR3 |
| Storage | MicroSD slot for up to 32GB  |
|Networking | Ethernet: Realtek RTL8211E 10/100/1000Mbps|
|Audio | Output: HDMI2.0a,<br> Input: MIC|
|Video Outputs | HDMI 2.0a and CVBS|
|USB | 1x USB 2.0 Host, 1x USB OTG 2.0 |
|Debug UART | 3pins Debug UART |
|GPIO | GPIO 26 pins|
|Buttons | Power(K1)|
|Power Source | DC input，MicroUSB (OTG)|
|LED | Power LED, Status LED |
|PCB | 8 Layer|
|Dimension| 68mm*48mm |


<!--  OEM data (must be coordinated/configrmed with Orange Pi)-->
## Product's Life Cycle

| Parameter | Status  |
|:--:|:--:|
| Production status: | In Production |
| Expected EOL: | Not available |
| Mainline Support:| Partial |

<!-- OS Support with links to the download page if possible -->
## Supported Operating Systems: 

- [Armbian](https://www.armbian.com/orange-pi-one-plus/) linux, different Debian or Ubuntu flavours to pick, active develpment
- [Android](#)


Support Matrix: 

| Project |  Upstream Support | Downstream Support | Not Supported | 
|:--:|:--:|:--:|:--:|
| Linux Kernel | Yes | Yes | | 
|U-Boot| Yes | Yes||
| Yocto| | | X |
|Buildroot| Yes | | |

Defconfigs: 
    
Linux defconfig: 
U-Boot defconfig: 

<!-- Specific Library support (always with the link to the lib code) -->
## Sofware library support and variants
- [Opi_GPIO](https://github.com/user_/lib_)