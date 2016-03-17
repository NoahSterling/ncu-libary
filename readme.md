## 介绍
用于查询图书是否能借阅。一次性查询多本图书，省时省力。
## 运行方式
```
git clone git@github.com:Lxxyx/NLib.git
cd NLib
npm install
```

将要查找的图书，放入`list.json`中即可。
然后
```
cd dist
node Nlib.js
```
## 开发
```
npm i babel-cli -g
// 安装完成后
npm run lib
```
另外一个online.js为网络教学平台登录。
开发方式相同。
```
npm run online
```
## TODO
1. 加入邮件提醒功能 // 已完成
2. 放入微信公众号中
3. 加入网络教学平台登录功能