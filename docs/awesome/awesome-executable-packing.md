<div class="github-widget" data-repo="dhondta/awesome-executable-packing"></div>
## Awesome Executable Packing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <a href="https://twitter.com/intent/tweet?text=Awesome%20Executable%20Packing%20-%20A%20curated%20list%20of%20resources%20related%20to%20the%20packing%20of%20various%20executable%20formats%20and%20its%20detection.%0D%0Ahttps%3a%2f%2fgithub%2ecom%2fdhondta%2fawesome-executable-packing%0D%0A&hashtags=awesomelists,malware,malwareresearch,executablepacking,cybersecurity,infosec"><img src="https://img.shields.io/badge/Tweet--lightgrey?logo=twitter&style=social" alt="Tweet" height="20"/></a>

&gt; 与可执行打包（包括可移植可执行文件、可执行文件和可链接格式等）相关的精选资源列表，其中包含对书籍、论文、博客文章和其他书面资源的引用，以及用于检测打包程序和解包可执行文件的打包程序和工具.

 *打包*是以不修改其目的的方式修改可执行文件的操作. 一般是以下操作之一或组合：
- 捆绑：制作一个包含多个文件的可执行文件
- 压缩：压缩可执行文件以减小其原始大小
- 编码：通过编码来混淆可执行文件
- 加密：通过加密来混淆可执行文件
- 变异：改变可执行文件的代码，使其使用修改后的指令集和架构（例如，使用寡态）
- 保护：使可执行文件的逆向更加困难（即使用反调试、反篡改或其他技巧）
- 虚拟化：嵌入允许虚拟化可执行指令的虚拟机






## :books: Literature


### Documentation

