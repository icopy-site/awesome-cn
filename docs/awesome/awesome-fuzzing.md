<div class="github-widget" data-repo="cpuu/awesome-fuzzing"></div>
## Awesome Fuzzing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> [Fuzzing](https://en.wikipedia.org/wiki/Fuzzing) or fuzz testing is an automated software testing technique that involves providing invalid, unexpected, or random data as inputs to a computer program. The program is then monitored for exceptions such as crashes, failing built-in code assertions, or potential memory leaks. Typically, fuzzers are used to test programs that take structured inputs. 

A curated list of references to awesome Fuzzing for security testing. Additionally there is a collection of freely available academic papers, tools and so on.

Your favorite tool or your own paper is not listed? Fork and create a Pull Request to add it!





## Books
- [Fuzzing Against the Machine: Automate vulnerability research with emulated IoT devices on QEMU](https://a.co/d/0bXISQgZ) (2023)
- [Fuzzing-101](https://github.com/antonio-morales/Fuzzing101)
- [The Fuzzing Book](https://www.fuzzingbook.org/) (2019)
- [The Art, Science, and Engineering of Fuzzing: A Survey](https://ieeexplore.ieee.org/document/8863940) (2019) - Actually, this document is a paper, but it contains more important and essential content than any other book.
- [Fuzzing for Software Security Testing and Quality Assurance, 2nd Edition](https://www.amazon.com/Fuzzing-Software-Security-Testing-Assurance/dp/1608078507/) (2018)
- [Fuzzing: Brute Force Vulnerability Discovery, 1st Edition](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119/) (2007)
- [Open Source Fuzzing Tools, 1st Edition](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950/) (2007)


## Talks
- [Fuzzing Labs - Patrick Ventuzelo](https://www.youtube.com/channel/UCGD1Qt2jgnFRjrfAITGdNfQ) - YouTube.
- [Effective File Format Fuzzing](https://youtu.be/qTTwqFRD1H8) - Black Hat Europe 2016.
- [Adventures in Fuzzing](https://www.youtube.com/watch?v=SngK4W4tVc0) - NYU Talk 2018.
- [Fuzzing with AFL](https://www.youtube.com/watch?v=DFQT1YxvpDo) - NDC Conferences 2018.

## Papers
To achieve a well-defined scope, I have chosen to include publications on fuzzing from 4 top major security conferences (2008–2025): (i) Network and Distributed System Security Symposium (NDSS), (ii) IEEE Symposium on Security and Privacy (S&P), (iii) USENIX Security Symposium (USEC), and (iv) ACM Conference on Computer and Communications Security (CCS).

> **Note:** Papers are selected based on whether the title contains the keyword "fuzz." If a paper is related to fuzzing but does not include "fuzz" in its title, it may have been missed. In that case, please open a [Pull Request](https://github.com/cpuu/awesome-fuzzing/pulls) and it will be reviewed for inclusion.


### The Network and Distributed System Security Symposium (NDSS)

<details><summary>2025 (10 papers)</summary>

- [Automatic Library Fuzzing through API Relation Evolvement, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-750-paper.pdf)
- [Blackbox Fuzzing of Distributed Systems with Multi-Dimensional Inputs and Symmetry-Based Feedback Pruning, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-1912-paper.pdf)
- [DUMPLING: Fine-grained Differential JavaScript Engine Fuzzing, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-1411-paper.pdf)
- [FUZZUER: Enabling Fuzzing of UEFI Interfaces on EDK-2, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-400-paper.pdf)
- [ICSQuartz: Scan Cycle-Aware and Vendor-Agnostic Fuzzing for Industrial Control Systems, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-795-paper.pdf)
- [MALintent: Coverage Guided Intent Fuzzing Framework for Android, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-125-paper.pdf)
- [Moneta: Ex-Vivo GPU Driver Fuzzing by Recalling In-Vivo Execution States, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-218-paper.pdf)
- [MSan: Efficiently Detecting Uninitialized Memory Errors During Fuzzing, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-1133-paper.pdf)
- [Truman: Constructing Device Behavior Models from OS Drivers to Fuzz Virtual Devices, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-301-paper.pdf)
- [TWINFUZZ: Differential Testing of Video Hardware Acceleration Stacks, 2025](https://www.ndss-symposium.org/wp-content/uploads/2025-526-paper.pdf)

</details>

<details><summary>2024 (7 papers)</summary>

- [DeepGo: Predictive Directed Greybox Fuzzing, 2024](https://www.ndss-symposium.org/wp-content/uploads/2024-514-paper.pdf)
- [EnclaveFuzz: Finding Vulnerabilities in SGX Applications, 2024](https://www.ndss-symposium.org/wp-content/uploads/2024-819-paper.pdf)
- [Large Language Model guided Protocol Fuzzing, 2024](https://www.ndss-symposium.org/wp-content/uploads/2024-556-paper.pdf)
- [MOCK: Optimizing Kernel Fuzzing Mutation with Context-aware Dependency, 2024](https://www.ndss-symposium.org/wp-content/uploads/2024-131-paper.pdf)
- [Predictive Context-sensitive Fuzzing, 2024](https://www.ndss-symposium.org/wp-content/uploads/ndss2024_f113_paper.pdf)
- [ReqsMiner: Automated Discovery of CDN Forwarding Request Inconsistencies and DoS Attacks with Grammar-based Fuzzing, 2024](https://www.ndss-symposium.org/wp-content/uploads/2024-31-paper.pdf)
- [ShapFuzz: Efficient Fuzzing via Shapley-Guided Byte Selection, 2024](https://www.ndss-symposium.org/wp-content/uploads/2024-134-paper.pdf)

</details>

<details><summary>2023 (4 papers)</summary>

- [DARWIN: Survival of the Fittest Fuzzing Mutators, 2023](https://www.ndss-symposium.org/wp-content/uploads/2023-159-paper.pdf)
- [FUZZILLI: Fuzzing for JavaScript JIT Compiler Vulnerabilities, 2023](https://www.ndss-symposium.org/wp-content/uploads/2023-290-paper.pdf)
- [LOKI: State-Aware Fuzzing Framework for the Implementation of Blockchain Consensus Protocols, 2023](https://www.ndss-symposium.org/wp-content/uploads/2023-78-paper.pdf)
- [No Grammar, No Problem: Towards Fuzzing the Linux Kernel without System-Call Description, 2023](https://www.ndss-symposium.org/wp-content/uploads/2023-688-paper.pdf)

</details>

<details><summary>2022 (4 papers)</summary>

- [Semantic-Informed Driver Fuzzing Without Both the Hardware Devices and the Emulators, 2022](https://www.ndss-symposium.org/wp-content/uploads/2022-345-paper.pdf)
- [MobFuzz: Adaptive Multi-objective Optimization in Gray-box Fuzzing, 2022](https://www.ndss-symposium.org/wp-content/uploads/2022-314-paper.pdf)
- [Context-Sensitive and Directional Concurrency Fuzzing for Data-Race Detection, 2022](https://www.ndss-symposium.org/wp-content/uploads/2022-296-paper.pdf)
- [EMS: History-Driven Mutation for Coverage-based Fuzzing, 2022](https://www.ndss-symposium.org/wp-content/uploads/2022-162-paper.pdf)

</details>

<details><summary>2021 (4 papers)</summary>

- [WINNIE : Fuzzing Windows Applications with Harness Synthesis and Fast Cloning, 2021](https://taesoo.kim/pubs/2021/jung:winnie.pdf)
- [Reinforcement Learning-based Hierarchical Seed Scheduling for Greybox Fuzzing, 2021](https://www.cs.ucr.edu/~heng/pubs/afl-hier.pdf)
- [PGFUZZ: Policy-Guided Fuzzing for Robotic Vehicles, 2021](https://beerkay.github.io/papers/Berkay2021PGFuzzNDSS.pdf)
- [Favocado: Fuzzing Binding Code of JavaScript Engines Using Semantically Correct Test Cases, 2021](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6A-2_24224_paper.pdf)

</details>

<details><summary>2020 (4 papers)</summary>

- [HFL: Hybrid Fuzzing on the Linux Kernel, 2020](https://www.unexploitable.systems/publication/kimhfl/)
- [HotFuzz: Discovering Algorithmic Denial-of-Service Vulnerabilities Through Guided Micro-Fuzzing, 2020](https://www.researchgate.net/publication/339164746_HotFuzz_Discovering_Algorithmic_Denial-of-Service_Vulnerabilities_Through_Guided_Micro-Fuzzing)
- [HYPER-CUBE: High-Dimensional Hypervisor Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/07/Hyper-Cube-NDSS20.pdf)
- [Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization, 2020](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24422.pdf)

</details>

<details><summary>2019 (5 papers)</summary>

- [CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines, 2019](https://daramg.gift/paper/han-ndss2019.pdf)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary, 2019](https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf)
- [REDQUEEN: Fuzzing with Input-to-State Correspondence, 2019](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf)
- [Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing, 2019](https://www.cs.ucr.edu/~heng/pubs/digfuzz_ndss19.pdf)
- [Life after Speech Recognition: Fuzzing Semantic Misinterpretation for Voice Assistant Applications, 2019](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_08-4_Zhang_paper.pdf)

</details>

<details><summary>2018 (4 papers)</summary>

- [INSTRIM: Lightweight Instrumentation for Coverage-guided Fuzzing, 2018](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_14_Hsu_paper.pdf)
- [IoTFuzzer: Discovering Memory Corruptions in IoT Through App-based Fuzzing, 2018](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_01A-1_Chen_paper.pdf)
- [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices, 2018](http://s3.eurecom.fr/docs/ndss18_muench.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing, 2018](https://lifeasageek.github.io/papers/han:meds.pdf)

</details>

<details><summary>2017 (2 papers)</summary>

- [Vuzzer: Application-aware evolutionary fuzzing, 2017](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/vuzzer-application-aware-evolutionary-fuzzing/)
- [DELTA: A Security Assessment Framework for Software-Defined Networks, 2017](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss201702A-1LeePaper.pdf)

</details>

<details><summary>2016 (1 paper)</summary>

- [Driller: Augmenting Fuzzing Through Selective Symbolic Execution, 2016](https://cancer.shtech.org/wiki/uploads/2016---NDSS---driller-augmenting-fuzzing-through-selective-symbolic-execution.pdf)

</details>

<details><summary>2008 (1 paper)</summary>

- [Automated Whitebox Fuzz Testing, 2008](https://www.ndss-symposium.org/wp-content/uploads/2017/09/Automated-Whitebox-Fuzz-Testing-paper-Patrice-Godefroid.pdf)

</details>


### IEEE Symposium on Security and Privacy (IEEE S&P)

<details><summary>2025 (7 papers)</summary>

- [CHIMERA: Fuzzing P4 Network Infrastructure for Multi-Plane Bug Detection and Vulnerability Discovery, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600c865/26hiVb0gXUA)
- [FirmRCA: Towards Post-Fuzzing Analysis on ARM Embedded Firmware with Efficient Event-based Fault Localization, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a002/21B7PVDny6I)
- [Fuzz-Testing Meets LLM-Based Agents: An Automated and Efficient Framework for Jailbreaking Text-To-Image Generation Models, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a336/26hiTETXKow)
- [HouseFuzz: Service-Aware Grey-Box Fuzzing for Vulnerability Detection in Linux-Based Firmware, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600d507/26hiVy3bGHm)
- [Predator: Directed Web Application Fuzzing for Efficient Vulnerability Validation, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a066/21B7Ray6BkA)
- [RGFuzz: Rule-Guided Fuzzer for WebAssembly Runtimes, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a003/21B7PWv1JGU)
- [Stateful Analysis and Fuzzing of Commercial Baseband Firmware, 2025](https://www.computer.org/csdl/proceedings-article/sp/2025/223600b120/26EkFox5zyg)

</details>

<details><summary>2024 (14 papers)</summary>

- [AFGen: Whole-Function Fuzzing for Applications and Libraries, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a011/1RjE9PjiDss)
- [Chronos: Finding Timeout Bugs in Practical Distributed Systems by Deep-Priority Fuzzing with Transient Delay, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a109/1Ub23heRtUA)
- [DY Fuzzing: Formal Dolev-Yao Models Meet Cryptographic Protocol Fuzz Testing, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a096/1Ub234bjuWA)
- [Everything is Good for Something: Counterexample-Guided Directed Fuzzing via Likely Invariant Inference, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a142/1Ub23ZRRhRu)
- [LABRADOR: Response Guided Directed Fuzzing for Black-box IoT Devices, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a127/1Ub23HQTJ1C)
- [LLMIF: Augmented Large Language Model for Fuzzing IoT Devices, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a196/1WPcYnhN15u)
- [Predecessor-aware Directed Greybox Fuzzing, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a040/1RjEaeMELbq)
- [SATURN: Host-Gadget Synergistic USB Driver Fuzzing, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a051/1RjEaqzRsfC)
- [SoK: Prudent Evaluation Practices for Fuzzing, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a137/1Ub23V26Svm)
- [SyzGen++: Dependency Inference for Augmenting Kernel Driver Fuzzing, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000e661/1ZZvBxFudzi)
- [SyzTrust: State-aware Fuzzing on Trusted OS Designed for IoT Devices, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a070/1RjEaG9OpTa)
- [Titan: Efficient Multi-target Directed Greybox Fuzzing, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a059/1RjEaxqvmQ8)
- [To Boldly Go Where No Fuzzer Has Gone Before: Finding Bugs in Linux' Wireless Stacks through VirtIO Devices, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a024/1RjEa0y9RMQ)
- [Towards Smart Contract Fuzzing on GPU, 2024](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a195/1WPcYmDLzKo)

</details>

<details><summary>2023 (10 papers)</summary>

- [TEEzz: Fuzzing Trusted Applications on COTS Android Devices, 2023](https://hexhive.epfl.ch/publications/files/23Oakland.pdf)
- [SEGFUZZ: Segmentizing Thread Interleaving to Discover Kernel Concurrency Bugs through Fuzzing, 2023](https://lifeasageek.github.io/papers/jeong-segfuzz.pdf)
- [RSFuzzer: Discovering Deep SMI Handler Vulnerabilities in UEFI Firmware with Hybrid Fuzzing, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b765/1OXH123kRcQ)
- [Toss a Fault to Your Witcher: Applying Grey-box Coverage-Guided Mutational Fuzzing to Detect SQL and Command Injection Vulnerabilities, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a116/1He7XPiaynS)
- [UTOPIA: Automatic Generation of Fuzz Driver using Unit Tests, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600a746/1OXH6X6Fexi)
- [SelectFuzz: Efficient Directed Fuzzing with Selective Path Exploration, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b050/1OXGOF6jNp6)
- [Finding Specification Blind Spots via Fuzz Testing, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600c708/1OXH7BohI2Y)
- [ODDFUZZ: Discovering Java Deserialization Vulnerabilities via Structure-Aware Directed Greybox Fuzzing, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600c726/1OXH0xA0Lrq)
- [VIDEZZO: Dependency-aware Virtual Device Fuzzing, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600d228/1OXH4y2HyuI)
- [DEVFUZZ: Automatic Device Model-Guided Device Driver Fuzzing, 2023](https://www.computer.org/csdl/proceedings-article/sp/2023/933600d246/1OXH2Xsv2Du)

</details>

<details><summary>2022 (5 papers)</summary>

- [PATA: Fuzzing with Path Aware Taint Analysis, 2022](http://www.wingtecher.com/themes/WingTecherResearch/assets/papers/sp22.pdf)
- [Jigsaw: Efficient and Scalable Path Constraints Fuzzing, 2022](https://www.cs.ucr.edu/~csong/oakland22-jigsaw.pdf)
- [FuzzUSB: Hybrid Stateful Fuzzing of USB Gadget Stacks, 2022](https://github.com/purseclab/fuzzusb/blob/main/paper/fuzzusb.pdf)
- [Effective Seed Scheduling for Fuzzing with Graph Centrality Analysis, 2022](https://arxiv.org/pdf/2203.12064.pdf)
- [BEACON : Directed Grey-Box Fuzzing with Provable Path Pruning, 2022](https://qingkaishi.github.io/public_pdfs/SP22.pdf)

</details>

<details><summary>2021 (5 papers)</summary>

- [STOCHFUZZ: Sound and Cost-effective Fuzzing of Stripped Binaries by Incremental and Stochastic Rewriting, 2021](https://www.cs.purdue.edu/homes/zhan3299/res/SP21b.pdf)
- [One Engine to Fuzz 'em All: Generic Language Processor Testing with Semantic Validation, 2021](https://huhong789.github.io/papers/polyglot-oakland2021.pdf)
- [NTFUZZ: Enabling Type-Aware Kernel Fuzzing on Windows with Static Binary Analysis, 2021](https://softsec.kaist.ac.kr/~jschoi/data/oakland2021.pdf)
- [DIFUZZRTL: Differential Fuzz Testing to Find CPU Bugs, 2021](https://lifeasageek.github.io/papers/jaewon-difuzzrtl.pdf)
- [DIANE: Identifying Fuzzing Triggers in Apps to Generate Under-constrained Inputs for IoT Devices, 2021](https://conand.me/publications/redini-diane-2021.pdf)

</details>

<details><summary>2020 (5 papers)</summary>

- [Fuzzing JavaScript Engines with Aspect-preserving Mutation, 2020](https://jakkdu.github.io/pubs/2020/park:die.pdf)
- [IJON: Exploring Deep State Spaces via Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/27/IJON-Oakland20.pdf)
- [Krace: Data Race Fuzzing for Kernel File Systems, 2020](https://www.cc.gatech.edu/~mxu80/pubs/xu:krace.pdf)
- [Pangolin:Incremental Hybrid Fuzzing with Polyhedral Path Abstraction, 2020](https://qingkaishi.github.io/public_pdfs/SP2020.pdf)
- [RetroWrite: Statically Instrumenting COTS Binaries for Fuzzing and Sanitization, 2020](https://www.semanticscholar.org/paper/RetroWrite%3A-Statically-Instrumenting-COTS-Binaries-Dinesh-Burow/845cafb153b0e4b9943c6d9b6a7e42c14845a0d6)

</details>

<details><summary>2019 (4 papers)</summary>

- [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000b122/19skgbGVFEQ)
- [Fuzzing File Systems via Two-Dimensional Input Space Exploration, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a594/19skfLYOpaw)
- [NEUZZ: Efficient Fuzzing with Neural Program Smoothing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a900/19skg5XghG0)
- [Razzer: Finding Kernel Race Bugs through Fuzzing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a296/19skfwZLirm)

</details>

<details><summary>2018 (3 papers)</summary>

- [Angora: Efficient Fuzzing by Principled Search, 2018](http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [CollAFL: Path Sensitive Fuzzing, 2018](http://chao.100871.net/papers/oakland18.pdf)
- [T-Fuzz: fuzzing by program transformation, 2018](https://nebelwelt.net/publications/files/18Oakland.pdf)

</details>

<details><summary>2017 (1 paper)</summary>

- [Skyfire: Data-Driven Seed Generation for Fuzzing, 2017](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)

</details>

<details><summary>2015 (1 paper)</summary>

- [Program-Adaptive Mutational Fuzzing, 2015](https://softsec.kaist.ac.kr/~sangkilc/papers/cha-oakland15.pdf)

</details>

<details><summary>2010 (1 paper)</summary>

- [TaintScope: A checksum-aware directed fuzzing tool for automatic software vulnerability detection, 2010](https://ieeexplore.ieee.org/abstract/document/5504701)

</details>



### USENIX Security

<details><summary>2025 (14 papers)</summary>

- [AidFuzzer: Adaptive Interrupt-Driven Firmware Fuzzing via Run-Time State Recognition, 2025](https://www.usenix.org/system/files/usenixsecurity25-wang-jianqiang.pdf)
- [ChainFuzz: Exploiting Upstream Vulnerabilities in Open-Source Supply Chains, 2025](https://www.usenix.org/system/files/usenixsecurity25-deng.pdf)
- [CoreCrisis: Threat-Guided and Context-Aware Iterative Learning and Fuzzing of 5G Core Networks, 2025](https://www.usenix.org/system/files/usenixsecurity25-dong-yilu.pdf)
- [Effective Directed Fuzzing with Hierarchical Scheduling for Web Vulnerability Detection, 2025](https://www.usenix.org/system/files/usenixsecurity25-lin-zihan.pdf)
- [Encarsia: Evaluating CPU Fuzzers via Automatic Bug Injection, 2025](https://www.usenix.org/system/files/usenixsecurity25-bolcskei.pdf)
- [From Alarms to Real Bugs: Multi-target Multi-step Directed Greybox Fuzzing for Static Analysis Result Verification, 2025](https://www.usenix.org/system/files/usenixsecurity25-bao-andrew.pdf)
- [Fuzzing the PHP Interpreter via Dataflow Fusion, 2025](https://www.usenix.org/system/files/usenixsecurity25-jiang-yuancheng.pdf)
- [GenHuzz: An Efficient Generative Hardware Fuzzer, 2025](https://www.usenix.org/system/files/usenixsecurity25-wu-lichao.pdf)
- [Lost in Translation: Enabling Confused Deputy Attacks on EDA Software with TransFuzz, 2025](https://www.usenix.org/system/files/usenixsecurity25-solt.pdf)
- [Low-Cost and Comprehensive Non-textual Input Fuzzing with LLM-Synthesized Input Generators, 2025](https://www.usenix.org/system/files/usenixsecurity25-zhang-kunpeng.pdf)
- [MBFuzzer: A Multi-Party Protocol Fuzzer for MQTT Brokers, 2025](https://www.usenix.org/system/files/usenixsecurity25-song-xiangpu.pdf)
- [PAPILLON: Efficient and Stealthy Fuzz Testing-Powered Jailbreaks for LLMs, 2025](https://www.usenix.org/system/files/usenixsecurity25-gong-xueluan.pdf)
- [Robust, Efficient, and Widely Available Greybox Fuzzing for COTS Binaries with System Call Pattern Feedback, 2025](https://www.usenix.org/system/files/usenixsecurity25-xiao-jifan.pdf)
- [Waltzz: WebAssembly Runtime Fuzzing with Stack-Invariant Transformation, 2025](https://www.usenix.org/system/files/usenixsecurity25-zhang-lingming.pdf)

</details>

<details><summary>2024 (12 papers)</summary>

- [Atropos: Effective Fuzzing of Web Applications for Server-Side Vulnerabilities, 2024](https://www.usenix.org/system/files/usenixsecurity24-guler.pdf)
- [Cascade: CPU Fuzzing via Intricate Program Generation, 2024](https://www.usenix.org/system/files/usenixsecurity24-solt.pdf)
- [Critical Code Guided Directed Greybox Fuzzing for Commits, 2024](https://www.usenix.org/system/files/usenixsecurity24-xiang-yi.pdf)
- [EL3XIR: Fuzzing COTS Secure Monitors, 2024](https://www.usenix.org/system/files/usenixsecurity24-lindenmeier.pdf)
- [Fuzzing BusyBox: Leveraging LLM and Crash Reuse for Embedded Bug Unearthing, 2024](https://www.usenix.org/system/files/usenixsecurity24-asmita.pdf)
- [HYPERPILL: Fuzzing for Hypervisor-bugs by Leveraging the Hardware Virtualization Interface, 2024](https://www.usenix.org/system/files/usenixsecurity24-bulekov.pdf)
- [MultiFuzz: A Multi-Stream Fuzzer For Testing Monolithic Firmware, 2024](https://www.usenix.org/system/files/usenixsecurity24-chesser.pdf)
- [ResolverFuzz: Automated Discovery of DNS Resolver Vulnerabilities with Query-Response Fuzzing, 2024](https://www.usenix.org/system/files/usenixsecurity24-zhang-qifan.pdf)
- [SDFuzz: Target States Driven Directed Fuzzing, 2024](https://www.usenix.org/system/files/usenixsecurity24-li-penghui.pdf)
- [SHiFT: Semi-hosted Fuzz Testing for Embedded Applications, 2024](https://www.usenix.org/system/files/usenixsecurity24-mera.pdf)
- [Towards Generic Database Management System Fuzzing, 2024](https://www.usenix.org/system/files/usenixsecurity24-yang-yupeng.pdf)
- [WhisperFuzz: White-Box Fuzzing for Detecting and Locating Timing Vulnerabilities in Processors, 2024](https://www.usenix.org/system/files/usenixsecurity24-borkar.pdf)

</details>

<details><summary>2023 (19 papers)</summary>

- [AIFORE: Smart Fuzzing Based on Automatic Input Format Reverse Engineering, 2023](https://www.usenix.org/system/files/usenixsecurity23-shi-ji.pdf)
- [autofz: Automated Fuzzer Composition at Runtime, 2023](https://www.usenix.org/system/files/usenixsecurity23-fu-yu-fu.pdf)
- [Automata-Guided Control-Flow-Sensitive Fuzz Driver Generation, 2023](https://www.usenix.org/system/files/usenixsecurity23-zhang-cen.pdf)
- [Automated Exploitable Heap Layout Generation for Heap Overflows Through Manipulation Distance-Guided Fuzzing, 2023](https://www.usenix.org/system/files/usenixsecurity23-zhang-bin.pdf)
- [Bleem: Packet Sequence Oriented Fuzzing for Protocol Implementations, 2023](https://www.usenix.org/system/files/usenixsecurity23-luo-zhengxiong.pdf)
- [BoKASAN: Binary-only Kernel Address Sanitizer for Effective Kernel Fuzzing, 2023](https://www.usenix.org/system/files/usenixsecurity23-cho.pdf)
- [CarpetFuzz: Automatic Program Option Constraint Extraction from Documentation for Fuzzing, 2023](https://www.usenix.org/system/files/usenixsecurity23-wang-dawei.pdf)
- [DDRace: Finding Concurrency UAF Vulnerabilities in Linux Drivers with Directed Fuzzing, 2023](https://www.usenix.org/system/files/usenixsecurity23-yuan-ming.pdf)
- [DynSQL: Stateful Fuzzing for Database Management Systems with Complex and Valid SQL Query Generation, 2023](https://www.usenix.org/system/files/usenixsecurity23-jiang-zu-ming.pdf)
- [Forming Faster Firmware Fuzzers, 2023](https://www.usenix.org/system/files/usenixsecurity23-seidel.pdf)
- [FuzzJIT: Oracle-Enhanced Fuzzing for JavaScript Engine JIT Compiler, 2023](https://www.usenix.org/system/files/usenixsecurity23-wang-junjie.pdf)
- [Fuzztruction: Using Fault Injection-based Fuzzing to Leverage Implicit Domain Knowledge, 2023](https://www.usenix.org/system/files/usenixsecurity23-bars.pdf)
- [GLeeFuzz: Fuzzing WebGL Through Error Message Guided Mutation, 2023](https://www.usenix.org/system/files/usenixsecurity23-peng.pdf)
- [Intender: Fuzzing Intent-Based Networking with Intent-State Transition Guidance, 2023](https://www.usenix.org/system/files/usenixsecurity23-kim-jiwon.pdf)
- [KextFuzz: Fuzzing macOS Kernel EXTensions on Apple Silicon via Exploiting Mitigations, 2023](https://www.usenix.org/system/files/usenixsecurity23-yin.pdf)
- [MINER: A Hybrid Data-Driven Approach for REST API Fuzzing, 2023](https://www.usenix.org/system/files/usenixsecurity23-lyu.pdf)
- [MorFuzz: Fuzzing Processor via Runtime Instruction Morphing enhanced Synchronizable Co-simulation, 2023](https://www.usenix.org/system/files/usenixsecurity23-xu-jinyan.pdf)
- [MTSan: A Feasible and Practical Memory Sanitizer for Fuzzing COTS Binaries, 2023](https://www.usenix.org/system/files/usenixsecurity23-chen-xingman.pdf)
- [PolyFuzz: Holistic Greybox Fuzzing of Multi-Language Systems, 2023](https://www.usenix.org/system/files/usenixsecurity23-li-wen.pdf)

</details>

<details><summary>2022 (14 papers)</summary>

- [StateFuzz: System Call-Based State-Aware Linux Driver Fuzzing, 2022](https://www.usenix.org/system/files/sec22-zhao-bodong.pdf)
- [FIXREVERTER: A Realistic Bug Injection Methodology for Benchmarking Fuzz Testing, 2022](https://www.usenix.org/system/files/sec22-zhang-zenong.pdf)
- [SGXFuzz: Efficiently Synthesizing Nested Structures for SGX Enclave Fuzzing, 2022](https://www.usenix.org/system/files/sec22-cloosters.pdf)
- [AmpFuzz: Fuzzing for Amplification DDoS Vulnerabilities, 2022](https://www.usenix.org/system/files/sec22-krupp.pdf)
- [Stateful Greybox Fuzzing, 2022](https://www.usenix.org/system/files/sec22-ba.pdf)
- [BrakTooth: Causing Havoc on Bluetooth Link Manager via Directed Fuzzing, 2022](https://www.usenix.org/system/files/sec22-garbelini.pdf)
- [Fuzzing Hardware Like Software, 2022](https://www.usenix.org/system/files/sec22-trippel.pdf)
- [Drifuzz: Harvesting Bugs in Device Drivers from Golden Seeds, 2022](https://www.usenix.org/system/files/sec22-shen-zekun.pdf)
- [FuzzOrigin: Detecting UXSS vulnerabilities in Browsers through Origin Fuzzing, 2022](https://www.usenix.org/system/files/sec22-kim.pdf)
- [TheHuzz: Instruction Fuzzing of Processors Using Golden-Reference Models for Finding Software-Exploitable Vulnerabilities, 2022](https://www.usenix.org/system/files/sec22-kande.pdf)
- [MundoFuzz: Hypervisor Fuzzing with Statistical Coverage Testing and Grammar Inference, 2022](https://www.usenix.org/system/files/sec22-myung.pdf)
- [Fuzzware: Using Precise MMIO Modeling for Effective Firmware Fuzzing, 2022](https://www.usenix.org/system/files/sec22-scharnowski.pdf)
- [SyzScope: Revealing High-Risk Security Impacts of Fuzzer-Exposed Bugs in Linux kernel, 2022](https://www.usenix.org/system/files/sec22-zou.pdf)
- [Morphuzz: Bending (Input) Space to Fuzz Virtual Devices, 2022](https://www.usenix.org/system/files/sec22-bulekov.pdf)

</details>

<details><summary>2021 (6 papers)</summary>

- [Breaking Through Binaries: Compiler-quality Instrumentation for Better Binary-only Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/nagy)
- [ICSFuzz: Manipulating I/Os and Repurposing Binary Code to Enable Instrumented Fuzzing in ICS Control Applications, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/tychalas)
- [Android SmartTVs Vulnerability Discovery via Log-Guided Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/aafer)
- [Constraint-guided Directed Greybox Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/lee-gwangmu)
- [Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/schumilo)
- [UNIFUZZ: A Holistic and Pragmatic Metrics-Driven Platform for Evaluating Fuzzers, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/li-yuwei)

</details>

<details><summary>2020 (10 papers)</summary>

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

</details>

<details><summary>2019 (2 papers)</summary>

- [Fuzzification: Anti-Fuzzing Techniques, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/jung)
- [AntiFuzz: Impeding Fuzzing Audits of Binary Executables, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/guler)

</details>

<details><summary>2018 (3 papers)</summary>

- [Charm: Facilitating Dynamic Analysis of Device Drivers of Mobile Systems, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/talebi)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/pailoor)
- [QSYM : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/yun)

</details>

<details><summary>2017 (2 papers)</summary>

- [OSS-Fuzz - Google's continuous fuzzing service for open source software, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/schumilo)

</details>

<details><summary>2015 (1 paper)</summary>

- [Protocol State Fuzzing of TLS Implementations, 2015](https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/de-ruiter)

</details>

<details><summary>2014 (1 paper)</summary>

- [Optimizing Seed Selection for Fuzzing, 2014](https://softsec.kaist.ac.kr/~sangkilc/papers/rebert-usenixsec14.pdf)

</details>

<details><summary>2013 (1 paper)</summary>

- [Dowsing for overflows: a guided fuzzer to find buffer boundary violations, 2013](http://enigma.usenix.org/sites/default/files/sec13_proceedings_interior.pdf#page=57)

</details>

<details><summary>2012 (1 paper)</summary>

- [Fuzzing with Code Fragments, 2012](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final73.pdf)

</details>


### ACM Conference on Computer and Communications Security (ACM CCS)

<details><summary>2025 (11 papers)</summary>

- [A Qualitative Analysis of Fuzzer Usability and Challenges, 2025](https://dl.acm.org/doi/10.1145/3719027.3765055)
- [ConTest: Taming the Cyber-physical Input Space in Fuzz Testing with Control Theory, 2025](https://dl.acm.org/doi/10.1145/3719027.3765129)
- [DiveFuzz: Enhancing CPU Fuzzing via Diverse Instruction Construction, 2025](https://dl.acm.org/doi/10.1145/3719027.3765167)
- [Error Messages to Fuzzing: Detecting XPS Parsing Vulnerabilities in Windows Printing Components, 2025](https://dl.acm.org/doi/10.1145/3719027.3744807)
- [Fuzzing Processing Pipelines for Zero-Knowledge Circuits, 2025](https://dl.acm.org/doi/10.1145/3719027.3744791)
- [Intent-aware Fuzzing for Android Hardened Application, 2025](https://dl.acm.org/doi/10.1145/3719027.3744858)
- [PromeFuzz: A Knowledge-Driven Approach to Fuzzing Harness Generation with Large Language Models, 2025](https://dl.acm.org/doi/10.1145/3719027.3765222)
- [Protocol-Aware Firmware Rehosting for Effective Fuzzing of Embedded Network Stacks, 2025](https://dl.acm.org/doi/10.1145/3719027.3765125)
- [RVISmith: Fuzzing Compilers for RVV Intrinsics, 2025](https://dl.acm.org/doi/10.1145/3719027.3744790)
- [SyzParam: Incorporating Runtime Parameters into Kernel Driver Fuzzing, 2025](https://dl.acm.org/doi/10.1145/3719027.3744838)
- [SyzSpec: Specification Generation for Linux Kernel Fuzzing via Under-Constrained Symbolic Execution, 2025](https://dl.acm.org/doi/10.1145/3719027.3744811)

</details>

<details><summary>2024 (19 papers)</summary>

- [Collapse Like A House of Cards: Hacking Building Automation System Through Fuzzing, 2024](https://dl.acm.org/doi/10.1145/3658644.3690216)
- [CountDown: Refcount-guided Fuzzing for Exposing Temporal Memory Errors in Linux Kernel, 2024](https://dl.acm.org/doi/10.1145/3658644.3690320)
- [CrossFire: Fuzzing macOS Cross-XPU Memory on Apple Silicon, 2024](https://dl.acm.org/doi/10.1145/3658644.3690376)
- [DarthShader: Fuzzing WebGPU Shader Translators & Compilers, 2024](https://dl.acm.org/doi/10.1145/3658644.3690209)
- [FOX: Coverage-guided Fuzzing as Online Stochastic Control, 2024](https://dl.acm.org/doi/10.1145/3658644.3670362)
- [Fuzz to the Future: Uncovering Occluded Future Vulnerabilities via Robust Fuzzing, 2024](https://dl.acm.org/doi/10.1145/3658644.3690278)
- [FuzzCache: Optimizing Web Application Fuzzing Through Software-Based Data Cache, 2024](https://dl.acm.org/doi/10.1145/3658644.3670278)
- [Fuzzing JavaScript Engines with a Graph-based IR, 2024](https://dl.acm.org/doi/10.1145/3658644.3690336)
- [Leveraging Binary Coverage for Effective Generation Guidance in Kernel Fuzzing, 2024](https://dl.acm.org/doi/10.1145/3658644.3690232)
- [LIFTFUZZ: Validating Binary Lifters through Context-aware Fuzzing with GPT, 2024](https://dl.acm.org/doi/10.1145/3658644.3670276)
- [No Peer, no Cry: Network Application Fuzzing via Fault Injection, 2024](https://dl.acm.org/doi/10.1145/3658644.3690274)
- [On Understanding and Forecasting Fuzzers Performance with Static Analysis, 2024](https://dl.acm.org/doi/10.1145/3658644.3670348)
- [OSmart: Whitebox Program Option Fuzzing, 2024](https://dl.acm.org/doi/10.1145/3658644.3690228)
- [Program Environment Fuzzing, 2024](https://dl.acm.org/doi/10.1145/3658644.3690229)
- [Prompt Fuzzing for Fuzz Driver Generation, 2024](https://dl.acm.org/doi/10.1145/3658644.3670396)
- [ProphetFuzz: Fully Automated Prediction and Fuzzing of High-Risk Option Combinations with Only Documentation via Large Language Model, 2024](https://dl.acm.org/doi/10.1145/3658644.3690231)
- [RANsacked: A Domain-Informed Approach for Fuzzing LTE and 5G RAN-Core Interfaces, 2024](https://dl.acm.org/doi/10.1145/3658644.3670320)
- [RIoTFuzzer: Companion App Assisted Remote Fuzzing for Detecting Vulnerabilities in IoT Devices, 2024](https://dl.acm.org/doi/10.1145/3658644.3670342)
- [Toss a Fault to BpfChecker: Revealing Implementation Flaws for eBPF runtimes with Differential Fuzzing, 2024](https://dl.acm.org/doi/10.1145/3658644.3690237)

</details>

<details><summary>2023 (9 papers)</summary>

- [DSFuzz: Detecting Deep State Bugs with Dependent State Exploration, 2023](https://dl.acm.org/doi/10.1145/3576915.3616594)
- [Fuzz on the Beach: Fuzzing Solana Smart Contracts, 2023](https://dl.acm.org/doi/10.1145/3576915.3623178)
- [Greybox Fuzzing of Distributed Systems, 2023](https://dl.acm.org/doi/10.1145/3576915.3623097)
- [Hopper: Interpretative Fuzzing for Libraries, 2023](https://dl.acm.org/doi/10.1145/3576915.3616610)
- [Lifting Network Protocol Implementation to Precise Format Specification with Security Applications, 2023](https://dl.acm.org/doi/10.1145/3576915.3616614)
- [NestFuzz: Enhancing Fuzzing with Comprehensive Understanding of Input Processing Logic, 2023](https://dl.acm.org/doi/10.1145/3576915.3623103)
- [Profile-guided System Optimizations for Accelerated Greybox Fuzzing, 2023](https://dl.acm.org/doi/10.1145/3576915.3616636)
- [PyRTFuzz: Detecting Bugs in Python Runtimes via Two-Level Collaborative Fuzzing, 2023](https://dl.acm.org/doi/10.1145/3576915.3623166)
- [SyzDirect: Directed Greybox Fuzzing for Linux Kernel, 2023](https://dl.acm.org/doi/10.1145/3576915.3623146)

</details>

<details><summary>2022 (6 papers)</summary>

- [SpecDoctor: Differential Fuzz Testing to Find Transient Execution Vulnerabilities, 2022](https://compsec.snu.ac.kr/papers/jaewon-specdoctor.pdf)
- [SFuzz: Slice-based Fuzzing for Real-Time Operating Systems, 2022](https://huhong789.github.io/papers/chen:sfuzz.pdf)
- [MC^2: Rigorous and Efficient Directed Greybox Fuzzing, 2022](https://arxiv.org/pdf/2208.14530.pdf)
- [LibAFL: A Framework to Build Modular and Reusable Fuzzers, 2022](https://www.s3.eurecom.fr/docs/ccs22_fioraldi.pdf)
- [JIT-Picking: Differential Fuzzing of JavaScript Engines, 2022](https://publications.cispa.saarland/3773/1/2022-CCS-JIT-Fuzzing.pdf)
- [DriveFuzz: Discovering Autonomous Driving Bugs through Driving Quality-Guided Fuzzing, 2022](https://chungkim.io/doc/ccs22-drivefuzz.pdf)

</details>

<details><summary>2021 (8 papers)</summary>

- [SoFi: Reflection-Augmented Fuzzing for JavaScript Engines, 2021](https://dl.acm.org/doi/pdf/10.1145/3460120.3484823)
- [T-Reqs: HTTP Request Smuggling with Differential Fuzzing, 2021](https://bahruz.me/papers/ccs2021treqs.pdf)
- [V-SHUTTLE: Scalable and Semantics-Aware Hypervisor Fuzzing, 2021](https://nesa.zju.edu.cn/download/ppt/pgn_slides_V-SHUTTLE.pdf)
- [Same Coverage, Less Bloat: Accelerating Binary-only Fuzzing with Coverage-preserving Coverage-guided Tracing, 2021](https://people.cs.vt.edu/snagy2/papers/21CCS.pdf)
- [HyperFuzzer: An Efficient Hybrid Fuzzer For Virtual CPUs, 2021](https://www.microsoft.com/en-us/research/uploads/prod/2021/09/hyperfuzzer-ccs21.pdf)
- [Regression Greybox Fuzzing, 2021](https://mboehme.github.io/paper/CCS21.pdf)
- [Hardware Support to Improve Fuzzing Performance and Precision, 2021](https://gts3.org/assets/papers/2021/ding:snap.pdf)
- [SNIPUZZ: Black-box Fuzzing of IoT Firmware via Message Snippet Inference, 2021](https://arxiv.org/pdf/2105.05445.pdf)

</details>

<details><summary>2020 (1 paper)</summary>

- [FREEDOM: Engineering a State-of-the-Art DOM Fuzzer, 2020](https://gts3.org/assets/papers/2020/xu:freedom.pdf)

</details>

<details><summary>2019 (3 papers)</summary>

- [Intriguer: Field-Level Constraint Solving for Hybrid Fuzzing, 2019](https://dl.acm.org/citation.cfm?id=3354249)
- [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts, 2019](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf)
- [Matryoshka: fuzzing deeply nested branches, 2019](https://web.cs.ucdavis.edu/~hchen/paper/chen2019matryoshka.pdf)

</details>

<details><summary>2018 (2 papers)</summary>

- [Evaluating Fuzz Testing, 2018](http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer, 2018](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)

</details>

<details><summary>2017 (7 papers)</summary>

- [IMF: Inferred Model-based Fuzzer, 2017](http://daramg.gift/paper/han-ccs2017.pdf)
- [SemFuzz: Semantics-based Automatic Generation of Proof-of-Concept Exploits, 2017](https://www.informatics.indiana.edu/xw7/papers/p2139-you.pdf)
- [AFL-based Fuzzing for Java with Kelinci, 2017](https://dl.acm.org/citation.cfm?id=3138820)
- [Designing New Operating Primitives to Improve Fuzzing Performance, 2017](http://iisp.gatech.edu/sites/default/files/images/designing_new_operating_primitives_to_improve_fuzzing_performance_vt.pdf)
- [Directed Greybox Fuzzing, 2017](https://dl.acm.org/citation.cfm?id=3134020)
- [SlowFuzz: Automated Domain-Independent Detection of Algorithmic Complexity Vulnerabilities, 2017](https://arxiv.org/pdf/1708.08437.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf)

</details>

<details><summary>2016 (3 papers)</summary>

- [Systematic Fuzzing and Testing of TLS Libraries, 2016](https://www.nds.rub.de/media/nds/veroeffentlichungen/2016/10/19/tls-attacker-ccs16.pdf)
- [Coverage-based Greybox Fuzzing as Markov Chain, 2016](https://ieeexplore.ieee.org/abstract/document/8233151)
- [eFuzz: A Fuzzer for DLMS/COSEM Electricity Meters, 2016](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.817.5616&rep=rep1&type=pdf)

</details>

<details><summary>2013 (2 papers)</summary>

- [Scheduling Black-box Mutational Fuzzing, 2013](https://softsec.kaist.ac.kr/~sangkilc/papers/woo-ccs13.pdf)
- [Taming compiler fuzzers, 2013](https://www.cs.utah.edu/~regehr/papers/pldi13.pdf)

</details>

<details><summary>2012 (1 paper)</summary>

- [SAGE: whitebox fuzzing for security testing, 2012](https://dl.acm.org/citation.cfm?id=2094081)

</details>

<details><summary>2008-2009 (2 papers)</summary>

- [Taint-based directed whitebox fuzzing, 2009](https://dl.acm.org/citation.cfm?id=1555061)
- [Grammar-based whitebox fuzzing, 2008](https://dl.acm.org/citation.cfm?id=1375607)

</details>


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
- [Fuzzle: Making a Puzzle for Fuzzers, 2022](https://softsec.kaist.ac.kr/~sangkilc/papers/lee-ase22.pdf)
- [Ifuzzer: An evolutionary interpreter fuzzer using genetic programming, 2016](https://www.cs.vu.nl/~herbertb/download/papers/ifuzzer-esorics16.pdf)
- [Hybrid fuzz testing: Discovering software bugs via fuzzing and symbolic execution, 2012](https://pdfs.semanticscholar.org/488a/b1e313f5109153f2c74e3b5d86d41e9b4b71.pdf)
- [Call-Flow Aware API Fuzz Testing for Security of Windows Systems, 2008](https://www.computer.org/csdl/proceedings/iccsa/2008/3243/00/3243a019-abs.html)
- [Feedback-directed random test generation, 2007](https://dl.acm.org/citation.cfm?id=1248841)
- [MTF-Storm:a high performance fuzzer for Modbus/TCP, 2018](https://doi.org/10.1109/ETFA.2018.8502600)
- [A Modbus/TCP Fuzzer for testing internetworked industrial systems, 2015](https://doi.org/10.1109/ETFA.2015.7301400)



## Tools
A curated collection of open-source fuzzing tools, organized by target category based on the taxonomy from [fuzzing-survey.org](https://fuzzing-survey.org/). Tools are selected based on a combination of factors including GitHub popularity, recency, availability of official repositories from original authors, and whether the project is actively maintained.
### File
- [AFL++](https://github.com/AFLplusplus/AFLplusplus) - A superior fork to Google's AFL with more speed, more and better mutations, more and better instrumentation, and custom module support.
- [Angora](https://github.com/AngoraFuzzer/Angora) - A mutation-based coverage guided fuzzer that increases branch coverage by solving path constraints without symbolic execution.
### Kernel
- [ACTOR](https://github.com/ucsb-seclab/actor) (2023) - An action-guided kernel fuzzing framework that generates inputs leveraging triggered actions and their temporal relationships.
- [NTFuzz](https://github.com/SoftSec-KAIST/NTFuzz) (2021) - A type-aware Windows kernel fuzzer that statically analyzes system binaries to infer system call types for more effective fuzzing.
- [KRACE](https://github.com/sslab-gatech/krace) (2020) - A coverage-guided fuzzing framework that detects data races in kernel file systems by exploring concurrency through multi-threaded syscall sequences.
- [Razzer](https://github.com/compsec-snu/razzer) (2019) - A kernel fuzzer that uses static analysis and two-phase fuzzing to detect race conditions and concurrency bugs in Linux kernels.
- [Hydra](https://github.com/sslab-gatech/hydra) (2019) - A fuzzing framework for automatically discovering semantic bugs in file systems using input mutators, feedback engines, and customizable checkers.
- [Janus](https://github.com/sslab-gatech/janus) (2019) - A file system fuzzer that finds memory corruptions in Linux kernel file systems by mutating both filesystem images and syscall sequences simultaneously.
- [DIFUZE](https://github.com/ucsb-seclab/difuze) (2017) - An interface-aware fuzzer for Linux kernel drivers that automatically recovers ioctl interfaces via LLVM analysis and generates targeted test cases.
- [IMF](https://github.com/SoftSec-KAIST/IMF) (2017) - A kernel API fuzzer that leverages automated API model inference to discover vulnerabilities in macOS kernel APIs.
- [kAFL](https://github.com/rub-syssec/kafl) (2017) - A hardware-assisted x86-64 VM kernel fuzzing framework with performant VM reloads for finding OS kernel vulnerabilities.
- [syzkaller](https://github.com/google/syzkaller) (2015) - An unsupervised coverage-guided kernel fuzzer supporting FreeBSD, Fuchsia, gVisor, Linux, NetBSD, OpenBSD, and Windows. 
- [Trinity](https://github.com/kernelslacker/trinity) (2012) - A Linux system call fuzzer that generates semi-intelligent random arguments to syscalls, including valid file descriptors, flags, and range-biased values.
### Network
### API
- [WuppieFuzz](https://github.com/TNO-S3/WuppieFuzz) - A coverage-guided REST API fuzzer developed on top of LibAFL.
- [IvySyn](https://gitlab.com/brown-ssl/ivysyn) - A fully-automated framework for discovering memory error vulnerabilities in Deep Learning (DL) frameworks.
- [MINER](https://github.com/puppet-meteor/MINER) - A REST API fuzzer that utilizes three data-driven designs working together to guide sequence generation, improve request generation quality, and capture unique errors caused by incorrect parameter usage.
- [RestTestGen](https://github.com/SeUniVr/RestTestGen) - A robust tool and framework designed for automated black-box testing of RESTful web APIs.
- [GraphFuzz](https://github.com/ForAllSecure/GraphFuzz) - An experimental framework for building structure-aware, library API fuzzers.
- [Minerva](https://github.com/ChijinZ/Minerva) - A browser fuzzer augmented by API mod-ref relations, aiming to synthesize highly-relevant browser API invocations in each test case.
- [FANS](https://github.com/iromise/fans) - A fuzzing tool for Android native system services with four components: interface collector, interface model extractor, dependency inferer, and fuzzer engine.
### JavaScript
### Firmware
### Hypervisor
### CPU
- [DifuzzRTL](https://github.com/compsec-snu/difuzz-rtl) - A differential fuzz testing approach for CPU verification.
- [MorFuzz](https://github.com/sycuricon/MorFuzz) - A generic RISC-V processor fuzzing framework that can efficiently detect software triggerable functional bugs.
- [SpecFuzz](https://github.com/tudinfse/SpecFuzz) - A tool to enable fuzzing for Spectre vulnerabilities.
- [Transynther](https://github.com/vernamlab/Medusa) - Automatically generates and tests building blocks for Meltdown attacks with various faults and microcode assists.
### Lib
### Web
- [TEFuzz](https://github.com/seclab-fudan/TEFuzz/) - A tailored fuzzing-based framework to facilitate the detection and exploitation of template escape bugs.
- [Witcher](https://github.com/sefcom/Witcher) - A web application fuzzer that utilizes mutational fuzzing to explore web applications and fault escalation to detect command and SQL injection vulnerabilities.
- [CorbFuzz](https://github.com/shouc/corbfuzz) - A state-aware fuzzer for generating as many responses from a web application as possible without need of setting up a database.
### DOM
### Argument
### Blockchain
- [Fluffy](https://github.com/snuspl/fluffy) - A multi-transaction differential fuzzer for finding consensus bugs in Ethereum.
- [LOKI](https://github.com/ConsensusFuzz/LOKI) - A Blockchain consensus protocol fuzzing framework that detects consensus memory related and logic bugs.
### DBMS
- [Squirrel](https://github.com/s3team/Squirrel) - A fuzzer for database management systems (DBMSs).


## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/cpuu/awesome-fuzzing/blob/master/contributing.md) first.
