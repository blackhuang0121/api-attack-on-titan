# api-attack-on-titan
Use API get to acquire information of characters of Attack on Titan.
本專案是透過 JavaScript 拉取 Attack on Titan API 的資料，動態生成角色卡片，顯示於網頁上。

## 🧠 使用技術

- HTML / CSS / JavaScript
- Live Server（本地預覽）
- Fetch API（抓取遠端資料）
- API 來源：[attackontitanapi.com](https://www.attackontitanapi.com/)

## 📂 專案結構
📁 titan-card-project/
├── index.html # 主頁面
├── style.css # 樣式檔
├── script.js # 拉 API + DOM 組件
└── README.md # 本說明文件

## 🚀 使用方式

1. clone 此專案
2. 用 VS Code 開啟資料夾
3. 安裝 Live Server 擴充功能
4. 在 `index.html` 上按右鍵 → Open with Live Server

## ✍️ 筆記

- 透過 `fetch()` 從 API 抓資料後，用 `.forEach()` 把每筆資料做成卡片
- 用 `innerHTML` 產生每張卡片內容
- 學會 CORS 與 `http://localhost` 執行的差異
