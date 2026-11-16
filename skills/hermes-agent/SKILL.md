---
name: oss-agent-hermes-run
description: Hermes Agent（NousResearch/hermes-agent）は、作業からスキルを作り改善し過去会話を検索して思い出す自己改善型エージェント。チャットアプリからサーバー作業を任せる常駐エージェントを作りたいときに使う。MIT。
---

# Hermes Agent（NousResearch/hermes-agent）

## 何のツールか
作業の経験からスキルを作って改善し、過去の会話を検索して思い出す自己改善型のエージェントです。Telegram・Discord・Slack・WhatsApp・CLIなど複数の入口から同じゲートウェイで操作できます。

## 使いどころ
常駐の個人・チーム向けエージェントを作りたいとき、チャットアプリからサーバー上の作業を任せたいとき。

## 導入（PowerShell）
CLIから導入し、モデルとメッセージング連携を設定します。VPSやDockerでの常駐運用が前提になりやすいです。
```powershell
# リポジトリのREADME手順に従いCLIを導入し、
# モデル（Nous Portal / OpenRouter / OpenAI など）と連携を設定する
```

## 基本の使い方
入口（チャットアプリ/CLI）から指示を送り、ゲートウェイ経由で作業させます。実行場所はローカル〜クラウドVMを選べます。

## 注意点
ライセンスはMIT。常駐・外部連携のため権限と認証情報の管理に注意。

## 出典
- GitHub: https://github.com/NousResearch/hermes-agent
- 掲載: https://meikan.moveai.jp/tools/hermes-agent/ （掲載★26.4万＝meikan集計値）
