<div class="github-widget" data-repo="cpuu/awesome-fuzzing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Fuzzing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> [Fuzzing](https://en.wikipedia.org/wiki/Fuzzing) 或模糊测试是一种自动化软件测试技术，涉及提供无效、意外或随机数据作为计算机程序的输入. 然后监视程序是否存在异常，例如崩溃、内置代码断言失败或潜在的内存泄漏. 通常，模糊器用于测试采用结构化输入的程序. 

用于安全测试的令人敬畏的 Fuzzing 参考的精选列表. 此外，还有一系列免费提供的学术论文、工具等.

您最喜欢的工具或您自己的论文未列出？  Fork 并创建一个 Pull Request 来添加它！





## Books
- [Fuzzing-101](https://github.com/antonio-morales/Fuzzing101)
- [The Fuzzing Book](https://www.fuzzingbook.org/) (2019)
- [The Art, Science, and Engineering of Fuzzing: A Survey](https://ieeexplore.ieee.org/document/8863940) (2019) - 
实际上，这份文件是一篇论文，但它包含的内容比任何其他书籍都重要.
- [Fuzzing for Software Security Testing and Quality Assurance, 2nd Edition](https://www.amazon.com/Fuzzing-Software-Security-Testing-Assurance/dp/1608078507/) (2018)
- [Fuzzing: Brute Force Vulnerability Discovery, 1st Edition](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119/) (2007)
- [Open Source Fuzzing Tools, 1st Edition](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950/) (2007)


## Talks
- [Fuzzing Labs - Patrick Ventuzelo](https://www.youtube.com/channel/UCGD1Qt2jgnFRjrfAITGdNfQ)， YouTube
- [Effective File Format Fuzzing](https://youtu.be/qTTwqFRD1H8), 黑帽欧洲 2016
- [Adventures in Fuzzing](https://www.youtube.com/watch?v=SngK4W4tVc0), 纽约大学讲座 2018
- [Fuzzing with AFL](https://www.youtube.com/watch?v=DFQT1YxvpDo), 2018 年国家数据中心会议

## Papers
为了达到明确定义的范围，我选择在 4
2008 年 1 月至 2019 年 7 月举行的顶级主要安全会议和其他会议.
它包括 (i) 网络和分布式系统安全研讨会 (NDSS)，(ii) IEEE Symposium on
安全和隐私 (S&amp;P)，(iii) USENIX 安全研讨会 (USEC)，和 (iv) ACM 计算机和通信安全会议 (CCS).


### The Network and Distributed System Security Symposium (NDSS)
- [WINNIE : Fuzzing Windows Applications with Harness Synthesis and Fast Cloning, 2021](https://taesoo.kim/pubs/2021/jung:winnie.pdf)
- [Reinforcement Learning-based Hierarchical Seed Scheduling for Greybox Fuzzing, 2021](https://www.cs.ucr.edu/~heng/pubs/afl-hier.pdf)
- [PGFUZZ: Policy-Guided Fuzzing for Robotic Vehicles, 2021](https://beerkay.github.io/papers/Berkay2021PGFuzzNDSS.pdf)
- [Favocado: Fuzzing Binding Code of JavaScript Engines Using Semantically Correct Test Cases, 2021](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6A-2_24224_paper.pdf/)
- [HFL: Hybrid Fuzzing on the Linux Kernel, 2020](https://www.unexploitable.systems/publication/kimhfl/)
- [HotFuzz: Discovering Algorithmic Denial-of-Service Vulnerabilities Through Guided Micro-Fuzzing, 2020](https://www.researchgate.net/publication/339164746_HotFuzz_Discovering_Algorithmic_Denial-of-Service_Vulnerabilities_Through_Guided_Micro-Fuzzing)
- [HYPER-CUBE: High-Dimensional Hypervisor Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/07/Hyper-Cube-NDSS20.pdf)
- [Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization, 2020](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24422.pdf)
- [CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines, 2019](https://daramg.gift/paper/han-ndss2019.pdf)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary, 2019](https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf)
- [REDQUEEN: Fuzzing with Input-to-State Correspondence, 2019](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf)
- [Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing, 2019](https://www.cs.ucr.edu/~heng/pubs/digfuzz_ndss19.pdf)
- [Life after Speech Recognition: Fuzzing Semantic Misinterpretation for Voice Assistant Applications, 2019](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_08-4_Zhang_paper.pdf)
- [INSTRIM: Lightweight Instrumentation for Coverage-guided Fuzzing, 2018](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_14_Hsu_paper.pdf)
- [IoTFuzzer: Discovering Memory Corruptions in IoT Through App-based Fuzzing, 2018](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_01A-1_Chen_paper.pdf)
- [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices, 2018](http://s3.eurecom.fr/docs/ndss18_muench.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing, 2018](https://lifeasageek.github.io/papers/han:meds.pdf)
- [Vuzzer: Application-aware evolutionary fuzzing, 2017](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/vuzzer-application-aware-evolutionary-fuzzing/)
- [DELTA: A Security Assessment Framework for Software-Defined Networks, 2017](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss201702A-1LeePaper.pdf)
- [Driller: Augmenting Fuzzing Through Selective Symbolic Execution, 2016](https://cancer.shtech.org/wiki/uploads/2016---NDSS---driller-augmenting-fuzzing-through-selective-symbolic-execution.pdf)
- [Automated Whitebox Fuzz Testing, 2008](https://www.ndss-symposium.org/wp-content/uploads/2017/09/Automated-Whitebox-Fuzz-Testing-paper-Patrice-Godefroid.pdf)


### IEEE Symposium on Security and Privacy (IEEE S&P)
- [STOCHFUZZ: Sound and Cost-effective Fuzzing of Stripped Binaries by Incremental and Stochastic Rewriting, 2021](https://www.cs.purdue.edu/homes/zhan3299/res/SP21b.pdf)
- [One Engine to Fuzz 'em All: Generic Language Processor Testing with Semantic Validation, 2021](https://huhong789.github.io/papers/polyglot-oakland2021.pdf)
- [NTFUZZ: Enabling Type-Aware Kernel Fuzzing on Windows with Static Binary Analysis, 2021](https://softsec.kaist.ac.kr/~jschoi/data/oakland2021.pdf)
- [DIFUZZRTL: Differential Fuzz Testing to Find CPU Bugs, 2021](https://lifeasageek.github.io/papers/jaewon-difuzzrtl.pdf)
- [DIANE: Identifying Fuzzing Triggers in Apps to Generate Under-constrained Inputs for IoT Devices, 2021](https://conand.me/publications/redini-diane-2021.pdf)
- [Fuzzing JavaScript Engines with Aspect-preserving Mutation, 2020](https://jakkdu.github.io/pubs/2020/park:die.pdf)
- [IJON: Exploring Deep State Spaces via Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/27/IJON-Oakland20.pdf)
- [Krace: Data Race Fuzzing for Kernel File Systems, 2020](https://www.cc.gatech.edu/~mxu80/pubs/xu:krace.pdf)
- [Pangolin:Incremental Hybrid Fuzzing with Polyhedral Path Abstraction, 2020](https://qingkaishi.github.io/public_pdfs/SP2020.pdf)
- [RetroWrite: Statically Instrumenting COTS Binaries for Fuzzing and Sanitization, 2020](https://www.semanticscholar.org/paper/RetroWrite%3A-Statically-Instrumenting-COTS-Binaries-Dinesh-Burow/845cafb153b0e4b9943c6d9b6a7e42c14845a0d6)
- [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000b122/19skgbGVFEQ)
- [Fuzzing File Systems via Two-Dimensional Input Space Exploration, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a594/19skfLYOpaw)
- [NEUZZ: Efficient Fuzzing with Neural Program Smoothing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a900/19skg5XghG0)
- [Razzer: Finding Kernel Race Bugs through Fuzzing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a296/19skfwZLirm)
- [Angora: Efficient Fuzzing by Principled Search, 2018](http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [CollAFL: Path Sensitive Fuzzing, 2018](http://chao.100871.net/papers/oakland18.pdf)
- [T-Fuzz: fuzzing by program transformation, 2018](https://nebelwelt.net/publications/files/18Oakland.pdf)
- [Skyfire: Data-Driven Seed Generation for Fuzzing, 2017](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)
- [Program-Adaptive Mutational Fuzzing, 2015](https://softsec.kaist.ac.kr/~sangkilc/papers/cha-oakland15.pdf)
- [TaintScope: A checksum-aware directed fuzzing tool for automatic software vulnerability detection, 2010](https://ieeexplore.ieee.org/abstract/document/5504701)



### USENIX Security
- [Breaking Through Binaries: Compiler-quality Instrumentation for Better Binary-only Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/nagy)
- [ICSFuzz: Manipulating I/Os and Repurposing Binary Code to Enable Instrumented Fuzzing in ICS Control Applications, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/tychalas)
- [Android SmartTVs Vulnerability Discovery via Log-Guided Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/aafer)
- [Constraint-guided Directed Greybox Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/lee-gwangmu)
- [Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/schumilo)
- [UNIFUZZ: A Holistic and Pragmatic Metrics-Driven Platform for Evaluating Fuzzers, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/li-yuwei)
- [FANS: Fuzzing Android Native System Services via Automated Interface Analysis, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/liu)
- [Analysis of DTLS Implementations Using Protocol State Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/fiterau-brostean)
- [EcoFuzz: Adaptive Energy-Saving Greybox Fuzzing as a Variant of the Adversarial Multi-Armed Bandit, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/yue)
- [Fuzzing Error Handling Code using Context-Sensitive Software Fault Injection, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/jiang)
- [FuzzGen: Automatic Fuzzer Generation, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/ispoglou)
- [ParmeSan: Sanitizer-guided Greybox Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/osterlund)
- [SpecFuzz: Bringing Spectre-type vulnerabilities to the surface, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/oleksenko)
- [FuzzGuard: Filtering out Unreachable Inputs in Directed Grey-box Fuzzing through Deep Learning, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/zong)
- [Montage: A Neural Network Language Model-Guided JavaScript Engine Fuzzer, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/lee-suyoung)
- [GREYONE: Data Flow Sensitive Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/gan)
- [Fuzzification: Anti-Fuzzing Techniques, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/jung)
- [AntiFuzz: Impeding Fuzzing Audits of Binary Executables, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/guler)
- [Charm: Facilitating Dynamic Analysis of Device Drivers of Mobile Systems, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/talebi)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/pailoor)
- [QSYM : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/yun)
- [OSS-Fuzz - Google's continuous fuzzing service for open source software, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/schumilo)
- [Protocol State Fuzzing of TLS Implementations, 2015](https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/de-ruiter)
- [Optimizing Seed Selection for Fuzzing, 2014](https://softsec.kaist.ac.kr/~sangkilc/papers/rebert-usenixsec14.pdf)
- [Dowsing for overflows: a guided fuzzer to find buffer boundary violations, 2013](http://enigma.usenix.org/sites/default/files/sec13_proceedings_interior.pdf#page=57)
- [Fuzzing with Code Fragments, 2012](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final73.pdf)


### ACM Conference on Computer and Communications Security (ACM CCS)
- [SoFi: Reflection-Augmented Fuzzing for JavaScript Engines, 2021](https://dl.acm.org/doi/pdf/10.1145/3460120.3484823)
- [T-Reqs: HTTP Request Smuggling with Differential Fuzzing, 2021](https://bahruz.me/papers/ccs2021treqs.pdf)
- [V-SHUTTLE: Scalable and Semantics-Aware Hypervisor Fuzzing, 2021](https://nesa.zju.edu.cn/download/ppt/pgn_slides_V-SHUTTLE.pdf)
- [Same Coverage, Less Bloat: Accelerating Binary-only Fuzzing with Coverage-preserving Coverage-guided Tracing, 2021](https://people.cs.vt.edu/snagy2/papers/21CCS.pdf)
- [HyperFuzzer: An Efficient Hybrid Fuzzer For Virtual CPUs, 2021](https://www.microsoft.com/en-us/research/uploads/prod/2021/09/hyperfuzzer-ccs21.pdf)
- [Regression Greybox Fuzzing, 2021](https://mboehme.github.io/paper/CCS21.pdf)
- [Hardware Support to Improve Fuzzing Performance and Precision, 2021](https://gts3.org/assets/papers/2021/ding:snap.pdf)
- [SNIPUZZ: Black-box Fuzzing of IoT Firmware via Message Snippet Inference, 2021](https://arxiv.org/pdf/2105.05445.pdf)
- [FREEDOM: Engineering a State-of-the-Art DOM Fuzzer, 2020](https://gts3.org/assets/papers/2020/xu:freedom.pdf)
- [Intriguer: Field-Level Constraint Solving for Hybrid Fuzzing, 2019](https://dl.acm.org/citation.cfm?id=3354249)
- [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts, 2019](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf)
- [Matryoshka: fuzzing deeply nested branches, 2019](https://web.cs.ucdavis.edu/~hchen/paper/chen2019matryoshka.pdf)
- [Evaluating Fuzz Testing, 2018](http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer, 2018](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)
- [IMF: Inferred Model-based Fuzzer, 2017](http://daramg.gift/paper/han-ccs2017.pdf)
- [SemFuzz: Semantics-based Automatic Generation of Proof-of-Concept Exploits, 2017](https://www.informatics.indiana.edu/xw7/papers/p2139-you.pdf)
- [AFL-based Fuzzing for Java with Kelinci, 2017](https://dl.acm.org/citation.cfm?id=3138820)
- [Designing New Operating Primitives to Improve Fuzzing Performance, 2017](http://iisp.gatech.edu/sites/default/files/images/designing_new_operating_primitives_to_improve_fuzzing_performance_vt.pdf)
- [Directed Greybox Fuzzing, 2017](https://dl.acm.org/citation.cfm?id=3134020)
- [SlowFuzz: Automated Domain-Independent Detection of Algorithmic Complexity Vulnerabilities, 2017](https://arxiv.org/pdf/1708.08437.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf)
- [Systematic Fuzzing and Testing of TLS Libraries, 2016](https://www.nds.rub.de/media/nds/veroeffentlichungen/2016/10/19/tls-attacker-ccs16.pdf)
- [Coverage-based Greybox Fuzzing as Markov Chain, 2016](https://ieeexplore.ieee.org/abstract/document/8233151)
- [eFuzz: A Fuzzer for DLMS/COSEM Electricity Meters, 2016](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.817.5616&rep=rep1&type=pdf)
- [Scheduling Black-box Mutational Fuzzing, 2013](https://softsec.kaist.ac.kr/~sangkilc/papers/woo-ccs13.pdf)
- [Taming compiler fuzzers, 2013](https://www.cs.utah.edu/~regehr/papers/pldi13.pdf)
- [SAGE: whitebox fuzzing for security testing, 2012](https://dl.acm.org/citation.cfm?id=2094081)
- [Grammar-based whitebox fuzzing, 2008](https://dl.acm.org/citation.cfm?id=1375607)
- [Taint-based directed whitebox fuzzing, 2009](https://dl.acm.org/citation.cfm?id=1555061)


### ArXiv (Fuzzing with Artificial Intelligence & Machine Learning)
- [MEUZZ: Smart Seed Scheduling for Hybrid Fuzzing, 2020](https://arxiv.org/abs/2002.08568)
- [A Review of Machine Learning Applications in Fuzzing, 2019](https://arxiv.org/abs/1906.11133)
- [Evolutionary Fuzzing of Android OS Vendor System Services, 2019](https://arxiv.org/abs/1906.00621)
- [MoonLight: Effective Fuzzing with Near-Optimal Corpus Distillation, 2019](https://arxiv.org/abs/1905.13055)
- [Coverage-Guided Fuzzing for Deep Neural Networks, 2018](https://arxiv.org/abs/1809.01266)
- [DLFuzz: Differential Fuzzing Testing of Deep Learning Systems, 2018](https://arxiv.org/abs/1808.09413)
- [TensorFuzz: Debugging Neural Networks with Coverage-Guided Fuzzing, 2018](https://arxiv.org/abs/1807.10875)
- [NEUZZ: Efficient Fuzzing with Neural Program Learning, 2018](https://arxiv.org/abs/1807.05620)
- [EnFuzz: From Ensemble Learning to Ensemble Fuzzing, 2018](https://arxiv.org/abs/1807.00182)
- [REST-ler: Automatic Intelligent REST API Fuzzing, 2018](https://arxiv.org/abs/1806.09739)
- [Deep Reinforcement Fuzzing, 2018](https://arxiv.org/abs/1801.04589)
- [Not all bytes are equal: Neural byte sieve for fuzzing, 2017](https://arxiv.org/abs/1711.04596)
- [Faster Fuzzing: Reinitialization with Deep Neural Models, 2017](https://arxiv.org/abs/1711.02807)
- [Learn&Fuzz: Machine Learning for Input Fuzzing, 2017](https://arxiv.org/abs/1701.07232)
- [Complementing Model Learning with Mutation-Based Fuzzing, 2016](https://arxiv.org/abs/1611.02429)

### The others
- [Ifuzzer: An evolutionary interpreter fuzzer using genetic programming, 2016](https://www.cs.vu.nl/~herbertb/download/papers/ifuzzer-esorics16.pdf)
- [Hybrid fuzz testing: Discovering software bugs via fuzzing and symbolic execution, 2012](https://pdfs.semanticscholar.org/488a/b1e313f5109153f2c74e3b5d86d41e9b4b71.pdf)
- [Call-Flow Aware API Fuzz Testing for Security of Windows Systems, 2008](https://www.computer.org/csdl/proceedings/iccsa/2008/3243/00/3243a019-abs.html)
- [Feedback-directed random test generation, 2007](https://dl.acm.org/citation.cfm?id=1248841)



## Tools
有关可用于利用模糊测试的各种开源工具的信息.
### General-purpose
- [radamsa](https://gitlab.com/akihe/radamsa) - 一个通用的模糊器.
- [zzuf](https://github.com/samhocevar/zzuf) - 一个透明的应用程序输入模糊器.
### Binary
- [American Fuzzy Lop plus plus (AFL++)](https://github.com/AFLplusplus/AFLplusplus)  - 优于 Google 的 AFL 的分支. 更快的速度，更多更好的突变，更多更好的仪器，自定义模块支持等. [paper](https://www.usenix.org/conference/woot20/presentation/fioraldi)
- [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - 一种面向安全的模糊器，它采用一种新型的编译时工具和遗传算法来自动发现干净、有趣的测试用例，这些测试用例会触发目标二进制文件中的新内部状态. 
- [WinAFL](https://github.com/googleprojectzero/winafl) - 用于模糊 Windows 二进制文件的 AFL 分支.
- [libFuzzer](http://llvm.org/docs/LibFuzzer.html) - 用于覆盖引导的模糊测试的库. [Tutorial from Google.](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)
- [Driller](https://github.com/shellphish/driller) - 的实施 [driller paper](https://www.cs.ucsb.edu/~vigna/publications/2016_NDSS_Driller.pdf) . 这个实现建立在 AFL 之上，angr 被用作符号跟踪器.
- [shellphish fuzzer](https://github.com/shellphish/fuzzer) - AFL 的 Python 接口，允许轻松注入测试用例和其他功能.
- [Eclipser](https://github.com/SoftSec-KAIST/Eclipser) - 基于二进制的模糊测试工具，通过利用一种称为灰盒 concolic 测试的新技术，改进了经典的基于覆盖的模糊测试.
- [Jazzer](https://github.com/CodeIntelligenceTesting/jazzer)  - 用于 Java 虚拟机的覆盖引导的进程内模糊器. 它基于 libFuzzer，可以直接应用于已编译的应用程序.
### Web, JavaScript
- [jsfunfuzz](https://github.com/MozillaSecurity/funfuzz) - JavaScript 引擎模糊器.
- [IFuzzer](https://github.com/vspandan/IFuzzer) - 使用遗传编程的进化解释器模糊器.
- [domato](https://github.com/googleprojectzero/domato) - DOM fuzzer 来自 [Google Project Zero](https://github.com/googleprojectzero). [Blog Post.](https://googleprojectzero.blogspot.com/2017/09/the-great-dom-fuzz-off-of-2017.html)
- [fuzzilli](https://github.com/googleprojectzero/fuzzilli) - 一个（覆盖）引导的 Javascript 引擎模糊器，由 Samuel Groß 编写.
- [CodeAlchemist](https://github.com/SoftSec-KAIST/CodeAlchemist) - JavaScript 引擎模糊器，由 KAIST SoftSec 实验室编写.
- [test-each](https://github.com/ehmicky/test-each) - 使用不同的输入重复测试.
- [gremlins.js](https://github.com/marmelab/gremlins.js) - gremlins.js 是一个用 JavaScript 编写的猴子测试库.
### Network protocol
- [dtls-fuzzer](https://github.com/assist-project/dtls-fuzzer) - 执行 DTLS 服务器的协议状态模糊测试的 Java 工具.
- [T-Fuzz](https://github.com/HexHive/T-Fuzz) - T-Fuzz 利用覆盖引导的模糊器生成输入.
- [TLS-Attacker](https://github.com/RUB-NDS/TLS-Attacker) - 用于分析 TLS 库的基于 Java 的框架.
- [DELTA](https://github.com/seungsoo-lee/DELTA) - SDN 安全评估框架.
- [boofuzz](https://github.com/jtpereyda/boofuzz)  - 人类网络协议模糊测试. 文档可在 http://boofuzz.readthedocs.io/ 获得，包括漂亮的快速入门指南.
- [LL-Fuzzer](https://github.com/mit-ll/LL-Fuzzer) - 适用于 Android 设备的自动 NFC 模糊测试框架.
- [tlsfuzzer](https://github.com/tomato42/tlsfuzzer) - SSL 和 TLS 协议测试套件和模糊器.
- [TumbleRF](https://github.com/riverloopsec/tumblerf) - 一个将模糊测试技术应用于射频系统的框架. 
- [PULSAR](https://github.com/hgascon/pulsar) - 一种专有网络协议的状态黑盒模糊测试方法.
- [SPIKE](https://github.com/guilhermeferreira/spikepp/tree/master/SPIKE) - 类似 sulley 的 fuzzer 开发框架，是 sulley 的前身.
- [PROTOS](https://www.ee.oulu.fi/roles/ouspg/Protos) - 协议实现的安全测试.
### Driver
- [Charm](https://github.com/trusslab/charm) - 一种有助于对移动系统的设备驱动程序进行动态分析的系统解决方案.
## Platform
- [certfuzz](https://github.com/CERTCC/certfuzz) - 它包含 CMU CERT 基本模糊测试框架 (BFF) 和 CERT 故障观察引擎 (FOE) 的源代码.
- [Peach Fuzzer Platform](https://www.peach.tech/products/peach-fuzzer/) - 一个自动化的安全测试平台，通过查找硬件和软件系统中的漏洞来防止零日攻击.
- [Blackhat USA 2018 AFL workshop training materials](https://github.com/wrauner/afl-fuzzing-training) - 来自三星研究院的@wrauner.
- [CI Fuzz](https://code-intelligence.com) - 一个与 CI/CD 无关的平台，用于对本机应用程序和 Java Web 应用程序进行基于反馈的模糊测试.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/cpuu/awesome-fuzzing/blob/master/contributing.md) 第一的.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，cpuu 已放弃所有版权和
本作品的相关或邻接权.
