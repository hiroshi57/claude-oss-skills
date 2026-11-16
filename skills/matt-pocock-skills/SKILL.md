---
name: oss-dev-mattpocockskills-use
description: Skills for Real Engineers（mattpocock/skills）は、実務のエンジニアリング手順をエージェント用スキルとして組み合わせて使うスキル集。トリアージ・計画・実装・レビューを型にしたいときに使う。MIT。
---

# Skills for Real Engineers（mattpocock/skills）

## 何のツールか
実務の開発工程（トリアージ・計画・実装・レビュー）を、小さなエージェント用スキルとして提供する集まりです。Claude Code・Codex・Copilotなど複数のエージェントで使えます。

## 使いどころ
大きな仕様駆動フレームワークが重いとき、AIコーディングの進め方を型として決めたいとき。

## 導入（PowerShell）
```powershell
npx skills add mattpocock/skills
```
プラグインとしての導入も可能です。導入後 `/setup-matt-pocock-skills` を一度実行して初期設定します。

## 基本の使い方
各工程のスキルを必要な場面で呼び出し、組み合わせて開発を進めます。

## 注意点
ライセンスはMIT。著作権表示とライセンス文の同梱が必要です。

## 出典
- GitHub: https://github.com/mattpocock/skills
- 掲載: https://meikan.moveai.jp/tools/matt-pocock-skills/ （掲載★32.5万＝meikan集計値）
