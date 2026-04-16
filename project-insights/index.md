# Project Insights Index

> 最後更新：2026-04-15
> 說明：本索引整理各專案目前階段、對外發表成熟度、主要阻塞與知識庫檔案位置，供 PM / RD / 管理者快速掌握狀態。

| 專案 | 目前階段 | 對外發表成熟度 | 最後更新 | 主要阻塞 | 檔案 |
|---|---|---|---|---|---|
| RoboticSuite | 第一版 released 後整合中 | Internal Only（接近 Soft Launch Ready） | 2026-04-10 | 客戶導向敘事、設備介接規範、Simulation/Finetuning 產品化表達仍不足 | `roboticsuite.md` |
| DeviceOn | 功能擴充與智慧化驗證中 | Soft Launch Ready | 2026-04-10 | AI 助手 memory 穩定性、CVE/預測功能未完成 | `deviceon.md` |
| 龍蝦（RAG 個人記憶助手） | 助理化方向重定義中 | Internal Only | 2026-04-10 | 與 RAG 的角色分工、session continuity、助理定位需再清楚 | `lobster-rag-assistant.md` |
| OpenClaw 會議記錄 Skill | 可用原型，邁向產品化 | Soft Launch Ready | 2026-04-10 | 正確性、語者對齊、人工校對節點、initial setup 流程 | `openclaw-meeting-skill.md` |

## 閱讀建議
- 想看機器人相關主線：先看 `roboticsuite.md`
- 想看智慧維運 / DeviceOn 助手：看 `deviceon.md`
- 想看 RAG / 記憶型助理定位：看 `lobster-rag-assistant.md`
- 想看會議錄音 → 逐字稿 → PM 助理化流程：看 `openclaw-meeting-skill.md`

## 固定歸檔連結
可直接打開原始逐字稿與會議內容檔案，用於追溯與外部知識工具餵料。

- **2026-03-20**
  - 逐字稿：`/meeting-archives/2026-03-20_BiWeeklyReport_逐字稿.txt`
  - 會議內容：`/meeting-archives/2026-03-20_BiWeeklyReport_會議內容.txt`
- **2026-04-10**
  - 逐字稿：`/meeting-archives/2026-04-10_BiWeeklyReport_逐字稿.txt`
  - 會議內容：`/meeting-archives/2026-04-10_BiWeeklyReport_會議內容.txt`

## 更新原則
- 每次新會議進來，先判斷涉及哪些專案
- 更新對應專案檔，而不是重寫新的單次摘要
- 所有重要技術與商務敘事都盡量附日期來源
