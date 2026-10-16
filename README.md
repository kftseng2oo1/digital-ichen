# 數位易經 · 三數起卦（優化版 v2.1）

用三個數字起卦的易經占卜工具。

**線上使用**：https://kftseng2oo1.github.io/digital-ichen/

## 檔案說明
- `數位易經_優化版_v2.1.html`：**完整的 App**（約 330 KB，含全部卦象資料與程式）
- `index.html`：PWA 入口，但目前**只有畫面、沒有任何 JavaScript**，按「開始占卜」不會有反應
- `manifest.json`、`sw.js`、`offline.html`、圖示：PWA 安裝與離線用

## 已知問題
`index.html` 疑似打包時被截斷，只剩約 25 KB，和完整版差很多。修法：把 `數位易經_優化版_v2.1.html` 用 [autopack](https://github.com/kftseng2oo1/autopack) 重新打包，或直接把它的內容複製到 `index.html`（保留 manifest 與 SW 註冊）。

## 起卦原理
- 第一數 ÷ 8 取餘數 → 上卦
- 第二數 ÷ 8 取餘數 → 下卦
- 三數相加 ÷ 6 取餘數 → 動爻

## 相關 repo
- [gold](https://github.com/kftseng2oo1/gold)、[DE2.3](https://github.com/kftseng2oo1/DE2.3)、[-_-_v2-1](https://github.com/kftseng2oo1/-_-_v2-1)：同系列的其他版本
- [gamei](https://github.com/kftseng2oo1/gamei)：六十四卦學習遊戲
