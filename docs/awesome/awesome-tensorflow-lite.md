<div class="github-widget" data-repo="margaretmz/awesome-tensorflow-lite"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<p align="center">
    <img src="https://raw.githubusercontent.com/margaretmz/awesome-tensorflow-lite/master/images/awesome-tflite.png" alt="awesome tflite" width="500">
</p>

## Awesome TensorFlow Lite [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![Twitter](https://img.shields.io/badge/Twitter-%40margaretmz-blue)](https://twitter.com/margaretmz)
[TensorFlow Lite](https://www.tensorflow.org/lite) 是一组帮助转换和优化 TensorFlow 模型以在移动和边缘设备上运行的工具. 它目前在超过 40 亿台设备上运行！ 使用 TensorFlow 2.x，您可以使用 tf.Keras 训练模型，轻松将模型转换为 .tflite 并进行部署； 或者您可以从模型动物园下载预训练的 TensorFlow Lite 模型.

这是一个很棒的 TensorFlow Lite 模型列表，其中包含示例应用程序、有用的工具和学习资源 -
* 展示社区使用 TensorFlow Lite 构建的内容
* 将所有样品并排放置以方便参考
* 分享知识和学习资源

如果您想贡献并遵循指南，请提交 PR [here](https://github.com/margaretmz/awesome-tensorflow-lite/blob/master/CONTRIBUTING.md).


## What is new
以下是 TensorFlow Lite 的新功能和工具： <img src="https://raw.githubusercontent.com/margaretmz/awesome-tensorflow-lite/master/images/icons/new.png" width='32' height='32'/>
* [Announcement of the new converter](https://groups.google.com/a/tensorflow.org/d/msg/tflite/Z_h7706dt8Q/sNrjPj4yGgAJ) - [MLIR](https://medium.com/tensorflow/mlir-a-new-intermediate-representation-and-compiler-framework-beba999ed18d)基于并支持新类别模型的转换，如 Mask R-CNN 和 Mobile BERT 等，支持功能控制流和更好的转换过程中的错误处理. 默认情况下在每晚构建中启用\.
* [Android Support Library](https://github.com/tensorflow/tflite-support/tree/master/tensorflow_lite_support/java) - 使移动开发更容易（[Android](https://github.com/tensorflow/examples/blob/master/lite/examples/image_classification/android/EXPLORE_THE_CODE.md) 示例代码）.
* [Model Maker](https://www.tensorflow.org/lite/guide/model_maker) - 创建您的自定义 [image & text](https://github.com/tensorflow/examples/tree/master/tensorflow_examples/lite/model_maker) 只需几行代码即可轻松进行分类模型. 请参阅下面的图标分类器以获取社区教程.
* [On-device training](https://blog.tensorflow.org/2019/12/example-on-device-model-personalization.html)  - 终于来了！ 目前仅限于图像分类的迁移学习，但这是一个很好的开始. 看官方 [Android](https://github.com/tensorflow/examples/blob/master/lite/examples/model_personalization/README.md) 示例代码和来自社区的另一个（[Blog](https://aqibsaeed.github.io/on-device-activity-recognition) | [Android](https://github.com/aqibsaeed/on-device-activity-recognition)).
* [Hexagon delegate](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/lite/g3doc/performance/hexagon_delegate.md)  - 如何使用 Hexagon Delegate 加速移动和边缘设备上的模型推理. 另见博文  [Accelerating TensorFlow Lite on Qualcomm Hexagon DSPs](https://blog.tensorflow.org/2019/12/accelerating-tensorflow-lite-on-qualcomm.html).
* [Model Metadata](https://www.tensorflow.org/lite/convert/metadata) - 提供模型描述的标准，这也使 [Code Gen and Android Studio ML Model Binding](https://www.tensorflow.org/lite/inference_with_metadata/codegen).

## Models with samples
以下是带有应用/设备实现和参考的 TensorFlow Lite 模型.
注意：包含来自 MediaPipe 的预训练 TensorFlow Lite 模型，您可以使用或不使用 MediaPipe 来实现这些模型.

### Computer vision

 | 任务 | 型号 | 应用\| 参考 | 来源 |
| ------------------------------- |-------------------------------------------------------------------------------------------------------------------------------------------------------------------| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------       | -------------------|
 | 分类 |  MobileNetV1 ([download](https://storage.googleapis.com/download.tensorflow.org/models/tflite/mobilenet_v1_1.0_224_quant_and_labels.zip))                          | [Android](https://github.com/tensorflow/examples/tree/master/lite/examples/image_classification/android) \| [iOS](https://github.com/tensorflow/examples/tree/master/lite/examples/image_classification/ios) \| [Raspberry Pi](https://github.com/tensorflow/examples/tree/master/lite/examples/image_classification/raspberry_pi) \| [Overview](https://www.tensorflow.org/lite/models/image_classification/overview) | tensorflow.org     |
 | 分类 |  MobileNetV2 | 在 Android 上识别花 [Codelab](https://codelabs.developers.google.com/codelabs/recognize-flowers-with-tensorflow-on-android/#0) \| [Android](https://github.com/tensorflow/examples/tree/master/lite/codelabs/flower_classification/android)                                                                                                                                                                    |  TensorFlow 团队 |
 | 分类 |  MobileNetV2 | 皮肤病变检测 [Android](https://github.com/AakashKumarNain/skin_cancer_detection/tree/master/demo)                                                                                                                                                                                                                                                                                                              | 社区 |
 | 分类 |  MobileNetV2 | 美国手语检测 [Android](https://github.com/sayannath/American-Sign-Language-Detection)                                                                                                                                                                                                                                                                                                              | 社区 |
 | 分类 |  EfficientNet-Lite0 ([download](https://github.com/margaretmz/icon-classifier/blob/master/ml-code/icons-50.tflite) ) | 图标分类器 [Colab & Android](https://github.com/margaretmz/icon-classifier) \| [tutorial 1](https://medium.com/swlh/icon-classifier-with-tflite-model-maker-9263c0021f72) \| [tutorial 2](https://medium.com/@margaretmz/icon-classifier-android-app-1fc0b727f761)                                                                                                                                                 | 社区 |
 | 物体检测 | 量化 COCO SSD MobileNet v1 ([download](https://storage.googleapis.com/download.tensorflow.org/models/tflite/coco_ssd_mobilenet_v1_1.0_quant_2018_06_29.zip)) | [Android](https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android) \| [iOS](https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/ios) \| [Overview](https://www.tensorflow.org/lite/models/object_detection/overview#starter_model)                                                                                                                     | tensorflow.org     |
 | 物体检测 | 优洛 | [Flutter](https://blog.francium.tech/real-time-object-detection-on-mobile-with-flutter-tensorflow-lite-and-yolo-android-part-a0042c9b62c6) \| [Paper](https://arxiv.org/abs/1506.02640)                                                                                                                                                                                                                                 | 社区 |
 | 物体检测 |  MobileNetV2 固态硬盘（[download](https://github.com/google/mediapipe/tree/master/mediapipe/models/ssdlite_object_detection.tflite))                                    | [Reference](https://github.com/google/mediapipe/blob/master/mediapipe/models/object_detection_saved_model/README.md)                                                                                                                                                                                                                                                                                                    | 媒体管道 |
 | 物体检测 | 移动数据 ([Paper](https://arxiv.org/abs/2004.14525))                                    | [Blog post (includes the TFLite conversion process)](https://sayak.dev/mobiledet-optimization/)                                                                                                                                                                                                                                                                                                    |  MobileDet 来自威斯康星大学麦迪逊分校和谷歌，博客文章来自社区 |
 | 车牌检测 | 固态硬盘移动网络 [(download)](https://github.com/ariG23498/Flutter-License/blob/master/assets/detect.tflite)                                                         | [Flutter](https://github.com/ariG23498/Flutter-License)                                                                                                                                                                                                                                                                                                                                                                 | 社区 |
 | 人脸检测 | 烈焰人脸 ([download](https://github.com/google/mediapipe/tree/master/mediapipe/models/face_detection_front.tflite))                                              | [Paper](https://sites.google.com/corp/view/perception-cv4arvr/blazeface)                                                                                                                                                                                                                                                                                                                                                | 媒体管道 |
 | 人脸认证 | [FaceNet](https://arxiv.org/pdf/1503.03832.pdf)                                            | [Flutter](https://github.com/sayannath/Face-Authentication-App)                                                                                                                                                                                                                                                                                                                                                | 社区 |
 | 手部检测和跟踪 | 手掌检测和手部地标（[download](https://github.com/google/mediapipe/tree/master/mediapipe/models#hand-detection-and-tracking))                        | [Blog post](https://mediapipe.page.link/handgoogleaiblog) \| [Model card](https://mediapipe.page.link/handmc) \|  [Android](https://github.com/supremetech/mediapipe-demo-hand-detection)                                                                                                                                                                                                                                                                                                          | 媒体管道和社区 |
 | 姿态估计 | 波塞内 ([download](https://storage.googleapis.com/download.tensorflow.org/models/tflite/posenet_mobilenet_v1_100_257x257_multi_kpt_stripped.tflite))             | [Android](https://github.com/tensorflow/examples/tree/master/lite/examples/posenet/android) \| [iOS](https://github.com/tensorflow/examples/tree/master/lite/examples/posenet/ios) \| [Overview](https://www.tensorflow.org/lite/models/pose_estimation/overview)                                                                                                                                                      | tensorflow.org     |
 | 细分 | 深实验室 V3 ([download](https://storage.googleapis.com/download.tensorflow.org/models/tflite/gpu/deeplabv3_257_mv_gpu.tflite))                                     | [Android & iOS](https://github.com/tensorflow/examples/tree/master/lite/examples/image_segmentation/) \| [Overview](https://www.tensorflow.org/lite/models/segmentation/overview)  \| 扑 [Image](https://github.com/kshitizrimal/Flutter-TFLite-Image-Segmentation) \| [Realtime](https://github.com/kshitizrimal/tflite-realtime-flutter) \| [Paper](https://arxiv.org/abs/1706.05587)                             |  tf.org 和社区 |
 | 细分 | 不同的变种 [DeepLab V3 models](https://github.com/tensorflow/models/blob/master/research/deeplab/g3doc/model_zoo.md)                                    | 型号 [TF Hub](https://tfhub.dev/s?module-type=image-segmentation&publisher=sayakpaul) 使用 Colab 笔记本 | 社区 |
 | 头发分割| [Download](https://github.com/google/mediapipe/tree/master/mediapipe/models/hair_segmentation.tflite)                                                             | [Paper](https://sites.google.com/corp/view/perception-cv4arvr/hair-segmentation)                                                                                                                                                                                                                                                                                                                                        | 媒体管道 |
 | 风格转移 | [Arbitrary image stylization](https://github.com/tensorflow/magenta/tree/master/magenta/models/arbitrary_image_stylization)                                       | [Overview](https://www.tensorflow.org/lite/models/style_transfer/overview) \| [Android](https://github.com/tensorflow/examples/tree/master/lite/examples/style_transfer/android) \| [Flutter](https://github.com/PuzzleLeaf/flutter_tflite_style_transfer)                                                                                                                                                              |  tf.org 和社区 |
 | 风格转移 |  .tflite 中质量更好的风格转移模型 | 型号 [TF Hub](https://tfhub.dev/sayakpaul/lite-model/arbitrary-image-stylization-inceptionv3/dr/predict/1) 使用 Colab 笔记本 | 社区 |
 | 鹅 | [U-GAT-IT](https://github.com/taki0112/UGATIT) (Selfie2Anime) | [Project repo](https://github.com/margaretmz/selfie2anime-with-tflite) \| [Android](https://github.com/margaretmz/selfie2anime-with-tflite/tree/master/android) \| [Tutorial](https://medium.com/google-developer-experts/selfie2anime-with-tflite-part-1-overview-f97500800ffe)                                                                                                                                        | 社区 |
 | 鹅 | [White-box CartoonGAN](https://github.com/SystemErrorWang/White-box-Cartoonization) ([download](https://tfhub.dev/sayakpaul/lite-model/cartoongan/dr/1))          | [Project repo](https://github.com/margaretmz/Cartoonizer-with-TFLite) \| [Android](https://github.com/margaretmz/Cartoonizer-with-TFLite/tree/master/android) \| [Tutorial](https://blog.tensorflow.org/2020/09/how-to-create-cartoonizer-with-tf-lite.html)                                                                                                                                                            | 社区 |
 | 视频风格转移 | 下载：<br> [Dynamic range models](https://tfhub.dev/sayakpaul/lite-model/arbitrary-image-stylization-inceptionv3-dynamic-shapes/dr/transfer/1))               | [Android](https://github.com/farmaker47/video_style_transfer) \| [Tutorial](https://medium.com/@farmaker47/android-implementation-of-video-style-transfer-with-tensorflow-lite-models-9338a6d2a3ea)                                                                                                                                                                                                                     | 社区 |
 | 分割和风格转移 |  DeepLabV3 和风格迁移 [models](https://github.com/margaretmz/segmentation-style-transfer/tree/master/ml)                                                     | [Project repo](https://github.com/margaretmz/segmentation-style-transfer)  \| [Android](https://github.com/margaretmz/segmentation-style-transfer/tree/master/android) \| [Tutorial](https://medium.com/google-developer-experts/image-background-stylizer-part-1-project-intro-d68c4547e7e3)                                                                                                                           | 社区 |
 | 低光图像增强| [Models on TF Hub](https://tfhub.dev/sayakpaul/mirnet-fixed/1)                                                     | [Project repo](https://github.com/sayakpaul/MIRNet-TFLite)  \| [Original Paper](https://arxiv.org/pdf/2003.06792v2.pdf) \| [Flutter](https://github.com/sayannath/MIRNet-Flutter) |  | 社区 |
 | 文本检测 | 工艺文本检测器（[Paper](https://arxiv.org/pdf/1904.01941))                          |[Download](https://github.com/tulasiram58827/craft_tflite/blob/main/models/craft_float_800.tflite?raw=true) \| [Project Repository](https://github.com/tulasiram58827/craft_tflite/)  \| [Blog1-Conversion to TFLite](https://tulasi.dev/craft-in-tflite) \| [Blog2-EAST vs CRAFT](https://sayak.dev/optimizing-text-detectors/) \| [Models on TF Hub](https://tfhub.dev/tulasiram58827/lite-model/craft-text-detector/dr/1)    \| 安卓（即将推出）| 社区 |
 | 文本检测 |  EAST 文本检测器（[Paper](https://arxiv.org/abs/1704.03155))                          |[Models on TF Hub](https://tfhub.dev/sayakpaul/lite-model/east-text-detector/dr/1) \| [Conversion and Inference Notebook](https://colab.research.google.com/github/sayakpaul/Adventures-in-TensorFlow-Lite/blob/master/EAST_TFLite.ipynb)   | 社区 |
 | 图像外推| [Models on TF Hub](https://tfhub.dev/sayakpaul/lite-model/boundless-quarter/dr/1)                                                     | [Colab Notebook](https://colab.research.google.com/github/sayakpaul/Adventures-in-TensorFlow-Lite/blob/master/Boundless_TFLite.ipynb)  \| [Original Paper](https://arxiv.org/pdf/2003.06792v2.pdf)                                                                                                                            | 社区 |
 | 文字识别 |[Models on TF Hub](https://tfhub.dev/tulasiram58827/lite-model/keras-ocr/dr/2)     | [Project Repository](https://github.com/tulasiram58827/ocr_tflite)                                                                    | 社区



### Text
 | 任务 | 型号 | 示例应用 | 来源 |
| ------------------- |---------------------------------------------------------------------------------------------------------------------------------| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
 | 问答 | 蒸馏器 | [Android](https://github.com/huggingface/tflite-android-transformers/blob/master/bert)                                                                                                                                                             | 拥抱脸|
 | 文本生成 |  GPT-2 / DistilGPT2 | [Android](https://github.com/huggingface/tflite-android-transformers/blob/master/gpt2)                                                                                                                                                             | 拥抱脸|
 | 文本分类 | [Download](https://storage.googleapis.com/download.tensorflow.org/models/tflite/text_classification/text_classification.tflite) | [Android](https://github.com/tensorflow/examples/tree/master/lite/examples/text_classification/android) \|[iOS](https://github.com/khurram18/TextClassafication) \| [Flutter](https://github.com/am15h/tflite_flutter_plugin/tree/master/example)  |  tf.org 和社区 |

### Speech
 | 任务 | 型号 | 应用\| 参考 | 来源 |
| ------------------ |------------------------------------| ------------------------------------------------------------------------------------- | ------------ |
 | 语音识别 | 深度演讲 | [Reference](https://github.com/mozilla/DeepSpeech/tree/master/native_client/java)      |  Mozilla |
 | 语音合成 |  Tacotron-2、FastSpeech2、MB-Melgan | [Android](https://github.com/TensorSpeech/TensorflowTTS/tree/master/examples/android)  |  TensorSpeech |
 | 语音合成(TTS) |  Tacotron2、FastSpeech2、MelGAN、MB-MelGAN、HiFi-GAN、Parallel WaveGAN | [Inference Notebook](https://github.com/tulasiram58827/TTS_TFLite/blob/main/End_to_End_TTS.ipynb)      \| [Project Repository](https://github.com/tulasiram58827/TTS_TFLite/)   | 社区 |

### Recommendation
 | 任务 | 型号 | 应用\| 参考 | 来源 |
| ------------------ |------------------------------------| ------------------------------------------------------------------------------------- | ------------ |
 | 设备推荐 | [Dual-Encoder](https://github.com/tensorflow/examples/tree/master/lite/examples/recommendation/ml)                 | [Android](https://github.com/tensorflow/examples/tree/master/lite/examples/recommendation/android) \| [iOS](https://github.com/zhuzilin/on-device_recommendation_tflite) \| [Reference](https://blog.tensorflow.org/2020/09/introduction-to-tflite-on-device-recommendation.html)      |  tf.org 和社区 |

### Game
 | 任务 | 型号 | 应用\| 参考 | 来源 |
| ------------------ |------------------------------------| ------------------------------------------------------------------------------------- | ------------ |
 | 游戏代理 | 强化学习 | [Flutter](https://github.com/windmaple/planestrike-flutter) \| [Tutorial](https://windmaple.medium.com/)      | 社区 |



## Model zoo

### TensorFlow Lite models
这些是可以在应用程序和事物中实现的 TensorFlow Lite 模型：
* [MobileNet](https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet/README.md) - 预训练的 MobileNet v2 和 v3 模型.
* TensorFlow Lite 模型
  * [TensorFlow Lite models](https://www.tensorflow.org/lite/models) - 带有官方 Android 和 iOS 示例.
  * [Pretrained models](https://www.tensorflow.org/lite/guide/hosted_models) - 量化和浮点变体.
  * [TensorFlow Hub](https://tfhub.dev/) - 设置“模型格式 = TFLite”以查找 TensorFlow Lite 模型.

### TensorFlow models
这些是可以转换为 .tflite 然后在应用程序和事物中实现的 TensorFlow 模型：
* [TensorFlow models](https://github.com/tensorflow/models/tree/master/official) - 官方 TensorFlow 模型.
* [Tensorflow detection model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md) - 在 COCO、KITTI、AVA v2.1、iNaturalist Species 数据集上进行了预训练.

## Ideas and Inspiration
* [E2E TFLite Tutorials](https://github.com/ml-gde/e2e-tflite-tutorials)  - 查看此存储库以获取示例应用程序创意并为您的教程项目寻求帮助. 项目完成后，TensorFlow Lite 模型、示例代码和教程的链接将添加到这个很棒的列表中.

## ML Kit examples
[ML Kit](https://developers.google.com/ml-kit) 是一种移动 SDK，可为移动开发人员带来 Google 的 ML 专业知识.
* 2019-10-01 [ML Kit Translate demo](https://codelabs.developers.google.com/codelabs/mlkit-android-translate/#0) - 材料设计教程 [Android](https://github.com/googlecodelabs/mlkit-android/tree/master/translate) (Kotlin) 示例 - 使用 ML Kit for Firebase 识别、识别语言并翻译来自实时摄像头的文本.
* 2019-03-13 [Computer Vision with ML Kit - Flutter In Focus](https://youtu.be/ymyYUCrJnxU).
* 2019-02-09 [Flutter + MLKit: Business Card Mail Extractor](https://medium.com/flutter-community/flutter-mlkit-8039ec66b6a)  - 一篇博客文章 [Flutter](https://github.com/DaemonLoki/Business-Card-Mail-Extractor) 示例代码.
* 2019-02-08 [From TensorFlow to ML Kit: Power your Android application with machine learning](https://speakerdeck.com/jinqian/from-tensorflow-to-ml-kit-power-your-android-application-with-machine-learning) - 谈话 [Android](https://github.com/xebia-france/magritte) (Kotlin) 示例代码.
* 2018-08-07 [Building a Custom Machine Learning Model on Android with TensorFlow Lite](https://medium.com/over-engineering/building-a-custom-machine-learning-model-on-android-with-tensorflow-lite-26447e53abf2).
* 2018-07-20 [ML Kit and Face Detection in Flutter](https://flatteredwithflutter.com/ml-kit-and-face-detection-in-flutter/).
* 2018-07-27 [ML Kit on Android 4: Landmark Detection](https://medium.com/google-developer-experts/exploring-firebase-mlkit-on-android-landmark-detection-part-four-5e86b8deac3a).
* 2018-07-28 [ML Kit on Android 3: Barcode Scanning](https://medium.com/google-developer-experts/exploring-firebase-mlkit-on-android-barcode-scanning-part-three-cc6f5921a108).
* 2018-05-31 [ML Kit on Android 2: Face Detection](https://medium.com/google-developer-experts/exploring-firebase-mlkit-on-android-face-detection-part-two-de7e307c52e0).
* 2018-05-22 [ML Kit on Android 1: Intro](https://medium.com/google-developer-experts/exploring-firebase-mlkit-on-android-introducing-mlkit-part-one-98fcfedbeee0).

## Plugins and SDKs
* [Edge Impulse](https://www.edgeimpulse.com/) - 由...制作 [@EdgeImpulse](https://twitter.com/EdgeImpulse) 帮助您为云中的嵌入式设备训练 TensorFlow Lite 模型.
* [Fritz.ai](https://www.fritz.ai/) - 一个机器学习平台 [@fritzlabs](https://twitter.com/fritzlabs) 这使得移动开发更容易：使用预先训练的 ML 模型和端到端平台来构建和部署自定义训练模型.
* [MediaPipe](https://github.com/google/mediapipe)  - Google AI 的跨平台（移动、桌面和 Edge TPU）AI 管道.  （下午 [Ming Yong](https://twitter.com/realmgyong)) | [MediaPipe examples](https://mediapipe.readthedocs.io/en/latest/examples.html).
* [Coral Edge TPU](https://coral.ai/) - 谷歌的边缘硬件. [Coral Edge TPU examples](https://coral.ai/examples/).
* [TensorFlow Lite Flutter Plugin](https://github.com/am15h/tflite_flutter_plugin/) - Provides a dart API similar to the TensorFlow Lite Java API for accessing TensorFlow Lite interpreter and performing inference in flutter apps. [tflite_flutter on pub.dev](https://pub.dev/packages/tflite_flutter).

## Helpful links
* [Netron](https://github.com/lutzroeder/netron) - 用于可视化模型的工具.
* [AI benchmark](http://ai-benchmark.com/tests.html) - 在智能手机上对计算机视觉模型进行基准测试的网站.
* [Performance measurement](https://www.tensorflow.org/lite/performance/measurement) - 如何在 Android 和 iOS 上衡量模型性能.
* [Material design guidelines for ML](https://material.io/collections/machine-learning/patterns-for-machine-learning-powered-features.html)  - 如何设计机器学习驱动的功能. 一个很好的例子： [ML Kit Showcase App](https://github.com/firebase/mlkit-material-android).
* [The People + AI Guide book](https://pair.withgoogle.com/) - 学习如何设计以人为本的人工智能产品.
* [Adventures in TensorFlow Lite](https://github.com/sayakpaul/Adventures-in-TensorFlow-Lite) - 展示 TensorFlow Lite 中重要的转换过程和一般探索的存储库.
* [TFProfiler](https://github.com/iglaweb/TFProfiler) - 基于 Android 的应用程序，用于分析 TensorFlow Lite 模型并测量其在智能手机上的性能.
* [TensorFlow Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers)
* [TensorFlow Lite Examples - Android](https://github.com/dailystudio/tensorflow-lite-examples-android) - 存储库重构并重写了 TensorFlow 官方网站中包含的所有 TensorFlow Lite Android 示例. 

## Learning resources
有兴趣但不知道如何开始？ 以下是一些学习资源，无论您是该领域的初学者还是从业者，它们都会在一段时间内为您提供帮助.

### Blog posts

* 2020-12-29 [YOLOv3 to TensorFlow Lite Conversion](https://medium.com/analytics-vidhya/yolov3-to-tensorflow-lite-conversion-4602cec5c239) - Nitin Tiwari.
* 2020-04-20 [What is new in TensorFlow Lite](https://blog.tensorflow.org/2020/04/whats-new-in-tensorflow-lite-from-devsummit-2020.html) - 作者：Khanh LeViet.
* 2020-04-17 [Optimizing style transfer to run on mobile with TFLite](https://blog.tensorflow.org/2020/04/optimizing-style-transfer-to-run-on-mobile-with-tflite.html) - Khanh LeViet 和 Luiz Gustavo Martins.
* 2020-04-14 [How TensorFlow Lite helps you from prototype to product](https://blog.tensorflow.org/2020/04/how-tensorflow-lite-helps-you-from-prototype-to-product.html) - 作者：Khanh LeViet.
* 2019-11-08 [Getting  Started with ML on MCUs with TensorFlow](https://blog.particle.io/2019/11/08/particle-machine-learning-101/) -  By Brandon Satrom.
* 2019-08-05 [TensorFlow Model Optimization Toolkit — float16 quantization halves model size](https://blog.tensorflow.org/2019/08/tensorflow-model-optimization-toolkit_5.html) - 由 TensorFlow 团队提供.
* 2018-07-13 [Training and serving a real-time mobile object detector in 30 minutes with Cloud TPUs](https://blog.tensorflow.org/2018/07/training-and-serving-realtime-mobile-object-detector-cloud-tpus.html) - 作者：Sara Robinson、Aakanksha Chowdhery 和 Jonathan Huang.
* 2018-06-11 - [Why the Future of Machine Learning is Tiny](https://petewarden.com/2018/06/11/why-the-future-of-machine-learning-is-tiny/) - 皮特·沃登 (Pete Warden).
* 2018-03-30 - [Using TensorFlow Lite on Android](https://blog.tensorflow.org/2018/03/using-tensorflow-lite-on-android.html)) - 劳伦斯·莫罗尼 (Laurence Moroney).

### Books
* 2021-12-01 [AI and Machine Learning On-Device Development](https://learning.oreilly.com/library/view/ai-and-machine/9781098101732/) （抢先体验）- 作者：劳伦斯·莫罗尼 (Laurence Moroney)[@lmoroney](https://twitter.com/lmoroney)).
* 2020-10-01 [AI and Machine Learning for Coders](https://learning.oreilly.com/library/view/ai-and-machine/9781492078180/) - 劳伦斯·莫罗尼 (Laurence Moroney)[@lmoroney](https://twitter.com/lmoroney)).
* 2020-04-06 [Mobile Deep Learning with TensorFlow Lite, ML Kit and Flutter](https://www.packtpub.com/product/mobile-deep-learning-with-tensorflow-lite-ml-kit-and-flutter/9781789611212)：构建可扩展的现实世界项目，以在 Android 和 iOS 上实现端到端的神经网络（[GitHub](https://github.com/PacktPublishing/Mobile-Deep-Learning-Projects)) - 作者：阿努巴夫·辛格 (Anubhav Singh)[@xprilion](https://github.com/xprilion)) 和 Rimjhim Bhadani ([@Rimjhim28](https://github.com/Rimjhim28)).
* 2019-12-01 [TinyML](http://shop.oreilly.com/product/0636920254508.do) - 皮特·沃登（Pete Warden）（[@petewarden](https://twitter.com/petewarden)）和丹尼尔·斯图纳亚克（[@dansitu](https://twitter.com/dansitu)).
* 2019-10-01 [Practical Deep Learning for Cloud, Mobile, and Edge](https://www.practicaldeeplearning.ai/) - Anirudh Koul ([@AnirudhKoul](https://twitter.com/AnirudhKoul)), Siddha Ganju ([@SiddhaGanju](https://twitter.com/SiddhaGanju)) 和 Meher Kasam ([@MeherKasam](https://twitter.com/MeherKasam)).

### Videos
* 2020-07-25 [Android ML by Hoi Lam](https://youtu.be/m_bEh8YifnQ) （GDG 加尔各答聚会）.
* 2020-04-01 [Easy on-device ML from prototype to production](https://youtu.be/ALxWJoh_BHw) （2020 年 TF 开发者峰会）.
* 2020-03-11 [TensorFlow Lite: ML for mobile and IoT devices](https://youtu.be/27Zx-4GOQA8) （2020 年 TF 开发者峰会）.
* 2019-10-31 [Keynote - TensorFlow Lite: ML for mobile and IoT devices](https://youtu.be/zjDGAiLqGk8).
* 2019-10-31 [TensorFlow Lite: Solution for running ML on-device](https://youtu.be/0SpZy7iouFU).
* 2019-10-31 [TensorFlow model optimization: Quantization and pruning](https://youtu.be/3JWRVx1OKQQ).
* 2019-10-29 [Inside TensorFlow: TensorFlow Lite](https://youtu.be/gHN0jDbJz8E).
* 2018-04-18 [TensorFlow Lite for Android (Coding TensorFlow)](https://youtu.be/JnhW5tQ_7Vo).

### Podcasts
* 2020-08-08 [Talking Machine Learning with Hoi Lam](https://anchor.fm/talkingwithapples/episodes/Talking-Machine-Learning-with-Hoi-Lam-eiaj7v).

### MOOCs
* [Introduction to TensorFlow Lite](https://www.udacity.com/course/intro-to-tensorflow-lite--ud190) - 由 Daniel Situnayake (@dansitu)、Paige Bailey ([@DynamicWebPaige](https://twitter.com/DynamicWebPaige)）和胡安·德尔加多.
* [Device-based Models with TensorFlow Lite](https://www.coursera.org/learn/device-based-models-tensorflow) - Laurence Moroney 的 Coursera 课程（[@lmoroney](https://twitter.com/lmoroney)).
* [The Future of ML is Tiny and Bright](https://www.edx.org/professional-certificate/harvardx-tiny-machine-learning)  - 由哈佛与谷歌合作创建的一系列 edX 课程. 讲师 - Vijay Janapa Reddi、Laurence Moroney 和 Pete Warden.
