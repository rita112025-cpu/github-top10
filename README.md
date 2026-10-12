# GitHub Top 10

以繁體中文整理的 GitHub 熱門開源專案精選頁，收錄 10 個值得關注的工具與資源，並依使用情境分成「任何人可用」與「Claude Code」兩類。

## 功能特色

- 瀏覽 10 個精選 GitHub 專案與簡介
- 依分類快速篩選專案
- 透過名稱、描述或標籤搜尋
- 一鍵複製各專案的 `git clone` 指令
- 響應式版面，支援桌面與行動裝置
- 單一 HTML 檔案，無須安裝套件或執行建置

## 開始使用

將專案複製到本機：

```bash
git clone https://github.com/rita112025-cpu/github-top10.git
cd github-top10
```

接著直接用瀏覽器開啟 `index.html` 即可。若希望透過本機伺服器預覽，也可以使用任何靜態檔案伺服器，例如：

```bash
python -m http.server 8000
```

開啟 <http://localhost:8000> 即可查看。

## 專案結構

```text
github-top10/
├── index.html  # 完整網站、樣式與互動邏輯
└── README.md   # 專案說明
```

## 技術說明

網站封裝於單一 `index.html`，包含：

- React 介面與互動邏輯
- Tailwind CSS 樣式
- 響應式設計
- Clipboard API 複製功能

## 更新內容

專案資料直接定義於 `index.html` 內。更新排行榜時，請同步確認專案名稱、GitHub 網址、描述、標籤及 clone 指令。

## 聲明

本專案僅整理並展示公開的開源專案資訊。各收錄專案的名稱、內容與授權皆歸原作者所有，實際資訊請以各專案的 GitHub 頁面為準。
