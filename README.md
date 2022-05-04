# Docker-php-8.1.1-apache
apacheサーバー php-8.1.1 docker開発環境

Dockerを使用してのPHP実行環境です。

手順
#### ①Dockerをインストール(https://www.docker.com/products/docker-desktop)

#### ②Zipファイルを解凍する

#### ③ターミナルで、ダウンロードしたファイルのディレクトリに移動し、以下のコマンドを実行
#### 「docker-compose up -d --build」



PHPの実行環境の完成

ファイル内容
・php
・pypmyadmin
・mysql
②のコマンドで、Dockerイメージが自動でダウンロードされます。
DBへのリンクは、indexに記載してます。DB情報と接続処理はDB.phpを参照してください。
