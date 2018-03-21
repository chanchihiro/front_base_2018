# front_base_2018
## 環境
Percel + PostCSS + Pug + ES6
## 事前に用意するもの
- yarnかnpmが使える
- parcelのインストール<br>
`yarn global add parcel-bundler`
## ファイル構成
`
.<br>
├── .babelrc<br>
├── package.json<br>
├── public<br>
└── src<br>
    ├── scss<br>
    │   └── style.scss<br>
    ├── images<br>
    │   └── parcel.png<br>
    ├── index.html<br>
    └── js<br>
        ├── app.js<br>
        └── modules<br>
            └── add.js<br>
`
## 開発手順
`yarn start` <br>
`parcel watch src/index.html -d public`
## 概要 / 意図
自分で案件をやるためにサクサク設定ファイルいらずのpercelを使ってフロントの環境構築をしてみました。
最小の案件では使えそうですがまだ実戦では使用していません。ドキドキ。