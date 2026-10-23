# ドローンレース（3マップ）

ブラウザで遊べるドローンのリングレースです。リンクを開いた人どうしで、半透明のドローンになって一緒に飛べます。

- 遊ぶ: GitHub Pages の URL を開く
- 仲間内だけの部屋: URL の最後に `?room=好きな名前` を付ける（例: `.../?room=sakura`）
- 「準備OK」を同じマップの全員が押すと、カウントダウンしてレース開始

## 通信について
位置・向き・表示名・レースの合図だけを、公開の MQTT 中継サーバー（broker.emqx.io、つながらない時は broker.hivemq.com）経由でやりとりします。公開サーバーなので、同じ部屋名を知っている人には見えます。

## 3D モデルのクレジット
- “chicken gun deserttown2 reupload” by amogusstrikesback2 — CC BY 4.0 — https://sketchfab.com/3d-models/chicken-gun-deserttown2-reupload-982d0fde7dcb4e6e96bfecc7f74c22bf
- “R6 3D map: Theme Park” by dok11 — CC BY 4.0 — https://sketchfab.com/3d-models/r6-3d-map-theme-park-d9fdcd8f90234b289ef53bb9c0291064
- 大聖堂・ドローン: 作者提供のモデル
