<div class="github-widget" data-repo="dhondta/awesome-executable-packing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Executable Packing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <a href="https://twitter.com/intent/tweet?text=Awesome%20Executable%20Packing%20-%20A%20curated%20list%20of%20resources%20related%20to%20the%20packing%20of%20various%20executable%20formats%20and%20its%20detection.%0D%0Ahttps%3a%2f%2fgithub%2ecom%2fdhondta%2fawesome-executable-packing%0D%0A&hashtags=awesomelists,malware,malwareresearch,executablepacking,cybersecurity,infosec"><img src="https://img.shields.io/badge/Tweet--lightgrey?logo=twitter&style=social" alt="Tweet" height="20"/></a>

> A curated list of resources related to executable packing (including Portable Executable, Executable and Linkable Format and others) containing references to books, papers, blog posts, and other written resources but also packers and tools for detecting packers and unpacking executables.

*Packing* is the action of modifying an executable in a way that does not modify its purpose. It is generally one or a combination of the following operations:
- bundling: makes a single executable with multiple files
- compression: compresses the executable to reduce its original size
- encryption: obfuscates the executable by encrypting it
- mutation: alters the executable's code so that it uses a modifided instruction set and architecture (e.g. using oligomorphism)
- protection: makes the reversing of the executable harder (i.e. using anti-debugging, anti-tampering or other tricks)
- virtualization: embeds a virtual machine that allows to virtualize executable's instructions






## :books: Literature


### Documentation

