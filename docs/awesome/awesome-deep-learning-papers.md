## Awesome - Most Cited Deep Learning Papers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[注意]由于自2017年以来每天发布的大量深度学习论文，此列表不再维护.

最受推崇的深度学习论文的精选清单（2012-2016）

 我们相信存在*经典*深度学习论文，无论其应用领域如何都值得阅读.  我们不想提供大量的论文，而是提供一份精选的深度学习论文*，这些论文在某些研究领域被视为*必读*.

## Background

在此列表之前，还存在其他*令人敬畏的深度学习列表*，例如， [Deep Vision](https://github.com/kjw0612/awesome-deep-vision) and [Awesome Recurrent Neural Networks](https://github.com/kjw0612/awesome-rnn) .  此外，在此列表出来后，深度学习初学者的另一个很棒的列表，称为 [Deep Learning Papers Reading Roadmap](https://github.com/songrotek/Deep-Learning-Papers-Reading-Roadmap)，已被许多深度学习研究人员所创造和喜爱.

 虽然*路线图清单*包含了许多重要的深度学习论文，但是对我来说，阅读它们感觉压倒一切.  正如我在介绍中所提到的，我相信开创性的作品可以为我们提供课程，无论其应用领域如何.  因此，我想在这里介绍** 100篇深度学习论文**，作为深入学习深度学习的一个很好的起点.

要每天获取新发布的论文的新闻，请关注我 [twitter](https://twitter.com/TerryUm_ML) 要么 [facebook page](https://www.facebook.com/terryum.io/)! 

## Awesome list criteria

1.建议列出2012年至2016年发布的**前100名深度学习论文**.
2.如果在列表中添加了纸张，则应删除另一篇论文（通常来自2016年的“更多论文”部分）以保留前100篇论文.（因此，删除论文也是重要的贡献以及添加论文）
3.重要但未能列入清单的论文将列在*超过前100名*部分.
4.请参阅最近6个月或2012年之前发表的论文的*新论文*和*旧论文*部分.

*（引用标准）*
- **< 6 months** : *New Papers* (by discussion)
-  ** 2016 **：+ 60引用或“2016年更多论文”
-  ** 2015 **：+ 200引文
-  ** 2014 **：+ 400引文
-  ** 2013 **：+ 600引用
-  ** 2012 **：+800引用
-  ** ~2012 **：*旧论文*（通过讨论）

 请注意，我们更喜欢开创性的深度学习论文，可以应用于各种研究而不是应用论文.  出于这个原因，一些符合标准的论文可能不被接受而其他论文可能会被接受.  这取决于论文的影响，适用于其他研究领域的研究稀缺性等.

**We need your contributions!**

如果您有任何建议（缺少论文，新论文，主要研究人员或拼写错误），请随时编辑并提出请求.
（请阅读 [contributing guide](https://github.com/terryum/awesome-deep-learning-papers/blob/master/Contributing.md) 有关进一步的说明，虽然只是让我知道论文的标题也可以对我们做出很大的贡献.）

（更新）您可以下载所有前100篇论文 [this](https://github.com/terryum/awesome-deep-learning-papers/blob/master/fetch_papers.py) 并收集所有作者的姓名 [this](https://github.com/terryum/awesome-deep-learning-papers/blob/master/get_authors.py) .  也， [bib file](https://github.com/terryum/awesome-deep-learning-papers/blob/master/top100papers.bib)  所有前100篇论文都可用.  谢谢，doodhwala， [Sven](https://github.com/sunshinemyson) and [grepinsight](https://github.com/grepinsight)!

+任何人都可以提供代码来获取前100篇论文作者的统计数据吗？


## Contents

* [Understanding / Generalization / Transfer](#understanding--generalization--transfer)
* [Optimization / Training Techniques](#optimization--training-techniques)
* [Unsupervised / Generative Models](#unsupervised--generative-models)
* [Convolutional Network Models](#convolutional-neural-network-models)
* [Image Segmentation / Object Detection](#image-segmentation--object-detection)
* [Image / Video / Etc](#image--video--etc)
* [Natural Language Processing / RNNs](#natural-language-processing--rnns)
* [Speech / Other Domain](#speech--other-domain)
* [Reinforcement Learning / Robotics](#reinforcement-learning--robotics)
* [More Papers from 2016](#more-papers-from-2016)

*（超过前100名）*

* [New Papers](#new-papers) ：不到6个月
* [Old Papers](#old-papers) ：2012年之前
* [HW / SW / Dataset](#hw--sw--dataset) ：技术报告
* [Book / Survey / Review](#book--survey--review)
* [Video Lectures / Tutorials / Blogs](#video-lectures--tutorials--blogs)
* [Appendix: More than Top 100](#appendix-more-than-top-100) ：更多的论文不在列表中

* * *

### Understanding / Generalization / Transfer
  -  **在神经网络中提炼知识**（2015），G.Hinton等.  [[PDF]]（http://arxiv.org/pdf/1503.02531）
  -  **深度神经网络容易被愚弄：对无法识别的图像的高置信度预测**（2015），A.Nguyen等.  [[PDF]]（http://arxiv.org/pdf/1412.1897）
  -  **深度神经网络中的特征如何可转移？**（2014），J.Yosinski等.  [[PDF]]（http://papers.nips.cc/paper/5347-how-transferable-are-features-in-deep-neural-networks.pdf）
  -  **美国有线电视新闻网现有特色：一个令人震惊的识别基准**（2014年），A.Razavian等人.  [[PDF]]（http://www.cv-foundation.org//openaccess/content_cvpr_workshops_2014/W15/papers/Razavian_CNN_Features_Off-the-Shelf_2014_CVPR_paper.pdf）
  -  **使用卷积神经网络学习和转移中级图像表示**（2014），M.Oquab等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Oquab_Learning_and_Transferring_2014_CVPR_paper.pdf）
-  **可视化和理解卷积网络**（2014），M.Zeiler和R. Fergus [[pdf]]（http://arxiv.org/pdf/1311.2901）
  -  ** Decaf：用于通用视觉识别的深度卷积激活功能**（2014），J.Donahue等.  [[PDF]]（http://arxiv.org/pdf/1310.1531）

<!---[Key researchers]  [Geoffrey Hinton](https://scholar.google.ca/citations?user=JicYPdAAAAAJ), [Yoshua Bengio](https://scholar.google.ca/citations?user=kukA0LcAAAAJ), [Jason Yosinski](https://scholar.google.ca/citations?hl=en&user=gxL1qj8AAAAJ) -->

### Optimization / Training Techniques
  -  **培训非常深的网络**（2015），R.Srivastava等.  [[PDF]]（http://papers.nips.cc/paper/5850-training-very-deep-networks.pdf）
-  **批量标准化：通过减少内部协变量转换加速深度网络培训**（2015），S.Loffe和C. Szegedy [[pdf]]（http://arxiv.org/pdf/1502.03167）
  -  **深入研究整流器：超越图像网络分类的人类水平**（2015），K.He等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/He_Delving_Deep_into_ICCV_2015_paper.pdf）
  -  **辍学：一种防止神经网络过度拟合的简单方法**（2014），N.Srivastava等.  [[PDF]]（http://jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf）
-  ** Adam：一种随机优化方法**（2014），D.Kingma和J. Ba [[pdf]]（http://arxiv.org/pdf/1412.6980）
  -  **通过阻止特征检测器的共同适应改善神经网络**（2012），G.Hinton等.  [[PDF]]（http://arxiv.org/pdf/1207.0580.pdf）
-  **随机搜索超参数优化**（2012）J.Bergstra和Y.Bengio [[pdf]]（http://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a）

<!---[Key researchers] [Geoffrey Hinton](https://scholar.google.ca/citations?user=JicYPdAAAAAJ), [Yoshua Bengio](https://scholar.google.ca/citations?user=kukA0LcAAAAJ), [Christian Szegedy](https://scholar.google.ca/citations?hl=en&user=3QeF7mAAAAAJ), [Sergey Ioffe](https://scholar.google.ca/citations?user=S5zOyIkAAAAJ), [Kaming He](https://scholar.google.ca/citations?hl=en&user=DhtAFkwAAAAJ), [Diederik P. Kingma](https://scholar.google.ca/citations?hl=en&user=yyIoQu4AAAAJ)-->

### Unsupervised / Generative Models
  -  ** Pixel recurrent neural networks **（2016），A.Oord et al.  [[PDF]]（http://arxiv.org/pdf/1601.06759v2.pdf）
  -  **改进训练GAN的技术**（2016），T.Salimans等.  [[PDF]]（http://papers.nips.cc/paper/6125-improved-techniques-for-training-gans.pdf）
  -  **使用深度卷积生成对抗网络的无监督表示学习**（2015），A.Radford等.  [[PDF]]（https://arxiv.org/pdf/1511.06434v2）
  -  ** DRAW：用于图像生成的递归神经网络**（2015），K.Gregor等.  [[PDF]]（http://arxiv.org/pdf/1502.04623）
  -  **生成对抗网**（2014年），I.Goodfellow等.  [[PDF]]（http://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf）
-  **自动编码变分贝叶斯**（2013），D.Kingma和M. Welling [[pdf]]（http://arxiv.org/pdf/1312.6114）
  -  **使用大规模无监督学习建立高级特征**（2013），Q.Le等人.  [[PDF]]（http://arxiv.org/pdf/1112.6209）

<!---[Key researchers] [Yoshua Bengio](https://scholar.google.ca/citations?user=kukA0LcAAAAJ), [Ian Goodfellow](https://scholar.google.ca/citations?user=iYN86KEAAAAJ), [Alex Graves](https://scholar.google.ca/citations?user=DaFHynwAAAAJ)-->
### Convolutional Neural Network Models
  -  **重新思考计算机视觉的初始架构**（2016），C.Szegedy等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.pdf）
  -  ** Inception-v4，inception-resnet和剩余联系对学习的影响**（2016），C.Szegedy等.  [[PDF]]（http://arxiv.org/pdf/1602.07261）
  -  **深度剩余网络中的身份映射**（2016），K.He等.  [[PDF]]（https://arxiv.org/pdf/1603.05027v2.pdf）
  -  **用于图像识别的深度残差学习**（2016），K.He等.  [[PDF]]（http://arxiv.org/pdf/1512.03385）
-  **空间变压器网络**（2015），M.Jaderberg等，[[pdf]]（http://papers.nips.cc/paper/5854-spatial-transformer-networks.pdf）
  -  **深入研究**（2015），C.Szegedy等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf）
-  **用于大规模图像识别的非常深的卷积网络**（2014），K.Simonyan和A. Zisserman [[pdf]]（http://arxiv.org/pdf/1409.1556）
  -  **细节中的魔鬼回归：深入研究卷积网**（2014），K.Chatfield等.  [[PDF]]（http://arxiv.org/pdf/1405.3531）
  -  ** OverFeat：使用卷积网络进行综合识别，定位和检测**（2013），P.Sermanet等.  [[PDF]]（http://arxiv.org/pdf/1312.6229）
  -  ** Maxout networks **（2013），I.Goodfellow et al.  [[PDF]]（http://arxiv.org/pdf/1302.4389v4）
  -  **网络网络**（2013），M.Lin等.  [[PDF]]（http://arxiv.org/pdf/1312.4400）
  -  **使用深度卷积神经网络的ImageNet分类**（2012），A.Krizhevsky等.  [[PDF]]（http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf）

<!---[Key researchers]  [Christian Szegedy](https://scholar.google.ca/citations?hl=en&user=3QeF7mAAAAAJ), [Kaming He](https://scholar.google.ca/citations?hl=en&user=DhtAFkwAAAAJ), [Shaoqing Ren](https://scholar.google.ca/citations?hl=en&user=AUhj438AAAAJ), [Jian Sun](https://scholar.google.ca/citations?hl=en&user=ALVSZAYAAAAJ), [Geoffrey Hinton](https://scholar.google.ca/citations?user=JicYPdAAAAAJ), [Yoshua Bengio](https://scholar.google.ca/citations?user=kukA0LcAAAAJ), [Yann LeCun](https://scholar.google.ca/citations?hl=en&user=WLN3QrAAAAAJ)-->

### Image: Segmentation / Object Detection
  -  **你只看一次：统一的实时物体检测**（2016），J.Redmon等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Redmon_You_Only_Look_CVPR_2016_paper.pdf）
  -  **用于语义分割的完全卷积网络**（2015），J.Long等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf）
  -  **更快的R-CNN：利用区域提案网络实现实时目标检测**（2015），S.Ren等.  [[PDF]]（http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf）
-  **快速R-CNN **（2015），R.Girshick [[pdf]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Girshick_Fast_R-CNN_ICCV_2015_paper.pdf）
  -  **用于精确对象检测和语义分割的丰富特征层次结构**（2014），R.Girshick等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf）
  -  **用于视觉识别的深度卷积网络中的空间金字塔池**（2014），K.He等.  [[PDF]]（http://arxiv.org/pdf/1406.4729）
  -  **使用深度卷积网和完全连接的CRF进行语义图像分割**，L.Chen等.  [[PDF]]（https://arxiv.org/pdf/1412.7062）
  -  **学习场景标记的等级特征**（2013），C.Farabet等.  [[PDF]]（https://hal-enpc.archives-ouvertes.fr/docs/00/74/20/77/PDF/farabet-pami-13.pdf）

<!---[Key researchers]  [Ross Girshick](https://scholar.google.ca/citations?hl=en&user=W8VIEZgAAAAJ), [Jeff Donahue](https://scholar.google.ca/citations?hl=en&user=UfbuDH8AAAAJ), [Trevor Darrell](https://scholar.google.ca/citations?hl=en&user=bh-uRFMAAAAJ)-->

### Image / Video / Etc
  -  **使用深度卷积网络的图像超分辨率**（2016），C.Dong等.  [[PDF]]（https://arxiv.org/pdf/1501.00092v3.pdf）
  -  **艺术风格的神经算法**（2015），L.Gatys等.  [[PDF]]（https://arxiv.org/pdf/1508.06576）
-  **用于生成图像描述的深度视觉语义对齐**（2015），A.Karpathy和L. Fei-Fei [[pdf]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers /Karpathy_Deep_Visual-Semantic_Alignments_2015_CVPR_paper.pdf）
  -  **显示，参与和讲述：视觉注意的神经图像标题生成**（2015），K.Xu等.  [[PDF]]（http://arxiv.org/pdf/1502.03044）
  -  **显示和告诉：神经图像标题生成器**（2015），O.Vinyals等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Vinyals_Show_and_Tell_2015_CVPR_paper.pdf）
  -  **用于视觉识别和描述的长期复发卷积网络**（2015），J.Donahue等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Donahue_Long-Term_Recurrent_Convolutional_2015_CVPR_paper.pdf）
  -  ** VQA：视觉问题回答**（2015），S.Antol等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Antol_VQA_Visual_Question_ICCV_2015_paper.pdf）
  -  ** DeepFace：弥补面部验证中人类绩效的差距**（2014），Y.Taigman等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Taigman_DeepFace_Closing_the_2014_CVPR_paper.pdf）：
  -  **使用卷积神经网络的大规模视频分类**（2014），A.Karpathy等.  [[PDF]]（http://vision.stanford.edu/pdf/karpathy14.pdf）
  -  **用于视频中动作识别的双流卷积网络**（2014），K.Simonyan等.  [[PDF]]（http://papers.nips.cc/paper/5353-two-stream-convolutional-networks-for-action-recognition-in-videos.pdf）
  -  **用于人类行为识别的3D卷积神经网络**（2013），S.Ji等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/icml2010_JiXYY10.pdf）

<!---[Key researchers]  [Oriol Vinyals](https://scholar.google.ca/citations?user=NkzyCvUAAAAJ), [Andrej Karpathy](https://scholar.google.ca/citations?user=l8WuQJgAAAAJ)-->

<!---[Key researchers]  [Alex Graves](https://scholar.google.ca/citations?user=DaFHynwAAAAJ)-->

### Natural Language Processing / RNNs
  -  **命名实体识别的神经架构**（2016），G.Lample等.  [[PDF]]（http://aclweb.org/anthology/N/N16/N16-1030.pdf）
  -  **探索语言建模的极限**（2016），R.Jozefowicz等.  [[PDF]]（http://arxiv.org/pdf/1602.02410）
  -  **阅读和理解教学机器**（2015），K.Hermann等.  [[PDF]]（http://papers.nips.cc/paper/5945-teaching-machines-to-read-and-comprehend.pdf）
  -  **基于注意力的神经机器翻译的有效方法**（2015），M.Luong等.  [[PDF]]（https://arxiv.org/pdf/1508.04025）
  -  **条件随机场作为递归神经网络**（2015），S.Zheng和S. Jayasumana.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Zheng_Conditional_Random_Fields_ICCV_2015_paper.pdf）
  -  **记忆网络**（2014），J.Weston等.  [[PDF]]（https://arxiv.org/pdf/1410.3916）
  -  **神经图灵机**（2014），A.Graves等.  [[PDF]]（https://arxiv.org/pdf/1410.5401）
  -  **联合学习校准和翻译的神经机器翻译**（2014），D.Bahdanau等.  [[PDF]]（http://arxiv.org/pdf/1409.0473）
  -  **用神经网络进行序列学习的序列**（2014），I.Sutskever等.  [[PDF]]（http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf）
  -  **使用RNN编码器 - 解码器进行统计机器翻译的学习短语表示**（2014），K.Cho等.  [[PDF]]（http://arxiv.org/pdf/1406.1078）
  -  **用于建模句子的卷积神经网络**（2014），N.Kalchbrenner等.  [[PDF]]（http://arxiv.org/pdf/1404.2188v1）
-  **用于句子分类的卷积神经网络**（2014），Y.Kim [[pdf]]（http://arxiv.org/pdf/1408.5882）
  -  **手套：单词表示的全局向量**（2014），J.Pennington等.  [[PDF]]（http://anthology.aclweb.org/D/D14/D14-1162.pdf）
-  **句子和文件的分布式陈述**（2014），Q.Le和T. Mikolov [[pdf]]（http://arxiv.org/pdf/1405.4053）
  -  **单词和短语的分布式表示及其组成**（2013），T.Mikolov等.  [[PDF]]（http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf）
  -  **对向量空间中单词表示的有效估计**（2013），T.Mikolov等.  [[PDF]]（http://arxiv.org/pdf/1301.3781）
  -  **在情感树库上的语义组合的递归深度模型**（2013），R.Socher等.  [[PDF]]（http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.383.1327&amp;rep=rep1&amp;type=pdf）
  -  **用递归神经网络生成序列**（2013），A.Graves.  [[PDF]]（https://arxiv.org/pdf/1308.0850）

<!---[Key researchers]  [Kyunghyun Cho](https://scholar.google.ca/citations?user=0RAmmIAAAAAJ), [Oriol Vinyals](https://scholar.google.ca/citations?user=NkzyCvUAAAAJ), [Richard Socher](https://scholar.google.ca/citations?hl=en&user=FaOcyfMAAAAJ), [Tomas Mikolov](https://scholar.google.ca/citations?user=oBu8kMMAAAAJ), [Christopher D. Manning](https://scholar.google.ca/citations?user=1zmDOdwAAAAJ), [Yoshua Bengio](https://scholar.google.ca/citations?user=kukA0LcAAAAJ)-->

### Speech / Other Domain
  -  **端到端基于注意力的大词汇量语音识别**（2016），D.Bahdanau等.  [[PDF]]（https://arxiv.org/pdf/1508.04395）
  -  **深度讲话2：英语和普通话的端到端语音识别**（2015），D.Amodei等.  [[PDF]]（https://arxiv.org/pdf/1512.02595）
-  **使用深度递归神经网络进行语音识别**（2013），A.Graves [[pdf]]（http://arxiv.org/pdf/1303.5778.pdf）
  -  **用于语音识别声学建模的深度神经网络：四个研究组的共同观点**（2012），G.Hinton等.  [[PDF]]（http://www.cs.toronto.edu/~asamir/papers/SPM_DNN_12.pdf）
  -  **用于大词汇量语音识别的依赖于上下文的预训练深度神经网络**（2012）G.Dahl等.  [[PDF]]（http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.337.7548&amp;rep=rep1&amp;type=pdf）
  -  **使用深度信念网络进行声学建模**（2012），A.Mohamed等.  [[PDF]]（http://www.cs.toronto.edu/~asamir/papers/speechDBN_jrnl.pdf）

<!---[Key researchers]  [Alex Graves](https://scholar.google.ca/citations?user=DaFHynwAAAAJ), [Geoffrey Hinton](https://scholar.google.ca/citations?user=JicYPdAAAAAJ), [Dong Yu](https://scholar.google.ca/citations?hl=en&user=tMY31_gAAAAJ)-->

### Reinforcement Learning / Robotics
  -  **深度视觉运动政策的端到端培训**（2016），S.Levine等.  [[PDF]]（http://www.jmlr.org/papers/volume17/15-522/source/15-522.pdf）
  -  **学习用于深度学习和大规模数据收集的机器人掌握的手眼协调**（2016），S.Levine等.  [[PDF]]（https://arxiv.org/pdf/1603.02199）
  -  **深度强化学习的异步方法**（2016），V.Mnih等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v48/mniha16.pdf）
  -  **使用双Q学习进行深度强化学习**（2016），H.Hasselt等.  [[pdf]]（https://arxiv.org/pdf/1509.06461.pdf）
  -  **掌握深度神经网络和树搜索的Go游戏**（2016），D.Silver等.  [[PDF]]（http://www.nature.com/nature/journal/v529/n7587/full/nature16961.html）
  -  **持续控制与深层强化学习**（2015），T.Lillicrap等.  [[PDF]]（https://arxiv.org/pdf/1509.02971）
  -  **通过深层强化学习进行人类控制**（2015），V.Mnih等.  [[PDF]]（http://www.davidqiu.com:8888/research/nature14236.pdf）
  -  **用于检测机器人抓握的深度学习**（2015），I.Lenz等.  [[PDF]]（http://www.cs.cornell.edu/~asaxena/papers/lenz_lee_saxena_deep_learning_grasping_ijrr2014.pdf）
  -  **使用深度强化学习来播放atari **（2013），V.Mnih等.  [[PDF]]（http://arxiv.org/pdf/1312.5602.pdf））

<!---[Key researchers]  [Sergey Levine](https://scholar.google.ca/citations?user=8R35rCwAAAAJ), [Volodymyr Mnih](https://scholar.google.ca/citations?hl=en&user=rLdfJ1gAAAAJ), [David Silver](https://scholar.google.ca/citations?user=-8DNE4UAAAAJ)-->

### More Papers from 2016
  -  **层标准化**（2016），J.Ba等.  [[PDF]]（https://arxiv.org/pdf/1607.06450v1.pdf）
  -  **学习通过梯度下降梯度下降学习**（2016），M.Andrychowicz等.  [[PDF]]（http://arxiv.org/pdf/1606.04474v1）
  -  **神经网络的域对抗训练**（2016），Y.Ganin等.  [[PDF]]（http://www.jmlr.org/papers/volume17/15-239/source/15-239.pdf）
  -  ** WaveNet：原始音频的生成模型**（2016），A.Oord等.  [[pdf]]（https://arxiv.org/pdf/1609.03499v2) [[web]]（https://deepmind.com/blog/wavenet-generative-model-raw-audio/）
  -  **彩色图像着色**（2016），R.Zhang等.  [[PDF]]（https://arxiv.org/pdf/1603.08511）
  -  **自然图像流形上的生成视觉操作**（2016），J.Zhu等.  [[PDF]]（https://arxiv.org/pdf/1609.03552）
  -  **纹理网络：纹理和程式化图像的前馈合成**（2016），D Ulyanov等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v48/ulyanov16.pdf）
  -  ** SSD：单发多箱探测器**（2016），W.Liu等.  [[PDF]]（https://arxiv.org/pdf/1512.02325）
  -  ** SqueezeNet：AlexNet级精度，参数减少50倍，模型尺寸&lt;1MB **（2016），F.Iandola等.  [[PDF]]（http://arxiv.org/pdf/1602.07360）
  -  ** Eie：压缩深度神经网络上的高效推理引擎**（2016），S.Han et al.  [[PDF]]（http://arxiv.org/pdf/1602.01528）
  -  **二值化神经网络：训练深度神经网络，其权重和激活约束为+ 1或-1 **（2016），M.Courbariaux等.  [[PDF]]（https://arxiv.org/pdf/1602.02830）
  -  **用于视觉和文本问答的动态记忆网络**（2016），C.Xiong等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v48/xiong16.pdf）
  -  **用于图像问答的堆叠注意网络**（2016），Z.Yang等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yang_Stacked_Attention_Networks_CVPR_2016_paper.pdf）
  -  **使用具有动态外部存储器的神经网络的混合计算**（2016），A.Graves等.  [[PDF]]（https://www.gwern.net/docs/2016-graves.pdf）
  -  ** Google的神经机器翻译系统：缩小人机翻译的差距**（2016），Y.Wu等.  [[PDF]]（https://arxiv.org/pdf/1609.08144）

* * *


### New papers
*新发表的论文（&lt;6个月）值得一读*
  -  MobileNets：用于移动视觉应用的高效卷积神经网络（2017），Andrew G. Howard等.  [[PDF]]（https://arxiv.org/pdf/1704.04861.pdf）
  - 卷积序列到序列学习（2017），Jonas Gehring等.  [[PDF]]（https://arxiv.org/pdf/1705.03122）
  - 基于知识的神经对话模型（2017），Marjan Ghazvininejad等.  [[PDF]]（https://arxiv.org/pdf/1702.01932）
  - 准确，大型Minibatch SGD：1小时（2017年）培训ImageNet，Priya Goyal等.  [[PDF]]（https://research.fb.com/wp-content/uploads/2017/06/imagenet1kin1h3.pdf）
  -  TACOTRON：迈向端到端语音合成（2017），Y.Wang等.  [[PDF]]（https://arxiv.org/pdf/1703.10135.pdf）
  - 深度照片风格转移（2017），F.Luan等.  [[PDF]]（http://arxiv.org/pdf/1703.07511v1.pdf）
  - 进化策略作为强化学习的可扩展替代方案（2017），T.Salimans等.  [[PDF]]（http://arxiv.org/pdf/1703.03864v1.pdf）
  -  Deformable Convolutional Networks（2017），J.Dai et al.  [[PDF]]（http://arxiv.org/pdf/1703.06211v2.pdf）
  -  Mask R-CNN（2017），K.He et al.  [[PDF]]（https://128.84.21.199/pdf/1703.06870）
  - 学习发现与生成对抗网络的跨域关系（2017），T.Kim等.  [[PDF]]（http://arxiv.org/pdf/1703.05192v1.pdf） 
- 深层语音：实时神经文本到语音转换（2017），S.Arik等，[[pdf]]（http://arxiv.org/pdf/1702.07825v2.pdf）
  -  PixelNet：像素的表示，像素和像素的表示（2017），A.Bansal等.  [[PDF]]（http://arxiv.org/pdf/1702.06506v1.pdf）
  - 批量重整化：为了减少批量标准化模型（2017年）中的小批量依赖性，S.Ioffe.  [[PDF]]（https://arxiv.org/abs/1702.03275）
  -  Wasserstein GAN（2017），M.Arjovsky等.  [[PDF]]（https://arxiv.org/pdf/1701.07875v1）
  - 理解深度学习需要重新思考泛化（2017），C.Zhang等.  [[PDF]]（https://arxiv.org/pdf/1611.03530）
  - 最小二乘生成对抗网络（2016），X.Mao等.  [[PDF]]（https://arxiv.org/abs/1611.04076v2）


### Old Papers
* 2012年之前发表的经典论文*
  - 无监督特征学习中的单层网络分析（2011），A.Coates等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/AISTATS2011_CoatesNL11.pdf）
  - 深度稀疏整流神经网络（2011），X.Glorot等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/AISTATS2011_GlorotBB11.pdf）
  - 自然语言处理（几乎）从零开始（2011年），R.Collobert等.  [[PDF]]（http://arxiv.org/pdf/1103.0398）
  - 基于递归神经网络的语言模型（2010），T.Mikolov等.  [[PDF]]（http://www.fit.vutbr.cz/research/groups/speech/servite/2010/rnnlm_mikolov.pdf）
  - 堆叠去噪自动编码器：使用局部去噪准则在深度网络中学习有用的表示（2010），P.Vincent等.  [[PDF]]（http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.297.3484&amp;rep=rep1&amp;type=pdf）
- 学习中级特征（2010），Y.Boureau [[pdf]]（http://ece.duke.edu/~lcarin/boureau-cvpr-10.pdf）
- 培训限制性boltzmann机器的实用指南（2010），G.Hinton [[pdf]]（http://www.csri.utoronto.ca/~hinton/absps/guideTR.pdf）
- 了解深度前馈神经网络训练的难度（2010），X.Glorot和Y. Bengio [[pdf]]（http://machinelearning.wustl.edu/mlpapers/paper_files/AISTATS2010_GlorotB10.pdf）
  - 为什么无人监督的预训练有助于深度学习（2010），D.Erhan等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/AISTATS2010_ErhanCBV10.pdf）
  - 为AI（2009），Y.Bengio学习深层架构.  [[PDF]]（http://sanghv.com/download/soft/machine%20learning,%20artificial%20intelligence,%20mathematics%20ebooks/ML/learning%20deep%20architectures%20for%20AI%20（2009）.PDF ）
  - 用于分级表示的可扩展无监督学习的卷积深度置信网络（2009），H.Lee等.  [[PDF]]（http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.149.802&amp;rep=rep1&amp;type=pdf）
  - 深入网络的贪婪分层训练（2007），Y.Bengio等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/NIPS2006_739.pdf）
  - 使用神经网络减少数据的维数，G.Hinton和R. Salakhutdinov.  [[PDF]]（http://homes.mpimf-heidelberg.mpg.de/~mhelmsta/pdf/2006%20Hinton%20Salakhudtkinov%20Science.pdf）
  - 深度信念网的快速学习算法（2006），G.Hinton等.  [[PDF]]（http://nuyoo.utm.mx/~jjf/rna/A8%20A%20fast%20learning%20algorithm%20for%20deep%20belief%20nets.pdf）
  - 基于梯度的学习应用于文档识别（1998），Y.LeCun等.  [[PDF]]（http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf）
  - 长期短期记忆（1997年），S.Hochreiter和J. Schmidhuber.  [[PDF]]（http://www.mitpressjournals.org/doi/pdfplus/10.1162/neco.1997.9.8.1735）


### HW / SW / Dataset
  -  SQUAD：100,000多个机器理解文本问题（2016），Rajpurkar等.  [[PDF]]（https://arxiv.org/pdf/1606.05250.pdf）
  -  OpenAI健身房（2016年），G.Brockman等.  [[PDF]]（https://arxiv.org/pdf/1606.01540）
  -  TensorFlow：异构分布式系统上的大规模机器学习（2016），M.Abadi等.  [[PDF]]（http://arxiv.org/pdf/1603.04467）
-  Theano：用于快速计算数学表达式的Python框架，R.Al-Rfou等.
  -  Torch7：类似matlab的机器学习环境，R.Collobert等.  [[PDF]]（https://ronan.collobert.com/pub/matos/2011_torch7_nipsw.pdf）
-  MatConvNet：matlab的卷积神经网络（2015），A.Vedaldi和K. Lenc [[pdf]]（http://arxiv.org/pdf/1412.4564）
  -  Imagenet大规模视觉识别挑战（2015），O.Russakovsky等.  [[PDF]]（http://arxiv.org/pdf/1409.0575）
  -  Caffe：用于快速特征嵌入的卷积体系结构（2014），Y.Jia等.  [[PDF]]（http://arxiv.org/pdf/1408.5093）


### Book / Survey / Review
  - 关于深度学习的起源（2017），H.Wang和Bhiksha Raj.  [[PDF]]（https://arxiv.org/pdf/1702.07800）
- 深度强化学习：概述（2017），Y.Li，[[pdf]]（http://arxiv.org/pdf/1701.07274v2.pdf）
  - 神经机器翻译和序列到序列模型（2017）：教程，G.Neubig.  [[PDF]]（http://arxiv.org/pdf/1703.01619v1.pdf）
  - 神经网络和深度学习（Book，2017年1月），Michael Nielsen.  [[HTML]]（http://neuralnetworksanddeeplearning.com/index.html）
  - 深度学习（Book，2016），Goodfellow等.  [[HTML]]（http://www.deeplearningbook.org/）
  -  LSTM：搜索空间奥德赛（2016），K.格雷夫等人.  [[PDF]]（https://arxiv.org/pdf/1503.04069.pdf?utm_content=buffereddc5&amp;utm_medium=social&amp;utm_source=plus.google.com&amp;utm_campaign=buffer）
  - 变分自动编码器教程（2016），C.Doersch.  [[PDF]]（https://arxiv.org/pdf/1606.05908）
- 深度学习（2015），Y.LeCun，Y.Bengio和G. Hinton [[pdf]]（https://www.cs.toronto.edu/~hinton/absps/NatureDeepReview.pdf）
- Deep learning in neural networks: An overview (2015), J. Schmidhuber [[pdf]](http://arxiv.org/pdf/1404.7828)
  - 代表性学习：审查和新观点（2013年），Y.Bengio等.  [[PDF]]（http://arxiv.org/pdf/1206.5538）

### Video Lectures / Tutorials / Blogs

*(Lectures)*
-  CS231n，用于视觉识别的卷积神经网络，斯坦福大学[[网页]]（http://cs231n.stanford.edu/）
- CS224d, Deep Learning for Natural Language Processing, Stanford University [[web]](http://cs224d.stanford.edu/)
-  Oxford Deep NLP 2017，自然语言处理深度学习，牛津大学[[网页]]（https://github.com/oxford-cs-deepnlp-2017/lectures）

*(Tutorials)*
-  NIPS 2016教程，长滩[[网页]]（https://nips.cc/Conferences/2016/Schedule?type=Tutorial）
- ICML 2016 Tutorials, New York City [[web]](http://techtalks.tv/icml/2016/tutorials/)
-  ICLR 2016视频，圣胡安[[网页]]（http://videolectures.net/iclr2016_san_juan/）
- 深度学习暑期学校2016，蒙特利尔[[网页]]（http://videolectures.net/deeplearning2016_montreal/）
-  2016年湾区深度学习学校，斯坦福[[网页]]（https://www.bayareadlschool.org/）

*(Blogs)*
-  OpenAI [[网页]]（https://www.openai.com/）
- 蒸馏[[网页]]（http://distill.pub/）
-  Andrej Karpathy博客[[网页]]（http://karpathy.github.io/）
-  Colah的博客[[网页]]（http://colah.github.io/）
-  WildML [[Web]]（http://www.wildml.com/）
-  FastML [[web]]（http://www.fastml.com/）
-  TheMorningPaper [[web]]（https://blog.acolyer.org）

### Appendix: More than Top 100
*(2016)*
  - 没有用于神经机器翻译的明确分割的字符级解码器（2016），J.Chung等.  [[PDF]]（https://arxiv.org/pdf/1603.06147）
  - 皮肤病学家级皮肤癌分类与深度神经网络（2017），A.Esteva等.  [[HTML]]（http://www.nature.com/nature/journal/v542/n7639/full/nature21056.html）
  - 使用多重多实例学习的弱监督对象定位（2017），R.Gokberk等.  [[PDF]]（https://arxiv.org/pdf/1503.00949）
  - 使用深度神经网络进行脑肿瘤分割（2017），M.Havaei等.  [[PDF]]（https://arxiv.org/pdf/1505.03540）
  - 教授强迫：一种新的训练递归网络的算法（2016），A.Lamb等.  [[PDF]]（https://arxiv.org/pdf/1610.09038）
  - 对抗性学习推理（2016），V.Dumoulin等.  [网络]]（https://ishmaelbelghazi.github.io/ALI/）[[PDF]]（https://arxiv.org/pdf/1606.00704v1）
- 了解卷积神经网络（2016），J.Koushik [[pdf]]（https://arxiv.org/pdf/1605.09081v1）
  - 将人类排除在外：关于贝叶斯优化的综述（2016），B.Shahriari等.  [[PDF]]（https://www.cs.ox.ac.uk/people/nando.defreitas/publications/BayesOptLoop.pdf）
- 递归神经网络的自适应计算时间（2016），A.Graves [[pdf]]（http://arxiv.org/pdf/1603.08983）
  - 密集连接的卷积网络（2016），G.Huang等.  [[PDF]]（https://arxiv.org/pdf/1608.06993v1）
- 用于精确物体检测和分割的基于区域的卷积网络（2016），R.Girshick等. 
  - 基于模型加速的连续深度q学习（2016），S.Gu等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v48/gu16.pdf）
  - 彻底检查cnn /每日邮件阅读理解任务（2016年），D.陈等人.  [[PDF]]（https://arxiv.org/pdf/1606.02858）
  - 使用混合词 - 字符模型实现开放式词汇神经机器翻译，M.Luong和C. Manning.  [[PDF]]（https://arxiv.org/pdf/1604.00788）
  - 用于自然语言处理的非常深的卷积网络（2016），A.Conneau等.  [[PDF]]（https://arxiv.org/pdf/1606.01781）
  - 一系列有效文本分类技巧（2016），A.Joulin等.  [[PDF]]（https://arxiv.org/pdf/1607.01759）
  - 用于语义分割的深层结构模型的高效分段训练（2016），G.Lin等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Lin_Efficient_Piecewise_Training_CVPR_2016_paper.pdf）
  - 学习构建用于问答的神经网络（2016），J.Andreas等.  [[PDF]]（https://arxiv.org/pdf/1601.01705）
  - 实时风格转移和超分辨率的感知损失（2016），J.Johnson等.  [[PDF]]（https://arxiv.org/pdf/1603.08155）
  - 使用卷积神经网络阅读野外文本（2016），M.Jaderberg等.  [[PDF]]（http://arxiv.org/pdf/1412.1842）
  - 什么是有效的检测建议？  （2016），J.Hosang等.  [[PDF]]（https://arxiv.org/pdf/1502.05082）
  - 内外网：使用跳过池和循环神经网络检测上下文中的对象（2016），S.Bell等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Bell_Inside-Outside_Net_Detecting_CVPR_2016_paper.pdf）.
  - 通过多任务网络级联的实例感知语义分段（2016），J.Dai等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Dai_Instance-Aware_Semantic_Segmentation_CVPR_2016_paper.pdf）
  - 使用pixelcnn解码器生成条件图像（2016），A.van den Oord等.  [[PDF]]（http://papers.nips.cc/paper/6527-tree-structured-reinforcement-learning-for-sequential-object-localization.pdf）
- 具有随机深度的深度网络（2016），G.Huang等，[[pdf]]（https://arxiv.org/pdf/1603.09382）
  - 随机梯度Langevin动力学的一致性和波动（2016），Yee Whye Teh等.  [[PDF]]（http://www.jmlr.org/papers/volume17/teh16a/teh16a.pdf）

*(2015)*
  - 询问你的神经元：一种基于神经的方法来回答关于图像的问题（2015），M.Malinowski等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Malinowski_Ask_Your_Neurons_ICCV_2015_paper.pdf）
  - 探索图像问答的模型和数据（2015），M.Ren等.  [[PDF]]（http://papers.nips.cc/paper/5640-stochastic-variational-inference-for-hidden-markov-models.pdf）
  - 你在和机器说话吗？  用于多语言图像问题的数据集和方法（2015），H.Gao等.  [[PDF]]（http://papers.nips.cc/paper/5641-are-you-talking-to-a-machine-dataset-and-methods-for-multilingual-image-question.pdf）
  -  Mind&#39;s eye：图像标题生成（2015）的反复视觉表现，X.Chen和C. Zitnick.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Chen_Minds_Eye_A_2015_CVPR_paper.pdf）
  - 从字幕到视觉概念和背面（2015），H.Fang等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Fang_From_Captions_to_2015_CVPR_paper.pdf）.
  - 迈向AI完整的问题回答：一系列必备玩具任务（2015年），J.Weston等.  [[PDF]]（http://arxiv.org/pdf/1502.05698）
  - 问我任何事情：用于自然语言处理的动态记忆网络（2015），A.Kumar等人.  [[PDF]]（http://arxiv.org/pdf/1506.07285）
  - 使用LSTM的无监督学习视频表示（2015），N.Srivastava等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v37/srivastava15.pdf）
  - 深度压缩：使用修剪，训练量化和霍夫曼编码压缩深度神经网络（2015），S.Han等.  [[PDF]]（https://arxiv.org/pdf/1510.00149）
  - 改进了树状结构长短期记忆网络的语义表示（2015），K.Tai等人.  [[PDF]]（https://arxiv.org/pdf/1503.00075）
  - 字符感知神经语言模型（2015），Y.Kim等.  [[PDF]]（https://arxiv.org/pdf/1508.06615）
  - 语法作为外语（2015），O.Vinyals等.  [[PDF]]（http://papers.nips.cc/paper/5635-grammar-as-a-foreign-language.pdf）
  - 信托区政策优化（2015），J.Schulman等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v37/schulman15.pdf）
- 超短片段：用于视频分类的深层网络（2015）[[pdf]]（http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Ng_Beyond_Short_Snippets_2015_CVPR_paper.pdf）
  - 学习用于语义分割的反卷积网络（2015），H.Noh等.  [[PDF]]（https://arxiv.org/pdf/1505.04366v1）
  - 利用三维卷积网络学习时空特征（2015），D.Tran等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Tran_Learning_Spatiotemporal_Features_ICCV_2015_paper.pdf）
  - 通过深度可视化理解神经网络（2015），J.Yosinski等.  [[PDF]]（https://arxiv.org/pdf/1506.06579）
  - 对经常性网络架构的实证探索（2015），R.Jozefowicz等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v37/jozefowicz15.pdf）
  - 使用对侧网络的拉普拉斯金字塔的深层生成图像模型（2015），E.Denton等.  [[PDF]]（http://papers.nips.cc/paper/5773-deep-generative-image-models-using-a-laplacian-pyramid-of-adversarial-networks.pdf）
  - 门控反馈回归神经网络（2015），J.Chung等.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v37/chung15.pdf）
  - 通过指数线性单位（ELUS）快速准确地进行深度网络学习（2015），D.Clevert等.  [[PDF]]（https://arxiv.org/pdf/1511.07289.pdf%5Cnhttp://arxiv.org/abs/1511.07289%5Cnhttp://arxiv.org/abs/1511.07289）
  - 指针网络（2015），O.Vinyals等.  [[PDF]]（http://papers.nips.cc/paper/5866-pointer-networks.pdf）
  - 可视化和理解循环网络（2015），A.Karpathy等.  [[PDF]]（https://arxiv.org/pdf/1506.02078）
  - 基于注意力的语音识别模型（2015），J.Chorowski等.  [[PDF]]（http://papers.nips.cc/paper/5847-attention-based-models-for-speech-recognition.pdf）
  - 端到端存储器网络（2015），S.Sukbaatar等.  [[PDF]]（http://papers.nips.cc/paper/5846-end-to-end-memory-networks.pdf）
  - 利用时间结构描述视频（2015），L.Yao等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Yao_Describing_Videos_by_ICCV_2015_paper.pdf）
  - 神经对话模型（2015），O.Vinyals和Q. Le.  [[PDF]]（https://arxiv.org/pdf/1506.05869.pdf）
  - 通过从嵌入词中学到的经验改善分布相似性，O.Levy等.  [[pdf]]（https://www.transacl.org/ojs/index.php/tacl/article/download/570/124）
  - 基于过渡的依赖性解析与堆栈长短期记忆（2015），C.Dyer等.  [[PDF]]（http://aclweb.org/anthology/P/P15/P15-1033.pdf）
  - 通过使用LSTM建模字符而不是单词来改进基于过渡的解析（2015），M.Ballesteros等.  [[PDF]]（http://aclweb.org/anthology/D/D15/D15-1041.pdf）
  - 查找形式函数：开放词汇表单表示的组合字符模型（2015），W.Ling等.  [[PDF]]（http://aclweb.org/anthology/D/D15/D15-1176.pdf）


*(~2014)*
-  DeepPose：通过深度神经网络进行人体姿态估计（2014），A.Toshev和C. Szegedy [[pdf]]（http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Toshev_DeepPose_Human_Pose_2014_CVPR_paper.pdf）
- 学习用于图像超分辨率的深度卷积网络（2014年，C.Dong等人[[pdf]]（https://www.researchgate.net/profile/Chen_Change_Loy/publication/264552416_Lecture_Notes_in_Computer_Science/links/53e583e50cf25d674e9c280e.pdf）
  - 视觉注意的循环模型（2014），V.Mnih等.  [[PDF]]（http://arxiv.org/pdf/1406.6247.pdf）
- Empirical evaluation of gated recurrent neural networks on sequence modeling (2014), J. Chung et al. [[pdf]](https://arxiv.org/pdf/1412.3555)
  - 解决神经机器翻译中罕见的单词问题（2014），M.Luong等.  [[PDF]]（https://arxiv.org/pdf/1410.8206）
  - 关于神经机器翻译的特性：编码器 - 解码器方法（2014），K.Cho等.  人.
  - 递归神经网络正则化（2014），W.Zaremba等.  [[PDF]]（http://arxiv.org/pdf/1409.2329）
  - 神经网络的迷人属性（2014），C.Szegedy等.  [[PDF]]（https://arxiv.org/pdf/1312.6199.pdf）
  - 采用递归神经网络进行端到端语音识别（2014），A.Graves和N. Jaitly.  [[PDF]]（http://www.jmlr.org/proceedings/papers/v32/graves14.pdf）
  - 使用深度神经网络的可扩展对象检测（2014），D.Erhan等.  [[PDF]]（http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Erhan_Scalable_Object_Detection_2014_CVPR_paper.pdf）
  - 关于初始化和动力学在深度学习中的重要性（2013），I.Sutskever等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/icml2013_sutskever13.pdf）
  - 使用dropconnect定量神经网络（2013），L.Wan等.  [[PDF]]（http://machinelearning.wustl.edu/mlpapers/paper_files/icml2013_wan13.pdf）
  - 学习场景标签的层次特征（2013），C.Farabet等.  [[PDF]]（https://hal-enpc.archives-ouvertes.fr/docs/00/74/20/77/PDF/farabet-pami-13.pdf）
- Linguistic Regularities in Continuous Space Word Representations (2013), T. Mikolov et al. [[pdf]](http://www.aclweb.org/anthology/N13-1#page=784)
  - 大规模分布式深度网络（2012），J.Dean等.  [[PDF]]（http://papers.nips.cc/paper/4687-large-scale-distributed-deep-networks.pdf）
- A Fast and Accurate Dependency Parser using Neural Networks. Chen and Manning. [[pdf]](http://cs.stanford.edu/people/danqi/papers/emnlp2014.pdf)



## Acknowledgement

 感谢您的所有贡献.  请务必阅读 [contributing guide](https://github.com/terryum/awesome-deep-learning-papers/blob/master/Contributing.md) 在你提出拉动请求之前.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Terry T. Um](https://www.facebook.com/terryum.io/) 已放弃对此作品的所有版权及相关或相邻权利.
