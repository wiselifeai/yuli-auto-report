# 有利車業營運報告中心｜GitHub Pages

本目錄是完整 GitHub Pages網站。請把本目錄內的所有檔案與資料夾放到 repository 根目錄。

## 網站入口

- `index.html`：報告中心首頁。
- `operations/current.html`：Supabase 截至 2026/10/11 的最新營運與現金流報告；`operations/index.html` 會轉址至此頁。
- `weekly/index.html`：每週報告索引。
- `weekly/week-06.html`：較新的既有正式週報；10/7–10/11另有未結週期暫行快照，尚非正式週報。
- `weekly/week-03.html`：第三週營運與現金流週報。
- `weekly/week-02.html`：第二週管理檢討。
- `analysis/monthly-comparison.html`：9月完整月與10月截至11日的月對月營運、毛利及現金流比較。
- `analysis/work-order-margin-current.html`：截至 2026/10/11 的工單毛利與缺成本彙總。
- `analysis/annual-simulation-current.html`：依最新完整成本期間重估的年度情境；舊 `analysis/annual-simulation.html` 轉址至此頁。
- `weekly/system-update-2026-10-11.html`：10/7–10/11未結週期的系統暫行快照，非正式週報。
- `strategy/index.html`：舊版經營戰略與營運日報。
- `archive/`：凍結的歷史版本與原始舊版。

## 這次如何更新已上線的 repository

1. 解壓縮更新包。
2. 進入 `github-pages` 資料夾。
3. 把資料夾裡的所有內容上傳到既有 repository 根目錄。
4. 選擇覆蓋既有 `index.html`、`README.md`、`404.html`、`report.md` 與 `robots.txt`。
5. 確認 `operations`、`weekly`、`analysis`、`strategy`、`archive` 五個資料夾都有上傳。
6. GitHub Pages重新部署後，原本的網站網址不變，但首頁會變成完整報告中心。

不要把 ZIP 檔直接上傳到 repository；GitHub不會替你解壓縮。

## 每日更新流程

1. 更新 `operations/current.html` 為最新營運報告；保留 `operations/index.html` 的轉址。
2. 當日版本另存到 `archive/operations/YYYY-MM-DD.html`。
3. 最新 Markdown 同步更新 `operations/report.md` 與根目錄 `report.md`。
4. 更新根目錄 `index.html` 的資料截止日及摘要數字；舊檔名應轉址至最新頁。

## 每週更新流程

1. 新週報新增為 `weekly/week-XX.html`。
2. 最新週報內容同步到 `weekly/index.html` 的第一筆。
3. 根目錄首頁的「最新每週檢討」改成新週數字與連結。
4. 舊週報保留原檔，不覆蓋，作為管理歷史。

## GitHub Pages設定

在 repository 的 `Settings` → `Pages`：

- Source：`Deploy from a branch`
- Branch：`main`
- Folder：`/(root)`

## iPhone使用

Safari開啟GitHub Pages網址後，點「分享」→「加入主畫面」。首頁已設定手機安全邊距與44px以上主要點擊區域。

## 隱私提醒

一般 GitHub Pages 應視為公開網站。`noindex`與`robots.txt`只要求搜尋引擎不要收錄，不是密碼保護。不要上傳車牌、個人電話、銀行帳號或其他不應公開的資料。
