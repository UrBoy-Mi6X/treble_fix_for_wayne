# Treble fix for Xiaomi wayne / 针对小米 wayne 使用 treble 包的修复

Please check following links first / 请在开始之前查看这些链接

phhusson's wiki / phhusson 的 wiki: https://github.com/phhusson/treble_experimentations/wiki

Detail of Xiaomi Mi 6X / 小米 6X 的使用情况: https://github.com/phhusson/treble_experimentations/wiki/Xiaomi-Mi-6X

And then, please visit wiki of this repository. / 然后阅读此 repository 的 wiki 页面。

> It will changes to shell commands in the future. / 将来会修改为 shell 脚本。

build.prop with some patches.

Fixes:
* VoLTE and flash light of the front camera.
* Corrected info of the phone.

Tested on AOSP v105 by phhusson.

Special thanks: TadiT7

Usage:
* Replace build.prop which on /system
* Set permission of /system/build.prop to 0644 / rw-r--r--

build.prop 修复版

修复：
* VoLTE、前置摄像头的闪光灯
* 修正手机信息

在 phhusson 的 AOSP v105 上测试通过

特别感谢：TadiT7

使用方法：
* 替换 /system 里面的 build.prop
* 将 /system/build.prop 的权限设置为 0644 / rw-r--r--