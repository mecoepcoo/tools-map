# 实用框架、工具整理汇总
- [通用工具](#通用工具)
- [Node.js](#Node.js)
  - [Node框架](#Node框架)
- [web通用](#web通用)
  - [web组件](#web组件)
  - [web交互](#web交互)
- [视图引擎](#视图引擎)
- [视觉效果](#视觉效果)

如果没有附地址，则默认为npm包

## 通用工具
通用工具在node和browser环境均可使用
### axios
[https://github.com/axios/axios](https://github.com/axios/axios)

简介：好用的**http请求库**。


### apidoc
[https://github.com/apidoc/apidoc](https://github.com/apidoc/apidoc)

简介：基于node的**RESTful文档生成工具**


### Lodash
[https://lodash.com/](https://lodash.com/)

简介：js工具库，用健壮的代码封装了诸多对字符串、数组、对象等常见数据类型的处理函数，如随机数生成、对象深拷贝等。


## Node.js
### Node框架
#### Express
[https://expressjs.com/](https://expressjs.com/)

简介：node经典脚手架，支持es5。


#### koa
[https://koajs.com/](https://koajs.com/)

简介：express团队打造的node脚手架，依赖node v7.6.0，支持es6（es2015）。


#### egg
[https://eggjs.org/zh-cn/](https://eggjs.org/zh-cn/)

简介：Egg.js 为企业级框架和应用而生，我们希望由 Egg.js 孕育出更多上层框架，帮助开发团队和开发人员降低开发和维护成本。

#### nestjs
[https://nestjs.com/](https://nestjs.com/)

简介：Nestjs是一个用于构建高效、可扩展的Node.js服务器应用程序的框架，它使用渐进式JavaScript，使用TypeScript构建并完全支持OOP，FP和FRP.


#### midway
[http://www.midwayjs.org/](http://www.midwayjs.org/)

简介： Midway 是阿里巴巴 - 淘宝前端架构团队，基于渐进式理念研发的 Node.js 框架。​Midway 基于 TypeScript 开发，结合了面向对象（OOP + Class + IoC）与函数式（FP + Function + Hooks）两种编程范式，并在此之上支持了 Web / 全栈 / 微服务 / RPC / Socket / Serverless 等多种场景，致力于为用户提供简单、易用、可靠的 Node.js 服务端研发体验


#### electron
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


### chalk
简介：终端字符串样式库。


### Inquirer.js
简介：创建交互式命令行。


### slash
简介：系统路径分隔符处理库


### minimist
简介：解析命令行参数


### dotenv
简介： 从 .env 文件**加载环境变量**


### hash-sum
简介：快速生成hash.


### semver
简介：npm语义化版本生成器


### leven
简介：比较两个字符串之间的差异


### portfinder
简介：自动寻找可用端口号


### ora
简介：在终端显示美观的转盘图标


### envinfo
简介：生成debug软件问题时所需的详细环境报告，例如操作系统、浏览器版本、安装的语言等


### memfs
简介：内存文件系统与fs模块api的相同实现


### strip-ansi
简介：从字符串中去除ANSI转义码


### address
简介：获取当前机器的ip，mac和dns信息


## web通用
### web组件
#### Swiper
中文网：[http://www.swiper.com.cn/](http://www.swiper.com.cn/)

英文网：[http://idangero.us/swiper/](http://idangero.us/swiper/)

简介：支持桌面、移动端触控的**轮播图插件**，有原生和JQuery两个版本。


#### PhotoSwipe
[http://photoswipe.com/](http://photoswipe.com/)

简介：**js画廊**，支持图像的缩放，移动端触控移动、缩放。


### web交互
#### draggable
[https://github.com/Shopify/draggable](https://github.com/Shopify/draggable)

简介：**js拖拽库**，可实现拼图、2.5d图形拖拽等。


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

## 视觉效果
### CountUp.js
[https://github.com/inorganik/countUp.js](https://github.com/inorganik/countUp.js)

简介：实现数字滚动效果，兼容所有浏览器。这个插件也有Vue，Ng，React，wordpress模块。
