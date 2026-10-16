# 數位易經 · 三數起卦（優化版 v2.1）

用三個數字起卦的易經占卜工具。

**線上使用**：https://kftseng2oo1.github.io/digital-ichen/

## 主要功能
- 八大類別：事業、健康、愛情、婚姻、財運、投資、官司、購屋
- 輸入三個數字起卦，顯示卦名、動爻爻辭、運勢分數與詳細指引
- 占卜紀錄、分享結果、📖 內建使用說明

## 檔案說明
- `index.html`：完整的 App（PWA 入口）
- `數位易經_優化版_v2.1.html`：原始完整版，與 index.html 內容相同，可刪除
- `manifest.json`、`sw.js`、`offline.html`、圖示：PWA 安裝與離線用

## 備註
2026-10 修復：原 `index.html` 打包時被截斷、沒有任何 JavaScript；已改用 v2.1 重建並保留 PWA 設定（見 PR #2）。

## 起卦原理
- 第一數 ÷ 8 取餘數 → 上卦
- 第二數 ÷ 8 取餘數 → 下卦
- 三數相加 ÷ 6 取餘數 → 動爻

## 相關 repo
- [gold](https://github.com/kftseng2oo1/gold)、[DE2.3](https://github.com/kftseng2oo1/DE2.3)、[-_-_v2-1](https://github.com/kftseng2oo1/-_-_v2-1)：同系列的其他版本
- [gamei](https://github.com/kftseng2oo1/gamei)：六十四卦學習遊戲
