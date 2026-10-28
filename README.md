# 藍牙健保卡讀卡系統 3D 概念模擬

三件式系統的互動 3D 概念頁（three.js，單一 HTML 檔）：

1. **腦波頭帶**：TPU 95A 列印兩件式（前額片 + 後扣帶），金杯版三點前額電極，額側白色電子盒，電極線繞過頭頂。
2. **平板**：量測 App 畫面，接收健保卡卡號與腦波串流。
3. **藍牙健保卡讀卡機**：無按鍵，插卡即喚醒，BLE 傳送到平板。

## 檔案

| 檔案 | 說明 |
|---|---|
| `藍牙健保卡讀卡系統_3D.html` | 三件式系統（直接用瀏覽器開啟） |
| `日照中心_寫實版.html` / `daycare-real.html` | 日照中心情境，寫實風格 |
| `日照中心_動畫版.html` / `daycare-toon.html` | 日照中心情境，動畫風格 |
| `藍牙健保卡讀卡機_3D.html` | 舊版，只有讀卡機，側邊仍有電源鍵 |
| `ble_nhi_reader_3d.html` | 更早的讀卡機版本 |
| `739827.jpg` | 讀卡機麵包板原型照片 |
| `金杯版*.jpg` | 頭帶列印件照片（正面 / 反面），3D 模型依此版本 |
| `金杯版列印示意圖_0.png` | Bambu Studio 切片畫面 |
| `messageImage_*.jpg` | 市售彈性頭帶參考圖 |

## 線上 3D 模擬

直接開啟：https://lcqiann.github.io/ble-nhi-reader-system/

日照中心情境版（長者配戴頭帶，無自動旋轉）：

- 寫實版：https://lcqiann.github.io/ble-nhi-reader-system/daycare-real.html
- 動畫版：https://lcqiann.github.io/ble-nhi-reader-system/daycare-toon.html

（GitHub Pages 自 `index.html` 發佈，與 `藍牙健保卡讀卡系統_3D.html` 內容相同）

## Claude 版本

https://claude.ai/artifact/S5hW3s3kvN6sxsTNieaWWV
