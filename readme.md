# 实用框架、工具整理汇总
- [通用工具](#通用工具)
- [Node.js](#Node.js)
- [前端通用](#前端通用)
- [视图引擎](#视图引擎)


## 通用工具
### apidoc
[https://github.com/apidoc/apidoc](https://github.com/apidoc/apidoc)

简介：基于node的**RESTful文档生成工具**


### Lodash
[https://lodash.com/](https://lodash.com/)

简介：js工具库，用健壮的代码封装了诸多对字符串、数组、对象等常见数据类型的处理函数，如随机数生成、对象深拷贝等。


## Node.js
### Express
[http://www.expressjs.com.cn/](http://www.expressjs.com.cn/)

简介：node经典脚手架，支持es5。


### koa
[https://koa.bootcss.com/](https://koa.bootcss.com/)

简介：express团队打造的node脚手架，依赖node v7.6.0，支持es6（es2015）。


### electron
[https://electronjs.org/](https://electronjs.org/)

简介：基于node的跨平台应用构建工具。


### jwt-simple
[https://github.com/hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple)

简介：node下的**JWT**（JSON Web Token）编解码工具。


### mongoose
[http://mongoosejs.com/](http://mongoosejs.com/)

简介：node下的**ODM**工具。


### lowdb
[https://github.com/typicode/lowdb](https://github.com/typicode/lowdb)

简介：node下的**JSON数据库**，支持Lodash，以JSON文件的形式存储数据，不需要额外配置数据服务器。


### jimp
[https://github.com/oliver-moran/jimp](https://github.com/oliver-moran/jimp)

简介：node下的**图形处理库**,有缩放、裁剪、滤镜、饱和度、颜色选择等图形处理功能。

### cheerio
[https://cheerio.js.org/](https://cheerio.js.org/)

简介：node下的html处理模块，可用作爬虫、页面抓取。


## 前端通用
### Swiper
中文网：[http://www.swiper.com.cn/](http://www.swiper.com.cn/)

英文网：[http://idangero.us/swiper/](http://idangero.us/swiper/)

简介：支持桌面、移动端触控的**轮播图插件**，有原生和JQuery两个版本。


### PhotoSwipe
[http://photoswipe.com/](http://photoswipe.com/)

简介：**js画廊**，支持图像的缩放，移动端触控移动、缩放。


### draggable
[https://github.com/Shopify/draggable](https://github.com/Shopify/draggable)

简介：**js拖拽库**，可实现拼图、2.5d图形拖拽等。

### axios
[https://github.com/axios/axios](https://github.com/axios/axios)

简介：好用的**http库**。


## 视图引擎
### ejs
[http://www.ejs.co/](http://www.ejs.co/)

简介：前端模版引擎，省去拼接字符串的繁琐操作，引入即可使用。插值为`<%=  %>`，支持任意js语句。

### handlebars
[http://handlebarsjs.com/](http://handlebarsjs.com/)

简介：前端模版引擎，引入即可使用，使用`{{ }}`插值模版的结构使代码更具可读性。

### art-template
[https://aui.github.io/art-template/zh-cn/index.html](https://aui.github.io/art-template/zh-cn/index.html)

简介：轻量前端模版引擎，浏览器模式下仅6KB(Gzip)，引入即可使用，同时支持`{{ }}`和`<%= %>`两种模版,与EJS一样，在`<%= %>`原始模版中支持任意js语句。