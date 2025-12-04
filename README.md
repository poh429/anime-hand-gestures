# anime-hand-gestures

🖐️ AI Anime Hand Gestures (咒術迴戰 & 一拳超人特效)

這是一個基於 Web 的 AI 手勢識別應用程式，完全在瀏覽器端運行（Client-side）。使用 Google MediaPipe 技術實時偵測手部骨架，並根據特定的手勢觸發《咒術迴戰》與《一拳超人》的視覺特效。

🎮 功能與手勢 (Features)

本應用程式支援一般手指計數 (1-10)，並包含以下特殊招式：

1. 虛式「紫」 (Hollow Purple)

來源：《咒術迴戰》五條悟

手勢：🖕 中指 (Middle Finger)

觸發條件：僅伸出中指，其他手指收起。

特效：畫面轉為紫色氛圍，指尖匯聚高能量紫色光球與閃電。

2. 術式反轉「赫」 (Red)

來源：《咒術迴戰》五條悟

手勢：🤘 搖滾手勢 (Metal / Horns)

觸發條件：伸出食指與小指，中指與無名指收起（支援寬鬆判定）。

特效：畫面轉為紅色警戒色，掌心爆發紅色斥力衝擊波。

3. 領域展開「無量空處」 (Unlimited Void)

來源：《咒術迴戰》五條悟

手勢：🤞 手指交叉 (Crossed Fingers)

觸發條件：食指與中指伸直並交叉（或緊貼），其他手指收起。

特效：畫面反白高對比，背景轉為宇宙星空，展現資訊過載的視覺效果。

4. 必殺・認真毆打 (Serious Punch)

來源：《一拳超人》埼玉

手勢：👊 握拳 (Fist)

觸發條件：所有手指彎曲收起。

特效：強烈的紅黃色衝擊波背景，伴隨劇烈的畫面震動與速度線。

🛠️ 技術棧 (Tech Stack)

HTML5 & Canvas API：核心繪圖與畫面處理。

Google MediaPipe Hands：高精度的手部骨架偵測模型。

Tailwind CSS：UI 樣式與響應式設計。

JavaScript (ES6+)：邏輯判斷與粒子特效繪製。

🚀 如何執行 (How to Run)

由於本專案是單一 HTML 檔案，您有多種方式運行：

方法 A：線上體驗 (GitHub Pages)

點擊這裡前往 demo 頁面

方法 B：本地運行

下載 index.html 檔案。

直接使用瀏覽器（Chrome, Edge, Safari 等）打開該檔案即可。

請允許瀏覽器使用攝像頭權限。

https://poh429.github.io/anime-hand-gestures/

MIT License

注意：本專案僅供學習與娛樂用途，特效靈感來自相關動漫作品。
