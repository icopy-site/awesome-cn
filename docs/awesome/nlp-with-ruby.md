<div class="github-widget" data-repo="arbox/nlp-with-ruby"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<img src="https://raw.githubusercontent.com/arbox/nlp-with-ruby/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[[RubyML](https://github.com/arbox/machine-learning-with-ruby) |
 [RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]



&gt;在Ruby中进行文本处理的有用资源

该精选清单包括 [_awesome_](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
有关文本计算处理的资源，库，信息源
在人类语言中 [Ruby programming language](https://github.com/arbox/nlp-with-ruby/blob/master/ruby).
该字段通常称为
[NLP](https://en.wikipedia.org/wiki/Natural_language_processing),
[Computational Linguistics](https://en.wikipedia.org/wiki/Computational_linguistics),
[HLT](https://en.wikipedia.org/wiki/Language_technology) （人类语言技术）
并可以与
[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence),
[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning),
[Information Retrieval](https://en.wikipedia.org/wiki/Information_retrieval),
[Text Mining](https://en.wikipedia.org/wiki/Text_mining),
[Knowledge Extraction](https://en.wikipedia.org/wiki/Knowledge_extraction)
和其他相关学科.

该列表来自我们在语言模型和NLP工具方面的日常工作.
Read [why](https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md) 这个列表很棒. 我们 [FAQ](https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md) 描述
您可能会对重要的决定和有用的答案感兴趣.

：sparkles：每个 [contribution](#contributing) 不客气！ 通过拉添加链接
请求或提出问题以开始讨论.

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
  操作管道的定义框架.
- [ruby-spark](https://github.com/ondra-m/ruby-spark) -
  使用易于理解的DSL进行Spark绑定.
- [phobos](https://github.com/phobos/phobos) -
  简化的Ruby客户端 [Apache Kafka](https://kafka.apache.org/).
- [parallel](https://github.com/grosser/parallel) -
  在多个CPU或多个线程上并行执行的主管.
- [pwrake](https://github.com/masa16/pwrake) -
  Rake扩展程序可并行运行本地和远程任务.

### Multipurpose Engines

- [open-nlp](https://github.com/louismullie/open-nlp) -
  Ruby绑定 [OpenNLP](https://opennlp.apache.org/) 工具包.
- [stanford-core-nlp](https://github.com/louismullie/stanford-core-nlp) -
  斯坦福大学的Ruby绑定 [CoreNLP](https://github.com/stanfordnlp/CoreNLP) 工具.
- [treat](https://github.com/louismullie/treat) -
  Ruby的自然语言处理框架（例如 [NLTK](http://www.nltk.org/) 对于Python）.
- [nlp_toolz](https://github.com/LeFnord/nlp_toolz) -
  包装一些 [OpenNLP](https://opennlp.apache.org/) 类和
  原本 [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser).
- [open_nlp](https://github.com/hck/open_nlp) -
  JRuby绑定 [OpenNLP](https://opennlp.apache.org/) 工具包.

#### On-line APIs

- [alchemyapi_ruby](https://github.com/alchemyapi/alchemyapi_ruby) -
  适用于AlchemyAPI / Bluemix的旧版Ruby SDK.
- [wit-ruby](https://github.com/wit-ai/wit-ruby) -
  Ruby客户端库 [Wit.ai](https://wit.ai/) 语言理解平台.
- [wlapi](https://github.com/arbox/wlapi) -的Ruby客户端库
  [Wortschatz Leipzig](http://wortschatz.uni-leipzig.de/de) 网页服务.
- [monkeylearn-ruby](https://github.com/monkeylearn/monkeylearn-ruby) -情绪
  分析，主题建模，语言检测，通过命名实体识别
  一个基于Ruby的Web API客户端.
- [google-cloud-language](https://github.com/googleapis/google-cloud-ruby/tree/master/google-cloud-language) -
  Google的Ruby自然语言服务API.

### Language Identification

语言识别是每个NLP管道中的首要关键步骤之一.

- [scylla](https://github.com/hashwin/scylla) -
  语言分类和识别.

### Segmentation

用于标记化，单词和句子边界检测和消除歧义的工具.

- [tokenizer](https://github.com/arbox/tokenizer) -
  简单的多语言标记器.
  <sup>[[tutorial](https://github.com/arbox/nlp-with-ruby/blob/master/tutorials/tokenizer.md)]</sup>
- [pragmatic_tokenizer](https://github.com/diasks2/pragmatic_tokenizer) -
  多语言令牌生成器，用于将字符串拆分为令牌.
- [nlp-pure](https://github.com/parhamr/nlp-pure) -
  在纯Ruby中以最小的依赖关系实现的自然语言处理算法.
- [textoken](https://github.com/manorie/textoken) -
  简单和可自定义的文本标记化库.
- [pragmatic_segmenter](https://github.com/diasks2/pragmatic_segmenter) -
  单词边界消除歧义与许多cookie.
- [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter) -
  Punkt Segmenter的纯Ruby实现.
- [tactful_tokenizer](https://github.com/zencephalon/Tactful_Tokenizer) -
  基于RegExp的令牌生成器，适用于不同的语言.
- [scapel](https://github.com/louismullie/scalpel) -
  句子边界消歧工具.

### Lexical Processing

#### Stemming

Stemming is the term used in information retrieval to describe the process for
将字形简化为基本表示形式. 区分茎
from [Lemmatization](#lemmatization) 因为`stems&#39;不一定有
语言动机.

- [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) -
  Ruby-Stemmer向Ruby公开了SnowBall API.
- [uea-stemmer](https://github.com/ealdent/uea-stemmer) -
  用于搜索和索引的保守词干.

#### Lemmatization

词法化被认为是寻找单词基本形式的过程. 引理
通常收集在字典中.

- [lemmatizer](https://github.com/yohasebe/lemmatizer) -
  基于WordNet的英语文本Lemmatizer.

#### Lexical Statistics: Counting Types and Tokens

- [wc](https://github.com/thesp0nge/wc) -
  用于统计文本中单词出现次数的功能.
- [word_count](https://github.com/AtelierConvivialite/word_count) -
  “字符串”和“哈希”对象的字计数器.
- [words_counted](https://github.com/abitdodgy/words_counted) -
  纯Ruby库使用不同的自定义选项来统计单词统计信息.

#### Filtering Stop Words

- [stopwords-filter](https://github.com/brenes/stopwords-filter) -过滤和
  基于SnowBall lemmatizer停止Word词典.

### Phrasal Level Processing

- [n_gram](https://github.com/reddavis/N-Gram) -
  N-Gram发生器.
- [ruby-ngram](https://github.com/tkellen/ruby-ngram) -
  将单词和短语分解为ngram.
- [raingrams](https://github.com/postmodern/raingrams) -
  用纯Ruby编写的灵活通用的ngrams库.

### Syntactic Processing

#### Constituency Parsing

- [stanfordparser](https://rubygems.org/gems/stanfordparser) -
  Stanford Parser的基于Ruby的包装器.
- [rley](https://github.com/famished-tiger/Rley) -
  纯Ruby的实现 [Earley](https://en.wikipedia.org/wiki/Earley_parser)
  无上下文选区语法的解析算法.
- [rsyntaxtree](https://github.com/yohasebe/rsyntaxtree) -
  基于Ruby的语法树的可视化 [RMagick](https://github.com/rmagick/rmagick).
  <sup>[dep: [ImageMagick](#imagemagick)]</sup>

### Semantic Analysis

- [amatch](https://github.com/flori/amatch) -
  字符串之间的五种距离类型集（包括Levenshtein，Sellers，Jaro-Winkler，“对距离”）.
- [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) -
  使用Damerau-Levenshtein算法计算编辑距离.
- [hotwater](https://github.com/colinsurprenant/hotwater) -
  快速的Ruby FFI字符串编辑距离算法.
- [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) -
  使用Damerau-Levenshtein算法快速进行字符串编辑距离计算.
- [tf_idf](https://github.com/reddavis/TF-IDF) -
  纯Ruby中的术语“频率/文档反向频率”.
- [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) -
  使用TF / IDF计算文本之间的相似度.

### Pragmatical Analysis
- [SentimentLib](https://github.com/nzaillian/sentiment_lib) -
  简单可扩展的情感分析工具.

## High Level Tasks

### Spelling and Error Correction

- [gingerice](https://github.com/subosito/gingerice) -
  通过进行拼写和语法更正 [Ginger](https://www.gingersoftware.com/) 火.
- [hunspell-i18n](https://github.com/romanbsd/hunspell) -
  Ruby绑定到标准 [Hunspell](https://hunspell.github.io/) 拼写检查器.
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
  微软翻译器API的Ruby客户端.
- [termit](https://github.com/pawurb/termit) -
  在您的终端中使用语音合成功能进行Google翻译.
- [zipf](https://github.com/pks/zipf) -
  BLEU和其他基本算法的实现.

### Sentiment Analysis

- [stimmung](https://github.com/pachacamac/stimmung) -
  语义极性基于
  [SentiWS](http://wortschatz.uni-leipzig.de/en/download) 词典.

### Numbers, Dates, and Time Parsing

- [chronic](https://github.com/mojombo/chronic) -
  纯Ruby自然语言日期解析器.
- [chronic_between](https://github.com/jrobertson/chronic_between) -
  用于日期和时间范围的简单Ruby自然语言解析器.
- [chronic_duration](https://github.com/henrypoydar/chronic_duration) -
  纯Ruby解析器用于经过的时间.
- [kronic](https://github.com/xaviershay/kronic) -
  解析和格式化人类可读日期的方法.
- [nickel](https://github.com/iainbeeston/nickel) -
  从自然措辞的文本中提取日期，时间和消息信息.
- [tickle](https://github.com/yb66/tickle) -
  解析器，用于重复发生和重复的事件.
- [numerizer](https://github.com/jduff/numerizer) -
  Ruby解析器，用于英文数字表达式.

### Named Entity Recognition

- [ruby-ner](https://github.com/mblongii/ruby-ner) -
  由Stanford NER和Ruby命名为Entity Recognition.
- [ruby-nlp](https://github.com/tiendung/ruby-nlp) -
  Stanford Pos-Tagger和名称实体识别器的Ruby绑定.

### Text-to-Speech-to-Text

- [espeak-ruby](https://github.com/dejan/espeak-ruby) -
  小型Ruby API，用于利用“ espeak”和“ lame”创建文本到语音的mp3文件.
- [tts](https://github.com/c2h2/tts) -
  使用Google翻译服务进行文本到语音的转换.
- [att_speech](https://github.com/adhearsion/att_speech) -
  AT＆T语音API上的Ruby包装器，用于语音到文本.
- [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) -
  Pocketsphinx bindings.

## Dialog Agents, Assistants, and Chatbots

- [chatterbot](https://github.com/muffinista/chatterbot) -
  基于红宝石的直接Twitter Bot Framework，使用OAuth进行身份验证.
- [lita](https://github.com/litaio/lita) -
  高度可扩展的聊天操作机器人框架，使用持久存储编写 [Redis](https://redis.io/).

## Linguistic Resources

- [rwordnet](https://github.com/doches/rwordnet) -
  适用于的纯Ruby自包含API库 [Princeton WordNet®](https://wordnet.princeton.edu/).
- [wordnet](https://github.com/ged/ruby-wordnet/blob/master/README.rdoc) -
  性能调整的绑定 [Princeton WordNet®](https://wordnet.princeton.edu/).

## Machine Learning Libraries

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) 演算法
用纯Ruby或其他编程语言编写，并带有适当的绑定
露比

有关最新列表，请查看[带Ruby的Awesome ML] [ml-with-ruby]列表.

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  用Ruby支持矢量机.
- [weka](https://github.com/paulgoetze/weka-jruby) -
  Weka的JRuby绑定，通过Weka实现的不同ML算法.
- [decisiontree](https://github.com/igrigorik/decisiontree) -
  纯Ruby中的决策树ID3算法
  <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
- [rtimbl](https://github.com/maspwr/rtimbl) -
  Timbl框架中基于记忆的学习者.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  通用分类器模块，允许贝叶斯和其他类型的分类.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  Ruby的实现 [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  （潜在Dirichlet分配），用于自动主题建模和文档聚类.
- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  Ruby与LIBLINEAR的接口（在文本分类方面比LIBSVM效率更高）.
- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis支持的贝叶斯分类器.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  基于OpenNLP Maxent框架的用于字符串数据的JRuby最大熵分类器.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  简单的朴素贝叶斯分类器.
- [nbayes](https://github.com/oasic/nbayes) -
  Naive Bayes的全功能Ruby实现.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  用于文本分类的通用机架框架.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  朴素贝叶斯文本分类实施作为OmniCat分类器策略.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby绑定到 [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [rblearn](https://github.com/himkt/rblearn) -特征提取和交叉验证库.

## Data Visualization

请参考 [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
[使用Ruby的数据科学] [ds-with-ruby]列表中的“参考”部分.

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
  使用的插件 [Sphinx](http://sphinxsearch.com/) 在（不仅是）基于Rails的项目中.
- [elasticsearch](https://github.com/elastic/elasticsearch-ruby/tree/master/elasticsearch) -
  Ruby客户端和API [Elasticsearch](https://www.elastic.co/).
- [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) -
  的Ruby和Rails集成 [Elasticsearch](https://www.elastic.co/).
- [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
  的Ruby API库 [Google](https://developers.google.com/api-client-library/ruby/) 服务.

## Language Aware String Manipulation

库用于语言感知的字符串操作，例如搜索，模式匹配，
大小写转换，代码转换，需要以下信息的正则表达式
基本语言.

- [fuzzy_match](https://github.com/seamusabshere/fuzzy_match) -
  具有距离测度和正则表达式的模糊字符串比较.
- [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) -
  Ruby的模糊字符串匹配库.
- [active_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) -
  RoR ActiveSupport gem具有可以处理大小写的各种字符串扩展名.
- [fuzzy_tools](https://github.com/brianhempel/fuzzy_tools) -
  Ruby中用于模糊搜索的工具集已针对准确性进行了调整.
- [u](http://disu.se/software/u-1.0/) -
  U扩展了Ruby的Unicode支持.
- [unicode](https://github.com/blackwinter/unicode) -
  Unicode规范化库.
- [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) -
  在字符串中查找许多常见信息.
- [regexp-examples](https://github.com/tom-lord/regexp-examples) -
  生成与给定正则表达式匹配的字符串.
- [verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) -
  使困难的正则表达式变得容易.
- [translit_kit](https://github.com/AnalyzePlatypus/TranslitKit) -
  将希伯来语和意第绪语文本音译成拉丁字符.
- [re2](https://github.com/mudge/re2) -
  用于文本挖掘和文本提取的高速正则表达式库.
- [regex_sample](https://github.com/mochizukikotaro/regex_sample) -
  从给定的正则表达式生成示例字符串.
- [iuliia](https://github.com/adnikiforov/iuliia-rb) -
  以多种可能的方式将西里尔文译成拉丁文（由 [reference implementation](https://github.com/nalgeon/iuliia)).

## Articles, Posts, Talks, and Presentations

- 2019
  -_使用Ruby从图像中提取文本_ by [aonemd](https://twitter.com/aonemd)
    <sup>[[post](https://aonemd.github.io/blog/extracting-text-from-images-using-ruby) |
    [code](https://gist.github.com/aonemd/7bb3c4760d9e47a9ce8e270198cb40a0)]</sup>
- 2018
  -_自然语言处理和推文情感分析_ [Cassandra Corrales](https://twitter.com/casita305)
    <sup>[[post](https://medium.com/@cmcorrales3/natural-language-processing-and-tweet-sentiment-analysis-fa1edbb5ddd5)]</sup>
- 2017
  -_Google NLP API符合Ruby_ by [Aja Hammerly](https://twitter.com/the_thagomizer)
    <sup>[[post](http://www.thagomizer.com/blog/2017/04/13/the-google-nlp-api-meets-ruby.html)]</sup>
  -语法不是万能的：针对Rubyists的NLP_作者： [Aja Hammerly](https://twitter.com/the_thagomizer)
    <sup>[[slides](http://www.thagomizer.com/files/NLP_RailsConf2017.pdf)]</sup>
  -_JRuby上的科学计算_ by [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
  -Ruby中的_Unicode标准化_ [Starr Horne](https://twitter.com/starrhorne)
    <sup>[[post](https://blog.honeybadger.io/ruby_unicode_normalization/)]</sup>
- 2016
  -_快速在Ruby中创建电报机器人_ [Ardian Haxha](https://twitter.com/ArdianHaxha)
    <sup>[[tutorial](https://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
  -_深度学习：Ruby开发人员简介_ by [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  -_我如何使纯Ruby word2vec程序快3倍以上_ [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  -_Dōmoarigatō，Roboto先生：使用Ruby进行机器学习_ by [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
- 2015
  -_N-gram分析乐趣和获利_ [Jesus Castello](https://github.com/matugm)
    <sup>[[tutorial](https://www.rubyguides.com/2015/09/ngram-analysis-ruby/)]</sup>
  -_通过Ruby_实现机器学习变得简单 [Lorenzo Masini](https://github.com/rugginoso)
    <sup>[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  -_使用Ruby机器学习查找巴黎希尔顿行情_ [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](http://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  -_探索Ruby中的自然语言处理_ by [Kevin Dias](https://github.com/diasks2)
    <sup>[[slides](https://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
  -_通过Ruby_实现机器学习变得简单 [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  -_Ruby中的实用数据科学_ Bobby Grayson
    <sup>[[slides](http://slides.com/bobbygrayson/p#/)]</sup>
- 2014
  -_使用Ruby进行自然语言解析_ by [Glauco Custódio](https://github.com/glaucocustodio)
    <sup>[[tutorial](http://glaucocustodio.github.io/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
  -_揭开数据科学的神秘面纱：使用Rails和Ngrams分析会议演讲_作者：
    [Todd Schneider](https://github.com/toddwschneider)
    <sup>[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram)]</sup>
  -_使用Ruby进行自然语言处理_ by [Konstantin Tennhard](https://github.com/t6d)
    <sup>[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU) |
    [video](https://www.youtube.com/watch?v=sPkeeWnsMn0) |
    [slides](http://euruko2013.org/speakers/presentations/natural_language_processing_with_ruby_and_opennlp-tennhard.pdf)]</sup>
- 2013
  -_如何解析&#39;go&#39;-Ruby中的自然语言处理_ by
    [Tom Cartwright](https://twitter.com/tomcartwrightuk)
    <sup>[[slides](https://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby) |
    [video](https://skillsmatter.com/skillscasts/4883-how-to-parse-go)]</sup>
  -_Ruby中的自然语言处理 [Brandon Black](https://twitter.com/brandonmblack)
    <sup>[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
  -_使用Ruby进行自然语言处理：n-grams_ by [Nathan Kleyn](https://github.com/nathankleyn)
    <sup>[[tutorial](https://www.sitepoint.com/natural-language-processing-ruby-n-grams/) |
    [code](https://github.com/nathankleyn/ruby-nlp)]</sup>
  -_寻求Lovecraft，第1部分：NLP和“对待宝石”简介，作者：
    [Robert Qualls](https://github.com/rlqualls)
    <sup>[[tutorial](https://www.sitepoint.com/seeking-lovecraft-part-1-an-introduction-to-nlp-and-the-treat-gem/)]</sup>
- 2012
  -_使用Ruby进行机器学习，第1部分_，作者： [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
- 2011
  -_红宝石单线_ [Benoit Hamelin](https://twitter.com/benoithamelin)
    <sup>[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>
  -_在Ruby中聚簇_ [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)/)]</sup>
- 2010
  -_bayes_motel – Ruby_的贝叶斯分类，作者为 [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
- 2009
  -_将UEA-Lite Stemmer移植到Ruby_ [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/07/16/porting-the-uea-lite-stemmer-to-ruby/)]</sup>
  -_Ruby的_NLP资源_ [Jason Adams](https://twitter.com/ealdent)
    <sup>[[post](https://ealdent.wordpress.com/2009/09/13/nlp-resources-for-ruby/)]</sup>
- 2008
  -_Ruby中的支持向量机（SVM）_ [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
  -_使用Ruby进行实用的文本分类_ [Gleicon Moraes](https://twitter.com/gleicon)
    <sup>[[post](https://zenmachine.wordpress.com/practical-text-classification-with-ruby/) |
    [code](https://github.com/gleicon/zenmachine)]</sup>
- 2007
  -_在Ruby中进行决策树学习_ [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>
- 2006
  -_说我的语言：使用Ruby进行自然语言处理 [Michael Granger](https://deveiate.org/resume.html)
    <sup>[[slides](https://deveiate.org/misc/Speak-My-Language.pdf) |
          [write-up](http://blog.nicksieger.com/articles/2006/10/22/rubyconf-natural-language-generation-and-processing-in-ruby/) |
          [write-up](http://juixe.com/papers/RubyConf2006.pdf)]</sup>

## Projects and Code Examples

- [Going the Distance](https://github.com/schneems/going_the_distance) -
  带有示例计算的各种距离算法的实现.
- [Named entity recognition with Stanford NER and Ruby](https://github.com/mblongii/ruby-ner) -
  Ruby和Java中的NER示例，其中包含一些 [explanations](https://web.archive.org/web/20120722225402/http://mblongii.com/2012/04/15/named-entity-recognition-with-stanford-ner-and-ruby/).
- [Words Counted](http://rubywordcount.com/) -
  由...提供支持的可定制单词统计的示例
  [words_counted](https://github.com/abitdodgy/words_counted).
- [RSyntaxTree](https://yohasebe.com/rsyntaxtree/) -
  基于Web的语法树可视化演示.

## Books

-  [Miller, Rob](https://twitter.com/robmil/).
   _使用Ruby进行文本处理：从您周围的数据中提取价值._
   实用程序员，2015年.
   <sup>[[link](https://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708)]</sup>
-  [Watson, Mark](https://twitter.com/mark_l_watson).
   _脚本情报：Web 3.0信息收集和处理.
   APRESS，2010年.
   <sup>[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510)]</sup>
-  [Watson, Mark](https://twitter.com/mark_l_watson).
   _实用语义网和链接数据应用程序._露露，2010年.
   <sup>[[link](http://www.lulu.com/shop/mark-watson/practical-semantic-web-and-linked-data-applications-java-edition/paperback/product-10915016.html)]</sup>

## Community

- [Reddit](https://www.reddit.com/r/LanguageTechnology/search?q=ruby&restrict_sr=on)
- [Stack Overflow](https://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)
- [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp&src=typd&lang=en)

## Needs your Help!

本节中的所有项目对社区来说确实很重要，但需要
更多关注. 如果您有空余时间和奉献精神，请花几个小时
在这里的代码上.

- [ferret](https://github.com/dbalmain/ferret) -
  C和Ruby中的信息检索.
- [summarize](https://github.com/ssoper/summarize) -
  Ruby本机包装 [Open Text Summarizer](https://github.com/neopunisher/Open-Text-Summarizer).

## Related Resources

- [Neural Machine Translation Implementations](https://github.com/jonsafari/nmt-list)
- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
  在其他很棒的项目中，还有与NLP相关的项目的简短列表.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  最新的NLP Ruby库集合.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  NLP相关资源的一般列表（大多数不适用于Ruby程序员）.
- [Scientific Ruby](http://sciruby.com/) -
  Ruby的线性代数，可视化和科学计算.
- [iRuby](https://github.com/SciRuby/iruby) -Jupyter的IRuby内核（以前为IPython）.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  大量的OCR（光学字符识别）资源.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  使用TensorFlow库进行机器学习
- <a name="imagemagic"></a>
  [ImageMagick](https://imagemagick.org/index.php)

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)]（https://creativecommons.org/publicdomain/zero/1.0/）“很棒的NLP和Ruby”，作者： [Andrei Beliankou](https://github.com/arbox) 和
[Contributors](https://github.com/arbox/nlp-with-ruby/graphs/contributors).

在法律允许的范围内，将CC0与
“使用Ruby的Awesome NLP”放弃了所有版权以及相关或邻近的权利
到“使用Ruby的超赞NLP”.

您应该已经收到了CC0法律代码的副本以及此副本
工作. 如果没有，请参阅<https://creativecommons.org/publicdomain/zero/1.0/> .

<!--- Links --->
[ruby]：https：//www.ruby-lang.org/en/
[动机]：https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md
[常见问题]：https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md
[ds-with-ruby]：https://github.com/arbox/data-science-with-ruby
[ml-with-ruby]：https://github.com/arbox/machine-learning-with-ruby
[change-pr]：https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md
