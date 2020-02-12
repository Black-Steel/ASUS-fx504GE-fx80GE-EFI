# ASUS-fx504GE-fx80GE-EFI
Mojave 10.15.3  
Bios version 318

# Condition
开始使用这位 [https://github.com/PoomSmart/ASUS-FX504GE-Hackintosh] 的引导成功安装，但是问题不少，后来发现是DSTDT.aml的问题，于是使用Clover F4自己提取本机的DSDT、SSDT，顺便了解了hotpatch的用法，把原来对DSDT的补丁全部做成了热补丁，不直接修改DSDT。  
解决了触控板的问题，FakeSMC换成了VirtualSMC。  
UHD630是Clover原生支持的，用Hackintool改成2048M显存 [https://blog.daliansky.net/Intel-FB-Patcher-tutorial-and-insertion-pose.html] ，取消了解除USB限制，自己定制了USB，睡眠没有打补丁，正常。

# Not Working
WIFI  
蓝牙  
GTX1050ti

# Problems
不接鼠标只用触控板一段时间后触控板会失效。  
PoomSmart提供的EFI开机会有一声“咚”，现在没了，完全复制ta原来的机型（Macbook pro 15,2, 改成15,1），可以，但是睡眠后直接进入桌面，没有登陆界面。