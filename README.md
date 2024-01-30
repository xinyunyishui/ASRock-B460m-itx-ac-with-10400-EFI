# ASRock-B460m-itx-ac-with-10400-EFI
OpenCore版本：0.9.7  
## 使用OC编辑器之前请将编辑器的OC升级至0.9.7
MacOS：Ventura 13.6  
主板：华擎B460m-ITX/AC  
CPU：i5-10400  
内存：金士顿8G*2 DDR4 2666  
ssd：西数SN550 500G NVME  
显卡：核显HD630  
HDIM+DP均可正常输出视频+音频  
前后6个USB完美  
板载有线网卡完美  
板载无线可用  
板载蓝牙可用，但是挑设备，实测只有一把FL980v2的键盘可以连上，其他耳机、手柄、罗技G603鼠标能识别但是无法连接，盲猜可能是应为设备是蓝牙4.x，键盘是5.0？    
  
所有kext截止2024.1.28日均为最新版本。  
  
# 关于蓝牙问题  
在[OpenIntelWireless/IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)提交了issues，作者回复如下：  
![PixPin_2024-01-29_09-09-57](https://github.com/xinyunyishui/ASRock-B460m-itx-ac-with-10400-EFI/assets/49899578/11fcff4d-0ef8-46f1-80c9-b889e5c339c4)

总结就是：又不是不能用^_^    
  
下载后请更改三码，其他可直接使用。
