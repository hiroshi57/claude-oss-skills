---
name: oss-web-firecrawl-scrape
description: Firecrawl（firecrawl/firecrawl）は、Webの検索・スクレイピング・クロールをスケールで行い、ページをLLM向けのMarkdownや構造化JSONに変換するAPI。AIエージェントにWebアクセスを組み込みたいときに使う。
---

# Firecrawl（firecrawl/firecrawl）

## 何のツールか
Webの検索・スクレイピング・クロールを行い、ページをLLMが扱いやすいMarkdownや構造化JSONに変換するAPIです。オープンソースで、ホスト型サービスもあります。

## 使いどころ
検索上位ページの本文取得、単一URLの変換、サイト全体のクロール、URL一覧の取得（Map）、AIエージェント/MCPへのWebアクセス組み込み。

## 導入（PowerShell）
```powershell
pip install firecrawl-py
# Node の場合: npm install firecrawl
```
firecrawl.dev でAPIキーを取得し、SDKでクライアントを初期化します。

## 基本の使い方
scrape（単一ページ）・search（検索）・crawl（サイト全体）・map（URL一覧）などを呼び出します。

## 注意点
クラウド版はAPIキーが必要でクレジットを消費。既定でrobots.txtを尊重。対象サイトの規約遵守は利用者の責任。本体はAGPL-3.0、SDK・一部UIはMIT。

## 出典
- GitHub: https://github.com/firecrawl/firecrawl
- 掲載: https://meikan.moveai.jp/tools/ （掲載★20.2万＝meikan集計値）
