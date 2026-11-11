# mc-prime-nester

PrimeNester Studio — UV 平板混拼與 iPad 外殼貼紙雙向設計器。

## 模組

| 頁面 | 用途 |
|------|------|
| [`index.html`](./index.html) | UV 平板印刷拼版、塗層解析、生產 PDF / AI JSX 導出 |
| [`skin-designer.html`](./skin-designer.html) | iPad 外殼貼紙雙向設計器（打印圖案 ↔ 產品渲染） |

## Skin Designer 雙向流程

1. **打印圖案 → 渲染圖**：上傳平面圖稿／相片，透視貼到 iPad 外殼預覽（可拖曳四角校正）。
2. **渲染圖 → 打印檔**：上傳現有產品渲染圖，對齊四角後展開成可打印平面 PNG／1:1 PDF（含刀線預覽），再丟回拼版 Studio。

機型模板含 iPad Pro 13/11、Air 13/11、mini；可調出血、相機開孔挖空與網格品質。
