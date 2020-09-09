---
bookCollapseSection: true
weight: 1
title: "Orange Pi I96"
---
<!-- Board Official Name -->
# Orange Pi I96

<!-- Image, prefer raw ones with no comments or marks -->

![Orange Pi I96](/images/opi-i96.png "Orange Pi I96")



<!-- Hardware description, taken from the OPI product page-->
## Hardware Specification
|Feature|Description|
|:--:|:-- |
|CPU | RDA8810PL ARM Cortex-A5 32bit |
|GPU | Vivante GC860 3D GPU|
|Memory| Integrated 256MB LPDDR2 SDRAM |
| Storage |TFcard/Integrated 500MB 8Bit 1.8V 4K SLC NandFlash|
|Networking | Onboard WIFI+BT (RDA5991)|
|Audio | No Video In/Output|
|Video Outputs | No Video In/Output |
|Camera | MIPI CSI-2 for up to 2 Megapixel |
|USB | 1x USB 2.0 Host, 1xUSB OTG ( MicroUSB)|
|RTC | No onboard RTC support |
|Debug UART | 3pins Debug UART |
|GPIO | 40 Pin 1.8V female GPIO connector |
|Buttons/Header | Power Button/Boot Switch Header|
|Power Source | Micro USB 5V@2A,Battery|
|LED | Power led & Status led|
|Dimension| 60mm*30mm |


<!--  OEM data (must be coordinated/configrmed with Orange Pi)-->
## Product's Life Cycle

| Parameter | Status  |
|:--:|:--:|
| Production status: | Not available|
| Expected EOL: | SOC is EOL,Not recommended for new Designs|
| Mainline Support:| Partial |

<!-- OS Support with links to the download page if possible -->
## Supported Operating Systems: 

- [Debian](#)
- [Android](#)


Support Matrix: 

| Project |  Upstream Support | Downstream Support | Not Supported | 
|:--:|:--:|:--:|:--:|
| Linux Kernel | Yes | Yes | | 
|U-Boot| No | Yes||
| Yocto| | | X |
|Buildroot| | x ||

Defconfigs: 
    
Linux defconfig:  ``` armv7_defconfig```

Linux Decice Tree: ``` rda8810pl-orangepi-i96.dts ```

U-Boot defconfig: ``` rda8810_config ```


<!-- Specific Library support (always with the link to the lib code) -->
## Sofware library support and variants
- [Opi_GPIO](https://github.com/user_/lib_)