- :bar_chart: [Android packers: Separating from the pack](https://www.fortiguard.com/events/759/2014-06-12-android-packers-separating-from-the-pack) (June 2014) 
- :bar_chart: [API deobfuscator: Resolving obfuscated API functions in modern packers](https://www.blackhat.com/docs/us-15/materials/us-15-Choi-API-Deobfuscator-Resolving-Obfuscated-API-Functions-In-Modern-Packers.pdf) (July 2015) 
- :bar_chart: [The art of unpacking](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf) (September 2015) 
- :pushpin: [Cloak and dagger: Unpacking hidden malware attacks](https://symantec-enterprise-blogs.security.com/blogs/expert-perspectives/unpacking-hidden-malware-attacks) (December 2016) 
- :bar_chart: [Dealing with virtualization packers](http://2008.caro.org/downloads/boris_lau_virtualization_obfs.pdf) (May 2008) 
- :scroll: [Implementing your own generic unpacker](https://gsec.hitb.org/materials/sg2015/whitepapers/Julien%20Lenoir%20-%20Implementing%20Your%20Own%20Generic%20Unpacker.pdf) (October 2015) 
- :bar_chart: [One packer to rule them all: Empirical identification, comparison and circumvention of current antivirus detection techniques](https://www.blackhat.com/docs/us-14/materials/us-14-Mesbahi-One-Packer-To-Rule-Them-All-WP.pdf) (July 2014) 
- :scroll: [One packer to rule them all: Empirical identification, comparison and circumvention of current antivirus detection techniques](https://www.blackhat.com/docs/us-14/materials/us-14-Mesbahi-One-Packer-To-Rule-Them-All.pdf) (July 2014) 
- :scroll: [PinDemonium: A DBI-based generic unpacker for Windows executables](https://www.blackhat.com/docs/us-16/materials/us-16-Mariani-Pindemonium-A-Dbi-Based-Generic-Unpacker-For-Windows-Executables-wp.pdf) (July 2016) 
- :bar_chart: [Qualitative and quantitative evaluation of software packers](http://webdiis.unizar.es/~ricardo/files/slides/industrial/slides_NcN-15.pdf) (December 2015) 
- :bar_chart: [Runtime packers testing experiences](https://docs.google.com/a/caro.org/viewer?a=v&pid=sites&srcid=Y2Fyby5vcmd8Y2Fyby13b3Jrc2hvcC0yMDA4fGd4OjZkNzk3MmI2YjZlMWMxZGI) (May 2008) 
- :bar_chart: [Runtime packers: The hidden problem?](https://www.blackhat.com/presentations/bh-usa-06/BH-US-06-Morgenstern.pdf) (July 2006) 
- :bar_chart: [TitanMist: Your first step to reversing nirvana](https://www.reversinglabs.com/blackhat/TitanMist_BlackHat-USA-10-Slides.pdf) (July 2010) 
- :bar_chart: [WaveAtlas: Surfing through the landscape of current malware packers](https://www.virusbulletin.com/virusbulletin/2016/12/vb2015-paper-waveatlas-surfing-through-landscape-current-malware-packers/) (September 2015) 
- :bar_chart: [We can still crack you! General unpacking method for Android Packer (NO ROOT)](https://www.blackhat.com/asia-15/briefings.html#we-can-still-crack-you-general-unpacking-method-for-android-packer-no-root) (September 2015) 
- :bar_chart: [When malware is packing heat](https://www.eurecom.fr/publication/5372) (January 2018)  :star:
- :pushpin: [Writing a packer](https://dr4k0nia.github.io/dotnet/coding/2021/06/24/Writing-a-Packer.html) (June 2021)
- :pushpin: [Writing a simple PE packer in detail](https://github.com/levanvn/Packer_Simple-1) (March 2019)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Scientific Research

- :page_with_curl: [Absent extreme learning machine algorithm with application to packed executable identification](https://link.springer.com/article/10.1007%2Fs00521-014-1558-4) (January 2016) 
- :page_with_curl: [An accurate packer identification method using support vector machine](https://www.jstage.jst.go.jp/article/transfun/E97.A/1/E97.A_253/_article) (January 2014) 
- :notebook: [Adaptive unpacking of Android Apps](https://ieeexplore.ieee.org/document/7985676) (May 2017) 
- :page_with_curl: [All-in-one framework for detection, unpacking, and verification for malware analysis](https://www.hindawi.com/journals/scn/2019/5278137/) (January 2019) 
- :page_with_curl: [Analysis of machine learning approaches to packing detection](https://arxiv.org/abs/2105.00473) (May 2021)  :star:
- :notebook: [Anti-unpacker tricks](http://2008.caro.org/downloads/unpackers.pdf) (May 2008) 
- :notebook: [Application of string kernel based support vector machine for malware packer identification](https://ieeexplore.ieee.org/document/6707043) (August 2013) 
- :notebook: [AppSpear: Bytecode decrypting and DEX reassembling for packed Android malware](https://link.springer.com/chapter/10.1007/978-3-319-26362-5_17) (November 2015) 
- :page_with_curl: [Automatic analysis of malware behavior using machine learning](https://dl.acm.org/doi/10.5555/2011216.2011217) （2011 年 12 月） 
- :notebook: [Automatic static unpacking of malware binaries](https://ieeexplore.ieee.org/document/5328814) (October 2009) 
- :page_with_curl: [BareUnpack: Generic unpacking on the bare-metal operating system](https://www.jstage.jst.go.jp/article/transinf/E101.D/12/E101.D_2017EDP7424/_article) (December 2018) 
- :page_with_curl: [Binary-code obfuscations in prevalent packer tools](https://doi.org/10.1145/2522968.2522972) (October 2013) 
- :page_with_curl: [BinStat tool for recognition of packed executables](http://www.ijofcs.org/abstract-v06n1-pp03.html) (September 2010) 
- :notebook: [BitBlaze: A new approach to computer security via binary analysis](https://link.springer.com/chapter/10.1007/978-3-540-89862-7_1) (December 2008) 
- :notebook: [Boosting scalability in anomaly-based packed executable filtering](https://link.springer.com/chapter/10.1007%2F978-3-642-34704-7_3) (November 2011) 
- :mortar_board: [Building a smart and automated tool for packed malware detections using machine learning](https://dial.uclouvain.be/memoire/ucl/en/object/thesis%3A25193) (June 2020)  :star:
- :notebook: [ByteWise: A case study in neural network obfuscation identification](https://ieeexplore.ieee.org/document/8301720/) (January 2018) 
- :notebook: [Challenging anti-virus through evolutionary malware obfuscation](https://link.springer.com/chapter/10.1007%2F978-3-319-31153-1_11) (April 2016) 
- :page_with_curl: [Classification of packed executables for accurate computer virus detection](http://www.sciencedirect.com/science/article/pii/S0167865508002110) (October 2008)  :star:
- :notebook: [Classifying packed programs as malicious software detected](https://www.semanticscholar.org/paper/Classifying-Packed-Programs-as-Malicious-Software-Osaghae/676f38819a0ed3028acce36f4f11b0c77e4cc0ae) (December 2016) 
- :notebook: [Collective classification for packed executable identification](https://doi.org/10.1145/2030376.2030379) (June 2012) 
- :notebook: [A comparative analysis of classifiers in the recognition of packed executables](https://ieeexplore.ieee.org/abstract/document/8995252) (November 2019) 
- :notebook: [A comparative assessment of malware classification using binary texture analysis and dynamic analysis](https://dl.acm.org/doi/10.1145/2046684.2046689) (September 2011) 
- :notebook: [Comparing malware samples for unpacking: A feasibility study](https://ieeexplore.ieee.org/document/7782073) (August 2016) 
- :page_with_curl: [A consistently-executing graph-based approach for malware packer identification](https://ieeexplore.ieee.org/document/8695825) (April 2019)  :star: :star:
- :notebook: [A control flow graph-based signature for packer identification](https://ieeexplore.ieee.org/document/8170793) (October 2017)  :star: :star:
- :notebook: [Countering entropy measure attacks on packed software detection](https://ieeexplore.ieee.org/document/6181079) (January 2012) 
- :notebook: [Denial-of-service attacks on host-based generic unpackers](https://link.springer.com/chapter/10.1007/978-3-642-11145-7_19) (December 2009) 
- :mortar_board: [Deobfuscation of packed and virtualization-obfuscation protected binaries](https://repository.arizona.edu/handle/10150/202716) (June 2011) 
- :notebook: [Design and development of a new scanning core engine for malware detection](https://ieeexplore.ieee.org/document/6388212) (October 2012) 
- :notebook: [Design and performance evaluation of binary code packing for protecting embedded software against reverse engineering](https://ieeexplore.ieee.org/document/5479571) (May 2010) 
- :notebook: [Detecting packed executable file: Supervised or anomaly detection method?](https://ieeexplore.ieee.org/abstract/document/7784628) (August 2016) 
- :page_with_curl: [Detecting packed executables based on raw binary data](https://www.semanticscholar.org/paper/DETECTING-PACKED-EXECUTABLES-BASED-ON-RAW-BINARY-Nataraja-Jacobb/53371424fb79de29a096e563b07fcae432f4d201) (June 2010) 
- :notebook: [Detecting packed executables using steganalysis](https://ieeexplore.ieee.org/document/7018361) (December 2014) 
- :mortar_board: [Detecting packed PE files: Executable file analysis for the Windows operating system](https://uia.brage.unit.no/uia-xmlui/handle/11250/2823655) (June 2021)  :star:
- :notebook: [Detection of metamorphic malware packers using multilayered LSTM networks](https://www.springerprofessional.de/en/detection-of-metamorphic-malware-packers-using-multilayered-lstm/18635334) (November 2020)  :star:
- :notebook: [Detection of packed executables using support vector machines](https://ieeexplore.ieee.org/document/6016774) (July 2011) 
- :notebook: [Detection of packed malware](https://doi.org/10.1145/2490428.2490431) (August 2012) 
- :notebook: [DexHunter: Toward extracting hidden code from packed Android applications](https://link.springer.com/chapter/10.1007/978-3-319-24177-7_15) (September 2015) 
- :notebook: [Dynamic binary instrumentation for deobfuscation and unpacking](https://hal.inria.fr/inria-00431666) (November 2009) 
- :notebook: [Dynamic classification of packing algorithms for inspecting executables using entropy analysis](https://ieeexplore.ieee.org/document/6703681) (October 2013) 
- :page_with_curl: [Effective, efficient, and robust packing detection and classification](http://www.sciencedirect.com/science/article/pii/S0167404818311040) (January 2018)  :star: :star: :star:
- :notebook: [Efficient and automatic instrumentation for packed binaries](https://link.springer.com/chapter/10.1007/978-3-642-02617-1_32) (June 2009) 
- :page_with_curl: [Efficient automatic original entry point detection](https://jise.iis.sinica.edu.tw/JISESearch/pages/View/PaperView.jsf?keyId=169_2256) (January 2019)  :star:
- :page_with_curl: [An efficient block-discriminant identification of packed malware](https://link.springer.com/article/10.1007%2Fs12046-015-0399-x) (August 2015) 
- :notebook: [Efficient malware packer identification using support vector machines with spectrum kernel](https://ieeexplore.ieee.org/document/6621654) (July 2013) 
- :page_with_curl: [Efficient SVM based packer identification with binary diffing measures](https://ieeexplore.ieee.org/document/8754440/) (July 2019) 
- :page_with_curl: [ELF-Miner: Using structural knowledge and data mining methods to detect new (Linux) malicious executables](https://dl.acm.org/doi/10.5555/2150963.2150968) (March 2012) 
- :page_with_curl: [EMBER: An open dataset for training static PE malware machine learning models](https://arxiv.org/abs/1804.04637) (April 2018) 
- :notebook: [An empirical evaluation of an unpacking method implemented with dynamic binary instrumentation](https://www.jstage.jst.go.jp/article/transinf/E94.D/9/E94.D_9_1778/_article) (September 2011) 
- :notebook: [Encoded executable file detection technique via executable file header analysis](https://www.earticle.net/Article/A105986) (April 2009) 
- :notebook: [Entropy analysis to classify unknown packing algorithms for malware detection](https://link.springer.com/article/10.1007/s10207-016-0330-4) (May 2016)  :star: :star:
- :notebook: [ESCAPE: Entropy score analysis of packed executable](https://dl.acm.org/doi/10.1145/2388576.2388607) (October 2012) 
- :notebook: [Ether: Malware analysis via hardware virtualization extensions](https://doi.org/10.1145/1455770.1455779) (October 2008) 
- :notebook: [Eureka: A framework for enabling static malware analysis](https://link.springer.com/chapter/10.1007%2F978-3-540-88313-5_31) (October 2008) 
- :notebook: [Experimental comparison of machine learning models in malware packing detection](https://ieeexplore.ieee.org/document/9237007) (September 2020)  :star:
- :notebook: [An experimental study on identifying obfuscation techniques in packer](https://docplayer.net/63501103-An-experimental-study-on-identifying-obfuscation-techniques-in-packer.html) (June 2016) 
- :notebook: [A fast flowgraph based classification system for packed and polymorphic malware on the endhost](https://ieeexplore.ieee.org/document/5474800/) (April 2010) 
- :notebook: [Feature set reduction for the detection of packed executables](https://ieeexplore.ieee.org/document/6912767) (June 2014) 
- :notebook: [A fine-grained classification approach for the packed malicious code](https://link.springer.com/chapter/10.1007/978-3-642-34129-8_49) (October 2012) 
- :notebook: [A generic approach to automatic deobfuscation of executable code](https://ieeexplore.ieee.org/document/7163054) (May 2015)  :star:
- :page_with_curl: [Generic packing detection using several complexity analysis for accurate malware detection](https://www.researchgate.net/publication/332594129_Generic_Packing_Detection_using_Several_Complexity_Analysis_for_Accurate_Malware_Detection?channel=doi&linkId=5cbf828b299bf120977ac78a&showFulltext=true) (January 2014) 
- :notebook: [Generic unpacker of executable files](https://www.semanticscholar.org/paper/Generic-Unpacker-of-Executable-Files-Milkovi/413321c5a473d59c18e861c1478cd44f88142275) (April 2015) 
- :notebook: [Generic unpacking method based on detecting original entry point](https://link.springer.com/chapter/10.1007/978-3-642-42054-2_74) (November 2013) 
- :page_with_curl: [Generic unpacking of self-modifying, aggressive, packed binary programs](https://arxiv.org/abs/0905.4581) (May 2009) 
- :notebook: [Generic unpacking techniques](https://ieeexplore.ieee.org/document/4909168) (February 2009) 
- :notebook: [Generic unpacking using entropy analysis](https://ieeexplore.ieee.org/document/5665789) (October 2010) 
- :notebook: [Gunpack: Un outil générique d'unpacking de malwares](https://www.sstic.org/2016/presentation/gunpack/) (June 2016) 
- :notebook: [A heuristic approach for detection of obfuscated malware](https://ieeexplore.ieee.org/document/5137328) (June 2009) 
- :page_with_curl: [A heuristics-based static analysis approach for detecting packed PE binaries](http://dx.doi.org/10.14257/ijsia.2013.7.5.24) (October 2013) 
- :notebook: [An implementation of a generic unpacking method on Bochs Emulator](https://www.semanticscholar.org/paper/An-Implementation-of-a-Generic-Unpacking-Method-on-HyungChanKim-Daisuke/d5c947520815105231673f1b87af57ed6abd379c) (September 2009) 
- :notebook: [Information theoretic method for classification of packed and encoded files](https://dl.acm.org/doi/10.1145/2799979.2800015) (September 2015) 
- :notebook: [Instructions-based detection of sophisticated obfuscation and packing](https://ieeexplore.ieee.org/document/6956729) (October 2014) 
- :page_with_curl: [A learning model to detect maliciousness of portable executable using integrated feature set](https://www.sciencedirect.com/science/article/pii/S1319157817300149) (January 2017) 
- :mortar_board: [Maitland: Analysis of packed and encrypted malware via paravirtualization extensions](https://dspace.library.uvic.ca/handle/1828/3866) (June 2012) 
- :notebook: [Mal-EVE: Static detection model for evasive malware](https://ieeexplore.ieee.org/document/7497952) (August 2015) 
- :page_with_curl: [Mal-flux: Rendering hidden code of packed binary executable](http://www.sciencedirect.com/science/article/pii/S1742287618303736) (March 2019)  :star:
- :page_with_curl: [Mal-XT: Higher accuracy hidden-code extraction of packed binary executable](https://iopscience.iop.org/article/10.1088/1757-899X/453/1/012001) (November 2018) 
- :page_with_curl: [Mal-xtract: Hidden code extraction using memory analysis](https://doi.org/10.1088%2F1742-6596%2F801%2F1%2F012058) (January 2017) 
- :page_with_curl: [Malware analysis using multiple API sequence mining control flow graph](https://arxiv.org/abs/1707.02691) (July 2017) 
- :page_with_curl: [Malware analysis using visualized images and entropy graphs](https://link.springer.com/article/10.1007%2Fs10207-014-0242-0) (February 2015) 
- :notebook: [Malware obfuscation techniques: A brief survey](https://ieeexplore.ieee.org/document/5633410) (November 2010) 
- :notebook: [Malware obfuscation through evolutionary packers](https://doi.org/10.1145/2739482.2764940) (July 2015) 
- :page_with_curl: [Malwise - An effective and efficient classification system for packed and polymorphic malware](https://ieeexplore.ieee.org/document/6171162) (June 2013) 
- :notebook: [McBoost: Boosting scalability in malware collection and analysis using statistical classification of executables](https://ieeexplore.ieee.org/document/4721567) (December 2008) 
- :notebook: [Memory behavior-based automatic malware unpacking in stealth debugging environment](https://ieeexplore.ieee.org/document/5665794) (October 2010) 
- :notebook: [Modern linux malware exposed](https://www.eurecom.fr/fr/publication/5584) (June 2018) 
- :notebook: [MutantX-S: Scalable malware clustering based on static features](https://www.usenix.org/conference/atc13/technical-sessions/presentation/hu) (June 2013) 
- :notebook: [The new signature generation method based on an unpacking algorithm and procedure for a packer detection](https://www.earticle.net/Article/A147420) (February 2011) 
- :page_with_curl: [Obfuscation: The hidden malware](https://ieeexplore.ieee.org/document/5975134) (August 2011) 
- :notebook: [Obfuscation: Where are we in anti-DSE protections? (a first attempt)](https://doi.org/10.1145/3371307.3371309) (December 2019) 
- :notebook: [OmniUnpack: Fast, generic, and safe unpacking of malware](https://ieeexplore.ieee.org/document/4413009) (December 2007)  :star: :star:
- :page_with_curl: [On the adoption of anomaly detection for packed executable filtering](https://www.sciencedirect.com/science/article/pii/S0167404814000522?via%3Dihub) (June 2014) 
- :notebook: [OPEM: A static-dynamic approach for machine-learning-based malware detection](https://link.springer.com/chapter/10.1007/978-3-642-33018-6_28) (September 2012) 
- :page_with_curl: [An original entry point detection method with candidate-sorting for more effective generic unpacking](https://www.jstage.jst.go.jp/article/transinf/E98.D/4/E98.D_2014EDP7268/_article) (January 2015) 
- :page_with_curl: [Packed malware detection using entropy related analysis: A survey](https://api.semanticscholar.org/CorpusID:212493886) (November 2015) 
- :page_with_curl: [Packed malware variants detection using deep belief networks](https://doi.org/10.1051/matecconf/202030902002) （2020 年 3 月）：星：
- :notebook: [Packed PE file detection for malware forensics](https://ieeexplore.ieee.org/document/5404211) (December 2009) 
- :page_with_curl: [Packer analysis report debugging and unpacking the NsPack 3.4 and 3.7 packer](https://www.sans.org/reading-room/whitepapers/malicious/packer-analysis-report-debugging-unpacking-nspack-34-37-packer-33428) (June 2010) 
- :notebook: [Packer classifier based on PE header information](https://dl.acm.org/doi/10.1145/2746194.2746213) (April 2015) 
- :page_with_curl: [Packer detection for multi-layer executables using entropy analysis](https://www.mdpi.com/1099-4300/19/3/125) (March 2017)  :star:
- :notebook: [Packer identification based on metadata signature](https://dl.acm.org/doi/10.1145/3151137.3160687) (December 2017)  :star: :star:
- :notebook: [Packer identification method based on byte sequences](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.5082) (November 2018) 
- :page_with_curl: [Packer identification using byte plot and Markov plot](https://link.springer.com/article/10.1007/s11416-015-0249-8) (September 2015)  :star: :star: :star:
- :notebook: [Packer identification using hidden Markov model](https://link.springer.com/chapter/10.1007/978-3-319-69456-6_8) (November 2017) 
- :mortar_board: [Packer-complexity analysis in PANDA](https://webthesis.biblio.polito.it/7519/) (January 2018) 
- :mortar_board: [Pandora's Bochs: Automatic unpacking of malware](https://www.researchgate.net/publication/268355151_Pandora%27s_Bochs_Automatic_Unpacking_of_Malware) (January 2008) 
- :notebook: [Pattern recognition techniques for the classification of malware packers](https://link.springer.com/chapter/10.1007/978-3-642-14081-5_23) (July 2010)  :star: :star:
- :page_with_curl: [PE file features in detection of packed executables](http://www.ijcte.org/show-42-485-1.html) (January 2012) 
- :notebook: [PE file header analysis-based packed PE file detection technique (PHAD)](https://ieeexplore.ieee.org/document/4654055) (October 2008) 
- :notebook: [PE-Probe: Leveraging packer detection and structural information to detect malicious portable executables](https://www.semanticscholar.org/paper/PE-Probe%3A-Leveraging-Packer-Detection-and-to-Detect-Shafiq-Tabish/9811ec751f2b5bb41ee46c0ee2a3b6eccc39bb9a) (June 2009) 
- :notebook: [PEAL - Packed executable analysis](https://link.springer.com/chapter/10.1007/978-3-642-29280-4_28) (January 2012) 
- :notebook: [PolyUnpack: Automating the hidden-code extraction of unpack-executing malware](https://ieeexplore.ieee.org/document/4041175) (December 2006)  :star:
- :notebook: [Prevalence and impact of low-entropy packing schemes in the malware ecosystem](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24297.pdf) (February 2020)  :star:
- :notebook: [RAMBO: Run-Time packer analysis with multiple branch observation](https://link.springer.com/chapter/10.1007/978-3-319-40667-1_10) (July 2016) 
- :mortar_board: [REFORM: A framework for malware packer analysis using information theory and statistical methods](https://researchrepository.rmit.edu.au/view/delivery/61RMIT_INST/12246783310001341/13248377300001341) (April 2010) 
- :notebook: [Renovo: A hidden code extractor for packed executables](https://dl.acm.org/doi/10.1145/1314389.1314399) (November 2007)  :star:
- :notebook: [RePEconstruct: Reconstructing binaries with self-modifying code and import address table destruction](https://ieeexplore.ieee.org/document/7888727) (October 2016) 
- :notebook: [Research and implementation of compression shell unpacking technology for PE file](https://ieeexplore.ieee.org/document/5231651) (May 2009) 
- :page_with_curl: [Revealing packed malware](https://ieeexplore.ieee.org/document/4639028) (September 2008) 
- :notebook: [Reverse engineering self-modifying code: Unpacker extraction](https://ieeexplore.ieee.org/document/5645447) (October 2010) 
- :notebook: [SATURN - Software deobfuscation framework based on LLVM](https://doi.org/10.1145/3338503.3357721) (November 2019)  :star:
- :page_with_curl: [SCORE: Source code optimization & reconstruction](https://ieeexplore.ieee.org/document/9139493) (July 2020)  :star:
- :notebook: [SE-PAC: A self-evolving packer classifier against rapid packers evolution](https://doi.org/10.1145/3422337.3447848) (April 2021)  :star:
- :page_with_curl: [Secure and advanced unpacking using computer emulation](https://link.springer.com/article/10.1007%2Fs11416-007-0046-0) (August 2007) 
- :notebook: [Semi-supervised learning for packed executable detection](https://ieeexplore.ieee.org/document/6060027) (September 2011) 
- :notebook: [Semi-supervised learning for unknown malware detection](https://link.springer.com/chapter/10.1007/978-3-642-19934-9_53) (April 2011) 
- :page_with_curl: [Sensitive system calls based packed malware variants detection using principal component initialized multilayers neural networks](https://cybersecurity.springeropen.com/articles/10.1186/s42400-018-0010-y) (September 2018)  :star: :star:
- :notebook: [SoK: Deep packer inspection: A longitudinal study of the complexity of run-time packers](https://ieeexplore.ieee.org/document/7163053) (May 2015)  :star: :star: :star:
- :notebook: [SPADE: Signature based packer detection](https://dl.acm.org/doi/10.1145/2490428.2490442) (August 2012) 
- :notebook: [A static, packer-agnostic filter to detect similar malware samples](https://link.springer.com/chapter/10.1007/978-3-642-37300-8_6) (July 2012) 
- :notebook: [Structural feature based anomaly detection for packed executable identification](https://link.springer.com/chapter/10.1007%2F978-3-642-21323-6_29) (June 2011) 
- :notebook: [The study of evasion of packed PE from static detection](https://ieeexplore.ieee.org/document/6280206) (June 2012) 
- :notebook: [A study of the packer problem and its solutions](https://link.springer.com/chapter/10.1007/978-3-540-87403-4_6) (September 2008) 
- :notebook: [Survey on malware evasion techniques: State of the art and challenges](https://ieeexplore.ieee.org/abstract/document/6174775) (February 2012) 
- :notebook: [Syntia: Synthesizing the semantics of obfuscated code](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko) (August 2017)  :star:
- :notebook: [Things you may not know about Android (Un) packers: A systematic study based on whole-system emulation.](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_04A-4_Duan_paper.pdf) (February 2018) 
- :notebook: [Thwarting real-time dynamic unpacking](https://dl.acm.org/doi/10.1145/1972551.1972556) (January 2011) 
- :notebook: [Toward generic unpacking techniques for malware analysis with quantification of code revelation](https://www.researchgate.net/publication/255608911_Toward_Generic_Unpacking_Techniques_for_Malware_Analysis_with_Quantification_of_Code_Revelation) (August 2009) 
- :notebook: [Towards paving the way for large-scale Windows malware analysis: Generic binary unpacking with orders-of-magnitude performance boost](https://dl.acm.org/doi/10.1145/3243734.3243771) (October 2018) 
- :page_with_curl: [Two techniques for detecting packed portable executable files](https://ieeexplore.ieee.org/document/6636333) (June 2013) 
- :notebook: [Unconditional self-modifying code elimination with dynamic compiler optimizations](https://ieeexplore.ieee.org/document/5665795) (October 2010) 
- :notebook: [Understanding linux malware](https://ieeexplore.ieee.org/document/8418602) (May 2018) 
- :mortar_board: [Unpacking framework for packed malicious executables](https://repositorio-aberto.up.pt/bitstream/10216/68815/2/25935.pdf) (July 2013) 
- :page_with_curl: [Unpacking techniques and tools in malware analysis](https://www.scientific.net/AMM.198-199.343) (September 2012) 
- :notebook: [Unpacking virtualization obfuscators](https://dl.acm.org/doi/10.5555/1855876.1855877) (August 2009) 
- :page_with_curl: [UnThemida: Commercial obfuscation technique analysis with a fully obfuscated program](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.2622) (July 2018)  :star:
- :page_with_curl: [Using entropy analysis to find encrypted and packed malware](https://ieeexplore.ieee.org/document/4140989) (March 2007)  :star:
- :notebook: [VMAttack: Deobfuscating virtualization-based packed binaries](https://dl.acm.org/doi/10.1145/3098954.3098995) (August 2017) 
- :page_with_curl: [WYSINWYX: What you see is not what you execute](https://doi.org/10.1145/1749608.1749612) (August 2010) 
- :page_with_curl: [x64Unpack: Hybrid emulation unpacker for 64-bit Windows Environments and detailed analysis results on VMProtect 3.4](https://ieeexplore.ieee.org/document/9139515) (July 2020)  :star:

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :bookmark_tabs: Datasets

- [CyberCrime](https://cybercrime-tracker.net/vx.php) - C² tracking and malware database.
- [Dataset of Packed PE](https://github.com/dhondta/dataset-packed-pe) - Sanitized version of the original dataset, PackingData, removing packed samples from the Notpacked folder but also samples in packer folders that failed to be packed (having a same hash as the original unpacked executable).
- [Ember](https://github.com/elastic/ember) - Collection of features from PE files that serve as a benchmark dataset for researchers.
- [Malfease](https://web.archive.org/web/20141221153307/http://malfease.oarci.net) - Dataset of about 5,000 packed malware samples.
- [Malheur](https://www.sec.cs.tu-bs.de/data/malheur) - 包含记录的恶意软件（malware）行为，并已用于开发对恶意软件行为进行分类和聚类的方法（参见 2011 年的 JCS 文章）。
- [MalShare](https://malshare.com) - Free Malware repository providing researchers access to samples, malicious feeds, and Yara results.
- [MalwareGallery](https://github.com/BaRRaKudaRain/MalwareGallery) - Yet another malware collection in the Internet.
- [OARC Malware Dataset](https://www.dns-oarc.net) - Semi-public dataset of 3,467 samples captured in the wild from Sep 2005 to Jan 2006 by mail traps, user submissions, honeypots and other sources aggregated by the OARC, available to qualified academic and industry researchers upon request.
- [Open Malware](https://web.archive.org/web/20190116100735/http://www.offensivecomputing.net/) - Online collection of malware samples.
- [PackingData](https://github.com/chesvectain/PackingData) - Original dataset with sample PE files packed with a large variety of packers, including ASPack, BeRoEXEPacker, exe32pack, eXpressor, FSG, JDPack, MEW, Molebox, MPRESS, Neolite, NSPack, Pckman, PECompact, PEtite, RLPack, UPX, WinUpack, Yoda's Crypter and Yoda's Protector.
- [Packware](https://github.com/ucsb-seclab/packware) - Datasets and codes that are needed to reproduce the experiments in the paper "When Malware is Packing Heat".
- [Runtime Packers Testset](https://www.researchgate.net/publication/268030543_Runtime_Packers_The_Hidden_Problem) - Dataset of 10 common Malware files, packed with about 40 different runtime packers in over 500 versions and options, with a total of about 5,000 samples.
- [SOREL](https://github.com/sophos-ai/SOREL-20M) - Sophos-ReversingLabs 20 Million dataset.
- [theZoo](https://github.com/ytisf/theZoo) - Project created to make the possibility of malware analysis open and available to the public.
- [ViruSign](https://www.virusign.com) - Another online malware database.
- [VirusShare](https://virusshare.com) - Virus online database with more thant 44 millions of samples.
- [VX Heaven](https://web.archive.org/web/20170817143838/http://vxheaven.org/) - Site dedicated to providing information about computer viruses.
- [VX Underground](https://vx-underground.org/samples.html) - PL-CERT based open source MWDB python application holding a malware database containing every APT sample from 2010 and over 7.5M malicious
binaries.
- [VXvault](http://vxvault.net/ViriList.php) - Online malware database.
- [WildList](http://www.wildlist.org/CurrentList.txt) - Cooperative listing of malwares reported as being in the wild by security professionals.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :package: Packers

### After 2010

- [.netshrink](https://www.pelock.com/products/netshrink) - Executable compressor for your Windows or Linux .NET application executable file using LZMA.
- [Alienyze](https://alienyze.com) - Advanced software protection and security for Windows 32-bit executables.
- [Alternate EXE Packer](https://www.alternate-tools.com/pages/c_exepacker.php) - Compression tool for executable files (type EXE) or DLL's relying on UPX 3.96.
- [Amber](https://github.com/EgeBalci/amber/releases) - Position-independent(reflective) PE loader that enables in-memory execution of native PE files(EXE, DLL, SYS).
- [Andromeda](https://blog.morphisec.com/andromeda-tactics-analyzed) - Custom packer used in malware campaigns using RunPE techniques for evading AV mitigation methods.
- [APKProtect](https://sourceforge.net/projects/apkprotect) - APK encryption and shell protection supporting Java and C++.
- [Armadillo](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/protectors/win/armd252b2.zip) - Incorporates both a license manager and wrapper system for protecting PE files.
- [ASPack](http://www.aspack.com/aspack.html) - Advanced solution created to provide Win32 EXE file packing and to protect them against non-professional reverse engineering.
- [ASProtect 32](http://www.aspack.com/asprotect32.html) - Multifunctional EXE packing tool designed for software developers to protect 32-bit applications with in-built application copy protection system.
- [ASProtect 64](http://www.aspack.com/asprotect64.html) - Tool for protecting 64-bit applications and .NET applications for Windows against unauthorized use, industrial and home copying, professional hacking and analysis of software products distributed over the Internet and on any physical media.
- [AutoIT](https://www.autoitscript.com/site) - Legitimate executable encryption service.
- [AxProtector](https://www.wibu.com/us/products/protection-suite/axprotector.html) - Encrypts the complete software you aim to protect, and shields it with a security shell, AxEngine, best-of-breed anti-debugging and anti-disassembly methods are then injected into your software.
- [BangCle](https://github.com/woxihuannisja/Bangcle) - Protection tool using the second generation Android Hardening Protection, loading the encrypted DEX file from memory dynamically.
- [Bero](https://blog.rosseaux.net/page/875fbe6549aa072b5ee0ac9cefff4827/BeRoEXEPacker) - Bero EXE Packer (BEP) for 32-bit windows executables.
- [BIN-crypter](https://www.autoitscript.com/forum/topic/129383-bin-crypter/) - EXE protection software against crackers and decompilers.
- [Code Virtualizer](https://www.oreans.com/CodeVirtualizer.php) - Code Virtualizer is a powerful code obfuscation system for Windows, Linux and macOS applications that helps developers to protect their sensitive code areas against Reverse Engineering with very strong obfuscation code, based on code virtualization.
- [ConfuserEx](https://github.com/mkaring/ConfuserEx) - An open-source, free protector for .NET applications.
- [Crinkler](https://github.com/runestubbe/Crinkler) - Compressing linker for Windows, specifically targeted towards executables with a size of just a few kilobytes.
- [DarkCrypt](https://totalcmd.net/plugring/darkcrypttc.html) - Simply and powerful plugin for Total Commander used for file encryption using 100 algorithms and 5 modes.
- [DexGuard](https://www.guardsquare.com/en/products/dexguard) - Android app obfuscation & security protocols for mobile app protection.
- [DexProtector](https://dexprotector.com/) - Multi-layered RASP solution that secures your Android and iOS apps against static and dynamic analysis, illegal use and tampering.
- [DotBundle](https://web.archive.org/web/20160508074421/http://www.dotbundle.com:80/download.html) - GUI tool to compress, encrypt ad password-protect a .NET application or embed .NET libraries.
- [DotNetZ](https://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/NETZ.shtml) - Straightforward and lightweight, command-line piece of software written in C that allows you to compress and pack Microsoft .NET Framework executable files.
- [ElecKey](https://www.sciensoft.com) - Suite of software and tools that offer a complete solution for software protection, copy protection, and license management.
- [ELFuck](https://github.com/timhsutw/elfuck) - ELF packer for i386 original version from sk2 by sd.
- [Enigma Protector](https://www.enigmaprotector.com) - Professional system for executable files licensing and protection.
- [Enigma Virtual Box](https://www.enigmaprotector.com/en/aboutvb.html) - Application virtualization system for Windows.
- [Eronona-Packer](https://github.com/Eronana/packer) - This is a packer for exe under win32.
- [EXE Bundle](https://www.webtoolmaster.com/exebundle.htm) - Bundles application files into a single PE32 file.
- [EXE Stealth](http://www.webtoolmaster.com/packer.htm) - Anti-cracking protection and licensing tool for PE files featuring compression and encryption polymorphic technology.
- [Ezuri](https://github.com/guitmz/ezuri/blob/master/ezuri.go) - A Simple Linux ELF Runtime Crypter.
- [GzExe](https://git.savannah.gnu.org/cgit/gzip.git) - Utility that allows to compress executables as a shell script.
- [hXOR-Packer](https://github.com/rurararura/hXOR-Packer) - PE packer with Huffman compression and XOR encryption.
- [LIAPP](https://liapp.lockincomp.com) - Easiest and most powerful mobile app security solution.
- [LM-X License Manager](https://www.x-formation.com/lm-x-license-manager) - LM-X License Manager lets you protect your products against piracy by enforcing various levels of security, save time, and reduce business risks.
- [m0dern_p4cker](https://github.com/n4sm/m0dern_p4cker) - Just a modern packer for elf binaries ( works on linux executables only ).
- [MidgetPack](https://github.com/arisada/midgetpack) - Midgetpack is a binary packer for ELF binaries, such as burneye, upx or other tools.
- [MPRESS](https://www.autohotkey.com/mpress/mpress_web.htm) - Compresses (using LZMA) and protects PE, .NET or Mach-O programs against reverse engineering.
- [NetCrypt](https://github.com/friedkiwi/netcrypt) - A proof-of-concept packer for .NET executables, designed to provide a starting point to explain the basic principles of runtime packing.
- [Obsidium](http://www.obsidium.de/show.php?home) - Feature-rich professional software protection and licensing system designed as a cost effective and easy to implement, yet reliable and non-invasive way to protect your 32- and 64-bit Windows software applications and games from reverse engineering.
- [Origami](https://github.com/dr4k0nia/Origami) - Packer compressing .net assemblies, (ab)using the PE format for data storage.
- [Pakkero](https://github.com/89luca89/pakkero) - Pakkero is a binary packer written in Go made for fun and educational purpose.
- [Papaw](https://github.com/dimkr/papaw) - Permissively-licensed packer for ELF executables using LZMA Zstandard or Deflate compression.
- [PE-Packer](https://github.com/czs108/PE-Packer) - Simple packer for Windows 32-bits PE files.
- [PE-Toy](https://github.com/r0ngwe1/petoy) - A PE file packer.
- [PELock](https://www.pelock.com) - Software protection system for Windows executable files ; protects your applications from tampering and reverse engineering, and provides extensive support for software license key management, including support for time trial periods.
- [PePacker](https://github.com/SamLarenN/PePacker) - Simple PE Packer Which Encrypts .text Section I release a simple PE file packer which encrypts the .text section and adds a decryption stub to the end of the last section.
- [PEShield](https://webscene.ir/tools/show/PE-SHIELD-0.25) - PE-SHiELD is a program, which encrypts 32-bit Windows EXE files, leaving them still executable.
- [PEtite](https://www.un4seen.com/petite/) - Free Win32 (Windows 95/98/2000/NT/XP/Vista/7/etc) executable (EXE/DLL/etc) compressor.
- [sePACKER](https://sourceforge.net/projects/sepacker/) - Simple Executable Packer is compressing executables' code section inorder to decrease size of binary files.
- [Silent-Packer](https://github.com/SilentVoid13/Silent_Packer) - Silent Packer is an ELF / PE packer written in pure C.
- [Simple-PE32-Packer](https://github.com/z3r0d4y5/Simple-PE32-Packer) - Simple PE32 Packer with aPLib compression library.
- [Smart Packer](https://www.smartpacker.nl) - Packs 32 & 64bit applications with DLLs, data files, 3rd party run-time into one single executable that runs instantly, with no installs or hassles.
- [theArk](https://github.com/aaaddress1/theArk) - Windows x86 PE Packer In C++.
- [Themida](https://www.oreans.com/themida.php) - From Renovo paper: Themida converts the original x86 instructions into virtual instructions in its own randomized instruction set, and then interpret these virtual instructions at run-time.
- [UPX](https://upx.github.io/) - Ultimate Packer for eXecutables.
- [Ward](https://github.com/ex0dus-0x/ward) - This is a simple implementation of an ELF packer that creates stealthy droppers for loading malicious ELFs in-memory.
- [xorPacker](https://github.com/nqntmqmqmb/xorPacker) - Simple packer working with all PE files which cipher your exe with a XOR implementation.
- [ZProtect](http://www.jiami.net) - Renames metadata entities and supports advanced obfuscation methods that harden protection scheme and foil reverse engineering altogether.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Between 2000 and 2010

- [20to4](http://20to4.net) - Executable compressor that is able to stuff about 20k of finest code and data into less than 4k.
- [ACProtect](https://www.yaldex.com/Bestsoft/Utilities/acprotect.htm) - Application that allows to protect Windows executable files against piracy, using RSA to create and verify the registration keys and unlock code.
- [AHPack](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/ahpacker01byfeuerraderahteam) - PE and PE+ file packer.
- [Application Protector](https://sourceforge.net/projects/balaji/) - Tool for protecting Windows applications.
- [AT4RE Protector](https://en.52yma.com/thread-5444-1-1.html) - 在 ASM 中编程的非常简单的 PE 文件保护器。
- [AverCryptor](https://web.archive.org/web/20071012084924/http://secnull.org) - Small and very handy utility designed to encrypt notes in which you can store any private information - it helps to hide your infection from antiviruses.
- [BurnEye](https://packetstormsecurity.com/files/29691/burneye-1.0-linux-static.tar.gz.html) - Burneye ELF encryption program, x86-linux binary.
- [ByteBoozer](https://csdb.dk/release/?id=33093) - Commodore 64 executable packer.
- [EXE Guarder](http://www.exeicon.com/exeguarder) - Licensing tool for PE files allowing to compress and specify a password notice.
- [EXE Wrapper](https://web.archive.org/web/20160331144211/http://533soft.com/exewrapper) - Protects any EXE file with a password from non-authorized execution.
- [Exe32Pack](https://exe32pack.apponic.com/) - Compresses Win32 EXEs, DLLs, etc and dynamically expands them upon execution.
- [EXECryptor](https://execryptor.freedownloadscenter.com/windows) - Protects EXE programs from reverse engineering, analysis, modifications and cracking.
- [eXPressor](https://www.cgsoftlabs.ro/express.html) - Used as a compressor this tool can compress EXE files to half their normal size.
- [FSG](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/compressors/win/fsg.zip) - *Fast Small Good*, perfect compressor for small exes, eg.
- [GHF Protector](https://www.delphibasics.info/home/delphibasicscounterstrikewireleases/ghfprotector10) - Executable packer / protector based on open source engines Morphine and AHPack.
- [Kkrunchy](http://www.farbrausch.de/~fg/kkrunchy) - Kkrunchy is a small exe packer primarily meant for 64k intros.
- [mPack](https://blog.fearcat.in/a?ID=00050-86a031da-e36f-4409-9a08-d3d993dbf8f5) - mPack - mario PACKersimple Win32 PE Executable compressor.
- [NSPack](https://nspack.apponic.com/) - 32/64-bits exe, dll, ocx, scr Windows program compressor.
- [NTPacker](https://hacking-software-free-download.blogspot.com/2013/02/nt-packer-v21.html) - PE file packer relying on aPlib for compression and/or XOR for encryption.
- [PECompact](http://www.bitsum.com/pec2.asp) - Windows executable compressor featuring third-party plug-ins offering protection against reverse engineering.
- [RLPack](https://web.archive.org/web/20070527132336/http://rlpack.jezgra.net) - Compresses your executables and dynamic link libraries in a way that keeps them small and has no effect on compressed file functionality.
- [Sentinel HASP Envelope](https://cpl.thalesgroup.com/en-gb/software-monetization/all-products/sentinel-hasp) - Wrapping application that protects the target application with a secure shield, providing a means to counteract reverse engineering and other anti-debugging measures.
- [Shiva](https://packetstormsecurity.com/files/31087/shiva-0.95.tar.gz.html) - Shiva is a tool to encrypt ELF executables under Linux.
- [Shrinker](https://web.archive.org/web/20081022073034/http://www.blinkinc.com/shrinker.htm) - Compresses (up to 70%) 16 and 32 bit Windows and real mode DOS programs.
- [tElock](https://www.softpedia.com/get/Programming/Packers-Crypters-Protectors/Telock.shtml) - Telock is a practical tool that intends to help developers who want to protect their work and reduce the size of the executable files.
- [TTProtect](http://www.ttprotect.com) - Professional protection tool designed for software developers to protect their PE applications against illegal modification or decompilation.
- [WinLite](http://www.win3x.org/win3board/viewtopic.php?t=1435&language=en) - Compresses Windows executables (such as Pklite, Diet or Wwpack) for executables programs under DOS.
- [WinUpack](https://www.sac.sk/download/pack/wupck039.zip) - Graphical interface for Upack, a command-line program used to create self-extracting archives from Windows PE files.
- [XComp](http://www.soft-lab.de/JoKo/index_old.htm) - PE32 映像文件打包器和重建器。
- [Yoda Crypter](https://sourceforge.net/projects/yodap/files/Yoda%20Crypter/1.3/yC1.3.zip/download) - Supports polymorphic encryption, softice detection, anti-debug API's, anti-dumping, etc, encrypts the Import Table and erases PE Header.
- [Yoda Protector](http://yodap.sourceforge.net) - Free, open source, Windows 32-bit software protector.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

### Before 2000

- [32Lite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/32lte02d.zip) - Compression tool for executable files created with Watcom C/C++ compiler.
- [624](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/624-11.zip) - COM packer that can compress COM programs shorter than 25000 bytes.
- [AinEXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/ain232.zip) - DOS executable packer.
- [aPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/apack099.zip) - 16-bit real-mode DOS executable ( .EXE and .COM ) compressor.
- [AVPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/avpck122.zip) - Encrypts EXE or COM files so that they'll be able to start on your PC only.
- [AXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/axe22.zip) - Program compression utility.
- [CEXE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/cexe10a.zip) - Compresses an input EXE into a smaller executable (only runs on WinNT, Win2000 and above - won't run on Win95 or Win98).
- [EPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/epack16.zip) - EXE and COM file compressor ; works with DOS/Windows95 files.
- [LGLZ](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/lglz104b.zip) - DOS EXE and COM file compressor using modified LZ77.
- [LzExe](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/lzexe100.zip) - MS-DOS executable file compressor.
- [Megalite](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/megal120.zip) - MS-DOS executable file compressor.
- [PACK](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/pack201.zip) - Executable files compressor.
- [PCShrink](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/pcsnk071.zip) - Windows 9x/NT executable file compressor relying on the aPLib compression library.
- [PE Diminisher](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/ped.zip) - Simple PE packer relying on the aPLib compression library.
- [PE-Protector](https://web.archive.org/web/20030324043555/https://www.exetools.com/files/protectors/win/pe-protector10.zip) - Encrypter/protector for Windows 9x/ME to protect executable files PE
against reverse engineering or cracking with a very strong protection.
- [PEBundle](http://www.collakesoftware.com/files/pebsetup.exe) - Physically attaches DLL(s) to an executable, resolving dependencies in memory.
- [PEPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/win/pepack10.zip) - PE compression tool based on the code of a newer version of PE-SHiELD.
- [Pro-Pack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/pp219.zip) - DOS executable file compressor.
- [RJCrush](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/rjcru110.zip) - EXE and COM files compressor with the ability to compress overlays.
- [SecuPack](https://web.archive.org/web/20210119235522/https://www.exetools.com/files/compressors/win/secupack15.zip) - Win32 executable compressor.
- [SysPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/syspack.zip) - Device drivers compressor.
- [T-Pack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/tpack05.zip) - Executable COM-FILE  compressor (LZ77) optimized for small files like BBS-Addys or similar files.
- [TinyProg](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/tinyp39.zip) - EXE and COM programs compressor.
- [Vacuum](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/vacuum.zip) - Runtime Compressor for DOS32 executables.
- [VGCrypt](https://github.com/dhondta/awesome-executable-packing/blob/master/ftp://ftp.cdrom.com/.3/sac/security/vgcrypt.zip) - PE crypter for Win95/98/NT.
- [WWPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/wwp305b5.zip) - Squeezes EXE files, compresses relocation tables, optimizes headers, protects EXE files from hacking.
- [XE](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/xe145-0119.zip) - DOS executable compression utility.
- [XPA](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/xpa.zip) - DOS executable packer.
- [XPack](https://web.archive.org/web/20060111104142/http://www.exetools.com/files/compressors/dos/xpak167m.zip) - PE32 映像文件打包器和重建器。

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## :wrench: Tools

- [.NET Deobfuscator](https://github.com/NotPrab/.NET-Deobfuscator) - List of .NET Deobfuscators and Unpackers.
- [Android Unpacker](https://github.com/strazzere/android-unpacker) - Android Unpacker presented at Defcon 22: Android Hacker Protection Level 0.
- [APKiD](https://github.com/rednaga/APKiD) - Android application Identifier for packers, protectors, obfuscators and oddities - PEiD for Android.
- [aPLib](https://ibsensoftware.com/products_aPLib.html) - Compression library based on the algorithm used in aPACK.
- [AppSpear](https://github.com/UchihaL/AppSpear) - Universal and automated unpacking system suitable for both Dalvik and ART.
- [Assiste (Packer)](https://assiste.com/Packer.html) - Assiste.com's example list of packers.
- [AVClass](https://github.com/malicialab/avclass) - Python tools to tag / label malware samples.
- [Bintropy](https://github.com/dhondta/bintropy) - Prototype analysis tool that estimates the likelihood that a binary file contains compressed or encrypted bytes.
- [BinUnpack](https://doi.org/10.1145/3243734.3243771) - Unpacking approach free from tedious memory access monitoring, therefore introducing very small runtime overhead.
- [BitBlaze](http://bitblaze.cs.berkeley.edu/release/index.html) - Analysis platform that features a novel fusion of static and dynamic analysis techniques, mixed concrete and symbolic execution, and whole-system emulation and binary instrumentation, all to facilitate state-of-the art research on real security problems.
- [Clamscan Unpacker](https://clamunpacker.sourceforge.io/) - Unpacker derived from ClamAV.
- [de4dot](https://github.com/0xd4d/de4dot) - .NET deobfuscator and unpacker.
- [de4js](https://github.com/lelinhtinh/de4js) - JavaScript Deobfuscator and Unpacker.
- [Defacto2 Packers Archive](https://defacto2.net/f/a520164) - MS-DOS & Windows32 binary file packers.
- [DIE](https://github.com/horsicq/DIE-engine/releases) - Detect It Easy ; Program for determining types of files.
- [Emulator](https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/Using-policies-to-manage-security/preventing-and-handling-virus-and-spyware-attacks-v40739565-d49e172/how-does-the-emulator-in-symantec-endpoint-protect-v121004909-d47e230.html) - Symantec Endpoint Protector (from v14) capability to create a virtual machine on the fly to identify, detonate, and eliminate malware hiding inside custom malware packers.
- [EtherUnpack](https://ether.gtisc.gatech.edu/web_unpack) - Precision universal automated unpacker (successor of PolyUnpack).
- [Eureka](https://web.archive.org/web/20150502154942/http://eureka.cyber-ta.org/) - Binary static analysis preparation framework implementing a novel binary unpacking strategy based on statistical bigram analysis and coarse-grained execution tracing.
- [EXEInfo-PE](https://github.com/ExeinfoASL/ASL) - Fast detector for executable PE files.
- [EXETools](https://forum.exetools.com) - Forum for reverse engineering and executale packing related topics.
- [FUU](https://github.com/crackinglandia/fuu) - Fast Universal Unpacker.
- [GUnpacker](http://qunpack.ahteam.org/?p=327) - Shell tool that performs OEP positioning and dumps decrypted code.
- [Justin](https://doi.org/10.1007/978-3-540-87403-4_6) - Just-In-Time AV scanning ; generic unpacking solution.
- [Malheur](https://github.com/rieck/malheur) - Tool for the automatic analysis of malware behavior (recorded from malicious software in a sandbox environment).
- [MalUnpack](https://github.com/hasherezade/mal_unpack) - Dynamic unpacker based on PE-sieve.
- [Manalyze](https://github.com/JusticeRage/Manalyze) - Robust parser for PE files with a flexible plugin architecture which allows users to statically analyze files in-depth.
- [OEPdet](https://ieeexplore.ieee.org/abstract/document/7782073) - Automated original-entry-point detector.
- [OllyDbg Scripts](https://github.com/xshows/ollydbg-script) - Collection of OllyDbg scripts for unpacking many different packers.
- [OmniUnpack](https://doi.org/10.1109/ACSAC.2007.15) - New technique for fast, generic, and safe unpacking of malware by monitoring the execution in real-time and detecting the removed layers of packing.
- [PackerAttacker](https://github.com/BromiumLabs/PackerAttacker) - Tool that uses memory and code hooks to detect packers.
- [PackerBreaker](https://www.portablefreeware.com/forums/viewtopic.php?t=21555) - Tool for helping unpack, decompress and decrypt most of the programs packed, compressed or encrypted using advanced emulation technology.
- [PackerGrind](https://github.com/rewhy/adaptiveunpacker) - Adaptive unpacking tool for tracking packing bahaviors and unpacking Android packed apps.
- [PackerID](https://github.com/sooshie/packerid) - Fork of packerid.py using PEid signatures and featuring additional output types, formats, digital signature extraction, and disassembly support.
- [Packing-Box](https://github.com/dhondta/docker-packing-box) - Docker image gathering many packing-related tools and for making datasets of packed executables for use with machine learning.
- [Pandora's Bochs](https://0x0badc0.de/gitweb?p=bochs/.git) - Extension to the Bochs PC eumlator to enable it to monitor execution of the unpacking stubs for extracting the original code.
- [PE Compression Test](http://pect.atspace.com/) - List of packers tested on a few sample executables for comparing compressed sizes.
- [PE Detective](https://ntcore.com/?page_id=367) - This GUI tool can scan single PE files or entire directories (also recursevely) and generate complete reports.
- [PE-bear](https://github.com/hasherezade/pe-bear-releases) - Freeware reversing tool for PE files aimed to deliver fast and flexible “first view” for malware analysts, stable and capable to handle malformed PE files.
- [Pefeats](https://github.com/roussieau/masterthesis/tree/master/src/detector/tools/pefeats) - Utility for extracting 119 features from a PE file for use with machine learning algorithms.
- [Pefile](https://github.com/erocarrera/pefile) - Multi-platform Python module to parse and work with Portable Executable files.
- [PEFrame](https://github.com/guelfoweb/peframe) - Tool for performing static analysis on PE malware and generic suspicious files.
- [PEiD](http://www.secretashell.com/codomain/peid/) - Packed Executable iDentifier.
- [PEiD (reborn)](https://github.com/dhondta/peid) - Python implementation of PEiD featuring an additional tool for making new signatures.
- [PEiD (yara)](https://github.com/K-atc/PEiD) - Yet another implementation of PEiD with yara.
- [PeLib](https://github.com/avast/pelib) - PE file manipulation library.
- [PEPack](https://github.com/merces/pev) - PE file packer detection tool, part of the Unix package "pev".
- [PINdemonium](https://github.com/Phat3/PINdemonium) - Unpacker for PE files exploiting the capabilities of PIN.
- [PolyUnpack](https://github.com/PlatonovIvan/PolyUnpack) - Implemention attempt of the general approach for extracting the original hidden code of PE files without any heuristic assumptions.
- [PortEx](https://github.com/katjahahn/PortEx) - Java library for static malware analysis of PE files.
- [PROTECTiON iD](http://pid.gamecopyworld.com/ProtectionID_v6.1.6_2k9.rar) - PE file signature-based scanner.
- [ProTools](http://protools.narod.ru/) - Programmer's Tools, a web site dedicated for all kinds of tools and utitlities for the true WinBloze programmer, including packers, crypters, etc.
- [PyPackerDetect](https://github.com/cylance/PyPackerDetect) - Small python script/library to detect whether an executable is packed.
- [PyPackerDetect (refactored)](https://github.com/dhondta/PyPackerDetect) - A complete refactoring of the original project to a Python package with a console script to detect whether an executable is packed.
- [PyPeid](https://github.com/FFRI/pypeid) - Yet another implementation of PEiD with yara-python.
- [Quick Unpack](http://qunpack.ahteam.org/?p=458) - Generic unpacker that facilitates the unpacking process.
- [RapidEXE](https://sourceforge.net/projects/rapidexe/) - Simple and efficient way to convert a PHP/Python script to a standalone executable.
- [RDG Packer Detector](http://www.rdgsoft.net/) - Packer detection tool.
- [Red Curtain](https://mandiant-red-curtain.apponic.com) - Free software for Incident Responders that assists with the analysis of malware ; it examines executable files (e.g., .exe, .dll, and so on) to determine how suspicious they are based on a set of criteria.
- [REMINDer](https://doi.org/10.1109/CSA.2009.5404211) - Packing detection tool based on the entropy value of the entry point section and the WRITE attribute.
- [Renovo](https://doi.org/10.1145/1314389.1314399) - Detection tool built on top of TEMU (dynamic analysis component of BitBlaze) based on the execution of newly-generated code and monitoring memory writes after the program starts.
- [RetDec](https://github.com/avast/retdec/releases) - Retargetable machine-code decompiler based on LLVM.
- [SAC](https://www.sac.sk/files.php?d=7&l=) - PACK: Archivers, exe-compressors, archiver shells and other related utils.
- [SymPack](https://www.amazon.com/Norton-AntiVirus-2007-Old-Version/dp/B000IAOIXW) - Safe, portable, largely eﬀective but not generic library for packing detection and unpacking ; part of the Norton Antivirus solution.
- [Titanium Platform](https://www.reversinglabs.com/products/malware-analysis-platform) - Machine learning hybrid cloud platform that harvests thousands of file types at scale, speeds threat detection through machine learning binary analysis, and continuously monitors an index of over 10B files for future threats.
- [Tuts 4 You](https://tuts4you.com/) - Non-commercial, independent community dedicated to the sharing of knowledge and information on reverse code engineering.
- [Unipacker](https://github.com/unipacker/unipacker) - Automatic and platform-independent unpacker for Windows binaries based on emulation.
- [UnpacMe](https://www.unpac.me/#/) - Automated malware unpacking service.
- [Unpckarc](https://web.archive.org/web/20191218043307/http://www.woodmann.com/crackz/Tools/) - Packed executables detection tool relying on several heuristics.
- [Uunp (IDA Pro plugin)](https://www.hex-rays.com/blog/unpacking-mpressed-pe-dlls-with-the-bochs-plugin/) - IDA Pro debugger plug-in module automating the analysis and unpacking of packed binaries.
- [VirusTotal](https://www.virustotal.com/gui/) - File analysis Web service for detecting malware.
- [VMUnpacker](https://www.leechermods.com/2010/01/vmunpacker-16-latest-version.html) - Unpacker based on the technology of virtual machine.

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>



## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://github.com/dhondta/awesome-executable-packing/blob/master/CONTRIBUTING.md) first.
