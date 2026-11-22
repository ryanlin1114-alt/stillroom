# STILLROOM 靜室

一個完全虛構的繁體中文心理恐怖互動網站。開始時是一個精緻的數位生活服務網站，隨著捲動、評估與房間互動，逐步呈現不可靠的文字、異常空間與隱藏結局。

## 開啟方式

將 `index.html`、`style.css`、`script.js` 放在同一資料夾，直接用瀏覽器開啟 `index.html` 即可。若想讓朋友透過網址開啟，請依照下方 GitHub Pages 教學。

## 主要互動

- 捲動探索：不同區塊的文字與整體氣氛隨探索進度改變。
- 個人空間評估：三題選擇題，完成後可進入房間。
- 互動房間：點擊門、窗、燈；連續互動將引出異常與結局。
- 回訪記憶：使用 `localStorage` 保留進度，重新整理仍會記得選擇。
- 聲音：右上角 ♫ 可自行開啟低頻環境音，預設關閉。
- 重設：頁尾「重設體驗」清除本機進度。

## 免費部署到 GitHub Pages

1. 前往 https://github.com/ 註冊或登入。
2. 點選右上角 `+` → `New repository`。
3. Repository name 輸入 `stillroom`，選擇 `Public`，點選 `Create repository`。
4. 進入新儲存庫，選 `Add file` → `Upload files`，上傳 `index.html`、`style.css`、`script.js`（也可以連 README.md 一起上傳）。**不要直接上傳 ZIP 檔**。
5. 按 `Commit changes` 儲存。
6. 點 `Settings` → 左側 `Pages`，在 `Build and deployment` 下把 Source 設為 `Deploy from a branch`。
7. Branch 選 `main`，資料夾選 `/(root)`，按 `Save`。
8. 等候 GitHub Pages 完成發佈（通常幾分鐘）。重新整理 Pages 設定頁，找到網站網址，通常是 `https://你的GitHub帳號.github.io/stillroom/`。
9. 以無痕模式測試網址，確認朋友不需登入也能開啟。

如要更新：重新上傳修改過的檔案並 commit，稍候公開網站便會更新。

## 隱私與安全

此作品不要求帳號、不會要求攝影機、麥克風、定位權限，也不會向伺服器傳送問卷選擇。互動紀錄僅保留在目前瀏覽器的 localStorage，可由頁尾重設。Google Fonts 為可選的外部字型資源，離線時會使用系統字型。

## 注意

- 品牌、方案、評價與價格皆為虛構展示，不提供真實商業服務。
- 手機與桌面皆支援；使用鍵盤也能操作主要按鈕。
- 支援偏好減少動態效果的系統設定。
