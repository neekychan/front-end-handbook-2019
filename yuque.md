<!-- # 前端开发者手册2019
 -->
**[Cody Lindley](http://codylindley.com/) 编著 [原文地址](https://frontendmasters.com/books/front-end-handbook/2019/)**

本手册由[Frontend Masters](https://frontendmasters.com/)赞助，通过深入现代化的前端工程课程来提高你的技能。

下载：[PDF](https://github.com/FrontendMasters/front-end-handbook-2019/raw/master/exports/Front-end%20Developer%20Handbook%202019.pdf) | [epub](https://github.com/FrontendMasters/front-end-handbook-2019/raw/master/exports/Front-End%20Developer%20Handbook%202019.epub)

翻译&校验：[neekychan](https://github.com/neekychan)([微博](https://weibo.com/cwlay)) 和 [freedom](https://github.com/yylifen) 

<img src="https://frontendmasters.com/books/front-end-handbook/2019/assets/images/FM_2019Cover_final.jpg" alt="前端开发者手册2019" title="前端开发者手册2019" height="600" />

### 概要

这是一本每个人都可以用来学习前端开发实践的指南。它大致总结和讨论了前端工程的实践：如何学习它以及在2019年实践它时会使用到的工具。

它是专门为以后准备从事前端开发和目前正在实践前端开发的人提供专业的学习材料和开发工具等资源而编写的。其次，它可以被管理人员、CTO、讲师和猎头用来了解前端开发的实践。

本手册的内容包含Web技术（HTML、CSS、DOM 和 JavaScript）及直接构建在这些开源技术之上的解决方案。书中引用和讨论的材料要么是课堂上最好的，要么是解决问题的最新材料。

本书对于前端开发者而言，不应该被认为是对所有资源的综合概述。其价值在于对足够多的分类信息进行简洁、集中、及时地整合，以免有人会偏向于某个领域苦苦探索。

这本手册的内容更新每年发布一次。到目前为止，这已经是第四年发布的版本。

**在手册中有什么：**

第0章介绍了今年前端开发的简要回顾和发展趋势。第1章和第2章简要介绍了前端开发的规则和实践。第3章和第4章组织并推荐了学习路径和资源。第5章组织和列出前端开发者使用的工具，第6章重点介绍前端信息的来源。

**欢迎在Github中贡献内容、提供建议和修正：**

[https://github.com/FrontendMasters/front-end-handbook-2019](https://github.com/FrontendMasters/front-end-handbook-2019)

## 第0章 回顾2018并展望未来

### 0.1 回顾2018

- React在去年发布了几个值得关注的版本，包括[生命周期函数](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#component-lifecycle-changes)、[context API](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#official-context-api)，[suspense](https://reactjs.org/docs/react-api.html#reactsuspense)、[React hooks](https://reactjs.org/docs/hooks-intro.html)。

- [微软终于收购了Github](https://news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/)。

- [用CSS可以创建字体啦](https://yusugomori.com/projects/css-sans/)。

- 过去我称之为前端驱动的应用程序，被称作[“无服务”](https://thepowerofserverless.info/)。不幸的是，这言过于实了。然而，[JAMstack](https://jamstack.org/)这个术语似乎确实引起了很多开发者的[共鸣](https://jamstackconf.com/nyc/)。

- 谷歌今年提供了一些简洁的工具来帮助网页加载更快，比如[squoosh](https://github.com/GoogleChromeLabs/squoosh/)和[quicklink](https://github.com/GoogleChromeLabs/quicklink)

- [Vue](https://risingstars.js.org/2018/en/#section-framework)今年比React获得更多的[Github star](https://hasvuepassedreactyet.surge.sh/)。但[使用](https://www.npmjs.com/browse/depended)[方面](https://2018.stateofjs.com/front-end-frameworks/overview/)React仍然占据主导地位。

- [RE:DOM](https://github.com/redom/redom)引入了一个类似于React的解决方案，但没有使用虚拟DOM和JSX。

- [DeskGap](https://deskgap.com/)和[Neutralino.js](https://neutralino.js.org/)作为NW.js和Electron的替代品出现。

- 2017年，[HTML和CSS前端开发者](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06)与[应用程序前端开发者](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06)之间产生了[巨大的](https://medium.com/@jerrylowm/the-death-of-front-end-developers-803a95e0f411)分歧。2018年，[分歧变得越来越大、越来越深](https://css-tricks.com/the-great-divide/)，且越来越多[人](https://rachelandrew.co.uk/archives/2019/01/30/html-css-and-our-vanishing-industry-entry-points/)开始[感受到](https://hackernoon.com/the-backendification-of-frontend-development-62f218a773d4)[这种](http://bradfrost.com/blog/post/big-ol-ball-o-javascript/)[分歧](https://justmarkup.com/log/2018/11/just-markup/)。

- 今年，和最近几年一样，有成堆的应用和框架的解决方案尝试角逐成为主流的JavaScript应用程序工具（例如[React、Angular、Vue等](https://stateofjs.com/2017/front-end/results)）让我为你列举一下，它们是[Radi.js](https://radi.js.org/), [DisplayJS](https://display.js.org/), [Stimulus](https://stimulusjs.org/), [Omi](https://github.com/Tencent/omi), [Quasar](https://quasar-framework.org/)。

- JavaScript框架开始提供自己的语言使其编译成JavaScript（例如[Mint](https://www.mint-lang.com/)）。

- [CodeSandbox](https://codesandbox.io/)逐渐成为在线代码共享的主流解决方案。

- [CSS Grid](https://cssgridgarden.com/)和[CSS Flexbox](https://flexboxfroggy.com/)已经完全被现代浏览器所支持，并且得到了一些重大的进展。但许多人仍然对[使用哪一种和如何使用](https://css-irl.info/to-grid-or-to-flex/)存在[困惑](https://www.youtube.com/watch?v=hs3piaN4b5I)。

- 许多人已经意识到使用类型体系（例如TypeScript和Flow）的长期成本。有些人得出的结论是，基于类型体系与基于模块体系（如AMD、Require.js）并不一样，前者带来的问题远比其[解决方案](https://medium.com/javascript-scene/the-typescript-tax-132ff4cb175b)更多。至少，许多开发者意识到，如果在大型代码库中需要类型，那么与包含类型的语言([Reason](https://reasonml.github.io/)、[Purescript](http://www.purescript.org/)、[Elm](https://elm-lang.org/))相比，束缚在类型体系中并不理想。

- [CSS变量](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)在现代Web浏览器当中得到了[支持](https://caniuse.com/#feat=css-variables)。

- [CSS in JS](http://michelebertoli.github.io/css-in-js/)风格爆发了，[有些](http://bradfrost.com/blog/link/whats-wrong-with-css-in-js/)人却对此产生了质疑。

- [ES模块](https://caniuse.com/#search=modules)已经可以在现代浏览器中使用，[动态导入](https://developers.google.com/web/updates/2017/11/dynamic-import#dynamic)也即将支持。我们甚至看见围绕这一事实的一些[工具](https://www.pikapkg.com/blog/introducing-pika-pack/)因此发生变化。

- 许多人认识到端到端的测试方式是正确地进行测试的起点，这在很大程度上要归功于[Cypress](https://www.cypress.io/how-it-works/)(换而言之，先Cypress，再[Jest](https://jestjs.io/))。

- 虽然[Webpack](https://webpack.js.org/)今年再次被大量使用，但许多开发者发现[Parcel](https://github.com/parcel-bundler/parcel)更容易启动和运行。

- 今年最重要的问题之一是，[JavaScript的成本](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)是多少？

- 今年[Babel 7 发布](https://babeljs.io/blog/2018/08/27/7.0.0)，这可是一件大事，因为距离上一次大版本发布已经是三年前了。

- 大家意识到JavaScript变化太快的事实之后，开始[谈论](https://www.robinwieruch.de/javascript-fundamentals-react-requirements/)在你学习诸如React之类的东西之前需要知道什么。竞争是实实在在的。

- 大多数开发者通过[Apollo](https://www.apollographql.com/)[发现了](https://blog.bitsrc.io/why-does-everyone-love-graphql-17de7f99f05a)GraphQL，并将其视为数据API的下一个发展方向。

- 在[NPM和Yarn](https://css-tricks.com/why-npm-scripts/)上Gulp及其相关工具退居二线，但这并未能阻止微软与[Just](https://github.com/Microsoft/just)合作。

- 今年，人们不仅可以lint/hint HTML、CSS和JavaScript，还可以对Web自身[lint/hint](https://webhint.io/)。

- [《2018年前端工具调查报告》](https://ashleynolan.co.uk/blog/frontend-tooling-survey-2018-results)值得一读，就算你仅仅是想了解jQuery还有多少使用量。

- [无可否认](https://2018.stateofjs.com/javascript-flavors/typescript/)，[TypeScript](https://www.typescriptlang.org/)今年收获了大量用户。

- [VScode](https://code.visualstudio.com/)成为了代码编辑器的[首选](https://triplebyte.com/blog/editor-report-the-rise-of-visual-studio-code)。

### 0.2 展望2019

- 以后希望会有更多这样的事情发生。“[远离Sass](https://cathydutton.co.uk/posts/why-i-stopped-using-sass/)”。

- 通过[https://cssdb.org](https://cssdb.org)关注和学习CSS即将新增的功能（和可能新增的功能），仍然是一个不错的主意。

- Google的[WebP](https://developers.google.com/speed/webp/)图像格式[今年得到大部分现代浏览器的支持](https://caniuse.com/#feat=webp)。

- [Prepack](https://prepack.io/)将继续发展。

- [GraphQL](https://graphql.org/)将继续被大量采用。

- 2019年，“[JavaScript现状](https://stateofjs.com/)”调查的作者将新增“[CSS现状](https://stateofcss.com/)”调查。

- 关注[Web动画API](https://caniuse.com/#feat=web-animation)。

- 你认识的人会尝试说服你去使用[TypeScript](https://www.typescriptlang.org/)。

- [swc-project](https://github.com/swc-project/swc)将会与Babel竞争一席之地。

- [JAMStack](https://jamstack.org/)将会[继续](https://jamstackconf.com/nyc/)。

- [一套代码多端运行的趋势仍会继续](https://quasar-framework.org/)。

- 对于[大型代码库](https://github.com/twbs/bootstrap/pull/23586)，更多开发者将会转向像[ReasonML](https://www.imaginarycloud.com/blog/reasonml-react-as-first-intended/)这样的语言，而不是JavaScript或者TypeScript。

- 此外，越来越多项目开始抛弃jQuery，转而使用原生DOM的解决方案。

- [Web组件](https://developer.mozilla.org/en-US/docs/Web/Web_Components)!在这一点上，我不知道Web组件将如何发挥作用。事实是，它们不会消失，一旦炒作结束，他们就不能获得太多的势头和使用。

## 第1章 前端开发者是什么？

本章阐述了前端开发和前端开发者训练的基本说明。

> *Web前端开发，也称为客户端开发，是为网站或Web应用程序生成HTML、CSS和JavaScript的实践，以便用户可以直接看到它们并与之交互。与前端开发相关的挑战是，用于前端创建网站的工具和技术不断变化，因此开发者需要持续了解该领域是如何发展的。*
>
> *设计一个网站的目的，就是确保当用户打开网站时，看到的信息被格式化成易于阅读且相关联的。更复杂的是，现在用户使用大量、不同的屏幕尺寸和分辨率的设备，从而迫使设计师在设计网站的时候不得不考虑这些问题，他们需要确保页面能够在不同的浏览器(跨浏览器)、不同的操作系统(跨平台)和不同的设备(跨设备)中正确运行，这就需要开发者进行仔细的规划。*
> 
> *— [维基百科](https://en.wikipedia.org/wiki/Front-end_web_development)*

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/what-is-front-end-dev.png)

*图片来源：[https://www.upwork.com/hiring/development/front-end-developer/](https://www.upwork.com/hiring/development/front-end-developer/)*

**前端开发者...**

前端开发者使用Web技术（[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)、[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)和[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)）来设计和开发网站以及Web应用，这些技术通常运行在[开放的Web平台](https://en.wikipedia.org/wiki/Open_Web_Platform)或作为非Web平台本地运行时环境(如[React Native](https://facebook.github.io/react-native/))。

一个人通过学习构建一个依赖于HTML、CSS和JavaScript的网站或Web应用程序进入前端开发领域。这些应用程序通常在[Web浏览器](https://en.wikipedia.org/wiki/Web_browser)中运行，但也能运行于[无头浏览器](https://en.wikipedia.org/wiki/Headless_browser)、[WebView](http://developer.telerik.com/featured/what-is-a-webview/)或者的本地运行时环境中运行。下面将详析这四种运行时场景：

**（最常见的）Web浏览器**

Web浏览器是用来检索、展示、遍历[WWW](https://en.wikipedia.org/wiki/World_Wide_Web)信息的软件。通常，浏览器运行在台式电脑或者笔记本电脑、平板电脑和手机上，但最近几乎能在任何设备（如冰箱、汽车等等）上找到浏览器。

最常见的Web浏览器（按[使用次数](https://en.wikipedia.org/wiki/Usage_share_of_web_browsers#Summary_tables)排序）是：

- [Chrome](http://www.google.com/chrome/)

- [Safari](http://www.apple.com/safari/)

- [Internet Explorer](https://en.wikipedia.org/wiki/Internet_Explorer) (备注: 不含[Edge](http://dev.modern.ie/), 特指IE9至IE11)

- [Firefox](https://www.mozilla.org/firefox/)

- [Edge](https://www.microsoft.com/en-us/windows/microsoft-edge)

**无头浏览器**

无头浏览器是一种**没有**图形用户界面的Web浏览器，可以通过命令行界面以编程方式控制该界面，以实现Web页面自动化(例如，功能测试、抓取、单元测试等)。
可以将无头浏览器看作可以从命令行以编程方式运行的浏览器，该命令行可以检索和遍历Web页面代码。

最常见的无头浏览器有：

- [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)

- [Zombie](https://github.com/assaf/zombie)

- [slimerjs](http://slimerjs.org/)

- [puppeteer](https://github.com/GoogleChrome/puppeteer)

**webview**

[webview](http://developer.telerik.com/featured/what-is-a-webview/)被用在原生操作系统上，在原生应用程序中运行Web页面。可以将[webview](http://developer.telerik.com/featured/what-is-a-webview/)想象成是网页浏览器的一个iframe或一个单标签，它被嵌入在设备里所运行的原生应用程序(例如，[iOS](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIWebView_Class/)、[android](http://developer.android.com/reference/android/webkit/WebView.html)、[windows](https://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.controls.webview.aspx))中。

[webview](http://developer.telerik.com/featured/what-is-a-webview/)开发最常见的解决方案有:

- [Cordova](https://cordova.apache.org/) (手机和平板的原生应用程序)

- [NW.js](https://github.com/nwjs/nw.js) (桌面应用程序)

- [Electron](http://electron.atom.io/) (桌面应用程序)

**Web原生技术**

最后，前端开发者可以从Web浏览器开发中学习到，编写代码不需要考虑浏览器引擎的限制。最近，开发环境正被设想成可以利用Web技术(例如，CSS和JavaScript)来构建原生应用程序，而不使用Web引擎。

这些环境的一些例子有:

- [Flutter](Flutter)

- [React Native](https://facebook.github.io/react-native/)

- [NativeScript](https://www.nativescript.org/)

> 注：
>
> 1、确定你已经清楚地理解了“Web平台”的含义。阅读“[Web开放平台](https://en.wikipedia.org/wiki/Open_Web_Platform)”的维基百科页面。探索构成Web平台相关的[众多技术](https://platform.html5.org/)。

## 第2章 前端开发实践：概要

本章节将从“前端开发者是如何形成的”开始，分析并广泛讲述前端开发工程的实践。

### 2.1 如何成为一名前端开发者

如何成为一名前端开发者呢？这个非常复杂的问题，可以根据下面的路线图思考一下：

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/frontend.png)
*图片来源: [https://github.com/kamranahmedse/developer-roadmap](https://github.com/kamranahmedse/developer-roadmap)*

现在一般来说，没人会指望大学毕业能取得前端工程学位。而且，我很少听到或见到有前端开发者，他们可能拥有一个不受欢迎的计算机科学学位或平面设计学位，最终却要专业地编写HTML、CSS和JavaScript。在我看来，现在从事前端工作的大多数人似乎都是自学成才的，或者是从设计和计算机科学领域跨界进入前端领域的。

如果你现在想开始成为一名前端开发者，我将大致遵循以下的流程开始说明（第3章和第4章会深入学习资源的更多细节）。

1. 大致了解[Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)[平台](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)是如何运作的。确保你了解[HTML、CSS、DOM、JavaScript、域名、DNS、URL、HTTP、浏览器和服务器与客户端](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)这些概念“是什么”和“使用在哪里”。不要从一开始就深入专研任何东西，只需要了解正在发挥作用的各个部分以及它们是如何组合在一起的。从构建简单的Web页面开始。

2. [学习HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)

3. [学习CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

4. 学习[JavaScript](https://youtu.be/QjKH1J77gjI?list=PL055Epbe6d5bQubu5EWf_kUNA3ef_qbmL)

5. 学习DOM

6. 学习用户界面设计的基础原理 (UI模式、交互设计、用户体验设计和可用性)

7. 学习CLI和命令行

8. 学习软件工程的实践（例如，应用程序设计与架构、模板、Git、测试、监控、自动化、代码质量和开发方法论）

9. 不要固执己见，用任何对你的大脑有意义的东西(例如，Webpack、React和Mobx)定制你的工具箱

10. 学习Node.js

简单地说一下学习建议，[在学习抽象概念前，先学习基础的底层技术](https://youtu.be/QjKH1J77gjI?list=PL055Epbe6d5bQubu5EWf_kUNA3ef_qbmL)。不要学习jQuery，先学DOM。不要学SASS，先学CSS。不要学习JSX，先学HTML，不要学TypeScript，先学JavaScript。不要学Handlebars，先学JavaScript ES6模板，不要学BootStrap，先学UI模式。

最近出现了许多未经认证的、昂贵的前端代码学校和训练营。这些学校通常是由那些来自官方学院的老师遵循传统教学模式授课（课程大纲、考试、小考、专题、小组专题和成绩等）。

谨记，如果你正考虑参加一个高价的培训项目，那就选择网上的吧！所有的知识你都可以从网上学到而且几乎不怎么花钱。然而，如果你需要某人告诉你如何低成本学习，你应该考虑传统的教师主导的课堂配置。除此之外，我不知道还有什么职业是可以通过互联网免费学习的、[每月几美元的录像课程会员资格](https://frontendmasters.com/join/)筛选费以及强烈的求知欲。

举个例子，如果你从今天就开始，以下有几个自学的资源供你选择：

- [从Web开始](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web) [阅读]

- [你想这样成为一名前端工程师吗](https://www.youtube.com/watch?v=Lsg84NtJbmI) [观看]

- [前端大师学习之路](https://frontendmasters.com/learn) [观看][付费]

- [Web开发介绍](https://frontendmasters.com/courses/web-development-v2/) [观看][付费]

- [Treehouse理工大学学位](https://teamtreehouse.com/techdegree/front-end-web-development-2) [观看][付费]

- [无学位的Web前端开发者](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001) [观看][付费]

- [成为Web前端开发者](https://www.lynda.com/learning-paths/Web/become-a-front-end-web-developer) [观看][付费]

- [freeCodeCamp](https://learn.freecodecamp.org/)[互动][观看]

当你准备开始的时候，你应该会对大部分复杂的内容感到担忧。抽象（例如，jQuery）落入错误的人手中，让人看起来是种高级的技能。但始终隐藏着一个事实，开发者对基础和底层的概念理解较差。

假设，在这个过程中你不单只是学习，也在实践你所学和研究的工具。有些人建议实践只是为了学习，当其他人建议只学习如何去实践的时候，我建议你找一种与你大脑运作方式相匹配的方法去实践。但是，可以肯定的是，这是一种融合。所以，不要只看不实践。学习，实践。学习，实践。不停地重复，因为事情总是变化得很快。这就是为什么要学习基本原理而不是抽象概念十分重要。

### 2.2 前端职称

[最近几年来，两种不同类型的前端开发者之间，在前端领域一直存在着巨大分歧](https://css-tricks.com/the-great-divide/)。一方面，专注于JavaScript的程序员，他们为前端运行时编写JavaScript，他们可能拥有计算机科学技能和软件开发背景。他们很可能视HTML和CSS为一种抽象（例如，[JSX](https://reactjs.org/docs/introducing-jsx.html)和[CSS in JS](https://hackernoon.com/all-you-need-to-know-about-css-in-js-984a72d48ebc)）。另一方面，很可能是非计算机科学出身的开发者，他们专注于HTML，CSS和JavaScript，因为它们专门属于UI。在2019年，进入或尝试了解前端开发者领域时，你能绝对能感受到这种分歧。“前端开发者”这个术语没有明确的定义，没有明确的词语来说明正在讨论的是哪种类型的前端开发者。

以下是各种前端职称的列表和描述（记住职称是[很难](https://blog.prototypr.io/dissecting-front-end-job-titles-7f72a0ef0bc5)）。最常用的前端开发者职称是，“前端开发者”或“前端工程师”。注意，任何带有“前端”，“客户端”，“Web UI”，“HTML”，“CSS”或“JavaScript”字眼职位的人，通常是指在HTML，CSS，DOM和JavaScript上有一定程度专业知识的人。

**前端开发者**：描述在一定程度上精通HTML、CSS、DOM和JavaScript并在Web平台上实现这些技术的开发者的通用职称。

**前端工程师（JavaScript开发者或全栈JavaScript开发者）**：这个职称授予给来自计算机科学、工程学背景，且能使用这些技术进行前端工作的开发者。这种角色一般要求具备计算机科学知识和多年的软件开发经验。当职称中包含“JavaScript应用程序”时，表明需要开发者必须是具有高级编程、软件开发和应用程序开发技能的高级JavaScript开发者，同时也拥有多年构建前端软件应用的经验。

**CSS和HTML开发者**：这个前端职称描述的是除了JavaScript和应用程序之外，开发者对HTML和CSS具有一定熟练度。

**Web前端设计师**：包含“设计师”的职称，表明设计师需要具备前端技能（HTML 和 CSS）以及专业的设计(视觉设计和交互设计)技能。

**UI（用户界面）**开发者或工程师：当头衔中包含“交互”和“UI”时，表明开发者除了应具备交互设计能力，还需具备前端开发者技能和前端工程师技能。

**移动或平板电脑前端开发者**：包含“移动”和“平板”的职称，有在移动或平板电脑设备运行的前端开发经验（要么是原生的，要么是在Web平台上，比如在浏览器上）。

**前端SEO专家**：包含“SEO”的职称，描述的是开发者具备以SEO策略来设计前端技术的丰富经验。

**前端无障碍专家**：包含“无障碍”的职称，描述的是开发者具备以支持无障碍要求和标准来设计前端技术的丰富经验。

**前端运维开发**：包含“运维开发”的职称，描述的是开发者具备与合作、集成、部署、自动化和质量相关软件开发实践的丰富经验。

**前端测试或QA**：包含“测试或QA”的职称，描述的是开发者具备测试和管理软件，包含单元测试，功能性测试，用户测试，A/B测试的丰富经验。

> 注：
>
> 1、如果你在职称中遇到“全栈”或“网页开发者”这些术语，被雇主用于描述负责Web或应用程序开发各个方面的角色。比如，前端（可能包括设计）和后端。

### 2.3 前端开发者必备的Web技能
![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/web-tech-employed.jpg)

下面是被前端开发者所使用的核心Web技能（可以考虑按顺序学习它们）：

1. 超文本链接（HTML）

2. 层叠样式表（CSS）

3. 同意资源定位（URLs）

4. 超文本传输协议（HTTP）

5. JavaScript编程语言（ECMAScript 262）

6. JavaScript对象表示法（JSON）

7. 文档对象模型（DOM）

8. Web API（HTML5以及相关 或 浏览器API）

9. Web内容无障碍指引（WCAG）& 无障碍的富网络应用程序（ARIA）

一个所有网页相关规范的综合性列表，请参阅[platform.html5.org](https://platform.html5.org/)或[MDN Web API](https://developer.mozilla.org/en-US/docs/Web/API)。

下面是刚刚提到的9种技术的定义，并提供了每种技术的相关文档和规范的链接。

**超文本标记链接（HTML）**

> *超文本标记语言，通常称为HTML，是一种用于创建网页的标准标记语言。Web浏览器能读取HTML文件并将其渲染成看可视化或可听的网页。HTML描述了一个网站的结构语义以及表示的线索，使之成为一种标记语言而非编程语言。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/HTML) & [中文地址](https://zh.wikipedia.org/wiki/HTML)*

大部分相关规范和文档：

- [W3C HTML规范大全](http://www.w3.org/standards/techs/html#w3c_all)

- [HTML元素]持续更新标准(https://html.spec.whatwg.org/multipage)

- [全局属性](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

- [W3C的HTML5.2标准](https://www.w3.org/TR/2017/REC-html52-20171214/)

- [W3C的HTML5.3标准](http://w3c.github.io/html/)

- [HTML属性参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
- [HTML元素参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

- [HTML语法]持续更新标准(https://html.spec.whatwg.org/multipage/syntax.html#syntax)

**层叠样式表（CSS）**

> *层叠样式表（CSS）是一种样式表语言，用于描述用标记语言编写的文档的外观和格式。尽管经常用于改变用HTML和XHTML所编写的网页和用户界面的样式，该语言能应用于任何类型的XML文档，包括纯XML、SVG和XUL。与HTML和JavaScript一样，CSS是基础技术，被大部分网站用于创建具有视觉吸引力的网页、Web应用程序的用户界面以及许多移动应用程序的用户界面的基础技术。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) & [中文地址](https://zh.wikipedia.org/wiki/%E5%B1%82%E5%8F%A0%E6%A0%B7%E5%BC%8F%E8%A1%A8)*

大部分相关规范和文档：

- [W3C CSS规范大全](http://www.w3.org/Style/CSS/current-work)

- [层叠样式表2.2版本（CSS 2.2）规范](https://www.w3.org/TR/CSS22/)

- [CSS参考](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

**超文本传输协议（HTTP）**

> *超文本传输协议（HTTP）一种用于分布式、协作的，超媒体信息系统的应用层协议。HTTP是WWW的数据通讯的基础。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) & [中文地址](https://zh.wikipedia.org/wiki/超文本传输协议)*

大部分相关规范：

- [超文本传输协议 -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)

- [HTTP/2](http://httpwg.org/specs/rfc7540.html)

**统一资源定位（URL）**

> *统一资源定位（URL）（也称为Web地址）是一种对资源的引用，指定了资源在计算机网络的位置和检索的机制。URL是一种特定类型的统一资源标识符(uniform resource identifier, URI)，尽管许多人将这两个术语混在一起使用。URL表示可访问指定资源的方法，但并非每个URI皆如此。URL常见于引用Web页面（http），但也用于文件传输(ftp)、电子邮件(mailto)、数据库访问(JDBC)和许多其他应用程序。*
> 
>*- [维基百科](https://en.wikipedia.org/wiki/Uniform_Resource_Locator) & [中文地址](https://zh.wikipedia.org/wiki/%E7%BB%9F%E4%B8%80%E8%B5%84%E6%BA%90%E5%AE%9A%E4%BD%8D%E7%AC%A6)*

大部分相关规范：

- [统一资源定位器（URL）](http://www.w3.org/Addressing/URL/url-spec.txt)

- [URL持续更新标准](https://url.spec.whatwg.org/)

**文档对象模型（DOM）**

> *文档对象模型(Document Object Model, DOM)是一种在跨平台和语言无关性的约定，用于表示HTML，XHTML和XML文档中的对象并与之交互。每个文档的节点都组织在一个树结构中，称为DOM树。可以使用对象上的方法对DOM树中的对象进行寻址和操作。DOM的公共接口在其应用程序编程接口(API)中指定。*
>
>*- [维基百科](https://en.wikipedia.org/wiki/Document_Object_Model) & [中文地址](https://zh.wikipedia.org/wiki/%E6%96%87%E6%A1%A3%E5%AF%B9%E8%B1%A1%E6%A8%A1%E5%9E%8B)*

大部分相关规范和文档：

- [DOM持续更新标准](https://dom.spec.whatwg.org/)

- [W3C DOM4](https://www.w3.org/TR/domcore/)

- [UI事件](https://www.w3.org/TR/uievents/)

**JavaScript编程语言（ECMAScript 262）**

> *JavaScript是一种高级、动态、无类型和解释的编程语言。它已通过ECMAScript实现语言的标准化。除了HTML和CSS，它也是万维网内容生产中三大基本技术之一。大多数网站中都采用这种技术，并且已被所有的现代Web浏览器所支持，不需要插件。JavaScript是一门基于原型、函数先行的语言，是一门多范式的语言，它支持面向对象编程、命令式编程以及函数式编程。它有一个用于处理文本、数组、日期和正则表达式的API，但不包括任何I/O操作，比如网络、存储或图形工具，这些都依赖于它所嵌入的主机环境。*
> 
> *- [维基百科](https://en.wikipedia.org/wiki/JavaScript) & [中文地址](https://zh.wikipedia.org/wiki/JavaScript)*

大部分相关规范和文档：

- [ECMAScript® 2018 语言规范](http://ecma-international.org/ecma-262/9.0/index.html#Title)

- [ECMAScript语言规范大全](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources)

**Web API (HTML5以及相关)**

> *当使用JavaScript为Web编写代码时，有非常多可用的API。下面列出了开发Web应用程序或站点时可能使用的所有接口(即对象类型)。*
> 
> *- [Mozilla](https://developer.mozilla.org/en-US/docs/Web/API)*

大部分相关文档：

- [Web API接口](https://developer.mozilla.org/en-US/docs/Web/API)

**JavaScript对象表示法（JSON）**

> *这是一种用于异步浏览器和服务器通信(AJAJ)的主要数据格式，在很大程度上替代了XML（被AJAX使用）。虽然JSON最初源于JavaScript脚本语言，但它是一种独立于语言的数据格式。解析和生成JSON数据的代码在许多编程语言中都是可用的。JSON格式最初由Douglas Crockford所制定。它目前由两个相互竞争的标准描述，RFC 7159和ECMA-404。ECMA标准非常简单，只描述允许的语法语法，而RFC还提供了一些语义和安全性方面的考虑。JSON的正式网络媒体类型是application/json。JSON的文件扩展名是.json。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/JSON) & [中文地址](https://zh.wikipedia.org/wiki/JSON)*

大部分相关规范：

- [JSON介绍](http://json.org/)

- [JSON API](http://jsonapi.org/)

- [JSON数据交换格式](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

**Web内容无障碍指南(WCAG)和无障碍的富互联网应用程序(ARIA)**

> *无障碍是指为残疾人设计产品、设备、服务或环境。无障碍设计的概念确保了两者的“直接访问”(即和“间接访问”，意思是与某人的辅助技术(例如，计算机屏幕阅读器)的兼容性。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/Accessibility) & [中文地址](https://zh.wikipedia.org/zh-cn/%E7%B6%B2%E9%A0%81%E8%A6%AA%E5%92%8C%E5%8A%9B)*

- [网页无障碍倡议（WAI）](https://www.w3.org/WAI/standards-guidelines/)

- [Web内容无障碍指南（WCAG）的现状](http://www.w3.org/standards/techs/wcag#w3c_all)

### 2.4 潜在的前端开发者技能
![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/front-end-skills.png)
*图片来源：[http://blog.naustud.io/2015/06/baseline-for-modern-front-end-developers.html](http://blog.naustud.io/2015/06/baseline-for-modern-front-end-developers.html)*

对于任何一种专业类型的前端开发者角色，假设已经具备对HTML、CSS、DOM、JavaScript、HTTP、URL和Web浏览器这些基本技能的高级理解。

除了上述的技能，前端开发者可能还需要特别擅长以下一项或多项技能:

- 内容管理系统(CMS)

- Node.js

- 跨浏览器测试

- 跨平台测试

- 单元测试

- 跨设备测试

- 无障碍和WAI-ARIA

- 搜索引擎优化（SEO）

- 交互或用户界面设计

- 用户体验

- 可用性

- 电商系统

- 门户系统

- 线框图

- CSS布局和网格

- DOM操作（比如：jQuery）

- 移动端的Web性能

- 加载测试

- 性能测试

- 渐进式增强和优雅降级

- 版本控制（比如：Git）

- MVC、MVVM、MV*

- 函数式编程

- 数据格式 （比如：JSON，XML）

- 数据API (比如：Restful API)

- Web字体嵌入

- 矢量图形（SVG）

- 正则表达式

- 微数据和微格式

- 任务运行器，构建工具，自动化进程工具

- 响应式网页设计

- 面向对象编程

- 应用程序框架

- 模块

- 依赖管理

- 包管理

- JavaScript动画

- CSS动画

- 图表和图形

- UI部件

- 代码质量测试

- 代码覆盖测试

- 代码复杂度分析

- 集成测试

- 命令行和CLI

- 模板策略

- 模板引擎

- 单页应用

- Web和浏览器安全性

- 浏览器开发者工具

### 2.5 前端开发者跨设备开发

前端开发者使用HTML、CSS和JS，通常运行在以下操作系统(简称OS)的[web平台](http://tess.oconnor.cx/2009/05/what-the-web-platform-is)(例如Web浏览器)上：

- [Android](https://www.android.com/)

- [Chromium](https://www.chromium.org/chromium-os)

- [iOS](https://developer.apple.com/ios/)

- [OS X(例如： MacOS)](https://www.apple.com/macos)

- [Ubuntu(或某个Linux操作系统)](https://www.ubuntu.com/)

- [Windows](https://www.microsoft.com/en-us/windows)

通常这些操作系统运行在以下一种或多种设备上：

- 台式电脑

- 手提电脑和上网本

- 手机

- 平板电脑

- 电视

- 手表

- [其他](https://en.wikipedia.org/wiki/Internet_of_things)（例如：任何能想象的到的东西，汽车、冰箱、电灯、恒温器等等）

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/growth-iot.jpg)

*图片来源:[https://www.enterpriseirregulars.com/104084/roundup-internet-things-forecasts-market-estimates-2015/](https://www.enterpriseirregulars.com/104084/roundup-internet-things-forecasts-market-estimates-2015/)*


普遍来说，前端技术能够运行在上述操作系统和使用在以下运行时的Web平台设备中：

- 网页浏览器（例如：[Chrome，IE，Safari，Firefox](http://outdatedbrowser.com/en)）

- 无头浏览器（例如：[Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)）

- [WebView](http://developer.telerik.com/featured/what-is-a-webview/)或浏览器标签（[iframe](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)）被嵌入在原生应用中，桥接原生API运行。WebView应用通常包含由Web技术构造的UI。（例如：HTML、CSS和JS）（例如：[Apache Cordova](https://cordova.apache.org/)、[NW.js](http://nwjs.io/)、 [Electron](http://electron.atom.io/)）

- 由Web技术构建的原生应用程序，在运行时通过原生API的桥接进行解析。UI将使用原生UI部分（例如：iOS原生控制）而非Web技术。（例子：[NativeScript](https://www.nativescript.org/)，[React Native](https://facebook.github.io/react-native/)）

### 2.6 团队的前端

前端开发者通常只是团队中设计和开发Web站点、web应用程序或基于web技术运行的原生应用程序的一员。

一个为Web平台构建**专业**Web站点或软件的开发团队，通常至少包含以下角色。

- 视觉设计师（字体、色彩、间距、表情、视觉概念与主题）

- UI设计师、交互设计师、信息体系结构师（线框，指定所有用户的交互和UI功能，结构化信息）

- 前端开发者（编写可以运行在客户端或设备上的代码）

- 后端开发者（编写运行在服务器的代码）

这些角色是依据重叠的技能排序的。前端开发者通常比后端开发更擅长于处理UI或交互设计以及后端开发。团队成员通过承担重叠角色的职责来担任多个角色的情况并不少见。

假设上面提到的团队是由项目负责人或某种产品负责人(即，利益相关者、项目经理、项目负责人等等)

一个更大的web团队可能包括以下上面没有提及到的角色:

- SEO分析师

- 开发运维工程师

- 性能工程师

- API开发者

- 数据库管理员

- QA工程师或测试员

### 2.7 全栈开发者

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/full-stack.jpg)

全栈开发者这个称谓有几种含义。如此之多，以至于这个称谓尚未有一个明确的定义。仅考虑下面所展示的两个调查结果。这些结果可能更可信，成为一名全栈开发者是很常见的。但是，在我近20年的经验中，这绝不是专业领域的普遍情况。

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/fullstack1.png)

*图片来源: [https://medium.freecodecamp.com/we-asked-15-000-people-who-they-are-and-how-theyre-learning-to-code-4104e29b2781#.ngcpn8nlz](https://medium.freecodecamp.com/we-asked-15-000-people-who-they-are-and-how-theyre-learning-to-code-4104e29b2781#.ngcpn8nlz)*

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/fullstack2.png)

*图片来源: [https://insights.stackoverflow.com/survey/2017#developer-profile-specific-developer-types](https://insights.stackoverflow.com/survey/2017#developer-profile-specific-developer-types)*

设计和开发一个网站或web应用程序的角色需要在视觉设计、UI和交互设计、[前端开发](https://github.com/kamranahmedse/developer-roadmap#-front-end-roadmap)和[后端开发](https://github.com/kamranahmedse/developer-roadmap#-back-end-roadmap)等领域拥有深厚的技能和丰富的经验。任何能在专业水平上胜任以上这4个角色中的一个或多个的人都是极其罕见的。

从实用的角度来看，你应该寻求成为这些角色(视觉设计、交互设计或IA、前端开发、后端开发)之一的专家，或者寻求聘请这样的专家。那些声称在一个或多个这样的角色上具有专家水平的人是非常稀有的。

然而，考虑到JavaScript已经涵盖了技术栈的所有层面(即Node.js)，寻找一个既能开发前端和后端的全栈JS开发者已经不是那么神秘了。通常，这些全栈开发者只能解决JavaScript。一个能为前端、后端、API和数据库代码的开发者不再像以前那样荒谬(不包括视觉设计、交互设计和CSS)。在我看来依旧很神秘，但不再像以前那样不寻常。因此，我不建议开发者成为一名"全栈"开发者。在少数情况下，这行得通。但一般来说，作为一个塑造职业生涯的一般概念上前端开发者，我会专注于前端技术。

### 2.8 前端面试

**准备：**

- [2017年前端开发者面试准备](http://davidshariff.com/blog/preparing-for-a-front-end-web-development-interview-in-2017/)

- [出色的前端面试](https://medium.freecodecamp.com/cracking-the-front-end-interview-9a34cd46237)

- [前端面试手册](https://github.com/yangshun/front-end-interview-handbook)

- [前端面试流程揭秘](https://dev.to/emmawedekind/decoding-the-front-end-interview-process-14dl)

**测试:**

- [Web前端开发测试](http://davidshariff.com/quiz/)

- [JavaScript Web测试](http://davidshariff.com/js-quiz/)


**你可能会被问到的问题:**

- [所有JavaScript开发者都应该知道的10个面试题](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

- [前端职位面试题](http://h5bp.github.io/Front-end-Developer-Interview-Questions/)

- [Web前端开发测试](http://davidshariff.com/quiz/)

- [前端开发者面试题](http://thatjsdude.com/interview/index.html)

- [（由一位前端工程师所编著的）前端JavaScript最佳面试题](https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-(Written-by-a-Frontend-Engineer))

**你的提问:**

- [一份开发者可向未来老板提问的开放列表](https://github.com/ChiperSoft/InterviewThis)

### 2.9 前端求职公告

存在大量的技术职位招聘渠道。以下精简的列表是当前用于寻求前端职位/职业最相关资源。

- [authenticjobs.com](authenticjobs.com)

- [careers.stackoverflow.com](careers.stackoverflow.com)

- [css-tricks.com/jobs](css-tricks.com/jobs)

- [frontenddeveloperjob.com](frontenddeveloperjob.com)

- [glassdoor.com](glassdoor.com)

- [jobs.github.com](jobs.github.com)

- [linkedin.com](linkedin.com)

- [remote.co](remote.co)

- [weworkremotely.com](weworkremotely.com)

- [www.smashingmagazine.com/jobs/](www.smashingmagazine.com/jobs/)

> 注：
>
> 1、想作为一个前端开发者进行远程工作，留意这些相关的[远程办公公司](https://github.com/jessicard/remote-jobs)。

### 2.10 前端薪酬

美国全国的平均水平，一个中级前端开发者的薪酬在6.5万美元到10万美元之间。

当然，对于刚刚进入前端领域的新人来说，大概是40K美元，这取决于你工作的地点和经验。

> 注：
>
> 1、一个领导级别或者高级的前端开发者或工程师可以住他想住的任何地方（也就是远程办公）而且年薪超过15万美元（访问[angel.co](https://angel.co/jobs)、注册、留意超过15万美元年薪的前端职位或在[Stack Overflow Jobs](https://stackoverflow.com/jobs?q=front-end&sort=y)测试你的薪水范围）

## 第3章 学习前端开发：自学资源和建议

本章重点介绍了个人可以用来指导自己的学习过程和成为职业的前端开发者的许多资源（视频培训，书籍等）。

所有的学习资源（文章，书籍，视频，截屏视频等）将包括免费和付费资料之分。 付费材料将以[付费]表示。

### 3.1 学习互联网Web

> *互联网是一个互联计算机网络的全球系统，它使用互联网协议套件（TCP/IP）连接全球数十亿台设备。 它是一个由数百万个本地到全球范围的私人、公共、学术、商业和政府网络组成的网络中的网络，通过广泛的电子、无线和光纤网络技术相互连接。 因特网承载广泛的信息资源和服务，例如互联超文本文档和万维网（WWW）的应用、电子邮件、电话和用于文件共享的对等网络。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Internet) & [中文地址](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91)*

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/how-the-internet-works.jpg)

*图片来源: [https://www.helloitsliam.com/2014/12/20/how-the-internet-works-infographic/](https://www.helloitsliam.com/2014/12/20/how-the-internet-works-infographic/)*

* [什么是互联网？](https://www.youtube.com/watch?v=Dxcc6ycZ73M) \[观看\]

* [互联网基础](http://internetfundamentals.com) \[观看\]

* [网络如何运作](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) \[阅读\]

* 互联网如何运作？ [https://developer.mozilla.org/en-US/docs/Learn/Common\_questions/How\_does\_the\_Internet_work](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work) 和[http://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm](http://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm) \[阅读\]

* [互联网如何运作](https://www.khanacademy.org/partner-content/code-org/internet-works) \[观看\]

* [互联网在5分钟内如何运作](https://www.youtube.com/watch?v=Dxcc6ycZ73M) \[观看\]

* [网络如何运作](https://www.eventedmind.com/classes/how-the-web-works-7f40254c) \[观看\]

* [什么是互联网？ 或者，“你说Tomato，我说TCP / IP”](http://www.20thingsilearned.com/en-US/what-is-the-internet/1) \[阅读\]

* [不要害怕上网](http://www.dontfeartheinternet.com/)

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/who-runs-the-internet-infographic.jpg)

*图片来源: [http://www.bitrebels.com/technology/find-out-who-runs-the-internet-chart/](http://www.bitrebels.com/technology/find-out-who-runs-the-internet-chart/)*

### 3.2 学习Web浏览器

> *Web浏览器（通常称为浏览器）是用于在万维网上检索，呈现和遍历信息资源的软件应用程序。 信息资源由统一资源标识符（URI/URL）标识，并且可以是网页、图像、视频或其他内容。 资源中存在的超链接使用户能够轻松地将其浏览器导航到相关资源。 虽然浏览器主要用于万维网，但它们也可用于访问私有网络中的Web服务器或文件系统中的文件提供的信息。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Web_browser) & [中文地址](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%A1%B5%E6%B5%8F%E8%A7%88%E5%99%A8)*

**（在桌面和移动设备上）[最常用的浏览器](https://netmarketshare.com/?options=%7B%22filter%22%3A%7B%22%24and%22%3A%5B%7B%22deviceType%22%3A%7B%22%24in%22%3A%5B%22Desktop%2Flaptop%22%2C%22Mobile%22%5D%7D%7D%5D%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22browser%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22browsersDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222018-01%22%2C%22dateEnd%22%3A%222018-12%22%2C%22segments%22%3A%22-1000%22%7D)是：**

1. Chrome（引擎：Blink + V8）

2. Firefox（引擎：Gecko + SpiderMonkey）

3. Internet Explorer（引擎：Trident + Chakra）

4. Safari（引擎：Webkit + SquirrelFish）

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/statcounter.png)

*图片来源: [http://gs.statcounter.com/browser-market-share](http://gs.statcounter.com/browser-market-share)*

**浏览器和Web技术（API）的演变**

* [evolutionoftheweb.com](http://www.evolutionoftheweb.com/) \[阅读\]

* [网络浏览器的时间表](https://en.wikipedia.org/wiki/Timeline_of_web_browsers) \[阅读\]

**最常用的[无头浏览器](http://www.asad.pw/HeadlessBrowsers/)是：**

* [无头Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md) (引擎: [Blink](https://www.chromium.org/blink) \+ V8)

* [SlimerJS](http://slimerjs.org/) (引擎: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) \+ [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))

**浏览器如何工作**

* [我学到的关于浏览器和网络的20件事](http://www.20thingsilearned.com/en-US/foreword/1) \[阅读\]

* [CSS速成：浏览器如何布局网页](http://dbaron.org/talks/2012-03-11-sxsw/master.xhtml) \[阅读\]

* [浏览器如何工作：现代网络浏览器的幕后](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) \[阅读\]

* [聚焦Quantum：什么是浏览器引擎？](https://hacks.mozilla.org/2017/05/quantum-up-close-what-is-a-browser-engine/)

* [浏览器渲染网站的真相是什么](https://www.youtube.com/watch?v=SmE4OwHztCc) \[观看\]

* [是什么导致重排](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) \[阅读\]

* [每个前端开发者应该知道的关于网页渲染的内容](http://frontendbabel.info/articles/webpage-rendering-101/) \[阅读\]

**浏览器优化：**

* [浏览器渲染优化](https://www.udacity.com/course/browser-rendering-optimization--ud860) \[观看\]

* [网站性能优化](https://www.udacity.com/course/website-performance-optimization--ud884) \[观看\]

**浏览器比较**

* [Web浏览器的比较](https://en.wikipedia.org/wiki/Comparison_of_web_browsers) \[阅读\]

**浏览器Hack**

* [browserhacks.com](http://browserhacks.com/) \[阅读\]

**浏览器开发**

前端开发者过去花了很多时间在几个不同的浏览器中开发代码。 这个问题曾经比今天严重多了。 现在，抽象工具（例如，React，Webpack，Post-CSS，Babel等）与现代浏览器相结合，使浏览器开发变得相当容易。 新的挑战不是用户将使用哪种浏览器，而是他们将在哪个设备上运行浏览器。

**安全浏览器**

大多数现代浏览器的最新版本被认为是安全浏览器。 也就是说，理论上，它们应该在不提示用户的情况下自动更新。 这种向自我更新浏览器的转变一直是对不自动更新的旧浏览器缓慢替代的过程。

**浏览器的选择**

截至今天，大多数前端开发者使用Chrome和“Chrome Dev Tools”来开发前端代码。 但是，最常用的现代浏览器都提供了一种开发者工具。 选择哪一个作为开发工具是主观的。 更重要的问题是知道有哪些浏览器，你必须支持哪些设备，然后进行适当的测试。

### 3.3 学习域名系统（DNS）

> *域名系统（DNS）是用于计算机、服务、连接到Internet或专用网络的任何资源的分层分布式命名系统。 它将各种信息与分配给每个参与实体的域名相关联。 最重要的是，它将人们可以轻易记忆的域名转换为全球计算机服务和设备所需的数字IP地址。 域名系统是大多数互联网服务功能的重要组成部分，因为它是互联网的主要目录服务。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/Domain_Name_System) & [中文地址](https://zh.wikipedia.org/wiki/%E5%9F%9F%E5%90%8D%E7%B3%BB%E7%BB%9F)*

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/how_dns_works.jpg)

*图像来源: [http://www.digital-digest.com/blog/DVDGuy/wp-content/uploads/2011/11/how\_dns\_works.jpg](http://www.digital-digest.com/blog/DVDGuy/wp-content/uploads/2011/11/how_dns_works.jpg)*

* [DNS术语、组件和概念介绍](https://www.digitalocean.com/community/tutorials/an-introduction-to-dns-terminology-components-and-concepts) \[阅读\]

* [DNS解析](https://www.youtube.com/watch?v=72snZctFFtA) \[观看\]

* [DNS如何工作](https://howdns.works/ep1/) \[阅读\]

* [互联网：IP地址和DNS](https://www.youtube.com/watch?v=5o8CwafCxnU&index=3&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7) \[观看\]

* [什么是域名？](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name) \[阅读\]

### 3.4 学习HTTP网络协议（包括CORS和WebSockets）

> *<b>HTTP</b> — 超文本传输协议（HTTP）是用于分布式协作超媒体信息系统的应用程序协议。 HTTP是万维网数据通信的基础。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) & [中文地址](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)*

**HTTP说明**

* [HTTP/2](https://http2.github.io/)

* [超文本传输协议 -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)

**HTTP文档**

* [MDN HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) \[观看\]

**HTTP视频、文章和教程**

* [高性能浏览器网络：每个Web开发者应该了解的关于网络和Web性能的内容](http://chimera.labs.oreilly.com/books/1230000000545/index.html) \[观看\]

* [MDN: HTTP概述](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) \[观看\]

* [HTTP: 权威指南](https://www.amazon.com/HTTP-Definitive-Guide-Guides/dp/1565925092/ref=cm_cr_arp_d_product_top?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=11b990b79d33ddbef63712765715a9c1&camp=1789&creative=9325) \[观看\]\[付费\]

* [HTTP/2常见问题](https://http2.github.io/faq/#what-are-the-key-differences-to-http1x) \[观看\]

* [HTTP基本原理](http://www.pluralsight.com/courses/xhttp-fund) \[观看\]\[付费\]

* [HTTP/2基本原理](https://app.pluralsight.com/library/courses/http2-fundamentals/table-of-contents) \[观看\]\[付费\]

* [HTTP: 每个Web开发者都必须知道的协议 - 第一部分](http://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177) \[观看\]

* [HTTP: 每个Web开发者必须知道的协议 - 第2部分](http://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155) \[观看\]

* [HTTP简介](http://code.tutsplus.com/series/http-succinctly--net-33683) \[观看\]

**HTTP状态码**

* [HTTP状态码](https://httpstatuses.com/)

* [一分钟速学HTTP状态码](http://webdesign.tutsplus.com/tutorials/http-status-codes-in-60-seconds--cms-24317) \[观看\]

> *<b>CORS</b> — 跨域资源共享（CORS）是一种允许从来自资源的域外的另一个域请求网页上的受限资源（例如，字体）的机制。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing) & [中文地址](https://zh.wikipedia.org/wiki/%E8%B7%A8%E4%BE%86%E6%BA%90%E8%B3%87%E6%BA%90%E5%85%B1%E4%BA%AB)*

**CORS说明**

* [跨域资源共享](https://www.w3.org/TR/cors/)

**CORS**

* [CORS实践](https://www.amazon.com/CORS-Action-Creating-consuming-cross-origin/dp/161729182X/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=47ebd885d688a4ed69f77a1bd8273f8a&camp=1789&creative=9325) \[观看\]\[付费\]

* [HTTP访问控制 (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS) \[观看\]

> *<b>WebSocket</b> — WebSocket是一种通过单个TCP连接提供全双工通信通道的协议。WebSocket协议在2011年由IETF标准化为RFC 6455，Web IDL中的WebSocket API由W3C标准化。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/WebSocket) & [中文地址](https://zh.wikipedia.org/wiki/WebSocket)*

**WebSocket**

* [使用WebSocket连接Web](https://code.tutsplus.com/courses/connect-the-web-with-websockets) \[观看\]

* [WebSocket：轻量级的客户端 — 服务器通信](https://www.amazon.com/WebSocket-Client-Server-Communications-Andrew-Lombardi/dp/1449369278/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=dd39395cf3d2ab4fc7c820d7c19db39a&camp=1789&creative=9325) \[观看\]\[付费\]

* [WebSocket协议](https://tools.ietf.org/html/rfc6455) \[观看\]

### 3.5 学习虚拟主机

> *网络托管服务是一种互联网托管服务，允许个人和组织通过万维网访问其网站。 Web主机是指在客户使用或租用的服务器上提供空间以及提供Internet连接（通常在数据中心中）的公司。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Web_hosting_service) & [中文地址](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%89%98%E7%AE%A1%E6%9C%8D%E5%8A%A1)*

**基础学习：**

* [Web托管101: 让你的网站一直在网络上运行](https://www.udemy.com/web-hosting-101/) \[视频\]

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/what-is-web-hosting-infographic.jpg)

*图片来源: [https://firstsiteguide.com/wp-content/uploads/2016/06/what-is-web-hosting-infographic.jpg](https://firstsiteguide.com/wp-content/uploads/2016/06/what-is-web-hosting-infographic.jpg)*

### 3.6 学习前端开发基础

* [每天的网上前端训练营](https://github.com/Microsoft/frontend-bootcamp) \[阅读\]

* [准备成为职业的Web开发](https://frontendmasters.com/learn/beginner/)

* [成为Web前端开发](https://www.lynda.com/learning-paths/Web/become-a-front-end-web-developer) \[观看\]\[付费\]

* [成为Web开发](http://www.yellowshoe.com.au/standards) \[阅读\]

* [freeCodeCamp](http://freecodecamp.com/) \[互动\]

  * [学习前端开发100天 \[阅读\]](https://github.com/nas5w/100-days-of-code-frontend#contibuting)

* [没有学位的Web前端开发](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001) \[观看\]\[付费\]

* [Web前端开发职业生涯快速入门](http://www.pluralsight.com/courses/front-end-web-development-career-kickstart) \[观看\]\[付费\]

* [Web前端开发：入门](http://www.pluralsight.com/courses/front-end-web-development-get-started) \[观看\]\[付费\]

* [Web前端开发学习使用HTML5、CSS和JavaScript快速入门](http://www.pluralsight.com/courses/front-end-web-app-html5-javascript-css) \[观看\]\[付费\]

* [Web前端开发：Big Nerd Ranch指南](https://www.amazon.com/Front-End-Web-Development-Ranch-Guide/dp/0134433947/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=06802d4e42ca55b03294779c960d0826&camp=1789&creative=9325) \[阅读\]\[付费\]

* [完整的Web开发介绍](https://frontendmasters.com/courses/web-development-v2/) \[观看\]\[付费\]

* [学习Web前端开发](https://teamtreehouse.com/tracks/front-end-web-development) \[观看\]\[付费\]

* [你想成为一名前端工程师吗](https://www.youtube.com/watch?v=Lsg84NtJbmI) \[观看\]

* [codecademy.com: 学习Web开发路线](https://www.codecademy.com/learn/paths/web-development) \[互动\]\[免费\]

* [web.dev](https://web.dev/learn) \[阅读\]

### 3.7 学习用户界面和交互设计

> *<b>用户界面设计</b> — 用户界面设计（UI）或用户界面工程是机器和软件（如计算机，家用电器，移动设备和其他电子设备）的用户界面设计，重点是最大化用户体验。 用户界面设计的目标是在完成用户目标（以用户为中心的设计）方面使用户的交互尽可能简单有效。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/User_interface_design) & [中文地址](https://zh.wikipedia.org/wiki/%E7%94%A8%E6%88%B7%E7%95%8C%E9%9D%A2%E8%AE%BE%E8%AE%A1)*
>

> *<b>交互设计模式</b> — 设计模式是记录常见设计问题解决方案的正式方式。 这个想法是由建筑师克里斯托弗亚历山大介绍用于城市规划和建筑建造，并已适用各种其他学科，包括教学和教学，开发组织和过程，软件架构和设计。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Design_pattern) & [中文地址](https://zh.wikipedia.org/wiki/%E4%BA%A4%E4%BA%92%E8%AE%BE%E8%AE%A1)*
>

> *<b>用户体验设计</b> — 用户体验设计（UXD或UED或XD）是通过改善用户与产品之间交互中提供的可用性，可触达性和愉悦来提高用户满意度的过程。 用户体验设计包括传统的人机交互（HCI）设计，并通过解决用户所感知的产品或服务的所有方面来扩展它。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/User_experience_design) & [中文地址](https://zh.wikipedia.org/wiki/%E4%BD%BF%E7%94%A8%E8%80%85%E7%B6%93%E9%A9%97)*
> 

> *<b>人机交互</b> - 人机交互（HCI）研究计算机技术的设计和使用，特别关注人（用户）和计算机之间的接口。 人机交互领域的研究人员都观察了人类与计算机交互的方式以及设计技术，这些技术可以让人类以新颖的方式与计算机进行交互。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Human%E2%80%93computer_interaction) & [中文地址](https://zh.wikipedia.org/wiki/%E4%BA%BA%E6%9C%BA%E4%BA%A4%E4%BA%92)*

我建议阅读以下关于此事的规范性文本，以便可以支持和有能力构建可用的用户界面。

* [关于表面：交互设计的要点](https://www.amazon.com/About-Face-Essentials-Interaction-Design-ebook/dp/B00MFPZ9UY/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=c723c84ad4d246cb7f1c4a737c5f38a4&camp=1789&creative=9325) \[阅读\]\[付费\]

* [黑客设计：逆向工程之美](https://www.amazon.com/Design-Hackers-Reverse-Engineering-Beauty/dp/1119998956/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=2a52f0968de21c03f069d857b9d92b37&camp=1789&creative=9325) \[阅读\]\[付费\]

* [非设计师设计](https://www.youtube.com/watch?v=ZbrzdMaumNk&feature=youtu.be) \[观看\]

* [设计接口](https://www.amazon.com/Designing-Interfaces-Jenifer-Tidwell/dp/1449379702/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=4539707bb145c676472472aab25eaa56&camp=1789&creative=9325) \[阅读\]\[付费\]

* [设计Web界面：丰富交互的原则和模式](https://www.amazon.com/Designing-Web-Interfaces-Principles-Interactions-ebook/dp/B0026OR33U/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=03fb59f4a4345732fae9ecdfaa5076ae&camp=1789&creative=9325) \[阅读\]\[付费\]

* [不要让用户思考和重访：网络可用性的常识方法](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=8b0b0771a9985e4e030ef1fe29cf6409&camp=1789&creative=9325) \[阅读\]\[付费\]

### 3.8 学习HTML和CSS

> *<b>HTML</b> — 超文本标记语言，通常称为HTML，是用于创建网页的标准标记语言。 Web浏览器可以读取HTML文件并将其呈现为可见或可听的网页。 HTML在语义上描述了网站的结构以及用于表示的提示，使其成为标记语言，而不是编程语言。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/HTML) & [中文地址](https://zh.wikipedia.org/wiki/HTML)*
>

> *<b>CSS</b> — 层叠样式表(CSS)是一种样式表语言，用于描述用标记语言编写的文档的外观和格式。 虽然最常用于更改用HTML和XHTML编写的网页和用户界面的样式，但该语言可以应用于任何类型的XML文档，包括纯XML，SVG和XUL。 与HTML和JavaScript一起，CSS是大多数网站使用的基础技术，用于创建具有视觉吸引力的网页，Web应用程序的用户界面以及许多移动应用程序的用户界面。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) & [中文地址](https://zh.wikipedia.org/wiki/HTML)*

就像要建造房屋，人们可能会认为HTML是结构而CSS是绘画和装饰。

**基础学习：**

* [CSS中的绝对居中定位](http://codepen.io/shshaw/full/gEiDt) \[阅读\]

* [CSS定位](http://www.pluralsight.com/courses/css-positioning-1834) \[观看\]\[付费\]

* [Web开发介绍（v2）](https://frontendmasters.com/courses/web-development-v2/) \[观看\]\[付费\]

* [Web前端开发：入门](http://www.pluralsight.com/courses/front-end-web-development-get-started) \[观看\]\[付费\]

* [Web前端开发HTML5，CSS和JavaScript快速入门](http://www.pluralsight.com/courses/front-end-web-app-html5-javascript-css) \[观看\]\[付费\]

* [HTML和CSS：设计和构建网站](https://www.amazon.com/gp/product/1118008189/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=b1c45ab715f267f7dfed8c981c14eceb&camp=1789&creative=9325) \[阅读\]\[付费\]

* [HTML文档流](http://www.pluralsight.com/courses/html-document-flow-1837) \[观看\]\[付费\]

* [HTML掌握：语义、标准和样式](https://www.amazon.com/gp/product/1590597656/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=a5c4eb997239ea9e57a86456cef7763c&camp=1789&creative=9325) \[阅读\]\[付费\]

* [互相干扰很难](https://internetingishard.com/) \[阅读\]

* [HTML和CSS简介：制作网页](https://www.khanacademy.org/computing/computer-programming/html-css) \[观看\]

* [学习编码HTML和CSS](http://learn.shayhowe.com/html-css/) \[阅读\]

* [学习CSS布局](http://learnlayout.com/) \[阅读\]

* [MarkSheet](http://marksheet.io/) \[阅读\]

* [MDN: HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML) \[阅读\]

* [MDN: CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS) \[阅读\]

* [HTML语义化：如何构建网页](https://webdesign.tutsplus.com/courses/semantic-html-how-to-structure-web-pages) \[观看\]

* [可靠的HTML表单结构](https://webdesign.tutsplus.com/courses/solid-html-form-structure) \[观看\]

* [了解CSS盒模型](https://webdesign.tutsplus.com/courses/understanding-the-css-box-model) \[观看\]

* [弹性的网页设计](https://resilientwebdesign.com/) \[阅读\]

**掌握CSS：**

* [Flexbox完全指南](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) \[阅读\]

* [用于响应式网页设计的CSS网格和Flexbox](https://frontendmasters.com/courses/css-grids-flexbox/) \[观看\]\[付费\]

* [CSS Diner](http://flukeout.github.io/) \[互动\]

* [从CSS4到CSS1的CSS选择器](http://css4-selectors.com/selectors/) \[阅读\]

* [CSS秘诀：日常网页设计问题更好的解决方案](https://www.amazon.com/CSS-Secrets-Solutions-Everyday-Problems/dp/1449372635/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=40a9480c18839b4b2ea798aa2afafd0e&camp=1789&creative=9325) \[阅读\]\[付费\]

* [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) \[阅读\]

* [深入CSS, v2](https://frontendmasters.com/courses/css-in-depth-v2/) \[观看\]\[付费\]

* [什么是Flexbox？！ 一个简单，免费的20集视频课程，帮助你掌握CSS Flexbox](http://flexbox.io/) \[观看\]

* [CSS 30秒 — 精选的有用CSS片段集合，你可以在30秒或更短的时间内理解这些片段。](https://atomiks.github.io/30-seconds-of-css/) \[阅读\]

**参考文献和文档：**

* [CSS触发器...布局、绘画和合成的游戏](http://csstriggers.com/)

* [cssreference.io](http://cssreference.io/)

* [cssvalues.com](http://cssvalues.com/)

* [Chrome浏览器的默认CSS](https://chromium.googlesource.com/chromium/blink/+/master/Source/core/css/html.css)

* [Head - 可以包含在文档中的所有内容的列表](http://gethead.info/)

* [HTML属性参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)

* [MDN CSS参考](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

* [MDN HTML元素参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

**词汇：**

* [CSS词汇表 - CSS覆盖注释，属性和选择器的编程参考](https://www.codecademy.com/articles/glossary-css)

* [CSS词汇](http://apps.workflower.fi/vocabs/css/en)

* [HTML元素的编程参考的HTML词汇表](https://www.codecademy.com/articles/glossary-html)

**规范标准：**

* [所有W3C CSS规范](http://www.w3.org/Style/CSS/current-work#roadmap)

* [所有W3C HTML规范](http://www.w3.org/standards/techs/html#w3c_all)

* [层叠样式表2级修订版2（CSS 2.2）规范](https://drafts.csswg.org/css2/)

* [CSS索引 - CSS规范定义的每个术语的列表](https://drafts.csswg.org/indexes/)

* [来自持续更新标准的HTML元素](https://html.spec.whatwg.org/multipage/semantics.html#semantics)

* [全局属性](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

* 来自持续更新标准的[HTML语法](https://html.spec.whatwg.org/multipage/syntax.html#syntax)

* [W3C的HTML 5.2](http://w3c.github.io/html/)

* [Level 3 选择器](http://www.w3.org/TR/css3-selectors/)

**CSS框架：**

* [原子设计](http://atomicdesign.bradfrost.com/) \[阅读\]

* [BEM](http://getbem.com/introduction/)

* [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/)

* [OOCSS](http://oocss.org/) \[阅读\]

* [SMACSS](https://smacss.com/) \[阅读\]\[付费\]

  * [用于CSS的可扩展模块化架构（SMACSS）](https://frontendmasters.com/courses/smacss/) \[观看\]\[付费\]

* [SUIT CSS](http://suitcss.github.io)

* [rscss](http://rscss.io/)

**书写规范**

* [CSS编码指南](http://codeguide.co/#css) \[阅读\]

* [CSS框架](https://github.com/jareware/css-architecture)

* [cssguidelin.es](http://cssguidelin.es/) \[阅读\]

* [常用的CSS](https://github.com/necolas/idiomatic-css) \[阅读\]

* [可维护的CSS](http://maintainablecss.com/) \[阅读\]

* [灵活，耐用，可持续的HTML和CSS的开发标准](http://mdo.github.io/code-guide/) \[阅读\]

### 3.9 学习搜索引擎优化

> *搜索引擎优化（SEO）是影响搜索引擎未付费结果中网站或网页可见性的过程 - 通常称为“自然”，“有机”或“获得”结果。 通常，较早（或在搜索结果页面上排名更高），并且搜索结果列表中出现更频繁的网站，它将从搜索引擎的用户收到的访问者越多。 SEO可以针对不同类型的搜索，包括图像搜索，本地搜索，视频搜索，学术搜索，新闻搜索和行业特定的垂直搜索引擎。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Search_engine_optimization)& [中文地址](https://zh.wikipedia.org/wiki/%E6%90%9C%E5%B0%8B%E5%BC%95%E6%93%8E%E6%9C%80%E4%BD%B3%E5%8C%96)*

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/how-does-seo-work.jpg)

*图像来源: [https://visual.ly/community/infographic/computers/how-does-seo-work](https://visual.ly/community/infographic/computers/how-does-seo-work)*

**基础学习：**

* [Google搜索引擎优化入门指南](http://static.googleusercontent.com/media/www.google.com/en//webmasters/docs/search-engine-optimization-starter-guide.pdf) \[阅读\]

* [现代SEO](https://frontendmasters.com/courses/modern-seo/) \[观看\]\[付费\]

* [David Booth的SEO基础](http://www.lynda.com/Analytics-tutorials/SEO-Fundamentals/187858-2.html) \[观看\]\[付费\]

* [Paul Wilson的SEO基础](http://www.pluralsight.com/courses/seo-fundamentals) \[观看\]\[付费\]

* [2016年初学者SEO教程](http://www.hobo-web.co.uk/seo-tutorial/) \[阅读\]

* [网页设计师的SEO教程](https://webdesign.tutsplus.com/courses/seo-for-web-designers) \[观看\]\[付费\]

### 3.10 学习JavaScript

> *JavaScript是一种高级，动态，无类型和解释型编程语言。 它已在ECMAScript语言规范中标准化。 除HTML和CSS外，它还是万维网内容制作的三大基本技术之一; 大多数网站都使用它，所有没有插件的现代网络浏览器都支持它。 JavaScript是基于原型的第一类函数，使其成为一种多范式语言，支持面向对象，命令式和函数式编程风格。 它具有用于处理文本，数组，日期和正则表达式的API，但不包括任何I/O，例如网络，存储或图形工具，在嵌入它的主机环境中依赖它们。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/JavaScript)& [中文地址](https://zh.wikipedia.org/wiki/JavaScript)*

**入门:**

* [MDN: JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) \[阅读\]

* [javascript.info](http://javascript.info/)

* [JavaScript启蒙](http://www.javascriptenlightenment.com/) \[阅读\]

* [动人的JavaScript](http://eloquentjavascript.net/) \[阅读\]

**基础学习：**

* [说说JavaScript](http://speakingjs.com/es5/index.html) \[阅读\]

* [没耐心程序员的JavaScript](http://exploringjs.com/impatient-js/index.html) \[阅读\]

* [你不知道的JS：Up和Going](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20&%20going/README.md#you-dont-know-js-up--going) \[阅读\]

* [你不知道的JS：类型和语法](https://github.com/getify/You-Dont-Know-JS/blob/master/types%20&%20grammar/README.md#you-dont-know-js-types--grammar) \[阅读\]

* [你不知道的JS：域和闭包](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20&%20closures/README.md#you-dont-know-js-scope--closures) \[阅读\]

* [你不知道的JS：this和对象原型](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20&%20object%20prototypes/README.md#you-dont-know-js-this--object-prototypes) \[阅读\]

* [现代JavaScript备忘清单 — 给你一份现代项目中经常遇到的JavaScript知识备忘清单。](https://github.com/mbeaudru/modern-js-cheatsheet) \[阅读\]

* [JavaScript: 最难的部分](https://frontendmasters.com/courses/javascript-hard-parts/) \[观看\]\[付费\]

* [JavaScript的深层基础 (v3)](https://frontendmasters.com/courses/deep-javascript-v3/) \[观看\]\[付费\]

**掌握：**

* [配置ES6](https://leanpub.com/setting-up-es6) \[阅读\]

* [适合所有人的ES6！](https://es6.io/) \[观看\]\[付费\]

* [ES6探索](http://exploringjs.com/es6.html) \[阅读\]

* [你不知道的JS: ES6 和 Beyond](https://github.com/getify/You-Dont-Know-JS/blob/master/es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond) \[阅读\]

* [了解ECMAScript 6：JavaScript开发者权威指南](https://www.amazon.com/Understanding-ECMAScript-Definitive-JavaScript-Developers/dp/1593277571/ref=as_li_ss_tl?&_encoding=UTF8&tag=fronenddevejo-20&linkCode=ur2&linkId=1ca4f5f23b42aeadad0990ab3bf91ca7&camp=1789&creative=9325) \[阅读\]\[付费\]

* [JavaScript: 最新部分](https://frontendmasters.com/courses/js-recent-parts/) \[观看\]\[付费\]

* [探索ES2016和ES2017](http://exploringjs.com/es2016-es2017/index.html) \[阅读\]

* [探索ES2018和ES2019](http://exploringjs.com/es2018-es2019/index.html) \[阅读\]

* [JavaScript正则表达启蒙](http://codylindley.com/techpro/2013_05_14__javascript-regular-expression-/) \[阅读\]

* [使用正则表达式](http://www.lynda.com/Regular-Expressions-tutorials/Using-Regular-Expressions/85870-2.html) \[观看\]\[付费\]

* [你不知道的JS: Async 和 性能](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/README.md#you-dont-know-js-async--performance) \[阅读\]

* [JavaScript中的Promises](http://www.amazon.com/JavaScript-Promises-Daniel-Parker/dp/1449373216/ref=pd_sim_sbs_14_5) \[阅读\]\[付费\]

* [测试驱动的JavaScript开发](http://www.amazon.com/dp/0321683919/) \[阅读\]\[付费\]

* [JS传闻](https://mythbusters.js.org/index.html) \[阅读\]

* [强大的JavaScript](https://molily.de/robust-javascript/) \[阅读\]

* [JavaScript算法和数据结构](https://github.com/trekhleb/javascript-algorithms#readme) \[阅读\]

* [每个JavaScript开发者都应该知道的33个概念](https://github.com/leonardomso/33-js-concepts) \[阅读\]

* [doesitmutate.xyz](https://doesitmutate.xyz/) \[阅读\]

**JavaScript函数式:**

* [函数式编程术语](https://github.com/hemanth/functional-programming-jargon#functional-programming-jargon)

* [函数式: JavaScript函数式编程](https://www.youtube.com/watch?v=BMUiFMZr7vk&list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) \[观看\]

* [Functional-Light-JS](https://github.com/getify/Functional-Light-JS) \[阅读\]

* [JavaScript中的函数式编程：如何使用函数改进JavaScript程序](https://www.amazon.com/Functional-Programming-JavaScript-functional-techniques/dp/1617292826/ref=sr_1_1?&_encoding=UTF8&tag=fronenddevejo-20&linkCode=ur2&linkId=dcc6b0cb7de57fa841f1b178d2d54b9d&camp=1789&creative=9325) \[阅读\]

* [函数式编程完全指南 (javascript)](https://drboolean.gitbooks.io/mostly-adequate-guide/content/) \[阅读\]

* [Frisby教授推出可组合函数式的JavaScript](https://egghead.io/courses/professor-frisby-introduces-composable-functional-javascript) \[观看\]

* [JavaScript Allongé](https://leanpub.com/javascriptallongesix) \[阅读\]\[付费\]

* [Functional-Lite JavaScript (v2)](https://frontendmasters.com/courses/functional-javascript-v2/) \[观看\]\[付费\]

* [JavaScript中硬核的函数式编程](https://frontendmasters.com/courses/functional-javascript/) \[观看\]\[付费\]

**参考文献和文档：**

* [MDN JavaScript参考](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

* [MSDN JavaScript参考](https://msdn.microsoft.com/en-us/library/yek4tbz0.aspx)

**词汇/百科全书/专业术语：**

* [JavaScript百科全书](http://www.crockford.com/javascript/encyclopedia/)

* [JavaScript词汇表](https://www.codecademy.com/articles/glossary-javascript)

* [JavaScript简化的专业术语](http://jargon.js.org/)

**标准/规范：**

* [如何阅读ECMAScript规范](https://timothygu.me/es-howto/)

* [ECMAScript® 2015语言规范](http://www.ecma-international.org/ecma-262/6.0/index.html)

* [ECMAScript® 2016语言规范](https://www.ecma-international.org/ecma-262/7.0/index.html)

* [ECMAScript® 2017语言规范](http://www.ecma-international.org/ecma-262/8.0/index.html)

* [ECMAScript® 2018语言规范](http://www.ecma-international.org/ecma-262/9.0/index.html)

* [ECMAScript® 2019语言规范](https://tc39.github.io/ecma262/)

* [ECMA262的状态、流程和文档](https://github.com/tc39/ecma262)

**样式：**

* [JavaScript Airbnb风格指南](http://airbnb.io/javascript/)

* [JavaScript标准风格](http://standardjs.com/rules.html)

* [JavaScript半标准风格](https://github.com/Flet/semistandard)

**不推荐使用的JS学习资源：**

* [Crockford on JavaScript - 第一卷: 早年](https://www.youtube.com/watch?v=JxAXlJEmNMg) \[观看\]

* [Crockford on JavaScript - 第二章: 然后是JavaScript](https://www.youtube.com/watch?v=RO1Wnu-xKoY) \[观看\]

* [Crockford on JavaScript - 第三幕:终极功能](https://www.youtube.com/watch?v=ya4UHuXNygM) \[观看\]

* [Crockford on JavaScript - 第四集:Ajax的蜕变](https://www.youtube.com/watch?v=Fv9qT9joc0M) \[观看\]

* [Crockford on JavaScript - 第五部分:万物终结](https://www.youtube.com/watch?v=47Ceot8yqeI) \[观看\]

* [Crockford on JavaScript - 场景6:Loopage](https://www.youtube.com/watch?v=QgwSUtYSUqA) \[观看\]

* [JavaScript模式](http://www.amazon.com/gp/product/0596806752/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=0596806752&linkCode=as2&tag=fronenddevejo-20&linkId=K56OPQZNQNMPF6QI) \[阅读\]\[付费\]

* [面向对象的JavaScript原理](http://www.amazon.com/gp/product/1593275404/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1593275404&linkCode=as2&tag=fronenddevejo-20&linkId=NQTZVDOIMJRGMAQM) \[阅读\]\[付费\]

* [JavaScript模块](http://jsmodules.io/cjs.html) \[阅读\]

* [函数式JavaScript：使用Underscore.js介绍函数式编程](http://www.amazon.com/gp/product/1449360726/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449360726&linkCode=as2&tag=fronenddevejo-20&linkId=BDQC3FTEB3YXTYCK) \[阅读\]\[付费\]

* [JavaScript和Web的优点](https://frontendmasters.com/courses/good-parts-javascript-web/) \[观看\]\[付费\]

* [高性能JavaScript（构建更快的Web应用程序接口）](http://www.amazon.com/Performance-JavaScript-Faster-Application-Interfaces/dp/059680279X/ref=sr_1_1) \[阅读\]\[付费\]

**JS搜索可视化:**

* [JavaScript Array探索](https://sdras.github.io/array-explorer/)

* [JavaScript Object探索](https://sdras.github.io/object-explorer/)

* [JavaScript可视化](https://tylermcginnis.com/javascript-visualizer/)

### 3.11 学习DOM、BOM、CSSOM和jQuery

> *<b>DOM</b> — 文档对象模型（DOM）是一种跨平台且与语言无关的约定，用于表示HTML，XHTML和XML文档中的对象并与之交互。 每个文档的节点都以树结构组织，称为DOM树。 可以通过使用对象上的方法来寻址和操纵DOM树中的对象。 DOM的公共接口在其应用程序编程接口（API）中指定。*
>
> *—[维基百科](https://en.wikipedia.org/wiki/Document_Object_Model) & [中文地址](https://zh.wikipedia.org/wiki/%E6%96%87%E6%A1%A3%E5%AF%B9%E8%B1%A1%E6%A8%A1%E5%9E%8B)*
> 

> *<b>BOM</b> — 浏览器对象模型（BOM）是一种特定于浏览器的约定，指的是Web浏览器公开的所有对象。 与文档对象模型不同，没有标准的实现和严格的定义，因此浏览器供应商可以自由地以任何方式实现BOM。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Browser_Object_Model) & [中文地址](https://zh.wikipedia.org/wiki/BOM)*
> 

> *<b>jQuery</b> — jQuery是一个跨平台的JavaScript库，旨在简化HTML的客户端脚本。 jQuery是目前使用最流行的JavaScript库，安装在网络上前1000万个流量最高的网站中的65％。 jQuery是根据MIT许可证授权的免费开源软件。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/JQuery) & [中文地址](https://zh.wikipedia.org/wiki/JQuery)*

理想的学习路线，肯定是最困难的，首先学习JavaScript，然后是DOM，然后是jQuery。 但是，要做一些对你的大脑有意义的事情。 大多数前端开发者通过首先学习jQuery来学习JavaScript然后学习DOM。 无论你采取什么样的学习路线，都要确保JavaScript，DOM和jQuery不会变成黑盒子。

**基础学习：**

* [文档对象模型](http://eloquentjavascript.net/13_dom.html) \[阅读\]

* [HTML/JS: 使网页互动](https://www.khanacademy.org/computing/computer-programming/html-css-js) \[观看\]

* [HTML/JS: 使用jQuery制作可交互的网页应用](https://www.khanacademy.org/computing/computer-programming/html-js-jquery) \[观看\]

* [jQuery启蒙](http://jqueryenlightenment.com/) \[阅读\]

* [什么是DOM？](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) \[阅读\]

**掌握：**

* [AdvancED DOM 脚本：动态网页设计技术](http://www.amazon.com/gp/product/1590598563/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1590598563&linkCode=as2&tag=fronenddevejo-20&linkId=VQZU5EQIQQXCF56Y) \[阅读\]\[付费\]

* [jQuery和纯DOM脚本的高级JS基础知识](https://frontendmasters.com/courses/javascript-jquery-dom/) \[观看\]\[付费\]

* [Douglas Crockford: 一个不方便的API - DOM的理论](https://www.youtube.com/watch?v=Y2Y0U-2qJMs&list=PL5586336C26BDB324&index=2) \[观看\]

* [DOM Enlightenment](http://www.amazon.com/DOM-Enlightenment-Cody-Lindley/dp/1449342841/) \[阅读\]\[付费\] 或者 [在线免费阅读](http://domenlightenment.com/)

* [修复常见的jQuery错误](http://www.pluralsight.com/courses/fixing-common-jquery-bugs) \[观看\]\[付费\]

* [jQuery-Free JavaScript](http://www.pluralsight.com/courses/jquery-free-javascript) \[观看\]\[付费\]

* [jQuery提示和技巧](http://www.pluralsight.com/courses/jquery-tips-and-tricks) \[观看\]\[付费\]

**参考文献/文档：**

* [jQuery文档](http://api.jquery.com/)

* [事件](https://html.spec.whatwg.org/#events-2)

* [DOM浏览器支持](http://www.webbrowsercompatibility.com/dom/desktop/)

* [DOM事件浏览器支持](http://www.webbrowsercompatibility.com/dom-events/desktop/)

* [HTML界面浏览器支持](http://www.webbrowsercompatibility.com/html-interfaces/desktop/)

* [MDN文档对象模型（DOM）](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

* [MDN浏览器对象模型](https://developer.mozilla.org/en-US/docs/Web/API/Window)

* [MDN文档对象模型](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

* [MDN事件参考](https://developer.mozilla.org/en-US/docs/Web/Events)

* [MSDN文档对象模型（DOM）](https://msdn.microsoft.com/en-us/library/hh772384%28v=vs.85%29.aspx)

* [CSS对象模型（CSSOM）](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Object_Model)

**标准/规范：**

* [文档对象模型（DOM）3级事件规范](https://www.w3.org/TR/DOM-Level-3-Events/)

* [文档对象模型（DOM）技术报告](http://www.w3.org/DOM/DOMTR)

* [DOM持续更新标准](https://dom.spec.whatwg.org/)

* [W3C DOM4](https://www.w3.org/TR/2015/REC-dom-20151119/)

### 3.12 学习Web动画

**基础学习:**

* [SVG要素和动画, v2](https://frontendmasters.com/courses/svg-essentials-animation/) \[付费\]\[观看\]

* [动画在网络中的风险](https://www.codeschool.com/courses/adventures-in-web-animations) \[付费\]\[观看\]

* [动画与Snap.svg](https://webdesign.tutsplus.com/courses/animating-with-snapsvg) \[付费\]\[观看\]

* [CSS3和HTML5中的动画](https://frontendmasters.com/courses/animation-storytelling-html5-css3/) \[付费\]\[观看\]

* [在CSS中创建动画](http://www.kirupa.com/css_animations/index.htm) \[阅读 & 观看\]

* [现实世界中的CSS动画](https://webdesign.tutsplus.com/courses/css-animation-in-the-real-world) \[付费\]\[观看\]

* [使用JavaScript创建基础HTML5动画](http://www.amazon.com/Foundation-HTML5-Animation-JavaScript-Lamberta/dp/1430236655/ref=sr_1_3) \[付费\]\[阅读\]

* [学习用JavaScript创建动画](http://www.kirupa.com/javascript_animations/index.htm) \[read & watch\]

* [使用CSS进行运动设计](https://frontendmasters.com/courses/motion-design-css/) \[付费\]\[观看\]

* [动画状态2015](https://air.mozilla.org/rachel-nabors-state-of-the-animation-2015/) \[观看\]

* [使用JavaScript开发Web动画：开发和设计](http://www.amazon.com/Web-Animation-using-JavaScript-Develop-ebook/dp/B00UNKXVDU/ref=sr_1_1) \[付费\]\[阅读\]


**标准和规范：**

* [Web动画](https://w3c.github.io/web-animations/)

### 3.13 学习Web字体、图标和图像

> *网络排版是指在万维网上使用字体。当HTML最初创建时，字体和样式完全由每个Web浏览器的设置控制。Netscape于1995年引入`<font>`标记之前，还没有任何单独的Web页面控制字体显示的机制，该标记随后被标准化为HTML 3.2规范。但是，标签指定的字体必须安装在用户的计算机上，或者使用备用字体，比如浏览器的默认sans-serif或monospace字体。1996年发布了第一个层叠样式表规范，提供了相同的功能。*
>

> *1998年发布了CSS2规范，试图通过添加字体匹配、合成和下载来改进字体选择过程。这些技术没有得到太多的应用，并且在CSS2.1规范中被删除了。然而，在1997年Internet Explorer发布的4.0版本中增加了对字体下载功能的支持。字体下载后来包含在CSS3字体模块中，并在Safari 3.1、Opera 10和Mozilla Firefox 3.5中实现。这随后增加了人们对Web排版和字体下载的兴趣。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Web_typography) & [中文地址](https://zh.wikipedia.org/wiki/Web%E5%AD%97%E4%BD%93%E6%8E%92%E5%8D%B0)*

**字体:**

* [字体加载策略的全面指南](https://www.zachleat.com/web/comprehensive-webfonts/) \[阅读\]

* [漂亮的Web Type是来自谷歌Web字体字典的最佳字体展示](http://hellohappy.org/beautiful-web-type/) \[阅读\]

* [通过@font-face的Web字体速成指南](http://www.html5rocks.com/en/tutorials/webfonts/quick/) \[阅读\]

* [MDN: Web字体](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Web_fonts) \[阅读\]

* [响应式Web排版，v2](https://frontendmasters.com/courses/responsive-typography-v2/) \[观看\]\[付费\]

* [Web排版](http://www.pluralsight.com/courses/typography-for-web-1790) \[观看\]\[付费\]

**图标:**

* [\[阅读\]](https://www.lynda.com/CSS-tutorials/Web-Icons-SVG/502312-2.html) \[观看\]

**图像:**

* [MDN: HTML中的图像](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML) \[阅读\]

* [MDN: 响应式图像](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) \[阅读\]

* [WEB里的SVG — 实用指南](https://svgontheweb.com/) \[阅读\]

### 3.14 学习无障碍

> *无障碍是指为残疾人设计产品、设备、服务或环境。无障碍设计的概念确保了两者的“直接访问”(即，无辅助)和“间接访问”的意思是与某人的辅助技术(例如，计算机屏幕阅读器)的兼容性。*
> 

> *无障碍可以看作是“访问的能力”，并从某些系统或实体中获益。该概念的重点是使残疾人或特殊需要的人能够获得服务，或通过使用辅助技术使他们能够获得服务;然而，无障碍方面的研究和开发给每个人都带来了好处。*
> 

> *无障碍不要与可用性混淆，可用性是指特定用户可以在特定的使用上下文中使用产品(如设备、服务或环境)来实现特定目标的有效性、效率和满意度。*
> 

> *无障碍与通用设计密切相关，通用设计是一个创造产品的过程，使具有尽可能广泛的能力的人能够使用这些产品，并在尽可能广泛的情况下进行操作。这是为了让所有人(无论他们是否有残疾)都能接触到这些东西。*
> 
> *— [维基百科](https://en.wikipedia.org/wiki/Accessibility) & [中文地址](https://zh.wikipedia.org/wiki/%E7%84%A1%E9%9A%9C%E7%A4%99%E7%92%B0%E5%A2%83)*

**基础学习:**

* [获得最低限度的网页无障碍访问的9个技巧](https://medium.com/@realabhijeet4u/9-tips-to-get-bare-minimum-of-web-accessibility-739899a9437c)

* [UX基础: 无障碍](http://www.lynda.com/Accessibility-tutorials/Foundations-UX-Accessibility/435008-2.html) \[观看\]\[付费\]

* [屏幕阅读器如何支持HTML元素](http://thepaciellogroup.github.io/AT-browser-tests/?utm_source=html5weekly&utm_medium=email) \[阅读\]

* [网页无障碍介绍](https://www.w3.org/WAI/intro/accessibility.php) \- WAI \[阅读\]

* [面向Web应用程序的通用设计: 面向所有人的Web应用程序](http://www.amazon.com/Universal-Design-Web-Applications-Everyone/dp/0596518730/ref=sr_1_1) \[阅读\]\[付费\]

* [Web无障碍: 快速开始](http://www.pluralsight.com/courses/web-accessibility-getting-started) \[观看\]\[付费\]

* [一个考虑到所有人的网页](http://rosenfeldmedia.com/books/a-web-for-everyone/) \[阅读\]\[付费\]

* [Web无障碍访问](https://frontendmasters.com/courses/web-accessibility/) \[观看\]\[付费\]

* [A11ycasts](https://www.youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g) \[观看\]

* [谷歌的无障碍访问](https://www.udacity.com/course/web-accessibility--ud891) \- Udacity course \[观看\]

**标准和规范:**

* [无障碍的富Internet应用程序(WAI-ARIA)现状](http://www.w3.org/standards/techs/aria#w3c_all)

* [无障碍网页计划(WAI)](http://www.w3.org/WAI/)

* [Web内容无障碍指南(WCAG)的现状](http://www.w3.org/standards/techs/wcag#w3c_all)

### 3.15 学习Web API 和浏览器API

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/web-api.png)

*图片来源: [http://www.evolutionoftheweb.com/](http://www.evolutionoftheweb.com/)*

BOM(浏览器对象模型)和DOM(文档对象模型)并不是浏览器内部唯一可以在Web平台上使用的浏览器API。所有不是特定的DOM或BOM，而是用于对浏览器进行编程的接口，都可以被看作是Web或Browser API(不幸的是，过去有些API被称为HTML5 API，它混淆了它们自己的特性和标准化，与指定HTML5标记语言的实际HTML5规范相混淆)。注意，Web或浏览器API确实包括设备API(例如，[`Navigator.getBattery()`](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/getBattery))，这些API可以通过浏览器在平板电脑和手机设备上使用。

你应该了解Web API 和浏览器API，并在适当的地方学习它们。要熟悉所有这些API，可以使用一个很好的工具来研究[HTML5test.com针对最流行的5个浏览器的测试结果](https://html5test.com/compare/browser/index.html)。

MDN有大量关于Web API 和浏览器API的信息。

* [MDN Web API参考](https://developer.mozilla.org/en-US/docs/Web/Reference/API)

* [MDN Web API接口引用 — 所有接口，按字母顺序排列](https://developer.mozilla.org/en-US/docs/Web/API)

* [列出对应用程序有用的设备访问API和其他API](https://developer.mozilla.org/en-US/docs/WebAPI)

请记住，并非每个API都是由W3C或WHATWG指定的。

除了MDN之外，你可能还会发现以下资源对学习所有Web API 和浏览器API很有帮助:

* [HTML5 JavaScript API索引](http://html5index.org/)

* [HTML5概述](http://html5-overview.net/current)

* [platform.html5.org](https://platform.html5.org/)

### 3.16 学习JSON（JavaScript对象表示法）

> *JSON是一种开放的标准格式，它使用可读的文本来传输由属性值对组成的数据对象。它是用于异步浏览器/服务器通信(AJAJ)的主要数据格式，在很大程度上替代了XML(AJAX使用的就是这种方式)。*
> 

> *虽然JSON最初源于JavaScript脚本语言，但它是一种独立于语言的数据格式。解析和生成JSON数据的代码在许多编程语言中都是可用的。*
> 

> *JSON格式最初由Douglas Crockford指定。它目前有两个相互竞争的标准描述，RFC 7159和ECMA-404。ECMA标准非常简单，只描述允许的语法语法，而RFC还提供了一些语义和安全性方面的考虑。JSON的官方Internet媒体类型是application/json。JSON文件名扩展名是.json。*
> 
> — [维基百科](https://en.wikipedia.org/wiki/JSON) & [中文地址](https://zh.wikipedia.org/wiki/JSON)

**基础学习:**

* [JavaScript对象表示法介绍: JSON入门指南](https://www.amazon.com/Introduction-JavaScript-Object-Notation-Point/dp/1491929480/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=24e8df4722cb62d086d3f8c87f4e17a1&camp=1789&creative=9325) \[阅读\]\[付费\]

* [json.com](https://www.json.com/) \[阅读\]

* [JSON是什么](https://mijingo.com/lessons/what-is-json/) \[观看\]

**参考文献和文档：**

* [json.org](http://json.org/) \[阅读\]

**标准和规范：**

* [JSON数据交换格式ECMA-404](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

* [JavaScript对象表示法(JSON)数据交换格式RFC 7159](https://tools.ietf.org/html/rfc7159)
* [STD 90 - RFC 8259 - JavaScript对象表示法(JSON)数据交换格式，2017年12月](https://www.rfc-editor.org/info/rfc8259)

**架构设计:**

* [JSON API](http://jsonapi.org/)

### 3.17 学习JS模板

JavaScript模板通常用于将视图的各个部分(UI)与逻辑和模型(数据或JSON)分离的[MV*](http://todomvc.com/)解决方案。

* [ES6模版方法：Handlebar杀手?](https://www.keithcirkel.co.uk/es6-template-literals/) \[阅读\]

* [从nunjucks开始](http://mozilla.github.io/nunjucks/getting-started.html) \[阅读\]

* [Lodash模板](https://lodash.com/docs/4.17.2#template) \[文档\]

注意到JavaScript 2015(ES6)添加了一个名为["字符串模板"](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/template_strings)的原生模板机制。此外，最近模板已经被[JSX](https://facebook.github.io/jsx/)、[一个模板元素](http://aurelia.io/docs/templating/basics)或[HTML字符串](https://angular.io/docs/ts/latest/guide/template-syntax.html#)之类的东西所取代。

如果我不使用React和JSX，我会首先使用JavaScript的["字符串模板"](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/template_strings)，当它也没有时，我会选择[nunjucks](http://mozilla.github.io/nunjucks/getting-started.html)。

### 3.18 学习静态站点生成器

静态站点生成器，通常使用服务器端代码(比如，ruby、php、python、nodeJS等)，从静态文本或数据+模板生成静态HTML文件，这些模板将静态地从服务器发送到客户端，而不具有动态性质。

**基础学习:**

* [JAMstack](https://jamstack.org/) \[阅读\]

* [静态网站生成器](http://www.oreilly.com/web-platform/free/static-site-generators.csp) \[阅读\]

* [与静态站点一起工作 — 将简单的功能带到现代站点](https://www.amazon.com/Working-Static-Sites-Bringing-Simplicity/dp/1491960949) \[阅读\]\[付费\]

### 3.19 通过JS学习计算机科学

* [六小时完成四个学期的计算机科学课](https://frontendmasters.com/courses/computer-science/) \[视频\]\[付费\]

* [六小时完成四个学期的计算机科学: 第二部分](https://frontendmasters.com/courses/computer-science-2/) \[视频\]\[付费\]

* [JavaScript中的计算机科学](https://github.com/davidshariff/computer-science) \[阅读\]

* [用JavaScript编写的经典计算机科学范例、算法和方法的集合](https://github.com/nzakas/computer-science-in-javascript) \[阅读\]

* [JavaScript算法的实用指南](https://frontendmasters.com/courses/practical-algorithms/) \[观看\]\[付费\]

* [面试中数据结构介绍](https://frontendmasters.com/courses/data-structures-interviews/) \[观看\]\[付费\]

* [大师级别的JavaScript算法和数据结构](https://www.udemy.com/js-algorithms-and-data-structures-masterclass/) \[观看\]\[付费\]

### 3.20 学习前端应用程序架构

**基础学习:**

* [掌握前端指南](https://github.com/grab/front-end-guide) \[观看\]

* [一组JavaScript项目的最佳实践](https://github.com/elsewhencode/project-guidelines)

* [现代Web开发的拼写书](https://github.com/dexteryy/spellbook-of-modern-webdev)

* [从零开始的JavaScript堆栈](https://github.com/verekia/js-stack-from-scratch)

**弃用学习的资料:**

* [JavaScript应用程序设计](https://www.amazon.com/JavaScript-Application-Design-Build-Approach/dp/1617291951?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=4dd15b53493d3b5148af2b3e5488e98d&camp=1789&creative=9325) \[观看\]\[付费\]

* [用React和Ampersand创建一个应用程序](http://learn.humanjavascript.com/react-ampersand) \[观看\]

* [Web应用程序现场指南](http://www.html5rocks.com/webappfieldguide/toc/index/) \[观看\]

* [前端指南问卷](https://github.com/bradfrost/frontend-guidelines-questionnaire) \[观看\]

* [人类的JavaScript](http://read.humanjavascript.com/) \[观看\]

* [Nicholas Zakas: 可伸缩的JavaScript应用程序架构](https://www.youtube.com/watch?v=vXjVFPosQHw) \[观看\]

* [组织JavaScript功能](https://frontendmasters.com/courses/organizing-javascript/) \[观看\]\[付费\]

* [JavaScript大型应用程序架构的模式](http://addyosmani.com/largescalejavascript/) \[观看\]

* [Terrific](http://terrifically.org/) \[观看\]

* [前端案例研究](https://github.com/andrew--r/frontend-case-studies) \[观看\]

到目前为止，还没有多少关于这个主题的一般内容。学习如何构建前端、SPA和JavaScript应用程序的大部分内容都是假设你已经决定使用Angular、Ember、React或Aurelia等工具了。

[2019](https://2018.stateofjs.com/front-end-frameworks/overview/)年，这是我学习[React](https://facebook.github.io/react/)和[Mobx](https://github.com/mobxjs/mobx)以及[Apollo/graphql](https://www.apollographql.com/)的建议。

### 3.21 学习数据API设计

- [API设计 v3](https://frontendmasters.com/courses/api-design-nodejs-v3/) [观看][付费]

- [构建你不讨厌的API](http://apisyouwonthate.com/) [阅读][付费]

- [JSON API](http://jsonapi.org/) [阅读]

### 3.22 学习React

**React入门**

- [教程：React基础](https://facebook.github.io/react/tutorial/tutorial.html) [阅读]

- [菜鸟学ReactJS](http://blog.andrewray.me/reactjs-for-stupid-people/) [阅读]

- [ReactJS初学者指南](https://egghead.io/courses/the-beginner-s-guide-to-reactjs) [观看]

- [React v4完整介绍](https://frontendmasters.com/courses/complete-react-v4/) [观看][付费]

- [React 🎄](https://react.holiday/) [阅读]

- [React语法视频订阅](https://school.reactpatterns.com/) [观看][付费]

- [React启蒙](https://www.reactenlightenment.com/) [阅读]

- [ReactJS教程#1 - ReactJS JavaScript入门和工作区设置](https://www.youtube.com/watch?v=MhkGQAoc7bc&t=6s) [观看]

**精通React**

- [构建你的第一个产品级品质的React应用程序](https://egghead.io/courses/build-your-first-production-quality-react-app) [观看][付费]

- [高级React组件模式](https://frontendmasters.com/courses/advanced-react-patterns/) [观看][付费]

- [中级React](https://frontendmasters.com/courses/intermediate-react/) [观看][付费]

- [React模式](https://reactpatterns.com/) [阅读]

- [8个关键React组件决策](https://medium.freecodecamp.org/8-key-react-component-decisions-cc965db11594) [阅读]

- [React-基础理论](https://github.com/reactjs/react-basic) [阅读]

- [React + Mobx实战示例代码库（CRUD、鉴权、高级模式等）](https://github.com/gothinkster/react-mobx-realworld-example-app)[编码]

- [React Router v4入门与路由原理](https://medium.freecodecamp.org/react-router-v4-philosophy-and-introduction-730fd4fff9bc)

一旦你熟练掌握React，就可以学习更健壮的状态管理方案，比如 [MobX](https://mobx.js.org/)。如果你拥有丰富的函数式编程经验的开发者，请查看[Redux](https://redux.js.org/)。当你需要帮助去理解React的setState以外的状态管理方式，“[React的高级状态管理（如：Redux和MobX）](https://frontendmasters.com/courses/react-state/)”

### 3.23 学习应用程序状态管理

- [JavaScript的状态管理](https://codeburst.io/state-management-in-javascript-15d0d98837e1) [阅读]

- [React（Redux和MobX）的高级状态管理](https://frontendmasters.com/courses/react-state/) [观看][付费]

- [React js教程 - Redux是怎样运作的](https://www.youtube.com/watch?v=1w-oQ-i1XB8&list=PLoYCgNOIyGADILc3iUJzygCqC8Tt3bRXt) [观看]

- [MobX+React真的超赞](https://www.youtube.com/watch?v=_q50BXqkAfI&t=10s) [观看]

### 3.24 学习渐进式网页应用（PWA）

> *与传统应用程序不同的是，PWA混合了普通网页（网站）和移动应用程序。这种新的应用程序模型试图将大多数现代浏览器提供的功能与移动体验的好处结合起来。*
>
> *在2015年，设计师朗西斯·贝里曼(Frances Berriman)和Google Chrome工程师亚历克斯·拉塞尔(Alex Russell)创造了”PWA“这一术语，用此来描述利用现代浏览器所支持的新特性的应用程序，包括Service Workers和Web App Manifests，让用户将网页应用程序升级为原生操作系统的一等应用程序。*
>
> *依据Google开发者的介绍，这些特性是：*
>
> - *渐进式 - 适用于所有用户，不考虑浏览器的选择，因为其以渐进式增强为核心原则构建的。*
> 
> - *连通性独立 - 适用于任何形式：桌面、移动、平板或未出现的形式。*
> 
> - *类App - 对用于来说更像一款app，以其app风格的交互和导航。*
> 
> - *实时 - 得益于service worker更新进程，可以时刻保持更新。*
> 
> - *安全 - 通过HTTPS可以防止窥探和确保内容不被篡改。*
> 
> - *发现 - 得益于W3C manifests[6]和services woker注册范围允许搜索引擎检索到它们，可以识别为”应用程序“。*
> 
> - *重新接触 - 通过推送通知等特性可以轻易让用户重新接触。*
> 
> - *可安装的 - 允许用户在首屏中“保存”他们认为最有用的应用。免除了使用应用商店的麻烦。*
>
> - *可链接的 - 通过URL可以轻易分享应用，并且不需要复杂的安装。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Progressive_web_app)*
>

- [PWA初学者指南](https://www.smashingmagazine.com/2016/08/a-beginners-guide-to-progressive-web-apps/) [阅读]

- [PWA](https://developers.google.com/web/progressive-web-apps/) [阅读]

- [PWA入门](https://www.pluralsight.com/courses/web-apps-progressive-getting-started) [观看][付费]

- [构建PWA](https://www.lynda.com/CSS-tutorials/Building-Progressive-Web-App/518052-2.html) [观看][付费]

- [Google推出的PWA介绍](https://www.udacity.com/course/intro-to-progressive-web-apps--ud811) [观看]

- [原生应用注定失败](https://medium.com/javascript-scene/native-apps-are-doomed-ac397148a2c0#.rfw9hdym6) [阅读]

- [为什么原生应用注定失败：原生应用注定失败 第2期](https://medium.com/javascript-scene/why-native-apps-really-are-doomed-native-apps-are-doomed-pt-2-e035b43170e9#.qjrm13yj3) [阅读]

- [你的第一个PWA](https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/)[阅读]

- [PWA与离线](https://frontendmasters.com/courses/progressive-web-apps/) [观看][付费]

### 3.25 学习JS API设计

- [设计更好的JavaScript API](http://www.smashingmagazine.com/2012/10/designing-javascript-apis-usability/) [阅读]

- [编写JavaScript API](http://blog.wolksoftware.com/writing-javascript-apis)[阅读]

### 3.26 学习浏览器网页开发者工具

> *网页开发者能使用网页开发工具进行测试和debug他们的代码。这与网站构建工具和IDE不同，它不是帮助开发者直接创造网页，而是用于去测试用户所看见的网站或网页应用界面的工具。*
>
> *网页开发工具作为浏览器的插件或浏览器内置功能出现。现时最流行的网页浏览器,如Google Chrome、Firefox、Opera、Internet Explorer和Safari都内置了网页工具帮助来网页开发者，许多附加的插件都能在他们引以为傲的插件下载中心找到。*
>
> *网页开发工具允许开发者使用各种网页技术，包括HTML，CSS，DOM，JavaScript以及网页浏览器处理的其他组件。由于对网页浏览器日益增长的需求，流行的网页浏览器已经包含了更多面向开发者的特性。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Web_development_tools)*
>

虽然大部分浏览器都配备了网页开发者工具，但[Chrome开发者工具](https://developers.google.com/web/tools/chrome-devtools/)是目前来说被谈及最多和最广泛使用的。

我建议学习和使用[Chrome网页开发者工具](https://developers.google.com/web/tools/chrome-devtools/)，简单而言，因为最好的网页开发者工具学习资源都是以Chrome DevTools而展开的。

**学习Chrome网页开发工具：**

- [Chrome开发者工具](https://code.tutsplus.com/courses/chrome-developer-tools)

- [探索和掌握Chrome DevTools](http://discover-devtools.codeschool.com/)

- [掌握Chrome开发者工具v2](https://frontendmasters.com/courses/chrome-dev-tools-v2/)

- [使用Chrome开发者工具v2](http://www.pluralsight.com/courses/chrome-developer-tools)

- [学习掌握Chrome开发者工具](https://www.lynda.com/Chrome-tutorials/Learning-Chrome-Web-Developer-Tools/590844-2.html)

**Chrome开发者工具文档：**

- [命令行API参考](https://developers.google.com/web/tools/chrome-devtools/console/command-line-reference)

- [键盘和UI快捷键参考](https://developers.google.com/web/tools/iterate/inspect-styles/shortcuts)

- [Per-Panel文档](https://developers.google.com/web/tools/chrome-devtools/#docs)

- [配置与定制DevTools](https://developer.chrome.com/devtools/docs/settings)

### 3.27 学习命令行（CLI）

> *命令行界面或命令语言解释器（CLI），也叫做命令行用户界面，控制台用户界面和字符用户界面（CUI），是一种与用户（或客户端）的计算机程序交互的手段，以连续的文本行（命令行）的形式向程序发出命令。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Command-line_interface)*
>

**基础学习：**

- [Bash指南](http://guide.bash.academy/) [阅读]

- [命令行高级用户](http://commandlinepoweruser.com/) [观看]

- [深入学习命令行是危险的](http://www.learnenough.com/command-line-tutorial) [阅读][部分免费]

**进阶学习：**

- [高级命令行技术](https://code.tutsplus.com/courses/advanced-command-line-techniques) [观看][付费]

- [Bash、VIM和Regex入门](https://frontendmasters.com/courses/bash-vim-regex/) [观看][付费]

### 3.28 学习Node.js

> *Node.js是一种开源，跨平台的运行时环境，用于开发服务端网页应用。Node.js程序是用JavaScript编写并且能运行在OS X, Microsoft Windows, Linux, FreeBSD, NonStop, IBM AIX, IBM System z and IBM i上的Node.js运行时。它由Node.js基金会托管和支持，Linux基金会的一个合作性的项目。*
> 
> *Node.js提供一个事件驱动架构和一个非阻塞性 I/O API，被设计用于优化应用的通量和实时网页应用的可扩展性。它使用了Google V8 JavaScript引擎来执行代码，并且大比例的基础模块都是由JavaScript所编写。Node.js拥有一个内置的库，让应用程序无需使用诸如Apache HTTP服务器，Nginx或IIS等软件即可成为一个Web服务器。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Node.js)*
>

**基础学习：**

- [Node艺术](https://github.com/maxogden/art-of-node#the-art-of-node) [阅读]

- [Node.js介绍](https://frontendmasters.com/courses/node-js/) [观看][付费]

- [来自Evented Mind的Node.js介绍](https://www.eventedmind.com/classes/introduction-to-node-js-4c0326de) [观看]

- [io.js 和 Node.js Next：入门](http://www.pluralsight.com/courses/running-node-applications-io-js) [观看][付费]

- [学习Node：向服务端转变](https://www.amazon.com/Learning-Node-Server-Side-Shelley-Powers/dp/1491943122/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=264ce29eb0775f4e8ccb7db892539555&camp=1789&creative=9325) [阅读][付费]

- [学习Node.js](https://github.com/workshopper/learnyounode)[自学研讨会]

- [Node.js基础](http://teamtreehouse.com/library/nodejs-basics) [观看][付费]

- [Node.js实践](https://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=e202c01e97ebad79157fab3b59723e94&camp=1789&creative=9325) [阅读][付费]

- [Node.js的实时Web](https://www.codeschool.com/courses/real-time-web-with-node-js) [观看]

- [Node.js的API设计](https://frontendmasters.com/courses/api-design-nodejs-v3/) [观看][付费]

- [学习Node](https://learnnode.com/) [观看][付费]

### 3.29 学习模块

**基础学习：**

- [面向没耐心程序员的JavaScript - 模块](http://exploringjs.com/impatient-js/ch_modules.html) [阅读]

- [深入ES6模块](https://ponyfoo.com/articles/es6-modules-in-depth) [阅读]

- [探索JS - 模块](http://exploringjs.com/es6/ch_modules.html#ch_modules) [阅读]

- [漫话ES模块](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/) [阅读]

**参考文献与文档：**

- [MDN - export](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export)

- [MDN - import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)

### 3.30 学习模块Loader和Bundler

**Webpack:**

- [Webpack](https://webpack.js.org/guides/getting-started/) [阅读]

- [Webpack4基本原理](https://frontendmasters.com/courses/webpack-fundamentals/) [观看][付费]

- [Survivejs.com关于Webpack的书](https://survivejs.com/webpack/introduction/) [阅读]

**Rollup:**

- [Rollup](http://rollupjs.org/guide/) [阅读]

  - [Microbundle](https://github.com/developit/microbundle)

**Parcel:**

- [Parcel](https://parceljs.org/getting_started.html) [阅读]


### 3.31 学习包管理器

> *包管理器或包管理系统是一组软件集合的工具，它可以通过一致的方式自动执行安装，更新，配置以及移除计算机操作系统软件包的过程。它通常维护了一个软件依赖和版本信息的数据库，以防止软件无法匹配和丢失前置依赖。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Package_manager)*
>

**基础学习：**

- [JavaScript包管理器工作原理介绍](https://medium.freecodecamp.com/javascript-package-managers-101-9afd926add0a#.hu6knvct3) [阅读]

- [npm和Bower所用的SemVer神秘与魔幻系列](http://developer.telerik.com/featured/mystical-magical-semver-ranges-used-npm-bower/) [阅读]

- [包管理器：针对菜鸟前端开发者的一份入门指南](http://codylindley.com/techpro/2013_04_12__package-managers-an-introducto/) [阅读]

- [npm文档](https://docs.npmjs.com/)

- [yarn文档](https://yarnpkg.com/en/docs/)

### 3.32 学习版本控制

> *软件配置管理组件，版本控制，也就是修正管理和源码管理，是一种对文档，计算机程序，大型网站和其他信息集合的变更管理。变更常用数字和字母代码表示，术语叫做“修订数字”，“修订等级”或“修订”。举个例子，一个初始的文档集是“修订1”，当产生第一个变更时，得到的集合就是“修订2”，如此类推。每个修订都与时间戳以及做修改的人有关。修订能够用来对比，复原和与某种类型的文件进行合并。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Version_control)*
>

Git是现今最常见用于版本控制解决方案。学习它吧！

**基础学习：**

- [正确使用Git](https://www.atlassian.com/git/) [阅读]

- [Git基础原理](http://www.pluralsight.com/courses/git-fundamentals) [观看][收费]

- [掌握Git](https://www.learnenough.com/git-tutorial) [阅读]

- [Ry的Git教程](https://www.amazon.com/Rys-Git-Tutorial-Ryan-Hodson-ebook/dp/B00QFIA5OC) [阅读]

**进阶学习：**

- [深入Git](https://frontendmasters.com/courses/git-in-depth/) [观看][付费]

- [Git高级教程](https://www.atlassian.com/git/tutorials/advanced-overview/) [阅读]

- [专业Git](http://git-scm.com/book/en/v2) [阅读]

- [学习Git分支](http://learngitbranching.js.org/)[互动]


**参考文献与文档：**

- [https://git-scm.com/doc](https://git-scm.com/doc)

- [git-cheatsheet](https://gist.github.com/eashish93/3eca6a90fef1ea6e586b7ec211ff72a5)

### 3.33 学习构建和任务自动化

> *构建自动化是自动创建软件构建和相关过程的过程，包括：将计算机源代码编译为二进制代码、打包二进制代码和运行自动化测试。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/Build_automation) & [中文链接](https://zh.wikipedia.org/wiki/%E7%B5%84%E5%BB%BA%E8%87%AA%E5%8B%95%E5%8C%96)*
>

**基础学习：**

- [从Gulp开始](https://www.amazon.com/Getting-Started-Gulp-Travis-Maynard/dp/1784395765?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=3eb1e7a868a09b44f90570c56ef5f53b&camp=1789&creative=9325) [阅读][付费]

- [Gulp基础](http://teamtreehouse.com/library/gulp-basics) [观看][付费]

- [JavaScript使用Gulp.js自动化构建](http://www.pluralsight.com/courses/javascript-build-automation-gulpjs) [观看][付费]

**参考文献与文档：**

- [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)

Gulp是伟大的。然而，你应该只需要执行`npm run`。在转向你应用程序栈的额外复杂性之前，你应该问一下自己，`npm run`是否可以完成这样工作。如果你需要更多功能，再使用Gulp。

**阅读：**

- [抛弃Grunt，一份使用npm作为构建工具的指引](http://www.sitepoint.com/guide-to-npm-as-a-build-tool/)

- [使用npm作为你下一个项目的构建系统](https://drublic.de/blog/npm-builds)

- [使用npm作为任务运行器](http://teamtreehouse.com/library/using-npm-as-a-task-runner) [观看][付费]

- [为什么我为了npm Scripts而放弃Gulp和Grunt](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.z8plsoxxs)

- [为什么要用npm Scripts？](https://css-tricks.com/why-npm-scripts/)

### 3.34 学习站点性能优化

> *Web性能优化，WPO或网站优化是关于提升那些在用户web浏览器中已下载和已展示web页面的速度的只是知识领域。随着全球平局网络速度的提升，网站管理者和站长应该考虑呈现给用户的网站耗时。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Web_performance_optimization)*
>

**基础学习：**

- [浏览器渲染优化](https://www.udacity.com/course/browser-rendering-optimization--ud860) [观看]

- [更快的网站：Web开发者的最佳性能实践](https://www.amazon.com/Even-Faster-Web-Sites-Performance/dp/0596522304?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=4fe6a82bbf727209ba337ecaa0e516bc&camp=1789&creative=9325) [阅读]

- [高性能网站：前端工程师的关键知识](https://www.amazon.com/High-Performance-Web-Sites-Essential/dp/0596529309/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=e93ab3ea06b7e3e93ee0d868249d0e3f&camp=1789&creative=9325) [阅读][付费]

- [JavaScript性能Rock](http://javascriptrocks.com/) [阅读][付费]

- [页面速度洞察规则](https://developers.google.com/speed/docs/insights/rules)[阅读]

- [最新的性能工具](http://www.perf-tooling.today/) [阅读]

- [性能日程表](http://calendar.perfplanet.com/) [阅读]

- [性能.rock](http://perf.rocks/) [阅读]

- [使用WebPageTest](https://www.amazon.com/Using-WebPageTest-Rick-Viscomi/dp/1491902590/ref=sr_1_1?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=91a76d5d4b4f47cf4e0d1392cc9cea30&camp=1789&creative=9325) [阅读]

- [Web性能日记 第二卷](https://www.amazon.com/Web-Performance-Daybook-Techniques-Optimizing/dp/1449332919/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=59e32c394c2377bb17af1d801b924d1d&camp=1789&creative=9325) [阅读][付费]

- [网站性能](https://frontendmasters.com/courses/web-performance/) [观看][付费]

- [基于Webpack4的Web性能](https://frontendmasters.com/courses/performance-webpack/) [观看][付费]

- [网站性能优化](https://www.udacity.com/course/website-performance-optimization--ud884) [观看]

- [前端性能清单2019[PDF, Apple Pages, MS Word]](https://www.smashingmagazine.com/2019/01/front-end-performance-checklist-2019-pdf-pages/) [阅读]

### 3.35 学习测试

> *单元测试 - 在计算机编程中，单元测试是一种软件测试的方法，它是源代码的独立单元，一个或多个计算机程序模块集合，以及关联的控制数据，使用程序和操作程序，以确定他们是否适合可用。直观地，可以将单元视为程序中最小的可测试部分。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Unit_testing) & [中文地址](https://zh.wikipedia.org/wiki/%E5%8D%95%E5%85%83%E6%B5%8B%E8%AF%95)*
>
> *功能性测试 - 功能性测试是一种质量保证的过程和黑盒测试。其测试用例基于被测试软件组件的规范。功能通过提供输入和校验输出来进行测试，很少考虑其内部程序架构（与白盒测试不同）。功能性测试经常用来表示系统是做何用的？*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Functional_testing)*
>
> *集成测试 - 集成测试（有时也叫做集成与测试，缩写I&T）是软件测试中的阶段，在这个阶段，单个软件模块被组合一起并以一组进行测试。这阶段出现于单元测试之后，校验测试之前。集成测试将已经单元测试的输入模块作为输入模块，将它们分组为更大的聚合，将集成测试计划中定义的测试应用于这些聚合，并将集成系统作为输出交付给系统测试。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/Integration_testing)*
>

**基础学习：**

- [JavaScript测试实践和准则](https://frontendmasters.com/courses/testing-practices-principles/) [观看][付费]

- [前端第一要素：测试和原型JavaScript Apps](http://www.pluralsight.com/courses/testing-and-prototyping-javascript-apps) [观看][付费]

- [一起编码：测试驱动的JavaScript](http://www.letscodejavascript.com/) [观看][付费]

- [JavaScript测试](https://www.udacity.com/course/javascript-testing--ud549) [观看]

- [JavaScript测试方法](http://jstesting.jcoglan.com/) [阅读][付费]

- [可测试的JavaScript](https://www.amazon.com/gp/product/1449323391?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=a27df21b09e3eff9ad8033a5c959e7f0&camp=1789&creative=9325) [阅读][付费]

- [测试驱动的JavaScript应用程序：快速、自信、可维护的代码](https://www.amazon.com/Test-Driving-JavaScript-Applications-Confident-Maintainable/dp/1680501747?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=c97c9c87e634569328a335cba0b0c15f&camp=1789&creative=9325) [阅读][付费]

- [测试驱动的JavaScript开发](https://www.amazon.com/dp/0321683919/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=f707aa5243bf6bac68bda05d1e6369e8&camp=1789&creative=9325) [阅读][付费]

- [Web测试人员之路：自动化测试新手指引](https://www.amazon.com/Way-Web-Tester-Beginners-Automating/dp/1680501836/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=3e2c87950e0350d64c9d9862ed2ef524&camp=1789&creative=9325) [阅读][付费]

- [测试React应用程序，v2](https://frontendmasters.com/courses/testing-react/) [观看][付费]

- [学习使用Mocha，Chai和Sinon进行JavaScript单元测试](https://www.udemy.com/learn-javascript-unit-testing-with-mocha-chai-and-sinon/) [观看][付费]

### 3.36 学习无头浏览器

> *无头浏览器指的是没有图形用户界面的web浏览器。*
>
> *在一个类似于流行web浏览器环境下，无头浏览器提供web页面的自动化控制，但无头浏览器是通过命令行界面或使用网络通讯进行操作。无头浏览器对于测试web页面特别有用，正如普通浏览器一样能够渲染和理解HTML，包括样式化元素，如页面布局，色彩，字体选择，JavaScript和AJAX的执行，这在使用其他测试方法的时候往往不可用。Google在2019年声明，使用无头浏览器能够帮助他们的搜索引擎从使用AJAX的网站中索引内容。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Headless_browser)*
>

- [开始使用Headless Chrome](https://developers.google.com/web/updates/2017/04/headless-chrome)[自述文件]

[PhantomJS已不再维护](https://www.infoq.com/news/2017/04/Phantomjs-future-uncertain)，并由[Headless Chrome](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)接手。

### 3.37 学习离线开发

离线开发（又叫离线优先）是设备开发事件的一个知识点和讨论点，这些设备不会经常连接到互联网或电源。

**基础学习：**

- [创建HTML5离线Web应用程序](http://apress.jensimmons.com/v5/pro-html5-programming/ch12.html) [阅读]

- [创建离线优先Web应用程序所需的一切知识](https://github.com/pazguille/offline-first) [阅读]

- [离线优先](http://www.webdirections.org/offlineworkshop/ibooksDraft.pdf) [阅读]

- [offlinefirst.org](http://offlinefirst.org/) [阅读]

- [离线食谱](https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/) [阅读]

- [离线-快速开始](https://developers.google.com/web/ilt/pwa/offline-quickstart) [阅读]

### 3.38 学习Web安全、浏览器安全和应用程序安全

- [浏览器安全手册](https://code.google.com/p/browsersec/wiki/Main) [阅读]

- [前端安全](https://mikewest.org/2013/09/frontend-security-frontendconf-2013) [观看]

- [Hacksplaining](https://www.hacksplaining.com/) [阅读]

- [HTML5安全备忘录](https://html5sec.org/) [阅读]

- [HTTP安全最佳实践](https://httpsecurityreport.com/best_practice.html) [阅读]

- [Web开发中的身份和数据安全：最佳实践](https://www.amazon.com/Identity-Data-Security-Web-Development/dp/1491937017?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=f5f2aaa4d5f944a3ccc316a16e3673f4&camp=1789&creative=9325) [阅读]

- [Web开发者的安全：使用JavaScript，HTML，CSS](https://www.amazon.com/Security-Web-Developers-Using-JavaScript/dp/1491928646/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=df49be399d7d1a12acebe5a85637a7a8&camp=1789&creative=9325) [阅读][付费]

- [Web应用程序安全基础](http://martinfowler.com/articles/web-security-basics.html) [阅读]

- [互联网：加密和公钥](https://www.youtube.com/watch?v=ZghMPWGXexs&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7&index=6) [观看]

- [互联网：网络安全和犯罪](https://www.youtube.com/watch?v=AuYNXgO_f3Y&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7&index=7) [观看]

- [复杂的Web：保卫现代浏览器应用程序的指南](http://lcamtuf.coredump.cx/tangled/) [阅读][付费]

- [Web安全基础](https://github.com/vasanthk/web-security-basics) [阅读]

- [Web安全](https://developer.mozilla.org/en-US/docs/Web/Security) [阅读]

- [Web安全](https://frontendmasters.com/courses/web-security/) [观看][付费]

- [全栈前端工程师](https://frontendmasters.com/courses/full-stack/) [观看][付费]

### 3.39 学习多设备开发

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/things.jpg)

*图片来源: [http://bradfrost.com/blog/post/this-is-the-web/](http://bradfrost.com/blog/post/this-is-the-web/)*

网站和网页应用能够运行在许多各种不同的计算机、手提电脑、平板电脑和手机上，也能运行在新式设备上（比如手表、温度调节器、冰箱等）。你确定你将会支持哪种设备以及怎样开发来支持这些设备，称为“多设备开发策略”。以下，我列举了最常见的多设备开发策略。

- 为所有设备构建一个[响应式（RWD）](https://en.wikipedia.org/wiki/Responsive_web_design)网站或应用程序。

- 为所有设备构建一个可适配且渐进式增强的网站或应用程序。

- 为了每个独立设备或一组设备构建一个网站，web应用，原生应用或混合应用。

- 尝试使用策略1，2，3中的小部分和部分来改造你已经构建的东西。

**基础学习：**

- [分开打包之书 - 响应式Web设计](https://abookapart.com/collections/responsive-design) [阅读][付费]

- [分开打包之书 - 为所有设备设计](https://abookapart.com/collections/design-for-any-device) [阅读][付费]

- [适配式Web设计](https://www.amazon.com/gp/product/0134216148?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=defa398e66db76e7edbb8ddfa28caa1e&camp=1789&creative=9325) [阅读]

- [使用渐进式增强的方式进行设计](https://www.amazon.[付费]com/Designing-Progressive-Enhancement-Building-Everyone/dp/0321658884/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=bdac6f12a3d24fe694468aa8145001eb&camp=1789&creative=9325) [阅读][付费]

- [移动Web开发](https://www.udacity.com/course/mobile-web-development--cs256) [观看]

- [用于响应式Web设计的CSS Grid和Flexbox](https://frontendmasters.com/courses/css-grids-flexbox/) [观看][付费]

- [响应式HTML邮件设计](https://frontendmasters.com/courses/responsive-email/) [观看][付费]

- [响应式图片](https://www.udacity.com/course/responsive-images--ud882) [观看][付费]

- [响应式Web排版，v2](https://frontendmasters.com/courses/responsive-typography-v2/) [观看][付费]

- [响应式Web设计基础理论](https://www.udacity.com/course/responsive-web-design-fundamentals--ud893) [观看]

## 第4章 学习前端开发：讲师指导资源和建议

本章重点介绍了通过前端开发学校、课程、计划和训练营等一些讲师指导学习的选择。  

以下表格包含一小部分由教师指导的课程（计划、学校和训练营）。 使用该表可以大致了解可用的内容和课程的成本、持续时间和位置。 （请注意，信息可能会实时更新）  

| 公司 | 方案 | 估计价格 | 现场支持 | 远程 | 周期 |
| :--- | :--- | :---: | :--- | :--- | :--- |
| Betamore |  [前端Web开发](http://betamore.com/academy/front-end-web-development/) | 3,000 | Baltimore, MD | | 10周 |
| BLOC |  [成为前端开发者](https://www.bloc.io/frontend-development-bootcamp) | 4,999 | | 是 | 16周(每周25小时) 或 32周(每周10小时) |
| General Assembly | [前端Web开发](https://generalassemb.ly/education/front-end-web-development) | 3,500 | 多个地点 | 8周，每周2天，每天3小时 |
| Thinkful | [前端Web开发](http://www.thinkful.com/courses/learn-web-development-online) | 300/月 | | 是 | 3个月，每周15小时 |
| 图灵软件设计学院 | [前端工程](https://www.turing.io/programs/front-end-engineering) | 20,000 | Denver, CO | | 7个月全职 |

> 注：
>
> 1. 有关评估学校、课程、计划和训练营的完整列表，请查看[switchup.org](https://www.switchup.org/front-end-development)或[coursereport.com](https://www.coursereport.com/tracks/front-end-developer-bootcamps)。
>

如果你负担不起（可能非常昂贵的）定向教育，使用回放屏幕录像、书籍和文章进行自学，也是自学前端开发的可行方法。

## 第5章 前端开发工具

本章讲述了行业的工具。 在研究工具本身之前，一定要了解一组工具所属的类别。请注意，仅仅因为列出了一个工具，或者记录了一类工具，这并不等于我认为前端开发者应该学习并使用它。 选择自己的工具箱。 我只是提供常见的工具箱选项而已。

### 5.1 Doc/API浏览工具

**浏览常见的开发者文档和API参考工具。**

+ [Dash](https://kapeli.com/dash) [OS X, iOS][付费]

+ [DevDocs](http://devdocs.io/)

+ [Velocity](https://velocity.silverlakesoftware.com/) [Windows][付费]

+ [Zeal](https://zealdocs.org/) [Windows, Linux]

**备忘单：**

+ [devhints.io](https://devhints.io/)

### 5.2 SEO工具

**常规SEO工具：**

+ [关键字工具](http://keywordtool.io/)

+ [Google网站管理员搜索控制台](https://www.google.com/webmasters/)

+ [Varvy SEO工具](https://varvy.com/tools/)


**用于查找SEO工具的工具：**

+ [SEO工具 - 完整列表](http://backlinko.com/seo-tools)

+ [CuratedSEOTools - 最好的SEO工具的策划目录](https://curatedseotools.com/)

### 5.3 原型图和线框工具

**创建：**

+ [Axure](http://www.axure.com/) [付费]

+ [界面原型制作工具](https://balsamiq.com/) [付费]

+ [Justinmind](http://www.justinmind.com/) [付费]

+ [Moqups](https://moqups.com/) [付费]

+ [proto.io](https://proto.io/) [付费]

+ [UXPin](http://www.uxpin.com/) [免费]

**协作和展示：**

+ [InVision](http://www.invisionapp.com/) [免费]

+ [Conceptboard](https://conceptboard.com/) [免费]

+ [myBalsamiq](https://balsamiq.cloud/) [付费]

+ [Marvel](https://marvelapp.com/) [免费]

### 5.4 图表工具

+ [draw.io](https://www.draw.io/) [免费]

+ [Cacoo](https://cacoo.com/) [免费]

+ [gliffy](https://www.gliffy.com/products/online/) [免费]

+ [sketchboard.io](https://sketchboard.io/) [付费]

### 5.5 HTTP和网络工具

+ [Charles](http://www.charlesproxy.com/) [付费]

+ [Chrome DevTools Network面板](https://developers.google.com/web/tools/chrome-devtools/profile/network-performance/resource-loading)

+ [Insomnia](https://insomnia.rest/) [免费]

+ [Mitmproxy](https://mitmproxy.org/) [免费]

+ [Paw](https://paw.cloud/) [付费]

+ [Postman](https://www.getpostman.com/) [免费]

### 5.6 代码编辑工具

> *源代码编辑器是一种文本编辑器程序，专门用于程序员编辑计算机程序的源代码。 它可以是独立的应用程序，也可以内置在集成开发环境（IDE）或者在Web浏览器中。 源代码编辑器是最基本的编程工具，因为程序员的基本工作是编写和编辑源代码。*
>
> *- [维基百科](https://en.wikipedia.org/wiki/Source_code_editor)* 
>

使用Notepad或者TextEdit等简单的文本编辑应用程序可以最低限度地编辑前端代码。但是，大多数前端从业者使用专门设计的代码编辑器来编辑编程语言。

可以这么说，代码编辑器有各种类型和大小。 选择哪一个都是相当主观的。 选择一个从里到外地学习，然后继续学习HTML、CSS、DOM和JavaScript。

但是，我坚信，代码编辑器应该具有以下特性（默认情况下或者通过插件）：

1. 关于如何使用编辑器的良好文档  

2. 关于HTML、CSS和JavaScript的代码质量报告（即提示、校验和错误信息）。  

3. 为HTML、CSS和JavaScript提供语法高亮显示。  

4. 为HTML、CSS和JavaScript提供代码补全。  

5. 可以通过插件机制进行定制。

6. 提供大型第三方插件库和社区插件库，可以根据自己的喜好自定义编辑器。

7. 小巧、简单、不与代码耦合（即不需要编辑代码）。

**代码编辑器：**

+ [Atom](https://atom.io/)

+ [Sublime Text](http://www.sublimetext.com/) [付费]

+ [WebStorm](https://www.jetbrains.com/webstorm/whatsnew/) [付费]

+ [Visual Studio Code](https://code.visualstudio.com/)

**在线代码编辑器：**

+ [PaizaCloud](https://paiza.cloud/) [免费]

+ [AWS Cloud9](https://aws.amazon.com/cloud9/) [付费]

+ [Codeanywhere](https://codeanywhere.com/) [免费]

+ [StackBliz](https://stackblitz.com/)

+ [codeSandbox](https://codesandbox.io/)

**可共享和可运行的简易代码编辑器：**


用于共享有限数量的可立即运行的代码。不是真正的代码编辑器，而是用于在Web浏览器中共享少量可立即运行代码的工具。

+ [CodePen](http://codepen.io/) [免费]

+ [jsbin.com](http://jsbin.com/) [免费]

+ [jsfiddle.net](http://jsfiddle.net/)

+ [glitch](https://glitch.com/)

我推荐使用Visual Studio Code，因为该工具的质量以及对编辑器的持续改进，其由Microsoft提供支持，因此不会停止它的维护和减慢它的更新速度。它被广泛使用：

![Performance](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/vscode.png)

*图片来源: [https://2018.stateofjs.com/other-tools/text_editors](https://2018.stateofjs.com/other-tools/text_editors)*

### 5.7 浏览器工具

**修正浏览器的JS实用工具：**

+ [History.js](https://github.com/browserstate/history.js)

+ [html2canvas](https://github.com/niklasvh/html2canvas)

+ [Platform.js](https://github.com/bestiejs/platform.js)

+ [URI.js](http://medialize.github.io/URI.js/)


**用于确定某个浏览器是否支持某个属性或者标签的常规参考工具：：**

+ [浏览器支持已损坏或者丢失的图像](http://codepen.io/bartveneman/full/qzCte/)

+ [Browserscope](http://www.browserscope.org/)

+ [caniuse.com](http://caniuse.com/)

+ [Firefox平台状态 - Web平台功能的实施和标准化路线图](https://platform-status.mozilla.org/)

+ [请用HTML5](http://html5please.com/)

+ [HTML5测试](https://html5test.com/)

+ [iwanttouse.com](http://www.iwanttouse.com/)

+ [Web平台测试仪表板](https://wpt.fyi/)

+ [whatwebcando.today](https://whatwebcando.today/)

**浏览器开发和调试工具：**

+ [Chrome开发者工具（又名DevTools）](https://developers.google.com/web/tools/?hl=en)

  + [Per-Panel文档](https://developers.google.com/web/tools/chrome-devtools/#docs)
  
  + [命令行API参考](https://developers.google.com/web/tools/javascript/command-line/command-line-reference?hl=en)
  
  + [键盘和UI快捷方式参考](https://developers.google.com/web/tools/iterate/inspect-styles/shortcuts)
  
  + [设置](https://developer.chrome.com/devtools/docs/settings)
  
+ [Firefox开发者工具](https://developer.mozilla.org/en-US/docs/Tools)

+ [Safari Web检查工具](https://developer.apple.com/safari/tools/)

+ [Vorlon.js](http://vorlonjs.com/)

**用于确定某个浏览器是否支持某个对象的JavaScript实用程序：**

+ [Feature.js](http://featurejs.com/)

+ [Modernizr](https://modernizr.com/)

**浏览器广泛支持的Polyfill和Shim**

+ [console-polyfill](https://github.com/paulmillr/console-polyfill)

+ [HTML5跨浏览器Polyfill](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills)

+ [fetch](https://github.com/github/fetch)

+ [socket.io](http://socket.io/)

+ [SockJS](https://github.com/sockjs/sockjs-client)

+ [webcomponents.js](https://github.com/WebComponents/webcomponentsjs)

+ [webshim](https://afarkas.github.io/webshim/demos/)

**浏览器的托管测试和自动化：**

+ [Browserling](https://www.browserling.com/) [免费]

+ [BrowserStack](https://www.browserstack.com/) [付费]

+ [CrossBrowserTesting.com](http://crossbrowsertesting.com/) [付费]

+ [Ghost Inspector](https://ghostinspector.com/) [免费]

+ [Nightcloud.io](http://nightcloud.io/)

+ [Sauce实验室](https://saucelabs.com/) [付费]

**无头浏览器:**

+ [slimerjs](http://slimerjs.org/)

+ [Zombie.js](http://zombie.js.org/)

+ [无头Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)

**自动化浏览器**

用于功能测试和[monkey测试](https://en.wikipedia.org/wiki/Monkey_testing)。

+ [CasperJS](http://casperjs.org/)

+ [Nightmare](https://github.com/segmentio/nightmare)

+ [TestCafe](https://github.com/DevExpress/testcafe)

**浏览器Hack**

+ [browserhacks.com](http://browserhacks.com/)

**浏览器同步工具：**

+ [Browsersync](http://www.browsersync.io/)

**浏览器列表：**

在不同的前端工具之间共享目标浏览器，例如Autoprefixer、Stylelint和babel-preset-env。

+ [Browserslist](https://github.com/ai/browserslist)
  + [http://browserl.ist/](http://browserl.ist/?q=%3E+2%25)

### 5.8 HTML工具

**HTML模板、样板和新手入门学习工具包：**

+ [dCodes](http://www.dcodes.net/2/docs/index.html)

+ [电子邮件样板](https://github.com/seanpowell/Email-Boilerplate)

+ [HTML模板](https://html5boilerplate.com/)

+ [HTML骨骼](http://html5bones.com/)

+ [移动模板](https://html5boilerplate.com/mobile/)

**HTML Polyfill：**

+ [html5shiv](https://github.com/aFarkas/html5shiv)

**转译：**

+ [Pug](https://pugjs.org/api/getting-started.html)

+ [Markdown](http://daringfireball.net/projects/markdown/)

**参考：**

+ [元素属性](https://html.spec.whatwg.org/multipage/indices.html#attributes-3)

+ [元素](https://html.spec.whatwg.org/multipage/indices.html#elements-3)

+ [HTML箭头](http://htmlarrows.com/)

+ [HTML实体查询](http://entity-lookup.leftlogic.com/)

+ [htmlreference.io](http://htmlreference.io/)

+ [HEAD - 免费的元素指南](https://gethead.info/)

**Linting和提示：**

+ [HTMLHint](http://htmlhint.com/)

+ [HTML-检查工具](https://github.com/philipwalton/html-inspector)

**优化**

+ [HTML压缩](http://kangax.github.io/html-minifier/)

**在线创建、生成和实验的工具：**

+ [tablesgenerator.com](http://www.tablesgenerator.com/)

**编码规范**

+ [HTML代码指南](http://codeguide.co/#html)

+ [一致的、语义化的HTML编写原则](https://github.com/necolas/idiomatic-html)

**工作流：**

+ [Emmet](http://emmet.io/)

**HTML大纲视图：**

+ [HTML5大纲视图](https://gsnedders.html5.org/outliner/)

**本月在GitHub上流行的HTML库：**

[https://github.com/trending?l=html&since=monthly](https://github.com/trending?l=html&since=monthly)

### 5.9 CSS工具

**CSS[实用工具](https://css-tricks.com/need-css-utility-library/):**

* [Basscss](http://basscss.com/)

* [Skeleton](http://getskeleton.com/)

* [Shed](http://tedconf.github.io/shed-css/)

* [Tailwind CSS](https://tailwindcss.com/)

* [Tachyons](https://github.com/tachyons-css/tachyons/)

**CSS框架(实用工具 + UI):**

* [Base](http://getbase.org/)

* [Bulma](http://bulma.io/)

* [Bootstrap 4](https://v4-alpha.getbootstrap.com/)

* [Concise](http://concisecss.com/)

* [Foundation](http://foundation.zurb.com/)

* [Material Design Lite (MDL)](http://www.getmdl.io/index.html)

* [Metro UI](http://metroui.org.ua/)

* [Mini.css](https://minicss.org/)

* [Mobi.css](http://getmobicss.com/)

* [Picnic](http://picnicss.com/)

* [Pure.css](http://purecss.io/)

* [Semantic UI](http://semantic-ui.com/)

* [Shoelace](https://shoelace.style/)

* [Spectre.css](https://picturepan2.github.io/spectre/)

**纯移动端的CSS框架：**

* [Ratchet](http://goratchet.com/)

**CSS重置：**

> *CSS重置(又叫“重置CSS”)是一组简短的、通常经过压缩(缩小)的CSS规则，用于将所有HTML元素的样式重置为一致的基线。*
> 
> *—[cssreset.com](http://cssreset.com/what-is-a-css-reset/)*

* [Eric Meyer的“Reset CSS” 2.0](https://meyerweb.com/eric/tools/css/reset/)

* [Normalize](https://necolas.github.io/normalize.css/)

* [sanitize.css](https://github.com/jonathantneal/sanitize.css)

**转译：**

* [pleeease.io](http://pleeease.io/)

* [PostCSS](https://github.com/postcss/postcss) & [cssnext](http://cssnext.io/)

* [rework](https://github.com/reworkcss/rework) & [myth](http://www.myth.io/)

**参考文献:**

* [CSS Cursors](http://csscursor.info/)

* [css3test.com](http://css3test.com/)

* [css3clickchart.com](http://css3clickchart.com/)

* [cssreference.io](http://cssreference.io/)

* [CSS索引 - CSS规范定义每个术语的列表](https://drafts.csswg.org/indexes/)

* [css4-selectors.com](http://css4-selectors.com/)

* [css4 Rocks](http://css4.rocks/)

* [CSS触发器...布局、绘制和合成的游戏](http://csstriggers.com/)

* [CSS Tricks Almanac](https://css-tricks.com/almanac/)

* [cssvalues.com](http://cssvalues.com/)

* [MDN CSS参考](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

* [CSS备忘单](https://adam-marsden.co.uk/css-cheat-sheet/)

* [CSS的下一步是什么？](https://cssdb.org/)

**校验和提示:**

* [CSS Lint](http://csslint.net/)

* [stylelint](http://stylelint.io/)

**代码格式化和美化：**

* [CSScomb](https://github.com/csscomb/csscomb.js)

* [CSSfmt](https://github.com/morishitter/cssfmt)

**优化：**

* [clean-css](https://github.com/jakubpawlowicz/clean-css)

* [cssnano](http://cssnano.co/)

* [CSSO](http://css.github.io/csso/)

* [purgecss](https://github.com/FullHuman/purgecss)

**在线创建、生成和测试工具:**

* [请用CSS箭头](http://cssarrowplease.com/)

* [CSS Matic](http://www.cssmatic.com/)

* [享受CSS](http://enjoycss.com/)

* [flexplorer](http://bennettfeely.com/flexplorer/)

* [patternify.com](http://patternify.com)

* [patternizer.com](http://patternizer.com/)

* [极限CSS梯型编辑器](http://www.colorzilla.com/gradient-editor/)

**CSS架构设计：**

* [Atomic Design](http://atomicdesign.bradfrost.com/) \[阅读\]

* [BEM](http://getbem.com/introduction/)

* [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/)

* [OOCSS](http://oocss.org/) \[阅读\]

* [SMACSS](https://smacss.com/) \[阅读\]\[付费\]

  * [CSS的可扩展模块化体系结构(SMACSS)](https://frontendmasters.com/courses/smacss/) \[观看\]\[付费\]
  
* [SUIT CSS](http://suitcss.github.io)

* [rscss](http://rscss.io/)

<!-- Authoring/Architecting Conventions: -->
**编辑和框架约定：**

* [CSS代码指南](http://codeguide.co/#css) \[阅读\]

* [CSS框架](https://github.com/jareware/css-architecture) \[阅读\]

* [cssguidelin.es](http://cssguidelin.es/) \[阅读\]

* [常用的CSS](https://github.com/necolas/idiomatic-css) \[阅读\]

* [可维护的CSS](http://maintainablecss.com/) \[阅读\]

* [HTML和CSS灵活开发、持久和可持续的标准](http://mdo.github.io/code-guide/) \[阅读\]

* [Airbnb CSS和Sass风格指南](https://github.com/airbnb/css) \[阅读\]

**风格指南资源：**

* [Frontify](https://frontify.com/) \[付费\]

* [SC5 STYLE GUIDE GENERATOR](http://styleguide.sc5.io/)

* [styleguide-generators](https://github.com/davidhund/styleguide-generators)

* [Catalog](https://docs.catalog.style/)

**CSS in JS:**

* [样式组件](https://www.styled-components.com/)

* [Emotion](https://emotion.sh/docs/introduction)

* [Radium](https://formidable.com/open-source/radium/)

* [Aphrodite](https://github.com/Khan/aphrodite)

**本月在GitHub上流行的CSS库：**

[https://github.com/trending?l=css&since=monthly](https://github.com/trending?l=css&since=monthly)

### 5.10 DOM工具

**DOM库和框架：**

* [Bliss](http://blissfuljs.com/docs.html)

* [jQuery](http://jquery.com/)

  * [你不需要jQuery](https://github.com/oneuijs/You-Dont-Need-jQuery)

* [Zepto](http://zeptojs.com/)

* [cash](https://github.com/kenwheeler/cash/)

* [Umbrella JS](http://umbrellajs.com/)

* [nanoJS](https://vladocar.github.io/nanoJS/)

**DOM实用工具：**

* [Keypress](http://dmauro.github.io/Keypress/)

* [Tether](http://tether.io/docs/welcome/)

* [clipboard.js](http://zenorocha.github.io/clipboard.js/)

**DOM事件工具：**

* [键盘事件查看器](http://w3c.github.io/uievents/tools/key-event-viewer.html)

**DOM性能工具：**

* [Chrome DevTools Timeline](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/timeline-tool)

* [DOM Monster](http://mir.aculo.us/dom-monster/)

**参考文献：**

* [事件](https://html.spec.whatwg.org/#events-2)

* [DOM浏览器支持](http://www.webbrowsercompatibility.com/dom/desktop/)

* [DOM事件浏览器支持](http://www.webbrowsercompatibility.com/dom-events/desktop/)

* [HTML接口浏览器支持](http://www.webbrowsercompatibility.com/html-interfaces/desktop/)

* [MDN 文档对象模型（DOM）](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

* [MDN 浏览器对象模型（BOM）](https://developer.mozilla.org/en-US/docs/Web/API/Window)

* [MDN 文档对象模型](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

* [MDN 事件引用](https://developer.mozilla.org/en-US/docs/Web/Events)

* [MSDN 文档对象模型（DOM）](https://msdn.microsoft.com/en-us/library/hh772384%28v=vs.85%29.aspx)

**DOM Polyfill和Shim:**

* [dom-shims](https://github.com/necolas/dom-shims)

* [指针事件Polyfill: 一个统一的Web平台事件系统](https://github.com/jquery/PEP)

**虚拟DOM:**

* [jsdom](https://github.com/tmpvar/jsdom)

* [虚拟DOM](https://github.com/Matt-Esch/virtual-dom)

### 5.11 JavaScript工具

**JS使用工具：**

* [accounting.js](http://openexchangerates.github.io/accounting.js/)

* [async](http://caolan.github.io/async/)

* [axios](https://github.com/mzabriskie/axios)

* [chance](http://chancejs.com/)

* [date-fns](https://date-fns.org/)

* [dinero](https://sarahdayan.github.io/dinero.js/module-Dinero.html)

* [Finance.js](http://financejs.org/)

* [format.js](http://formatjs.io/)

* [Howler.js](https://howlerjs.com)

* [immutable](https://facebook.github.io/immutable-js/)

* [is.js](http://arasatasaygin.github.io/is.js/)

* [lodash](https://lodash.com/)

  * [You-Dont-Need-Lodash-Underscore](https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore)

* [Luxon](https://moment.github.io/luxon/)

  * [你（可能）不需要Moment.js](https://github.com/you-dont-need/You-Dont-Need-Momentjs)

* [Math.js](http://mathjs.org/)

* [Moment.js](http://momentjs.com/)

* [Numeral.js](http://numeraljs.com/)

* [Ramda](http://ramdajs.com/)

* [RxJS](http://reactivex.io/rxjs/)

* [string.js](http://stringjs.com/)

* [TheoremJS](https://theorem.js.org/)

* [voca](https://vocajs.com/)

* [wait](https://github.com/elving/wait)

* [xregexp.com](http://xregexp.com/)

**转换JavaScript对象工具:**

* [transform-www](https://transform.now.sh/)

**转译和类型检查(ES _to ES_):**

* [TypeScript](https://www.typescriptlang.org/)

**类型检查(ES _to ES_):**

* [Flow](https://flowtype.org/)

**转译(ES _to ES_):**

* [Babel](https://babeljs.io/)

* [sucrase](https://sucrase.io)

* [scw](https://swc-project.github.io/)

**代码分析引擎：**

* [Tern](https://ternjs.net/)

**校验提示和风格校验:**

* [eslint](http://eslint.org/)

**单元测试：**

* [AVA](https://github.com/avajs/ava)

* [Jasmine](http://jasmine.github.io/)

* [Mocha](http://mochajs.org/)

* [Tape](https://github.com/substack/tape)

**单元测试的测试断言：**

* [Chai](http://chaijs.com/)

* [expect.js](https://github.com/Automattic/expect.js)

* [should.js](http://shouldjs.github.io/)

**用于单元测试的测试间谍、存根和Mocks:**

* [sinon.js](http://sinonjs.org/)

* [Kakapo.js](http://devlucky.github.io/kakapo-js)

**代码格式化和美化：**

* [esformatter](https://github.com/millermedeiros/esformatter#esformatterformatstr-optsstring)

* [js-beautify](http://jsbeautifier.org/)

* [jsfmt](http://rdio.github.io/jsfmt/)

* [prettier](https://github.com/jlongster/prettier)

**性能测试：**

* [benchmark.js](http://benchmarkjs.com/)

* [jsperf.com](https://jsperf.com/)

**可视化、静态分析、复杂度、覆盖工具：**

* [Coveralls](https://coveralls.io/) \[付费\]

* [Esprima](http://esprima.org/)

* [istanbul](https://github.com/gotwarlost/istanbul)

**优化:**

* [闭包编译器](https://developers.google.com/closure/compiler/)

* [Terser](https://github.com/terser-js/terser)

* [optimize-js](https://github.com/nolanlawson/optimize-js)

* [Prepack](https://prepack.io/)

**混淆：**

* [Javascript混淆工具](http://www.javascriptobfuscator.com/) \[免费\]

* [JScrambler](https://jscrambler.com/) \[付费\]

**可分享和可运行的代码编辑器:**

* [CodeSandbox](https://codesandbox.io/) \[免费\]

**在线正则表达式编辑器和可视化工具:**

* [debuggex](https://www.debuggex.com)

* [regex101](https://regex101.com/)

* [regexper](http://regexper.com/)

* [RegExr](http://regexr.com/)

**编写规范工具：**

* [Airbnb的ESLint配置，遵循我们的样式指南](https://www.npmjs.com/package/eslint-config-airbnb)

* [标准-ESLint可共享Config](https://github.com/feross/eslint-config-standard)

**本月在GitHub上流行的JS库：**

[https://github.com/trending?l=javascript&since=monthly](https://github.com/trending?l=javascript&since=monthly)

**被依赖最多的NPM包：**

[https://www.npmjs.com/browse/depended](https://www.npmjs.com/browse/depended)

### 5.12 无头内容管理系统工具

**站点生成器列表：**

* [无头CMS](https://headlesscms.org/)

### 5.13 静态站点生成器工具

**站点生成器列表：**

* [staticgen.com](https://www.staticgen.com/)

* [staticsitegenerators.net](https://staticsitegenerators.net/)

### 5.14 无障碍工具

**指南**

* [A11Y风格指南](http://a11y-style-guide.com/style-guide/)

* [无障碍指南清单](http://accessibility.voxmedia.com)

* [交互式WCAG 2.0](http://code.viget.com/interactive-wcag/)

* [18F无障碍指南](https://pages.18f.gov/accessibility/checklist/)

**网站扫描仪**

* [aXe浏览器扩展](http://www.deque.com/products/axe/)

* [Chrome辅助开发工具](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb)

* [Tenon无障碍工具](https://tenon.io)

* [WAVE无障碍工具](http://wave.webaim.org)

**颜色对比测试**

* [Colorable](http://jxnblk.com/colorable/demos/text/)

* [Colorable Matrix](http://jxnblk.com/colorable/demos/matrix/)

* [安全色](http://colorsafe.co)

* [颜色比](http://leaverou.github.io/contrast-ratio/)

**低视力模拟器**

* [SEE](https://chrome.google.com/webstore/detail/see/dkihcccbkkakkbpikjmpnbamkgbjfdcn) (Chrome)

* [Spectrum](https://chrome.google.com/webstore/detail/spectrum/ofclemegkcmilinpcimpjkfhjfgmhieb) (Chrome)

* [NoCoffee](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl) (Chrome)

**屏幕阅读器**

* [VoiceOver](http://www.apple.com/accessibility/) (Mac)

* [JAWS](http://www.freedomscientific.com/Products/Blindness/JAWS) (Win)

* [NVDA](https://www.nvaccess.org) (Win)

* [ChromeVox](http://www.chromevox.com) (Chrome浏览器扩展)

* [基本屏幕阅读器命令](https://www.paciellogroup.com/blog/2015/01/basic-screen-reader-commands-for-accessibility-testing/)

**可读性测试**

* [Expresso App](http://www.expresso-app.org)

* [Hemingway App](http://www.hemingwayapp.com)

* [Grammarly](https://www.grammarly.com)

* [可读性评分](https://readability-score.com/text/)

* [MS Office](https://support.office.com/en-us/article/Test-your-document-s-readability-0adc0e9a-b3fb-4bde-85f4-c9e88926c6aa)

**文章**

* [ARIA快速入门](http://a11yproject.com/posts/getting-started-aria/)

* [重新定义Web的无障碍](http://alistapart.com/article/reframing-accessibility-for-the-web)

* [无障碍问题的字母表](https://the-pastry-box-project.net/anne-gibson/2014-July-31)

* [实用ARIA实例](http://heydonworks.com/practical_aria_examples/)

* [MDN无障碍指南](https://developer.mozilla.org/en-US/docs/Learn/Accessibility)

* [在Chrome开发工具中启用无障碍面板](https://umaar.com/dev-tips/101-accessibility-inspection/)

### 5.15 应用程序框架（桌面、移动、平板电脑等）工具

**前端应用程序框架:**

* [AngularJS](https://github.com/angular/angular.js) (即Angular 1.x.x) + [Batarang](https://github.com/angular/angularjs-batarang)

* [Angular](https://github.com/angular/angular) (即Angular 2.0.0 +) + [angular-cli](https://github.com/angular/angular-cli)

* [Aurelia](http://aurelia.io/) \+ [Aurelia CLI](https://github.com/aurelia/cli)

* [Ember](http://emberjs.com/) \+ [embercli](https://ember-cli.com/) \+ [Ember检查工具](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi?hl=en)

* [Polymer](https://www.polymer-project.org/1.0/)

* [React](http://facebook.github.io/react/) \+ [create-react-app](https://github.com/facebookincubator/create-react-app) \+ [React开发者工具](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)

* [Vue.js](http://vuejs.org/) \+ [vue-cli](https://github.com/vuejs/vue-cli) & [Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en)

* [Riot](http://riotjs.com/)

**原生混合移动WebView (即浏览器引擎驱动) 框架:**

这些解决方案通常使用[Cordova](https://cordova.apache.org/)、[crosswalk](https://crosswalk-project.org/)或者自定义WebView作为到原生API的桥梁。

* [ionic](http://ionicframework.com/)

* [onsen.io](http://onsen.io/)

**原生混合移动开发Webview(即浏览器引擎驱动)环境、平台和工具:**

这些解决方案通常使用[Cordova](https://cordova.apache.org/)、[crosswalk](https://crosswalk-project.org/)或者自定义WebView作为到原生API的桥梁。

* [Adobe PhoneGap](http://phonegap.com/) \[付费\]

* [cocoon.io](https://cocoon.io) \[免费\]

* [ionic hub](http://ionic.io/) \[免费\]

* [kony](http://www.kony.com/products/mobility-platform) \[付费\]

* [Monaca](https://monaca.io/) \[付费\]

**原生桌面应用程序框架:**

* [Electron](http://electron.atom.io/)

* [NW.js](https://github.com/nwjs/nw.js)

* [proton](https://proton-native.js.org/#/)

* [Neutralino.js](https://neutralino.js.org/)

* [DeskGap](https://deskgap.com/)

**原生移动应用程序框架(又叫JavaScript原生应用程序)**

这些解决方案在运行时使用JS引擎来解释JS并将其连接到本地API。无需使用浏览器引擎或者WebView。UI由原生UI组件构造。

* [Flutter](https://flutter.io/)

* [NativeScript](https://www.nativescript.org/)

* [React Native](https://facebook.github.io/react-native/)

* [tabris.js](https://tabrisjs.com/) \[免费\]

* [trigger.io](https://trigger.io/how-it-works/) \[付费\]

* [weex](https://weex.apache.org/)

**参考文献和演示应用程序:**

* [todomvc.com](http://todomvc.com/)

* [RealWorld示例应用程序](https://github.com/gothinkster/realworld) \[代码\]

* [前端准则草案](https://github.com/bradfrost/frontend-guidelines-questionnaire)

* [前端准则](https://github.com/bendc/frontend-guidelines)

**性能：**

* [js-framework-benchmark](https://github.com/krausest/js-framework-benchmark)

* [前端性能检查列表2019\[PDF、Apple Pages、MS Word\]](https://www.smashingmagazine.com/2019/01/front-end-performance-checklist-2019-pdf-pages/) \[阅读\]

如果你是前端JavaScript应用程序开发新手，我建议从[Vue.js](http://vuejs.org/)开始。然后我会把[React](http://facebook.github.io/react/)应用到工作中。然后我也会学习 [Angular 2+](https://angular.io/), [Ember](http://emberjs.com/), or [Aurelia](http://aurelia.io/)。

如果你正在构建一个与数据交互最少的简单网站(主要是静态内容的网站)，那么应该避免使用前端框架。使用像[Gulp and jQuery](https://github.com/vigetlabs/blendid)这样的任务运行器可以完成很多工作，同时避免了不必要的学习和使用应用程序框架工具的复杂性。

想要比“React”精巧的框架，考虑一下“[Preact](https://preactjs.com/)”。
Preact试图以用尽可能少的代码来重新创建React(或类似的库，如Mithril)的核心价值主张，并优先为ES2015提供支持。目前该库大约为3kb(minified和gzipped)。

### 5.16 管理JavaScript应用程序的工具

* [JSUI](https://github.com/kitze/JSUI)


### 5.17 状态工具

* [Redux](https://redux.js.org/)

* [Mobx](https://mobx.js.org/)

* [mobx-state-tree](https://github.com/mobxjs/mobx-state-tree)

* [Cerebral](https://github.com/cerebral/cerebral)

* [freactal](https://github.com/FormidableLabs/freactal)

* [unistore](https://github.com/developit/unistore)

* [unstated](https://github.com/jamiebuilds/unstated)

* [Vuex](https://vuex.vuejs.org/en/)

### 5.18 渐进式Web应用程序工具：

* [lighthouse](https://developers.google.com/web/tools/lighthouse/)

* [渐进式Web应用程序清单](https://developers.google.com/web/progressive-web-apps/checklist)

### 5.19 GUI开发和构建工具

* [CodeKit](http://incident57.com/codekit/)

* [Prepros](https://prepros.io/)

* [KoalaApp](http://koala-app.com/) \[免费\]

### 5.20 模板和数据绑定工具

**模板:**

* [doT.js](http://olado.github.io/doT/)

* [art-template](https://aui.github.io/art-template/)

* [Nunjuncks](http://mozilla.github.io/nunjucks/)

**模板和双向数据绑定:**

* [ractive.js](https://ractive.js.org/)

* [react.js](https://facebook.github.io/react/index.html)

  * [preact](https://preactjs.com/)

  * [inferno](https://infernojs.org/)

  * [nerv](https://github.com/NervJS/nerv)

  * [rax](https://github.com/alibaba/rax)

* [riot](http://riotjs.com/)

* [Rivets.js](http://rivetsjs.com/)

* [vue.js](http://vuejs.org/)

**虚拟DOM模板:**

* [JSX](https://facebook.github.io/jsx/)

### 5.21 UI小部件和组件工具包

**Web平台：**

* jQuery的[Kendo UI](http://www.telerik.com/kendo-ui) \[免费\]

* [Materialize](http://materializecss.com/)

* [Office UI结构](http://dev.office.com/fabric)

* [语义化的UI](http://semantic-ui.com/)

* [UiKit](https://getuikit.com/)

* [Webix](http://webix.com/) \[付费\]

**Web平台上React规范**

* [Ant Design](https://ant.design/)

* [Material ui](http://material-ui.com/)

* [Semantic-UI-React](https://react.semantic-ui.com/)

* [ExtReact](https://www.sencha.com/products/extreact/#app) \[付费\]

* [Fabric](https://developer.microsoft.com/en-us/fabric)

**原生桌面、笔记本电脑、上网本应用程序通过网络平台 (即NW.js和Electron一起使用):**

* [Photon](http://photonkit.com/)

* [OSX、EL Capitan和Windows 10的响应式UI组件](http://gabrielbull.github.io/react-desktop/)

如果需要一组基础UI小部件和组件，可以从[Semantic UI](http://semantic-ui.com/)开始。
如果你正在构建一些需要网格、电子表格或主网格的东西，你必须查看[Kendo UI](http://www.telerik.com/kendo-ui)或者[Webix](http://webix.com/)。请记住，这些解决方案中的大多数仍然需要jQuery。

### 5.22 数据可视化（例如，图表）工具

**JS库:**

* [d3](http://d3js.org/)

* [sigmajs](http://sigmajs.org/)

**Widget和组件:**

* [amCharts](http://www.amcharts.com/) \[免费\]

* [AnyChart](http://www.anychart.com/) \[非商业免费\]

* [C3.js](http://c3js.org/)

* [Chartist-jsj](https://github.com/gionkunz/chartist-js)

* [Chart.js](http://www.chartjs.org/)

* [Epoch](http://epochjs.github.io/epoch/)

* [FusionCharts](http://www.fusioncharts.com/) \[付费\]

* [Google图表](https://developers.google.com/chart/interactive/docs/)

* [Highcharts](http://www.highcharts.com/) \[非商业部分免费\]

* [ZingChart](http://www.zingchart.com/) \[部分免费\]

**服务（用于嵌入和分享的托管数据可视化服务）：**

* [ChartBlocks](http://www.chartblocks.com/) \[部分免费\]

* [Datawrapper](https://datawrapper.de/)

* [infogr.am](https://infogr.am) \[部分免费\]

* [plotly](https://plot.ly/) \[部分免费\]

### 5.23 图形（SVG、canvas、WebGL）工具

**常规:**

* [Fabric.js](http://fabricjs.com/)

* [Two.js](http://jonobr1.github.io/two.js/#introduction)

**Canvas:**

* [EaselJS](https://github.com/CreateJS/EaselJS)

* [Paper.js](http://paperjs.org/)

**SVG:**

* [d3](http://d3js.org/)

* [GraphicsJS](http://www.graphicsjs.org/)

* [Raphaël](http://dmitrybaranovskiy.github.io/raphael/)

* [Snap.svg](http://snapsvg.io/)

* [svg.js](http://svgjs.com/)

**WebGL:**

* [pixi.js](https://github.com/pixijs/pixi.js)

* [three.js](http://threejs.org/)

### 5.24 动画工具

**CSS和JavaScript实用工具：**

* [Animate Plus](https://github.com/bendc/animateplus)

* [Animate](https://github.com/daneden/animate.css)

* [Anime.js](http://animejs.com/)

* [Animista.net](http://animista.net/)

* [Dynamics.js](http://dynamicsjs.com/)

* [GreenSock-JS](http://greensock.com/)

* [Kute.js](http://thednp.github.io/kute.js/)

* [Magic](https://github.com/miniMAC/magic)

* [Micron.js](https://webkul.github.io/micron/)

* [Motion](http://mojs.io/)

* [TweenJS](https://github.com/CreateJS/TweenJS)

* [Popmotion](https://popmotion.io)

* [Velocity.js](http://julian.com/research/velocity/)

**Polyfills/Shims:**

* [web-animations-js](https://github.com/web-animations/web-animations-js)

**动画的参考文献：**

* [canianimate.com](http://canianimate.com/)

### 5.25 JSON工具

**在线编辑器：**

* [JSONmate](http://jsonmate.com/)

* [JSON在线编辑](https://jsoneditoronline.org/)

**格式化和验证：**

* [jsonformatter.org](http://jsonformatter.org/)

* [JSON格式化和校验](https://jsonformatter.curiousconcept.com/)

**查询工具：**

* [DefiantJS](http://www.defiantjs.com/)

* [JSON Mask](https://github.com/nemtsov/json-mask)

* [ObjectPath](http://objectpath.org/)

**生成模拟JSON工具:**

* [JSON生成器](http://www.json-generator.com/)

* [Mockaroo](https://www.mockaroo.com/) \[免费\]

**在线JSON模拟API工具：**

* [FillText.com](http://www.filltext.com/)

* [FakeJSON](https://fakejson.com) \[免费\]

* [Jam API](https://github.com/dinubs/jam-api)

* [JSONPlaceholder](http://jsonplaceholder.typicode.com/)

* [jsonbin.io](https://jsonbin.io)

* [jsonbin.org](https://jsonbin.org/)

* [mockable.io](https://www.mockable.io/)

* [mockapi.io](http://www.mockapi.io/)

* [Mocky](http://www.mocky.io/)

* [RANDOM USER GENERATOR](https://randomuser.me/)

**公开的JSON API列表：**

* [用于Web开发的JSON API的集合列表](https://github.com/toddmotto/public-apis)

**本地JSON模拟API工具:**

* [json-server](https://github.com/typicode/json-server)

**JSON规格和模式：**

* [json-schema.org](http://json-schema.org/) & [jsonschema.net](http://jsonschema.net/)

* [{json:api}](http://jsonapi.org/)

### 5.26 占位符内容工具

**图像：**

* [placehold.it](http://placehold.it)

* [Satyr](http://satyr.io)

* [Placeimg](http://placeimg.com)

* [Lorem像素](http://lorempixel.com)

* [CSS-Tricks图像资源](https://css-tricks.com/sites-with-high-quality-photos-you-can-use-for-free/)

* [LibreStock](http://librestock.com)

* [Unsplash](https://unsplash.it)

**Device Mockups：**

* [placeit.net](https://placeit.net)

* [mockuphone.com](http://mockuphone.com)

**文本：**

* [Meet the Ipsums](http://meettheipsums.com)

* [catipsum.com](http://www.catipsum.com/)

* [baconipsum.com](http://baconipsum.com/) ([API](http://baconipsum.com/json-api/))

**用户数据：**

* [uinames.com](https://uinames.com)

* [randomuser.me](https://randomuser.me)

### 5.27 测试工具

**软件测试框架：**

* [Intern](https://theintern.github.io/)

* [Jest](http://facebook.github.io/jest/)

  * [majestic](https://majestic.debuggable.io/)

  * [Enzyme](https://github.com/airbnb/enzyme)

  * [Cheerio](https://github.com/cheeriojs/cheerio)

**单元测试：**

* [AVA](https://github.com/avajs/ava)

* [Jasmine](http://jasmine.github.io/)

* [Mocha](http://mochajs.org/)

* [Tape](https://github.com/substack/tape)

**单元测试的测试断言：**

* [Chai](http://chaijs.com/)

* [expect.js](https://github.com/Automattic/expect.js)

* [should.js](http://shouldjs.github.io/)

**用于单元测试的测试监听，存根和模拟：**

* [sinon.js](http://sinonjs.org/)

* [Kakapo.js](http://devlucky.github.io/kakapo-js)

**浏览器的托管测试和自动化：**

* [Browserling](https://www.browserling.com/) \[付费\]

* [BrowserStack](https://www.browserstack.com) \[付费\]

* [CrossBrowserTesting.com](http://crossbrowsertesting.com/) \[付费\]

* [Nightcloud.io](http://nightcloud.io/)

* [Sauce Labs](https://saucelabs.com/) \[付费\]

**集成和功能测试：**

* [Cypress](https://www.cypress.io/)

* [Nightwatch](http://nightwatchjs.org/)

* [WebDriver.io](http://webdriver.io/)

**浏览器自动化：**

* [CasperJS](http://casperjs.org/)

* [Nightmare](https://github.com/segmentio/nightmare)

* [TestCafe](https://github.com/DevExpress/testcafe)

**UI测试工具：**

* [gremlins.js](https://github.com/marmelab/gremlins.js)

* [Percy](https://percy.io)

* [BackstopJS](https://github.com/garris/BackstopJS)

* [PhantomCSS](https://github.com/Huddle/PhantomCSS)

* [Ghost检查工具](https://ghostinspector.com/)

* [diff.io](https://diff.io/)

**死链和错误链接自动检测器：**

* [Monkey Test It](https://monkeytest.it/)

**HTTP存根**

* [Polly.JS](https://netflix.github.io/pollyjs/#/README)

### 5.28 前端数据存储工具（即客户端中的数据存储解决方案）

* [AlaSQL](http://alasql.org/)

* [Dexie.js](http://www.dexie.org/)

* [LocalForage](https://localforage.github.io/localForage/)

* [LokiJS](http://lokijs.org/#/)

* [Lovefield](https://google.github.io/lovefield)

* [lowdb](https://github.com/typicode/lowdb)

* [Pouchdb](http://pouchdb.com/)

* [NeDB](https://github.com/louischatriot/nedb)

* [RxDB](https://pubkey.github.io/rxdb/install.html)

* [ImmortalDB](https://github.com/gruns/ImmortalDB)

### 5.29 模块加载和打包工具

* [Parcel](https://parceljs.org/)

* [Rollup](http://rollupjs.org/)

  * [Microbundle](https://github.com/developit/microbundle)

* [webpack](https://webpack.js.org/)

  * [Poi](https://poi.js.org/)

  * [jetpack](https://github.com/KidkArolis/jetpack)

* [Fusebox](https://fuse-box.org/)

* [Browserify](http://browserify.org/)

### 5.30 模块和包源码仓库工具

* [NPM](https://www.npmjs.com/)

* [yarn](https://yarnpkg.com/)

* [PNPM](https://pnpm.js.org/)

### 5.31 托管工具

**常规的**

* [AWS](https://aws.amazon.com/websites/) \[付费\]

* [DigitalOcean](https://digitalocean.com) \[付费\]

* [WebFaction](https://www.webfaction.com/) \[付费\]

**静态的**

* [Firebase Hosting](https://firebase.google.com/docs/hosting/) \[免费\]

* [netlify](https://www.netlify.com) \[免费\]

  * [Bitballoon](https://www.bitballoon.com/)

* [Surge](https://surge.sh/) \[免费\]

* [Forge](https://getforge.com/) \[付费\]

### 5.32 项目管理和代码托管工具

* [Assembla](https://www.assembla.com) \[免费\]

* [Bitbucket](https://bitbucket.org) \[免费\]

* [Codebase](https://www.codebasehq.com/) \[付费\]

* [Github](https://github.com/) \[免费\]

* [GitLab](https://about.gitlab.com/) \[免费\]

* [Unfuddle](https://unfuddle.com/) \[付费\]

### 5.33 协作和通信工具

* [Slack](https://slack.com/) 和 [screenhero](https://screenhero.com/) \[免费\]

* [appear.in](https://appear.in/)

* [Mattermost](https://mattermost.org/) \[免费\]

**编码和GitHub协作与沟通：**

* [Gitter](https://gitter.im) \[免费\]

### 5.34 内容托管管理和API工具

**无头内容管理系统工具:**

* [Contentful](https://www.contentful.com/) \[付费\]

* [prismic.io](https://prismic.io/) \[免费\]

* [Headless](https://www.headless.rest/)

**自托管的无头内容管理系统工具:**

* [Cockpit](https://getcockpit.com/)

* [Directus 7 App](https://directus.io/)

**托管内容管理系统:**

* [LightCMS](https://www.lightcms.com) \[付费\]

* [Surreal CMS](http://www.surrealcms.com/) \[付费\]

**静态的内容管理系统工具:**

* [webhook.com](http://www.webhook.com/)

* [Dato CMS](https://www.datocms.com/)

* [siteleaf](https://www.siteleaf.com/)

* [forestry.io](https://forestry.io/)

### 5.35 后端和API工具

**数据和后端服务，也叫BAAS：**

* [Backendless](https://backendless.com)

* [Firebase](https://www.firebase.com/index.html) \[免费\]

* [Pusher](https://pusher.com/) \[免费\]

* [restdb.io](https://restdb.io/) \[免费\]

* [MongoDB Stitch](https://www.mongodb.com/cloud/stitch)

**数据和后端**

* [GraphQL](http://graphql.org/)

  * [Apollo](http://www.apollodata.com/)

  * [Relay](https://facebook.github.io/relay/)

* [Falcor](https://netflix.github.io/falcor/)

* [RxDB](https://github.com/pubkey/rxdb)

**用户管理服务：**

* [Auth0](https://auth0.com) \[付费\]

* [AuthRocket](https://authrocket.com)

* [Okta](https://developer.okta.com/)

**搜索**

* [Algolia](https://www.algolia.com)

### 5.36 离线工具

* [Hoodie](http://hood.ie/)

* [Offline.js](http://github.hubspot.com/offline/docs/welcome/)

* [PouchDB](http://pouchdb.com/)

* [upup](https://www.talater.com/upup/)

* [Workbox](https://developers.google.com/web/tools/workbox/)

更多相关工具，请查看 [这里](https://github.com/pazguille/offline-first#tools)。

### 5.37 安全工具

**编码工具：**

* [DOMPurify](https://github.com/cure53/DOMPurify)

* [XSS](http://jsxss.com/en/index.html)

**安全扫描仪/评估器/测试仪：**

* [Netsparker](https://www.netsparker.com)

* [Websecurify](http://www.websecurify.com/)

* [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)

**参考文献：**

* [HTML5安全备忘单](https://html5sec.org/)

### 5.38 构建工具

**任务或构建工具：**

* [Gulp](http://gulpjs.com/)

**自用任务或构建工具：**

* [Brunch](http://brunch.io/)

在接触Gulp之前，确保[npm scripts](https://docs.npmjs.com/misc/scripts)或[yarn script](https://yarnpkg.com/en/docs/package-json#toc-scripts)是否符合要求。 请阅读["我为什么留下npm Scripts抛弃了Gulp和Grunt"](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.nw3huib54)。

### 5.39 部署工具

* [Bamboo](https://www.atlassian.com/software/bamboo/) \[付费\]

* [Buddy](https://buddy.works/) \[免费\]

* [CircleCI](https://circleci.com/) \[免费\]

* [Codeship](https://codeship.com/) \[免费\]

* [Deploybot](https://deploybot.com/) \[免费\]

* [Deployhq](https://www.deployhq.com/) \[免费\]

* [FTPLOY](http://ftploy.com/) \[免费\]

* [Now](https://zeit.co/now) \[免费\]

* [Travis CI](http://docs.travis-ci.com/) \[免费\]

* [Semaphore](https://semaphoreci.com/) \[免费\]

* [Springloops](http://www.springloops.io/) \[免费\]

<!-- 5.40 - Site/App Monitoring Tools -->
### 5.40 站点和应用程序监视工具

**运行时监控：**

* [Uptime Robot](https://uptimerobot.com/) \[免费\]

**常规监控工具：**

* [Pingdom](https://www.pingdom.com/) \[免费\]

* [New Relic](http://newrelic.com/)

* [Uptrends](https://www.uptrends.com/) \[付费\]

### 5.41 JavaScript错误报告和监控

+ [bugsnag](https://bugsnag.com/) [付费]

+ [errorception](https://errorception.com/) [付费]

+ [Honeybadger](https://www.honeybadger.io/) [付费]

+ [Raygun](https://raygun.io/) [付费]

+ [Rollbar](https://rollbar.com/) [免费]

+ [Sentry](https://getsentry.com/welcome/) [免费]

+ [TrackJS](https://trackjs.com/) [付费]

### 5.42 性能工具

**报告：**

+ [bundlephobia.com](https://bundlephobia.com/)

+ [GTmetrix](https://gtmetrix.com/)

+ [sitespeed.io](https://www.sitespeed.io/)

+ [速度曲线](https://speedcurve.com/)[付费]

+ [Web页面测试](http://www.webpagetest.org/)

+ [Sonarwhal](https://sonarwhal.com/)

+ [webhint.io](https://webhint.io/)

+ [Datadog](https://www.datadoghq.com/)[付费]

+ [Lighthosue](https://developers.google.com/web/tools/lighthouse/)

**JS工具：**

+ [imagemin](https://github.com/imagemin/imagemin)

+ [ImageOptim-CLI](http://jamiemason.github.io/ImageOptim-CLI/)

**预算：**

+ [performancebudget.io](http://www.performancebudget.io/)

**参考文献和文件：**

+ [Jank Free](http://jankfree.org/)

+ [ES6相对于ES5的性能](https://kpdecker.github.io/six-speed/)

**清单：**

+ [前端清单](https://frontendchecklist.io/)

+ [2019前端性能清单 [PDF，Apple Pages，MS Word]](https://www.smashingmagazine.com/2019/01/front-end-performance-checklist-2019-pdf-pages/) [阅读]

### 5.43 查找工具的工具

+ [built with](http://builtwith.com/)

+ [frontendtools.com](http://frontendtools.com/)

+ [javascripting.com](http://www.javascripting.com/)

+ [js.coach](https://js.coach/)

+ [JSter](http://jster.net/)

+ [npms](https://npms.io/)

+ [stackshare.io](http://stackshare.io/)

+ [Unheap](http://www.unheap.com/)

+ [bestof.js.org](https://bestof.js.org/)

+ [librariers.io](https://libraries.io/)

### 5.44 文档生成工具

+ [docz](https://www.docz.site/)

+ [ESDoc](https://github.com/esdoc/esdoc)

+ [JSDoc](http://usejsdoc.org/)

+ [documentjs](https://documentjs.com/)

## 第6章 前端社区、简报、新闻网站和播客

**一般的前端简报、新闻和播客：**

+ [大型Web秀](http://5by5.tv/bigwebshow)

+ [开发贴士](https://umaar.com/dev-tips/)

+ [前端欢乐时光](http://frontendhappyhour.com/)

+ [前端前端](http://frontendfront.com/)

+ [前端焦点](http://frontendfocus.co/)

+ [Web平台新闻周刊](https://webplatform.news/)

+ [ShopTalk Show](http://shoptalkshow.com/)

+ [用户体验设计简报](http://uxdesignnewsletter.com/)

+ [Web开发阅读清单](https://wdrl.info/)

+ [Web平台播客](http://thewebplatform.libsyn.com/)

+ [Web工具周刊](http://webtoolsweekly.com/)

+ [新鲜酿造的前端](https://freshbrewed.co/frontend/)

+ [小型Foo周刊](https://ponyfoo.com/weekly)

+ [CSS技巧](https://css-tricks.com/newsletters/)

+ [语法](https://syntax.fm/)

**HTML/CSS简报：**

+ [无障碍周刊](http://a11yweekly.com/)

+ [CSS周刊](http://css-weekly.com/archives/)

+ [CSS布局新闻](http://csslayout.news/)

**JavaScript简报、新闻和播客：**

+ [超赞的JavaScript简报](https://js.libhunt.com/newsletter?f=es-top-d)

+ [Echo JS](http://www.echojs.com/)

+ [ECMAScript日志](https://ecmascript-daily.github.io/)

+ [ES最新消息](http://esnextnews.com/)

+ [闲聊JavaScript](https://devchat.tv/js-jabber/)

+ [JavaScript精华](http://javascriptkicks.com/)

+ [JavaScript周刊](http://javascriptweekly.com/)

+ [React状态](https://react.statuscode.com/)

+ [JS党](https://changelog.com/jsparty)

+ [JAMStack电台](https://www.heavybit.com/library/podcasts/jamstack-radio/)

+ [我的JavaScript故事](https://devchat.tv/my-javascript-story/)

**前端社区**

+ [http://fedsonslack.com/](http://fedsonslack.com/)

+ [前端](https://spectrum.chat/frontend/)系列
  
> 注：
>
> 1.需要更多简报、新闻网站和播客看看[超赞咨讯](https://github.com/vredniy/awesome-newsletters)。
>
> 2.通过搜索[https://www.meetup.com/](https://www.meetup.com/)查找本地前端开发社区  
>



