# RazerBlade15-Base-Model-Hackintosh

参考了这两位大佬的设置：

https://github.com/doanhxd/Razer-Blade-15-Advanced-2018-Hackintosh

https://github.com/Tyson-Hu/RazerBlade15-Base-Model-Hackintosh_macOS_Monterey

用标准版的OC直接无法引导，精英版的能用，但有点小问题，就稍微改了下，至少我自己的电脑能用了

采用了mod版OC 0.7.6，正式版的会导致引导不了Windows，开机就蓝屏报错ACPI BIOS ERROR

记得自己补全下三码

![QQ截图20211104103106](https://user-images.githubusercontent.com/70944645/140248038-a5461053-c2a7-431e-84e7-4b5ed04b782f.jpg)

HEVC硬解正常

![截屏2021-11-03 23 49 53](https://user-images.githubusercontent.com/70944645/140248155-056be1fd-105a-453d-9798-fa553eb7a771.png)

外接显示器最好用Type-C的，我这边能用，但分辨率有点奇怪，之后有空再修复

<img width="1424" alt="截屏2021-11-03 23 50 51" src="https://user-images.githubusercontent.com/70944645/140248248-2394a415-2c42-49b8-8aa6-cb268bb4728e.png">

更换过无线网卡BCM94352Z，Intel原装网卡自己添加下驱动就好

https://github.com/OpenIntelWireless/itlwm

已知问题：

1.隔空投送只能单向传输，手机到电脑没问题，电脑到手机有问题，看远景貌似是这款网卡的通病，暂时无解

2.开机默认耳机输出，扬声器外放需要手动切换下，如需自动切换使用蓝牙耳机即可

<img width="1424" alt="截屏2021-12-09 15 13 41" src="https://user-images.githubusercontent.com/70944645/145360445-f77000f7-0b97-494d-822e-d5ceafa128d6.png">

<img width="1424" alt="139776457-a5e7efa6-c240-44ff-8460-2e7b62cb8da7" src="https://user-images.githubusercontent.com/70944645/140242543-2c0b72e9-d4e0-45a4-b91d-cccd524d00b3.png">
