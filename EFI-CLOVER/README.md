# ASUS-fx504GE-fx80GE-EFI-CLOVER
## PS：可以用OC版的SSDT来修改完善
* Bios version 318
* Mojave 10.15.3

# Condition
* 开始参考 [https://github.com/PoomSmart/ASUS-FX504GE-Hackintosh] 成功安装，直接使用其EFI但是问题不少，后来发现是DSTDT.aml的问题，于是使用Clover F4自己提取本机的DSDT、SSDT，顺便了解了hotpatch的用法，把原来对DSDT的修改全部做成了热补丁，不直接修改DSDT。
* 解决了触控板的问题，FakeSMC换成了VirtualSMC。
* UHD630是Clover原生支持的，用Hackintool改成2048M显存 [https://blog.daliansky.net/Intel-FB-Patcher-tutorial-and-insertion-pose.html] ，取消了解除USB限制，自己定制了USB，睡眠没有打补丁，正常。

# Working
* 集显UHD630
* 声卡ALC255
* FN调节亮度
* ELAN1200触控板
* USB
* 睡眠

# Not Working
* WIFI
* 蓝牙
* GTX1050ti