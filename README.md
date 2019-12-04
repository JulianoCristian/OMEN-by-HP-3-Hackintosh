# OMEN by HP Laptop 15-ce0xx

### 😥此EFI可能存在某些问题，谨慎使用


### 配置

| 产品名称暗影精灵3 | OMEN by HP Laptop 15-ce0xx                |
| ----------------- | ----------------------------------------- |
| BIOS              | F.17                          |
| 处理器            | Intel(R) Core(TM) i7-7300HQ CPU  |
| 独立显卡           | NVIDIA GeForce GTX 1050ti                 |
| 显卡              | Intel(R) HD Graphics 630                  |
| 声卡              | ALC295                    |
| 硬盘              | 970EVO 256G、HGST 1T      |

### 已经正常的以及一些说明

- 声卡驱动正常，没发现破音
- 配置页面显示正常
- 所有功能正常使用，无报错，包括APP Store、Facetime、iTunes等
- 电池正常
- 休眠正常
- 蓝牙以及无线更换了BCM94360CS2
- 机器上~~所有接口~~均正常，已修复Type-c
- 有线网卡正常，无线网卡无解
- 原生电源驱动正常，电池显示打了补丁 
- USB已经定制热补丁没有定义接口

### 无效功能

- 小太阳(亮度调节)正常 但是是使用USB键盘接入 去把F14\F15快捷键设置成F1\F2的
- ~~type-c输出dp用不了~~（唯一一个挂在核显输出dp的）
- 独显是没法驱动的，这个大家都知道！
- 由于独显没法驱动，所以HDMI、miniDP 无法使用！
- 触摸板为PS2我修复无法完美 （使用ApplePS2SmartTouchPad可以使用3指貌似，如有需求请自行替换）
- 其它问题暂时没发现，或者没注意到，毕竟每个人的使用程度不一样，我的要求就是能简单的娱乐办公就行了！

### 一些参考教程

【黑果小兵】macOS Catalina 10.15.1 19B88 正式版 with Clover 5098原版镜像[双EFI双平台版 ](https://blog.daliansky.net/macOS-Catalina-10.15.1-19B88-Release-version-with-Clover-5098-original-image-Double-EFI-Version.html)

远景论坛[修改dsdt实现电量显示方法（整理修改已有帖子）](http://bbs.pcbeta.com/viewthread-1778499-1-1.html)

tonymacx86[HP OMEN 15-dc电池错误](https://www.tonymacx86.com/threads/solved-hp-omen-15-dc-battery-error.263814/#post-1841023)

[[指南]如何修补DSDT的工作电池状态](https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/)

### 安装完之后可以干些什么？

我也不知道我只是日常使用

### 致谢

- 感谢 [Acidanthera](https://github.com/acidanthera) 提供 [AppleALC](https://github.com/acidanthera/AppleALC)，[HibernationFixup](https://github.com/acidanthera/HibernationFixup)，[Lilu](https://github.com/acidanthera/Lilu)，[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)，[VirtualSMC](https://github.com/acidanthera/VirtualSMC)，[VoodooPS2](https://github.com/acidanthera/VoodooPS2) 和 [WhateverGreen](https://github.com/acidanthera/WhateverGreen)。
- 感谢 [apianti](https://sourceforge.net/u/apianti)，[blackosx](https://sourceforge.net/u/blackosx)，[blusseau](https://sourceforge.net/u/blusseau)，[dmazar](https://sourceforge.net/u/dmazar) 和 [slice2009](https://sourceforge.net/u/slice2009) 提供 [Clover](https://sourceforge.net/projects/cloverefiboot)。
- 感谢 [RehabMan](https://github.com/RehabMan) 提供 [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander)，[OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config)，[OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet)，[OS-X-USB-Inject-All](https://github.com/RehabMan/OS-X-USB-Inject-All) 和 [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext)。
- 感谢远景论坛的各位大佬提供的教程，以及[黑果小兵](https://github.com/daliansky)的镜像。
- 感谢Catalina黑苹果交流II群的群友 h81 4170 指出视频接口修复方法
- 感谢远景黑苹果触摸设备交流群的群友 Leo null 点醒修复硬件解码问题

### 常见问题

**Q:如何进入BIOS或者设置启动项？**

A:开机后按下ESC键，然后根据指引选择

**Q:为什么在你的电脑上可以，而我的电脑上不行呢？**

A:我也不知道，您可以尝试问一下你的电脑:为什么你不行？

**Q:为什么这么费电？**

A:Google搜索:如何禁用独立显卡以节省电量

**Q:为什么没有HiDPI？**

A:我并不能解决所有的问题，如果您能向我提供帮助，那么太感激您了！

联系方式：Hatsune._Miku@outlook.com
