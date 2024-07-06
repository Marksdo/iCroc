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

# iCroc - iOSおよびmacOS用のCroc CLIアプリ

[App Storeから最新リリースをダウンロード](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- アプリのインターフェイスと操作ロジックを完全に再設計。
- 組み込みのcrocバージョンをv10.0.8にアップグレード。
- iOSおよびmacOSのハンドオフ機能を追加。
- より多くの言語をサポート。

V1.1
---
- アプリアイコンを再設計。
- バグ修正とパフォーマンスの向上。

V1.0
---
crocは、任意の2台のコンピュータ間でファイルやフォルダを簡単かつ安全に転送できるツールです。私の知る限り、crocは以下のすべてを行う唯一のCLIファイル転送ツールです：

- 任意の2台のコンピュータ間でデータを転送可能（リレーを使用）
- エンドツーエンドの暗号化を提供（PAKEを使用）
- クロスプラットフォーム転送を簡単に実現（Windows、Linux、Mac）
- 複数のファイル転送を許可
- 中断された転送の再開を許可
- ローカルサーバーやポートフォワーディングが不要
- IPv6優先でIPv4フォールバック
- torなどのプロキシを使用可能

このコマンドラインアプリケーションのソースコードは以下で見つけることができます：

https://github.com/schollz/croc

## macOSの設定でiCrocを有効化
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 iCrocでファイルを素早く送信
- Finderでファイルを選択してiCrocで開く
- Finderでファイルを選択して⌘+Cでコピーし、iCrocを開いて⌘+Vでファイルを送信
- ファイルをiCrocにドラッグ

# ⚡ ハンドオフ
- iOSおよびmacOSデバイスにiCrocアプリをインストール
- iOSおよびmacOSでハンドオフ機能を有効化
- 送信者がコードフレーズを生成すると、他のデバイスのiCrocが自動的にコードフレーズを取得

# 🔮 中断されたタスクを再開
- 送信者がファイルを再送し、受信者はnew code-phrase@old code-phrase形式を使用 例: 4161-mambo-young-baby@7611-south-concept-satire
- 送信者が前のコードフレーズをカスタムトークンとして使用してファイルを再送信

# 💾 カスタム受信フォルダ
- 受信フォルダは~/Downloads/'${code-phrase}'に保存されます
- '@folderName'を使用すると~/Downloads/folderNameに保存されます 例: 8443-siren-mayor-origin@mypics
- 同じターゲットフォルダを使用すると中断された転送タスクが自動的に再開されます