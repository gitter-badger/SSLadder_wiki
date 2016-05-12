title: 如何搭配 Shadowsocks 使用 Dropbox 客户端( PC / Mac )
category: 软件教程
---

**本教程适用于：已经在 Windows 或 OS X 上使用 Shadowsocks 的用户。仅在 Chrome 中配置 SSLadder 请使用网页版**

下面以 OS X 的客户端为例

首先打开 Dropbox 的偏好设置 Dropbox徽标 --- 设置徽标 --- 首选项 

![屏幕快照 2016-04-09 下午6.31.27.png](https://ooo.0o0.ooo/2016/04/09/5708dafee5953.png)

然后进入 网络 --- 代理服务器 --- 更改设置

![屏幕快照 2016-04-09 下午6.31.42.png](https://ooo.0o0.ooo/2016/04/09/5708daffd088f.png)

更改为 手动

然后：

![屏幕快照 2016-04-09 下午6.32.00.png](https://ooo.0o0.ooo/2016/04/09/5708db00305ea.png)


代理服务器类型（Proxy Type）：选择 SOCKS5

服务器地址（Server）请一律填写 127.0.0.1

代理端口（Port）： 填写 1080 （Shadowsocks的默认端口 如果改了端口以改后端口为准）

然后重启 Dropbox 客户端即可!