<div class="github-widget" data-repo="kdeldycke/awesome-billing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable awesome-heading-->

<p align="center">
  <a href="https://github.com/kdeldycke/awesome-billing/">
    <img src="https://raw.githubusercontent.com/kdeldycke/awesome-billing/raw/main/assets/awesome-billing-header.jpg" alt="💰 Awesome Billing">
  </a>
</p>

<p>任何公司都需要在某一时刻从客户那里获得资金. 那时我们开发人员的事情变得一团糟，因为我们试图协调业务的复杂性与我们的软件堆栈.</p>

<p>这<img src="https://awesome.re/badge-flat.svg" alt="Awesome">list 帮助软件工程师<strong>引导计费和支付系统，并理解发票、定价、会计、市场、欺诈和商业智能</strong>.</p>


<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=6 --minlevel=2 -->


<!-- mdformat-toc end -->

## Basics

<img align="right" width="50%" src="https://raw.githubusercontent.com/kdeldycke/awesome-billing/master/./assets/cloud-software-stack-billing.jpg"/>

在斯坦福的课堂上提供 [overview of cloud computing](http://web.stanford.edu/class/cs349d/docs/L01_overview.pdf)，平台的软件架构如右图描述 →

<!--lint disable double-link-->

该知识库涵盖了云堆栈右侧的第一个柱状边界. 它是生态系统的横向支柱之一，客户、产品和业务在这里相遇. 这 [other pillar being Identity and Access Management (IAM) 👤](https://github.com/kdeldycke/awesome-iam/).

<!--lint enable double-link-->

在这里，我们列出了全局：域的定义和战略重要性，以及一些关键特征.

- [Open guide to AWS](https://github.com/open-guides/og-aws#billing-and-cost-management) - 链接到*计费和成本管理* 部分.

- [Use-cases for cloud services](https://news.ycombinator.com/item?id=19830022) - 为了优化投资回报率，将所有常规工作负载保留在传统架构中，并为弹性和实验性项目保留云计算.

- [5 things I learned while developing a billing system](https://arnon.dk/5-things-i-learned-developing-billing-system/)  - 对计费系统各个方面的精彩介绍，从货币到发票，包括有关计划更改逻辑的精彩插图. 所有这些主题稍后将在下面的专门部分中详细介绍.

 - 如何招聘该领域的软件工程师？  “诀窍是让会计/计费/支付部门成为数据工程的反面.”  ([source](https://twitter.com/kdeldycke/status/1422564355799924736))

## Pricing

从每月订阅到类似商品的移动消费，有很多方案来构建您的产品定价. 包括旧的购物车漏斗.

- [Don't just roll the dice – Software pricing guide](https://neildavidson.com/downloads/dont-just-roll-the-dice-2.0.0.pdf) - 不仅是庞大而完整的定价方案集合，还有对收入模型的心理效应和影响.

- [Business Model Patterns](https://reasonstreet.co/business-model-library/) - 销售产品和服务的 11 种不同方式的列表.

- [Axial - Business models](https://axial.substack.com/p/axial-business-models) - 38 种灵感模型.

- [The Network Monetization Map: Aligning Incentives with Revenue](https://medium.com/breadcrumb/the-network-monetization-map-aligning-incentives-with-revenue-b73c362d1ad5) - 6种依靠网络效应的变现模式.

### Usage-based Pricing

弹性资源的动态方案.

- [Why I Love Usage-Based Pricing](https://www.rdegges.com/2020/the-only-type-of-api-services-ill-use/)  - “我喜欢这种定价模式的最重要原因是它极大地激励了客户和服务提供商为每个人的最大利益行事.” 还详细说明了其他定价模型的问题.

- [Socially Optimal Pricing of Cloud Computing Resources](https://webee.technion.ac.il/people/shimkin/PAPERS/Menache-CloudPricing-Conf2011.pdf)  - “社会最优运营点是独一无二的，可以通过线性的、基于使用的关税来维持，该关税对每单位资源和单位时间收取固定价格.” 本文证明了基于使用的云资源定价是合理的.

- [A Survey of Profit Optimization Techniques for Cloud Providers](https://dl.acm.org/doi/fullHtml/10.1145/3376917) - “首先讨论提高用户服务质量的策略，然后讨论云资源的定价策略以最大化收入.”

 - “计费并不是故意复杂的：这是为弹性付出的代价.”  ([source](https://twitter.com/kdeldycke/status/1214160678363246592)) - 或者为什么如果选择公用事业定价方案，您可能会收到源源不断的抱怨用户：虽然精确到（毫）美分，但这种模式对于没有准备好花时间掌握基本概念的客户来说是令人沮丧的.

- [Riemann sum](https://en.wikipedia.org/wiki/Riemann_sum) - 关于使用量化的起点.

- [Allen's interval algebra](https://en.wikipedia.org/wiki/Allen%27s_interval_algebra)  - 实施基于使用的定价很棘手，这个代数将帮助您组织时间推理. 也看到这个 [Stack Overflow question with clean schema](https://stackoverflow.com/questions/12069082/allens-interval-algebra-operations-in-sql?rq=1).

- [Reconcile Your Monthly GCP Invoice with BigQuery Billing Export](https://medium.com/@lukwam/reconcile-your-monthly-gcp-invoice-with-bigquery-billing-export-b36ae0c961e)  - 在此开发人员跟踪其费用的过程中，您可以看到云计费的困难. 虽然没有明确指出，为云资源定价是困难的，是空间、时间和货币之间量化、粒度和舍入的结果.

- [AWS EC2 T2 Instances Demystified: Don't Learn The Hard Way](https://roberttisdale.com/aws-ec2-t2-instances-demystified-dont-learn-hard-way/) - 一个非常棘手的可突发实例的示例，它会累积并限制其自身的 CPU 使用信用量.

- [“Designing billing for a service can be really challenging”](https://news.ycombinator.com/item?id=23536919) - 关于 AWS 简单电子邮件服务定价计划设计的个人轶事.

- [Subscription-based pricing is dead: Smart SaaS companies are shifting to usage-based models](https://techcrunch.com/2021/01/29/subscription-based-pricing-is-dead-smart-saas-companies-are-shifting-to-usage-based-models/) - 基于使用的定价更加优化和公平：它“允许客户以低成本开始，最大限度地减少开始时的摩擦，同时仍然保留随着时间的推移通过客户获利的能力”.

- [Electropedia: Tariffs for electricity](https://www.electropedia.org/iev/iev.nsf/index?openform&part=691)  - 在云之前，还有另一种按使用量定价的计量资源：电力. 这是国际电工委员会对其词汇量的详细（和多语言）分类.

### Subscription Plans

在 SaaS 企业中非常受欢迎，订阅计划很容易理解.

- [Pricing low-touch SaaS](https://stripe.com/en-in/atlas/guides/saas-pricing) - “在低接触 SaaS 中，最常见的软件包呈现方式是定价网格中的不同列，每一列对应于一个计划，以不同的价格提供，具有对功能的不同访问权限或沿某个轴的最大允许使用量对企业来说很有趣.”

- [`f-license`](https://github.com/furkansenharputlu/f-license) - Go 中的开源许可证密钥生成和验证工具.

### Hybrid

不常见的定价方案.

- [The Three Part Tariff](https://tomtunguz.com/three-part-tariffs/) - 除了线性定价之外，定价结构中还有额外的平台费用和免费层组件.

- [Google Ads API: `BillingCap` enum](https://developers.google.com/ad-manager/api/reference/v201911/CompanyService.BillingCap) - 上限实际值：每月滚动，优化的定价方案，以限制来自客户的惊喜，我们或多或少地销售配额.

### Strategy

理论和实践洞察力，帮助您选择正确的定价策略.

 ——“赚钱有两种方式，可以捆绑，也可以解绑.”  - [Jim Barksdale](https://hbr.org/podcast/2014/07/marc-andreessen-and-jim-barksdale-on-how-to-make-money.html#transcript-section).

- [Pricing Psychology](https://www.nickkolenda.com/psychological-pricing-strategies/)  - 你应该使用哪些数字？ 应该多高？ 应该是圆的吗？ 本指南有 42 个技巧可帮助您选择最优惠的价格.

- [The 7 factors to consider when pricing your startup product](https://tomtunguz.com/how-to-price-your-startups-product/) - 定价是一种令人反感的工具，可以增强您的产品价值并强调公司的核心营销信息.

- [The cup-of-coffee pricing fallacy](https://blog.gingerlime.com/2020/the-cup-of-coffee-pricing-fallacy/) - 解释为什么这是一个草率的类比.

### Market Research

调查方法和价格发现技术以找到合适的价格点.

- [Jeremy Howard - From Predictive Modelling to Optimization](https://youtu.be/vYrWTDxoeGg?t=542)  - “在保险中，价格就是产品.  （……）我如何改变价格来赚大钱？” 或者如何交付结果（为客户提供最优价格）而不是交付数据（计算客户的风险，这是以前精算师使用的标准方法）.

- [Gabor–Granger method](https://en.wikipedia.org/wiki/Gabor%E2%80%93Granger_method)  - 用于调查以确定新产品或服务的价格. 结果可用于生成需求图表和收入曲线.

- [Van Westendorp's Price Sensitivity Meter](https://en.wikipedia.org/wiki/Van_Westendorp%27s_Price_Sensitivity_Meter)  - PSM 是一种确定消费者价格偏好的市场技术. 允许绘制收入曲线以估计提供最大收入的价格点.

- [Pricing niche products](https://kevinlynagh.com/notes/pricing-niche-products/)  - “不过，反对简单定价的最有说服力的论点是，它限制了你对市场的了解程度.” 然后作者设置了维克里拍卖来发现价格.

- [Finding the max revenue price mark for digital products](https://medium.com/@hovm/finding-the-max-revenue-price-mark-for-digital-products-24cef24f746d)  - “要找到为您的产品提供最大收入的最佳价格，您需要现场测试多个价格点； 然后你重建收入曲线并找到峰值.”

- [Personalised pricing and EU law](https://www.econstor.eu/bitstream/10419/205221/1/de-Streel-Jacques.pdf) - 由于消费者保护和数据保护规则，欧盟禁止某些价格个性化案例.

## Product Catalog

可供客户购买的所有可用服务、产品、变体、选项和定价的中央存储库. 云服务的目录大部分时间都是量身定制的，但也有一些经典的 PDM 解决方案（[Product Data Management](https://en.wikipedia.org/wiki/Product_information_management)，又名用于产品信息管理的 PIM）可能符合要求.

- [GCP Product Catalog](https://cloud.google.com/blog/products/gcp/introducing-cloud-billing-catalog-api-gcp-pricing-in-real-time) - 所有 GCP SKU 作为 API 提供.

- [Akeneo PIM](https://github.com/akeneo/pim-community-dev) - 商业 Akeneo 产品的开源变体.

- [Pimcore](https://github.com/pimcore/pimcore) - 用于管理产品元数据的开源 UI 和数据库，用 PHP Symfony 编写.

- [OpenPIM](https://www.openpim.org) - 一个精简的开源项目，专注于 PIM-only 功能.

- [Comparing 3 open source PIM solutions](https://medium.com/@slavapedak/comparing-3-free-and-open-source-product-information-management-pim-solutions-e83a1898f91e) - Comparative study of the 3 projects above.

## Calculator

根据您计划使用的资源模拟虚拟发票.

- [Cloud Cost Calculator](https://github.com/scalyr/cloud-costs) - 基于 Web 的工具，用于为给定的一组需求寻找最便宜的云服务器.

- [Cloudorado](https://www.cloudorado.com) - 使用 ECU（亚马逊的 vCPU）作为 CPU 功率测量单元的比较矩阵.

- [EC2Instances.info](https://ec2instances.info) - 简单的 Amazon EC2 实例比较.

## Cost Forecast

帮助您的客户根据他们过去的使用情况预测他们即将到来的和未来的消费.

- [Forecasting: Principles and Practice](https://otexts.com/fpp2/) - “对预测方法的全面介绍，并提供有关每种方法的足够信息，以便读者能够明智地使用它们.”

- [Transforming Financial Forecasting with Data Science and Machine Learning at Uber](https://eng.uber.com/transforming-financial-forecasting-machine-learning/) - 讨论 Uber 如何在其财务规划平台中应用数据科学和机器学习.

- [Time Series Prediction - A short introduction for pragmatists](https://www.liip.ch/en/blog/time-series-prediction-a-short-comparison-of-best-practices) - [Facebook's Prophet](https://facebook.github.io/prophet/) （哪一个 [uses Stan underneath](https://statmodeling.stat.columbia.edu/2017/03/01/facebooks-prophet-uses-stan/))，似乎值得检查以在考虑季节性的同时实施成本预测工具.

- [Forecasting with sktime](https://github.com/alan-turing-institute/sktime/blob/master/examples/01_forecasting.ipynb)  - 关于如何使用过去数据进行时间前向预测的教程. 并阅读 [difference between sktime and the Prophet project](https://news.ycombinator.com/item?id=24543861) 上面提到的.

- [Komiser](https://github.com/mlabouardy/komiser) - 开源工具，通过发现隐藏成本、监控支出增长以及根据自定义建议进行有影响力的更改来保持在预算范围内.

- [GCP Cost Forecast](https://cloud.google.com//billing/docs/how-to/reports#cost-forecast) - 资源消耗的消耗趋势线示例.

- [AWS Forecast](https://aws.amazon.com/forecast/) - 一个功能齐全的托管产品，可对任何时间序列进行预测.

- [How to save money on your AWS bill](https://twitter.com/QuinnyPig/status/1091041507342086144)  - “最大的成本节省是： 1. 关闭你不使用的东西；  2.然后点实例；  3. 然后是预留实例.”

## Marketplace

市场将供应与需求联系起来，从而导致金融交易. 如果不涉及付款，则它是聚合器或集线器. 不是市场.

- [Customized Regression Model for Airbnb Dynamic Pricing](https://www.kdd.org/kdd2018/accepted-papers/view/customized-regression-model-for-airbnb-dynamic-pricing) - 本文描述了 Airbnb 部署的定价策略模型.

- [Papers we love: Auctions and Bidding](https://github.com/papers-we-love/papers-we-love/tree/master/economics#auctions-and-bidding) - 关于投标和拍卖的论文集.

- [Vickrey auction](https://en.wikipedia.org/wiki/Vickrey_auction) - 由一个暗示 [HN comment](https://news.ycombinator.com/item?id=19145391) ，其中是的，“&#39;询问人们他们愿意支付什么费用以及有多少很少奏效.&#39;  （……）\[但\]使用类似于谷歌的广告拍卖机制的 Vickrey 拍卖可以激发一个人的最大支付意愿.”

- [19 Tactics to Solve the Chicken-or-Egg Problem and Grow Your Marketplace](https://www.nfx.com/post/19-marketplace-tactics-for-overcoming-the-chicken-or-egg-problem)  - “哪个先出现，供给还是需求？ 鸡肉还是鸡蛋？”

- 如何启动和扩展市场业务： [Constrain the marketplace](https://www.lennyrachitsky.com/p/how-to-kickstart-and-scale-a-marketplace) ; 决定专注于市场的哪一边； 推动初始供应； 推动初始需求. 一个由 4 部分组成的系列，对数十名具有建立和扩展市场的直接经验的人进行了采访.

### Cloud Resources

本小节重点介绍匹配资源生产者和消费者的投标/要求机制. 大多数时候，这些都是片面的市场，大平台试图摊销未充分利用的库存.

- [Incentive Engineering for Computational Resource Management](https://agoric.com/assets/pdf/papers/incentive-engineering-for-computational-resource-management.pdf) - 探讨“与编程实践和市场机制兼容的处理器时间和存储分配机制”的论文.

- [Pricing of Service in Clouds: Optimal Response and Strategic Interactions](http://www.sigmetrics.org/mama/2013/abstracts2013/UrgaonkarEtAl.pdf)  - “消费者应如何调节其需求以优化其利润？  （……）供应商和消费者应如何协商他们将采用的具体定价结构？” 涵盖非线性模型、分层定价、弹性需求、消费者和供应商策略.

- [Dynamic Cloud Pricing for Revenue Maximization](https://henryhxu.github.io/share/hxu-tcc2013.pdf) - “Amazon's spot price is unlikely to be set according to market supply and demand. Rather, price oscillates within a very narrow band most of the time, which is more likely to be an artifact of some pricing algorithm with predetermined reserve price.”

- [Usage Patterns and the Economics of the Public Cloud](https://vita.mcafee.cc/PDF/EconPublicCloud.pdf)  - “我们研究了云计算中的供需经济学.  （……）这些结果解释了为什么目前固定价格占主导地位，尽管似乎需要时变动态. 检查实际的 CPU 利用率为未来提供了一个视角.  (...) 需求波动将与动态定价很重要的三个经典行业（酒店、电力、航空公司）相提并论，而动态价格对效率至关重要.”

- [Maximizing Profit of Cloud Brokers under Quantized Billing Cycles: a Dynamic Pricing Strategy based on Ski-Rental Problem](https://arxiv.org/pdf/1507.02545.pdf)  - “我们算法的核心思想是利用定价信号来调节用户需求. 有人可能会争辩说，这种算法为用户提供的服务很差，因为它会将任务推出队列以最大化云代理的利润.”

- [Present or Future: Optimal Pricing for Spot Instances](https://web.archive.org/web/20150708151037/http://www.temple.edu/cis/icdcs2013/data/5000a410.pdf) - “现货资源的定价政策应精心设计，并应考虑对现在和未来的影响.”

 - “你总是支付现货市场价格，而不是你的出价.”  ([source](https://news.ycombinator.com/item?id=20347716)) - 投标机制的简单说明.

- [Deconstructing Amazon EC2 Spot Instance Pricing](http://www.cs.technion.ac.il/~dan/papers/Spotprice11CloudCom.pdf)  - “拥有大量备用容量的云提供商必须要么激励客户购买它，要么遭受损失. 亚马逊是第一个应对这一挑战的云提供商，它允许客户竞标备用容量，并在竞标者的出价超过定期变化的现货价格时向他们提供资源.”

- [GCP Preemptible VMs vs AWS Spot Instances](https://news.ycombinator.com/item?id=9564287) - “Google's prices are fixed, whereas AWS uses a market model”.

 - “查看 3 个月的现货价格历史记录以估算成本并发现可用区和实例类型与额外容量的组合.”  ([source](https://news.ycombinator.com/item?id=16071684)) - 用户正在寻求现货市场的更多透明度.

- [The Eternal Cost Savings Of Netflix's Internal Spot Market](http://highscalability.com/blog/2017/12/4/the-eternal-cost-savings-of-netflixs-internal-spot-market.html) - 当你足够大时 [creating an internal secondary market](https://medium.com/netflix-techblog/creating-your-own-ec2-spot-market-6dd001875f5) 例如，具有经济意义.

- [AutoSpotting](https://github.com/AutoSpotting/AutoSpotting) - Tool that easily and reliably converts (all) your existing AutoScaling groups to cheaper spot instances.

### Online Ads

有针对性的在线广告市场与传统的云市场有很多共同之处. 从概念到技术，那里有一些很好的灵感.

- [RTB Budget Pacing Summarized](https://github.com/PragmaticLab/RTB_Budget_Pacing_Summarized) - 用于有针对性的在线广告的预算节奏资源集合.

- [Samsung's online ads platform/exchange war story](https://github.com/eloraiby/fs-pacer/blob/master/fs-pacer.md) - 如何扩展到 5M 出价请求/秒，最大响应时间为 2 毫秒.

- [`RTB4Free`](https://github.com/RTB4FREE) - 开源投标人和需求方平台 (DSP).

## Accounting

 - “会计部门通常是向后的. 财务部门通常是面向前方的.”  ([source](https://news.ycombinator.com/item?id=25366184))

### Double-Entry Model

会计的核心概念是复式记账. 为了正确设计任何强大的追踪资金的系统，这是最关键的部分.

- [Accounting for Developers 101](https://docs.google.com/document/d/1HDLRa6vKpclO1JtxbGB5NeAYWf8cf1UMGy22o8OZZq4) - 会计历史和词汇的一般介绍.

- [Accounting for Computer Scientists](https://martin.kleppmann.com/2011/03/07/accounting-for-computer-scientists.html) - 描述如何以资金流动的图表形式查看会计，然后这些变动如何在小公司的财务报表中实现.

- [The Double-Entry Counting Method](https://beancount.github.io/docs/the_double_entry_counting_method.html) - 与上述相同的前提，但更加详细和完整，因为它增加了报告和实施细节.

- [Accounting Memento For Entrepreneurs (US GAAP)](https://www.odoo.com/documentation/functional/accounting.html) - 一种与会计概念一起玩的互动形式.

### Bookkeeping

您需要了解的有关保持会计数据干净整洁的日常实践的所有信息.

- [So, you want to learn Bookkeeping!](http://www.dwmbeancounter.com/tutorial/Tutorial.html) - 专注于记录和维护企业交易的日常操作.

- [Plain text accounting tools](https://plaintextaccounting.org/#software) - 广泛的开源个人理财项目列表，这些项目可能非常适合寻找复式记账和簿记的灵感.

- 以及图形会计工具列表： [GNUCash](https://gnucash.org) (GTK+), [Grisbi](https://grisbi.org) （C）， [Firefly III](https://firefly-iii.org) （PHP）.

- [GnuCash Tutorial and Concepts Guide](https://www.gnucash.org/docs/v2.4/C/gnucash-guide/) - A complete tutorial on personal finance tracking with GnuCash.

- [Frappe Books](https://github.com/frappe/books) - 适用于小型企业和自由职业者的免费桌面簿记软件.

- [Luca](https://github.com/brandon-rhodes/luca) - YAML 会计和 JSON 税表.

- [Sequence](https://github.com/decimals/sequence)  - 存储、验证和报告资产移动的 API. 也称为分类帐. 序列是不可变的、可扩展的和易于使用的.

- [Go DB Ledger](https://github.com/darcys22/godbledger) - 一个开源会计系统，旨在使复式记账交易的记录可编程.

- [Ledger](https://github.com/numary/ledger) - 可编写脚本的财务分类账，旨在简化复杂金融交易的建模.

- [Akaunting](https://github.com/akaunting/akaunting) - 专为小型企业和自由职业者设计的开源软件.

### Software design and implementation

现在您已经对会计的概念和实践有了一定的了解，这里有一些资源可以帮助您将这些知识应用到软件系统中.

- [Moonpig: a billing system that doesn't suck](https://blog.plover.com/prog/Moonpig.html)  - 计费和会计系统背后的设计决策. 要点：一些公司仍然通过支票付款； 不要使用花车； 复杂的客户工作流程； 日期和时间问题； 可变数据.

- [Books, an immutable double-entry accounting database service](https://developer.squareup.com/blog/books-an-immutable-double-entry-accounting-database-service/) - 解释在 Square 内部使用 Google Spanner 的复式记账系统的基本数据模型.

- [Django Hordak](https://django-hordak.readthedocs.io) - Django 复式记账系统的核心功能.

- [Managed accounts for Django](https://github.com/django-oscar/django-oscar-accounts) - “管理账户”是可以借记和贷记的资金分配.

- [Triple‐entry accounting with blockchain: How far have we come?](https://onlinelibrary.wiley.com/doi/abs/10.1111/acfi.12556)  - “三式记账法是一种新的、更有效的方法，可以解决困扰当前会计系统的基本信任和透明度问题. 如果实施得当，使用区块链的三式记账可以从根本上改善会计.”

### Currencies

跨国公司需要知道如何在当地货币之间进行权衡.

- [Tutorial on multiple currency accounting](https://www.mathstat.dal.ca/~selinger/accounting/tutorial.html) - 实施多币种会计系统的绝佳资源.

## Finance

整理好帐户后，您就可以开始从财务数据中提取见解和指标.

- [Accounts Demystified: The Astonishingly Simple Guide To Accounting](https://amzn.com/0273744704/?tag=kevideld-20) - 帮助您学习如何分析和监控公司的财务业绩.

- [The Games People Play With Cash Flow](https://commoncog.com/blog/cash-flow-games/)  - “Malone 创造了一个新的会计指标，他称之为‘未计利息、折旧和税项的收益’或 EBITDA.” 这就是有线电视公司首席执行官如何理解现金流的方式，就像房地产业务一样. 本文从这个例子开始，描述了 SaaS 模型的其他现金流游戏.

- [Financial Intelligence for Entrepreneurs: What You Really Need to Know About the Numbers](https://amzn.com/1422119157/?tag=kevideld-20) - 让您充分了解如何使用财务数据为您的业务做出更好的决策.

- [What is FinOps](https://www.finops.org/introduction/what-is-finops/) - 技术金融和业务领导团队共享云运营和管理的相同语言和流程的框架.

- [Algebraic Models for Accounting Systems](https://amzn.com/9814287113/?tag=kevideld-20) - 应用于会计系统分析的高级抽象代数.

## Contracts

所有发票和付款条款和条件均由最终用户和服务提供商之间签署的合同实现. 我们从中得出所有计费周期规则的来源.

- [Is this what Enterprise mean?](https://twitter.com/steffoz/status/1389946268764475394)  - 设计不当的合同管理用例疏远了大企业客户. 见 [associated HN comments](https://news.ycombinator.com/item?id=27053246) 批量购买许可证.

- [CUDs vs. Commit Contracts vs. SUDs in Google Cloud](https://www.cloudbakers.com/blog/cuds-vs.-commit-contracts-vs.-suds-in-google-cloud) - 解释 GCP 中各种类型的折扣和提交之间的区别.

- [Quantity discounts on a virtual good: The results of a massive pricing experiment](https://www.pnas.org/content/pnas/113/27/7323.full.pdf) - “对大宗采购实施 9-70% 的降价，我们发现对收入的影响非常小，无论是正面的还是负面的.”

## Coupons and Vouchers

- [Raising Prices is Hard](https://www.backblaze.com/blog/raising-prices-is-hard/)  - Backblaze 对提高主要报价的价格进行事后分析. 他们想创建一个基于信用系统的扩展程序. 这成为了少数最高级工程师的全职工作，并导致了为期六个月的项目.

- [Details on Expiring DigitalOcean Credits](https://blog.digitalocean.com/details-on-expiring-digitalocean-credits/) - 您必须为信用添加时间限制的原因：未使用的帐户作为我们资产负债表上的负债.

- [Hacking Scooters: How I Created \$100k Worth Of Free Rides](https://webcache.googleusercontent.com/search?q=cache:7hrzYYk5-IwJ:https://fant.io/p/hacking-voi/) - 关于如何利用促销代码获得无限次免费乘车的警示故事.

- [China's Pinduoduo reports theft of online discount vouchers to police](https://www.reuters.com/article/us-pinduoduo-china/chinas-pinduoduo-reports-theft-of-online-discount-vouchers-to-police-idUSKCN1PE05J) - 下一级诈骗：“某网络集体利用平台漏洞‘盗取’数千万元优惠券”.

- [Council Directive 2016/1065 as regards the treatment of vouchers](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32016L1065) - 涉及代金券时适用增值税的欧洲指令.

- [The coupon code is a slap in the face](https://justinjackson.ca/the-coupon-code-is-a-slap-in-the-face)  - 指出用户在没有优惠券的情况下遇到空白优惠券字段的负面后果. 请参阅文章末尾的更新，研究支持这一轶事.

## Taxes

- [2017 Tax Software Developer's Guides](https://www.mass.gov/lists/2017-tax-software-developers-guides) - 供开发人员测试其税码的测试用例列表.

- [{Digital,Cloud,Electronic,Online} Services VAT Rate Database](https://github.com/kdeldycke/vat-rates) - 为每个居住国（包括地域例外）集中适用于外国在线服务的增值税税率.

- [Global VAT & GST on digital services](https://www.avalara.com/vatlive/en/global-vat-gst-on-e-services.html) - 要求对外国提供的在线服务征税的国家名单.

 - “英国超市（……）向您收取后端卡处理费用，但他们会从您的结账价格中扣除该费用.”  ([source](https://news.ycombinator.com/item?id=22047028)) - 这允许他们 [claim the VAT on processing fees as input tax](https://www.gov.uk/guidance/vat-guide-notice-700#section4).

- [Streamlined Sales Tax Governing Board](https://www.streamlinedsalestax.org/about-us/about-sstgb) - 一项美国多州倡议，旨在实现销售税会计和征收的自动化和标准化.

### European VAT

- [How to correctly setup SaaS subscriptions to charge VAT in Europe](https://medium.com/slight-pause/how-to-setup-saas-subscriptions-correctly-to-charge-vat-in-europe-d75d857b5d01) - “如果你认为你可以像我们一样设置一个简单的 Stripe 集成并继续前进，那你就大错特错了.”

- [Council Directive 2006/112/EC](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L:2006:347:FULL) - 欧盟关于增值税共同制度的参考.

- [What does the "Reverse Charge" refer to?](https://news.ycombinator.com/item?id=8767388) - 答：企业将增值税处理责任转移给客户的条款.

## Invoice

发票实现消费的服务或购买的产品，等待通过支付交易结算.

- [On GCP invoiced billing](https://news.ycombinator.com/item?id=17517479) - [Invoiced billing](https://cloud.google.com/billing/docs/how-to/invoiced-billing) （客户在使用服务并开具发票后进行 B2B 友好付款）是 GCP 的一个痛点.

- [Digital signatures: how Sleek leverages Cloud HSM to guarantee the integrity of legal documents](https://medium.com/google-developers/digital-signatures-how-sleek-leverages-cloud-hsm-to-guarantee-the-integrity-of-legal-documents-a7bd3b82faf6)  - 这是依靠 GCP 的 HSM 对文档进行数字签名并提供不可变审计跟踪的好方法. 可能适用于发票和合同协议.

- [OpenTimestamps](https://opentimestamps.org) - 超越上述解决方案，直接在比特币区块链上为不可变文档添加时间戳.

- [Manta](https://github.com/hql287/Manta) - 灵活的发票桌面应用程序，带有漂亮和可定制的模板.

- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - 用于管理发票、客户和付款的自托管开源应用程序.

- [Volcano](https://github.com/volcano/volcano) - 灵活的、与网关无关的计费系统.

- [InvoiceGenerator](https://github.com/by-cx/InvoiceGenerator) - 库生成一个简单的发票.

- [Ruby Invoicing Framework](https://github.com/code-mancers/invoicing)  - 用于生成和显示发票（适用于商业 Rails 应用程序）. 它允许灵活的业务逻辑； 提供税务处理、佣金计算等工具.

- [Refact](http://en.userstudio.fr/projects/refact/) - 一个试图用信息图表修改电话账单的设计项目.

- [InvoiceNet](https://github.com/naiveHobo/InvoiceNet) - 深度神经网络从发票文件中提取智能信息.

- [Factur-X](https://github.com/akretion/factur-x) - Python 库支持法国和德国的电子发票标准.

- [Universal Business Language](https://en.wikipedia.org/wiki/Universal_Business_Language) - 大多数发票软件都可以读取和写入 UBL 文档 (XML) 以进行数据传输.

- [EU eInvoicing](https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/eInvoicing) - 电子发票的欧洲标准.

## Payments

- [The Best Payment Gateway for Startups](http://aynuriev.com/best-payment-gateway-startups/) - 顶级支付提供商的基准、他们的定价和模式.

- [Avoiding Double Payments in a Distributed Payments System](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb)  - RDBMS 是为银行围绕交易构建的，以解决该特定问题. 然后 NoSQL 迫使我们仔细实施系统以避免双重支出.

- [Monzo's bank transfers post-mortem](https://monzo.com/blog/2019/06/20/why-bank-transfers-failed-on-30th-may-2019/) - 或者为什么您应该为网关提供商的中断做好准备并解决问题.

- [How to Build an Insurance Company](https://www.moderntreasury.com/journal/how-to-build-an-insurance-company) - 支付操作架构的重要性.

- [EU's Late Payment Directive](https://ec.europa.eu/growth/smes/support/late-payment_en) - 关于滞纳金的适用费用的欧洲规则.

- [High failure rate of Point Of Sale devices in the upper Midwest](https://news.ycombinator.com/item?id=20043944)  - 根本原因？ 人们在低湿度空气中穿着大量羊毛，产生大量静电.

- ACH 的工作原理：开发人员的观点， [part 1](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-1/), [part 2](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-2/), [part 3](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-3/), [part 4](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-4/).

- [Handling system failures during payment communication](https://blogs.dropbox.com/tech/2017/09/handling-system-failures-during-payment-communication/) - Dropbox 试图说明不可靠的支付提供商的经历.

- [Why was I charged?](https://wpchrg.wordpress.com)  - 在用户对付款的投诉源源不断的情况下，WordPress 创建了一个专门的子域来帮助客户了解意外交易. 诀窍是直接在银行对帐单中添加那种网站的 URL.

- [moov](https://github.com/moov-io) - 金融技术的开源基础设施.

- [Fintech Open Source Foundation](https://github.com/finos) - 另一套金融项目的开源项目.

### Receipt

收据实现付款交易.

- [The humble receipt gets a brilliant redesign](https://www.fastcompany.com/90347782/the-humble-receipt-gets-a-brilliant-redesign) - 当 Netflix 数据工程师重新访问收据时.

- [The long, long history of long, long CVS receipts](https://www.vox.com/the-goods/2018/10/10/17956950/why-are-cvs-pharmacy-receipts-so-long) - “CVS is a drugstore much like other drugstores, with one important difference: The receipts are very long.”

### Credit Cards

最流行的支付设备.

- ['Is that even legal?': Companies may be sharing new credit or debit card information without you knowing](https://www.cbc.ca/news/business/banking-information-shared-with-third-parties-1.5102931)  - 一些信用卡和借记卡公司提供“更新服务”，允许与商家共享新帐号和到期日期.  Visa的实现叫做 [VAU](https://developer.visa.com/capabilities/vau) 万事达卡是 [ABU](https://developer.mastercard.com/product/automatic-billing-updater).

- [Strong Customer Authentication](https://stripe.com/guides/strong-customer-authentication) - [Payment Services Directive](https://en.wikipedia.org/wiki/Payment_Services_Directive) 2、解释.

- [Address Verification System](https://en.wikipedia.org/wiki/Address_Verification_System) - 一种检查客户帐单地址与信用卡相关帐单地址匹配的系统.

- [pci-blackbox](https://github.com/trustly/pci-blackbox) - 基于 PostgreSQL 和 PL/pgSQL 的 PCI-DSS 兼容卡系统.

### Bank Accounts

老式的付款方式：通过银行.

- [A (shallow) dive into the American banking system](https://blog.yossarian.net/2019/12/25/A-shallow-dive-into-the-American-banking-system) - 杂项笔记的收集主要集中在可路由账户的常见情况，即支票和储蓄.

- [Open IBAN](https://openiban.com) - 免费和公开的 IBAN 验证和计算网络服务.

- [Swift Codes](https://bank.codes/swift-code/) - Swift / BIC 代码仅供个人使用.

- [Swift Codes Repository](https://github.com/PeterNotenboom/SwiftCodes) - 一个似乎抓取上面网站的存储库.

### Online Payments

通常的汇款服务.

- [UPI 101: The Basics](https://the-other-side.blog/upi-the-basics/)  - “在本文中，我们将了解印度的统一支付接口. 一项已有四年历史的支付方案已占印度数字支付的 40-45%.”

- [The untold story of Stripe](https://www.wired.co.uk/article/stripe-payments-apple-amazon-facebook) - 我们在其中了解到“一旦营业额达到一定水平，Paypal 会自动将业务置于 21 至 60 天的滚动储备中，这意味着公司高达 30% 的收入可能会被锁定长达两个月.”

- [Idempotency in the context of payments](https://developers.google.com/standard-payments/reference/idempotency)  - “幂等性可以防止竞争条件. 幂等性规定来自同一客户端的多个相同请求不会导致不同的最终状态.”

- [Optimizing payments with machine learning](https://dropbox.tech/machine-learning/optimizing-payments-with-machine-learning) - 描述了一个经典的支付工作流程，然后介绍了机器学习如何替代硬编码的业务规则并微调支付失败/重试循环以提高收费的成功率.

## Fraud

有金钱激励来开发您的业务. 准备好与成群的欺诈者和阴暗的用户作斗争.

- [Detecting fraudulent activity in a cloud using privacy-friendly data aggregates](https://arxiv.org/pdf/1411.6721v1.pdf) - 讨论一种通过使用非侵入性、隐私友好型数据（计费数据）来检测欺诈活动（发起 DDoS 攻击、比特币挖掘……）的方法.

<!--lint disable double-link-->

- [Awesome List of IAM: Fraud links](https://github.com/kdeldycke/awesome-iam#fraud) - 专门用于与用户帐户相关的欺诈管理的部分，来自我们的姊妹存储库.

<!--lint enable double-link-->

- [Driving Global Fraud Losses Down While Empowering Business Growth](https://youtu.be/yJKWpTBVTiI?t=60)  - 在 Uber Eats 的这次演讲中，我们从最大的支付处理商那里了解到“亏损率下降的成长型业务在业内极为罕见”. 此外，欺诈可以采取多种形式：对不易腐烂的商品退款、滥用促销、退款……

### Cards

大多数欺诈是利用最常见的流行支付设备：信用卡.

- [How I Stopped a Credit Card Thief From Ripping Off 3,537 People – and Saved Our Nonprofit in the Process](https://www.freecodecamp.org/news/stopping-credit-card-fraud-and-saving-our-nonprofit/) - 描述一种被称为“卡片测试”的欺诈技术，其中会根据您的 API 检查大量被盗卡片的有效性.

- [How Candy Japan got credit card fraud somewhat under control](https://www.candyjapan.com/behind-the-scenes/how-i-got-credit-card-fraud-somewhat-under-control) - 所涉及的建议 [warning signals](https://www.candyjapan.com/behind-the-scenes/fraudulent-transaction-warning-signs) 试图猜测哪些订单可能是欺诈，或试图让欺诈者更加困难的对策.

- [Five Fun Fraud Facts](https://blog.sift.com/2013/five-ecommerce-fraud-facts/)  - 我们可以提供给 ML 系统以检测欺诈的另一小部分功能集合. 对HN的评论也出土了 [more qualifying signals](https://news.ycombinator.com/item?id=6376350) 和 [derived geodata on the transaction](https://news.ycombinator.com/item?id=6376221).

- [Credit Card Fraud Detection using Autoencoders in Keras](https://medium.com/@curiousily/credit-card-fraud-detection-using-autoencoders-in-keras-tensorflow-for-hackers-part-vii-20e0c85301bd) - 关于如何依靠异常检测来实施可疑卡交易的教程.

- [Training an ML model to score chargebacks](https://twitter.com/patio11/status/1315452323330621440) - 一个平台网络效应的例子，它可以预测赢得争议的可能性.

- [How credit card thieves use free-to-play apps to launder gains](https://kromtech.com/blog/security-center/digital-laundry) - 为防止滥用，服务提供商必须加强信用卡验证和帐户创建过程.

### Trust Score

基于信号集合的综合评分通常是用户可信度的最佳代表. 大多数时候，客户支持依靠他们在这些操作没有自动触发时采取行动.

- [The Secret Trust Scores Companies Use to Judge Us All](https://www.wsj.com/articles/the-secret-trust-scores-companies-use-to-judge-us-all-11554523206) - 我们购买的几乎所有东西、我们购买的方式以及我们从哪里购买的东西都会被秘密地输入人工智能驱动的验证服务，帮助公司防范信用卡和其他形式的欺诈.

- [GCP improved account management policies to better support customers](https://cloudplatform.googleblog.com/2018/07/improving-our-account-management-policies-to-better-support-customers.html) - 或者为什么过度依赖欺诈自动化可能会导致用户不满.

- [Digital Ocean's Update on Customer Shutdown Incident](https://blog.digitalocean.com/an-update-on-last-weeks-customer-shutdown-incident/) - 从业务的角度来看，积极关闭用户服务器是好的，可以防止欺诈者滥用免费资源，除非它不是.

- [Awesome Credit Modeling](https://github.com/mourarthur/awesome-credit-modeling#readme)  - 如何使用统计方法对申请人进行分类以降低风险. 那里有很多灵感和研究论文来提高总体评分.

### Statistics

自动化欺诈检测的最佳工具.

- [Benford's law](https://en.wikipedia.org/wiki/Benford's_law) - 数字分布可能是会计欺诈的信号.

- [Integer percentages as electoral falsification fingerprints](https://arxiv.org/pdf/1410.6059.pdf)  - 本着与上述相同的精神，本文表明，在选举中报告轮数的频率是人为异常的信号. 可能适用于某些打击欺诈的领域.

- [Huber loss](https://en.wikipedia.org/wiki/Huber_loss) - “稳健回归中使用的损失函数，与平方误差损失相比，它对数据中的异常值不太敏感.”

- [Peak Detection in the Python World](https://blog.ytotech.com/2015/11/01/findpeaks-in-python/) - 检测异常值的简单方法.

### Billing

- [More than 600 million users installed Android 'fleeceware' apps from the Play Store](https://www.zdnet.com/article/more-than-600-million-users-installed-android-fleeceware-apps-from-the-play-store/) - 一种新的欺诈行为，在试用期结束后，应用程序会默默地向用户收费.

- [CEO Fraud](https://www.knowbe4.com/ceo-fraud) - 负责收取付款的计费团队是此类欺诈的牺牲品，其中 CEO 被冒充以赞扬特殊的付款交易.

- [The Challenges of Operating a Computing Cloud and Charging for its Use](https://web.stanford.edu/class/cs349d/docs/theimer.pdf)  - 跳过 AWS VP 演示的前 90%（关于一般系统可靠性）. 最后四张幻灯片很好地总结了计费云服务的含义，尤其是使用软配额来限制欺诈.

- [Fraud in Telephony Networks](http://www.s3.eurecom.fr/docs/eurosp17_sahin.pdf)  - 大多数电话欺诈都围绕计费和微交易计量. 本文采用分类法（第 6 页）区分根本原因、漏洞、利用技术以及欺诈者可以从中受益的方式.

## UX/UI

当涉及到金钱时，用户很容易生气.  UX 和 UI 可能有助于减少挫败感.

- [Apple Subscriptions HIG](https://developer.apple.com/design/human-interface-guidelines/subscriptions/overview/) - 如何制作的指南和建议 [auto-renewable subscriptions](https://developer.apple.com/app-store/subscriptions/) 方便使用的.

- [Which has a higher conversion rate: A single long ecommerce checkout form or a multi-step one?](https://capitalandgrowth.org/questions/2055/which-has-a-higher-conversion-rate-a-single-long-e.html) - 首先关注购物车中的其他内容，例如通过在信用卡和完成步骤附近添加保证（信任标记、推荐）以及您可能在产品探索早期使用的一些保证语言来缓解焦虑和事后猜测过程.

## Business Intelligence

作为计费管道的利益相关者，您使用所有关键数据来衡量和报告业务的健康状况.

### Metrics

定义和收集值得监控的关键绩效指标 (KPI).

- [Startup financial models - 12 templates compared for SaaS](https://www.stephnass.com/blog/startup-financial-model) - 在您的运营中获得更好的可见性的重要灵感来源.

- [16 Startup Metrics](https://a16z.com/2015/08/21/16-metrics/) - 两个关键指标是客户获取成本 (CAC) 和客户终身价值 (CLV).

- [Thinking about growth and profit](https://jlongster.com/thinking-growth-profit) - 讨论投资、利润和增长之间的关系，以及它如何影响定价、免费试用和计划结构的决策.

- [A Quantitative Approach to Product Market Fit](https://tribecap.co/a-quantitative-approach-to-product-market-fit/) - 上面生成的指标具有更大的影响力，因为它们被用作验证产品与市场契合度的重要信号.

- [Startup growth calculator](http://growth.tlb.org) - 为初创公司提供简单而有效的交互式盈利能力计算器.

- [An Overview of Visa](http://minesafetydisclosures.com/blog/2019/7/23/part-ll-an-overview-of-visa) - Visa商业模式和指标的重大细分.

- [The SaaS Financial Model You'll Actually Use](https://baremetrics.com/blog/saas-financial-model) - 完整的 statup 财务概览，为您提供有关您生成的指标如何适应更大范围的额外背景信息.

### Customer Lifetime Value

您为每位客户创造了多少净价值？ 客户生命周期价值（CLV，或 LTV）量化了这一点，理解并采取行动是您企业销售工作中最重要的部分.

- [You're all calculating churn rates wrong](https://medium.com/swlh/youre-all-calculating-churn-rates-wrong-cbab072cd992)  - “从表面上看，流失率似乎是客户生命周期变化的自然代表. 让我们深入研究为什么这是不正确的.” 流失率不是计算 CLV 的有意义的指标，因为在客户生命周期内，流失概率不是恒定的. 大部分时间是因为您的免费试用和优惠券.

- [How to project customer retention](https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf) - 一篇开创性的论文，与上述相比具有更强的方法： [the exponential distributions is replaced by a geometric model](https://news.ycombinator.com/item?id=24833319)，更适合月度合同.

- [RFM (customer value)](https://en.wikipedia.org/wiki/RFM_%28customer_value%29) - CLV 的改进模型，用于根据新近度、频率和货币价值对用户进行细分.

- [Churn Prediction](https://towardsdatascience.com/churn-prediction-3a4a36c2129a)  - “如何以简单的方式使用 Python，通过将预测方法应用于您的所有行为来推动公司的发展.” 依赖于 XGBoost 二进制分类.

- [Lifetimes](https://github.com/CamDavidsonPilon/lifetimes) - 一个功能齐全的 Python 包，用于根据用户的“活着”和“死亡”状态分析用户.

- [`retentionizer`](https://github.com/chrisclark/retentionizer) - Python 包显示每个群组的预计保留率并计算该群组中给定客户的 LTV.

### Data Engineering

要实现数据生产和消费的工业化，您需要数据工程师对数据进行清理、持久化和整合. 只有在获得这些数据基础之后，您才可能会考虑入职数据科学家.

- [AI vs Data Science vs Data Engineering](https://blog.insightdatascience.com/how-emerging-ai-roles-fit-in-the-data-landscape-d4cd922c389b)  - “数据工程师构建数据管道和基础设施，以确保转换数据的持续可用性. 数据科学家从这些数据中分析和构建模型，以开发新的产品功能或推动业务的底线.” 至于人工智能专业人士，他们的重点是认知自动化.

- [Ten Ways Your Data Project is Going to Fail](https://www.martingoodson.com/ten-ways-your-data-project-is-going-to-fail/)  - 你不需要数据科学家.  “对于 ETL，聘请数据工程师. 对于报告，请聘请 BI 分析师. 结束.”

- [Cargo cult data science](http://blog.richardweiss.org/2017/07/25/data-science-in-organizations.html)  - “数据科学最好被视为公司文化的一种形式，而不是一组技术. 然而，许多公司将尝试通过获取数据科学技术来创造这种公司文化，而不是致力于他们的文化.”

- [Why not use Double or Float to represent currency?](https://stackoverflow.com/questions/3730019/why-not-use-double-or-float-to-represent-currency/3730040#3730040) - 因为精度：浮点数和双精度数不能准确地表示我们用于货币的以 10 为底的倍数.

- [Never Use Floats for Money](https://husobee.github.io/money/float/2016/09/23/never-use-floats-for-currency.html)  - “这正是我们试图用二进制表示 10^-1 或 0.1 时遇到的问题. 没有 0.1 或 0.01 的精确二进制表示.”

- [European Spreadsheet Risks Interest Group - Horror Stories](http://www.eusprig.org/horror-stories.htm) - 一系列案例，其中不受控制和未经测试的电子表格模型导致收入损失、定价错误、决策失误、欺诈和系统性财务失败.

### Tools

用于构建可视化、仪表板、SQL 查询和深入研究数据的软件.

- [Practical Business Python](https://pbpython.com) - 一个博客，收集和传播有关如何在业务环境中更有效地使用 Python 的想法.

- [`redash`](https://github.com/getredash/redash) - 连接和查询您的数据源，构建仪表板以可视化数据并与您的公司共享.

- [Metabase](https://github.com/metabase/metabase) - Metabase 是一个开源解决方案，用于探索和可视化数据并支持大量数据库.

- [Apache Superset](https://github.com/apache/incubator-superset) - 企业级商业智能 Web 应用程序.

- [Meltano](https://gitlab.com/meltano/meltano) - 用于整个数据生命周期的开源约定优于配置的产品，从加载数据到分析数据.

- [`insights`](https://github.com/mariusandra/insights) - Insights 是一种可视化探索 PostgreSQL 数据库的工具，重点是生成显示业务绩效随时间变化的图表.

- [`falcon`](https://github.com/plotly/falcon) - 适用于 Windows 和 Mac 的免费开源 SQL 客户端，带有内置图表.

## Competitive Analysis

一堆资源，用于跟踪在该域中运营的所有公司的当前状态和进度.

- [AWS Cost Management announcements](https://aws.amazon.com/about-aws/whats-new/aws-cost-management/) - 添加到计费边界的所有新功能的来源.

- [AWS reserved instances vs saving plan](https://www.prosperops.com/assets/img/blog/ris_and_savings_plans.png) - 不同方案的特征矩阵及其平均折扣.

- [EC2 Spot Price Tracker](https://github.com/grosskur/ec2price) - 收集和绘制 EC2 现货价格的 Web 应用程序.

- [GCP billing release notes](https://cloud.google.com/billing/docs/release-notes) - GCP 计费功能的最新变化.

- [GCP billing news](https://www.gcpweekly.com/gcp-resources/tag/billing/) - 来自非官方的 Google Cloud Platform 时事通讯.

- [More choice, less complexity: New Compute Engine pricing options on tap](https://cloud.google.com/blog/products/compute/more-choice-less-complexity-new-compute-engine-pricing-options-on-tap) - 最近 GCP 定价功能的总结.

- [DigitalOcean Billing changelog](http://docs.digitalocean.com/release-notes/billing/) - DO 上的所有最新账单更新.

## Commercial Solutions

- [Orbitera](https://www.orbitera.com) - GCP 的计费子公司.

- [16 Online Subscription Billing Tools](https://www.analyzo.com/search/online-subscription-billing-tools/106) - 订阅和定期计费服务的最新列表.

- [OpenCell](https://opencellsoft.com) - 源自开源电信计费项目的货币化平台.

- [Laravel Spark](https://spark.laravel.com) - 为您不想编码的所有内容提供脚手架的软件包：订阅和团队计费、发票，还有用户帐户功能.

- [Bullet Train](https://bullettrain.co) - 与上述相同，但适用于 Ruby on Rails.

- [ASP.NET Zero](https://aspnetzero.com) - 多租户、身份验证和授权、发票和付款.

- [Nextless JS](https://nextlessjs.com) - 使用 React 和无服务器在 Node.js 中构建 SaaS 产品所需的一切：身份验证和授权、发票和付款.

- [Chargebee](https://www.chargebee.com) - 订阅计费和收入操作.

- [Armatic Billing & Invoicing Software](https://www.armatic.com/billing) - 发票、应收账款.

- [Sensus Billing Access Application](https://sensus.com/products/billing-access/) - 公用事业公司的计费和计量解决方案.

- [Quaderno](https://quaderno.io)  - 计算销售税、增值税和消费税； 自动收据.

- [keygen](https://keygen.sh) - 销售和管理许可证密钥.

## History

- [The vanished grandeur of accounting](https://www.bostonglobe.com/ideas/2014/06/07/the-vanished-grandeur-accounting/3zcbRBoPDNIryWyNYNMvbO/story.html) - 会计绘画是荷兰艺术的重要流派.

- [Engineering and Operations in the Bell System](http://bitsavers.trailing-edge.com/communications/westernElectric/books/Engineering_and_Operations_in_the_Bell_System_2ed_1984.pdf) - Starting at page #445, the "10.5 Billing Equipment and Systems" section describe the history and technical evolutions of Bell's phone calls metering and pricing.

## Contributing

随时欢迎您的贡献！ 请看一下 [contribution guidelines](https://github.com/kdeldycke/awesome-billing/blob/master/.github/contributing.md) 第一的.

## Footnotes

The [header image](https://github.com/kdeldycke/awesome-billing/blob/main/assets/awesome-billing-header.jpg) 是基于修改 [photo](https://unsplash.com/photos/u2zSzMTwIjQ) 经过 [Denny Müller](https://unsplash.com/@redaquamedia).
