<div class="github-widget" data-repo="kdeldycke/awesome-billing"></div>
<!--lint disable awesome-heading-->

<p align="center">
  <a href="https://github.com/kdeldycke/awesome-billing/">
    <img src="https://raw.githubusercontent.com/kdeldycke/awesome-billing/raw/main/assets/awesome-billing-header.jpg" alt="💰 Awesome Billing">
  </a>
</p>

<p align="center">
  <a href="https://github.com/sponsors/kdeldycke">
    <strong>Yᴏᴜʀ Pᴀʏᴍᴇɴᴛ & Bɪʟʟɪɴɢ Pʀᴏᴅᴜᴄᴛ ʜᴇʀᴇ!</strong>
    <br/>
    <sup>Add a link to your company or project here: back me up via a GitHub sponsorship.</sup>
  </a>
</p>

---

<p align="center">
  <i>Money is the most universal and most efficient system of mutual trust ever devised.</i><br>
  — Yuval Noah Harari<sup id="intro-quote-ref"><a href="#intro-quote-def">[1]</a></sup>
</p>

Any company needs at one point to get money from customers. That's when things gets messy for us developers, as we try to reconcile the complexity of the business with our software stack.

This [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) list helps software engineers **bootstrap billing & payments systems, and make sense of invoicing, pricing, accounting, marketplace, fraud and business intelligence**.


<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=6 --minlevel=2 -->


<!-- mdformat-toc end -->

## Basics

<img align="right" width="50%" src="https://raw.githubusercontent.com/kdeldycke/awesome-billing/master/./assets/cloud-software-stack-billing.jpg"/>

