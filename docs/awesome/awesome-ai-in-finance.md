<div class="github-widget" data-repo="georgezouq/awesome-ai-in-finance"></div>
<div align="center">
	<img width="500" height="350" src="https://raw.githubusercontent.com/georgezouq/awesome-ai-in-finance/master/media/logo.svg?sanitize=true" alt="Awesome">
	<br>
  <p>
    <a href="https://github.com/georgezouq/awesome-deep-reinforcement-learning-in-finance">量化金融中的 DL/RL/SL 策略研究和工具</a>
  </p>
</div>

## Awesome AI in Finance

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

机器学习算法和有用的工具在金融市场中的使用. 

我们收集所有市场，包括“股票/期货/货币”等传统市场和加密货币市场.

&gt; 我们有 50.75% 的时间是正确的，但我们在 50.75% 的时间里是 100% 正确的，你可以通过这种方式赚取数十亿美元.
&gt; --- Renaissance Technologies 联合首席执行官罗伯特·默瑟 (Robert Mercer)




## Papers

- [THE THEORY OF SPECULATION L. BACHELIER 1900](http://www.radio.goldseek.com/bachelier-thesis-theory-of-speculation-en.pdf) - 决定证券交易所走势的影响因素是.
- [Brownian Motion in the Stock Market Osborne,1959](http://m.e-m-h.org/Osbo59.pdf) - 过去、现在甚至预期的事件，通常没有明显的表现.
- [An Investigation into the Use of Reinforcement Learning Techniques within the Algorithmic Trading Domain(2015)](http://www.doc.ic.ac.uk/teaching/distinguished-projects/2015/j.cumming.pdf)
- [Ten Financial Applications of Machine Learning (Presentation Slides)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3197726)
- [A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem](https://arxiv.org/pdf/1706.10059.pdf)
- [Reinforcement Learning for Trading 1994](http://papers.nips.cc/paper/1551-reinforcement-learning-for-trading.pdf)
- [Dragon-Kings, Black Swans and the Prediction of Crises Didier Sornette](https://arxiv.org/pdf/0907.4290.pdf) - 我们开发了与有意义的异常值相对应的“龙王”概念，这些异常值被发现在各种系统的广泛条件下与事件大小分布中的幂律共存. 
- [Financial Trading as a Game: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1807.02787.pdf)  - 从金融市场产生持续利润的自动程序对每个市场从业者都是有利可图的. 深度强化学习的最新进展为此类交易代理的端到端培训提供了一个框架.
- [MACHINE LEARNING FOR TRADING](https://cims.nyu.edu/~ritter/ritter2017machine.pdf) - With an appropriate choice of the reward function, reinforcement learning techniques (specifically, Q-learning) can successfully handle the risk-averse case.
- [Ten Financial Applications of Machine Learning (Seminar Slides) (2018)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3197726)

## Courses & Book

- [NYU: Overview of Advanced Methods of Reinforcement Learning in Finance](https://www.coursera.org/learn/advanced-methods-reinforcement-learning-finance/home/welcome)
- [Udacity: Artificial Intelligence for Trading](https://www.udacity.com/course/ai-for-trading--nd880)
- [AI in Finance](https://cfte.education/) - 在线学习金融科技.
- [Advanced-Deep-Trading](https://github.com/Rachnog/Advanced-Deep-Trading) - 大部分实验基于“金融机器学习进展”一书.
- [Advances in Financial Machine Learning](https://www.amazon.com/Advances-Financial-Machine-Learning-Marcos-ebook/dp/B079KLDW21/ref=sr_1_1?s=books&ie=UTF8&qid=1541717436&sr=1-1)  - 读者将学习如何以适合 ML 算法的方式构建大数据； 如何使用 ML 算法对该数据进行研究； 如何使用超级计算方法.

## Strategies & Research

### Time Series Data

使用技术分析指数的价格和数量过程

- [stockpredictionai](https://github.com/borisbanushev/stockpredictionai)  - 在此笔记本中，我将创建一个完整的流程来预测股价走势. 跟着走，我们会取得一些不错的成绩. 为此，我们将使用带有 LSTM（一种递归神经网络）的生成对抗网络 (GAN) 作为生成器，并使用卷积神经网络 CNN 作为鉴别器.
- [Personae](https://github.com/Ceruleanacg/Personae) - Personae 是用于量化交易的深度强化学习和监督学习的工具和环境的回购.
- [AutomatedStockTrading-DeepQ-Learning](https://github.com/sachink2010/AutomatedStockTrading-DeepQ-Learning)  - 每天，全球数以百万计的交易者都在尝试通过交易股票来赚钱. 如今，实物交易者也正在被自动交易机器人所取代. 算法交易市场经历了显着的增长，大量公司正在使用它. 我试图建立一个深度 Q 学习强化代理模型.
- [tf_deep_rl_trader](https://github.com/miroblog/tf_deep_rl_trader) - 交易环境（OpenAI Gym）+ PPO（TensorForce）.
- [trading-gym](https://github.com/6-Billionaires/trading-gym) - 这个交易健身房是第一个用短期交易本身来训练代理人的交易.
- [trading-rl](https://github.com/Kostis-S-Z/trading-rl) - 使用价格追踪的金融交易深度强化学习.
- [deep_rl_trader](https://github.com/miroblog/deep_rl_trader) - 交易环境（OpenAI Gym）+ DDQN（Keras-RL）.
- [RL-Stock](https://github.com/wangshub/RL-Stock) - 如何用深度强化学习自动炒股.
- [Quantitative-Trading](https://github.com/Ceruleanacg/Quantitative-Trading) - 量化交易的论文和代码工具.
- [gym-trading](https://github.com/hackthemarket/gym-trading) - 强化学习算法交易模型的环境.
- [zenbrain](https://github.com/carlos8f/zenbrain) - 机器学习机器人的框架.
- [DeepLearningNotes](https://github.com/AlphaSmartDog/DeepLearningNotes) - 量化分析中的机器学习.
- [stock_market_reinforcement_learning](https://github.com/kh-kim/stock_market_reinforcement_learning) - 股票交易市场 OpenAI 健身房环境，使用 Keras 进行深度强化学习.

### Portfolio Management

- [Deep-Reinforcement-Stock-Trading](https://github.com/Albert-Z-Guo/Deep-Reinforcement-Stock-Trading)  - 用于投资组合管理的轻量级深度强化学习框架. 该项目探索了在高度模块化和可扩展的框架中将深度强化学习算法应用于股票交易的可能性.
- [qtrader](https://github.com/filangel/qtrader) - 投资组合管理的强化学习.
- [PGPortfolio](https://github.com/ZhengyaoJiang/PGPortfolio) - PGPortfolio - Policy Gradient Portfolio，《A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem》的源代码.
- [DeepDow](https://github.com/jankrepl/deepdow) - 通过深度学习优化投资组合.

### High Frequency Trading

- [SGX-Full-OrderBook-Tick-Data-Trading-Strategy](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy) - 使用数据科学方法（机器学习）对完整订单分时数据提供高频交易 (HFT) 策略的解决方案.
- [HFT_Bitcoin](https://github.com/ghgr/HFT_Bitcoin) - 比特币交易所高频交易分析.

### Event Drive

- [stockpredictionai](https://github.com/borisbanushev/stockpredictionai)  - 在此笔记本中，我将创建一个完整的流程来预测股价走势. 跟着走，我们会取得一些不错的成绩. 为此，我们将使用带有 LSTM（一种递归神经网络）的生成对抗网络 (GAN) 作为生成器，并使用卷积神经网络 CNN 作为鉴别器.
- [trump2cash](https://github.com/maxbbraun/trump2cash) - 由特朗普推文提供支持的股票交易机器人.

### Crypto Currencies Strategies

- [LSTM-Crypto-Price-Prediction](https://github.com/SC4RECOIN/LSTM-Crypto-Price-Prediction) - 使用 lstm-RNN 预测加密市场的价格趋势以使用交易机器人.
- [tforce_btc_trader](https://github.com/lefnire/tforce_btc_trader) - TensorForce 比特币交易机器人.
- [Tensorflow-NeuroEvolution-Trading-Bot](https://github.com/SC4RECOIN/Tensorflow-NeuroEvolution-Trading-Bot) - 使用 tensorflow 构建大量模型，这些模型可以交易 cyrpto 并迭代繁殖和变异.
- [gekkoga](https://github.com/gekkowarez/gekkoga) - 使用 Gekko 解决交易策略优化的遗传算法.
- [Gekko_ANN_Strategies](https://github.com/markchen8717/Gekko_ANN_Strategies) - Gekko 交易机器人的 ANN 交易策略.
- [gekko-neuralnet](https://github.com/zschro/gekko-neuralnet) - Gekko 的神经网络策略.
- [bitcoin_prediction](https://github.com/llSourcell/bitcoin_prediction) - 这是 YouTube 上 Siraj Raval 的“比特币预测”代码.

### Technical Analysis

- [quant-trading](https://github.com/je-suis-tm/quant-trading) - Python量化交易策略.
- [Gekko-Bot-Resources](https://github.com/cloggy45/Gekko-Bot-Resources) - Gekko 机器人资源.
- [gekko_tools](https://github.com/tommiehansen/gekko_tools) - Gekko 策略、工具等.
- [gekko RSI_WR](https://github.com/zzmike76/gekko) - Gekko RSI_WR 策略.
- [gekko HL](https://github.com/mounirlabaied/gekko-strat-hl) - 计算下降峰值并继续交易.
- [EthTradingAlgorithm](https://github.com/Philipid3s/EthTradingAlgorithm) - 使用 Python 3.5 和库 ZipLine 的以太坊交易算法.
- [gekko_trading_stuff](https://github.com/thegamecat/gekko-trading-stuff) - 我在这个很棒的加密货币交易平台上使用的文件的垃圾场.
- [forex.analytics](https://github.com/mkmarek/forex.analytics) - Node.js 本机库使用遗传算法对 OHLC 数据集执行技术分析v.
- [Bitcoin_MACD_Strategy](https://github.com/VermeirJellen/Bitcoin_MACD_Strategy) - 比特币 - MACD 交叉交易策略回测.
- [crypto-signal](https://github.com/CryptoSignal/crypto-signal)  - 用于 Bittrex、Binance、GDAX 等的自动加密货币交易和技术分析 (TA) 机器人！  （250 多个硬币）.
- [Gekko-Strategies](https://github.com/xFFFFF/Gekko-Strategies) - 带有回测结果和一些有用工具的 Gekko 交易机器人策略.
- [gekko-gannswing](https://github.com/johndoe75/gekko-gannswing) - Gekko 交易机器人的江恩摆动交易策略.

### Lottery & Gamble

- [LotteryPredict](https://github.com/chengstone/LotteryPredict) - 使用 LSTM 预测彩票.

### Arbitrage

- [ArbitrageBot](https://github.com/BatuhanUsluel/ArbitrageBot) - 目前在 bittrex 和 poloniex 上运行的套利机器人.
- [r2](https://github.com/bitrinjani/r2) - R2 Bitcoin Arbitrager 是一个基于 Node.js + TypeScript 的自动套利交易系统.
- [cryptocurrency-arbitrage](https://github.com/manu354/cryptocurrency-arbitrage)  - 加密货币套利机会计算器. 超过 800 种货币和 50 个市场.
- [bitcoin-arbitrage](https://github.com/maxme/bitcoin-arbitrage) - 比特币套利 - 机会探测器.
- [blackbird](https://github.com/butor/blackbird) - 黑鸟比特币套利：多头/空头市场中性策略.

## Data Sources

#### Traditional Markets

- [Quandl](https://www.quandl.com/tools/api) - 通过一个免费的 API 从数百个发布者那里获取数百万个金融和经济数据集.
- [yahoo-finance](https://github.com/lukaszbanasiak/yahoo-finance)  - 从 Yahoo! 获取股票数据的 Python 模块金融.
- [Tushare](https://github.com/waditu/tushare) - TuShare 是一个抓取中国股票历史数据的工具.

#### Crypto Currencies

- [CryptoInscriber](https://github.com/Optixal/CryptoInscriber)  - 实时加密货币历史贸易数据记录簿. 从任何加密货币交易所下载实时历史交易数据，无论是用于机器学习、回测/可视化交易策略还是用于 Quantopian/Zipline.
- [Gekko-Datasets](https://github.com/xFFFFF/Gekko-Datasets) - Gekko Trading Bot dataset dumps. Ready to use and download history files in SQLite format.

## Research Tools

- [JAQS](https://github.com/quantOS-org/JAQS) - 一个开源量化策略研究平台.
- [pyfolio](https://github.com/quantopian/pyfolio) - Python 中的投资组合和风险分析.
- [alphalens](https://github.com/quantopian/alphalens) - 预测（alpha）股票因素的绩效分析.
- [empyrical](https://github.com/quantopian/empyrical)  - 共同的财务风险和绩效指标. 由 zipline 和 pyfolio 使用.
- [zvt](https://github.com/zvtvz/zvt) - 零向量交易者.

## Trading System

用于回溯测试和实时交易

### Traditional Market

**System**

- [zipline](https://github.com/quantopian/zipline) - Zipline，一个 Pythonic 算法交易库.
- [TradingView](http://tradingview.com/) - 获取实时信息和市场见解.
- [rqalpha](https://github.com/ricequant/rqalpha) - 支持多种证券的可扩展、可替换的 Python 算法回测和交易框架.
- [backtrader](https://github.com/backtrader/backtrader) - 用于交易策略的 Python 回测库.
- [kungfu](https://github.com/taurusai/kungfu) - 功夫大师交易系统.

**合并与重建**

- [pylivetrader](https://github.com/alpacahq/pylivetrader) - 带有 zipline 接口的 Python 实时交易执行库.
- [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting) - 作为硬币交易策略的回测框架.

### Crypto Currencies

- [zenbot](https://github.com/DeviaVir/zenbot) - Zenbot 是一个使用 Node.js 和 MongoDB 的命令行加密货币交易机器人.
- [bot18](https://github.com/carlos8f/bot18) - Bot18 是由 Zenbot 开发的高频加密货币交易机器人.
- [magic8bot](https://github.com/magic8bot/magic8bot) - Magic8bot 是一个使用 Node.js 和 MongoDB 的加密货币交易机器人.
- [catalyst](https://github.com/enigmampc/catalyst) - Python 中加密资产的算法交易库.
- [QuantResearchDev](https://github.com/mounirlabaied/QuantResearchDev) - Quant Research dev &amp; Traders 开源项目.
- [MACD](https://github.com/sudoscripter/MACD) - Zenbot Macd 自动交易.
- [abu](https://github.com/bbfamily/abu) - 基于python的量化交易系统.

#### Plugins

- [easytrader](https://github.com/shidenggui/easytrader)
- [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting) - 该项目测试 bt 和 Quantopian Zipline 作为硬币交易策略的回测框架.
- [Gekko-BacktestTool](https://github.com/xFFFFF/Gekko-BacktestTool)  - Gekko Trading Bot 的批量回测、导入和策略参数优化. 使用一个命令，您将运行任意数量的回测.

## TA Lib

- [pandas_talib](https://github.com/femtotrader/pandas_talib) - 技术分析指标的 Python Pandas 实现.
- [finta](https://github.com/peerchemist/finta) - 在 Python-Pandas 中实现的常见金融技术指标（70 多个指标）.
- [tulipnode](https://github.com/TulipCharts/tulipnode)  - 郁金香节点是郁金香指标的官方 Node.js 包装器. 它提供超过 100 种技术分析叠加和指标功能.
- [techan.js](https://github.com/andredumas/techan.js) - 基于 D3 构建的可视化技术分析和图表（烛台、OHLC、指标）库.

## Exchange API

在现实世界中做！

- [IbPy](https://github.com/blampe/IbPy) - Interactive Brokers 在线交易系统的 Python API.
- [HuobiFeeder](https://github.com/mmmaaaggg/HuobiFeeder) - 连接HUOBIPRO交易所，获取ABAT交易平台回测/分析和实时交易的市场/历史数据.
- [ctpwrapper](https://github.com/nooperpudd/ctpwrapper) - 上海期货交易所CTP api.

### Framework

- [tf-quant-finance](https://github.com/google/tf-quant-finance) - 用于量化金融的高性能 TensorFlow 库.

### Visualizing

- [playground](https://github.com/tensorflow/playground) - 玩神经网络.
- [netron](https://github.com/lutzroeder/netron) - 用于深度学习和机器学习模型的可视化工具.

### GYM Environment

- [TradingGym](https://github.com/Yvictor/TradingGym) - 用于训练强化学习代理或简单规则库算法的交易和回测环境.
- [TradzQAI](https://github.com/kkuette/TradzQAI) - 强化学习代理、回测和培训的交易环境.
- [btgym](https://github.com/Kismuz/btgym) - 可扩展、事件驱动、深度学习友好的回测库.

## Articles

- [The-Economist](https://github.com/nailperry-zd/The-Economist) - The Economist 经济学人，持续更新.
- [nyu-mlif-notes](https://github.com/wizardforcel/nyu-mlif-notes) - 金融笔记中的纽约大学机器学习.
- [Using LSTMs to Turn Feelings Into Trades](https://www.quantopian.com/posts/watch-our-webinar-buying-happiness-using-lstms-to-turn-feelings-into-trades-now?utm_source=forum&utm_medium=twitter&utm_campaign=sentiment-analysis)
- [Maury Osborne和三文鱼的故事](https://zhuanlan.zhihu.com/p/20586843)
- [布朗运动、伊藤引理——细说Black-Scholes公式的前世今生（上篇）](https://zhuanlan.zhihu.com/p/32664487) 
- [布朗运动、伊藤引理——细说Black-Scholes公式的前世今生（下篇）](https://zhuanlan.zhihu.com/p/32746192)
- [趋势策略小试牛刀，海龟交易体系的构建](https://www.ricequant.com/community/topic/62/%E8%B6%8B%E5%8A%BF%E7%AD%96%E7%95%A5%E5%B0%8F%E8%AF%95%E7%89%9B%E5%88%80-%E6%B5%B7%E9%BE%9F%E4%BA%A4%E6%98%93%E4%BD%93%E7%B3%BB%E7%9A%84%E6%9E%84%E5%BB%BA)

## Others

- [zipline-tensorboard](https://github.com/jimgoo/zipline-tensorboard) - TensorBoard 作为 Zipline 仪表板 http://jimgoo.com/tensorboard-and-zip.
- [gekko-quasar-ui](https://github.com/H256/gekko-quasar-ui) - 使用 Quasar 框架的 gekko 交易机器人的 UI 端口.

#### Other Resource

- [Awesome-Quant-Machine-Learning-Trading](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading) - 以机器学习为重点的量化/算法交易资源.
- [awesome-quant](https://github.com/wilsonfreitas/awesome-quant) - 用于 Quants（量化金融）的非常棒的库、包和资源的精选列表.
- [awesome-quant-china](https://github.com/thuquant/awesome-quant) - 中国的量化资源.
- [awesome-rl](https://github.com/aikorea/awesome-rl)
