---
name: oss-dev-rea-analyze
description: REA（morluto/rea）は、ソースコードのないアプリやネイティブバイナリの仕組みをAIエージェントに解析させるリバースエンジニアリング用MCPツール群。競合アプリの機能解析、Electron/.NET/Webの静的解析、バイナリ挙動の調査をしたいときに使う。
---

# REA（morluto/rea）

## 何のツールか
ソースが手に入らないアプリやネイティブバイナリの挙動を、AIエージェントに調べさせるためのリバースエンジニアリング用MCPツール群です。JavaScript/Electron、.NET、Webサイトの静的解析に加え、Hopper・Ghidra・IDAと連携したネイティブ解析にも対応します。

## 使いどころ
競合アプリの機能がどう動いているかを調べたいとき、配布バイナリやElectronアプリの中身を解析したいとき。

## 導入（PowerShell）
```powershell
npx rea-agents setup
```
導入後、対応するAIエージェントにMCPとして登録します。ネイティブ解析にはHopper・Ghidra・IDAのいずれかを併用すると効果的です。

## 基本の使い方
セットアップ後、エージェントから解析対象を指定して静的解析やバイナリ解析を依頼します。

## 注意点
リバースエンジニアリングは対象ソフトの利用規約や各国の法令に触れる場合があります。解析対象の権利と適法性を確認してください。

## 出典
- GitHub: https://github.com/morluto/rea
- 掲載: https://meikan.moveai.jp/tools/rea/ （掲載★46.2万＝meikan集計値）