In a Stanford class providing an [overview of cloud computing](http://web.stanford.edu/class/cs349d/docs/L01_overview.pdf), the software architecture of the platform is described as in the right diagram →

<!--lint disable double-link-->

Billing is one of the transversal pillar of the ecosystem, where customers, products and business meets. The [other pillar being Identity and Access Management (IAM) 👤](https://github.com/kdeldycke/awesome-iam/).

<!--lint enable double-link-->

This highlight the strategic importance of the domain, not only for cloud providers but virtually any business, especially those who are software-centric.

- [Pricing, my only growth hack at Qonto](https://getlago.substack.com/p/pricing-my-only-growth-hack-at-qonto?s=r) - Most businesses don't know how to iterate over pricing: sales teams dictates them without involvement of the people in charge of implementation, which ends up in frustration for all. That's why you need to recognize billing as a critical function of your organization.

- [5 things I learned while developing a billing system](https://arnon.dk/5-things-i-learned-developing-billing-system/) - A great introduction on all the various aspects of a billing system, from currency to invoices, including great illustrations on the logic of changing plans. All these topics are detailed in dedicated sections below.

- [Open guide to AWS](https://github.com/open-guides/og-aws#billing-and-cost-management) - Links to the *Billing and Cost Management* section which details the broad characteristics of billing for a cloud provider.

- [Billed for ¥21,120, invoiced at ¥2,112,000 and paid ¥2,112,000](https://twitter.com/kur/status/1668082843728367616) - [Get rid of integers and floats for monetary values](https://twitter.com/kdeldycke/status/1599113889093890049). Use decimals. Or face the risks of anomalous x100 charges.

- How to recruit software engineers in this domain? “The trick is to make the accounting/billing/payment department the antechamber of data engineering.” ([source](https://twitter.com/kdeldycke/status/1422564355799924736))

## Pricing

From monthly subscription to commodity-like on-the-go consumption, there's plenty of scheme out there to structure your product's pricing. Including the good old shopping-cart funnel.

- [Don't just roll the dice – Software pricing guide](https://neildavidson.com/downloads/dont-just-roll-the-dice-2.0.0.pdf) - Huge and complete collection of pricing scheme, with their psychological effect and impact on revenue model.

- [Business Model Patterns](https://reasonstreet.co/business-model-library/) - A list of 15 different ways to sell products and services.

- [Axial - Business models](https://axial.substack.com/p/axial-business-models) - 38 models for inspiration.

- [The Network Monetization Map: Aligning Incentives with Revenue](https://medium.com/breadcrumb/the-network-monetization-map-aligning-incentives-with-revenue-b73c362d1ad5) - 6 models of monetization relying on network effect.

- [The 5 Pillars of PriceOps](https://priceops.org) - A manifesto inspired by the DevOps movement in which pricing is no longer ossified, but is practiced as a responsive iteration process, and implemented as a flexible property of the system.

### Usage-based Pricing

The dynamic scheme for elastic resources.

- [Why I Love Usage-Based Pricing](https://www.rdegges.com/2020/the-only-type-of-api-services-ill-use/) - “The most important reason I like this pricing model is that it heavily incentivizes both the customer and the service provider to act in everyone's best interest.” Also details issues with other pricing models.

- [Use-cases for cloud services](https://news.ycombinator.com/item?id=19830022) - The reason usage-based pricing makes even more sense for cloud services: to optimize ROI, keep all regular workload in traditional architecture and reserve cloud computing for elastic and experimental projects.

- [Socially Optimal Pricing of Cloud Computing Resources](https://webee.technion.ac.il/people/shimkin/PAPERS/Menache-CloudPricing-Conf2011.pdf) - “The socially optimal operating point is unique, and can be sustained by a linear, usage-based tariff, which charges a fixed price per unit resource and unit time.” This paper justify usage-based pricing for cloud resources.

- [A Survey of Profit Optimization Techniques for Cloud Providers](https://dl.acm.org/doi/fullHtml/10.1145/3376917) - “The strategy of improving user service quality is discussed first, followed by the pricing strategy for cloud resources to maximize revenue.”

- “Billing is not complex on purpose: it's the price to pay for elasticity.” ([source](https://twitter.com/kdeldycke/status/1214160678363246592)) - Or why you're likely to get an endless stream of complaining users if choosing utility pricing scheme: while accurate to the (milli-)cent, this model is frustrating for customers not ready to invest time grasping the underlaying concepts.

- [Octane's Meter Types](https://docs.getoctane.io/data-types-reporting-types-and-aggregations#Wggma) - Nice illustrations of the quantization applied to time and value quantums on variable usages.

- [Riemann sum](https://en.wikipedia.org/wiki/Riemann_sum) - The starting point about quantization of usage.

- [Allen's interval algebra](https://en.wikipedia.org/wiki/Allen%27s_interval_algebra) - Implementing usage-based pricing is tricky, and this algebra will help you organize temporal reasoning. Also see this [Stack Overflow question with clean schema](https://stackoverflow.com/questions/12069082/allens-interval-algebra-operations-in-sql?rq=1).

- [Reconcile Your Monthly GCP Invoice with BigQuery Billing Export](https://medium.com/@lukwam/reconcile-your-monthly-gcp-invoice-with-bigquery-billing-export-b36ae0c961e) - Behind the quest of this developer to track its expenses, you get a glimpse on cloud billing difficulties. While not explicitly pointed out, pricing cloud resources is hard and the result of quantization, granularity and rounding, between space, time and currencies.

- [AWS EC2 T2 Instances Demystified: Don't Learn The Hard Way](https://roberttisdale.com/aws-ec2-t2-instances-demystified-dont-learn-hard-way/) - An example of really tricky burstable instances which accrues and limits its own amount of CPU usage credits.

- [“Designing billing for a service can be really challenging”](https://news.ycombinator.com/item?id=23536919) - Personal anecdote on the design of the pricing plan for AWS Simple Email Service.

- [Subscription-based pricing is dead: Smart SaaS companies are shifting to usage-based models](https://techcrunch.com/2021/01/29/subscription-based-pricing-is-dead-smart-saas-companies-are-shifting-to-usage-based-models/) - Usage-based pricing is more optimal and more fair: it “allows a customer to start at a low cost, minimizing friction to getting started while still preserving the ability to monetize a customer over time”.

- [Electropedia: Tariffs for electricity](https://www.electropedia.org/iev/iev.nsf/index?openform&part=691) - Before the cloud, there was another metered resource priced by its usage: electricity. Here is a detailed (and multi-lingual) taxonomy of its vocabulary from the International Electrotechnical Commission.

- [Lago](https://github.com/getlago/lago) - Open-source metering & usage-based billing.

### Subscription Plans

Highly popular for SaaS businesses, subscription plans are easy to comprehend.

- [Pricing low-touch SaaS](https://stripe.com/en-in/atlas/guides/saas-pricing) - “In low-touch SaaS, the most common way packages are presented are as different columns in a pricing grid, with each column corresponding to a plan, offered at a different price, with differential access to features or maximum allowable usage along some axis interesting to the business.”

- [Lotus](https://github.com/uselotus/lotus) - Open-source project to manage pricing & packaging infrastructure.

- [`f-license`](https://github.com/furkansenharputlu/f-license) - Open-source license key generation and verification tool in Go.

### Hybrid

Uncommon pricing schemes.

- [The Three Part Tariff](https://tomtunguz.com/three-part-tariffs/) - Beyond linear pricing, there is a place for additional platform fees and free-tiers in the pricing structure.

### Strategy

Theory and practical insight to help you choose the right pricing tactics.

- "There are two ways to make money. You can bundle, or you can unbundle." - [Jim Barksdale](https://hbr.org/podcast/2014/07/marc-andreessen-and-jim-barksdale-on-how-to-make-money.html#transcript-section).

- [Pricing Psychology](https://www.nickkolenda.com/psychological-pricing-strategies/) - Which numbers should you use? How high should it be? Should it be rounded? This guide has 42 tricks to help you choose the best price.

- [The 7 factors to consider when pricing your startup product](https://tomtunguz.com/how-to-price-your-startups-product/) - Pricing is an offensive tool to reinforce your product value and underscore the company core marketing message.

- [The Anatomy of SaaS Pricing Strategy](https://www.priceintelligently.com/hubfs/Price-Intelligently-SaaS-Pricing-Strategy.pdf) - Explain how to articulate the pricing of SaaS businesses around the product strategy.

- [The cup-of-coffee pricing fallacy](https://blog.gingerlime.com/2020/the-cup-of-coffee-pricing-fallacy/) - Explains why it is a sloppy analogy.

### Market Research

Survey methods and price discovery technics to find the right price point.

- [Jeremy Howard - From Predictive Modelling to Optimization](https://youtu.be/vYrWTDxoeGg?t=542) - “In insurance, the price is the product. (…) How do I change price to make shitload of money?” Or how to deliver results (optimal price for a customer) instead of delivering data (calculating a customer's risk, which had been the standard approach used by actuaries previously).

- [Gabor–Granger method](https://en.wikipedia.org/wiki/Gabor%E2%80%93Granger_method) - Used in surveys to determine the price for a new product or service. The results can be used to produce a demand chart and a revenue curve.

- [Van Westendorp's Price Sensitivity Meter](https://en.wikipedia.org/wiki/Van_Westendorp%27s_Price_Sensitivity_Meter) - PSM is a market technique for determining consumer price preferences. Allows for drawing a revenue curve to estimate the price point delivering the maximum revenue.

- [Pricing niche products](https://kevinlynagh.com/notes/pricing-niche-products/) - “The most compelling argument against simply picking a price, though, is that it limits how much you can learn about your market.” Then the author setup vickrey auctions to discover price.

- [Finding the max revenue price mark for digital products](https://medium.com/@hovm/finding-the-max-revenue-price-mark-for-digital-products-24cef24f746d) - “To find the optimal price that provides maximum revenue for your product you will need to field-test several price points; you then reconstruct the revenue curve and find the peak.”

- [Personalised pricing and EU law](https://www.econstor.eu/bitstream/10419/205221/1/de-Streel-Jacques.pdf) - Some cases of price personalisation are prohibited in EU due to consumer protection and data protection rules.

## Product Catalog

The central repository of all available services, products, variants, options and pricing available to the customer to purchase. Catalogs for cloud services are most of the time tailor-made, but there is some classic PDM solutions ([Product Data Management](https://en.wikipedia.org/wiki/Product_information_management), a.k.a. PIM for Product Information Management) out there that might fit the bill.

- [GCP Product Catalog](https://cloud.google.com/blog/products/gcp/introducing-cloud-billing-catalog-api-gcp-pricing-in-real-time) - All GCP SKUs available as an API.

- [Akeneo PIM](https://github.com/akeneo/pim-community-dev) - The open-source variant of the commercial Akeneo products.

- [Pimcore](https://github.com/pimcore/pimcore) - An open-source UI and database to manage product metadata, written in PHP Symfony.

- [OpenPIM](https://www.openpim.org) - A streamlined open-source project, focusing on PIM-only features.

- [Comparing 3 open source PIM solutions](https://medium.com/@slavapedak/comparing-3-free-and-open-source-product-information-management-pim-solutions-e83a1898f91e) - Comparative study of the 3 projects above.

## Calculator

Simulate a virtual invoice depending on the resource you plan to use.

- [Cloud Cost Calculator](https://github.com/scalyr/cloud-costs) - Web-based tool for finding the cheapest cloud servers for a given set of requirements.

- [Cloudorado](https://www.cloudorado.com) - A comparison matrix which use ECU (Amazon's vCPU) as a CPU power measure unit.

- [EC2Instances.info](https://ec2instances.info) - Easy Amazon EC2 Instance Comparison.

## Cost Forecast

Help your customers predict their upcoming and future consumption based on their past usage.

- [Forecasting: Principles and Practice](https://otexts.com/fpp2/) - “Comprehensive introduction to forecasting methods and to present enough information about each method for readers to be able to use them sensibly.”

- [Transforming Financial Forecasting with Data Science and Machine Learning at Uber](https://www.uber.com/blog/transforming-financial-forecasting-machine-learning/) - Discusses how Uber apply data science and machine learning in their financial planning platforms.

- [Time Series Prediction - A short introduction for pragmatists](https://www.liip.ch/en/blog/time-series-prediction-a-short-comparison-of-best-practices) - Great introduction on how time series can be used to evaluate business problems.

- [Forecasting with sktime](https://github.com/alan-turing-institute/sktime/blob/master/examples/01_forecasting.ipynb) - A more detailed tutorial on how to use past data to make temporal forward predictions. And be aware of the [differences between sktime and the Prophet project](https://news.ycombinator.com/item?id=24543861) mentionned in the article above.

- [Darts](https://github.com/unit8co/darts) - Python library for user-friendly forecasting and anomaly detection on time series. It wraps a huge number of models, including [Prophet](https://facebook.github.io/prophet/). Great for experiments, but bear in mind that all the [models in Darts expects](https://news.ycombinator.com/item?id=37665435) that your data comes at a very regular interval, and make a lot of assumptions about their shape.

- [Komiser](https://github.com/mlabouardy/komiser) - Open-source tool to stay under budget by uncovering hidden costs, monitoring increases in spend, and making impactful changes based on custom recommendations.

- [GCP Cost Forecast](https://cloud.google.com//billing/docs/how-to/reports#cost-forecast) - An example of consumption trend line for resource consumption.

- [AWS Forecast](https://aws.amazon.com/forecast/) - A full-featured hosted product to perform forecasting on any time-series.

- [How to save money on your AWS bill](https://twitter.com/QuinnyPig/status/1091041507342086144) - “The biggest cost savings there are: 1. Turning things off that you're not using; 2. Then spot instances; 3. Then reserved instances.”

## Marketplace

A marketplace connect supply with demand that lead to a financial transaction. If there is no payment involved, then it is an aggregator, or a hub. Not a marketplace.

- [Customized Regression Model for Airbnb Dynamic Pricing](https://www.kdd.org/kdd2018/accepted-papers/view/customized-regression-model-for-airbnb-dynamic-pricing) - This paper describes the pricing strategy model deployed at Airbnb.

- [Papers we love: Auctions and Bidding](https://github.com/papers-we-love/papers-we-love/tree/master/economics#auctions-and-bidding) - A collection of papers on bidding and auctions.

- [Vickrey auction](https://en.wikipedia.org/wiki/Vickrey_auction) - Hinted by an [HN comment](https://news.ycombinator.com/item?id=19145391), in which yes, “‘Asking people what they'd pay for and how much rarely works.’ (…) \[but\] using a Vickrey auction, similar to Google's ad auction mechanism, can elicit a person's maximum willingness-to-pay.”

- [19 Tactics to Solve the Chicken-or-Egg Problem and Grow Your Marketplace](https://www.nfx.com/post/19-marketplace-tactics-for-overcoming-the-chicken-or-egg-problem) - “Which comes first, the supply or the demand? Chicken or egg?”

- How to Kickstart and Scale a Marketplace Business: [Constrain the marketplace](https://www.lennyrachitsky.com/p/how-to-kickstart-and-scale-a-marketplace); Decide which side of the marketplace to concentrate on; Drive initial supply; Drive initial demand. A 4-parts series with dozen of interviews of people with direct experience building and scaling marketplaces.

- [A Rake Too Far: Optimal Platform Pricing Strategy](https://abovethecrowd.com/2013/04/18/a-rake-too-far-optimal-platformpricing-strategy/) - A bit of vocabulary: “In a casino, the term *rake* refers to the commission that the house earns for operating a poker game. (…) While casinos use the term *rake*, a plethora of interesting word choices exist which all describe the same thing – keeping a little bit of the revenue for the company that is running the service.”

### Cloud Resources

This sub-section focus on bid/ask mechanism matching resource producer with consumers. Most of the time these are one-sided markets with the big platform trying to amortized under-utilized inventory.

- [Incentive Engineering for Computational Resource Management](https://papers.agoric.com/assets/pdf/papers/incentive-engineering-for-computational-resource-management.pdf) - Paper exploring the “mechanisms for the allocation of processor time and storage that are compatible both with programming practice and with market mechanisms.”

- [Pricing of Service in Clouds: Optimal Response and Strategic Interactions](http://www.sigmetrics.org/mama/2013/abstracts2013/UrgaonkarEtAl.pdf) - “How should the consumer modulate its demand to optimize its profits? (…) How should the provider and consumer negotiate the specific pricing structure they will employ?” Covers non-linear models, tiered pricing, elastic demand, consumer et provider strategies.

- [Dynamic Cloud Pricing for Revenue Maximization](https://henryhxu.github.io/share/hxu-tcc2013.pdf) - “Amazon's spot price is unlikely to be set according to market supply and demand. Rather, price oscillates within a very narrow band most of the time, which is more likely to be an artifact of some pricing algorithm with predetermined reserve price.”

- [Usage Patterns and the Economics of the Public Cloud](https://mc4f.ee/Papers/PDF/EconPublicCloud.pdf) - “We examine the economics of demand and supply in cloud computing. (…) These results explain why fixed prices currently prevail despite the seeming need for time-varying dynamics. Examining the actual CPU utilization provides a lens into the future. (…) demand fluctuations would be on par with the three classic industries where dynamic pricing is important (hotels, electricity, airlines) and dynamic prices would be essential for efficiency.”

- [Maximizing Profit of Cloud Brokers under Quantized Billing Cycles: a Dynamic Pricing Strategy based on Ski-Rental Problem](https://arxiv.org/pdf/1507.02545.pdf) - “The key idea of our algorithms is to use pricing signal to regulate user demand. One may argue that such an algorithm gives poor service to the user as it pushes tasks out of the queue in order to maximize cloud broker's profit.”

- [Present or Future: Optimal Pricing for Spot Instances](https://web.archive.org/web/20150708151037/http://www.temple.edu/cis/icdcs2013/data/5000a410.pdf) - “Pricing policy of spot resources should be carefully designed and the impact on both present and future should be considered.”

- “You always pay the spot market price, not your bid.” ([source](https://news.ycombinator.com/item?id=20347716)) - Simple explanation of the bidding mechanism.

- [Deconstructing Amazon EC2 Spot Instance Pricing](http://www.cs.technion.ac.il/~dan/papers/Spotprice11CloudCom.pdf) - “Cloud providers possessing large quantities of spare capacity must either incentivize clients to purchase it or suffer losses. Amazon is the first cloud provider to address this challenge, by allowing clients to bid on spare capacity and by granting resources to bidders while their bids exceed a periodically changing spot price.”

- [GCP Preemptible VMs vs AWS Spot Instances](https://news.ycombinator.com/item?id=9564287) - “Google's prices are fixed, whereas AWS uses a market model”.

- “Look at the 3-month spot price history to estimate cost and to discover combinations of availability zone and instance type with extra capacity.” ([source](https://news.ycombinator.com/item?id=16071684)) - Users are seeking more transparency on the spot market.

- [The Eternal Cost Savings Of Netflix's Internal Spot Market](http://highscalability.com/blog/2017/12/4/the-eternal-cost-savings-of-netflixs-internal-spot-market.html) - When you're big enough that [creating an internal secondary market](https://medium.com/netflix-techblog/creating-your-own-ec2-spot-market-6dd001875f5) for instances makes economic sense.

- [AutoSpotting](https://github.com/AutoSpotting/AutoSpotting) - Tool that easily and reliably converts (all) your existing AutoScaling groups to cheaper spot instances.

### Online Ads

Targeted online advertisements marketplaces have a lot in common with traditional cloud marketplace. Some good inspiration there, from concepts to tech.

- [RTB Budget Pacing Summarized](https://github.com/PragmaticLab/RTB_Budget_Pacing_Summarized) - A collection of budget pacing resources for targeted online advertisements.

- [Samsung's online ads platform/exchange war story](https://github.com/eloraiby/fs-pacer/blob/master/fs-pacer.md) - How to scale to 5M bid request/s, 2ms Max Response Time.

- [`RTB4Free`](https://github.com/RTB4FREE) - Open Source Bidder and Demand Side Platform (DSP).

## Accounting

- “The Accounting department is usually backwards facing. The Finance department is usually forwards facing.” ([source](https://news.ycombinator.com/item?id=25366184))

### Double-Entry Model

The core concept of accounting is double-entry. It is the most critical part to grasp in order to properly design any robust system that tracks money.

- [Accounting for Developers 101](https://docs.google.com/document/d/1HDLRa6vKpclO1JtxbGB5NeAYWf8cf1UMGy22o8OZZq4) - A general introduction to history and vocabulary of accounting.

- [Accounting for Computer Scientists](https://martin.kleppmann.com/2011/03/07/accounting-for-computer-scientists.html) - Describes how to view accounting in the form of graphs in which money flows, then how these movements are materialized in the financial statements of a small company.

- [The Double-Entry Counting Method](https://beancount.github.io/docs/the_double_entry_counting_method.html) - Same premise as above, but way more detailed and complete, as it adds reporting and implementation details.

- [Accounting Memento For Entrepreneurs (US GAAP)](https://www.odoo.com/documentation/functional/accounting.html) - An interactive form to play with accounting concepts.

### Bookkeeping

Everything you need to know about the daily practice of keeping your accounting data clean and tidy.

- [So, you want to learn Bookkeeping!](https://www.dwmbeancounter.com/BCTutorials/BCIntro/index.html) - Focus on the daily operations of recording and maintaining the transactions of a business.

- [Reconciliation: A game designed to frustrate the player](https://bam.kalzumeus.com/archive/a-game-that-intentionally-frustrates-the-player/) - “Reconciliation is a business process which arises almost entirely because of a lack of structured data in the pipelines that convey money between businesses”. There are some hack to streamline the process, like adding an arbitrary discount to produce unique trailing decimals, or setup a couple of virtual bank accounts as proxy.

- [Plain text accounting tools](https://plaintextaccounting.org/#software) - Extensive list of open-source personal finance projects that might be great to look into for inspiration on double-entry accounting and bookkeeping.

- And a list of graphical accounting tools: [GNUCash](https://gnucash.org) (GTK+), [Grisbi](https://grisbi.org) (C), [Firefly III](https://firefly-iii.org) (PHP).

- [GnuCash Tutorial and Concepts Guide](https://www.gnucash.org/docs/v2.4/C/gnucash-guide/) - A complete tutorial on personal finance tracking with GnuCash.

- [Frappe Books](https://github.com/frappe/books) - Free Desktop book-keeping software for small-businesses and freelancers.

- [Luca](https://github.com/brandon-rhodes/luca) - YAML accounting and JSON tax forms.

- [Sequence](https://github.com/decimals/sequence) - API that store, validate and reports asset movements. Also known as a Ledger. Sequence is immutable, scalable, and easy to use.

- [Go DB Ledger](https://github.com/darcys22/godbledger) - An open source accounting system that aims to make the recording of double entry bookkeeping transactions programmable.

- [Ledger](https://github.com/numary/ledger) - A scriptable financial ledger, designed to make it easy to model complex financial transactions.

- [Akaunting](https://github.com/akaunting/akaunting) - Open source software designed for small businesses and freelancers.

### Software design and implementation

Now that you're somewhat familiar with the concepts and practice of accounting, here are some resources to help you implement that knowledge into software systems.

- [Moonpig: a billing system that doesn't suck](https://blog.plover.com/prog/Moonpig.html) - Design decisions behind a billing and accounting system. Key takeaway: some companies still pays by checks; do not use floats; complex customer workflows; date and time issues; mutable data.

- [Books, an immutable double-entry accounting database service](https://developer.squareup.com/blog/books-an-immutable-double-entry-accounting-database-service/) - Explain the basic data model of a double-entry accounting system relying on Google Spanner for internal use at Square.

- [TigerBeetle](https://github.com/coilhq/tigerbeetle) - A distributed financial accounting database to ensure that the money either moves, or doesn't move, that it doesn't get lost somewhere in between.

- [Django Hordak](https://django-hordak.readthedocs.io) - Core functionality of a double entry accounting system for Django.

- [Managed accounts for Django](https://github.com/django-oscar/django-oscar-accounts) - A 'managed account' is an allocation of money that can be debited and credited.

- [Triple‐entry accounting with blockchain: How far have we come?](https://sci-hub.st/10.1111/acfi.12556) - “Triple‐entry accounting is a new and a more efficient way to address fundamental trust and transparency issues that plague current accounting systems. Triple‐entry accounting with blockchain, when properly implemented, can fundamentally improve accounting.”

### Currencies

Global companies needs to know how to juggle between local currencies.

- [Tutorial on multiple currency accounting](https://www.mathstat.dal.ca/~selinger/accounting/tutorial.html) - An excellent resource for implementing multi-currency accounting systems.

## Finance

Once you've got your accounts in order, you can start extracting insights and metrics from your financial data.

- [Accounts Demystified: The Astonishingly Simple Guide To Accounting](https://www.amazon.com/dp/0273744704?&linkCode=ll1&tag=kevideld-20&linkId=f491ee18c48fdaf3226904a39612cc22&language=en_US&ref_=as_li_ss_tl) - Helps you learn how to analyse and monitor your company's financial performance.

- [The Games People Play With Cash Flow](https://commoncog.com/blog/cash-flow-games/) - “Malone created a new accounting metric, something he called ‘earnings before interest, depreciation, and taxes’, or EBITDA.” This is how a cable company CEO made sense of cash flow, like real-estate business did. The article starts with this example and describes other cash flow games for SaaS models.

- [Financial Intelligence for Entrepreneurs: What You Really Need to Know About the Numbers](https://www.amazon.com/dp/1422119157?&linkCode=ll1&tag=kevideld-20&linkId=8d87e9235a1a05c4e0bec4b25230f28d&language=en_US&ref_=as_li_ss_tl) - Allows you to fully understand how to use financial data to make better decisions for your business.

- [What is FinOps](https://www.finops.org/introduction/what-is-finops/) - A framework for tech finance and business leadership teams to share the same language and processes of cloud operations and management.

- [Algebraic Models for Accounting Systems](https://www.amazon.com/dp/9814287113?&linkCode=ll1&tag=kevideld-20&linkId=3d8973d09f9143db8db8639615d12413&language=en_US&ref_=as_li_ss_tl) - Advanced abstract algebra applied to the analysis of accounting systems.

## Contracts

All the invoicing terms & conditions are materialzed by the contract signed between the end-user and the service provider. That's the source from where we derives all the rules of the billing cycle.

- [Is this what Enterprise mean?](https://twitter.com/steffoz/status/1389946268764475394) - When contracts, invoicing and payments are not working together, you end up alienating your big enterprise customers. See the associated HN comments [on bulk license purchase](https://news.ycombinator.com/item?id=27053246).

- [Entitlements untangled: The modern way to software monetization](https://www.stigg.io/blog-posts/entitlements-untangled-the-modern-way-to-software-monetization) - “The concept of Entitlements encapsulates the feature access settings under various product variants (aka Pricing Plans or Packages), bridging the gap between how a product is sold and how it behaves for a variant. In essence, entitlements are a set of permissions defining what a customer (paying or non-paying) can do with your software application.”

- [CUDs vs. Commit Contracts vs. SUDs in Google Cloud](https://66degrees.com/blog/cloud-optimization/cuds-suds-commits-in-google-cloud/) - Explains the differences between various types of discounts and usage commitments in GCP.

- [Quantity discounts on a virtual good: The results of a massive pricing experiment](https://sci-hub.st/https://www.pnas.org/doi/pdf/10.1073/pnas.1510501113) - “Implementing price reductions ranging from 9–70% for large purchases, we found remarkably little impact on revenue, either positively or negatively.” If discounts are a placebo and are still widely used in the industry, maybe they are a marketing hack to lure big customers?

- “It used to be I could just give a lump sum and let Google Ads play until there is no more budget. Not anymore.” - ([source](https://news.ycombinator.com/item?id=36325785)) - Google Ads used to implement a concept of capped actuals. A kind of monthly budget with rollover, which is an optimal billing scheme to limit surprises for customers. It always looked to me as a way to sell quotas.

## Coupons and Vouchers

- [Raising Prices is Hard](https://www.backblaze.com/blog/raising-prices-is-hard/) - Backblaze post-mortem on raising prices on their main offer. They wanted to create an extension program based on credit system. This became a full-time job for a handful of their most senior engineers, and resulted in a six month project.

- [Details on Expiring DigitalOcean Credits](https://blog.digitalocean.com/details-on-expiring-digitalocean-credits/) - The reason you have to add an time limit on credits: unused ones accounts as liabilities on our balance sheet.

- [Hacking Scooters: How I Created \$100k Worth Of Free Rides](https://webcache.googleusercontent.com/search?q=cache:7hrzYYk5-IwJ:https://fant.io/p/hacking-voi/) - A cautionary tale on how promo codes can be exploited to get unlimited free rides.

- [China's Pinduoduo reports theft of online discount vouchers to police](https://www.reuters.com/article/us-pinduoduo-china/chinas-pinduoduo-reports-theft-of-online-discount-vouchers-to-police-idUSKCN1PE05J) - The next level of fraud: “an online collective exploited a loophole on its platform to ‘steal’ tens of millions of yuan worth of discount vouchers”.

- [Council Directive 2016/1065 as regards the treatment of vouchers](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32016L1065) - European directive on the application of VAT when vouchers are involved.

- [The coupon code is a slap in the face](https://justinjackson.ca/the-coupon-code-is-a-slap-in-the-face) - Point the negative consequences of users encountering a blank coupon field without having a coupon. See the update at the end of the article with research backing up this anecdote.

## Taxes

- [2017 Tax Software Developer's Guides](https://www.mass.gov/lists/2017-tax-software-developers-guides) - A list of test cases for developers to test their tax code against.

- [{Digital,Cloud,Electronic,Online} Services VAT Rate Database](https://github.com/kdeldycke/vat-rates) - Centralize applicable VAT rates on foreign online services, for each country of residence (including territorial exceptions).

- [Global VAT & GST on digital services](https://www.avalara.com/vatlive/en/global-vat-gst-on-e-services.html) - List of countries requiring application of taxes on foreign provided online services.

- “British supermarkets (…) charge you a fee for their backend card processing, but they subtract that fee from your checkout price.” ([source](https://news.ycombinator.com/item?id=22047028)) - Which allows them to [claim the VAT on processing fees as input tax](https://www.gov.uk/guidance/vat-guide-notice-700#section4).

- [Streamlined Sales Tax Governing Board](https://www.streamlinedsalestax.org/about-us/about-sstgb) - A multi-states US initiative to automate and standadize sales tax accounting and collection.

### European VAT

- [How to correctly setup SaaS subscriptions to charge VAT in Europe](https://medium.com/slight-pause/how-to-setup-saas-subscriptions-correctly-to-charge-vat-in-europe-d75d857b5d01) - “If you think you can just setup a simple Stripe integration and move on, like us, you'd be sadly mistaken.”

<!--lint disable double-link-->

- [Council Directive 2006/112/EC](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L:2006:347:FULL) - European Union reference on the common system of VAT.

<!--lint enable double-link-->

- [What does the "Reverse Charge" refer to?](https://news.ycombinator.com/item?id=8767388) - Answer: a provision in which a business transfer the responsibility of VAT handling to the customer.

## Invoice

The invoice materialize a consumed service or purchased product, waiting to be settled by a payment transaction.

- [On GCP invoiced billing](https://news.ycombinator.com/item?id=17517479) - [Invoiced billing](https://cloud.google.com/billing/docs/how-to/invoiced-billing) is a B2B-friendly payment happening after the service is consumed and an invoice issued. It seems to be a pain to setup on GCP but I suspect is a consequence of trying to reduce (costly) fraud.

### Structure

<!--lint disable double-link-->

- [Content of EU invoices](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L:2006:347:FULL#d1e6510-1-1) - The information required on a EU invoice is detailed by Article 226, Section 4 (Content of invoices) of Council Directive 2006/112/EC on the common system of VAT.

<!--lint enable double-link-->

### Integrity

Once issued, an invoice must be immutable.

- [Digital signatures: how Sleek leverages Cloud HSM to guarantee the integrity of legal documents](https://medium.com/google-developers/digital-signatures-how-sleek-leverages-cloud-hsm-to-guarantee-the-integrity-of-legal-documents-a7bd3b82faf6) - Here is a great way to rely on GCP's HSM to digitally sign documents and provide an immutable audit-trail. Might be applied to invoices as well as contract agreements.

- [OpenTimestamps](https://opentimestamps.org) - Go beyond the solution above, and timestamp immutable document directly on Bitcoin's blockchain.

- [Credit note](https://en.wikipedia.org/wiki/Credit_note) - Because an invoice is immutable, the only way to fully or partially cancel it is to produce a credit note.

### Generators

- [Manta](https://github.com/hql287/Manta) - Flexible invoicing desktop app with beautiful & customizable templates.

- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - A self-hosted open-source application for managing your invoices, clients and payments.

- [Volcano](https://github.com/volcano/volcano) - Flexible, gateway-agnostic billing system.

- [InvoiceGenerator](https://github.com/by-cx/InvoiceGenerator) - Library to generate a simple invoices.

- [Ruby Invoicing Framework](https://github.com/code-mancers/invoicing) - For generating and displaying invoices (ideal for commercial Rails apps). It allows for flexible business logic; provides tools for tax handling, commission calculation etc.

- [Refact](http://en.userstudio.fr/projects/refact/) - A design project trying to revamp a phone bill with infographics.

### Extrators

- [InvoiceNet](https://github.com/naiveHobo/InvoiceNet) - Deep neural network to extract intelligent information from invoice documents.

### Electronic invoices

- [Factur-X](https://github.com/akretion/factur-x) - Python library to support the e-invoicing standard for France and Germany.

- [Universal Business Language](https://en.wikipedia.org/wiki/Universal_Business_Language) - Most invoicing software can read and write UBL documents (XML) for data transfer.

- [EU eInvoicing](https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/eInvoicing) - European standard on electronic invoice.

- [GOBL](https://gobl.org) - JSON Schema, Open Source Go library, global tax database, with conversion tools, all in one.

## Payments

- [The Best Payment Gateway for Startups](http://aynuriev.com/best-payment-gateway-startups/) - A benchmark of top payment providers, their pricing and models.

- [Avoiding Double Payments in a Distributed Payments System](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb) - RDBMS were build for banks around transactions to solve that specific issue. Then NoSQL came forcing us to carefully implement systems to avoid double spending.

- [Monzo's bank transfers post-mortem](https://monzo.com/blog/2019/06/20/why-bank-transfers-failed-on-30th-may-2019/) - Or why you should be prepared for and work around gateway provider's outages.

- [How to Build an Insurance Company](https://www.moderntreasury.com/journal/how-to-build-an-insurance-company) - The importance of payment ops architecture.

- [EU's Late Payment Directive](https://single-market-economy.ec.europa.eu/smes/sme-strategy/late-payment-directive_en) - European rules on applicable fees for late payments.

- [High failure rate of Point Of Sale devices in the upper Midwest](https://news.ycombinator.com/item?id=20043944) - The root cause? People wearing a lot of wool in low humidity air, generating a lot of static.

- How ACH works: A developer perspective, [part 1](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-1/), [part 2](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-2/), [part 3](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-3/), [part 4](https://engineering.gusto.com/how-ach-works-a-developer-perspective-part-4/).

- [Handling system failures during payment communication](https://blogs.dropbox.com/tech/2017/09/handling-system-failures-during-payment-communication/) - Dropbox's experience trying to account for an unreliable payment provider.

- [Why was I charged?](https://wpchrg.wordpress.com) - Under a constant stream of user complaints about payments, WordPress created a dedicated subdomains to help customers understand unexpected transactions. The trick is to add the URL of that kind of site directly in the bank statement.

- [moov](https://github.com/moov-io) - Open-source infrastructure for financial technology.

- [Fintech Open Source Foundation](https://github.com/finos) - Another set of open-source projects for financial projects.

### Receipt

A receipt materialize the payment transaction.

- [The humble receipt gets a brilliant redesign](https://susielu.com/data-viz/reviziting-the-receipt) - When a Netflix data engineer revisit receipts.

- [The long, long history of long, long CVS receipts](https://www.vox.com/the-goods/2018/10/10/17956950/why-are-cvs-pharmacy-receipts-so-long) - “CVS is a drugstore much like other drugstores, with one important difference: The receipts are very long.”

### Credit Cards

The most popular payment device.

- ['Is that even legal?': Companies may be sharing new credit or debit card information without you knowing](https://www.cbc.ca/news/business/banking-information-shared-with-third-parties-1.5102931) - Some credit and debit card companies have "updating service" that allows new account numbers and expiry dates to be shared with merchants. Visa's implementation is called [VAU](https://developer.visa.com/capabilities/vau) and Mastercard's is [ABU](https://developer.mastercard.com/product/automatic-billing-updater).

- [Strong Customer Authentication](https://stripe.com/guides/strong-customer-authentication) - [Payment Services Directive](https://en.wikipedia.org/wiki/Payment_Services_Directive) 2, explained.

- [Address Verification System](https://en.wikipedia.org/wiki/Address_Verification_System) - A system checking the matching of customer's billing addresses with the one associated with the credit card.

- [pci-blackbox](https://github.com/pjfoley/pci-blackbox) - PCI-DSS compliant card system built on PostgreSQL and PL/pgSQL.

### Bank Accounts

The old-fashioned way of payment: by the way of banks.

- [A (shallow) dive into the American banking system](https://blog.yossarian.net/2019/12/25/A-shallow-dive-into-the-American-banking-system) - Collection of miscellaneous notes primarily focused on the common cases of routable accounts, i.e. checking and savings.

- [Open IBAN](https://openiban.com) - Free and public IBAN validation and calculation webservice.

- [Swift Codes](https://bank.codes/swift-code/) - Swift / BIC codes for personal use only.

- [Swift Codes Repository](https://github.com/PeterNotenboom/SwiftCodes) - A repository that seems to scrape the website above.

### Online Payments

The usual money transfer services.

- [UPI 101: The Basics](https://the-other-side.blog/upi-the-basics/) - “In this article, we will learn about India's Unified Payments Interface. A four-year-old payment scheme that has been accounting for 40-45% of digital payments across India.”

- [20 years of payment processing problems](https://kaimi.io/en/2022/07/20-years-of-payment-processing-problems-en/) - A huge collection of everythings that went wrong, and still is, with payment APIs from the past 2 decades. Any issue exposed in this article that gets unaddressed will end up as stolen money.

- [The untold story of Stripe](https://www.wired.co.uk/article/stripe-payments-apple-amazon-facebook) - In which we learn that “once turnover hit a certain level, Paypal automatically put the business on a 21 to 60 day rolling reserve, meaning that up to 30 per cent of a company's revenue could be locked up for up to two months.”

- [Idempotency in the context of payments](https://developers.google.com/standard-payments/reference/idempotency) - “Idempotency prevents race conditions. Idempotency dictates that multiple identical requests from the same client do not result in a different final state.”

- [Optimizing payments with machine learning](https://dropbox.tech/machine-learning/optimizing-payments-with-machine-learning) - Describes a classic payment workflow, then how machine learning can replace hard-coded business rules and fine-tune the payment failures/retries loop to increase the success rates of charges.

## Fraud

There's monetary incentives to exploit your business. Be prepared to fight hordes of fraudsters and shady users.

- [Detecting fraudulent activity in a cloud using privacy-friendly data aggregates](https://arxiv.org/pdf/1411.6721v1.pdf) - Discusses a method to detect fraudulent activity (launching DDoS attacks, Bitcoin mining, …) by using non-intrusive, privacy-friendly data: billing data.

<!--lint disable double-link-->

- [Awesome List of IAM: Fraud links](https://github.com/kdeldycke/awesome-iam#fraud) - Section dedicated to fraud management related to user accounts, from our sister repository.

<!--lint enable double-link-->

- [Driving Global Fraud Losses Down While Empowering Business Growth](https://youtu.be/yJKWpTBVTiI?t=60) - In this talk by Uber Eats, we learn from the biggest payment processor that “growing businesses with declining loss rates is extremely rare in the industry”. Also, fraud can takes several forms: chargebacks on non-perishable goods, promo abuse, refunds…

- [KYC and AML: beyond the acronyms](https://www.bitsaboutmoney.com/archive/kyc-and-aml-beyond-the-acronyms/) - KYC is nuanced and fuzzy, because it is a stochastic process to reduce risk.

- [Awesome Fraud Detection Research Papers](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers) - Papers sourced from several conferences on all sort of fraud: credit card, payment transactions, loans, customs inspections, money laundering networks, and more.

### Cards

The majority of fraud is exploiting the most common popular payment device: credit cards.

- [Reproducible Machine Learning for Credit Card Fraud detection](https://fraud-detection-handbook.github.io/fraud-detection-handbook/) - A practical handbook on how to identify patterns in transactions.

- [How I Stopped a Credit Card Thief From Ripping Off 3,537 People – and Saved Our Nonprofit in the Process](https://www.freecodecamp.org/news/stopping-credit-card-fraud-and-saving-our-nonprofit/) - Describe a fraud technique known as "card testing", in which massive batch of stolen cards are checked for their validity against your API.

- [How Candy Japan got credit card fraud somewhat under control](https://www.candyjapan.com/behind-the-scenes/how-i-got-credit-card-fraud-somewhat-under-control) - Suggestions involved either [warning signals](https://www.candyjapan.com/behind-the-scenes/fraudulent-transaction-warning-signs) for trying to guess which orders might be fraud, or countermeasures to try to make things harder for the fraudsters.

- [Five Fun Fraud Facts](https://blog.sift.com/2013/five-ecommerce-fraud-facts/) - Another tiny collection of features we can feed to a ML system to detect fraud. Comments on HN also unearthed [more qualifying signals](https://news.ycombinator.com/item?id=6376350) and [derived geodata on the transaction](https://news.ycombinator.com/item?id=6376221).

- [Credit Card Fraud Detection using Autoencoders in Keras](https://medium.com/@curiousily/credit-card-fraud-detection-using-autoencoders-in-keras-tensorflow-for-hackers-part-vii-20e0c85301bd) - Tutorial on how to rely on anomaly detection to implement suspicious card transactions.

- [Training an ML model to score chargebacks](https://twitter.com/patio11/status/1315452323330621440) - An example of a platform's network effect, which allows to predict the likelyhood of winning a dispute.

- [How credit card thieves use free-to-play apps to launder gains](https://kromtech.com/blog/security-center/digital-laundry) - To prevent abuses, service provider must strengthen both credit card verification and the account creation process.

### Trust Score

Synthetic score based on a collection of signals are often the best proxy of user's trustworthiness. Customer support most of the time rely on them to take action when these actions are not triggered automatically.

- [The Secret Trust Scores Companies Use to Judge Us All](https://www.wsj.com/articles/the-secret-trust-scores-companies-use-to-judge-us-all-11554523206) - Nearly everything we buy, how we buy, and where we're buying from is secretly fed into AI-powered verification services that help companies guard against credit-card and other forms of fraud.

- [GCP improved account management policies to better support customers](https://cloudplatform.googleblog.com/2018/07/improving-our-account-management-policies-to-better-support-customers.html) - Or why relying too much on fraud automation might lead to disgruntled users.

- [Digital Ocean's Update on Customer Shutdown Incident](https://blog.digitalocean.com/an-update-on-last-weeks-customer-shutdown-incident/) - Aggressively shutting down user servers is good from a business point of view to prevent fraudster abusing free resources, until it's not.

- [Awesome Credit Modeling](https://github.com/mourarthur/awesome-credit-modeling#readme) - How to use statistical methods to classify applicants into categories to reduce risks. Lots of inspiration and reasearch papers there to improve general scoring.

### Statistics

Best tools to automate fraud detection.

- [Benford's law](https://en.wikipedia.org/wiki/Benford's_law) - Digit distribution can be a signal of accounting fraud.

- [Integer percentages as electoral falsification fingerprints](https://arxiv.org/pdf/1410.6059.pdf) - In the same spirit as above, this paper show that frequency of reported round numbers in election is a signal of man-made anomalies. Might be applicable in some fraud-fighting area.

- [Huber loss](https://en.wikipedia.org/wiki/Huber_loss) - “A loss function used in robust regression, that is less sensitive to outliers in data than the squared error loss.”

- [Peak Detection in the Python World](https://blog.ytotech.com/2015/11/01/findpeaks-in-python/) - Simple way to detect outliers.

### Billing

- [More than 600 million users installed Android 'fleeceware' apps from the Play Store](https://www.zdnet.com/article/more-than-600-million-users-installed-android-fleeceware-apps-from-the-play-store/) - A new kind of fraud, in which apps silently keep charging users after the end of the trial period.

- [CEO Fraud](https://www.knowbe4.com/ceo-fraud) - A billing team responsible for collecting payment is prey to this kind of fraud, in which the CEO is impersonated to commend exceptional payment transactions.

- [The Challenges of Operating a Computing Cloud and Charging for its Use](https://web.stanford.edu/class/cs349d/docs/theimer.pdf) - Skip the first 90% of this presentation by an AWS VP (which is about general system reliability). The last four slides are a good summary of what billing cloud services entails, especially the use of soft quotas to limit fraud.

- [Fraud in Telephony Networks](http://www.s3.eurecom.fr/docs/eurosp17_sahin.pdf) - Most of telephony frauds gravitates around billing and the metering of micro-transactions. This paper feature a taxonomy (on page 6) differentiating the root causes, vulnerabilities, exploitation techniques, and the way fraudsters can benefits from them.

## UX/UI

Users gets easily angry when it comes to money. UX and UI might helps a lot to reduce frustration.

- [Apple In-app purchase Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/in-app-purchase#Autorenewable-subscriptions) - Guide and recommendation on how to make [auto-renewable subscriptions](https://developer.apple.com/app-store/subscriptions/) user-friendly.

- [Which has a higher conversion rate: A single long ecommerce checkout form or a multi-step one?](https://capitalandgrowth.org/questions/2055/which-has-a-higher-conversion-rate-a-single-long-e.html) - Focus first on other things in the cart, like easing anxiety and second-guessing by adding reassurance (trust marks, testimonials) near the credit card and completion steps, as well as some guarantee language that you may have used earlier in the product exploration process.

## Business Intelligence

As stakeholder of the billing pipeline, you sat on all the critical data to measure and report on the health of the business.

### Metrics

Definition and collection of Key Performance Indicators (KPIs) worth monitoring.

- [Startup financial models - 12 templates compared for SaaS](https://www.stephnass.com/blog/startup-financial-model) - A great source of inspiration to get better visibility in your operations.

- [16 Startup Metrics](https://a16z.com/2015/08/21/16-metrics/) - The 2 critical metrics being Customer Acquisition Cost (CAC) and Customer Lifetime Value (CLV).

- [Thinking about growth and profit](https://jlongster.com/thinking-growth-profit) - Discuss the relationship between investments, profit and growth, and how it influence decisions on pricing, free trials and plan structure.

- [A Quantitative Approach to Product Market Fit](https://tribecap.co/a-quantitative-approach-to-product-market-fit/) - Metrics produced above have a greater reach, as they're used as important signals to validate product-market fit.

- [Startup growth calculator](http://growth.tlb.org) - Simple yet effective interactive profitability calculator for startups.

- [An Overview of Visa](http://minesafetydisclosures.com/blog/2019/7/23/part-ll-an-overview-of-visa) - Great breakdown of Visa business models and metrics.

- [The SaaS Financial Model You'll Actually Use](https://web.archive.org/web/20230205234207/https://baremetrics.com/blog/saas-financial-model) - A complete tour of the financials of a statup, which gives you extra-context on how the metrics you produce fit into the larger picture.

### Customer Lifetime Value

How much net value do you produce per customer? The Customer Lifetime Value (CLV, or LTV for Life-Time Value) quantify that. Understanding and acting on it is the most important part of your business's sales efforts.

- [You're all calculating churn rates wrong](https://medium.com/swlh/youre-all-calculating-churn-rates-wrong-cbab072cd992) - “On the surface, churn rate may seem like a natural proxy for changes in customer lifetimes. Let's dig into why that is not true.” Churn rate is not a meaningful metric to compute CLV: during the customer lifetime, the churn probability is not constant. Most of the time because of your free trial and vouchers. This article illustrate the influence of the distribution used to model the probability of a customer quitting.

- [How to project customer retention](https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf) - A seminal paper, with a stronger approach compared to the one above: [the exponential distributions is replaced by a geometric model](https://news.ycombinator.com/item?id=24833319), which is better suited to discrete time intervals like monthly contracts, the former being more appropriate to continuous time process.

- [Survival Analysis For Customer Retention](https://two-wrongs.com/survival-analysis-for-customer-retention.html) - Illustrates how retention can be better modelled using a survival function like [Kaplan–Meier survival curves](https://two-wrongs.com/bootstrapping-kaplan-meier-confidence-intervals.html).

- [RFM (customer value)](https://en.wikipedia.org/wiki/RFM_%28customer_value%29) - A refined model of CLV, used to segment users based on Recency, Frequency and Monetary value.

- [Churn Prediction](https://towardsdatascience.com/churn-prediction-3a4a36c2129a) - “How to use Python in a simplistic way to fuel your company's growth by applying the predictive approach to all your actions.” Relies on XGBoost binary classification.

- [Lifetimes](https://github.com/CamDavidsonPilon/lifetimes) - A full-featured Python package to analyze your users based on their "alive" and "dead" states.

- [`retentionizer`](https://github.com/chrisclark/retentionizer) - Python package to show the projected retention rates for each cohort and calculate the LTV of a given customer in that cohort.

### Data Engineering

To industrialize data production and consumption, your need data engineers to clean up, persist and consolidate data. Only after you get these data foundation you might think of onboarding data scientists.

- [AI vs Data Science vs Data Engineering](https://blog.insightdatascience.com/how-emerging-ai-roles-fit-in-the-data-landscape-d4cd922c389b) - “Data Engineers build data pipelines and infrastructure to ensure a constant availability of transformed data. Data Scientists analyze and build models from these data to develop new product features or drive the bottom line of the business.” As for AI professionals, their focus is on cognitive automation.

- [Ten Ways Your Data Project is Going to Fail](https://www.martingoodson.com/ten-ways-your-data-project-is-going-to-fail/) - You don't need data scientists. “For ETL, hire data engineers. For reporting, hire BI analysts. The end.”

- [Cargo cult data science](http://blog.richardweiss.org/2017/07/25/data-science-in-organizations.html) - “Data science is best viewed as a form of company culture, rather than a set of technologies. However, many firms will try to create that company culture by acquiring data-science technology, rather than working on their culture.”

- [Why not use Double or Float to represent currency?](https://stackoverflow.com/questions/3730019/why-not-use-double-or-float-to-represent-currency/3730040#3730040) - Because of precision: floats and doubles cannot accurately represent the base 10 multiples that we use for money.

- [Never Use Floats for Money](https://husobee.github.io/money/float/2016/09/23/never-use-floats-for-currency.html) - “This is precisely the problem we have when trying to represent 10^-1, or 0.1 in binary. There is not an exact binary representation of 0.1 or 0.01.”

- [European Spreadsheet Risks Interest Group - Horror Stories](https://eusprig.org/research-info/horror-stories/) - A collection of cases in which uncontrolled and untested spreadsheet models led to lost revenue, mispricing, poor decision making, fraud and systemic financial failure.

### Tools

Software to build visualizations, dashboards, SQL queries and drill down into data.

- [Practical Business Python](https://pbpython.com) - A blog collecting and spreading ideas on how to use Python more effectively in the business setting.

- [`redash`](https://github.com/getredash/redash) - Connect and query your data sources, build dashboards to visualize data and share them with your company.

- [Metabase](https://github.com/metabase/metabase) - Metabase is an open source solution to explore and visualize data and supports lots of databases.

- [Apache Superset](https://github.com/apache/incubator-superset) - Enterprise-ready business intelligence web application.

- [Meltano](https://gitlab.com/meltano/meltano) - Open source convention-over-configuration product for the whole data lifecycle, all the way from loading data to analyzing it.

- [`insights`](https://github.com/mariusandra/insights) - Insights is a tool to visually explore a PostgreSQL database, with an emphasis on generating graphs that show business performance over time.

- [`falcon`](https://github.com/plotly/falcon) - Free, open-source SQL client for Windows and Mac with builtin graphs.

## Competitive Analysis

A bunch of resources to keep track of the current status and progress of all companies operating in the domain.

- [Patents on billing systems of the dot-com era](https://news.ycombinator.com/item?id=34773821) - All of them have been abandonned and constitute prior art. This means there is nothing to prevent anybody to implement or commercialize these concepts.

- “You need a slightly more sophisticated developer team to cobble together a billing platform” ([source](https://www.techemails.com/i/124009734/google-pms-on-stripe)) - Google's Product Director take on building billing systems: you need a certain kind of engineers to tackle that domain. It is not for everyone.

### Cloud providers

- [AWS Cost Management announcements](https://aws.amazon.com/about-aws/whats-new/aws-cost-management/) - The source of all new features added to the billing perimeter.

- [AWS reserved instances vs saving plan](https://www.prosperops.com/wp-content/uploads/2022/01/ris_and_savings_plans.png) - A feature matrix of the different scheme and their average dicounts.

- [GCP billing release notes](https://cloud.google.com/billing/docs/release-notes) - Latest changes of GCP billing features.

- [GCP billing news](https://www.gcpweekly.com/gcp-resources/tag/billing/) - From the unofficial Google Cloud Platform newsletter.

- [More choice, less complexity: New Compute Engine pricing options on tap](https://cloud.google.com/blog/products/compute/more-choice-less-complexity-new-compute-engine-pricing-options-on-tap) - A wrap-up of recent GCP pricing features.

- [Orbitera](https://en.wikipedia.org/wiki/Orbitera) - GCP's billing subsidiary.

- [DigitalOcean Billing changelog](http://docs.digitalocean.com/release-notes/billing/) - All the latest billing updates on DO.

## History

- “Larry Page went to U of M and used the Michigan Terminal System. (…) when Google was working on App Engine, Page took inspiration from MTS and would exhort engineers to follow its example. (…) when I look at my AWS and GCP bills now, it feels very familiar!” ([source](https://news.ycombinator.com/item?id=35123587)) - The direct filiation between old-school university mainframes and current cloud services.

- [Engineering and Operations in the Bell System](http://bitsavers.trailing-edge.com/communications/westernElectric/books/Engineering_and_Operations_in_the_Bell_System_2ed_1984.pdf) - Starting at page #445, the "10.5 Billing Equipment and Systems" section describe the history and technical evolutions of Bell's phone calls metering and pricing.

- [The vanished grandeur of accounting](https://www.bostonglobe.com/ideas/2014/06/07/the-vanished-grandeur-accounting/3zcbRBoPDNIryWyNYNMvbO/story.html) - Accounting paintings were a significant genre in Dutch art.

## Humour

Billing is not funny.

- [Detax](https://detax.framer.website) - A site mockup of an tax avoidance product for small businesses.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/kdeldycke/awesome-billing/blob/master/.github/contributing.md) first.

## Footnotes

The [header image](https://github.com/kdeldycke/awesome-billing/blob/main/assets/awesome-billing-header.jpg) is based on a modified [photo](https://unsplash.com/photos/u2zSzMTwIjQ) by [Denny Müller](https://unsplash.com/@redaquamedia).

<!--lint disable no-undefined-references-->

<a name="intro-quote-def">\[1\]</a>: [*Sapiens: A Brief History of Humankind*](https://www.amazon.com/dp/0062316095?_encoding=UTF8&psc=1&linkCode=ll1&tag=kevideld-20&linkId=71ccb002da0dbe49c502954960175b66&language=en_US&ref_=as_li_ss_tl) (Harper, 2015). [\[↑\]](#intro-quote-ref)
