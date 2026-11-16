---
name: oss-automation-n8n-use
description: n8n（n8n-io/n8n）は、AIエージェントと業務ワークフローをビジュアルに構築・運用するfair-codeプラットフォーム。1500以上の連携で業務自動化や多段AIエージェントを組みたいときに使う。
---

# n8n（n8n-io/n8n）

## 何のツールか
AIエージェントと業務ワークフローを、ビジュアルなキャンバスと独自コードで構築・運用するプラットフォームです。セルフホストにもクラウドにも対応します。

## 使いどころ
複数モデルの接続・切替、条件分岐や人による承認を含む業務自動化、既存システムとのAI統合をしたいとき。

## 導入（PowerShell・Docker）
```powershell
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```
起動後、ブラウザで http://localhost:5678 を開きます。

## 基本の使い方
エディタでノードを配置してワークフローを組み、必要に応じてJavaScript/Python/npmでロジックを追加、テストして本番運用に移します。

## 注意点
機密データはセルフホストやセキュアな環境で扱うこと。エンタープライズ機能（RBAC・監査証跡など）は有償ライセンス対象。fair-code（Sustainable Use License）。

## 出典
- GitHub: https://github.com/n8n-io/n8n
- 掲載: https://meikan.moveai.jp/tools/ （掲載★21.1万＝meikan集計値）
