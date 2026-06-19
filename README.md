# LA Trip 2026 ☀️ — Eternal Sunshine Travel App

ロサンゼルス旅行（2026/6/20–6/22）の旅程アプリ。Ariana Grande @ Kia Forum を中心に、
旅程（表）・食事マップ・フライト・ホテル・コンサート・費用・持ち物チェックリストを
1ページにまとめています。`index.html` 単体で動く静的サイトです（ビルド不要）。

## 機能
- 🗓 **旅程**：日ごとの表。各スポット名タップでGoogleマップが開く
- 🍴 食事マップ / ✈️ フライト / 🏨 ホテル / 🎤 コンサート / 💳 費用 / ✅ 持ち物
- 出発までのカウントダウン、チェックリストは端末に保存（localStorage）
- スマホ最適化・Eternal Sunshine風デザイン（紫×パステル）

## 🔒 プライバシー
公開版のため、パスポート番号・生年月日・予約番号・カード情報などの機微情報は
**意図的に除外**しています。

## 🚀 GitHub Pages へのデプロイ

### 方法A：Web UIだけ（git不要・いちばん簡単）
1. https://github.com/new で新規リポジトリを作成（名前は例: `la-trip-2026`、**Public**）
2. 作成後の画面の **uploading an existing file** をクリック
3. このフォルダの `index.html`（と `README.md`）をドラッグ&ドロップ → **Commit changes**
4. **Settings → Pages** → Source を `Deploy from a branch` → `main` / `/ (root)` にして **Save**
5. 数十秒後に公開 👉 `https://USERNAME.github.io/la-trip-2026/`

### 方法B：コマンド（gitが使えるPCで）
```bash
cd "Los Angles Travel App"
git init -b main
git add index.html README.md .gitignore
git commit -m "LA Trip 2026 travel app"
git remote add origin https://github.com/USERNAME/la-trip-2026.git
git push -u origin main
```
あとは方法Aの手順4と同じく Settings → Pages を設定。

## ローカルで開く
`index.html` をブラウザでダブルクリックするだけでOK。
