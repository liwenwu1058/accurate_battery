# accurate_battery
精准电量，干掉虚假的UI电量，酷安@大鸟转转转酒吧

电量判断至小数点后一位且采用四舍五入变为整数

有两个版本：

后缀**带**no_trickle的为**不将**涓流充电过程加入电量统计的版本，100%后仍会有充电电流。

后缀**不带**no_trickle的为**将**涓流充电过程加入电量统计的版本，99%-100%充电会极为缓慢。


使用自编译的aarch64-linux-musl-gcc，项目地址：[aarch64-linux-musl-gcc](https://github.com/chase535/aarch64-linux-musl-gcc)

已经开启CI构建，可在Actions页面下载CI构建版本以获取最新测试版，**不保证CI构建版本的功能性及稳定性**

**程序遵循AGPLv3开源协议**
