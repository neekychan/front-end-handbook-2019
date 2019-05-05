<!-- # Chapter 1. What Is a Front-end Developer? -->
# 第一章 前端开发者是什么？
<!-- This chapter provides a baseline explanation for front-end development and the front-end developer discipline. -->
本章节阐述了前端开发的基本解释和前端开发者的规则。

<!-- Front-end web development, also known as client-side development is the practice of producing HTML, CSS and JavaScript for a website or Web Application so that a user can see and interact with them directly. The challenge associated with front end development is that the tools and techniques used to create the front end of a website change constantly and so the developer needs to constantly be aware of how the field is developing. -->
<!-- The objective of designing a site is to ensure that when the users open up the site they see the information in a format that is easy to read and relevant. This is further complicated by the fact that users now use a large variety of devices with varying screen sizes and resolutions thus forcing the designer to take into consideration these aspects when designing the site. They need to ensure that their site comes up correctly in different browsers (cross-browser), different operating systems (cross-platform) and different devices (cross-device), which requires careful planning on the side of the developer. -->

> *前端web开发（也称作客户端开发）是网页和网页应用的生产HTML、CSS和JavaScript实践，以使用户能看见并与之直接交互。与前端开发关联的挑战是用于创建前端web的工具和技术不停地改变，并且开发者需要持续了解该领域是如何发展的。*
>
> *设计一个网站的目的，就是确保当用户打开网站时，看到的信息被格式化成易于阅读且相关联的。实际上会更加复杂，现在用户使用大量不同的设备、不同的屏幕尺寸和分辨率，以至使设计师在设计网页的时候不得不考虑这些问题，他们必须确保页面能够在不同浏览器（夸浏览器）、不同的操作系统和不同的设备中正确展示，这就需要开发者有细心的规划。*
> 
> *- [维基百科](https://en.wikipedia.org/wiki/Front-end_web_development)*


![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/what-is-front-end-dev.png)

*图片来源：[https://www.upwork.com/hiring/development/front-end-developer/](https://www.upwork.com/hiring/development/front-end-developer/)*

<!-- A Front-end Developer... -->
### 前端开发者...
<!-- A front-end developer architects and develops websites and web applications using web technologies (i.e., HTML, CSS, and JavaScript), which typically runs on the Open Web Platform or acts as compilation input for non-web platform environments (i.e., React Native). -->
前端开发者使用web技术（[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)、[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)、[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)）来设计和开发网站和web应用，这些技术通常运行在[Open Web Platform](https://en.wikipedia.org/wiki/Open_Web_Platform)或作为非网页平台环境的编译入口。(如[React Native](https://facebook.github.io/react-native/))

<!-- A person enters into the field of front-end development by learning to build a website or web application which relies on HTML, CSS, and JavaScript and commonly runs in a web browser but can also run in a headless browser, WebView, or as compilation input for a native runtime environment. These four run times scenarios are explained below. -->

通过学习构建依赖于HTML, CSS, and JavaScript的网站或网页应用来进入前端开发领域。通常运行在[web浏览器](https://en.wikipedia.org/wiki/Web_browser)中，但也能运行于[无头浏览器](https://en.wikipedia.org/wiki/Headless_browser)、[WebView](http://developer.telerik.com/featured/what-is-a-webview/)或者原生运行环境中。下面将介绍四种运行时方案：

<!-- Web Browsers (most common) -->
### Web浏览器（最常见的）

<!-- A web browser is software used to retrieve, present, and traverse information on the WWW. Typically, browsers run on a desktop or laptop computer, tablet, or phone, but as of late a browser can be found on just about anything (i.e, on a fridge, in cars, etc.). -->

Web浏览器是一款用于检索、展示、遍历[WWW](https://en.wikipedia.org/wiki/World_Wide_Web)信息的软件。通常，浏览器运行在桌面以及手提电脑、平板电脑、手机，但最近浏览器几乎能运行在任何设备上。（冰箱、汽车等等）

<!-- The most common web browsers are (shown in order of most used first): -->

### 最常见的Web浏览器（按照最[常用](https://en.wikipedia.org/wiki/Usage_share_of_web_browsers#Summary_tables)的顺序排列）：

- [Chrome](http://www.google.com/chrome/)
- [Safari](http://www.apple.com/safari/)
- [Internet Explorer](https://en.wikipedia.org/wiki/Internet_Explorer) (备注: 不含[Edge](http://dev.modern.ie/), 特指 IE 9 至 IE 11)
- [Firefox](https://www.mozilla.org/firefox/)
- [Edge](https://www.microsoft.com/en-us/windows/microsoft-edge)

### 无头浏览器

<!-- Headless browsers are a web browser without a graphical user interface that can be controlled from a command line interface programmatically for the purpose of web page automation (e.g., functional testing, scraping, unit testing, etc.). Think of headless browsers as a browser that you can run programmatically from the command line that can retrieve and traverse web page code. -->

Headless浏览器指**不包含**图形界面的浏览器，通过命令行界面以编码的方式进行控制以达到网页自动化的目的（功能测试、网页爬取、单元测试）。

<!-- The most common headless browsers are: -->

### 最常见的无头浏览器：

- [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)
- [Zombie](https://github.com/assaf/zombie)
- [slimerjs](http://slimerjs.org/)
- [puppeteer](https://github.com/GoogleChrome/puppeteer)

### Webviews

<!-- Webviews are used by a native OS, in a native application, to run web pages. Think of a webview like an iframe or a single tab from a web browser that is embedded in a native application running on a device (e.g., iOS, android, windows). -->

[Webviews](http://developer.telerik.com/featured/what-is-a-webview/)用在原生操作系统上，在原生应用中运行网页。你可以将[webviews](http://developer.telerik.com/featured/what-is-a-webview/)想象成是网页浏览器的一个iframe或一个单标签，它被嵌入在设备里所运行的原生应用中。(如[iOS](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIWebView_Class/)、[android](http://developer.android.com/reference/android/webkit/WebView.html)、[windows](https://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.controls.webview.aspx))。

<!-- The most common solutions for webview development are: -->
### 最常见的[webview](http://developer.telerik.com/featured/what-is-a-webview/)开发解决方案：

- [Cordova](https://cordova.apache.org/) (手机/平板的原生应用)
- [NW.js](https://github.com/nwjs/nw.js) (桌面应用)
- [Electron](http://electron.atom.io/) (桌面应用)

### Native from Web Tech

<!-- Eventually, what is learned from web browser development can be used by front-end developers to craft code for environments that are not fueled by a browser engine (i.e. web platform). As of late, development environments are being dreamed up that use web technologies (e.g., CSS and JavaScript), without web engines, to create native applications. -->

最后，前端开发者可以从网页浏览器开发中所学的知识，不受浏览器引擎的限制来编写代码。最近，开发环境正被设想成可以利用网页技术（CSS、JavaScript）且不使用网页引擎来构建原生应用。

<!-- Some examples of these environments are: -->

### 这些环境部分的列子：

- [Flutter](Flutter)
- [React Native](https://facebook.github.io/react-native/)
- [NativeScript](https://www.nativescript.org/)

<!-- Notes: -->
<!-- Make sure you are clear what exactly is meant by the "web platform". Read the, "Open Web Platform" Wikipedia page. Explore the many technologies that make up the web platform. -->

> 备注：
>
> 1、确保你清晰理解“web platform”的含义。阅读“[Open Web Platform](https://en.wikipedia.org/wiki/Open_Web_Platform)”的维基百科页面。探索web platform相关的[众多技术](https://platform.html5.org/)。