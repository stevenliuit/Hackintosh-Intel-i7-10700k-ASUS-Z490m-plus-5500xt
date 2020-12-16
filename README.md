# Hackintosh-Intel-i7-10700k-ASUS-Z490m-plus-5500xt
* Hackintosh 10700k + 5500xt双风扇8g显卡

## 硬件配置
* CPU:i7-10700K
* 主板:华硕 PRIME Z490-PLUS
* 内存:三星DDR4 16G 3200MHZ
* 硬盘:intel 480g 企业盘（SSDSC2KW480H6）
* 声卡:ALC887 (仿冒id 99)
* 网卡:I219-V/华硕
* 独立显卡:AMD Radeon RX 5500 XT 8G /技嘉
* 无线网卡+蓝牙:fenvi FV-T919（BCM94360CD）



## 当前引导Bootlader
**Opencore 0.6.4**


# 配置机芯文件和相关工具
* 机芯文件 随意修改了一个 自己根据图片 自己去修改吧
* 我这里下载的是OpenCore Configurator 2.19.0版本 
* 下载地址:[OpenCore Configurator 2.19.0版本](https://mackie100projects.altervista.org/download-opencore-configurator/)

![avatar](image/hackingtosh-1.png)

* 我的电脑配置鲁大师截图
![avatar](image/hackingtosh-2.png)

* 支持双显硬解码
![avatar](image/hackingtosh-3.png)

# 安装选项
**Bios 设置**
* 关闭的选项（自行寻找）
    * Fast Boot
    * CSM
    * Thunderbolt
    * Intel SGX
    * CFG Lock (此主板直接关闭 "Bios version 0403")

* 开启的选项（自行寻找）
    * VT-x
    * 4G Decoding
    * Hyper-Threading
    * XHCI Hand-off
    * Os Type: Windows (您必须从安全启动菜单中删除所有安全密钥)
        * 如果不起作用，请选择 "Other Os"
    * **IMPORTANT:** 你必须设置 Onboard GPU（集成显卡） 内存为 64MB 使用集成显卡没有任何问题

