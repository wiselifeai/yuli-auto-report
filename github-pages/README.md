# 有利車業營運報告｜GitHub Pages 發布檔

這個目錄可以直接作為 GitHub repository 的根目錄。

## 第一次發布

1. 在 GitHub 建立新的 repository，例如 `yuli-auto-report`。
2. 將本目錄內的所有檔案上傳到 repository 根目錄，不要只上傳 `index.html`。
3. 開啟 repository 的 `Settings` → `Pages`。
4. 在 `Build and deployment` 選擇 `Deploy from a branch`。
5. Branch 選擇 `main`，資料夾選擇 `/(root)`，按下 `Save`。
6. 等待 GitHub 完成發布，網址通常為：

   `https://你的帳號.github.io/yuli-auto-report/`

## 每日更新

1. 用最新報告覆蓋根目錄的 `index.html`。
2. 把當天版本另存到 `archive/YYYY-MM-DD.html`。
3. 用最新 Markdown 覆蓋 `report.md`。
4. Commit 並 push；GitHub Pages完成發布後，原網址會自動顯示新版。

## iPhone 使用

用 Safari 開啟網站後，點「分享」→「加入主畫面」。主畫面名稱會顯示「有利營運報告」。

## 隱私提醒

一般 GitHub Pages 應視為公開網站。本版加入 `noindex` 與 `robots.txt`，只是在要求搜尋引擎不要收錄，並不是登入保護。上傳前仍應避免放入車牌、個人電話、銀行帳號或其他敏感資料。

## 檔案用途

- `index.html`：固定網址顯示的最新版。
- `report.md`：最新版 Markdown。
- `archive/2026-08-13.html`：目前歷史快照。
- `.nojekyll`：讓 GitHub Pages直接發布靜態檔案。
- `robots.txt`：要求搜尋引擎不要建立索引。
- `404.html`：網址輸入錯誤時返回首頁。
