# 智慧流程圖產生器 V1.9.5.2
Final Code Cleanup & UX Polish Edition

## 本版整理

依最終測試結果，移除重構後未再使用的死碼：

- `escRe`
- `lineInfo`
- `parseStepText`
- `historyArmTimer`
- `armHistoryBeforeEdit`
- `serializedSvg`
- `flowBackgroundColor`

這些程式沒有任何呼叫端，移除不會改變既有功能。

## 多頁 PDF 文案調整

若使用「自動多頁」模式，但目前內容實際只需要 1 頁，
現在會顯示：

`自動多頁模式・目前 1 頁（內容可容納於單頁）`

避免使用者誤以為多頁模式沒有生效。

## 保留

- 11 組流程範例
- 輸出預覽
- SVG / PNG / JSON / PDF
- 單頁 / 多頁 PDF
- 左側工具收合
- 左側獨立捲軸
- 右側原始預覽設計
- 節點雙擊編輯
- 拖曳 / 縮放 / 鎖定 / 防重疊
- Undo / Redo
- 自動儲存與恢復
- 流程圖及所有輸出固定純白底
- GitHub Pages 可部署
