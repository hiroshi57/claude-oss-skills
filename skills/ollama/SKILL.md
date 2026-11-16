---
name: oss-llm-ollama-run
description: Ollama（ollama/ollama）は、オープンなLLMをローカルやクラウドで手軽に動かすツール。ローカルでモデルをチャット実行したり、コーディングツールやAPIから使いたいときに使う。
---

# Ollama（ollama/ollama）

## 何のツールか
オープンなモデルをローカルやクラウドで手軽に動かすツールです。ローカル実行でプライバシーを保ちやすいのが特徴です。

## 使いどころ
モデルとのチャット、コーディングツール連携、REST API / Python / JavaScript からのアプリ開発。

## 導入（PowerShell）
```powershell
irm https://ollama.com/install.ps1 | iex
```

## 基本の使い方
```powershell
ollama run gemma4        # モデルを起動してチャット
# REST: http://localhost:11434/api/chat にリクエスト
```
`pip install ollama` / `npm i ollama` でライブラリも利用できます。

## 注意点
バックエンドは llama.cpp。利用できるモデルの一覧は ollama.com/library。ローカル実行とクラウド利用の違いは公式ドキュメントで確認してください。

## 出典
- GitHub: https://github.com/ollama/ollama
- 掲載: https://meikan.moveai.jp/tools/ （掲載★18.7万＝meikan集計値）
