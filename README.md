## Custom Recovery | Device Tree
[Red Magic 7s Pro]
| Device                  | Red Magic 7s Pro                                          |
| ----------------------- | ---------------------------------------------------------|
| SoC                     | Qualcomm SM8450 Snapdragon 8+ Gen 1 (4 nm)                      |      
| CPU                     | Octa-core (1x3.00 GHz Cortex-X2 & 3x2.50 GHz Cortex-A710 & 4x1.80 GHz Cortex-A510)  |
| GPU                     | Adreno 730                                             |
| Internal                | 256GB 12GB RAM, 512GB 16GB RAM, UFS 3.1                 |
| Model                   | NX709S |
| Codename                | NX709S (...official codename.) |

### Release Notes
* TWRP now boots, decryption is working fine but aren't tested in GSI.
* It was tested in a device running RMOS 6.0 (NX709S) firmware, but it should work in RMOS 5.5 too.
* Do not flash OTA firmware yet, it is not well-tested, could brick your device.
* Red Magic 7s Pro is Virtual A/B with dedicated Recovery Partition, no need to `boot` it like other A/Bs, just `flash` it.

### Working Features
* Internal Storage
* FastbootD
* ADB Commands and Terminal
* Flashing .zip files like magisk and recovery.
* Flashing non-logical .img files.
* ADB Sideload
* MTP

### Issues and Bugs
* External Storage (...tester don't own OTG, can't check.)
* Flashing OTA.
* Backup/Restore (...backup actually works, but restoring it not yet tested.)
* Vibration/Haptics

### Credits
```
# Copyright (C) 2023 The Android Open Source Project
# Copyright (C) 2023 SebaUbuntu's TWRP device tree generator
# SPDX-License-Identifier: Apache-2.0
```
