# Ruby 网页抓取

此列表包含与网页抓取和数据处理相关的 ruby​​ 库

- [Ruby 网页抓取](#ruby-web-scraping)
  - [网络](#network)
  - [网页抓取框架](#web-scraping-frameworks)
  - [HTML/XML 解析](#htmlxml-解析)
  - [文本处理](#text-processing)
  - [特定格式处理](#specific-formats-processing)
  - [自然语言处理](#natural-language-processing)
  - [浏览器自动化和仿真](#browser-automation-and-emulation)
  - [多处理](#multiprocessing)
  - [异步](#异步)
  - [队列](#queue)
  - [电子邮件](#email)
  - [URL 操作](#url-manipulation)
  - [网页内容提取](#web-content-extracting)
  - [WebSocket](#websocket)
  - [DNS 解析](#dns-resolving)
  - [计算机视觉](#computer-vision)
  - [地理位置](#geolocation)
  - [其他 Ruby 列表](#other-Ruby-lists)

## 网络

- [httparty](https://github.com/jnunemaker/httparty) 让 http 再次变得有趣！
- [http](https://github.com/tarcieri/http) 用于发出 HTTP 请求的简单 Ruby DSL
- [excon](https://github.com/excon/excon) 适用于 Ruby 的可用、快速、简单的 HTTP(S) 1.1
- [nestful](https://github.com/maccman/nestful) 带有健全 API 的简单 Ruby HTTP/REST 客户端
- [EM-HTTP-Request](https://github.com/igrigorik/em-http-request) - 基于 EventMachine 的异步 HTTP 客户端
- [excon](https://github.com/excon/excon) - 可用、快速、简单的 Ruby HTTP 1.1。它作为通用 HTTP(s) 客户端工作得很好，特别适合在 API 客户端中使用。
- [Faraday](https://github.com/lostisland/faraday) - 一个 HTTP 客户端库，在许多适配器（例如 Net::HTTP）上提供通用接口，并在处理请求时包含 Rack 中间件的概念/响应周期。
- [Http Client](https://github.com/nahi/httpclient) - 在 Ruby 中提供类似于 libwww-perl (LWP) 的功能。
- [HTTP](https://github.com/httprb/http.rb) - HTTP Gem：用于发出 HTTP 请求的简单 Ruby DSL。
- [Http-2](https://github.com/igrigorik/http-2) - HTTP/2 协议的纯 Ruby 实现
- [Patron](https://github.com/toland/patron) - Patron 是一个基于 libcurl 的 Ruby HTTP 客户端库。
- [RESTClient](https://github.com/rest-client/rest-client) - Ruby 的简单 HTTP 和 REST 客户端，灵感来自用于指定操作的微框架语法。
- [Savon](https://github.com/savonrb/savon) - Savon 是 Ruby 编程语言的 SOAP 客户端。
- [Sawyer](https://github.com/lostisland/sawyer) - HTTP 的秘密用户代理，建立在 Faraday 之上。
- [Spyke](https://github.com/balvig/spyke) - 以类似 ActiveRecord 的方式与 REST 服务交互。
- [Typhoeus](https://github.com/typhoeus/typhoeus) - Typhoeus 包装了 libcurl 以便发出快速可靠的请求。
- [Mechanize](https://github.com/sparklemotion/mechanize) - Mechanize 是一个 ruby​​ 库，可以轻松实现自动化 Web 交互。

## Web 抓取框架

- [upton](https://github.com/propublica/upton) - 一个包含电池的框架，用于轻松进行网络抓取
- [Wombat](https://github.com/felipecsl/wombat) - 具有优雅 DSL 的 Web 抓取工具，可解析网页中的结构化数据。
- [Anemone](https://github.com/chriskite/anemone) - 网络蜘蛛框架，可以蜘蛛域并收集有关它访问的页面的有用信息
- [Spidr](https://github.com/postmodern/spidr) - 多功能 Ruby 网络爬虫库，可以爬取一个站点、多个域、某些链接或无限。 Spidr 旨在快速且易于使用。
- [kimuraframework](https://github.com/vifreefly/kimuraframework) - 用 Ruby 编写的现代网络抓取框架，可与 Headless Chromium/Firefox、PhantomJS 或简单的 HTTP 请求一起使用，并允许抓取并与 JavaScript 交互呈现的网站
- [arachnid2](https://github.com/samnissen/arachnid2) 一个简单、快速、无框架的爬虫，具有合理的默认值和许多选项。抓取页面并直接针对 Typhoeus 响应或 Watir 浏览器运行您的代码。

## HTML/XML 解析

- [nokogiri](https://github.com/sparklemotion/nokogiri) - 支持 XPath 和 CSS 选择器的 HTML、XML、SAX 和 Reader 解析器
- [loofah](https://github.com/flavorjones/loofah) - 基于 Nokogiri 的 HTML/XML 操作和清理
- [HappyMapper](https://github.com/dam5s/happymapper) - 允许您解析 XML 数据并将其快速轻松地转换为 ruby​​ 数据结构。
- [HTML::Pipeline](https://github.com/jch/html-pipeline) - HTML 处理过滤器和实用程序。
- [Oga](https://github.com/YorickPeterse/oga) - 用 Ruby 编写的 XML/HTML 解析器。 Oga 不需要 libxml 等系统库，在各种平台上安装更容易、更快捷。
- [Ox](https://github.com/ohler55/ox) - 一个快速的 XML 解析器和对象编组器。
- [ROXML](https://github.com/Empact/roxml) - 使用注解样式类方法在 Ruby 和 XML 之间自定义映射和双向编组，通过
