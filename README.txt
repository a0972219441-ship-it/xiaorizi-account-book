小日子記帳 PWA（本機保存版）
檔案：index.html、manifest.webmanifest、sw.js、icon.svg。

功能：手動銀行／現金餘額、收入支出與轉帳紀錄、每月預算、ETF 持股與股息、信用卡／貸款負債、資產負債估算、JSON 備份與還原。

注意：資料保存在目前瀏覽器本機，不會自動同步；請定期備份。銀行餘額與 ETF 價格／股息均需手動輸入。交易紀錄不會自動改動銀行餘額。尚未實作銀行／券商自動同步、即時 ETF 行情、跨裝置同步、信用卡到期提醒、貸款攤還表。

Android 手機部署 GitHub Pages：
1. 解壓縮 ZIP。
2. 開啟 GitHub 儲存庫 xiaorizi-account-book，點 Add file → Upload files。
3. 將解壓縮後的 index.html、manifest.webmanifest、sw.js、icon.svg、README.txt 上傳到儲存庫根目錄（不要只上傳 ZIP），再 Commit changes。
4. 儲存庫 Settings → Pages，選 Deploy from a branch，Branch 選 main、資料夾選 /(root)，儲存。
5. 等 Pages 部署完成，開啟它提供的 HTTPS 網址；在 Android Chrome 的 ⋮ 選「加到主畫面」或「安裝應用程式」。
直接用 file:// 開啟 HTML 可能無法安裝 PWA。
