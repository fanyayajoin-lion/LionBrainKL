# 🦁 群獅知識庫 v4

> 傳產翻譯機 — 知識萃取與管理系統

## 架構

\`\`\`
Telegram Bot → AI 萃取 → GitHub (LionBrainKL) → Obsidian (本地同步)
\`\`\`

## 快速開始

1. **Obsidian 安裝**：下載 https://obsidian.md
2. **開啟 Vault**：指向 `LionBrainKL` 的本地 clone
3. **Git 同步**：
   \`\`\`bash
   git clone https://github.com/fanyayajoin-lion/LionBrainKL.git
   \`\`\`
4. **Telegram Bot**：@Lionkingclaw_bot — 直接發想法

## 目錄說明

- `00_Raw/` — 原始輸入（Bot 自動存放）
- `01_Concepts/` — 核心概念（萃取後）
- `04_Daily/` — 每日筆記
- `05_Weekly/` — 每週回顧
- `06_Reflection/` — 反思提問

## Cron 任務

- 🌅 **晨報**（08:00）— 每日新聞摘要
- 🌙 **夜間 Q&A**（23:00）— 反思提問
- 📊 **週報**（週日）— 每週回顧

## 相關資源

- [SCHEMA.md](SCHEMA.md) — 完整規範
- [Templates/](Templates/) — 頁面模板
