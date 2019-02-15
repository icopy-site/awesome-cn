<div class="github-widget" data-repo="arbox/nlp-with-ruby"></div>
<img src="https://raw.githubusercontent.com/arbox/nlp-with-ruby/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[[RubyML](https://github.com/arbox/machine-learning-with-ruby) |
 [RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]



&gt; Ruby中用于文本处理的有用资源

这个策划清单包括 [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
资源，图书馆，关于文本计算处理的信息来源
在人类语言中 [Ruby programming language](https://github.com/arbox/nlp-with-ruby/blob/master/ruby).
那个领域通常被称为
[NLP](https://en.wikipedia.org/wiki/Natural_language_processing),
[Computational Linguistics](https://en.wikipedia.org/wiki/Computational_linguistics),
[HLT](https://en.wikipedia.org/wiki/Language_technology) （人类语言技术）
并且可以与...结合使用
[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence),
[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning),
[Information Retrieval](https://en.wikipedia.org/wiki/Information_retrieval),
[Text Mining](https://en.wikipedia.org/wiki/Text_mining),
[Knowledge Extraction](https://en.wikipedia.org/wiki/Knowledge_extraction)
和其他相关学科.

此列表来自我们对语言模型和NLP工具的日常工作.
Read [why](https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md)  这个清单太棒了.  我们 [FAQ](https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md) 描述了
您可能感兴趣的重要决定和有用的答案.

：闪耀：每一个 [contribution](#contributing)  不客气！  通过pull添加链接
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

NLP管道以纯文本开头.

### Pipeline Generation

- [composable_operations](https://github.com/t6d/composable_operations) -
  运营管道的定义框架.
- [ruby-spark](https://github.com/ondra-m/ruby-spark) -
  使用易于理解的DSL进行Spark绑定.
- [phobos](https://github.com/phobos/phobos) -
  简化的Ruby客户端 [Apache Kafka](https://kafka.apache.org/).
- [parallel](https://github.com/grosser/parallel) -
  在多个CPU或多个线程中并行执行的管理程序.
- [pwrake](https://github.com/masa16/pwrake) -
  Rake扩展以并行运行本地和远程任务.

### Multipurpose Engines

- [open-nlp](https://github.com/louismullie/open-nlp) -
  Ruby Bindings for [OpenNLP](https://opennlp.apache.org/) 工具包.
- [stanford-core-nlp](https://github.com/louismullie/stanford-core-nlp) -
  斯坦福的Ruby Bindings [CoreNLP](https://github.com/stanfordnlp/CoreNLP) 工具.
- [treat](https://github.com/louismullie/treat) -
  Ruby的自然语言处理框架（如 [NLTK](http://www.nltk.org/) 对于Python）.
- [nlp_toolz](https://github.com/LeFnord/nlp_toolz) -
  包裹在一些 [OpenNLP](https://opennlp.apache.org/) 课程和
  原本 [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser).
- [open_nlp](https://github.com/hck/open_nlp) -
  JRuby Bindings for [OpenNLP](https://opennlp.apache.org/) 工具包.

#### On-line APIs

- [alchemyapi_ruby](https://github.com/alchemyapi/alchemyapi_ruby) -
  适用于AlchemyAPI / Bluemix的旧版Ruby SDK.
- [wit-ruby](https://github.com/wit-ai/wit-ruby) -
  Ruby客户端库 [Wit.ai](https://wit.ai/) 语言理解平台.
- [wlapi](https://github.com/arbox/wlapi) - 用于的Ruby客户端库
  [Wortschatz Leipzig](http://wortschatz.uni-leipzig.de/de) 网页服务.
- [monkeylearn-ruby](https://github.com/monkeylearn/monkeylearn-ruby) - 情绪
  分析，主题建模，语言检测，命名实体识别
  基于Ruby的Web API客户端.
- [google-cloud-language](https://github.com/googleapis/google-cloud-ruby/tree/master/google-cloud-language) -
  适用于Ruby的Google自然语言服务API.

### Language Identification

语言识别是每个NLP管道中最重要的步骤之一.

- [scylla](https://github.com/hashwin/scylla) -
  语言分类与识别.

### Segmentation

用于标记化，单词和句子边界检测和消歧的工具.

- [tokenizer](https://github.com/arbox/tokenizer) -
  简单的多语言标记器.
  <sup>[[tutorial](https://github.com/arbox/nlp-with-ruby/blob/master/tutorials/tokenizer.md)]</sup>
- [pragmatic_tokenizer](https://github.com/diasks2/pragmatic_tokenizer) -
  多语言标记生成器将字符串拆分为标记.
- [nlp-pure](https://github.com/parhamr/nlp-pure) -
  自然语言处理算法在纯Ruby中实现，具有最小的依赖性.
- [textoken](https://github.com/manorie/textoken) -
  简单且可自定义的文本标记化库.
- [pragmatic_segmenter](https://github.com/diasks2/pragmatic_segmenter) -
  Word边界消歧与许多饼干.
- [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter) -
  Punkt Segmenter的纯Ruby实现.
- [tactful_tokenizer](https://github.com/zencephalon/Tactful_Tokenizer) -
  基于RegExp的不同语言的标记器.
- [scapel](https://github.com/louismullie/scalpel) -
  句子边界消歧工具.

### Lexical Processing

#### Stemming

词干是在信息检索中用来描述过程的术语
 将字形缩减为某种基本表示.  应该区分词干
from [Lemmatization](#lemmatization) 因为`茎&#39;不一定有
语言动机.

- [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) -
  Ruby-Stemmer将SnowBall API暴露给Ruby.
- [uea-stemmer](https://github.com/ealdent/uea-stemmer) -
  用于搜索和索引的保守词干分析器.

#### Lemmatization

 词形还原被认为是找到单词的基本形式的过程.  引理
通常收集在词典中.

- [lemmatizer](https://github.com/yohasebe/lemmatizer) -
  基于WordNet的Lemmatizer用于英文文本.

#### Lexical Statistics: Counting Types and Tokens

- [wc](https://github.com/thesp0nge/wc) -
  计算文本中单词出现次数的工具.
- [word_count](https://github.com/AtelierConvivialite/word_count) -
  `String`和`Hash`对象的字计数器.
- [words_counted](https://github.com/abitdodgy/words_counted) -
  纯Ruby库计数单词统计与不同的自定义选项.

#### Filtering Stop Words

- [stopwords-filter](https://github.com/brenes/stopwords-filter) - 过滤和
  根据SnowBall lemmatizer停止Word Lexicon.

### Phrasal Level Processing

- [n_gram](https://github.com/reddavis/N-Gram) -
  N-Gram发生器.
- [ruby-ngram](https://github.com/tkellen/ruby-ngram) -
  将单词和短语分成ngrams.
- [raingrams](https://github.com/postmodern/raingrams) -
  用纯Ruby编写的灵活通用的ngrams库.

### Syntactic Processing

#### Constituency Parsing

- [stanfordparser](https://rubygems.org/gems/stanfordparser) -
  基于Ruby的Stanford Parser包装器.
- [rley](https://github.com/famished-tiger/Rley) -
  纯Ruby实现了 [Earley](https://en.wikipedia.org/wiki/Earley_parser)
  无上下文选区语法的解析算法.
- [rsyntaxtree](https://github.com/yohasebe/rsyntaxtree) -
  基于XML的Ruby语法树可视化 [RMagick](https://github.com/rmagick/rmagick).
  <sup>[dep: [ImageMagick](#imagemagick)]</sup>

### Semantic Analysis

- [amatch](https://github.com/flori/amatch) -
  字符串之间的五种距离类型集（包括Levenshtein，卖家，Jaro-Winkler，&#39;对距离&#39;）.
- [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) -
  使用Damerau-Levenshtein算法计算编辑距离.
- [hotwater](https://github.com/colinsurprenant/hotwater) -
  快速Ruby FFI字符串编辑距离算法.
- [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) -
  使用Damerau-Levenshtein算法进行快速字符串编辑距离计算.
- [tf_idf](https://github.com/reddavis/TF-IDF) -
  纯Ruby中的术语频率/反向文档频率.
- [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) -
  使用TF / IDF计算文本之间的相似性.

### Pragmatical Analysis
- [SentimentLib](https://github.com/nzaillian/sentiment_lib) -
  Simple extensible sentiment analysis gem.

## High Level Tasks

### Spelling and Error Correction

- [gingerice](https://github.com/subosito/gingerice) -
  拼写和语法修正通过 [Ginger](https://www.gingersoftware.com/) API.
- [hunspell-i18n](https://github.com/romanbsd/hunspell) -
  Ruby绑定到标准 [Hunspell](https://hunspell.github.io/) 拼写检查程序.
- [ffi-hunspell](https://github.com/postmodern/ffi-hunspell) -
  基于FFI的Ruby绑定 [Hunspell](https://hunspell.github.io/).
- [hunspell](https://github.com/segabor/Hunspell) -
  Ruby绑定到 [Hunspell](https://hunspell.github.io/) 通过Ruby C API.

### Text Alignment

- [alignment](https://github.com/povilasjurcys/alignment) -
  双语文本的对齐例程（Gale-Church实现）.

### Machine Translation

- [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
  Google API Ruby客户端.
- [microsoft_translator](https://github.com/ikayzo/microsoft_translator) -
  用于microsoft翻译器API的Ruby客户端.
- [termit](https://github.com/pawurb/termit) -
  Google Translate在您的终端中进行语音合成.
- [zipf](https://github.com/pks/zipf) -
  BLEU和其他基本算法的实现.

### Sentiment Analysis

- [stimmung](https://github.com/pachacamac/stimmung) -
  基于XML的语义极性
  [SentiWS](http://wortschatz.uni-leipzig.de/en/download) 词汇.

### Numbers, Dates, and Time Parsing

- [chronic](https://github.com/mojombo/chronic) -
  纯Ruby自然语言日期解析器.
- [chronic_between](https://github.com/jrobertson/chronic_between) -
  用于日期和时间范围的简单Ruby自然语言解析器.
- [chronic_duration](https://github.com/henrypoydar/chronic_duration) -
  经过时间的纯Ruby解析器.
- [kronic](https://github.com/xaviershay/kronic) -
  解析和格式化人类可读日期的方法.
- [nickel](https://github.com/iainbeeston/nickel) -
  从自然措辞的文本中提取日期，时间和消息信息.
- [tickle](https://github.com/yb66/tickle) -
  解决重复和重复事件的解析器.
- [numerizer](https://github.com/jduff/numerizer) -
  用于英文数字表达式的Ruby解析器.

### Named Entity Recognition

- [ruby-ner](https://github.com/mblongii/ruby-ner) -
  使用Stanford NER和Ruby命名实体识别.
- [ruby-nlp](https://github.com/tiendung/ruby-nlp) -
  用于Stanford Pos-Tagger和名称实体识别器的Ruby绑定.

### Text-to-Speech-to-Text

- [espeak-ruby](https://github.com/dejan/espeak-ruby) -
  小型Ruby API，用于利用“espeak”和“lame”创建文本到语音的mp3文件.
- [tts](https://github.com/c2h2/tts) -
  使用Google翻译服务进行文字转语音转换.
- [att_speech](https://github.com/adhearsion/att_speech) -
  用于语音到文本的AT＆T Speech API的Ruby包装器.
- [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) -
  Pocketsphinx绑定.

## Dialog Agents, Assistants, and Chatbots

- [chatterbot](https://github.com/muffinista/chatterbot) -
  简单的基于ruby的Twitter Bot Framework，使用OAuth进行身份验证.
- [lita](https://github.com/litaio/lita) -
  高度可扩展的聊天操作机器人框架，用持久存储编写 [Redis](https://redis.io/).

## Linguistic Resources

- [rwordnet](https://github.com/doches/rwordnet) -
  纯Ruby自包含的API库 [Princeton WordNet®](https://wordnet.princeton.edu/).
- [wordnet](https://github.com/ged/ruby-wordnet/blob/master/README.rdoc) -
  性能调整绑定 [Princeton WordNet®](https://wordnet.princeton.edu/).

## Machine Learning Libraries

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) 算法
在纯Ruby中或用其他编程语言编写适当的绑定
对于Ruby.

有关更多最新列表，请查看[带有Ruby的Awesome ML] [ml-with-ruby]列表.

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  支持Ruby的矢量机.
- [weka](https://github.com/paulgoetze/weka-jruby) -
  针对Weka的JRuby绑定，通过Weka实现的不同ML算法.
- [decisiontree](https://github.com/igrigorik/decisiontree) -
  纯Ruby中的决策树ID3算法
  <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
- [rtimbl](https://github.com/maspwr/rtimbl) -
  来自Timbl框架的基于记忆的学习者.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  通用分类器模块允许贝叶斯和其他类型的分类.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  Ruby的实现 [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  （潜在Dirichlet分配）用于自动主题建模和文档聚类.
- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  与LIBLINEAR的Ruby接口（比LIBSVM更有效地进行文本分类）.
- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis支持的贝叶斯分类器.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  JRuby字符串数据的最大熵分类器，基于OpenNLP Maxent框架.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  简单的朴素贝叶斯分类器.
- [nbayes](https://github.com/oasic/nbayes) -
  功能齐全的Ruby实现朴素贝叶斯.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  用于文本分类的通用机架框架.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  Naive Bayes文本分类实现为OmniCat分类器策略.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby绑定到 [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [rblearn](https://github.com/himkt/rblearn) - 特征提取和交叉验证库.

## Data Visualization

请参考 [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
关于[带有Ruby的数据科学] [ds-with-ruby]列表的部分.

## Optical Character Recognition

* [tesseract-ocr](https://github.com/meh/ruby-tesseract-ocr) -
  基于FFI的包装器 [Tesseract OCR Engine](https://github.com/tesseract-ocr/tesseract).

## Text Extraction

- [yomu](https://github.com/yomurb/yomu) -
  用于从文件和文档中提取文本和元数据的库
  使用 [Apache Tika](https://tika.apache.org/) 内容分析工具包.

## Full Text Search, Information Retrieval, Indexing

- [rsolr](https://github.com/rsolr/rsolr) -
  Ruby和Rails客户端库 [Apache Solr](http://lucene.apache.org/solr/).
- [sunspot](https://github.com/sunspot/sunspot) -
  以Rails为中心的客户端 [Apache Solr](http://lucene.apache.org/solr/).
- [thinking-sphinx](https://github.com/pat/thinking-sphinx) -
  [Active Record](https://guides.rubyonrails.org/active_record_basics.html)
  插件使用 [Sphinx](http://sphinxsearch.com/) in（不仅仅是）基于Rails的项目.
- [elasticsearch](https://github.com/elastic/elasticsearch-ruby/tree/master/elasticsearch) -
  Ruby客户端和API [Elasticsearch](https://www.elastic.co/).
- [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) -
  Ruby和Rails集成 [Elasticsearch](https://www.elastic.co/).
- [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
  Ruby API库 [Google](https://developers.google.com/api-client-library/ruby/) 服务.

## Language Aware String Manipulation

用于语言感知字符串操作的库，即搜索，模式匹配，
大小写转换，转码，需要信息的正则表达式
基础语言.

- [fuzzy_match](https://github.com/seamusabshere/fuzzy_match) -
  距离测度与正则表达式的模糊字符串比较.
- [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) -
  Ruby的模糊字符串匹配库.
- [active_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) -
  RoR`ActiveSupport` gem有各种可以处理大小写的字符串扩展.
- [fuzzy_tools](https://github.com/brianhempel/fuzzy_tools) -
  用于Ruby中模糊搜索的工具集调整了准确性.
- [u](http://disu.se/software/u-1.0/) -
  U扩展了Ruby的Unicode支持.
- [unicode](https://github.com/blackwinter/unicode) -
  Unicode规范化库.
- [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) -
  在字符串中查找许多常见信息.
- [regexp-examples](https://github.com/tom-lord/regexp-examples) -
  生成与给定正则表达式匹配的字符串.
- [verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) -
  使困难的正则表达变得容易
- [translit_kit](https://github.com/AnalyzePlatypus/TranslitKit) -
  将希伯来语和意第绪语音译成拉丁字符.
- [re2](https://github.com/mudge/re2) -
  用于文本挖掘和文本提取的高速正则表达式库.
- [regex_sample](https://github.com/mochizukikotaro/regex_sample) -
  从给定的正则表达式生成样本字符串.

## Articles, Posts, Talks, and Presentations

- 2019
  - 使用Ruby_ by从图像中提取文本 [aonemd](https://twitter.com/aonemd)
    <sup>[[post](https://aonemd.github.io/blog/extracting-text-from-images-using-ruby) |
    [code](https://gist.github.com/aonemd/7bb3c4760d9e47a9ce8e270198cb40a0)]</sup>
- 2018
  -  _Natural语言处理和推文情感分析_ [Cassandra Corrales](https://twitter.com/casita305)
    <sup>[[post](https://medium.com/@cmcorrales3/natural-language-processing-and-tweet-sentiment-analysis-fa1edbb5ddd5)]</sup>
- 2017
  -  _Google NLP API符合Ruby_ by [Aja Hammerly](https://twitter.com/the_thagomizer)
    <sup>[[post](http://www.thagomizer.com/blog/2017/04/13/the-google-nlp-api-meets-ruby.html)]</sup>
  -  _Syntax不是一切：NLP for Rubyists_ by [Aja Hammerly](https://twitter.com/the_thagomizer)
    <sup>[[slides](http://www.thagomizer.com/files/NLP_RailsConf2017.pdf)]</sup>
  - 关于JRuby_的科学计算 [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
  -  Ruby_中的_Unicode规范化 [Starr Horne](https://twitter.com/starrhorne)
    <sup>[[post](https://blog.honeybadger.io/ruby_unicode_normalization/)]</sup>
- 2016
  -  _快速创建Ruby_中的Telegram Bot [Ardian Haxha](https://twitter.com/ArdianHaxha)
    <sup>[[tutorial](https://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
  -  _Deep Learning：Ruby Developers的简介_ [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  - 我如何使用一个纯Ruby的word2vec程序，速度提高3倍以上 [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  - _Dōmoarigatō，Roboto先生：Ruby_的机器学习 [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
- 2015
  - 用于娱乐和利润的_N-gram分析 [Jesus Castello](https://github.com/matugm)
    <sup>[[tutorial](https://www.rubyguides.com/2015/09/ngram-analysis-ruby/)]</sup>
  - 使用Ruby_ by，_Machine Learning变得简单 [Lorenzo Masini](https://github.com/rugginoso)
    <sup>[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  - 使用Ruby机器学习查找Paris Hilton Quotes_ [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](http://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  - 在Ruby_中探索自然语言处理 [Kevin Dias](https://github.com/diasks2)
    <sup>[[slides](https://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
  - 使用Ruby_ by，_Machine Learning变得简单 [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  --Bobby Grayson撰写的Ruby_实用数据科学
    <sup>[[slides](http://slides.com/bobbygrayson/p#/)]</sup>
- 2014
  -  _Natural语言用Ruby_解析 [Glauco Custódio](https://github.com/glaucocustodio)
    <sup>[[tutorial](http://glaucocustodio.github.io/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
  -  _Demystifying数据科学：用Rails和Ngrams_分析会议谈判
    [Todd Schneider](https://github.com/toddwschneider)
    <sup>[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram)]</sup>
  - 使用Ruby_的_Natural语言处理 [Konstantin Tennhard](https://github.com/t6d)
    <sup>[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU) |
    [video](https://www.youtube.com/watch?v=sPkeeWnsMn0) |
    [slides](http://euruko2013.org/speakers/presentations/natural_language_processing_with_ruby_and_opennlp-tennhard.pdf)]</sup>
- 2013
  - 如何解析&#39;go&#39; -  Ruby_中的自然语言处理
    [Tom Cartwright](https://twitter.com/tomcartwrightuk)
    <sup>[[slides](https://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby) |
    [video](https://skillsmatter.com/skillscasts/4883-how-to-parse-go)]</sup>
  -  Ruby_中的_Natural语言处理 [Brandon Black](https://twitter.com/brandonmblack)
    <sup>[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
  - 使用Ruby的_Natural语言处理：n-gram_ by [Nathan Kleyn](https://github.com/nathankleyn)
    <sup>[[tutorial](https://www.sitepoint.com/natural-language-processing-ruby-n-grams/) |
    [code](https://github.com/nathankleyn/ruby-nlp)]</sup>
  -  _Seeking Lovecraft，第1部分：NLP和Treat Gem_的介绍
    [Robert Qualls](https://github.com/rlqualls)
    <sup>[[tutorial](https://www.sitepoint.com/seeking-lovecraft-part-1-an-introduction-to-nlp-and-the-treat-gem/)]</sup>
- 2012
  - 使用Ruby学习_Machine，第一部分由 [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
- 2011
  -  _Ruby one-liners_ by [Benoit Hamelin](https://twitter.com/benoithamelin)
    <sup>[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>
  - 在Ruby_中的_Clustering by [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)/)]</sup>
- 2010
  - _bayes_motel – Bayesian classification for Ruby_ by [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
- 2009
  -  _将UEA-Lite Stemmer输出到Ruby_ [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/07/16/porting-the-uea-lite-stemmer-to-ruby/)]</sup>
  -  Ruby_的_NLP资源 [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/09/13/nlp-resources-for-ruby/)]</sup>
- 2008
  - 在Ruby_中使用_Support Vector Machines（SVM） [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
  - 使用Ruby_的_实用文本分类 [Gleicon Moraes](https://twitter.com/gleicon)
    <sup>[[post](https://zenmachine.wordpress.com/practical-text-classification-with-ruby/) |
    [code](https://github.com/gleicon/zenmachine)]</sup>
- 2007
  - 在Ruby_中的_Decision树学习 [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>
- 2006
  -  _Speak我的语言：Ruby_的自然语言处理 [Michael Granger](https://deveiate.org/resume.html)
    <sup>[[slides](https://deveiate.org/misc/Speak-My-Language.pdf) |
          [write-up](http://blog.nicksieger.com/articles/2006/10/22/rubyconf-natural-language-generation-and-processing-in-ruby/) |
          [write-up](http://juixe.com/papers/RubyConf2006.pdf)]</sup>

## Projects and Code Examples

- [Going the Distance](https://github.com/schneems/going_the_distance) -
  通过示例计算实现各种距离算法.
- [Named entity recognition with Stanford NER and Ruby](https://github.com/mblongii/ruby-ner) -
  有一些在Ruby和Java中的NER示例 [explanations](https://web.archive.org/web/20120722225402/http://mblongii.com/2012/04/15/named-entity-recognition-with-stanford-ner-and-ruby/).
- [Words Counted](http://rubywordcount.com/) -
  可自定义的单词统计的示例
  [words_counted](https://github.com/abitdodgy/words_counted).
- [RSyntaxTree](https://yohasebe.com/rsyntaxtree/) -
  基于Web的语法树可视化演示.

## Books

-  [Miller, Rob](https://twitter.com/robmil/).
   _Text处理Ruby：从你周围的数据中提取价值._
   务实的程序员，2015年.
   <sup>[[link](https://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708)]</sup>
-  [Watson, Mark](https://twitter.com/mark_l_watson).
   _Scripting Intelligence：Web 3.0信息收集和处理._
   APRESS，2010.
   <sup>[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510)]</sup>
-  [Watson, Mark](https://twitter.com/mark_l_watson).
   _Practical Semantic Web和Linked Data Applications._ Lulu，2010.
   <sup>[[link](http://www.lulu.com/shop/mark-watson/practical-semantic-web-and-linked-data-applications-java-edition/paperback/product-10915016.html)]</sup>

## Community

- [Reddit](https://www.reddit.com/r/LanguageTechnology/search?q=ruby&restrict_sr=on)
- [Stack Overflow](https://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)
- [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp&src=typd&lang=en)

## Needs your Help!

本节中的所有项目对社区而言非常重要，但需要
 更多的关注.  如果你有空闲时间和奉献精神，请花几个小时
在这里的代码.

- [ferret](https://github.com/dbalmain/ferret) -
  C和Ruby中的信息检索.
- [summarize](https://github.com/ssoper/summarize) -
  Ruby原生包装器 [Open Text Summarizer](https://github.com/neopunisher/Open-Text-Summarizer).

## Related Resources

- [Neural Machine Translation Implementations](https://github.com/jonsafari/nmt-list)
- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
  在其他令人敬畏的项目中，NLP相关项目的简短列表.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  用于NLP的Ruby库的最新收集.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  NLP相关资源的一般列表（主要不适用于Ruby程序员）.
- [Scientific Ruby](http://sciruby.com/) -
  Ruby的线性代数，可视化和科学计算.
- [iRuby](https://github.com/SciRuby/iruby) - 用于Jupyter的IRuby内核（formelly IPython）.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  多种OCR（光学字符识别）资源.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  使用TensorFlow库进行机器学习.
- <a name="imagemagic"></a>
  [ImageMagick](https://imagemagick.org/index.php)

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)]（https://creativecommons.org/publicdomain/zero/1.0/）`令人敬畏的NLP with Ruby` by [Andrei Beliankou](https://github.com/arbox) 和
[Contributors](https://github.com/arbox/nlp-with-ruby/graphs/contributors).

在法律允许的范围内，与CC0相关联的人
“令人敬畏的NLP与Ruby”已放弃所有版权及相关或相邻权利
用“红宝石”来实现“令人敬畏的NLP”.

您应该已经收到了CC0 legalcode的副本
 工作.  如果没有，请参阅 <https://creativecommons.org/publicdomain/zero/1.0/>  .

<!--- Links --->
[ruby]：https：//www.ruby-lang.org/en/
[动机]：https：//github.com/arbox/nlp-with-ruby/blob/master/motivation.md
[faq]：https：//github.com/arbox/nlp-with-ruby/blob/master/FAQ.md
[ds-with-ruby]：https：//github.com/arbox/data-science-with-ruby
[ml-with-ruby]：https：//github.com/arbox/machine-learning-with-ruby
[change-pr]：https：//github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md
