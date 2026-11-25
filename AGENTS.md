# General development instructions

## Scope

本 Repo 是共用開發知識入口，不是各專案的程式碼所在地。進入目標 Repo 後讀取其 AGENTS.md 與適用的情境規則。不可假設跨 Repo 規則會由 Agent 自動載入。

## Working rules

- Minimal change：保持既有風格、避免無關重構、一次性抽象及不必要依賴。
- 先定義可驗證的成功準則；需求不明時先問影響設計的問題。
- 優先複用既有實作、測試及 Issue；新增功能採可觀察行為的 TDD。
- 不移除不相關的既有程式碼；不覆蓋他人變更。
- 區分已驗證、未驗證及失敗；附上實際命令、測試結果與限制，不捏造證據。
- 破壞性操作、正式環境修改、權限擴張與未授權部署需另行核准。
- 不將秘密、憑證、敏感資料或真實使用者資料寫入 Git、日誌或外部工具。

## Context pointers

- 需求釐清、拆票、實作與驗收： [workflows/development.md](workflows/development.md)
- 選用 Matt Pocock Skills： [skills/README.md](skills/README.md)
- 多專案管理、派工及交接： [workflows/project-coordination.md](workflows/project-coordination.md)

依任務讀取必要文件，不載入全部知識。受管制情境的更嚴格安全規則優先；文件無法取代實際權限隔離。
