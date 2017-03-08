# gulp-build
gulp 完整项目构件流程 es6 css\js压缩 支持多bundle情况

## 使用方法
* 源代码放到app目录下,app每个页面入口js命名为 main-x.js。x为自己的js业务名
* html放到html目录下，app中js会编译到lib目录生成main.x-bundle.js。所以html请引用../lib/main-x-bundle.js，x为自己的js业务名
* 图片放到images目录下
* 三方js放到lib目录下

## 开发中的调试
```
gulp watch
```
* app中js会编译到lib目录生成main.x-bundle.js，x为自己的js业务名
* app中js会编译到lib目录生成main.x-bundle.js。所以html请引用../lib/main-x-bundle.js，x为自己的js业务名

## 打包测试环境到dist
```
gulp build-dev
```

## 打包生产环境到dist
```
gulp build-prod
```
