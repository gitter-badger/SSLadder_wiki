title: 如何选择连接方式
category: SSLadder
---

第一次用 SSLadder 可能有些迷糊 因为我们提供~~三种~~ 两种连接方式（目前仅支持 Shadowsocks 和 SSLadder 浏览器代理 Amyconnect正在调试)

其实这主要是个人的选择问题

# 对于 PC / Mac / Linux / Chromebook 用户

如果你只是用浏览器上上网，或者你用的是 Chromebook 可以使用 SSLadder 浏览器代理

当然 如果你需要系统级支持（比如 GTA Online联机）和追求稳定性 请选择 `Shadowsocks`


# 路由器用户

`Shadowsocks`

# 对于 iOS / Android / 路由器 用户

我们更推荐在手机和路由器这类设备上上用 `Shadowsocks` 

因为 `SSLadder 浏览器代理`是 `AES` 加密.在移动设备上 AES的解密速度不如谷歌的 `CHACHA20` 算法 

而 `Shadowsocks` 方面 我们有 `CHACHA20` 服务器 在ARM和MIPS设备上 解密速度比AES快（在电脑上相反 电脑CPU有AES解密指令集）

还有一点 `SSLadder 浏览器代理` 在移动平台上比较少应用 文档少(大神级别才玩得起) 支持这种方式的App也少（目前已知 iOS 的 Surge 支持 SSLadder 浏览器代理)


