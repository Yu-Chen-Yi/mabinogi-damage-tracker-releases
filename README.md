# Mabinogi Damage Tracker

《新瑪奇》傷害統計工具的官方發行頁面。

## 下載

請從 GitHub 頁面右側的 **Releases** 下載最新版本：

- `Mabinogi-Damage-Tracker-vX.Y.Z-win-x64.zip`（建議：含程式、自然語音附加環境與說明）
- `Mabinogi-Damage-Tracker-vX.Y.Z.exe`（單獨程式；語音製作仍需要附加環境）
- `SHA256SUMS.txt`（用來驗證下載檔案）

本儲存庫僅提供程式執行檔與版本更新說明，不包含完整原始碼。

## 使用方式

1. Windows 電腦需先安裝 [Npcap](https://npcap.com/)。
2. 下載並解壓縮最新版本的完整 ZIP。
3. 執行資料夾內的 EXE，首次使用時輸入授權金鑰。請保留旁邊的 `addons/edge-tts`，供自然語音製作使用。
4. 程式會在瀏覽器開啟傷害統計介面。

自動按鍵功能另需安裝 AutoHotkey v2；不使用自動按鍵時不需要安裝。更新前請正常關閉舊後端，備份並保留自己的資料庫、設定 JSON 與自訂音效。

自然語音使用獨立附加環境，不修改系統 Python；生成時需要網路，輸入文字會傳送至 Microsoft 線上服務。已生成的音檔可離線播放。

Windows 或防毒軟體可能會對尚未使用程式碼簽章的下載檔顯示警告。請只從本頁 Releases 下載，並可用同版本的 `SHA256SUMS.txt` 核對檔案雜湊。

## 更新

完整版本紀錄請參閱 [CHANGELOG.md](CHANGELOG.md)。

## 問題回報

回報時請提供版本號、發生問題的操作方式，以及可公開的錯誤訊息或截圖。請勿公開授權金鑰。
