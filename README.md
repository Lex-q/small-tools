RPA来实现Windows屏幕自动解锁

项目背景：我需要用到微信自动文件发送的脚本，但是pc有安全限制只有在锁屏解锁的状态才能发送文件，所以需要前面穿插这个自动解锁脚本使用。

1、Python 安装 Pywinio库。

pip isntall pywinio

2、安装64位系统上的驱动签名：
​ 以管理员身份打开命令窗口CMD。
​ 键入以下命令以启动测试签名。

​ bcdedit.exe /set TESTSIGNING ON

然后重启计算机。

3.运行unlock.py（可以搭配bat自动脚本使用）

参考：https://blog.csdn.net/weixin_44358694/article/details/128303572
