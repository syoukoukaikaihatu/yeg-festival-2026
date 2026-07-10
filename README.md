# YEG祭2026 会場案内（本番用・背景画像組み込み版）

## GitHubへアップロードするもの
このフォルダの中身をすべて、リポジトリの一番上（ルート）へアップロードしてください。

- index.html
- .nojekyll
- vercel.json
- README.md
- assets フォルダ
- data フォルダ

特に `assets/map.webp` が会場マップ画像です。`assets` フォルダごとアップロードしてください。

## GitHub Pages
Settings → Pages → Deploy from a branch → main / (root) → Save

## 更新方法
- 会場マップ：`assets/map.webp` を同じ名前で差し替え
- 出展者：`data/exhibitors.json` を編集
- タイムテーブル：`data/timetable.json` を編集
