# 大二影展專題：《半畝方糖》網頁專案

本專案為逢甲大學行銷學系大二影展專題介紹網頁，聚焦臺中東區「帝國製糖廠臺中營業所與星泉湖畔」，透過「出站即達的都市慢活文化綠洲」的核心定位，翻轉大眾長期以來對歷史古蹟老舊、無聊的刻板印象。

## 專案功能特色
- **SEO 最佳化**：包含完整的 Meta 標籤、Open Graph 社交協議與語意化 HTML5 標記。
- **RWD 響應式佈局**：支援手機、平板與桌上型電腦，影片採 16:9 自適應縮放與響應網格。
- **CSS 模組化與網格系統**：實作糖廠深綠色（`#2C5E3B`）與復古木質調（`#F5F2EB`）之雙欄側邊導覽與卡片網格。
- **檔案模組化切割**：CSS 樣式表獨立抽離至 `css/` 資料夾中（包含 `layout.css`、`components.css` 與 `responsive.css`）。
- **多分頁互動架構**：劃分專題首頁 (`index.html`)、完整企劃章節與影展短片欣賞。

---

## Vibe Coding 指令紀錄 (Prompts Log)

本專案運用 Vibe Coding 模式，透過明確架構、情緒調性與技術邊界進行人機協同開發。以下為生成此專案的核心提示詞紀錄：

### Prompt 1：專案架構與基礎骨幹建立
> **Prompt:**  
> 「請扮演資深前端工程師與數位行銷策展人。我正在製作大二影展專題介紹網頁，主題是針對臺中帝國糖廠與星泉湖的短片企劃《半畝方糖》。  
> 請幫我規劃一個現代化靜態網站。  
> 規範要求：  
> 1. 具備頂端導覽列與側邊選單欄。  
> 2. 具有完整的 SEO Meta 標籤（含 Title, Description, Keywords, Open Graph）。  
> 3. 需將樣式抽離至獨立的 `css/` 資料夾中，採用語意化 HTML5 標籤。」

### Prompt 2：CSS Grid 系統與 RWD 跨裝置適配
> **Prompt:**  
> 「請為上述影展專案撰寫完整的 CSS 樣式表。需採用『糖廠綠 (#2C5E3B)』與『黃銅金 (#C69C6D)』為主色調，營造復古質感。版面採用雙欄 Grid 結構，並設定響應式排版與 16:9 比例自適應影片容器，支援行動裝置自動摺疊與單欄轉場。」

### Prompt 3：互動分頁修正與首頁 Hero Banner 視覺優化
> **Prompt:**  
> 「請在 JavaScript 中加入 `event.preventDefault()` 以解決點擊選單時頁面跳動與重複顯示的問題。同時在首頁加入吸睛的 Hero Banner 視覺大封面與三大亮點卡片，讓整體網頁具備專業影展官網水準。」

### Prompt 4：GitHub 部署與 CSS 路徑除錯
> **Prompt:**  
> 「請協助檢查 GitHub 與 Vercel 部署時的資料夾結構，確保 `css/` 資料夾內的 `layout.css`、`components.css` 與 `responsive.css` 路徑完全正確，解決本機端與雲端伺服器的大小寫及路徑對應問題，讓網頁完美呈現復古木質調。」

---

## 專案部署連結

1. **Prompt 說明檔 (GitHub README)**：  
   `https://github.com/jianyouxin-ux/` *(請填入妳們實際的 GitHub 專案網址)*
2. **Vercel 部署網址**：  
   `https://715-jianyouxin8-7536.vercel.app`
