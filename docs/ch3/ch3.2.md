<!-- 3.2. - Learn Web Browsers -->
### 3.2 学习Web浏览器

> A web browser (commonly referred to as a browser) is a software application for retrieving, presenting, and traversing information resources on the World Wide Web. An information resource is identified by a Uniform Resource Identifier (URI/URL) and may be a web page, image, video or other piece of content. Hyperlinks present in resources enable users easily to navigate their browsers to related resources. Although browsers are primarily intended to use the World Wide Web, they can also be used to access information provided by web servers in private networks or files in file systems.
> 
> — [Wikipedia](https://en.wikipedia.org/wiki/Web_browser)

#### The [most commonly used browsers](https://netmarketshare.com/?options=%7B%22filter%22%3A%7B%22%24and%22%3A%5B%7B%22deviceType%22%3A%7B%22%24in%22%3A%5B%22Desktop%2Flaptop%22%2C%22Mobile%22%5D%7D%7D%5D%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22browser%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22browsersDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222018-01%22%2C%22dateEnd%22%3A%222018-12%22%2C%22segments%22%3A%22-1000%22%7D) (on desktop and mobile) are:

1.  [Chrome](http://www.google.com/chrome/) (engine: [Blink](https://en.wikipedia.org/wiki/Blink_%28layout_engine%29) \+ [V8](https://en.wikipedia.org/wiki/V8_%28JavaScript_engine%29))
2.  [Firefox](https://www.mozilla.org/en-US/firefox/new/) (engine: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) \+ [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))
3.  [Internet Explorer](http://windows.microsoft.com/en-us/internet-explorer/download-ie) (engine: [Trident](https://en.wikipedia.org/wiki/Trident_%28layout_engine%29) \+ [Chakra](https://en.wikipedia.org/wiki/Chakra_%28JScript_engine%29))
4.  [Safari](https://www.apple.com/safari/) (engine: [Webkit](https://en.wikipedia.org/wiki/WebKit) \+ [SquirrelFish](https://trac.webkit.org/wiki/SquirrelFish))

![](assets/images/statcounter.png "http://gs.statcounter.com/browser-market-share")

Image source: [http://gs.statcounter.com/browser-market-share](http://gs.statcounter.com/browser-market-share)

#### Evolution of Browsers & Web Technologies (i.e., APIs)

*   [evolutionoftheweb.com](http://www.evolutionoftheweb.com/) \[read\]
*   [Timeline of web browsers](https://en.wikipedia.org/wiki/Timeline_of_web_browsers) \[read\]

#### The Most Commonly Used [Headless Browser](http://www.asad.pw/HeadlessBrowsers/) Are:

*   [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md) (engine: [Blink](https://www.chromium.org/blink) \+ V8)
*   [SlimerJS](http://slimerjs.org/) (engine: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) \+ [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))

#### How Browsers Work

*   [20 Things I Learned About Browsers and the Web](http://www.20thingsilearned.com/en-US/foreword/1) \[read\]
*   [Fast CSS: How Browsers Lay Out Web Pages](http://dbaron.org/talks/2012-03-11-sxsw/master.xhtml) \[read\]
*   [How Browsers Work: Behind the scenes of modern web browsers](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) \[read\]
*   [Quantum Up Close: What is a browser engine?](https://hacks.mozilla.org/2017/05/quantum-up-close-what-is-a-browser-engine/)
*   [So How Does the Browser Actually Render a Website](https://www.youtube.com/watch?v=SmE4OwHztCc) \[watch\]
*   [What forces layout / reflow](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) \[read\]
*   [What Every Frontend Developer Should Know About Webpage Rendering](http://frontendbabel.info/articles/webpage-rendering-101/) \[read\]

#### Optimizing for Browsers:

*   [Browser Rendering Optimization](https://www.udacity.com/course/browser-rendering-optimization--ud860) \[watch\]
*   [Website Performance Optimization](https://www.udacity.com/course/website-performance-optimization--ud884) \[watch\]

#### Comparing Browsers

*   [Comparison of Web Browsers](https://en.wikipedia.org/wiki/Comparison_of_web_browsers) \[read\]

#### Browser Hacks

*   [browserhacks.com](http://browserhacks.com/) \[read\]

#### Developing for Browsers

In the past, front-end developers spent a lot of time making code work in several different browsers. This was once a bigger issue than it is today. Today, abstractions (e.g., React, Webpack, Post-CSS, Babel etc...) combined with modern browsers make browser development fairly easy. The new challenge is not which browser the user will use, but on which device they will run the browser.

#### Evergreen Browsers

The latest versions of most modern browsers are considered evergreen browsers. That is, in theory, they are supposed to automatically update themselves silently without prompting the user. This move towards self-updating browsers has been in reaction to the slow process of eliminating older browsers that do not auto-update.

#### Picking a Browser

As of today, most front-end developers use Chrome and "Chrome Dev Tools" to develop front-end code. However, the most used modern browsers all offer a flavor of developer tools. Picking one to use for development is a subjective choice. The more important issue is knowing which browsers, on which devices, you have to support and then testing appropriately.