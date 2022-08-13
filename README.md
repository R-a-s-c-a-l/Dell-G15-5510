# Dell G15 5510

|            |                                                           |
| --------   | --------------------------------------------------------- |
| Model      | Dell G15 5510                                             |
| CPU        | Intel(R) Core(TM) i7-10870H                               |
| GPU        | Intel(R) UHD Graphics 630                                 |                                                                     
| Disk       | Unknown                                                   |
| Ethernet   | Realtek RTL8111                                           |
| Bootloader | OpenCore 0.8.3 Release                                    |
| Supported macOS Version | macOS BigSur & Monterey                      |

# 状态
## 正常
 - 键盘、触摸板 (GPIO中断、支持手势)
 - 雷雳、 USB部分正常、PCIe隧道无设备测试、视频输出直通独显无解
 - HDMI、直通独显无解
 - Wi-Fi 蓝牙 (驱动自行添加)
 - 声卡 (Intel SST 内置麦克风无法驱动、耳机需要ALCFixPlug,否则无法使用->[点我下载](https://github.com/Core-i99/DELL-G15-5510-ALCPlugFix))
 - 亮度 
 - 快捷键(部分)
 - 电池
 - 睡眠
 - USB
## 不正常
 - 帮别人做, 没详细测试, 有问题请提交issues
 ## 鸣谢
- [VoodooI2C](https://github.com/VoodooI2C) 提供 [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- [Core-i99](https://github.com/Core-i99) 提供 [DELL-G15-5510-ALCPlugFix](https://github.com/Core-i99/DELL-G15-5510-ALCPlugFix)
- [zhen-zen](https://github.com/zhen-zen) 提供 [ThermalSolution](https://github.com/zhen-zen/ThermalSolution).
- [1Revenger1](https://github.com/1Revenger1) 提供 [ECEnabler](https://github.com/1Revenger1/ECEnabler).
- [Acidanthera](https://github.com/acidanthera) 提供 [AppleALC](https://github.com/acidanthera/AppleALC), [BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM), [Lilu](https://github.com/acidanthera/Lilu), [OcBinaryData](https://github.com/acidanthera/OcBinaryData), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg) [VoodooInput](https://github.com/acidanthera/VoodooInput), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [BrightnessKeys](https://github.com/acidanthera/BrightnessKeys) ,[WhateverGreen](https://github.com/acidanthera/WhateverGreen), [CpuTscSync](https://github.com/acidanthera/CpuTscSync),
