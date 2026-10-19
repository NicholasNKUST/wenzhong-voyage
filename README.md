# 文中號出航

石城漁港與龜山島海域的潮汐、海流、浪高、風、天氣與水溫監測，附即時動態地圖與當季海洋生物圖鑑。

作者：Nicholas Li

## 使用方式

打開網頁就會自動抓取最新的海象與天氣資料，之後每 30 分鐘更新一次，不需要複製貼上。
如果網路受限導致抓取失敗，頁面上的「手動更新資料」可以改用複製貼上的方式。

## 部署到 GitHub Pages

1. 把 `index.html` 放在 repo 根目錄（或 `docs/` 資料夾）。
2. 到 repo 的 **Settings → Pages**。
3. **Source** 選 **Deploy from a branch**，Branch 選 `main`，資料夾選 `/ (root)`（或 `/docs`）。
4. 存檔後約一分鐘，網址會是 `https://<帳號>.github.io/<repo 名稱>/`。

## 資料來源

- 海象：[Open-Meteo Marine API](https://open-meteo.com/en/docs/marine-weather-api)（MeteoFrance SMOC 海流與潮位、波浪模式）
- 天氣：[Open-Meteo Forecast API](https://open-meteo.com/en/docs)
- Open-Meteo 免費版限非商業用途，不需要 API 金鑰。

模式網格約 8 公里，沿岸精度有限，不能取代官方潮汐表與航行警報。出海前請以[中央氣象署海象監測](https://www.cwa.gov.tw/V8/C/M/OBS_Marine.html)為準。
