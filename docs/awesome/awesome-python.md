<div class="github-widget" data-repo="vinta/awesome-python"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的Python框架，库，软件和资源的精选清单.

受启发 [awesome-php](https://github.com/ziadoz/awesome-php).


---

## Admin Panels

*用于管理界面的库.*

* [ajenti](https://github.com/ajenti/ajenti) -您的服务器应有的管理面板.
* [django-grappelli](https://grappelliproject.com/) -Django Admin-Interface的爵士外观.
* [django-jet](https://github.com/geex-arts/django-jet) -具有改进功能的Django管理界面的现代响应模板.
* [django-suit](https://djangosuit.com/) -可选的Django Admin界面（仅用于非商业用途免费）.
* [django-xadmin](https://github.com/sshwsfc/xadmin) -替换Django admin附带许多好处.
* [flask-admin](https://github.com/flask-admin/flask-admin) -Flask的简单和可扩展的管理界面框架.
* [flower](https://github.com/mher/flower) -Celery的实时监控器和Web管理员.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) -具有良好UI的任何应用程序的管理面板框架（例如Jet Django）
* [wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.

## Algorithms and Design Patterns

 *数据结构，算法和设计模式的Python实现. 另见 [awesome-algorithms](https://github.com/tayllan/awesome-algorithms).*

*算法
    * [algorithms](https://github.com/keon/algorithms) -数据结构和算法的最少示例.
    * [python-ds](https://github.com/prabhupant/python-ds) -用于采访采访的数据结构和算法的集合.
    * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) -分类集合的快速和纯Python实现.
    * [TheAlgorithms](https://github.com/TheAlgorithms/Python) -用Python实现的所有算法.
*设计模式
    * [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) -一个简单而有效的库，用于实现通用设计模式.
    * [python-patterns](https://github.com/faif/python-patterns) -Python中的设计模式集合.
    * [transitions](https://github.com/pytransitions/transitions) -轻量级的，面向对象的有限状态机实现.

## ASGI Servers

*[ASGI](https://asgi.readthedocs.io/en/latest/)兼容的Web服务器.*

* [daphne](https://github.com/django/daphne) -用于ASGI和ASGI-HTTP的HTTP，HTTP2和WebSocket协议服务器.
* [uvicorn](https://github.com/encode/uvicorn) -使用uvloop和httptools的闪电般快速的ASGI服务器实现.

## Asynchronous Programming

* [asyncio](https://docs.python.org/3/library/asyncio.html) -（Python标准库）异步I / O，事件循环，协程和任务.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
* [trio](https://github.com/python-trio/trio) -异步并发和I / O的友好库.
* [Twisted](https://twistedmatrix.com/trac/) -事件驱动的网络引擎.
* [uvloop](https://github.com/MagicStack/uvloop) -超快速异步事件循环.

## Audio

*用于处理音频及其元数据的库.

*音频
    * [audioread](https://github.com/beetbox/audioread) -跨库（GStreamer +核心音频+ MAD + FFmpeg）音频解码.
    * [dejavu](https://github.com/worldveil/dejavu) -音频指纹识别.
    * [kapre](https://github.com/keunwoochoi/kapre) -大声音频预处理器
    * [librosa](https://github.com/librosa/librosa) -用于音频和音乐分析的Python库
    * [matchering](https://github.com/sergree/matchering) -用于自动参考音频制作的库.
    * [mingus](http://bspaans.github.io/python-mingus/) -带有MIDI文件和播放支持的高级音乐理论和乐谱包.
    * [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) -音频特征提取，分类，分段和应用.
    * [pydub](https://github.com/jiaaro/pydub) -通过简单易用的高级界面处理音频.
    * [TimeSide](https://github.com/Parisson/TimeSide) -开放的Web音频处理框架.
*元数据
    * [beets](https://github.com/beetbox/beets) -音乐库管理员和 [MusicBrainz](https://musicbrainz.org/) 标签.
    * [eyeD3](https://github.com/nicfit/eyeD3) -用于处理音频文件（特别是包含ID3元数据的MP3文件）的工具.
    * [mutagen](https://github.com/quodlibet/mutagen) -处理音频元数据的Python模块.
    * [tinytag](https://github.com/devsnd/tinytag) -用于读取MP3，OGG，FLAC和Wave文件的音乐元数据的库.

## Authentication

*用于实施身份验证方案的库.*

* OAuth
    * [authlib](https://github.com/lepture/authlib) -JavaScript对象签名和加密草案实施.
    * [django-allauth](https://github.com/pennersr/django-allauth) -适用于Django的身份验证应用程序，“可正常使用”.
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) -适用于Django的OAuth 2好东西.
    * [oauthlib](https://github.com/idan/oauthlib) -OAuth请求签名逻辑的通用且彻底的实现.
    * [python-oauth2](https://github.com/joestump/python-oauth2) -用于创建OAuth客户端和服务器的经过全面测试的抽象界面.
    * [python-social-auth](https://github.com/omab/python-social-auth) -易于设置的社交身份验证机制.
*智威汤逊
    * [pyjwt](https://github.com/jpadilla/pyjwt) -Python中的JSON Web令牌实现.
    * [python-jose](https://github.com/mpdavis/python-jose/) -Python中的JOSE实现.
    * [python-jwt](https://github.com/davedoesdev/python-jwt) -用于生成和验证JSON Web令牌的模块.

## Build Tools

*从源代码编译软件.*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) -嵌入式Linux的类似make的构建工具.
* [buildout](http://www.buildout.org/en/latest/) -用于从多个部分创建，组装和部署应用程序的构建系统.
* [PlatformIO](https://github.com/platformio/platformio-core) -一个控制台工具，用于使用不同的开发平台构建代码.
* [pybuilder](https://github.com/pybuilder/pybuilder) -用纯Python编写的连续构建工具.
* [SCons](http://www.scons.org/) -一种软件构造工具.

## Built-in Classes Enhancement

*用于增强Python内置类的库.*

* [attrs](https://github.com/python-attrs/attrs) -替换类定义中的__init __，__ eq __，__ repr__等样板.
* [bidict](https://github.com/jab/bidict) -高效的Pythonic双向地图数据结构和相关功能.
* [Box](https://github.com/cdgriffith/Box) -具有高级点符号访问功能的Python词典.
* [dataclasses](https://docs.python.org/3/library/dataclasses.html) -（Python标准库）数据类.
* [DottedDict](https://github.com/carlosescri/DottedDict) -一个库，提供一种使用点路径符号访问列表和字典的方法.

## CMS


* [django-cms](https://www.django-cms.org/en/) -基于Django的开源企业CMS.
* [indico](https://github.com/indico/indico) -功能丰富的事件管理系统，由@ [CERN](https://en.wikipedia.org/wiki/CERN).
* [Kotti](https://github.com/Kotti/Kotti) -基于Pyramid的高级Pythonic Web应用程序框架.
* [plone](https://plone.org/) -在开源应用程序服务器Zope之上构建的CMS.
* [quokka](https://github.com/rochacbruno/quokka) -由Flask和MongoDB支持的灵活，可扩展的小型CMS.

## Caching

*用于缓存数据的库.*

* [beaker](https://github.com/bbangert/beaker) -用于会话和缓存的WSGI中间件.
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) -Django模型的自动缓存和失效.
* [django-cacheops](https://github.com/Suor/django-cacheops) -光滑的ORM缓存，具有自动的粒度事件驱动的失效功能.
* [dogpile.cache](http://dogpilecache.readthedocs.io/en/latest/) -dogpile.cache是​​同一作者制作的Beaker的下一代替代产品.
* [HermesCache](https://pypi.org/project/HermesCache/) -具有基于标记的失效和防止堆效应的Python缓存库.
* [pylibmc](https://github.com/lericson/pylibmc) -围绕 [libmemcached](https://libmemcached.org/libMemcached.html) 接口.
* [python-diskcache](http://www.grantjenks.com/docs/diskcache/) -SQLite和文件支持的缓存后端，查找速度比memcached和redis快.

## ChatOps Tools

*用于聊天机器人开发的库.*

* [errbot](https://github.com/errbotio/errbot/) -实施ChatOps的最简单，最受欢迎的聊天机器人.

## Code Analysis

 *静态分析，棉短绒和代码质量检查器的工具. 另见 [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

*代码分析
    * [coala](https://github.com/coala/coala/) -语言独立且易于扩展的代码分析应用程序.
    * [code2flow](https://github.com/scottrogowski/code2flow) -将您的Python和JavaScript代码转换为DOT流程图.
    * [prospector](https://github.com/PyCQA/prospector) -分析Python代码的工具.
    * [pycallgraph](https://github.com/gak/pycallgraph) -可视化您的Python应用程序流程（调用图）的库.
    * [vulture](https://github.com/jendrikseipp/vulture) -查找和分析无效的Python代码的工具.
*代码短毛
    * [flake8](https://pypi.org/project/flake8/) -围绕着pycodestyle，pyflakes和McCabe的包装器.
        * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions)
    * [pylama](https://github.com/klen/pylama) -用于Python和JavaScript的代码审核工具.
    * [pylint](https://www.pylint.org/) -完全可定制的源代码分析器.
    * [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) -有史以来最严格，最自以为是的python linter.
*代码格式化程序
    * [black](https://github.com/python/black) -毫不妥协的Python代码格式化程序.
    * [isort](https://github.com/timothycrosley/isort) -用于对导入进行排序的Python实用程序/库.
    * [yapf](https://github.com/google/yapf) -另一个来自Google的Python代码格式化程序.
*静态类型检查器，另请参见 [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing)
    * [mypy](http://mypy-lang.org/) -在编译期间检查变量类型.
    * [pyre-check](https://github.com/facebook/pyre-check) -性能类型检查.
    * [typeshed](https://github.com/python/typeshed) -具有静态类型的Python库存根的集合.
*静态类型注释生成器
    * [MonkeyType](https://github.com/Instagram/MonkeyType) -一个用于Python的系统，通过收集运行时类型来生成静态类型注释.
    * [pyannotate](https://github.com/dropbox/pyannotate) -自动生成PEP-484注释.
    * [pytype](https://github.com/google/pytype) -Pytype检查并推断Python代码的类型-无需类型注释.

## Command-line Interface Development

*用于构建命令行应用程序的库.

*命令行应用程序开发
    * [cement](http://builtoncement.com/) - CLI Application Framework for Python.
    * [click](http://click.pocoo.org/dev/) -用于以可组合方式创建漂亮的命令行界面的软件包.
    * [cliff](https://docs.openstack.org/developer/cliff/) -用于使用多级命令创建命令行程序的框架.
    * [docopt](http://docopt.org/) -Pythonic命令行参数解析器.
    * [python-fire](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object.
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) -用于构建功能强大的交互式命令行的库.
*终端渲染
    * [alive-progress](https://github.com/rsalmei/alive-progress) -一种新型进度栏，具有实时吞吐量，eta和非常酷的动画.
    * [asciimatics](https://github.com/peterbrittain/asciimatics) -一个用于创建全屏文本UI（从交互式表单到ASCII动画）的软件包.
    * [bashplotlib](https://github.com/glamp/bashplotlib) -在终端中进行基本绘图.
    * [colorama](https://pypi.org/project/colorama/) -跨平台的彩色终端文本.
    * [rich](https://github.com/willmcgugan/rich)  -用于在终端中显示富文本和精美格式的Python库. 还提供了一个很棒的`RichHandler`日志处理程序.
    * [tqdm](https://github.com/tqdm/tqdm) -快速，可扩展的进度条，用于循环和CLI.

## Command-line Tools

*有用的基于CLI的工具可提高工作效率.*

*生产力工具
    * [copier](https://github.com/pykong/copier) -用于渲染项目模板的库和命令行实用程序.
    * [cookiecutter](https://github.com/audreyr/cookiecutter) -从cookiecutter（项目模板）创建项目的命令行实用程序.
    * [doitlive](https://github.com/sloria/doitlive) -在终端中进行实时演示的工具.
    * [howdoi](https://github.com/gleitz/howdoi) -通过命令行即时编码答案.
    * [Invoke](https://github.com/pyinvoke/invoke#readme) -一种工具，用于管理面向外壳的子流程，并将可执行的Python代码组织到CLI可以调用的任务中.
    * [PathPicker](https://github.com/facebook/PathPicker) -从bash输出中选择文件.
    * [percol](https://github.com/mooz/percol) -在UNIX上的传统管道概念中增加了交互选择的味道.
    * [thefuck](https://github.com/nvbn/thefuck) -更正先前的控制台命令.
    * [tmuxp](https://github.com/tony/tmuxp) - 一种 [tmux](https://github.com/tmux/tmux) 会话管理器.
    * [try](https://github.com/timofurrer/try) -一个简单的CLI来试用python软件包-从未如此简单.
* CLI增强功能
    * [httpie](https://github.com/jakubroztocil/httpie) -命令行HTTP客户端，方便用户的cURL替换.
    * [iredis](https://github.com/laixintao/iredis) -具有自动完成功能和语法突出显示功能的Redis CLI.
    * [kube-shell](https://github.com/cloudnativelabs/kube-shell) -用于Kubernetes CLI的集成外壳.
    * [litecli](https://github.com/dbcli/litecli) -具有自动完成功能和语法突出显示功能的SQLite CLI.
    * [mycli](https://github.com/dbcli/mycli) -具有自动补全功能和语法突出显示功能的MySQL CLI.
    * [pgcli](https://github.com/dbcli/pgcli) -具有自动完成功能和语法突出显示功能的PostgreSQL CLI.
    * [saws](https://github.com/donnemartin/saws) -增压 [aws-cli](https://github.com/aws/aws-cli).

## Compatibility

*用于从Python 2迁移到3的库.

* [python-future](http://python-future.org/index.html) -Python 2和Python 3之间缺少兼容性层.
* [modernize](https://github.com/PyCQA/modernize) -现代化Python代码，以便最终进行Python 3迁移.
* [six](https://pypi.org/project/six/) -Python 2和3兼容性实用程序.

## Computer Vision

*计算机视觉图书馆.

* [EasyOCR](https://github.com/JaidedAI/EasyOCR) -支持40多种语言的即用型OCR.
* [Face Recognition](https://github.com/ageitgey/face_recognition) -简单的面部识别库.
* [Kornia](https://github.com/kornia/kornia/) -PyTorch的开源可区分计算机视觉库.
* [OpenCV](https://opencv.org/) -开源计算机视觉库.
* [pytesseract](https://github.com/madmaze/pytesseract) -的包装 [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [SimpleCV](https://github.com/sightmachine/SimpleCV) -用于构建计算机视觉应用程序的开源框架.
* [tesserocr](https://github.com/sirfz/tesserocr) -另一个用于OCR的tesseract-ocr API的简单，友好的包装器.

## Concurrency and Parallelism

 *用于并发和并行执行的库. 另见 [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) -（Python标准库）用于异步执行可调用对象的高级接口.
* [eventlet](http://eventlet.net/) -具有WSGI支持的异步框架.
* [gevent](http://www.gevent.org/) -使用基于协程的Python网络库 [greenlet](https://github.com/python-greenlet/greenlet).
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) -（Python标准库）基于进程的并行性.
* [scoop](https://github.com/soravux/scoop) -Python中的可伸缩并行操作.
* [uvloop](https://github.com/MagicStack/uvloop) -在`libuv`之上的`asyncio`事件循环的超快速实现.

## Configuration

*用于存储和解析配置选项的库.

* [configobj](https://github.com/DiffSK/configobj) -带有验证的INI文件解析器.
* [configparser](https://docs.python.org/3/library/configparser.html) -（Python标准库）INI文件解析器.
* [hydra](https://github.com/facebookresearch/hydra) -Hydra是用于优雅配置复杂应用程序的框架.
* [profig](https://profig.readthedocs.io/en/latest/) -通过值转换从多种格式进行配置.
* [python-decouple](https://github.com/henriquebastos/python-decouple) -严格将设置与代码分开.

## Cryptography

* [cryptography](https://cryptography.io/en/latest/) -旨在向Python开发人员公开密码基元和配方的软件包.
* [paramiko](https://github.com/paramiko/paramiko) -领先的原生Python SSHv2协议库.
* [passlib](https://passlib.readthedocs.io/en/stable/) -安全的密码存储/哈希库，非常高的水平.
* [pynacl](https://github.com/pyca/pynacl) -将Python绑定到网络和密码（NaCl）库.

## Data Analysis

*用于数据分析的库.*

* [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler) -AWS上的熊猫.
* [Blaze](https://github.com/blaze/blaze) -NumPy和Pandas与大数据的接口.
* [Open Mining](https://github.com/mining/mining) -熊猫界面中的商业智能（BI）.
* [Optimus](https://github.com/ironmussa/Optimus) -使用PySpark简化了敏捷数据科学工作流程.
* [Orange](https://orange.biolab.si/) -通过可视化编程或脚本进行数据挖掘，数据可视化，分析和机器学习.
* [Pandas](http://pandas.pydata.org/) -提供高性能，易于使用的数据结构和数据分析工具的库.

## Data Validation

 *用于验证数据的库. 在许多情况下用于表格.*

* [Cerberus](https://github.com/pyeve/cerberus) -轻巧且可扩展的数据验证库.
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) -验证和反序列化通过XML，JSON和HTML表单发布获得的数据.
* [jsonschema](https://github.com/Julian/jsonschema) -的实现 [JSON Schema](http://json-schema.org/) 适用于Python.
* [schema](https://github.com/keleshev/schema) -用于验证Python数据结构的库.
* [Schematics](https://github.com/schematics/schematics) -数据结构验证.
* [valideer](https://github.com/podio/valideer) -轻量级可扩展数据验证和适配库.
* [voluptuous](https://github.com/alecthomas/voluptuous) -Python数据验证库.

## Data Visualization

 *用于可视化数据的库. 另见 [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) -用于Python的声明性统计可视化库.
* [Bokeh](https://github.com/bokeh/bokeh) -用于Python的交互式Web绘图.
* [bqplot](https://github.com/bloomberg/bqplot) -Jupyter Notebook的交互式绘图库
* [Cartopy](https://github.com/SciTools/cartopy) -具有matplotlib支持的制图python库
* [Dash](https://plot.ly/products/dash/) -在Flask，React和Plotly之上构建，旨在用于分析Web应用程序.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash)
* [diagrams](https://github.com/mingrammer/diagrams) -图表为代码.
* [Matplotlib](http://matplotlib.org/) -Python 2D绘图库.
* [plotnine](https://github.com/has2k1/plotnine) -基于ggplot2的Python图形语法.
* [Pygal](http://www.pygal.org/en/latest/) -Python SVG Charts Creator.
* [PyGraphviz](https://pypi.org/project/pygraphviz/) -Python接口 [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) -交互式和实时2D / 3D /图像绘制以及科学/工程部件.
* [Seaborn](https://github.com/mwaskom/seaborn) -使用Matplotlib进行统计数据可视化.
* [VisPy](https://github.com/vispy/vispy) -基于OpenGL的高性能科学可视化.

## Database

*使用Python实现的数据库.*

* [pickleDB](https://github.com/patx/pickledb) -用于Python的简单轻量级键值存储.
* [tinydb](https://github.com/msiemens/tinydb) -小型的，面向文档的数据库.
* [ZODB](https://github.com/zopefoundation/ZODB)  -Python的本机对象数据库. 键值和对象图数据库.

## Database Drivers

*用于连接和操作数据库的库.

* MySQL- [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) -具有Python 3支持的MySQL连接器（[mysql-python](https://sourceforge.net/projects/mysql-python/) 叉子）.
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) -与mysql-python兼容的纯Python MySQL驱动程序.
* PostgreSQL- [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg2](http://initd.org/psycopg/) -最受欢迎的Python PostgreSQL适配器.
    * [queries](https://github.com/gmr/queries) -psycopg2库的包装，用于与PostgreSQL交互.
* SQlite- [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite)
    * [sqlite3](https://docs.python.org/3/library/sqlite3.html) -（Python标准库）符合DB-API 2.0的SQlite接口
    * [SuperSQLite](https://github.com/plasticityai/supersqlite) -建立在 [apsw](https://github.com/rogerbinns/apsw).
*其他关系数据库
    * [pymssql](https://pymssql.readthedocs.io/en/latest/) -Microsoft SQL Server的简单数据库接口.
    * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) -具有ClickHouse本地接口的Python驱动程序.
* NoSQL数据库
    * [cassandra-driver](https://github.com/datastax/python-driver) -Apache Cassandra的Python驱动程序.
    * [happybase](https://github.com/wbolster/happybase) -Apache HBase的开发人员友好型库.
    * [kafka-python](https://github.com/dpkp/kafka-python) -Apache Kafka的Python客户端.
    * [py2neo](https://py2neo.org/) -用于Neo4j的客户端库和工具包.
    * [pymongo](https://github.com/mongodb/mongo-python-driver) -MongoDB的官方Python客户端.
    * [redis-py](https://github.com/andymccurdy/redis-py) -Redis的Python客户端.
*异步客户端
    * [motor](https://github.com/mongodb/motor) -MongoDB的异步Python驱动程序.

## Date and Time

*用于处理日期和时间的库.*

* [Arrow](https://arrow.readthedocs.io/en/latest/) -一个Python库，它提供了一种明智且人性化的方法来创建，处理，格式化和转换日期，时间和时间戳.
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) -一个Python 3库，用于解析人类编写的时间和日期.
* [dateutil](https://github.com/dateutil/dateutil) -对标准Python的扩展 [datetime](https://docs.python.org/3/library/datetime.html) 模块.
* [delorean](https://github.com/myusuf3/delorean/) -一个库，用于清除与日期时间有关的不便事实.
* [maya](https://github.com/timofurrer/maya) -人类的约会时间.
* [moment](https://github.com/zachwill/moment)  -用于处理日期/时间的Python库. 受启发 [Moment.js](http://momentjs.com/).
* [Pendulum](https://github.com/sdispater/pendulum) -Python日期时间变得容易.
* [PyTime](https://github.com/shinux/PyTime) -一个易于使用的Python模块，旨在按字符串操作日期/时间/日期时间.
* [pytz](https://launchpad.net/pytz)  -世界时区定义，现代和历史. 带来 [tz database](https://en.wikipedia.org/wiki/Tz_database) 进入Python.
* [when.py](https://github.com/dirn/When.py) -提供用户友好的功能，以帮助执行常见的日期和时间操作.

## Debugging Tools

*用于调试代码的库.*

*类似pdb的调试器
    * [ipdb](https://github.com/gotcha/ipdb) -启用IPython [pdb](https://docs.python.org/3/library/pdb.html).
    * [pdb++](https://github.com/antocuni/pdb) -pdb的另一种替代产品.
    * [pudb](https://github.com/inducer/pudb) -基于控制台的全屏Python调试器.
    * [wdb](https://github.com/Kozea/wdb) -通过WebSocket的不可能的Web调试器.
*追踪
    * [lptrace](https://github.com/khamidou/lptrace) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) 适用于Python程序.
    * [manhole](https://github.com/ionelmc/python-manhole) -调试UNIX套接字连接，并显示所有线程的堆栈跟踪和交互式提示.
    * [pyringe](https://github.com/google/pyringe) -能够附加到Python进程并将代码注入到Python进程中的调试器.
    * [python-hunter](https://github.com/ionelmc/python-hunter) -灵活的代码跟踪工具包.
*个人资料
    * [line_profiler](https://github.com/rkern/line_profiler) -逐行分析.
    * [memory_profiler](https://github.com/fabianp/memory_profiler) -监视Python代码的内存使用情况.
    * [py-spy](https://github.com/benfred/py-spy)  -用于Python程序的采样分析器. 写在锈.
    * [pyflame](https://github.com/uber/pyflame) -用于Python的跟踪分析器.
    * [vprof](https://github.com/nvdv/vprof) -视觉Python分析器.
* 其他
    * [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) -显示Django的各种调试信息.
    * [django-devserver](https://github.com/dcramer/django-devserver) -Django运行服务器的直接替代品.
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) -django-debug-toolbar到flask的端口.
    * [icecream](https://github.com/gruns/icecream) -通过一个简单的函数调用检查变量，表达式和程序执行情况.
    * [pyelftools](https://github.com/eliben/pyelftools) -解析和分析ELF文件和DWARF调试信息.

## Deep Learning

 *神经网络和深度学习框架. 另见 [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [caffe](https://github.com/BVLC/caffe) -深度学习的快速开放框架.
* [keras](https://github.com/keras-team/keras) -高级神经网络库，能够在TensorFlow或Theano之上运行.
* [mxnet](https://github.com/dmlc/mxnet) -旨在提高效率和灵活性的深度学习框架.
* [pytorch](https://github.com/pytorch/pytorch) -具有强大GPU加速功能的Python中的张量和动态神经网络.
* [SerpentAI](https://github.com/SerpentAI/SerpentAI)  -游戏代理框架. 使用任何视频游戏作为深度学习沙箱.
* [tensorflow](https://github.com/tensorflow/tensorflow) -Google创建的最受欢迎的深度学习框架.
* [Theano](https://github.com/Theano/Theano) -用于快速数值计算的库.

## DevOps Tools

* DevOps的软件和库.*

* 配置管理
    * [ansible](https://github.com/ansible/ansible) -完全简单的IT自动化平台.
    * [cloudinit](https://cloudinit.readthedocs.io/en/latest/) -多分发包，用于处理云实例的早期初始化.
    * [OpenStack](https://www.openstack.org/) -用于构建私有和公共云的开源软件.
    * [pyinfra](https://github.com/Fizzadar/pyinfra) -通用的CLI工具和python库，可自动执行基础架构.
* SSH样式的部署
    * [cuisine](https://github.com/sebastien/cuisine) -织物的类似厨师的功能.
    * [fabric](https://github.com/fabric/fabric) -用于远程执行和部署的简单Pythonic工具.
    * [fabtools](https://github.com/fabtools/fabtools) -编写很棒的Fabric文件的工具.
* 流程管理
    * [honcho](https://github.com/nickstenning/honcho) -的Python克隆 [Foreman](https://github.com/ddollar/foreman)，用于管理基于Procfile的应用程序.
    * [supervisor](https://github.com/Supervisor/supervisor) -UNIX的主管过程控制系统.
*监控
    * [psutil](https://github.com/giampaolo/psutil) -跨平台的流程和系统实用程序模块.
*备份
    * [BorgBackup](https://www.borgbackup.org/) -具有压缩和加密功能的重复数据删除存档器.
* 其他
    * [docker-compose](https://docs.docker.com/compose/) -快速，隔离的开发环境，使用 [Docker](https://www.docker.com/).

## Distributed Computing

*分布式计算的框架和库.

* 批量处理
    * [dask](https://github.com/dask/dask) -用于分析计算的灵活并行计算库.
    * [luigi](https://github.com/spotify/luigi) -一个模块，可帮助您构建批处理作业的复杂管道.
    * [mrjob](https://github.com/Yelp/mrjob) -在Hadoop或Amazon Web Services上运行MapReduce作业.
    * [PySpark](https://pypi.org/project/pyspark/) - [Apache Spark](https://spark.apache.org/) Python API.
    * [Ray](https://github.com/ray-project/ray/) -用于统一和分布式Python的系统，统一了机器学习生态系统.
*流处理
    * [faust](https://github.com/robinhood/faust) -流处理库，可移植来自 [Kafka Streams](https://kafka.apache.org/documentation/streams/) 到Python.
    * [streamparse](https://github.com/Parsely/streamparse) -通过实时数据流运行Python代码 [Apache Storm](http://storm.apache.org/).

## Distribution

*用于创建打包的可执行文件以进行发行的库.*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) -构建和分发Virtualenv作为Debian软件包.
* [Nuitka](http://nuitka.net/) -将脚本，模块，程序包编译为可执行文件或扩展模块.
* [py2app](http://pythonhosted.org/py2app/) -冻结Python脚本（Mac OS X）.
* [py2exe](http://www.py2exe.org/) -冻结Python脚本（Windows）.
* [pyarmor](https://github.com/dashingsoft/pyarmor) -用于混淆python脚本，将混淆后的脚本绑定到固定计算机或使混淆后的脚本失效的工具.
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) -将Python程序转换为独立的可执行文件（跨平台）.
* [pynsist](http://pynsist.readthedocs.io/en/latest/) -安装Windows的工具，安装程序捆绑Python本身.
* [shiv](https://github.com/linkedin/shiv) -命令行实用程序，用于构建完全独立的zipapp（PEP 441），但包括其所有依赖性.

## Documentation

*用于生成项目文档的库.*

* [sphinx](https://github.com/sphinx-doc/sphinx/) -Python文档生成器.
    * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc)
* [pdoc](https://github.com/mitmproxy/pdoc) -替换Epydoc以自动生成Python库的API文档.
* [pycco](https://github.com/pycco-docs/pycco) -识字编程风格的文档生成器.

## Downloader

*要下载的库.*

* [akshare](https://github.com/jindaxiang/akshare) -为人类建立的财务数据接口库！
* [s3cmd](https://github.com/s3tools/s3cmd) -用于管理Amazon S3和CloudFront的命令行工具.
* [s4cmd](https://github.com/bloomreach/s4cmd) -超级S3命令行工具，可提高性能.
* [you-get](https://you-get.org/) -用Python 3编写的YouTube / Youku / Niconico视频下载器.
* [youtube-dl](https://rg3.github.io/youtube-dl/) -一个小型命令行程序，可从YouTube下载视频.

## E-commerce

*用于电子商务和支付的框架和库.*

* [alipay](https://github.com/lxneng/alipay) -适用于Python的非官方支付宝API.
* [Cartridge](https://github.com/stephenmcd/cartridge) -使用夹层构建的购物车应用.
* [django-oscar](http://oscarcommerce.com/) -Django的开源电子商务框架.
* [django-shop](https://github.com/awesto/django-shop) -基于Django的商店系统.
* [forex-python](https://github.com/MicroPyramid/forex-python) -汇率，比特币价格指数和货币换算.
* [merchant](https://github.com/agiliq/merchant) -一个Django应用，可以接受来自各种付款处理商的付款.
* [money](https://github.com/carlospalol/money) -`Money`类，具有可选的CLDR支持的语言环境感知格式和可扩展的货币兑换.
* [python-currencies](https://github.com/Alir3z4/python-currencies) -显示货币格式及其肮脏的货币.
* [saleor](http://getsaleor.com/) -Django的电子商务店面.
* [shoop](https://www.shuup.com/en/) -基于Django的开源电子商务平台.

## Editor Plugins and IDEs

*埃马克斯
    * [elpy](https://github.com/jorgenschaefer/elpy) -Emacs Python开发环境.
*崇高的文字
    * [anaconda](https://github.com/DamnWidget/anaconda) -Anaconda可在功能齐全的Python开发IDE中转换Sublime Text 3.
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) -出色的自动完成库Jedi的Sublime Text插件.
* 我来了
    * [jedi-vim](https://github.com/davidhalter/jedi-vim) -用于Python的Jedi自动完成库的Vim绑定.
    * [python-mode](https://github.com/python-mode/python-mode) -用于将Vim转换为Python IDE的多合一插件.
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) -包括 [Jedi](https://github.com/davidhalter/jedi)基于Python的完成引擎.
* 视觉工作室
    * [PTVS](https://github.com/Microsoft/PTVS) -适用于Visual Studio的Python工具.
* Visual Studio代码
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) -官方VSCode扩展，具有对Python的丰富支持.
* IDE
    * [PyCharm](https://www.jetbrains.com/pycharm/)  -JetBrains的商业Python IDE. 有免费的社区版.
    * [spyder](https://github.com/spyder-ide/spyder) -开源Python IDE.

## Email

*用于发送和解析电子邮件的库.

*邮件服务器
    * [modoboa](https://github.com/modoboa/modoboa) -包含现代Web UI的邮件托管和管理平台.
    * [salmon](https://github.com/moggers87/salmon) -Python邮件服务器.
*客户
    * [imbox](https://github.com/martinrusev/imbox) -适用于人类的Python IMAP.
    * [yagmail](https://github.com/kootenpv/yagmail) -另一个Gmail / SMTP客户端.
* 其他
    * [flanker](https://github.com/mailgun/flanker) -电子邮件地址和Mime解析库.
    * [mailer](https://github.com/marrow/mailer) -高性能可扩展邮件传递框架.

## Enterprise Application Integrations

*用于企业环境中系统集成的平台和工具*

* [Zato](https://zato.io) -Python中的ESB，SOA，REST，API和云集成.

## Environment Management

*用于Python版本和虚拟环境管理的库.*

* [pyenv](https://github.com/pyenv/pyenv) -简单的Python版本管理.
* [virtualenv](https://github.com/pypa/virtualenv) -创建隔离的Python环境的工具.

## Files

*用于文件操作和MIME类型检测的库.

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) -（Python标准库）将文件名映射到MIME类型.
* [path.py](https://github.com/jaraco/path.py) -用于的模块包装 [os.path](https://docs.python.org/3/library/os.path.html).
* [pathlib](https://docs.python.org/3/library/pathlib.html) -（Python标准库）一个跨平台的，面向对象的路径库.
* [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2) -Python的文件系统抽象层.
* [python-magic](https://github.com/ahupp/python-magic) -libmagic文件类型标识库的Python接口.
* [Unipath](https://github.com/mikeorr/Unipath) -面向对象的文件/目录操作方法.
* [watchdog](https://github.com/gorakhargosh/watchdog) -用于监视文件系统事件的API和Shell实用程序.

## Foreign Function Interface

*用于提供外来功能接口的库.

* [cffi](https://pypi.org/project/cffi/) -外部函数接口，用于Python调用C代码.
* [ctypes](https://docs.python.org/3/library/ctypes.html) -（Python标准库）用于Python调用C代码的外函数接口.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) -Nvidia的CUDA API的Python包装器.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) -简化的包装器和接口生成器.

## Forms

*用于处理表单的库.*

* [Deform](https://github.com/Pylons/deform) -受正式表单生成库影响的Python HTML表单生成库.
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) -Bootstrap 3与Django的集成.
* [django-bootstrap4](https://github.com/zostera/django-bootstrap4) -Bootstrap 4与Django的集成.
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms) -Django应用程式，可让您以非常优雅且干燥的方式建立漂亮的表格.
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) -独立于平台的Django表单序列化程序.
* [WTForms](https://github.com/wtforms/wtforms) -灵活的表单验证和渲染库.

## Functional Programming

*使用Python进行功能编程.*

* [Coconut](https://github.com/evhub/coconut) -为简单，优雅，Pythonic函数式编程而构建的Python变体.
* [CyToolz](https://github.com/pytoolz/cytoolz/) -“工具”的Cython实现：高性能功能实用程序.
* [fn.py](https://github.com/kachayev/fn.py) -Python中的函数式编程：实现缺少功能以享受FP.
* [funcy](https://github.com/Suor/funcy) -精美实用的功能工具.
* [more-itertools](https://github.com/erikrose/more-itertools) -除了`itertools`之外，还有更多用于操作可迭代程序的例程.
* [returns](https://github.com/dry-python/returns) -一组类型安全的monad，转换器和合成实用程序.
* [Toolz](https://github.com/pytoolz/toolz) -用于迭代器，函数和字典的函数实用程序的集合.

## GUI Development

*用于处理图形用户界面应用程序的库.

* [curses](https://docs.python.org/3/library/curses.html) 内置包装 [ncurses](http://www.gnu.org/software/ncurses/) 用于创建终端GUI应用程序.
* [Eel](https://github.com/ChrisKnott/Eel) -用于制作简单的类似电子的脱机HTML / JS GUI应用程序的库.
* [enaml](https://github.com/nucleic/enaml) -使用声明性语法（如QML）创建漂亮的用户界面.
* [Flexx](https://github.com/zoofIO/flexx) -Flexx是用于创建GUI的纯Python工具箱，它使用Web技术进行呈现.
* [Gooey](https://github.com/chriskiehl/Gooey) -使用命令行将命令行程序转换为完整的GUI应用程序.
* [kivy](https://kivy.org/) -用于创建在Windows，Linux，Mac OS X，Android和iOS上运行的NUI应用程序的库.
* [pyglet](https://github.com/pyglet/pyglet) -适用于Python的跨平台窗口和多媒体库.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) -GLib / GObject / GIO / GTK +（GTK + 3）的Python绑定.
* [PyQt](https://riverbankcomputing.com/software/pyqt/intro) -的Python绑定 [Qt](https://www.qt.io/) 跨平台应用程序和UI框架.
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) -tkinter，Qt，WxPython和Remi的包装器.
* [pywebview](https://github.com/r0x0r/pywebview/) -围绕Webview组件的轻型跨平台本机包装.
* [Tkinter](https://wiki.python.org/moin/TkInter) -Tkinter是Python的事实上的标准GUI软件包.
* [Toga](https://github.com/pybee/toga) -Python本机，OS本机GUI工具包.
* [urwid](http://urwid.org/) -一个用于创建终端GUI应用程序的库，该应用程序对窗口小部件，事件，丰富的颜色等具有强大的支持.
* [wxPython](https://wxpython.org/) -wxWidgets C ++类库与Python的混合.
* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) -一个简单的GPU加速的Python GUI框架

## GraphQL

*使用GraphQL的库.*

* [graphene](https://github.com/graphql-python/graphene/) -适用于Python的GraphQL框架.
* [tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp/) -Tartiflette的基于aiohttp的包装器，用于通过HTTP公开GraphQL API.
* [tartiflette-asgi](https://github.com/tartiflette/tartiflette-asgi/) -Tartiflette GraphQL引擎的ASGI支持.
* [tartiflette](https://tartiflette.io) -适用于Python 3.6及更高版本和asyncio的SDL优先GraphQL引擎实现.

## Game Development

*很棒的游戏开发库.*

* [Arcade](https://arcade.academy/index.html) -Arcade是一个现代Python框架，用于制作具有引人注目的图形和声音的游戏.
* [Cocos2d](http://cocos2d.org/) -cocos2d是用于构建2D游戏，演示和其他图形/交互应用程序的框架.
* [Harfang3D](http://www.harfang3d.com) -用于3D，VR和游戏开发的Python框架.
* [Panda3D](https://www.panda3d.org/) -迪士尼开发的3D游戏引擎.
* [Pygame](http://www.pygame.org/news.html) -Pygame是一组旨在编写游戏的Python模块.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) -用于Ogre 3D渲染引擎的Python绑定，可用于游戏，模拟和任何3D.
* [PyOpenGL](http://pyopengl.sourceforge.net/) -OpenGL及其相关API的Python ctypes绑定.
* [PySDL2](https://pysdl2.readthedocs.io) -SDL2库的基于ctypes的包装器.
* [RenPy](https://www.renpy.org/) -Visual Novel引擎.

## Geolocation

*用于对地址进行地理编码以及使用纬度和经度的库.*

* [django-countries](https://github.com/SmileyChris/django-countries) -一个Django应用，可为模型和表单提供国家/地区字段.
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) -世界一流的地理网络框架.
* [GeoIP](https://github.com/maxmind/geoip-api-python) -用于MaxMind GeoIP旧版数据库的Python API.
* [geojson](https://github.com/frewsxcv/python-geojson) -GeoJSON的Python绑定和实用程序.
* [geopy](https://github.com/geopy/geopy) -Python地理编码工具箱.

## HTML Manipulation

*用于HTML和XML的库.

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) -提供Pythonic习惯用法，用于迭代，搜索和修改HTML或XML.
* [bleach](https://github.com/mozilla/bleach) -基于白名单的HTML清理和文本链接库.
* [cssutils](https://pypi.org/project/cssutils/) -Python的CSS库.
* [html5lib](https://github.com/html5lib/html5lib-python) -符合标准的库，用于解析和序列化HTML文档和片段.
* [lxml](http://lxml.de/) -一个非常快速，易于使用的通用库，用于处理HTML和XML.
* [MarkupSafe](https://github.com/pallets/markupsafe) -为Python实现XML / HTML / XHTML标记安全字符串.
* [pyquery](https://github.com/gawel/pyquery) -用于解析HTML的类似于jQuery的库.
* [untangle](https://github.com/stchris/untangle) -将XML文档转换为Python对象以便于访问.
* [WeasyPrint](http://weasyprint.org) -用于HTML和CSS的可视化呈现引擎，可以导出为PDF.
* [xmldataset](https://xmldataset.readthedocs.io/en/latest/) -简单的XML解析.
* [xmltodict](https://github.com/martinblech/xmltodict) -使用XML就像使用JSON.

## HTTP Clients

*使用HTTP的库.*

* [grequests](https://github.com/spyoungtech/grequests) -请求+ gevent用于异步HTTP请求.
* [httplib2](https://github.com/httplib2/httplib2) -全面的HTTP客户端库.
* [httpx](https://github.com/encode/httpx) -用于Python的下一代HTTP客户端.
* [requests](https://github.com/psf/requests) -人类的HTTP请求.
* [treq](https://github.com/twisted/treq) -诸如Twisted的HTTP客户端之上的API之类的Python请求.
* [urllib3](https://github.com/shazow/urllib3) -具有线程安全连接池的HTTP库，文件发布支持，健全性.

## Hardware

*用于硬件编程的库.*

* [ino](http://inotool.org/) -用于处理的命令行工具包 [Arduino](https://www.arduino.cc/).
* [keyboard](https://github.com/boppreh/keyboard) -在Windows和Linux上挂钩并模拟全局键盘事件.
* [mouse](https://github.com/boppreh/mouse) -在Windows和Linux上挂钩并模拟全局鼠标事件.
* [Pingo](http://www.pingo.io/) -Pingo为编程设备提供了统一的API，例如Raspberry Pi，pcDuino，Intel Galileo等.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) -用于鼠标和键盘的跨平台控制的模块.
* [scapy](https://github.com/secdev/scapy) -出色的数据包处理库.
* [wifi](https://github.com/rockymeza/wifi) -用于在Linux上使用WiFi的Python库和命令行工具.

## Image Processing

*用于处理图像的库.*

* [hmap](https://github.com/rossgoodwin/hmap) -图像直方图重新映射.
* [imgSeek](https://sourceforge.net/projects/imgseek/) -使用视觉相似性搜索图像集合的项目.
* [nude.py](https://github.com/hhatto/nude.py) -裸露检测.
* [pagan](https://github.com/daboth/pagan) -基于输入字符串和哈希值的Retro identicon（Avatar）生成.
* [pillow](https://github.com/python-pillow/Pillow) -枕头很友好 [PIL](http://www.pythonware.com/products/pil/) 叉子.
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) -在Python中创建条形码，没有任何额外的依赖关系.
* [pygram](https://github.com/ajkumar25/pygram) -类似Instagram的图像过滤器.
* [PyMatting](http://github.com/pymatting/pymatting) -Alpha遮罩库.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) -一个纯Python QR Code生成器.
* [pywal](https://github.com/dylanaraps/pywal) -一种从图像生成配色方案的工具.
* [pyvips](https://github.com/libvips/pyvips) -具有低内存需求的快速图像处理库.
* [Quads](https://github.com/fogleman/Quads) -基于四叉树的计算机艺术.
* [scikit-image](http://scikit-image.org/) -用于（科学）图像处理的Python库.
* [thumbor](https://github.com/thumbor/thumbor)  -智能影像服务. 它可以按需裁剪，调整图像大小和翻转图像.
* [wand](https://github.com/dahlia/wand) -的Python绑定 [MagickWand](http://www.imagemagick.org/script/magick-wand.php)，ImageMagick的C API.

## Implementations

* Python的实现.*

* [CLPython](https://github.com/metawilm/cl-python) -以Common Lisp编写的Python编程语言的实现.
* [CPython](https://github.com/python/cpython) -**默认的，最广泛使用的用C语言编写的Python编程语言的实现.**
* [Cython](http://cython.org/) -针对Python优化静态编译器.
* [Grumpy](https://github.com/google/grumpy) -更多的编译器比更强大的CPython2.7替换（alpha）解释器.
* [IronPython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C#.
* [Jython](https://hg.python.org/jython) -为JVM用Java编写的Python编程语言的实现.
* [MicroPython](https://github.com/micropython/micropython) -精简高效的Python编程语言实现.
* [Numba](http://numba.pydata.org/) -针对科学Python的LLVM的Python JIT编译器.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) -嵌入在Python中的x86-64汇编器.
* [Pyjion](https://github.com/Microsoft/Pyjion) -基于CoreCLR的Python JIT.
* [PyPy](https://foss.heptapod.net/pypy/pypy) -Python语言的非常快速且合规的实现.
* [Pyston](https://github.com/dropbox/pyston) -使用JIT技术的Python实现.
* [Stackless Python](https://github.com/stackless-dev/stackless) -Python编程语言的增强版本.

## Interactive Interpreter

*交互式Python解释器（REPL）.*

* [bpython](https://github.com/bpython/bpython) -精美的Python解释器接口.
* [Jupyter Notebook (IPython)](https://jupyter.org) -丰富的工具包，可帮助您充分利用Python的交互功能.
    * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)
* [ptpython](https://github.com/jonathanslenders/ptpython) -建立在 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).

## Internationalization

*用于i18n的库.*

* [Babel](http://babel.pocoo.org/en/latest/) -Python的国际化库.
* [PyICU](https://github.com/ovalhub/pyicu) -Unicode C ++库的国际组件的包装（[ICU](http://site.icu-project.org/)).

## Job Scheduler

*用于计划作业的库.*

* [Airflow](https://airflow.apache.org/) -Airflow是一个以编程方式编写，安排和监视工作流的平台.
* [APScheduler](http://apscheduler.readthedocs.io/en/latest/) -轻巧但功能强大的进程内任务计划程序，可让您计划功能.
* [django-schedule](https://github.com/thauber/django-schedule) -适用于Django的日历应用程序.
* [doit](http://pydoit.org/) -任务运行器和构建工具.
* [gunnery](https://github.com/gunnery/gunnery) -具有基于Web界面的分布式系统的多功能任务执行工具.
* [Joblib](https://joblib.readthedocs.io/) -一组用于在Python中提供轻量级流水线的工具.
* [Plan](https://github.com/fengsp/plan) -像用魅惑一样用Python编写crontab文件.
* [Prefect](https://github.com/PrefectHQ/prefect) -现代的工作流程编排框架，可轻松构建，调度和监视强大的数据管道.
* [schedule](https://github.com/dbader/schedule) -针对人类的Python作业调度.
* [Spiff](https://github.com/knipknap/SpiffWorkflow) -用纯Python实现的功能强大的工作流引擎.
* [TaskFlow](https://docs.openstack.org/developer/taskflow/) -一个Python库，可帮助您轻松，一致且可靠地执行任务.

## Logging

*用于生成和使用日志的库.*

* [logbook](http://logbook.readthedocs.io/en/stable/) -记录Python的替代品.
* [logging](https://docs.python.org/3/library/logging.html) -（Python标准库）Python的日志记录工具.
* [loguru](https://github.com/Delgan/loguru) -旨在以Python带来令人愉悦的日志记录的库.
* [sentry-python](https://github.com/getsentry/sentry-python) -适用于Python的Sentry SDK.
* [structlog](https://www.structlog.org/en/stable/) -结构化日志变得容易.

## Machine Learning

 *机器学习图书馆. 另见 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [gym](https://github.com/openai/gym) -用于开发和比较强化学习算法的工具包.
* [H2O](https://github.com/h2oai/h2o-3) -开源快速可扩展机器学习平台.
* [Metrics](https://github.com/benhamner/Metrics) -机器学习评估指标.
* [NuPIC](https://github.com/numenta/nupic) -Numenta智能计算平台.
* [scikit-learn](http://scikit-learn.org/) -最受欢迎的机器学习Python库.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)的可扩展机器学习库.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) -用于的轻量级Python包装器 [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).
* [xgboost](https://github.com/dmlc/xgboost) -可扩展，可移植和分布式的梯度增强库.
* [MindsDB](https://github.com/mindsdb/mindsdb) -MindsDB是用于现有数据库的开源AI层，可让您使用标准查询轻松地开发，训练和部署最新的机器学习模型.

## Microsoft Windows

*在Microsoft Windows上进行Python编程.

* [Python(x,y)](http://python-xy.github.io/) -基于Qt和Spyder的面向科学应用程序的Python发行版.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) -用于Python扩展包的非官方Windows二进制文件.
* [PythonNet](https://github.com/pythonnet/pythonnet) -与.NET公共语言运行库（CLR）的Python集成.
* [PyWin32](https://github.com/mhammond/pywin32) -Windows的Python扩展.
* [WinPython](https://winpython.github.io/) -Windows 7/8的可移植开发环境.

## Miscellaneous

*不属于上述类别的有用的库或工具.*

* [blinker](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system.
* [boltons](https://github.com/mahmoud/boltons) -一组纯Python实用程序.
* [itsdangerous](https://github.com/pallets/itsdangerous) -各种帮助程序，将可信数据传递到不可信环境.
* [magenta](https://github.com/magenta/magenta) -使用人工智能产生音乐和艺术的工具.
* [pluginbase](https://github.com/mitsuhiko/pluginbase) -一个简单但灵活的Python插件系统.
* [tryton](http://www.tryton.org/) -通用业务框架.

## Natural Language Processing

*使用人类语言的图书馆.*

- 一般
    * [gensim](https://github.com/RaRe-Technologies/gensim) -人类主题建模.
    * [langid.py](https://github.com/saffsd/langid.py) -独立的语言识别系统.
    * [nltk](http://www.nltk.org/) -用于构建Python程序以使用人类语言数据的领先平台.
    * [pattern](https://github.com/clips/pattern) -网络挖掘模块.
    * [polyglot](https://github.com/aboSamoor/polyglot) -支持数百种语言的自然语言管道.
    * [pytext](https://github.com/facebookresearch/pytext) -基于PyTorch的自然语言建模框架.
    * [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) -一个工具包，可用于研究的快速深度学习NLP原型.
    * [spacy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
    * [Stanza](https://github.com/stanfordnlp/stanza) -Stanford NLP Group的官方Python库，支持60多种语言.
-中文
    * [funNLP](https://github.com/fighting41love/funNLP) -中文NLP的工具和数据集的集合.
    * [jieba](https://github.com/fxsjy/jieba) -最受欢迎的中文文本分割库.
    * [pkuseg-python](https://github.com/lancopku/pkuseg-python) -用于各个领域的中文分词的工具包.
    * [snownlp](https://github.com/isnowfy/snownlp) -用于处理中文文本的库.

## Network Virtualization

*用于虚拟网络和SDN（软件定义网络）的工具和库.*

* [mininet](https://github.com/mininet/mininet) -用Python编写的流行网络模拟器和API.
* [napalm](https://github.com/napalm-automation/napalm) -跨供应商API，用于操纵网络设备.
* [pox](https://github.com/noxrepo/pox) -基于Python的SDN控制应用程序，例如OpenFlow SDN控制器.

## News Feed

*用于建立用户活动的库.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) -根据您网站上的操作生成常规活动流.
* [Stream Framework](https://github.com/tschellenbach/Stream-Framework) -使用Cassandra和Redis构建新闻提要和通知系统.

## ORM

*实现对象关系映射或数据映射技术的库.

*关系数据库
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) -Django ORM.
    * [SQLAlchemy](https://www.sqlalchemy.org/) -Python SQL工具包和对象关系映射器.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
    * [dataset](https://github.com/pudo/dataset) -将Python字典存储在数据库中-与SQLite，MySQL和PostgreSQL一起使用.
    * [orator](https://github.com/sdispater/orator) -  The Orator ORM provides a simple yet beautiful ActiveRecord implementation.
    * [orm](https://github.com/encode/orm) -异步ORM.
    * [peewee](https://github.com/coleifer/peewee) -一个小的，富有表现力的ORM.
    * [pony](https://github.com/ponyorm/pony/) -ORM，提供面向生成器的SQL接口.
    * [pydal](https://github.com/web2py/pydal/) -一个纯Python数据库抽象层.
* NoSQL数据库
    * [hot-redis](https://github.com/stephenmcd/hot-redis) -Redis的丰富Python数据类型.
    * [mongoengine](https://github.com/MongoEngine/mongoengine) -用于MongoDB的Python对象文档映射器.
    * [PynamoDB](https://github.com/pynamodb/PynamoDB) -用于的Pythonic界面 [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).
    * [redisco](https://github.com/kiddouk/redisco) -用于Redis的简单模型和容器的Python库.

## Package Management

*用于程序包和依赖项管理的库.

* [pip](https://pip.pypa.io/en/stable/) -Python的软件包安装程序.
    * [pip-tools](https://github.com/jazzband/pip-tools) -一组用于使固定的Python依赖关系保持最新的工具.
    * [PyPI](https://pypi.org/)
* [conda](https://github.com/conda/conda/) -跨平台，与Python无关的二进制软件包管理器.
* [poetry](https://github.com/sdispater/poetry) -Python依赖关系管理和打包变得容易.

## Package Repositories

*本地PyPI存储库服务器和代理.

* [bandersnatch](https://github.com/pypa/bandersnatch/) -由Python包装规范（PyPA）提供的PyPI镜像工具.
* [devpi](https://github.com/devpi/devpi) -PyPI服务器和包装/测试/发布工具.
* [localshop](https://github.com/jazzband/localshop) -本地PyPI服务器（自定义程序包和pypi的自动镜像）.
* [warehouse](https://github.com/pypa/warehouse) -下一代Python软件包存储库（PyPI）.

## Penetration Testing

*用于渗透测试的框架和工具.

* [fsociety](https://github.com/Manisso/fsociety) -渗透测试框架.
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) -社会工程工具包.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) -自动SQL注入和数据库接管工具.

## Permissions

*允许或拒绝用户访问数据或功能的图书馆.*

* [django-guardian](https://github.com/django-guardian/django-guardian) -为Django 1.2+实现每个对象的权限
* [django-rules](https://github.com/dfunckt/django-rules) -一个小巧但功能强大的应用程序，无需数据库即可提供对Django的对象级权限.

## Processes

*用于启动和与OS进程通信的库.

* [delegator.py](https://github.com/amitt001/delegator.py) - [Subprocesses](https://docs.python.org/3/library/subprocess.html) 适用于人类2.0.
* [sarge](https://sarge.readthedocs.io/en/latest/) -子流程的另一个包装.
* [sh](https://github.com/amoffat/sh) -完善的Python子流程.

## Recommender Systems

*用于构建推荐系统的库.*

* [annoy](https://github.com/spotify/annoy) -C ++ / Python中的近似最近邻居已针对内存使用进行了优化.
* [fastFM](https://github.com/ibayer/fastFM) -分解机库.
* [implicit](https://github.com/benfred/implicit) -对隐式数据集进行协作过滤的快速Python实现.
* [libffm](https://github.com/guestwalk/libffm) -现场感知分解机（FFM）库.
* [lightfm](https://github.com/lyst/lightfm) -许多流行的推荐算法的Python实现.
* [spotlight](https://github.com/maciejkula/spotlight) -使用PyTorch的深度推荐器模型.
* [Surprise](https://github.com/NicolasHug/Surprise) -用于构建和分析推荐系统的scikit.
* [tensorrec](https://github.com/jfkirk/tensorrec) -TensorFlow中的推荐引擎框架.

## Refactoring

*用于Python的重构工具和库*

 * [Bicycle Repair Man](http://bicyclerepair.sourceforge.net/) -Bicycle Repair Man，Python的重构工具.
 * [Bowler](https://pybowler.io/) -现代Python的安全代码重构.
 * [Rope](https://github.com/python-rope/rope) -Rope是python重构库.

## RESTful API

*用于构建RESTful API的库.

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) -强大且灵活的工具包，用于构建Web API.
    * [django-tastypie](http://tastypieapi.org/) -为Django应用创建美味的API.
* 烧瓶
    * [eve](https://github.com/pyeve/eve) -由Flask，MongoDB和良好意图支持的REST API框架.
    * [flask-api](https://github.com/flask-api/flask-api) -Flask的可浏览Web API.
    * [flask-restful](https://github.com/flask-restful/flask-restful) -快速构建Flask的REST API.
*金字塔
    * [cornice](https://github.com/Cornices/cornice) -金字塔的RESTful框架.
*与框架无关
    * [apistar](https://github.com/encode/apistar) -为Python 3设计的智能Web API框架.
    * [falcon](https://github.com/falconry/falcon) -用于构建云API和Web应用程序后端的高性能框架.
    * [fastapi](https://github.com/tiangolo/fastapi) -一种现代，快速的Web框架，用于基于标准Python类型提示使用Python 3.6+构建API.
    * [hug](https://github.com/hugapi/hug) -一个用于彻底公开API的Python 3框架.
    * [sandman2](https://github.com/jeffknupp/sandman2) -用于现有数据库驱动系统的自动化REST API.
    * [sanic](https://github.com/huge-success/sanic) -Python 3.6以上版本的Web服务器和Web框架，可以快速运行.
    * [vibora](https://vibora.io/) -受Flask启发的快速，高效和异步的Web框架.

## Robotics

*机器人技术库.*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) -这是具有可视化效果的各种机器人算法的汇编.
* [rospy](http://wiki.ros.org/rospy) -这是ROS（机器人操作系统）的库.

## RPC Servers

*RPC-compatible servers.*

* [RPyC](https://github.com/tomerfiliba/rpyc) （远程Python调用）-用于Python的透明且对称的RPC库
* [zeroRPC](https://github.com/0rpc/zerorpc-python) -zerorpc是基于以下内容的灵活RPC实现： [ZeroMQ](http://zeromq.org/) 和 [MessagePack](http://msgpack.org/).

## Science

 *科学计算图书馆. 另见 [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists).*

* [astropy](http://www.astropy.org/) -天文学社区Python库.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) -为全自动高通量测序分析提供最佳实践管道.
* [bccb](https://github.com/chapmanb/bcbb) -收集与生物学分析有关的有用代码.
* [Biopython](http://biopython.org/wiki/Main_Page) -Biopython是一套免费的生物计算工具.
* [cclib](http://cclib.github.io/) -用于解析和解释计算化学软件包结果的库.
* [Colour](http://colour-science.org/) -实施大量的色彩理论转换和算法.
* [Karate Club](https://github.com/benedekrozemberczki/karateclub) -用于图形结构化数据的无监督机器学习工具箱.
* [NetworkX](https://networkx.github.io/) -用于复杂网络的高生产率软件.
* [NIPY](http://nipy.org) -神经影像工具箱的集合.
* [NumPy](http://www.numpy.org/) -使用Python进行科学计算的基本软件包.
* [ObsPy](https://github.com/obspy/obspy/wiki/) -地震学的Python工具箱.
* [Open Babel](http://openbabel.org/wiki/Main_Page) -一种化学工具箱，旨在说多种化学数据语言.
* [PyDy](http://www.pydy.org/) -Python Dynamics的缩写，用于协助工作流进行动态运动建模.
* [PyMC](https://github.com/pymc-devs/pymc3) -马尔可夫链蒙特卡洛采样工具包.
* [QuTiP](http://qutip.org/) -Python中的Quantum Toolbox.
* [RDKit](http://www.rdkit.org/) -化学信息学和机器学习软件.
* [SciPy](https://www.scipy.org/) -用于数学，科学和工程的基于Python的开源软件生态系统.
* [SimPy](https://gitlab.com/team-simpy/simpy) -基于过程的离散事件模拟框架.
* [statsmodels](https://github.com/statsmodels/statsmodels) -Python中的统计建模和计量经济学.
* [SymPy](https://github.com/sympy/sympy) -用于符号数学的Python库.
* [Zipline](https://github.com/quantopian/zipline) -Pythonic算法交易库.

## Search

*用于对数据建立索引并执行搜索查询的库和软件.*

* [django-haystack](https://github.com/django-haystack/django-haystack) -模块化搜索Django.
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) -Elasticsearch的官方高级Python客户端.
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) -的官方低层Python客户端 [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [pysolr](https://github.com/django-haystack/pysolr) -用于的轻量级Python包装器 [Apache Solr](https://lucene.apache.org/solr/).
* [whoosh](http://whoosh.readthedocs.io/en/latest/) -快速的纯Python搜索引擎库.

## Serialization

*用于序列化复杂数据类型的库*

* [marshmallow](https://github.com/marshmallow-code/marshmallow) -用于将复杂对象与简单Python数据类型之间来回转换的轻量级库.
* [pysimdjson](https://github.com/TkTech/pysimdjson) -的Python绑定 [simdjson](https://github.com/lemire/simdjson).
* [python-rapidjson](https://github.com/python-rapidjson/python-rapidjson) -周围的Python包装器 [RapidJSON](https://github.com/Tencent/rapidjson).
* [ultrajson](https://github.com/esnme/ultrajson) -使用Python绑定用C编写的快速JSON解码器和编码器.

## Serverless Frameworks

*用于开发无服务器Python代码的框架.*

* [python-lambda](https://github.com/nficano/python-lambda) -用于在AWS Lambda中开发和部署Python代码的工具包.
* [Zappa](https://github.com/Miserlou/Zappa) -用于在AWS Lambda和API网关上部署WSGI应用程序的工具.

## Shell

*基于Python的Shell.*

* [xonsh](https://github.com/xonsh/xonsh/) -一种Python驱动的，跨平台，Unix视界的外壳语言和命令提示符.

## Specific Formats Processing

*用于解析和处理特定文本格式的库.

* 一般
    * [tablib](https://github.com/jazzband/tablib) -XLS，CSV，JSON，YAML中的表格数据集模块.
*办公室
    * [docxtpl](https://github.com/elapouya/python-docx-template) -通过jinja2模板编辑docx文档
    * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) -用于读取和写入Excel 2010 xlsx / xlsm / xltx / xltm文件的库.
    * [pyexcel](https://github.com/pyexcel/pyexcel) -提供一个用于读取，操作和写入csv，ods，xls，xlsx和xlsm文件的API.
    * [python-docx](https://github.com/python-openxml/python-docx) -读取，查询和修改Microsoft Word 2007/2008 docx文件.
    * [python-pptx](https://github.com/scanny/python-pptx) -用于创建和更新PowerPoint（.pptx）文件的Python库.
    * [unoconv](https://github.com/unoconv/unoconv) -在LibreOffice / OpenOffice支持的任何文档格式之间转换.
    * [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) -用于创建Excel .xlsx文件的Python模块.
    * [xlwings](https://github.com/ZoomerAnalytics/xlwings) -BSD许可的库，可轻松从Excel调用Python，反之亦然.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) -从Excel文件写入和读取数据以及格式化信息.
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) -从PDF文档中提取信息的工具.
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) -能够拆分，合并和转换PDF页面的库.
    * [ReportLab](https://www.reportlab.com/opensource/) -允许快速创建丰富的PDF文档.
*降价
    * [Mistune](https://github.com/lepture/mistune) -Markdown最快和全功能的纯Python解析器.
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) -John Gruber的Markdown的Python实现.
* YAML
    * [PyYAML](http://pyyaml.org/) -适用于Python的YAML实现.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) -用于转换为CSV并与CSV协同工作的实用程序.
*存档
    * [unp](https://github.com/mitsuhiko/unp) -可以轻松解压缩档案的命令行工具.

## Static Site Generator

*静态网站生成器是一款将一些文本+模板作为输入并在输出中生成HTML文件的软件.*

* [lektor](https://github.com/lektor/lektor) -易于使用的静态CMS和博客引擎.
* [mkdocs](https://github.com/mkdocs/mkdocs/) -Markdown友好的文档生成器.
* [makesite](https://github.com/sunainapai/makesite) -简单，轻巧且无魔力的静态站点/博客生成器（&lt;130行）.
* [nikola](https://github.com/getnikola/nikola) -静态网站和博客生成器.
* [pelican](https://github.com/getpelican/pelican) -支持Markdown和reST语法的静态站点生成器.

## Tagging

*用于标记项目的库.*

* [django-taggit](https://github.com/jazzband/django-taggit) -Django的简单标记.

## Task Queues

*用于处理任务队列的库.

* [celery](https://docs.celeryproject.org/en/stable/) -基于分布式消息传递的异步任务队列/作业队列.
* [daramatiq](https://github.com/Bogdanp/dramatiq) -适用于Python 3的快速可靠的后台任务处理库.
* [huey](https://github.com/coleifer/huey) -很少的多线程任务队列.
* [mrq](https://github.com/pricingassistant/mrq) -使用Redis和gevent的Python中的分布式工作者任务队列.
* [rq](https://github.com/rq/rq) -适用于Python的简单作业队列.

## Template Engine

*用于模板化和词法化的库和工具.

* [Genshi](https://genshi.edgewall.org/) -用于生成网络感知输出的Python模板工具包.
* [Jinja2](https://github.com/pallets/jinja) -一种现代且设计师友好的模板语言.
* [Mako](http://www.makotemplates.org/) -适用于Python平台的超快速和轻量级模板.

## Testing

*用于测试代码库和生成测试数据的库.

*测试框架
    * [hypothesis](https://github.com/HypothesisWorks/hypothesis) -假设是一个高级的Quickcheck样式基于属性的测试库.
    * [nose2](https://github.com/nose-devs/nose2) -基于“ unittest2”的“鼻子”的后继者.
    * [pytest](https://docs.pytest.org/en/latest/) -成熟的功能齐全的Python测试工具.
    * [Robot Framework](https://github.com/robotframework/robotframework) -通用的测试自动化框架.
    * [unittest](https://docs.python.org/3/library/unittest.html) -（Python标准库）单元测试框架.
*测试选手
    * [green](https://github.com/CleanCut/green) -干净，多彩的测试运行器.
    * [mamba](http://nestorsalceda.github.io/mamba/)  -Python的权威测试工具. 生于BDD的旗帜下.
    * [tox](https://tox.readthedocs.io/en/latest/) -自动构建和测试多个Python版本的发行版
* GUI / Web Testing
    * [locust](https://github.com/locustio/locust) -用Python编写的可扩展用户负载测试工具.
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) -PyAutoGUI是人类的跨平台GUI自动化Python模块.
    * [Schemathesis](https://github.com/kiwicom/schemathesis) -使用Open API / Swagger规范构建的Web应用程序基于属性的自动测试工具.
    * [Selenium](https://pypi.org/project/selenium/) -的Python绑定 [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [sixpack](https://github.com/seatgeek/sixpack) -与语言无关的A / B测试框架.
    * [splinter](https://github.com/cobrateam/splinter) -用于测试Web应用程序的开源工具.
*模拟
    * [doublex](https://pypi.org/project/doublex/) -强大的Python测试框架加倍.
    * [freezegun](https://github.com/spulec/freezegun) -通过模拟datetime模块穿越时间.
    * [httmock](https://github.com/patrys/httmock) -一个针对Python 2.6+和3.2+的请求的模拟库.
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) -适用于Python的HTTP请求模拟工具.
    * [mock](https://docs.python.org/3/library/unittest.mock.html) -（Python标准库）一个模拟和补丁库.
    * [mocket](https://github.com/mindflayer/python-mocket) -具有gevent / asyncio / SSL支持的套接字模拟框架.
    * [responses](https://github.com/getsentry/responses) -用于模拟请求Python库的实用程序库.
    * [VCR.py](https://github.com/kevin1024/vcrpy) -在测试中记录并重放HTTP交互.
*对象工厂
    * [factory_boy](https://github.com/FactoryBoy/factory_boy) -Python的测试装置替代品.
    * [mixer](https://github.com/klen/mixer)  -更换其他灯具. 支持Django，Flask，SQLAlchemy，Peewee等
    * [model_mommy](https://github.com/vandersonmota/model_mommy) -创建用于在Django中测试的随机装置.
*代码覆盖率
    * [coverage](https://pypi.org/project/coverage/) -代码覆盖率测量.
*假数据
    * [fake2db](https://github.com/emirozer/fake2db) -伪数据库生成器.
    * [faker](https://github.com/joke2k/faker) -生成伪造数据的Python包.
    * [mimesis](https://github.com/lk-geimfari/mimesis) -是一个Python库，可帮助您生成虚假数据.
    * [radar](https://pypi.org/project/radar/) -生成随机的日期时间/时间.

## Text Processing

*用于解析和处理纯文本的库.*

* 一般
    * [chardet](https://github.com/chardet/chardet) -与Python 2/3兼容的字符编码检测器.
    * [difflib](https://docs.python.org/3/library/difflib.html) -（Python标准库）用于计算增量的帮助程序.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) -使Unicode文本更容易打乱，更自动地保持一致.
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) -模糊字符串匹配.
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) -快速计算Levenshtein距离和字符串相似度.
    * [pangu.py](https://github.com/vinta/pangu.py) -偏执的文字间距.
    * [pyfiglet](https://github.com/pwaller/pyfiglet) -用Python编写的figlet的实现.
    * [pypinyin](https://github.com/mozillazg/python-pinyin) - Convert Chinese hanzi (汉字) to pinyin (拼音).
    * [textdistance](https://github.com/orsinium/textdistance) -使用30多种算法计算序列之间的距离.
    * [unidecode](https://pypi.org/project/Unidecode/) -Unicode文本的ASCII音译.
* Sl
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) -可以保留unicode的Python slugify库.
    * [python-slugify](https://github.com/un33k/python-slugify) -Python slugify库，可将unicode转换为ASCII.
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) -一个slugifier，它以Django为依赖关系生成unicode slug.
*唯一标识符
    * [hashids](https://github.com/davidaurelio/hashids-python) - 实施 [hashids](http://hashids.org) 在Python中.
    * [shortuuid](https://github.com/skorokithakis/shortuuid) -生成器库，用于生成简洁，明确和URL安全的UUID.
*解析器
    * [ply](https://github.com/dabeaz/ply) -为Python实现lex和yacc解析工具.
    * [pygments](http://pygments.org/) -通用语法荧光笔.
    * [pyparsing](https://github.com/pyparsing/pyparsing) -用于生成解析器的通用框架.
    * [python-nameparser](https://github.com/derek73/python-nameparser) -将人名解析为其各个组成部分.
    * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) -解析，格式化，存储和验证国际电话号码.
    * [python-user-agents](https://github.com/selwin/python-user-agents) -浏览器用户代理解析器.
    * [sqlparse](https://github.com/andialbrecht/sqlparse) -非验证SQL解析器.

## Third-party APIs

 *用于访问第三方服务API的库. 另见 [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [apache-libcloud](https://libcloud.apache.org/) -一个适用于所有云的Python库.
* [boto3](https://github.com/boto/boto3) -Amazon Web Services的Python接口.
* [django-wordpress](https://github.com/istrategylabs/django-wordpress) -Django的WordPress模型和视图.
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) -Facebook平台Python SDK.
* [google-api-python-client](https://github.com/google/google-api-python-client) -适用于Python的Google API客户端库.
* [gspread](https://github.com/burnash/gspread) -Google Spreadsheets Python API.
* [twython](https://github.com/ryanmcgrath/twython) -Twitter API的Python包装器.

## URL Manipulation

*用于解析URL的库.

* [furl](https://github.com/gruns/furl) -一个小的Python库，使解析和操作URL变得容易.
* [purl](https://github.com/codeinthehole/purl) -简单，不可变的URL类，带有用于查询和操作的干净API.
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) -纯Python URL缩短库.
* [webargs](https://github.com/marshmallow-code/webargs) -友好的库，用于解析HTTP请求参数，并内置对流行的Web框架的支持.

## Video

*用于处理视频和GIF的库.

* [moviepy](https://zulko.github.io/moviepy/) -用于基于脚本的电影编辑的模块，具有多种格式，包括动画GIF.
* [scikit-video](https://github.com/aizvorski/scikit-video) -SciPy的视频处理例程.
* [vidgear](https://github.com/abhiTronix/vidgear) -最强大的多线程视频处理框架.

## Web Asset Management

*用于管理，压缩和最小化网站资产的工具.*

* [django-compressor](https://github.com/django-compressor/django-compressor) -将链接的和内联的JavaScript或CSS压缩到单个缓存的文件中.
* [django-pipeline](https://github.com/jazzband/django-pipeline) -Django的资产包装库.
* [django-storages](https://github.com/jschneier/django-storages) -Django的自定义存储后端集合.
* [fanstatic](http://www.fanstatic.org/en/latest/) -将静态文件依赖项打包，优化并作为Python包提供.
* [fileconveyor](http://wimleers.com/fileconveyor) -守护程序，用于检测文件并将其同步到CDN，S3和FTP.
* [flask-assets](https://github.com/miracle2k/flask-assets) -帮助您将Webassets集成到Flask应用中.
* [webassets](https://github.com/miracle2k/webassets) -捆绑，优化和管理静态资源的唯一缓存无效化URL.



* [html2text](https://github.com/Alir3z4/html2text) -将HTML转换为Markdown格式的文本.
* [python-readability](https://github.com/buriy/python-readability) -arc90的可读性工具的快速Python端口.
* [requests-html](https://github.com/psf/requests-html) -人类的Pythonic HTML解析.
* [sumy](https://github.com/miso-belica/sumy) -自动汇总文本文档和HTML页面的模块.
* [textract](https://github.com/deanmalmgren/textract) -从任何文档，Word，PowerPoint，PDF等中提取文本.
* [toapi](https://github.com/gaojiuli/toapi) -每个网站都提供API.

## Web Crawling

*图书馆自动刮网*.

* [cola](https://github.com/chineking/cola) -分布式爬网框架.
* [feedparser](https://pythonhosted.org/feedparser/) -通用Feed解析器.
* [grab](https://github.com/lorien/grab) -网站抓取框架.
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) -用于自动与网站进行交互的Python库.
* [portia](https://github.com/scrapinghub/portia) -Scrapy的视觉抓取.
* [pyspider](https://github.com/binux/pyspider) -强大的蜘蛛系统.
* [robobrowser](https://github.com/jmcarp/robobrowser) -一个简单的Pythonic库，无需独立的Web浏览器即可浏览Web.
* [scrapy](https://scrapy.org/) -快速的高级屏幕抓取和网络爬网框架.

## Web Frameworks

 *传统的全栈Web框架. 另见 [RESTful API](https://github.com/vinta/awesome-python#restful-api).*

*同步
    * [Django](https://www.djangoproject.com/) -Python中最受欢迎的网络框架.
        * [awesome-django](https://github.com/shahraizali/awesome-django)
        * [awesome-django](https://github.com/wsvincent/awesome-django)
    * [Flask](http://flask.pocoo.org/) -Python的微框架.
        * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
    * [Pyramid](https://pylonsproject.org/) -一个小型，快速，扎实的开源Python Web框架.
        * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid)
    * [Masonite](https://github.com/MasoniteFramework/masonite) -以开发人员为中心的现代Python Web框架.
*异步
    * [Tornado](http://www.tornadoweb.org/en/latest/) -Web框架和异步网络库.

## WebSocket

*用于WebSocket的库.*

* [autobahn-python](https://github.com/crossbario/autobahn-python) -Twisted和Python上的WebSocket和WAMP for Python [asyncio](https://docs.python.org/3/library/asyncio.html).
* [channels](https://github.com/django/channels) -适用于Django的开发人员友好型异步.
* [websockets](https://github.com/aaugustin/websockets) -一个用于构建WebSocket服务器和客户端的库，重点是正确性和简单性.

## WSGI Servers

*与WSGI兼容的Web服务器.

* [bjoern](https://github.com/jonashaag/bjoern) -异步，非常快，用C语言编写.
* [gunicorn](https://github.com/benoitc/gunicorn) -预分叉，部分用C编写.
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) -一个项目旨在使用C语言编写用于构建托管服务的完整堆栈.
* [waitress](https://github.com/Pylons/waitress) -多线程，为金字塔供电.
* [werkzeug](https://github.com/pallets/werkzeug) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

## Resources

在哪里发现学习资源或新的Python库.

## Books

- [Fluent Python](https://www.oreilly.com/library/view/fluent-python/9781491946237/)
- [Think Python](https://greenteapress.com/wp/think-python-2e/)

## Websites

*教程
    * [Full Stack Python](https://www.fullstackpython.com/)
    * [Python Cheatsheet](https://www.pythoncheatsheet.org/)
    * [Real Python](https://realpython.com)
    * [The Hitchhiker’s Guide to Python](https://docs.python-guide.org/)
    * [Ultimate Python study guide](https://github.com/huangsam/ultimate-python)
*图书馆
    * [Awesome Python @LibHunt](https://python.libhunt.com/)
* 其他
    * [Python ZEEF](https://python.zeef.com/alan.richmond)
    * [Pythonic News](https://news.python.sc/)
    * [What the f*ck Python!](https://github.com/satwikkansal/wtfpython)

## Newsletters

* [Awesome Python Newsletter](http://python.libhunt.com/newsletter)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Tricks](https://realpython.com/python-tricks/)
* [Python Weekly](http://www.pythonweekly.com/)

## Podcasts

* [Django Chat](https://djangochat.com/)
* [Podcast.\_\_init__](https://podcastinit.com/)
* [Python Bytes](https://pythonbytes.fm)
* [Running in Production](https://runninginproduction.com/)
* [Talk Python To Me](https://talkpython.fm/)
* [Test and Code](https://testandcode.com/)
* [The Real Python Podcast](https://realpython.com/podcasts/rpp/)

## Contributing

永远欢迎您的贡献！ 请看看 [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) 第一.

如果不确定这些库是否很棒，我将打开一些拉取请求，您可以 [vote for them](https://github.com/vinta/awesome-python/pulls) 通过添加：+1：给他们. 当请求的投票达到** 20 **时，合并请求将被合并.

- - -

如果您对此清单有任何疑问，请随时与我联系 [@VintaChen](https://twitter.com/VintaChen) 在Twitter上或在GitHub上发布问题.
