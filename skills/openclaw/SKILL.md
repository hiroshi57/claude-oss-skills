---
name: oss-agent-openclaw-run
description: OpenClaw（openclaw/openclaw）は、自分のPCやサーバーに常駐し、Slack/Discord/Telegramなどのチャットから仕事を頼めるオープンソースのAIアシスタント。データを手元に残したまま常駐アシスタントを立てたいときに使う。
---

# OpenClaw（openclaw/openclaw）

## 何のツールか
自分の機器に常駐して、SlackやDiscord、Telegramなどのチャットから作業を頼めるAIアシスタントです。データや認証情報を手元に残したまま使え、モデル（Claudeなど）やスキル・プラグインを差し替えられます。

## 使いどころ
個人やチームで、チャットから呼べる常駐アシスタントを自前環境で動かしたいとき。

## 導入（PowerShell）
公式は1行のシェルインストーラーを配布しています。Windowsでは WSL やGit Bash 経由での実行が無難です。
```powershell
wsl bash -c "curl -fsSL https://openclaw.ai/install.sh | bash"
```

## 基本の使い方
初回の対話式セットアップで、使うモデルとゲートウェイを設定し、チャット連携を繋ぎます。

## 注意点
外部に公開する前に、サンドボックスとセキュリティ設定を確認してください。常駐・外部連携のため権限と認証情報の管理が重要です。

## 出典
- GitHub: https://github.com/openclaw/openclaw
- 掲載: https://meikan.moveai.jp/tools/openclaw/ （掲載★39.5万＝meikan集計値）
