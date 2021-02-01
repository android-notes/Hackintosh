# OpenCore Hackintosh
![](https://github.com/android-notes/Hackintosh/blob/main/image/1.png?raw=true)

MacOS version: 10.15.7 (19H15)
OpenCore: 0.6.5

## Hardware
* CPU: i9-10850k
* dGPU: GTX 760
* iGPU: Intel UHD Graphics 630
* Mainboard: Gigabyte Z490 Gaming X
  * Ethernet: Intel I219V11 
  * Audio: ALC1200(but Hackintool show ALCS1200A), need fake id

* Wifi/BT: fenvi T919
* SSD: Gigabyte Gen4 1T
* Memory: Kingston HyperX 3200 16Gx2

## BIOS
#### Disable:
* Fast Boot
* Secure Boot
* Serial Port
* VT-d 
* CSM
* Intel Software Guard Extensions(SGX)
* Intel Platform Trust
* CFG Lock 

#### Enable:
* Above 4G decoding
* Hyper-Threading
* EHCI/XHCI Hand-off
* OS type: Windows 8.1/10 UEFI Mode
* Internal Graphics: Enable(auto casue  Hardware Acceleration failed)
* DVMT Pre-Allocated(iGPU Memory): 64MB
* SATA Mode: AHCI

bios version F5, x.m.p is not necessary
![bios](https://github.com/android-notes/Hackintosh/blob/main/image/4.png?raw=true)


## Working
* iGPU Hardware Acceleration
* Wifi and Bluetooth 
* Audio 
* Sleep/Wake
* Shutdown
* Restart
* Magic Trackpad 1
* AirDrop
* AppleID/iCloud/AppleStore
* Multiboot

## Note
Generate your own SystemSerialNumber/MLB/SystemUUID [Config.plist](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#platforminfo)

![Hardware Acceleration](https://github.com/android-notes/Hackintosh/blob/main/image/2.png?raw=true)

![muitiboot](https://github.com/android-notes/Hackintosh/blob/main/image/3.jpeg?raw=true)
