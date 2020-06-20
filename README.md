### 介绍
这是一个由`HTML`页面编写的简历，大小为`A4`大小。可以打印为`PDF`格式

### 开发
全局安装`parcel`
```
yarn add global parcel //或者
npm i parcel -g
```

本地预览
```
parcel src/index.html
```
部署到GitHub pages
```
parcel build src/index.html --public-url ./
```
### 在线编辑
开发者工具的`console`页面输入
```
document.designMode ='on'
```