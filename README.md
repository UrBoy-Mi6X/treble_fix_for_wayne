# Treble fix for Xiaomi wayne
> 针对小米 wayne 使用 treble 包的修复

Please check following links first / 请在开始之前查看这些链接

phhusson's wiki / phhusson 的 wiki: https://github.com/phhusson/treble_experimentations/wiki

Detail of Xiaomi Mi 6X / 小米 6X 的使用情况: https://github.com/phhusson/treble_experimentations/wiki/Xiaomi-Mi-6X

And then, please visit wiki of this repository. / 然后阅读此 repository 的 wiki 页面。

Special thanks / 特别感谢: [phhusson](https://github.com/phhusson), [TadiT7](https://github.com/tadit7), [TingyiChen](https://github.com/tingyichen)

Fixes:
* ~~Brightness~~ (already patched since AOSP 9.0 v104)
* ~~Flashlight of front camera~~ (already patched since AOSP 9.0 v106)
* Fingerprint key
* Metadata
* VoLTE (with app `org.codeaurora.ims`)
* Dual Camera (with Magisk module `Xiaomi Mi A2 Camera`, have some bugs)
* Wired Control (should futher fixing)
* Goodix Fingerpring (should futher fixing)

Usage:
* Pack these files into a zip file. (e.g:update.zip)
* "Install" zip file on Magisk what you packed.

修复：
* ~~亮度~~（已于 AOSP v104 修复）
* ~~前置摄像头闪光灯~~（已于 AOSP v106 修复）
* 指纹按键
* 手机信息
* VoLTE（需要安装 `org.codeaurora.ims`）
* 双摄像头（需要 Magisk 模块 `Xiaomi Mi A2 Camera`，有些 bug，手动往 `/system/build.prop` 添加 `persist.camera.expose.aux=1` 开启）
* 线控（目前无效）
* Goodix 指纹（目前无效）

使用方法：
* 将这些文件打包成一个 zip 文件。（例：update.zip）
* 在 Magisk “安装”打包的文件。