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

