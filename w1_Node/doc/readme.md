# NodeJS

## day1-1

### 介绍
谢进荣      广西    老谢  laoxie

### 三阶段课程介绍
* 9周
    * 第1周：nodeJS
    * 第2~4周：Vue.js
    * 第5~6周：React.js
    * 第7周：混合开发
    * 第8周：小程序 
    * 第9周：就业周

    * 三阶段：
        * 今日事，今日毕（时间->效率）
        * 留级：超过3次（心里暗示：）
            * 三阶段不允许留级

* 困难：
    * 知难而进
    * 坚持就是胜利
    * 拼搏到无能为力、坚持到感动自己

* 三阶段怎么学习：
    * 记笔记：课堂笔记->整理->梳理大纲（xmind思维导图，脑图）
    * [写文章：]
    * 写代码：能动手千万别BB
        * 每天500行+
    * 做项目
        * 
    * 查文档（30s）
        * 技术文档（课堂笔记、文章、搜索引擎）
        * 需求文档

* 如何对待视频：
    * 

### 知识点

* 服务端与客户端
    * 服务端：服务器（一台7*24小时开机的电脑）
    * 客户端：用户端（一台个人电脑）

* 模块化开发
    * 利用第三方框架：require.js(AMD规范),sea.js(CMD规范)
    * NodeJS：commonJS规范
    * ES6 ： ES Module 规范


### 复习
* ES6前如何实现模块化开发：利用第三方框架（require.js:AMD, sea.js，异步）
    * require(['jquery'],($)=>{
        console.log($)
    })
    
* ES6：ES Module
    import $ from 'jquery'
* Node:commonJS
    * let $ = require('jquery');//必须符合commonjs的规范
    console.log($)

### 知识点
* 路由：根据url地址的不同响应不同的内容
* express: 

* fs: file system

## day1-2

### 复习NodeJS

1. 模块坏开发
        规范          框架             异同
    * AMD           require.js      异步（预加载）
    * CMD           sea.js          异步（延迟加载）
    * CommonJS      nodejs          同步（后端）
    * ES Module     es6             同步（前端）

2. 模块分类
    * 自定义模块
    * 内置模块
        * http
        * url
        * querystring
        * path
        * fs
    * 第三方模块
    * 文件模块（json）

    ```html
        http://www.laoxie.com?username=laoxie&password=123
        F:/xxx/xxx
    ```

3. 操作
    * 引入 require()
    * 导出 
        * exports.xxx = {}
        * module.exports = {}

4. 练习
    * 静态资源服务


* 什么是h5：大前端（全栈，全端）
    * 前端：html+css+js 
    * 后端：php+mySQL,nodeJS+MongoDB

### 类比能力
* 用熟悉的东西理解陌生的东西
* 三段论
    * 给你一个条件
    * 给你一个问题
    * 根据条件得出问题的答案


### 知识点
* fs
    * stream
    * pipe

    ```js
        let gulp = require('gulp');
        gulp.task('build',()=>{
            gulp.src('./src/js/*.js')  //得到一个文件流（stream，液体）
            .pipe(concat())
            .pipe(uglify())
            .pipe(gulp.dist('..'))
        })
    ```



    