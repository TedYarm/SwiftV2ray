# SwiftV2ray

集成 V2Ray 的一个简单 gui 工具。没有开机启动／每次启动需要身份验证以设置网络，没有复杂的配置，完全依赖于 v2ray 自身的配置文件，初衷是尽可能简单。

pac 服务器使用 8080 端口，不能修改。

除了 App 本身的包文件夹，只在 ~/Documents/Logs/ 里写了个简单的日志（最大 10M，不可改），卸载直接移除 App 和 log 即可。

建议 routing 里不要加 内网field／chinip／chinasites，我一直遇到内网有部分 ip 访问不稳定，所以在程序里内置了内网不走代理的网络设置；chinaip 和 chinasites 个人感觉没有 pac 使用流畅。

配置编辑器是一个独立的项目集成，使用 ACE web 编辑器。
