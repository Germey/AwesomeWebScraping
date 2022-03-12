# Ruby 网页抓取

此列表包含与网页抓取和数据处理相关的 Ruby​​ 库。

- [网络请求工具](#网络请求工具)
- [网页抓取框架](#网页抓取框架)
- [HTML/XML](#HTML/XML)
- [文本处理](#文本处理)
- [特定格式处理](#特定格式处理)
- [自然语言处理](#自然语言处理)
- [浏览器自动化和仿真](#浏览器自动化和仿真)
- [多进程](#多进程)
- [异步](#异步)
- [队列](#队列)
- [电子邮件](#电子邮件)
- [URL 操作](#URL操作)
- [网页内容提取](#网页内容提取)
- [WebSocket](#WebSocket)
- [DNS 解析](#DNS解析)
- [计算机视觉](#计算机视觉)
- [地理位置](#地理位置)
- [其他 Ruby 列表](#其他Ruby列表)

## 网络请求工具

- [httparty](https://github.com/jnunemaker/httparty) 让 http 再次变得有趣！
- [http](https://github.com/tarcieri/http) 用于发出 HTTP 请求的简单 Ruby DSL。
- [excon](https://github.com/excon/excon) 适用于 Ruby 的可用、快速、简单的 HTTP(S) 1.1。
- [nestful](https://github.com/maccman/nestful) 带有健全 API 的简单 Ruby HTTP/REST 客户端。
- [EM-HTTP-Request](https://github.com/igrigorik/em-http-request) - 基于 EventMachine 的异步 HTTP 客户端。
- [excon](https://github.com/excon/excon) - 可用、快速、简单的 Ruby HTTP 1.1。它作为通用 HTTP(s) 客户端工作得很好，特别适合在 API 客户端中使用。
- [Faraday](https://github.com/lostisland/faraday) - 一个 HTTP 客户端库，在许多适配器（例如 Net::HTTP）上提供通用接口，并在处理请求时包含 Rack 中间件的概念/响应周期。
- [Http Client](https://github.com/nahi/httpclient) - 在 Ruby 中提供类似于 libwww-perl (LWP) 的功能。
- [HTTP](https://github.com/httprb/http.rb) - HTTP Gem：用于发出 HTTP 请求的简单 Ruby DSL。
- [Http-2](https://github.com/igrigorik/http-2) - HTTP/2 协议的纯 Ruby 实现。
- [Patron](https://github.com/toland/patron) - Patron 是一个基于 libcurl 的 Ruby HTTP 客户端库。
- [RESTClient](https://github.com/rest-client/rest-client) - Ruby 的简单 HTTP 和 REST 客户端，灵感来自用于指定操作的微框架语法。
- [Savon](https://github.com/savonrb/savon) - Savon 是 Ruby 编程语言的 SOAP 客户端。
- [Sawyer](https://github.com/lostisland/sawyer) - HTTP 的秘密用户代理，建立在 Faraday 之上。
- [Spyke](https://github.com/balvig/spyke) - 以类似 ActiveRecord 的方式与 REST 服务交互。
- [Typhoeus](https://github.com/typhoeus/typhoeus) - Typhoeus 包装了 libcurl 以便发出快速可靠的请求。
- [Mechanize](https://github.com/sparklemotion/mechanize) - Mechanize 是一个 ruby​​ 库，可以轻松实现自动化 Web 交互。

## 网页抓取框架

- [upton](https://github.com/propublica/upton) - 一个包含电池的框架，用于轻松进行网络抓取。
- [Wombat](https://github.com/felipecsl/wombat) - 具有优雅 DSL 的 Web 抓取工具，可解析网页中的结构化数据。
- [Anemone](https://github.com/chriskite/anemone) - 网络蜘蛛框架，可以蜘蛛域并收集有关它访问的页面的有用信息。
- [Spidr](https://github.com/postmodern/spidr) - 多功能 Ruby 网络爬虫库，可以爬取一个站点、多个域、某些链接或无限。 Spidr 旨在快速且易于使用。
- [kimuraframework](https://github.com/vifreefly/kimuraframework) - 用 Ruby 编写的现代网络抓取框架，可与 Headless Chromium/Firefox、PhantomJS 或简单的 HTTP 请求一起使用，并允许抓取并与 JavaScript 交互呈现的网站。
- [arachnid2](https://github.com/samnissen/arachnid2) 一个简单、快速、无框架的爬虫，具有合理的默认值和许多选项。抓取页面并直接针对 Typhoeus 响应或 Watir 浏览器运行您的代码。

## HTML/XML

- [nokogiri](https://github.com/sparklemotion/nokogiri) - 支持 XPath 和 CSS 选择器的 HTML、XML、SAX 和 Reader 解析器。
- [loofah](https://github.com/flavorjones/loofah) - 基于 Nokogiri 的 HTML/XML 操作和清理。
- [HappyMapper](https://github.com/dam5s/happymapper) - 允许您解析 XML 数据并将其快速轻松地转换为 ruby​​ 数据结构。
- [HTML::Pipeline](https://github.com/jch/html-pipeline) - HTML 处理过滤器和实用程序。
- [Oga](https://github.com/YorickPeterse/oga) - 用 Ruby 编写的 XML/HTML 解析器。 Oga 不需要 libxml 等系统库，在各种平台上安装更容易、更快捷。
- [Ox](https://github.com/ohler55/ox) - 一个快速的 XML 解析器和对象编组器。
- [ROXML](https://github.com/Empact/roxml) - 使用注解样式类方法在 Ruby 和 XML 之间自定义映射和双向编组。
- [equivalent-xml](https://github.com/mbklein/equivalent-xml) - Nokogiri::XML 的 XML 文档等效性的简单测试。

## 文本处理

_用于解析和操作纯文本的库。_

- 一般的
  - [Kiba](https://github.com/thbar/kiba) - 用于编写可靠、简洁、经过良好测试和可维护的数据处理代码的库。
  - [diffy](https://github.com/samg/diffy) - 一种从两个字符串或文件生成差异的便捷方法。
  - [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) - 在一个字符串中查找很多种常见的信息。
- 电话号码
  - [GlobalPhone](https://github.com/sstephenson/global_phone) - 使用 Google 的 libphonenumber 数据库在 Ruby 中解析、验证和格式化电话号码。
- 国家名称
  - [i18n_data](https://github.com/grosser/i18n_data) - 国家/语言名称和 2 字母代码对，85 种语言，用于国家/语言 i18n。
  - [normalize_country](https://github.com/sshaw/normalize_country) - 将国家名称和代码转换为标准，包括 XML、CSV 和 DB 的转换程序。
- 用户代理
  - [设备检测器](https://github.com/podigee/device_detector) - 一个精确和快速的用户代理解析器和设备检测器，由最大和最新的用户代理数据库支持。
- 通用解析器
  - [Parslet](http://kschiess.github.io/parslet/) - 一个小型 Rub​​y 库，用于以 PEG（解析表达式语法）方式构建解析器。
  - [Treetop](https://github.com/cjheath/treetop) - PEG（解析表达式语法）解析器。
  - [rley](https://github.com/famished-tiger/Rley) - Ruby gem 实现基于 Earley 算法的通用上下文无关语法解析器。
- 约会时间
  - [Chronic](https://github.com/mojombo/chronic) - 用纯 Ruby 编写的自然语言日期/时间解析器。
  - [yymmdd](https://github.com/sshaw/yymmdd) - 用于惯用日期解析和格式化的微型 DSL。
  - [Chronic Between](https://github.com/jrobertson/chronic_between) - 用于日期和时间范围的简单 Ruby 自然语言解析器。
  - [Chronic Duration](https://github.com/hpoydar/chronic_duration) - 一个简单的 Ruby 自然语言解析器，用于计算经过的时间。
  - [Kronic](https://github.com/xaviershay/kronic) - 一个用于解析和格式化人类可读日期的简单库。
  - [Nickel](https://github.com/iainbeeston/nickel) - 从自然措辞的文本中提取日期、时间和消息信息。
  - [Tickle](https://github.com/yb66/tickle) - 用于重复事件的自然语言解析器
- 人名
  - [nameable](https://github.com/chorn/nameable) - 一个 Ruby gem，提供人名的解析和输出，以及性别和种族匹配。
- N-gram
  - [N-Gram](https://github.com/reddavis/N-Gram) - Ruby 中的 N-Gram 生成器。
  - [ngram](https://github.com/tkellen/ruby-ngram) - 将单词和短语分解成 ngram。
  - [raingrams](https://github.com/postmodern/raingrams) - 一个用 Ruby 编写的灵活且通用的 ngrams 库。
- 文字相似度
  - [FuzzyMatch](https://github.com/seamusabshere/fuzzy_match) - 基于字符串相似度和正则表达式规则。
  - [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) - ruby​​ 的模糊字符串匹配库。
  - [FuzzyTools](https://github.com/brianhempel/fuzzy_tools) - 内存中 TF-IDF 模糊文档查找，带有针对不同记录链接数据集进行调整的精美默认标记器，便于开箱即用。
  - [Going the Distance](https://github.com/schneems/going_the_distance) - 包含执行各种距离计算的脚本。
  - [hotwater](https://github.com/colinsurprenant/hotwater) - 快速 Ruby FFI 字符串编辑距离算法。
  - [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) - 快速字符串编辑距离计算，使用 Damerau-Levenshtein 算法。
  - [TF-IDF](https://github.com/reddavis/TF-IDF) - 词频 - Ruby 中的逆文档频率。
  - [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) - 使用 tf\*idf 计算文本之间的相似度。

## 特定格式处理

_用于解析和处理特定文本格式的库。_

- 一般的
  - [markup](https://github.com/github/markup) — 将 mardown、rst、creole 等转换为 HTML 的 GitHub 库。
- 办公室
  - [Yomu](https://github.com/Erol) - 从文件和文档（.doc、.docx、.pages、.odt、.rtf、.pdf）中读取文本和元数据。
  - [电子表格](https://github.com/zdavatz/spreadsheet) - 电子表格库旨在读取和写入电子表格文档。
  - [roo](https://github.com/Empact/roo) - Roo 实现了所有电子表格类型的读取权限和 Google 电子表格的读取/写入权限。
  - [google-spreadsheet-ruby](https://github.com/gimite/google-spreadsheet-ruby) - 这是一个读/写谷歌电子表格的库。
  - [rubyXL](https://github.com/weshatheleopard/rubyXL) - ruby​​XL 是一个允许解析、创建和操作 Microsoft Excel (.xlsx/.xlsm) 文档。
  - [remote_table](https://github.com/seamusabshere/remote_table) - 打开本地或远程 XLSX、XLS、ODS、CSV（逗号分隔）、TSV（制表符分隔）、其他定界、固定宽度文件和 Google 文档。
  - [sheets](https://github.com/bspaulding/Sheets) - 以原生 ruby​​ 格式轻松处理电子表格。
  - [工作簿](https://github.com/murb/workbook) - 工作簿包含工作簿，就像在表格中一样，包含行、包含单元格、读取/写入 excel、ods 和 csv 以及制表符分隔的文件。
  - [oxcelix](https://github.com/gbiczo/oxcelix) - 一个快速的 Excel 2007/2010 (.xlsx) 文件解析器，它返回矩阵对象的集合。
  - [wrap_excel](https://github.com/tomiacannondale/wrap_excel) - WrapExcel 是对 win32ole 的封装，方便使用 ruby 进行 Excel 操作。
- libpcap
  - [PacketFul](https://github.com/packetfu/packetfu) - 用于读取和写入数据包到接口或 libpcap 格式文件的库。
- JSON
  - [JsonCompare](https://github.com/a2design-company/json-compare) - 返回两个 JSON 文件之间的差异。
  - [JSON](https://github.com/flori/json) — 包括 JSON 的纯 Ruby 和 C 实现。
  - [JSON::Stream](https://github.com/dgraham/json-stream) — 一个流式 JSON 解析器，可生成类似 SAX 的事件。
  - [YAJL](https://github.com/brianmario/yajl-ruby) — Ruby 的流式 JSON 解析和编码库（C 绑定到 YAJL）。
  - [OJ](https://github.com/ohler55/oj) — 优化 JSON，顾名思义，是为了提供速度优化的 JSON 处理而编写的。到目前为止，它已经实现了这一点，并且比任何其他 Ruby JSON 解析器快大约 2 倍，并且在序列化 JSON 方面快 3 倍或更多倍。
- Markdown
  - [kramdown](https://github.com/gettalong/kramdown) - Kramdown 是另一种降价解析器，但速度快，纯 Ruby，使用严格的语法定义并支持几个常见的扩展。
  - [Maruku](https://github.com/bhollis/maruku) - 一个纯 Ruby Markdown-superset 解释器。
  - [Redcarpet](https://github.com/vmg/redcarpet) - 一个快速、安全和可扩展的 Markdown 到 (X)HTML 解析器。
- Feed/RSS
  - [Feed normalizer](https://github.com/aasmith/feed-normalizer) - Atom 和 RSS 解析器的可扩展 Ruby 包装器。
  - [Feedjira](https://github.com/feedjira/feedjira) - 一个提要获取和解析库。
  - [Ratom](https://github.com/seangeo/ratom) - 一个快速的、基于 libxml 的 Ruby Atom 库。
  - [Simple rss](https://github.com/cardmagic/simple-rss) - 一个简单、灵活、可扩展、自由的 RSS 和 Atom 阅读器。
- BSON
  - [BSON](https://github.com/mongodb/bson-ruby) — BSON 规范 (2.0.0+) 的 Ruby 实现，http://bsonspec.org
- 消息包
  - [MessagePack](https://github.com/msgpack/msgpack-ruby) — 一种高效的二进制序列化格式。它允许您在 JSON 等多种语言之间交换数据，但速度更快、体积更小。例如，小整数（如标志或错误代码）被编码为单个字节，而典型的短字符串除了字符串本身之外只需要一个额外的字节。请参阅 http://msgpack.org
- Protobuf
  - [Protobuf](https://github.com/localshred/protobuf) — Protocol Buffers 的 Ruby 实现。
- RDF
  - [rdf](https://github.com/ruby-rdf/rdf) - 用于处理资源描述框架 (RDF) 数据的纯 Ruby 库

## 自然语言处理

_用于处理人类语言的库。_

- 一般的
  - [Treat](https://github.com/louismullie/treat) - Treat 是 Ruby 中用于自然语言处理和计算语言学的工具包。
  - [Pragmatic Segmenter](https://github.com/diasks2/pragmatic_segmenter) - Pragmatic Segmenter 是一个基于规则的句子边界检测 gem，可以在多种语言中开箱即用。
  - [文本](https://github.com/threedaymonk/text) - 文本算法的集合，包括 Levenshtein 距离、Metaphone、Soundex 2、Porter 词干和白色相似度。
  - [whatlanguage](https://github.com/peterc/whatlanguage) - 一个用于 Ruby 的语言检测库，它使用布隆过滤器来提高速度。
  - [nlp](https://github.com/knife/nlp) - 波兰语的 NLP 工具。
  - [NlpToolz](https://github.com/LeFnord/nlp_toolz) - 基本的 NLP 工具，主要基于 OpenNLP，此时实现了句子查找器、标记器和 POS 标记器，以及 Berkeley Parser。
  - [Open NLP (Ruby bindings)](https://github.com/louismullie/open-nlp)
  - [斯坦福核心 NLP（Ruby 绑定）](https://github.com/louismullie/stanford-core-nlp)
  - [ve](https://github.com/Kimtaro/ve) - 一个易于使用的语言框架。
  - [zipf](https://github.com/pks/zipf) - 各种 NLP 工具和库的集合。
  - [ruby-ner](https://github.com/mblongii/ruby-ner) - 使用斯坦福 NER 和 Ruby 进行命名实体识别。
  - [ruby-nlp](https://github.com/tiendung/ruby-nlp) - 用于斯坦福 Pos-Tagger 和名称实体识别器的 Ruby 绑定。
  - [linkparser](https://github.com/ged/linkparser) - CMU 链接的 Abiword 版本的 Ruby 绑定语法，英语的句法解析器。
- 词性标注器
  - [engtagger](https://github.com/yohasebe/engtagger) - 英语词性标注库； Lingua::EN::Tagger 的 Ruby 端口。
  - [rbtagger](http://rbtagger.rubyforge.org/) - 一个简单的基于 ruby​​ 规则的词性标注器。
  - [TreeTagger for Ruby](https://github.com/LeFnord/rstt) - Helmut Schmid 的 TreeTagger 基于 Ruby 的包装器。
- 句子分割
  - [语用分段器](https://github.com/diasks2/pragmatic_segmenter)
  - [Punkt 分段器](https://github.com/lfcipriani/punkt-segmenter)
  - [TactfulTokenizer](https://github.com/zencephalon/Tactful_Tokenizer)
  - [手术刀](https://github.com/louismullie/scalpel)
  - [SRX 英文](https://github.com/apohllo/srx-english)
- 词干
  - [希腊词干分析器](https://github.com/skroutz/greek_stemmer) - 希腊词干分析器。
  - [Ruby-Stemmer](https://github.com/aurelian/ruby-stemmer) - Ruby-Stemmer 向 Ruby 公开 SnowBall API。
  - [土耳其语词干分析器](https://github.com/skroutz/turkish_stemmer) - 土耳其语词干分析器。
  - [uea-stemmer](https://github.com/ealdent/uea-stemmer) - 用于搜索和索引的保守词干分析器。
- 总结
  - [Epitome](https://github.com/McFreely/epitome) - 一个让你的文字更短的小宝石； Lexrank 算法的实现
  - [ots](https://github.com/deepfryed/ots) - 用于打开文本摘要器的 Ruby 绑定。
  - [summarize](https://github.com/ssoper/summarize) - Open Text Summarizer 的 Ruby C 包装器。
- 分词器
  - [Jieba](https://github.com/mimosa/jieba-jruby) - 中文分词器和分词器(jRuby)。
  - [MeCab](https://github.com/markburns/mecab) - 日本形态分析仪 [[MeCab Heroku buildpack](https://github.com/diasks2/heroku-buildpack-mecab)]
  - [NLP Pure](https://github.com/parhamr/nlp-pure) - 在纯 Ruby 中实现的自然语言处理算法具有最小的依赖关系。
  - [rseg](https://github.com/yzhang/rseg) - 纯 Ruby 中的中文分词 (中文分词) 例程
  - [thailang4r](https://github.com/veer66/thailang4r) - 泰语分词器。
  - [tiny_segmenter](https://github.com/6/tiny_segmenter) - TinySegmenter.js 的 Ruby 端口，用于标记日语文本。
  - [tokenizer](https://github.com/arbox/tokenizer) - 一个简单的多语言分词器。
- 字数
  - [wc](https://github.com/thesp0nge/wc) - 用于计算给定文本中单词出现次数的 ruby​​gem。
  - [word_count](https://github.com/AtelierConvivialite/word_count) - Ruby 中字符串和哈希的字数计数器。
  - [字数分析器](https://github.com/diasks2/word_count_analyzer) - 根据使用的工具分析可能导致字数差异的文本潜在区域的字符串。
  - [WordsCounted](https://github.com/abitdodgy/words_counted) - 高度可定制的 Ruby 文本分析器。

## 浏览器自动化和仿真

- [selenium](https://github.com/seleniumhq/selenium) - 浏览器自动化框架和生态系统。
- [Watir](https://github.com/watir/watir) - 基于 WebDriver 的 Ruby 绑定构建的 Watir 实现。
- [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) - 用于无头 WebKit 的 Capybara 驱动程序，用于测试 JavaScript Web 应用程序。
- [poltergeist](https://github.com/teampoltergeist/poltergeist) - Capybara 的 PhantomJS 驱动程序。

## 多处理

- [赛璐珞](https://github.com/celluoid/celluloid) - 基于 Actor 的 Ruby 并发对象框架。
- [并行](https://github.com/grosser/parallel) - 在并行进程（> 使用所有 CPU）或线程（> 加速阻塞操作）中运行任何代码。
- [Concurrent Ruby](https://github.com/ruby-concurrency/concurrent-ruby) - 现代并发工具，包括代理、期货、承诺、线程池、监督者等。
- [childprocess](https://github.com/jarib/childprocess) - 用于管理子进程的跨平台 ruby​​ 库。
- [forkoff](https://github.com/ahoward/forkoff) - 用于 ruby​​ 的脑死简单并行处理。
- [posix-spawn](https://github.com/rtomayko/posix-spawn) - Fast Process::spawn for Rubys >= 1.8.7 基于 posix_spawn() 系统接口。
- [thread](https://github.com/meh/ruby-thread) — 线程库的扩展（包括线程池）。
- [Sprawling](https://github.com/dreikanter/ruby-bookmarks) — 为 Rails 生成 gem，以轻松分叉或线程化长时间运行的代码块。

## 异步

_用于异步网络编程的库。_

- [EventMachine](https://github.com/eventmachine/eventmachine) - 事件驱动 I/O 和轻量级并发库。

## 队列

- [Resque](https://github.com/resque/resque) 一个 Redis 支持的 Ruby 库，用于创建后台作业，将它们放置在多个队列中。
- [Delayed::Job](https://github.com/tobi/delayed_job) — 数据库支持的异步优先级队列。
- [Qu](https://github.com/bkeepers/qu) 一个用于排队和处理后台作业的 Ruby 库。
- [Sidekiq](http://sidekiq.org) - 一个全功能的 Ruby 后台处理框架。它旨在简单地与 ​​ 任何现代 Rails 应用程序集成复制和比其他现有解决方案更高的性能。
- [Sneakers](https://github.com/jondot/sneakers) - Ruby 和 RabbitMQ 的快速后台处理框架。
- [Backburner](https://github.com/nesquena/backburner) - Backburner 是一个 beanstalkd 驱动的作业队列，可以处理大量的作业。
- [Delayed::Job](https://github.com/collectiveidea/delayed_job) - 数据库支持的异步优先级队列。
- [Que](https://github.com/chanks/que) - 一个 Ruby 作业队列，它使用 PostgreSQL 的咨询锁来提高速度和可靠性。
- [Shoryuken](https://github.com/phstc/shoryuken) - 一个超高效的基于 AWS SQS 线程的 Ruby 消息处理器。
- [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) - 使用赛璐珞的单进程后台处理库。目标是成为 Sidekiq 的弟弟。

## 电子邮件

_用于解析电子邮件的库。_

- [mail](https://github.com/mikel/mail) 一个真正的 Ruby 邮件库

## URL 操作

_用于解析 URL 的库。_

- [addressable](https://github.com/sporkmonger/addressable) - Addressable 是 URI 实现的替代品，它是 Ruby 标准库的一部分。它更符合 RFC 3986、RFC 3987 和 RFC 6570（第 4 级），提供对 IRI 和 URI 模板的支持。

## 网页内容提取

_用于提取网页内容的库。_

- [Metainspector](https://github.com/jaimeiniesta/metainspector) - 抓取给定的 URL，并返回其标题、元描述、元关键字、包含所有链接的数组、其中的所有图像等。
- [LinkThumbnailer](https://github.com/gottfrois/link_thumbnailer) - 从给定 URL 生成缩略图图像和视频的 Ruby gem。很像带有链接预览的流行社交网站。
- [docsplit](http://documentcloud.github.io/docsplit/) - Docsplit 是一个命令行实用程序和 Ruby 库，用于将文档拆分为其组成部分。
- [Ruby Readability](https://github.com/cantino/ruby-readability) - 提取网页主要可读内容的工具。

## WebSocket

_使用 WebSocket 的库。_

- [em-websocket](https://github.com/igrigorik/em-websocket) - 基于 EventMachine 的 WebSocket 服务器。
- [Faye](http://faye.jcoglan.com/ruby.html) - 一组工具，用于在 Web 客户端之间进行简单的发布-订阅消息传递。
- [Firehose](https://github.com/polleverywhere/firehose) - 构建实时 Ruby Web 应用程序。
- [Slanger](https://github.com/stevegraham/slanger) - 与 Pusher 库兼容的开放式 Pusher 实现。

## DNS 解析

- [em-resolve-replace](https://github.com/mperham/em-resolv-replace) - EventMachine-aware 纯 Ruby DNS 解析。
- [Celluloid::DNS](https://github.com/celluloid/celluloid-dns) - 一个高性能的 DNS 客户端解析器和服务器，可以很容易地集成到其他项目中或用作独立的守护进程。它是从 RubyDNS 派生的，现在根据这个库实现。

## 计算机视觉

- [ruby-opencv](https://github.com/ruby-opencv/ruby-opencv) - Ruby 的 OpenCV 包装器。

## 地理位置

- [geocoder](https://github.com/alexreisner/geocoder) - 一个完整的 Ruby 地理编码解决方案。借助 Rails，它添加 ​​ 了地理编码（按街道或 IP 地址）、反向地理编码（根据给定坐标查找街道地址）和距离查询。
- [Geokit](https://github.com/geokit/geokit) - Geokit gem 提供地理编码和距离/航向计算。
- [geoip](https://github.com/cjheath/geoip) - 在 GeoIP 数据库中搜索给定的主机或 IP 地址，并返回有关分配 IP 地址的国家、城市、ISP 和其他信息信息。

## 其他 Ruby 列表

- [awesome-ruby](https://github.com/markets/awesome-ruby/blob/master/README.md) 来自 Markets。
- [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby) 来自 Sdogruyol。
- [ruby-nlp](https://github.com/diasks2/ruby-nlp) - 自然语言处理 (NLP) Ruby 库、工具和软件的集合。
