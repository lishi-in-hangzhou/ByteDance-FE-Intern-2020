[toc]

# 基础知识篇
本文的资料大部分来自 W3C，因为不需要翻墙就可以看，老司机自行 MDN/标准文档/官方文档

## 阶段一
### HTML
*  知道大概的标签分类，以及每个标签能够实现的事情
*  了解块级元素、内联元素等概念
*  了解音视频、地图等新特性，详见《HTML 5 于 CSS 3 权威指南》

#### 资料区
[W3C][HTML-W3C]、[HTML 规范][HTML-规范]

[HTML-W3C]: https://www.w3school.com.cn/tags/index.asp
[HTML-规范]: https://www.runoob.com/w3cnote/html-css-guide.html#html"

### 切图
*  了解常用图片类型以及每个的使用场景
*  会使用 [PS][PS] 进行简单的图片处理

#### 资料区
[切图技巧][切图技巧1]、[ps切图实用小技巧、图片格式的区别及相关内容][切图技巧2]、[图片制作][图片制作]

[PS]: http://www.16xx8.com/photoshop/jiaocheng/28970.html
[切图技巧1]: https://blog.csdn.net/xiaoermingn/article/details/53240266
[切图技巧2]: https://juejin.im/post/58ec558d570c350057e849f0
[图片制作]: https://juejin.im/post/58eb062861ff4b006b576d9c

### 假装这里有个作业
* 给一个 PSD ，输出切出来的图片资源，对命名、图片类型以及压缩比率等方面给出一些理解
* 通过原生的 HTML 实现界面还原
* 将代码提交到制定的 github 仓库

