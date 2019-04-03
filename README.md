# ThinkPadT570_HackIntoSh_Clover
本引导根据网络及爱好者指引配置，只在本机测试使用，未在其他机型测试，使用需谨慎

电脑配置信息

处理器	
CPU系列第七代智能英特尔酷睿i5 CPU型号i5-7200U CPU主频2.5GHz 最高睿频3.1GHz 核心架构Kaby Lake

存储设备 内存容量8GB  硬盘容量1TB(SATA HDD) + 128GB(M.2 SSD)

屏幕分辨率1920x1080

显卡	
显卡类型双显卡(独立显卡 + 集成显卡)

显卡芯片NVIDIA GeForce 940MX + Intel HD Graphics 620 显存容量2G

多媒体	
摄像头720p HD 摄像头

音频系统HD Audio, Realtek ALC3268

麦克风Built-in Dual Array Microphone(内置双阵列麦克风)

网络通信	
无线网卡Intel 8265(2x2 AC)

有线网卡Intel I219-V (Jacksonville(千兆以太网卡))

蓝牙BT 4.2

I/O接口	
数据接口3个USB3.0(1个USB接口为Always On),1个USB Type C

视频接口HDMI

音频接口Combo jack(麦克风/耳机二合一接口)

读卡器4合1读卡器(MMC,SD,SDHC,SDXC)

输入设备	
指取设备TrackPad 经典触控板 多点触控 3+2按键

电源描述	
电池类型4芯电池(32Wh)+3芯后置电池(24Whr)

### 以下硬件无法驱动
指纹、intel无线网卡无解、蓝牙；无线网卡用的网件usb小卡代替，电池驱动感觉不完美，掉电快。

SD读卡器更改配置，可以识别使用，速度不快。

声卡、usb定制使用hacktool软件补丁clover，声卡为ALC3268，所以我选了id为29的，正常外放跟耳机，hdmi也正常。

感谢
黑果小兵提供系统包
宪武提供初版EFI、电池驱动方案
其他机友支持