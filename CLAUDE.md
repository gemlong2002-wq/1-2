# CLAUDE.md — 1-2 公積金記帳本

## 專案型態
純 HTML 單檔前端（React + Babel standalone + Tailwind CDN），
GitHub Pages 靜態站，後端為獨立 GAS Web App（不在本 repo）。

## 執行紅線（強制）
- 不得 push main（一律由 Boss 本人 push）
- 不得改動 token / 驗證相關程式碼，除非該次任務明確要求
- 不得動後端 Code.gs（不在本 repo，也不從這裡改）
- 改 schema / 資料結構前必須先問

## 版本紀律
- 每次改動 index.html 並 commit，必須同步更新 index.html 內的
  APP_VERSION 常數為該次 commit 的日期時間（格式 YYYY/MM/DD HH:MM）。
- 漏更新會導致畫面顯示錯誤版本，比沒有版本時間更糟。
