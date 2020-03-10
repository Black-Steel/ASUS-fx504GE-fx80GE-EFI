# ASUS-fx504GE-fx80GE-EFI-OC
* Bios version 318
* Mojave 10.15.3

# Condition
## 参考了三位大佬的内容
* [精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)
* [使用OpenCore引导黑苹果](https://blog.xjn819.com/?p=543)
* [OC-little](https://github.com/daliansky/OC-little)

# Working
* 集显UHD630
* 声卡ALC255
* FN调节亮度（在config.plist里关了，手动打开，ACPI->Add、Patch）
* ELAN1200触控板
* USB
* 睡眠
* 蓝牙+WIFI（DW1820A）
* config.plit里面CFG Lock的部分是False，没解锁的要打开（教程很多，直接搜）

# Not Working
* GTX1050ti