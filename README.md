おじさん
===
### 使い方

- ### githubからダウンロード

`git clone git://github.com/fastec02/Ojisan_docker`

- ### Docker

#### Dockerのビルド

`docker-compose build`

#### Dockerの起動

`docker-compose up -d`

#### Dockerの作業シェルに入る

`docker exec -it node /bin/sh`

- ### npm

#### npmのインストール

`npm install`

#### npmサーバの起動

`npm run serve`

===

### ポートの変更

####  docker-compose.ymlの内容を変更
##### ex:
##### ポートを8080に（デフォルト）
>ports:
>  - "8080:3000"
##### ポートを9090に
>ports:
>  - "9090:3000"
