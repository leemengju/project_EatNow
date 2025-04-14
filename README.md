# 🛵 EatNow - 外送平台專案

這是一個以**外送平台**為主題，針對**都市上班族**這一核心 Persona，進行創意發想與功能開發的專案，目標是解決上班族在繁忙工作期間訂餐的痛點，並實現具有基本可用性的產品原型（MVP）。



## 🎯 專案目標

**EatNow** 致力於提升都市上班族的用餐效率，解決午餐選擇困難、訂單等待時間過長、付款流程繁瑣等問題。  
透過簡單直觀的頁面設計與模擬訂單流程，縮短點餐時間，提升用戶體驗。



## 🧑‍💼 Persona 分析

| 名稱           | 描述                                     |
|----------------|------------------------------------------|
|  目標用戶     | 都市上班族、時間有限、午餐高頻訂餐需求   |
| 使用場景     | 短時間內完成點餐，快速查看菜單與結帳     |
| 核心需求     | 1. 快速瀏覽餐點 2. 篩選餐點分類 3. 結帳流程簡單 |
| 使用設備     | 電腦 / 手機                               |



## 💡 核心特色

- **快速瀏覽餐點** — 分類篩選，減少選擇困難  
- **便捷結帳流程** — 最少點擊即可完成訂單  
- **跨裝置支援** — 響應式版面，適配不同螢幕  
- **模擬資料架構** — 使用 JSON 模擬後端，便於前端測試



## 🧑‍💻 技術架構

- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap 5**
- **JSON**（模擬餐點資料）



## 📦 專案架構 & 安裝說明

### 專案結構

```bash
project_EatNow/
│
├── resource/                      # 圖片與靜態資源
│
├── cover/                         # 簡報封面
│
├── A.Login_Page.html              # 登錄
├── B.Landing_Page.html            # 首頁
├── C.Restaurant_Page.html         # 餐廳頁
├── D.Order_Page.html              # 點餐頁
├── E.Cashier_Page.html            # 結帳頁
└── F.Deliver_Page.html            # 外送頁
```




###  前置需求

- 已安裝 [Visual Studio Code](https://code.visualstudio.com/)
- 安裝 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 擴充功能



##  安裝步驟

1️⃣ 複製專案至本地：
```bash
git clone https://github.com/leemengju/project_EatNow.git
```


2️⃣ 使用 VS Code 開啟專案資料夾：
```bash
code project_EatNow
```


##  啟動專案
注意： 本專案使用 JSON 模擬資料，必須透過本地伺服器啟動，否則瀏覽器會因CORS 限制導致資料無法讀取。

使用 Live Server 啟動方法：

在 VS Code 中，右鍵點擊 index.html

選擇「Open with Live Server」

預設網址：http://127.0.0.1:5500/index.html



## 功能說明
首頁：瀏覽外送餐點，按類別篩選，加入購物車。

餐廳頁：瀏覽不同合作餐廳的菜單資訊與評分。

點餐頁：檢視餐廳詳細菜單，選擇餐點加入購物車。

外送頁 / 結帳頁：查看選購清單，填寫外送地址與付款資訊，完成訂單結帳。

