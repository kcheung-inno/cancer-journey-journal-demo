# 致謝與著作歸屬

## 建立者

**Ken Cheung** — 概念、臨床內容設計、介面規格、驗收
© 2026 Ken Cheung. All rights reserved.

## 本專案的原創部分

- 症狀知識庫：症狀清單、三分類架構、每個症狀的**四級「病人語言」分級描述**、
  中文同義詞對照
- 自由文本解析：同義詞比對、否定偵測、強度詞與數值擷取、同病灶去重、
  病人可覆寫機制
- 急症規則：腫瘤科與心理急症的多線索組合規則與三級分流（立即／24 小時／門診）
- 情緒篩檢流程：觸發條件、溫和邀請、計分與摘要呈現
- 回診摘要結構：紅旗置頂 → 心理狀態 → 症狀表 → 功能狀態 → 病人原話 → 未提及
- 介面設計與圖示（圖示以程式繪製，為原創圖形）

示範版僅收錄其中一部分（18 個症狀、4 條急症規則）；完整版為私有。

## 臨床知識的來源

本專案的臨床內容是**依公開標準重新撰寫**，不是任何機構的官方產品：

- **CTCAE v5.0**（Common Terminology Criteria for Adverse Events, U.S. National
  Cancer Institute, 2017）— 引用 1–4 級的分級概念與 adverse event 英文名稱。
  病人語言的級別描述為自行撰寫，非 NCI 原文翻譯。
  CTCAE 為美國政府著作，於美國境內不受著作權保護；NCI 請求使用時標註來源。
- **PRO-CTCAE**（U.S. NCI）— 借用「症狀 ＋ 屬性（嚴重度／頻率／干擾）」的提問結構。
- **PHQ-2 / PHQ-9**（Kroenke, Spitzer, Williams；2001、2003）— PHQ 系列可自由使用，
  本專案使用中文改寫版，非官方驗證翻譯。
- **GAD-2 / GAD-7**（Spitzer, Kroenke, Williams, Löwe；2006、2007）— 同上。
- **ECOG performance status**（Oken et al., 1982）— 由病人自評活動量推估，
  非正式 ECOG 評估。

## 工具

介面以原生 HTML／CSS／JavaScript 撰寫，未使用前端框架、UI 元件庫或外部字型。
示範檔經壓縮後發布；完整版之原始碼為私有。

## 商標

「CTCAE」、「PRO-CTCAE」、「Google Play」、「Android」為其各自權利人之商標，
本專案僅作描述性使用。本專案與 U.S. NCI、Pfizer、Google 均無隸屬、贊助或
背書關係。
