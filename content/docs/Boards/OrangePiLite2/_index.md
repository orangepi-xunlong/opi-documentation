---
bookCollapseSection: true
weight: 6
title: "Orange Pi Lite2"
---

<!-- Board Official Name -->
# Orange Pi Lite2

<!-- Image, prefer raw ones with no comments or marks -->

![Orange Pi Lite2](/images/opilite2.jpg "Orange Pi Lite2")



<!-- Hardware description, taken from the OPI product page-->
## Hardware Specification
|Feature|Description|
|:--:|:-- |
|CPU | H6 Quad-core 64-bit 1.8GHZ ARM Cortex™-A53 |
|GPU | Mali-T720 GPU, OpenGL ES1.1/2.0/3.0/3.1, DX11, Supports ASTC(Adaptive Scalable Texture Compression)|
|Memory| 1GB LPDDR3 |
| Storage | MicroSD slot for up to 32GB  |
|Networking | AP6255, IEEE 802.11 AC/bb/g/n, BT4.1|
|Audio | Output: HDMI2.0a,<br> Input: MIC|
|Video Outputs | HDMI 2.0a and CVBS|
|Camera|A CSI input connector Camera, Support 8 bit digital camera interface|
|USB | 1x USB 3.0 Host, 1x USB 2.0 Host, 1x USB OTG 2.0 |
|Debug UART | 3pins Debug UART |
|GPIO | GPIO 26 pins|
|Buttons | Power(K1)|
|Power Source | DC input，MicroUSB (OTG)|
|LED | Power LED, Status LED |
|PCB | 8 Layer|
|Dimension| 69mm*48mm |


<!--  OEM data (must be coordinated/configrmed with Orange Pi)-->
## Product's Life Cycle

| Parameter | Status  |
|:--:|:--:|
| Production status: | In Production |
| Expected EOL: | Not available |
| Mainline Support:| Partial |

<!-- OS Support with links to the download page if possible -->
## Supported Operating Systems: 

- [Armbian](https://www.armbian.com/orange-pi-lite-2/) linux, different Debian or Ubuntu flavours to pick, active develpment
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
