---
name: oss-dev-superpowers-use
description: Superpowers（obra/superpowers）は、Claude Codeなどのコーディングエージェントに開発の進め方（要件整理・設計・TDD・レビュー）を手順書として組み込むOSS。中〜大規模の機能を任せたいときに使う。MIT。
---

# Superpowers（obra/superpowers）

## 何のツールか
コーディングエージェントに開発の流れ（要件整理・設計・実装計画・テスト駆動開発・サブエージェント分担・レビュー）を手順として組み込むプラグインです。エージェントが場当たり的にコードを書くのを防ぎます。

## 使いどころ
中〜大規模の機能をエージェントに任せたいとき。小さな修正では手順が重く、トークン消費も増えやすいので不向きです。

## 導入（Claude Code のコマンド）
```
/plugin marketplace add obra/superpowers-marketplace
/plugin install superpowers@superpowers-marketplace
```

## 基本の使い方
導入後、エージェントが各工程を順に踏んで実装を進めます。

## 注意点
ライセンスはMIT。小規模作業には過剰になりやすい点に注意。

## 出典
- GitHub: https://github.com/obra/superpowers
- 掲載: https://meikan.moveai.jp/tools/superpowers/ （掲載★31.8万＝meikan集計値）
