<div class="github-widget" data-repo="kjw0612/awesome-deep-vision"></div>
## Awesome Deep Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

受启发的计算机视觉深度学习资源精选列表 [awesome-php](https://github.com/ziadoz/awesome-php) 和 [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

维护者 - [Jiwon Kim](https://github.com/kjw0612), [Heesoo Myeong](https://github.com/hmyeong), [Myungsub Choi](https://github.com/myungsub), [Jung Kwon Lee](https://github.com/deruci), [Taeksoo Kim](https://github.com/jazzsaxmafia)

该项目没有得到积极维护. 

## Contributing
请随时 [pull requests](https://github.com/kjw0612/awesome-deep-vision/pulls) 添加文件.

[![Join the chat at https://gitter.im/kjw0612/awesome-deep-vision](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/kjw0612/awesome-deep-vision?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Sharing
+ [Share on Twitter](http://twitter.com/home?status=http://jiwonkim.org/awesome-deep-vision%0ADeep Learning Resources for Computer Vision)
+ [Share on Facebook](http://www.facebook.com/sharer/sharer.php?u=https://jiwonkim.org/awesome-deep-vision)
+ [Share on Google Plus](http://plus.google.com/share?url=https://jiwonkim.org/awesome-deep-vision)
+ [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://jiwonkim.org/awesome-deep-vision&title=Awesome%20Deep%20Vision&summary=&source=)


## Papers

### ImageNet Classification
![classification](https://cloud.githubusercontent.com/assets/5226447/8451949/327b9566-2022-11e5-8b34-53b4a64c13ad.PNG)
（来自 Alex Krizhevsky、Ilya Sutskever、Geoffrey E. Hinton，ImageNet Classification with Deep Convolutional Neural Networks，NIPS，2012.）
* 微软（深度残差学习） [[Paper](http://arxiv.org/pdf/1512.03385v1.pdf)][[Slide](http://image-net.org/challenges/talks/ilsvrc2015_deep_residual_learning_kaiminghe.pdf)]
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Deep Residual Learning for Image Recognition, arXiv:1512.03385.
* 微软（PReLu/权重初始化）[[论文]](http://arxiv.org/pdf/1502.01852)
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification, arXiv:1502.01852.
* 批量标准化 [[论文]](http://arxiv.org/pdf/1502.03167)
  * Sergey Ioffe、Christian Szegedy，批量归一化：通过减少内部协变量偏移加速深度网络训练，arXiv：1502.03167.
* GoogLeNet [[论文]](http://arxiv.org/pdf/1409.4842)
  * Christian Szegedy、Wei Liu、Yangqing Jia、Pierre Sermanet、Scott Reed、Dragomir Anguelov、Dumitru Erhan、Vincent Vanhoucke、Andrew Rabinovich，CVPR，2015 年.
* VGG-Net [[Web]](http://www.robots.ox.ac.uk/~vgg/research/very_deep/) [[论文]](http://arxiv.org/pdf/1409.1556)
  * Karen Simonyan 和 Andrew Zisserman，用于大规模视觉识别的超深卷积网络，ICLR，2015 年.
* AlexNet [[论文]](http://papers.nips.cc/book/advances-in-neural-information-processing-systems-25-2012)
  * Alex Krizhevsky、Ilya Sutskever、Geoffrey E. Hinton，使用深度卷积神经网络进行 ImageNet 分类，NIPS，2012 年.

### Object Detection
![object_detection](https://cloud.githubusercontent.com/assets/5226447/8452063/f76ba500-2022-11e5-8db1-2cd5d490e3b3.PNG)
（来自 Shaoqing Ren、Kaiming He、Ross Girshick、Jian Sun，Faster R-CNN：使用区域提议网络实现实时目标检测，arXiv：1506.01497.）

* PVANET [[论文]](https://arxiv.org/pdf/1608.08021) [[代码]](https://github.com/sanghoon/pva-faster-rcnn)
  * Kye-Hyeon Kim、Sanghoon Hong、Byungseok Roh、Yeongjae Cheon、Minje Park、PVANET：用于实时对象检测的深度但轻量级神经网络，arXiv：1608.08021
* OverFeat，纽约大学 [[论文]](http://arxiv.org/pdf/1312.6229.pdf)
  * OverFeat：使用卷积网络的集成识别、定位和检测，ICLR，2014 年.
  * Ross Girshick、Jeff Donahue、Trevor Darrell、Jitendra Malik，Rich feature hierarchies for accurate object detection and semantic segmentation，CVPR，2014.
* SPP，微软研究院 [[论文]](http://arxiv.org/pdf/1406.4729)
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition, ECCV, 2014.
* Fast R-CNN，微软研究院[[论文]](http://arxiv.org/pdf/1504.08083)
  * Ross Girshick，Fast R-CNN，arXiv：1504.08083.
* Faster R-CNN，微软研究院[[论文]](http://arxiv.org/pdf/1506.01497)
  * Shaoqing Ren、Kaiming He、Ross Girshick、Jian Sun，Faster R-CNN：使用区域提议网络实现实时目标检测，arXiv：1506.01497.
* R-CNN minus R, Oxford [[论文]](http://arxiv.org/pdf/1506.06981)
  * Karel Lenc、Andrea Vedaldi、R-CNN 减去 R、arXiv:1506.06981.
* 拥挤场景中的端到端人员检测[[论文]](http://arxiv.org/abs/1506.04878)
  * Russell Stewart、Mykhaylo Andriluka，拥挤场景中的端到端人员检测，arXiv：1506.04878.
* 你只看一次：统一的实时对象检测[[论文]](http://arxiv.org/abs/1506.02640)，[[论文版本 2]](https://arxiv.org/abs/ 1612.08242), [[C 代码]](https://github.com/pjreddie/darknet), [[Tensorflow 代码]](https://github.com/thtrieu/darkflow)
  * Joseph Redmon、Santosh Divvala、Ross Girshick、Ali Farhadi，你只看一次：统一的实时对象检测，arXiv：1506.02640
  * 约瑟夫·雷德蒙、阿里·法哈迪（第 2 版）
* 内外网 [[论文]](http://arxiv.org/abs/1512.04143)
  * Sean Bell、C. Lawrence Zitnick、Kavita Bala、Ross Girshick，Inside-Outside Net：使用 Skip Pooling 和递归神经网络检测上下文中的对象
* 深度残差网络（当前最先进的技术）[[论文]](http://arxiv.org/abs/1512.03385)
  * Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, Deep Residual Learning for Image Recognition
* 多倍多实例学习的弱监督目标定位 [[Paper](http://arxiv.org/pdf/1503.00949.pdf)]
* R-FCN [[论文]](https://arxiv.org/abs/1605.06409) [[代码]](https://github.com/daijifeng001/R-FCN)
  * Jifeng Dai, Yi Li, Kaiming He, Jian Sun, R-FCN: Object Detection via Region-based Fully Convolutional Networks
* SSD [[论文]](https://arxiv.org/pdf/1512.02325v2.pdf) [[代码]](https://github.com/weiliu89/caffe/tree/ssd)
  * Wei Liu1, Dragomir Anguelov, Dumitru Erhan, Christian Szegedy, Scott Reed, Cheng-Yang Fu, Alexander C. Berg, SSD: Single Shot MultiBox Detector, arXiv:1512.02325
* 现代卷积对象检测器的速度/精度权衡 [[论文]](https://arxiv.org/pdf/1611.10012v1.pdf)
  * Jonathan Huang, Vivek Rathod, Chen Sun, Menglong Zhu, Anoop Korattikara, Alireza Fathi, Ian Fischer, Zbigniew Wojna, Yang Song, Sergio Guadarrama, Kevin Murphy, Google Research, arXiv:1611.10012

### Video Classification
* Nicolas Ballas、Li Yao、Pal Chris、Aaron Courville，“深入研究用于学习视频表示的卷积网络”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06432v4.pdf)]
* Michael Mathieu、camille couprie、Yann Lecun，“超越均方误差的深度多尺度视频预测”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.05440v6.pdf)]

### Object Tracking
 * Seunghoon Hong、Tackgeun You、Suha Kwak、Bohyung Han，通过使用卷积神经网络学习判别显着图进行在线跟踪，arXiv：1502.06796.  [[论文]](http://arxiv.org/pdf/1502.06796)
* Hanxi Li、Yi Li 和 Fatih Porikli，DeepTrack：通过用于视觉跟踪的卷积神经网络学习判别特征表示，BMVC，2014 年.[[论文]](http://www.bmva.org/bmvc/2014/files/论文028.pdf)
* N Wang、DY Yeung，学习用于视觉跟踪的深度压缩图像表示，NIPS，2013.[[论文]](http://winsty.net/papers/dlt.pdf)
* Lijun Wang, Wanli Ouyang, Xiaogang Wang, and Huchuan Lu, Visual Tracking with fully Convolutional Networks, ICCV 2015  [[Paper](http://202.118.75.4/lu/Paper/ICCV2015/iccv15_lijun.pdf)] [[Code](https://github.com/scott89/FCNT)]
* Hyeonseob Namand Bohyung Han，学习用于视觉跟踪的多域卷积神经网络， [[Paper](http://arxiv.org/pdf/1510.07945.pdf)] [[Code](https://github.com/HyeonseobNam/MDNet)] [[Project Page](http://cvlab.postech.ac.kr/research/mdnet/)]

### Low-Level Vision

#### Super-Resolution
* 迭代图像重建
   * Sven Behnke：学习迭代图像重建.  IJCAI, 2001. [[论文]](http://www.ais.uni-bonn.de/behnke/papers/ijcai01.pdf)
   * Sven Behnke：在神经抽象金字塔中学习迭代图像重建. 国际计算智能与应用杂志，第一卷.  1，没有.  4, pp. 427-438, 2001. [[论文]](http://www.ais.uni-bonn.de/behnke/papers/ijcia01.pdf)
* 超分辨率 (SRCNN) [[Web]](http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html) [[Paper-ECCV14]](http://personal.ie.cuhk .edu.hk/~ccloy/files/eccv_2014_deepresolution.pdf) [[Paper-arXiv15]](http://arxiv.org/pdf/1501.00092.pdf)
  * Chao Dong、Chen Chang Loy、Kaiming He、Xiaoou Tang，学习用于图像超分辨率的深度卷积网络，ECCV，2014.
  * Chao Dong, Chen Change Loy, Kaiming He, Xiaoou Tang, Image Super-Resolution Using Deep Convolutional Networks, arXiv:1501.00092.
* 非常深的超分辨率
  * Jiwon Kim、Jung Kwon Lee、Kyoung Mu Lee，使用超深卷积网络实现精确图像超分辨率，arXiv:1511.04587，2015 年.[[论文]](http://arxiv.org/abs/1511.04587)
* 深度递归卷积网络
  * Jiwon Kim、Jung Kwon Lee、Kyoung Mu Lee，用于图像超分辨率的深度递归卷积网络，arXiv:1511.04491，2015 年.[[论文]](http://arxiv.org/abs/1511.04491)
* Casade-稀疏编码网络
   * Zhaowen Wang、Ding Liu、Wei Han、Jianchao Yang 和 Thomas S. Huang，具有稀疏先验的图像超分辨率深度网络.  ICCV, 2015. [[论文]](http://www.ifp.illinois.edu/~dingliu2/iccv15/iccv15.pdf) [[代码]](http://www.ifp.illinois.edu/~ dingliu2/iccv15/)
* 超分辨率的感知损失
  * Justin Johnson、Alexandre Alahi、Li Fei-Fei，实时风格迁移和超分辨率的感知损失，arXiv:1603.08155，2016 年.[[论文]](http://arxiv.org/abs/1603.08155) [ [补充]](http://cs.stanford.edu/people/jcjohns/papers/fast-style/fast-style-supp.pdf)
* SRGAN
  * Christian Ledig、Lucas Theis、Ferenc Huszar、Jose Caballero、Andrew Cunningham、Alejandro Acosta、Andrew Aitken、Alykhan Tejani、Johannes Totz、Zehan Wang、Wenzhe Shi，使用生成对抗网络的逼真单图像超分辨率，arXiv： 1609.04802v3, 2016. [[论文]](https://arxiv.org/pdf/1609.04802v3.pdf)
* 其他
  * Osendorfer、Christian、Hubert Soyer 和 Patrick van der Smagt，具有快速近似卷积稀疏编码的图像超分辨率，ICONIP，2014.[[Paper ICONIP-2014]](http://brml.org/uploads/tx_sibibtex/ 281.pdf)

#### Other Applications
* 光流 (FlowNet) [[论文]](http://arxiv.org/pdf/1504.06852)
  * Philipp Fischer, Alexey Dosovitskiy, Eddy Ilg, Philip Häusser, Caner Hazırbaş, Vladimir Golkov, Patrick van der Smagt, Daniel Cremers, Thomas Brox, FlowNet: Learning Optical Flow with Convolutional Networks, arXiv:1504.06852.
*压缩伪影减少[[Paper-arXiv15]](http://arxiv.org/pdf/1504.06993)
  * Chao Dong、Yubin Deng、Chen Change Loy、Xiaoou Tang，深度卷积网络减少压缩伪影，arXiv：1504.06993.
* 模糊去除
  * Christian J. Schuler、Michael Hirsch、Stefan Harmeling、Bernhard Schölkopf，Learning to Deblur，arXiv:1406.7444 [[论文]](http://arxiv.org/pdf/1406.7444.pdf)
  * Jian Sun, Wenfei Cao, Zongben Xu, Jean Ponce, Learning a Convolutional Neural Network for Non-uniform Motion Blur Removal, CVPR, 2015 [[论文]](http://arxiv.org/pdf/1503.00593)
* 图像反卷积 [[Web]](http://lxu.me/projects/dcnn/) [[Paper]](http://lxu.me/mypapers/dcnn_nips14.pdf)
  * Li Xu, Jimmy SJ. Ren, Ce Liu, Jiaya Jia, Deep Convolutional Neural Network for Image Deconvolution, NIPS, 2014.
* Deep Edge-Aware Filter [[论文]](http://jmlr.org/proceedings/papers/v37/xub15.pdf)
  * Li Xu, Jimmy SJ. Ren, Qiong Yan, Renjie Liao, Jiaya Jia, Deep Edge-Aware Filters, ICML, 2015.
  * Jure Žbontar、Yann LeCun，使用卷积神经网络计算立体匹配成本，CVPR，2015 年.
* 彩色图像着色 Richard Zhang、Phillip Isola、Alexei A. Efros，ECCV，2016 [[论文]](http://arxiv.org/pdf/1603.08511.pdf)，[[代码]](https://github .com/richzhang/colorization)
* Ryan Dahl，[[博客]](http://tinyclouds.org/colorize/)
* 通过修复进行特征学习[[论文]](https://arxiv.org/pdf/1604.07379v1.pdf)[[代码]](https://github.com/pathak22/context-encoder)
  * Deepak Pathak、Philipp Krahenbuhl、Jeff Donahue、Trevor Darrell、Alexei A. Efros，上下文编码器：通过修复进行特征学习，CVPR，2016

### Edge Detection
![edge_detection](https://cloud.githubusercontent.com/assets/5226447/8452371/93ca6f7e-2025-11e5-90f2-d428fd5ff7ac.PNG)
（来自 Gedas Bertasius、Jianbo Shi、Lorenzo Torresani，DeepEdge：用于自上而下轮廓检测的多尺度分叉深度网络，CVPR，2015 年.）

* 整体嵌套边缘检测 [[论文]](http://arxiv.org/pdf/1504.06375) [[代码]](https://github.com/s9xie/hed)
  * Saining Xie、Zhuowen Tu，整体嵌套边缘检测，arXiv：1504.06375.
* DeepEdge [[论文]](http://arxiv.org/pdf/1412.1123)
  * Gedas Bertasius、Jianbo Shi、Lorenzo Torresani，DeepEdge：用于自上而下轮廓检测的多尺度分叉深度网络，CVPR，2015 年.
* DeepContour [[论文]](http://mc.eistar.net/UpLoadFiles/Papers/DeepContour_cvpr15.pdf)
  * Wei Shen, Xinggang Wang, Yan Wang, Xiang Bai, Zhijiang Zhang, DeepContour: A Deep Convolutional Feature Learned by Positive-Sharing Loss for Contour Detection, CVPR, 2015.

### Semantic Segmentation
![semantic_segmantation](https://cloud.githubusercontent.com/assets/5226447/8452076/0ba8340c-2023-11e5-88bc-bebf4509b6bb.PNG)
（来自 Jifeng Dai、Kaiming He、Jian Sun，BoxSup：利用边界框监督卷积网络进行语义分割，arXiv：1503.01640.）
* PASCAL VOC2012 挑战排行榜（2016 年 9 月 1 日）
  ![VOC2012_top_rankings](https://cloud.githubusercontent.com/assets/3803777/18164608/c3678488-7038-11e6-9ec1-74a1542dce13.png)
  （来自 PASCAL VOC2012 [leaderboards](http://host.robots.ox.ac.uk:8080/leaderboard/displaylb.php?challengeid=11&compid=6))
* SEC：种子、扩展和约束
  * Alexander Kolesnikov、Christoph Lampert，种子、扩展和约束：弱监督图像分割的三个原则，ECCV，2016.[[论文]](http://pub.ist.ac.at/~akolesnikov/files/ECCV2016 /main.pdf) [[代码]](https://github.com/kolesman/SEC)
* Adelaide
   * Guosheng Lin、Chunhua Shen、Ian Reid、Anton van dan Hengel，用于语义分割的深度结构化模型的高效分段训练，arXiv：1504.01013.  [[论文]](http://arxiv.org/pdf/1504.01013)（VOC2012排名第一）
   * Guosheng Lin、Chunhua Shen、Ian Reid、Anton van den Hengel，深度学习消息传递推理中的消息，arXiv：1508.02108.  [[论文]](http://arxiv.org/pdf/1506.02108)（VOC2012排名第4）
* 深度解析网络（DPN）
  * Ziwei Liu、Xiaoxiao Li、Ping Luo、Chen Change Loy、Xiaoou Tang，通过深度解析网络进行语义图像分割，arXiv:1509.02634 / ICCV 2015 [[论文]](http://arxiv.org/pdf/1509.02634.pdf ) (VOC 2012排名第2)
* CentraleSuperBoundaries，INRIA [[论文]](http://arxiv.org/pdf/1511.07386)
  * Iasonas Kokkinos，使用深度学习在边界检测中超越人类，arXiv：1411.07386（VOC 2012 排名第 4）
* BoxSup [[论文]](http://arxiv.org/pdf/1503.01640)
   * Jifeng Dai、Kaiming He、Jian Sun、BoxSup：利用边界框监督卷积网络进行语义分割，arXiv：1503.01640.  （VOC2012排名第6）
* 态度
   * Hyeonwoo Noh、Seunghoon Hong、Bohyung Han，用于语义分割的学习反卷积网络，arXiv：1505.04366.  [[论文]](http://arxiv.org/pdf/1505.04366)（VOC2012排名第7）
   * Seunghoon Hong、Hyeonwoo Noh、Bohyung Han，用于半监督语义分割的解耦深度神经网络，arXiv：1506.04924.  [[论文]](http://arxiv.org/pdf/1506.04924)
  * Seunghoon Hong、Junhyuk Oh、Bohyung Han 和 Honglak Lee，使用深度卷积神经网络学习语义分割的可迁移知识，arXiv：1512.07928 [[Paper](http://arxiv.org/pdf/1512.07928.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/transfernet/)]
* 作为循环神经网络的条件随机场 [[论文]](http://arxiv.org/pdf/1502.03240)
   * Shuai Zheng、Sadeep Jayasumana、Bernardino Romera-Paredes、Vibhav Vineet、Zhizhong Su、Dalong Du、Chang Huang、Philip HS Torr，作为循环神经网络的条件随机场，arXiv：1502.03240.  （VOC2012排名第8）
* 深度实验室
   * Liang-Chieh Chen、George Papandreou、Kevin Murphy、Alan L. Yuille，用于语义图像分割的 DCNN 的弱监督和半监督学习，arXiv：1502.02734.  [[论文]](http://arxiv.org/pdf/1502.02734)（VOC2012排名第9）
  * Mohammadreza Mostajabi、Payman Yadollahpour、Gregory Shakhnarovich，具有缩小功能的前馈语义分割，CVPR，2015
* 联合校准 [[论文]](http://arxiv.org/pdf/1507.01581)
  * Holger Caesar、Jasper Uijlings、Vittorio Ferrari，语义分割的联合校准，arXiv：1507.01581.
  * Jonathan Long、Evan Shelhamer、Trevor Darrell，用于语义分割的完全卷积网络，CVPR，2015 年.
  * Bharath Hariharan、Pablo Arbelaez、Ross Girshick、Jitendra Malik，用于对象分割和细粒度本地化的超列，CVPR，2015 年.
* 深度层次解析
  * Abhishek Sharma、Oncel Tuzel、David W. Jacobs，语义分割的深度层次解析，CVPR，2015 年.[[论文]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sharma_Deep_Hierarchical_Parsing_2015_CVPR_paper.pdf )
* 学习场景标签的分层特征 [[Paper-ICML12]](http://yann.lecun.com/exdb/publis/pdf/farabet-icml-12.pdf) [[Paper-PAMI13]](http:/ /yann.lecun.com/exdb/publis/pdf/farabet-pami-13.pdf)
  * Clement Farabet、Camille Couprie、Laurent Najman、Yann LeCun，场景解析与多尺度特征学习、纯度树和最佳覆盖，ICML，2012 年.
  * Clement Farabet、Camille Couprie、Laurent Najman、Yann LeCun，Learning Hierarchical Features for Scene Labeling，PAMI，2013.
* 剑桥大学 [[Web]](http://mi.eng.cam.ac.uk/projects/segnet/)
   * Vijay Badrinarayanan、Alex Kendall 和 Roberto Cipolla “SegNet：一种用于图像分割的深度卷积编码器-解码器架构.”  arXiv 预印本 arXiv:1511.00561, 2015. [[论文]](http://arxiv.org/abs/1511.00561)
 * Alex Kendall、Vijay Badrinarayanan 和 Roberto Cipolla “贝叶斯 SegNet：用于场景理解的深度卷积编码器-解码器架构中的模型不确定性.”  arXiv 预印本 arXiv:1511.02680, 2015. [[论文]](http://arxiv.org/abs/1511.00561)
* Princeton
  * Fisher Yu，Vladlen Koltun，“通过扩张卷积进行多尺度上下文聚合”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.07122v2.pdf)]
 *大学. 华盛顿的 Allen AI
  * Hamid Izadinia、Fereshteh Sadeghi、Santosh Kumar Divvala、Yejin Choi、Ali Farhadi，“用于语义分割、视觉蕴含和释义的句段短语表”，ICCV，2015 年， [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Izadinia_Segment-Phrase_Table_for_ICCV_2015_paper.pdf)]
* 因里亚
  * Iasonas Kokkinos，“使用深度学习突破边界检测的边界”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.07386v2.pdf)]
* 加州大学圣地亚哥分校
  * Niloufar Pourian、S. Karthikeyan 和 BS Manjunath，“通过图像部分学习社区进行基于弱监督图的语义分割”，ICCV，2015 年， [[Paper](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Pourian_Weakly_Supervised_Graph_ICCV_2015_paper.pdf)]

### Visual Attention and Saliency
![saliency](https://cloud.githubusercontent.com/assets/5226447/8492362/7ec65b88-2183-11e5-978f-017e45ddba32.png)
(from Nian Liu, Junwei Han, Dingwen Zhang, Shifeng Wen, Tianming Liu, Predicting Eye Fixations using Convolutional Neural Networks, CVPR, 2015.)

  * Nian Liu, Junwei Han, Dingwen Zhang, Shifeng Wen, Tianming Liu, Predicting Eye Fixations using Convolutional Neural Networks, CVPR, 2015.
  * Saurabh Singh、Derek Hoiem、David Forsyth，Learning a Sequential Search for Landmarks，CVPR，2015 年.
* 具有视觉注意的多目标识别 [[论文]](http://arxiv.org/pdf/1412.7755.pdf)
  * Jimmy Leiba、Volodymyr Two、Koray Kavukcuoglu，具有视觉注意的多对象识别，ICLR，
* 视觉注意力的循环模型 [[论文]](http://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf)
  * Volodymyr Mnih、Nicolas Heess、Alex Graves、Koray Kavukcuoglu，视觉注意力的循环模型，NIPS，2014 年.

### Object Recognition
   * Maxime Oquab、Leon Bottou、Ivan Laptev、Josef Sivic，对象定位是免费的吗？  – 使用卷积神经网络进行弱监督学习，CVPR，2015 年.
  * Mircea Cimpoi、Subhransu Maji、Andrea Vedaldi，用于纹理识别和分割的深度滤波器组，CVPR，2015 年.

### Human Pose Estimation
* Zhe Cao, Tomas Simon, Shih-En Wei, and Yaser Sheikh, Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields, CVPR, 2017.
* Leonid Pishchulin、Eldar Insafutdinov、Siyu Tang、Bjoern Andres、Mykhaylo Andriluka、Peter Gehler 和 Bernt Schiele，Deepcut：多人姿势估计的联合子集划分和标记，CVPR，
* Shih-En Wei, Varun Ramakrishna, Takeo Kanade, and Yaser Sheikh, Convolutional pose machines, CVPR, 2016.
* Alejandro Newell、Kaiyu Yang 和 Jia Deng，用于人体姿势估计的堆叠沙漏网络，ECCV，2016 年.
* Tomas Pfister、James Charles 和 Andrew Zisserman，用于视频中人体姿势估计的流动卷积神经网络，ICCV，2015 年.
* Jonathan J. Tompson、Arjun Jain、Yann LeCun、Christoph Bregler，卷积网络联合训练和人体姿态估计图形模型，NIPS，2014 年.

### Understanding CNN
![understanding](https://cloud.githubusercontent.com/assets/5226447/8452083/1aaa0066-2023-11e5-800b-2248ead51584.PNG)
（来自 Aravindh Mahendran、Andrea Vedaldi，通过反转它们来理解深度图像表示，CVPR，2015 年.）

* Bolei Zhou、Aditya Khosla、Agata Lapedriza、Aude Oliva、Antonio Torralba，深度场景 CNN 中出现的物体检测器，ICLR，2015 年.
* Alexey Dosovitskiy、Thomas Brox，使用卷积网络反转视觉表示，arXiv，2015 年.[[论文]](http://arxiv.org/abs/1506.02753)
* Matthrew Zeiler、Rob Fergus，可视化和理解卷积网络，ECCV，2014 年.[[论文]](https://www.cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf)


### Image and Language

#### Image Captioning
![image_captioning](https://cloud.githubusercontent.com/assets/5226447/8452051/e8f81030-2022-11e5-85db-c68e7d8251ce.PNG)
（来自 Andrej Karpathy、Li Fei-Fei，Deep Visual-Semantic Alignments for Generating Image Description，CVPR，2015 年.）

* UCLA / 百度[[论文]](http://arxiv.org/pdf/1410.1090)
  * Junhua Mao, Wei Xu, Yi Yang, Jiang Wang, Alan L. Yuille, Explain Images with Multimodal Recurrent Neural Networks, arXiv:1410.1090.
* Toronto [[Paper]](http://arxiv.org/pdf/1411.2539)
  * Ryan Kiros、Ruslan Salakhutdinov、Richard S. Zemel，使用多模态神经语言模型统一视觉语义嵌入，arXiv：1411.2539.
* 伯克利 [[论文]](http://arxiv.org/pdf/1411.4389)
  * Jeff Donahue、Lisa Anne Hendricks、Sergio Guadarrama、Marcus Rohrbach、Subhashini Venugopalan、Kate Saenko、Trevor Darrell，用于视觉识别和描述的长期循环卷积网络，arXiv：1411.4389.
* 谷歌[[论文]](http://arxiv.org/pdf/1411.4555)
  * Oriol Vinyals、Alexander Toshev、Samy Bengio、Dumitru Erhan，展示和讲述：神经图像字幕生成器，arXiv：1411.4555.
* 斯坦福 [[Web]](http://cs.stanford.edu/people/karpathy/deepimagesent/) [[论文]](http://cs.stanford.edu/people/karpathy/cvpr2015.pdf)
  * Andrej Karpathy、Li Fei-Fei，用于生成图像描述的深度视觉语义对齐，CVPR，2015 年.
* UML / UT [[论文]](http://arxiv.org/pdf/1412.4729)
  * Subhashini Venugopalan、Huijuan Xu、Jeff Donahue、Marcus Rohrbach、Raymond Mooney、Kate Saenko，使用深度递归神经网络将视频翻译成自然语言，NAACL-HLT，2015 年.
* CMU / 微软 [[Paper-arXiv]](http://arxiv.org/pdf/1411.5654) [[Paper-CVPR]](http://www.cs.cmu.edu/~xinleic/papers/cvpr15_rnn .pdf)
  * Xinlei Chen，C. Lawrence Zitnick，学习图像标题生成的循环视觉表示，arXiv：1411.5654.
  * Xinlei Chen, C. Lawrence Zitnick, Mind&#39;s Eye: A Recurrent Visual Representation for Image Caption Generation, CVPR 2015
* 微软 [[论文]](http://arxiv.org/pdf/1411.4952)
  * Hao Fang、Saurabh Gupta、Forrest Iandola、Rupesh Srivastava、Li Deng、Piotr Dollár、Jianfeng Gao、Xiaodong He、Margaret Mitchell、John C. Platt、C. Lawrence Zitnick、Geoffrey Zweig，从字幕到视觉概念及背面，CVPR , 2015.
 *大学. 蒙特利尔/大学. 多伦多 [[Web](http://kelvinxu.github.io/projects/capgen.html)] [[Paper](http://www.cs.toronto.edu/~zemel/documents/captionAttn.pdf)]
  * Kelvin Xu、Jimmy Lei Ba、Ryan Kiros、Kyunghyun Cho、Aaron Courville、Ruslan Salakhutdinov、Richard S. Zemel、Yoshua Bengio，Show、Attend 和 Tell：具有视觉注意力的神经图像字幕生成，arXiv:1502.03044 / ICML 2015
* Idiap / EPFL / Facebook [[Paper](http://arxiv.org/pdf/1502.03671)]
  * Remi Lebret、Peter O. Pinheiro、Ronan Collobert，基于短语的图像说明，arXiv:1502.03671/ICML2015
*加州大学洛杉矶分校/百度 [[Paper](http://arxiv.org/pdf/1504.06692)]
  * Junhua Mao, Wei Xu, Yi Yang, Jiang Wang, Zhiheng Huang, Alan L. Yuille, Learning like a Child: Fast Novel Visual Concept Learning from Sentence Descriptions of Images, arXiv:1504.06692
* 硕士 + 伯克利
  * Jacob Devlin、Saurabh Gupta、Ross Girshick、Margaret Mitchell、C. Lawrence Zitnick，Exploring Nearest Neighbor Approaches for Image Captioning，arXiv：1505.04467 [[Paper](http://arxiv.org/pdf/1505.04467.pdf)]
  * Jacob Devlin、Hao Cheng、Hao Fang、Saurabh Gupta、Li Deng、Xiaodong He、Geoffrey Zweig、Margaret Mitchell，图像字幕的语言模型：怪癖和有效方法，arXiv：1505.01809 [[Paper](http://arxiv.org/pdf/1505.01809.pdf)]
* Adelaide [[Paper](http://arxiv.org/pdf/1506.01144.pdf)]
  * Qi Wu, Chunhua Shen, Anton van den Hengel, Lingqiao Liu, Anthony Dick, Image Captioning with an Intermediate Attributes Layer, arXiv:1506.01144
*蒂尔堡 [[Paper](http://arxiv.org/pdf/1506.03694.pdf)]
  * Grzegorz Chrupala, Akos Kadar, Afra Alishahi, Learning language through pictures, arXiv:1506.03694
 *大学. 蒙特利尔 [[Paper](http://arxiv.org/pdf/1507.01053.pdf)]
  * Kyunghyun Cho、Aaron Courville、Yoshua Bengio，使用基于注意力的编码器-解码器网络描述多媒体内容，arXiv：1507.01053
* 康奈尔 [[Paper](http://arxiv.org/pdf/1508.02091.pdf)]
  * Jack Hessel、Nicolas Savva、Michael J. Wilber，神经图像字幕中的图像表示和新领域，arXiv：1508.02091
  * Ting Yao、Tao Mei 和 Chong-Wah Ngo，“Learning Query and Image Similarities
    with Ranking Canonical Correlation Analysis”, ICCV, 2015

#### Video Captioning
* 伯克利 [[Web]](http://jeffdonahue.com/lrcn/) [[论文]](http://arxiv.org/pdf/1411.4389.pdf)
  * Jeff Donahue、Lisa Anne Hendricks、Sergio Guadarrama、Marcus Rohrbach、Subhashini Venugopalan、Kate Saenko、Trevor Darrell，用于视觉识别和描述的长期循环卷积网络，CVPR，2015 年.
* UT / UML / Berkeley [[论文]](http://arxiv.org/pdf/1412.4729)
  * Subhashini Venugopalan、Huijuan Xu、Jeff Donahue、Marcus Rohrbach、Raymond Mooney、Kate Saenko，使用深度递归神经网络将视频翻译成自然语言，arXiv：1412.4729.
* 微软 [[论文]](http://arxiv.org/pdf/1505.01861)
  * Yingwei Pan, Tao Mei, Ting Yao, Houqiang Li, Yong Rui, Joint Modeling Embedding and Translation to Bridge Video and Language, arXiv:1505.01861.
* UT / Berkeley / UML [[论文]](http://arxiv.org/pdf/1505.00487)
  * Subhashini Venugopalan、Marcus Rohrbach、Jeff Donahue、Raymond Mooney、Trevor Darrell、Kate Saenko，序列到序列——视频到文本，arXiv：1505.00487.
 *大学. 蒙特利尔/大学. 舍布鲁克 [[Paper](http://arxiv.org/pdf/1502.08029.pdf)]
  * Li Yao、Atousa Torabi、Kyunghyun Cho、Nicolas Ballas、Christopher Pal、Hugo Larochelle、Aaron Courville，利用时间结构描述视频，arXiv：1502.08029
* MPI /伯克利 [[Paper](http://arxiv.org/pdf/1506.01698.pdf)]
  * Anna Rohrbach、Marcus Rohrbach、Bernt Schiele，电影描述的长短篇小说，arXiv：1506.01698
 *大学. 多伦多/麻省理工学院 [[Paper](http://arxiv.org/pdf/1506.06724.pdf)]
  * Yukun Zhu、Ryan Kiros、Richard Zemel、Ruslan Salakhutdinov、Raquel Urtasun、Antonio Torralba、Sanja Fidler，对齐书籍和电影：通过看电影和阅读书籍实现故事般的视觉解释，arXiv：1506.06724
 *大学. 蒙特利尔 [[Paper](http://arxiv.org/pdf/1507.01053.pdf)]
  * Kyunghyun Cho、Aaron Courville、Yoshua Bengio，使用基于注意力的编码器-解码器网络描述多媒体内容，arXiv：1507.01053
* 陶业大学/南加州大学 [[paper](https://arxiv.org/pdf/1612.06950.pdf)]
  * Dotan Kaufman、Gil Levi、Tal Hassner、Lior Wolf，视频注释和摘要的时间镶嵌，arXiv：1612.06950.

#### Question Answering
![question_answering](https://cloud.githubusercontent.com/assets/5226447/8452068/ffe7b1f6-2022-11e5-87ab-4f6d4696c220.PNG)
（来自 Stanislaw Antol、Aishwarya Agrawal、Jiasen Lu、Margaret Mitchell、Dhruv Batra、C. Lawrence Zitnick、Devi Parikh，VQA：视觉问答，CVPR，2015 SUNw：场景理解研讨会）

* 弗吉尼亚理工大学 / MSR [[Web]](http://www.visualqa.org/) [[论文]](http://arxiv.org/pdf/1505.00468)
  * Stanislaw Antol、Aishwarya Agrawal、Jiasen Lu、Margaret Mitchell、Dhruv Batra、C. Lawrence Zitnick、Devi Parikh、VQA：视觉问答、CVPR、2015 SUNw：场景理解研讨会.
* MPI / Berkeley [[Web]](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/vision-and-language/visual-turing-challenge/ ) [[论文]](http://arxiv.org/pdf/1505.01121)
  * Mateusz Malinowski、Marcus Rohrbach、Mario Fritz，问你的神经元：一种基于神经的方法来回答有关图像的问题，arXiv:1505.01121.
* 多伦多 [[论文]](http://arxiv.org/pdf/1505.02074) [[数据集]](http://www.cs.toronto.edu/~mren/imageqa/data/cocoqa/)
  * Mengye Ren、Ryan Kiros、Richard Zemel，图像问答：视觉语义嵌入模型和新数据集，arXiv:1505.02074 / ICML 2015 深度学习研讨会.
* 百度/加州大学洛杉矶分校 [[论文]](http://arxiv.org/pdf/1505.05612) [[数据集]]()
  * Hauyuan Gao, Junhua Mao, Jie Zhou, Zhiheng Huang, Lei Wang, Wei Xu, Are You Talking to a Machine? Dataset and Methods for Multilingual Image Question Answering, arXiv:1505.05612.
* 态度 [[Paper](http://arxiv.org/pdf/1511.05756.pdf)] [[Project Page](http://cvlab.postech.ac.kr/research/dppnet/)]
  * Hyeonwoo Noh、Paul Hongsuck Seo 和 Bohyung Han，使用具有动态参数预测的卷积神经网络进行图像问答，arXiv：1511.05765
* 卡内基梅隆大学 / 微软研究院 [[Paper](http://arxiv.org/pdf/1511.02274v2.pdf)]
   * Yang, Z.、He, X.、Gao, J.、Deng, L. 和 Smola, A.（2015 年）. 用于图像问答的堆叠注意网络.  arXiv:1511.02274.
*元思维 [[Paper](http://arxiv.org/pdf/1603.01417v1.pdf)]
  * Xiong, Caiming, Stephen Merity, and Richard Socher. "Dynamic Memory Networks for Visual and Textual Question Answering." arXiv:1603.01417 (2016).
* 转向 + 集线器 [[Paper](http://arxiv.org/abs/1606.01455)]
  * Jin-Hwa Kim、Sang-Woo Lee、Dong-Hyun Kwak、Min-Oh Heo、Jeonghee Kim、Jung-Woo Ha、Byoung-Tak Zhang，*视觉 QA 的多模式残差学习*，arXiv:1606:01455
* 加州大学伯克利分校 + 索尼 [[Paper](https://arxiv.org/pdf/1606.01847)]
  * Akira Fukui、Dong Huk Park、Daylen Yang、Anna Rohrbach、Trevor Darrell 和 Marcus Rohrbach，*用于视觉问答和视觉基础的多模式紧凑双线性池*，arXiv：1606.01847
* 邮政科技 [[Paper](http://arxiv.org/pdf/1606.03647.pdf)]
  * Hyeonwoo Noh 和 Bohyung Han，*使用 VQA 的联合损失最小化训练循环应答单元*，arXiv：1606.03647
* 转向 + 集线器 [[Paper](http://arxiv.org/abs/1610.04325)]
  * Jin-Hwa Kim、Kyoung Woon On、Jeonghee Kim、Jung-Woo Ha、Byoung-Tak Zhang，*低秩双线性池化的 Hadamard 积*，arXiv：1610.04325.

### Image Generation
* 卷积/循环网络
   * Aäron van den Oord、Nal Kalchbrenner、Oriol Vinyals、Lasse Espeholt、Alex Graves、Koray Kavukcuoglu.  “使用 PixelCNN 解码器生成条件图像”[[论文]](https://arxiv.org/pdf/1606.05328v2.pdf)[[代码]](https://github.com/kundan2510/pixelCNN)
  * Alexey Dosovitskiy、Jost Tobias Springenberg、Thomas Brox，“学习使用卷积神经网络生成椅子”，CVPR，2015 年.[[论文]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/ Dosovitskiy_Learning_to_Generate_2015_CVPR_paper.pdf)
  * Karol Gregor、Ivo Danihelka、Alex Graves、Danilo Jimenez Rezende、Daan Wierstra，“DRAW：用于图像生成的递归神经网络”，ICML，2015 年. [[Paper](https://arxiv.org/pdf/1502.04623v2.pdf)] 
* 对抗网络
  * Ian J. Goodfellow、Jean Pouget-Abadie、Mehdi Mirza、Bing Xu、David Warde-Farley、Sherjil Ozair、Aaron Courville、Yoshua Bengio，生成对抗网络，NIPS，2014 年.[[论文]](http://arxiv .org/abs/1406.2661)
  * Emily Denton、Soumith Chintala、Arthur Szlam、Rob Fergus，Deep Generative Image Models using a ￼Laplacian Pyramid of Adversarial Networks，NIPS，2015.[[论文]](http://arxiv.org/abs/1506.05751)
  * Lucas Theis、Aäron van den Oord、Matthias Bethge，“关于生成模型评估的说明”，ICLR 2016. [[Paper](http://arxiv.org/abs/1511.01844)]
  * Zhenwen Dai、Andreas Damianou、Javier Gonzalez、Neil Lawrence，“变分自动编码深度高斯过程”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06455v2.pdf)]
  * Elman Mansimov、Emilio Parisotto、Jimmy Ba、Ruslan Salakhutdinov，“使用注意力从字幕生成图像”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.02793v2.pdf)]
  * Jost Tobias Springenberg，“使用分类生成对抗网络进行无监督和半监督学习”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.06390v1.pdf)]
  * Harrison Edwards、Amos Storkey，“与对手的审查陈述”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.05897v3.pdf)]
  * Takeru Miyato、Shin-ichi Maeda、Masanori Koyama、Ken Nakae、Shin Ishii，“虚拟对抗训练的分布平滑”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1507.00677v8.pdf)]
  * Jun-Yan Zhu、Philipp Krahenbuhl、Eli Shechtman 和 Alexei A. Efros，“自然图像流形上的生成视觉操作”，ECCV [[Paper](https://arxiv.org/pdf/1609.03552v2.pdf)] [[Code](https://github.com/junyanz/iGAN)] [[Video](https://youtu.be/9c4z6YsBGQ0)]
* 混合卷积网络和对抗网络
  * Alec Radford、Luke Metz、Soumith Chintala，“使用深度卷积生成对抗网络进行无监督表示学习”，ICLR 2016. [[Paper](http://arxiv.org/pdf/1511.06434.pdf)]

### Other Topics
*视觉类比 [[Paper](https://web.eecs.umich.edu/~honglak/nips2015-analogy.pdf)]
  * Scott Reed、Yi Zhang、Yuting Zhang、Honglak Lee，Deep Visual Analogy Making，NIPS，2015
  * Xiaolong Wang、David F. Fouhey、Abhinav Gupta，设计用于表面法线估计的深度网络，CVPR，2015 年.
  * Georgia Gkioxari、Jitendra Malik，Finding Action Tubes，CVPR，2015 年.
  * Cong Zhang, Hongsheng Li, Xiaogang Wang, Xiaokang Yang, Cross-scene Crowd Counting via Deep Convolutional Neural Networks, CVPR, 2015.
  * Fang Wang、Le Kang、Yi Li，使用卷积神经网络进行基于草图的 3D 形状检索，CVPR，2015 年.
* 弱监督分类
  * Samaneh Azadi、Jiashi Feng、Stefanie Jegelka、Trevor Darrell，“带有噪声标签的深度 CNN 的辅助图像正则化”，ICLR 2016， [[Paper](http://arxiv.org/pdf/1511.07069v2.pdf)]
* 艺术风格 [[论文]](http://arxiv.org/abs/1508.06576) [[代码]](https://github.com/jcjohnson/neural-style)
  * Leon A. Gatys、Alexander S. Ecker、Matthias Bethge，艺术风格的神经算法.
* 人类注视估计
  * Xucong Zhang、Yusuke Sugano、Mario Fritz、Andreas Bulling，野外基于外观的注视估计，CVPR，2015 年.[[论文]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/ Zhang_Appearance-Based_Gaze_Estimation_2015_CVPR_paper.pdf) [[网站]](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/gaze-based-human-computer-interaction/基于外观的注视估计在野外 mpiigaze/)
* 人脸识别
  * Yaniv Taigman、Ming Yang、Marc&#39;Aurelio Ranzato、Lior Wolf、DeepFace：缩小人脸验证中与人类水平性能的差距，CVPR，2014 年.[[论文]](https://www.cs.toronto.edu /~ranzato/publications/taigman_cvpr14.pdf)
  * Yi Sun, Ding Liang, Xiaogang Wang, Xiaoou Tang, DeepID3: Face Recognition with Very Deep Neural Networks, 2015. [[论文]](http://arxiv.org/abs/1502.00873)
  * Florian Schroff、Dmitry Kalenichenko、James Philbin，FaceNet：人脸识别和聚类的统一嵌入，CVPR，2015 年.[[论文]](http://arxiv.org/abs/1503.03832)
* 面部地标检测
  * Yue Wu、Tal Hassner、KangGeon Kim、Gerard Medioni、Prem Natarajan，使用调整后的卷积神经网络进行面部标志检测，2015 年.[[论文]](http://arxiv.org/abs/1511.04031) [[项目]] (http://www.openu.ac.il/home/hassner/projects/tcnn_landmarks/)

## Courses
* 深度视觉
  * [斯坦福] [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
  * [CUHK] [ELEG 5040: Advanced Topics in Signal Processing(Introduction to Deep Learning)](https://piazza.com/cuhk.edu.hk/spring2015/eleg5040/home)
* 更多深度学习
  * [斯坦福] [CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/)
  * [牛津] [Deep Learning by Prof. Nando de Freitas](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
  * [纽约大学] [Deep Learning by Prof. Yann LeCun](http://cilvr.cs.nyu.edu/doku.php?id=courses:deeplearning2014:start)

## Books
* 免费在线书籍
  * [Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](http://www.iro.umontreal.ca/~bengioy/dlbook/)
  * [Neural Networks and Deep Learning by Michael Nielsen](http://neuralnetworksanddeeplearning.com/)
  * [Deep Learning Tutorial by LISA lab, University of Montreal](http://deeplearning.net/tutorial/deeplearning.pdf)

## Videos
* 会谈
  * [Deep Learning, Self-Taught Learning and Unsupervised Feature Learning By Andrew Ng](https://www.youtube.com/watch?v=n1ViNeWhC24)
  * [Recent Developments in Deep Learning By Geoff Hinton](https://www.youtube.com/watch?v=vShMxxqtDDs)
  * [The Unreasonable Effectiveness of Deep Learning by Yann LeCun](https://www.youtube.com/watch?v=sc-KbuZqGkI)
  * [Deep Learning of Representations by Yoshua bengio](https://www.youtube.com/watch?v=4xsVFLnHC_0)


## Software
### Framework
* Tensorflow：谷歌使用数据流图进行数值计算的开源软件库 [[Web](https://www.tensorflow.org/)]
* Torch7：Lua 中的深度学习库，被 Facebook 和 Google Deepmind 使用 [[Web](http://torch.ch/)]
  * 基于 Torch 的深度学习库： [[torchnet](https://github.com/torchnet/torchnet)],
* Caffe：BVLC 的深度学习框架 [[Web](http://caffe.berkeleyvision.org/)]
* Theano：Python 中的数学库，由 LISA 实验室维护 [[Web](http://deeplearning.net/software/theano/)]
  * 基于 Theano 的深度学习库： [[Pylearn2](http://deeplearning.net/software/pylearn2/)], [[Blocks](https://github.com/mila-udem/blocks)], [[Keras](http://keras.io/)], [[Lasagne](https://github.com/Lasagne/Lasagne)]
* MatConvNet：用于 MATLAB 的 CNN [[Web](http://www.vlfeat.org/matconvnet/)]
* MXNet：一个灵活高效的异构分布式系统深度学习库，支持多语言 [[Web](http://mxnet.io/)]
* Deepgaze：基于CNNs的人机交互计算机视觉库 [[Web](https://github.com/mpatacchiola/deepgaze)]

### Applications
* 对抗训练
  * 论文“生成对抗网络”[[Web]](https://github.com/goodfeli/adversarial) 的代码和超参数
* 理解和可视化
  *“通过反转理解深度图像表示”的源代码，CVPR，2015 年.[[Web]](https://github.com/aravindhm/deep-goggle)
* 语义分割
  * 论文“Rich feature hierarchies for accurate object detection and semantic segmentation”的源代码，CVPR，2014.[[Web]](https://github.com/rbgirshick/rcnn)
  * 论文“Fully Convolutional Networks for Semantic Segmentation”的源代码，CVPR，2015 年.[[Web]](https://github.com/longjon/caffe/tree/future)
* 超分辨率
  * 动漫风格的图像超分辨率 [[Web]](https://github.com/nagadomi/waifu2x)
* 边缘检测
  * 论文“DeepContour：通过轮廓检测的正共享损失学习的深度卷积特征”的源代码，CVPR，2015 年.[[Web]](https://github.com/shenwei1231/DeepContour)
  * 论文“整体嵌套边缘检测”的源代码，ICCV 2015.[[Web]](https://github.com/s9xie/hed)

## Tutorials
* [CVPR 2014] [Tutorial on Deep Learning in Computer Vision](https://sites.google.com/site/deeplearningcvpr2014/)
* [CVPR 2015] [Applied Deep Learning for Computer Vision with Torch](https://github.com/soumith/cvpr2015)

## Blogs
* [Deep down the rabbit hole: CVPR 2015 and beyond@Tombone's Computer Vision Blog](http://www.computervisionblog.com/2015/06/deep-down-rabbit-hole-cvpr-2015-and.html)
* [CVPR recap and where we're going@Zoya Bylinskii (MIT PhD Student)'s Blog](http://zoyathinks.blogspot.kr/2015/06/cvpr-recap-and-where-were-going.html)
* [Facebook's AI Painting@Wired](http://www.wired.com/2015/06/facebook-googles-fake-brains-spawn-new-visual-reality/)
* [Inceptionism: Going Deeper into Neural Networks@Google Research](http://googleresearch.blogspot.kr/2015/06/inceptionism-going-deeper-into-neural.html)
* [Implementing Neural networks](http://peterroelants.github.io/) 
