<div class="github-widget" data-repo="secretGeek/awesomeCSV"></div>
## Awesome CSV [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**精心策划的 CSV 相关工具和资源列表**

[CSV](https://en.wikipedia.org/wiki/Comma-separated_values) 仍然是遥远过去最具未来感的数据格式.

 XML 起起落落.  JSON只是昙花一现.  YAML 是有毒的酒杯.  **CSV 将比它们都更持久.**

当最后一只蟑螂咽下最后一口气时，她的临终行为将是在 CSV 文件中划掉她的死亡日期，以供后代使用.






这里有一些处理 CSV 的很棒的工具：

## Tools

- [NimbleText/Live](https://NimbleText.com/Live)  - 使用模式来操纵 CSV； 世界上最简单的代码生成器*.
- [PapaParse](https://www.papaparse.com) - 一个强大的浏览器内 CSV 解析器.
- [d3-dsv](https://github.com/d3/d3-dsv) - 用于分隔符分隔值的 d3.js 解析器和格式化程序模块.
- [CSVKit](http://csvkit.readthedocs.org/en/0.7.3/) - CSV 实用程序，包括 csvsql / csvgrep / csvstat 等.
- [XSV](https://github.com/BurntSushi/xsv) - 用 Rust 编写的快速 CSV 命令行工具包.
- [sed (gnu tool)](https://www.gnu.org/software/sed/manual/sed.html) - 流编辑器.
- [gawk (gnu tool)](https://www.gnu.org/software/gawk/manual/gawk.html) - 文本处理和数据提取使用 [awk](http://pubs.opengroup.org/onlinepubs/009695399/utilities/awk.html).
- [awk by example](https://github.com/learnbyexample/Command-line-text-processing/blob/master/gnu_awk.md#default-field-separation) - 使用 awk 的综合示例.
- [Miller](http://johnkerl.org/miller/doc/) - 像 sed / awk / cut / join / sort 等名称索引数据，如 CSV.
- [ParaText](https://github.com/wiseio/paratext) - CSV 解析速度为每秒 2.5 GB.
- [CSVGet](http://github.com/fizx/csvget/tree/master) - 从站点获取结构化数据作为 CSV.
- [CSVfix](https://code.google.com/p/csvfix/) - 用于处理 CSV 数据的工具.
- [Tad](https://www.tadviewer.com) - 快速免费的跨平台 CSV 查看器.
- [Nvd3-tags](http://blog.tryolabs.com/2015/02/27/nvd3-tags-a-tiny-library-for-making-charts-from-csv-data/) - 用于从 csv 数据制作图表的小型库.
- [Powershell: Import-CSV](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/import-csv) - 用于处理 CSV 的强大内置工具（[example](https://gist.github.com/dfinke/786ba9edae1b0265ada10b36a7a11ba9)).
- [CSV Tools](https://onlinecsvtools.com/) - 有用的 CSV 实用程序的集合.
- [graph-cli](https://github.com/mcastorina/graph-cli) - 灵活的命令行工具，用于从 CSV 数据创建图表.
- [CSV to SQL](http://www.convertcsv.com/csv-to-sql.htm) - 从 CSV 数据创建插入/更新/删除等的在线工具.
- [C#: kbCSV](https://github.com/kentcb/KBCsv/blob/master/README.md) - 一个高效、易于使用的 .NET CSV 解析和编写库.
- [csvprintf](https://github.com/archiecobbs/csvprintf) - 用于基于 CSV 文件解析和格式化输出的 UNIX 命令行实用程序.
- [Mockaroo](https://www.mockaroo.com/) - CSV / JSON / SQL / Excel 的随机数据生成器.
- [Ron's CSV Editor](https://www.ronsplace.eu/products/ronseditor)  - 处理大文件，做神奇的事情. 永恒格式的永恒编辑器.
- [Rainbow CSV plugins](https://github.com/mechatroner/rainbow_csv#rainbow-csv-in-other-editors)  - 用于 CSV/TSV 语法突出显示的文本编辑器插件集合. 可以用来 [Vim](https://github.com/mechatroner/rainbow_csv), [VS Code](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv), [Atom](https://atom.io/packages/rainbow-csv), [Sublime Text](https://packagecontrol.io/packages/rainbow_csv) 和其他编辑.
- [Mighty Merge](https://mightymerge.io/) - 加入/合并 csv 文件.
- [Modern CSV](https://www.moderncsv.com/) - 用于编辑 CSV 文件和查看大文件的工具.

### Repair or Validate CSV

- [Csvlint.go](https://github.com/Clever/csvlint) - 用于根据 RFC 4180 验证 CSV 文件的命令行工具.
- [csvstudio](http://www.csvstudio.com/) - 一个智能应用程序，用于修复非常大的 CSV 文件中的语法错误.
- [scrubcsv](https://github.com/faradayio/scrubcsv) - 从 CSV 文件中删除错误记录并规范化（需要 rust）
- [reconcile-csv](https://github.com/OpenRefine/reconcile-csv/blob/master/README.md) - 查找一组相关 CSV 之间的关系

## Generate Table Schema

- [CSV Schema](https://csv-schema.surge.sh/) — 分析 CSV 文件并生成数据库表模式，所有这些都在浏览器中完成
- 需要：此类别中的更多工具.


### Treat CSV as SQL

- [TextQL](http://dinedal.github.io/textql/) - 针对 CSV 或 TSV 执行 SQL.
- [Datasette Facets](https://simonwillison.net/2018/May/20/datasette-facets/) - 面向任何 CSV 文件或 SQLite 数据库的分面浏览和 JSON API.
- [q](https://harelba.github.io/q/) - 直接在 CSV 文件上运行 SQL
- [RBQL](https://rbql.org) - Rainbow 查询语言，一种带有 JavaScript 或 Python 后端的类似 SQL 的语言.
- [PSKit Query](https://github.com/dfinke/PSKit#sql-query) — Powershell 模块允许您对对象运行简单查询，包括使用 csv 导入

### Convert to or from CSV

- [CSV to Table](https://github.com/vividvilla/csvtotable) - 将 CSV 文件转换为可搜索和可排序的 HTML 表格.

### CSV <-> JSON

- [Agnes](http://www.secretgeek.net/agnes/twoWay.html) - 两种方式 Csv 到 Json **.
- [csv2json](https://www.csvjson.com/csv2json) - 在线工具将您的 CSV 或 TSV 格式数据转换为 JSON 和 [vice versa](https://www.csvjson.com/json2csv).
- [csv-to-json](https://mango-is.com/tools/csv-to-json/) - 简单、隐私友好且离线优先的在线 csv 到 json 转换器.


## Essays

&gt; 一旦你找到了完美的数据序列化文件格式，你就不再寻找了
>
> [David Wengier](https://twitter.com/davidwengier/status/1159606464220000257)


- [Thinking about CSV](https://blog.datacite.org/thinking-about-csv/) - 马丁芬纳.
- [In Praise of CSV](https://usopendata.org/2015/03/10/csv) - 沃尔多贾奎斯.
- [Stop Rolling Your Own CSV Parser!](http://www.secretgeek.net/csv_trouble) - 莱昂班布里克 ***.
- [So You Want To Write Your Own CSV code?](http://thomasburette.com/blog/2014/05/25/so-you-want-to-write-your-own-CSV-code/) - 托马斯·伯瑞特.
- [Falsehoods Programmers Believe About CSVs](https://donatstudios.com/Falsehoods-Programmers-Believe-About-CSVs) - 杰西多纳特
- [ASCII Delimited Text - Not CSV or TAB delimited text](https://ronaldduncan.wordpress.com/2009/10/31/text-file-formats-ascii-delimited-text-not-csv-or-tab-delimited-text/) - 罗纳德邓肯.

## Data

- [US Data.gov](https://catalog.data.gov/dataset?res_format=CSV) - 18789+ CSV 数据集.
- [Australian Government Open Data](https://data.gov.au/dataset?res_format=CSV) - 2715+ CSV 数据集.
- [Reference data in csv](https://datahub.io/collections/reference-data) - CSV 和 JSON 格式的易于使用的参考数据.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) - 公共领域中以主题为中心的高质量开放数据集列表.
- [United Nations data](https://data.un.org) - 来自联合国的数据
- [Fake Name Generator](https://www.fakenamegenerator.com/order.php) - 批量生成带有其他身份数据的假名以供测试.

## Conferences

- [csv,conf](https://csvconf.com/) - 面向各地数据制作者的社区会议.


## Standards

 &gt; 标准的美妙之处在于有很多标准可供选择.<br />  ——（可能）格蕾丝·霍珀.

- [RFC 4180](https://tools.ietf.org/html/rfc4180) ([html version](http://www.faqs.org/rfcs/rfc4180.html)) - “*逗号分隔值 (CSV) 文件的通用格式和 MIME 类型*”.
  - [Definition of the CSV Format](https://tools.ietf.org/html/rfc4180#section-2)
  - [MIME Type Registration of text/csv](https://tools.ietf.org/html/rfc4180#section-3)
- [W3C: Model for Tabular Data and Metadata on the Web](https://www.w3.org/TR/tabular-data-model/)
- [CSV Schema Language](http://digital-preservation.github.io/csv-schema/csv-schema-1.2.html) - 一种用于定义和验证 CSV 数据的语言.
- [csv,specs](https://github.com/csvspecs)  - 逗号分隔值 (CSV) 格式规范（和测试），包括.  CSV v1.0、CSV v1.1、CSV Strict、CSV &lt;3 Numerics、CSV &lt;3 JSON、CSV &lt;3 YAML.
- [Tabular Data Resource](http://frictionlessdata.io/specs/tabular-data-resource/) - A [Data Resource](http://frictionlessdata.io/specs/data-resource/) 专门用于描述表格数据，如 CSV 文件或电子表格
- [CSVY](https://csvy.org/) - 将 YAML 标头添加到 CSV 文件以描述其格式的标准

## META: Other similar lists

- [structured-text-tools](https://github.com/dbohdan/structured-text-tools) - 用于操作 CSV / XML / HTML / JSON / INI 等的命令行工具列表.
- [META-META](https://raw.githubusercontent.com/secretGeek/AwesomeCSV/master/awesomecsv.csv) - **此列表为 CSV**.
- [META-META-META](https://nimbletext.com/Live/-971009575/) - 一种 NimbleText 模式，可从此列表中生成此降价页面作为 CSV.


## Code of Conduct

See [Code of Conduct](https://github.com/secretGeek/awesomeCSV/blob/master/code-of-conduct.md)


## Funtribute

要体验贡献的乐趣，请参阅 [Contributing](https://github.com/secretGeek/awesomeCSV/blob/master/contributing.md)


## Footnotes

 `*`<span id='footnote1' ></span> 我是的作者 [NimbleText](https://NimbleText.com/Live) . 当然，我把它放在第一位. 如果我没有亲自评价它，我就不会花这么多时间来制作和改进它.

 `**`<span id='footnote2' ></span> 我写了 `agnes` 但并不真正认可它供其他人使用（因此没有将源代码迁移到 GitHub）. 它速度慢且非流式传输. 我会选择 `papa-parse`. 从好的方面来说，`agnes` 拥有比大多数人更全面的测试套件和更简单的 api.

 `***`<span id='footnote3' ></span> 我也是.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Leon Bambrick](http://secretgeek.net) 已放弃该作品的所有版权和相关或邻接权.
