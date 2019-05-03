<!-- 3.2. - Learn Web Browsers -->
### 3.2 学习Web浏览器

 <!-- A web browser (commonly referred to as a browser) is a software application for retrieving, presenting, and traversing information resources on the World Wide Web. An information resource is identified by a Uniform Resource Identifier (URI/URL) and may be a web page, image, video or other piece of content. Hyperlinks present in resources enable users easily to navigate their browsers to related resources. Although browsers are primarily intended to use the World Wide Web, they can also be used to access information provided by web servers in private networks or files in file systems.
 — [Wikipedia](https://en.wikipedia.org/wiki/Web_browser) -->

> *Web浏览器（通常称为浏览器）是用于在万维网上检索，呈现和遍历信息资源的软件应用程序。 信息资源由统一资源标识符（URI/URL）标识，并且可以是网页、图像、视频或其他内容。 资源中存在的超链接使用户能够轻松地将其浏览器导航到相关资源。 虽然浏览器主要用于万维网，但它们也可用于访问私有网络中的Web服务器或文件系统中的文件提供的信息。*
>
> *— [维基百科](https://en.wikipedia.org/wiki/Web_browser) & [中文地址](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%A1%B5%E6%B5%8F%E8%A7%88%E5%99%A8)*

<!-- The most commonly used browsers (on desktop and mobile) are: -->

#### （在桌面和移动设备上）[最常用的浏览器](https://netmarketshare.com/?options=%7B%22filter%22%3A%7B%22%24and%22%3A%5B%7B%22deviceType%22%3A%7B%22%24in%22%3A%5B%22Desktop%2Flaptop%22%2C%22Mobile%22%5D%7D%7D%5D%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22browser%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22browsersDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222018-01%22%2C%22dateEnd%22%3A%222018-12%22%2C%22segments%22%3A%22-1000%22%7D)是：

1. Chrome（引擎：Blink + V8）

2. Firefox（引擎：Gecko + SpiderMonkey）

3. Internet Explorer（引擎：Trident + Chakra）

4. Safari（引擎：Webkit + SquirrelFish）

![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/statcounter.png)

*图片来源: [http://gs.statcounter.com/browser-market-share](http://gs.statcounter.com/browser-market-share)*

<!-- Evolution of Browsers & Web Technologies (i.e., APIs) -->
#### 浏览器和Web技术（即API）的演变

*   [evolutionoftheweb.com](http://www.evolutionoftheweb.com/) \[阅读\]

*   [网络浏览器的时间表](https://en.wikipedia.org/wiki/Timeline_of_web_browsers) \[阅读\]

<!-- The Most Commonly Used Headless Browser Are: -->
#### 最常用的[无头浏览器](http://www.asad.pw/HeadlessBrowsers/)是：

*   [无头Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md) (引擎: [Blink](https://www.chromium.org/blink) \+ V8)

*   [SlimerJS](http://slimerjs.org/) (引擎: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) \+ [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))

<!-- How Browsers Work -->
#### 浏览器如何工作

*   [我学到的关于浏览器和网络的20件事](http://www.20thingsilearned.com/en-US/foreword/1) \[阅读\]

*   [CSS速成：浏览器如何布局网页](http://dbaron.org/talks/2012-03-11-sxsw/master.xhtml) \[阅读\]

*   [浏览器如何工作：现代网络浏览器的幕后](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) \[阅读\]

*   [聚焦Quantum：什么是浏览器引擎？](https://hacks.mozilla.org/2017/05/quantum-up-close-what-is-a-browser-engine/)

*   [那么浏览器如何渲染网站的真相是什么](https://www.youtube.com/watch?v=SmE4OwHztCc) \[观看\]

*   [是什么导致重排](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) \[阅读\]

*   [每个前端开发人员应该知道的关于网页渲染的内容](http://frontendbabel.info/articles/webpage-rendering-101/) \[阅读\]

<!-- Optimizing for Browsers: -->
#### 浏览器优化：

*   [浏览器渲染优化](https://www.udacity.com/course/browser-rendering-optimization--ud860) \[观看\]

*   [网站性能优化](https://www.udacity.com/course/website-performance-optimization--ud884) \[观看\]

<!-- Comparing Browsers -->
#### 浏览器比较

*   [Web浏览器的比较](https://en.wikipedia.org/wiki/Comparison_of_web_browsers) \[阅读\]

<!-- Browser Hacks -->
#### 浏览器Hack

*   [browserhacks.com](http://browserhacks.com/) \[阅读\]

<!-- Developing for Browsers -->
#### 浏览器开发

<!-- In the past, front-end developers spent a lot of time making code work in several different browsers. This was once a bigger issue than it is today. Today, abstractions (e.g., React, Webpack, Post-CSS, Babel etc...) combined with modern browsers make browser development fairly easy. The new challenge is not which browser the user will use, but on which device they will run the browser. -->
前端开发人员过去花了很多时间在几个不同的浏览器中开发代码。 这个问题曾经比今天更严重。 现在，抽象（例如，React，Webpack，Post-CSS，Babel等......）与现代浏览器相结合，使浏览器开发变得相当容易。 新的挑战不是用户将使用哪种浏览器，而是他们将在哪个设备上运行浏览器。

<!-- Evergreen Browsers -->
#### 安全浏览器

<!-- The latest versions of most modern browsers are considered evergreen browsers. That is, in theory, they are supposed to automatically update themselves silently without prompting the user. This move towards self-updating browsers has been in reaction to the slow process of eliminating older browsers that do not auto-update. -->
大多数现代浏览器的最新版本被认为是安全浏览器。 也就是说，理论上，它们应该在不提示用户的情况下自动更新。 这种向自我更新浏览器的转变一直是对不自动更新的旧浏览器缓慢替代的过程。

<!-- Picking a Browser -->
#### 浏览器的选择

<!-- As of today, most front-end developers use Chrome and "Chrome Dev Tools" to develop front-end code. However, the most used modern browsers all offer a flavor of developer tools. Picking one to use for development is a subjective choice. The more important issue is knowing which browsers, on which devices, you have to support and then testing appropriately. -->
截至今天，大多数前端开发人员使用Chrome和“Chrome Dev Tools”来开发前端代码。 但是，最常用的现代浏览器都提供了一种开发人员工具。 选择哪一个作为开发工具是主观的。 更重要的问题是知道有哪些浏览器，你必须支持哪些设备，然后进行适当的测试。
