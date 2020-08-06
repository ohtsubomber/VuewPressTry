# VuePress実行環境構築方法

1. Docker-Composeで立ち上げる

   ```
   docker-compose up
   ```
   
1. 初回のみコンテナの中から初期化（VuePressのインストール？）を実行する

   ```
   ./init.sh
   ```
1. myapp/docs/README.mdを好きに編集する
1. コンテナの中からコンパイルする
   ```
   vuepress dev docs
   ```
1. ブラウザからlocalhost:8080にアクセスして確認