# OpenCore Hackintosh

MacOS version: 12.4 (21F79)
OpenCore: 0.8.0

## 硬件
* CPU: i9-10850k
* 独显: Asus Dual RX6600 8G
* 核显: Intel UHD Graphics 630
* 主板: Gigabyte Z490 Gaming X
  * 有线网: Intel I219V（免驱）
  * 声卡: ALC1200
* Wifi/蓝牙: fenvi T919
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
* Re-Rize Bar Support

#### Enable:
* Above 4G decoding
* Hyper-Threading
* EHCI/XHCI Hand-off
* OS type: Windows 10
* Internal Graphics: Enable(auto casue  Hardware Acceleration failed)
* DVMT Pre-Allocated(iGPU Memory): 64MB
* SATA Mode: AHCI

bios version F21, x.m.p非必须


## Working
* iGPU Hardware Acceleration
* Wifi and Bluetooth 
* Audio 
* Shutdown
* Restart
* Sleep
* Magic Trackpad 1
* AirDrop
* AppleID/iCloud/AppleStore

## Note
Generate your own SystemSerialNumber/MLB/SystemUUID 
