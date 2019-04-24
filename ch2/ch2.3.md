<!-- 2.3 - Baseline Web Technologies Employed by Front-End Developers -->
# 2.3 前端开发者所需要的基础技术
![](https://frontendmasters.com/books/front-end-handbook/2019/assets/images/web-tech-employed.jpg)
<!-- The following core web technologies are employed by front-end developers (consider learning them in this order): -->
下面是被前端开发者所使用的核心网页技术（可考虑按顺序学习它们）：

<!-- Hyper Text Markup Language (aka HTML) -->
<!-- Cascading Style Sheets (aka CSS) -->
<!-- Uniform Resource Locators (aka URLs) -->
<!-- Hypertext Transfer Protocol (aka HTTP) -->
<!-- JavaScript Programming Language (aka ECMAScript 262) -->
<!-- JavaScript Object Notation (aka JSON) -->
<!-- Document Object Model (aka DOM) -->
<!-- Web APIs (aka HTML5 and friends or Browser APIs) -->
<!-- Web Content Accessibility Guidelines (aka WCAG) & Accessible Rich Internet Applications (aka ARIA) -->
<!-- For a comprehensive list of all web related specifications have a look at platform.html5.org or MDN Web APIs. -->

1. 超文本链接（aka HTML）
2. 层叠样式表（aka CSS）
3. 同意资源定位 （aka URLs）
4. 超文本传输协议（aka HTTP）
5. JavaScript编程语言（aka ECMAScript 262）
6. JavaScript对象简谱（aka JSON）
7. 文档对象模型（aka JSON）
8. Web APIs（aka HTML5 和 friends 或 浏览器APIs ）
9. 网页内容无障碍指引（aka WCAG）& 无障碍的富网络应用程序（aka ARIA）

一个所有网页相关规范的综合性列表，清参阅[platform.html5.org](https://platform.html5.org/)或【MDN Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)。

<!-- The nine technologies just mentioned are defined below along with a link to the relevant documentation and specification for each technology. -->

下面定义了九个被提到技术，并提供了每一种技术相关的文档和规范的链接。

<!-- Hyper Text Markup Language (aka HTML) -->
### 超文本标记链接（aka HTML）
<!-- HyperText Markup Language, commonly referred to as HTML, is the standard markup language used to create web pages. Web browsers can read HTML files and render them into visible or audible web pages. HTML describes the structure of a website semantically along with cues for presentation, making it a markup language, rather than a programming language. -->
> 超文本标记链接，通常称为HTML，是一种用于创建网页的标准标记语言。网页浏览器能读取HTML文件并将其渲染成看得见听得到的网页。HTML语义地描述了一种网站结构以及用于展示的提示，使其成为一种标记语言而非一种编程语言。— [Wikipedia](https://en.wikipedia.org/wiki/HTML)

Most relevant specifications / documentation:
大部分相关的规范/文档：

<!-- All W3C HTML Spec
The elements of HTML from the Living Standard
Global attributes
HTML 5.2 from W3C
HTML 5.3 from W3C
HTML attribute reference
HTML element reference
The HTML Syntax from the Living Standard -->
- [W3C HTML规范大全](http://www.w3.org/standards/techs/html#w3c_all)
- 标准[HTML元素](https://html.spec.whatwg.org/multipage)
- [全局属性](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
- [W3C的HTML5.2标准](https://www.w3.org/TR/2017/REC-html52-20171214/)
- [W3C的HTML5.3标准](http://w3c.github.io/html/)
- [HTML属性参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
- [HTML元素参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- 标准[HTML语法](https://html.spec.whatwg.org/multipage/syntax.html#syntax)

<!-- Cascading Style Sheets (aka CSS) -->
### 层叠样式表（aka CSS）
<!-- Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document written in a markup language. Although most often used to change the style of web pages and user interfaces written in HTML and XHTML, the language can be applied to any kind of XML document, including plain XML, SVG and XUL. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications. -->
> 层叠样式表（CSS）一种用样式表语言,用于描述用标记语言编写的文档的外观和格式。尽管经常用于改变用HTML和XHTML所编写的网页和用户界面的样式，该语言能应用于任何类型的XML文档，包括纯XML，SVG和XUL。由于HTLM和JavaScript，CSS是基础技术，被大部分网站用于创建外表迷人的网页，网页应用程序的用户界面和许多移动应用的用户界面。— [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

<!-- Most relevant specifications / documentation: -->
大部分相关的规范/文档：

<!-- All W3C CSS Specifications
Cascading Style Sheets Level 2 Revision 2 (CSS 2.2) Specification
CSS reference
Selectors Level 3 -->

- [W3C CSS规范大全](http://www.w3.org/Style/CSS/current-work)
- [层叠样式表 2.2版本（CSS 2.2）规范](https://www.w3.org/TR/CSS22/)
- [CSS参考](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

<!-- Hypertext Transfer Protocol (aka HTTP) -->
### 超文本传输协议（aka HTTP）
<!-- The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web. -->

> 超文本传输协议（HTTP）一种用于分布式、协作的，超媒体信息系统的应用协议。HTTP是WWW的数据通讯的基础。— [Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

<!-- Most relevant specifications: -->
大部分相关的规范：

<!-- Hypertext Transfer Protocol -- HTTP/1.1 -->
<!-- HTTP/2 -->
- [超文本传输协议 -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)
- [HTTP/2](http://httpwg.org/specs/rfc7540.html)

<!-- Uniform Resource Locators (aka URL) -->
### 统一资源定位（aka URL）
<!-- A uniform resource locator (URL) (also called a web address) is a reference to a resource that specifies the location of the resource on a computer network and a mechanism for retrieving it. A URL is a specific type of uniform resource identifier (URI), although many people use the two terms interchangeably. A URL implies the means to access an indicated resource, which is not true of every URI. URLs occur most commonly to reference web pages (http), but are also used for file transfer (ftp), email (mailto), database access (JDBC), and many other applications. -->

<!-- — Wikipedia -->
> 统一资源定位（URL）（也称为web地址）是一种对资源的引用，指定了资源在计算机网络的位置和检索的机制。URL是一种明确的统一资源标志符类型（URI），尽管许多人将它混在一起使用。URL表示可访问指定资源的方法，但并非每个URI皆如此。URL常见于引用网页（http）,但也用于文件传输协议(ftp)，邮件（mailto），访问数据库（JDBC）和许多其他应用。- [Wikipedia](https://en.wikipedia.org/wiki/Uniform_Resource_Locator)

<!-- Most relevant specifications: -->
大部分相关的规范

<!-- Uniform Resource Locators (URL)
URL Living Standard -->
- [统一资源定位器（URL）](http://www.w3.org/Addressing/URL/url-spec.txt)
- [URL标准](https://url.spec.whatwg.org/)

<!-- Document Object Model (aka DOM) -->
### 文档对象模型（aka DOM）

<!-- The Document Object Model (DOM) is a cross-platform and language-independent convention for representing and interacting with objects in HTML, XHTML, and XML documents. The nodes of every document are organized in a tree structure, called the DOM tree. Objects in the DOM tree may be addressed and manipulated by using methods on the objects. The public interface of a DOM is specified in its application programming interface (API). -->

<!-- — Wikipedia -->

> 文档对象模型是一种在跨平台和语言无关性的约定，用于表示HTML，XHTML和XML文档中的对象并与之交互。每个文档中的节点都在一个树状结构树种被组织起来，被叫做DOM树。可用对象中的方法对DOM树中的对象进行寻址和操作。DOM的公有接口在其应用程序编程接口中被指定。

<!-- Most relevant specifications / documentation: -->
大部分相关的规范/文档：

<!-- DOM Living Standard
W3C DOM4
UI Events -->

- [DOM标注](https://dom.spec.whatwg.org/)
- [W3C DOM4](https://www.w3.org/TR/domcore/)
- [UI事件](https://www.w3.org/TR/uievents/)

<!-- JavaScript Programming Language (aka ECMAScript 262) -->
### JavaScript编程语言（aka ECMAScript 262）

<!-- JavaScript is a high level, dynamic, untyped, and interpreted programming language. It has been standardized in the ECMAScript language specification. Alongside HTML and CSS, it is one of the three essential technologies of World Wide Web content production; the majority of websites employ it and it is supported by all modern web browsers without plug-ins. JavaScript is prototype-based with first-class functions, making it a multi-paradigm language, supporting object-oriented, imperative, and functional programming styles. It has an API for working with text, arrays, dates and regular expressions, but does not include any I/O, such as networking, storage or graphics facilities, relying for these upon the host environment in which it is embedded. -->

<!-- — Wikipedia -->

> JavaScript是一种高级，动态，无类型和解析型编程语言。其已在ECMAScript语言规范中被标准化。和HTML、CSS一样，它是WWW内容生产中三大关键的技术之一。大多数网站中都采用这种技术，并且已被现代浏览器所支持，出了plug-ins外。JavaScript是一种基于原型和一等函数构成的多维语言，支持面向对象，多范式和函数式编程风格。- [Wikipedia](https://en.wikipedia.org/wiki/JavaScript)

<!-- Most relevant specifications / documentation: -->
大部分相关的规范/文档：

<!-- ECMAScript® 2018 Language Specification
All ECMAScript Language Specifications -->
- [ECMAScript® 2018 语言规范](http://ecma-international.org/ecma-262/9.0/index.html#Title)
- [ECMAScript语言规范大全](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources)

<!-- Web APIs (aka HTML5 and friends) -->
### Web APIs (aka HTML5 and friends)

<!-- When writing code for the Web using JavaScript, there are a great many APIs available. Below is a list of all the interfaces (that is, types of objects) that you may be able to use while developing your Web app or site. -->

<!-- — Mozilla -->
> 当用JavaScript编写网页代码的时候，会有非常多可用的APIs。下面列出了当你在开发你的网页应用和站点时，你有可能使用到的接口（即对象的类型） - [Mozilla](https://developer.mozilla.org/en-US/docs/Web/API)

<!-- Most relevant documentation: -->
大部分相关的文档：

<!-- Web API Interfaces -->
- [Web API接口](https://developer.mozilla.org/en-US/docs/Web/API)

<!-- JavaScript Object Notation (aka JSON) -->
### JavaScript对象简谱（aka JSON）

<!-- It is the primary data format used for asynchronous browser/server communication (AJAJ), largely replacing XML (used by AJAX). Although originally derived from the JavaScript scripting language, JSON is a language-independent data format. Code for parsing and generating JSON data is readily available in many programming languages. The JSON format was originally specified by Douglas Crockford. It is currently described by two competing standards, RFC 7159 and ECMA-404. The ECMA standard is minimal, describing only the allowed grammar syntax, whereas the RFC also provides some semantic and security considerations. The official Internet media type for JSON is application/json. The JSON filename extension is .json.

— Wikipedia -->

> 这是一种用于异步浏览器/服务器通讯的主要数据格式，已大规模替代XML（被AJAX使用）。尽管源自于JavaScript语言，JSON是一种语言无关性的数据格式。在许多编程语言中能容易使用用于解析和生成JSON数据的代码。JSON格式最初由Douglas Crockford所制定。当前被两种相互竞争的标准所描述，RFC 7159 and ECMA-404。ECMA标准在最小限度描述了所允许的语法，然而RFC也提供了一些语义和安全的考虑。JSON的正式网络媒体类型是application/json。JSON的文件扩展名是.json。

<!-- Most relevant specifications: -->
大部分相关的规范：

<!-- Introducing JSON
JSON API
The JSON Data Interchange Format -->

- [JSON简介](http://json.org/)
- [JSON API](http://jsonapi.org/)
- [JSON数据交换格式](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

<!-- Web Content Accessibility Guidelines (aka WCAG) & Accessible Rich Internet Applications (aka ARIA) -->

### 网页内容无障碍直男（aka WCAG）& 无障碍的富网络应用程序（aka ARIA）

<!-- Accessibility refers to the design of products, devices, services, or environments for people with disabilities. The concept of accessible design ensures both “direct access” (i.e., unassisted) and "indirect access" meaning compatibility with a person's assistive technology (for example, computer screen readers).

— Wikipedia -->

> 无障碍性是指为残疾人士设计产品，设备，服务或环境。无障碍设计的概念既确保了“直接使用（例如：无辅助）”和“间接使用”，意味着与人的辅助技术的兼容性。（例如，计算机屏幕朗读者）- [Wikipedia](https://en.wikipedia.org/wiki/JSON)

<!-- Web Accessibility Initiative (WAI)
Web Content Accessibility Guidelines (WCAG) Current Status -->
- [网页易读性倡议（WAI）](https://www.w3.org/WAI/standards-guidelines/)
- [网页内容无障碍指南（WCAG）当前状态](http://www.w3.org/standards/techs/wcag#w3c_all)
