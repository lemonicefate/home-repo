# Project coordination

- Project Registry：專案名稱、repository、生命週期與工作情境的導航來源。不要在 Home Repo 複製即時進度。
- GitHub Issues / Projects / PR：實際任務、狀態、驗收證據與決策紀錄的主要來源。
- Coding Lead：定義成功準則、拆分互不衝突的工作、檢查結果及整合；子 Agent 回報 commit、測試、風險與阻塞。
- 派工應明確指定目標 repository、分支、可修改範圍、驗收條件及安全停止點。
- 若使用多 Agent 工作區，優先透過工作區原生功能讀取子 Agent 結果，避免將大量中間輸出塞入主對話。
- 長時間自主執行仍須遵守權限、核准與資料隔離；不得繞過人工介入點。

情境欄位可由 Registry 或啟動器明確指定通用或專用 Home Repo，但必須先確認工具真的支援該欄位；不要假設原生自動路由。
