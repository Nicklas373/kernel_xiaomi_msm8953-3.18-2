# Clarity Kernel for Xiaomi Redmi Note 4x (msm8953) source

Clarity is an EAS based kernel that have aim to get fully balanced with battery and performance usage without need any configuration to use. 
and also, always up-to-date with CAF, AOSP/Common, F2FS & EXFAT, designed for flash & forget kernel :3.

<p align="center">
  <img width="800" height="400" src="https://raw.githubusercontent.com/Nicklas373/kernel_xiaomi_msm8953-3.18-2/readme/background.png"><br>
</p>

## Branches Information
```
master : Current source branch that used for all branch on this kernel, it's based on LA.UM.8.6.r1-01900-89xx.0
	 and cloned directly from https://source.codeaurora.org/quic/la/kernel/msm-3.18/tag/?h=LA.UM.8.6.r1-01900-89xx.0

pie : Current stable hmp branch, this branch is stock based kernel with always up-to-date from caf, aosp/common
      , exfat, f2fs and keep it up with no mods or customizations. Only include several optimization to make it stable,
      because it's designed to keep stock and use as base kernel (Based on LA.UM.8.6.r1-02900-89xx.0).

dev/kasumi : Current clarity kernel branch, with eas merged and other kernel features that already detail on xda thread
             (This is almost force push build, but not always push on xda or telegram due private build).

dev/kasumi-uc : Current clarity kernel branch, with underclocked cpu not gpu, however this branch is rare to update and
                still on testing phase.
```

## About device
![Redmi Note 4](http://i01.appmifile.com/webfile/globalimg/7/537557F3-A4F1-2490-E9D3-138B2A11DBF6.png "Redmi Note 4")

##### Redmi Note 4x
| Feature                 | Specification                     |
| :---------------------- | :-------------------------------- |
| CPU                     | Octa-core 2.0 GHz Cortex-A53      |
| Chipset                 | Qualcomm MSM8953 Snapdragon 625   |
| GPU                     | Adreno 506                        |
| Memory                  | 2/3/4 GB                          |
| Shipped Android Version | 6.0.1                             |
| Storage                 | 32/64 GB                          |
| MicroSD                 | Up to 256 GB                      |
| Battery                 | 4100 mAh (non-removable)          |
| Dimensions              | 151 x 76 x 8.5 mm                 |
| Display                 | 1920x1080 pixels, 5.5 (~401 PPI)  |
| Rear Camera             | 13 MP, LED flash                  |
| Front Camera            | 5 MP                              |
| Release Date            | January 2017                      |

## Features
Based on Clarity Kernel r15 build 20191220
- Based on CAF Kernel Tag 'LA.UM.8.6.r1-02900-89xx.0'
- Up-to-date for aosp common kernel 3.18 (https://https://source.codeaurora.org/quic/la/kernel/msm-3.18)
- Up-to-date for f2fs stable branch (https://github.com/jaegeuk/f2fs-stable)
- Up-to-date for exfat stable branch (https://github.com/arter97/exfat-linux)
- Compiled using Clang 10.0.0 NusantaraClang (Compat VDSO)
- Merge EAS Based on (https://github.com/EAS-Project/msm-3.18)
- Merge PELT Halflife 16ms for EAS
- Energy Model Management Framework for legacy support
- Schedutil & Pwrutilx CPU Governor
- CPUSets & Stune Assist (EAS Assist Management)
- 100Hz timer tick rate frequency
- Upstreamed CFQ and BFQ I/O Schedulers
- Audio Optimizations (UHQA, Slimbus OC, etc)
- Updated LZO/LZ4 Compressor/Decompressor Module
- Optimized CPU Boost for EAS (Dynamic Stune Boost v3)
- Upstreamed ZRAM,ZSMALLOC & ZCACHE
- Improved Power Efficient Workqueue
- Cortex a53 Optimizations
- USB Fastcharge
- Backlight Dimmer
- Klapse
- And any other improvement or feature that i forget to tell '_' (Check git for more details)

## Download build
[![Download Clarity Kernel](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/clarity-kernel/files/Mido/r16/)

## XDA Support
[XDA-Thread](https://forum.xda-developers.com/redmi-note-4/xiaomi-redmi-note-4-snapdragon-roms-kernels-recoveries--other-development/kernel-clarity-kernel-t3992235)

## Telegram Channel
[Telegram](https://t.me/clarityci)

# HANA-CI Build Project || 2016-2020
