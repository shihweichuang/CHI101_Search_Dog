# 搜狗 Search Dog - 中原浪浪 AI 辨識追蹤系統

以 LINE Bot 串接雲端及邊緣運算的方式，達到 AIoT、行動化技術，進行校狗的辨識及追蹤，並推廣動服社活動，協助狗狗們找到一個家。

- AI 影像辨識模型

  以 YOLO 系列模型進行模型訓練及調用

- AIoT 應用

  將模型轉檔導入邊緣運算裝置 Jetson Nano <br>
  使用 MQTT 協定將辨識資料存入 DB <br>
  建構 MySQL 資料庫 <br>

- LINE Bot

  以 GCP Cloud Run 及 Compute Engine 部屬程式
