# claude-oss-skills

meikan.moveai.jp の「AI社員の道具箱（OSS）」に掲載された、GitHubスター5万以上のOSSツールを、使い方をまとめた Claude スキル（SKILL.md）に変換して貯めるリポジトリです。

- 生成元: https://meikan.moveai.jp/tools/
- 生成スキル: `di-ai-ossskill-generate`（2日に1回の定期タスクで自動巡回）
- 構成:
  - `skills/<tool-slug>/SKILL.md` … 各ツールの使い方スキル
  - `registry.json` … 処理済み台帳（重複生成を防ぐ唯一の正本）

初回は掲載全件、以降は `registry.json` にある処理済みを除いた差分のみを対象にします。
