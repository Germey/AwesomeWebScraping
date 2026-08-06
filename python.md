# Python 网页抓取

此列表包含与网络抓取和数据处理相关的 Python 库。

- [网络请求工具](#网络请求工具)
- [网页抓取](#网页抓取)
- [HTML/XML](#HTML/XML)
- [文本处理](#文本处理)
- [结构化格式](#结构化格式)
- [序列化](#序列化)
- [自然语言处理](#自然语言处理)
- [浏览器自动化](#浏览器自动化)
- [多进程](#多进程)
- [作业队列](#任务队列)
- [消息队列](#消息队列)
- [云计算](#云计算)
- [电子邮件](#电子邮件)
- [URL 和网络地址](#URL和网络地址)
- [网页内容提取](#网页内容提取)
- [异步](#异步)
- [WebSocket](#WebSocket)
- [DNS 解析](#DNS解析)
- [计算机视觉](#计算机视觉)
- [代理服务器](#代理服务器)
- [Whois](#Whois)
- [特定网页抓取](#特定网页抓取)
- [JavaScript 引擎绑定](#JavaScript引擎绑定)
- [其他 Python 列表](#其他Python列表)

## 网络请求工具

### 网络请求库：通用

- [urllib](https://docs.python.org/3.4/library/urllib.html?highlight=urllib#module-urllib) - 网络库 (stdlib)。
- [requests](https://github.com/kennethreitz/requests) - 几乎是最流行的网络请求库。
- [grab](https://github.com/lorien/grab) - 网络库（基于 pycurl）。
- [pycurl](https://github.com/pycurl/pycurl) - 网络库（基于 [libcurl](http://curl.haxx.se/libcurl/)）。
- [urllib3](https://github.com/shazow/urllib3) - 具有线程安全连接池、文件发布支持、健全友好等的 Python HTTP 库。
- [httplib2](https://github.com/httplib2/httplib2) - 小型、快速的 HTTP 客户端库。具有持久连接、缓存和 Google App Engine 支持。
- [RoboBrowser](https://github.com/jmcarp/robobrowser) - 一个简单的 Pythonic 库，用于在没有独立 Web 浏览器的情况下浏览 Web。
- [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - 用于自动与网站交互的 Python 库。
- [mechanize](https://github.com/python-mechanize/mechanize) - 有状态的程序化网页浏览。
- [socket](https://docs.python.org/3/library/socket.html) 底层网络接口 (stdlib)。
- [Unirest for Python](https://github.com/Mashape/unirest-python) - Unirest 是一组轻量级的 HTTP 库，支持多种语言。
- [hyper](https://github.com/Lukasa/hyper) - Python 的 HTTP/2 客户端。
- [PySocks](https://github.com/Anorov/PySocks) - 更新和积极维护的 SocksiPy 版本，具有错误修复和额外功能。作为插座模块的直接替代品。

### 网络请求工具：异步

- [treq](https://github.com/dreid/treq) - API 之类的请求。
- [aiohttp](https://github.com/KeepSafe/aiohttp) - asyncio 的 http 客户端/服务器 (PEP-3156)。

### 网络请求工具：底层

- [dpkt](https://github.com/kbandla/dpkt) - 快速、简单的数据包创建/解析，具有基本 TCP/IP 协议的定义。
- [pyOpenSSL](https://github.com/pyca/pyopenssl) - 一个围绕 OpenSSL 库的 Python 包装器。
- [tlslite-ng](https://github.com/tomato42/tlslite-ng) - 纯 python 中的 TLS 实现。
- [scapy](https://github.com/secdev/scapy) - 强大的基于 Python 的交互式数据包操作程序和库。
- [impacket](https://github.com/SecureAuthCorp/impacket/) - 对网络协议数据包的低级编程访问。

## 网页抓取

### 网页抓取：框架

- [grab](https://grablab.org/docs/) - 网络抓取框架（基于 pycurl/multicurl）。
- [scrapy](http://scrapy.org/) - 网络抓取框架（基于 Twisted）。
- [pyspider](https://github.com/binux/pyspider) - 一个强大的爬取系统。
- [cola](https://github.com/chineking/cola) - 一个分布式爬虫框架。
- [ruia](https://github.com/howie6879/ruia) - 基于 asyncio 的异步 Python 3.6+网页抓取微框架。
- [ioweb](https://github.com/lorien/ioweb) - 基于 gevent 和 lxml 的网页抓取框架。
- [autoscraper](https://github.com/alirezamika/autoscraper) - 一个智能、自动、轻量级的网络爬虫。
- [frontera](https://github.com/scrapinghub/frontera) - 一个可扩展的网络爬虫框架。
- [Scrapegraph-ai](https://github.com/VinciGit00/Scrapegraph-ai) - 一个使用 AI 进行抓取的开源库

### 网页抓取：工具

- [portia](https://github.com/scrapinghub/portia) - Scrapy 的可视化抓取。
- [restkit](https://github.com/benoitc/restkit) - Python 的 HTTP 资源工具包。它允许您轻松访问 HTTP 资源并围绕它构建对象。
- [requests-html](https://github.com/kennethreitz/requests-html) - Pythonic HTML Parsing for Humans。
- [ScrapydWeb](https://github.com/my8100/scrapydweb) - Scrapyd 集群管理的全功能 Web UI，支持 Scrapy 日志分析&可视化、自动打包、定时任务、邮件通知等。
- [Starbelly](https://github.com/HyperionGray/starbelly) - Starbelly 是一个用户友好且高度可配置的网络爬虫前端。
- [Gerapy](https://github.com/Gerapy/Gerapy) - 基于 Scrapy, Scrapyd, Django、Vue.js 的分布式爬虫管理框架。

### 网页抓取：绕过保护

- [cloudscraper](https://github.com/venomous/cloudscraper) - 绕过 Cloudflare 的反机器人页面的 Python 模块。

## HTML/XML

### HTML/XML：通用

- [lxml](https://github.com/lxml/lxml/) - 有效的 HTML/XML 处理库，支持 XPATH。
- [cssselect](https://github.com/scrapy/cssselect) - 使用带有 CSS 选择器的 DOM 树。
- [pyquery](https://github.com/gawel/pyquery) - 使用类 jQuery 选择器的 DOM 树。
- [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) - 慢速 HTML/XMl 处理库，纯 Python 编写。
- [html5lib](https://github.com/html5lib/html5lib-python) - 根据 [WHATWG 规范](url=http://www.whatwg.org/) 构建 HTML/XML 文档的 DOM。该规范用于所有现代浏览器。
- [feedparser](https://github.com/kurtmckee/feedparser) - 解析 RSS/ATOM 提要。
- [MarkupSafe](https://github.com/mitsuhiko/markupsafe) - 为 Python 实现 XML/HTML/XHTML 标记安全字符串。
- [xmltodict](https://github.com/martinblech/xmltodict) - 使用 XML 感觉就像使用 JSON。
- [xhtml2pdf](https://github.com/chrisglass/xhtml2pdf) - HTML/CSS 到 PDF 转换器。
- [untangle](https://github.com/stchris/untangle) - 将 XML 文档转换为 Python 对象以便于访问。
- [hodor](https://github.com/CompileInc/hodor) - 围绕 lxml 和 cssselect 的配置驱动包装器。
- [chopper](https://github.com/jurismarches/chopper) - 使用相应 CSS 规则从 HTML 页面中提取部分并保留正确 HTML 的工具。
- [selectolax](https://github.com/rushter/selectolax) - Python 绑定到 Modest 引擎（带有 CSS 选择器的快速 HTML5 解析器）。
- [parsel](https://github.com/scrapy/parsel) - 允许您使用 XPath 或 CSS 选择器从 XML/HTML 文档中提取数据。
- [html5-parser](https://github.com/kovidgoyal/html5-parser) - 用于 python 的基于 C 的快速 HTML5 解析。
- [gazpacho](https://github.com/maxhumber/gazpacho/) - 一个简单、快速、现代的网络抓取库。

### HTML/XML：消毒

- [Bleach](https://github.com/mozilla/bleach) - HTML 的清理（需要 html5lib）。
- [sanitize](https://github.com/Alir3z4/sanitize) - 为混乱的数据世界带来理智。

### HTML/XML：元数据

- [extruct](https://github.com/scrapinghub/extruct) - 用于从 HTML 标记中提取嵌入元数据的库。

## 文本处理

用于解析和操作纯文本的库。

### 文本处理：通用

- [difflib](https://docs.python.org/3/library/difflib.html) - （Python 标准库）计算增量的助手。
- [Levenshtein](https://github.com/ztane/python-Levenshtein/) - 快速计算 Levenshtein 距离和字符串相似度。
- [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - 模糊字符串匹配。
- [esmre](https://code.google.com/p/esmre/) - 正则表达式加速器。
- [ftfy](https://github.com/LuminosoInsight/python-ftfy) - 自动减少 Unicode 文本的损坏和更一致。

### 文本处理：音译

- [unidecode](https://pypi.python.org/pypi/Unidecode) - Unicode 文本的 ASCII 音译库。

### 文本处理：字符编码

- [uniout](https://github.com/moskytw/uniout) - 打印可读字符而不是转义字符串。
- [chardet](https://github.com/chardet/chardet) - Python 2/3 兼容的字符编码检测器。
- [xpinyin](https://github.com/lxneng/xpinyin) - 一个将汉字（汉字）翻译成拼音（拼音）的库。
- [pangu.py](https://github.com/vinta/pangu.py) - CJK 和字母数字的间距文本。
- [cchardet](https://github.com/PyYoshi/cChardet) - cChardet 是高速通用字符编码检测器，绑定到 uchardet。

### 文本处理：Slugify

- [awesome-slugify](https://github.com/dimka665/awesome-slugify) - 一个可以保存 unicode 的 Python slugify 库。
- [python-slugify](https://github.com/un33k/python-slugify) - 一个将 unicode 转换为 ASCII 的 Python slugify 库。
- [unicode-slugify](https://github.com/mozilla/unicode-slugify) - 生成 unicode slug 的 slugifier。
- [pytils](https://github.com/j2a/pytils) - 处理俄语字符串的简单工具（包括 pytils.translit.slugify）。

### 文本处理：通用解析器

- [PLY](http://www.dabeaz.com/ply/) - 用于 Python 的 lex 和 yacc 解析工具的实现。
- [pyparsing](https://github.com/pyparsing/pyparsing) - 用于生成解析器的通用框架。

### 文本处理：人名

- [python-nameparser](https://github.com/derek73/python-nameparser) - 将人名解析成各自的组成部分。

### 文本处理：电话号码

- [电话号码](https://github.com/daviddrysdale/python-phonenumbers) - 解析、格式化、存储和验证国际电话号码。

### 文本处理：用户代理字符串

- [HTTP 代理解析器](https://github.com/shon/httpagentparser) - Python HTTP 代理解析器。
- [uap-python](https://github.com/ua-parser/uap-python) - ua-parser 的 Python 实现。
- [python-user-agents](https://github.com/selwin/python-user-agents) - 浏览器用户代理解析器。
- [fake-useragent](https://github.com/hellysmile/fake-useragent) - Python 用户代理字符串伪造者，基于浏览器的世界统计数据。
- [user_agent](https://github.com/lorien/user_agent) - 用户代理数据生成器。

### 文本处理：robots.txt

- [reppy](https://github.com/seomoz/reppy) - 适用于 Python 的现代 robots.txt 解析器。

### 文本处理：日期和时间

- [dateutil](https://github.com/dateutil/dateutil) - 对标准 Python 日期时间功能的有用扩展。
- [dateparser](https://github.com/scrapinghub/dateparser) - 用于人类可读日期的 python 解析器。
- [ciso8601](https://github.com/closeio/ciso8601) - 将 ISO 8601 或 RFC 3339 日期时间字符串转换为 Python 日期时间对象。

### 文本处理： 价格和货币

- [price-parser](https://github.com/scrapinghub/price-parser) - 一个用于从原始文本字符串中提取价格和货币的小型库。

## 结构化格式

用于解析和操作特定文本格式的库。

### 结构化格式：通用

- [tablib](https://github.com/kennethreitz/tablib) - XLS、CSV、JSON、YAML 格式的表格数据集模块。
- [texttract](https://github.com/deanmalmgren/textract) - 从任何文档、Word、PowerPoint、PDF 等中提取文本。
- [messytables](https://github.com/okfn/messytables) - 解析杂乱表格数据的工具。
- [rows](https://github.com/turicas/rows) - 一个通用的、漂亮的表格数据界面，无论格式如何（目前是 CSV、HTML、XLS、TXT）。

### 结构化格式：Office

- [python-docx](https://github.com/python-openxml/python-docx) - 读取、查询和修改 Microsoft Word 2007/2008 docx 文件。
- [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - 从 Excel 文件中写入和读取数据以及格式化信息。
- [XlsxWriter](https://xlsxwriter.readthedocs.org/) - 用于创建 Excel .xlsx 文件的 Python 模块。
- [xlwings](http://xlwings.org/) - 一个 BSD 许可的库，可以轻松地从 Excel 调用 Python，反之亦然。
- [openpyxl](https://openpyxl.readthedocs.org/en/latest/) - 用于读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。
- [Marmir](https://github.com/brianray/mm) - 采用 Python 数据结构并将它们转换为电子表格。

### 结构化格式：PDF

- [PDFMiner](https://github.com/euske/pdfminer) - 从 PDF 文档中提取信息的工具。
- [PyPDF2](https://github.com/mstamy2/PyPDF2) - 一个能够拆分、合并和转换 PDF 页面的库。
- [ReportLab](http://www.reportlab.com/opensource/) - 允许快速创建丰富的 PDF 文档。
- [pdftables](https://pypi.python.org/pypi/pdftables) - 直接从 PDF 文件中提取表格

### 结构化格式：Markdown

- [Python-Markdown](https://github.com/waylan/Python-Markdown) - John Gruber 的 Markdown 的 Python 实现。
- [Mistune](https://github.com/lepture/mistune) - 最快且功能齐全的 Markdown 纯 Python 解析器。
- [markdown2](https://pypi.python.org/pypi/markdown2) - Markdown 的快速且完整的 Python 实现。
- [mistletoe](https://github.com/miyuchina/mistletoe) - 在纯 Python 中快速、可扩展且符合规范的 Markdown 解析器。

### 结构化格式：YAML

- [PyYAML](https://github.com/yaml/pyyaml) - Python 的 YAML 实现。

### 结构化格式：CSS

- [cssutils](https://pypi.python.org/pypi/cssutils/) - Python 的 CSS 库。

### 结构化格式：ATOM/RSS

- [feedparser](http://pythonhosted.org/feedparser/) - 通用提要解析器。

### 结构化格式：SQL

- [sqlparse](https://sqlparse.readthedocs.org/) - 一个非验证 SQL 解析器。

### 结构化格式：HTTP

- [http-parser](https://github.com/benoitc/http-parser) - C 中 python 的 HTTP 请求/响应解析器。
- [httptools](https://github.com/MagicStack/httptools) - Node.js HTTP 解析器的 Python 绑定。

### 结构化格式：微格式

- [opengraph](https://github.com/erikriver/opengraph) - 解析开放图协议标签的 Python 模块。

### 结构化格式：可移植的可执行文件

- [pefile](https://github.com/erocarrera/pefile) - 一个多平台模块，用于解析和使用可移植可执行文件（又名 PE）文件。

### 结构化格式：PSD

- [psd-tools](https://github.com/kmike/psd-tools) - 读取 Adob​​e Photoshop PSD 文件（如 [规范](https://www.adobe.com/devnet-apps/photoshop) 中所述/fileformatashtml/PhotoshopFileFormats.htm)) 到 Python 数据结构。

### 结构化格式：书签文件

- [bookmarks-parser](https://github.com/bookmarks-tools/bookmarks-parser) - 解析 Firefox/Chrome HTML 书签文件。

## 序列化

- [orjson](https://github.com/ijl/orjson) - 支持数据类和日期时间的快速、正确的 Python JSON 库。
- [ujson](https://github.com/esnme/ultrajson) - 用 C 语言编写的超快速 JSON 解码器和编码器，带有 Python 绑定。

## 自然语言处理

用于处理人类语言的库。

- [NLTK](http://www.nltk.org/) - 用于构建 Python 程序以处理人类语言数据的领先平台。
- [spacy](https://github.com/explosion/spaCy) - 允许使用最先进的深度学习模型来完成常见的 NLP 任务。
- [fastai](https://github.com/fastai/fastai) - 带有免费视频教程 + 活跃论坛社区的深度学习库，lib 的缺点：需要 GPU。
- [gensim](https://github.com/RaRe-Technologies/gensim) - 用于主题建模、文档索引和大型语料库相似性检索的库。
- [Pattern](http://www.clips.ua.ac.be/pattern) - Python 的网络挖掘模块。它具有用于自然语言处理、机器学习等的工具。
- [TextBlob](http://textblob.readthedocs.org/) - 为深入研究常见的 NLP 任务提供一致的 API。站在 NLTK 和 Pattern 的巨大肩膀上。
- [jieba](https://github.com/fxsjy/jieba) - 中文分词工具。
- [SnowNLP](https://github.com/isnowfy/snownlp) - 处理中文文本的库。
- [loso](https://github.com/victorlin/loso) - 另一个中文分词库。
- [genius](https://github.com/duanhongyi/genius) - 基于条件随机场的中文片段。
- [langid.py](https://github.com/saffsd/langid.py) - 独立的语言识别系统。
- [韩语](https://korean.readthedocs.org/) - [韩语](http://en.wikipedia.org/wiki/Korean_language) 形态学库。
- [pymorphy2](https://github.com/kmike/pymorphy2) - 俄语的形态分析器（POS 标记器 + 转换引擎）。
- [PyPLN](https://github.com/NAMD/pypln.backend) - 用于自然语言处理的分布式管道，用 Python 制作。该项目的目标是创建一种使用 NLTK 处理大型语料库的简单方法，并带有 Web 界面。
- [langdetect](https://github.com/Mimino666/langdetect) - Google 语言检测库到 Python 的端口。

## 浏览器自动化

### 浏览器自动化：浏览器

- [selenium](http://selenium-python.readthedocs.io/) - 自动化真实浏览器（Chrome、Firefox、Opera、IE）。
- [Ghost.py](http://carrerasrodrigo.github.io/Ghost.py/) - QtWebKit 的包装器（需要 PyQT）。
- [Spynner](https://github.com/makinacorpus/spynner) - QtWebKit QtWebKit 的包装器（需要 PyQT）。
- [Splinter](https://github.com/cobrateam/splinter) - 浏览器模拟器的通用 API (selenium webdrivers, django client, zope)。
- [Requestium](https://github.com/tryolabs/requestium) - Requests 和 Selenium 之间的集成层，用于 Web 操作的自动化。
- [Splash](https://github.com/scrapinghub/splash) - 具有 HTTP API 的轻量级、可编写脚本的浏览器即服务。
- [pyppeteer](https://github.com/miyakogi/pyppeteer) - 无头 chrome/chromium 自动化库（puppeteer 的非官方端口）。
- [Playwright](https://github.com/microsoft/playwright-python) - Playwright 是一个 Python 库，可通过单个 API 自动化 Chromium、Firefox 和 WebKit 浏览器。
- [seleniumbase](https://github.com/seleniumbase/SeleniumBase) - 用于 Web/UI 测试 + RPA 的 Python 框架。 🤖 🏰 快速、简单、可靠。
- [invisible-playwright](https://github.com/feder-cr/invisible_playwright) - Playwright 封装基于自定义补丁的 Firefox 150，无 JavaScript 注入即可绕过 reCAPTCHA v3 和 FingerprintPro。

### 浏览器自动化：工具

- [xvfbwrapper](https://github.com/cgoldberg/xvfbwrapper) - 用于在 X 虚拟帧缓冲区 (Xvfb) 中运行显示的 Python 包装器。

## 多进程

- [线程](http://docs.python.org/3/library/threading.html) - 运行线程的标准 python 库。对 I/O 密集型任务有效。由于 python GIL，对 CPU 密集型任务无用。
- [multiprocessing](http://docs.python.org/3/library/multiprocessing.html) - 运行进程的标准 Python 库。
- [concurrent-futures](https://docs.python.org/3/library/concurrent.futures.html) - concurrent.futures 模块为异步执行可调用对象提供高级接口。

## 异步

用于异步网络编程的库。

- [asyncio](https://docs.python.org/3/library/asyncio.html) - （Python 3.4+ 中的 Python 标准库）异步 I/O、事件循环、协程和任务。
- [Twisted](https://twistedmatrix.com/trac/) - 一个事件驱动的网络引擎。
- [Tornado](http://www.tornadoweb.org/) - 一个 Web 框架和异步网络库。
- [pulsar](https://github.com/quantmind/pulsar) - Python 的事件驱动并发框架。
- [diesel](https://github.com/jamwt/diesel) - 基于 Greenlet 的 Python 事件 I/O 框架。
- [gevent](http://www.gevent.org/) - 一个使用 [greenlet](https://github.com/python-greenlet/greenlet) 的基于协程的 Python 网络库。
- [eventlet](http://eventlet.net/) - 支持 WSGI 的异步框架。
- [明天](https://github.com/madisonmay/Tomorrow) - 异步代码的魔术装饰器语法。
- [grequests](https://github.com/kennethreitz/grequests) - 轻松制作异步 HTTP 请求。

## 任务队列

- [芹菜](http://www.celeryproject.org/) - 基于分布式消息传递的异步任务队列/作业队列。
- [huey](https://github.com/coleifer/huey) - 小的多线程任务队列。
- [mrq](https://github.com/pricingassistant/mrq) - Mr. Queue - Python 中使用 Redis 和 gevent 的分布式工作任务队列。
- [RQ](https://github.com/rq/rq) - 基于 redis 的轻量级任务队列管理器
- [simpleq](https://github.com/rdegges/simpleq) - 一个简单、无限可扩展、基于 Amazon SQS 的队列。
- [python-gearman](https://github.com/Yelp/python-gearman) - Gearman 的 python API。

## 消息队列

- [kombu](https://github.com/celery/kombu) - Python 的消息传递库。

## 云计算

- [picloud](http://docs.picloud.com/) - 在云端执行 python 代码。
- [dominoup.com](http://www.dominoup.com/) - 在云端执行 R、Python 和 matlab 代码。
- [minigun-requests](https://github.com/umihico/minigun-requests) - Web 抓取 API 将大量 GET 和 xpath 外包给云计算。
- [pythonista-chromeless](https://github.com/umihico/pythonista-chromeless) - 在 selenium 上执行给定 python 代码的 AWS lambda。

## 电子邮件

用于解析电子邮件的库。

- [flanker](https://github.com/mailgun/flanker) - 一个电子邮件地址和 Mime 解析库。
- [Talon](https://github.com/mailgun/talon) - Mailgun 库，用于提取消息引用和签名。

## URL 和网络地址

用于解析/修改 URL、网络地址、域名的库。

### URL 和网络地址：URL

- [furl](https://github.com/gruns/furl) - 一个小型 Python 库，使操作 URL 变得简单。
- [purl](https://github.com/codeinthehole/purl) - 一个简单的、不可变的 URL 类，具有用于询问和操作的干净 API。
- [urllib.parse](https://docs.python.org/3/library/urllib.parse.html) - 在组件（寻址方案、网络位置、路径等）中分解统一资源定位器（URL）字符串的接口)，将组件组合回 URL 字符串，并在给定“基本 URL”的情况下将“相对 URL”转换为“绝对 URL”（标准库）。

### URL 和网络地址：网络地址

- [netaddr](https://github.com/drkjam/netaddr) - 一个用于表示和操作网络地址的 Python 库。
- [micawber](https://github.com/coleifer/micawber) - 一个用于从 URL 中提取丰富内容的小型库。

### URL 和网络地址：域名

- [tldextract](https://github.com/john-kurkowski/tldextract) - 使用公共后缀列表准确地将 TLD 与 URL 的注册域和子域分开。
- [find_domains](https://github.com/lorien/find_domains) - 在文本数据中搜索域名的库。

## 网页内容提取

用于提取 Web 内容的库。

- [newspaper](https://github.com/codelucas/newspaper) - Python 中的新闻提取、文章提取和内容管理。
- [python-goose](https://github.com/grangier/python-goose) - HTML 内容/文章提取器。
- [scrapely](https://github.com/scrapy/scrapely) - 用于从 HTML 页面中提取结构化数据的库。给定一些示例网页和要提取的数据，为所有相似页面构建解析器。
- [htmldate](https://github.com/adbar/htmldate) - 使用常见的结构模式或基于文本的启发式查找创建日期。
- [lassie](https://github.com/michaelhelmick/lassie) - 人类的 Web 内容检索。
- [html2text](https://github.com/Alir3z4/html2text) - 将 HTML 转换为 Markdown 格式的文本。
- [libextract](https://github.com/datalib/libextract) - 从网站中提取数据。
- [python-readability](https://github.com/buriy/python-readability) - arc90 可读性工具的快速 Python 端口。
- [sumy](https://github.com/miso-belica/sumy) - 用于自动汇总文本文档和 HTML 页面的模块。
- [Haul](https://github.com/vinta/Haul) - 可扩展的图像爬虫。
- [you-get](http://www.soimort.org/you-get/) - 一个用 Python 3 编写的 YouTube/Youku/Niconico 视频下载器。
- [youtube-dl](http://rg3.github.io/youtube-dl/) - 从 YouTube 下载视频的小型命令行程序。
- [WikiTeam](https://github.com/WikiTeam/wikiteam) - 下载和保存 wiki 的工具。
- [linkchecker](https://github.com/wummel/linkchecker) - 检查网络文档或完整网站中的链接。
- [python-sitemap](https://github.com/c4software/python-sitemap) - 从网站制作站点地图的迷你网站爬虫。
- [trafilatura](https://github.com/adbar/trafilatura) - 快速提取正文和评论以及结构，转换为 TXT、CSV 和 XML。
- [advertools](https://github.com/eliasdabbas/advertools) - 一个可定制的爬虫，用于分析 SEO 以及页面和网站的内容。
- [photon](https://github.com/s0md3v/Photon) - 为 OSINT 设计的令人难以置信的快速爬虫。
- [extractnet](https://github.com/currentsapi/extractnet) - Python 3 中基于机器学习的内容和元数据提取。

## 网络套接字

用于使用 WebSocket 的库。

- [Crossbar](https://github.com/crossbario/crossbar/) - 开源统一的应用程序路由器（用于高速公路上的 Python 的 Websocket 和 WAMP）。
- [AutobahnPython](https://github.com/tavendo/AutobahnPython) - Twisted 和 [asyncio](https://docs.python.org/3/library/asyncio.html) 上用于 Python 的 WebSocket 和 WAMP。
- [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) - Python 2 和 3 以及 PyPy 的 WebSocket 客户端和服务器库。

## DNS 解析

- [dnspython](https://github.com/rthalley/dnspython) - 一个强大的 python DNS 工具包。
- [dnsyo](https://github.com/samarudge/dnsyo) - 对照 1500 多个全球 DNS 服务器检查您的 DNS。
- [pycares](https://github.com/saghul/pycares) - 与 c-ares 的接口。 c-ares 是一个异步执行 DNS 请求和名称解析的 C 库。

## 计算机视觉

- [OpenCV](https://github.com/Itseez/opencv) - 开源计算机视觉库。
- [SimpleCV](https://github.com/sightmachine/SimpleCV) - 简洁、易读的相机接口、图像处理、特征提取和格式转换（基于 OpenCV）。
- [mahotas](https://github.com/luispedro/mahotas) - 在 numpy 数组上运行的快速计算机视觉算法（全部用 C++ 实现）。

## 代理服务器

- [scylla](https://github.com/imWildCat/scylla) - 人类智能代理池。
- [ProxyBroker](https://github.com/constverum/Proxybroker) - 代理 [Finder |检查器 |服务器]。
- [shadowsocks](https://github.com/shadowsocks/shadowsocks) - 帮助您绕过防火墙的快速隧道代理（TCP 和 UDP 支持、用户管理 API、TCP 快速打开、Worker 和优雅重启、目标 IP 黑名单）。
- [tproxy](https://github.com/benoitc/tproxy) - tproxy 是一个基于 Gevent 的简单 TCP 路由代理（第 7 层），可让您在 Python 中配置例程逻辑。

## Whois

- [python-whois](https://github.com/joepie91/python-whois) - 用于检索和解析 WHOIS 数据的 python 模块。

## 特定网页抓取

- [twitter-scraper](https://github.com/bisguzar/twitter-scraper) - 无需身份验证即可抓取 Twitter 前端 API。
- [Ultimate-Facebook-Scraper](https://github.com/harismuneer/Ultimate-Facebook-Scraper) - 一个爬取几乎所有关于 Facebook 用户个人资料的机器人。
- [instagram-scraper](https://github.com/rarcega/instagram-scraper) - 抓取 Instagram 用户的照片和视频。

## JavaScript 引擎绑定

- [Js2Py](https://github.com/PiotrDabkowski/Js2Py) - 用 100% 纯 Python 编写的 JavaScript 到 Python 翻译器和 JavaScript 解释器。
- [v8eval](https://github.com/sony/v8eval/) - 多语言绑定到 JavaScript 引擎 V8。

## 其他 Python 列表

- [awesome-python](https://github.com/vinta/awesome-python)
- [pycrumbs](https://github.com/kirang89/pycrumbs)
- [python-github-projects](https://github.com/checkcheckzz/python-github-projects)
- [python_reference](https://github.com/rasbt/python_reference)
- [pythonidae](https://github.com/svaksha/pythonidae)
