# iStoreOS 固件

iStoreOS 目标是提供一个人人会用的路由兼轻 NAS 系统，不管是作为路由还是 NAS，你都有相似的操作体验。
iStoreOS 来源于 OpenWRT，相较于原版 OpenWRT，iStoreOS 具有以下优势：

1. iStoreOS 提供了**软件中心**：[**iStore**](https://github.com/linkease/istore)，尽可能解决插件之间的依赖关系，可让大家自由自在安装插件，并且支持插件备份以及恢复。
2. iStoreOS 固件升级时会保留用户安装的插件，避免升级以后还要再安装一遍插件。
3. iStoreOS 官方支持的硬件都可以**在线升级**，无需手动下载固件升级。
4. iStoreOS 拥有**沙箱模式**。通过 U 盘进入沙箱模式，后续的软件安装更新以及系统配置都在沙箱进行。不管安装插件搞坏了系统还是配置错误导致系统故障，拔掉 U 盘就回到进沙箱前的状态。如果对当前状态满意还可以回写到非沙箱环境。沙箱模式本身也是系统扩容的最简单的方法。
5. iStoreOS 本身就是精简版本，所有的额外功能都是触发到了，依赖软件中心去额外安装插件实现。iStoreOS并不是臃肿的把所有用到的插件内置到固件中。

iStoreOS 还做了很多很多的交互简化，但是即使再简化，对于不同的用户级别，我们还是得提供了三套完全不一样的交互 UI。更多介绍请移步我们的 [WIKI](https://github.com/istoreos/istoreos/wiki) 以及我们的[官网](https://site.istoreos.com)

## 支持硬件

* 目前 [iStoreOS](https://site.istoreos.com/firmware) 固件支持机型一览表。

| 型号 | 型号 | 型号 | 型号 |
|------|------|------|------|
| [X86_64](https://site.istoreos.com/firmware/download?devicename=x86_64&firmware=iStoreOS) | [EasePi-R1](https://site.istoreos.com/firmware/download?devicename=easepi-r1&firmware=iStoreOS) | [EasePi-ARS2](https://site.istoreos.com/firmware/download?devicename=ars2&firmware=iStoreOS) | [EasePi-ARS4](http://fw.koolcenter.com/iStoreOS/ars4/) | 
| [ZX3000](https://site.istoreos.com/firmware/download?devicename=zx3000&firmware=iStoreOS) | [HinLink-H88K](https://site.istoreos.com/firmware/download?devicename=h88k&firmware=iStoreOS) | [HinLink-H66/68/69K系列](https://site.istoreos.com/firmware/download?devicename=h6xk&firmware=iStoreOS) | [HinLink-H28K](https://site.istoreos.com/firmware/download?devicename=h28k&firmware=iStoreOS) |
| [NanoPi-R6S/R6C](https://site.istoreos.com/firmware/download?devicename=r6s&firmware=iStoreOS) | [NanoPi-R5S/R5C](https://site.istoreos.com/firmware/download?devicename=r5s&firmware=iStoreOS) | [NanoPi-R4S](https://site.istoreos.com/firmware/download?devicename=r4s&firmware=iStoreOS) | [NanoPi-R4SE](https://site.istoreos.com/firmware/download?devicename=r4se&firmware=iStoreOS) |
| [NanoPi-R3S](https://site.istoreos.com/firmware/download?devicename=r3s&firmware=iStoreOS) | [NanoPi-R2S/2C](https://site.istoreos.com/firmware/download?devicename=r2s&firmware=iStoreOS) | [电犀牛R66/68S](https://site.istoreos.com/firmware/download?devicename=r6xs&firmware=iStoreOS) | [Radxa-E54C](https://site.istoreos.com/firmware/download?devicename=e54c&firmware=iStoreOS) |
| [Radxa-E52C](https://site.istoreos.com/firmware/download?devicename=e52c&firmware=iStoreOS) | [Radxa-E20C](https://site.istoreos.com/firmware/download?devicename=e20c&firmware=iStoreOS) | [树莓派5](https://site.istoreos.com/firmware/download?devicename=rpi5&firmware=iStoreOS) | [树莓派4](https://site.istoreos.com/firmware/download?devicename=rpi4&firmware=iStoreOS) |
| [SEED-AC1](https://site.istoreos.com/firmware/download?devicename=seed-ac1&firmware=iStoreOS) | [SEED-AC3](https://site.istoreos.com/firmware/download?devicename=seed-ac3&firmware=iStoreOS) | [GL-BE3600](https://site.istoreos.com/firmware/download?devicename=gl-be3600&firmware=iStoreOS) | [GL-MT3000](https://site.istoreos.com/firmware/download?devicename=mt3000&firmware=iStoreOS) |
| [莱因特T68M](https://site.istoreos.com/firmware/download?devicename=t68m&firmware=iStoreOS) | [Station-P2](https://site.istoreos.com/firmware/download?devicename=station-p2&firmware=iStoreOS) |


## 关注更新

更多iStoreOS 功能，请关注我们的账号：

* [酷友社B站账号](https://space.bilibili.com/1492058311?spm_id_from=333.788.0.0)
* [酷友社 Youtube](https://www.youtube.com/channel/UCvENMyIFurJi_SrnbnbyiZw)
* [QQ 群](https://www.koolcenter.com/posts/117)
* [TG 群](https://t.me/+QwxW7aimSMeRdQJX)
* 微信扫码关注公众号：[istoreos-gongzhong](https://doc.linkease.com/assets/img/istoreos-gongzhong.7b082729.png)
