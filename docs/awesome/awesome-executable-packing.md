<div class="github-widget" data-repo="dhondta/awesome-executable-packing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Executable Packing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <a href="https://twitter.com/intent/tweet?text=Awesome%20Executable%20Packing%20-%20A%20curated%20list%20of%20resources%20related%20to%20the%20packing%20of%20various%20executable%20formats%20and%20its%20detection.%0D%0Ahttps%3a%2f%2fgithub%2ecom%2fdhondta%2fawesome-executable-packing%0D%0A&hashtags=awesomelists,malware,malwareresearch,executablepacking,cybersecurity,infosec"><img src="https://img.shields.io/badge/Tweet--lightgrey?logo=twitter&style=social" alt="Tweet" height="20"/></a>

&gt; 与可执行文件打包相关的资源列表（包括可移植可执行文件、可执行文件和可链接格式等），其中包含对书籍、论文、博客文章和其他书面资源的引用，还包括用于检测打包程序和解包可执行文件的打包程序和工具.

 *Packing* 是以不改变其用途的方式修改可执行文件的操作. 一般是以下操作之一或组合：
- 捆绑：使单个可执行文件具有多个文件
- 压缩：压缩可执行文件以减小其原始大小
- 加密：通过加密来混淆可执行文件
- 突变：改变可执行文件的代码，使其使用修改后的指令集和架构（例如使用寡态）
- 保护：使可执行文件的逆向更难（即使用反调试、反篡改或其他技巧）
- 虚拟化：嵌入允许虚拟化可执行指令的虚拟机






## :books: Literature


### Documentation

