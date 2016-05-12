title: 如何在各大系统配置 思科 Anyconnect
category: 使用教程
---
## 前言

*因为Anyconnect的协议缺陷，Anyconnect速度和稳定性并没有Shadowsocks好 我们推荐用户升级设备系统到 Android 4.1 / iOS9.0以上并使用Shadowsocks的客户端*

随着Google 和 Apple 先后在自家系统添加了系统级VPN应用的API（Android 4.1+ 添加了[VPNService](http://developer.android.com/reference/android/net/VpnService.html) API , iOS 9+添加了[Network Extension](https://developer.apple.com/library/ios/documentation/NetworkExtension/Reference/Network_Extension_Framework_Reference/) 的系统级API),许多人的 Shadowsocks 科学上网的需求被系统级API解决,再也不需要Root和越狱自己心爱的设备了 



但是老设备、老系统或者系统不支持Shadowsocks怎么办?



Anyconnect就是救星!



**提醒:我们并不推荐在有Shadowsocks解决方案的情况下使用Anyconnect**

# 配置准备

首先，请在 [客户端下载](https://wiki.Anyconnect.com/page/download/) 下载对应平台的 Anyconnect 的客户端

教程快速导航: [Windows 和 Mac OS X](#Desktop) / [Windows Phone](#Windows Phone) / [iOS](#iOS)

# 本教程适用于

Windows PC+ Mac OS X + Windows Phone + iOS

# 各大平台的配置教程

## Desktop

本教程适用于: Windows 和 Mac OS X 系统

由于Windows和Mac版Anyconnect相似度很高(几乎同一个界面) 

所以本文以Mac OS X El Capitan下的Anyconnect为例

偷懒 以后再写

## Windows Phone

我站首席软粉Ray正在努力写出

## iOS

*本教程仅建议iOS 8用户使用,iOS 9用户请用更简单的Shadowrocket*

首先，从 [App Store](https://itunes.apple.com/cn/app/cisco-anyconnect/id392790924?mt=8) 下载 Anyconnect

下载完成后 在桌面上找到AnyConnect


![IMG_1415.PNG](https://ooo.0o0.ooo/2016/05/12/57341875e2df2.png)



打开Anyconnect,点击 `连接`

![IMG_1405.PNG](https://ooo.0o0.ooo/2016/05/12/57341beb3cfbe.png)

选择`添加VPN连接`

![IMG_1406.PNG](https://ooo.0o0.ooo/2016/05/12/573419b77b1f2.png)



`说明` - 给你的VPN连接信息起一个名字

`输入服务器地址` - 格式是 服务器地址:端口 示例: `ac-us1.ssladder.com:1234` 

![IMG_1416.PNG](https://ooo.0o0.ooo/2016/05/12/57341caed1c06.png)

点保存，回到原来的界面，打开`AnyConnect VPN`的开关

![IMG_1405.PNG](https://ooo.0o0.ooo/2016/05/12/57341beb3cfbe.png)

如果你的设备与服务器通信正常，会提示身份认证

请分别输入你的`用户名`和`密码`

`用户名` SSLadder 用户中心的用户名 (见用户中心右上角) 将来可能改为Shadowsocks的端口号为用户名

`密码` - 和浏览器代理一样 输入SSLadder 用户中心的登录密码

![UserName](https://ooo.0o0.ooo/2016/05/12/573419d2c65ec.png)

![Password](https://ooo.0o0.ooo/2016/05/12/573419d2a8863.png)

正在连接...

![IMG_1408.PNG](https://ooo.0o0.ooo/2016/05/12/573419cf737d0.png)

如果用户名和密码正确无误 一会儿 你应该能够看到顶部多了个"VPN"的图标 详细信息也会显示已连接

![IMG_1412.PNG](https://ooo.0o0.ooo/2016/05/12/573419b7f29e3.png)



That's all!享受自由的互联网吧!