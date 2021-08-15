## ソースコードのインストール
https://github.com/pachirapachira/youtubelesson

## dockerとdocker-composeのインストール

Docker公式ページに入ってインストールをしましょう  
https://docs.docker.jp/get-docker.html  
Docker Desktop for MacやDocker Desktop for Windowsをインストールすれば  
dockerとdocker-composeは両方インストールできます。  

ターミナルでバージョン情報が出ればOK  
docker --version  
docker-compose -version  

## docker-composeでサンプルのアプリをノートパソコン内に作成してみよう
ターミナル内でダウンロードしたフォルダに移動しよう  

cd lesson1_docker_docker-composeの絶対パス  
docker-compose up -d  

ブラウザで以下のURLを入力
http://localhost:3000/
メモアプリが表示されます。

