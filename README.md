## ThinkCentre-M930q Hackintosh OpenCore EFI

![image](Screenshot/m930q.png)

### [简体中文](README.zh_CN.md)


### OpenCore

[OpenCore 0.9.0](https://github.com/acidanthera/OpenCorePkg)


### Spec

- Chipset: Q470
- CPU: Intel 10th i3-10105
- Memo: Samsung 32GB(2x16GB) DDR4 2666 Mhz
- iGPU: Intel UHD Graphic 630
- HDA: Realtek ALC233
- SSD: WD SN750 512G
- LAN: Realtek RTL8111HSD
- WLAN: BCM94360CS2


### BIOS

```
Devices
  |-- Serial Port Setup
    |-- Serial Port1 Address: Disabled
  |-- ATA Drive Setup
    |-- Configure STAT as: ACHI
  |-- Video Setup
    |-- Select Active Video: IGD
    |-- Pre-Allocated Memory Size: 64MB
    |-- Total Graphics Memory: Maximum

Advanced
  |-- CPU Setup
    |-- Intel(R) Hyper-Threading Technology: Enabled
    |-- Core Multi-Processing: Enabled
    |-- Intel(R) Virtualization Technology: Enabled
    |-- VT-d Feature: Disabled

Security
  |-- Secure Boot
    |-- Secure Boot: Disabled

Startup
  |-- Fast Boot: Disabled
```


### Screenshot

![macOS Ventura](Screenshot/about.png)

![Info](Screenshot/info.png)

![Geekbench 5](Screenshot/geekbench5.png)


### Kexts

- [Lilu.kext 1.6.4](https://github.com/acidanthera/Lilu)
- [SMCProcessor.kext 1.3.1](https://github.com/acidanthera/VirtualSMC)
- [SMCSuperIO.kext 1.3.1](https://github.com/acidanthera/VirtualSMC)
- [VirtualSMC.kext 1.3.1](https://github.com/acidanthera/VirtualSMC)
- [WhateverGreen.kext 1.6.4](https://github.com/acidanthera/WhateverGreen)
- [AppleALC.kext 1.8.0](https://github.com/acidanthera/AppleALC)
- [IntelMausi.kext 1.0.7](https://github.com/acidanthera/IntelMausi)


### Tools

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA OCC.
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) Generate SMBIOS.
- [MountEFI](https://github.com/corpnewt/MountEFI) Mount EFI partition.
- [EFI Agent](https://github.com/headkaze/EFI-Agent) Better EFI partition mount App.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.
