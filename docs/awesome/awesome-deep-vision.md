<div class="github-widget" data-repo="kjw0612/awesome-deep-vision"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Deep Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

灵感来自于计算机视觉的深度学习资源的精选列表 [awesome-php](https://github.com/ziadoz/awesome-php) 和 [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

维护者 -  [Jiwon Kim](https://github.com/kjw0612), [Heesoo Myeong](https://github.com/hmyeong), [Myungsub Choi](https://github.com/myungsub), [Jung Kwon Lee](https://github.com/deruci), [Taeksoo Kim](https://github.com/jazzsaxmafia)

 我们正在寻找维护者！  如果有兴趣，请告诉我（jiwon@alum.mit.edu）.

## Contributing
请随意 [pull requests](https://github.com/kjw0612/awesome-deep-vision/pulls) 添加论文.

[![Join the chat at https://gitter.im/kjw0612/awesome-deep-vision](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/kjw0612/awesome-deep-vision?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Sharing
+ [Share on Twitter](http://twitter.com/home?status=http://jiwonkim.org/awesome-deep-vision%0ADeep Learning Resources for Computer Vision)
+ [Share on Facebook](http://www.facebook.com/sharer/sharer.php?u=https://jiwonkim.org/awesome-deep-vision)
+ [Share on Google Plus](http://plus.google.com/share?url=https://jiwonkim.org/awesome-deep-vision)
+ [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://jiwonkim.org/awesome-deep-vision&title=Awesome%20Deep%20Vision&summary=&source=)


## Papers

### ImageNet Classification
![classification](https://cloud.githubusercontent.com/assets/5226447/8451949/327b9566-2022-11e5-8b34-53b4a64c13ad.PNG)
（来自Alex Krizhevsky，Ilya Sutskever，Geoffrey E. Hinton，ImageNet分类与深度卷积神经网络，NIPS，2012年.）
*微软（深度学习） [[Paper](http://arxiv.org/pdf/1512.03385v1.pdf)][[Slide](http://image-net.org/challenges/talks/ilsvrc2015_deep_residual_learning_kaiminghe.pdf)]
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Deep Residual Learning for Image Recognition, arXiv:1512.03385.
* Microsoft（PReLu /权重初始化）[[论文]]（http://arxiv.org/pdf/1502.01852）
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification, arXiv:1502.01852.
*批量标准化[[论文]]（http://arxiv.org/pdf/1502.03167）
  * Sergey Ioffe，Christian Szegedy，批量标准化：通过减少内部协变量转换来加速深度网络训练，arXiv：1502.03167.
* GoogLeNet [[论文]]（http://arxiv.org/pdf/1409.4842）
  * Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich, CVPR, 2015.
* VGG-Net [[网站]]（http://www.robots.ox.ac.uk/~vgg/research/very_deep/)[ [文件]]（http://arxiv.org/pdf/1409.1556）
  * Karen Simonyan和Andrew Zisserman，用于大规模视觉识别的超深卷积网络，ICLR，2015.
* AlexNet [[论文]]（http://papers.nips.cc/book/advances-in-neural-information-processing-systems-25-2012）
  * Alex Krizhevsky，Ilya Sutskever，Geoffrey E. Hinton，ImageNet分类与深度卷积神经网络，NIPS，2012.

### Object Detection
![object_detection](https://cloud.githubusercontent.com/assets/5226447/8452063/f76ba500-2022-11e5-8db1-2cd5d490e3b3.PNG)
（来自Shaoqing Ren，Kaiming He，Ross Girshick，Jian Sun，更快的R-CNN：用区域提案网络进行实时物体检测，arXiv：1506.01497.）

* PVANET [[论文]]（https://arxiv.org/pdf/1608.08021）[[代码]]（https://github.com/sanghoon/pva-faster-rcnn）
  * Kye-Hyeon Kim，Sanghoon Hong，Byungseok Roh，Yeongjae Cheon，Minje Park，PVANET：深度但轻量级的神经网络，用于实时物体检测，arXiv：1608.08021
* OverFeat，纽约大学[[论文]]（http://arxiv.org/pdf/1312.6229.pdf）
  * OverFeat：使用卷积网络的集成识别，本地化和检测，ICLR，2014.
  * Ross Girshick，Jeff Donahue，Trevor Darrell，Jitendra Malik，用于精确对象检测和语义分割的丰富特征层次结构，CVPR，2014.
* SPP，Microsoft Research [[论文]]（http://arxiv.org/pdf/1406.4729）
  * Kaiming He，Zhang Xiangyu Zhang，Shaoqing Ren，Sun Sun，用于视觉识别的深度卷积网络中的空间金字塔池，ECCV，2014.
*快速R-CNN，微软研究[[论文]]（http://arxiv.org/pdf/1504.08083）
  * Ross Girshick，Fast R-CNN，arXiv：1504.08083.
*更快的R-CNN，微软研究[[论文]]（http://arxiv.org/pdf/1506.01497）
  * Shaoqing Ren，Kaiming He，Ross Girshick，Jian Sun，更快的R-CNN：利用区域提案网络进行实时目标检测，arXiv：1506.01497.
* R-CNN减去R，牛津[[论文]]（http://arxiv.org/pdf/1506.06981）
  * Karel Lenc，Andrea Vedaldi，R-CNN减去R，arXiv：1506.06981.
*拥挤场景中的端到端人员检测[[论文]]（http://arxiv.org/abs/1506.04878）
  * Russell Stewart，Mykhaylo Andriluka，在拥挤的场景中端到端的人物检测，arXiv：1506.04878.
*您只看一次：统一，实时对象检测[[纸张]]（http://arxiv.org/abs/1506.02640），[[纸张版本2]]（https://arxiv.org/abs/ 1612.08242），[[C Code]]（https://github.com/pjreddie/darknet），[[Tensorflow Code]]（https://github.com/thtrieu/darkflow）
  * Joseph Redmon，Santosh Divvala，Ross Girshick，Ali Farhadi，你只看一次：统一，实时物体检测，arXiv：1506.02640
  * Joseph Redmon，Ali Farhadi（第2版）
*内外网[[论文]]（http://arxiv.org/abs/1512.04143）
  * Sean Bell，C.Lawrence Zitnick，Kavita Bala，Ross Girshick，Inside-Outside Net：使用Skip Pooling和Recurrent Neural Networks检测上下文中的对象
*深度剩余网络（现有技术水平）[[文件]]（http://arxiv.org/abs/1512.03385）
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Deep Residual Learning for Image Recognition
*具有多重多实例学习的弱监督对象本地化 [[Paper](http://arxiv.org/pdf/1503.00949.pdf)]
* R-FCN [[论文]]（https://arxiv.org/abs/1605.06409）[[代码]]（https://github.com/daijifeng001/R-FCN）
  * Jifeng Dai, Yi Li, Kaiming He, Jian Sun, R-FCN: Object Detection via Region-based Fully Convolutional Networks
* SSD [[论文]]（https://arxiv.org/pdf/1512.02325v2.pdf）[[代码]]（https://github.com/weiliu89/caffe/tree/ssd）
  * Wei Liu1, Dragomir Anguelov, Dumitru Erhan, Christian Szegedy, Scott Reed, Cheng-Yang Fu, Alexander C. Berg, SSD: Single Shot MultiBox Detector, arXiv:1512.02325
*现代卷积物体探测器的速度/精度权衡[[论文]]（https://arxiv.org/pdf/1611.10012v1.pdf）
  * Jonathan Huang，Vivek Rathod，陈孙，朱梦龙，Anoop Korattikara，Alireza Fathi，Ian Fischer，Zbigniew Wojna，杨松，Sergio Guadarrama，Kevin Murphy，Google Research，arXiv：1611.10012

### Video Classification
* Nicolas Ballas，Li Yao，Pal Chris，Aaron Courville，“深入研究用于学习视频表示的卷积网络”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06432v4.pdf)]
* Michael Mathieu，camille couprie，Yann Lecun，“深度多尺度视频预测超越均方误差”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.05440v6.pdf)]

### Object Tracking
 * Seunghoon Hong，Tackgeun You，Suha Kwak，Bohyung Han，使用卷积神经网络学习判别显着性映射的在线跟踪，arXiv：1502.06796.  [[纸张]]（http://arxiv.org/pdf/1502.06796）
* Hanxi Li，Yi Li和Fatih Porikli，DeepTrack：用于视觉跟踪的卷积神经网络学习判别特征表示，BMVC，2014.[[论文]]（http://www.bmva.org/bmvc/2014/files/ paper028.pdf）
* N Wang，DY Yeung，学习深度紧凑的视觉跟踪图像表示，NIPS，2013.[[论文]]（http://winsty.net/papers/dlt.pdf）
* Lijun Wang, Wanli Ouyang, Xiaogang Wang, and Huchuan Lu, Visual Tracking with fully Convolutional Networks, ICCV 2015  [[Paper](http://202.118.75.4/lu/Paper/ICCV2015/iccv15_lijun.pdf)] [[Code](https://github.com/scott89/FCNT)]
* Hyeonseob Namand Bohyung Han，学习用于视觉跟踪的多域卷积神经网络， [[Paper](http://arxiv.org/pdf/1510.07945.pdf)] [[Code](https://github.com/HyeonseobNam/MDNet)] [[Project Page](http://cvlab.postech.ac.kr/research/mdnet/)]

### Low-Level Vision

#### Super-Resolution
*迭代图像重建
   * Sven Behnke：学习迭代图像重建.  IJCAI，2001.[[论文]]（http://www.ais.uni-bonn.de/behnke/papers/ijcai01.pdf）
   * Sven Behnke：在神经抽象金字塔中学习迭代图像重建.  国际计算智能与应用杂志，第一卷.  1，不.  4，pp.427-438,2001.[[论文]]（http://www.ais.uni-bonn.de/behnke/papers/ijcia01.pdf）
*超级决议（SRCNN）[[网页]]（http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html）[[Paper-ECCV14]]（http：//personal.ie.cuhk .edu.hk /~ccloy / files / eccv_2014_deepresolution.pdf）[[Paper-arXiv15]]（http://arxiv.org/pdf/1501.00092.pdf）
  * Chao Dong，Chen Change Loy，Kaiming He，Xiaoou Tang，学习深度卷积网络进行图像超分辨率，ECCV，2014.
  * Chao Dong，Chen Change Loy，Kaiming He，Xiaoou Tang，使用Deep Convolutional Networks的图像超分辨率，arXiv：1501.00092.
*非常深的超分辨率
  * Jiwon Kim，Jung Kwon Lee，Kyoung Mu Lee，使用非常深度卷积网络的精确图像超分辨率，arXiv：1511.04587,2015.[[论文]]（http://arxiv.org/abs/1511.04587）
* Deeply-Recursive Convolutional Network
  * Jiwon Kim，Jung Kwon Lee，Kyoung Mu Lee，图像超分辨率的深度递归卷积网络，arXiv：1511.04491,2015.[[论文]]（http://arxiv.org/abs/1511.04491）
* Casade-Sparse-Coding-Network
   * Zhaowen Wang，Ding Liu，Wei Han，Jianchao Yang和Thomas S. Huang，用于稀疏先验的图像超分辨率的深度网络.  ICCV，2015.[[论文]]（http://www.ifp.illinois.edu/~dingliu2/iccv15/iccv15.pdf）[[代码]]（http://www.ifp.illinois.edu/~ dingliu2 / iccv15 /）
*超分辨率的感知损失
  * Justin Johnson，Alexandre Alahi，李飞飞，实时风格转移和超分辨率的感知损失，arXiv：1603.08155,2016.[[论文]]（http://arxiv.org/abs/1603.08155）[ [补充]]（http://cs.stanford.edu/people/jcjohns/papers/fast-style/fast-style-supp.pdf）
* SRGAN
  * Christian Ledig，Lucas Theis，Ferenc Huszar，Jose Caballero，Andrew Cunningham，Alejandro Acosta，Andrew Aitken，Alykhan Tejani，Johannes Totz，Zehan Wang，Wenzhe Shi，使用生成对抗网络的逼真单图像超分辨率，arXiv： 1609.04802v3,2016.[[论文]]（https://arxiv.org/pdf/1609.04802v3.pdf）
* 其他
  * Osendorfer，Christian，Hubert Soyer和Patrick van der Smagt，具有快速近似卷积稀疏编码的图像超分辨率，ICONIP，2014.[[Paper ICONIP-2014]]（http://brml.org/uploads/tx_sibibtex/ 281.pdf）

#### Other Applications
*光流（FlowNet）[[论文]]（http://arxiv.org/pdf/1504.06852）
  * Philipp Fischer，Alexey Dosovitskiy，Eddy Ilg，PhilipHäusser，CanerHazırbaş，Vladimir Golkov，Patrick van der Smagt，Daniel Cremers，Thomas Brox，FlowNet：使用卷积网络学习光流，arXiv：1504.06852.
*压缩文物减少[[Paper-arXiv15]]（http://arxiv.org/pdf/1504.06993）
  * Chao Dong，Yubin Deng，Chen改变Loy，Xiaoou Tang，通过深度卷积网络减少压缩文物，arXiv：1504.06993.
*模糊删除
  * Christian J. Schuler，Michael Hirsch，Stefan Harmeling，BernhardSchölkopf，学习Deblur，arXiv：1406.7444 [[论文]]（http://arxiv.org/pdf/1406.7444.pdf）
  *孙健，曹文飞，徐宗本，Jean Ponce，学习用于非均匀运动模糊去除的卷积神经网络，CVPR，2015 [[论文]]（http://arxiv.org/pdf/1503.00593）
*图像解卷积[[Web]]（http://lxu.me/projects/dcnn/)[ [Paper]]（http://lxu.me/mypapers/dcnn_nips14.pdf）
  * Li Xu, Jimmy SJ. Ren, Ce Liu, Jiaya Jia, Deep Convolutional Neural Network for Image Deconvolution, NIPS, 2014.
* Deep Edge-Aware Filter [[Paper]]（http://jmlr.org/proceedings/papers/v37/xub15.pdf）
  * Li Xu, Jimmy SJ. Ren, Qiong Yan, Renjie Liao, Jiaya Jia, Deep Edge-Aware Filters, ICML, 2015.
  *JureŽbontar，Yann LeCun，使用卷积神经网络计算立体匹配成本，CVPR，2015.
*彩色图像着色Richard Zhang，Phillip Isola，Alexei A. Efros，ECCV，2016 [[论文]]（http://arxiv.org/pdf/1603.08511.pdf），[[Code]]（https：// github的.com / richzhang /彩色）
* Ryan Dahl，[[博客]]（http://tinyclouds.org/colorize/）
*通过修补功能学习[[论文]]（https://arxiv.org/pdf/1604.07379v1.pdf）[[代码]]（https://github.com/pathak22/context-encoder）
  * Deepak Pathak，Philipp Krahenbuhl，Jeff Donahue，Trevor Darrell，Alexei A. Efros，背景编码器：通过修复功能学习，CVPR，2016

### Edge Detection
![edge_detection](https://cloud.githubusercontent.com/assets/5226447/8452371/93ca6f7e-2025-11e5-90f2-d428fd5ff7ac.PNG)
（来自Gedas Bertasius，Jianbo Shi，Lorenzo Torresani，DeepEdge：用于自上而下轮廓检测的多尺度分叉深度网络，CVPR，2015.）

*整体嵌套边缘检测[[论文]]（http://arxiv.org/pdf/1504.06375）[[代码]]（https://github.com/s9xie/hed）
  * Saining Xie, Zhuowen Tu, Holistically-Nested Edge Detection, arXiv:1504.06375.
* DeepEdge [[论文]]（http://arxiv.org/pdf/1412.1123）
  * Gedas Bertasius，Jianbo Shi，Lorenzo Torresani，DeepEdge：用于自上而下轮廓检测的多尺度分叉深度网络，CVPR，2015.
* DeepContour [[论文]]（http://mc.eistar.net/UpLoadFiles/Papers/DeepContour_cvpr15.pdf）
  * Wei Shen, Xinggang Wang, Yan Wang, Xiang Bai, Zhijiang Zhang, DeepContour: A Deep Convolutional Feature Learned by Positive-Sharing Loss for Contour Detection, CVPR, 2015.

### Semantic Segmentation
![semantic_segmantation](https://cloud.githubusercontent.com/assets/5226447/8452076/0ba8340c-2023-11e5-88bc-bebf4509b6bb.PNG)
（来自Jifeng Dai，Kaiming He，Jian Sun，BoxSup：利用边界框监督卷积网络进行语义分割，arXiv：1503.01640.）
* PASCAL VOC2012挑战排行榜（2016年9月1日）
  ![VOC2012_top_rankings](https://cloud.githubusercontent.com/assets/3803777/18164608/c3678488-7038-11e6-9ec1-74a1542dce13.png)
  （来自PASCAL VOC2012 [leaderboards](http://host.robots.ox.ac.uk:8080/leaderboard/displaylb.php?challengeid=11&compid=6))
* SEC：种子，扩展和约束
  * Alexander Kolesnikov，Christoph Lampert，Seed，Expand and Constrain：弱监督图像分割的三个原则，ECCV，2016.[[论文]]（http://pub.ist.ac.at/~akolesnikov/files/ECCV2016 /main.pdf) [[Code]]（https://github.com/kolesman/SEC）
*阿德莱德
   *郭国胜，沉春华，Ian Reid，Anton van dan Hengel，用于语义分割的深层结构模型的高效分段训练，arXiv：1504.01013.  [[论文]]（http://arxiv.org/pdf/1504.01013）（VOC2012排名第一）
   *郭国胜，沉春华，伊恩里德，安东范登亨格尔，深入学习消息传递推理中的信息，arXiv：1508.02108.  [[论文]]（http://arxiv.org/pdf/1506.02108）（VOC2012排名第4）
*深度解析网络（DPN）
  *刘子伟，李晓晓，罗平，陈改Loy，唐小鸥，深度解析网络的语义图像分割，arXiv：1509.02634 / ICCV 2015 [[论文]]（http://arxiv.org/pdf/1509.02634.pdf ）（2012年VOC排名第2）
* CentraleSuperBoundaries，INRIA [[论文]]（http://arxiv.org/pdf/1511.07386）
  * Iasonas Kokkinos，使用深度学习在边界检测中超越人类，arXiv：1411.07386（2012年VOC排名第四）
* BoxSup [[论文]]（http://arxiv.org/pdf/1503.01640）
   * Jifeng Dai，Kaiming He，Jian Sun，BoxSup：利用边界框监督卷积网络进行语义分割，arXiv：1503.01640.  （VOC2012排名第6）
* POSTECH
   * Hyeonwoo Noh，Seunghoon Hong，Bohyung Han，学习语义分割的反卷积网络，arXiv：1505.04366.  [[论文]]（http://arxiv.org/pdf/1505.04366）（在VOC2012排名第7）
  * Seunghoon Hong, Hyeonwoo Noh, Bohyung Han, Decoupled Deep Neural Network for Semi-supervised Semantic Segmentation, arXiv:1506.04924. [[Paper]](http://arxiv.org/pdf/1506.04924)
  * Seunghoon Hong，Junhyuk Oh，Bohyung Han和Honglak Lee，深度卷积神经网络的语义分割学习可转移知识，arXiv：1512.07928 [[Paper](http://arxiv.org/pdf/1512.07928.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/transfernet/)]
*条件随机场作为回归神经网络[[论文]]（http://arxiv.org/pdf/1502.03240）
   * Shuai Zheng，Sadeep Jayasumana，Bernardino Romera-Paredes，Vibhav Vineet，Zhizhong Su，Dalong Du，Chang Huang，Philip HS Torr，Conditional Random Fields as Recurrent Neural Networks，arXiv：1502.03240.  （VOC2012排名第8）
* DeepLab
   * Liang-Chieh Chen，George Papandreou，Kevin Murphy，Alan L. Yuille，用于语义图像分割的DCNN的弱和半监督学习，arXiv：1502.02734.  [[论文]]（http://arxiv.org/pdf/1502.02734）（在VOC2012排名第9）
  * Mohammadreza Mostajabi，Payman Yadollahpour，Gregory Shakhnarovich，前馈语义分段与缩小功能，CVPR，2015
*联合校准[[论文]]（http://arxiv.org/pdf/1507.01581）
  * Holger Caesar，Jasper Uijlings，Vittorio Ferrari，语义分割联合校准，arXiv：1507.01581.
  * Jonathan Long，Evan Shelhamer，Trevor Darrell，语义分割的完全卷积网络，CVPR，2015.
  * Bharath Hariharan，Pablo Arbelaez，Ross Girshick，Jitendra Malik，用于对象分割和细粒度本地化的Hypercolumns，CVPR，2015.
*深层次分析
  * Abhishek Sharma，Oncel Tuzel，David W. Jacobs，用于语义分割的深层次分析，CVPR，2015.[[论文]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sharma_Deep_Hierarchical_Parsing_2015_CVPR_paper.pdf ）
*学习场景标签的分层特征[[Paper-ICML12]]（http://yann.lecun.com/exdb/publis/pdf/farabet-icml-12.pdf) [[Paper-PAMI13]]（http：/ /yann.lecun.com/exdb/publis/pdf/farabet-pami-13.pdf）
  * Clement Farabet，Camille Couprie，Laurent Najman，Yann LeCun，场景解析与多尺度特征学习，纯度树和最佳封面，ICML，2012.
  * Clement Farabet，Camille Couprie，Laurent Najman，Yann LeCun，学习场景标签的等级特征，PAMI，2013.
*剑桥大学[[网页]]（http://mi.eng.cam.ac.uk/projects/segnet/）
   * Vijay Badrinarayanan，Alex Kendall和Roberto Cipolla“SegNet：用于图像分割的深度卷积编码器 - 解码器架构”.  arXiv preprint arXiv：1511.00561,2015.[[Paper]]（http://arxiv.org/abs/1511.00561）
 * Alex Kendall，Vijay Badrinarayanan和Roberto Cipolla“贝叶斯SegNet：用于场景理解的深度卷积编码器 - 解码器架构中的模型不确定性.”  arXiv preprint arXiv：1511.02680,2015.[[论文]]（http://arxiv.org/abs/1511.00561）
*普林斯顿
  * Fisher Yu，Vladlen Koltun，“扩张卷积的多尺度背景聚合”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.07122v2.pdf)]
 *大学  华盛顿，艾伦AI
  * Hamid Izadinia，Fereshteh Sadeghi，Santosh Kumar Divvala，Yejin Choi，Ali Farhadi，“Segment-Phrase Table的语义分割，视觉蕴涵和释义”，ICCV，2015， [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Izadinia_Segment-Phrase_Table_for_ICCV_2015_paper.pdf)]
* INRIA
  * Iasonas Kokkinos，“利用深度学习进行边界检测的边界”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.07386v2.pdf)]
* UCSB
  * Niloufar Pourian，S.Karthikeyan和BS Manjunath，“通过学习图像部分社区的弱监督基于图形的语义分割”，ICCV，2015， [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Pourian_Weakly_Supervised_Graph_ICCV_2015_paper.pdf)]

### Visual Attention and Saliency
![saliency](https://cloud.githubusercontent.com/assets/5226447/8492362/7ec65b88-2183-11e5-978f-017e45ddba32.png)
(from Nian Liu, Junwei Han, Dingwen Zhang, Shifeng Wen, Tianming Liu, Predicting Eye Fixations using Convolutional Neural Networks, CVPR, 2015.)

  * Nian Liu, Junwei Han, Dingwen Zhang, Shifeng Wen, Tianming Liu, Predicting Eye Fixations using Convolutional Neural Networks, CVPR, 2015.
  * Saurabh Singh，Derek Hoiem，David Forsyth，学习顺序搜索地标，CVPR，2015.
*具有视觉注意力的多目标识别[[论文]]（http://arxiv.org/pdf/1412.7755.pdf）
  * Jimmy Lei Ba，Volodymyr Mnih，Koray Kavukcuoglu，具有视觉注意力的多重物体识别，ICLR，2015.
*视觉注意的复发模型[[论文]]（http://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf）
  * Volodymyr Mnih，Nicolas Heess，Alex Graves，Koray Kavukcuoglu，视觉注意的复发模型，NIPS，2014.

### Object Recognition
   * Maxime Oquab，Leon Bottou，Ivan Laptev，Josef Sivic，是免费的对象本地化吗？   - 使用卷积神经网络进行弱监督学习，CVPR，2015.
  * Mircea Cimpoi，Subhransu Maji，Andrea Vedaldi，用于纹理识别和分割的深层滤波器组，CVPR，2015.

### Human Pose Estimation
* Zhe Cao，Tomas Simon，Shih-En Wei和Yaser Sheikh，使用Part Affinity Fields的实时多人2D姿势估计，CVPR，2017.
* Leonid Pishchulin，Eldar Insafutdinov，Siyu Tang，Bjoern Andres，Mykhaylo Andriluka，Peter Gehler和Bernt Schiele，Deepcut：用于多人姿势估计的联合子集分区和标签，CVPR，2016.
* Shih-En Wei，Varun Ramakrishna，Takeo Kanade和Yaser Sheikh，Convolutional姿势机器，CVPR，2016.
*亚历杭德罗·纽厄尔，杨凯宇和贾登，用于人体姿势估计的堆叠沙漏网络，ECCV，2016.
*托马斯·普菲斯特，詹姆斯·查尔斯和安德鲁·齐瑟曼，视频中人类姿势评估的流动评论，ICCV，2015.
* Jonathan J. Tompson，Arjun Jain，Yann LeCun，Christoph Bregler，卷积网络的联合训练和人体姿势估计的图形模型，NIPS，2014.

### Understanding CNN
![understanding](https://cloud.githubusercontent.com/assets/5226447/8452083/1aaa0066-2023-11e5-800b-2248ead51584.PNG)
（来自Aravindh Mahendran，Andrea Vedaldi，通过反思他们理解深度图像表达，CVPR，2015年.）

* Bolei Zhou，Aditya Khosla，Agata Lapedriza，Aude Oliva，Antonio Torralba，物体探测器出现在深度场景CNN，ICLR，2015年.[[arXiv Paper]]（http://arxiv.org/abs/1412.6856）
* Alexey Dosovitskiy，Thomas Brox，使用卷积网络反转视觉表示，arXiv，2015年.[[论文]]（http://arxiv.org/abs/1506.02753）
* Matthrew Zeiler，Rob Fergus，可视化和理解卷积网络，ECCV，2014.[[论文]]（https://www.cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf）


### Image and Language

#### Image Captioning
![image_captioning](https://cloud.githubusercontent.com/assets/5226447/8452051/e8f81030-2022-11e5-85db-c68e7d8251ce.PNG)
（来自Andrej Karpathy，李飞飞，用于生成图像描述的深层视觉语义对齐，CVPR，2015.）

*加州大学洛杉矶分校/百度[[论文]]（http://arxiv.org/pdf/1410.1090）
  * Junhua Mao, Wei Xu, Yi Yang, Jiang Wang, Alan L. Yuille, Explain Images with Multimodal Recurrent Neural Networks, arXiv:1410.1090.
*多伦多[[论文]]（http://arxiv.org/pdf/1411.2539）
  * Ryan Kiros，Ruslan Salakhutdinov，Richard S. Zemel，使用多模态神经语言模型统一视觉语义嵌入，arXiv：1411.2539.
*伯克利[[文件]]（http://arxiv.org/pdf/1411.4389）
  * Jeff Donahue，Lisa Anne Hendricks，Sergio Guadarrama，Marcus Rohrbach，Subhashini Venugopalan，Kate Saenko，Trevor Darrell，视觉识别和描述的长期循环卷积网络，arXiv：1411.4389.
* Google [[论文]]（http://arxiv.org/pdf/1411.4555）
  * Oriol Vinyals，Alexander Toshev，Samy Bengio，Dumitru Erhan，Show and Tell：神经图像标题生成器，arXiv：1411.4555.
*斯坦福[[网页]]（http://cs.stanford.edu/people/karpathy/deepimagesent/)[ [论文]]（http://cs.stanford.edu/people/karpathy/cvpr2015.pdf）
  * Andrej Karpathy，Li Fei-Fei，用于生成图像描述的深层视觉语义对齐，CVPR，2015.
* UML / UT [[论文]]（http://arxiv.org/pdf/1412.4729）
  * Subhashini Venugopalan，Huijuan Xu，Jeff Donahue，Marcus Rohrbach，Raymond Mooney，Kate Saenko，使用深度回归神经网络将视频转换为自然语言，NAACL-HLT，2015.
* CMU / Microsoft [[Paper-arXiv]]（http://arxiv.org/pdf/1411.5654）[[Paper-CVPR]]（http://www.cs.cmu.edu/~xinleic/papers/cvpr15_rnn .PDF）
  * Xinlei Chen，C.Lawrence Zitnick，学习图像标题生成的周期性视觉表示，arXiv：1411.5654.
  * Xinlei Chen，C.Lawrence Zitnick，Mind&#39;s Eye：图像标题生成的经常性视觉表示，CVPR 2015
*微软[[论文]]（http://arxiv.org/pdf/1411.4952）
  *郝芳，Saurabh Gupta，Forrest Iandola，Rupesh Srivastava，Li Deng，PiotrDollár，Jianfeng Gao，Xiaodong He，Margaret Mitchell，John C. Platt，C.Lawrence Zitnick，Geoffrey Zweig，从Captions到Visual Concepts and Back，CVPR ，2015年.
 *大学  蒙特利尔/大学  多伦多 [[Web](http://kelvinxu.github.io/projects/capgen.html)] [[Paper](http://www.cs.toronto.edu/~zemel/documents/captionAttn.pdf)]
  * Kelvin Xu，Jimmy Lei Ba，Ryan Kiros，Kyunghyun Cho，Aaron Courville，Ruslan Salakhutdinov，Richard S. Zemel，Yoshua Bengio，Show，Attend，and Tell：神经图像标题生成与视觉注意，arXiv：1502.03044 / ICML 2015
* Idiap / EPFL / Facebook [[Paper](http://arxiv.org/pdf/1502.03671)]
  * Remi Lebret，Pedro O. Pinheiro，Ronan Collobert，基于短语的图像字幕，arXiv：1502.03671 / ICML 2015
*加州大学洛杉矶分校/百度 [[Paper](http://arxiv.org/pdf/1504.06692)]
  *毛俊华，徐伟，杨毅，王江，黄志恒，Alan L. Yuille，像孩子一样学习：从图像句子描述学习快速小说视觉概念，arXiv：1504.06692
* MS +伯克利
  * Jacob Devlin，Saurabh Gupta，Ross Girshick，Margaret Mitchell，C.Lawrence Zitnick，探索图像字幕的最近邻法，arXiv：1505.04467 [[Paper](http://arxiv.org/pdf/1505.04467.pdf)]
  * Jacob Devlin，Hao Cheng，Hao Fang，Saurabh Gupta，Li Deng，Xiaodong He，Geoffrey Zweig，Margaret Mitchell，图像字幕语言模型：怪癖和什么有效，arXiv：1505.01809 [[Paper](http://arxiv.org/pdf/1505.01809.pdf)]
*阿德莱德 [[Paper](http://arxiv.org/pdf/1506.01144.pdf)]
  * Qi Wu, Chunhua Shen, Anton van den Hengel, Lingqiao Liu, Anthony Dick, Image Captioning with an Intermediate Attributes Layer, arXiv:1506.01144
*蒂尔堡 [[Paper](http://arxiv.org/pdf/1506.03694.pdf)]
  * Grzegorz Chrupala，Akos Kadar，Afra Alishahi，通过图片学习语言，arXiv：1506.03694
 *大学  蒙特利尔 [[Paper](http://arxiv.org/pdf/1507.01053.pdf)]
  * Kyunghyun Cho，Aaron Courville，Yoshua Bengio，使用基于注意力的编码器 - 解码器网络描述多媒体内容，arXiv：1507.01053
康奈尔 [[Paper](http://arxiv.org/pdf/1508.02091.pdf)]
  * Jack Hessel，Nicolas Savva，Michael J. Wilber，图像表示和神经图像字幕中的新域，arXiv：1508.02091
  * Ting Yao，Tao Mei和Chong-Wah Ngo，“学习查询和图像相似性
    与排序典型相关分析“，ICCV，2015

#### Video Captioning
* Berkeley [[Web]](http://jeffdonahue.com/lrcn/) [[Paper]](http://arxiv.org/pdf/1411.4389.pdf)
  * Jeff Donahue，Lisa Anne Hendricks，Sergio Guadarrama，Marcus Rohrbach，Subhashini Venugopalan，Kate Saenko，Trevor Darrell，视觉识别和描述的长期循环卷积网络，CVPR，2015.
* UT / UML / Berkeley [[论文]]（http://arxiv.org/pdf/1412.4729）
  * Subhashini Venugopalan，Huijuan Xu，Jeff Donahue，Marcus Rohrbach，Raymond Mooney，Kate Saenko，使用深度回归神经网络将视频转换为自然语言，arXiv：1412.4729.
*微软[[论文]]（http://arxiv.org/pdf/1505.01861）
  * Yingwei Pan, Tao Mei, Ting Yao, Houqiang Li, Yong Rui, Joint Modeling Embedding and Translation to Bridge Video and Language, arXiv:1505.01861.
* UT / Berkeley / UML [[论文]]（http://arxiv.org/pdf/1505.00487）
  * Subhashini Venugopalan，Marcus Rohrbach，Jeff Donahue，Raymond Mooney，Trevor Darrell，Kate Saenko，序列到序列 - 视频到文本，arXiv：1505.00487.
 *大学  蒙特利尔/大学  舍布鲁克 [[Paper](http://arxiv.org/pdf/1502.08029.pdf)]
  * Li Yao，Atousa Torabi，Kyunghyun Cho，Nicolas Ballas，Christopher Pal，Hugo Larochelle，Aaron Courville，通过利用时间结构描述视频，arXiv：1502.08029
* MPI /伯克利 [[Paper](http://arxiv.org/pdf/1506.01698.pdf)]
  * Anna Rohrbach，Marcus Rohrbach，Bernt Schiele，电影描述的长篇小说，arXiv：1506.01698
*大学多伦多/麻省理工学院 [[Paper](http://arxiv.org/pdf/1506.06724.pdf)]
  * Yukun Zhu，Ryan Kiros，Richard Zemel，Ruslan Salakhutdinov，Raquel Urtasun，Antonio Torralba，Sanja Fidler，调整书籍和电影：通过观看电影和阅读书籍实现故事般的视觉解释，arXiv：1506.06724
 *大学  蒙特利尔 [[Paper](http://arxiv.org/pdf/1507.01053.pdf)]
  * Kyunghyun Cho，Aaron Courville，Yoshua Bengio，使用基于注意力的编码器 - 解码器网络描述多媒体内容，arXiv：1507.01053
* TAU / USC [[paper](https://arxiv.org/pdf/1612.06950.pdf)]
  * Dotan Kaufman，Gil Levi，Tal Hassner，Lior Wolf，视频注释和摘要的时间曲面细分，arXiv：1612.06950.

#### Question Answering
![question_answering](https://cloud.githubusercontent.com/assets/5226447/8452068/ffe7b1f6-2022-11e5-87ab-4f6d4696c220.PNG)
（来自Stanislaw Antol，Aishwarya Agrawal，Jiasen Lu，Margaret Mitchell，Dhruv Batra，C.Lawrence Zitnick，Devi Parikh，VQA：Visual Question Answering，CVPR，2015 SUNw：Scene Understanding workshop）

*弗吉尼亚理工大学/ MSR [[网站]]（http://www.visualqa.org/）[[论文]]（http://arxiv.org/pdf/1505.00468）
  * Stanislaw Antol，Aishwarya Agrawal，Jiasen Lu，Margaret Mitchell，Dhruv Batra，C.Lawrence Zitnick，Devi Parikh，VQA：Visual Question Answering，CVPR，2015 SUNw：Scene Understanding workshop.
* MPI / Berkeley [[Web]]（https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/vision-and-language/visual-turing-challenge/ ）[[文件]]（http://arxiv.org/pdf/1505.01121）
  * Mateusz Malinowski，Marcus Rohrbach，Mario Fritz，问问你的神经元：基于神经的方法来回答关于图像的问题，arXiv：1505.01121.
*多伦多[[论文]]（http://arxiv.org/pdf/1505.02074）[[数据集]]（http://www.cs.toronto.edu/~mren/imageqa/data/cocoqa/）
  * Mengye Ren，Ryan Kiros，Richard Zemel，图像问题回答：视觉语义嵌入模型和新数据集，arXiv：1505.02074 / ICML 2015深度学习研讨会.
*百度/ UCLA [[论文]]（http://arxiv.org/pdf/1505.05612）[[数据集]]（）
  * Hauyuan Gao, Junhua Mao, Jie Zhou, Zhiheng Huang, Lei Wang, Wei Xu, Are You Talking to a Machine? Dataset and Methods for Multilingual Image Question Answering, arXiv:1505.05612.
* POSTECH [[Paper](http://arxiv.org/pdf/1511.05756.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/dppnet/)]
  * Hyeonwoo Noh，Paul Hongsuck Seo和Bohyung Han，图像问题回答使用卷积神经网络进行动态参数预测，arXiv：1511.05765
* CMU /微软研究院 [[Paper](http://arxiv.org/pdf/1511.02274v2.pdf)]
   * Yang，Z.，He，X.，Gao，J.，Deng，L.，＆Smola，A.（2015）.  用于图像问答的堆叠注意网络.  的arXiv：1511.02274.
* MetaMind [[Paper](http://arxiv.org/pdf/1603.01417v1.pdf)]
   *熊，蔡明，Stephen Merity和Richard Socher.  “用于视觉和文本问答的动态内存网络.”  arXiv：1603.01417（2016）.
*请+ NAVER [[Paper](http://arxiv.org/abs/1606.01455)]
  * Jin-Hwa Kim，Sang-Woo Lee，Dong-Hyun Kwak，Min-Oh Heo，Jeonghee Kim，Jung-Woo Ha，Byoung-Tak Zhang，* Multimodal Residual Learning for Visual QA *，arXiv：1606：01455
* UC Berkeley + Sony [[Paper](https://arxiv.org/pdf/1606.01847)]
  * Akira Fukui，Dong Huk Park，Daylen Yang，Anna Rohrbach，Trevor Darrell和Marcus Rohrbach，* Multimodal Compact双线性池用于视觉问答和视觉接地*，arXiv：1606.01847
* Postech [[Paper](http://arxiv.org/pdf/1606.03647.pdf)]
  * Hyeonwoo Noh和Bohyung Han，*为VQA *训练经常性应答单位联合损失最小化，arXiv：1606.03647
*请+ NAVER [[Paper](http://arxiv.org/abs/1610.04325)]
  * Jin-Hwa Kim，Kyoung Woon On，Jeonghee Kim，Jung-Woo Ha，Byoung-Tak Zhang，* Hadamard低级双线性池化产品*，arXiv：1610.04325.

### Image Generation
*卷积/经常性网络
   *Aäronvanden Oord，Nal Kalchbrenner，Oriol Vinyals，Lasse Espeholt，Alex Graves，Koray Kavukcuoglu.  “使用PixelCNN解码器生成条件图像”[[Paper]]（https://arxiv.org/pdf/1606.05328v2.pdf) [[Code]]（https://github.com/kundan2510/pixelCNN）
  * Alexey Dosovitskiy，Jost Tobias Springenberg，Thomas Brox，“学习用卷积神经网络生成椅子”，CVPR，2015年.[[论文]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/ Dosovitskiy_Learning_to_Generate_2015_CVPR_paper.pdf）
  * Karol Gregor，Ivo Danihelka，Alex Graves，Danilo Jimenez Rezende，Daan Wierstra，“绘图：用于图像生成的递归神经网络”，ICML，2015. [[Paper](https://arxiv.org/pdf/1502.04623v2.pdf)] 
*对抗网络
  * Ian J. Goodfellow，Jean Pouget-Abadie，Mehdi Mirza，Bing Xu，David Warde-Farley，Sherjil Ozair，Aaron Courville，Yoshua Bengio，Generative Adversarial Networks，NIPS，2014.[[论文]]（http：// arxiv .ORG / ABS / 1406.2661）
  * Emily Denton，Soumith Chintala，Arthur Szlam，Rob Fergus，使用￼Laplacian金字塔对抗网络的深度生成图像模型，NIPS，2015.[[论文]]（http://arxiv.org/abs/1506.05751）
  * Lucas Theis，Aaron van den Oord，Matthias Bethge，“关于评估生成模型的注释”，ICLR 2016. [[Paper](http://arxiv.org/abs/1511.01844)]
  * Zhenwen Dai，Andreas Damianou，Javier Gonzalez，Neil Lawrence，“变分自动编码深高斯过程”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06455v2.pdf)]
  * Elman Mansimov，Emilio Parisotto，Jimmy Ba，Ruslan Salakhutdinov，“从注意的字幕中生成图像”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.02793v2.pdf)]
  * Jost Tobias Springenberg，“使用分类生成对抗网络的无监督和半监督学习”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.06390v1.pdf)]
  *哈里森爱德华兹，Amos Storkey，“与对手一起审查陈述”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.05897v3.pdf)]
  * Takeru Miyato，Shin-ichi Maeda，Masanori Koyama，Ken Nakae，Shin Ishii，“分布式平滑与虚拟对抗训练”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1507.00677v8.pdf)]
  * Jun-Yan Zhu，Philipp Krahenbuhl，Eli Shechtman和Alexei A. Efros，“自然图像流形上的生成视觉操纵”，ECCV 2016. [[Paper](https://arxiv.org/pdf/1609.03552v2.pdf)] [[Code](https://github.com/junyanz/iGAN)] [[Video](https://youtu.be/9c4z6YsBGQ0)]
*混合卷积网络和对抗网络
  * Alec Radford，Luke Metz，Soumith Chintala，“使用深度卷积生成对抗网络进行无监督表示学习”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06434.pdf)]

### Other Topics
*视觉类比 [[Paper](https://web.eecs.umich.edu/~honglak/nips2015-analogy.pdf)]
  * Scott Reed，Yi Zhang，Yuting Zhang，Honglak Lee，Deep Visual Analogy Making，NIPS，2015
  * Xiaolong Wang，David F. Fouhey，Abhinav Gupta，设计用于表面法线估计的深度网络，CVPR，2015.
  * Georgia Gkioxari，Jitendra Malik，Finding Action Tubes，CVPR，2015.
  *张聪，李宏生，王晓刚，杨小康，通过深度卷积神经网络的跨场景人群计数，CVPR，2015.
  *方王，乐康，李毅，基于轮廓的三维形状检索使用卷积神经网络，CVPR，2015.
*弱监督分类
  * Samaneh Azadi，Jiashi Feng，Stefanie Jegelka，Trevor Darrell，“带有噪声标签的深度CNN的辅助图像正规化”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.07069v2.pdf)]
*艺术风格[[论文]]（http://arxiv.org/abs/1508.06576）[[代码]]（https://github.com/jcjohnson/neural-style）
  * Leon A. Gatys，Alexander S. Ecker，Matthias Bethge，艺术风格的神经算法.
*人类凝视估计
  * Xucong Zhang，Yusuke Sugano，Mario Fritz，Andreas Bulling，“基于外观的野外凝视估计”，CVPR，2015年.[[论文]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/ Zhang_Appearance-Based_Gaze_Estimation_2015_CVPR_paper.pdf）[[Website]]（https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/gaze-based-human-computer-interaction/基于外观的注视估计-内式野生mpiigaze /）
* 人脸识别
  * Yaniv Taigman，Ming Yang，Marc&#39;Aurelio Ranzato，Lior Wolf，DeepFace：在人脸验证方面缩小差距，CVPR，2014年.[[论文]]（https://www.cs.toronto.edu /~ranzato/publications/taigman_cvpr14.pdf）
  *孙奕，丁亮，王小刚，唐小鸥，DeepID3：极深度神经网络的人脸识别，2015.[[论文]]（http://arxiv.org/abs/1502.00873）
  * Florian Schroff，Dmitry Kalenichenko，James Philbin，FaceNet：用于人脸识别和聚类的统一嵌入，CVPR，2015.[[论文]]（http://arxiv.org/abs/1503.03832）
*面部地标检测
  * Yue Wu，Tal Hassner，KangGeon Kim，Gerard Medioni，Prem Natarajan，面部地标检测与调整卷积神经网络，2015年.[[论文]]（http://arxiv.org/abs/1511.04031) [[Project]] （http://www.openu.ac.il/home/hassner/projects/tcnn_landmarks/）

## Courses
*深度视觉
  * [斯坦福] [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
  * [CUHK] [ELEG 5040: Advanced Topics in Signal Processing(Introduction to Deep Learning)](https://piazza.com/cuhk.edu.hk/spring2015/eleg5040/home)
*更多深度学习
  * [斯坦福] [CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/)
  * [牛津] [Deep Learning by Prof. Nando de Freitas](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
  * [纽约大学] [Deep Learning by Prof. Yann LeCun](http://cilvr.cs.nyu.edu/doku.php?id=courses:deeplearning2014:start)

## Books
*免费在线图书
  * [Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](http://www.iro.umontreal.ca/~bengioy/dlbook/)
  * [Neural Networks and Deep Learning by Michael Nielsen](http://neuralnetworksanddeeplearning.com/)
  * [Deep Learning Tutorial by LISA lab, University of Montreal](http://deeplearning.net/tutorial/deeplearning.pdf)

## Videos
*会谈
  * [Deep Learning, Self-Taught Learning and Unsupervised Feature Learning By Andrew Ng](https://www.youtube.com/watch?v=n1ViNeWhC24)
  * [Recent Developments in Deep Learning By Geoff Hinton](https://www.youtube.com/watch?v=vShMxxqtDDs)
  * [The Unreasonable Effectiveness of Deep Learning by Yann LeCun](https://www.youtube.com/watch?v=sc-KbuZqGkI)
  * [Deep Learning of Representations by Yoshua bengio](https://www.youtube.com/watch?v=4xsVFLnHC_0)


## Software
### Framework
* Tensorflow：一个开源软件库，用于使用谷歌的数据流图进行数值计算 [[Web](https://www.tensorflow.org/)]
* Torch7：Lua中的深度学习库，由Facebook和Google Deepmind使用 [[Web](http://torch.ch/)]
  *基于火炬的深度学习库： [[torchnet](https://github.com/torchnet/torchnet)],
* Caffe：BVLC的深度学习框架 [[Web](http://caffe.berkeleyvision.org/)]
* Theano：Python中的数学库，由LISA实验室维护 [[Web](http://deeplearning.net/software/theano/)]
  *基于Theano的深度学习库： [[Pylearn2](http://deeplearning.net/software/pylearn2/)], [[Blocks](https://github.com/mila-udem/blocks)], [[Keras](http://keras.io/)], [[Lasagne](https://github.com/Lasagne/Lasagne)]
* MatConvNet：用于MATLAB的CNN [[Web](http://www.vlfeat.org/matconvnet/)]
* MXNet：灵活高效的深度学习库，适用于具有多语言支持的异构分布式系统 [[Web](http://mxnet.io/)]
* Deepgaze：基于CNN的人机交互计算机视觉库 [[Web](https://github.com/mpatacchiola/deepgaze)]

### Applications
*对抗训练
  *“生成性对抗网络”[[Web]]（https://github.com/goodfeli/adversarial）论文的代码和超参数
*理解和可视化
  *“通过反转来理解深度图像表示”的源代码，CVPR，2015.[[Web]]（https://github.com/aravindhm/deep-goggle）
*语义分段
  *论文的源代码“用于精确对象检测和语义分割的丰富特征层次结构”，CVPR，2014.[[Web]]（https://github.com/rbgirshick/rcnn）
  *文章“用于语义分割的完全卷积网络”的源代码，CVPR，2015.[[Web]]（https://github.com/longjon/caffe/tree/future）
*超分辨率
  *动漫风格艺术的图像超分辨率[[Web]]（https://github.com/nagadomi/waifu2x）
*边缘检测
  *文章的源代码“DeepContour：通过轮廓检测的正共享损失学习的深度卷积特征”，CVPR，2015.[[Web]]（https://github.com/shenwei1231/DeepContour）
  * ICCV 2015论文“Holistically-Nested Edge Detection”的源代码.[[Web]]（https://github.com/s9xie/hed）

## Tutorials
* [CVPR 2014] [Tutorial on Deep Learning in Computer Vision](https://sites.google.com/site/deeplearningcvpr2014/)
* [CVPR 2015] [Applied Deep Learning for Computer Vision with Torch](https://github.com/soumith/cvpr2015)

## Blogs
* [Deep down the rabbit hole: CVPR 2015 and beyond@Tombone's Computer Vision Blog](http://www.computervisionblog.com/2015/06/deep-down-rabbit-hole-cvpr-2015-and.html)
* [CVPR recap and where we're going@Zoya Bylinskii (MIT PhD Student)'s Blog](http://zoyathinks.blogspot.kr/2015/06/cvpr-recap-and-where-were-going.html)
* [Facebook's AI Painting@Wired](http://www.wired.com/2015/06/facebook-googles-fake-brains-spawn-new-visual-reality/)
* [Inceptionism: Going Deeper into Neural Networks@Google Research](http://googleresearch.blogspot.kr/2015/06/inceptionism-going-deeper-into-neural.html)
* [Implementing Neural networks](http://peterroelants.github.io/) 
