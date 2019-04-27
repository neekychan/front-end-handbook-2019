# 第0章 回顾2018年并展望未来
<!-- React had several notable releases this past year that included, lifecycle methods, context API, suspense, and React hooks. -->
- 在过去一年，React中有不少瞩目的发布，包括[lifecycle函数](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#component-lifecycle-changes)、[context API](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#official-context-api)，[suspense](https://reactjs.org/docs/react-api.html#reactsuspense)、[React hooks](https://reactjs.org/docs/hooks-intro.html)。
<!-- Microsoft buys Github. Yeah, that happened. -->
- [微软收购Github](https://news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/)。没错，这是真的。
<!-- Fonts created by CSS became a thing. -->
- 用CSS制作[Fonts](https://yusugomori.com/projects/css-sans/)。
<!-- What I used to call front-end driven apps, gets labeled "serverless". Unfortunately, this term is overloaded. However, the term JAMstack does seem to be resonating with developers. -->
- 我以往称作前端驱动的APP，被称作[“无服务”](https://thepowerofserverless.info/)。不幸的是，这言过于实了。然而，[JAMstack](https://jamstack.org/)看起来引起了开发者的[回响](https://jamstackconf.com/nyc/)。
<!-- Google offered some neat tools this year to help make webpages load faster, i.e. squoosh and quicklink. -->
Google提供了一些好用的工具去帮助网页加载得更快，也就是[squoosh](https://github.com/GoogleChromeLabs/squoosh/)和[quicklink](https://github.com/GoogleChromeLabs/quicklink)
<!-- Vue gets more Github stars than React this year. But React remains dominate in terms of use. -->
- 这里年里，[Vue](https://risingstars.js.org/2018/en/#section-framework)比React获得了更多的[Github stars](https://hasvuepassedreactyet.surge.sh/)。但React在[使用](https://www.npmjs.com/browse/depended)[方面](https://2018.stateofjs.com/front-end-frameworks/overview/)仍占主导地位。
<!-- A solution similar to React, without a virtual DOM or JSX, is introduced RE:DOM. -->
- [RE:DOM](https://github.com/redom/redom)引入了一个类似于React的解决方案，不包含虚拟DOM和JSX。
<!-- Alternatives to NW.js and Electron show up, DeskGap and Neutralino.js. -->
- [DeskGap](https://deskgap.com/)和[Neutralino.js](https://neutralino.js.org/)作为NW.js和Electron的替代品出现。
<!-- In 2017 the great divide between a front-end HTML & CSS developer v.s. front-end application developer is realized/verbalized. In 2018 that divide has grown wider and deeper and more people start to feel the divide. -->
- 在2017年， [前端HTML&CSS开发者](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06)与[前端应用开发者](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06)之间产生了[巨大的](https://medium.com/@jerrylowm/the-death-of-front-end-developers-803a95e0f411)分水岭。在2018年，分水岭越发[宽广和加深](https://css-tricks.com/the-great-divide/)，且越来越多[人](https://rachelandrew.co.uk/archives/2019/01/30/html-css-and-our-vanishing-industry-entry-points/)开始[感受](https://hackernoon.com/the-backendification-of-frontend-development-62f218a773d4)到这种[情形](https://justmarkup.com/log/2018/11/just-markup/)。
<!-- This year, like most recent years, was stock full of app/framework solutions trying to contend with the mainstream JavaScript app tools (i.e. React, Angular, and Vue etc...) Let me list them for you. Radi.js, DisplayJS, Stimulus, Omi, Quasar. -->
- 这一年，与最近几年一样，有成堆的应用/框架的解决方案尝试角逐成为主流的JavaScript App工具（例如[React、Angular、Vue等等](https://stateofjs.com/2017/front-end/results)）让我为你列举一下，[Radi.js](https://radi.js.org/), [DisplayJS](https://display.js.org/), [Stimulus](https://stimulusjs.org/), [Omi](https://github.com/Tencent/omi), [Quasar](https://quasar-framework.org/).
<!-- JavaScript frameworks start offering their own languages that compile to JavaScript (e.g. Mint). -->
- JavaScript框架开始提供其语言使其编译成JavaScript（例如[Mint](https://www.mint-lang.com/)）。
<!-- CodeSandbox evolves to become the dominant solution for online code sharing. -->
- [CodeSandbox](https://codesandbox.io/)已经演变成在线代码分享的主流解决方案。
<!-- CSS Grid and CSS Flexbox are fully supported in modern browsers and get taken for some serious rides. But many are left wondering when to use which one and how. -->
- [CSS Grid](https://cssgridgarden.com/)和[CSS Flexbox](https://flexboxfroggy.com/)已经完全被现在浏览器所支持，并且得到了一些重大的进展。但许多人仍然对[使用哪一种和怎么使用](https://css-irl.info/to-grid-or-to-flex/)存在[困惑](https://www.youtube.com/watch?v=hs3piaN4b5I)。
<!-- Many realize the long terms costs of bolted on type systems (e.g. TypeScript and Flow). Some concluded bolted on systems are not unlike bolted on module systems (i.e. AMD/Require.js) and come with more issues than solutions. Minimally, many developers realize that if types are needed in large code bases, that bolted on systems are not ideal in comparison to languages that have them baked in (e.g. Reason, Purescript, Elm). -->
- 许多人已经意识到长期使用类型体系的代价。一些人推断说，基于类型体系与基于模块体系（如AMD、Require.js）并不一样，前者带来的问题远比其[解决方案](https://medium.com/javascript-scene/the-typescript-tax-132ff4cb175b)要更多。最低限度，许多开发者意识到如果类型体系是大型代码库所需要的，与([Reason](https://reasonml.github.io/)、[Purescript](http://www.purescript.org/)、[Elm](https://elm-lang.org/))的语言相比，束缚在类型体系并不明智。
<!-- CSS Variables gain browser support among modern web browsers -->
- [CSS变量](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)在现代Web浏览器当中得到了[支持](https://caniuse.com/#feat=css-variables)。
<!-- The flavors of CSS in JS exploded and some question the practice. -->
- [CSS in JS](http://michelebertoli.github.io/css-in-js/)方式流行，[有些](http://bradfrost.com/blog/link/whats-wrong-with-css-in-js/)人却对此产生质疑。
<!-- ES modules are now usable in modern browsers and dynamic imports are close behind. We are even seeing a shift in tooling around this fact. -->
- [ES modules](https://caniuse.com/#search=modules) 在现代浏览器中已经可以用，[dynamic imports](https://developers.google.com/web/updates/2017/11/dynamic-import#dynamic)也即将支持。我们甚至看见一些[工具](https://www.pikapkg.com/blog/introducing-pika-pack/)因此发生变化。
<!-- Many realize that end to end testing is the starting point of doing tests correctly in large part due to Cypress (i.e. Cypress first, then Jest). -->
- 基于[Cypress](https://www.cypress.io/how-it-works/)，许多人发现端到端的测试，在很大程度上是正确的开始。(i.e. 先是Cypress first, 后是 [Jest](https://jestjs.io/))
<!-- While Webpack was heavily used again this year, many developers found Parcel to be easier to get up and running. -->
- 那年，当[Webpack](https://webpack.js.org/)再一次被大量使用，许多开发者发现[Parcel](https://github.com/parcel-bundler/parcel)变得更容易启动和运行。
<!-- One of the most important questions asked this year was, what is the cost of JavaScript. -->
- 那年提出的最重要的一个问题是，[JavaScript的成本](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)是多少？
<!-- Babel 7 was released this year. That's a big deal because the last major release was almost three years ago. -->
- [Babel 7发布](https://babeljs.io/blog/2018/08/27/7.0.0)，这可是一件大事，因为对上一次大版本发布已经在三年前了。
<!-- The reality of too much JavaScript change too fast is realized and people start talking about what you need to know before you can even learn something like React. The fight is real. -->
- JavaScript变化太快的事实已经被意识到，人们开始[谈论](https://www.robinwieruch.de/javascript-fundamentals-react-requirements/)在你学习诸如React的东西前需要知道什么。斗争是真实的。
<!-- Most developers found GraphQL, via Apollo, and see it as the next evolution for data API's. -->
- 大部分开发者通过[Apollo](https://www.apollographql.com/)[发现](https://blog.bitsrc.io/why-does-everyone-love-graphql-17de7f99f05a)了GraphQL，把它看作是data API's的下一场革命。
<!-- Gulp and friends definitely took a back seat to NPM/Yarn run. But this did not stop Microsoft from getting in the game with Just. -->
- Gulp及其相关明显地落后于[NPM/Yarn](https://css-tricks.com/why-npm-scripts/)，但这并未能阻止微软用[Just](https://github.com/Microsoft/just)参与这场竞争。
<!-- This year, one can not only lint/hint HTML, CSS, and JavaScript they can lint/hint the web itself. -->
- 这一年，不但可以lint/hint HTML、CSS和JavaScript，还可以对web自身[lint/hint](https://webhint.io/)。
<!-- The 2018 Front-End Tooling survey is worth reading if only to realize just how much jQuery is still used. -->
- [《2018年前端工具调查报告》](https://ashleynolan.co.uk/blog/frontend-tooling-survey-2018-results)很值得一读，如果你仅仅想了解有多少jQuery仍然在被使用。
<!-- It can't be denied TypeScript gained a lot of users this year. -->
- [无可否认](https://2018.stateofjs.com/javascript-flavors/typescript/)，[TypeScript](https://www.typescriptlang.org/)今年收获了大量使用者。
<!-- VScode, dominates as the code editor of choice. -->
- [VScode](https://code.visualstudio.com/)成为了代码编辑器的[首选](https://triplebyte.com/blog/editor-report-the-rise-of-visual-studio-code)。