- ：地球美洲： [a.out (FreeBSD manual pages)](https://www.freebsd.org/cgi/man.cgi?a.out(5))
- ：地球美洲： [A.out binary format](https://wiki.osdev.org/A.out)
- ：地球美洲： [About anti-debug tricks](https://anti-debug.checkpoint.com)
- ：bar_chart： [Android packers: Separating from the pack](https://www.fortiguard.com/events/759/2014-06-12-android-packers-separating-from-the-pack)
- ：图钉： [Anti debugging protection techniques with examples](https://www.apriorit.com/dev-blog/367-anti-reverse-engineering-protection-techniques-to-use-before-releasing-software)
- ：page_facing_up： [Anti-unpacker tricks](https://pferrie.tripod.com/papers/unpackers.pdf)
- ：page_facing_up： [Anti-unpacker tricks - Part 14 (and previous parts)](https://www.virusbulletin.com/virusbulletin/2010/11/anti-unpacker-tricks-part-fourteen/)
- ：bar_chart： [API deobfuscator: Resolving obfuscated API functions in modern packers](https://www.blackhat.com/docs/us-15/materials/us-15-Choi-API-Deobfuscator-Resolving-Obfuscated-API-Functions-In-Modern-Packers.pdf)
- ：bar_chart： [The art of unpacking](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf)
- ：图钉： [Cloak and dagger: Unpacking hidden malware attacks](https://symantec-enterprise-blogs.security.com/blogs/expert-perspectives/unpacking-hidden-malware-attacks)
- ：地球美洲： [COM binary format](https://wiki.osdev.org/COM)
- ：地球美洲： [Common object file format (COFF)](https://wiki.osdev.org/COFF)
- ：地球美洲： [Comparison of executable file formats](https://en.wikipedia.org/wiki/Comparison_of_executable_file_formats)
- ：地球美洲： [Defacto2](https://defacto2.net/defacto2)
- ：bar_chart： [Dynamic binary analysis and obfuscated codes](https://triton.quarkslab.com/files/sthack2016-rthomas-jsalwan.pdf)
- ：地球美洲： [elf (FreeBSD manual pages)](https://www.freebsd.org/cgi/man.cgi?elf(5))
- ：图钉： [Entropy and the distinctive signs of packer PE files](https://n10info.blogspot.com/2014/06/entropy-and-distinctive-signs-of-packed.html)
- ：地球美洲： [Executable and linkable format (ELF)](https://wiki.osdev.org/ELF)
- ：剪贴板： [Executable and linking format (ELF) specification](https://refspecs.linuxfoundation.org/elf/elf.pdf)
- ：地球美洲： [Executable file formats](https://docs.fileformat.com/executable)
- ：地球美洲： [FatELF: Universal binaries for Linux (HALTED)](https://icculus.org/fatelf)
- ：剪贴板： [Hyperion: Implementation of a PE-Crypter](https://www.exploit-db.com/docs/english/18849-hyperion-implementation-of-a-pe-crypter.pdf)
- ：滚动： [Implementing your own generic unpacker](https://gsec.hitb.org/materials/sg2015/whitepapers/Julien%20Lenoir%20-%20Implementing%20Your%20Own%20Generic%20Unpacker.pdf)
- ：图钉： [Mach-O - A look at apple executable files](https://redmaple.tech/blogs/macho-files)
- ：地球美洲： [Mach-O file format reference](https://github.com/aidansteele/osx-abi-macho-file-format-reference)
- ：bar_chart： [Mach-O internals](https://yossarian.net/res/pub/macho-internals/macho-internals.pdf)
- ：剪贴板： [Microsoft portable executable and common object file format specification](http://www.skyfree.org/linux/references/coff.pdf)
- ：地球美洲： [MITRE ATT&CK | T1027.002 | obfuscated files or information: Software packing](https://attack.mitre.org/techniques/T1027/002)
- ：地球美洲： [MZ disk operating system (DOS)](https://wiki.osdev.org/MZ)
- ：bar_chart： [One packer to rule them all: Empirical identification, comparison and circumvention of current antivirus detection techniques](https://www.blackhat.com/docs/us-14/materials/us-14-Mesbahi-One-Packer-To-Rule-Them-All-WP.pdf)
- ：滚动： [One packer to rule them all: Empirical identification, comparison and circumvention of current antivirus detection techniques](https://www.blackhat.com/docs/us-14/materials/us-14-Mesbahi-One-Packer-To-Rule-Them-All.pdf)
- ：图钉： [Packer detection tool evaluation](https://github.com/FFRI/PackerDetectionToolEvaluation)
- ：page_facing_up： [Packers](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/corkami/packers.pdf)  ：星：：星：：星：
- ：图钉： [Parsing mach-O files](https://lowlevelbits.org/parsing-mach-o-files)
- ：地球美洲： [PE format (Microsoft docs)](https://docs.microsoft.com/en-us/windows/win32/debug/pe-format)
- ：滚动： [PinDemonium: A DBI-based generic unpacker for Windows executables](https://www.blackhat.com/docs/us-16/materials/us-16-Mariani-Pindemonium-A-Dbi-Based-Generic-Unpacker-For-Windows-Executables-wp.pdf)
- ：地球美洲： [Portable executable (PE)](https://wiki.osdev.org/PE)
- ：bar_chart： [Reverse engineering malware: Binary obfuscation and protection](http://www.cse.tkk.fi/fi/opinnot/T-110.6220/2014_Reverse_Engineering_Malware_AND_Mobile_Platform_Security_AND_Software_Security/luennot-files/Binary%20Obfuscation%20and%20Protection.pdf)
- ：bar_chart： [Runtime packers: The hidden problem?](https://www.blackhat.com/presentations/bh-usa-06/BH-US-06-Morgenstern.pdf)
- ：bar_chart： [TitanMist: Your first step to reversing nirvana](https://www.reversinglabs.com/blackhat/TitanMist_BlackHat-USA-10-Slides.pdf)
- ：图钉： [Tuts 4 you - UnPackMe (.NET)](https://forum.tuts4you.com/forum/155-unpackme-net)
- ：图钉： [Tuts 4 you | unpackme](https://forum.tuts4you.com/forum/147-unpackme)
- ：关闭_book： [The "Ultimate" anti-debugging reference](http://pferrie.epizy.com/papers/antidebug.pdf)
- ：图钉： [Unpacking, reversing, patching](https://resources.infosecinstitute.com/topic/unpacking-reversing-patching)
- ：bar_chart： [Virtual machine obfuscation](https://compil2019.minesparis.psl.eu/wp-content/uploads/2019/02/BeatriceCreusillet-Obfuscation-quarkslab.pdf)
- ：bar_chart： [We can still crack you! General unpacking method for Android Packer (NO ROOT)](https://www.blackhat.com/asia-15/briefings.html#we-can-still-crack-you-general-unpacking-method-for-android-packer-no-root)
- ：bar_chart： [When malware is packing heat](https://www.eurecom.fr/publication/5372)
- ：剪贴板： [Win32 portable executable packing uncovered](https://securitylabs.websense.com/content/Assets/HistoryofPackingTechnology.pdf)
- ：图钉： [Writing a packer](https://dr4k0nia.github.io/posts/Writing-a-Packer)
- ：图钉： [Writing a simple PE packer in detail](https://github.com/levanvn/Packer_Simple-1)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Scientific Research

- ：报纸： [Absent extreme learning machine algorithm with application to packed executable identification](https://link.springer.com/article/10.1007%2Fs00521-014-1558-4) （2016 年 1 月） 
- ：报纸： [An accurate packer identification method using support vector machine](https://www.jstage.jst.go.jp/article/transfun/E97.A/1/E97.A_253/_article) （2014年1月） 
- ：笔记本： [Adaptive unpacking of Android Apps](https://ieeexplore.ieee.org/document/7985676) （2017 年 5 月） 
- ：报纸： [Advanced preprocessing of binary executable files and its usage in retargetable decompilation](https://www.fit.vut.cz/research/publication/10531) （2014 年 12 月） 
- ：报纸： [All-in-one framework for detection, unpacking, and verification for malware analysis](https://www.hindawi.com/journals/scn/2019/5278137/) （2019 年 1 月）：明星：
- ：报纸： [Analysis of machine learning approaches to packing detection](https://arxiv.org/abs/2105.00473) （2021 年 5 月）：明星：
- ：报纸： [Anti-emulation trends in modern packers: A survey on the evolution of anti-emulation techniques in UPA packers](https://doi.org/10.1007/s11416-017-0291-9) （2018 年 5 月）：明星：
- ：笔记本： [Anti-unpacker tricks](http://2008.caro.org/downloads/unpackers.pdf) （2008 年 5 月） 
- ：笔记本： [Application of string kernel based support vector machine for malware packer identification](https://ieeexplore.ieee.org/document/6707043) （2013年8月） 
- ：报纸： [The application research of virtual machine in packers](https://www.semanticscholar.org/paper/The-Application-Research-of-Virtual-Machine-in-Wen-yu/fff04e0073ac2018bff5242919cdca47deacad7a) （2011 年 8 月） 
- ：笔记本： [AppSpear: Bytecode decrypting and DEX reassembling for packed Android malware](https://link.springer.com/chapter/10.1007/978-3-319-26362-5_17) （2015 年 11 月） 
- ：报纸： [The arms race: Adversarial search defeats entropy used to detect malware](https://www.sciencedirect.com/science/article/pii/S0957417418306535) （2018 年 10 月）：明星：
- ：报纸： [Automatic analysis of malware behavior using machine learning](https://dl.acm.org/doi/10.5555/2011216.2011217) （2011 年 12 月） 
- ：笔记本： [Automatic static unpacking of malware binaries](https://ieeexplore.ieee.org/document/5328814) （2009 年 10 月） 
- ：报纸： [BareUnpack: Generic unpacking on the bare-metal operating system](https://www.jstage.jst.go.jp/article/transinf/E101.D/12/E101.D_2017EDP7424/_article) （2018 年 12 月） 
- ：报纸： [Binary-code obfuscations in prevalent packer tools](https://dl.acm.org/doi/10.1145/2522968.2522972) （2013 年 10 月）：明星：
- ：报纸： [BinStat tool for recognition of packed executables](http://www.ijofcs.org/abstract-v06n1-pp03.html) （2010 年 9 月） 
- ：笔记本： [BitBlaze: A new approach to computer security via binary analysis](https://link.springer.com/chapter/10.1007/978-3-540-89862-7_1) （2008 年 12 月） 
- ：笔记本： [Boosting scalability in anomaly-based packed executable filtering](https://link.springer.com/chapter/10.1007%2F978-3-642-34704-7_3) （2011 年 11 月） 
- ：砂浆板： [Building a smart and automated tool for packed malware detections using machine learning](https://dial.uclouvain.be/memoire/ucl/en/object/thesis%3A25193) （2020 年 6 月）：明星：
- :newspaper: 使用 DBI 工具绕过商业保护方法的反分析（2021 年 1 月）:star:
- ：笔记本： [ByteWise: A case study in neural network obfuscation identification](https://ieeexplore.ieee.org/document/8301720/) （2018 年 1 月） 
- ：笔记本： [Challenging anti-virus through evolutionary malware obfuscation](https://link.springer.com/chapter/10.1007%2F978-3-319-31153-1_11) （2016 年 4 月） 
- ：报纸： [Classification of packed executables for accurate computer virus detection](http://www.sciencedirect.com/science/article/pii/S0167865508002110) （2008 年 10 月） 
- ：笔记本： [Classifying packed malware represented as control flow graphs using deep graph convolutional neural network](https://ieeexplore.ieee.org/document/9103752) （2020 年 3 月）：明星：
- ：笔记本： [Classifying packed programs as malicious software detected](https://www.semanticscholar.org/paper/Classifying-Packed-Programs-as-Malicious-Software-Osaghae/676f38819a0ed3028acce36f4f11b0c77e4cc0ae) （2016 年 12 月）：明星：
- ：报纸： [A close look at a daily dataset of malware samples](https://dl.acm.org/doi/10.1145/3291061) （2019 年 1 月） 
- ：笔记本： [Collective classification for packed executable identification](https://doi.org/10.1145/2030376.2030379) （2012 年 6 月） 
- ：笔记本： [A comparative analysis of classifiers in the recognition of packed executables](https://ieeexplore.ieee.org/abstract/document/8995252) （2019 年 11 月）:star:
- ：报纸： [A comparative analysis of software protection schemes](https://www.researchgate.net/publication/281653855_A_Comparative_Analysis_of_Software_Protection_Schemes) （2014 年 6 月） 
- ：笔记本： [A comparative assessment of malware classification using binary texture analysis and dynamic analysis](https://dl.acm.org/doi/10.1145/2046684.2046689) （2011 年 9 月） 
- ：笔记本： [Comparing malware samples for unpacking: A feasibility study](https://ieeexplore.ieee.org/document/7782073) （2016 年 8 月） 
- ：砂浆板： [Computational-intelligence techniques for malware generation](https://raw.githubusercontent.com/jimmy-sonny/ConferencesAndTalks/master/Ms.C%20Thesis/Thesis_Marcelli.pdf) （2015 年 10 月） 
- ：报纸： [A consistently-executing graph-based approach for malware packer identification](https://ieeexplore.ieee.org/document/8695825) （2019 年 4 月）：明星：
- ：笔记本： [A control flow graph-based signature for packer identification](https://ieeexplore.ieee.org/document/8170793) （2017 年 10 月） 
- ：笔记本： [Countering entropy measure attacks on packed software detection](https://ieeexplore.ieee.org/document/6181079) （2012 年 1 月） 
- ：bar_chart： [Dealing with virtualization packers](http://2008.caro.org/downloads/boris_lau_virtualization_obfs.pdf) （2008 年 5 月） 
- ：笔记本： [Denial-of-service attacks on host-based generic unpackers](https://link.springer.com/chapter/10.1007/978-3-642-11145-7_19) （2009 年 12 月） 
- ：砂浆板： [Deobfuscation of packed and virtualization-obfuscation protected binaries](https://repository.arizona.edu/handle/10150/202716) （2011 年 6 月） 
- ：笔记本： [Design and development of a new scanning core engine for malware detection](https://ieeexplore.ieee.org/document/6388212) （2012 年 10 月） 
- ：笔记本： [Design and performance evaluation of binary code packing for protecting embedded software against reverse engineering](https://ieeexplore.ieee.org/document/5479571) （2010 年 5 月） 
- ：笔记本： [Detecting packed executable file: Supervised or anomaly detection method?](https://ieeexplore.ieee.org/abstract/document/7784628) （2016 年 8 月） 
- ：报纸： [Detecting packed executables based on raw binary data](https://www.semanticscholar.org/paper/DETECTING-PACKED-EXECUTABLES-BASED-ON-RAW-BINARY-Nataraja-Jacobb/53371424fb79de29a096e563b07fcae432f4d201) （2010 年 6 月） 
- ：笔记本： [Detecting packed executables using steganalysis](https://ieeexplore.ieee.org/document/7018361) （2014 年 12 月） 
- ：砂浆板： [Detecting packed PE files: Executable file analysis for the Windows operating system](https://uia.brage.unit.no/uia-xmlui/handle/11250/2823655) （2021 年 6 月）：明星：
- ：笔记本： [Detecting traditional packers, decisively](https://link.springer.com/chapter/10.1007/978-3-642-41284-4_10) （2013 年 10 月） 
- ：笔记本： [Detection of metamorphic malware packers using multilayered LSTM networks](https://www.springerprofessional.de/en/detection-of-metamorphic-malware-packers-using-multilayered-lstm/18635334) （2020 年 11 月）:star:
- ：笔记本： [Detection of packed executables using support vector machines](https://ieeexplore.ieee.org/document/6016774) （2011 年 7 月） 
- ：笔记本： [Detection of packed malware](https://doi.org/10.1145/2490428.2490431) （2012 年 8 月） 
- ：笔记本： [DexHunter: Toward extracting hidden code from packed Android applications](https://link.springer.com/chapter/10.1007/978-3-319-24177-7_15) （2015 年 9 月） 
- ：笔记本： [Disabling anti-debugging techniques for unpacking system in user-level debugger](https://ieeexplore.ieee.org/document/8939719) （2019 年 10 月）：明星：
- ：笔记本： [Dynamic binary instrumentation for deobfuscation and unpacking](https://hal.inria.fr/inria-00431666) （2009 年 11 月） 
- ：笔记本： [Dynamic classification of packing algorithms for inspecting executables using entropy analysis](https://ieeexplore.ieee.org/document/6703681) （2013 年 10 月） 
- ：报纸： [Effective, efficient, and robust packing detection and classification](http://www.sciencedirect.com/science/article/pii/S0167404818311040) （2019 年 5 月）：star2：：star2：：star2：
- ：笔记本： [Efficient and automatic instrumentation for packed binaries](https://link.springer.com/chapter/10.1007/978-3-642-02617-1_32) （2009 年 6 月） 
- ：报纸： [Efficient automatic original entry point detection](https://jise.iis.sinica.edu.tw/JISESearch/pages/View/PaperView.jsf?keyId=169_2256) （2019 年 1 月）：明星：
- ：报纸： [An efficient block-discriminant identification of packed malware](https://link.springer.com/article/10.1007%2Fs12046-015-0399-x) （2015 年 8 月） 
- ：笔记本： [Efficient malware packer identification using support vector machines with spectrum kernel](https://ieeexplore.ieee.org/document/6621654) （2013 年 7 月） 
- ：报纸： [Efficient SVM based packer identification with binary diffing measures](https://ieeexplore.ieee.org/document/8754440/) （2019 年 7 月）：明星：
- ：报纸： [ELF-Miner: Using structural knowledge and data mining methods to detect new (Linux) malicious executables](https://dl.acm.org/doi/10.5555/2150963.2150968) （2012 年 3 月） 
- ：报纸： [EMBER: An open dataset for training static PE malware machine learning models](https://arxiv.org/abs/1804.04637) （2018 年 4 月）：明星：
- ：笔记本： [An empirical evaluation of an unpacking method implemented with dynamic binary instrumentation](https://www.jstage.jst.go.jp/article/transinf/E94.D/9/E94.D_9_1778/_article) （2011 年 9 月） 
- ：笔记本： [Encoded executable file detection technique via executable file header analysis](https://www.earticle.net/Article/A105986) （2009 年 4 月） 
- ：笔记本： [Entropy analysis to classify unknown packing algorithms for malware detection](https://link.springer.com/article/10.1007/s10207-016-0330-4) （2016 年 5 月）：明星：
- ：笔记本： [ESCAPE: Entropy score analysis of packed executable](https://dl.acm.org/doi/10.1145/2388576.2388607) （2012 年 10 月） 
- ：笔记本： [Ether: Malware analysis via hardware virtualization extensions](https://dl.acm.org/doi/10.1145/1455770.1455779) （2008 年 10 月） 
- ：笔记本： [Eureka: A framework for enabling static malware analysis](https://link.springer.com/chapter/10.1007%2F978-3-540-88313-5_31) （2008 年 10 月） 
- ：笔记本： [Evading machine learning malware detection](https://www.blackhat.com/us-17/briefings.html#bot-vs.-bot-for-evading-machine-learning-malware-detection) （2017 年 7 月） 
- ：笔记本： [Experimental comparison of machine learning models in malware packing detection](https://ieeexplore.ieee.org/document/9237007) （2020 年 9 月）:star:
- ：笔记本： [An experimental study on identifying obfuscation techniques in packer](https://docplayer.net/63501103-An-experimental-study-on-identifying-obfuscation-techniques-in-packer.html) （2016 年 6 月） 
- ：砂浆板： [Experimental toolkit for studying executable packing - Analysis of the state-of-the-art packing detection techniques](https://dial.uclouvain.be/memoire/ucl/en/object/thesis%3A35692) （2022 年 6 月）：明星：
- ：笔记本： [A fast flowgraph based classification system for packed and polymorphic malware on the endhost](https://ieeexplore.ieee.org/document/5474800/) （2010 年 4 月） 
- ：笔记本： [A fast randomness test that preserves local detail](https://researchrepository.rmit.edu.au/esploro/outputs/conferenceProceeding/A-fast-randomness-test-that-preserves-local-detail/9921861589001341) （2008 年 10 月） 
- ：笔记本： [Feature set reduction for the detection of packed executables](https://ieeexplore.ieee.org/document/6912767) （2014 年 6 月） 
- ：报纸： [File packing from the malware perspective: Techniques, analysis approaches, and directions for enhancements](https://dl.acm.org/doi/10.1145/3530810) （2022 年 4 月）：明星：
- ：笔记本： [A fine-grained classification approach for the packed malicious code](https://link.springer.com/chapter/10.1007/978-3-642-34129-8_49) （2012 年 10 月） 
- ：笔记本： [A generic approach to automatic deobfuscation of executable code](https://ieeexplore.ieee.org/document/7163054) （2015 年 5 月）：明星：
- ：报纸： [Generic packing detection using several complexity analysis for accurate malware detection](https://www.researchgate.net/publication/332594129_Generic_Packing_Detection_using_Several_Complexity_Analysis_for_Accurate_Malware_Detection?channel=doi&linkId=5cbf828b299bf120977ac78a&showFulltext=true) （2014年1月） 
- ：笔记本： [Generic unpacker of executable files](https://www.semanticscholar.org/paper/Generic-Unpacker-of-Executable-Files-Milkovi/413321c5a473d59c18e861c1478cd44f88142275) （2015 年 4 月） 
- ：笔记本： [Generic unpacking method based on detecting original entry point](https://link.springer.com/chapter/10.1007/978-3-642-42054-2_74) （2013年11月） 
- ：报纸： [Generic unpacking of self-modifying, aggressive, packed binary programs](https://arxiv.org/abs/0905.4581) （2009 年 5 月） 
- ：笔记本： [Generic unpacking techniques](https://ieeexplore.ieee.org/document/4909168) （2009 年 2 月） 
- ：笔记本： [Generic unpacking using entropy analysis](https://ieeexplore.ieee.org/document/5665789) （2010 年 10 月） 
- ：笔记本： [Gunpack: Un outil générique d'unpacking de malwares](https://www.sstic.org/2016/presentation/gunpack/) （2016 年 6 月） 
- ：报纸： [Hashing-based encryption and anti-debugger support for packing multiple files into single executable](http://ijarcs.info/index.php/Ijarcs/article/view/5526/4622) （2018 年 2 月） 
- ：笔记本： [A heuristic approach for detection of obfuscated malware](https://ieeexplore.ieee.org/document/5137328) （2009 年 6 月） 
- ：报纸： [A heuristics-based static analysis approach for detecting packed PE binaries](http://dx.doi.org/10.14257/ijsia.2013.7.5.24) （2013 年 10 月） 
- ：笔记本： [An implementation of a generic unpacking method on Bochs Emulator](https://www.semanticscholar.org/paper/An-Implementation-of-a-Generic-Unpacking-Method-on-HyungChanKim-Daisuke/d5c947520815105231673f1b87af57ed6abd379c) （2009 年 9 月） 
- ：笔记本： [Information theoretic method for classification of packed and encoded files](https://dl.acm.org/doi/10.1145/2799979.2800015) （2015 年 9 月） 
- ：笔记本： [Instructions-based detection of sophisticated obfuscation and packing](https://ieeexplore.ieee.org/document/6956729) （2014 年 10 月） 
- ：报纸： [A learning model to detect maliciousness of portable executable using integrated feature set](https://www.sciencedirect.com/science/article/pii/S1319157817300149) （2017 年 1 月） 
- ：笔记本： [Limits of static analysis for malware detection](https://ieeexplore.ieee.org/document/4413008) （2007 年 12 月） 
- ：砂浆板： [Maitland: Analysis of packed and encrypted malware via paravirtualization extensions](https://dspace.library.uvic.ca/handle/1828/3866) （2012 年 6 月） 
- ：笔记本： [Mal-EVE: Static detection model for evasive malware](https://ieeexplore.ieee.org/document/7497952) （2015 年 8 月） 
- ：报纸： [Mal-flux: Rendering hidden code of packed binary executable](http://www.sciencedirect.com/science/article/pii/S1742287618303736) （2019 年 3 月）：明星：
- ：报纸： [Mal-XT: Higher accuracy hidden-code extraction of packed binary executable](https://iopscience.iop.org/article/10.1088/1757-899X/453/1/012001) （2018 年 11 月） 
- ：报纸： [Mal-xtract: Hidden code extraction using memory analysis](https://doi.org/10.1088%2F1742-6596%2F801%2F1%2F012058) （2017 年 1 月） 
- ：报纸： [Malware analysis using multiple API sequence mining control flow graph](https://arxiv.org/abs/1707.02691) （2017 年 7 月） 
- ：报纸： [Malware analysis using visualized images and entropy graphs](https://link.springer.com/article/10.1007%2Fs10207-014-0242-0) （2015 年 2 月） 
- ：笔记本： [Malware images: Visualization and automatic classification](https://doi.org/10.1145/2016904.2016908) （2011 年 7 月） 
- ：笔记本： [Malware obfuscation techniques: A brief survey](https://ieeexplore.ieee.org/document/5633410) （2010 年 11 月） 
- ：笔记本： [Malware obfuscation through evolutionary packers](https://doi.org/10.1145/2739482.2764940) （2015 年 7 月） 
- ：报纸： [Malwise - An effective and efficient classification system for packed and polymorphic malware](https://ieeexplore.ieee.org/document/6171162) （2013年六月） 
- ：笔记本： [McBoost: Boosting scalability in malware collection and analysis using statistical classification of executables](https://ieeexplore.ieee.org/document/4721567) （2008 年 12 月） 
- ：笔记本： [Memory behavior-based automatic malware unpacking in stealth debugging environment](https://ieeexplore.ieee.org/document/5665794) （2010 年 10 月） 
- ：笔记本： [Metadata recovery from obfuscated programs using machine learning](https://doi.org/10.1145/3015135.3015136) （2016 年 12 月） 
- ：笔记本： [Modern linux malware exposed](https://www.eurecom.fr/fr/publication/5584) （2018 年 6 月） 
- ：笔记本： [MutantX-S: Scalable malware clustering based on static features](https://www.usenix.org/conference/atc13/technical-sessions/presentation/hu) （2013年六月） 
- ：笔记本： [The new signature generation method based on an unpacking algorithm and procedure for a packer detection](https://www.earticle.net/Article/A147420) （2011 年 2 月） 
- ：笔记本： [Obfuscation-resilient executable payload extraction from packed malware](https://www.usenix.org/conference/usenixsecurity21/presentation/cheng-binlin) （2021 年 8 月）：明星：
- ：报纸： [Obfuscation: The hidden malware](https://ieeexplore.ieee.org/document/5975134) （2011 年 8 月） 
- ：笔记本： [Obfuscation: Where are we in anti-DSE protections? (a first attempt)](https://doi.org/10.1145/3371307.3371309) （2019 年 12 月）:star:
- ：笔记本： [OmniUnpack: Fast, generic, and safe unpacking of malware](https://ieeexplore.ieee.org/document/4413009) （2007 年 12 月） 
- ：笔记本： [On the (Im)possibility of obfuscating programs](https://link.springer.com/chapter/10.1007/3-540-44647-8_1) （2001 年 8 月） 
- ：报纸： [On the adoption of anomaly detection for packed executable filtering](https://www.sciencedirect.com/science/article/pii/S0167404814000522?via%3Dihub) （2014 年 6 月） 
- ：笔记本： [OPEM: A static-dynamic approach for machine-learning-based malware detection](https://link.springer.com/chapter/10.1007/978-3-642-33018-6_28) （2012 年 9 月） 
- ：报纸： [An original entry point detection method with candidate-sorting for more effective generic unpacking](https://www.jstage.jst.go.jp/article/transinf/E98.D/4/E98.D_2014EDP7268/_article) （2015 年 1 月） 
- ：报纸： [Packed malware detection using entropy related analysis: A survey](https://api.semanticscholar.org/CorpusID:212493886) （2015 年 11 月） 
- ：报纸： [Packed malware variants detection using deep belief networks](https://doi.org/10.1051/matecconf/202030902002) （2020 年 3 月）：明星：
- ：笔记本： [Packed PE file detection for malware forensics](https://ieeexplore.ieee.org/document/5404211) （2009 年 12 月） 
- ：报纸： [Packer analysis report debugging and unpacking the NsPack 3.4 and 3.7 packer](https://www.sans.org/reading-room/whitepapers/malicious/packer-analysis-report-debugging-unpacking-nspack-34-37-packer-33428) （2010 年 6 月） 
- ：笔记本： [Packer classifier based on PE header information](https://dl.acm.org/doi/10.1145/2746194.2746213) （2015 年 4 月） 
- ：报纸： [Packer detection for multi-layer executables using entropy analysis](https://www.mdpi.com/1099-4300/19/3/125) （2017 年 3 月）：明星：
- ：笔记本： [Packer identification based on metadata signature](https://dl.acm.org/doi/10.1145/3151137.3160687) （2017 年 12 月） 
- ：笔记本： [Packer identification method based on byte sequences](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.5082) （2018 年 11 月）：明星：
- ：报纸： [Packer identification using byte plot and Markov plot](https://link.springer.com/article/10.1007/s11416-015-0249-8) （2015 年 9 月）：明星：
- ：笔记本： [Packer identification using hidden Markov model](https://link.springer.com/chapter/10.1007/978-3-319-69456-6_8) （2017 年 11 月） 
- ：砂浆板： [Packer-complexity analysis in PANDA](https://webthesis.biblio.polito.it/7519/) （2018 年 1 月） 
- ：砂浆板： [Packing detection and classification relying on machine learning to stop malware propagation](https://theses.hal.science/tel-03781104) （2021 年 12 月）：明星：
- ：砂浆板： [Pandora's Bochs: Automatic unpacking of malware](https://www.researchgate.net/publication/268355151_Pandora%27s_Bochs_Automatic_Unpacking_of_Malware) （2008 年 1 月） 
- ：笔记本： [Pattern recognition techniques for the classification of malware packers](https://link.springer.com/chapter/10.1007/978-3-642-14081-5_23) （2010 年 7 月） 
- ：报纸： [PE file features in detection of packed executables](http://www.ijcte.org/show-42-485-1.html) （2012 年 1 月） 
- ：笔记本： [PE file header analysis-based packed PE file detection technique (PHAD)](https://ieeexplore.ieee.org/document/4654055) （2008 年 10 月） 
- ：笔记本： [PE-Miner: Mining structural information to detect malicious executables in realtime](https://link.springer.com/chapter/10.1007/978-3-642-04342-0_7) （2009 年 9 月） 
- ：笔记本： [PE-Probe: Leveraging packer detection and structural information to detect malicious portable executables](https://www.semanticscholar.org/paper/PE-Probe%3A-Leveraging-Packer-Detection-and-to-Detect-Shafiq-Tabish/9811ec751f2b5bb41ee46c0ee2a3b6eccc39bb9a) （2009 年 6 月） 
- ：笔记本： [PEAL - Packed executable analysis](https://link.springer.com/chapter/10.1007/978-3-642-29280-4_28) （2012 年 1 月） 
- ：报纸： [PEzoNG: Advanced packer for automated evasion on Windows](https://doi.org/10.1007/s11416-022-00417-2) （2022 年 12 月） 
- ：笔记本： [PolyPack: An automated online packing service for optimal antivirus evasion](https://dl.acm.org/doi/10.5555/1855876.1855885) （2009 年 8 月） 
- ：笔记本： [PolyUnpack: Automating the hidden-code extraction of unpack-executing malware](https://ieeexplore.ieee.org/document/4041175) （2006 年 12 月）：明星：：明星：
- ：笔记本： [Preprocessing of binary executable files towards retargetable decompilation](https://www.fit.vut.cz/research/publication/10200) （2013 年 7 月） 
- ：笔记本： [Prevalence and impact of low-entropy packing schemes in the malware ecosystem](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24297.pdf) （2020 年 2 月）：明星：
- ：bar_chart： [Qualitative and quantitative evaluation of software packers](http://webdiis.unizar.es/~ricardo/files/slides/industrial/slides_NcN-15.pdf) （2015 年 12 月） 
- ：笔记本： [RAMBO: Run-Time packer analysis with multiple branch observation](https://link.springer.com/chapter/10.1007/978-3-319-40667-1_10) （2016 年 7 月） 
- ：砂浆板： [REFORM: A framework for malware packer analysis using information theory and statistical methods](https://researchrepository.rmit.edu.au/view/delivery/61RMIT_INST/12246783310001341/13248377300001341) （2010 年 4 月） 
- ：笔记本： [Renovo: A hidden code extractor for packed executables](https://dl.acm.org/doi/10.1145/1314389.1314399) （2007 年 11 月）：明星：
- ：笔记本： [RePEconstruct: Reconstructing binaries with self-modifying code and import address table destruction](https://ieeexplore.ieee.org/document/7888727) （2016 年 10 月） 
- :notebook: RePEF — 用于恢复打包的可执行文件以进行恶意软件分析的系统（2011 年 7 月） 
- ：笔记本： [Research and implementation of compression shell unpacking technology for PE file](https://ieeexplore.ieee.org/document/5231651) （2009 年 5 月） 
- ：报纸： [Research and implementation of packing technology for PE files](https://www.semanticscholar.org/paper/Research-and-Implementation-of-Packing-Technology-Senlin/c973f26f2ac8c1861cc5d714f0d579135fa1491e) （2013 年 1 月） 
- ：笔记本： [Research of software information hiding algorithm based on packing technology](https://link.springer.com/chapter/10.1007/978-981-15-8086-4_8) （2020 年 9 月）:star:
- ：报纸： [Revealing packed malware](https://ieeexplore.ieee.org/document/4639028) （2008 年 9 月） 
- ：笔记本： [Reverse engineering self-modifying code: Unpacker extraction](https://ieeexplore.ieee.org/document/5645447) （2010 年 10 月） 
- ：砂浆板： [Robust static analysis of portable executable malware](https://repo.zenk-security.com/Virus-Infections-Detections-Preventions/Robust%20Static%20Analysis%20ofPortable%20ExecutableMalware.pdf) （2014 年 12 月） 
- ：bar_chart： [Runtime packers testing experiences](https://docs.google.com/a/caro.org/viewer?a=v&pid=sites&srcid=Y2Fyby5vcmd8Y2Fyby13b3Jrc2hvcC0yMDA4fGd4OjZkNzk3MmI2YjZlMWMxZGI) （2008 年 5 月） 
- ：笔记本： [SATURN - Software deobfuscation framework based on LLVM](https://dl.acm.org/doi/10.1145/3338503.3357721) （2019 年 11 月）:star:
- ：报纸： [SCORE: Source code optimization & reconstruction](https://ieeexplore.ieee.org/document/9139493) （2020 年 7 月）：明星：
- ：笔记本： [SE-PAC: A self-evolving packer classifier against rapid packers evolution](https://dl.acm.org/doi/10.1145/3422337.3447848) （2021 年 4 月）：明星：
- ：报纸： [Secure and advanced unpacking using computer emulation](https://link.springer.com/article/10.1007%2Fs11416-007-0046-0) （2007 年 8 月） 
- ：笔记本： [Semi-supervised learning for packed executable detection](https://ieeexplore.ieee.org/document/6060027) （2011 年 9 月） 
- ：笔记本： [Semi-supervised learning for unknown malware detection](https://link.springer.com/chapter/10.1007/978-3-642-19934-9_53) （2011 年 4 月） 
- ：报纸： [Sensitive system calls based packed malware variants detection using principal component initialized multilayers neural networks](https://cybersecurity.springeropen.com/articles/10.1186/s42400-018-0010-y) （2018 年 9 月）：明星：
- ：笔记本： [SoK: Deep packer inspection: A longitudinal study of the complexity of run-time packers](https://ieeexplore.ieee.org/document/7163053) （2015 年 5 月）：明星：：明星：
- ：笔记本： [SPADE: Signature based packer detection](https://dl.acm.org/doi/10.1145/2490428.2490442) （2012 年 8 月） 
- ：报纸： [Standards and policies on packer use](http://pferrie.epizy.com/papers/con2010.htm) （2010 年 10 月） 
- ：笔记本： [Static analysis of executables to detect malicious patterns](https://dl.acm.org/doi/10.5555/1251353.1251365) （2003 年 8 月） 
- ：报纸： [Static malware detection & subterfuge: Quantifying the robustness of machine learning and current anti-virus](http://arxiv.org/abs/1806.04773) （2018 年 6 月）：明星：
- ：笔记本： [A static, packer-agnostic filter to detect similar malware samples](https://link.springer.com/chapter/10.1007/978-3-642-37300-8_6) （2012 年 7 月） 
- ：笔记本： [Structural feature based anomaly detection for packed executable identification](https://link.springer.com/chapter/10.1007%2F978-3-642-21323-6_29) （2011 年 6 月） 
- ：笔记本： [The study of evasion of packed PE from static detection](https://ieeexplore.ieee.org/document/6280206) （2012 年 6 月） 
- ：笔记本： [A study of the packer problem and its solutions](https://link.springer.com/chapter/10.1007/978-3-540-87403-4_6) （2008 年 9 月） 
- :notebook: 基于机器学习的恶意软件检测和分类技术调查（2021 年 9 月）:star:
- :newspaper: 恶意软件分析技术调查：静态、动态、混合和内存分析（2018 年 9 月） 
- ：笔记本： [Survey on malware evasion techniques: State of the art and challenges](https://ieeexplore.ieee.org/abstract/document/6174775) （2012 年 2 月） 
- ：笔记本： [Syntia: Synthesizing the semantics of obfuscated code](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko) （2017 年 8 月）：明星：
- ：笔记本： [Things you may not know about Android (Un) packers: A systematic study based on whole-system emulation.](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_04A-4_Duan_paper.pdf) （2018 年 2 月） 
- ：笔记本： [Thwarting real-time dynamic unpacking](https://dl.acm.org/doi/10.1145/1972551.1972556) （2011 年 1 月） 
- ：笔记本： [A token strengthened encryption packer to prevent reverse engineering PE files](https://ieeexplore.ieee.org/document/7280213) （2015 年 1 月） 
- ：笔记本： [Toward generic unpacking techniques for malware analysis with quantification of code revelation](https://www.researchgate.net/publication/255608911_Toward_Generic_Unpacking_Techniques_for_Malware_Analysis_with_Quantification_of_Code_Revelation) （2009 年 8 月） 
- ：笔记本： [Towards paving the way for large-scale Windows malware analysis: Generic binary unpacking with orders-of-magnitude performance boost](https://dl.acm.org/doi/10.1145/3243734.3243771) （2018 年 10 月）：明星：
- ：报纸： [Two techniques for detecting packed portable executable files](https://ieeexplore.ieee.org/document/6636333) （2013年六月） 
- ：笔记本： [Unconditional self-modifying code elimination with dynamic compiler optimizations](https://ieeexplore.ieee.org/document/5665795) （2010 年 10 月） 
- ：笔记本： [Understanding linux malware](https://ieeexplore.ieee.org/document/8418602) （2018 年 5 月）：明星：
- ：笔记本： [A unpacking and reconstruction system-agunpacker](https://ieeexplore.ieee.org/document/5374512) (January 2009) 
- ：砂浆板： [Unpacking framework for packed malicious executables](https://repositorio-aberto.up.pt/bitstream/10216/68815/2/25935.pdf) （2013 年 7 月） 
- ：报纸： [Unpacking techniques and tools in malware analysis](https://www.scientific.net/AMM.198-199.343) （2012 年 9 月） 
- ：笔记本： [Unpacking virtualization obfuscators](https://dl.acm.org/doi/10.5555/1855876.1855877) （2009 年 8 月） 
- ：报纸： [UnThemida: Commercial obfuscation technique analysis with a fully obfuscated program](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.2622) （2018 年 7 月）：明星：
- ：报纸： [Using entropy analysis to find encrypted and packed malware](https://ieeexplore.ieee.org/document/4140989) （2007 年 3 月） 
- ：笔记本： [VMAttack: Deobfuscating virtualization-based packed binaries](https://dl.acm.org/doi/10.1145/3098954.3098995) （2017 年 8 月） 
- ：笔记本： [VMRe: A reverse framework of virtual machine protection packed binaries](https://ieeexplore.ieee.org/document/8923473) （2019 年 6 月）：明星：
- ：bar_chart： [WaveAtlas: Surfing through the landscape of current malware packers](https://www.virusbulletin.com/virusbulletin/2016/12/vb2015-paper-waveatlas-surfing-through-landscape-current-malware-packers/) （2015 年 9 月） 
- ：笔记本： [When malware is packin' heat; limits of machine learning classifiers based on static analysis features](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24310.pdf) （2020 年 1 月）：明星：
- ：报纸： [WYSINWYX: What you see is not what you execute](https://dl.acm.org/doi/10.1145/1749608.1749612) （2010 年 8 月） 
- ：报纸： [x64Unpack: Hybrid emulation unpacker for 64-bit Windows Environments and detailed analysis results on VMProtect 3.4](https://ieeexplore.ieee.org/document/9139515) （2020 年 7 月）：明星：

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :bookmark_tabs: Datasets

- [Contagio](https://contagiodump.blogspot.com) - Contagio 是最新的恶意软件样本、威胁、观察和分析的集合.
- [CyberCrime](https://cybercrime-tracker.net/vx.php) - C² 跟踪和恶意软件数据库.
- [Dataset of Packed ELF](https://github.com/dhondta/dataset-packed-elf) - 打包的 ELF 样本数据集.
- [Dataset of Packed PE](https://github.com/dhondta/dataset-packed-pe) - 原始数据集 PackingData 的净化版本，从 Notpacked 文件夹中删除打包样本，但也删除打包文件夹中未能打包的样本（与原始解压可执行文件具有相同的哈希值）.
- [Ember](https://github.com/elastic/ember) - 从 PE 文件中收集功能，作为研究人员的基准数据集.
- [FFRI Dataset Scripts](https://github.com/FFRI/ffridataset-scripts) - 制作像 FFRI 数据集这样的数据集.
- [MaleX](https://github.com/Mayachitra-Inc/MaleX) - 为恶意软件研究人员精选的恶意软件和良性 Windows 可执行样本数据集，包含 1,044,394 个 Windows 可执行二进制文件和相应的图像表示，其中 864,669 个标记为恶意软件，179,725 个标记为良性.
- [Malfease](https://web.archive.org/web/20141221153307/http://malfease.oarci.net) - 约 5,000 个打包恶意软件样本的数据集.
- [Malheur](https://www.sec.cs.tu-bs.de/data/malheur) - 包含恶意软件 (malware) 的记录行为，并已用于开发分类和聚类恶意软件行为的方法（参见 2011 年的 JCS 文章）.
- [Malicia](http://malicia-project.com/dataset.html) - 2013 年 11 个月内从 500 个路过式下载服务器收集的 11,688 个恶意 PE 文件的数据集（已停用）.
- [MalShare](https://malshare.com) - 免费的恶意软件存储库，使研究人员可以访问样本、恶意源和 Yara 结果.
- [MalwareBazaar](https://bazaar.abuse.ch/browse) - 由 abuse.ch 运营的项目旨在收集和共享恶意软件样本，帮助 IT 安全研究人员和威胁分析师保护他们的支持者和客户免受网络威胁.
- [MalwareGallery](https://github.com/BaRRaKudaRain/MalwareGallery) - Internet 中的另一个恶意软件集合.
- [MalwareTips](https://malwaretips.com/) - MalwareTips 是一个社区驱动的平台，提供有关恶意软件和网络威胁的最新信息和资源.
- [OARC Malware Dataset](https://www.dns-oarc.net) - 从 2005 年 9 月到 2006 年 1 月通过邮件陷阱、用户提交、蜜罐和 OARC 汇总的其他来源在野外捕获的 3,467 个样本的半公开数据集，可根据要求提供给合格的学术和行业研究人员.
- [Open Malware Project](https://web.archive.org/web/20190116100735/http://www.offensivecomputing.net/) - 在线收集恶意软件样本（以前称为 Offensive Computing）.
- [PackingData](https://github.com/chesvectain/PackingData) - 带有样本 PE 文件的原始数据集，其中包含各种打包程序，包括 ASPack、BeRoEXEPacker、exe32pack、eXpressor、FSG、JDPack、MEW、Molebox、MPRESS、Neolite、NSPack、Pckman、PECompact、PEtite、RLPack、UPX、WinUpack，尤达的地穴和尤达的保护者.
- [Packware](https://github.com/ucsb-seclab/packware) - 重现论文“When Malware is Packing Heat”中的实验所需的数据集和代码.
- [RCE Lab](https://github.com/apuromafo/RCE_Lab)  - Crackme、keygenme、serialme；  “tuts4you”文件夹包含许多打包的二进制文件.
- [Runtime Packers Testset](https://www.researchgate.net/publication/268030543_Runtime_Packers_The_Hidden_Problem) - 10 个常见恶意软件文件的数据集，包含约 40 个不同的运行时打包程序，有 500 多个版本和选项，总共约 5,000 个样本.
- [SAC](https://www.sac.sk/files.php?d=7&l=)  - 斯洛伐克防病毒中心，AVIR 和 ESET 公司的非商业项目； 包含打包器、检测器和解包器.
- [SOREL](https://github.com/sophos-ai/SOREL-20M) - Sophos-ReversingLabs 2000 万数据集.
- [theZoo](https://github.com/ytisf/theZoo) - 创建的项目是为了使恶意软件分析的可能性向公众开放和可用.
- [ViruSign](https://www.virusign.com) - 另一个在线恶意软件数据库.
- [VirusShare](https://virusshare.com) - 包含超过 4400 万个样本的病毒在线数据库.
- [VX Heaven](https://web.archive.org/web/20170817143838/http://vxheaven.org/) - 专门提供有关计算机病毒信息的站点.
- [VX Underground](https://vx-underground.org/samples.html) - 基于 PL-CERT 的开源 MWDB python 应用程序持有一个恶意软件数据库，其中包含 2010 年的每个 APT 样本和超过 750 万个恶意二进制文件.
- [VXvault](http://vxvault.net/ViriList.php) - 在线恶意软件数据库.
- [WildList](http://www.wildlist.org/CurrentList.txt) - 合作列出被安全专家报告为在野的恶意软件.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :package: Packers

### After 2010

- [Alienyze](https://alienyze.com) - Windows 32 位可执行文件的高级软件保护和安全性.
- [Alternate EXE Packer](https://www.alternate-tools.com/pages/c_exepacker.php) - 可执行文件（EXE 类型）或依赖于 UPX 3.96 的 DLL 的压缩工具.
- [Amber](https://github.com/EgeBalci/amber/releases) - 与位置无关（反射）的 PE 加载器，可在内存中执行本机 PE 文件（EXE、DLL、SYS）.
- [Andromeda](https://blog.morphisec.com/andromeda-tactics-analyzed) - 恶意软件活动中使用的自定义打包程序使用 RunPE 技术来规避 AV 缓解方法.
- [APKProtect](https://sourceforge.net/projects/apkprotect) - 支持Java和C++的APK加密和外壳保护.
- [Armadillo](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/protectors/win/armd252b2.zip) - 结合了用于保护 PE 文件的许可证管理器和包装器系统.
- [ASPack](http://www.aspack.com/aspack.html) - 为提供 Win32 EXE 文件打包和保护它们免受非专业逆向工程而创建的高级解决方案.
- [ASProtect 32](http://www.aspack.com/asprotect32.html) - 专为软件开发人员设计的多功能 EXE 打包工具，可通过内置的应用程序复制保护系统保护 32 位应用程序.
- [ASProtect 64](http://www.aspack.com/asprotect64.html) - 用于保护 Windows 的 64 位应用程序和 .NET 应用程序免受未经授权的使用、工业和家庭复制、专业黑客攻击以及对通过 Internet 和任何物理媒体分发的软件产品进行分析的工具.
- [AutoIT](https://www.autoitscript.com/site) - 合法的可执行加密服务.
- [AxProtector](https://www.wibu.com/us/products/protection-suite/axprotector.html) - 对您要保护的完整软件进行加密，并使用安全外壳对其进行屏蔽，AxEngine，然后将最佳的反调试和反反汇编方法注入到您的软件中.
- [BangCle](https://github.com/woxihuannisja/Bangcle) - 使用第二代Android Hardening Protection的保护工具，从内存中动态加载加密的DEX文件.
- [Bero](https://blog.rosseaux.net/page/875fbe6549aa072b5ee0ac9cefff4827/BeRoEXEPacker) - 用于 32 位 Windows 可执行文件的 Bero EXE Packer (BEP).
- [BIN-crypter](https://www.autoitscript.com/forum/topic/129383-bin-crypter/) - EXE 保护软件免受破解者和反编译器的侵害.
- [BoxedApp Packer](https://www.boxedapp.com/boxedapppacker)
- [Code Virtualizer](https://www.oreans.com/CodeVirtualizer.php) - Code Virtualizer 是一个强大的代码混淆系统，适用于 Windows、Linux 和 macOS 应用程序，可帮助开发人员保护其敏感代码区域免受基于代码虚拟化的非常强大的混淆代码的逆向工程.
- [ConfuserEx](https://github.com/mkaring/ConfuserEx) - .NET 应用程序的开源免费保护程序.
- [Crinkler](https://github.com/runestubbe/Crinkler) - 用于 Windows 的压缩链接器，专门针对大小只有几千字节的可执行文件.
- [DarkCrypt](https://totalcmd.net/plugring/darkcrypttc.html) - 简单而强大的 Total Commander 插件，用于使用 100 种算法和 5 种模式进行文件加密.
- [DexGuard](https://www.guardsquare.com/en/products/dexguard) - 用于保护移动应用程序的 Android 应用程序混淆和安全协议.
- [DexProtector](https://dexprotector.com/) - 多层 RASP 解决方案，保护您的 Android 和 iOS 应用程序免受静态和动态分析、非法使用和篡改.
- [DotBundle](https://web.archive.org/web/20160508074421/http://www.dotbundle.com:80/download.html) - 用于压缩、加密广告密码保护 .NET 应用程序或嵌入 .NET 库的 GUI 工具.
- [DotNetZ](https://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/NETZ.shtml) - 用 C 语言编写的简单、轻量级的命令行软件，允许您压缩和打包 Microsoft .NET Framework 可执行文件.
- [ElecKey](https://www.sciensoft.com) - 一套软件和工具，为软件保护、复制保护和许可证管理提供完整的解决方案.
- [ELFCrypt](https://github.com/droberson/ELFcrypt) - 使用 RC4 加密的简单 ELF 加密器.
- [ELFuck](https://github.com/timhsutw/elfuck) - 来自 sd 的 sk2 的 i386 原始版本的 ELF 打包器.
- [Enigma Protector](https://www.enigmaprotector.com) - 用于可执行文件许可和保护的专业系统.
- [Enigma Virtual Box](https://www.enigmaprotector.com/en/aboutvb.html) - 适用于 Windows 的应用程序虚拟化系统.
- [Eronona-Packer](https://github.com/Eronana/packer) - 这是 win32 下的 exe 加壳程序.
- [EXE Bundle](https://www.webtoolmaster.com/exebundle.htm) - 将应用程序文件捆绑到单个 PE32 文件中.
- [EXE Stealth](http://www.webtoolmaster.com/packer.htm) - 具有压缩和加密多态技术的PE文件防破解保护和许可工具.
- [Ezuri](https://github.com/guitmz/ezuri/blob/master/ezuri.go) - 一个简单的 Linux ELF 运行时加密器.
- [GzExe](https://git.savannah.gnu.org/cgit/gzip.git) - 允许将可执行文件压缩为 shell 脚本的实用程序.
- [hXOR-Packer](https://github.com/rurararura/hXOR-Packer) - 具有霍夫曼压缩和 XOR 加密的 PE 加壳器.
- [LIAPP](https://liapp.lockincomp.com) - 最简单、最强大的移动应用程序安全解决方案.
- [LM-X License Manager](https://www.x-formation.com/lm-x-license-manager) - LM-X License Manager 通过实施各种级别的安全性、节省时间和降低业务风险，让您保护您的产品免遭盗版.
- [m0dern_p4cker](https://github.com/n4sm/m0dern_p4cker) - 只是一个用于 elf 二进制文件的现代打包器（仅适用于 linux 可执行文件）.
- [MidgetPack](https://github.com/arisada/midgetpack) - Midgetpack 是用于 ELF 二进制文件的二进制打包程序，例如 burneye、upx 或其他工具.
- [MPRESS](https://www.autohotkey.com/mpress/mpress_web.htm) - 压缩（使用 LZMA）并保护 PE、.NET 或 Mach-O 程序免受逆向工程.
- [NetCrypt](https://github.com/friedkiwi/netcrypt) - .NET 可执行文件的概念验证打包程序，旨在提供一个起点来解释运行时打包的基本原则.
- [.netshrink](https://www.pelock.com/products/netshrink) - 使用 LZMA 的 Windows 或 Linux .NET 应用程序可执行文件的可执行压缩器.
- [NPack](http://www.nsdsn.com/english/nspack.zip) - 可以压缩 32 位和 64 位 exe、dll、ocx、scr Windows 程序.
- [Obsidium](http://www.obsidium.de/show.php?home) - 功能丰富的专业软件保护和许可系统，旨在作为一种经济高效且易于实施、可靠且非侵入性的方式来保护您的 32 位和 64 位 Windows 软件应用程序和游戏免遭逆向工程.
- [Origami](https://github.com/dr4k0nia/Origami) - Packer 压缩 .net 程序集，(ab) 使用 PE 格式进行数据存储.
- [Pakkero](https://github.com/89luca89/pakkero) - Pakkero 是一个用 Go 编写的二进制打包程序，用于娱乐和教育目的.
- [Papaw](https://github.com/dimkr/papaw) - 使用 LZMA Zstandard 或 Deflate 压缩的 ELF 可执行文件的许可打包程序.
- [PE-Packer](https://github.com/czs108/PE-Packer) - 用于 Windows 32 位 PE 文件的简单打包程序.
- [PE-Toy](https://github.com/r0ngwe1/petoy) - 一个 PE 文件打包器.
- [PELock](https://www.pelock.com)  - Windows可执行文件的软件保护系统； 保护您的应用程序免遭篡改和逆向工程，并为软件许可证密钥管理提供广泛的支持，包括对计时试用期的支持.
- [PePacker](https://github.com/SamLarenN/PePacker) - 加密 .text 部分的简单 PE 加壳器 我发布了一个简单的 PE 文件加壳器，它加密了 .text 部分并在最后一节的末尾添加了一个解密存根.
- [PEShield](https://webscene.ir/tools/show/PE-SHIELD-0.25) - PE-SHiELD 是一个程序，它加密 32 位 Windows EXE 文件，使它们仍然可执行.
- [PESpin](http://downloads.fyxm.net/PESpin-95477.html)
- [PEtite](https://www.un4seen.com/petite/) - 免费的 Win32 (Windows 95/98/2000/NT/XP/Vista/7/etc) 可执行文件 (EXE/DLL/etc) 压缩器.
- PEzoNG - 自动创建隐形二进制文件的框架，目标是在 Windows 环境中检测率非常低.
- [RapidEXE](https://sourceforge.net/projects/rapidexe) - 将 PHP/Python 脚本转换为独立可执行文件的简单有效的方法.
- [Silent-Packer](https://github.com/SilentVoid13/Silent_Packer) - Silent Packer 是一个用纯 C 语言编写的 ELF / PE 打包器.
- [Simple-PE32-Packer](https://github.com/z3r0d4y5/Simple-PE32-Packer) - 带有 PLib 压缩库的简单 PE32 Packer.
- [SimpleDPack](https://github.com/YuriSizuku/SimpleDpack) - 一个非常简单的Windows EXE 打包工具，用于学习或研究PE 结构.
- [Smart Packer](https://www.smartpacker.nl) - 将 32 位和 64 位应用程序与 DLL、数据文件、第 3 方运行时打包到一个可立即运行的可执行文件中，无需安装或麻烦.
- [theArk](https://github.com/aaaddress1/theArk) - C++ 中的 Windows x86 PE 打包程序.
- [Themida](https://www.oreans.com/themida.php) - 来自 Renovo 论文：Themida 将原始的 x86 指令转换为自己的随机指令集中的虚拟指令，然后在运行时解释这些虚拟指令.
- [UPX](https://upx.github.io/) - 用于可执行文件的 Ultimate Packer.
- [VMPROTECT](https://github.com/eaglx/VMPROTECT) - 使用虚拟机的混淆方法.
- [VMProtect](https://vmpsoft.com/products/vmprotect) - VMProtect 通过在具有非标准架构的虚拟机上执行代码来保护代码，这使得分析和破解软件变得极其困难.
- [Ward](https://github.com/ex0dus-0x/ward) - ELF 打包器的简单实现，它创建用于在内存中加载恶意 ELF 的隐蔽滴管.
- [xorPacker](https://github.com/nqntmqmqmb/xorPacker) - 简单的打包程序处理所有 PE 文件，这些文件使用 XOR 实现对您的 exe 进行加密.
- [ZProtect](http://www.jiami.net) - 重命名元数据实体并支持高级混淆方法，这些方法可以强化保护方案并完全阻止逆向工程.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Between 2000 and 2010

- [20to4](http://20to4.net) - 能够将大约 20k 的最佳代码和数据填充到不到 4k 的可执行压缩器.
- [ACProtect](https://www.yaldex.com/Bestsoft/Utilities/acprotect.htm) - 允许保护 Windows 可执行文件免受盗版的应用程序，使用 RSA 创建和验证注册密钥和解锁代码.
- [AHPack](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/ahpacker01byfeuerraderahteam) - PE 和 PE+ 文件打包器.
- [Application Protector](https://sourceforge.net/projects/balaji/) - 用于保护 Windows 应用程序的工具.
- [AT4RE Protector](https://en.52yma.com/thread-5444-1-1.html) - 用 ASM 编程的非常简单的 PE 文件保护器.
- [AverCryptor](https://web.archive.org/web/20071012084924/http://secnull.org) - 小巧且非常方便的实用程序，旨在加密您可以在其中存储任何私人信息的笔记 - 它有助于隐藏您的感染免受防病毒软件的侵害.
- [BurnEye](https://packetstormsecurity.com/files/29691/burneye-1.0-linux-static.tar.gz.html) - Burneye ELF 加密程序，x86-linux 二进制.
- [ByteBoozer](https://csdb.dk/release/?id=33093) - Commodore 64 可执行打包程序.
- [EXE Guarder](http://www.exeicon.com/exeguarder) - 允许压缩和指定密码通知的 PE 文件许可工具.
- [EXE Wrapper](https://web.archive.org/web/20160331144211/http://533soft.com/exewrapper) - 使用密码保护任何 EXE 文件免遭未经授权的执行.
- [Exe32Pack](https://exe32pack.apponic.com/) - 压缩 Win32 EXE、DLL 等，并在执行时动态扩展它们.
- [EXECryptor](https://execryptor.freedownloadscenter.com/windows) - 保护 EXE 程序免受逆向工程、分析、修改和破解.
- [ExeFog](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/exefog11-executablepackerbybagie) - 简单的 Win32 PE 文件打包器.
- [eXPressor](https://www.cgsoftlabs.ro/express.html) - 用作压缩器，此工具可以将 EXE 文件压缩到正常大小的一半.
- [FSG](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/compressors/win/fsg.zip) - *Fast Small Good*，适用于小型 exe 的完美压缩器，例如.
- [GHF Protector](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/ghfprotector10) - 基于开源引擎 Morphine 和 AHPack 的可执行打包器/保护器.
- [HackStop](https://defacto2.net/f/a520164?packer=hs) - EXE 和 COM 程序加密器和保护器.
- [Kkrunchy](http://www.farbrausch.de/~fg/kkrunchy) - Kkrunchy 是一个主要用于 64k 介绍的小型 exe 打包器.
- [mPack](https://blog.fearcat.in/a?ID=00050-86a031da-e36f-4409-9a08-d3d993dbf8f5) - mPack - mario PACKersimple Win32 PE 可执行压缩器.
- [NSPack](https://nspack.apponic.com/) - 32/64 位 exe、dll、ocx、scr Windows 程序压缩器.
- [NTPacker](https://hacking-software-free-download.blogspot.com/2013/02/nt-packer-v21.html) - 依赖 aPlib 进行压缩和/或 XOR 进行加密的 PE 文件打包器.
- [PECompact](http://www.bitsum.com/pec2.asp) - Windows 可执行压缩器具有第三方插件，可防止逆向工程.
- [RDMC](https://www.sac.sk/download/pack/rdm006be.zip) - 基于 DMC 算法的打包器.
- [RLPack](https://web.archive.org/web/20070527132336/http://rlpack.jezgra.net) - 压缩您的可执行文件和动态链接库，使它们保持较小并且不影响压缩文件的功能.
- [RSCC](https://defacto2.net/f/a520164?packer=rscc)  - ROSE 超级 COM 地穴； 用于大于 300-400B 且小于 60kB 的文件的多态加密器.
- [RUCC](https://defacto2.net/f/a520164?packer=rucc)  - ROSE Ultra COM 压缩器； 基于 624 的 COM 和 EXE 压缩实用程序.
- [Sentinel HASP Envelope](https://cpl.thalesgroup.com/en-gb/software-monetization/all-products/sentinel-hasp) - 包装应用程序，使用安全盾牌保护目标应用程序，提供抵消逆向工程和其他反调试措施的方法.
- [sePACKER](https://sourceforge.net/projects/sepacker/) - Simple Executable Packer 正在压缩可执行文件的代码部分以减小二进制文件的大小.
- [Shiva](https://packetstormsecurity.com/files/31087/shiva-0.95.tar.gz.html) - Shiva 是一个在 Linux 下加密 ELF 可执行文件的工具.
- [tElock](https://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/Telock.shtml) - Telock 是一款实用工具，旨在帮助想要保护其工作并减小可执行文件大小的开发人员.
- [TTProtect](http://www.ttprotect.com) - 为软件开发者设计的专业保护工具，保护他们的PE应用程序不被非法修改或反编译.
- [UPack](https://www.sac.sk/download/pack/upack399.rar) - 压缩 Windows PE 文件.
- [UPX-Scrambler](https://defacto2.net/f/a520164?packer=upxs) - 用于使用 UPX（最高 1.06）打包的文件的扰频器，因此它们无法使用“-d”选项解压.
- [WinUpack](https://www.sac.sk/download/pack/wupck039.zip) - Upack 的图形界面，这是一个命令行程序，用于从 Windows PE 文件创建自解压存档.
- [XComp](http://www.soft-lab.de/JoKo/index_old.htm) - PE32 图像文件打包器和重建器.
- [Yoda Crypter](https://sourceforge.net/projects/yodap/files/Yoda%20Crypter/1.3/yC1.3.zip/download) - 支持多态加密、软检测、反调试API、反倾销等，加密导入表并擦除PE Header.
- [Yoda Protector](http://yodap.sourceforge.net) - 免费、开源、Windows 32 位软件保护程序.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Before 2000

- [32Lite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/32lte02d.zip) - 用于使用 Watcom C/C++ 编译器创建的可执行文件的压缩工具.
- [624](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/624-11.zip) - 可以压缩短于 25000 字节的 COM 程序的 COM 加壳器.
- [ABK Scrambler](https://defacto2.net/f/a520164?packer=abk-scrambler) - 从 ABKprot 重新编码的 COM 文件扰码器和保护器.
- [AEP](https://defacto2.net/f/a520164?packer=aep) - COM 和 EXE 文件的附加编码保护.
- [AINEXE](https://defacto2.net/f/a520164?packer=ainexe) - DOS 可执行打包程序（AIN Archiver 套件的一部分）.
- [aPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/apack099.zip) - 16 位实模式 DOS 可执行文件（.EXE 和 .COM）压缩器.
- [AVPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/avpck122.zip) - 加密 EXE 或 COM 文件，以便它们只能在您的 PC 上启动.
- [AXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/axe22.zip) - 程序压缩实用程序.
- [BIN-Lock](https://defacto2.net/f/a520164?packer=bin-lock) - 用于防止逆向工程的 COM 文件扰码器.
- [BitLok](https://defacto2.net/f/a520164?packer=bitlok) - COM 和 EXE 文件保护程序.
- [C0NtRiVER](https://defacto2.net/f/a520164?packer=c0ntriver) - COM 文件加密器.
- [CauseWay Compressor](https://github.com/tkchia/causeway/tree/1ead4be14c9e536262e225f090b40b0c6cded286/watcom) - DOS EXE 压缩器.
- [CC Pro](https://defacto2.net/f/a520164?packer=ccpro) - COM 和 EXE 可执行文件压缩实用程序.
- [CEXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/cexe10a.zip) - 将输入 EXE 压缩成较小的可执行文件（仅在 WinNT、Win2000 及更高版本上运行 - 不会在 Win95 或 Win98 上运行）.
- [COMProtector](https://defacto2.net/f/a520164?packer=comprotector) - 通过对 DOS .COM 文件进行随机加密并添加一些反调试技巧，为 DOS .COM 文件添加一个安全信封.
- [CrackStop](https://defacto2.net/f/a520164?packer=crackstop) - 围绕 DOS EXE 文件创建安全信封以保护其免受黑客攻击的工具.
- [Crunch](https://defacto2.net/f/a520164?packer=crunch) - COM 和 EXE 文件的文件加密器.
- [EPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/epack16.zip)  - EXE 和 COM 文件压缩器； 适用于 DOS/Windows95 文件.
- [ExeGuard](https://defacto2.net/f/a520164?packer=exeguard) - DOS EXE 文件免费保护器使用反调试标记来防止黑客攻击、分析和解包.
- [EXELOCK 666](https://defacto2.net/f/a520164?packer=exelock666) - 用于保护 .EXE 文件的实用程序，因此没有 lamers 可以破解版权.
- [FSE](https://defacto2.net/f/a520164?packer=fse) - 用于保护 COM 和 EXE 程序的 Final Fantasy Security Envelope 免费软件.
- [Gardian Angel](https://defacto2.net/f/a520164?packer=gardian-angel) - 使用各种反调试技巧的 COM 和 EXE 加密器和保护器.
- [JMCryptExe](https://defacto2.net/f/a520164?packer=jmce) - DOS EXE 加密器.
- [LGLZ](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/lglz104b.zip) - 使用修改后的 LZ77 的 DOS EXE 和 COM 文件压缩器.
- [LzExe](https://defacto2.net/f/a520164?packer=lzexe) - MS-DOS 可执行文件压缩器.
- [Mask](https://defacto2.net/f/a520164?packer=mask) - 使用加密和反调试技巧防止 COM 程序被破解的工具.
- [Megalite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/megal120.zip) - MS-DOS 可执行文件压缩器.
- [Mess](https://defacto2.net/f/a520164?packer=mess) - 此工具与 HackStop 的功能相同，不同之处在于它是非商业用途的免费软件.
- [Morphine](https://github.com/bowlofstew/rootkit.com/blob/master/hf/Morphine27) - PE文件加密应用.
- [Neolite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/neolte20.zip) - 压缩 Windows 32 位 EXE 文件和 DLL.
- [PACK](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/pack201.zip) - 可执行文件压缩器.
- [PCShrink](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/pcsnk071.zip) - 依赖于 aPLib 压缩库的 Windows 9x/NT 可执行文件压缩器.
- [PE Diminisher](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/ped.zip) - 依赖于 aPLib 压缩库的简单 PE 打包器.
- [PE-Protector](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/protectors/win/pe-protector10.zip) - 适用于 Windows 9x/ME 的加密器/保护器，用于保护可执行文件 PE 以防止逆向工程或破解，提供非常强大的保护.
- [PEBundle](http://www.collakesoftware.com/files/pebsetup.exe) - 将 DLL 物理附加到可执行文件，解决内存中的依赖关系.
- [PEPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/pepack10.zip) - 基于较新版本PE-SHiELD代码的PE压缩工具.
- [PKlite](https://defacto2.net/f/a520164?packer=pklite) - 易于使用的文件压缩程序，用于压缩 DOS 和 Windows 可执行文件.
- [Pro-Pack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/pp219.zip) - DOS 可执行文件压缩器.
- [RERP](https://www.sac.sk/download/pack/rerp.rar) - ROSE 的 EXE 重定位打包器.
- [RJCrush](https://www.sac.sk/download/pack/rjc-beta.zip) - 具有压缩叠加功能的 EXE 和 COM 文件压缩器.
- [Scorpion](https://defacto2.net/f/a520164?packer=scorpion) - EXE 和 COM 文件加密器和保护器.
- [SecuPack](https://web.archive.org/web/20210119235522/https://www.exetools.com/files/compressors/win/secupack15.zip) - Win32 可执行压缩器.
- [Shrinker](https://www.sac.sk/download/pack/shrinker.exe) - 压缩（高达 70%）16 位和 32 位 Windows 和实模式 DOS 程序.
- [SPack](https://www.sac.sk/download/pack/spack20.zip)
- [$PIRIT](https://defacto2.net/f/a520164?packer=%24pirit) - COM/EXE 可执行文件多态加密器.
- [SysPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/syspack.zip) - 设备驱动压缩机.
- [T-Pack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/tpack05.zip) - 可执行的 COM-FILE 压缩器 (LZ77) 针对 BBS-Addys 或类似文件等小文件进行了优化.
- [TinyProg](https://www.sac.sk/download/pack/tinyp39.zip) - EXE 和 COM 程序压缩器.
- [TRAP](https://defacto2.net/f/a520164?packer=trap) - EXE 和 COM 文件加密器和保护器.
- [Vacuum](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/vacuum.zip) - DOS32 可执行文件的运行时压缩器.
- [VGCrypt](https://github.com/dhondta/awesome-executable-packing/blob/master/ftp://ftp.cdrom.com/.3/sac/security/vgcrypt.zip) - 用于 Win95/98/NT 的 PE 加密器.
- [WinLite](https://www.sac.sk/download/pack/winlite1.zip) - 为 DOS 下的可执行程序压缩 Windows 可执行文件（例如 Pklite、Diet 或 Wwpack）.
- [WWPack](https://defacto2.net/f/a520164?packer=wwpack) - 压缩 EXE 文件，压缩重定位表，优化标头，保护 EXE 文件免受黑客攻击.
- [XE](https://defacto2.net/f/a520164?packer=xe) - PE32 图像文件打包器和重建器.
- [XorCopy](https://defacto2.net/f/a520164?packer=xorcopy) - COM 文件基于 XOR 的加密器.
- [XORER](https://defacto2.net/f/a520164?packer=xorer) - COM 文件基于 XOR 的加密器.
- [XPA](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/xpa.zip) - DOS 可执行打包程序.
- [XPack](https://defacto2.net/f/a520164?packer=xpack) - EXE/COM/SYS 可执行文件压缩器.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :wrench: Tools

- [Android Unpacker](https://github.com/strazzere/android-unpacker) - Android Unpacker 在 Defcon 22 上展示：Android 黑客保护级别 0.
- [Angr](https://github.com/angr/angr) - 与平台无关的二进制分析框架.
- [APKiD](https://github.com/rednaga/APKiD) - 用于加壳器、保护器、混淆器和怪癖的 Android 应用程序标识符 - 用于 Android 的 PEiD.
- [aPLib](https://ibsensoftware.com/products_aPLib.html) - 基于 aPACK 中使用的算法的压缩库.
- [AppSpear](https://github.com/UchihaL/AppSpear) - 适用于 Dalvik 和 ART 的通用自动拆包系统.
- [Assiste (Packer)](https://assiste.com/Packer.html) - Assite.com 的打包程序示例列表.
- [AVClass](https://github.com/malicialab/avclass) - 用于标记/标记恶意软件样本的 Python 工具.
- [Bintropy](https://github.com/dhondta/bintropy) - 估计二进制文件包含压缩或加密字节的可能性的原型分析工具.
- [BinUnpack](https://doi.org/10.1145/3243734.3243771) - 免于繁琐的内存访问监控的解包方法，因此引入非常小的运行时开销.
- [Binutils](https://www.gnu.org/software/binutils) - GNU Binutils 是 Linux 二进制工具的集合（它包括 Readelf）.
- [BitBlaze](http://bitblaze.cs.berkeley.edu/release/index.html) - 分析平台以新颖的方式融合了静态和动态分析技术、混合具体和符号执行以及全系统仿真和二进制检测，所有这些都有助于对实际安全问题进行最先进的研究.
- [Capa](https://github.com/mandiant/capa) - 用于识别 PE、ELF 或 .NET 可执行文件中功能的开源工具.
- [Capstone](https://www.capstone-engine.org) - 轻量级多平台、多架构的反汇编框架.
- [CFF Explorer](https://ntcore.com/?page_id=388) - PE32/64 和 .NET 编辑器，Explorer Suite 的一部分.
- [ChkEXE](https://defacto2.net/f/a91dea6?dosmachine=svga&dosspeed=max) - 识别几乎所有的 EXE/COM 加壳器、加密器或保护器.
- [Clamscan Unpacker](https://clamunpacker.sourceforge.io/) - 来自 ClamAV 的解包器.
- [COM2EXE](https://defacto2.net/f/a520164?tool=com2exe) - 将 COM 文件转换为 EXE 格式的免费工具.
- [de4dot](https://github.com/0xd4d/de4dot) - .NET 去混淆器和解包器.
- [de4js](https://github.com/lelinhtinh/de4js) - JavaScript 去混淆器和解包器.
- [Defacto2 Analyzers Archive](https://defacto2.net/f/aa2e6ec) - 1990 年代和 2000 年代 60 个二进制文件分析器的集合，适用于 MS-DOS 和 Windows32.
- [Defacto2 Packers Archive](https://defacto2.net/f/a520164) - 从 1990 年代到 2000 年代，为 MS-DOS 和 Windows32 收集了 460 个二进制和数据文件打包器.
- [Defacto2 Unpackers Archive](https://defacto2.net/f/a218ab4) - 1990 年代和 2000 年代 MS-DOS 和 Windows 32 的 152 个二进制文件解包器的集合.
- [DIE](https://github.com/horsicq/DIE-engine/releases)  - 轻松检测； 确定文件类型的程序.
- [DSFF](https://github.com/packing-box/python-dsff) - 用于交换数据集和转换为 ARFF（用于 Weka）、CSV 或 Packing-Box 的数据集结构的数据集文件格式.
- [DynamoRIO](https://dynamorio.org) - 运行时代码操纵系统，支持在程序执行时对程序的任何部分进行代码转换.
- [Emulator](https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/Using-policies-to-manage-security/preventing-and-handling-virus-and-spyware-attacks-v40739565-d49e172/how-does-the-emulator-in-symantec-endpoint-protect-v121004909-d47e230.html) - Symantec Endpoint Protector（自 v14 起）能够动态创建虚拟机，以识别、引爆和消除隐藏在自定义恶意软件打包程序中的恶意软件.
- [EtherUnpack](https://ether.gtisc.gatech.edu/web_unpack) - 精密通用自动拆包器（PolyUnpack 的继任者）.
- [Eureka](https://web.archive.org/web/20150502154942/http://eureka.cyber-ta.org) - 二进制静态分析准备框架实现了一种基于统计双语法分析和粗粒度执行跟踪的新型二进制解包策略.
- [EXEInfo-PE](https://github.com/ExeinfoASL/ASL) - 可执行 PE 文件的快速检测器.
- [ExeScan](https://defacto2.net/f/ae2c42e) - 可执行文件分析器，可检测最著名的 EXE/COM 保护器、加壳器、转换器和编译器.
- [EXETools](https://forum.exetools.com) - 逆向工程和可执行打包相关主题的论坛.
- [FUU](https://github.com/crackinglandia/fuu) - 快速通用解包器.
- [GetTyp](https://www.helger.com/gt/gt.htm) - 基于特殊字符串和字节码的DOS文件格式检测程序.
- [GUnpacker](http://qunpack.ahteam.org/?p=327) - 执行 OEP 定位和转储解密代码的 Shell 工具.
- [IDR](https://github.com/crypto2011/IDR) - 交互式 Delphi 重构器.
- [ImpREC](https://www.aldeid.com/wiki/ImpREC) - 这可用于修复打包程序的导入表.
- [Justin](https://doi.org/10.1007/978-3-540-87403-4_6)  - 即时 AV 扫描； 通用解包解决方案.
- [Language 2000](https://farrokhi.net/language) - 终极编译器检测实用程序.
- [LIEF](https://github.com/lief-project/LIEF)  - 仪器可执行格式库； 用于解析 PE、ELF、Mach-O 和 DEX 格式、修改和重建可执行文件的 Python 包.
- [Lissom](https://github.com/dhondta/awesome-executable-packing/blob/master/ttp://www.fit.vutbr.cz/research/groups/lissom) - 可重定向反编译器，由预处理部分和反编译核心组成.
- [LordPE](https://www.aldeid.com/wiki/LordPE) - PE 标题查看器、编辑器和重建器.
- [Malheur](https://github.com/rieck/malheur) - 用于自动分析恶意软件行为的工具（从沙盒环境中的恶意软件中记录）.
- [MalUnpack](https://github.com/hasherezade/mal_unpack) - 基于 PE 筛的动态拆包器.
- [Manalyze](https://github.com/JusticeRage/Manalyze) - Robust parser for PE files with a flexible plugin architecture which allows users to statically analyze files in-depth.
- [MRC](https://mandiant-red-curtain.apponic.com)  - (Mandiant Red Curtain) 用于协助分析恶意软件的事件响应者的免费软件； 它检查可执行文件（例如，.exe、.dll 等），根据一组标准确定它们的可疑程度.
- [.NET Deobfuscator](https://github.com/NotPrab/.NET-Deobfuscator) - .NET Deobfuscators 和 Unpackers 列表.
- [Oedipus](https://github.com/tum-i4/Oedipus) - 一个使用机器学习算法实现针对混淆程序的元数据恢复攻击的 Python 框架.
- [OEPdet](https://ieeexplore.ieee.org/abstract/document/7782073) - 自动原始入口点检测器.
- [OllyDbg Scripts](https://github.com/xshows/ollydbg-script) - 用于解压许多不同打包程序的 OllyDbg 脚本集合.
- [OmniUnpack](https://doi.org/10.1109/ACSAC.2007.15) - 通过实时监控执行和检测移除的包装层来快速、通用和安全地解压恶意软件的新技术.
- [PackerAttacker](https://github.com/BromiumLabs/PackerAttacker) - 使用内存和代码挂钩来检测加壳器的工具.
- [PackerBreaker](https://www.portablefreeware.com/forums/viewtopic.php?t=21555) - 帮助解包、解压缩和解密大多数使用高级仿真技术打包、压缩或加密的程序的工具.
- [PackerGrind](https://github.com/rewhy/adaptiveunpacker) - 自适应解包工具，用于跟踪打包行为和解包 Android 打包应用程序.
- [PackerID](https://github.com/sooshie/packerid) - packerid.py 的分支使用 PEid 签名并具有额外的输出类型、格式、数字签名提取和反汇编支持.
- [PackID](https://github.com/mesaleh/PackiD) - 使用与 PEiD 相同的数据库语法的封隔器识别多平台工具/库.
- [Packing-Box](https://github.com/dhondta/docker-packing-box) - Docker 图像收集了许多与打包相关的工具，并用于制作打包可执行文件的数据集以用于机器学习.
- [PANDA](https://github.com/panda-re/panda) - 架构中立的动态分析平台.
- [Pandora's Bochs](https://0x0badc0.de/gitweb?p=bochs/.git) - 扩展到 Bochs PC eumlator，使其能够监控解包存根的执行以提取原始代码.
- [PCjs](https://www.pcjs.org) - PCjs 使用 JavaScript 重现 IBM PC 体验，使用原始 ROM、以原始速度运行的 CPU 以及早期的 IBM 视频卡和显示器.
- [PE Compression Test](http://pect.atspace.com/) - 在一些样本可执行文件上测试的打包程序列表，用于比较压缩后的大小.
- [PE Detective](https://ntcore.com/?page_id=367) - 这个 GUI 工具可以扫描单个 PE 文件或整个目录（也可以递归地）并生成完整的报告.
- [PE-bear](https://github.com/hasherezade/pe-bear-releases) - 用于 PE 文件的免费软件逆向工具旨在为恶意软件分析师提供快速灵活的“第一视图”，稳定且能够处理格式错误的 PE 文件.
- [PEdump](https://pedump.me/) - Dump windows PE files using Ruby.
- [Pefeats](https://github.com/roussieau/masterthesis/tree/master/src/detector/tools/pefeats) - 用于从 PE 文件中提取 119 个特征以用于机器学习算法的实用程序.
- [Pefile](https://github.com/erocarrera/pefile) - 用于解析和处理可移植可执行文件的多平台 Python 模块.
- [PEFrame](https://github.com/guelfoweb/peframe) - 对 PE 恶意软件和一般可疑文件执行静态分析的工具.
- [PEiD](http://www.secretashell.com/codomain/peid/) - 打包的可执行标识符.
- [PEiD (CLI)](https://github.com/dhondta/peid) - PEiD 的 Python 实现，具有用于制作新签名的附加工具.
- [PEiD (yara)](https://github.com/K-atc/PEiD) - PEiD 的另一个实现与 yara.
- [PeLib](https://github.com/avast/pelib) - PE 文件操作库.
- [PEPack](https://github.com/merces/pev) - PE 文件加壳检测工具，Unix 包“pev”的一部分.
- [PEscan](https://tzworks.com/prototype_page.php?proto_id=15) - 用于扫描 PE 文件以识别它们是如何构建的 CLI 工具.
- [PETools](https://github.com/petoolse/petools) - 用于处理 PE 文件的老式逆向工程工具（自 2002 年以来历史悠久）.
- [PEview](http://wjradburn.com/software) - 提供了一种快速简便的方法来查看 32 位可移植可执行文件 (PE) 和组件对象文件格式 (COFF) 文件的结构和内容.
- [PExplorer](http://www.heaventools.com/overview.htm) - 大多数功能丰富的程序，用于检查您自己的软件的内部工作，更重要的是，您没有源代码的第三方 Windows 应用程序和库.
- [Pin](https://www.intel.com/content/www/us/en/developer/articles/tool/pin-a-dynamic-binary-instrumentation-tool.html) - 用于 IA-32、x86-64 和 MIC 指令集架构的动态二进制检测框架，支持创建动态程序分析工具.
- [PINdemonium](https://github.com/Phat3/PINdemonium) - 利用 PIN 功能的 PE 文件解包器.
- [PolyUnpack](https://github.com/PlatonovIvan/PolyUnpack) - 尝试在没有任何启发式假设的情况下提取 PE 文件的原始隐藏代码的一般方法.
- [PortEx](https://github.com/katjahahn/PortEx) - 用于 PE 文件静态恶意软件分析的 Java 库，侧重于 PE 畸形鲁棒性和异常检测.
- [PROTECTiON iD](https://web.archive.org/web/20210331144912/https://protectionid.net) - 基于 PE 文件签名的扫描器.
- [ProTools](http://protools.narod.ru) - Programmer&#39;s Tools，一个专门为真正的 WinBloze 程序员提供各种工具和实用程序的网站，包括加壳器、加密器等.
- [PyPackerDetect](https://github.com/cylance/PyPackerDetect) - 用于检测可执行文件是否已打包的小型 python 脚本/库.
- [PyPackerDetect (refactored)](https://github.com/dhondta/PyPackerDetect) - A complete refactoring of the original project to a Python package with a console script to detect whether an executable is packed.
- [PyPeid](https://github.com/FFRI/pypeid) - 另一个使用 yara-python 的 PEiD 实现.
- [Quick Unpack](http://qunpack.ahteam.org/?p=458) - 促进解包过程的通用解包器.
- [RDG Packer Detector](http://www.rdgsoft.net) - 打包机检测工具.
- [Reko](https://github.com/uxmal/reko) - 机器代码二进制文件的免费反编译器.
- [REMINDer](https://doi.org/10.1109/CSA.2009.5404211) - 基于入口点部分熵值和WRITE属性的装箱检测工具.
- [REMnux](https://remnux.org) - 用于逆向工程和分析恶意软件的 Linux 工具包.
- [Renovo](https://doi.org/10.1145/1314389.1314399) - 建立在 TEMU（BitBlaze 的动态分析组件）之上的检测工具，基于新生成代码的执行和程序启动后监控内存写入.
- [ResourceHacker](http://angusj.com/resourcehacker) - 32 位和 64 位 Windows 应用程序的资源编辑器.
- [RetDec](https://github.com/avast/retdec) - 基于 LLVM 的可重定向机器代码反编译器.
- [RTD](https://www.sac.sk/download/pack/rtd_rp24.zip) - 玫瑰补丁 - TinyProt/Rosetiny 解包器.
- [RUPP](https://www.sac.sk/download/pack/rupp037.rar) - ROSE SWE UnPaCKER PaCKaGE（仅适用于 DOS 可执行文件）.
- [SAFE](https://github.com/dhondta/awesome-executable-packing/blob/master/mailto:mihai@cs.wisc.edu) - 可执行文件的静态分析器（按需提供）.
- [ShowStopper](https://github.com/CheckPointSW/showstopper) - 帮助恶意软件研究人员探索和测试反调试技术或验证调试器插件或与标准反调试方法冲突的其他解决方案的工具.
- [StudPE](http://www.cgsoftlabs.ro/studpe.html) - PE 查看器和编辑器（32/64 位）.
- [SymPack](https://www.amazon.com/Norton-AntiVirus-2007-Old-Version/dp/B000IAOIXW)  - 安全、便携、高效但不是通用的包装检测和拆包库；  Norton Antivirus 解决方案的一部分.
- [Titanium Platform](https://www.reversinglabs.com/products/malware-analysis-platform) - 机器学习混合云平台，可大规模收集数千种文件类型，通过机器学习二进制分析加速威胁检测，并持续监控超过 10B 文件的索引以应对未来威胁.
- [TrID](https://mark0.net/soft-trid-e.html) - 用于根据二进制签名识别文件类型的实用程序.
- [Triton](https://github.com/jonathansalwan/Triton) - 动态二进制分析库.
- [Tuts 4 You](https://tuts4you.com) - 致力于分享逆向代码工程知识和信息的非商业独立社区.
- [Unipacker](https://github.com/unipacker/unipacker) - Automatic and platform-independent unpacker for Windows binaries based on emulation.
- [UnpacMe](https://www.unpac.me) - 自动恶意软件解包服务.
- [Unpckarc](https://web.archive.org/web/20191218043307/http://www.woodmann.com/crackz/Tools/) - 依赖于多种启发式方法的打包可执行文件检测工具.
- [UU](https://www.sac.sk/download/pack/uu215e.exe) - 通用解包器.
- [Uundo](https://www.sac.sk/download/pack/uundo.zip) - 通用撤消 - 通用解包器.
- [Uunp (IDA Pro plugin)](https://www.hex-rays.com/blog/unpacking-mpressed-pe-dlls-with-the-bochs-plugin/) - IDA Pro 调试器插件模块自动分析和解包打包的二进制文件.
- [UUP](https://www.sac.sk/download/pack/uup14.zip) - 通用 exe 文件 UnPacker.
- [VirusTotal](https://www.virustotal.com/gui/) - 用于检测恶意软件的文件分析 Web 服务.
- [VMUnpacker](https://www.leechermods.com/2010/01/vmunpacker-16-latest-version.html) - 基于虚拟机技术的解包器.
- [Winbindex](https://github.com/m417z/winbindex) - Windows 二进制文件的索引，包括 EXE、DLL 和 SYS 文件等可执行文件的下载链接.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## Contributing

欢迎投稿！ 请阅读 [contribution guidelines](https://github.com/dhondta/awesome-executable-packing/blob/master/CONTRIBUTING.md) 第一的.
