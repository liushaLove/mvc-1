#### MVC介绍
##### 实现功能
1. 加减乘除
2. tab 切换
3. 左晃右晃
4. 悬浮变色

##### 进行打包压缩
```javascrit
rm -rf dist && parcel build src/index.html --no-minify --public-url
```

##### 启动服务
```javascript
yarn src/index.html
```
