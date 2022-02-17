# gulp-de
gulpでsass、pug、typescript、webpを使うときの開発環境  
自分用です

## ファイル構成
```
project/  
　├ dist/  
　├ src/  
　│　├ img/  
　│　├ pug/  
　│　├ scss/  
　│　├ ts/  
　├ gulpfile.js  
  ├ package-lock.json  
　└ package.json
```

## 導入手順
- 以下のコマンドをプロジェクトファイルにて使用  
`npm i`
- srcフォルダ等を上記ファイル構成の用に作成
- 以下のコマンドでリアルタイムコンパイル  
`npx gulp`
