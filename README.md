# PlagueWatch MVP

全球鼠疫（Yersinia pestis）近實時監測 Web App 示範版本，已加入封城／封關／檢疫措施資訊。

## 功能

- 互動世界地圖（Leaflet + Dark basemap）
- 狀態顏色區分：
  - 橙色：發展中／未確認個案
  - 青色：封關／邊境檢疫措施
  - 紫色：地方性疫區
  - 灰色：歷史參考
- 側邊欄警報列表（可篩選）
- 點擊跳轉地圖 + 彈出詳情（含措施說明）
- 基本教育資訊與免責聲明

## 使用方式

1. 直接用瀏覽器開啟 `plague-monitor-mvp.html`。
2. 或部署到任何靜態主機（Vercel、Netlify、GitHub Pages 等）。

建議啟用 GitHub Pages：
- Settings → Pages → Source: Deploy from a branch → main / root

## 下一步擴展建議

- 接入真實數據源：HealthMap、WHO Disease Outbreak News、ProMED-mail、新聞 API
- 後端定時任務更新數據
- 加入推送通知
- 人工審核流程（確認／謠言／已解決）

## 重要聲明

此為 MVP 示範，使用基於 2026 年 10 月公開報告的樣本數據。  
許多「封關」報導實為加強檢疫與篩查，而非完全關閉邊境。  
**非官方監測系統**，不可替代 WHO、CDC 或各國衛生部門的官方資訊。

數據參考來源包括 WHO DON、各國衛生部門聲明及國際新聞報導。

更新：2026-10-11
