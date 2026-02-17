# 📺 YouTube 封面抓取工具

一個現代化、高效能的網頁工具，可立即抓取並下載多種解析度的 YouTube 影片封面圖。採用流暢的磨砂玻璃 (Glassmorphism) 介面設計並針對速度進行了優化。

[English Version](./readme.md)

---

## ✨ 功能特點

* **多解析度支援**：自動獲取超高清 (MaxRes)、高清 (SD)、標準 (HQ) 及普通 (MQ) 畫質。
* **智慧解析**：內建 URL 解析器，支援各種 YouTube 連結格式。
* **現代化 UI**：使用 Tailwind CSS 與 Inter 字體打造精美的磨砂玻璃風格介面。
* **雙語支援**：自動偵測使用者瀏覽器語系（英文/中文）。
* **一鍵下載**：使用 Blob URL 技術實現直接下載功能。
* **動態連結**：支援 URL Hash 碎片，可直接分享特定影片的抓取結果。

## 🚀 技術棧

* **前端**: HTML5, Tailwind CSS
* **字體**: Google Fonts (Inter & Noto Sans TC)
* **圖標**: Heroicons (SVG)
* **邏輯**: 原生 JavaScript (ES6+)

## 🛠️ 使用說明

1.  **貼上網址**：複製 YouTube 影片網址（例如：`https://www.youtube.com/watch?v=...`）。
2.  **獲取**：點擊 **「獲取封面」** 按鈕或按下 Enter 鍵。
3.  **預覽**：查看可用的解析度及其具體尺寸（如 1280x720）。
4.  **下載**：點擊任何封面卡片即可將圖片儲存至您的裝置。

## 📦 安裝與部署

由於這是一個純前端工具，您可以直接在瀏覽器中打開 `index.html`，或將其部署至 GitHub Pages、Vercel 或 Netlify。

```bash
git clone [https://github.com/yourusername/yt-thumbnail-downloader.git](https://github.com/yourusername/yt-thumbnail-downloader.git)
cd yt-thumbnail-downloader
# 在瀏覽器中開啟 index.html

```

## 📄 開源授權

本專案採用 [MIT License]() 授權。
