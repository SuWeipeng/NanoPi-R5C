# 中文简体 | [English](https://github.com/DHDAXCW/NanoPi-R4S-2021/blob/main/EngLish.md)
# NanoPi-R4S-2021 每天自动更新插件和内核版本。
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## 强烈推荐三星TF卡\海康TF卡。哪怕是很难刷上的固件，只有三星刷上可以开机。
### 固件分类 在[releases](https://github.com/DHDAXCW/NanoPi-R4S-2021/releases)有备注关键词
- 正式版（含超频）对折腾的，可以选择，电压一定要考虑。超频都是升压的，会造成不稳定的。比如跑cpu测试容易升压等。
- Docker版 含Docker插件，会导致udp转发失效 慎用哦，只要别开passwall的udp，啥都不影响使用！
- 稳定版 含有日常使用插件
- 此版本取消了精简版，改为稳定版
### 注：不要用恢复备份。。不保证某个插件是否正常运行。。。建议重新设置贼好！！！
### 默认编译  

- 用户名：root 密码：password  管理IP：192.168.2.1
- 下载地址： https://github.com/DHDAXCW/NanoPi-R4S-2021/releases
- x86_64固件下载 https://github.com/DHDAXCW/lede/releases
### - Docker：正式版带docker，有超频，带有docker插件。（对passwall的udp要求很高，不要刷docker版本）
- 电报群：https://t.me/DHDAXCW
- X86固件 ：[点击链接下载](https://github.com/DHDAXCW/lede/releases)
# 在线升级
- 复制以下代码，在TTYD终端执行，过程中不得离开，否则还得重新下载，请刷ext4格式明天再升级
### 该升级只支持4G版，1G版不支持，请不要用此升级。1G版内存tmp分区空间不足，无法下载升级包
- 多版本在里面，自己选 👇
```
wget https://raw.githubusercontent.com/DHDAXCW/NanoPi-R4S-2021/main/scripts/autoupdate.sh && sh autoupdate.sh
```
# 插件展示
 ![Alt text](data/20.jpg?raw=true "Title")
## 提示
 - 我的固件加了动态超频，不管热不热这是取决后台运行程序在跑什么。
 - 感觉很热  就加风扇，推荐 风扇6cm×6cm，薄1cm，usb也行 或者端子线zh1.5（风扇脚本目前在建设中）
# [赏个鸡腿吧](https://afdian.net/@dhdaxcw/plan)

## 鸣谢

特别感谢以下项目：

Openwrt 官方项目：

<https://github.com/openwrt/openwrt>

Lean 大的 Openwrt 项目：

<https://github.com/coolsnowwolf/lede>

immortalwrt 的 OpenWrt 项目：

<https://github.com/immortalwrt/immortalwrt>

P3TERX 大佬的 Actions-OpenWrt 项目：

<https://github.com/P3TERX/Actions-OpenWrt>
