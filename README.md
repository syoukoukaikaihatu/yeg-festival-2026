# YEG祭2026 会場案内（本番用）

## GitHub Pagesへの公開
1. ZIPを解凍します。
2. このフォルダ内のファイル・フォルダをすべて、リポジトリの最上位へアップロードします。
3. GitHubの `Settings` → `Pages` を開きます。
4. `Deploy from a branch`、`main`、`/(root)` を選択して保存します。

## 更新方法
- 出展者情報：`data/exhibitors.json`
- タイムテーブル：`data/timetable.json`
- 会場マップ：`assets/map.webp`（同じファイル名で差し替え）

## 構成
- `index.html`：本体
- `assets/map.webp`：会場マップ
- `data/exhibitors.json`：出展者情報
- `data/timetable.json`：タイムテーブル
- `vercel.json`：Vercel用セキュリティヘッダー
- `.nojekyll`：GitHub Pages用
