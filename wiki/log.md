# 操作日誌（只追加，不得刪改既有紀錄）

格式：`## [YYYY-MM-DD] 類型 | 摘要`，類型為 `ingest` / `query` / `lint` / `schema`。
取最近 5 筆：`grep "^## \[" wiki/log.md | tail -5`

---

## [2026-11-10] schema | 建立知識庫結構
- 建立 `AGENTS.md`（維運規範）
- 建立 `raw/` 原始來源目錄與 `wiki/` 知識庫目錄
- 建立 `wiki/index.md`、`wiki/log.md`、`wiki/overview.md`
