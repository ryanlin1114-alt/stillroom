# STILLROOM 靜室 v2 — 捲動式心理恐怖網站

完整繁體中文靜態網站。主線不需要點擊、填寫問卷或登入；只要持續向下捲動，就能從正常商業網站進入逐漸失序的心理恐怖敘事。

## 使用方式

將 `index.html`、`style.css`、`script.js` 放在同一資料夾，開啟 `index.html` 即可。Google Fonts 在網路正常時載入；字型不可用時會自動使用系統字型。

## 更新現有 GitHub Pages

1. 開啟既有的 `stillroom` GitHub 儲存庫。
2. 刪除舊版的 `index.html`、`style.css`、`script.js`（可先下載備份）。
3. 使用 **Add file → Upload files** 上傳新版的同名三個檔案，以及可選的 `README.md`。若 GitHub 允許直接上傳覆蓋同名檔案，可直接覆蓋，不必先刪除。
4. 按 **Commit changes**。
5. Pages 仍沿用原本的 `main` / `/(root)` 設定，不需重新設定。稍等部署完成後重新整理網站。

網址仍為 `https://ryanlin1114-alt.github.io/stillroom/`。

## 設計說明

- 前段：可信的空間設計品牌網站。
- 中段：兩個相同空間的矛盾、評論與文案逐漸失真。
- 中後段：sticky 捲動房間與走廊；捲動距離驅動透視、光線與文字。
- 結尾：不直接揭露全部真相，保留開放式的不安。
- 沒有跳臉、外部追蹤、攝影機、麥克風、定位或資料提交。
- 所有品牌、評論與方案皆為虛構。

## 檔案

- `index.html`：頁面結構與敘事文案
- `style.css`：響應式排版、場景與動畫
- `script.js`：捲動觸發與內容變化
