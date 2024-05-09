# v2rayNG
安卓版 V2Ray 客户端，支持 Xray core 和 v2fly core


Geoip 和 Geosite
geoip.dat 和 geosite.dat 文件位于 Android/data/com.v2ray.ang/files/assets 中（某些 Android 设备的路径可能不同）
下载功能将在此版本库中获得增强版（注意需要使用有效的代理服务器）
可手动导入最新的官方域名列表和 IP 列表
可在同一文件夹中使用第三方数据文件，如 h2y


文档 
https://github.com/2dust/v2rayNG/wiki


V2rayNG 文件夹下的 Android 项目可以直接在 Android Studio 中编译，也可以使用 Gradle 封装器编译。 但 aar 中的 v2ray 内核（可能）已经过时。
可以从 Golang 项目 AndroidLibV2rayLite 或 AndroidLibXrayLite 中编译 aar。 如需快速入门，请阅读 Go Mobile 和 Makefiles for Go Developers 指南。

v2rayNG 可以在 Android 模拟器上运行。 对于 WSA，需要通过 appops set [package name] ACTIVATE_VPN allow 授予 VPN 权限。

通过DeepL翻译 https://www.deepl.com/app/?utm_source=android&utm_medium=app&utm_campaign=share-translation
