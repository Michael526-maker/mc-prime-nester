# mc-prime-nester

PrimeNester Studio — UV 平板混拼、AI 打印生成、iPad 外殼貼紙工具。

## 推薦流程（簡單）

1. 將**對手產品渲染圖**放入 [`references/`](./references/)（或喺網頁直接上傳）
2. 打開 [`ai-print.html`](./ai-print.html) **AI 打印工作室** → 一鍵生成**直向打印稿**
3. 下載後丟去 [`index.html`](./index.html) 拼版 Studio 排產
4. **自家渲染程式**稍後再單獨做（唔再依賴透視展開）

## 模組

| 頁面 | 用途 |
|------|------|
| [`ai-print.html`](./ai-print.html) | **主推** · 對手參考圖 → 智能／AI 生成打印稿 |
| [`index.html`](./index.html) | UV 平板印刷拼版、塗層解析、生產 PDF / AI JSX |
| [`skin-designer.html`](./skin-designer.html) | 進階 · 透視雙向設計器（可選） |
| [`references/`](./references/) | 放置對手渲染圖 |
| [`prints/`](./prints/) | 打印稿輸出位置說明 |

## AI 打印工作室

- **智能提取（免 API）**：由參考圖中心裁出直向圖案，套上機型刀線／相機開孔
- **AI 重繪（可選）**：喺頁面「AI 設定」填入 Hugging Face Token 後重繪打印圖

機型模板：iPad Pro 13/11、Air 13/11、mini（全部直向）。
