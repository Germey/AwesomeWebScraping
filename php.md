# PHP 网页抓取

此列表包含与网页抓取和数据处理相关的 PHP 库。

- [网络请求工具](#网络请求工具)
- [网页抓取框架](#HTML/XML解析)
- [HTML/XML](#HTML/XML)
- [文本处理](#文本处理)
- [特定格式处理](#特定格式处理)
- [自然语言处理](#自然语言处理)
- [浏览器自动化和仿真](#浏览器自动化和仿真)
- [多进程](#多进程)
- [队列](#队列)
- [云计算](#云计算)
- [电子邮件](#电子邮件)
- [URL 操作](#URL操作)
- [网页内容提取](#网页内容提取)
- [异步](#异步)
- [WebSocket](#WebSocket)
- [DNS 解析](#DNS解析)
- [计算机视觉](#计算机视觉)
- [地理编码](#地理编码)
- [API 客户端](#API客户端)
- [其他 PHP 列表](#其他PHP列表)

## 网络请求工具

- [Guzzle](https://github.com/guzzle/guzzle) - 一个全面的 HTTP 客户端。
- [Buzz](https://github.com/kriswallsmith/Buzz) - 另一个 HTTP 客户端。
- [Requests](https://github.com/rmccue/Requests) - 一个简单的 HTTP 库。
- [HTTPFul](https://github.com/nategood/httpful) - 一个可链接的 HTTP 客户端。
- [Goutte](https://github.com/fabpot/Goutte) - 一个简单的网络爬虫。
- [PHP Spider](https://github.com/mvdbos/php-spider) - 一个全面的网络蜘蛛。

## Web 抓取框架

- TODO

## HTML/XML

- [HTML5 PHP](https://github.com/Masterminds/html5-php) - HTML5 解析器和序列化程序库。
- [QueryPath](https://github.com/technosophos/querypath) - 一个类似 jQuery 的库，用于在 PHP 中处理 XML 和 HTML 文档。它现在通过 HTML5-PHP 项目包含对 HTML5 的支持。
- [DiDOM](https://github.com/Imangazaliev/DiDOM) - 超快速的 HTML 解析器（因为它是建立在纯 PHP 之上的）。
- [PHPScraper](https://github.com/spekulatius/phpscraper) - 一个高度自以为是的网络界面。

## 文本处理

_用于解析和操作纯文本的库。_

- 通用
  - [ANSI 到 HTML5](https://github.com/sensiolabs/ansi-to-html) - ANSI 到 HTML5 转换器库。
  - [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - 用于处理 UTF-8 字符串的可移植库。
  - [Hoa String](https://github.com/hoaproject/Ustring) - 另一个 UTF-8 字符串库。
  - [Stringy](https://github.com/danielstjules/Stringy) - 支持多字节的字符串操作库。
  - [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - 一个用于操作和转换颜色的库。
  - [Text](https://github.com/kzykhys/Text) - 一个文本操作库。
  - [Flux](https://github.com/selvinortiz/flux) - 一个正则表达式构建库。
- 音译
  - [Urlify](https://github.com/jbroadway/urlify) - Django 的 URLify.js 的 PHP 端口。
  - [Slugify](https://github.com/cocur/slugify) - 一个将字符串转换为 slug 的库。
- 用户代理
  - [设备检测器](https://github.com/piwik/device-detector) - 另一个用于解析用户代理字符串的库。
  - [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - 用于检测移动设备（包括平板电脑）的轻量级 PHP 类。
  - [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - 一个用于解析用户代理字符串的库。
- 计量单位
  - [ByteUnits](https://github.com/gabrielelana/byte-units) - 一个在二进制和公制系统中解析、格式化和转换字节单位的库。
  - [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - 用于在度量单位之间进行转换的库。
  - [PHP Conversion](https://github.com/Crisu83/php-conversion) - 另一个用于在度量单位之间进行转换的库。
- 电话号码
  - [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - Google 电话号码处理库的 PHP 实现。

## 特定格式处理

_用于解析和处理特定文本格式的库。_

- CSV
  - [CSV](https://github.com/thephpleague/csv) - 一个 CSV 数据操作库。
- Office
  - [PHPWord](https://github.com/PHPOffice/PHPWord) - 用于处理 Microsoft Word 文档的库。
  - [PHPExcel](https://github.com/PHPOffice/PHPExcel) - 用于处理 Microsoft Excel 文档的库。
  - [PHPPowerPoint](https://github.com/PHPOffice/PHPPowerPoint) - 用于处理 Microsoft PowerPoint 文档的库。
  - [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - 用于操作 Microsoft Excel 文档的库。
- Markdown
  - [PHP Markdown](https://github.com/michelf/php-markdown) - Markdown 解析器。
  - [CommonMark PHP](https://github.com/thephpleague/commonmark) - 一个支持完整 [CommonMark 规范](http://spec.commonmark.org/) 的 Markdown 解析器。
  - [Parsedown](https://github.com/erusev/parsedown) - 另一个 Markdown 解析器。
  - [Ciconia](https://github.com/kzykhys/Ciconia) - 另一个 Markdown 解析器
  - [Cebe Markdown](https://github.com/cebe/markdown) - 一个快速且可扩展的 Markdown 解析器。
- BBCode
  - [Decoda](https://github.com/milesj/decoda) - 用于 BBCode 样式标记的轻量级词法字符串解析器。
- JSON
  - [JsonMapper](https://github.com/netresearch/jsonmapper) - 一个将嵌套 JSON 结构映射到 PHP 类的库。
- 电子名片
  - [vobject](https://github.com/fruux/sabre-vobject) - VObject 库允许您轻松解析和操作 iCalendar 和 vCard 对象。
- 文件类型检测
  - [Hoa Mime](https://github.com/hoaproject/Mime) - 另一个 MIME 检测库。
  - [Canal](https://github.com/dflydev/dflydev-canal) - 确定互联网媒体类型的库。
  - [Apache MIME 类型](https://github.com/dflydev/dflydev-apache-mime-types) - 解析 Apache MIME 类型的库。
- GeoJSON
  - [GeoJSON](https://github.com/jmikola/geojson) - GeoJSON 实现。

## 自然语言处理

_用于处理人类语言的库。_

- [PHP NlpTools](https://github.com/angeloskath/php-nlp-tools) - PHP 中的自然语言处理工具。
- [nlpTools](https://github.com/atrilla/nlptools) - PHP 的自然语言处理工具包。

## 浏览器自动化和仿真

- [php-webdriver](https://github.com/facebook/php-webdriver) - webdriver 的 php 客户端。
- [PHP PhantomJS](https://github.com/jonnnnyw/php-phantomjs) - 通过 PHP 执行 PhantomJS 命令
- [Mink](https://github.com/minkphp/Mink) - 用于多个浏览器模拟器的通用 API（selenium、zombie.js、goutte）。

## 多进程

- [Spork](https://github.com/kriswallsmith/spork) - 一个进程分叉库。

## 异步

_用于异步网络编程的库。_

- [React](https://github.com/reactphp/react) - 一个事件驱动的非阻塞 I/O 库。
- [Rx.PHP](https://github.com/asm89/Rx.PHP) - 一个反应式扩展库。
- [Hoa EventSource](https://github.com/hoaproject/Eventsource) - 一个事件源库。
- [Evenement](https://github.com/igorw/evenement) - 一个事件调度器库。
- [Event](https://github.com/thephpleague/event) - 一个专注于领域事件的事件库。
- [Broadway](https://github.com/qandidate-labs/broadway) - 事件源和 CQRS 库。

## 队列

- [Pheanstalk](https://github.com/pda/pheanstalk) - 一个 Beanstalkd 客户端库。
- [PHP AMQP](https://github.com/videlalvaro/php-amqplib) - 一个纯 PHP AMQP 库。
- [Thumper](https://github.com/videlalvaro/Thumper) - RabbitMQ 模式库。
- [Bernard](https://github.com/bernardphp/bernard) - 一个多后端抽象库。

## 云计算

- TODO

## 电子邮件

_用于解析电子邮件的库。_

- [电子邮件回复解析器](https://github.com/willdurand/EmailReplyParser) - 一个电子邮件回复解析器库。
- [电子邮件验证器](https://github.com/nojacko/email-validator) - 一个小型电子邮件地址验证库。

## URL 操作

_用于解析 URL 的库。_

- [Purl](https://github.com/jwage/purl) - 一个 URL 操作库。
- [PHP 域解析器](https://github.com/jeremykendall/php-domain-parser) - 域后缀解析器库。
- [Uri](https://github.com/thephpleague/uri) (PHP League) - 一个简单的 URL 操作库（兼容 PSR-7）。

## 网页内容提取

- 来自 Web 文档的文本和元数据
  - [Essence](https://github.com/felixgirault/essence) - 用于提取网络媒体的库。
  - [Embera](https://github.com/mpratt/Embera) - 一个 Oembed 消费者库。
  - [Embed](https://github.com/oscarotero/Embed) - 一个很棒的库，用于从网页获取有用的信息。
- 视频
  - [Youtube-Downloader](https://github.com/jeckman/YouTube-Downloader) - 用于从 youtube 下载视频的 PHP 脚本；还将 youtube 提要解析为播客的 RSS 附件。

## 网络套接字

_使用 WebSocket 的库。_

- [Ratchet](https://github.com/cboden/Ratchet) - 一个网络套接字库。
- [Hoa WebSocket](https://github.com/hoaproject/Websocket) - 另一个 Web 套接字库。
- [Elephant.io](https://github.com/Wisembly/Elephant.io) - 另一个 Web 套接字库。

## DNS 解析

- [Net_DNS2](https://github.com/mikepultz/netdns2) - 原生 PHP DNS 解析器和更新器。

## 计算机视觉

- [OpenCV-for-PHP](https://github.com/mgdm/OpenCV-for-PHP) - PHP 的 OpenCV 绑定。

## 地理编码

- [GeoCoder](http://geocoder-php.org/) - 一个地理编码库。
- [GeoTools](https://github.com/php-loep/Geotools) - 地理相关工具库。

## 其他 PHP 列表

- [awesome-php](https://github.com/ziadoz/awesome-php)
