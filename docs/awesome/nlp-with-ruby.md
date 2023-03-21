<div class="github-widget" data-repo="arbox/nlp-with-ruby"></div>
<img src="https://raw.githubusercontent.com/arbox/nlp-with-ruby/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[[RubyML](https://github.com/arbox/machine-learning-with-ruby) |
 [RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]



&gt; 在 Ruby 中进行文本处理的有用资源

这个精选列表包括 [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
有关文本计算处理的资源、图书馆、信息源
在人类语言中 [Ruby programming language](https://github.com/arbox/nlp-with-ruby/blob/master/ruby).
该字段通常被称为
[NLP](https://en.wikipedia.org/wiki/Natural_language_processing),
[Computational Linguistics](https://en.wikipedia.org/wiki/Computational_linguistics),
[HLT](https://en.wikipedia.org/wiki/Language_technology) （人类语言技术）
并可与
[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence),
[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning),
[Information Retrieval](https://en.wikipedia.org/wiki/Information_retrieval),
[Text Mining](https://en.wikipedia.org/wiki/Text_mining),
[Knowledge Extraction](https://en.wikipedia.org/wiki/Knowledge_extraction)
及其他相关学科.

此列表来自我们在语言模型和 NLP 工具方面的日常工作.
Read [why](https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md) 这个列表很棒. 我们 [FAQ](https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md) 描述了
您可能感兴趣的重要决定和有用的答案.

:sparkles: 每个 [contribution](#contributing) 欢迎！ 通过pull添加链接
请求或创建问题以开始讨论.

跟着我们 [Twitter](https://twitter.com/NonWebRuby)
and please spread the word using the `#RubyNLP` hash tag!

<!-- nodoc -->

<!-- toc -->


<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

请帮助我们填写此部分！  ：笑脸：

## NLP Pipeline Subtasks

NLP 管道以纯文本开始.

### Pipeline Generation

- [composable_operations](https://github.com/t6d/composable_operations) -
  操作管道的定义框架.
- [ruby-spark](https://github.com/ondra-m/ruby-spark) -
  具有易于理解的 DSL 的 Spark 绑定.
- [phobos](https://github.com/phobos/phobos) -
  简化的 Ruby 客户端 [Apache Kafka](https://kafka.apache.org/).
- [parallel](https://github.com/grosser/parallel) -
  用于在多个 CPU 或多个线程中并行执行的主管.
- [pwrake](https://github.com/masa16/pwrake) -
  Rake 扩展以并行运行本地和远程任务.

### Multipurpose Engines

- [open-nlp](https://github.com/louismullie/open-nlp) -
  Ruby 绑定 [OpenNLP](https://opennlp.apache.org/) 工具包.
- [stanford-core-nlp](https://github.com/louismullie/stanford-core-nlp) -
  斯坦福大学的 Ruby 绑定 [CoreNLP](https://github.com/stanfordnlp/CoreNLP) 工具.
- [treat](https://github.com/louismullie/treat) -
  Ruby 的自然语言处理框架（如 [NLTK](http://www.nltk.org/) 对于 Python）.
- [nlp_toolz](https://github.com/LeFnord/nlp_toolz) -
  包装一些 [OpenNLP](https://opennlp.apache.org/) 类和
  原本 [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser).
- [open_nlp](https://github.com/hck/open_nlp) -
  JRuby 绑定 [OpenNLP](https://opennlp.apache.org/) 工具包.
- [ruby-spacy](https://github.com/yohasebe/ruby-spacy) —
  spaCy NLP 库的包装器模块，通过 [PyCall](https://github.com/mrkn/pycall.rb).

#### On-line APIs

- [alchemyapi_ruby](https://github.com/alchemyapi/alchemyapi_ruby) -
  适用于 AlchemyAPI/Bluemix 的旧版 Ruby SDK.
- [wit-ruby](https://github.com/wit-ai/wit-ruby) -
  Ruby 客户端库 [Wit.ai](https://wit.ai/) 语言理解平台.
- [wlapi](https://github.com/arbox/wlapi) - Ruby 客户端库
  [Wortschatz Leipzig](http://wortschatz.uni-leipzig.de/de) 网页服务.
- [monkeylearn-ruby](https://github.com/monkeylearn/monkeylearn-ruby) - 情绪
  分析、主题建模、语言检测、命名实体识别
  基于 Ruby 的 Web API 客户端.
- [google-cloud-language](https://github.com/googleapis/google-cloud-ruby/tree/master/google-cloud-language) -
  Google 的 Ruby 自然语言服务 API.

### Language Identification

语言识别是每个 NLP 管道中的第一个关键步骤之一.

- [scylla](https://github.com/hashwin/scylla) -
  语言分类和识别.

### Segmentation

标记化、单词和句子边界检测和消歧的工具.

- [tokenizer](https://github.com/arbox/tokenizer) -
  简单的多语言分词器.
  <sup>[[tutorial](https://github.com/arbox/nlp-with-ruby/blob/master/tutorials/tokenizer.md)]</sup>
- [pragmatic_tokenizer](https://github.com/diasks2/pragmatic_tokenizer) -
  将字符串拆分为标记的多语言分词器.
- [nlp-pure](https://github.com/parhamr/nlp-pure) -
  在纯 Ruby 中实现的自然语言处理算法具有最小的依赖性.
- [textoken](https://github.com/manorie/textoken) -
  简单且可自定义的文本标记化库.
- [pragmatic_segmenter](https://github.com/diasks2/pragmatic_segmenter) -
  使用许多 cookie 的词边界消歧.
- [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter) -
  Punkt Segmenter 的纯 Ruby 实现.
- [tactful_tokenizer](https://github.com/zencephalon/Tactful_Tokenizer) -
  用于不同语言的基于 RegExp 的分词器.
- [scapel](https://github.com/louismullie/scalpel) -
  句子边界消歧工具.

### Lexical Processing

#### Stemming

词干提取是信息检索中用来描述信息检索过程的术语
将字形简化为某种基本表示形式. 应区分词干
from [Lemmatization](#lemmatization) 因为“茎”不一定有
语言动机.

- [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) -
  Ruby-Stemmer 将 SnowBall API 公开给 Ruby.
- [uea-stemmer](https://github.com/ealdent/uea-stemmer) -
  用于搜索和索引的保守词干分析器.

#### Lemmatization

词形还原被认为是寻找单词基本形式的过程. 引理
经常收录在字典中.

- [lemmatizer](https://github.com/yohasebe/lemmatizer) -
  基于 WordNet 的英文文本 Lemmatizer.

#### Lexical Statistics: Counting Types and Tokens

- [wc](https://github.com/thesp0nge/wc) -
  计算文本中单词出现次数的工具.
- [word_count](https://github.com/AtelierConvivialite/word_count) -
  `String` 和 `Hash` 对象的单词计数器.
- [words_counted](https://github.com/abitdodgy/words_counted) -
  纯 Ruby 库使用不同的自定义选项统计单词.

#### Filtering Stop Words

- [stopwords-filter](https://github.com/brenes/stopwords-filter) - 过滤和
  基于 SnowBall lemmatizer 的停止词词典.

### Phrasal Level Processing

- [n_gram](https://github.com/reddavis/N-Gram) -
  N-Gram 生成器.
- [ruby-ngram](https://github.com/tkellen/ruby-ngram) -
  将单词和短语分解为 ngram.
- [raingrams](https://github.com/postmodern/raingrams) -
  用纯 Ruby 编写的灵活且通用的 ngrams 库.

### Syntactic Processing

#### Constituency Parsing

- [stanfordparser](https://rubygems.org/gems/stanfordparser) -
  斯坦福解析器的基于 Ruby 的包装器.
- [rley](https://github.com/famished-tiger/Rley) -
  纯 Ruby 实现 [Earley](https://en.wikipedia.org/wiki/Earley_parser)
  上下文无关选区语法的解析算法.
- [rsyntaxtree](https://github.com/yohasebe/rsyntaxtree) -
  基于 Ruby 语法树的可视化 [RMagick](https://github.com/rmagick/rmagick).
  <sup>[dep: [ImageMagick](#imagemagick)]</sup>

### Semantic Analysis

- [amatch](https://github.com/flori/amatch) -
  字符串之间的五种距离类型集（包括 Levenshtein、Sellers、Jaro-Winkler、“对距离”）.
- [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) -
  使用 Damerau-Levenshtein 算法计算编辑距离.
- [hotwater](https://github.com/colinsurprenant/hotwater) -
  快速 Ruby FFI 字符串编辑距离算法.
- [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) -
  快速字符串编辑距离计算，使用 Damerau-Levenshtein 算法.
- [tf_idf](https://github.com/reddavis/TF-IDF) -
  纯 Ruby 中的词频/逆文档频率.
- [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) -
  使用 TF/IDF 计算文本之间的相似度.

### Pragmatical Analysis
- [SentimentLib](https://github.com/nzaillian/sentiment_lib) -
  简单的可扩展情感分析 gem.

## High Level Tasks

### Spelling and Error Correction

- [gingerice](https://github.com/subosito/gingerice) -
  拼写和语法更正通过 [Ginger](https://www.gingersoftware.com/) 应用程序接口.
- [hunspell-i18n](https://github.com/romanbsd/hunspell) -
  Ruby 绑定到标准 [Hunspell](https://hunspell.github.io/) 拼写检查器.
- [ffi-hunspell](https://github.com/postmodern/ffi-hunspell) -
  基于 FFI 的 Ruby 绑定 [Hunspell](https://hunspell.github.io/).
- [hunspell](https://github.com/segabor/Hunspell) -
  Ruby 绑定到 [Hunspell](https://hunspell.github.io/) 通过 Ruby C API.

### Text Alignment

- [alignment](https://github.com/povilasjurcys/alignment) -
  双语文本对齐例程（Gale-Church 实现）.

### Machine Translation

- [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
  谷歌 API 红宝石客户端.
- [microsoft_translator](https://github.com/ikayzo/microsoft_translator) -
  微软翻译器 API 的 Ruby 客户端.
- [termit](https://github.com/pawurb/termit) -
  谷歌翻译在您的终端中进行语音合成.
- [zipf](https://github.com/pks/zipf) -
  BLEU 和其他基本算法的实现.

### Sentiment Analysis

- [stimmung](https://github.com/pachacamac/stimmung) -
  语义极性基于
  [SentiWS](http://wortschatz.uni-leipzig.de/en/download) 词典.

### Numbers, Dates, and Time Parsing

- [chronic](https://github.com/mojombo/chronic) -
  纯 Ruby 自然语言日期解析器.
- [chronic_between](https://github.com/jrobertson/chronic_between) -
  用于日期和时间范围的简单 Ruby 自然语言解析器.
- [chronic_duration](https://github.com/henrypoydar/chronic_duration) -
  经过时间的纯 Ruby 解析器.
- [kronic](https://github.com/xaviershay/kronic) -
  解析和格式化人类可读日期的方法.
- [nickel](https://github.com/iainbeeston/nickel) -
  从自然措辞的文本中提取日期、时间和消息信息.
- [tickle](https://github.com/yb66/tickle) -
  用于重复发生和重复事件的解析器.
- [numerizer](https://github.com/jduff/numerizer) -
  用于英语数字表达式的 Ruby 解析器.

### Named Entity Recognition

- [ruby-ner](https://github.com/mblongii/ruby-ner) -
  使用 Stanford NER 和 Ruby 进行命名实体识别.
- [ruby-nlp](https://github.com/tiendung/ruby-nlp) -
  用于 Stanford Pos-Tagger 和名称实体识别器的 Ruby 绑定.

### Text-to-Speech-to-Text

- [espeak-ruby](https://github.com/dejan/espeak-ruby) -
  用于利用“espeak”和“lame”创建文本转语音 mp3 文件的小型 Rub​​y API.
- [tts](https://github.com/c2h2/tts) -
  使用谷歌翻译服务的文本到语音转换.
- [att_speech](https://github.com/adhearsion/att_speech) -
  AT&amp;T Speech API 上的 Ruby 包装器，用于语音到文本.
- [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) -
  Pocketsphinx 绑定.

## Dialog Agents, Assistants, and Chatbots

- [chatterbot](https://github.com/muffinista/chatterbot) -
  简单的基于 ruby​​ 的 Twitter Bot 框架，使用 OAuth 进行身份验证.
- [lita](https://github.com/litaio/lita) -
  高度可扩展的聊天操作机器人框架，使用持久存储编写 [Redis](https://redis.io/).

## Linguistic Resources

- [rwordnet](https://github.com/doches/rwordnet) -
  纯 Ruby 自包含的 API 库，用于 [Princeton WordNet®](https://wordnet.princeton.edu/).
- [wordnet](https://github.com/ged/ruby-wordnet/blob/master/README.rdoc) -
  性能调优绑定 [Princeton WordNet®](https://wordnet.princeton.edu/).

## Machine Learning Libraries

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) 算法
in pure Ruby or written in other programming languages with appropriate bindings
对于红宝石.

有关更多最新列表，请查看 [Awesome ML with Ruby][ml-with-ruby] 列表.

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  用 Ruby 支持向量机.
- [weka](https://github.com/paulgoetze/weka-jruby) -
  Weka 的 JRuby 绑定，通过 Weka 实现的不同 ML 算法.
- [decisiontree](https://github.com/igrigorik/decisiontree) -
  纯 Ruby 中的决策树 ID3 算法
  <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
- [rtimbl](https://github.com/maspwr/rtimbl) -
  来自 Timbl 框架的基于记忆的学习者.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  允许贝叶斯和其他类型分类的通用分类器模块.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  红宝石实现 [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  （潜在狄利克雷分配）用于自动主题建模和文档聚类.
- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  LIBLINEAR 的 Ruby 接口（在文本分类方面比 LIBSVM 更有效）.
- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis 支持的贝叶斯分类器.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  基于 OpenNLP Maxent 框架的字符串数据的 JRuby 最大熵分类器.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  简单朴素贝叶斯分类器.
- [nbayes](https://github.com/oasic/nbayes) -
  朴素贝叶斯的全功能 Ruby 实现.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  用于文本分类的通用机架框架.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  作为 OmniCat 分类器策略的朴素贝叶斯文本分类实现.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby 绑定到 [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [rblearn](https://github.com/himkt/rblearn) - 特征提取和交叉验证库.

## Data Visualization

请参阅 [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
[Data Science with Ruby][ds-with-ruby] 列表部分.

## Optical Character Recognition

* [tesseract-ocr](https://github.com/meh/ruby-tesseract-ocr) -
  基于 FFI 的包装器 [Tesseract OCR Engine](https://github.com/tesseract-ocr/tesseract).

## Text Extraction

- [yomu](https://github.com/yomurb/yomu) -
  用于从文件和文档中提取文本和元数据的库
  使用 [Apache Tika](https://tika.apache.org/) 内容分析工具包.

## Full Text Search, Information Retrieval, Indexing

- [rsolr](https://github.com/rsolr/rsolr) -
  Ruby 和 Rails 客户端库 [Apache Solr](http://lucene.apache.org/solr/).
- [sunspot](https://github.com/sunspot/sunspot) -
  以 Rails 为中心的客户端 [Apache Solr](http://lucene.apache.org/solr/).
- [thinking-sphinx](https://github.com/pat/thinking-sphinx) -
  [Active Record](https://guides.rubyonrails.org/active_record_basics.html)
  使用插件 [Sphinx](http://sphinxsearch.com/) 在（不仅）基于 Rails 的项目中.
- [elasticsearch](https://github.com/elastic/elasticsearch-ruby/tree/master/elasticsearch) -
  Ruby 客户端和 API [Elasticsearch](https://www.elastic.co/).
- [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) -
  Ruby 和 Rails 集成 [Elasticsearch](https://www.elastic.co/).
- [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
  Ruby API 库用于 [Google](https://developers.google.com/api-client-library/ruby/) 服务.

## Language Aware String Manipulation

用于语言感知字符串操作的库，即搜索、模式匹配、
需要有关信息的大小写转换、转码、正则表达式
底层语言.

- [fuzzy_match](https://github.com/seamusabshere/fuzzy_match) -
  模糊字符串与距离度量和正则表达式的比较.
- [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) -
  Ruby 的模糊字符串匹配库.
- [active_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) -
  RoR `ActiveSupport` gem 有各种可以处理大小写的字符串扩展.
- [fuzzy_tools](https://github.com/brianhempel/fuzzy_tools) -
  Ruby 中的模糊搜索工具集已针对准确性进行了调整.
- [u](http://disu.se/software/u-1.0/) -
  U 扩展了 Ruby 的 Unicode 支持.
- [unicode](https://github.com/blackwinter/unicode) -
  Unicode 规范化库.
- [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) -
  在一个字符串中查找很多种常见的信息.
- [regexp-examples](https://github.com/tom-lord/regexp-examples) -
  生成与给定正则表达式匹配的字符串.
- [verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) -
  使困难的正则表达式变得简单.
- [translit_kit](https://github.com/AnalyzePlatypus/TranslitKit) -
  将希伯来语和意第绪语文本音译为拉丁字符.
- [re2](https://github.com/mudge/re2) -
  用于文本挖掘和文本提取的高速正则表达式库.
- [regex_sample](https://github.com/mochizukikotaro/regex_sample) -
  从给定的正则表达式生成样本字符串.
- [iuliia](https://github.com/adnikiforov/iuliia-rb) —
  以多种可能的方式将西里尔字母音译为拉丁字母（由 [reference implementation](https://github.com/nalgeon/iuliia)).

## Articles, Posts, Talks, and Presentations

- 2019
  - _使用 Ruby 从图像中提取文本_ by [aonemd](https://twitter.com/aonemd)
    <sup>[[post](https://aonemd.github.io/blog/extracting-text-from-images-using-ruby) |
    [code](https://gist.github.com/aonemd/7bb3c4760d9e47a9ce8e270198cb40a0)]</sup>
- 2018
  - _自然语言处理和推文情感分析_ by [Cassandra Corrales](https://twitter.com/casita305)
    <sup>[[post](https://medium.com/@cmcorrales3/natural-language-processing-and-tweet-sentiment-analysis-fa1edbb5ddd5)]</sup>
- 2017
  - _Google NLP API 与 Ruby 相遇_作者： [Aja Hammerly](https://twitter.com/the_thagomizer)
    <sup>[[post](http://www.thagomizer.com/blog/2017/04/13/the-google-nlp-api-meets-ruby.html)]</sup>
  -_语法不是一切：Rubyists 的 NLP_作者 [Aja Hammerly](https://twitter.com/the_thagomizer)
    <sup>[[slides](http://www.thagomizer.com/files/NLP_RailsConf2017.pdf)]</sup>
  -_JRuby 上的科学计算_作者： [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
  - _Ruby 中的 Unicode 规范化_ by [Starr Horne](https://twitter.com/starrhorne)
    <sup>[[post](https://blog.honeybadger.io/ruby_unicode_normalization/)]</sup>
- 2016
  -_在 Ruby 中快速创建 Telegram 机器人_作者： [Ardian Haxha](https://twitter.com/ArdianHaxha)
    <sup>[[tutorial](https://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
  -_深度学习：Ruby 开发人员简介_作者： [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  - _我如何使纯 Ruby word2vec 程序快 3 倍以上_ by [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  - _Dōmo arigatō，Roboto 先生：使用 Ruby 进行机器学习_ 作者： [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
- 2015
  - _N-gram 分析的乐趣和利润_ by [Jesus Castello](https://github.com/matugm)
    <sup>[[tutorial](https://www.rubyguides.com/2015/09/ngram-analysis-ruby/)]</sup>
  -_Ruby 使机器学习变得简单_作者： [Lorenzo Masini](https://github.com/rugginoso)
    <sup>[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  - _使用 Ruby 机器学习查找 Paris Hilton 语录_ 作者： [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](http://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  -_探索 Ruby 中的自然语言处理_作者： [Kevin Dias](https://github.com/diasks2)
    <sup>[[slides](https://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
  -_Ruby 使机器学习变得简单_作者： [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  -_Ruby 中的实用数据科学_作者：Bobby Grayson
    <sup>[[slides](http://slides.com/bobbygrayson/p#/)]</sup>
- 2014
  -_用 Ruby 进行自然语言解析_作者： [Glauco Custódio](https://github.com/glaucocustodio)
    <sup>[[tutorial](http://glaucocustodio.github.io/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
  -_揭开数据科学的神秘面纱：使用 Rails 和 Ngrams 分析会议谈话_作者：
    [Todd Schneider](https://github.com/toddwschneider)
    <sup>[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram)]</sup>
  -_用 Ruby 进行自然语言处理_作者： [Konstantin Tennhard](https://github.com/t6d)
    <sup>[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU) |
    [video](https://www.youtube.com/watch?v=sPkeeWnsMn0) |
    [slides](http://euruko2013.org/speakers/presentations/natural_language_processing_with_ruby_and_opennlp-tennhard.pdf)]</sup>
- 2013
  - _How to parse &#39;go&#39; - Ruby 中的自然语言处理_ by
    [Tom Cartwright](https://twitter.com/tomcartwrightuk)
    <sup>[[slides](https://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby) |
    [video](https://skillsmatter.com/skillscasts/4883-how-to-parse-go)]</sup>
  - _Ruby 中的自然语言处理_ 作者： [Brandon Black](https://twitter.com/brandonmblack)
    <sup>[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
  - _用 Ruby 进行自然语言处理：n-grams_ by [Nathan Kleyn](https://github.com/nathankleyn)
    <sup>[[tutorial](https://www.sitepoint.com/natural-language-processing-ruby-n-grams/) |
    [code](https://github.com/nathankleyn/ruby-nlp)]</sup>
  -_Seeking Lovecraft，第 1 部分：NLP 和 Treat Gem 简介_作者：
    [Robert Qualls](https://github.com/rlqualls)
    <sup>[[tutorial](https://www.sitepoint.com/seeking-lovecraft-part-1-an-introduction-to-nlp-and-the-treat-gem/)]</sup>
- 2012
  -_Ruby 机器学习，第一部分_作者： [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
- 2011
  - _Ruby one-liners_ by [Benoit Hamelin](https://twitter.com/benoithamelin)
    <sup>[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>
  - _Ruby 中的集群_ [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)/)]</sup>
- 2010
  - _bayes_motel – Bayesian classification for Ruby_ by [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
- 2009
  - _将 UEA-Lite Stemmer 移植到 Ruby_ by [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/07/16/porting-the-uea-lite-stemmer-to-ruby/)]</sup>
  -_Ruby 的 NLP 资源_作者： [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/09/13/nlp-resources-for-ruby/)]</sup>
- 2008
  - _Ruby 中的支持向量机 (SVM)_ 作者： [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
  - _Ruby 实用文本分类_ by [Gleicon Moraes](https://twitter.com/gleicon)
    <sup>[[post](https://zenmachine.wordpress.com/practical-text-classification-with-ruby/) |
    [code](https://github.com/gleicon/zenmachine)]</sup>
- 2007
  -_Ruby 中的决策树学习_作者： [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>
- 2006
  -_Speak My Language：使用 Ruby 进行自然语言处理_作者： [Michael Granger](https://deveiate.org/resume.html)
    <sup>[[slides](https://deveiate.org/misc/Speak-My-Language.pdf) |
          [write-up](http://blog.nicksieger.com/articles/2006/10/22/rubyconf-natural-language-generation-and-processing-in-ruby/) |
          [write-up](http://juixe.com/papers/RubyConf2006.pdf)]</sup>

## Projects and Code Examples

- [Going the Distance](https://github.com/schneems/going_the_distance) -
  通过示例计算实现各种距离算法.
- [Named entity recognition with Stanford NER and Ruby](https://github.com/mblongii/ruby-ner) -
  Ruby 和 Java 中的 NER 示例以及一些 [explanations](https://web.archive.org/web/20120722225402/http://mblongii.com/2012/04/15/named-entity-recognition-with-stanford-ner-and-ruby/).
- [Words Counted](http://rubywordcount.com/) -
  可自定义的单词统计示例
  [words_counted](https://github.com/abitdodgy/words_counted).
- [RSyntaxTree](https://yohasebe.com/rsyntaxtree/) -
  基于 Web 的句法树可视化演示.

## Books

-  [Miller, Rob](https://twitter.com/robmil/).
   _使用 Ruby 进行文本处理：从您周围的数据中提取价值._
   实用程序员，2015 年.
   <sup>[[link](https://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708)]</sup>
-  [Watson, Mark](https://twitter.com/mark_l_watson).
   _脚本智能：Web 3.0 信息收集和处理._
   美联社，2010 年.
   <sup>[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510)]</sup>
-  [Watson, Mark](https://twitter.com/mark_l_watson).
   _实用语义网和关联数据应用程序._ Lulu，2010 年.
   <sup>[[link](http://www.lulu.com/shop/mark-watson/practical-semantic-web-and-linked-data-applications-java-edition/paperback/product-10915016.html)]</sup>

## Community

- [Reddit](https://www.reddit.com/r/LanguageTechnology/search?q=ruby&restrict_sr=on)
- [Stack Overflow](https://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)
- [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp&src=typd&lang=en)

## Needs your Help!

本节中的所有项目对社区都非常重要，但需要
更多的关注. 如果您有空闲时间和奉献精神，请花几个小时
在这里的代码上.

- [ferret](https://github.com/dbalmain/ferret) -
  C 和 Ruby 中的信息检索.
- [summarize](https://github.com/ssoper/summarize) -
  Ruby 原生包装器 [Open Text Summarizer](https://github.com/neopunisher/Open-Text-Summarizer).

## Related Resources

- [Neural Machine Translation Implementations](https://github.com/jonsafari/nmt-list)
- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
  在其他很棒的项目中，有一个 NLP 相关项目的简短列表.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  NLP 的最先进的 Ruby 库集合.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  NLP 相关资源的一般列表（大部分不适合 Ruby 程序员）.
- [Scientific Ruby](http://sciruby.com/) -
  Ruby 的线性代数、可视化和科学计算.
- [iRuby](https://github.com/SciRuby/iruby) - 用于 Jupyter 的 IRuby 内核（正式名称为 IPython）.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  大量的 OCR（光学字符识别）资源.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  使用 TensorFlow 库进行机器学习.
- <a name="imagemagic"></a>
  [ImageMagick](https://imagemagick.org/index.php)

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) `Awesome NLP with Ruby` by [Andrei Beliankou](https://github.com/arbox) 和
[Contributors](https://github.com/arbox/nlp-with-ruby/graphs/contributors).

在法律允许的范围内，将 CC0 与
`Awesome NLP with Ruby` 放弃了所有版权和相关或相邻的权利
到 `Awesome NLP with Ruby`.

您应该已经收到一份 CC0 合法代码的副本以及此
工作. 如果没有，请参阅<https://creativecommons.org/publicdomain/zero/1.0/> .

<!--- Links --->
[红宝石]：https://www.ruby-lang.org/en/
【动机】：https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md
[faq]: https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md
[ds-with-ruby]：https://github.com/arbox/data-science-with-ruby
[ml-with-ruby]：https://github.com/arbox/machine-learning-with-ruby
[更改-pr]：https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md
