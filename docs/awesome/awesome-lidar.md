<div class="github-widget" data-repo="szenergy/awesome-lidar"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome LIDAR [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<img src="https://raw.githubusercontent.com/szenergy/awesome-lidar/master/img/lidar.svg?sanitize=true" align="right" width="100">

&gt; 精选的 LIDAR 传感器及其应用列表.

[LIDAR](https://en.wikipedia.org/wiki/Lidar) 是一种遥感传感器，它使用激光以 ~cm 的精度测量周围环境. 感官数据通常称为点云，表示 3D 或 2D 数据点集. 该列表包含硬件、数据集、点云处理算法、点云框架、模拟器等.

欢迎投稿！ 请 [check out](https://github.com/szenergy/awesome-lidar/blob/master/contributing.md) 我们的指导方针.



## Conventions

- 任何带有 OctoCat :octocat: 的列表项都有一个 GitHub 存储库或组织
- 任何带有 RedCircle :red_circle: 的列表项都有 YouTube 视频或频道
- 任何带有论文的列表项：报纸：有科学论文或详细描述

## Manufacturers

- [Velodyne](https://velodynelidar.com/)  - Ouster 和 Velodyne 宣布成功完成对等*合并*，自 2023 年 2 月 10 日起生效.Velodyne 是一家机械和固态激光雷达制造商. 总部位于美国加利福尼亚州圣何塞.
  - [YouTube channel :red_circle:](https://www.youtube.com/user/VelodyneLiDAR)
  - [ROS driver :octocat:](https://github.com/ros-drivers/velodyne)
- [Ouster](https://ouster.com/)  - 激光雷达制造商，专注于数字旋转激光雷达.  Ouster 总部位于美国旧金山.
  - [YouTube channel :red_circle:](https://www.youtube.com/c/Ouster-lidar)
  - [GitHub organization :octocat:](https://github.com/ouster-lidar)
- [Livox](https://www.livoxtech.com/) - 激光雷达制造商.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCnLpB5QxlQUexi40vM12mNQ)
  - [GitHub organization :octocat:](https://github.com/Livox-SDK)
- [SICK](https://www.sick.com/ag/en/) - 传感器和自动化制造商，总部位于德国瓦尔德基希.
  - [YouTube channel :red_circle:](https://www.youtube.com/user/SICKSensors)
  - [GitHub organization :octocat:](https://github.com/SICKAG)
- [Hokuyo](https://www.hokuyo-aut.jp/) - 传感器和自动化制造商，总部位于日本大阪.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCYzJXC82IEy-h-io2REin5g)
- [Pioneer](http://autonomousdriving.pioneer/en/3d-lidar/)  - 激光雷达制造商，专注于基于 MEMS 反射镜的光栅扫描激光雷达 (3D-LiDAR). 先锋总部位于日本东京.
  - [YouTube channel :red_circle:](https://www.youtube.com/user/PioneerCorporationPR)
- [Luminar](https://www.luminartech.com/)  - 专注于紧凑型汽车级传感器的激光雷达制造商.  Luminar 总部位于美国加利福尼亚州帕洛阿尔托.
  - [Vimeo channel :red_circle:](https://vimeo.com/luminartech)
  - [GitHub organization :octocat:](https://github.com/luminartech)
- [Hesai](https://www.hesaitech.com/) - 禾赛科技是一家激光雷达制造商，成立于中国上海.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCG2_ffm6sdMsK-FX8yOLNYQ/videos)
  - [GitHub organization :octocat:](https://github.com/HesaiTechnology)
- [Robosense](http://www.robosense.ai/) - RoboSense（速腾创新科技有限公司）是位于深圳和北京（中国）的 LIDAR 传感器、AI 算法和 IC 芯片组制造商.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCYCK8j678N6d_ayWE_8F3rQ)
  - [GitHub organization :octocat:](https://github.com/RoboSense-LiDAR)
- [Ibeo](https://www.ibeo-as.com/) - Ibeo Automotive Systems GmbH 是一家汽车行业/环境检测激光扫描仪/激光雷达制造商，总部位于德国汉堡.
  - [YouTube channel :red_circle:](https://www.youtube.com/c/IbeoAutomotive/)
- [Innoviz](https://innoviz.tech/) - Innoviz technologies / 专注于固态激光雷达.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCVc1KFsu2eb20M8pKFwGiFQ)
- [Quanenergy](https://quanergy.com/)  - Quanenergy Systems / 固态和机械 LIDAR 传感器 / 提供测绘、工业自动化、运输和安全方面的端到端解决方案. 总部位于美国加利福尼亚州桑尼维尔.
  - [YouTube channel :red_circle:](https://www.youtube.com/c/QuanergySystems)
- [Cepton](https://www.cepton.com/index.html) - Cepton (Cepton Technologies, Inc.) / pioneers in frictionless, and mirrorless design, self-developed MMT (micro motion technology) lidar technology. The headquarter is located in San Jose, California, USA.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCUgkBZZ1UWWkkXJ5zD6o8QQ)
- [Blickfeld](https://www.blickfeld.com/) - Blickfeld 是一家用于自主移动和物联网的固态激光雷达制造商，总部位于德国慕尼黑.
  - [YouTube channel :red_circle:](https://www.youtube.com/c/BlickfeldLiDAR)
  - [GitHub organization :octocat:](https://github.com/Blickfeld)
- [Neuvition](https://www.neuvition.com/) - Neuvition 是一家位于中国吴江的固态激光雷达制造商.
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UClFjlekWJo4T5bfzxX0ZW3A)
- [Aeva](https://www.aeva.com/) - Aeva 正在为自动驾驶、消费电子、健康、工业机器人和安全的所有设备带来下一波感知技术，美国加利福尼亚州山景城.
  - [YouTube channel :red_circle:](https://www.youtube.com/c/AevaInc)
  - [GitHub organization :octocat:](https://github.com/aevainc)

## Datasets

- [Ford Dataset](https://avdata.ford.com/)  - 数据集带有时间戳，包含来自所有传感器的原始数据、校准值、姿态轨迹、地面真实姿态和 3D 地图. 数据与机器人操作系统 (ROS) 兼容.
  - [Paper :newspaper:](https://arxiv.org/pdf/2003.07969.pdf)
  - [GitHub repository :octocat:](https://github.com/Ford/AVData)
- [Audi A2D2 Dataset](https://www.a2d2.audi) - 该数据集具有 2D 语义分割、3D 点云、3D 边界框和车辆总线数据.
  - [Paper :newspaper:](https://www.a2d2.audi/content/dam/a2d2/dataset/a2d2-audi-autonomous-driving-dataset.pdf)
- [Waymo Open Dataset](https://waymo.com/open/) - 数据集包含独立生成的激光雷达和相机数据标签，而不仅仅是投影.
- [Oxford RobotCar](https://robotcar-dataset.robots.ox.ac.uk/) - Oxford RobotCar 数据集包含超过 100 次重复通过英国牛津的一致路线，这些路线在一年多的时间里被捕获. 
  - [YouTube channel :red_circle:](https://www.youtube.com/c/ORIOxfordRoboticsInstitute)
  - [Paper :newspaper:](https://robotcar-dataset.robots.ox.ac.uk/images/RCD_RTK.pdf)
- [EU Long-term Dataset](https://epan-utbm.github.io/utbm_robocar_dataset/)  - 这个数据集是用我们的机器人汽车（当然是人类驾驶模式）收集的，配备了多达 11 个异构传感器，在法国蒙贝利亚尔的市中心（用于长期数据）和郊区（用于环形交叉路口数据）. 根据法国交通规则，车速限制在 50 公里/小时.
- [NuScenes](https://www.nuscenes.org/) - Public large-scale dataset for autonomous driving.
  - [Paper :newspaper:](https://arxiv.org/pdf/1903.11027.pdf)
- [Lyft](https://level5.lyft.com/dataset/) - 由配备激光雷达和摄像头的福特 Fusion 车队收集的公共数据集.
- [KITTI](http://www.cvlibs.net/datasets/kitti/raw_data.php) - 广泛的公共数据集，主要关注计算机视觉应用，但也包含 LIDAR 点云.
- [Semantic KITTI](http://semantic-kitti.org/) - 用于语义和全景场景分割的数据集.
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=3qNOXvkpK4I)
- [CADC - Canadian Adverse Driving Conditions Dataset](http://cadcd.uwaterloo.ca/) - 恶劣天气条件下（下雪天气）自动驾驶的公共大型数据集.
  - [Paper :newspaper:](https://arxiv.org/pdf/2001.10117.pdf)
- [UofTPed50 Dataset](https://www.autodrive.utoronto.ca/uoftped50)  - 多伦多大学，aUToronto 的自动驾驶汽车数据集，其中包含 GPS/IMU、3D LIDAR 和单目相机数据. 可用于3D行人检测.
  - [Paper :newspaper:](https://arxiv.org/pdf/1905.08758.pdf)
- [PandaSet Open Dataset](https://scale.com/open-datasets/pandaset)  - Hesa​​i &amp; Scale 提供的自动驾驶公共大规模数据集. 它使研究人员能够使用真正的自动驾驶汽车的完整传感器套装来研究具有挑战性的城市驾驶情况.
- [Cirrus dataset](https://developer.volvocars.com/open-datasets/cirrus/) 来自 LIDAR 扫描模式非均匀分布的公共数据集，重点是远距离. 在此数据集中，使用了 Luminar Hydra LIDAR. 该数据集可在沃尔沃汽车创新门户网站上获得.
  - [Paper :newspaper:](https://arxiv.org/pdf/2012.02938.pdf)
- [USyd Dataset- The Univerisity of Sydney Campus- Dataset](http://its.acfr.usyd.edu.au/datasets/usyd-campus-dataset/)  - 在 1.5 年期间每周在悉尼大学校园及周边地区收集的长期、大规模数据集. 它包括多种传感器模式并涵盖各种环境条件.  ROS兼容
  - [Paper :newspaper:](https://ieeexplore.ieee.org/document/9109704)
- [Brno Urban Dataset :octocat:](https://github.com/Robotics-BUT/Brno-Urban-Dataset) - 捷克布尔诺的自动驾驶汽车和自动机器人的导航和定位数据集.
  - [Paper :newspaper:](https://ieeexplore.ieee.org/document/9197277)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=wDFePIViwqY)
- [Argoverse :octocat:](https://www.argoverse.org/) - 旨在支持自动驾驶车辆感知任务的数据集，包括在美国宾夕法尼亚州匹兹堡和佛罗里达州迈阿密收集的 3D 跟踪和运动预测.
  - [Paper :newspaper:](https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=DM8jWfi69zM)
- [Boreas Dataset](https://www.boreas.utias.utoronto.ca/)  - Boreas 数据集是通过在 1 年的过程中重复行驶导致明显的季节性变化的路线收集的.  Boreas 总共包含超过 350 公里的驾驶数据，其中包括雨和大雪等恶劣天气条件下的几个序列.  Boreas 数据采集平台具有独特的高质量传感器套件，包括 128 通道 Velodyne Alpha Prime 激光雷达、360 度 Navtech 雷达，以及从 Applanix POSLV GPS/IMU 获得的准确地面实况姿态. 
  - [Paper 📰](https://arxiv.org/abs/2203.10168)
  - [GitHub repository :octocat:](https://github.com/utiasASRL/pyboreas)

## Libraries

- [Point Cloud Library (PCL)](http://www.pointclouds.org/) - 流行的高度并行编程库，具有大量工业和研究用例. 
  - [GitHub repository :octocat:](https://github.com/PointCloudLibrary/pcl)
- [Open3D library](http://www.open3d.org/docs/release/)  - Open3D 库包含 3D 数据处理和可视化算法. 它是开源的，同时支持 C++ 和 Python.
  - [GitHub repository :octocat:](https://github.com/intel-isl/Open3D)
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCRJBlASPfPBtPXJSPffJV-w)
- [PyTorch Geometric :newspaper:](https://arxiv.org/pdf/1903.02428.pdf) - PyTorch 的几何深度学习扩展库.
  - [GitHub repository :octocat:](https://github.com/rusty1s/pytorch_geometric)
- [PyTorch3d](https://pytorch3d.org/) - PyTorch3d 是一个用于深度学习的库，由 Facebook 人工智能研究计算机视觉团队编写和维护 3D 数据.
  - [GitHub repository :octocat:](https://github.com/facebookresearch/pytorch3d)
- [Kaolin](https://kaolin.readthedocs.io/en/latest/) - Kaolin 是 NVIDIA Technologies 为游戏和应用程序开发人员编写的用于加速 3D 深度学习研究的 PyTorch 库.
  - [GitHub repository :octocat:](https://github.com/NVIDIAGameWorks/kaolin/)
  - [Paper :newspaper:](https://arxiv.org/pdf/1911.05063.pdf)
- [PyVista](https://docs.pyvista.org/) - 通过可视化工具包的简化界面进行 3D 绘图和网格分析.
  - [GitHub repository :octocat:](https://github.com/pyvista/pyvista)
  - [Paper :newspaper:](https://joss.theoj.org/papers/10.21105/joss.01450)
- [pyntcloud](https://pyntcloud.readthedocs.io/en/latest/) - Pyntcloud 是一个 Python 3 库，用于利用 Python 科学堆栈的强大功能处理 3D 点云.
  - [GitHub repository :octocat:](https://github.com/daavoo/pyntcloud)
- [pointcloudset](https://virtual-vehicle.github.io/pointcloudset/) - 用于高效分析随时间记录的大型点云数据集的 Python 库.
  - [GitHub repository :octocat:](https://github.com/virtual-vehicle/pointcloudset) 

## Frameworks

- [Autoware](https://www.autoware.ai/) - 自动驾驶汽车学术和研究应用中的流行框架.
  - [GitLab repository :octocat:](https://gitlab.com/autowarefoundation/autoware.ai)
  - [Paper :newspaper:](https://www.researchgate.net/profile/Takuya_Azumi/publication/327198306_Autoware_on_Board_Enabling_Autonomous_Vehicles_with_Embedded_Systems/links/5c9085da45851564fae6dcd0/Autoware-on-Board-Enabling-Autonomous-Vehicles-with-Embedded-Systems.pdf)
- [Baidu Apollo](https://apollo.auto/) - Apollo 是一个流行的框架，可以加速自动驾驶汽车的开发、测试和部署.
  - [GitHub repository :octocat:](https://github.com/ApolloAuto/apollo)
  - [YouTube channel :red_circle:](https://www.youtube.com/c/ApolloAuto)

## Algorithms

### Basic matching algorithms
- [Iterative closest point (ICP) :red_circle:](https://www.youtube.com/watch?v=uzOCS_gdZuM) - 特征匹配应用程序 (ICP) 的必备算法.
  - [GitHub repository :octocat:](https://github.com/pglira/simpleICP) - simpleICP C++ /Julia / Matlab / Octave / Python 实现.
  - [GitHub repository :octocat:](https://github.com/ethz-asl/libpointmatcher) - libpointmatcher，一个实现 ICP 算法的模块化库.
  - [Paper :newspaper:](https://link.springer.com/content/pdf/10.1007/s10514-013-9327-2.pdf) - libpointmatcher：比较真实世界数据集上的 ICP 变体.
- [Normal distributions transform :red_circle:](https://www.youtube.com/watch?v=0YV4a2asb8Y) - 更新的大规模并行特征匹配 (NDT) 方法.
- [KISS-ICP :red_circle:](https://www.youtube.com/watch?v=kMMH8rA1ggI) - 为点对点 ICP 辩护——如果方法正确，注册简单、准确且稳健.
  - [GitHub repository :octocat:](https://github.com/PRBonn/kiss-icp)
  - [Paper :newspaper:](https://arxiv.org/pdf/2209.15397.pdf)

### Semantic segmentation
- [RangeNet++ :newspaper:](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/milioto2019iros.pdf) - 具有全卷积网络的快速准确的 LiDAR 语义分割.
  - [GitHub repository :octocat:](https://github.com/PRBonn/rangenet_lib)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=uo3ZuLuFAzk)
- [PolarNet :newspaper:](https://arxiv.org/pdf/2003.14032.pdf) - 改进的在线 LiDAR 点云语义分割网格表示.
  - [GitHub repository :octocat:](https://github.com/edwardzhou130/PolarSeg)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=iIhttRSMqjE)
- [Frustum PointNets :newspaper:](https://arxiv.org/pdf/1711.08488.pdf) - 用于从 RGB-D 数据进行 3D 对象检测的 Frustum PointNets.
  - [GitHub repository :octocat:](https://github.com/charlesq34/frustum-pointnets)
- [Study of LIDAR Semantic Segmentation](https://larissa.triess.eu/scan-semseg/) - LiDAR 点云的基于扫描的语义分割：一项实验研究 IV 2020.
  - [Paper :newspaper:](https://arxiv.org/abs/2004.11803)
  - [GitHub repository :octocat:](http://ltriess.github.io/scan-semseg)
- [LIDAR-MOS :newspaper:](https://www.ipb.uni-bonn.de/pdfs/chen2021ral-iros.pdf) - 3D 激光雷达数据中的移动对象分割
  - [GitHub repository :octocat:](https://github.com/PRBonn/LiDAR-MOS)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=NHvsYhk4dhw)
- [SuperPoint Graph :newspaper:](https://arxiv.org/pdf/1711.09869.pdf)- 具有超点图的大规模点云语义分割
  - [GitHub repository :octocat:](https://github.com/PRBonn/LiDAR-MOS)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=Ijr3kGSU_tU)
- [RandLA-Net :newspaper:](https://arxiv.org/pdf/1911.11236.pdf) - 大规模点云的高效语义分割
  - [GitHub repository :octocat:](https://github.com/QingyongHu/RandLA-Net)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=Ar3eY_lwzMk)
- [Automatic labelling :newspaper:](https://arxiv.org/pdf/2108.13757.pdf) - 使用数据融合自动标记城市点云
  - [GitHub repository :octocat:](https://github.com/Amsterdam-AI-Team/Urban_PointCloud_Processing)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=qMj_WM6D0vI)

### Ground segmentation
- [Plane Seg :octocat:](https://github.com/ori-drs/plane_seg)  - ROS 兼容的地平面分割； 用于将平面安装到激光雷达的库.
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=YYs4lJ9t-Xo)
- [LineFit Graph :newspaper:](https://ieeexplore.ieee.org/abstract/document/5548059)- 水平 3D LiDAR 数据的基于线拟合的快速地面分割
  - [GitHub repository :octocat:](https://github.com/lorenwel/linefit_ground_segmentation)
- [Patchwork :newspaper:](https://arxiv.org/pdf/2108.05560.pdf)- 用于 3D LiDAR 数据的基于区域平面拟合的鲁棒和快速地面分割 
  - [GitHub repository :octocat:](https://github.com/LimHyungTae/patchwork)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=rclqeDi4gow)
- [Patchwork++ :newspaper:](https://arxiv.org/pdf/2207.11919.pdf) - 拼布的改进版本.  Patchwork++ 也为深度学习用户提供 pybinding
  - [GitHub repository :octocat:](https://github.com/url-kaist/patchwork-plusplus-ros)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=fogCM159GRk)


### Simultaneous localization and mapping SLAM and LIDAR-based odometry and or mapping LOAM
- [LOAM J. Zhang and S. Singh :red_circle:](https://youtu.be/8ezyhTAEyHs) - LOAM：实时激光雷达测距和映射.
- [LeGO-LOAM :octocat:](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM) - 用于 ROS 兼容 UGV 的轻型和地面优化激光雷达里程计和映射 (LeGO-LOAM) 系统. 
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=7uCxLUs9fwQ)
- [Cartographer :octocat:](https://github.com/cartographer-project/cartographer) - Cartographer 是 ROS 兼容系统，可跨多个平台和传感器配置提供 2D 和 3D 实时同步定位和映射 (SLAM).
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=29Knm-phAyI)
- [SuMa++ :newspaper:](http://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/chen2019iros.pdf) - 基于激光雷达的语义 SLAM.
  - [GitHub repository :octocat:](https://github.com/PRBonn/semantic_suma/)
  - [YouTube video :red_circle:](https://youtu.be/uo3ZuLuFAzk)
- [OverlapNet :newspaper:](http://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/chen2020rss.pdf) - 基于 LiDAR 的 SLAM 的闭环.
  - [GitHub repository :octocat:](https://github.com/PRBonn/OverlapNet)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=YTfliBco6aw)
- [LIO-SAM :newspaper:](https://arxiv.org/pdf/2007.00258.pdf) - 通过平滑和映射的紧耦合激光雷达惯性里程计.
  - [GitHub repository :octocat:](https://github.com/TixiaoShan/LIO-SAM)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=A0H8CoORZJU)
- [Removert :newspaper:](http://ras.papercept.net/images/temp/IROS/files/0855.pdf) - 删除，然后还原：使用多分辨率范围图像构建静态点云地图.
  - [GitHub repository :octocat:](https://github.com/irapkaist/removert)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=M9PEGi5fAq8)

### Object detection and object tracking
- [Learning to Optimally Segment Point Clouds :newspaper:](https://arxiv.org/abs/1912.04976)  - 卡内基梅隆大学的 Peiyun Hu、David Held 和 Deva Ramanan.  IEEE 机器人与自动化快报，2020 年.
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=wLxIAwIL870)
  - [GitHub repository :octocat:](https://github.com/peiyunh/opcseg)
- [Leveraging Heteroscedastic Aleatoric Uncertainties for Robust Real-Time LiDAR 3D Object Detection :newspaper:](https://arxiv.org/pdf/1809.05590.pdf)  - Di Feng、Lars Rosenbaum、Fabian Timm、Klaus Dietmayer. 第 30 届 IEEE 智能汽车研讨会，2019 年.
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=2DzH9COLpkU)
- [What You See is What You Get: Exploiting Visibility for 3D Object Detection :newspaper:](https://arxiv.org/pdf/1912.04986.pdf) - 胡佩云、Jason Ziglar、David Held、Deva Ramanan，2019 年.
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=497OF-otY2k)
  - [GitHub repository :octocat:](https://github.com/peiyunh/WYSIWYG)
- [urban_road_filter :newspaper:](https://doi.org/10.3390/s22010194)-
用于自动驾驶车辆的基于激光雷达的实时城市道路和人行道检测
  - [GitHub repository :octocat:](https://github.com/jkk-research/urban_road_filter)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=T2qi4pldR-E)

## Simulators
- [CoppeliaSim](https://www.coppeliarobotics.com/coppeliaSim) - 跨平台通用机器人模拟器（以前称为 V-REP）.
  - [YouTube channel :red_circle:](https://www.youtube.com/user/VirtualRobotPlatform)
- [OSRF Gazebo](http://gazebosim.org/) - 基于 OGRE 的通用机器人模拟器，兼容 ROS/ROS2.
  - [GitHub repository :octocat:](https://github.com/osrf/gazebo)
- [CARLA](https://carla.org/)  - 用于汽车应用的基于虚幻引擎的模拟器. 兼容Autoware、百度Apollo和ROS/ROS2.
  - [GitHub repository :octocat:](https://github.com/carla-simulator/carla)
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UC1llP9ekCwt8nEJzMJBQekg)
- [LGSVL](https://www.lgsvlsimulator.com/)  - 用于汽车应用的基于 Unity 引擎的模拟器. 兼容Autoware、百度Apollo和ROS/ROS2.
  - [GitHub repository :octocat:](https://github.com/lgsvl/simulator)
  - [YouTube channel :red_circle:](https://www.youtube.com/c/LGSVLSimulator)
- [AirSim](https://microsoft.github.io/AirSim)  - 基于虚幻引擎的无人机和汽车模拟器. 与 ROS 兼容.
  - [GitHub repository :octocat:](https://github.com/microsoft/AirSim)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=gnz1X3UNM5Y)

## Related awesome
- [Awesome point cloud analysis :octocat:](https://github.com/Yochengliu/awesome-point-cloud-analysis#readme)
- [Awesome robotics :octocat:](https://github.com/Kiloreux/awesome-robotics#readme)
- [Awesome robotics libraries :octocat:](https://github.com/jslee02/awesome-robotics-libraries#readme)
- [Awesome ROS2 :octocat:](https://github.com/fkromer/awesome-ros2#readme)
- [Awesome artificial intelligence :octocat:](https://github.com/owainlewis/awesome-artificial-intelligence#readme)
- [Awesome computer vision :octocat:](https://github.com/jbhuang0604/awesome-computer-vision#readme)
- [Awesome machine learning :octocat:](https://github.com/josephmisiti/awesome-machine-learning#readme)
- [Awesome deep learning :octocat:](https://github.com/ChristosChristofidis/awesome-deep-learning#readme)
- [Awesome reinforcement learning :octocat:](https://github.com/aikorea/awesome-rl/#readme)
- [Awesome SLAM datasets :octocat:](https://github.com/youngguncho/awesome-slam-datasets#readme)
- [Awesome electronics :octocat:](https://github.com/kitspace/awesome-electronics#readme)
- [Awesome vehicle security and car hacking :octocat:](https://github.com/jaredthecoder/awesome-vehicle-security#readme)
- [Awesome LIDAR-Camera calibration :octocat:](https://github.com/Deephome/Awesome-LiDAR-Camera-Calibration)

## Others
- [ARHeadsetKit](https://github.com/philipturner/ARHeadsetKit)  - 使用 5 美元的 Google Cardboard 复制 Microsoft Hololens. 托管用于研究的源代码 [scene color reconstruction](https://github.com/philipturner/scene-color-reconstruction).
- [Pointcloudprinter :octocat:](https://github.com/marian42/pointcloudprinter) - 一种将空中激光雷达扫描的点云数据转换为实体网格以进行 3D 打印的工具.
- [CloudCompare](https://cloudcompare.org/) - CloudCompare 是一款免费的跨平台点云编辑器软件.
  - [GitHub repository :octocat:](https://github.com/CloudCompare)
- [Pcx :octocat:](https://github.com/keijiro/Pcx) - Unity 的点云导入器/渲染器.
- [Bpy :octocat:](https://github.com/uhlik/bpy) - 用于 Blender、点云可视化工具的点云导入器/渲染器/编辑器.
- [Semantic Segmentation Editor :octocat:](https://github.com/Hitachi-Automotive-And-Industry-Lab/semantic-segmentation-editor) - 日立汽车工业实验室的点云和图像语义分割编辑器，点云注释器/标签.
- [3D Bounding Box Annotation Tool :octocat:](https://github.com/walzimmer/3d-bat) - 3D BAT：用于全环绕、多模态数据流、点云注释器/标签的半自动、基于 Web 的 3D 注释工具箱.
  - [Paper :newspaper:](https://arxiv.org/pdf/1905.00525.pdf)
  - [YouTube video :red_circle:](https://www.youtube.com/watch?v=gSGG4Lw8BSU)
- [Photogrammetry importer :octocat:](https://github.com/SBCV/Blender-Addon-Photogrammetry-Importer) - 用于导入多个库的重建结果的 Blender 插件.
- [Foxglove](https://foxglove.dev/) - Foxglove Studio 是一款集成的机器人可视化和诊断工具，可在您的浏览器中使用，也可在 Linux、Windows 和 macOS 上作为桌面应用程序下载.
  - [GitHub repository :octocat:](https://github.com/foxglove/studio)
  - [YouTube channel :red_circle:](https://www.youtube.com/channel/UCrIbrBxb9HBAnlhbx2QycsA)
- [MeshLab](https://www.meshlab.net/) - MeshLab 是一个开源、可移植和可扩展的系统，用于处理和编辑 3D 三角形网格和点云.
  - [GitHub repository :octocat:](https://github.com/cnr-isti-vclab/meshlab) 
