# B360M-DS3H-I5-9600KF-RX580-CLOVER
技嘉B360M DS3H i5-9600KF RX580  macOS Mojave 10.14.6 Hackintosh 黑苹果驱动Clover分享

黑苹果Clover驱动分享项目基本上没有时间维护了，现在精力用来研究自己的信息安全技术了，黑苹果基本上不碰了，但是最近攒机不得不又来折腾下黑苹果，既然折腾了那就顺便来水一篇文章吧。驱动下载

## 驱动下载

Github项目下载：https://github.com/sqlsec/B360M-DS3H-I5-9600KF-RX580-CLOVER/releases

文章地址：https://www.sqlsec.com/2019/12/pc.html

如果Github访问比较卡的话，也可以访问[OneDriver](https://uijay-my.sharepoint.com/:u:/g/personal/aywtc_myoffice_fun/EWgx14JaUktEikTU5jCG5PQBnIfs-WnHRo7Fy7m3Eu6kBQ?e=eCjNyw)  、[蓝奏云](https://www.lanzous.com/i7wpo4h) 

# 主机参数

总价**￥4694** ，以下硬件是国光当时购买的价格仅供参考。

| 组件  | 名称                                   | 购买渠道                                                     | 价格     |
| ----- | -------------------------------------- | ------------------------------------------------------------ | -------- |
| CPU   | i5 9600KF                              | [淘宝](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.3d7b2e8dbUBo6Z&id=604090130728&_u=82ehsl2icfd1) | ￥1170   |
| 内存  | 阿斯加特 洛极红甲 T2 16GB * 2  2666MHz | [京东](https://item.jd.com/61101875649.html)                 | ￥533    |
| 硬盘1 | 海康威视C16 NVME 1TB                   | [淘宝](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.92b72e8d3PQbE7&id=591768278482&_u=82ehsl2i29bd) | ￥739    |
| 硬盘2 | 海康威视C16 SATA 512GB                 | [淘宝](https://detail.tmall.com/item.htm?id=608852330391&spm=a1z09.2.0.0.92b72e8d3PQbE7&_u=82ehsl2i3abb&skuId=4447910455639) | ￥349    |
| 硬盘3 | 希捷 ST2000DM006 7200转 2TB PMR        | [淘宝](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.79182e8dBTCPKp&id=562918490191&_u=82ehsl2i864c) | ￥258    |
| 主板  | 技嘉B360M DS3H                         | 咸鱼                                                         | ￥325    |
| 显卡  | 蓝宝石RX580 2304SP 8GB 白金版          | [淘宝](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.92b72e8d3PQbE7&id=591402176938&_u=82ehsl2icd55) | ￥798    |
| 电源  | 海盗船VS550 额定550W                   | 咸鱼                                                         | ￥138    |
| 机箱  | TT开拓者M3                             | [淘宝](https://buyertrade.taobao.com/trade/itemlist/list_bought_items.htm?spm=a1z09.2.a2109.d1000368.3d7b2e8dbUBo6Z&nekot=1470211439694) | ￥129    |
| 散热  | 九州风神冰凌MiNi + 日食风扇 * 3        | [淘宝](https://detail.tmall.com/item.htm?id=15911422639&spm=a1z09.2.0.0.92b72e8d3PQbE7&_u=82ehsl2i6caf) | ￥85     |
| 网卡  | BCM94360CD 1750Mbps                    | 咸鱼                                                         | ￥170.00 |

这里面用了32GB内存和3.5TB容量的硬盘，读者朋友可以根据自己的需求来调整，选择适合自己的配置。

# 外设参数

总价**￥3864** ，以下硬件是国光当时购买的价格仅供参考。

| 组件     | 名称                                   | 购买渠道                                                     | 价格   |
| -------- | -------------------------------------- | ------------------------------------------------------------ | ------ |
| 键盘     | ikbc poker 61键                        | [京东](https://item.jd.com/3277415.html)                     | ￥399  |
| 鼠标     | 罗技G302                               | 咸鱼                                                         | ￥55   |
| 耳机     | SONY MDR-XB950N1                       | [淘宝](https://detail.tmall.com/item.htm?id=547808872912&spm=a1z09.2.0.0.79182e8d8dpWCW&_u=82ehsl2i583d) | ￥1199 |
| 音箱     | MINISO A18蓝牙音箱                     | MINISO                                                       | ￥129  |
| 键盘掌托 | 香椿木-小号-60键                       | 淘宝                                                         | ￥28   |
| 键帽     | 无刻PBT键帽                            | [淘宝](https://item.taobao.com/item.htm?spm=a1z09.8149145.0.0.1c754a56zPULa4&id=537726367165&_u=82ehsl2ia484) | ￥17   |
| 显示器1  | 13.3寸 京东方 A屏 IPS铝合金外壳便携    | [咸鱼](https://2.taobao.com/item.htm?id=599543376244&spm=a1z09.2.0.0.79182e8d8dpWCW&_u=82ehsl2i65ac) | ￥398  |
| 显示器2  | 27寸 LG面板 组装4K IPS                 | 咸鱼                                                         | ￥750  |
| 平板1    | 小米平板2 2+64GB                       | 咸鱼                                                         | ￥240  |
| 平板2    | BlackBook小黑平板intel X7-Z8700 4+64GB | 咸鱼                                                         | ￥550  |
| 摆件     | 小米智能魔方                           | 米家                                                         | ￥99   |

# 驱动情况

具体也可以参考Bilibili的效果演示视频：

## BIOS

### 系统

**主板型号**：B360M DS3H

**BIOS版本**：F15 （BIOS官网更新一下 否则主板不支持酷睿9代的CPU）

**BIOS日期**：06/05/2019

### BIOS功能

**安全选项**：系统

**快速启动**：启动

**SATA Support**：仅最后一次开机所使用的硬盘

**VGA支持**：自动

**USB Support**：全部初始化

**通过存储设备启动**：UEFI

**其他PCI设备**：UEFI

### 集成外设

**预设启动的显示设备**：PCIe插槽1

**板载网卡**：开启

### 芯片组

**VT-d**：启动

**音效控制器**：启动

**4G以上解码**：关闭

### 电源管理

**平台电力管理**：关闭

**鼠标唤醒**：关闭

## Kexts

本次黑苹果的Kexts已经被国光精简并升级到了最新版本，删除了一些乱七八糟无用或者冲突的Kexts驱动文件：

| 文件名                                                       | 版本                    | 作用                         |
| ------------------------------------------------------------ | ----------------------- | ---------------------------- |
| [AppleALC.kext](https://github.com/acidanthera/applealc/releases) | 1.4.4                   | 原生声卡驱动                 |
| [FakeSMC_ACPISensors.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/) | 6.26-357-gceb835ea.1800 | 温度传感器系列               |
| [FakeSMC_CPUSensors.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/) | 6.26-357-gceb835ea.1800 | 温度传感器系列               |
| [FakeSMC_GPUSensors.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/) | 6.26-357-gceb835ea.1800 | 温度传感器系列               |
| [FakeSMC_LPCSensors.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/) | 6.26-357-gceb835ea.1800 | 温度传感器系列               |
| [FakeSMC_SMMSensors.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/) | 6.26-357-gceb835ea.1800 | 温度传感器系列               |
| [FakeSMC.kext](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/) | 6.26-357-gceb835ea.1800 | 欺骗OS X系统                 |
| [IntelMausiEthernet.kext]()                                  | 2.5.0d0                 | 板载网卡驱动                 |
| [Lilu.kext](https://github.com/acidanthera/Lilu/releases)    | 1.4.0                   | 黑苹果驱动扩展补丁           |
| USBPorts.kext                                                | 1.0                     | 国光自己定制的USB驱动        |
| [WhateverGreen.kext](https://github.com/acidanthera/whatevergreen/releases) | 1.3.5                   | 显卡黑屏、花屏、睡眠黑屏补丁 |

## CPU

高低频正常，日常使用温度 30℃以下：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/8c05d889-17c5-46c6-b067-f9264ca397c1.jpg)     

使用log记录功能`CPU Requsted  Frequency_0(MHz)`的值从低到高如下：

```
800、834、844...{有点多 总之频段基本上都覆盖了的}...4598、4599、4600
```

## GPU

后HDMI、DP接口均可正常4K60Hz输出，机型设置使用`iMacPro1,1` H264硬解、HEVC硬解均成功解锁激活：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/3a8f3e23-cf66-4732-be70-4a2799583ffe.jpg)    

比较蛋疼的是国光我尝试了其他的一些机型就不能开启显卡硬解，有点坑，这个可能是F结尾没有核显的CPU造成的。

## WiFi

目前BCM943602CD实际体验比我之前的BCM943602CS还要稳定：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/4165246a-9f31-41df-9eb0-b205b3e5a65e.jpg)  

参数里面也解锁了多频段、支持无线唤醒和隔空投送：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/97fc1b42-b059-4042-9a08-a19f743e6d31.jpg)    

## 蓝牙

黑苹果蓝牙第一次使用还算稳定，瞎折腾了之后又不稳定了，尝试命令行下删除系统自带的蓝牙配置文件后重启再次连接解决问题，蓝牙又变的好用了：

```bash
# 删除系统自带的蓝牙配置文件(系统重启后会自动生成 可以放心删)
sudo rm /Library/Preferences/com.apple.Bluetooth.plist

# 重启
sudo reboot
```

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/e5e9fa8c-e54e-4798-b56d-3386a410cd8d.jpg)  

## USB

黑苹果USB定制折腾过后，现在后置4个USB3.0已经前置1个USB3.0接口均已经5Gbps满速，蓝牙已经内建，无效多余USB端口均已经删除：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/7ac4de1e-45de-495c-aa22-573b572e41d4.jpg)  

## 声卡

使用`AppleALC.kext`原生声卡驱动，Clover里面注入ID值为`5`，麦克风也可以正常使用，可以看到下方输入电平的是有变化的：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/7a790abb-a422-4e5e-986b-d5bbe6198f6a.jpg)  

## 睡眠

系统升级到10.14.6的时候 本次更换的无线网卡BCM94360CD点击睡眠的时候电脑虽然会断电一次，而且会自动唤醒，导致睡眠失败。

后来远景论坛查资料原来是蓝牙内建的问题，于是USB定制时候就顺便把蓝牙内建了，现在睡眠正常，也可以正常使用键盘和鼠标唤醒，美滋滋，这个才是真正意义上完美黑苹果！！！

## TRIM

TRIM可以延长SSD使用寿命，这里我们可以使用命令手动开启：

```bash
sudo trimforce enable
Is this OK(y/N)? y
```

启动成功重启，关于本机里面查看SSD的TRIM支持情况：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/a6b66655-f3f7-478c-9c3b-eaad80205b7c.jpg)  

## AirDrop

因为免驱无线网卡，蓝牙和WiFi均成功驱动，所以隔空投送自然也是可以正常使用的：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/a55eeeb0-8a8c-468f-93f1-384954589ab4.jpg)    

##  传感器

CPU、GPU、硬盘、风扇转速、电压、功耗均可以正常监测到：

![](https://dn-coding-net-tweet.codehub.cn/photo/2019/109140e5-9aad-495b-9c4b-29264caa1e11.jpg)  
