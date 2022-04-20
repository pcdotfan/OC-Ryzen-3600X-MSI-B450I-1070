# [OpenCore](https://github.com/acidanthera/OpenCorePkg) configuration for Ryzen 3600X &amp; MSI B450I Gaming Plus AC

## Builds

| Type                   | Name                                  |
| ---------------------- | ------------------------------------- |
| CPU                    | Ryzen 3600X                           |
| MB                     | MSI B450I Gaming Plus AC              |
| Audio                  | ALC887                                |
| GPU                    | Nvidia 1070  |
| RAM                    | 32G DDR4 (16G * 2)                     |
| Wireless   | RTL8111                               |
| macOS                  | High Sierra (17G14033)                    |

## Read Me First

- If your cpu don't have 6 cores, you must change patch values
  of `algrey - Force cpuid_cores_per_package` to boot your system.
  See [AMD_Vanilla ReadMe](https://github.com/AMD-OSX/AMD_Vanilla#read-me-first) for details.

## Features

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] Power Management by [SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alcid=1)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen), [Nvidia Webdrivers](https://www.tonymacx86.com/nvidia-drivers/)
- [ ] Bluetooth (not tested yet)
- [ ] iMessage / FaceTime / Airdrop / Handoff (not tested yet)

## Issues

Not fully tested, use it with care.
