# Lucky 手冊

Lucky 的拍立得成長相簿：日記、照片影片、去過的地方、朋友通訊錄、訓練進度和用品紀錄。

- 網頁：GitHub Pages（`https://fuwei0618-cmd.github.io/Lucky/`），可以加到手機主畫面當 App 用。
- 資料：登入 Microsoft 帳號後，紀錄、照片和影片都存在自己的 OneDrive「應用程式／Lucky 手冊」資料夾，這個 repo 裡沒有任何個人資料。
- 不讓搜尋引擎收錄（`robots.txt` 和 `noindex`）。

## 檔案

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 整個 App |
| `sw.js` | 離線快取，改了 `index.html` 要把裡面的 `VERSION` 加一 |
| `manifest.webmanifest`、`icons/` | 加到主畫面時的名稱和圖示 |
