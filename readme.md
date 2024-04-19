# ASUS-B460M-TUF-I5-10900

sonoma ota升级失败的bug:

1、disable 掉Airportltlwm.kext，蓝牙相关的两个kext
2、SecureBootModel设置为Disable
3、重启， 清nvram
4、增量更新会失败，走全量镜像更新