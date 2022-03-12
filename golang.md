# Golang 网页抓取

此列表包含与 Web 抓取和数据处理相关的 Golang 库。

- [网络请求工具](#网络请求工具)
- [网页抓取框架](#网页抓取框架)
- [HTML/XML](#HTML/XML)
- [文本处理](#文本处理)
- [特定格式处理](#特定格式处理)
- [自然语言处理](#自然语言处理)
- [浏览器自动化和仿真](#浏览器自动化和仿真)
- [多进程](#多进程)
- [队列](#队列)
- [电子邮件](#电子邮件)
- [URL 和网络地址操作](#URL和网络地址操作)
- [网页内容提取](#网页内容提取)
- [异步](#异步)
- [WebSocket](#WebSocket)
- [DNS 解析](#DNS解析)
- [计算机视觉](#计算机视觉)
- [代理服务器](#代理服务器)

## 网络请求工具

- 通用
  - [net](https://golang.org/pkg/net/) - 操作网络的内置包。
  - [net/http](https://golang.org/pkg/net/http/) - 能够进行 HTTP 编程的内置包
- 异步
  - [goroutine](https://tour.golang.org/concurrency/1) - Golang 中的 Concurrency。

## Web 抓取框架

- [Pholcus](https://github.com/henrylee2cn/pholcus) - Pholcus 是一款分布式、高并发、功能强大的网络爬虫软件。
- [go_spider](https://github.com/hu17889/go_spider) - 一个灵活、模块化、可扩展的 Go 并发爬虫（spider）框架。
- [ants-go](https://github.com/wcong/ants-go) - golang 中的分布式的爬虫引擎。
- [geziyor](https://github.com/geziyor/geziyor) - Geziyor，一个超快的网页抓取框架，支持 JS 渲染。
- [colly](https://github.com/gocolly/colly) - 快速优雅的抓取框架
- [dataflowkit](https://github.com/slotix/dataflowkit) - 数据流工具包 - 从网站中提取结构化数据。
- [ferret](https://github.com/MontFerret/ferret) - 具有声明性查询语言的网络抓取工具。
- [crawlab](https://github.com/crawlab-team/crawlab) - 功能强大的爬虫框架。

## HTML/XML

- [encoding/xml](https://golang.org/pkg/encoding/xml/) - 内置包实现了一个简单的 XML 1.0 解析器。

## 文本处理

_用于解析和操作纯文本的库。_

- 通用
  - [regexp](https://golang.org/pkg/regexp/) - 内置包实现正则表达式搜索。

## 特定格式处理

_用于解析和处理特定文本格式的库。_

- 通用
  - [encoding/json](https://golang.org/pkg/encoding/json/) - 内置包实现了 RFC 4627 中定义的 JSON 编码和解码。
  - [allot](https://github.com/sbstjn/allot) - CLI 工具和机器人的占位符和通配符文本解析。
  - [bbConvert](https://github.com/CalebQ42/bbConvert) - 将 bbCode 转换为 HTML，允许您添加对自定义 bbCode 标签的支持。
  - [blackfriday](https://github.com/russross/blackfriday) - Go 中的 Markdown 处理器。
  - [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer。
  - [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Go 的 Editorconfig 文件解析器和操纵器。
  - [enca](https://github.com/endeveit/enca) - [libenca](http://cihar.com/software/enca/) 的最小 cgo 绑定。
  - [genex](https://github.com/alixaxel/genex) - 计算正则表达式并将其扩展为所有匹配的字符串。
  - [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub 风格的 Markdown 渲染器（使用 blackfriday），带有围栏代码块突出显示，可点击的标题锚链接。
  - [go-humanize](https://github.com/dustin/go-humanize) - 将时间、数字和内存大小格式化为人类可读格式。
  - [go-nmea](https://github.com/adrianmo/go-nmea) - Go 语言的 NMEA 解析器库。
  - [go-runewidth](https://github.com/mattn/go-runewidth) - 获取字符或字符串的固定宽度的函数。
  - [go-slugify](https://github.com/mozillazg/go-slugify) - 使用多种语言支持制作漂亮的 slug。
  - [go-vcard](https://github.com/emersion/go-vcard) - 解析和格式化 vCard。
  - [gofeed](https://github.com/mmcdole/gofeed) - 在 Go 中解析 RSS 和 Atom 提要。
  - [gographviz](https://github.com/awalterschulze/gographviz) - 解析 Graphviz DOT 语言。
  - [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - 将字节格式化为字符串。
  - [gonameparts](https://github.com/polera/gonameparts) - 将人名解析为单独的名称部分。
  - [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery 为 Go 语言带来了类似于 jQuery 的语法和一组特性。
  - [goregen](https://github.com/zach-klippenstein/goregen) - 从正则表达式生成随机字符串的库。
  - [gotext](https://github.com/leonelquinteros/gotext) - Go 的 GNU gettext 实用程序。
  - [guesslanguage](https://github.com/endeveit/guesslanguage) - 确定 unicode 文本的自然语言的函数。
  - [inject](https://github.com/facebookgo/inject) - 包注入提供了一个基于反射的注入器。
  - [mxj](https://github.com/clbanning/mxj) - 将 XML 编码/解码为 JSON 或 map[string]interface{}；使用点符号路径和通配符提取值。替换 x2j 和 j2x 包。
  - [sh](https://github.com/mvdan/sh) - 一个 shell 解析器和格式化程序。
  - [slug](https://github.com/gosimple/slug) - URL 友好的 slugify，支持多种语言。
  - [Slugify](https://github.com/avelino/slugify) - 一个处理字符串的 Go slugify 应用程序。
  - [toml](https://github.com/BurntSushi/toml) - TOML 配置格式（带反射的编码器/解码器）。
  - [xpath](https://github.com/antchfx/xpath) - Go 的 XPath 包。
  - [xquery](https://github.com/antchfx/xquery) - XQuery 允许您使用 XPath 表达式从 HTML/XML 文档中提取数据。

## 自然语言处理

_用于处理人类语言的库。_

- [dpar](https://github.com/danieldk/dpar/) - 基于转换的统计依赖解析器。
- [go-eco](https://github.com/ThePaw/go-eco) - 相似度、相异度和距离矩阵；多样性、公平和不平等措施；物种丰富度估算器；共倾模型。
- [go-i18n](https://github.com/nicksnyder/go-i18n/) - 用于处理本地化文本的包和随附工具。
- [go-mystem](https://github.com/dveselov/mystem) - CGo 绑定到 Yandex.Mystem - 俄罗斯形态分析仪。
- [go-nlp](https://github.com/nuance/go-nlp) - 用于处理离散概率分布的实用程序和其他对 NLP 工作有用的工具。
- [go-stem](https://github.com/agonopol/go-stem) - 搬运工词干算法的实现。
- [go-unidecode](https://github.com/mozillazg/go-unidecode) - Unicode 文本的 ASCII 音译。
- [go2vec](https://github.com/danieldk/go2vec) - word2vec 嵌入的阅读器和实用功能。
- [gojieba](https://github.com/yanyiwu/gojieba) - 中文分词算法。
- [jieba](https://github.com/fxsjy/jieba) - jieba 的 Go 实现。
- [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - 雪球 libstemmer 库的 Go 绑定，包括 porter 2。
- [gounidecode](https://github.com/fiam/gounidecode) - Go 的 Unicode 音译（也称为 unidecode）。
- [icu](https://github.com/goodsign/icu) - icu4c C 库检测和转换功能的 Cgo 绑定。保证与版本 50.1 的兼容性。
- [libtextcat](https://github.com/goodsign/libtextcat) - libtextcat C 库的 Cgo 绑定。保证与 2.2 版本的兼容性。
- [MMSEGO](https://github.com/awsong/MMSEGO) - 这是一个中文分词算法，[MMSEG](http://technology.chtsai.org/mmseg/)的 GO 实现。
- [paicehusk](https://github.com/rookii/paicehusk) - Paice/Husk 词干算法的 Golang 实现。
- [porter](https://github.com/a2800276/porter) - 这是 Martin Porter 的 Porter 词干算法 C 实现的一个相当简单的移植。
- [porter2](https://github.com/zhenjl/porter2) - 真正快速的 Porter 2 词干分析器。
- [prose](https://github.com/jdkato/prose) - 支持标记化、词性标记、命名实体提取等的文本处理库。
- [RAKE.go](https://github.com/Obaied/RAKE.go) - 快速自动关键字提取算法 (RAKE) 的 Go 端口。
- [segment](https://github.com/blevesearch/segment) - 用于执行 Unicode 文本分割的 Go 库，如 [Unicode 标准附件 #29](http://www.unicode.org/reports/tr29) 中所述/)
- [sentences](https://github.com/neurosnap/sentences) - 句子标记器：将文本转换为句子列表。
- [snowball](https://github.com/goodsign/snowball) - Go 的 Snowball 词干分析器端口（cgo 包装器）。提供词干提取功能。
- [Snowball native](http://snowball.tartarus.org/)
- [stemmer](https://github.com/dchest/stemmer) - Go 编程语言的 Stemmer 包。包括英语和德语词干分析器。
- [textcat](https://github.com/pebbe/textcat) - 用于基于 n-gram 的文本分类的 Go 包，支持 utf-8 和原始文本。
- [whatlanggo](https://github.com/abadojack/whatlanggo) - Go 的自然语言检测包。支持 84 种语言和 24 种文字（书写系统，例如拉丁文、西里尔文等）。
- [when](https://github.com/olebedev/when) - 具有可插入规则的自然 EN 和 RU 语言日期/时间解析器。

## 浏览器自动化和仿真

- [chromedp](https://github.com/chromedp/chromedp) - 一种更快、更简单的方式来驱动支持 Chrome DevTools 协议的浏览器。

## 多进程

- TODO

## 异步

_用于异步网络编程的库。_

- TODO

## 队列

- [NSQ](https://github.com/nsqio/nsq) - 一个实时分布式消息传递平台。
- [NATS](https://github.com/nats-io/go-nats) - 用于 NATS（云原生消息传递系统）的 Golang 客户端。

## 电子邮件

_用于解析电子邮件的库。_

- [douceur](https://github.com/aymerick/douceur) - 用于 HTML 电子邮件的 CSS 内联。
- [email](https://github.com/jordan-wright/email) - 一个强大而灵活的 Go 电子邮件库。
- [go-dkim](https://github.com/toorop/go-dkim) - 一个 DKIM 库，用于签名和验证电子邮件。
- [go-imap](https://github.com/emersion/go-imap) - 用于客户端和服务器的 IMAP 库。
- [go-message](https://github.com/emersion/go-message) - Internet 消息格式和邮件消息的流媒体库。
- [Gomail](https://github.com/go-gomail/gomail/) - Gomail 是一个非常简单而强大的电子邮件发送包。
- [Hectane](https://github.com/hectane/hectane) - 提供 HTTP API 的轻量级 SMTP 客户端。
- [hermes](https://github.com/matcornic/hermes) - 生成干净、响应式 HTML 电子邮件的 Golang 包。
- [MailHog](https://github.com/mailhog/MailHog) - 使用 Web 和 API 接口进行电子邮件和 SMTP 测试。
- [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid 用于发送电子邮件的 Go 库。
- [smtp](https://github.com/mailhog/smtp) - SMTP 服务器协议状态机。

## URL 和网络地址操作

_用于解析/修改 URL 和网络地址的库。_

- 网址
  - [net/url](https://golang.org/pkg/net/url/)
- 网络地址
  - TODO

## 网页内容提取

_用于提取网页内容的库。_

- HTML 页面中的文本和元数据
- [x/net/html](golang.org/x/net/html)

## 网络套接字

_使用 WebSocket 的库。_

- [gorilla/websocket](https://github.com/gorilla/websocket)

## DNS 解析

- [net](https://golang.org/pkg/net/) - 内置一些 DNS 相关功能。
- [miekg/dns](https://github.com/miekg/dns) - Go 中的 DNS 库。

## 计算机视觉

- TODO

## 代理服务器

- [gin](https://github.com/codegangsta/gin) - Go Web 服务器的实时重新加载实用程序。
- [Caddy](https://github.com/mholt/caddy) - 快速、跨平台的 HTTP/2 网络服务器，带有自动 HTTPS，也可以作为反向代理服务器。
