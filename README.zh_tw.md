# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - 適用於 iOS 和 macOS 的 Croc CLI 應用程式

從 [應用商店下載最新版本](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- 完全重新設計整個應用程式介面及操作邏輯。
- 將嵌入的 croc 版本升級到 v10.0.8。
- 添加對 iOS 和 macOS 接力功能的支持。
- 支援更多語言。

V1.1
---
- 應用程式圖示重新設計。
- 修復了錯誤並提升了效能。

V1.0
---
croc 是一款允許任意兩台電腦簡單且安全地傳輸文件和文件夾的工具。據我所知，croc 是唯一一個 CLI 文件傳輸工具，能做到以下所有事情：

- 允許任意兩台電腦傳輸資料（使用中繼）
- 提供端到端加密（使用 PAKE）
- 實現跨平台輕鬆傳輸（Windows、Linux、Mac）
- 允許多文件傳輸
- 允許恢復中斷的傳輸
- 不需要本地伺服器或端口轉發
- 優先使用 IPv6，支持 IPv4 回退
- 可以使用代理，例如 tor

該命令行應用程式的源代碼可以在這裡找到：

https://github.com/schollz/croc

## 在 macOS 上啟用 iCroc
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 使用 iCroc 快速傳送文件
- 在 Finder 中選擇文件，然後使用 iCroc 開啟
- 在 Finder 中選擇文件並按 ⌘+C 複製，然後開啟 iCroc 並按 ⌘+V 傳送文件
- 將文件拖入 iCroc

# ⚡ 接力功能
- iOS 和 macOS 設備都安裝 iCroc 應用程式
- 啟用 iOS 和 macOS 的接力功能
- 當發送方生成暗號時，另一台設備的 iCroc 將自動獲取暗號

# 🔮 恢復中斷任務
- 發送方重新發送文件，接收方使用格式 new code-phrase@old code-phrase，例如：4161-mambo-young-baby@7611-south-concept-satire
- 發送方重新發送文件時使用自訂權杖作為之前的暗號

# 💾 自訂接收資料夾
- 接收資料夾將保存到 ~/Downloads/'${code-phrase}'
- 使用 '@folderName' 將保存到 ~/Downloads/folderName，例如：8443-siren-mayor-origin@mypics
- 使用相同的目標資料夾將自動恢復中斷的傳輸任務