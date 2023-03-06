
![AboutmyMAC](https://user-images.githubusercontent.com/73241309/223200474-f027d2f8-a6a7-4ed1-a5a4-4fd2f9893b48.PNG)


# 1. Table of content
- [1. Table of content](#1-table-of-content)
- [2. What is this for?](#2-what-is-this-for)
- [3. Hardware](#3-hardware)
- [4. What is working?](#4-what-is-working)
- [5. How to use it?](#5-how-to-use-it)
- [6. Support / Feedback](#6-support--feedback)
- [7. How to contribute?](#7-how-to-contribute)
- [8. Sponsor me!](#8-how-to-sponsor)

# 2. What is this for?
Hackintosh (openCore) Computer with both Windows and macOS on two seperate disks.


# 3. Hardware
- ASUS ROG MAXIMUS Z690 HERO
- Intel i9 13900k
- 2 x 32GB DDR5-5600 Kingston Fury
- 2 x NVMe Samsung EVO970 2TB
- Sapphire Nitro+ RX 6900 XT
- Artic Liquid Freezer 280
- Fenvi T919 WiFI & BLE

# 4. What is working?

# Working
- [x] **Tested with macOS Ventura 13.2.1
- [x] **Wifi and Bluetooth** (via BCM94360CD using a MQUPIN fenvi T919 Wireless Card)
- [x] **Audio**: Realtek ALC1220-VB (AppleALC.kext, layout-id=7,FakeID.kext, FakePCIID_Intel_HDMI_Audio.kext)
- [x] **USB**, all ports.
- [x] **Thunderbolt 4** including Hot-plug
- [x] **2.5Gbit Ethernet (Intel I225-V)**
- [x] **With iMacPro1,1: Amazon Prime Video and Netflix in Safari. AppleTV.** 
- [x] **Sleep/Wake**
- [x] **Shutdown**
- [x] **Restart**


# 5. How to use it?

1. Create an MacOS Ventura 13.2.1 USB-Installer Stick 
2. Mount the EFI-partition of the "Install macOS Ventura" disk (use Hackintool)
3. Delete all folders and copy my entira EFI folder to the root of the EFI-partition
4. Generate new Serial Numbers https://www.tonymacx86.com/threads/an-idiots-guide-to-imessage.196827/
5. Insert new Serial Numbers to PlattformInfo/Generic (MLB,SystemSerialNumber,SystemUUID) and save
6. Boot from USB Installer and install macOS
7. After installation in macOS copy EFI Partition from USB Installer to EFI Partition of the System Drive
8. Have fun



# 6. Support / Feedback
Any bugs? Feature request? Message me [here](https://github.com/bangertech) or click on the "Issues" tab here on the GitHub repository!

# 7. How to contribute?

Fork the repository and create PR's.

# 8. How to sponsor?


<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FD26FHKRWS3US" target="_blank"><img src="https://pics.paypal.com/00/s/N2EwMzk4NzUtOTQ4Yy00Yjc4LWIwYmUtMTA3MWExNWIzYzMz/file.PNG" alt="SUPPORT" height="51"></a>