- :earth_americas: [a.out (FreeBSD manual pages)](https://www.freebsd.org/cgi/man.cgi?a.out(5))
- :earth_americas: [A.out binary format](https://wiki.osdev.org/A.out)
- :earth_americas: [About anti-debug tricks](https://anti-debug.checkpoint.com/about)
- ：bar_chart： [Android packers: Separating from the pack](https://www.fortiguard.com/events/759/2014-06-12-android-packers-separating-from-the-pack)
- ：图钉： [Anti debugging protection techniques with examples](https://www.apriorit.com/dev-blog/367-anti-reverse-engineering-protection-techniques-to-use-before-releasing-software)
- ：bar_chart： [API deobfuscator: Resolving obfuscated API functions in modern packers](https://www.blackhat.com/docs/us-15/materials/us-15-Choi-API-Deobfuscator-Resolving-Obfuscated-API-Functions-In-Modern-Packers.pdf)
- ：bar_chart： [The art of unpacking](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf)
- ：图钉： [Cloak and dagger: Unpacking hidden malware attacks](https://symantec-enterprise-blogs.security.com/blogs/expert-perspectives/unpacking-hidden-malware-attacks)
- :earth_americas: [COM binary format](https://wiki.osdev.org/COM)
- :earth_americas: [Common object file format (COFF)](https://wiki.osdev.org/COFF)
- :earth_americas: [Comparison of executable file formats](https://en.wikipedia.org/wiki/Comparison_of_executable_file_formats)
- :earth_americas: [Defacto2](https://defacto2.net/defacto2)
- ：bar_chart： [Dynamic binary analysis and obfuscated codes](https://triton.quarkslab.com/files/sthack2016-rthomas-jsalwan.pdf)
- :earth_americas: [elf (FreeBSD manual pages)](https://www.freebsd.org/cgi/man.cgi?elf(5))
- :earth_americas: [Executable and linkable format (ELF)](https://wiki.osdev.org/ELF)
- ：剪贴板： [Executable and linking format (ELF) specification](https://refspecs.linuxfoundation.org/elf/elf.pdf)
- :earth_americas: [Executable file formats](https://docs.fileformat.com/executable)
- :earth_americas: [FatELF: Universal binaries for Linux (HALTED)](https://icculus.org/fatelf)
- ：滚动： [Implementing your own generic unpacker](https://gsec.hitb.org/materials/sg2015/whitepapers/Julien%20Lenoir%20-%20Implementing%20Your%20Own%20Generic%20Unpacker.pdf)
- ：图钉： [Mach-O - A look at apple executable files](https://redmaple.tech/blogs/macho-files)
- :earth_americas: [Mach-O file format reference](https://github.com/aidansteele/osx-abi-macho-file-format-reference)
- ：bar_chart： [Mach-O internals](https://yossarian.net/res/pub/macho-internals/macho-internals.pdf)
- ：剪贴板： [Microsoft portable executable and common object file format specification](http://www.skyfree.org/linux/references/coff.pdf)
- :earth_americas: [MITRE ATT&CK | T1027.002 | obfuscated files or information: Software packing](https://attack.mitre.org/techniques/T1027/002)
- :earth_americas: [MZ disk operating system (DOS)](https://wiki.osdev.org/MZ)
- ：bar_chart： [One packer to rule them all: Empirical identification, comparison and circumvention of current antivirus detection techniques](https://www.blackhat.com/docs/us-14/materials/us-14-Mesbahi-One-Packer-To-Rule-Them-All-WP.pdf)
- ：滚动： [One packer to rule them all: Empirical identification, comparison and circumvention of current antivirus detection techniques](https://www.blackhat.com/docs/us-14/materials/us-14-Mesbahi-One-Packer-To-Rule-Them-All.pdf)
- ：图钉： [Parsing mach-O files](https://lowlevelbits.org/parsing-mach-o-files)
- :earth_americas: [PE format (Microsoft docs)](https://docs.microsoft.com/en-us/windows/win32/debug/pe-format)
- ：滚动： [PinDemonium: A DBI-based generic unpacker for Windows executables](https://www.blackhat.com/docs/us-16/materials/us-16-Mariani-Pindemonium-A-Dbi-Based-Generic-Unpacker-For-Windows-Executables-wp.pdf)
- :earth_americas: [Portable executable (PE)](https://wiki.osdev.org/PE)
- ：bar_chart： [Runtime packers: The hidden problem?](https://www.blackhat.com/presentations/bh-usa-06/BH-US-06-Morgenstern.pdf)
- ：bar_chart： [TitanMist: Your first step to reversing nirvana](https://www.reversinglabs.com/blackhat/TitanMist_BlackHat-USA-10-Slides.pdf)
- ：图钉： [Tuts 4 you - UnPackMe (.NET)](https://forum.tuts4you.com/forum/155-unpackme-net)
- ：图钉： [Tuts 4 you | unpackme](https://forum.tuts4you.com/forum/147-unpackme)
- ：bar_chart： [Virtual machine obfuscation](https://compil2019.minesparis.psl.eu/wp-content/uploads/2019/02/BeatriceCreusillet-Obfuscation-quarkslab.pdf)
- ：bar_chart： [We can still crack you! General unpacking method for Android Packer (NO ROOT)](https://www.blackhat.com/asia-15/briefings.html#we-can-still-crack-you-general-unpacking-method-for-android-packer-no-root)
- ：剪贴板： [Win32 portable executable packing uncovered](https://securitylabs.websense.com/content/Assets/HistoryofPackingTechnology.pdf)
- ：图钉： [Writing a packer](https://dr4k0nia.github.io/dotnet/coding/2021/06/24/Writing-a-Packer.html)
- ：图钉： [Writing a simple PE packer in detail](https://github.com/levanvn/Packer_Simple-1)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Scientific Research

- ：报纸： [Absent extreme learning machine algorithm with application to packed executable identification](https://link.springer.com/article/10.1007%2Fs00521-014-1558-4) （2016 年 1 月） 
- ：报纸： [An accurate packer identification method using support vector machine](https://www.jstage.jst.go.jp/article/transfun/E97.A/1/E97.A_253/_article) （2014年1月） 
- ：笔记本： [Adaptive unpacking of Android Apps](https://ieeexplore.ieee.org/document/7985676) （2017 年 5 月） 
- ：报纸： [All-in-one framework for detection, unpacking, and verification for malware analysis](https://www.hindawi.com/journals/scn/2019/5278137/) （2019 年 1 月）：星：
- ：报纸： [Analysis of machine learning approaches to packing detection](https://arxiv.org/abs/2105.00473) （2021 年 5 月） :star: :star: :star:
- ：笔记本： [Anti-unpacker tricks](http://2008.caro.org/downloads/unpackers.pdf) （2008 年 5 月） 
- ：笔记本： [Application of string kernel based support vector machine for malware packer identification](https://ieeexplore.ieee.org/document/6707043) （2013年八月） 
- ：笔记本： [AppSpear: Bytecode decrypting and DEX reassembling for packed Android malware](https://link.springer.com/chapter/10.1007/978-3-319-26362-5_17) （2015 年 11 月） 
- ：报纸： [Automatic analysis of malware behavior using machine learning](https://dl.acm.org/doi/10.5555/2011216.2011217) （2011 年 12 月） 
- ：笔记本： [Automatic static unpacking of malware binaries](https://ieeexplore.ieee.org/document/5328814) （2009 年 10 月） 
- ：报纸： [BareUnpack: Generic unpacking on the bare-metal operating system](https://www.jstage.jst.go.jp/article/transinf/E101.D/12/E101.D_2017EDP7424/_article) （2018 年 12 月）：星：
- ：报纸： [Binary-code obfuscations in prevalent packer tools](https://doi.org/10.1145/2522968.2522972) （2013 年 10 月）：星：
- ：报纸： [BinStat tool for recognition of packed executables](http://www.ijofcs.org/abstract-v06n1-pp03.html) （2010 年 9 月） 
- ：笔记本： [BitBlaze: A new approach to computer security via binary analysis](https://link.springer.com/chapter/10.1007/978-3-540-89862-7_1) （2008 年 12 月） 
- ：笔记本： [Boosting scalability in anomaly-based packed executable filtering](https://link.springer.com/chapter/10.1007%2F978-3-642-34704-7_3) (November 2011) 
- ：砂浆板： [Building a smart and automated tool for packed malware detections using machine learning](https://dial.uclouvain.be/memoire/ucl/en/object/thesis%3A25193) （2020 年 6 月）:star: :star:
- ：笔记本： [ByteWise: A case study in neural network obfuscation identification](https://ieeexplore.ieee.org/document/8301720/) （2018 年 1 月）：星：
- ：笔记本： [Challenging anti-virus through evolutionary malware obfuscation](https://link.springer.com/chapter/10.1007%2F978-3-319-31153-1_11) （2016 年 4 月） 
- ：报纸： [Classification of packed executables for accurate computer virus detection](http://www.sciencedirect.com/science/article/pii/S0167865508002110) （2008 年 10 月） 
- ：笔记本： [Classifying packed programs as malicious software detected](https://www.semanticscholar.org/paper/Classifying-Packed-Programs-as-Malicious-Software-Osaghae/676f38819a0ed3028acce36f4f11b0c77e4cc0ae) （2016 年 12 月）：星：
- ：报纸： [A close look at a daily dataset of malware samples](https://doi.org/10.1145/3291061) （2019 年 1 月）：星：
- ：笔记本： [Collective classification for packed executable identification](https://doi.org/10.1145/2030376.2030379) （2012 年 6 月） 
- ：笔记本： [A comparative analysis of classifiers in the recognition of packed executables](https://ieeexplore.ieee.org/abstract/document/8995252) （2019 年 11 月）：星：
- ：笔记本： [A comparative assessment of malware classification using binary texture analysis and dynamic analysis](https://dl.acm.org/doi/10.1145/2046684.2046689) （2011 年 9 月） 
- ：笔记本： [Comparing malware samples for unpacking: A feasibility study](https://ieeexplore.ieee.org/document/7782073) （2016 年 8 月） 
- ：砂浆板： [Computational-intelligence techniques for malware generation](https://raw.githubusercontent.com/jimmy-sonny/ConferencesAndTalks/master/Ms.C%20Thesis/Thesis_Marcelli.pdf) （2015 年 10 月） 
- ：报纸： [A consistently-executing graph-based approach for malware packer identification](https://ieeexplore.ieee.org/document/8695825) （2019 年 4 月）：星：
- ：笔记本： [A control flow graph-based signature for packer identification](https://ieeexplore.ieee.org/document/8170793) （2017 年 10 月）：星：
- ：笔记本： [Countering entropy measure attacks on packed software detection](https://ieeexplore.ieee.org/document/6181079) （2012 年 1 月） 
- ：bar_chart： [Dealing with virtualization packers](http://2008.caro.org/downloads/boris_lau_virtualization_obfs.pdf) （2008 年 5 月） 
- ：笔记本： [Denial-of-service attacks on host-based generic unpackers](https://link.springer.com/chapter/10.1007/978-3-642-11145-7_19) （2009 年 12 月） 
- ：砂浆板： [Deobfuscation of packed and virtualization-obfuscation protected binaries](https://repository.arizona.edu/handle/10150/202716) （2011 年 6 月） 
- ：笔记本： [Design and development of a new scanning core engine for malware detection](https://ieeexplore.ieee.org/document/6388212) （2012 年 10 月） 
- ：笔记本： [Design and performance evaluation of binary code packing for protecting embedded software against reverse engineering](https://ieeexplore.ieee.org/document/5479571) （2010 年 5 月） 
- ：笔记本： [Detecting packed executable file: Supervised or anomaly detection method?](https://ieeexplore.ieee.org/abstract/document/7784628) （2016 年 8 月）：星：
- ：报纸： [Detecting packed executables based on raw binary data](https://www.semanticscholar.org/paper/DETECTING-PACKED-EXECUTABLES-BASED-ON-RAW-BINARY-Nataraja-Jacobb/53371424fb79de29a096e563b07fcae432f4d201) （2010 年 6 月） 
- ：笔记本： [Detecting packed executables using steganalysis](https://ieeexplore.ieee.org/document/7018361) （2014 年 12 月） 
- ：砂浆板： [Detecting packed PE files: Executable file analysis for the Windows operating system](https://uia.brage.unit.no/uia-xmlui/handle/11250/2823655) （2021 年 6 月）:star::star::star:
- ：笔记本： [Detection of metamorphic malware packers using multilayered LSTM networks](https://www.springerprofessional.de/en/detection-of-metamorphic-malware-packers-using-multilayered-lstm/18635334) （2020 年 11 月）:star::star:
- ：笔记本： [Detection of packed executables using support vector machines](https://ieeexplore.ieee.org/document/6016774) （2011 年 7 月） 
- ：笔记本： [Detection of packed malware](https://doi.org/10.1145/2490428.2490431) （2012 年 8 月） 
- ：笔记本： [DexHunter: Toward extracting hidden code from packed Android applications](https://link.springer.com/chapter/10.1007/978-3-319-24177-7_15) （2015 年 9 月） 
- ：笔记本： [Disabling anti-debugging techniques for unpacking system in user-level debugger](https://ieeexplore.ieee.org/document/8939719) （2019 年 10 月）：星：
- ：笔记本： [Dynamic binary instrumentation for deobfuscation and unpacking](https://hal.inria.fr/inria-00431666) （2009 年 11 月） 
- ：笔记本： [Dynamic classification of packing algorithms for inspecting executables using entropy analysis](https://ieeexplore.ieee.org/document/6703681) （2013 年 10 月） 
- ：报纸： [Effective, efficient, and robust packing detection and classification](http://www.sciencedirect.com/science/article/pii/S0167404818311040) （2018 年 1 月）：星：
- ：笔记本： [Efficient and automatic instrumentation for packed binaries](https://link.springer.com/chapter/10.1007/978-3-642-02617-1_32) （2009 年 6 月） 
- ：报纸： [Efficient automatic original entry point detection](https://jise.iis.sinica.edu.tw/JISESearch/pages/View/PaperView.jsf?keyId=169_2256) （2019 年 1 月）：星：
- ：报纸： [An efficient block-discriminant identification of packed malware](https://link.springer.com/article/10.1007%2Fs12046-015-0399-x) （2015 年 8 月） 
- ：笔记本： [Efficient malware packer identification using support vector machines with spectrum kernel](https://ieeexplore.ieee.org/document/6621654) （2013 年 7 月） 
- ：报纸： [Efficient SVM based packer identification with binary diffing measures](https://ieeexplore.ieee.org/document/8754440/) （2019 年 7 月）：星：
- ：报纸： [ELF-Miner: Using structural knowledge and data mining methods to detect new (Linux) malicious executables](https://dl.acm.org/doi/10.5555/2150963.2150968) （2012 年 3 月） 
- ：报纸： [EMBER: An open dataset for training static PE malware machine learning models](https://arxiv.org/abs/1804.04637) （2018 年 4 月）：星：
- ：笔记本： [An empirical evaluation of an unpacking method implemented with dynamic binary instrumentation](https://www.jstage.jst.go.jp/article/transinf/E94.D/9/E94.D_9_1778/_article) （2011 年 9 月） 
- ：笔记本： [Encoded executable file detection technique via executable file header analysis](https://www.earticle.net/Article/A105986) （2009 年 4 月） 
- ：笔记本： [Entropy analysis to classify unknown packing algorithms for malware detection](https://link.springer.com/article/10.1007/s10207-016-0330-4) （2016 年 5 月）：星：
- ：笔记本： [ESCAPE: Entropy score analysis of packed executable](https://dl.acm.org/doi/10.1145/2388576.2388607) （2012 年 10 月） 
- ：笔记本： [Ether: Malware analysis via hardware virtualization extensions](https://doi.org/10.1145/1455770.1455779) （2008 年 10 月） 
- ：笔记本： [Eureka: A framework for enabling static malware analysis](https://link.springer.com/chapter/10.1007%2F978-3-540-88313-5_31) （2008 年 10 月） 
- ：笔记本： [Experimental comparison of machine learning models in malware packing detection](https://ieeexplore.ieee.org/document/9237007) （2020 年 9 月） :star: :star:
- ：笔记本： [An experimental study on identifying obfuscation techniques in packer](https://docplayer.net/63501103-An-experimental-study-on-identifying-obfuscation-techniques-in-packer.html) （2016 年 6 月） 
- ：笔记本： [A fast flowgraph based classification system for packed and polymorphic malware on the endhost](https://ieeexplore.ieee.org/document/5474800/) （2010 年 4 月） 
- ：笔记本： [Feature set reduction for the detection of packed executables](https://ieeexplore.ieee.org/document/6912767) （2014 年 6 月） 
- ：笔记本： [A fine-grained classification approach for the packed malicious code](https://link.springer.com/chapter/10.1007/978-3-642-34129-8_49) （2012 年 10 月） 
- ：笔记本： [A generic approach to automatic deobfuscation of executable code](https://ieeexplore.ieee.org/document/7163054) （2015 年 5 月）：星：：星：
- ：报纸： [Generic packing detection using several complexity analysis for accurate malware detection](https://www.researchgate.net/publication/332594129_Generic_Packing_Detection_using_Several_Complexity_Analysis_for_Accurate_Malware_Detection?channel=doi&linkId=5cbf828b299bf120977ac78a&showFulltext=true) （2014年1月） 
- ：笔记本： [Generic unpacker of executable files](https://www.semanticscholar.org/paper/Generic-Unpacker-of-Executable-Files-Milkovi/413321c5a473d59c18e861c1478cd44f88142275) （2015 年 4 月） 
- ：笔记本： [Generic unpacking method based on detecting original entry point](https://link.springer.com/chapter/10.1007/978-3-642-42054-2_74) （2013年11月） 
- ：报纸： [Generic unpacking of self-modifying, aggressive, packed binary programs](https://arxiv.org/abs/0905.4581) （2009 年 5 月） 
- ：笔记本： [Generic unpacking techniques](https://ieeexplore.ieee.org/document/4909168) （2009 年 2 月） 
- ：笔记本： [Generic unpacking using entropy analysis](https://ieeexplore.ieee.org/document/5665789) （2010 年 10 月） 
- ：笔记本： [Gunpack: Un outil générique d'unpacking de malwares](https://www.sstic.org/2016/presentation/gunpack/) （2016 年 6 月） 
- ：笔记本： [A heuristic approach for detection of obfuscated malware](https://ieeexplore.ieee.org/document/5137328) （2009 年 6 月） 
- ：报纸： [A heuristics-based static analysis approach for detecting packed PE binaries](http://dx.doi.org/10.14257/ijsia.2013.7.5.24) （2013 年 10 月） 
- ：笔记本： [An implementation of a generic unpacking method on Bochs Emulator](https://www.semanticscholar.org/paper/An-Implementation-of-a-Generic-Unpacking-Method-on-HyungChanKim-Daisuke/d5c947520815105231673f1b87af57ed6abd379c) （2009 年 9 月） 
- ：笔记本： [Information theoretic method for classification of packed and encoded files](https://dl.acm.org/doi/10.1145/2799979.2800015) （2015 年 9 月） 
- ：笔记本： [Instructions-based detection of sophisticated obfuscation and packing](https://ieeexplore.ieee.org/document/6956729) （2014 年 10 月） 
- ：报纸： [A learning model to detect maliciousness of portable executable using integrated feature set](https://www.sciencedirect.com/science/article/pii/S1319157817300149) （2017 年 1 月） 
- ：笔记本： [Limits of static analysis for malware detection](https://ieeexplore.ieee.org/document/4413008) （2007 年 12 月） 
- ：砂浆板： [Maitland: Analysis of packed and encrypted malware via paravirtualization extensions](https://dspace.library.uvic.ca/handle/1828/3866) （2012 年 6 月） 
- ：笔记本： [Mal-EVE: Static detection model for evasive malware](https://ieeexplore.ieee.org/document/7497952) （2015 年 8 月） 
- ：报纸： [Mal-flux: Rendering hidden code of packed binary executable](http://www.sciencedirect.com/science/article/pii/S1742287618303736) （2019 年 3 月）：星：
- ：报纸： [Mal-XT: Higher accuracy hidden-code extraction of packed binary executable](https://iopscience.iop.org/article/10.1088/1757-899X/453/1/012001) （2018 年 11 月）：星：
- ：报纸： [Mal-xtract: Hidden code extraction using memory analysis](https://doi.org/10.1088%2F1742-6596%2F801%2F1%2F012058) （2017 年 1 月） 
- ：报纸： [Malware analysis using multiple API sequence mining control flow graph](https://arxiv.org/abs/1707.02691) （2017 年 7 月）：星：
- ：报纸： [Malware analysis using visualized images and entropy graphs](https://link.springer.com/article/10.1007%2Fs10207-014-0242-0) （2015 年 2 月） 
- ：笔记本： [Malware obfuscation techniques: A brief survey](https://ieeexplore.ieee.org/document/5633410) （2010 年 11 月） 
- ：笔记本： [Malware obfuscation through evolutionary packers](https://doi.org/10.1145/2739482.2764940) （2015 年 7 月） 
- ：报纸： [Malwise - An effective and efficient classification system for packed and polymorphic malware](https://ieeexplore.ieee.org/document/6171162) （2013年六月） 
- ：笔记本： [McBoost: Boosting scalability in malware collection and analysis using statistical classification of executables](https://ieeexplore.ieee.org/document/4721567) （2008 年 12 月） 
- ：笔记本： [Memory behavior-based automatic malware unpacking in stealth debugging environment](https://ieeexplore.ieee.org/document/5665794) （2010 年 10 月） 
- ：笔记本： [Modern linux malware exposed](https://www.eurecom.fr/fr/publication/5584) （2018 年 6 月） 
- ：笔记本： [MutantX-S: Scalable malware clustering based on static features](https://www.usenix.org/conference/atc13/technical-sessions/presentation/hu) （2013年六月） 
- ：笔记本： [The new signature generation method based on an unpacking algorithm and procedure for a packer detection](https://www.earticle.net/Article/A147420) （2011 年 2 月） 
- ：笔记本： [Obfuscation-resilient executable payload extraction from packed malware](https://www.usenix.org/conference/usenixsecurity21/presentation/cheng-binlin) （2021 年 8 月） :star: :star: :star:
- ：报纸： [Obfuscation: The hidden malware](https://ieeexplore.ieee.org/document/5975134) （2011 年 8 月） 
- ：笔记本： [Obfuscation: Where are we in anti-DSE protections? (a first attempt)](https://doi.org/10.1145/3371307.3371309) （2019 年 12 月）：星：
- ：笔记本： [OmniUnpack: Fast, generic, and safe unpacking of malware](https://ieeexplore.ieee.org/document/4413009) （2007 年 12 月） 
- ：报纸： [On the adoption of anomaly detection for packed executable filtering](https://www.sciencedirect.com/science/article/pii/S0167404814000522?via%3Dihub) （2014 年 6 月） 
- ：笔记本： [OPEM: A static-dynamic approach for machine-learning-based malware detection](https://link.springer.com/chapter/10.1007/978-3-642-33018-6_28) （2012 年 9 月） 
- ：报纸： [An original entry point detection method with candidate-sorting for more effective generic unpacking](https://www.jstage.jst.go.jp/article/transinf/E98.D/4/E98.D_2014EDP7268/_article) （2015 年 1 月） 
- ：报纸： [Packed malware detection using entropy related analysis: A survey](https://api.semanticscholar.org/CorpusID:212493886) （2015 年 11 月） 
- ：报纸： [Packed malware variants detection using deep belief networks](https://doi.org/10.1051/matecconf/202030902002) （2020 年 3 月） 
- ：笔记本： [Packed PE file detection for malware forensics](https://ieeexplore.ieee.org/document/5404211) （2009 年 12 月） 
- ：报纸： [Packer analysis report debugging and unpacking the NsPack 3.4 and 3.7 packer](https://www.sans.org/reading-room/whitepapers/malicious/packer-analysis-report-debugging-unpacking-nspack-34-37-packer-33428) （2010 年 6 月） 
- ：笔记本： [Packer classifier based on PE header information](https://dl.acm.org/doi/10.1145/2746194.2746213) （2015 年 4 月） 
- ：报纸： [Packer detection for multi-layer executables using entropy analysis](https://www.mdpi.com/1099-4300/19/3/125) （2017 年 3 月）：星：
- ：笔记本： [Packer identification based on metadata signature](https://dl.acm.org/doi/10.1145/3151137.3160687) （2017 年 12 月）：星：
- ：笔记本： [Packer identification method based on byte sequences](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.5082) （2018 年 11 月）：星：
- ：报纸： [Packer identification using byte plot and Markov plot](https://link.springer.com/article/10.1007/s11416-015-0249-8) （2015 年 9 月）：星：
- ：笔记本： [Packer identification using hidden Markov model](https://link.springer.com/chapter/10.1007/978-3-319-69456-6_8) （2017 年 11 月）：星：
- ：砂浆板： [Packer-complexity analysis in PANDA](https://webthesis.biblio.polito.it/7519/) （2018 年 1 月）：星：
- ：砂浆板： [Pandora's Bochs: Automatic unpacking of malware](https://www.researchgate.net/publication/268355151_Pandora%27s_Bochs_Automatic_Unpacking_of_Malware) （2008 年 1 月） 
- ：笔记本： [Pattern recognition techniques for the classification of malware packers](https://link.springer.com/chapter/10.1007/978-3-642-14081-5_23) （2010 年 7 月） 
- ：报纸： [PE file features in detection of packed executables](http://www.ijcte.org/show-42-485-1.html) （2012 年 1 月） 
- ：笔记本： [PE file header analysis-based packed PE file detection technique (PHAD)](https://ieeexplore.ieee.org/document/4654055) （2008 年 10 月） 
- ：笔记本： [PE-Probe: Leveraging packer detection and structural information to detect malicious portable executables](https://www.semanticscholar.org/paper/PE-Probe%3A-Leveraging-Packer-Detection-and-to-Detect-Shafiq-Tabish/9811ec751f2b5bb41ee46c0ee2a3b6eccc39bb9a) （2009 年 6 月） 
- ：笔记本： [PEAL - Packed executable analysis](https://link.springer.com/chapter/10.1007/978-3-642-29280-4_28) （2012 年 1 月） 
- ：笔记本： [PolyUnpack: Automating the hidden-code extraction of unpack-executing malware](https://ieeexplore.ieee.org/document/4041175) （2006 年 12 月） 
- ：笔记本： [Prevalence and impact of low-entropy packing schemes in the malware ecosystem](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24297.pdf) （2020 年 2 月） :star: :star:
- ：bar_chart： [Qualitative and quantitative evaluation of software packers](http://webdiis.unizar.es/~ricardo/files/slides/industrial/slides_NcN-15.pdf) （2015 年 12 月） 
- ：笔记本： [RAMBO: Run-Time packer analysis with multiple branch observation](https://link.springer.com/chapter/10.1007/978-3-319-40667-1_10) （2016 年 7 月） 
- ：砂浆板： [REFORM: A framework for malware packer analysis using information theory and statistical methods](https://researchrepository.rmit.edu.au/view/delivery/61RMIT_INST/12246783310001341/13248377300001341) （2010 年 4 月） 
- ：笔记本： [Renovo: A hidden code extractor for packed executables](https://dl.acm.org/doi/10.1145/1314389.1314399) （2007 年 11 月） 
- ：笔记本： [RePEconstruct: Reconstructing binaries with self-modifying code and import address table destruction](https://ieeexplore.ieee.org/document/7888727) （2016 年 10 月）：星：
- :notebook: RePEF — 用于恢复打包可执行文件以进行恶意软件分析的系统（2011 年 7 月） 
- ：笔记本： [Research and implementation of compression shell unpacking technology for PE file](https://ieeexplore.ieee.org/document/5231651) （2009 年 5 月） 
- ：报纸： [Revealing packed malware](https://ieeexplore.ieee.org/document/4639028) （2008 年 9 月） 
- ：笔记本： [Reverse engineering self-modifying code: Unpacker extraction](https://ieeexplore.ieee.org/document/5645447) （2010 年 10 月） 
- ：砂浆板： [Robust static analysis of portable executable malware](https://repo.zenk-security.com/Virus-Infections-Detections-Preventions/Robust%20Static%20Analysis%20ofPortable%20ExecutableMalware.pdf) （2014 年 12 月） 
- ：bar_chart： [Runtime packers testing experiences](https://docs.google.com/a/caro.org/viewer?a=v&pid=sites&srcid=Y2Fyby5vcmd8Y2Fyby13b3Jrc2hvcC0yMDA4fGd4OjZkNzk3MmI2YjZlMWMxZGI) （2008 年 5 月） 
- ：笔记本： [SATURN - Software deobfuscation framework based on LLVM](https://doi.org/10.1145/3338503.3357721) （2019 年 11 月）:star: :star:
- ：报纸： [SCORE: Source code optimization & reconstruction](https://ieeexplore.ieee.org/document/9139493) （2020 年 7 月） :star: :star:
- ：笔记本： [SE-PAC: A self-evolving packer classifier against rapid packers evolution](https://doi.org/10.1145/3422337.3447848) （2021 年 4 月）:star::star::star:
- ：报纸： [Secure and advanced unpacking using computer emulation](https://link.springer.com/article/10.1007%2Fs11416-007-0046-0) （2007 年 8 月） 
- ：笔记本： [Semi-supervised learning for packed executable detection](https://ieeexplore.ieee.org/document/6060027) （2011 年 9 月） 
- ：笔记本： [Semi-supervised learning for unknown malware detection](https://link.springer.com/chapter/10.1007/978-3-642-19934-9_53) （2011 年 4 月） 
- ：报纸： [Sensitive system calls based packed malware variants detection using principal component initialized multilayers neural networks](https://cybersecurity.springeropen.com/articles/10.1186/s42400-018-0010-y) （2018 年 9 月）：星：
- ：笔记本： [SoK: Deep packer inspection: A longitudinal study of the complexity of run-time packers](https://ieeexplore.ieee.org/document/7163053) （2015 年 5 月）:star2::star2::star2:
- ：笔记本： [SPADE: Signature based packer detection](https://dl.acm.org/doi/10.1145/2490428.2490442) （2012 年 8 月） 
- ：笔记本： [Static analysis of executables to detect malicious patterns](https://dl.acm.org/doi/10.5555/1251353.1251365) （2003 年 8 月） 
- ：笔记本： [A static, packer-agnostic filter to detect similar malware samples](https://link.springer.com/chapter/10.1007/978-3-642-37300-8_6) （2012 年 7 月） 
- ：笔记本： [Structural feature based anomaly detection for packed executable identification](https://link.springer.com/chapter/10.1007%2F978-3-642-21323-6_29) （2011 年 6 月） 
- ：笔记本： [The study of evasion of packed PE from static detection](https://ieeexplore.ieee.org/document/6280206) （2012 年 6 月） 
- ：笔记本： [A study of the packer problem and its solutions](https://link.springer.com/chapter/10.1007/978-3-540-87403-4_6) （2008 年 9 月） 
- ：笔记本： [Survey on malware evasion techniques: State of the art and challenges](https://ieeexplore.ieee.org/abstract/document/6174775) （2012 年 2 月） 
- ：笔记本： [Syntia: Synthesizing the semantics of obfuscated code](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko) （2017 年 8 月）：星：
- ：笔记本： [Things you may not know about Android (Un) packers: A systematic study based on whole-system emulation.](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_04A-4_Duan_paper.pdf) （2018 年 2 月）：星：
- ：笔记本： [Thwarting real-time dynamic unpacking](https://dl.acm.org/doi/10.1145/1972551.1972556) （2011 年 1 月） 
- ：笔记本： [Toward generic unpacking techniques for malware analysis with quantification of code revelation](https://www.researchgate.net/publication/255608911_Toward_Generic_Unpacking_Techniques_for_Malware_Analysis_with_Quantification_of_Code_Revelation) （2009 年 8 月） 
- ：笔记本： [Towards paving the way for large-scale Windows malware analysis: Generic binary unpacking with orders-of-magnitude performance boost](https://dl.acm.org/doi/10.1145/3243734.3243771) （2018 年 10 月）：星：
- ：报纸： [Two techniques for detecting packed portable executable files](https://ieeexplore.ieee.org/document/6636333) （2013年六月） 
- ：笔记本： [Unconditional self-modifying code elimination with dynamic compiler optimizations](https://ieeexplore.ieee.org/document/5665795) （2010 年 10 月） 
- ：笔记本： [Understanding linux malware](https://ieeexplore.ieee.org/document/8418602) （2018 年 5 月）：星：
- ：砂浆板： [Unpacking framework for packed malicious executables](https://repositorio-aberto.up.pt/bitstream/10216/68815/2/25935.pdf) （2013 年 7 月） 
- ：报纸： [Unpacking techniques and tools in malware analysis](https://www.scientific.net/AMM.198-199.343) （2012 年 9 月） 
- ：笔记本： [Unpacking virtualization obfuscators](https://dl.acm.org/doi/10.5555/1855876.1855877) （2009 年 8 月） 
- ：报纸： [UnThemida: Commercial obfuscation technique analysis with a fully obfuscated program](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.2622) （2018 年 7 月）：星：：星：
- ：报纸： [Using entropy analysis to find encrypted and packed malware](https://ieeexplore.ieee.org/document/4140989) （2007 年 3 月） 
- ：笔记本： [VMAttack: Deobfuscating virtualization-based packed binaries](https://dl.acm.org/doi/10.1145/3098954.3098995) （2017 年 8 月）：星：
- ：bar_chart： [WaveAtlas: Surfing through the landscape of current malware packers](https://www.virusbulletin.com/virusbulletin/2016/12/vb2015-paper-waveatlas-surfing-through-landscape-current-malware-packers/) （2015 年 9 月） 
- ：bar_chart： [When malware is packing heat](https://www.eurecom.fr/publication/5372) （2018 年 1 月）：星：
- ：报纸： [WYSINWYX: What you see is not what you execute](https://doi.org/10.1145/1749608.1749612) （2010 年 8 月） 
- ：报纸： [x64Unpack: Hybrid emulation unpacker for 64-bit Windows Environments and detailed analysis results on VMProtect 3.4](https://ieeexplore.ieee.org/document/9139515) （2020 年 7 月） :star: :star:

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :bookmark_tabs: Datasets

- [CyberCrime](https://cybercrime-tracker.net/vx.php) - C² 跟踪和恶意软件数据库.
- [Dataset of Packed ELF](https://github.com/dhondta/dataset-packed-elf) - 打包的 ELF 样本数据集.
- [Dataset of Packed PE](https://github.com/dhondta/dataset-packed-pe) - 原始数据集 PackingData 的净化版本，从 Notpacked 文件夹中移除打包样本，但也移除打包器文件夹中未能打包的样本（与原始解压可执行文件具有相同的哈希值）.
- [Ember](https://github.com/elastic/ember) - 从作为研究人员基准数据集的 PE 文件中收集特征.
- [MaleX](https://github.com/Mayachitra-Inc/MaleX) - 恶意软件研究人员的恶意软件和良性 Windows 可执行样本数据集包含 1,044,394 个 Windows 可执行二进制文件和相应的图像表示，其中 864,669 个标记为恶意软件，179,725 个标记为良性.
- [Malfease](https://web.archive.org/web/20141221153307/http://malfease.oarci.net) - 大约 5,000 个打包恶意软件样本的数据集.
- [Malheur](https://www.sec.cs.tu-bs.de/data/malheur) - 包含记录的恶意软件（malware）行为，并已用于开发对恶意软件行为进行分类和聚类的方法（参见 2011 年的 JCS 文章）.
- [Malicia](http://malicia-project.com/dataset.html) - 2013 年 11 个月期间从 500 个路过式下载服务器收集的 11,688 个恶意 PE 文件的数据集（已停产）.
- [MalShare](https://malshare.com) - 免费的恶意软件存储库为研究人员提供访问样本、恶意源和 Yara 结果的权限.
- [MalwareBazaar](https://bazaar.abuse.ch) - 由 abuse.ch 运营的项目旨在收集和共享恶意软件样本，帮助 IT 安全研究人员和威胁分析师保护他们的选区和客户免受网络威胁.
- [MalwareGallery](https://github.com/BaRRaKudaRain/MalwareGallery) - Internet 中的另一个恶意软件集合.
- [OARC Malware Dataset](https://www.dns-oarc.net) - 2005 年 9 月至 2006 年 1 月通过邮件陷阱、用户提交、蜜罐和 OARC 汇总的其他来源在野外捕获的 3,467 个样本的半公开数据集，可根据要求提供给合格的学术和行业研究人员.
- [Open Malware](https://web.archive.org/web/20190116100735/http://www.offensivecomputing.net/) - 在线收集恶意软件样本.
- [PackingData](https://github.com/chesvectain/PackingData) - 原始数据集，包含带有各种打包程序的示例 PE 文件，包括 ASPack、BeRoEXEPacker、exe32pack、eXpressor、FSG、JDPack、MEW、Molebox、MPRESS、Neolite、NSPack、Pckman、PECompact、PEtite、RLPack、UPX、WinUpack、尤达的密码器和尤达的保护者.
- [Packware](https://github.com/ucsb-seclab/packware) - 重现论文“When Malware is Packing Heat”中的实验所需的数据集和代码.
- [Runtime Packers Testset](https://www.researchgate.net/publication/268030543_Runtime_Packers_The_Hidden_Problem) - 10 个常见恶意软件文件的数据集，包含超过 500 个版本和选项的大约 40 个不同的运行时打包程序，总共大约 5,000 个样本.
- [SOREL](https://github.com/sophos-ai/SOREL-20M) - Sophos-ReversingLabs 2000 万数据集.
- [theZoo](https://github.com/ytisf/theZoo) - 为使恶意软件分析的可能性向公众开放和可用而创建的项目.
- [ViruSign](https://www.virusign.com) - 另一个在线恶意软件数据库.
- [VirusShare](https://virusshare.com) - 超过 4400 万个样本的病毒在线数据库.
- [VX Heaven](https://web.archive.org/web/20170817143838/http://vxheaven.org/) - 专门提供有关计算机病毒信息的站点.
- [VX Underground](https://vx-underground.org/samples.html) - 基于 PL-CERT 的开源 MWDB python 应用程序包含一个恶意软件数据库，其中包含 2010 年的每个 APT 样本和超过 750 万个恶意二进制文件.
- [VXvault](http://vxvault.net/ViriList.php) - 在线恶意软件数据库.
- [WildList](http://www.wildlist.org/CurrentList.txt) - 安全专业人员报告的恶意软件合作列表.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :package: Packers

### After 2010

- [.netshrink](https://www.pelock.com/products/netshrink) - 使用 LZMA 的 Windows 或 Linux .NET 应用程序可执行文件的可执行压缩器.
- [Alienyze](https://alienyze.com) - Windows 32 位可执行文件的高级软件保护和安全性.
- [Alternate EXE Packer](https://www.alternate-tools.com/pages/c_exepacker.php) - 可执行文件（EXE 类型）或依赖 UPX 3.96 的 DLL 的压缩工具.
- [Amber](https://github.com/EgeBalci/amber/releases) - 与位置无关（反射）的 PE 加载器，可以在内存中执行本机 PE 文件（EXE、DLL、SYS）.
- [Andromeda](https://blog.morphisec.com/andromeda-tactics-analyzed) - 在恶意软件活动中使用的自定义加壳程序使用 RunPE 技术来规避 AV 缓解方法.
- [APKProtect](https://sourceforge.net/projects/apkprotect) - 支持 Java 和 C++ 的 APK 加密和外壳保护.
- [Armadillo](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/protectors/win/armd252b2.zip) - 结合了用于保护 PE 文件的许可证管理器和包装系统.
- [ASPack](http://www.aspack.com/aspack.html) - 创建高级解决方案以提供 Win32 EXE 文件打包并保护它们免受非专业逆向工程的影响.
- [ASProtect 32](http://www.aspack.com/asprotect32.html) - 专为软件开发人员设计的多功能 EXE 打包工具，通过内置的应用程序复制保护系统保护 32 位应用程序.
- [ASProtect 64](http://www.aspack.com/asprotect64.html) - 用于保护 Windows 的 64 位应用程序和 .NET 应用程序免受未经授权的使用、工业和家庭复制、专业黑客攻击以及对 Internet 和任何物理媒体上分发的软件产品的分析的工具.
- [AutoIT](https://www.autoitscript.com/site) - 合法的可执行加密服务.
- [AxProtector](https://www.wibu.com/us/products/protection-suite/axprotector.html) - 加密您要保护的完整软件，并使用安全外壳、AxEngine 保护它，然后将最佳反调试和反反汇编方法注入您的软件.
- [BangCle](https://github.com/woxihuannisja/Bangcle) - 使用第二代Android Hardening Protection的保护工具，从内存中动态加载加密的DEX文件.
- [Bero](https://blog.rosseaux.net/page/875fbe6549aa072b5ee0ac9cefff4827/BeRoEXEPacker) - 用于 32 位 Windows 可执行文件的 Bero EXE Packer (BEP).
- [BIN-crypter](https://www.autoitscript.com/forum/topic/129383-bin-crypter/) - 针对破解者和反编译器的 EXE 保护软件.
- [Code Virtualizer](https://www.oreans.com/CodeVirtualizer.php) - Code Virtualizer 是一个强大的代码混淆系统，适用于 Windows、Linux 和 macOS 应用程序，可帮助开发人员通过基于代码虚拟化的非常强大的混淆代码来保护其敏感代码区域免受逆向工程.
- [ConfuserEx](https://github.com/mkaring/ConfuserEx) - 一个开源的、免费的 .NET 应用程序保护器.
- [Crinkler](https://github.com/runestubbe/Crinkler) - 压缩 Windows 的链接器，专门针对大小仅为几千字节的可执行文件.
- [DarkCrypt](https://totalcmd.net/plugring/darkcrypttc.html) - 简单而强大的 Total Commander 插件，用于使用 100 种算法和 5 种模式进行文件加密.
- [DexGuard](https://www.guardsquare.com/en/products/dexguard) - 用于移动应用保护的 Android 应用混淆和安全协议.
- [DexProtector](https://dexprotector.com/) - 多层 RASP 解决方案，保护您的 Android 和 iOS 应用程序免受静态和动态分析、非法使用和篡改.
- [DotBundle](https://web.archive.org/web/20160508074421/http://www.dotbundle.com:80/download.html) - 用于压缩、加密广告密码保护 .NET 应用程序或嵌入 .NET 库的 GUI 工具.
- [DotNetZ](https://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/NETZ.shtml) - 用 C 语言编写的简单、轻量级的命令行软件，可让您压缩和打包 Microsoft .NET Framework 可执行文件.
- [ElecKey](https://www.sciensoft.com) - 一套软件和工具，为软件保护、复制保护和许可证管理提供完整的解决方案.
- [ELFuck](https://github.com/timhsutw/elfuck) - 来自 sd 的 sk2 的 i386 原始版本的 ELF 打包程序.
- [Enigma Protector](https://www.enigmaprotector.com) - 可执行文件许可和保护的专业系统.
- [Enigma Virtual Box](https://www.enigmaprotector.com/en/aboutvb.html) - 适用于 Windows 的应用程序虚拟化系统.
- [Eronona-Packer](https://github.com/Eronana/packer) - 这是win32下的exe打包器.
- [EXE Bundle](https://www.webtoolmaster.com/exebundle.htm) - 将应用程序文件捆绑到单个 PE32 文件中.
- [EXE Stealth](http://www.webtoolmaster.com/packer.htm) - 具有压缩和加密多态技术的PE文件的防破解保护和许可工具.
- [Ezuri](https://github.com/guitmz/ezuri/blob/master/ezuri.go) - 一个简单的 Linux ELF 运行时加密器.
- [GzExe](https://git.savannah.gnu.org/cgit/gzip.git) - 允许将可执行文件压缩为 shell 脚本的实用程序.
- [hXOR-Packer](https://github.com/rurararura/hXOR-Packer) - 具有 Huffman 压缩和 XOR 加密的 PE 打包器.
- [LIAPP](https://liapp.lockincomp.com) - 最简单、最强大的移动应用安全解决方案.
- [LM-X License Manager](https://www.x-formation.com/lm-x-license-manager) - LM-X 许可证管理器让您可以通过实施各种级别的安全性、节省时间和降低业务风险来保护您的产品免受盗版.
- [m0dern_p4cker](https://github.com/n4sm/m0dern_p4cker) - 只是 elf 二进制文件的现代打包程序（仅适用于 linux 可执行文件）.
- [MidgetPack](https://github.com/arisada/midgetpack) - Midgetpack 是 ELF 二进制文件的二进制打包器，例如 burneye、upx 或其他工具.
- [MPRESS](https://www.autohotkey.com/mpress/mpress_web.htm) - 压缩（使用 LZMA）并保护 PE、.NET 或 Mach-O 程序免受逆向工程.
- [NetCrypt](https://github.com/friedkiwi/netcrypt) - .NET 可执行文件的概念验证打包程序，旨在为解释运行时打包的基本原理提供一个起点.
- [Obsidium](http://www.obsidium.de/show.php?home) - 功能丰富的专业软件保护和许可系统，设计为一种经济高效且易于实施、可靠且非侵入性的方式，可保护您的 32 位和 64 位 Windows 软件应用程序和游戏免受逆向工程的影响.
- [Origami](https://github.com/dr4k0nia/Origami) - Packer 压缩 .net 程序集，（ab）使用 PE 格式进行数据存储.
- [Pakkero](https://github.com/89luca89/pakkero) - Pakkero 是一个用 Go 编写的二进制打包器，用于娱乐和教育目的.
- [Papaw](https://github.com/dimkr/papaw) - 使用 LZMA Zstandard 或 Deflate 压缩的 ELF 可执行文件的许可打包程序.
- [PE-Packer](https://github.com/czs108/PE-Packer) - Windows 32 位 PE 文件的简单打包程序.
- [PE-Toy](https://github.com/r0ngwe1/petoy) - PE 文件打包器.
- [PELock](https://www.pelock.com)  - Windows 可执行文件的软件保护系统； 保护您的应用程序免遭篡改和逆向工程，并为软件许可证密钥管理提供广泛支持，包括对时间试用期的支持.
- [PePacker](https://github.com/SamLarenN/PePacker) - 加密 .text 部分的简单 PE 打包器 我发布了一个简单的 PE 文件打包器，它加密 .text 部分并在最后一部分的末尾添加一个解密存根.
- [PEShield](https://webscene.ir/tools/show/PE-SHIELD-0.25) - PE-SHIELD 是一个程序，它加密 32 位 Windows EXE 文件，使其仍然可执行.
- [PESpin](http://downloads.fyxm.net/PESpin-95477.html)
- [PEtite](https://www.un4seen.com/petite/) - 免费的 Win32 (Windows 95/98/2000/NT/XP/Vista/7/etc) 可执行 (EXE/DLL/etc) 压缩器.
- [sePACKER](https://sourceforge.net/projects/sepacker/) - Simple Executable Packer 正在压缩可执行文件的代码部分以减小二进制文件的大小.
- [Silent-Packer](https://github.com/SilentVoid13/Silent_Packer) - Silent Packer 是一个用纯 C 编写的 ELF / PE 打包器.
- [Simple-PE32-Packer](https://github.com/z3r0d4y5/Simple-PE32-Packer) - 带有 aPLib 压缩库的简单 PE32 Packer.
- [Smart Packer](https://www.smartpacker.nl) - Packs 32 & 64bit applications with DLLs, data files, 3rd party run-time into one single executable that runs instantly, with no installs or hassles.
- [theArk](https://github.com/aaaddress1/theArk) - C++ 中的 Windows x86 PE 打包程序.
- [Themida](https://www.oreans.com/themida.php) - 来自 Renovo 论文：Themida 将原始 x86 指令转换为自己的随机指令集中的虚拟指令，然后在运行时解释这些虚拟指令.
- [UPX](https://upx.github.io/) - 可执行文件的终极打包程序.
- [Ward](https://github.com/ex0dus-0x/ward) - 这是一个 ELF 打包器的简单实现，它创建了用于在内存中加载恶意 ELF 的隐蔽释放器.
- [xorPacker](https://github.com/nqntmqmqmb/xorPacker) - 使用所有 PE 文件的简单打包程序，这些文件使用 XOR 实现加密您的 exe.
- [ZProtect](http://www.jiami.net) - 重命名元数据实体并支持高级混淆方法，这些方法可以强化保护方案并完全阻止逆向工程.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Between 2000 and 2010

- [20to4](http://20to4.net) - 可执行压缩器，能够将大约 20k 最好的代码和数据填充到小于 4k 的空间中.
- [ACProtect](https://www.yaldex.com/Bestsoft/Utilities/acprotect.htm) - 允许保护 Windows 可执行文件免受盗版的应用程序，使用 RSA 创建和验证注册密钥和解锁代码.
- [AHPack](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/ahpacker01byfeuerraderahteam) - PE 和 PE+ 文件打包器.
- [Application Protector](https://sourceforge.net/projects/balaji/) - 用于保护 Windows 应用程序的工具.
- [AT4RE Protector](https://en.52yma.com/thread-5444-1-1.html) - 在 ASM 中编程的非常简单的 PE 文件保护器.
- [AverCryptor](https://web.archive.org/web/20071012084924/http://secnull.org) - 小巧且非常方便的实用程序，旨在加密您可以存储任何私人信息的笔记 - 它有助于隐藏您的防病毒感染.
- [BurnEye](https://packetstormsecurity.com/files/29691/burneye-1.0-linux-static.tar.gz.html) - Burneye ELF 加密程序，x86-linux 二进制文件.
- [ByteBoozer](https://csdb.dk/release/?id=33093) - Commodore 64 可执行打包程序.
- [EXE Guarder](http://www.exeicon.com/exeguarder) - PE 文件的许可工具，允许压缩和指定密码通知.
- [EXE Wrapper](https://web.archive.org/web/20160331144211/http://533soft.com/exewrapper) - 保护任何带有密码的 EXE 文件免遭未经授权的执行.
- [Exe32Pack](https://exe32pack.apponic.com/) - 压缩 Win32 EXE、DLL 等，并在执行时动态扩展它们.
- [EXECryptor](https://execryptor.freedownloadscenter.com/windows) - 保护 EXE 程序免受逆向工程、分析、修改和破解.
- [eXPressor](https://www.cgsoftlabs.ro/express.html) - 用作压缩器，此工具可以将 EXE 文件压缩到正常大小的一半.
- [FSG](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/compressors/win/fsg.zip) - *Fast Small Good*，适合小型 exe 的完美压缩器，例如.
- [GHF Protector](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/ghfprotector10) - Executable packer / protector based on open source engines Morphine and AHPack.
- [HackStop](https://defacto2.net/f/a520164?packer=hs) - EXE 和 COM 程序加密器和保护器.
- [Kkrunchy](http://www.farbrausch.de/~fg/kkrunchy) - Kkrunchy 是一个小型 exe 打包程序，主要用于 64k 介绍.
- [mPack](https://blog.fearcat.in/a?ID=00050-86a031da-e36f-4409-9a08-d3d993dbf8f5) - mPack - mario PACKersimple Win32 PE 可执行压缩器.
- [NSPack](https://nspack.apponic.com/) - 32/64 位 exe、dll、ocx、scr Windows 程序压缩器.
- [NTPacker](https://hacking-software-free-download.blogspot.com/2013/02/nt-packer-v21.html) - PE 文件打包器依赖 aPlib 进行压缩和/或 XOR 进行加密.
- [PECompact](http://www.bitsum.com/pec2.asp) - Windows 可执行压缩器具有第三方插件，可防止逆向工程.
- [RLPack](https://web.archive.org/web/20070527132336/http://rlpack.jezgra.net) - 压缩您的可执行文件和动态链接库，使其保持较小且对压缩文件功能没有影响.
- [RSCC](https://defacto2.net/f/a520164?packer=rscc)  - 玫瑰超级 COM 地穴； 用于大于 300-400B 且小于 60kB 的文件的多态加密器.
- [RUCC](https://defacto2.net/f/a520164?packer=rucc)  - ROSE Ultra COM 压缩机； 基于 624 的 COM 和 EXE 压缩实用程序.
- [Sentinel HASP Envelope](https://cpl.thalesgroup.com/en-gb/software-monetization/all-products/sentinel-hasp) - 包装应用程序，用安全防护罩保护目标应用程序，提供一种方法来抵消逆向工程和其他反调试措施.
- [Shiva](https://packetstormsecurity.com/files/31087/shiva-0.95.tar.gz.html) - Shiva 是一个在 Linux 下加密 ELF 可执行文件的工具.
- [Shrinker](https://web.archive.org/web/20081022073034/http://www.blinkinc.com/shrinker.htm) - 压缩（高达 70%）16 位和 32 位 Windows 和实模式 DOS 程序.
- [tElock](https://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/Telock.shtml) - Telock 是一款实用工具，旨在帮助想要保护其工作并减小可执行文件大小的开发人员.
- [TTProtect](http://www.ttprotect.com) - 专为软件开发人员设计的专业保护工具，用于保护他们的 PE 应用程序免受非法修改或反编译.
- [UPX-Scrambler](https://defacto2.net/f/a520164?packer=upxs) - 使用 UPX（最高 1.06）打包的文件的扰码器，因此无法使用“-d”选项解压缩它们.
- [WinLite](http://www.win3x.org/win3board/viewtopic.php?t=1435&language=en) - 为 DOS 下的可执行程序压缩 Windows 可执行文件（例如 Pklite、Diet 或 Wwpack）.
- [WinUpack](https://www.sac.sk/download/pack/wupck039.zip) - Upack 的图形界面，这是一个用于从 Windows PE 文件创建自解压档案的命令行程序.
- [XComp](http://www.soft-lab.de/JoKo/index_old.htm) - PE32 映像文件打包器和重建器.
- [Yoda Crypter](https://sourceforge.net/projects/yodap/files/Yoda%20Crypter/1.3/yC1.3.zip/download) - 支持多态加密、软检测、反调试API、反倾销等，加密导入表和擦除PE Header.
- [Yoda Protector](http://yodap.sourceforge.net) - 免费、开源、Windows 32 位软件保护程序.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Before 2000

- [$PIRIT](https://defacto2.net/f/a520164?packer=%24pirit) - COM/EXE 可执行文件多态加密器.
- [32Lite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/32lte02d.zip) - 使用 Watcom C/C++ 编译器创建的可执行文件的压缩工具.
- [624](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/624-11.zip) - COM 打包器，可以压缩小于 25000 字节的 COM 程序.
- [ABK Scrambler](https://defacto2.net/f/a520164?packer=abk-scrambler) - 从 ABKprot 重新编码的 COM 文件加扰器和保护器.
- [AEP](https://defacto2.net/f/a520164?packer=aep) - 为 COM 和 EXE 文件添加编码保护.
- [AINEXE](https://defacto2.net/f/a520164?packer=ainexe) - DOS 可执行打包程序（AIN Archiver 套件的一部分）.
- [aPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/apack099.zip) - 16 位实模式 DOS 可执行文件（.EXE 和 .COM）压缩器.
- [AVPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/avpck122.zip) - 加密 EXE 或 COM 文件，以便它们只能在您的 PC 上启动.
- [AXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/axe22.zip) - 程序压缩实用程序.
- [BIN-Lock](https://defacto2.net/f/a520164?packer=bin-lock) - 用于防止逆向工程的 COM 文件加扰器.
- [BitLok](https://defacto2.net/f/a520164?packer=bitlok) - COM 和 EXE 文件保护器.
- [C0NtRiVER](https://defacto2.net/f/a520164?packer=c0ntriver) - COM 文件加密器.
- [CauseWay Compressor](https://github.com/tkchia/causeway/tree/1ead4be14c9e536262e225f090b40b0c6cded286/watcom) - DOS EXE 压缩器.
- [CC Pro](https://defacto2.net/f/a520164?packer=ccpro) - COM 和 EXE 可执行文件压缩实用程序.
- [CEXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/cexe10a.zip) - 将输入的 EXE 压缩成更小的可执行文件（仅在 WinNT、Win2000 及更高版本上运行 - 不会在 Win95 或 Win98 上运行）.
- [COMProtector](https://defacto2.net/f/a520164?packer=comprotector) - 通过随机加密并添加几个反调试技巧，在 DOS .COM 文件周围添加安全信封.
- [CrackStop](https://defacto2.net/f/a520164?packer=crackstop) - 在 DOS EXE 文件周围创建安全信封以保护其免受破解的工具.
- [Crunch](https://defacto2.net/f/a520164?packer=crunch) - COM 和 EXE 文件的文件加密器.
- [EPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/epack16.zip)  - EXE 和 COM 文件压缩器； 适用于 DOS/Windows95 文件.
- [ExeGuard](https://defacto2.net/f/a520164?packer=exeguard) - DOS EXE 文件免费保护器使用反调试刻度来防止黑客攻击、分析和解包.
- [EXELOCK 666](https://defacto2.net/f/a520164?packer=exelock666) - 保护 .EXE 文件的实用程序，因此没有人可以破解版权.
- [FSE](https://defacto2.net/f/a520164?packer=fse) - 最终幻想安全信封免费软件，用于保护 COM 和 EXE 程序.
- [Gardian Angel](https://defacto2.net/f/a520164?packer=gardian-angel) - 使用各种反调试技巧的 COM 和 EXE 加密器和保护器.
- [JMCryptExe](https://defacto2.net/f/a520164?packer=jmce) - DOS EXE 加密器.
- [LGLZ](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/lglz104b.zip) - DOS EXE 和 COM 文件压缩器使用修改后的 LZ77.
- [LzExe](https://defacto2.net/f/a520164?packer=lzexe) - MS-DOS 可执行文件压缩器.
- [Mask](https://defacto2.net/f/a520164?packer=mask) - 使用加密和反调试技巧防止 COM 程序被破解的工具.
- [Megalite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/megal120.zip) - MS-DOS 可执行文件压缩器.
- [Mess](https://defacto2.net/f/a520164?packer=mess) - 此工具与 HackStop 的功能相同，但它是用于非商业用途的免费软件.
- [Neolite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/neolte20.zip) - 压缩 Windows 32 位 EXE 文件和 DLL.
- [PACK](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/pack201.zip) - 可执行文件压缩器.
- [PCShrink](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/pcsnk071.zip) - 依赖于 aPLib 压缩库的 Windows 9x/NT 可执行文件压缩器.
- [PE Diminisher](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/ped.zip) - 简单的 PE 打包器，依赖于 aPLib 压缩库.
- [PE-Protector](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/protectors/win/pe-protector10.zip) - 用于 Windows 9x/ME 的加密器/保护器，用于保护可执行文件 PE 以防逆向工程或破解，具有非常强大的保护功能.
- [PEBundle](http://www.collakesoftware.com/files/pebsetup.exe) - 将 DLL 物理附加到可执行文件，解决内存中的依赖关系.
- [PEPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/pepack10.zip) - 基于更新版本PE-SHIELD代码的PE压缩工具.
- [PKlite](https://defacto2.net/f/a520164?packer=pklite) - 易于使用的文件压缩程序，用于压缩 DOS 和 Windows 可执行文件.
- [Pro-Pack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/pp219.zip) - DOS 可执行文件压缩器.
- [RJCrush](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/rjcru110.zip) - EXE 和 COM 文件压缩器具有压缩覆盖的能力.
- [Scorpion](https://defacto2.net/f/a520164?packer=scorpion) - EXE 和 COM 文件加密器和保护器.
- [SecuPack](https://web.archive.org/web/20210119235522/https://www.exetools.com/files/compressors/win/secupack15.zip) - Win32 可执行压缩器.
- [SysPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/syspack.zip) - 设备驱动程序压缩器.
- [T-Pack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/tpack05.zip) - 可执行的 COM-FILE 压缩器 (LZ77) 针对 BBS-Addys 或类似文件等小文件进行了优化.
- [TinyProg](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/tinyp39.zip) - EXE 和 COM 程序压缩器.
- [TRAP](https://defacto2.net/f/a520164?packer=trap) - EXE 和 COM 文件加密器和保护器.
- [Vacuum](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/vacuum.zip) - 用于 DOS32 可执行文件的运行时压缩器.
- [VGCrypt](https://github.com/dhondta/awesome-executable-packing/blob/master/ftp://ftp.cdrom.com/.3/sac/security/vgcrypt.zip) - 用于 Win95/98/NT 的 PE 加密器.
- [WWPack](https://defacto2.net/f/a520164?packer=wwpack) - 压缩 EXE 文件，压缩重定位表，优化标题，保护 EXE 文件免受黑客攻击.
- [XE](https://defacto2.net/f/a520164?packer=xe) - PE32 映像文件打包器和重建器.
- [XorCopy](https://defacto2.net/f/a520164?packer=xorcopy) - 基于 COM 文件 XOR 的加密器.
- [XORER](https://defacto2.net/f/a520164?packer=xorer) - 基于 COM 文件 XOR 的加密器.
- [XPA](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/xpa.zip) - DOS 可执行打包程序.
- [XPack](https://defacto2.net/f/a520164?packer=xpack) - EXE/COM/SYS 可执行文件压缩器.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :wrench: Tools

- [.NET Deobfuscator](https://github.com/NotPrab/.NET-Deobfuscator) - List of .NET Deobfuscators and Unpackers.
- [Android Unpacker](https://github.com/strazzere/android-unpacker) - 在 Defcon 22 上展示的 Android Unpacker：Android Hacker Protection Level 0.
- [Angr](https://github.com/angr/angr) - 平台无关的二进制分析框架.
- [APKiD](https://github.com/rednaga/APKiD) - 用于打包器、保护器、混淆器和怪异的 Android 应用程序标识符 - 适用于 Android 的 PEiD.
- [aPLib](https://ibsensoftware.com/products_aPLib.html) - 基于 aPACK 中使用的算法的压缩库.
- [AppSpear](https://github.com/UchihaL/AppSpear) - 适用于 Dalvik 和 ART 的通用自动拆包系统.
- [Assiste (Packer)](https://assiste.com/Packer.html) - Assiste.com 的打包程序示例列表.
- [AVClass](https://github.com/malicialab/avclass) - 用于标记/标记恶意软件样本的 Python 工具.
- [Bintropy](https://github.com/dhondta/bintropy) - 原型分析工具，用于估计二进制文件包含压缩或加密字节的可能性.
- [BinUnpack](https://doi.org/10.1145/3243734.3243771) - Unpacking approach free from tedious memory access monitoring, therefore introducing very small runtime overhead.
- [BitBlaze](http://bitblaze.cs.berkeley.edu/release/index.html) - 分析平台，具有静态和动态分析技术、混合具体和符号执行、全系统仿真和二进制仪器的新颖融合，所有这些都有助于对实际安全问题进行最先进的研究.
- [Capstone](https://www.capstone-engine.org) - 轻量级多平台、多架构反汇编框架.
- [ChkEXE](https://defacto2.net/f/a91dea6?dosmachine=svga&dosspeed=max) - 识别几乎所有 EXE/COM 打包程序、加密程序或保护程序.
- [Clamscan Unpacker](https://clamunpacker.sourceforge.io/) - 来自 ClamAV 的解包器.
- [COM2EXE](https://defacto2.net/f/a520164?tool=com2exe) - 用于将 COM 文件转换为 EXE 格式的免费工具.
- [de4dot](https://github.com/0xd4d/de4dot) - .NET 反混淆器和解包器.
- [de4js](https://github.com/lelinhtinh/de4js) - JavaScript 反混淆器和解包器.
- [Defacto2 Analyzers Archive](https://defacto2.net/f/aa2e6ec) - 从 1990 年代和 2000 年代收集 60 个用于 MS-DOS 和 Windows32 的二进制文件分析器.
- [Defacto2 Packers Archive](https://defacto2.net/f/a520164) - 从 1990 年代和 2000 年代收集 460 个用于 MS-DOS 和 Windows32 的二进制和数据文件打包程序.
- [Defacto2 Unpackers Archive](https://defacto2.net/f/a218ab4) - 从 1990 年代和 2000 年代收集 152 个用于 MS-DOS 和 Windows 32 的二进制文件解包器.
- [DIE](https://github.com/horsicq/DIE-engine/releases)  - 轻松检测； 用于确定文件类型的程序.
- [Emulator](https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/Using-policies-to-manage-security/preventing-and-handling-virus-and-spyware-attacks-v40739565-d49e172/how-does-the-emulator-in-symantec-endpoint-protect-v121004909-d47e230.html) - Symantec Endpoint Protector（从 v14 开始）能够动态创建虚拟机，以识别、引爆和消除隐藏在自定义恶意软件打包程序中的恶意软件.
- [EtherUnpack](https://ether.gtisc.gatech.edu/web_unpack) - 精密通用自动拆包机（PolyUnpack 的继任者）.
- [Eureka](https://web.archive.org/web/20150502154942/http://eureka.cyber-ta.org/) - 二进制静态分析准备框架，实现基于统计二元分析和粗粒度执行跟踪的新型二进制解包策略.
- [EXEInfo-PE](https://github.com/ExeinfoASL/ASL) - 可执行PE文件的快速检测器.
- [ExeScan](https://defacto2.net/f/ae2c42e) - 可执行文件分析器，可检测最著名的 EXE/COM 保护程序、打包程序、转换器和编译器.
- [EXETools](https://forum.exetools.com) - 逆向工程和执行包装相关主题的论坛.
- [FUU](https://github.com/crackinglandia/fuu) - 快速通用解包器.
- [GetTyp](https://www.helger.com/gt/gt.htm) - 基于特殊字符串和字节码的 DOS 文件格式检测程序.
- [GUnpacker](http://qunpack.ahteam.org/?p=327) - 执行 OEP 定位和转储解密代码的 Shell 工具.
- [Justin](https://doi.org/10.1007/978-3-540-87403-4_6)  - 即时 AV 扫描； 通用拆包解决方案.
- [Language 2000](https://farrokhi.net/language) - 终极编译器检测实用程序.
- [LIEF](https://github.com/lief-project/LIEF)  - 仪器可执行格式库； 用于解析 PE、ELF、Mach-O 和 DEX 格式、修改和重建可执行文件的 Python 包.
- [Malheur](https://github.com/rieck/malheur) - 用于自动分析恶意软件行为的工具（从沙盒环境中的恶意软件中记录）.
- [MalUnpack](https://github.com/hasherezade/mal_unpack) - 基于 PE 筛的动态拆包器.
- [Manalyze](https://github.com/JusticeRage/Manalyze) - 强大的 PE 文件解析器，具有灵活的插件架构，允许用户深入静态分析文件.
- [OEPdet](https://ieeexplore.ieee.org/abstract/document/7782073) - 自动原始入口点检测器.
- [OllyDbg Scripts](https://github.com/xshows/ollydbg-script) - OllyDbg 脚本的集合，用于解压许多不同的打包程序.
- [OmniUnpack](https://doi.org/10.1109/ACSAC.2007.15) - 通过实时监控执行并检测已移除的打包层来快速、通用和安全地解包恶意软件的新技术.
- [PackerAttacker](https://github.com/BromiumLabs/PackerAttacker) - 使用内存和代码挂钩来检测加壳程序的工具.
- [PackerBreaker](https://www.portablefreeware.com/forums/viewtopic.php?t=21555) - 用于帮助解包、解压缩和解密大多数使用高级仿真技术打包、压缩或加密的程序的工具.
- [PackerGrind](https://github.com/rewhy/adaptiveunpacker) - 用于跟踪打包行为和解包 Android 打包应用程序的自适应解包工具.
- [PackerID](https://github.com/sooshie/packerid) - 使用 PEid 签名并具有额外的输出类型、格式、数字签名提取和反汇编支持的 packerid.py 的分支.
- [Packing-Box](https://github.com/dhondta/docker-packing-box) - Docker 映像收集许多与打包相关的工具，并用于制作打包可执行文件的数据集以用于机器学习.
- [PANDA](https://github.com/panda-re/panda) - 架构中性动态分析平台.
- [Pandora's Bochs](https://0x0badc0.de/gitweb?p=bochs/.git) - 对 Bochs PC 仿真器的扩展，使其能够监控解包存根的执行以提取原始代码.
- [PCjs](https://www.pcjs.org) - PCjs 使用 JavaScript 重新创建 IBM PC 体验，使用原始 ROM、以原始速度运行的 CPU 以及早期的 IBM 视频卡和显示器.
- [PE Compression Test](http://pect.atspace.com/) - 在几个示例可执行文件上测试的打包程序列表，用于比较压缩大小.
- [PE Detective](https://ntcore.com/?page_id=367) - 这个 GUI 工具可以扫描单个 PE 文件或整个目录（也可以递归）并生成完整的报告.
- [PE-bear](https://github.com/hasherezade/pe-bear-releases) - PE 文件的免费软件反转工具旨在为恶意软件分析师提供快速灵活的“第一视图”，稳定且能够处理格式错误的 PE 文件.
- [Pefeats](https://github.com/roussieau/masterthesis/tree/master/src/detector/tools/pefeats) - 从 PE 文件中提取 119 个特征以用于机器学习算法的实用程序.
- [Pefile](https://github.com/erocarrera/pefile) - 用于解析和使用可移植可执行文件的多平台 Python 模块.
- [PEFrame](https://github.com/guelfoweb/peframe) - 对 PE 恶意软件和通用可疑文件进行静态分析的工具.
- [PEiD](http://www.secretashell.com/codomain/peid/) - 打包的可执行标识符.
- [PEiD (CLI)](https://github.com/dhondta/peid) - PEiD 的 Python 实现具有用于制作新签名的附加工具.
- [PEiD (yara)](https://github.com/K-atc/PEiD) - 使用 yara 的另一种 PEiD 实现.
- [PeLib](https://github.com/avast/pelib) - PE 文件操作库.
- [PEPack](https://github.com/merces/pev) - PE 文件打包器检测工具，属于 Unix 包“pev”的一部分.
- [PEscan](https://tzworks.com/prototype_page.php?proto_id=15) - CLI 工具扫描 PE 文件以识别它们是如何构建的.
- [PETools](https://github.com/petoolse/petools) - 用于操作 PE 文件的老式逆向工程工具（自 2002 年以来有着悠久的历史）.
- [PEview](http://wjradburn.com/software) - 提供一种快速简便的方法来查看 32 位可移植可执行文件 (PE) 和组件对象文件格式 (COFF) 文件的结构和内容.
- [Pin - A Dynamic Binary Instrumentation Tool](https://www.intel.com/content/www/us/en/developer/articles/tool/pin-a-dynamic-binary-instrumentation-tool.html) - 用于 IA-32、x86-64 和 MIC 指令集架构的动态二进制检测框架，可以创建动态程序分析工具.
- [PINdemonium](https://github.com/Phat3/PINdemonium) - 利用 PIN 功能的 PE 文件解包器.
- [PolyUnpack](https://github.com/PlatonovIvan/PolyUnpack) - 尝试在没有任何启发式假设的情况下提取 PE 文件的原始隐藏代码的一般方法.
- [PortEx](https://github.com/katjahahn/PortEx) - 用于对 PE 文件进行静态恶意软件分析的 Java 库.
- [PROTECTiON iD](http://pid.gamecopyworld.com/ProtectionID_v6.1.6_2k9.rar) - 基于PE文件签名的扫描器.
- [ProTools](http://protools.narod.ru) - Programmer&#39;s Tools，一个专门为真正的 WinBloze 程序员提供各种工具和实用程序的网站，包括打包程序、加密程序等.
- [PyPackerDetect](https://github.com/cylance/PyPackerDetect) - 用于检测可执行文件是否已打包的小型 python 脚本/库.
- [PyPackerDetect (refactored)](https://github.com/dhondta/PyPackerDetect) - 将原始项目完整重构为带有控制台脚本的 Python 包，以检测是否打包了可执行文件.
- [PyPeid](https://github.com/FFRI/pypeid) - 使用 yara-python 的另一个 PEiD 实现.
- [Quick Unpack](http://qunpack.ahteam.org/?p=458) - 通用解包器，有助于解包过程.
- [RapidEXE](https://sourceforge.net/projects/rapidexe) - 将 PHP/Python 脚本转换为独立可执行文件的简单有效的方法.
- [RDG Packer Detector](http://www.rdgsoft.net) - 封隔器检测工具.
- [Red Curtain](https://mandiant-red-curtain.apponic.com)  - 协助分析恶意软件的事件响应者的免费软件； 它检查可执行文件（例如，.exe、.dll 等）以根据一组标准确定它们的可疑程度.
- [Reko](https://github.com/uxmal/reko) - 机器代码二进制文件的免费反编译器.
- [REMINDer](https://doi.org/10.1109/CSA.2009.5404211) - 基于入口点部分的熵值和WRITE属性的打包检测工具.
- [REMnux](https://remnux.org) - 用于逆向工程和分析恶意软件的 Linux 工具包.
- [Renovo](https://doi.org/10.1145/1314389.1314399) - 基于TEMU（BitBlaze的动态分析组件）构建的检测工具，基于程序启动后新生成代码的执行和监控内存写入.
- [RetDec](https://github.com/avast/retdec) - 基于 LLVM 的可重定向机器代码反编译器.
- [SAC](https://www.sac.sk/files.php?d=7&l=) - PACK：存档器、exe 压缩器、存档器外壳和其他相关实用程序.
- [SAFE](https://github.com/dhondta/awesome-executable-packing/blob/master/mailto:mihai@cs.wisc.edu) - 可执行文件的静态分析器（按需提供）.
- [ShowStopper](https://github.com/CheckPointSW/showstopper) - 帮助恶意软件研究人员探索和测试反调试技术或验证调试器插件或其他与标准反调试方法冲突的解决方案的工具.
- [SymPack](https://www.amazon.com/Norton-AntiVirus-2007-Old-Version/dp/B000IAOIXW)  - 安全、便携、非常有效但不是用于打包检测和拆包的通用库； 诺顿防病毒解决方案的一部分.
- [Titanium Platform](https://www.reversinglabs.com/products/malware-analysis-platform) - 机器学习混合云平台，可大规模收集数千种文件类型，通过机器学习二进制分析加速威胁检测，并持续监控超过 10B 文件的索引以应对未来威胁.
- [TrID](https://mark0.net/soft-trid-e.html) - 用于从二进制签名中识别文件类型的实用程序.
- [Triton](https://github.com/jonathansalwan/Triton) - 动态二进制分析库.
- [Tuts 4 You](https://tuts4you.com) - 非商业的、独立的社区，致力于分享逆向代码工程的知识和信息.
- [Unipacker](https://github.com/unipacker/unipacker) - 基于仿真的 Windows 二进制文件的自动和平台无关解包器.
- [UnpacMe](https://www.unpac.me) - 自动恶意软件解包服务.
- [Unpckarc](https://web.archive.org/web/20191218043307/http://www.woodmann.com/crackz/Tools/) - 打包的可执行文件检测工具依赖于几种启发式方法.
- [Uunp (IDA Pro plugin)](https://www.hex-rays.com/blog/unpacking-mpressed-pe-dlls-with-the-bochs-plugin/) - IDA Pro 调试器插件模块自动分析和解包打包的二进制文件.
- [VirusTotal](https://www.virustotal.com/gui/) - 用于检测恶意软件的文件分析 Web 服务.
- [VMUnpacker](https://www.leechermods.com/2010/01/vmunpacker-16-latest-version.html) - 基于虚拟机技术的解包器.
- [Winbindex](https://github.com/m417z/winbindex) - Windows 二进制文件的索引，包括可执行文件（如 exe、dll 和 sys 文件）的下载链接.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## Contributing

欢迎投稿！ 请阅读 [contribution guidelines](https://github.com/dhondta/awesome-executable-packing/blob/master/CONTRIBUTING.md) 第一的.