### 扩展学习
* [浏览器渲染机制](https://blog.csdn.net/qq_34009967/article/details/80628748)，早年写的一篇博文，个人觉得适合入门，再深入的见 webkit 工作原理，资料自行 Google


## 阶段二
### CSS
* 基础知识
    * 熟练掌握基础样式语法，可以面向 MDN 编程，但是需要大概知道 CSS 有哪些东西
    * 熟悉样式的[引用方式][引用方式](内联、内部、外部)以及各种场景的样式优先级
    * [css 选择器][css 选择器]
    * [盒模型][盒模型]
    * 各种[定位][定位] + [浮动][浮动]
    * [背景][背景]、[文本][文本]、[字体][字体]、[轮廓][轮廓]
    * CSS3的一些东西 [Transform][Transform]、[Transition][Transition]、[Animation][Animation]
    * 样式兼容，如一些 hack 方法、厂商前缀等等
* 深入 CSS，这部分知识比较灵活但是比较重要 具体资料自行 Google，还有很多比较好玩的但是不常用的自行探索
    * BFC、IFC、GFC、FFC & 流体特性
    * baseLine & vertical-align
    * 层叠上下文
    * 三列布局、水平/垂直居中、弹性布局等等
    * css 渲染
* 代码规范
    * [CSS 规范](https://www.runoob.com/w3cnote/html-css-guide.html#css)

[引用方式]: https://www.w3school.com.cn/html/html_css.asp
[css 选择器]: https://www.w3school.com.cn/css/css_selector_type.asp
[盒模型]: https://www.w3school.com.cn/css/css_boxmodel.asp
[浮动]: https://www.w3school.com.cn/css/css_positioning_floating.asp
[定位]: https://www.w3school.com.cn/css/css_positioning_absolute.asp
[背景]: https://www.w3school.com.cn/css/css_background.asp
[文本]: https://www.w3school.com.cn/css/css_text.asp
[字体]: https://www.w3school.com.cn/css/css_font.asp
[轮廓]: https://www.w3school.com.cn/css/css_outline.asp
[Transform]: https://www.w3cplus.com/content/css3-transform
[Transition]: https://www.w3cplus.com/content/css3-transition
[Animation]: https://www.w3cplus.com/content/css3-animation

### 假装这里有个作业
* 在之前的基础上，加上 CSS 完成静态页面的制作
* 将代码提交 github

### 扩展学习
* [Flex](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html) [Flex2](https://note.youdao.com/ynoteshare1/index.html?id=71219e0def4cb6ca5afbb69c7c408c76&type=note)
* [趣味学习](http://flexboxfroggy.com/#zh-cn)
* [RN 中的 Flex](https://www.tuicool.com/articles/JzmMryr)
* [CSS 生态介绍](https://zhuanlan.zhihu.com/p/24953328)
* [BEM](https://www.w3cplus.com/css/battling-bem-extended-edition-common-problems-and-how-to-avoid-them.html)
* 张鑫旭博客

## JS
在介绍 JS 之前推荐几本书，红宝书([JavaScript高级程序设计](https://www.ituring.com.cn/article/470027))/犀牛书([javascript权威指南](https://book.douban.com/subject/10549733/))、[你不知道的 JS 系列](https://book.douban.com/subject/26351021/)、[阮一峰 ES6 标准入门](https://es6.ruanyifeng.com/)   
JS 进阶就是 [ECMA][ECMA] 标准的学习了，很多没法解释的场景都可以在这上面找到答案

* [什么是 JS](https://www.w3school.com.cn/js/index.asp)
* [怎么用 JS](https://www.w3school.com.cn/js/js_howto.asp)
* JS 语句、语法、注释、变量、数据类型、函数、运算符、判断、分支、循环、异常处理，见 W3C/MDN
* JS 全局对象
    * location
    * history
    * navigator
    * storage
* JSON 在 JS 中的运用
* 正则在 JS 中的运用，推荐看《[精通正则表达式](https://book.douban.com/subject/2154713/)》
* 熟悉 ES6 语法(let、const、箭头函数、解构、Set、Map、Promise、Generator、async/await、class、Module-静态动态模块、迭代器)，就目前工作情况来看异步、状态管理、迭代器、模块的概念比较重要，有机会可以看标准详细了解一下底层实现，这对其他工具的理解和使用有很大帮助

### 假装这里有个作业
* 在上次的作业上，加上 js 交互
* 提交到 github

### 扩展学习
* js 内存泄漏 & js 层面的前端优化
* js 原型、闭包
* 了解 this 的绑定以及原理
* 了解作用域链
* 了解 js 编译过程
* 了解 TS/flow

[ECMA]: https://ecma262.docschina.org/#sec-toprimitive

## DOM
熟悉 DOM 操作和 JQ，虽然 JQ 逐渐退出了历史舞台，但其很多设计原理、理念还是很值得深入研究的

* 熟悉 DOM 的 [API][API-DOM]
    * [getElementById][getElementById]
    * [getElementsByTagName][getElementsByTagName]
    * [getElementsByClassName][getElementsByClassName]
    * [appendChild][appendChild]
    * removeChild
    * replaceChild
    * insertBefore
    * createAttribute
    * createElement
    * createTextNode
    * getAttribute
    * setAttribute
    * querySelector
    * querySelectorAll

* [DOM 事件][DOM 事件]
    * click 事件
    * mouseup、mousedown、mousemove
    * mouseover、mouseenter
    * mouseout、mouseleave
    * 键盘事件、进度事件、拖拽事件、粘贴板事件、焦点事件、进度事件、资源事件、表单事件、session/hash 历史事件、网页状态事件等等

* [JQ][JQ]
    * JQ 常用选择器的是使用
    * 各种 DOM 操作的实现原理
    * JQ 的 AJAX 操作

* 思考
    * React 事件系统的实现以及解决了什么问题
    * [DOM 模型][DOM模型]是什么样的
    * DOM 层面的性能优化
    * JQ Deferred & Promise


[API-DOM]: https://www.w3school.com.cn/htmldom/dom_methods.asp
[getElementById]: http://javascript.ruanyifeng.com/dom/document.html#toc16
[getElementsByTagName]: http://javascript.ruanyifeng.com/dom/document.html#toc13
[getElementsByClassName]: http://javascript.ruanyifeng.com/dom/document.html#toc14
[appendChild]: http://javascript.ruanyifeng.com/dom/node.html#toc18
[DOM 事件]: http://javascript.ruanyifeng.com/dom/event-type.html#toc1
[JQ]: http://www.shouce.ren/api/view/a/1527
[DOM模型]: http://javascript.ruanyifeng.com/#dom

### 假装这里有个作业

* 在之前的基础上加上 DOM 操作
* 使用 JQ 实现一版
* 代码提交到 github

### 扩展学习

* [正则表达式 30 分钟入门教程](https://deerchao.cn/tutorials/regex/regex.htm)
* [Web Worker](http://javascript.ruanyifeng.com/htmlapi/webworker.html)
* webSocket、Service Worker
* [canvas](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API/Tutorial)、[SVG](https://www.runoob.com/svg/svg-tutorial.html)
* [Chrome 开发者工具](https://developers.google.com/web/tools/chrome-devtools/)

# 进阶
## 框架学习
推荐路线 [React][官方文档] + [react-router][React-router] + [redux][redux] 或者 [vue][vue] + [vue-router][vue-router] + [vuex][vuex]

### React
有能力翻墙的同学请直接看 React [官方文档][官方文档]

* [React JSX][React JSX]
* [React 组件][React 组件]
* [React State][React State]
* [React Props][React Props]
* [React 组件 API][React 组件 API]
* [React 组件生命周期][React 组件生命周期]
* [React 表单与事件][React 表单与事件]
* [React Refs][React Refs]
* 服务端渲染
* [源码阅读][源码阅读]，了解虚拟 DOM、diff、fiber、调度、事件合成等等

### [React Router][React Router]

思考下常用路由的实现方式，可以是服务端实现也可以是前端实现

### [Redux][Redux]

* react-redux 等库的使用
* redux 中间件
* redux 异步
* 其他工具，如 [MobX][MobX]、[Flux][Flux]


        
        
[node]: http://www.ruanyifeng.com/blog/2016/10/npm_scripts.html?utm_source=tuicool&utm_medium=referral
[ESLint]: https://cnodejs.org/topic/57c68052b4a3bca66bbddbdd
[stylelint]: https://www.w3cplus.com/workflow/How-to-lint-your-css-with-stylelint.html?utm_source=tuicool&utm_medium=referral
[webpack]: https://webpack.docschina.org/concepts/
[node]: http://nodejs.cn/api/
[babel]: https://babeljs.io/

[官方文档]: http://react.html.cn/docs/getting-started.html
[React-router]: https://react-router.docschina.org/web/example/basic
[redux]: https://www.redux.org.cn/
[源码阅读]: https://react.jokcy.me
[vue]: https://cn.vuejs.org/index.html
[vuex]: https://vuex.vuejs.org/zh/
[vue-router]: https://router.vuejs.org/zh/
[MobX]: https://suprise.gitbooks.io/mobx-cn/content/fp.html
[Flux]: http://www.ruanyifeng.com/blog/2016/01/flux.html
[Redux]: https://react-redux.js.org/api/connect
[React Router]: http://react-guide.github.io/react-router-cn/docs/API.html
[React JSX]: https://www.runoob.com/react/react-jsx.html
[React 组件]: https://www.runoob.com/react/react-components.html
[React State]: https://www.runoob.com/react/react-state.html
[React Props]: https://www.runoob.com/react/react-props.html
[React 组件 API]: https://www.runoob.com/react/react-component-api.html
[React 组件生命周期]: https://www.runoob.com/react/react-component-life-cycle.html
[React 表单与事件]: https://www.runoob.com/react/react-forms-events.html
[React Refs]: https://www.runoob.com/react/react-refs.html


## 其他零碎知识

### 代码管理
git 大法最好的应该是《Git Pro》，下面是一些国内的链接，仅供参考   

*  [git 安装与配置][git-配置]
*  [git 工作流程][git 工作流程]
*  [git 基础指令][git 基础指令]、[分支][分支]
*  [git 工作区 暂存区][git 工作区]
*  [git 命令清单][git 命令清单]
*  git 常用指令配置建议，尽量少用图形工具(小乌龟、sourcetree)  
   btw~ 也可以使用 svn 来管理代码，看个人爱好，不过现在公司都是 git 流了，只有在某些场景下才会用 svn

~~~~ git
[alias]
	commonLog = log --pretty=format:\"%h - %an, %ar : %s\"
	lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
	cr = !sh -c 'git push origin HEAD:refs/for/$1' -
  	ci = commit
  	ciamend = commit --amend -m ''
  	patch = !sh -c 'git ciamend && git cr $1' -
  	st = status
  	br = branch
	stp = stash pop
~~~~

[git-配置]: http://www.shouce.ren/api/view/a/7484
[git 工作流程]: http://www.shouce.ren/api/view/a/7485
[git 基础指令]: http://www.shouce.ren/api/view/a/7488
[分支]: http://www.shouce.ren/api/view/a/7489
[git 工作区]: http://www.shouce.ren/api/view/a/7487
[git 命令清单]: http://www.shouce.ren/api/view/a/12177

### 工程化
*  [安装 node 与使用 NPM/yarn][node]
*  熟悉静态检查工具
*  [ESLint][ESLint]
*  [stylelint][stylelint]
*  less/sass
*  [webpack][webpack]
*  [babel][babel]
*  [node][node]
       * node 框架可以自行学习 koa2/express  
       * 推荐书籍《深入浅出 node.js》
*  前端单元测试(字节用的是 Jest + Enzyme)
    * [Mock](https://github.com/nuysoft/Mock/wiki)
    * [Karma](https://karma-runner.github.io/4.0/intro/installation.html)
    * [Mocha](http://www.ruanyifeng.com/blog/2015/12/a-mocha-tutorial-of-examples.html)
    * [Jest](https://jestjs.io/docs/en/mock-functions#mocking-modules)

### 工具
* lodash/underscore
* Web Inspector
* fiddler/wireshark/Charles
* Debug 技巧，[前端调试技巧与诀窍][前端调试技巧与诀窍]、[分享一些 Chrome 浏览器的前端调试技巧][分享一些 Chrome 浏览器的前端调试技巧]、[精读前端调试技巧][精读前端调试技巧]

### 程序设计
* 面向对象
* 设计原则 SOLID
* 设计模式
* 数据结构(常见数据结构、算法)
* UML

### 性能提升
* requestAnimationFrame
* HTTP缓存
* lazyload/prefetch
* CDN

[前端调试技巧与诀窍]: https://juejin.im/post/5901e8d6a0bb9f0065e64f63
[分享一些 Chrome 浏览器的前端调试技巧]: https://juejin.im/post/5d09c39ee51d4576bc1a0e07
[精读前端调试技巧]: https://zhuanlan.zhihu.com/p/27334352

## 假装这里有个作业
* 搭建一个简单的脚手架，用 React/Vue 全家桶重构之前的项目，加上单元测试
* 提交到 github




