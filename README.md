# HP OMEN 15-ek0066TX OpenCore EFI
---
## **Warning!**
- **이 EFI는 한국 내수용 HP OME 15-ek0066TX에 맞춰 제작되었습니다. 타 국가 발매판에 대하여 정상작동을 보증하지 않습니다.**

- **This EFI optimized for HP OMEN 15-ek0066TX released in KOREA. Not guaranteed for releases in other countries.**

- **이 파일을 사용하여 발생하는 피해는 보증하지 않습니다.** 
- **Damage caused by the use of this file is not guaranteed.**
---
### Specs:
> HP OMEN 15-ek0066TX:
```mdblock
Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz (12 CPUs)
SAMSUNG SODIMM 3200MHz 16GB
KIOXIA NVME SSD 512GB
Main Display: IPS FHD 144Hz
Intel(R) UHD Graphics
NVIDIA GeForce RTX 2060 with GDDR6 6GB
```
---
### Works:
- [x] Booting
- [x] 144hz-display
- [x] Intel UHD 630 Graphics 
- [x] Keyboard
- [x] Trackpad
- [x] USB3.0 / 2.0 /Thunderbolt
- [x] Wifi + Bluetooth
- [x] LAN Adapter
- [x] Battery & Power management
- [x] Webcam
- [x] Audio (3.5 Jack & USB-C Both Support)
- [x] Sleep

---
### Fixed:
- [x] USB Mapping Error with Big Sur 11.4

---
### Issue:
- Slow booting speed, You need waiting for almost 5min in Black screen.
- Microphone
- Can't Use RTX2060 Graphics card. (NVIDIA Webdriver Not supported)
- SDCard Slot
- HDMI & Mini Display Port

---
### Not Tested:

---
### Requirements
- Opencore Pkg 0.7.2
- Propertree for edit config.plist
- Over 8GB USB for initial booting

---
### Include KEXTS Infomation
```mdblock
AirportItlwm.kext
AppleALC.kext
CPUFriend.kext
CPUFriendDataProvider.kext
CpuTscSync.kext
ECEnabler.kext
IntelBluetoothFirmware.kext
IntelBluetoothInjector.kext
Lilu.kext
NoTouchID.kext
NVMeFix.kext
RealtekRTL8111.kext
SMCBatteryManager.kext
SMCDellSensors.kext
SMCLightSensor.kext
SMCProcessor.kext
SMCSuperIO.kext
USBMap.kext
VirtualSMC.kext
VoodooI2C.kext
VoodooI2CHID.kext
VoodooPS2Controller.kext
WhateverGreen.kext
XHCI-unsupported.kext
```
---
### Post-install & Tools
- **You must generate your own serial number with GenSMBIOS for using facetime & imessages** (https://github.com/corpnewt/GenSMBIOS)
- You can edit serial number & config.plist with Propertree (https://github.com/corpnewt/ProperTree)
---
### Credits
- dortania's Opencore Guide (https://dortania.github.io/)
- x86.co.kr (https://x86.co.kr/)
