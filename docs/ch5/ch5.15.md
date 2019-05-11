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

* [RealWorld示例应用程序](https://github.com/gothinkster/realworld) \[code\]

* [前端准则草案](https://github.com/bradfrost/frontend-guidelines-questionnaire)

* [前端准则](https://github.com/bendc/frontend-guidelines)

**性能：**

* [js-framework-benchmark](https://github.com/krausest/js-framework-benchmark)

* [前端性能检查列表2019\[PDF、Apple Pages、MS Word\]](https://www.smashingmagazine.com/2019/01/front-end-performance-checklist-2019-pdf-pages/) \[阅读\]

如果你是前端JavaScript应用程序开发新手，我建议从[Vue.js](http://vuejs.org/)开始。然后我会把[React](http://facebook.github.io/react/)应用到工作中。然后我也会学习 [Angular 2+](https://angular.io/), [Ember](http://emberjs.com/), or [Aurelia](http://aurelia.io/)。

如果你正在构建一个与数据交互最少的简单网站(主要是静态内容的网站)，那么应该避免使用前端框架。使用像[Gulp and jQuery](https://github.com/vigetlabs/blendid)这样的任务运行器可以完成很多工作，同时避免了不必要的学习和使用应用程序框架工具的复杂性。

想要比“React”精巧的框架，考虑一下“[Preact](https://preactjs.com/)”。
Preact试图以用尽可能少的代码来重新创建React(或类似的库，如Mithril)的核心价值主张，并优先为ES2015提供支持。目前该库大约为3kb(minified和gzipped)。

