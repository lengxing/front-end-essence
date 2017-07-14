# 一个程序员一路走来的成长经历

<br>
这是仓库记录了我的读数笔记和学习经历。

## 目录
### 读过的书
[GitHub秘籍](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md#markdown-%E6%96%87%E4%BB%B6%E8%AF%AD%E6%B3%95%E9%AB%98%E4%BA%AE)
[七天学会NodeJS](http://nqdeng.github.io/7-days-nodejs/)
<br>
### 你是如何进行网站优化的？
减少http请求次数
>CSS合并，JS合并，图片合并（雪碧图），图片的延迟加载
### 作用域链
当代码在一个环境中执行时，会创建变量对象的一个作用域链（scope chain）。作用域链的用途，是保证对执行环境有权访问的所有变量和函数的有序访问。作用域链的前端，始终都是当前执行的代码所在环境的变量对象。如果这个环境是函数，则将其活动对象（activation object）作为变量对象。活动对象在最开始时只包含一个变量，即 arguments 对象（这个对象在全局环境中是不存在的）。作用域链中的下一个变量对象来自包含（外部）环境，而再下一个变量对象则来自下一个包含环境。这样，一直延续到全局执行环境；全局执行环境的变量对象始终都是作用域链中的最后一个对象。
<br>
标识符解析是沿着作用域链一级一级地搜索标识符的过程。搜索过程始终从作用域链的前端开始，然后逐级地向后回溯，直至找到标识符为止（如果找不到标识符，通常会导致错误发生）。
### 什么是闭包？
函数执行的时候会形成一个新的私有作用域，保护了里面的变量不受外界的干扰。
