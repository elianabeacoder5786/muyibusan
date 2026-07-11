# 🍁 木易 TRIP｜釜山旅遊行程

三人行釜山深度旅遊行程網頁，2025.10.24 – 11.01（9天8夜）。
內含逐日行程、時間軸、Naver Map 韓文地名快速查表（可點擊複製），適合手機瀏覽使用。

## 🔗 線上瀏覽

部署完成後，網址會是：

```
https://<你的GitHub帳號>.github.io/<repo名稱>/
```

（依照下方步驟設定 GitHub Pages 後，把網址貼在這裡方便之後直接打開）

## 🚀 用 GitHub Pages 發布步驟

### 1. 建立 Repository
1. 登入 [GitHub](https://github.com)，右上角點 **+** → **New repository**
2. Repository name 自訂，例如 `busan-trip-2025`
3. 選擇 **Public**（GitHub Pages 免費方案僅支援公開儲存庫）
4. 不用勾選 "Add a README file"（我們自己上傳）
5. 點 **Create repository**

### 2. 上傳檔案
把這個資料夾裡的檔案上傳到剛建立的 repo：

- **網頁瀏覽器操作**：進到 repo 頁面 → 點 **Add file** → **Upload files** → 把 `index.html` 和 `README.md` 拖進去 → **Commit changes**
- **或用 Git 指令**：
  ```bash
  git init
  git add index.html README.md
  git commit -m "釜山行程網頁"
  git branch -M main
  git remote add origin https://github.com/<你的帳號>/<repo名稱>.git
  git push -u origin main
  ```

> ⚠️ 重要：檔案名稱建議改成 `index.html`（GitHub Pages 預設會直接開啟這個檔案），這樣網址才會乾淨，不用加檔名。

### 3. 開啟 GitHub Pages
1. 進到 repo 的 **Settings**
2. 左側選單找到 **Pages**
3. 在 **Build and deployment** → **Source** 選擇 **Deploy from a branch**
4. **Branch** 選擇 `main`，資料夾選 `/ (root)`
5. 點 **Save**
6. 等待約 1–2 分鐘，重新整理頁面，上方會出現一個綠色網址（格式如 `https://<帳號>.github.io/<repo名稱>/`）

### 4. 完成 🎉
打開該網址，就能在手機或電腦上直接看到行程網頁，之後也可以直接分享這個連結給同行的朋友。

## 🔄 之後想修改行程內容怎麼辦？

- 直接在 GitHub 網頁上點進 `index.html` → 點右上角鉛筆圖示 **Edit** → 修改後 **Commit changes**
- 存檔後，GitHub Pages 網站約 1 分鐘內會自動更新，不用重新部署

## 📱 使用小提醒

- 建議加到手機主畫面（iOS：Safari 開啟網址 → 分享 → 加入主畫面），開起來就像 App 一樣方便
- Naver Map 查表區塊點一下地名可直接複製韓文，貼到 Naver Map App 搜尋即可查路線
- 此網頁純前端 HTML/CSS/JS，不需要任何後端或資料庫，GitHub Pages 免費方案即可長期使用

## 📄 檔案結構

```
.
├── index.html   # 行程網頁主檔案（原檔名：木易TRIP_釜山行程.html）
└── README.md    # 本說明文件
```
