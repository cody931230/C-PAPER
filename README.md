# LLM 研究 Wiki

個人 LLM 研究知識庫，依循 Karpathy 的 LLM Wiki 模式：由 LLM 持續維護一組互相連結的 markdown 頁面，而不是每次都從原始文件重新檢索。

## 使用方式

1. 把來源放入 `raw/`（論文放 `raw/papers/`、文章放 `raw/articles/` 等）。**原始檔不要修改。**
2. 請 Agent 讀取 `AGENTS.md`，然後說「ingest `raw/...`」。
3. 用 Obsidian 開啟本資料夾，從 `wiki/index.md` 或 `wiki/overview.md` 開始瀏覽。

## 規範

所有維運規則見 [`AGENTS.md`](AGENTS.md)。

## 建議工具

- **Obsidian**：瀏覽 wiki 與 Graph View
- **Obsidian Web Clipper**：把網路文章存成 markdown
- **Git**：整個資料夾可以是一個 git repo，享有版本紀錄
