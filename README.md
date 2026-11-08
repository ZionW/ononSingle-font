# ononSingle

以 Google Fonts Noto Sans TC 衍生的 Rhino 單線字型，包含繁體中文、英文字母、數字及符號。

![Rhino 9 中英文數字符號測試畫面](Rhino9-測試截圖.png)

畫面中的曲線為 ononSingle 方框修正試版在 Rhino 9 的輸出。

## 使用方法

安裝 `ononSingle.ttf` 並重新啟動 Rhino。使用 **TextObject（文字方塊）**，選擇 ononSingle、輸出「曲線」並勾選「雕刻字體」。一般使用不需要 Python；輸出是曲線，不能以可編輯文字工具修改。

## 本版測試及限制

這次修正了「木」字筆畫，以及 374 個字形中 490 處與 Google 原字形比對後疑似缺角的方框。截圖為 Rhino 9 的方框修正試版，包含中英文、數字與符號；此畫面測試文件共 719 條有效曲線。字型名稱於測試後改回 ononSingle，字形內容相同。

全字型自動結構掃描涵蓋 20,299 個非空字形與 231,468 個輪廓，字元對應與 Google 原始字型一致。未發現零長度輪廓、相鄰重複線上點或微小折返；仍有 177 個符合特定形狀的三角形候選輪廓待人工判斷，詳見 [font-audit.json](font-audit.json)。這些檢查不代表已逐字確認筆畫完整或筆順正確。

這是試用版：尚未逐字檢視全部方框，也尚未全面修順撇、捺交會處或逐字核對筆順。Mac Rhino 的部分曲線方向可能反轉；加工軟體也可能重新排列刀路。

## 授權

原始字型來自 [Google Fonts Noto Sans TC](https://github.com/google/fonts/tree/main/ofl/notosanstc)。本字型為衍生作品，非 Google 官方產品；依 SIL Open Font License 1.1 發布，版權及授權聲明見 [OFL.txt](OFL.txt)。
