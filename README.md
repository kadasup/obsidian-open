# obsidian-open

一頁式跳板：把 `https://` 連結轉成 `obsidian://open`，讓不放行自訂協定的 App（例如 Claude 桌面版）也能一鍵開啟 Obsidian 筆記，開完自動關閉分頁。

## 用法

```
https://kadasup.github.io/obsidian-open/#<vault 內相對路徑，不含 .md>
```

例：`https://kadasup.github.io/obsidian-open/#筆記草稿/2026-09-11 照片整理與去重方案`

- 預設 vault 是 `secondbrain`；要換 vault 加 `?vault=名稱`
- 筆記路徑放在 `#` 之後，**只留在瀏覽器、不會送到 GitHub**
- 瀏覽器第一次會問「要開啟 Obsidian 嗎」，勾「一律允許」之後就不再問
- Chrome／Edge 會自動關閉跳板分頁；Firefox 不允許腳本關分頁，會留一句提示

本 repo 只有這一頁靜態 HTML，不含任何筆記內容。
