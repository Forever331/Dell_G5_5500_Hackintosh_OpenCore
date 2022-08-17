# Dell_G5_5500_Hackintosh  

(截至2022/08/12 该OpenCore EFI版本为0.8.3 仅支持macOS Monterey )  

## 该EFI适用于
|硬件|型号|
|-|:-------:|
|CPU|Intel(R) Core(TM) i7-10750H|
|Memory|16GB DDR4 (8Gx2)|
|Storage|NVMe KBG40ZNS512G|
|GPU|Intel(R) UHD Graphics|
|GPU|NVIDIA GeForce RTX 2060 ( 已屏蔽 ) |
|Ethernet|Killer E2500 Gigabit Ethernet Controller|
|WLAN|Killer(R) Wi-Fi 6 AX1650i 160MHz Wireless Network Adapter (201NGW)|
|Bluetooth|英特尔(R) 无线 Bluetooth(R) (隔空投送无法使用)|
|Audio|Realtek ALC3254 (ALC295) Layout-ID = 77 (麦克风无法使用)|
|Display|15.6寸 1920x1080 144Hz|
|Thunderbolt 3|我没雷电设备 但是TypeC口插U盘是能识别的|
|Webcam|我换了摄像头 型号就不写了 摄像头USB端口已内建|
|Card Reader|USB通道 直接插卡试一下 (设备里看不到读卡器)|
|TouchPad & Keyboard|TouchPad(PS/2+HID) Keyboard(PS/2)|
>  USB端口已使用Hackintool导出USBPorts.kext

## 完善情况
✅ Monterey 12.5使用正常 仿冒设备(MackBook Pro16,4 i7-9750H)   
✅ 屏幕背光正常调节  
✅ 扬声器正常使用  
✅ 以太网网卡正常使用  
✅ WIFI正常使用  
✅ 蓝牙正常使用  
✅ 核显正常  
✅ 风扇转速检测正常  
✅ 节能正常  
✅ 睡眠正常  
✅ CPU频率识别正常  
✅ 键盘正常  
✅ 触摸板正常  
✅ Dell热键可用(亮度键为FN+F11/F12)  
🤔 正常使用比Windows续航多1小时+(电池健康度79% 请自行测试)  
😔 耳机插孔低音量可用(无麦克风 待修复)  
😔 投屏有点小问题(平板或手机可连接电脑 但电脑无法连接手机或平板)  
⚠️ 想要白果的自己写SMBIOS  
⚠️ HDMI未测试(应该用不了)  
⚠️ DP未测试(应该用不了?)  
⚠️ 屏幕无144hz(等待修复)   
❌ RTX 2060 无法驱动(已屏蔽)  
❌ 麦克风无法驱动(无驱动)  
❌ 隔空投送无法使用(仅识别)  
❌ 接力、随航、跨设备粘贴、通用控制无法使用(请尝试更换免驱博通网卡)


## macOS概览 
鄙人对该机型的一点微小的工作  
[截图预览](Image/Preview.md)

## 鸣谢
[黑果小兵的部落格](https://blog.daliansky.net/)  
[国光](https://www.sqlsec.com/)  
[黑苹果星球](https://heipg.cn/)

## 更新记录

#### 2022/08/03 (后续可能会长期更新)
* 更新 OpenCore 至 0.8.3 正式版
* Driver存在 OpenHfsPlus.efi 和 HfsPlus.efi 按需开启

#### 2021/09/30 
* OpenCore EFI 0.7.3 BigSur
