# README.md
- [Deutsch](README.de.md)
- [English](README.md)
- [Spanish](README.es.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)

# iCroc - 适用于 iOS 和 macOS 的 Croc CLI 应用

从 [应用商店下载最新版本](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- 全面重新设计整个应用界面及操作逻辑。
- 将嵌入的 croc 版本升级到 v10.0.8。
- 添加对 iOS 和 macOS 传递功能的支持。
- 支持更多语言。

V1.1
---
- 应用图标重新设计。
- 修复了错误并提升了性能。

V1.0
---
croc 是一款允许任意两台计算机简单且安全地传输文件和文件夹的工具。据我所知，croc 是唯一一个 CLI 文件传输工具，能做到以下所有事情：

- 允许任意两台计算机传输数据（使用中继）
- 提供端到端加密（使用 PAKE）
- 实现跨平台轻松传输（Windows、Linux、Mac）
- 允许多文件传输
- 允许恢复中断的传输
- 不需要本地服务器或端口转发
- 优先使用 ipv6，支持 ipv4 回退
- 可以使用代理，例如 tor

该命令行应用的源代码可以在这里找到：

https://github.com/schollz/croc

## 在 macOS 上激活 iCroc
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 使用 iCroc 快速发送文件
- 在 Finder 中选择文件，然后使用 iCroc 打开
- 在 Finder 中选择文件并按 ⌘+C 复制，然后打开 iCroc 并按 ⌘+V 发送文件
- 将文件拖入 iCroc

# ⚡ 传递功能
- iOS 和 macOS 设备都安装 iCroc 应用
- 启用 iOS 和 macOS 的传递功能
- 当发送方生成暗号时，另一台设备的 iCroc 将自动获取暗号

# 🔮 恢复中断任务
- 发送方重新发送文件，接收方使用格式 new code-phrase@old code-phrase，例如：4161-mambo-young-baby@7611-south-concept-satire
- 发送方重新发送文件时使用自定义令牌作为之前的暗号

# 💾 自定义接收文件夹
- 接收文件夹将保存到 ~/Downloads/'${code-phrase}'
- 使用 '@folderName' 将保存到 ~/Downloads/folderName，例如：8443-siren-mayor-origin@mypics
- 使用相同的目标文件夹将自动恢复中断的传输任务