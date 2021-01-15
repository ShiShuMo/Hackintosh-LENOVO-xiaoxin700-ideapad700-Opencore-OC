## Hackintosh-LENOVO-xiaoxin700-ideapad700-Opencore-OC

- 联想小新 700 （i5-6300HQ）黑苹果 Opencore 引导，使用 Opencore 0.6.6 Mod 开发版，支持 10.15和Big Sur最新版全新安装以及 无损 OTA 升级，几乎完美，加入了最新的 intel 网卡驱动，默认使用 airportitlwm.kext(BigSur版)，本人使用BigSur 11.1版本，具体如何使用请参考互联网。

- 增加另外三个配置文件如下：
  config(brcm_appleps2)：使用博通网卡及蓝牙驱动，使用ApplePS2SmartTouchPad键盘及触摸板驱动。
  config(brcm_voodps2)：用博通网卡及蓝牙驱动，使用VoodooPS2Controller键盘及触摸板驱动，具有原生按键调节亮度功能。
  config(intel_appleps2)：使用intel网卡及蓝牙驱动，使用ApplePS2SmartTouchPad键盘及触摸板驱动。
  默认配置为使用intel网卡及蓝牙驱动，使用VoodooPS2Controller键盘及触摸板驱动，具有原生按键调节亮度功能。
  
## 电脑配置

| 规格     | 详细信息                                     |
| -------- | ---------------------------------------- |
| 电脑型号 | 联想小新 700笔记本电脑 15.6''(HD530/GTX950M)             |
| 处理器   | 英特尔 酷睿 i5-6300HQ/i7-6700HQ 处理器             |
| 内存     | 8GB/16GB 三星 DDR4 2133MHz                 |
| 硬盘     | 西数 NVMe固态硬盘 SN550 1T                  |
| 集成显卡 | 英特尔 HD 图形530                            |
| 显示器   | 京东方 FHD 1920x1080 (15.6 英寸) |
| 声卡     | 瑞昱 ALC235 (节点:18/33)                     |
| 网卡     | 英特尔 无线 AX200 (原装 英特尔 无线 AC3165)       |
| 读卡器   | 通用集成 USB3.0 读卡器                      |

## 目前情况

- 音量按键调节正常。
- 亮度按键小太阳正常。
- 键盘、触控板驱动正常。
- -唤醒睡眠 ok 鼠标键盘唤醒。
- USB定制 ok 鼠标键盘接口内建。
- 显卡硬解 ok。
- 变频(i5-6300HQ）ssdt定制(0.6GHZ~3.1GHZ) ok 声卡 ok 自动切换音响耳机。
- 机型 macbookpro 13,3 (2016)。
- 电源 4项。
- 暂未发现其他 Bugs,欢迎提交 issues。

## 鸣谢

- 感谢 [Acidanthera](https://github.com/acidanthera) 提供 [AppleALC](https://github.com/acidanthera/AppleALC)，[HibernationFixup](https://github.com/acidanthera/HibernationFixup)，[Lilu](https://github.com/acidanthera/Lilu)，[NVMeFix](https://github.com/acidanthera/NVMeFix)，[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)，[VirtualSMC](https://github.com/acidanthera/VirtualSMC)，[VoodooPS2](https://github.com/acidanthera/VoodooPS2) 和 [WhateverGreen](https://github.com/acidanthera/WhateverGreen)，[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup)，[BrcmBluetoothInjector](https://github.com/acidanthera/BrcmBluetoothInjector)，[BrightnessKeys](https://github.com/acidanthera/BrightnessKeys)，[CPUFriend](https://github.com/acidanthera/CPUFriend)，[RTCMemoryFixup](https://github.com/acidanthera/RTCMemoryFixup)。
- 感谢 [daliansky](https://github.com/daliansky) 提供 [OC-little](https://github.com/daliansky/OC-little)。
- 感谢 [OpenIntelWireless](https://github.com/OpenIntelWireless) 提供 [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)，[AirportItlwm](https://github.com/OpenIntelWireless/itlwm)。
- 感谢 [Mieze](https://github.com/Mieze) 提供 [RTL8111_driver_for_OS_X](https://github.com/Mieze/RTL8111_driver_for_OS_X)。
- 感谢互联网Hackintosh大佬提供一系列补丁文件。