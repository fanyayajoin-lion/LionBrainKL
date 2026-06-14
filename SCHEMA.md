# 群獅知識庫 v4

## 目錄結構

| 目錄 | 用途 | 來源 |
|------|------|------|
| `00_Raw/` | 原始輸入，待分類 | Telegram Bot |
| `01_Concepts/` | 核心概念頁 | 萃取後 |
| `02_Ideas/` | 靈感與想法 | Telegram Bot |
| `03_Tasks/` | 任務與待辦 | Telegram Bot |
| `04_Daily/` | 每日筆記 | 每日回顧 |
| `05_Weekly/` | 每週回顧 | 每週 cron |
| `06_Reflection/` | 反思與提問 | 夜間 Q&A |
| `07_Projects/` | 專案檔案 | 專案管理 |
| `08_Archives/` | 歸檔 | 季度清理 |
| `Templates/` | 模板 | 參考 |

## Tag 系統

### 主題標籤
- `#ai` — AI 相關
- `#marketing` — 行銷
- `#digital-transformation` — 數位轉型
- `#brand` — 品牌
- `#finance` — 財務
- `#supply-chain` — 供應鏈
- `#business-model` — 商業模式

### 類型標籤
- `#concept` — 核心概念
- `#idea` — 靈感
- `#task` — 任務
- `#note` — 筆記
- `#question` — 問題
- `#reference` — 參考資料

### 狀態標籤
- `#draft` — 草稿
- `#review` — 待審核
- `#done` — 已完成
- `#archived` — 已歸檔

## 檔案命名規範
- 日期前綴：YYYYMMDD-HHMMSS
- 標題使用中文或英文
- 避免特殊字元（/, \, *, ?, ", <, >, |）
- 範例：`20260614-210000-AI數位轉型.md`

## 內容格式
所有檔案使用 YAML frontmatter + Markdown 格式：

\`\`\`yaml
---
type: concept|idea|task|note|question
title: 標題
tags: [tag1, tag2]
created: YYYY-MM-DDTHH:MM:SS
source: telegram|manual|cron
---
\`\`\`
