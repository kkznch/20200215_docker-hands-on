# 「tech美られでぃ #4 Docker どっか〜ん！（初心者向け）」解答用リポジトリ

## 概要

[tech美られでぃ #4 Docker どっか〜ん！（初心者向け）](https://tech-chura-lady.connpass.com/event/163133) のハンズオンで最終的に作りたいものを本リポジトリに置いています。


## 動かす方法

- リポジトリを clone します
  ```shell
  $ git clone git@github.com:kkznch/20200215_docker-hands-on_completed.git
  $ cd 20200215_docker-hands-on_completed
  ```
- docker-compose コマンドで Docker コンテナを起動します
  ```shell
  $ docker-compose up -d
  ```
- Makefile を実行してなんか色々初期化します（docker が動いてないと実行できないよ）
  ```shell
  $ make init
  ```
- ブラウザから以下の URL にアクセスすると良い感じにアプリが動いてるはず
  - http://localhost
  

## 止める方法

- コンテナを止めるだけのコマンド
  ```shell
  $ docker-compose stop
  ```
- イメージとコンテナを消し去るコマンド
  ```shell
  $ docker-compose down
  ```
