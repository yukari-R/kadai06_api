# 課題6 -APIを使ったアプリ-

## 紹介と使い方　＊作りたかったもの
  - その日いる場所と、日記的な一言コメントを保存し続けられる、地図✖️日記アプリを作りたかった
  - 技術的な面で言えば、LocalStorage or firebaseに緯度・経度を蓄積させて、地図に反映させるアプリを作りたかった

## 工夫した点
  - 授業で学習したことの応用をしてみたかったので、ローカルストレージとの組み合わせにトライした

## 苦戦した点（未解決）
  - 現在地を取得し、テキストデータと合わせてローカルストレージに入れることまではできた
  - pushpin,infoboxが反映されない問題が解消していない
  - ⓪位置情報を取得、①"send"ボタンを押した際、②テキストデータがローカルストレージに入る、③ローカルストレージのデータを読み取ってPinやinfoboxに緯度・経度とテキストデータが反映されるという流れにしたいのだが、①②を中心にコードを書くと、③Mapを読み取らない、という問題が発生。記述の順番、構造の問題とは認識しているが、解決せず調査中

## 参考にした web サイトなど
  - https://qiita.com/aotenjo007/items/7ee5abc8e6396b140558
  - https://codezine.jp/article/detail/5037
  - https://job-support.ne.jp/blog/javascript/return-value
  - https://blog.codecamp.jp/javascript-geolocation
