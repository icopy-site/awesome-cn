<div class="github-widget" data-repo="typeddjango/awesome-python-typing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Python Typing [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Gitter](https://img.shields.io/gitter/room/mypy-django/Lobby?color=9cf&style=flat-square)][TypedDjango]

很棒的Python类型，存根，插件和与之配合使用的工具的集合.




[Full list of typed projects on PyPi](https://pypi.org/search/?q=&o=&c=Typing+%3A%3A+Typed) 在这儿.


## Static type checkers

- [mypy](https://github.com/python/mypy) -适用于Python 3和2的可选静态类型（PEP 484）.
- [pyre](https://pyre-check.org/) -适用于Python 3的性能类型检查器.
- [pytype](https://github.com/google/pytype) -用于检查和推断Python代码类型的工具-无需类型注释.
- [PyCharm](https://www.jetbrains.com/pycharm/) -专业开发人员的IDE.
- [pyright](https://github.com/Microsoft/pyright)  -快速类型检查器，适用于大型Python源库. 它可以在“监视”模式下运行，并在修改文件后执行快速的增量更新.
- [pyanalyze](https://github.com/quora/pyanalyze) -适用于Python的可扩展静态分析器和类型检查器.

## Dynamic type checkers

- [beartype](https://github.com/beartype/beartype) -纯Python中难以置信的`O（1）`运行时类型检查. 
- [pytypes](https://github.com/Stewori/pytypes) -提供了丰富的实用程序，用于运行时类型检查.
- [pydantic](https://github.com/samuelcolvin/pydantic)  -使用Python类型提示进行数据解析. 支持数据类.
- [typeguard](https://github.com/agronholm/typeguard) -另一个运行时类型检查器.
- [typical](https://github.com/seandstewart/typical/)  -使用类型提示进行数据解析和自动类型强制. 支持数据类，标准类，函数签名等.

## Stub packages

- [Typeshed](https://github.com/python/typeshed) -具有静态类型的Python库存根的集合.
- [django-stubs](https://github.com/typeddjango/django-stubs) -存根 [Django](https://github.com/django/django).
- [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) -存根 [DRF](https://github.com/encode/django-rest-framework).
- [numpy-stubs](https://github.com/numpy/numpy-stubs) -[NumPy]的存根.
<!--lint disable double-link-->
- [dry-python/returns](https://github.com/dry-python/returns) -存根 [returns](https://github.com/dry-python/returns).
<!--lint enable double-link-->
- [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) -存根 [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy).
- [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) -存根 [grpc](https://github.com/grpc/grpc).
- [boto3-stubs](https://github.com/vemel/mypy_boto3_builder) -存根 [boto3](https://github.com/boto/boto3).
- [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) -存根 [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
- [ordered-set-stubs](https://github.com/rominf/ordered-set-stubs) -存根 [OrderedSet](https://github.com/LuminosoInsight/ordered-set).
- [pyspark-stubs](https://github.com/zero323/pyspark-stubs) -存根 [PySpark](https://spark.apache.org/docs/latest/api/python/index.html).
- [pythonista-stubs](https://github.com/hbmartin/pythonista-stubs) -存根 [Pythonista](http://omz-software.com/pythonista/docs/ios/).
- [wsgitypes](https://github.com/shabbyrobe/wsgitypes)  -输入WSGI应用程序实现者. 这些不是存根文件，它们是您标记为支持的接口，以帮助您对WSGI一致性进行类型检查.
- [data-science-types](https://github.com/predictive-analytics-lab/data-science-types) -[NumPy]的存根， [pandas](https://github.com/pandas-dev/pandas)和 [Matplotlib](https://github.com/matplotlib/matplotlib).

## Backports and improvements

- [typed-ast](https://github.com/python/typed_ast) - Modified fork of CPython's ast module that parses `# type:` comments.
- [typing-extensions](https://github.com/python/typing/tree/master/typing_extensions) -反向移植和实验类型提示.
- [typingplus](https://github.com/contains-io/typingplus/) -支持反向移植，动态is_instance和抽象类型强制转换.
- [typet](https://github.com/contains-io/typet) -长度限制类型，动态对象验证.

## Tools

### Linters

- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) -有史以来最严格，最自以为是的python linter.
- [flake8-mypy](https://github.com/ambv/flake8-mypy) -用于集成mypy的flake8插件.
- [flake8-pyi](https://github.com/ambv/flake8-pyi) -Flake8插件，提供类型提示存根文件的专业化.
- [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) -flake8插件，用于验证注释的复杂性.
- [flake8-annotations](https://github.com/sco1/flake8-annotations) -flake8插件，用于检查函数定义中是否存在类型注释.

### Testing

- [pytest-mypy](https://github.com/dbader/pytest-mypy) -Pytest的Mypy静态类型检查器插件.
- [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) -Pytest插件，用于测试mypy类型，存根和插件.
- [pytest-mypy-testing](https://github.com/davidfritzsche/pytest-mypy-testing) -Pytest插件来测试mypy静态类型分析.

### Working with types

- [MonkeyType](https://github.com/instagram/MonkeyType) -收集函数参数和返回值的运行时类型，并可以基于运行时收集的类型自动生成存根文件，甚至将草稿类型注释直接添加到您的Python代码中.
- [merge_pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) -pytype工具链的一部分，将存根文件应用于源代码.
- [pyannotate](https://github.com/dropbox/pyannotate) -根据调用参数和运行时观察到的返回类型，将注释插入源代码中.
- [pytest-annotate](https://github.com/kensho-technologies/pytest-annotate) -pytest的Pyannotate插件.
- [retype](https://github.com/ambv/retype) -另一个将存根应用于代码的工具.
- [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) -从protobuf生成mypy存根的工具.
- [mypyc](https://github.com/python/mypy/tree/master/mypyc) -将经过mypy注释的静态类型的Python模块编译为CPython C扩展.
- [typing_inspect](https://github.com/ilevkivskyi/typing_inspect) -Typeing_inspect模块定义了实验性API，用于对Python标准键入模块中定义的类型进行运行时检查.
- [typing-json](https://pypi.org/project/typing-json/) -用于处理类型化对象和JSON的库.

### Mypy plugins

- [pynamodb-mypy](https://github.com/pynamodb/pynamodb-mypy) -插件 [PynamoDB](https://github.com/pynamodb/PynamoDB) 支持.
- [mypy-zope](https://github.com/Shoobx/mypy-zope) -插件 [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) 支持.
- [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) -插件已集成到mypy中.
- [loguru-mypy](https://github.com/kornicameister/loguru-mypy) -插件 [loguru](https://github.com/Delgan/loguru) 支持.


## Integrations

- [mypy-PyCharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) -Mypy集成的PyCharm.
- [vim-mypy](https://github.com/Integralist/vim-mypy) -Mypy与Vim集成.
- [linter-mypy](https://atom.io/packages/linter-mypy) -用于Atom的Mypy集成.
- [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) -用于Emacs的Mypy集成.


## Articles

### PEPs

- [PEP-3107](https://www.python.org/dev/peps/pep-3107) -功能注释.
- [PEP-482](https://www.python.org/dev/peps/pep-0482/) -类型提示的文献概述.
- [PEP-483](https://www.python.org/dev/peps/pep-0483/) -类型提示理论.
- [PEP-484](https://www.python.org/dev/peps/pep-0484/) -类型提示.
- [PEP-526](https://www.python.org/dev/peps/pep-0526/) -变量注释的语法.
- [PEP-544](https://www.python.org/dev/peps/pep-0544/) -协议：结构子类型化（静态鸭子输入）.
- [PEP-557](https://www.python.org/dev/peps/pep-0557/) -数据类.
- [PEP-560](https://www.python.org/dev/peps/pep-0560/) -对键入模块和泛型类型的核心支持.
- [PEP-561](https://www.python.org/dev/peps/pep-0561/) -分发和包装类型信息.
- [PEP-563](https://www.python.org/dev/peps/pep-0563/) -推迟对注释的评估.
- [PEP-585](https://www.python.org/dev/peps/pep-0585/) -在标准集合中键入提示泛型.
- [PEP-586](https://www.python.org/dev/peps/pep-0586/) -文字类型.
- [PEP-589](https://www.python.org/dev/peps/pep-0589/) -TypedDict：具有固定键集的字典的类型提示.
- [PEP-591](https://www.python.org/dev/peps/pep-0591/) -在输入中添加最终修饰符.
- [PEP-593](https://www.python.org/dev/peps/pep-0593/) -灵活的功能和变量注释.
- [PEP-604](https://www.python.org/dev/peps/pep-0604/) -Union []的互补语法.
- [PEP-612](https://www.python.org/dev/peps/pep-0612/) -参数规范变量.
- [PEP-613](https://www.python.org/dev/peps/pep-0613/) -显式类型别名.


### Python docs

- [typing](https://docs.python.org/3/library/typing.html) -支持类型提示.

### Tools' docs

- [MyPy docs](https://mypy.readthedocs.io/en/latest/stubs.html) -有关存根的常规信息.

### Third-party articles

- [1-minute guide to real constants in Python](https://sobolevn.me/2018/07/real-python-contants) -有关`Final`常量和继承的完整教程.
- [Simple dependent types in Python](https://sobolevn.me/2019/01/simple-dependent-types-in-python) -有关“文字”类型的完整教程.
- [Typechecking Django and DRF](https://sobolevn.me/2019/08/typechecking-django-and-drf) -有关django类型检查的完整教程.
- [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) -有关测试mypy类型的完整教程.
- [The state of type hints in Python](https://www.bernat.tech/the-state-of-type-hints-in-python/) -截至2018年5月.

## Communities

- [python/typing](https://gitter.im/python/typing) -官方打字聊天.
<!--lint disable awesome-list-item-->
-[TypedDjango]-官方组织聊天室.
<!--lint enable awesome-list-item-->
- [PythonRu#typing](https://python-ru.slack.com) -俄罗斯闲聊（邀请是 [here](https://slack.python.ru/)）关于类型.


## Related

- [awesome-python](https://github.com/vinta/awesome-python) -精选的Python框架，库，软件和资源的精选清单.
- [python-typecheckers](https://github.com/ethanhs/python-typecheckers) -Python类型检查器列表：静态和运行时.


[typeddjango]：https://gitter.im/mypy-django/Lobby
[numpy]：http://github.com/numpy/numpy
