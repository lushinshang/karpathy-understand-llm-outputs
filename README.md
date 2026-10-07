# 一萬行程式碼，一個人來看

Karpathy 在 2026-10-02 的 X 貼文中，提出一個四級「看懂 LLM 輸出」的階梯：寫作（ASD-STE100）、圖表、網頁（HTML）、解說影片。本篇導讀把這則貼文，與他 2025 年 6 月在 Y Combinator 演講中「一萬行 diff，人仍是瓶頸」的說法並排閱讀，並引用 ASD-STE100 維護單位（STEMG）2026 年 6 月白皮書的提醒：看起來清楚，不等於經過驗證。

## 200字介紹

Karpathy 在 2026 年 10 月 2 日的 X 貼文裡說，我們會花愈來愈多時間去理解語言模型的輸出，並提出四層階梯：請 LLM 用 ASD-STE100 寫作、做圖表、輸出 HTML 網頁、做解說影片，愈往上愈好讀。這篇導讀以貼文為主角，並排他 2025 年在 Y Combinator 談「一萬行 diff，人仍是瓶頸」的說法，也交代這套航空維修受控語言的來歷。ASD-STE100 的維護單位 STEMG 在 2026 年 6 月的白皮書提醒：AI 產生的文字看起來清楚，不等於已驗證合規。本文把這個提醒延伸到後面三層，並標明哪些是本文的類推，最後整理三種實際用法與各自依據。

線上閱讀：https://lushinshang.github.io/karpathy-understand-llm-outputs/

## 檔案說明

| 路徑 | 說明 |
|------|------|
|  | 單檔 HTML，CSS／JS 內嵌，可直接用瀏覽器開啟 |
|  | 導讀 Markdown 原稿（含 YAML frontmatter 與來源清單） |
| 、 | 四層階梯示意圖（桌面／手機） |
| 、 | 頁首總覽圖（桌面／手機） |

## 原始資料

| 類型 | 名稱 | 網址 |
|------|------|------|
| 社群貼文（主角） | Andrej Karpathy 在 X 的貼文（2026-10-02） | https://x.com/karpathy/status/2105819303471976479 |
| 演講影片 | Andrej Karpathy, Software Is Changing (Again)（Y Combinator AI Startup School，2025 年 6 月） | https://www.youtube.com/watch?v=LCEmiRjPEtQ |
| 官方網站與文件 | ASD-STE100 官方網站與 STEMG 白皮書（2026 年 6 月） | https://www.asd-ste100.org/ |

原始逐字稿位置：不適用（來源為 X 貼文與影片，未保存逐字稿）。

## 最重要的官方與第一手來源

- Karpathy X 貼文（第一手）：https://x.com/karpathy/status/2105819303471976479
- Karpathy YC 演講（第一手）：https://www.youtube.com/watch?v=LCEmiRjPEtQ
- ASD-STE100 官方網站（STEMG）：https://www.asd-ste100.org/
- About STE（沿革、53 條規則、約 900／約 1,200 字、Issue 9）：https://www.asd-ste100.org/about_STE.html
- FAQ（1979 年起因）：https://www.asd-ste100.org/STE_faq.html
- Downloads（白皮書摘要、Issue 9 申請）：https://www.asd-ste100.org/STE_downloads.html
- STEMG 白皮書 ASD-STE100 Simplified Technical English and Artificial Intelligence（2026 年 6 月，文件自署）：https://www.asd-ste100.org/assets/files/WhitePaper-ASD-STE100_and_AI.pdf
- Chervak, Drury & Ouellette (1996)，Simplified English for aircraft workcards（補充研究）：https://researchconnect.buffalo.edu/en/publications/simplified-english-for-aircraft-workcards/

近一週的二手評論（FourWeekMBA、gu-log、max.nardit.com）僅作佐證與對照，完整清單見文章末尾「來源」。
