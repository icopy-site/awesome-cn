<div class="github-widget" data-repo="typeddjango/awesome-python-typing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Python Typing [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) ![Gitter](https://img.shields.io/gitter/room/mypy-django/Lobby?color=9cf&style=flat-square)

很棒的Python类型，存根，插件和与之配合使用的工具的集合.





## Static type checkers

- [mypy](https://github.com/python/mypy) -适用于Python 3和2的可选静态类型（PEP 484）.
- [pyre](https://pyre-check.org/) -适用于Python 3的性能类型检查器.
- [pytype](https://github.com/google/pytype) -用于检查和推断Python代码类型的工具-无需类型注释.
- [PyCharm](https://www.jetbrains.com/pycharm/) -专业开发人员的IDE.
- [pyright](https://github.com/Microsoft/pyright)  -快速类型检查器，适用于大型Python源库.  它可以在“监视”模式下运行，并在修改文件后执行快速的增量更新.

## Dynamic type checkers

- [pytypes](https://github.com/Stewori/pytypes) -提供了一组丰富的实用程序，用于运行时类型检查.
- [pydantic](https://github.com/samuelcolvin/pydantic)  -使用Python类型提示进行数据解析.  支持数据类.
- [typeguard](https://github.com/agronholm/typeguard) -另一个运行时类型检查器.
- [typical](https://github.com/seandstewart/typical/)  -使用类型提示进行数据解析和自动类型强制.  支持数据类，标准类，函数签名等.

## Stub packages

- [Typeshed](https://github.com/python/typeshed) -具有静态类型的Python库存根的集合.
- [django-stubs](https://github.com/typeddjango/django-stubs) -存根 [Django](https://github.com/django/django).
- [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) -存根 [DRF](https://github.com/encode/django-rest-framework).
- [numpy-stubs](https://github.com/numpy/numpy-stubs) -存根 [NumPy](http://github.com/numpy/numpy).
- [dry-python/returns](https://github.com/dry-python/returns) -存根 [returns](https://github.com/dry-python/returns).
- [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) -存根 [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy).
- [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) -存根 [grpc](https://github.com/grpc/grpc).
- [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) -存根 [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
- [ordered-set-stubs](https://github.com/rominf/ordered-set-stubs) -存根 [OrderedSet](https://github.com/LuminosoInsight/ordered-set).
- [pyspark-stubs](https://github.com/zero323/pyspark-stubs) -存根 [PySpark](https://spark.apache.org/docs/latest/api/python/index.html).
- [pythonista-stubs](https://github.com/hbmartin/pythonista-stubs) -存根 [Pythonista](http://omz-software.com/pythonista/docs/ios/).

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
- [flake8-annotations](https://github.com/python-discord/flake8-annotations) -flake8插件，用于检查函数定义中是否存在类型注释.

### Testing

- [pytest-mypy](https://github.com/dbader/pytest-mypy) -Pytest的Mypy静态类型检查器插件.
- [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) -Pytest插件，用于测试mypy类型，存根和插件.

### Working with types

- [MonkeyType](https://github.com/instagram/MonkeyType) -收集函数参数和返回值的运行时类型，并可以基于运行时收集的类型自动生成存根文件，甚至将草稿类型注释直接添加到Python代码中.
- [merge_pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) -pytype工具链的一部分，将存根文件应用于源代码.
- [retype](https://github.com/ambv/retype) -另一个将存根应用于代码的工具.
- [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) -从protobuf生成mypy存根的工具.
- [mypyc](https://github.com/python/mypy/tree/master/mypyc) -将经过mypy注释的静态类型的Python模块编译为CPython C扩展.
- [typing_inspect](https://github.com/ilevkivskyi/typing_inspect) -typeing_inspect模块定义了实验API，用于对Python标准类型模块中定义的类型进行运行时检查.
- [typing-json](https://pypi.org/project/typing-json/) -用于处理类型化对象和JSON的库.   

### Mypy plugins

- [pynamodb-mypy](https://github.com/lyft/pynamodb-mypy) -插件 [PynamoDB](https://github.com/pynamodb/PynamoDB) 支持.
- [mypy-zope](https://github.com/Shoobx/mypy-zope) -插件 [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) 支持.
- [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) -插件已经集成到mypy中.


## Integrations

- [mypy-PyCharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) -Mypy集成的PyCharm.
- [vim-mypy](https://github.com/Integralist/vim-mypy) -Mypy与Vim集成.
- [linter-mypy](https://atom.io/packages/linter-mypy) -用于Atom的Mypy集成.
- [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) -用于Emacs的Mypy集成.


## Articles

### PEPs

- [PEP-483](https://www.python.org/dev/peps/pep-0483/) -关于类型提示理论.
- [PEP-484](https://www.python.org/dev/peps/pep-0484/) -关于类型注释.
- [PEP-544](https://www.python.org/dev/peps/pep-0544/) -关于协议.
- [PEP-561](https://www.python.org/dev/peps/pep-0561/) -关于分配和包装类型信息.
- [PEP-563](https://www.python.org/dev/peps/pep-0563/) -关于推迟评估注释.
- [PEP-586](https://www.python.org/dev/peps/pep-0586/) -关于文字类型.
- [PEP-3107](https://www.python.org/dev/peps/pep-3107/) -关于功能注释.

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
- [TypedDjango](https://gitter.im/mypy-django/Lobby) -官方组织网格聊天.
- [PythonRu#typing](https://python-ru.slack.com) -俄罗斯闲聊（邀请是 [here](https://slack.python.ru/)）关于类型.


## Related

- [awesome-python](https://github.com/vinta/awesome-python) -精选的Python框架，库，软件和资源的精选清单.
- [python-typecheckers](https://github.com/ethanhs/python-typecheckers) -Python类型检查器列表：静态和运行时.


## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
