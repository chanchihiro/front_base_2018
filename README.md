# front_base_2018
## 概要 / 意図
自分で案件をやるためにサクサク設定ファイルいらずのParcelを使ってフロントの環境構築をしてみました。
最小の案件では使えそうですがまだ実戦では使用していません。ドキドキ。
## 環境
Parcel + PostCSS + Pug + ES6
## 環境構築
`yarn install`
## 事前に用意するもの
yarnが使える状態
```
parcelのインストール
yarn global add parcel-bundler
```
## ファイル構成
```
.
├── .babelrc
├── package.json
├── public
└── src
    ├── scss
    │   └── style.scss
    ├── images
    │   └── parcel.png
    ├── index.html
    └── js
        ├── app.js
        └── modules
            └── add.js
```
## 開発手順
```
ビルドしてwatchしてくれる
yarn run start
```