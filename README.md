# 平江皮影戯デジタルアーカイブ ホームページ

このフォルダは、GitHub Pages / 静岡大学HP / 一般Webサーバーで公開できるホームページ一式です。

## 機能

- 原文・日本語訳・演目名で検索
- 各セリフをZenodo上の音声ファイルにリンク
- 「音声」ボタンで該当時刻から再生
- 「動画」リンクで該当時刻の動画を開く
- 英語訳なし
- 写真・ポスター資料付き

## 公開方法

### GitHub Pages の場合
1. このZIPを展開
2. `index.html`, `data.json`, `assets/` をGitHubリポジトリにアップロード
3. Settings → Pages → Deploy from branch を有効化
4. 表示されたURLにアクセス

## Zenodo

DOI: https://doi.org/10.5281/zenodo.20084809

## 注意

Zenodoの音声ファイルURLは以下の形式で参照しています。

`https://zenodo.org/records/20084809/files/ファイル名?download=1`

Zenodo側のファイル名が変更された場合は、`index.html` 内の `audio_url` を修正してください。
