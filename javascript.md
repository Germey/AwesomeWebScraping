# JavaScript 网页抓取

此列表包含与 Web 抓取和数据处理相关的 JavaScript 库。该列表的内容主要是在可以在 Node.js 中运行的库（非网络浏览器）。

- [JavaScript 网页抓取](#javascript-web-scraping)
  - [网络](#network)
  - [网页抓取框架](#web-scraping-frameworks)
  - [HTML/XML 解析](#htmlxml-解析)
  - [文本处理](#text-processing)
  - [特定格式处理](#specific-formats-processing)
  - [自然语言处理](#natural-language-processing)
  - [浏览器自动化和仿真](#browser-automation-and-emulation)
  - [多处理](#multiprocessing)
  - [队列](#queue)
  - [电子邮件](#email)
  - [URL 和网络地址操作](#url-and-network-address-manipulation)
  - [网页内容提取](#web-content-extracting)
  - [异步](#异步)
  - [WebSocket](#websocket)
  - [DNS 解析](#dns-resolving)
  - [计算机视觉](#computer-vision)
  - [代理服务器](#proxy-server)
  - [其他 JavaScript 列表](#other-javascript-lists)
  - [数据结构](#data-structure)

## 网络请求工具

- [request](https://github.com/request/request) - 简化的 HTTP 请求客户端。
- [socks5-http-client](https://github.com/mattcg/socks5-http-client) - Node.js 的 JavaScript 中的 SOCKS v5 HTTP 客户端实现
- [rest](https://github.com/cujojs/rest) - 用于 JavaScript 的 RESTful HTTP 客户端
- [wreck](https://github.com/hapijs/wreck) - HTTP 客户端实用程序
- [got](https://github.com/sindresorhus/got) - 简化的 HTTP 请求
- [node-fetch](https://github.com/bitinn/node-fetch) - 将 window.fetch 引入 Node.js 的轻量级模块
- [bent](https://github.com/mikeal/bent) - 带有 async/await 的 Node.js 功能 HTTP 客户端
- [axios](https://github.com/axios/axios) - 用于浏览器和 node.js 的基于 Promise 的 HTTP 客户端
- [superagent](https://github.com/visionmedia/superagent) - 适用于 Node.js 和浏览器的 Ajax（JS HTTP 客户端）
- [urllib](https://github.com/node-modules/urllib) - 在复杂的世界中请求 HTTP(s) URL
- [needle](https://github.com/tomas/needle) - Node.js 的灵活、可流式传输的 HTTP 客户端。具有代理、iconv、cookie、deflate 和多部分支持

## Web 抓取框架

- [webparsy](https://github.com/joseconstela/webparsy) - 用于使用 Puppeteer 和 YAML 抓取网站的 NodeJS 库和 cli
- [node-crawler](https://github.com/sylvinus/node-crawler) - 用于 NodeJS + 服务器端 jQuery 的 Web Crawler/Spider
- [node-simplecrawler](https://github.com/cgiffard/node-simplecrawler) - 灵活的节点事件驱动爬虫
- [Apify SDK](https://github.com/apifytech/apify-js) - 适用于 JavaScript 的可扩展网络爬取和抓取库。支持使用无头 Chrome 和 Puppeteer 开发数据提取和 Web 自动化作业（不仅如此）。
- [Ayakashi](https://github.com/ayakashi-io/ayakashi) - 下一代网页抓取框架。具有创建可靠且可维护的刮削和自动化系统的所有必要工具。
- [pjscrape](https://github.com/nrabinowitz/pjscrape) - 一个用 Javascript 编写的网络抓取框架，使用 PhantomJS 和 jQuery

## HTML/XML 解析

- 通用
  - [parse5](https://github.com/inikulin/parse5) - WHATWG HTML5 规范兼容，快速且可用于 Node 和 io.js 的生产 HTML 解析/序列化工具集
  - [htmlparser2](https://github.com/fb55/htmlparser2) - 原谅 html 和 xml 解析器
  - [sax-js](https://github.com/isaacs/sax-js) - 用于 JS 的 sax 样式解析器
  - [cheerio](https://github.com/cheeriojs/cheerio) - 专为服务器设计的核心 jQuery 的快速、灵活和精简的实现
- 防护
  - [js-xss](https://github.com/leizongmin/js-xss) - 使用白名单指定的配置清理不受信任的 HTML（以防止 XSS）。
  - [surgeon](https://github.com/gajus/surgeon) - 声明式 DOM 提取表达式评估器

## 文本处理

_用于解析和操作纯文本的库。_

- 通用
  - [string.js](https://github.com/jprichardson/string.js) - 额外的 JavaScript 字符串方法。
  - [accounting.js](https://github.com/openexchangerates/accounting.js) - 用于数字、货币和货币格式化的轻量级 JavaScript 库 - 完全可本地化，零依赖。
  - [validator.js](https://github.com/chriso/validator.js) - 字符串验证和清理。
- 日期和时间
  - [moment](https://github.com/moment/moment) - 在 javascript 中解析、验证、操作和显示日期。
    - [moment-timezone](https://github.com/moment/moment-timezone) - moment.js 的时区支持。
  - [date](https://github.com/MatthewMueller/date) - 人类的日期()。
  - [ms.js](https://github.com/guille/ms.js) - 微小的毫秒转换实用程序。
- HTML 实体
  - [he](https://github.com/mathiasbynens/he) - 用 Ja​​vaScript 编写的强大的 HTML 实体编码器/解码器。
- 货币
  - [money.js](https://github.com/openexchangerates/money.js) - 简单小巧的 JavaScript 库，用于从任何货币到任何货币的实时货币转换和汇率计算。
- 颜色
  - [chroma.js](https://github.com/gka/chroma.js) - 用于各种颜色操作的 JavaScript 库。
  - [color](https://github.com/harthur/color) - JavaScript 颜色转换和操作库。
  - [TinyColor](https://github.com/bgrins/TinyColor) - JavaScript 的快速、小型颜色处理和转换。
- 用户代理
  - [UAParser.js](https://github.com/faisalman/ua-parser-js) - 基于 JavaScript 的轻量级用户代理字符串解析器。支持浏览器和 node.js 环境。
- 语义版本
  - [node-semver](https://github.com/npm/node-semver) - 节点的 semver 解析器

## 特定格式处理

_用于解析和处理特定文本格式的库。_

- 通用
  - [jBinary](https://github.com/jDataView/jBinary) - 具有用于描述文件类型和数据结构的声明性语法的二进制文件的高级 I/O（加载、解析、操作、序列化、保存）。
- Office
  - [js-xlsx](https://github.com/SheetJS/js-xlsx) - XLSX / XLSM / XLSB / XLS / SpreadsheetML (Excel Spreadsheet) / ODS 解析器和编写器
- CSV
  - [BabyParse](https://github.com/Rich-Harris/BabyParse) - 基于 Papa Parse 的快速可靠的 CSV 解析器。 Papa Parse 用于浏览器，Baby Parse 用于 Node.js。
  - [CSV](https://github.com/knrz/CSV.js) - 一个简单、超快的 CSV 解析器和编码器。完全符合 RFC 4180。
- JSON
  - [json3](https://github.com/bestiejs/json3) - 与几乎所有 JavaScript 平台兼容的现代 JSON 实现。
- EXIF
  - [exif-js](https://github.com/exif-js/exif-js) - 用于读取 EXIF 图像元数据的 JavaScript 库
- CSS
  - [parse-css](https://github.com/tabatkins/parse-css) - 基于标准的 CSS 解析器
  - [parser-lib CSS parser](https://github.com/CSSLint/parser-lib) - ParserLib CSS 解析器是一个用 JavaScript 编写的受 CSS3 SAX 启发的解析器。默认情况下，解析器仅处理标准 CSS 语法，不进行验证（检查属性名称和值）。
- Torrent
  - [parse-torrent](https://github.com/feross/parse-torrent) - 解析一个 torrent 标识符（magnet uri、.torrent 文件、信息哈希）
- SQL
  - [SQL Parser](https://github.com/forward/sql-parser) - SQL Parser 是用 JS 编写的 SQL 的词法分析器、语法和解析器。目前它只能解析相当基本的 SELECT 查询。
- YAML
  - [JS-YAML](https://github.com/nodeca/js-yaml) - JavaScript YAML 解析器和转储器。非常快。
- Markdown
  - [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown 解析器， 100% CommonMark 支持、扩展、语法插件和高速
- Atom/RSS
  - [node-feedparser](https://github.com/danmactough/node-feedparser) - Node.js 中强大的 RSS、Atom 和 RDF 提要解析
- 书签（火狐，谷歌浏览器，...）
  - [node-bookmarks-parser](https://github.com/calibr/node-bookmarks-parser) - 解析 Firefox/Chrome HTML 书签文件

## 自然语言处理

_用于处理人类语言的库。_

- 通用
  - [natural](https://github.com/NaturalNode/natural) - 节点的通用自然语言工具
  - [nlp_compromise](https://github.com/spencermountain/nlp_compromise) - 自然语言处理
  - [Hanzi](https://github.com/nieldlr/Hanzi) - HanziJS 是一个汉字和 NLP 模块，用于 Node.js 的中文语言处理
  - [salient](https://github.com/nyxtom/salient) - Node.js 的机器学习、自然语言处理和情感分析工具包
  - [node-summary](https://github.com/jbrooksuk/node-summary) - 使用简单的摘要算法总结文本的节点模块
- 词干
  - [snowball-js](https://github.com/fortnightlabs/snowball-js) - 流行的雪球词干提取 nlp 算法的 javascript 实现
  - [porter-stemmer](https://github.com/jedp/porter-stemmer) - Martin Porter 的 node.js 词干分析器
  - [Porter-Stemmer](https://github.com/kristopolous/Porter-Stemmer) - Porter Stemmer 的 Javascript 实现
  - [lunr-languages](https://github.com/MihaiValentin/lunr-languages) - Lunr Javascript 库的语言词干和停用词集合
- 语言检测
  - [franc](https://github.com/wooorm/franc) - 自然语言检测
  - [guessLanguage.js](https://github.com/richtr/guessLanguage.js) - 基于 trigram 统计分析的 Node.js 自然语言检测库

## 浏览器自动化和仿真

- [phantomjs](https://github.com/ariya/phantomjs) - 可编写脚本的无头 WebKit。
- [slimerjs](https://github.com/laurentj/slimerjs) - 一个运行 Gecko 的类似 PhantomJS 的工具。
- [casperjs](https://github.com/n1k0/casperjs) - PhantomJS 和 SlimerJS 的导航脚本和测试实用程序。
- [zombie](https://github.com/assaf/zombie) - 使用 node.js 进行快速、全栈、无头浏览器测试。
- [nightmare](https://github.com/segmentio/nightmare) - Nightmare 是一个高级包装器，可让您自动执行浏览器任务
- [puppeteer](https://github.com/GoogleChrome/puppeteer) - Puppeteer 是一个 Node 库，它提供了一个高级 API 来通过 DevTools 协议控制无头 Chrome 或 Chromium。它还可以配置为使用完整（非无头）Chrome 或 Chromium。
- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - 由 Headless Chrome 驱动的分布式爬虫
- [puppeteer-recorder](https://github.com/checkly/puppeteer-recorder) - Puppeteer 记录器是一个 Chrome 扩展程序，可以记录您的浏览器交互并生成 Puppeteer 脚本。
- [wendigo](https://github.com/angrykoala/wendigo) - 基于 Puppeteer 构建的面向测试的无头浏览器。
- [Playwright](https://github.com/microsoft/playwright) - Node.js 库，使用单个 API 自动化 Chromium、Firefox 和 WebKit

## 多处理

- [nexpect](https://github.com/nodejitsu/nexpect) - 在 node.js 中轻松生成和控制子进程
- [respawn](https://github.com/mafintosh/respawn) - 生成一个进程并在它崩溃时重新启动它
- [node-webworker](https://github.com/pgriess/node-webworker) - NodeJS 的 WebWorkers 实现

## 异步

_用于异步网络编程的库。_

- [socket.io](https://github.com/socketio/socket.io) - 实时应用程序框架（Node.JS 服务器）
- [engine.io](https://github.com/socketio/engine.io) - Engine.IO 是 Socket.IO 的基于传输的跨浏览器/跨设备双向通信层的实现
- [async](https://github.com/caolan/async) - 节点和浏览器的异步实用程序

## 队列

- [kue](https://github.com/Automattic/kue) - Kue 是一个由 redis 支持的优先级作业队列，为 node.js 构建
- [bull](https://github.com/OptimalBits/bull) - 一个轻量级、健壮和快速的作业处理队列。为坚如磐石的稳定性和原子性而精心编写。

## 电子邮件

_用于解析电子邮件的库。_

- [mailparser](https://github.com/andris9/mailparser) - 解码 mime 格式的电子邮件

## URL 和网络地址操作

_用于解析/修改 URL 和网络地址的库。_

- 网址
  - [query-string](https://github.com/sindresorhus/query-string) - 解析和字符串化 URL 查询字符串。
  - [URI.js](https://github.com/medialize/URI.js/) - Javascript URL 变异库。
  - [jsurl](https://github.com/Mikhus/jsurl) - 使用 JavaScript 进行轻量级 URL 操作。
  - [arg.js](https://github.com/stretchr/arg.js) - 轻量级 URL 参数和参数解析器
- 网络地址
  - [node-ip](https://github.com/indutny/node-ip) - node.js 的 IP 地址工具
  - [ip-address](https://github.com/beaugunderson/ip-address) - 用于在 JavaScript 中解析和操作 IPv6（和 v4）地址的库

## 网页内容提取

_用于提取网页内容的库。_

- [node-read](https://github.com/bndr/node-read) - 从任何页面获取可读内容。基于 Arc90 的可读性项目，使用 Cheerio 引擎。
- [node-ytdl-core](https://github.com/fent/node-ytdl-core) - JavaScript 中的 Youtube 视频下载器
- [ImageResolver](https://github.com/mauricesvay/ImageResolver) - 尽最大努力在不加载所有图像的情况下确定 URL 上的主图像。

## 网络套接字

_使用 WebSocket 的库。_

- [websocket.io](https://github.com/LearnBoost/websocket.io) - WebSocket.IO 是 Socket.IO 之前使用的 websocket 服务器的抽象。它对 websocket 协议/规范和 API 具有最广泛的支持，允许与更高级别的框架（例如 Engine、Socket.IO 的实时核心）进行互操作。
- [WebScoket-Node](https://github.com/theturtle32/WebSocket-Node) - Node.JS 的 WebSocket 实现（草案 -08 到最终 RFC 6455）

## DNS 解析

- [multicast-dns](https://github.com/mafintosh/multicast-dns) - 纯 javascript 中的低级多播 dns 实现
- [node-dns](https://github.com/tjfontaine/node-dns) - 用纯 javascript 替换 node.js 的 dns 模块

## 计算机视觉

- [tracking.js](https://github.com/eduardolundgren/tracking.js) - 一种现代的网络计算机视觉方法。
- [ocrad.js](https://github.com/antimatter15/ocrad.js) - 通过 Emscripten 的 Javascript 中的 OCR。

## 代理服务器

- [toxy](https://github.com/h2non/toxy) - 用于模拟服务器故障场景和意外网络条件的可破解 HTTP 代理
- [proxy-chain](https://github.com/apifytech/proxy-chain) - 代理服务器的 Node.js 实现（想想 Squid），支持 SSL、身份验证和上游代理链

## 数据结构

- [immutable-js](https://github.com/facebook/immutable-js) - 用于 Javascript 的不可变持久数据集合，可提高效率和简单性。
- [lodash](https://github.com/lodash/lodash) - 更一致的对数组、字符串、对象和参数对象的跨环境迭代支持

## 其他 JavaScript 列表

- [awesome-javascript](https://github.com/sorrycc/awesome-javascript)
