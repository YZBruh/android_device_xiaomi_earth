# TWRP Device Tree for Xiaomi Redmi 12C (earth)
===========================================

The Redmi 12C is a budget range smartphone from Redmi, Released 2022, December 31
This project is licensed under the terms of the Boost Software License

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
OS        | Android 12, MIUI 13        
CPU     | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
Chipset | MediaTek Helio G88 (12nm)
GPU     | Mali-G52 MC2
Memory  | 4GB/6GB RAM
Storage | 64GB/128GB
MicroSD | microSDXC (dedicated slot)
Battery | Non-removable Li-Ion 5000 mAh battery
Resolution | 1080 x 2400 pixels, 20:9 ratio (~405 ppi density)
Camera (Rear)  | 50 MP, f/1.8, (wide) / 0.8 MP, f/2.4 (depth)
Rear Camera Features | LED flash, HDR, panorama
Video        | 1080p@30fps        
Camera (Front)  | 8 MP, f/2.0, (wide)
Features| Fingerprint (in the back), accelerometer, proximity, compass

## Situation
- [X] Correct screen/recovery size
- [ ] Working Touch, screen
- [X] Backup to internal/microSD
- [X] Restore from internal/microSD
- [X] reboot to system
- [X] ADB

Medium checks
- [X] update.zip sideload
- [X] UI colors (red/blue inversions)
- [X] Screen goes off and on
- [X] F2FS/EXT4 Support, exFAT/NTFS where supported
- [X] all important partitions listed in mount/backup lists
- [X] backup/restore to/from external (USB-OTG) storage
- [X] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [X] decrypt /data
- [X] Correct date

Minor checks
- [X] MTP export
- [X] reboot to bootloader
- [X] reboot to recovery
- [X] poweroff
- [X] battery level
- [X] temperature
- [X] encrypted backups
- [ ] input devices via USB (USB-OTG) - keyboard, mouse and disks (not supported by the device)
- [ ] USB mass storage export
- [X] set brightness
- [X] vibrate
- [X] screenshot
- [ ] partition SD card

## Device picture

![Redmi 12C](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-12c-1.jpg "Redmi 12C")
