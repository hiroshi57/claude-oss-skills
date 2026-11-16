---
name: oss-media-ytdlp-download
description: yt-dlp（yt-dlp/yt-dlp）は、数千サイトに対応したコマンドライン型の動画・音声ダウンローダー。動画取得・音声抽出・字幕やプレイリスト取得をしたいときに使う。
---

# yt-dlp（yt-dlp/yt-dlp）

## 何のツールか
数千のサイトに対応したコマンドライン型の動画・音声ダウンローダーです（youtube-dl系のフォーク）。

## 使いどころ
動画・音声の取得、音声のみの抽出、プレイリスト取得、画質/音質の選択、字幕・サムネイル・メタデータの保存。

## 導入（PowerShell）
```powershell
pip install "yt-dlp[default]"
# または winget install yt-dlp.yt-dlp
```
結合・後処理には ffmpeg / ffprobe の併用が強く推奨されます。

## 基本の使い方
```powershell
yt-dlp <URL>                         # 通常のダウンロード
yt-dlp -F <URL>                      # 利用可能な形式の一覧
yt-dlp -f <形式> <URL>               # 形式を指定して取得
yt-dlp -x --audio-format mp3 <URL>   # mp3で音声抽出
yt-dlp -U                            # 本体の更新
```

## 注意点
stable版は古くなりやすく、通常利用はnightly版が推奨。`--cookies` の書き出しには個人情報が含まれ得るので取り扱い注意。本体はUnlicenseだが、PyInstallerビルド全体はGPLv3+扱い。対象サイトの規約遵守は利用者の責任。

## 出典
- GitHub: https://github.com/yt-dlp/yt-dlp
- 掲載: https://meikan.moveai.jp/tools/ （掲載★20.8万＝meikan集計値）
