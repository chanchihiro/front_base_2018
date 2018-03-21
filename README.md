# front_base_2018
## 概要 / 意図
自分で案件をやるためにサクサク設定ファイルいらずのpercelを使ってフロントの環境構築をしてみました。
最小の案件では使えそうですがまだ実戦では使用していません。ドキドキ。
## 環境
Percel + PostCSS + Pug + ES6
## 事前に用意するもの
- yarnかnpmが使える
- parcelのインストール<br>
`yarn global add parcel-bundler`
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
`yarn start` <br>
`parcel watch src/index.html -d public`