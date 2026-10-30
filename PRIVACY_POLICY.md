# 隱私權政策 — 療程日誌（Cancer Journey Journal）

**版本 1.2.1　·　生效日：2026 年 10 月 30 日**
**開發者：Ken Cheung**

本政策說明「療程日誌」（以下稱「本 App」）如何處理你的資料。摘要一句話：
**本 App 不收集、不上傳、不分享任何個人資料。**

---

## 一、我們不收集任何資料

本 App 沒有伺服器、沒有帳號系統、沒有分析工具（無 Google Analytics、
Firebase、Crashlytics 等）、沒有廣告 SDK、沒有任何追蹤器。

你輸入的所有內容——身體狀況描述、症狀分級、體力自評、步行時間、
情緒篩檢答案、稱呼與診斷欄位——**只儲存在你的裝置本機**，不會傳送給
開發者或任何第三方。

本 App 在飛航模式下功能完全相同；不具備上傳資料的能力。

## 二、資料儲存位置與方式

- 位置：裝置瀏覽器／Android WebView 的 `localStorage`（鍵名 `cjj.v1`）。
- 未加密儲存（與一般瀏覽器資料相同層級的保護）；能解鎖裝置的人可讀取。
- 不會備份到雲端，也不會同步到其他裝置。

## 三、你對資料的控制

| 操作 | 位置 | 效果 |
|---|---|---|
| 匯出備份 | 設定 → 匯出備份 | 產生 JSON 檔到你選擇的位置，可自行保管或轉移 |
| 刪除單筆 | 時間軸每則記錄的「刪除」 | 立即刪除該筆 |
| 清除全部 | 設定 → 清除所有記錄 | 立即且不可回復地刪除本機所有資料 |
| 完整移除 | 解除安裝 App／清除瀏覽器資料 | 資料一併消失 |

## 四、分享給醫師

只有在**你自己**按下「複製文字」「傳給醫師」「列印／存 PDF」時，摘要
內容才會離開本 App，且由你決定分享的對象與方式（通訊軟體、紙本、
螢幕出示）。開發者不會收到任何副本。

請注意：摘要可能包含情緒狀態與自傷相關紀錄。是否揭露由你決定。

## 五、權限

本 App 不需要相機、麥克風、位置、通訊錄、健康資料或相簿權限。
Android 版本由 Capacitor 預設宣告 `INTERNET` 權限（WebView 載入本機
檔案所需），但 App 不會發出任何網路請求，也未連結任何伺服器。

## 六、兒童與未成年人

本 App 非針對 18 歲以下使用者設計。未成年人請由法定代理人協助使用。

## 七、你的權利

由於開發者不持有任何你的資料，無法提供查閱、更正或刪除服務——資料
完全在你的裝置上，由你自行控制。若你認為本 App 的行為與本政策不符，
請與我們聯絡。

## 八、政策變更

若未來版本新增雲端同步、帳號或其他資料處理功能，本政策會同步更新，
並在 App 更新說明中告知。在更新前，本 App 維持「不收集、不上傳」的行為。

## 九、醫療聲明

本 App 是記錄與溝通工具，不是醫療器材，不提供診斷、治療或處置建議，
不能取代醫療專業人員的判斷。詳見 `DISCLAIMER.md` 與 App 內
「設定 → 關於與授權」。

緊急狀況請直接求助：**香港 999**、**中國內地 120**。心理支持：香港
「情緒通」18111、撒瑪利亞防止自殺會 2389 2222；中國內地 全國心理援助熱線 12356。

## 十、聯絡方式

- 開發者：Ken Cheung
- 電子郵件：**kcheung.inno@gmail.com**

---

### English summary

This app collects no data. There is no server, account, analytics or ad SDK.
Everything you type is stored only in your device's `localStorage` and never
transmitted. You can export, delete, or wipe all data from the Settings
screen. The developer holds no copy of your data and cannot retrieve it.
The app is not a medical device and does not provide diagnosis or treatment
advice.
