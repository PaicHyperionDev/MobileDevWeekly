# [平安科技移动开发二队技术周报](https://github.com/PaicHyperionDev/MobileDevWeekly)（特别版のReact Native专题）

> @author ASCE1885的 [Github](https://github.com/ASCE1885)  [简书](http://www.jianshu.com/users/4ef984470da8/latest_articles) [微博](http://weibo.com/asce885/profile?rightmod=1&wvr=6&mod=personinfo) [CSDN](http://blog.csdn.net/asce1885)

> 随着React Native For Android的发布，React Native俨然已经成为移动开发的一个热门技术选型，本期周报简单总结使用React Native进行开发所需要的技术储备，入门React Native开发。

## 深入浅出 ES6 系列

ECMAScript 6已经正式发布了，作为它最重要的方言，Javascript也即将迎来语法上的重大变革，本系列文章就来看一下ES6将给我们带来哪些新内容。

* [ES6是什么](http://www.infoq.com/cn/articles/es6-in-depth-an-introduction)
* [迭代器和for-of循环](http://www.infoq.com/cn/articles/es6-in-depth-iterators-and-the-for-of-loop)
* [生成器 Generators](http://www.infoq.com/cn/articles/es6-in-depth-generators)
* [模板字符串](http://www.infoq.com/cn/articles/es6-in-depth-template-string)
* [不定参数和默认参数](http://www.infoq.com/cn/articles/es6-in-depth-rest-parameters-and-defaults)
* [解构 Destructuring](http://www.infoq.com/cn/articles/es6-in-depth-destructuring)
* [箭头函数 Arrow Functions](http://www.infoq.com/cn/articles/es6-in-depth-arrow-functions)
* [Symbols](http://www.infoq.com/cn/articles/es6-in-depth-symbols)
* [学习Babel和Broccoli，马上就用ES6](http://www.infoq.com/cn/articles/es6-in-depth-babel-and-broccoli)
* [集合](http://www.infoq.com/cn/articles/es6-in-depth-collections)
* [生成器 Generators，续篇](http://www.infoq.com/cn/articles/es6-in-depth-generators-continued)
* [代理 Proxies](http://www.infoq.com/cn/articles/es6-in-depth-proxies-and-reflect)


## 深入浅出 React 系列

#### 1）[React的设计哲学 - 简单之美](http://www.infoq.com/cn/articles/react-art-of-simplity)

React最初来自Facebook内部的广告系统项目，项目实施过程中前端开发遇到了巨大挑战，代码变得越来越臃肿且混乱不堪，难以维护。于是痛定思痛，他们决定抛开很多所谓的“最佳实践”，重新思考前端界面的构建方式，于是就有了React。

#### 2）[React开发神器Webpack](http://www.infoq.com/cn/articles/react-and-webpack)

本文主要了解一下用于React开发和模块管理的主流工具Webpack。称之为React开发神器有点标题党了，不过Webpack确实是笔者见过的功能最为强大的前端模块管理和打包工具。虽然Webpack是一个通用的工具，并不只适合于React，但是很多React的文章或者项目都使用了Webpack，尤其是react-hot-loader这样的神器存在，让Webpack成为最主流的React开发工具。

#### 3）[理解JSX和组件](http://www.infoq.com/cn/articles/react-jsx-and-component)

JSX这种混合使用JavaScript和XML的语言第一眼看上去很“丑”，也很神奇，但是其语法和背后的逻辑却极其简单。相信读完本文你就可以对JSX和组件有一个全面的了解，并能够用JSX来直观的构造用户界面。

#### 4）[虚拟DOM Diff算法解析](http://www.infoq.com/cn/articles/react-dom-diff)

React中最神奇的部分莫过于虚拟DOM，以及其高效的Diff算法。这让我们可以无需担心性能问题而”毫无顾忌”的随时“刷新”整个页面，由虚拟DOM来确保只对界面上真正变化的部分进行实际的DOM操作。React在这一部分已经做到足够透明，在实际开发中我们基本无需关心虚拟DOM是如何运作的。然而，作为有态度的程序员，我们总是对技术背后的原理充满着好奇。理解其运行机制不仅有助于更好的理解React组件的生命周期，而且对于进一步优化React程序也会有很大帮助。

## React Native 探索系列

#### 1）[背景、规划和风险](http://www.infoq.com/cn/articles/react-native-overview)

React Native项目成员Tom Occhino发表的React Native: Bringing modern web techniques to mobile详细描述了React Native的设计理念。Occhino认为尽管Native开发成本更高，但现阶段Native仍然是必须的，因为Web的用户体验仍无法超越Native。

#### 2）[布局篇](http://www.infoq.com/cn/articles/react-native-layout)

布局篇主要讲解了react布局的宽度，flex布局，图片布局，定位和文本元素等。

#### 3）[与 react-web 的融合](http://www.infoq.com/cn/articles/react-native-web)

对于react-native在实际中的应用， facebook官方的说法是react-native是为多平台提供共同的开发方式，而不是说一份代码，多处使用。 然后一份代码能够多处使用还是很有意义的。

## Flex 布局教程

#### 1）[语法篇](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

布局的传统解决方案，基于盒状模型，依赖 display属性 + position属性 + float属性。它对于那些特殊布局非常不方便，比如，垂直居中就不容易实现。2009年，W3C提出了一种新的方案----Flex布局，可以简便、完整、响应式地实现各种页面布局。目前，它已经得到了所有浏览器的支持，这意味着，现在就能很安全地使用这项功能。

#### 2）[实例篇](http://www.ruanyifeng.com/blog/2015/07/flex-examples.html)

上一篇文章介绍了Flex布局的语法，今天介绍常见布局的Flex写法。你会看到，不管是什么布局，Flex往往都可以几行命令搞定。

## 其他

#### 1）[React Native For Android初体验](http://www.jianshu.com/p/847a54e0c385)

React Native For Android提前发布了，代码托管在Github上面，本文是一个尝鲜体验，主要介绍环境配置的过程。

#### 2）[React Native: Android 的打包](http://www.liaohuqiu.net/cn/posts/react-native-android-package/)

本文介绍 React Native 中的资源打包，重点介绍使用 react-native-gradle 插件进行 Android APP 的打包。

#### 3）[React Native For Android 架构初探](http://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=207782506&idx=1&sn=3ff6b03c0d59fbda406f64739d9272cf)

Facebook 在2015.9.15发布了 React Native for Android，把JavaScript 开发技术扩展到了Android平台。React Native 让开发者使用 JavaScript 和 React 编写应用，利用相同的核心代码就可以创建 基于Web，iOS 和 Android 平台的原生应用。本文将浅析Android React的架构及相关基础知识。

#### 4）[React Native通信机制详解](http://blog.cnbang.net/tech/2698/)

React Native是facebook刚开源的框架，可以用javascript直接开发原生APP，先不说这个框架后续是否能得到大众认可，单从源码来说，这个框架源码里有非常多的设计思想和实现方式值得学习，本篇先来看看它最基础的JavaScript-ObjectC通信机制(以下简称JS/OC)。

#### 5）[颠覆式前端UI开发框架：React](http://www.infoq.com/cn/articles/subversion-front-end-ui-development-framework-react?utm_source=infoq&utm_medium=related_content_link&utm_campaign=relatedContent_articles_clk)

基于HTML的前端界面开发正变得越来越复杂，其本质问题基本都可以归结于如何将来自于服务器端或者用户输入的动态数据高效的反映到复杂的用户界面上。而来自Facebook的React框架正是完全面向此问题的一个解决方案，按官网描述，其出发点为：用于开发数据不断变化的大型应用程序（Building large applications with data that changes over time）。相比传统型的前端开发，React开辟了一个相当另类的途径，实现了前端界面的高效率高性能开发。

## 汇总

#### 1）[React-Native入门指南](https://github.com/vczero/react-native-lession)

React Native入门的系列教程，主要针对iOS版本。

#### 2）[React-Native学习指南](https://github.com/ele828/react-native-guide)

本指南汇集React-Native各类学习资源，给大家提供便利。

#### 3）[Awesome React Native](https://github.com/jondot/awesome-react-native)

另外一个React Native资源的汇总

#### 4）[读读日报：React Native（Android & iOS）](http://dudu.zhihu.com/circle/140816)

读读日报上面对React Native相关文章的专题。

> 文末摄影鉴赏

![](http://upload-images.jianshu.io/upload_images/191937-2f8b6ab023427d54.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
