# ASUS-fx504GE-fx80GE-EFI
ASUS-fx504GE-fx80GE-EFI
**MacOS版本：14.4.1**
**OpenCore版本：1.0.0**
- ~~VoodooPS2Controller.kext 升级后会导致内置键盘无法使用.~~（以前会）
- 使用耳机会导致输出严重失真 音响有较大底噪
- 后续更换了英特尔AX210网卡实现了WIFI和蓝牙
- 原RTL8821CE只驱动了蓝牙，RTL网卡的EFI将会放在RTL-EFI
- 长时间睡眠睡死暂未解决
## 工作的部分

- CPU（睿频4.0Ghz）
- 核芯显卡
- 有线网卡
- 音频（Layout=3）
- USB（定制USBPorts.kext）
- 触摸板
- 摄像头
- 蓝牙
- HDMI
- WIFI

[![3755-D6-C7-BF62-4410-AFAB-41765-FA6703-B.png](https://github.com/YugeSQl/ASUS-fx504GE-fx80GE-EFI/blob/main/3755D6C7-BF62-4410-AFAB-41765FA6703B.png)](3755-D6-C7-BF62-4410-AFAB-41765-FA6703-B.jpg)
