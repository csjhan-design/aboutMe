🌻 智慧桃園 桃園智慧 — 詹老師個人品牌網站（社區樂活親切版）

「不用背英文、不用記複雜步驟，用講話就能操作、一學就會！」

專為桃園在地社區大哥大姐、婆婆媽媽、里辦公處、社區發展協會與樂齡學堂量身打造的 AI 生活應用講師個人品牌網站。

📖 專案簡介 (Overview)

本專案為「智慧桃園 桃園智慧 詹老師」之官方個人品牌與教學作品集網站。

一改傳統科技網站冰冷的黑底與艱澀術語，採用「暖陽樂活・護眼高對比」的無障礙使用者體驗（Senior-Friendly UX）設計，讓社區長輩與合作單位能輕鬆閱讀、實際體驗 AI 提示詞（Prompt），並快速透過 LINE 或臉書聯繫開課邀約。

✨ 核心功能與設計亮點 (Key Features)

1. 👵 長輩友善無障礙體驗 (Senior-Friendly UX)

三段式一鍵字體放大鏡：頂部導覽列內建「標準 (16px) / 大字 (18px，預設) / 超大 (21px)」即時切換按鈕，全站採用 rem 相對單位，長輩閱讀不費眼力。

暖陽護眼配色：以柔和暖米白（#FFFBF5）為基底，搭配溫暖橘紅與安心翠綠高對比大按鈕，視覺溫暖不刺眼。

口語化貼心提示（Friendly Toast）：所有複製動作皆具備大字體動態彈出提醒，操作回饋清楚直覺。

2. 🗺️ 桃園在地精神視覺識別 (Custom GIS SVG Logo)

左上角品牌標誌採用真實經緯度比例繪製之「桃園市全境輪廓剪影 SVG」，並特別將「平鎮區」以亮黃色區塊突顯，展現道地桃園子弟深耕在地的精神。

3. 💡 互動式「AI 生活妙招點一點」專區

針對社區課堂最受歡迎的四大生活情境設計互動式體驗卡，並支援「一鍵複製示範問句」，可直接貼至 LINE 或 ChatGPT 體驗：

🌸 做專屬早安圖：出遊拍照自動撰寫溫暖祝福語

🍲 冰箱剩菜變大餐：拍照或口述食材自動生成少油健康食譜

🛡️ 防詐騙與看藥袋：可疑簡訊把關與醫療藥單翻譯

👨‍👩‍👧‍👦 做小遊戲陪金孫：透過自然語言對話設計祖孫同樂小遊戲

4. 🎮 實戰作品展示與自動網頁縮圖

整合 thum.io 自動網頁截圖服務與完整比例縮放（object-contain），並內建圖片載入失敗防呆機制（onerror fallback）：

🔥 三國赤壁連環火（休閒動腦網頁射擊遊戲）

線上體驗：https://csjhan-design.github.io/StoreMemoryMap/

🎁 好康優惠購物網（分類清晰的特惠資訊平台）

線上體驗：https://csjhan-design.github.io/dealsiteforfree/

5. 🏅 實務淬鍊時間軸 ＆ 專業認證專區

左欄（實務淬鍊與養成）：以直式時間軸（Vertical Timeline）整合工作經歷（電商倉儲物流、手機螢幕 ITO 品保、PCB 設備工程師）與學歷背景（淡江大學電機工程學系、中大壢中）。

右欄（專業培訓與認證）：清晰展示 NVIDIA 深度學習基礎原理與實踐（認證合格）、龍華科技大學 Vibe Coding 專班（結訓） 與 中原大學 Python 暨 AI 數據分析工作坊（結訓）。

6. 🤝 社區開課一鍵邀約系統

內建「一鍵複製開課邀約招呼語」功能，方便里長、社區幹部或民眾複製後直接點選「加老師 LINE 好友」貼上傳送。

🛠️ 技術架構 (Tech Stack)

本專案採 Single-File Architecture（單一檔案無相依架構），無須安裝 Node.js 或進行編譯打包，直接開啟或上傳即可運行：

結構：HTML5 Semantic Tags

樣式：Tailwind CSS (CDN) + 自訂暖陽主題變數

字型：Google Fonts - Noto Sans TC (思源黑體)

圖示：Font Awesome 6.4.0 + 客製化 SVG 向量地圖

自動縮圖服務：Thum.io Screenshot API

互動邏輯：原生 Vanilla JavaScript (ES6+)

🚀 快速啟動與部署教學 (Deployment Guide)

方式一：本機直接預覽

下載專案中的 index.html 檔案。

直接使用瀏覽器（Chrome / Safari / Edge）雙擊打開 index.html 即可完整瀏覽與互動。

方式二：免費部署至 GitHub Pages（推薦）

在您的 GitHub 建立一個新的公開儲存庫（Repository），例如命名為 personal-website（或 csjhan-design.github.io）。

將 index.html 與本 README.md 上傳至儲存庫根目錄。

進入該儲存庫的 Settings（設定） ➔ 左側選單點選 Pages。

在 Build and deployment 下方的 Branch 選擇 main（或 master），資料夾選擇 / (root)，點擊 Save。

等待約 1～2 分鐘，即可透過 GitHub 提供的網址全球連線瀏覽！

🔧 常見客製化修改指南 (Customization)

若未來需要新增作品或更新資訊，只需在 index.html 中搜尋對應關鍵字即可修改：

新增或修改「AI 生活妙招」內容：
搜尋 const lifeTipsData =，即可在 JavaScript 物件中修改標題 (title)、說明 (desc) 與示範問句 (prompt)。

更換作品網址與自動縮圖：
搜尋 https://image.thum.io/get/width/1024/，在後方換上您的新作品網址，系統便會自動抓取該網站的最新畫面作為縮圖。

更新個人照片：
搜尋 https://files.catbox.moe/clhtb0.png，替換為新的去背照片連結或本地圖片路徑（如 ./assets/profile.png）。

📞 聯絡詹老師 (Contact)

歡迎桃園各區里辦公處、社區發展協會、長青學苑、媽媽教室及學校企業洽詢 AI 課程與系統合作：

LINE ID：csjhan（點此直接加 LINE 好友）

Facebook 專頁：智慧桃園 桃園智慧 詹老師 FB

電子信箱：c.s.jhan@gmail.com
