# Dell_G5_5500_Hackintosh

### 该EFI适用于
|硬件|型号|
|-|:-------:|
|CPU|Intel(R) Core(TM) i7-10750H|
|Memory|16GB DDR4 (8Gx2)|
|Storage|NVMe KBG40ZNS512G|
|GPU|Intel(R) UHD Graphics|
|GPU|NVIDIA GeForce RTX 2060 ( 无法工作 ) |
|Ethernet|Killer E2500 Gigabit Ethernet Controller|
|WLAN|Killer(R) Wi-Fi 6 AX1650i 160MHz Wireless Network Adapter (201NGW)|
|Bluetooth|英特尔(R) 无线 Bluetooth(R) (隔空投送无法使用)|
|Audio|Realtek ALC3254 (ALC295) Layout-ID = 77 (麦克风无法使用)|
|Display|15.6寸 1920x1080 144Hz|
|Thunderbolt 3|我没雷电设备 但是TypeC口插U盘是能识别的|
|Webcam|我换了摄像头 型号就不写了 摄像头的USB端口我加入了的|
|Card Reader|USB通道 直接插卡试一下 (设备里看不到读卡器)|
|TouchPad & Keyboard|这俩走的PS/2通道|
> 触摸板 因为PS/2通道的只有鼠标驱动能用 所以插入其他鼠标(USB/蓝牙)会被顶替掉 
>> 键盘没事(我不知道为啥)

>  USB端口基本都加入了有些可能没加入进去 自己在Win上面用工具抓一下 替换掉Kexts/UTBMap.kext

✅ BigSur 11.6使用正常 仿冒设备(MackBook Pro16,4 i7-9750H)  
✅ Dell热键可用  
✅ 键盘背光可用  
✅ 背光正常调节  
✅ 扬声器正常使用  
✅ 以太网网卡正常使用  
✅ WIFI正常使用  
✅ 蓝牙正常使用  
✅ 核显正常 144hz正常  
⚠️ 想要白果的自己写SMBIOS  
⚠️ HDMI未测试(应该用不了)  
⚠️ DP未测试(应该用不了?)  
❌ 隔空投送无法使用  
❌ RTX 2060 无法驱动  
❌ 麦克风无法使用  

### macOS概览 
鄙人对该机型的一点微小的工作
![](https://s3.bmp.ovh/imgs/2021/09/e5b7b01c6a724619.png)

#### 鸣谢
[黑果小兵的部落格](https://blog.daliansky.net/)  
[国光](https://www.sqlsec.com/)  
[Github的各位开源的朋友](https://Github.com)  

(截至2021/09/30 该OpenCore EFI版本为0.7.3 仅支持BigSur )
