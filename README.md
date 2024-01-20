[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2024.01.20
> Usage instructions: [here](./docs/README.md#usage)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#slam>SLAM</a></li>
    <li><a href=#sfm>SFM</a></li>
    <li><a href=#visual-localization>Visual Localization</a></li>
    <li><a href=#keypoint-detection>Keypoint Detection</a></li>
    <li><a href=#image-matching>Image Matching</a></li>
    <li><a href=#nerf>NeRF</a></li>
    <li><a href=#bev>BEV</a></li>
    <li><a href=#registration>Registration</a></li>
    <li><a href=#localization>Localization</a></li>
    <li><a href=#feature>Feature</a></li>
    <li><a href=#matching>Matching</a></li>
    <li><a href=#relocalization>Relocalization</a></li>
    <li><a href=#imu>IMU</a></li>
    <li><a href=#transformer>Transformer</a></li>
    <li><a href=#occupancy>Occupancy</a></li>
    <li><a href=#occupancy-map>Occupancy Map</a></li>
    <li><a href=#occupancy-predict>Occupancy Predict</a></li>
  </ol>
</details>

## SLAM

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-17**|**Event-Based Visual Odometry on Non-Holonomic Ground Vehicles**|Wanting Xu et.al.|[2401.09331](http://arxiv.org/abs/2401.09331)|**[link](https://github.com/gowanting/nhevo)**|
|**2024-01-11**|**On State Estimation in Multi-Sensor Fusion Navigation: Optimization and Filtering**|Feng Zhu et.al.|[2401.05836](http://arxiv.org/abs/2401.05836)|null|
|**2023-12-19**|**Loss it right: Euclidean and Riemannian Metrics in Learning-based Visual Odometry**|Olaya Álvarez-Tuñón et.al.|[2401.05396](http://arxiv.org/abs/2401.05396)|**[link](https://github.com/remaro-network/Loss_VO_right)**|
|**2024-01-07**|**Amirkabir campus dataset: Real-world challenges and scenarios of Visual Inertial Odometry (VIO) for visually impaired people**|Ali Samadzadeh et.al.|[2401.03604](http://arxiv.org/abs/2401.03604)|**[link](https://github.com/A3DV/VIRec)**|
|**2024-01-03**|**LEAP-VO: Long-term Effective Any Point Tracking for Visual Odometry**|Weirong Chen et.al.|[2401.01887](http://arxiv.org/abs/2401.01887)|null|
|**2023-12-28**|**SR-LIVO: LiDAR-Inertial-Visual Odometry and Mapping with Sweep Reconstruction**|Zikang Yuan et.al.|[2312.16800](http://arxiv.org/abs/2312.16800)|**[link](https://github.com/ZikangYuan/sr_livo)**|
|**2023-12-20**|**NeRF-VO: Real-Time Sparse Visual Odometry with Neural Radiance Fields**|Jens Naumann et.al.|[2312.13471](http://arxiv.org/abs/2312.13471)|null|
|**2023-12-22**|**Ternary-type Opacity and Hybrid Odometry for RGB-only NeRF-SLAM**|Junru Lin et.al.|[2312.13332](http://arxiv.org/abs/2312.13332)|null|
|**2023-12-20**|**Brain-Inspired Visual Odometry: Balancing Speed and Interpretability through a System of Systems Approach**|Habib Boloorchi Tabrizi et.al.|[2312.13162](http://arxiv.org/abs/2312.13162)|null|
|**2023-12-20**|**Trajectory Approximation of Video Based on Phase Correlation for Forward Facing Camera**|Abdulkadhem A. Abdulkadhem et.al.|[2312.12680](http://arxiv.org/abs/2312.12680)|null|
|**2023-12-15**|**Deep Event Visual Odometry**|Simon Klenk et.al.|[2312.09800](http://arxiv.org/abs/2312.09800)|**[link](https://github.com/tum-vision/devo)**|
|**2023-12-10**|**SuperPrimitive: Scene Reconstruction at a Primitive Level**|Kirill Mazur et.al.|[2312.05889](http://arxiv.org/abs/2312.05889)|null|
|**2023-12-04**|**iMatching: Imperative Correspondence Learning**|Zitong Zhan et.al.|[2312.02141](http://arxiv.org/abs/2312.02141)|null|
|**2023-11-30**|**Event-based Visual Inertial Velometer**|Xiuyuan Lu et.al.|[2311.18189](http://arxiv.org/abs/2311.18189)|null|
|**2023-11-21**|**CoVOR-SLAM: Cooperative SLAM using Visual Odometry and Ranges for Multi-Robot Systems**|Young-Hee Lee et.al.|[2311.12580](http://arxiv.org/abs/2311.12580)|null|
|**2023-11-10**|**Dense Visual Odometry Using Genetic Algorithm**|Slimane Djema et.al.|[2311.06149](http://arxiv.org/abs/2311.06149)|null|
|**2023-11-07**|**Inertial Guided Uncertainty Estimation of Feature Correspondence in Visual-Inertial Odometry/SLAM**|Seongwook Yoon et.al.|[2311.03722](http://arxiv.org/abs/2311.03722)|null|
|**2023-10-23**|**Converting Depth Images and Point Clouds for Feature-based Pose Estimation**|Robert Lösch et.al.|[2310.14924](http://arxiv.org/abs/2310.14924)|**[link](https://github.com/rlsch/depth-conversions)**|
|**2023-10-17**|**Open-Structure: a Structural Benchmark Dataset for SLAM Algorithms**|Yanyan Li et.al.|[2310.10931](http://arxiv.org/abs/2310.10931)|**[link](https://github.com/yanyan-li/open-structure)**|
|**2023-10-12**|**Jointly Optimized Global-Local Visual Localization of UAVs**|Haoling Li et.al.|[2310.08082](http://arxiv.org/abs/2310.08082)|null|
|**2023-10-10**|**l-dyno: framework to learn consistent visual features using robot's motion**|Kartikeya Singh et.al.|[2310.06249](http://arxiv.org/abs/2310.06249)|null|
|**2023-10-08**|**XVO: Generalized Visual Odometry via Cross-Modal Self-Training**|Lei Lai et.al.|[2309.16772](http://arxiv.org/abs/2309.16772)|null|
|**2023-10-22**|**ObVi-SLAM: Long-Term Object-Visual SLAM**|Amanda Adkins et.al.|[2309.15268](http://arxiv.org/abs/2309.15268)|null|
|**2023-09-23**|**Tag-based Visual Odometry Estimation for Indoor UAVs Localization**|Massimiliano Bertoni et.al.|[2309.13311](http://arxiv.org/abs/2309.13311)|null|
|**2023-09-22**|**Exposing the Unseen: Exposure Time Emulation for Offline Benchmarking of Vision Algorithms**|Olivier Gamache et.al.|[2309.13139](http://arxiv.org/abs/2309.13139)|**[link](https://github.com/norlab-ulaval/borealhdr)**|
|**2023-09-20**|**Conformalized Multimodal Uncertainty Regression and Reasoning**|Domenico Parente et.al.|[2309.11018](http://arxiv.org/abs/2309.11018)|null|
|**2023-09-20**|**OCC-VO: Dense Mapping via 3D Occupancy-Based Visual Odometry for Autonomous Driving**|Heng Li et.al.|[2309.11011](http://arxiv.org/abs/2309.11011)|null|
|**2023-09-19**|**LiDAR-Generated Images Derived Keypoints Assisted Point Cloud Registration Scheme in Odometry Estimation**|Haizhou Zhang et.al.|[2309.10436](http://arxiv.org/abs/2309.10436)|**[link](https://github.com/tiers/ws-lidar-as-camera-odom)**|
|**2023-09-21**|**Dive Deeper into Rectifying Homography for Stereo Camera Online Self-Calibration**|Hongbo Zhao et.al.|[2309.10314](http://arxiv.org/abs/2309.10314)|null|
|**2023-09-18**|**End-to-End Learned Event- and Image-based Visual Odometry**|Roberto Pellerito et.al.|[2309.09947](http://arxiv.org/abs/2309.09947)|null|
|**2023-09-14**|**An Explicit Method for Fast Monocular Depth Recovery in Corridor Environments**|Yehao Liu et.al.|[2309.07408](http://arxiv.org/abs/2309.07408)|null|
|**2023-10-10**|**Evaluating Visual Odometry Methods for Autonomous Driving in Rain**|Yu Xiang Tan et.al.|[2309.05249](http://arxiv.org/abs/2309.05249)|null|
|**2023-09-08**|**Robot Localization and Mapping Final Report -- Sequential Adversarial Learning for Self-Supervised Deep Visual Odometry**|Akankshya Kar et.al.|[2309.04147](http://arxiv.org/abs/2309.04147)|null|
|**2023-09-04**|**EMR-MSF: Self-Supervised Recurrent Monocular Scene Flow Exploiting Ego-Motion Rigidity**|Zijie Jiang et.al.|[2309.01296](http://arxiv.org/abs/2309.01296)|null|
|**2023-08-27**|**Deep Learning for Visual Localization and Mapping: A Survey**|Changhao Chen et.al.|[2308.14039](http://arxiv.org/abs/2308.14039)|null|
|**2023-08-19**|**Enhancing State Estimation in Robots: A Data-Driven Approach with Differentiable Ensemble Kalman Filters**|Xiao Liu et.al.|[2308.09870](http://arxiv.org/abs/2308.09870)|**[link](https://github.com/ir-lab/denkf)**|
|**2023-08-12**|**4DRVO-Net: Deep 4D Radar-Visual Odometry Using Multi-Modal and Multi-Scale Adaptive Fusion**|Guirong Zhuo et.al.|[2308.06573](http://arxiv.org/abs/2308.06573)|null|
|**2023-08-10**|**Mono-hydra: Real-time 3D scene graph construction from monocular camera input with IMU**|U. V. B. L. Udugama et.al.|[2308.05515](http://arxiv.org/abs/2308.05515)|null|
|**2023-08-02**|**A Small Form Factor Aerial Research Vehicle for Pick-and-Place Tasks with Onboard Real-Time Object Detection and Visual Odometry**|Cora A. Dimmig et.al.|[2308.01398](http://arxiv.org/abs/2308.01398)|null|
|**2023-08-02**|**Stereo Visual Odometry with Deep Learning-Based Point and Line Feature Matching using an Attention Graph Neural Network**|Shenbagaraj Kannapiran et.al.|[2308.01125](http://arxiv.org/abs/2308.01125)|null|
|**2023-08-02**|**Preliminary Design of the Dragonfly Navigation Filter**|Ben Schilling et.al.|[2307.13513](http://arxiv.org/abs/2307.13513)|null|
|**2023-07-19**|**Optimizing the extended Fourier Mellin Transformation Algorithm**|Wenqing Jiang et.al.|[2307.10015](http://arxiv.org/abs/2307.10015)|**[link](https://github.com/star-center/o-efmt)**|
|**2023-12-26**|**Tightly-Coupled LiDAR-Visual SLAM Based on Geometric Features for Mobile Agents**|Ke Cao et.al.|[2307.07763](http://arxiv.org/abs/2307.07763)|null|
|**2023-09-12**|**Event-based Stereo Visual Odometry with Native Temporal Resolution via Continuous-time Gaussian Process Regression**|Jianeng Wang et.al.|[2306.01188](http://arxiv.org/abs/2306.01188)|null|
|**2023-07-06**|**OSPC: Online Sequential Photometric Calibration**|Jawad Haidar et.al.|[2305.17673](http://arxiv.org/abs/2305.17673)|null|
|**2023-05-15**|**Event Camera-based Visual Odometry for Dynamic Motion Tracking of a Legged Robot Using Adaptive Time Surface**|Shifan Zhu et.al.|[2305.08962](http://arxiv.org/abs/2305.08962)|null|
|**2023-09-12**|**Transformer-based model for monocular visual odometry: a video understanding approach**|André O. Françani et.al.|[2305.06121](http://arxiv.org/abs/2305.06121)|**[link](https://github.com/aofrancani/tsformer-vo)**|
|**2023-04-29**|**Modality-invariant Visual Odometry for Embodied Vision**|Marius Memmel et.al.|[2305.00348](http://arxiv.org/abs/2305.00348)|**[link](https://github.com/memmelma/vo-transformer)**|
|**2023-04-21**|**FSNet: Redesign Self-Supervised MonoDepth for Full-Scale Depth Prediction for Autonomous Driving**|Yuxuan Liu et.al.|[2304.10719](http://arxiv.org/abs/2304.10719)|null|
|**2023-07-08**|**Visual-LiDAR Odometry and Mapping with Monocular Scale Correction and Visual Bootstrapping**|Hanyu Cai et.al.|[2304.08978](http://arxiv.org/abs/2304.08978)|null|
|**2023-04-12**|**SiLK -- Simple Learned Keypoints**|Pierre Gleize et.al.|[2304.06194](http://arxiv.org/abs/2304.06194)|**[link](https://github.com/facebookresearch/silk)**|
|**2023-04-11**|**ClusterFusion: Real-time Relative Positioning and Dense Reconstruction for UAV Cluster**|Yifei Dong et.al.|[2304.04943](http://arxiv.org/abs/2304.04943)|null|
|**2023-03-21**|**Learning a Depth Covariance Function**|Eric Dexheimer et.al.|[2303.12157](http://arxiv.org/abs/2303.12157)|null|
|**2023-03-21**|**Online Learning of Wheel Odometry Correction for Mobile Robots with Attention-based Neural Network**|Alessandro Navone et.al.|[2303.11725](http://arxiv.org/abs/2303.11725)|null|
|**2023-03-20**|**VR-SLAM: A Visual-Range Simultaneous Localization and Mapping System using Monocular Camera and Ultra-wideband Sensors**|Thien Hoang Nguyen et.al.|[2303.10903](http://arxiv.org/abs/2303.10903)|null|
|**2023-03-17**|**CoVIO: Online Continual Learning for Visual-Inertial Odometry**|Niclas Vödisch et.al.|[2303.10149](http://arxiv.org/abs/2303.10149)|**[link](https://github.com/robot-learning-freiburg/CL-SLAM)**|
|**2023-03-15**|**UMS-VINS: United Monocular-Stereo Features for Visual-Inertial Tightly Coupled Odometry**|Chaoyang Jiang et.al.|[2303.08550](http://arxiv.org/abs/2303.08550)|null|
|**2023-03-13**|**Discovering Multiple Algorithm Configurations**|Leonid Keselman et.al.|[2303.07434](http://arxiv.org/abs/2303.07434)|null|
|**2023-03-09**|**Virtual Inverse Perspective Mapping for Simultaneous Pose and Motion Estimation**|Masahiro Hirano et.al.|[2303.05192](http://arxiv.org/abs/2303.05192)|null|
|**2023-07-25**|**Stereo Event-based Visual-Inertial Odometry**|Kunfeng Wang et.al.|[2303.05086](http://arxiv.org/abs/2303.05086)|**[link](https://github.com/wkunfeng/sevio)**|
|**2023-03-07**|**Long Distance GNSS-Denied Visual Inertial Navigation for Autonomous Fixed Wing Unmanned Air Vehicles: SO(3) Manifold Filter based on Virtual Vision Sensor**|Eduardo Gallo et.al.|[2303.03804](http://arxiv.org/abs/2303.03804)|null|
|**2023-03-03**|**Lightweight, Uncertainty-Aware Conformalized Visual Odometry**|Alex C. Stutts et.al.|[2303.02207](http://arxiv.org/abs/2303.02207)|null|
|**2023-02-24**|**FLSea: Underwater Visual-Inertial and Stereo-Vision Forward-Looking Datasets**|Yelena Randall et.al.|[2302.12772](http://arxiv.org/abs/2302.12772)|null|
|**2023-02-27**|**CP+: Camera Poses Augmentation with Large-scale LiDAR Maps**|Jiadi Cui et.al.|[2302.12198](http://arxiv.org/abs/2302.12198)|null|
|**2023-02-19**|**EdgeVO: An Efficient and Accurate Edge-based Visual Odometry**|Hui Zhao et.al.|[2302.09493](http://arxiv.org/abs/2302.09493)|null|
|**2023-01-27**|**HDPV-SLAM: Hybrid Depth-augmented Panoramic Visual SLAM for Mobile Mapping System with Tilted LiDAR and Panoramic Visual Camera**|Mostafa Ahmadi et.al.|[2301.11823v1](http://arxiv.org/abs/2301.11823v1)|null|
|**2023-01-26**|**Distributed Optimization Methods for Multi-Robot Systems: Part I -- A Tutorial**|Ola Shorinwa et.al.|[2301.11313v1](http://arxiv.org/abs/2301.11313v1)|null|
|**2023-01-24**|**Generalized Object Search**|Kaiyu Zheng et.al.|[2301.10121v1](http://arxiv.org/abs/2301.10121v1)|null|
|**2023-01-22**|**Improving Autonomous Vehicle Mapping and Navigation in Work Zones Using Crowdsourcing Vehicle Trajectories**|Hanlin Chen et.al.|[2301.09194v1](http://arxiv.org/abs/2301.09194v1)|null|
|**2023-01-21**|**Dense RGB SLAM with Neural Implicit Maps**|Heng Li et.al.|[2301.08930v1](http://arxiv.org/abs/2301.08930v1)|null|
|**2023-01-18**|**Extended FastSLAM Using Cellular Multipath Component Delays and Angular Information**|Junshi Chen et.al.|[2301.07560v1](http://arxiv.org/abs/2301.07560v1)|null|
|**2023-01-17**|**COVINS-G: A Generic Back-end for Collaborative Visual-Inertial SLAM**|Manthan Patel et.al.|[2301.07147v1](http://arxiv.org/abs/2301.07147v1)|null|
|**2023-01-31**|**Swarm-SLAM : Sparse Decentralized Collaborative Simultaneous Localization and Mapping Framework for Multi-Robot Systems**|Pierre-Yves Lajoie et.al.|[2301.06230v2](http://arxiv.org/abs/2301.06230v2)|**[link](https://github.com/mistlab/swarm-slam)**|
|**2023-01-13**|**A LiDAR-Inertial-Visual SLAM System with Loop Detection**|Kangcheng Liu et.al.|[2301.05604v1](http://arxiv.org/abs/2301.05604v1)|null|
|**2023-01-11**|**AdaptSLAM: Edge-Assisted Adaptive SLAM with Resource Constraints via Uncertainty Minimization**|Ying Chen et.al.|[2301.04620v1](http://arxiv.org/abs/2301.04620v1)|**[link](https://github.com/i3tyc/adaptslam)**|
|**2023-01-12**|**TBV Radar SLAM -- trust but verify loop candidates**|Daniel Adolfsson et.al.|[2301.04397v2](http://arxiv.org/abs/2301.04397v2)|null|
|**2022-12-31**|**Digital Twin-Enabled Domain Adaptation for Zero-Touch UAV Networks: Survey and Challenges**|Maxwell McManus et.al.|[2301.03359v1](http://arxiv.org/abs/2301.03359v1)|null|
|**2023-01-09**|**Motion Addition and Motion Optimization**|Liqun Qi et.al.|[2301.03174v1](http://arxiv.org/abs/2301.03174v1)|null|
|**2023-01-08**|**Towards Open World NeRF-Based SLAM**|Daniil Lisus et.al.|[2301.03102v1](http://arxiv.org/abs/2301.03102v1)|null|
|**2023-01-06**|**CyberLoc: Towards Accurate Long-term Visual Localization**|Liu Liu et.al.|[2301.02403v1](http://arxiv.org/abs/2301.02403v1)|null|
|**2023-01-03**|**LunarNav: Crater-based Localization for Long-range Autonomous Lunar Rover Navigation**|Shreyansh Daftry et.al.|[2301.01350](http://arxiv.org/abs/2301.01350)|null|
|**2022-12-31**|**4Seasons: Benchmarking Visual SLAM and Long-Term Localization for Autonomous Driving in Challenging Conditions**|Patrick Wenzel et.al.|[2301.01147](http://arxiv.org/abs/2301.01147)|null|
|**2023-01-03**|**BS3D: Building-scale 3D Reconstruction from RGB-D Images**|Janne Mustaniemi et.al.|[2301.01057v1](http://arxiv.org/abs/2301.01057v1)|null|
|**2023-01-10**|**An Event-based Algorithm for Simultaneous 6-DOF Camera Pose Tracking and Mapping**|Masoud Dayani Najafabadi et.al.|[2301.00618v2](http://arxiv.org/abs/2301.00618v2)|null|
|**2022-12-25**|**A Combined Approach Toward Consistent Reconstructions of Indoor Spaces Based on 6D RGB-D Odometry and KinectFusion**|Nadia Figueroa et.al.|[2212.14772](http://arxiv.org/abs/2212.14772)|null|
|**2022-12-29**|**An Enhanced LiDAR-Inertial SLAM System for Robotics Localization and Mapping**|Kangcheng Liu et.al.|[2212.14209v1](http://arxiv.org/abs/2212.14209v1)|**[link](https://github.com/KangchengLiu/slam_resources)**|
|**2022-12-27**|**Clock and Orientation-Robust Simultaneous Radio Localization and Mapping at Millimeter Wave Bands**|Felipe Gómez-Cuba et.al.|[2212.13477v1](http://arxiv.org/abs/2212.13477v1)|**[link](https://github.com/gomezcuba/castro-5g)**|
|**2023-04-14**|**ESVIO: Event-based Stereo Visual Inertial Odometry**|Peiyu Chen et.al.|[2212.13184](http://arxiv.org/abs/2212.13184)|**[link](https://github.com/arclab-hku/event_based_vo-vio-slam)**|
|**2022-12-24**|**A Comprehensive Review on Autonomous Navigation**|Saeid Nahavandi et.al.|[2212.12808v1](http://arxiv.org/abs/2212.12808v1)|null|
|**2022-12-23**|**Radio SLAM for 6G Systems at THz Frequencies: Design and Experimental Validation**|Marina Lotti et.al.|[2212.12388v1](http://arxiv.org/abs/2212.12388v1)|null|
|**2022-12-23**|**Implementation of a Blind navigation method in outdoors/indoors areas**|Mohammad Javadian Farzaneh et.al.|[2212.12185v1](http://arxiv.org/abs/2212.12185v1)|null|
|**2022-12-22**|**S-Graphs+: Real-time Localization and Mapping leveraging Hierarchical Representations**|Hriday Bavle et.al.|[2212.11770v1](http://arxiv.org/abs/2212.11770v1)|**[link](https://github.com/snt-arg/s_graphs_docker)**|
|**2022-12-22**|**Active SLAM: A Review On Last Decade**|Muhammad Farhan Ahmed et.al.|[2212.11654v1](http://arxiv.org/abs/2212.11654v1)|null|
|**2022-12-27**|**Motion, Unit Dual Quaternion and Motion Optimization**|Liqun Qi et.al.|[2212.11593v2](http://arxiv.org/abs/2212.11593v2)|null|
|**2022-12-22**|**Vision-Based Environmental Perception for Autonomous Driving**|Fei Liu et.al.|[2212.11453v1](http://arxiv.org/abs/2212.11453v1)|null|
|**2022-12-19**|**Mu $^{2}$ SLAM: Multitask, Multilingual Speech and Language Models**|Yong Cheng et.al.|[2212.09553v1](http://arxiv.org/abs/2212.09553v1)|null|
|**2022-12-16**|**Cartographer_glass: 2D Graph SLAM Framework using LiDAR for Glass Environments**|Lasitha Weerakoon et.al.|[2212.08633v1](http://arxiv.org/abs/2212.08633v1)|null|
|**2022-12-16**|**rWiFiSLAM: Effective WiFi Ranging based SLAM System in Ambient Environments**|Bo Wei et.al.|[2212.08418v1](http://arxiv.org/abs/2212.08418v1)|null|
|**2023-03-02**|**AirVO: An Illumination-Robust Point-Line Visual Odometry**|Kuan Xu et.al.|[2212.07595](http://arxiv.org/abs/2212.07595)|**[link](https://github.com/xukuanHIT/AirVO)**|
|**2022-12-14**|**Autonomous Vehicle Navigation with LIDAR using Path Planning**|Rahul M K et.al.|[2212.07155](http://arxiv.org/abs/2212.07155)|null|
|**2022-12-14**|**RIS-Enabled and Access-Point-Free Simultaneous Radio Localization and Mapping**|Hyowon Kim et.al.|[2212.07141v1](http://arxiv.org/abs/2212.07141v1)|null|
|**2022-12-13**|**Know What You Don't Know: Consistency in Sliding Window Filtering with Unobservable States Applied to Visual-Inertial SLAM (Extended Version)**|Daniil Lisus et.al.|[2212.06923v1](http://arxiv.org/abs/2212.06923v1)|null|
|**2022-12-13**|**SST: Real-time End-to-end Monocular 3D Reconstruction via Sparse Spatial-Temporal Guidance**|Chenyangguang Zhang et.al.|[2212.06524v1](http://arxiv.org/abs/2212.06524v1)|null|
|**2022-12-13**|**Localization and Navigation System for Indoor Mobile Robot**|Yanbaihui Liu et.al.|[2212.06391v1](http://arxiv.org/abs/2212.06391v1)|null|
|**2022-12-12**|**Evaluation of RGB-D SLAM in Large Indoor Environments**|Kirill Muravyev et.al.|[2212.05980v1](http://arxiv.org/abs/2212.05980v1)|null|
|**2022-12-19**|**A Light-Weight LiDAR-Inertial SLAM System with Loop Closing**|Kangcheng Liu et.al.|[2212.05743v2](http://arxiv.org/abs/2212.05743v2)|**[link](https://github.com/KangchengLiu/deep-learning-localization-mapping)**|
|**2022-12-12**|**An Integrated LiDAR-SLAM System for Complex Environment with Noisy Point Clouds**|Kangcheng Liu et.al.|[2212.05705v1](http://arxiv.org/abs/2212.05705v1)|**[link](https://github.com/KangchengLiu/deep-learning-localization-mapping)**|
|**2022-12-09**|**SLAM for Visually Impaired People: A Survey**|Marziyeh Bamdad et.al.|[2212.04745v1](http://arxiv.org/abs/2212.04745v1)|null|
|**2022-12-09**|**Ego-Body Pose Estimation via Ego-Head Pose Estimation**|Jiaman Li et.al.|[2212.04636v1](http://arxiv.org/abs/2212.04636v1)|null|
|**2022-12-06**|**Receding Horizon Planning with Rule Hierarchies for Autonomous Vehicles**|Sushant Veer et.al.|[2212.03323v1](http://arxiv.org/abs/2212.03323v1)|null|
|**2022-12-06**|**PRISM: Probabilistic Real-Time Inference in Spatial World Models**|Atanas Mirchev et.al.|[2212.02988v1](http://arxiv.org/abs/2212.02988v1)|null|
|**2022-12-06**|**RGB-L: Enhancing Indirect Visual SLAM using LiDAR-based Dense Depth Maps**|Florian Sauerbeck et.al.|[2212.02085v2](http://arxiv.org/abs/2212.02085v2)|**[link](https://github.com/tumftm/orb_slam3_rgbl)**|
|**2022-12-05**|**DL-SLOT: Dynamic LiDAR SLAM and object tracking based on collaborative graph optimization**|Xuebo Tian et.al.|[2212.02077v1](http://arxiv.org/abs/2212.02077v1)|null|
|**2022-12-05**|**ObjectMatch: Robust Registration using Canonical Object Correspondences**|Can Gümeli et.al.|[2212.01985v1](http://arxiv.org/abs/2212.01985v1)|null|
|**2022-12-02**|**Sparse SPN: Depth Completion from Sparse Keypoints**|Yuqun Wu et.al.|[2212.00987v1](http://arxiv.org/abs/2212.00987v1)|null|
|**2022-12-01**|**maplab 2.0 -- A Modular and Multi-Modal Mapping Framework**|Andrei Cramariuc et.al.|[2212.00654v1](http://arxiv.org/abs/2212.00654v1)|**[link](https://github.com/ethz-asl/maplab)**|
|**2022-12-01**|**AstroSLAM: Autonomous Monocular Navigation in the Vicinity of a Celestial Small Body -- Theory and Experiments**|Mehregan Dor et.al.|[2212.00350v1](http://arxiv.org/abs/2212.00350v1)|null|
|**2022-11-30**|**MVRackLay: Monocular Multi-View Layout Estimation for Warehouse Racks and Shelves**|Pranjali Pathre et.al.|[2211.16882v1](http://arxiv.org/abs/2211.16882v1)|null|
|**2022-11-29**|**PatchMatch-Stereo-Panorama, a fast dense reconstruction from 360° video images**|Hartmut Surmann et.al.|[2211.16266v1](http://arxiv.org/abs/2211.16266v1)|**[link](https://github.com/roblabwh/patchmatch)**|
|**2022-11-29**|**MmWave Mapping and SLAM for 5G and Beyond**|Yu Ge et.al.|[2211.16024v1](http://arxiv.org/abs/2211.16024v1)|null|
|**2022-11-28**|**Safety-quantifiable Line Feature-based Monocular Visual Localization with 3D Prior Map**|Xi Zheng et.al.|[2211.15127](http://arxiv.org/abs/2211.15127)|null|
|**2022-11-29**|**BALF: Simple and Efficient Blur Aware Local Feature Detector**|Zhenjun Zhao et.al.|[2211.14731v2](http://arxiv.org/abs/2211.14731v2)|null|
|**2022-11-27**|**Development of a Modular Real-time Shared-control System for a Smart Wheelchair**|Vaishanth Ramaraj et.al.|[2211.14711v1](http://arxiv.org/abs/2211.14711v1)|null|
|**2022-11-26**|**A1 SLAM: Quadruped SLAM using the A1's Onboard Sensors**|Jerred Chen et.al.|[2211.14432v1](http://arxiv.org/abs/2211.14432v1)|**[link](https://github.com/jerredchen/a1_slam)**|
|**2022-11-23**|**ActiveRMAP: Radiance Field for Active Mapping And Planning**|Huangying Zhan et.al.|[2211.12656v1](http://arxiv.org/abs/2211.12656v1)|null|
|**2022-11-22**|**Vision-based localization methods under GPS-denied conditions**|Zihao Lu et.al.|[2211.11988v1](http://arxiv.org/abs/2211.11988v1)|null|
|**2022-11-21**|**Towards Live 3D Reconstruction from Wearable Video: An Evaluation of V-SLAM, NeRF, and Videogrammetry Techniques**|David Ramirez et.al.|[2211.11836v1](http://arxiv.org/abs/2211.11836v1)|null|
|**2022-11-21**|**ESLAM: Efficient Dense SLAM System Based on Hybrid Representation of Signed Distance Fields**|Mohammad Mahdi Johari et.al.|[2211.11704v1](http://arxiv.org/abs/2211.11704v1)|null|
|**2022-11-24**|**Data Fusion for Multipath-Based SLAM: Combing Information from Multiple Propagation Paths**|Erik Leitinger et.al.|[2211.09241v2](http://arxiv.org/abs/2211.09241v2)|null|
|**2022-11-16**|**Self-supervised Egomotion and Depth Learning via Bi-directional Coarse-to-Fine Scale Recovery**|Hao Qu et.al.|[2211.08904v1](http://arxiv.org/abs/2211.08904v1)|null|
|**2022-11-20**|**Detecting Line Segments in Motion-blurred Images with Events**|Huai Yu et.al.|[2211.07365v2](http://arxiv.org/abs/2211.07365v2)|**[link](https://github.com/lh9171338/FE-LSD)**|
|**2022-11-13**|**Automatic Eye-in-Hand Calibration using EKF**|Aditya Ramakrishnan et.al.|[2211.06881v1](http://arxiv.org/abs/2211.06881v1)|null|
|**2022-11-12**|**Active View Planning for Visual SLAM in Outdoor Environments Based on Continuous Information Modeling**|Zhihao Wang et.al.|[2211.06557v1](http://arxiv.org/abs/2211.06557v1)|null|
|**2022-11-11**|**Multi-domain Cooperative SLAM: The Enabler for Integrated Sensing and Communications**|Jie Yang et.al.|[2211.05982v1](http://arxiv.org/abs/2211.05982v1)|null|
|**2022-11-10**|**Online Stochastic Variational Gaussian Process Mapping for Large-Scale SLAM in Real Time**|Ignacio Torroba et.al.|[2211.05601v1](http://arxiv.org/abs/2211.05601v1)|**[link](https://github.com/ignaciotb/uwexploration)**|
|**2022-11-07**|**When Geometry is not Enough: Using Reflector Markers in Lidar SLAM**|Gerhard Kurz et.al.|[2211.03484v1](http://arxiv.org/abs/2211.03484v1)|null|
|**2022-11-07**|**Detecting Invalid Map Merges in Lifelong SLAM**|Matthias Holoch et.al.|[2211.03423v1](http://arxiv.org/abs/2211.03423v1)|null|
|**2022-11-06**|**Wheel-SLAM: Simultaneous Localization and Terrain Mapping Using One Wheel-mounted IMU**|Yibin Wu et.al.|[2211.03174v1](http://arxiv.org/abs/2211.03174v1)|**[link](https://github.com/i2nav-whu/wheel-slam)**|
|**2022-11-07**|**Lidar-level localization with radar? The CFEAR approach to accurate, fast and robust large-scale radar odometry in diverse environments**|Daniel Adolfsson et.al.|[2211.02445v2](http://arxiv.org/abs/2211.02445v2)|**[link](https://github.com/dan11003/cfear_evaluation)**|
|**2022-11-03**|**DyOb-SLAM : Dynamic Object Tracking SLAM System**|Rushmian Annoy Wadud et.al.|[2211.01941v1](http://arxiv.org/abs/2211.01941v1)|null|
|**2022-11-03**|**Enhanced Visual Feedback with Decoupled Viewpoint Control in Immersive Humanoid Robot Teleoperation using SLAM**|Yang Chen et.al.|[2211.01749v1](http://arxiv.org/abs/2211.01749v1)|null|
|**2022-11-04**|**$D^2$ SLAM: Decentralized and Distributed Collaborative Visual-inertial SLAM System for Aerial Swarm**|Hao Xu et.al.|[2211.01538v2](http://arxiv.org/abs/2211.01538v2)|**[link](https://github.com/hkust-aerial-robotics/d2slam)**|
|**2022-11-02**|**Semantic SuperPoint: A Deep Semantic Descriptor**|Gabriel S. Gama et.al.|[2211.01098v1](http://arxiv.org/abs/2211.01098v1)|**[link](https://github.com/gabriel-sgama/semantic-superpoint)**|
|**2022-11-02**|**Ambiguity-Aware Multi-Object Pose Optimization for Visually-Assisted Robot Manipulation**|Myung-Hwan Jeon et.al.|[2211.00960v1](http://arxiv.org/abs/2211.00960v1)|**[link](https://github.com/rpmsnu/prima6d)**|
|**2022-10-31**|**Mapping Extended Landmarks for Radar SLAM**|Shuai Sun et.al.|[2210.17207v1](http://arxiv.org/abs/2210.17207v1)|null|
|**2022-10-25**|**MAROAM: Map-based Radar SLAM through Two-step Feature Selection**|Dequan Wang et.al.|[2210.13797v1](http://arxiv.org/abs/2210.13797v1)|null|
|**2022-10-25**|**S3E: A Large-scale Multimodal Dataset for Collaborative SLAM**|Dapeng Feng et.al.|[2210.13723v1](http://arxiv.org/abs/2210.13723v1)|**[link](https://github.com/pengyu-team/s3e)**|
|**2022-10-24**|**NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields**|Antoni Rosinol et.al.|[2210.13641v1](http://arxiv.org/abs/2210.13641v1)|**[link](https://github.com/ToniRV/NeRF-SLAM)**|
|**2022-10-24**|**Compact simultaneous label-free autofluorescence multi-harmonic (SLAM) microscopy for user-friendly photodamage-monitored imaging**|Geng Wang et.al.|[2210.13556v1](http://arxiv.org/abs/2210.13556v1)|null|
|**2022-10-28**|**VP-SLAM: A Monocular Real-time Visual SLAM with Points, Lines and Vanishing Points**|Andreas Georgis et.al.|[2210.12756v2](http://arxiv.org/abs/2210.12756v2)|null|
|**2022-10-22**|**SLAM: Semantic Learning based Activation Map for Weakly Supervised Semantic Segmentation**|Junliang Chen et.al.|[2210.12417v1](http://arxiv.org/abs/2210.12417v1)|null|
|**2022-10-21**|**DCL-SLAM: A Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm**|Shipeng Zhong et.al.|[2210.11978v1](http://arxiv.org/abs/2210.11978v1)|**[link](https://github.com/pengyu-team/dcl-slam)**|
|**2022-10-21**|**Motion Primitives Based Kinodynamic RRT for Autonomous Vehicle Navigation in Complex Environments**|Shubham Kedia et.al.|[2210.11652v1](http://arxiv.org/abs/2210.11652v1)|null|
|**2022-10-22**|**Visual SLAM: What are the Current Trends and What to Expect?**|Ali Tourani et.al.|[2210.10491v2](http://arxiv.org/abs/2210.10491v2)|null|
|**2022-10-18**|**Split-KalmanNet: A Robust Model-Based Deep Learning Approach for SLAM**|Geon Choi et.al.|[2210.09636v1](http://arxiv.org/abs/2210.09636v1)|null|
|**2022-10-16**|**D2SLAM: Semantic visual SLAM based on the influence of Depth for Dynamic environments**|Ayman Beghdadi et.al.|[2210.08647v1](http://arxiv.org/abs/2210.08647v1)|null|
|**2022-10-16**|**Indoor Smartphone SLAM with Learned Echoic Location Features**|Wenjie Luo et.al.|[2210.08493v1](http://arxiv.org/abs/2210.08493v1)|null|
|**2022-10-15**|**Self-Improving SLAM in Dynamic Environments: Learning When to Mask**|Adrian Bojko et.al.|[2210.08350v1](http://arxiv.org/abs/2210.08350v1)|**[link](https://github.com/adrianbojko/consinv-dataset)**|
|**2022-10-13**|**Design and Evaluation of a Generic Visual SLAM Framework for Multi-Camera Systems**|Pushyami Kaveti et.al.|[2210.07315v1](http://arxiv.org/abs/2210.07315v1)|null|
|**2022-10-12**|**RING++: Roto-translation Invariant Gram for Global Localization on a Sparse Scan Map**|Xuecheng Xu et.al.|[2210.05984v1](http://arxiv.org/abs/2210.05984v1)|**[link](https://github.com/MaverickPeter/MR_SLAM)**|
|**2022-10-11**|**Observability Analysis of Graph SLAM-Based Joint Calibration of Multiple Microphone Arrays and Sound Source Localization**|Yuanzheng He et.al.|[2210.05600v1](http://arxiv.org/abs/2210.05600v1)|null|
|**2022-10-11**|**Autonomous Asteroid Characterization Through Nanosatellite Swarming**|Kaitlin Dennison et.al.|[2210.05518v1](http://arxiv.org/abs/2210.05518v1)|null|
|**2022-10-11**|**DeepMLE: A Robust Deep Maximum Likelihood Estimator for Two-view Structure from Motion**|Yuxi Xiao et.al.|[2210.05517v1](http://arxiv.org/abs/2210.05517v1)|null|
|**2022-10-11**|**Multi-Object Navigation with dynamically learned neural implicit representations**|Pierre Marza et.al.|[2210.05129v1](http://arxiv.org/abs/2210.05129v1)|null|
|**2022-10-12**|**Spectral Sparsification for Communication-Efficient Collaborative Rotation and Translation Estimation**|Yulun Tian et.al.|[2210.05020v2](http://arxiv.org/abs/2210.05020v2)|null|
|**2022-10-10**|**Using Detection, Tracking and Prediction in Visual SLAM to Achieve Real-time Semantic Mapping of Dynamic Scenarios**|Xingyu Chen et.al.|[2210.04562v1](http://arxiv.org/abs/2210.04562v1)|null|
|**2022-10-09**|**Fusing Event-based Camera and Radar for SLAM Using Spiking Neural Networks with Continual STDP Learning**|Ali Safa et.al.|[2210.04236v1](http://arxiv.org/abs/2210.04236v1)|null|
|**2022-10-06**|**SCORE: A Second-Order Conic Initialization for Range-Aided SLAM**|Alan Papalia et.al.|[2210.03177v1](http://arxiv.org/abs/2210.03177v1)|**[link](https://github.com/marineroboticsgroup/score)**|
|**2022-10-06**|**Feature-Realistic Neural Fusion for Real-Time, Open Set Scene Understanding**|Kirill Mazur et.al.|[2210.03043v1](http://arxiv.org/abs/2210.03043v1)|null|
|**2022-10-06**|**Feasibility on Detecting Door Slamming towards Monitoring Early Signs of Domestic Violence**|Osian Morgan et.al.|[2210.02642v1](http://arxiv.org/abs/2210.02642v1)|null|
|**2022-10-05**|**MOTSLAM: MOT-assisted monocular dynamic SLAM using single-view depth estimation**|Hanwei Zhang et.al.|[2210.02038v1](http://arxiv.org/abs/2210.02038v1)|null|
|**2022-10-04**|**O2S: Open-source open shuttle**|Nwankwo Linus et.al.|[2210.01627v1](http://arxiv.org/abs/2210.01627v1)|null|
|**2022-10-04**|**Wi-Closure: Reliable and Efficient Search of Inter-robot Loop Closures Using Wireless Sensing**|Weiying Wang et.al.|[2210.01320v1](http://arxiv.org/abs/2210.01320v1)|null|
|**2022-10-03**|**Probabilistic Volumetric Fusion for Dense Monocular SLAM**|Antoni Rosinol et.al.|[2210.01276v1](http://arxiv.org/abs/2210.01276v1)|null|
|**2022-10-03**|**DRACo-SLAM: Distributed Robust Acoustic Communication-efficient SLAM for Imaging Sonar Equipped Underwater Robot Teams**|John McConnell et.al.|[2210.00867v1](http://arxiv.org/abs/2210.00867v1)|**[link](https://github.com/jake3991/draco-slam)**|
|**2022-10-03**|**A Benchmark for Multi-Modal Lidar SLAM with Ground Truth in GNSS-Denied Environments**|Ha Sier et.al.|[2210.00812v1](http://arxiv.org/abs/2210.00812v1)|**[link](https://github.com/tiers/tiers-lidars-dataset-enhanced)**|
|**2022-10-01**|**Det-SLAM: A semantic visual SLAM for highly dynamic scenes using Detectron2**|Ali Eslamian et.al.|[2210.00278v1](http://arxiv.org/abs/2210.00278v1)|null|
|**2022-09-30**|**PyPose: A Library for Robot Learning with Physics-based Optimization**|Chen Wang et.al.|[2209.15428v1](http://arxiv.org/abs/2209.15428v1)|**[link](https://github.com/pypose/pypose)**|
|**2022-09-29**|**DirectTracker: 3D Multi-Object Tracking Using Direct Image Alignment and Photometric Bundle Adjustment**|Mariia Gladkova et.al.|[2209.14965v1](http://arxiv.org/abs/2209.14965v1)|null|
|**2022-09-28**|**Robust Incremental Smoothing and Mapping (riSAM)**|Daniel McGann et.al.|[2209.14359v1](http://arxiv.org/abs/2209.14359v1)|null|
|**2022-09-27**|**Orbeez-SLAM: A Real-time Monocular Visual SLAM with ORB Features and NeRF-realized Mapping**|Chi-Ming Chung et.al.|[2209.13274v1](http://arxiv.org/abs/2209.13274v1)|**[link](https://github.com/MarvinChung/Orbeez-slam)**|
|**2022-09-24**|**Graph Neural Networks for Multi-Robot Active Information Acquisition**|Mariliza Tzes et.al.|[2209.12091v1](http://arxiv.org/abs/2209.12091v1)|null|
|**2022-09-24**|**Closing the Loop: Graph Networks to Unify Semantic Objects and Visual Features for Multi-object Scenes**|Jonathan J. Y. Kim et.al.|[2209.11894v1](http://arxiv.org/abs/2209.11894v1)|null|
|**2022-09-23**|**involve-MI: Informative Planning with High-Dimensional Non-Parametric Beliefs**|Gilad Rotman et.al.|[2209.11591v1](http://arxiv.org/abs/2209.11591v1)|null|
|**2022-09-23**|**Automatic Sign Reading and Localization for Semantic Mapping with an Office Robot**|David Balaban et.al.|[2209.11432v1](http://arxiv.org/abs/2209.11432v1)|null|
|**2022-09-22**|**SQ-SLAM: Monocular Semantic SLAM Based on Superquadric Object Representation**|Xiao Han et.al.|[2209.10817v1](http://arxiv.org/abs/2209.10817v1)|null|
|**2022-09-22**|**Acoustic SLAM based on the Direction-of-Arrival and the Direct-to-Reverberant Energy Ratio**|Wenhao Qiu et.al.|[2209.10726v1](http://arxiv.org/abs/2209.10726v1)|null|
|**2022-09-21**|**Visual Localization and Mapping in Dynamic and Changing Environments**|João Carlos Virgolino Soares et.al.|[2209.10710v1](http://arxiv.org/abs/2209.10710v1)|null|
|**2022-09-20**|**Uncertainty-Aware Tightly-Coupled GPS Fused LIO-SLAM**|Sabir Hossain et.al.|[2209.10047v1](http://arxiv.org/abs/2209.10047v1)|null|
|**2022-09-20**|**WGICP: Differentiable Weighted GICP-Based Lidar Odometry**|Sanghyun Son et.al.|[2209.09777v1](http://arxiv.org/abs/2209.09777v1)|null|
|**2022-09-20**|**PADLoC: LiDAR-Based Deep Loop Closure Detection and Registration using Panoptic Attention**|José Arce et.al.|[2209.09699v1](http://arxiv.org/abs/2209.09699v1)|**[link](https://github.com/robot-learning-freiburg/PADLoC)**|
|**2022-09-19**|**MeSLAM: Memory Efficient SLAM based on Neural Fields**|Evgenii Kruzhkov et.al.|[2209.09357v1](http://arxiv.org/abs/2209.09357v1)|null|
|**2022-09-19**|**LMBAO: A Landmark Map for Bundle Adjustment Odometry in LiDAR SLAM**|Letian Zhang et.al.|[2209.08810v1](http://arxiv.org/abs/2209.08810v1)|null|
|**2022-09-18**|**HGI-SLAM: Loop Closure With Human and Geometric Importance Features**|Shuhul Mujoo et.al.|[2209.08608v1](http://arxiv.org/abs/2209.08608v1)|null|
|**2022-09-18**|**Data-driven Loop Closure Detection in Bathymetric Point Clouds for Underwater SLAM**|Jiarui Tan et.al.|[2209.08578v1](http://arxiv.org/abs/2209.08578v1)|**[link](https://github.com/tjr16/bathy_nn_learning)**|
|**2022-09-17**|**DytanVO: Joint Refinement of Visual Odometry and Motion Segmentation in Dynamic Environments**|Shihao Shen et.al.|[2209.08430v1](http://arxiv.org/abs/2209.08430v1)|**[link](https://github.com/geniussh/dytanvo)**|
|**2022-09-17**|**OA-SLAM: Leveraging Objects for Camera Relocalization in Visual SLAM**|Matthieu Zins et.al.|[2209.08338v1](http://arxiv.org/abs/2209.08338v1)|null|
|**2022-09-17**|**PlaneSLAM: Plane-based LiDAR SLAM for Motion Planning in Structured 3D Environments**|Adam Dai et.al.|[2209.08248v1](http://arxiv.org/abs/2209.08248v1)|**[link](https://github.com/stanford-navlab/planeslam)**|
|**2022-09-16**|**ViWiD: Leveraging WiFi for Robust and Resource-Efficient SLAM**|Aditya Arun et.al.|[2209.08091v1](http://arxiv.org/abs/2209.08091v1)|null|
|**2022-09-16**|**iDF-SLAM: End-to-End RGB-D SLAM with Neural Implicit Mapping and Deep Feature Tracking**|Yuhang Ming et.al.|[2209.07919v1](http://arxiv.org/abs/2209.07919v1)|null|
|**2022-09-16**|**TwistSLAM++: Fusing multiple modalities for accurate dynamic semantic SLAM**|Mathieu Gonzalez et.al.|[2209.07888v1](http://arxiv.org/abs/2209.07888v1)|null|
|**2022-09-15**|**Landmark Management in the Application of Radar SLAM**|Shuai Sun et.al.|[2209.07199v1](http://arxiv.org/abs/2209.07199v1)|null|
|**2022-09-15**|**PROB-SLAM: Real-time Visual SLAM Based on Probabilistic Graph Optimization**|Xianwei Meng et.al.|[2209.07061v1](http://arxiv.org/abs/2209.07061v1)|null|
|**2022-09-14**|**Semantic Visual Simultaneous Localization and Mapping: A Survey**|Kaiqi Chen et.al.|[2209.06428v1](http://arxiv.org/abs/2209.06428v1)|null|
|**2022-09-13**|**Optimizing SLAM Evaluation Footprint Through Dynamic Range Coverage Analysis of Datasets**|Islam Ali et.al.|[2209.06316v1](http://arxiv.org/abs/2209.06316v1)|null|
|**2022-09-12**|**A Review on Visual-SLAM: Advancements from Geometric Modelling to Learning-based Semantic Scene Understanding**|Tin Lai et.al.|[2209.05222v1](http://arxiv.org/abs/2209.05222v1)|null|
|**2022-09-12**|**Attitude-Guided Loop Closure for Cameras with Negative Plane**|Ze Wang et.al.|[2209.05167v1](http://arxiv.org/abs/2209.05167v1)|**[link](https://github.com/flysoaryun/lf-vio-loop)**|
|**2022-09-09**|**General Place Recognition Survey: Towards the Real-world Autonomy Age**|Peng Yin et.al.|[2209.04497v1](http://arxiv.org/abs/2209.04497v1)|**[link](https://github.com/MetaSLAM/GPRS)**|
|**2022-09-08**|**ExplORB-SLAM: Active Visual SLAM Exploiting the Pose-graph Topology**|Julio A. Placed et.al.|[2209.03693v1](http://arxiv.org/abs/2209.03693v1)|**[link](https://github.com/julioplaced/explorb-slam)**|
|**2022-09-08**|**R $^3$ LIVE++: A Robust, Real-time, Radiance reconstruction package with a tightly-coupled LiDAR-Inertial-Visual state Estimator**|Jiarong Lin et.al.|[2209.03666v1](http://arxiv.org/abs/2209.03666v1)|**[link](https://github.com/hku-mars/r3live)**|
|**2022-09-06**|**Group- $k$ Consistent Measurement Set Maximization for Robust Outlier Detection**|Brendon Forsgren et.al.|[2209.02658v1](http://arxiv.org/abs/2209.02658v1)|**[link](https://bitbucket.org/jmangelson/gkcm)**|
|**2022-09-05**|**Neuromorphic Visual Odometry with Resonator Networks**|Alpha Renner et.al.|[2209.02000v1](http://arxiv.org/abs/2209.02000v1)|null|
|**2022-09-05**|**MuCaSLAM: CNN-Based Frame Quality Assessment for Mobile Robot with Omnidirectional Visual SLAM**|Pavel Karpyshev et.al.|[2209.01936v1](http://arxiv.org/abs/2209.01936v1)|null|
|**2022-09-05**|**ElasticROS: An Elastically Collaborative Robot Operation System for Fog and Cloud Robotics**|Boyi Liu et.al.|[2209.01774v1](http://arxiv.org/abs/2209.01774v1)|null|
|**2022-09-04**|**CloudVision: DNN-based Visual Localization of Autonomous Robots using Prebuilt LiDAR Point Cloud**|Evgeny Yudin et.al.|[2209.01605v1](http://arxiv.org/abs/2209.01605v1)|null|
|**2022-08-31**|**PFilter: Building Persistent Maps through Feature Filtering for Fast and Accurate LiDAR-based SLAM**|Yifan Duan et.al.|[2208.14848v1](http://arxiv.org/abs/2208.14848v1)|null|
|**2022-08-30**|**BioSLAM: A Bio-inspired Lifelong Memory System for General Place Recognition**|Peng Yin et.al.|[2208.14543v1](http://arxiv.org/abs/2208.14543v1)|null|
|**2022-08-27**|**Learning to SLAM on the Fly in Unknown Environments: A Continual Learning Approach for Drones in Visually Ambiguous Scenes**|Ali Safa et.al.|[2208.12997v1](http://arxiv.org/abs/2208.12997v1)|null|
|**2022-08-25**|**FusionPortable: A Multi-Sensor Campus-Scene Dataset for Evaluation of Localization and Mapping Accuracy on Diverse Platforms**|Jianhao Jiao et.al.|[2208.11865v1](http://arxiv.org/abs/2208.11865v1)|null|
|**2022-08-25**|**Lidar SLAM for Autonomous Driving Vehicles**|Farhad Aghili et.al.|[2208.11855v1](http://arxiv.org/abs/2208.11855v1)|null|
|**2022-08-24**|**DynaVINS: A Visual-Inertial SLAM for Dynamic Environments**|Seungwon Song et.al.|[2208.11500v1](http://arxiv.org/abs/2208.11500v1)|**[link](https://github.com/url-kaist/dynavins)**|
|**2022-08-22**|**Doppler Exploitation in Bistatic mmWave Radio SLAM**|Yu Ge et.al.|[2208.10204v1](http://arxiv.org/abs/2208.10204v1)|null|
|**2022-08-21**|**Hilti-Oxford Dataset: A Millimetre-Accurate Benchmark for Simultaneous Localization and Mapping**|Lintong Zhang et.al.|[2208.09825v1](http://arxiv.org/abs/2208.09825v1)|null|
|**2022-08-26**|**JVLDLoc: a Joint Optimization of Visual-LiDAR Constraints and Direction Priors for Localization in Driving Scenario**|Longrui Dong et.al.|[2208.09777v2](http://arxiv.org/abs/2208.09777v2)|null|
|**2022-08-15**|**BoW3D: Bag of Words for Real-time Loop Closing in 3D LiDAR SLAM**|Yunge Cui et.al.|[2208.07473v1](http://arxiv.org/abs/2208.07473v1)|**[link](https://github.com/yungecui/bow3d)**|
|**2022-08-12**|**Handling Constrained Optimization in Factor Graphs for Autonomous Navigation**|Barbara Bazzana et.al.|[2208.06325v1](http://arxiv.org/abs/2208.06325v1)|null|
|**2022-08-11**|**RelPose: Predicting Probabilistic Relative Rotation for Single Objects in the Wild**|Jason Y. Zhang et.al.|[2208.05963v1](http://arxiv.org/abs/2208.05963v1)|null|
|**2022-08-08**|**Visual-Inertial Multi-Instance Dynamic SLAM with Object-level Relocalisation**|Yifei Ren et.al.|[2208.04274v1](http://arxiv.org/abs/2208.04274v1)|null|
|**2022-08-08**|**SLAM-TKA: Real-time Intra-operative Measurement of Tibial Resection Plane in Conventional Total Knee Arthroplasty**|Shuai Zhang et.al.|[2208.03945v1](http://arxiv.org/abs/2208.03945v1)|**[link](https://github.com/zsustc/calibration)**|
|**2022-08-05**|**A Survey on Visual Map Localization Using LiDARs and Cameras**|Elhousni Mahdi et.al.|[2208.03376v1](http://arxiv.org/abs/2208.03376v1)|null|
|**2022-08-04**|**SROS2: Usable Cyber Security Tools for ROS 2**|Victor Mayoral Vilches et.al.|[2208.02615v1](http://arxiv.org/abs/2208.02615v1)|**[link](https://github.com/ros-swg/turtlebot3_demo)**|
|**2022-08-03**|**Evaluation and comparison of eight popular Lidar and Visual SLAM algorithms**|Bharath Garigipati et.al.|[2208.02063v1](http://arxiv.org/abs/2208.02063v1)|null|
|**2022-08-02**|**Present and Future of SLAM in Extreme Underground Environments**|Kamak Ebadi et.al.|[2208.01787v1](http://arxiv.org/abs/2208.01787v1)|null|
|**2022-08-01**|**Visual-Inertial SLAM with Tightly-Coupled Dropout-Tolerant GPS Fusion**|Simon Boche et.al.|[2208.00709v1](http://arxiv.org/abs/2208.00709v1)|null|
|**2022-07-29**|**Neural Density-Distance Fields**|Itsuki Ueda et.al.|[2207.14455v1](http://arxiv.org/abs/2207.14455v1)|**[link](https://github.com/ueda0319/neddf)**|
|**2022-07-25**|**DeepFusion: Real-Time Dense 3D Reconstruction for Monocular SLAM using Single-View Depth and Gradient Predictions**|Tristan Laidlow et.al.|[2207.12244v1](http://arxiv.org/abs/2207.12244v1)|null|
|**2022-07-25**|**Scalable Fiducial Tag Localization on a 3D Prior Map via Graph-Theoretic Global Tag-Map Registration**|Kenji Koide et.al.|[2207.11942v1](http://arxiv.org/abs/2207.11942v1)|null|
|**2022-07-22**|**NeurAR: Neural Uncertainty for Autonomous 3D Reconstruction**|Yunlong Ran et.al.|[2207.10985v1](http://arxiv.org/abs/2207.10985v1)|null|
|**2022-07-22**|**Dense RGB-D-Inertial SLAM with Map Deformations**|Tristan Laidlow et.al.|[2207.10940v1](http://arxiv.org/abs/2207.10940v1)|null|
|**2022-07-22**|**PLD-SLAM: A Real-Time Visual SLAM Using Points and Line Segments in Dynamic Scenes**|BaoSheng Zhang et.al.|[2207.10916v1](http://arxiv.org/abs/2207.10916v1)|null|
|**2022-07-21**|**Multi-Event-Camera Depth Estimation and Outlier Rejection by Refocused Events Fusion**|Suman Ghosh et.al.|[2207.10494v1](http://arxiv.org/abs/2207.10494v1)|**[link](https://github.com/tub-rip/dvs_mcemvs)**|
|**2022-07-21**|**Online Localisation and Colored Mesh Reconstruction Architecture for 3D Visual Feedback in Robotic Exploration Missions**|Quentin Serdel et.al.|[2207.10489v1](http://arxiv.org/abs/2207.10489v1)|**[link](https://github.com/onera/olcmr)**|
|**2022-07-21**|**On applicability of von Karman's momentum theory in predicting the water entry load of V-shaped structures with varying initial velocity**|Yujin Lu et.al.|[2207.10413v1](http://arxiv.org/abs/2207.10413v1)|null|
|**2022-07-19**|**Hybrid Belief Pruning with Guarantees for Viewpoint-Dependent Semantic SLAM**|Tuvy Lemberg et.al.|[2207.09103v1](http://arxiv.org/abs/2207.09103v1)|null|
|**2022-07-18**|**DeFlowSLAM: Self-Supervised Scene Motion Decomposition for Dynamic Dense SLAM**|Weicai Ye et.al.|[2207.08794v1](http://arxiv.org/abs/2207.08794v1)|**[link](https://github.com/zju3dv/DeFlowSLAM)**|
|**2022-07-18**|**Revisiting PatchMatch Multi-View Stereo for Urban 3D Reconstruction**|Marco Orsingher et.al.|[2207.08439v1](http://arxiv.org/abs/2207.08439v1)|null|
|**2022-07-18**|**ORB-based SLAM accelerator on SoC FPGA**|Vibhakar Vemulapati et.al.|[2207.08405v1](http://arxiv.org/abs/2207.08405v1)|null|
|**2022-07-14**|**Challenges of SLAM in extremely unstructured environments: the DLR Planetary Stereo, Solid-State LiDAR, Inertial Dataset**|Riccardo Giubilato et.al.|[2207.06815v1](http://arxiv.org/abs/2207.06815v1)|null|
|**2022-07-14**|**Semi-supervised Vector-Quantization in Visual SLAM using HGCN**|Amir Zarringhalam et.al.|[2207.06738v1](http://arxiv.org/abs/2207.06738v1)|null|
|**2022-07-14**|**Self-supervised Vector-Quantization in Visual SLAM using Deep Convolutional Autoencoders**|Amir Zarringhalam et.al.|[2207.06732v1](http://arxiv.org/abs/2207.06732v1)|null|
|**2022-07-13**|**SLAM: SLO-Aware Memory Optimization for Serverless Applications**|Gor Safaryan et.al.|[2207.06183v1](http://arxiv.org/abs/2207.06183v1)|null|
|**2022-07-19**|**Structure PLP-SLAM: Efficient Sparse Mapping and Localization using Point, Line and Plane for Monocular, RGB-D and Stereo Cameras**|Fangwen Shu et.al.|[2207.06058v2](http://arxiv.org/abs/2207.06058v2)|**[link](https://github.com/peterfws/structure-plp-slam)**|
|**2022-07-12**|**Accelerating Certifiable Estimation with Preconditioned Eigensolvers**|David M. Rosen et.al.|[2207.05257v1](http://arxiv.org/abs/2207.05257v1)|null|
|**2022-07-12**|**Robust Key-Frame Stereo Visual SLAM with low-threshold Point and Line Features**|Meiyu Zhi et.al.|[2207.05244v1](http://arxiv.org/abs/2207.05244v1)|null|
|**2022-07-14**|**SLAM Backends with Objects in Motion: A Unifying Framework and Tutorial**|Chih-Yuan Chiu et.al.|[2207.05043v2](http://arxiv.org/abs/2207.05043v2)|null|
|**2022-07-08**|**BlindSpotNet: Seeing Where We Cannot See**|Taichi Fukuda et.al.|[2207.03870v1](http://arxiv.org/abs/2207.03870v1)|null|
|**2022-07-08**|**Continuous Target-free Extrinsic Calibration of a Multi-Sensor System from a Sequence of Static Viewpoints**|Philipp Glira et.al.|[2207.03785v1](http://arxiv.org/abs/2207.03785v1)|null|
|**2022-07-08**|**Distributed Ranging SLAM for Multiple Robots with Ultra-WideBand and Odometry Measurements**|Ran Liu et.al.|[2207.03700v1](http://arxiv.org/abs/2207.03700v1)|null|
|**2022-07-07**|**RWT-SLAM: Robust Visual SLAM for Highly Weak-textured Environments**|Qihao Peng et.al.|[2207.03539v1](http://arxiv.org/abs/2207.03539v1)|null|
|**2022-07-06**|**VI-SLAM2tag: Low-Effort Labeled Dataset Collection for Fingerprinting-Based Indoor Localization**|Marius Laska et.al.|[2207.02668v1](http://arxiv.org/abs/2207.02668v1)|null|
|**2022-07-06**|**A Novel Hybrid Endoscopic Dataset for Evaluating Machine Learning-based Photometric Image Enhancement Models**|Axel Garcia-Vega et.al.|[2207.02396v1](http://arxiv.org/abs/2207.02396v1)|null|
|**2022-07-04**|**VECtor: A Versatile Event-Centric Benchmark for Multi-Sensor SLAM**|Ling Gao et.al.|[2207.01404v1](http://arxiv.org/abs/2207.01404v1)|null|
|**2022-07-04**|**VIP-SLAM: An Efficient Tightly-Coupled RGB-D Visual Inertial Planar SLAM**|Danpeng Chen et.al.|[2207.01158v1](http://arxiv.org/abs/2207.01158v1)|null|
|**2022-07-03**|**Wireless Channel Prediction in Partially Observed Environments**|Mingsheng Yin et.al.|[2207.00934v1](http://arxiv.org/abs/2207.00934v1)|null|
|**2022-07-01**|**A Survey on Active Simultaneous Localization and Mapping: State of the Art and New Frontiers**|Julio A. Placed et.al.|[2207.00254v1](http://arxiv.org/abs/2207.00254v1)|null|
|**2022-07-01**|**Keeping Less is More: Point Sparsification for Visual SLAM**|Yeonsoo Park et.al.|[2207.00225v1](http://arxiv.org/abs/2207.00225v1)|null|
|**2022-06-30**|**Controlled and impulsive compression of an entrapped air bubble during impact**|Utkarsh Jain et.al.|[2206.15297v1](http://arxiv.org/abs/2206.15297v1)|null|
|**2022-06-30**|**Neural Rendering for Stereo 3D Reconstruction of Deformable Tissues in Robotic Surgery**|Yuehao Wang et.al.|[2206.15255v1](http://arxiv.org/abs/2206.15255v1)|**[link](https://github.com/med-air/endonerf)**|
|**2022-06-27**|**IBISCape: A Simulated Benchmark for multi-modal SLAM Systems Evaluation in Large-scale Dynamic Environments**|Abanob Soliman et.al.|[2206.13455v1](http://arxiv.org/abs/2206.13455v1)|**[link](https://github.com/AbanobSoliman/IBISCape)**|
|**2022-06-26**|**An Efficient Global Optimality Certificate for Landmark-Based SLAM**|Connor Holmes et.al.|[2206.12961v1](http://arxiv.org/abs/2206.12961v1)|**[link](https://github.com/holmesco/se-sync-landmarks)**|
|**2022-06-21**|**Object Structural Points Representation for Graph-based Semantic Monocular Localization and Mapping**|Davide Tateo et.al.|[2206.10263v1](http://arxiv.org/abs/2206.10263v1)|**[link](https://github.com/airlab-polimi/c-slam)**|
|**2022-06-20**|**Data Fusion for Radio Frequency SLAM with Robust Sampling**|Erik Leitinger et.al.|[2206.09746v1](http://arxiv.org/abs/2206.09746v1)|null|
|**2022-06-19**|**RF-LIO: Removal-First Tightly-coupled Lidar Inertial Odometry in High Dynamic Environments**|Chenglong Qian et.al.|[2206.09463v1](http://arxiv.org/abs/2206.09463v1)|null|
|**2022-06-17**|**Efficient WiFi LiDAR SLAM for Autonomous Robots in Large Environments**|Khairuldanial Ismail et.al.|[2206.08733v1](http://arxiv.org/abs/2206.08733v1)|null|
|**2022-06-17**|**An Algorithm for the SE(3)-Transformation on Neural Implicit Maps for Remapping Functions**|Yijun Yuan et.al.|[2206.08712v1](http://arxiv.org/abs/2206.08712v1)|**[link](https://github.com/jarrome/imt_mapping)**|
|**2022-06-13**|**ICP Algorithm: Theory, Practice And Its SLAM-oriented Taxonomy**|Hao Bai et.al.|[2206.06435v1](http://arxiv.org/abs/2206.06435v1)|null|
|**2022-06-10**|**Experimental Evaluation of Visual-Inertial Odometry Systems for Arable Farming**|Javier Cremona et.al.|[2206.05066v1](http://arxiv.org/abs/2206.05066v1)|**[link](https://github.com/cifasis/slam_agricultural_evaluation)**|
|**2022-06-09**|**SparseFormer: Attention-based Depth Completion Network**|Frederik Warburg et.al.|[2206.04557v1](http://arxiv.org/abs/2206.04557v1)|null|
|**2022-06-07**|**Robot Self-Calibration Using Actuated 3D Sensors**|Arne Peters et.al.|[2206.03430v1](http://arxiv.org/abs/2206.03430v1)|null|
|**2022-06-07**|**Object Scan Context: Object-centric Spatial Descriptor for Place Recognition within 3D Point Cloud Map**|Haodong Yuan et.al.|[2206.03062v1](http://arxiv.org/abs/2206.03062v1)|null|
|**2022-06-05**|**DarkSLAM: GAN-assisted Visual SLAM for Reliable Operation in Low-light Conditions**|Alena Savinykh et.al.|[2206.02199v1](http://arxiv.org/abs/2206.02199v1)|null|
|**2022-06-04**|**C $^3$ Fusion: Consistent Contrastive Colon Fusion, Towards Deep SLAM in Colonoscopy**|Erez Posner et.al.|[2206.01961v1](http://arxiv.org/abs/2206.01961v1)|null|
|**2022-06-01**|**PaGO-LOAM: Robust Ground-Optimized LiDAR Odometry**|Dong-Uk Seo et.al.|[2206.00266v1](http://arxiv.org/abs/2206.00266v1)|**[link](https://github.com/url-kaist/alterground-lego-loam)**|
|**2022-05-27**|**A Look at Improving Robustness in Visual-inertial SLAM by Moment Matching**|Arno Solin et.al.|[2205.13821v1](http://arxiv.org/abs/2205.13821v1)|null|
|**2022-05-31**|**LAMP 2.0: A Robust Multi-Robot SLAM System for Operation in Challenging Large-Scale Underground Environments**|Yun Chang et.al.|[2205.13135v2](http://arxiv.org/abs/2205.13135v2)|**[link](https://github.com/nebula-autonomy/nebula-multirobot-dataset)**|
|**2022-05-25**|**Wildcat: Online Continuous-Time 3D Lidar-Inertial SLAM**|Milad Ramezani et.al.|[2205.12595v1](http://arxiv.org/abs/2205.12595v1)|null|
|**2022-05-24**|**Loop Closure Prioritization for Efficient and Scalable Multi-Robot SLAM**|Christopher E. Denniston et.al.|[2205.12402v1](http://arxiv.org/abs/2205.12402v1)|**[link](https://github.com/nebula-autonomy/lamp)**|
|**2022-05-22**|**ALITA: A Large-scale Incremental Dataset for Long-term Autonomy**|Peng Yin et.al.|[2205.10737v1](http://arxiv.org/abs/2205.10737v1)|**[link](https://github.com/metaslam/alita)**|
|**2022-05-19**|**FogROS 2: An Adaptive and Extensible Platform for Cloud and Fog Robotics Using ROS 2**|Jeffrey Ichnowski et.al.|[2205.09778v1](http://arxiv.org/abs/2205.09778v1)|**[link](https://github.com/BerkeleyAutomation/FogROS2)**|
|**2022-05-17**|**Global Data Association for SLAM with 3D Grassmannian Manifold Objects**|Parker C. Lusk et.al.|[2205.08556v1](http://arxiv.org/abs/2205.08556v1)|null|
|**2022-05-19**|**Cluster on Wheels**|Yuanyuan Yang et.al.|[2205.08151v2](http://arxiv.org/abs/2205.08151v2)|null|
|**2022-05-12**|**Dynamic Dense RGB-D SLAM using Learning-based Visual Odometry**|Shihao Shen et.al.|[2205.05916v1](http://arxiv.org/abs/2205.05916v1)|**[link](https://github.com/geniussh/dynamic-dense-rgbd-slam-with-tartanvo)**|
|**2022-05-12**|**S3E-GNN: Sparse Spatial Scene Embedding with Graph Neural Networks for Camera Relocalization**|Ran Cheng et.al.|[2205.05861v1](http://arxiv.org/abs/2205.05861v1)|null|
|**2022-05-14**|**Multi-modal Semantic SLAM for Complex Dynamic Environments**|Han Wang et.al.|[2205.04300v2](http://arxiv.org/abs/2205.04300v2)|**[link](https://github.com/wh200720041/mms_slam)**|
|**2022-05-06**|**OROS: Orchestrating ROS-driven Collaborative Connected Robots in Mission-Critical Operations**|Carmen Delgado et.al.|[2205.03256v1](http://arxiv.org/abs/2205.03256v1)|null|
|**2022-05-05**|**CNN-Augmented Visual-Inertial SLAM with Planar Constraints**|Pan Ji et.al.|[2205.02940v1](http://arxiv.org/abs/2205.02940v1)|null|
|**2022-05-05**|**PMBM-based SLAM Filters in 5G mmWave Vehicular Networks**|Hyowon Kim et.al.|[2205.02502v1](http://arxiv.org/abs/2205.02502v1)|null|
|**2022-05-04**|**BodySLAM: Joint Camera Localisation, Mapping, and Human Motion Tracking**|Dorian Henning et.al.|[2205.02301v1](http://arxiv.org/abs/2205.02301v1)|null|
|**2022-05-04**|**A Global Asymptotic Convergent Observer for SLAM**|Seyed Hamed Hashemi et.al.|[2205.01953v1](http://arxiv.org/abs/2205.01953v1)|null|
|**2022-05-04**|**Symmetry and Uncertainty-Aware Object SLAM for 6DoF Object Pose Estimation**|Nathaniel Merrill et.al.|[2205.01823v1](http://arxiv.org/abs/2205.01823v1)|**[link](https://github.com/rpng/suo_slam)**|
|**2022-05-03**|**GeoRefine: Self-Supervised Online Depth Refinement for Accurate Dense Mapping**|Pan Ji et.al.|[2205.01656v1](http://arxiv.org/abs/2205.01656v1)|null|
|**2022-04-29**|**Struct-MDC: Mesh-Refined Unsupervised Depth Completion Leveraging Structural Regularities from Visual SLAM**|Jinwoo Jeon et.al.|[2204.13877v1](http://arxiv.org/abs/2204.13877v1)|**[link](https://github.com/url-kaist/Struct-MDC)**|
|**2022-04-27**|**The Revisiting Problem in Simultaneous Localization and Mapping: A Survey on Visual Loop Closure Detection**|Konstantinos A. Tsintotas et.al.|[2204.12831v1](http://arxiv.org/abs/2204.12831v1)|null|
|**2022-04-27**|**Dynamic Registration: Joint Ego Motion Estimation and 3D Moving Object Detection in Dynamic Environment**|Wenyu Li et.al.|[2204.12769v1](http://arxiv.org/abs/2204.12769v1)|null|
|**2022-04-29**|**MLO: Multi-Object Tracking and Lidar Odometry in Dynamic Environment**|Tingchen Ma et.al.|[2204.11621v2](http://arxiv.org/abs/2204.11621v2)|null|
|**2022-04-23**|**Indoor simultaneous localization and mapping based on fringe projection profilometry**|Yang Zhao et.al.|[2204.11020v1](http://arxiv.org/abs/2204.11020v1)|null|
|**2022-04-22**|**Enough is Enough: Towards Autonomous Uncertainty-driven Stopping Criteria**|Julio A. Placed et.al.|[2204.10631v1](http://arxiv.org/abs/2204.10631v1)|null|
|**2022-04-22**|**Fast Autonomous Robotic Exploration Using the Underlying Graph Structure**|Julio A. Placed et.al.|[2204.10610v1](http://arxiv.org/abs/2204.10610v1)|null|
|**2022-04-22**|**Making Parameterization and Constrains of Object Landmark Globally Consistent via SPD(3) Manifold and Improved Cost Functions**|Yutong Hu et.al.|[2204.10552v1](http://arxiv.org/abs/2204.10552v1)|null|
|**2022-04-22**|**Implicit Object Mapping With Noisy Data**|Jad Abou-Chakra et.al.|[2204.10516v1](http://arxiv.org/abs/2204.10516v1)|**[link](https://github.com/jc211/implicit_object_reconstruction_dataset)**|
|**2022-04-19**|**Photometric single-view dense 3D reconstruction in endoscopy**|Victor M. Batlle et.al.|[2204.09083v1](http://arxiv.org/abs/2204.09083v1)|null|
|**2022-04-18**|**Pulsar skips: Understanding variations in the regular periods of rotating neutron stars**|Clayton Miller et.al.|[2204.08449v1](http://arxiv.org/abs/2204.08449v1)|null|
|**2022-04-18**|**Tracking monocular camera pose and deformation for SLAM inside the human body**|Juan J. Gomez Rodriguez et.al.|[2204.08309v1](http://arxiv.org/abs/2204.08309v1)|null|
|**2022-04-18**|**Mapping While Following: 2D LiDAR SLAM in Indoor Dynamic Environments with a Person Tracker**|Hanjing Ye et.al.|[2204.08163v1](http://arxiv.org/abs/2204.08163v1)|null|
|**2022-04-14**|**ViViD++: Vision for Visibility Dataset**|Alex Junho Lee et.al.|[2204.06183v2](http://arxiv.org/abs/2204.06183v2)|null|
|**2022-04-12**|**HiTPR: Hierarchical Transformer for Place Recognition in Point Cloud**|Zhixing Hou et.al.|[2204.05481v1](http://arxiv.org/abs/2204.05481v1)|null|
|**2022-04-12**|**RGB-D Semantic SLAM for Surgical Robot Navigation in the Operating Room**|Cong Gao et.al.|[2204.05467v1](http://arxiv.org/abs/2204.05467v1)|null|
|**2022-04-11**|**Optimized SC-F-LOAM: Optimized Fast LiDAR Odometry and Mapping Using Scan Context**|Lizhou Liao et.al.|[2204.04932v1](http://arxiv.org/abs/2204.04932v1)|**[link](https://github.com/SlamCabbage/Optimized-SC-F-LOAM)**|
|**2022-04-04**|**Monitoring social distancing with single image depth estimation**|Alessio Mingozzi et.al.|[2204.01693v1](http://arxiv.org/abs/2204.01693v1)|null|
|**2022-04-01**|**Bi-directional Loop Closure for Visual SLAM**|Ihtisham Ali et.al.|[2204.01524v1](http://arxiv.org/abs/2204.01524v1)|null|
|**2022-04-04**|**IMOT: General-Purpose, Fast and Robust Estimation for Spatial Perception Problems with Outliers**|Lei Sun et.al.|[2204.01324v1](http://arxiv.org/abs/2204.01324v1)|null|
|**2022-04-03**|**Indoor Navigation Assistance for Visually Impaired People via Dynamic SLAM and Panoptic Segmentation with an RGB-D Sensor**|Wenyan Ou et.al.|[2204.01154v1](http://arxiv.org/abs/2204.01154v1)|null|
|**2022-04-02**|**UrbanFly: Uncertainty-Aware Planning for Navigation Amongst High-Rises with Monocular Visual-Inertial SLAM Maps**|Ayyappa Swamy Thatavarthy et.al.|[2204.00865v1](http://arxiv.org/abs/2204.00865v1)|**[link](https://github.com/sudarshan-s-harithas/urbanfly)**|
|**2022-03-31**|**Curiosity Driven Self-supervised Tactile Exploration of Unknown Objects**|Yujie Lu et.al.|[2204.00035v1](http://arxiv.org/abs/2204.00035v1)|null|
|**2022-03-30**|**GTP-SLAM: Game-Theoretic Priors for Simultaneous Localization and Mapping in Multi-Agent Scenarios**|Chih-Yuan Chiu et.al.|[2203.16690v1](http://arxiv.org/abs/2203.16690v1)|null|
|**2022-03-29**|**Indoor SLAM Using a Foot-mounted IMU and the local Magnetic Field**|Mostafa Osman et.al.|[2203.15866v1](http://arxiv.org/abs/2203.15866v1)|null|
|**2022-03-29**|**Eventor: An Efficient Event-Based Monocular Multi-View Stereo Accelerator on FPGA Platform**|Mingjun Li et.al.|[2203.15439v1](http://arxiv.org/abs/2203.15439v1)|null|
|**2022-03-29**|**Sparse Image based Navigation Architecture to Mitigate the need of precise Localization in Mobile Robots**|Pranay Mathur et.al.|[2203.15272v1](http://arxiv.org/abs/2203.15272v1)|null|
|**2022-03-28**|**Are High-Resolution Event Cameras Really Needed?**|Daniel Gehrig et.al.|[2203.14672v1](http://arxiv.org/abs/2203.14672v1)|null|
|**2022-03-25**|**Spectral Measurement Sparsification for Pose-Graph SLAM**|Kevin J. Doherty et.al.|[2203.13897v1](http://arxiv.org/abs/2203.13897v1)|**[link](https://github.com/MarineRoboticsGroup/mac)**|
|**2022-03-25**|**FD-SLAM: 3-D Reconstruction Using Features and Dense Matching**|Xingrui Yang et.al.|[2203.13861v1](http://arxiv.org/abs/2203.13861v1)|null|
|**2022-03-25**|**Gravity-constrained point cloud registration**|Vladimír Kubelka et.al.|[2203.13799v1](http://arxiv.org/abs/2203.13799v1)|null|
|**2022-03-24**|**MD-SLAM: Multi-cue Direct SLAM**|Luca Di Giammarino et.al.|[2203.13237v1](http://arxiv.org/abs/2203.13237v1)|**[link](https://github.com/digiamm/md_slam)**|
|**2022-03-24**|**Unsupervised Simultaneous Learning for Camera Re-Localization and Depth Estimation from Video**|Shun Taguchi et.al.|[2203.12804v1](http://arxiv.org/abs/2203.12804v1)|null|
|**2022-03-19**|**Hybrid Active and Passive Sensing for SLAM in Wireless Communication Systems**|Jie Yang et.al.|[2203.10267v1](http://arxiv.org/abs/2203.10267v1)|null|
|**2022-03-16**|**Any Way You Look At It: Semantic Crossview Localization and Mapping with LiDAR**|Ian D. Miller et.al.|[2203.08925v1](http://arxiv.org/abs/2203.08925v1)|**[link](https://github.com/iandouglas96/cross_view_slam)**|
|**2022-03-15**|**Neural RF SLAM for unsupervised positioning and mapping with channel state information**|Shreya Kadambi et.al.|[2203.08264v1](http://arxiv.org/abs/2203.08264v1)|null|
|**2022-03-15**|**Simultaneous Localisation and Mapping with Quadric Surfaces**|Tristan Laidlow et.al.|[2203.08040v1](http://arxiv.org/abs/2203.08040v1)|null|
|**2022-03-14**|**Drift Reduced Navigation with Deep Explainable Features**|Mohd Omama et.al.|[2203.06897v1](http://arxiv.org/abs/2203.06897v1)|**[link](https://github.com/mohdomama/drndef)**|
|**2022-03-11**|**An Efficient Accelerator for Deep Learning-based Point Cloud Registration on FPGAs**|Keisuke Sugiura et.al.|[2203.05763v1](http://arxiv.org/abs/2203.05763v1)|null|
|**2022-03-10**|**High Definition, Inexpensive, Underwater Mapping**|Bharat Joshi et.al.|[2203.05640v1](http://arxiv.org/abs/2203.05640v1)|**[link](https://github.com/autonomousfieldroboticslab/gopro_ros)**|
|**2022-03-10**|**SelfTune: Metrically Scaled Monocular Depth Estimation through Self-Supervised Learning**|Jaehoon Choi et.al.|[2203.05332v1](http://arxiv.org/abs/2203.05332v1)|null|
|**2022-03-08**|**Tune your Place Recognition: Self-Supervised Domain Calibration via Robust SLAM**|Pierre-Yves Lajoie et.al.|[2203.04446v1](http://arxiv.org/abs/2203.04446v1)|**[link](https://github.com/mistlab/vpr-calibration-and-uncertainty)**|
|**2022-03-08**|**SLAM-Supported Self-Training for 6D Object Pose Estimation**|Ziqi Lu et.al.|[2203.04424v1](http://arxiv.org/abs/2203.04424v1)|**[link](https://github.com/520xyxyzq/slam-super-6d)**|
|**2022-03-08**|**An Online Semantic Mapping System for Extending and Enhancing Visual SLAM**|Thorsten Hempel et.al.|[2203.03944v1](http://arxiv.org/abs/2203.03944v1)|null|
|**2022-03-07**|**Multi-Modal Lidar Dataset for Benchmarking General-Purpose Localization and Mapping Algorithms**|Qingqing Li et.al.|[2203.03454v1](http://arxiv.org/abs/2203.03454v1)|**[link](https://github.com/tiers/tiers-lidars-dataset)**|
|**2022-03-07**|**OverlapTransformer: An Efficient and Rotation-Invariant Transformer Network for LiDAR-Based Place Recognition**|Junyi Ma et.al.|[2203.03397v1](http://arxiv.org/abs/2203.03397v1)|**[link](https://github.com/haomo-ai/OverlapTransformer)**|
|**2022-03-06**|**Minimum Cost Multicuts for Incorrect Landmark Edge Detection in Pose-graph SLAM**|Kazushi Aiba et.al.|[2203.02887v1](http://arxiv.org/abs/2203.02887v1)|null|
|**2022-03-06**|**RGB-D SLAM in Indoor Planar Environments with Multiple Large Dynamic Objects**|Ran Long et.al.|[2203.02882v1](http://arxiv.org/abs/2203.02882v1)|null|
|**2022-03-03**|**STUN: Self-Teaching Uncertainty Estimation for Place Recognition**|Kaiwen Cai et.al.|[2203.01851v1](http://arxiv.org/abs/2203.01851v1)|**[link](https://github.com/ramdrop/stun)**|
|**2022-03-03**|**Continual SLAM: Beyond Lifelong Simultaneous Localization and Mapping through Continual Learning**|Niclas Vödisch et.al.|[2203.01578v1](http://arxiv.org/abs/2203.01578v1)|**[link](https://github.com/robot-learning-freiburg/CL-SLAM)**|
|**2022-03-02**|**FAST-LIVO: Fast and Tightly-coupled Sparse-Direct LiDAR-Inertial-Visual Odometry**|Chunran Zheng et.al.|[2203.00893v1](http://arxiv.org/abs/2203.00893v1)|**[link](https://github.com/hku-mars/fast-livo)**|
|**2022-03-02**|**Distributed Riemannian Optimization with Lazy Communication for Collaborative Geometric Estimation**|Yulun Tian et.al.|[2203.00851v1](http://arxiv.org/abs/2203.00851v1)|null|
|**2022-03-01**|**Descriptellation: Deep Learned Constellation Descriptors for SLAM**|Chunwei Xing et.al.|[2203.00567v1](http://arxiv.org/abs/2203.00567v1)|null|
|**2022-03-01**|**Collaborative Robot Mapping using Spectral Graph Analysis**|Lukas Bernreiter et.al.|[2203.00308v1](http://arxiv.org/abs/2203.00308v1)|null|
|**2022-02-26**|**RL-PGO: Reinforcement Learning-based Planar Pose-Graph Optimization**|Nikolaos Kourtzanidis et.al.|[2202.13221v1](http://arxiv.org/abs/2202.13221v1)|**[link](https://github.com/Nick-Kou/RL-PGO)**|
|**2022-02-25**|**Probabilistic Data Association for Semantic SLAM at Scale**|Elad Michael et.al.|[2202.12802v1](http://arxiv.org/abs/2202.12802v1)|**[link](https://github.com/eladmichael/probabilisticsemslam)**|
|**2022-02-24**|**TwistSLAM: Constrained SLAM in Dynamic Environment**|Mathieu Gonzalez et.al.|[2202.12384v1](http://arxiv.org/abs/2202.12384v1)|null|
|**2022-02-24**|**Light Robust Monocular Depth Estimation For Outdoor Environment Via Monochrome And Color Camera Fusion**|Hyeonsoo Jang et.al.|[2202.12108v1](http://arxiv.org/abs/2202.12108v1)|null|
|**2022-02-23**|**MITI: SLAM Benchmark for Laparoscopic Surgery**|Regine Hartwig et.al.|[2202.11496v1](http://arxiv.org/abs/2202.11496v1)|null|
|**2022-02-23**|**DL-SLOT: Dynamic Lidar SLAM and Object Tracking Based On Graph Optimization**|Xuebo Tian et.al.|[2202.11431v1](http://arxiv.org/abs/2202.11431v1)|null|
|**2022-02-23**|**Are We Ready for Robust and Resilient SLAM? A Framework For Quantitative Characterization of SLAM Datasets**|Islam Ali et.al.|[2202.11312v1](http://arxiv.org/abs/2202.11312v1)|null|
|**2022-02-22**|**SAGE: SLAM with Appearance and Geometry Prior for Endoscopy**|Xingtong Liu et.al.|[2202.09487v2](http://arxiv.org/abs/2202.09487v2)|**[link](https://github.com/lppllppl920/sage-slam)**|
|**2022-02-18**|**OKVIS2: Realtime Scalable Visual-Inertial SLAM with Loop Closure**|Stefan Leutenegger et.al.|[2202.09199v1](http://arxiv.org/abs/2202.09199v1)|null|
|**2022-02-18**|**MultiRes-NetVLAD: Augmenting Place Recognition Training with Low-Resolution Imagery**|Ahmad Khaliq et.al.|[2202.09146v1](http://arxiv.org/abs/2202.09146v1)|**[link](https://github.com/ahmedest61/multires-netvlad)**|
|**2022-02-18**|**An Energy-Efficient and Runtime-Reconfigurable FPGA-Based Accelerator for Robotic Localization Systems**|Qiang Liu et.al.|[2202.08952v1](http://arxiv.org/abs/2202.08952v1)|null|
|**2022-02-17**|**Continuous-Time vs. Discrete-Time Vision-based SLAM: A Comparative Study**|Giovanni Cioffi et.al.|[2202.08894v1](http://arxiv.org/abs/2202.08894v1)|**[link](https://github.com/uzh-rpg/rpg_vision-based_slam)**|
|**2022-02-17**|**LiDAR-Inertial 3D SLAM with Plane Constraint for Multi-story Building**|Jiashi Zhang et.al.|[2202.08487v1](http://arxiv.org/abs/2202.08487v1)|null|
|**2022-02-16**|**Virtual Maps for Autonomous Exploration of Cluttered Underwater Environments**|Jinkun Wang et.al.|[2202.08359v1](http://arxiv.org/abs/2202.08359v1)|null|
|**2022-02-11**|**Overhead Image Factors for Underwater Sonar-based SLAM**|John McConnell et.al.|[2202.05811v1](http://arxiv.org/abs/2202.05811v1)|null|
|**2022-02-10**|**Scale Estimation with Dual Quadrics for Monocular Object SLAM**|Shuangfu Song et.al.|[2202.04816v1](http://arxiv.org/abs/2202.04816v1)|null|
|**2022-02-08**|**A Novel Image Descriptor with Aggregated Semantic Skeleton Representation for Long-term Visual Place Recognition**|Nie Jiwei et.al.|[2202.03677v1](http://arxiv.org/abs/2202.03677v1)|null|
|**2022-01-25**|**Autonomous Vehicles: Open-Source Technologies, Considerations, and Development**|Oussama Saoudi et.al.|[2202.03148v1](http://arxiv.org/abs/2202.03148v1)|null|
|**2022-02-07**|**Temporal Point Cloud Completion with Pose Disturbance**|Jieqi Shi et.al.|[2202.03084v1](http://arxiv.org/abs/2202.03084v1)|null|
|**2022-02-04**|**DYP-SLAM: A Real-time Visual SLAM Based on YOLO and Probability in Dynamic Environments**|Xinggang Hu et.al.|[2202.01938v1](http://arxiv.org/abs/2202.01938v1)|null|
|**2022-02-01**|**A Model for Multi-View Residual Covariances based on Perspective Deformation**|Alejandro Fontan et.al.|[2202.00765v1](http://arxiv.org/abs/2202.00765v1)|null|
|**2022-01-30**|**Joint Vehicular Localization and Reflective Mapping Based on Team Channel-SLAM**|Xinghe Chu et.al.|[2201.12726v1](http://arxiv.org/abs/2201.12726v1)|null|
|**2022-01-28**|**RGB-D SLAM Using Attention Guided Frame Association**|Ali Caglayan et.al.|[2201.12047v1](http://arxiv.org/abs/2201.12047v1)|null|
|**2022-02-04**|**Learning to Act with Affordance-Aware Multimodal Neural SLAM**|Zhiwei Jia et.al.|[2201.09862v2](http://arxiv.org/abs/2201.09862v2)|**[link](https://github.com/amazon-research/multimodal-neuralslam)**|
|**2022-01-22**|**Phase-SLAM: Phase Based Simultaneous Localization and Mapping for Mobile Structured Light Illumination Systems**|Xi Zheng et.al.|[2201.09048v1](http://arxiv.org/abs/2201.09048v1)|**[link](https://github.com/zhengxi-git/phase-slam)**|
|**2022-01-17**|**SC-LiDAR-SLAM: a Front-end Agnostic Versatile LiDAR SLAM System**|Giseop Kim et.al.|[2201.06423v1](http://arxiv.org/abs/2201.06423v1)|null|
|**2022-01-14**|**SRVIO: Super Robust Visual Inertial Odometry for dynamic environments and challenging Loop-closure conditions**|Ali Samadzadeh et.al.|[2201.05386v1](http://arxiv.org/abs/2201.05386v1)|**[link](https://github.com/aa-samad/srvio)**|
|**2022-01-19**|**Multi-Hypothesis Scan Matching through Clustering**|Giorgio Iavicoli et.al.|[2201.03814v2](http://arxiv.org/abs/2201.03814v2)|null|
|**2022-01-11**|**Performance Guarantees for Spectral Initialization in Rotation Averaging and Pose-Graph SLAM**|Kevin J. Doherty et.al.|[2201.03773v1](http://arxiv.org/abs/2201.03773v1)|null|
|**2022-01-10**|**High-resolution Ecosystem Mapping in Repetitive Environments Using Dual Camera SLAM**|Brian M. Hopkinson et.al.|[2201.03364v1](http://arxiv.org/abs/2201.03364v1)|**[link](https://github.com/bmhopkinson/hyslam)**|
|**2022-01-10**|**Why-So-Deep: Towards Boosting Previously Trained Models for Visual Place Recognition**|M. Usman Maqbool Bhutta et.al.|[2201.03212v1](http://arxiv.org/abs/2201.03212v1)|**[link](https://github.com/UsmanMaqbool/why-so-deep)**|
|**2022-01-04**|**Formulations of Hydrodynamic Force in the Transition Stage of the Water Entry of Linear Wedges with Constant and Varying Speeds**|Xueliang Wen et.al.|[2201.00959v1](http://arxiv.org/abs/2201.00959v1)|null|
|**2021-12-29**|**Efficient Belief Space Planning in High-Dimensional State Spaces using PIVOT: Predictive Incremental Variable Ordering Tactic**|Khen Elimelech et.al.|[2112.14428v1](http://arxiv.org/abs/2112.14428v1)|null|
|**2021-12-19**|**M2DGR: A Multi-sensor and Multi-scenario SLAM Dataset for Ground Robots**|Jie Yin et.al.|[2112.13659v1](http://arxiv.org/abs/2112.13659v1)|**[link](https://github.com/SJTU-ViSYS/M2DGR)**|
|**2021-12-27**|**UV-SLAM: Unconstrained Line-based SLAM Using Vanishing Points for Structural Mapping**|Hyunjun Lim et.al.|[2112.13515v1](http://arxiv.org/abs/2112.13515v1)|**[link](https://github.com/url-kaist/uv-slam)**|
|**2021-12-25**|**Simultaneous Location of Rail Vehicles and Mapping of Environment with Multiple LiDARs**|Yusheng Wang et.al.|[2112.13224v1](http://arxiv.org/abs/2112.13224v1)|null|
|**2021-12-25**|**Edge Robotics: Edge-Computing-Accelerated Multi-Robot Simultaneous Localization and Mapping**|Peng Huang et.al.|[2112.13222v1](http://arxiv.org/abs/2112.13222v1)|null|
|**2021-12-24**|**3D Point Cloud Reconstruction and SLAM as an Input**|Ziyu Li et.al.|[2112.12907v1](http://arxiv.org/abs/2112.12907v1)|null|
|**2021-12-22**|**NICE-SLAM: Neural Implicit Scalable Encoding for SLAM**|Zihan Zhu et.al.|[2112.12130v1](http://arxiv.org/abs/2112.12130v1)|**[link](https://github.com/cvg/nice-slam)**|
|**2021-12-18**|**Fast and Robust Registration of Partially Overlapping Point Clouds**|Eduardo Arnold et.al.|[2112.09922v1](http://arxiv.org/abs/2112.09922v1)|**[link](https://github.com/eduardohenriquearnold/fastreg)**|
|**2021-12-17**|**Symmetry-aware Neural Architecture for Embodied Visual Navigation**|Shuang Liu et.al.|[2112.09515v1](http://arxiv.org/abs/2112.09515v1)|null|
|**2021-12-27**|**Homography Decomposition Networks for Planar Object Tracking**|Xinrui Zhan et.al.|[2112.07909v3](http://arxiv.org/abs/2112.07909v3)|**[link](https://github.com/zhanxinrui/hdn)**|
|**2021-12-14**|**Autonomous Navigation System from Simultaneous Localization and Mapping**|Micheal Caracciolo et.al.|[2112.07723v1](http://arxiv.org/abs/2112.07723v1)|**[link](https://github.com/michealcarac/VSLAM-Mapping)**|
|**2021-12-12**|**360-DFPE: Leveraging Monocular 360-Layouts for Direct Floor Plan Estimation**|Bolivar Solarte et.al.|[2112.06180v2](http://arxiv.org/abs/2112.06180v2)|**[link](https://github.com/EnriqueSolarte/direct_360_FPE)**|
|**2021-12-11**|**Simultaneous Localization and Mapping: Through the Lens of Nonlinear Optimization**|Amay Saxena et.al.|[2112.05921v1](http://arxiv.org/abs/2112.05921v1)|null|
|**2021-12-07**|**Hybrid Visual SLAM for Underwater Vehicle Manipulator Systems**|Gideon Billings et.al.|[2112.03826v1](http://arxiv.org/abs/2112.03826v1)|null|
|**2021-12-05**|**Iterated Posterior Linearization PMB Filter for 5G SLAM**|Yu Ge et.al.|[2112.02575v1](http://arxiv.org/abs/2112.02575v1)|null|
|**2021-12-03**|**Fast Direct Stereo Visual SLAM**|Jiawei Mo et.al.|[2112.01890v1](http://arxiv.org/abs/2112.01890v1)|**[link](https://github.com/irvlab/direct_stereo_slam)**|
|**2021-12-02**|**MegBA: A High-Performance and Distributed Library for Large-Scale Bundle Adjustment**|Jie Ren et.al.|[2112.01349v2](http://arxiv.org/abs/2112.01349v2)|**[link](https://github.com/megviirobot/megba)**|
|**2021-12-01**|**Research on Event Accumulator Settings for Event-Based SLAM**|Kun Xiao et.al.|[2112.00427v1](http://arxiv.org/abs/2112.00427v1)|**[link](https://github.com/robin-shaun/event-slam-accumulator-settings)**|
|**2021-11-29**|**An in-depth experimental study of sensor usage and visual reasoning of robots navigating in real environments**|Assem Sadek et.al.|[2111.14666v1](http://arxiv.org/abs/2111.14666v1)|null|
|**2021-11-29**|**Deployment of Aerial Robots after a major fire of an industrial hall with hazardous substances, a report**|Hartmut Surmann et.al.|[2111.14542v1](http://arxiv.org/abs/2111.14542v1)|null|
|**2021-11-24**|**Automatic Mapping with Obstacle Identification for Indoor Human Mobility Assessment**|V. Ayala-Alfaro et.al.|[2111.12690v1](http://arxiv.org/abs/2111.12690v1)|null|
|**2021-11-24**|**Autonomous bot with ML-based reactive navigation for indoor environment**|Yash Srivastava et.al.|[2111.12542v1](http://arxiv.org/abs/2111.12542v1)|null|
|**2021-11-22**|**A General Framework for Lifelong Localization and Mapping in Changing Environment**|Min Zhao et.al.|[2111.10946v1](http://arxiv.org/abs/2111.10946v1)|**[link](https://github.com/sanduan168/lifelong-slam-dataset)**|
|**2021-11-17**|**Probabilistic Spatial Distribution Prior Based Attentional Keypoints Matching Network**|Xiaoming Zhao et.al.|[2111.09006v2](http://arxiv.org/abs/2111.09006v2)|null|
|**2021-11-10**|**Comparing dominance of tennis' big three via multiple-output Bayesian quantile regression models**|Bruno Santos et.al.|[2111.05631v1](http://arxiv.org/abs/2111.05631v1)|null|
|**2021-11-10**|**TomoSLAM: factor graph optimization for rotation angle refinement in microtomography**|Mark Griguletskii et.al.|[2111.05562v1](http://arxiv.org/abs/2111.05562v1)|null|
|**2021-11-07**|**Hierarchical Segment-based Optimization for SLAM**|Yuxin Tian et.al.|[2111.04101v1](http://arxiv.org/abs/2111.04101v1)|null|
|**2021-11-07**|**Online Mutual Adaptation of Deep Depth Prediction and Visual SLAM**|Shing Yan Loo et.al.|[2111.04096v2](http://arxiv.org/abs/2111.04096v2)|null|
|**2021-11-05**|**MSC-VO: Exploiting Manhattan and Structural Constraints for Visual Odometry**|Joan P. Company-Corcoles et.al.|[2111.03408v1](http://arxiv.org/abs/2111.03408v1)|null|
|**2021-10-31**|**Loop closure detection using local 3D deep descriptors**|Youjie Zhou et.al.|[2111.00440v1](http://arxiv.org/abs/2111.00440v1)|**[link](https://github.com/yiming107/l3d_loop_closure)**|
|**2021-10-27**|**Millimeter Wave Wireless Assisted Robot Navigation with Link State Classification**|Mingsheng Yin et.al.|[2110.14789v2](http://arxiv.org/abs/2110.14789v2)|**[link](https://github.com/nyu-wireless/mmwRobotNav)**|
|**2021-10-27**|**Efficient Placard Discovery for Semantic Mapping During Frontier Exploration**|David Balaban et.al.|[2110.14742v1](http://arxiv.org/abs/2110.14742v1)|null|
|**2021-10-26**|**Robust Multi-view Registration of Point Sets with Laplacian Mixture Model**|Jin Zhang et.al.|[2110.13744v1](http://arxiv.org/abs/2110.13744v1)|null|
|**2021-10-25**|**WOLF: A modular estimation framework for robotics based on factor graphs**|Joan Sola et.al.|[2110.12919v1](http://arxiv.org/abs/2110.12919v1)|null|
|**2021-10-21**|**Real-Time Ground-Plane Refined LiDAR SLAM**|Fan Yang et.al.|[2110.11517v1](http://arxiv.org/abs/2110.11517v1)|null|
|**2021-10-21**|**SymbioLCD: Ensemble-Based Loop Closure Detection using CNN-Extracted Objects and Visual Bag-of-Words**|Jonathan J. Y. Kim et.al.|[2110.11491v1](http://arxiv.org/abs/2110.11491v1)|null|
|**2021-10-21**|**InterpolationSLAM: A Novel Robust Visual SLAM System in Rotational Motion**|Zhenkun Zhu et.al.|[2110.11040v2](http://arxiv.org/abs/2110.11040v2)|null|
|**2021-10-20**|**SLAM: A Unified Encoder for Speech and Language Modeling via Speech-Text Joint Pre-Training**|Ankur Bapna et.al.|[2110.10329v1](http://arxiv.org/abs/2110.10329v1)|null|
|**2021-10-18**|**Enhancing exploration algorithms for navigation with visual SLAM**|Kirill Muravyev et.al.|[2110.09156v1](http://arxiv.org/abs/2110.09156v1)|null|
|**2021-10-18**|**Accurate and Robust Object-oriented SLAM with 3D Quadric Landmark Construction in Outdoor Environment**|Rui Tian et.al.|[2110.08977v1](http://arxiv.org/abs/2110.08977v1)|null|
|**2021-10-16**|**Partial Hierarchical Pose Graph Optimization for SLAM**|Alexander Korovko et.al.|[2110.08639v1](http://arxiv.org/abs/2110.08639v1)|null|
|**2021-10-14**|**Active SLAM over Continuous Trajectory and Control: A Covariance-Feedback Approach**|Shumon Koga et.al.|[2110.07546v1](http://arxiv.org/abs/2110.07546v1)|null|
|**2021-10-13**|**Collaborative Radio SLAM for Multiple Robots based on WiFi Fingerprint Similarity**|Ran Liu et.al.|[2110.06541v2](http://arxiv.org/abs/2110.06541v2)|null|
|**2021-10-12**|**Learning Efficient Multi-Agent Cooperative Visual Exploration**|Chao Yu et.al.|[2110.05734v1](http://arxiv.org/abs/2110.05734v1)|null|
|**2021-10-07**|**Self-Supervised Depth Completion for Active Stereo**|Frederik Warburg et.al.|[2110.03234v1](http://arxiv.org/abs/2110.03234v1)|null|
|**2021-10-06**|**InterpolationSLAM: A Novel Robust Visual SLAM System in Rotating Scenes**|Zhenkun Zhu et.al.|[2110.02593v1](http://arxiv.org/abs/2110.02593v1)|null|
|**2021-10-03**|**AEROS: Adaptive RObust least-Squares for Graph-Based SLAM**|Milad Ramezani et.al.|[2110.02018v1](http://arxiv.org/abs/2110.02018v1)|null|
|**2021-10-04**|**Fast Uncertainty Quantification for Active Graph SLAM**|Julio A. Placed et.al.|[2110.01289v1](http://arxiv.org/abs/2110.01289v1)|**[link](https://github.com/julioplaced/active_graph_slam)**|
|**2021-10-04**|**Geometry-based Graph Pruning for Lifelong SLAM**|Gerhard Kurz et.al.|[2110.01286v1](http://arxiv.org/abs/2110.01286v1)|null|
|**2021-10-03**|**Quadrotor Control on $SU(2)\times R^3$ with SLAM Integration**|Marcus Greiff et.al.|[2110.01099v1](http://arxiv.org/abs/2110.01099v1)|null|
|**2021-10-02**|**Online Incremental Non-Gaussian Inference for SLAM Using Normalizing Flows**|Qiangqiang Huang et.al.|[2110.00876v1](http://arxiv.org/abs/2110.00876v1)|**[link](https://github.com/marineroboticsgroup/nf-isam)**|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## SFM

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-15**|**3DMASC: Accessible, explainable 3D point clouds classification. Application to Bi-spectral Topo-bathymetric lidar data**|Mathilde Letard et.al.|[2401.09481](http://arxiv.org/abs/2401.09481)|null|
|**2024-01-17**|**3D Scene Geometry Estimation from 360 $^\circ$ Imagery: A Survey**|Thiago Lopes Trugillo da Silveira et.al.|[2401.09252](http://arxiv.org/abs/2401.09252)|null|
|**2024-01-17**|**ICON: Incremental CONfidence for Joint Pose and Radiance Field Optimization**|Weiyao Wang et.al.|[2401.08937](http://arxiv.org/abs/2401.08937)|null|
|**2024-01-16**|**Cross-Modal Semi-Dense 6-DoF Tracking of an Event Camera in Challenging Conditions**|Yi-Fan Zuo et.al.|[2401.08043](http://arxiv.org/abs/2401.08043)|**[link](https://github.com/zyfff/canny-evt)**|
|**2024-01-10**|**Structure from Duplicates: Neural Inverse Graphics from a Pile of Objects**|Tianhang Cheng et.al.|[2401.05236](http://arxiv.org/abs/2401.05236)|**[link](https://github.com/tianhang-cheng/sfd)**|
|**2024-01-07**|**A Classification of Critical Configurations for any Number of Projective Views**|Martin Bråtelund et.al.|[2401.03450](http://arxiv.org/abs/2401.03450)|**[link](https://github.com/mabraate/critical-configurations)**|
|**2023-12-24**|**Residual Learning for Image Point Descriptors**|Rashik Shrestha et.al.|[2312.15471](http://arxiv.org/abs/2312.15471)|null|
|**2023-12-16**|**Transformers in Unsupervised Structure-from-Motion**|Hemang Chawla et.al.|[2312.10529](http://arxiv.org/abs/2312.10529)|**[link](https://github.com/neurai-lab/mt-sfmlearner)**|
|**2023-12-14**|**HeadRecon: High-Fidelity 3D Head Reconstruction from Monocular Video**|Xueying Wang et.al.|[2312.08863](http://arxiv.org/abs/2312.08863)|null|
|**2023-12-14**|**CF-NeRF: Camera Parameter Free Neural Radiance Fields with Incremental Learning**|Qingsong Yan et.al.|[2312.08760](http://arxiv.org/abs/2312.08760)|null|
|**2023-12-11**|**Keypoint-based Stereophotoclinometry for Characterizing and Navigating Small Bodies: A Factor Graph Approach**|Travis Driver et.al.|[2312.06865](http://arxiv.org/abs/2312.06865)|null|
|**2023-12-11**|**Gaussian Splatting SLAM**|Hidenobu Matsuki et.al.|[2312.06741](http://arxiv.org/abs/2312.06741)|null|
|**2023-12-10**|**SuperPrimitive: Scene Reconstruction at a Primitive Level**|Kirill Mazur et.al.|[2312.05889](http://arxiv.org/abs/2312.05889)|null|
|**2023-12-07**|**Visual Geometry Grounded Deep Structure From Motion**|Jianyuan Wang et.al.|[2312.04563](http://arxiv.org/abs/2312.04563)|null|
|**2023-11-30**|**Distributed Global Structure-from-Motion with a Deep Front-End**|Ayush Baid et.al.|[2311.18801](http://arxiv.org/abs/2311.18801)|**[link](https://github.com/borglab/gtsfm)**|
|**2023-11-21**|**Robot Hand-Eye Calibration using Structure-from-Motion**|Nicolas Andreff et.al.|[2311.11808](http://arxiv.org/abs/2311.11808)|null|
|**2023-11-18**|**LOSTU: Fast, Scalable, and Uncertainty-Aware Triangulation**|Sébastien Henry et.al.|[2311.11171](http://arxiv.org/abs/2311.11171)|null|
|**2023-11-10**|**MonoProb: Self-Supervised Monocular Depth Estimation with Interpretable Uncertainty**|Rémi Marsal et.al.|[2311.06137](http://arxiv.org/abs/2311.06137)|**[link](https://github.com/cea-list/monoprob)**|
|**2023-11-08**|**VET: Visual Error Tomography for Point Cloud Completion and High-Quality Neural Rendering**|Linus Franke et.al.|[2311.04634](http://arxiv.org/abs/2311.04634)|**[link](https://github.com/lfranke/vet)**|
|**2023-10-22**|**A Quantitative Evaluation of Dense 3D Reconstruction of Sinus Anatomy from Monocular Endoscopic Video**|Jan Emily Mangulabnan et.al.|[2310.14364](http://arxiv.org/abs/2310.14364)|null|
|**2023-10-20**|**FMRT: Learning Accurate Feature Matching with Reconciliatory Transformer**|Xinyu Zhang et.al.|[2310.13605](http://arxiv.org/abs/2310.13605)|null|
|**2023-10-09**|**Colmap-PCD: An Open-source Tool for Fine Image-to-point cloud Registration**|Chunge Bai et.al.|[2310.05504](http://arxiv.org/abs/2310.05504)|**[link](https://github.com/xiaobaiiiiii/colmap-pcd)**|
|**2023-10-08**|**LocoNeRF: A NeRF-based Approach for Local Structure from Motion for Precise Localization**|Artem Nenashev et.al.|[2310.05134](http://arxiv.org/abs/2310.05134)|null|
|**2023-12-27**|**Pose-Free Generalizable Rendering Transformer**|Zhiwen Fan et.al.|[2310.03704](http://arxiv.org/abs/2310.03704)|**[link](https://github.com/zhiwenfan/DragView)**|
|**2023-10-02**|**Leveraging Cutting Edge Deep Learning Based Image Matching for Reconstructing a Large Scene from Sparse Images**|Georg Bökman et.al.|[2310.01092](http://arxiv.org/abs/2310.01092)|null|
|**2023-10-01**|**Propagating Semantic Labels in Video Data**|David Balaban et.al.|[2310.00783](http://arxiv.org/abs/2310.00783)|null|
|**2023-09-22**|**Scalable Semantic 3D Mapping of Coral Reefs with Deep Learning**|Jonathan Sauder et.al.|[2309.12804](http://arxiv.org/abs/2309.12804)|null|
|**2023-09-21**|**On-the-Fly SfM: What you capture is What you get**|Zongqian Zhan et.al.|[2309.11883](http://arxiv.org/abs/2309.11883)|null|
|**2023-09-19**|**Using an Uncrewed Surface Vehicle to Create a Volumetric Model of Non-Navigable Rivers and Other Shallow Bodies of Water**|Jayesh Tripathi et.al.|[2309.10269](http://arxiv.org/abs/2309.10269)|null|
|**2023-09-16**|**DynaMoN: Motion-Aware Fast And Robust Camera Localization for Dynamic NeRF**|Mert Asim Karaoglu et.al.|[2309.08927](http://arxiv.org/abs/2309.08927)|null|
|**2023-09-08**|**Robot Localization and Mapping Final Report -- Sequential Adversarial Learning for Self-Supervised Deep Visual Odometry**|Akankshya Kar et.al.|[2309.04147](http://arxiv.org/abs/2309.04147)|null|
|**2023-09-01**|**SQLdepth: Generalizable Self-Supervised Fine-Structured Monocular Depth Estimation**|Youhong Wang et.al.|[2309.00526](http://arxiv.org/abs/2309.00526)|null|
|**2023-09-01**|**Dense Voxel 3D Reconstruction Using a Monocular Event Camera**|Haodong Chen et.al.|[2309.00385](http://arxiv.org/abs/2309.00385)|null|
|**2023-12-04**|**Learning Structure-from-Motion with Graph Attention Networks**|Lucas Brynte et.al.|[2308.15984](http://arxiv.org/abs/2308.15984)|null|
|**2023-08-26**|**Disjoint Pose and Shape for 3D Face Reconstruction**|Raja Kumar et.al.|[2308.13903](http://arxiv.org/abs/2308.13903)|null|
|**2023-08-30**|**CamP: Camera Preconditioning for Neural Radiance Fields**|Keunhong Park et.al.|[2308.10902](http://arxiv.org/abs/2308.10902)|null|
|**2023-08-18**|**Unsupervised 3D Pose Estimation with Non-Rigid Structure-from-Motion Modeling**|Haorui Ji et.al.|[2308.10705](http://arxiv.org/abs/2308.10705)|null|
|**2023-08-14**|**Large-scale environment mapping and immersive human-robot interaction for agricultural mobile robot teleoperation**|Tao Liu et.al.|[2308.07231](http://arxiv.org/abs/2308.07231)|**[link](https://github.com/liutao1126/enhance-sfm)**|
|**2023-08-11**|**Efficient Large-scale AUV-based Visual Seafloor Mapping**|Mengkun She et.al.|[2308.06147](http://arxiv.org/abs/2308.06147)|null|
|**2023-08-04**|**EDI: ESKF-based Disjoint Initialization for Visual-Inertial SLAM Systems**|Weihan Wang et.al.|[2308.02670](http://arxiv.org/abs/2308.02670)|null|
|**2023-08-15**|**Tirtha -- An Automated Platform to Crowdsource Images and Create 3D Models of Heritage Sites**|Jyotirmaya Shivottam et.al.|[2308.01246](http://arxiv.org/abs/2308.01246)|**[link](https://github.com/smlab-niser/tirtha-public)**|
|**2023-08-02**|**Stereo Visual Odometry with Deep Learning-Based Point and Line Feature Matching using an Attention Graph Neural Network**|Shenbagaraj Kannapiran et.al.|[2308.01125](http://arxiv.org/abs/2308.01125)|null|
|**2023-07-27**|**PointOdyssey: A Large-Scale Synthetic Dataset for Long-Term Point Tracking**|Yang Zheng et.al.|[2307.15055](http://arxiv.org/abs/2307.15055)|**[link](https://github.com/y-zheng18/point_odyssey)**|
|**2023-11-30**|**SACReg: Scene-Agnostic Coordinate Regression for Visual Localization**|Jerome Revaud et.al.|[2307.11702](http://arxiv.org/abs/2307.11702)|null|
|**2023-07-19**|**Lazy Visual Localization via Motion Averaging**|Siyan Dong et.al.|[2307.09981](http://arxiv.org/abs/2307.09981)|null|
|**2023-07-10**|**Efficient Match Pair Retrieval for Large-scale UAV Images via Graph Indexed Global Descriptor**|San Jiang et.al.|[2307.04520](http://arxiv.org/abs/2307.04520)|null|
|**2023-11-07**|**RGB-D Mapping and Tracking in a Plenoxel Radiance Field**|Andreas L. Teigen et.al.|[2307.03404](http://arxiv.org/abs/2307.03404)|**[link](https://github.com/ysus33/rgb-d_plenoxel_mapping_tracking)**|
|**2023-06-29**|**The Drunkard's Odometry: Estimating Camera Motion in Deforming Scenes**|David Recasens et.al.|[2306.16917](http://arxiv.org/abs/2306.16917)|**[link](https://github.com/UZ-SLAMLab/DrunkardsOdometry)**|
|**2023-06-27**|**Detector-Free Structure from Motion**|Xingyi He et.al.|[2306.15669](http://arxiv.org/abs/2306.15669)|**[link](https://github.com/zju3dv/DetectorFreeSfM)**|
|**2023-08-18**|**PoseDiffusion: Solving Pose Estimation via Diffusion-aided Bundle Adjustment**|Jianyuan Wang et.al.|[2306.15667](http://arxiv.org/abs/2306.15667)|null|
|**2023-06-24**|**3D Reconstruction of Spherical Images based on Incremental Structure from Motion**|San Jiang et.al.|[2306.12770](http://arxiv.org/abs/2306.12770)|**[link](https://github.com/json87/spheresfm)**|
|**2023-10-13**|**NAVI: Category-Agnostic Image Collections with High-Quality 3D Shape and Pose Annotations**|Varun Jampani et.al.|[2306.09109](http://arxiv.org/abs/2306.09109)|null|
|**2023-11-15**|**Yes, we CANN: Constrained Approximate Nearest Neighbors for local feature-based visual localization**|Dror Aiger et.al.|[2306.09012](http://arxiv.org/abs/2306.09012)|**[link](https://github.com/google-research/google-research)**|
|**2023-06-10**|**3D reconstruction using Structure for Motion**|Kshitij Karnawat et.al.|[2306.06360](http://arxiv.org/abs/2306.06360)|**[link](https://github.com/kshitijkarnawat/structure-from-motion)**|
|**2023-06-02**|**Self-supervised Interest Point Detection and Description for Fisheye and Perspective Images**|Marcela Mera-Trujillo et.al.|[2306.01938](http://arxiv.org/abs/2306.01938)|null|
|**2023-05-31**|**FlowCam: Training Generalizable 3D Radiance Fields without Camera Poses via Pixel-Aligned Scene Flow**|Cameron Smith et.al.|[2306.00180](http://arxiv.org/abs/2306.00180)|null|
|**2023-05-19**|**SIDAR: Synthetic Image Dataset for Alignment & Restoration**|Monika Kwiatkowski et.al.|[2305.12036](http://arxiv.org/abs/2305.12036)|**[link](https://github.com/niika/SIDAR)**|
|**2023-05-09**|**Eiffel Tower: A Deep-Sea Underwater Dataset for Long-Term Visual Localization**|Clémentin Boittiaux et.al.|[2305.05301](http://arxiv.org/abs/2305.05301)|**[link](https://github.com/clementinboittiaux/sfm-pipeline)**|
|**2023-05-09**|**Rotation Synchronization via Deep Matrix Factorization**|Gk Tejus et.al.|[2305.05268](http://arxiv.org/abs/2305.05268)|**[link](https://github.com/gktejus/DMF-Synch)**|
|**2023-04-20**|**A Comparative Neural Radiance Field (NeRF) 3D Analysis of Camera Poses from HoloLens Trajectories and Structure from Motion**|Miriam Jäger et.al.|[2304.10664](http://arxiv.org/abs/2304.10664)|null|
|**2023-07-24**|**Fusing Structure from Motion and Simulation-Augmented Pose Regression from Optical Flow for Challenging Indoor Environments**|Felix Ott et.al.|[2304.07250](http://arxiv.org/abs/2304.07250)|null|
|**2023-04-12**|**Visual Localization using Imperfect 3D Models from the Internet**|Vojtech Panek et.al.|[2304.05947](http://arxiv.org/abs/2304.05947)|**[link](https://github.com/v-pnk/cadloc)**|
|**2023-04-08**|**Photometric Correction for Infrared Sensors**|Jincheng Zhang et.al.|[2304.03930](http://arxiv.org/abs/2304.03930)|null|
|**2023-04-07**|**DualRefine: Self-Supervised Depth and Pose Estimation Through Iterative Epipolar Sampling and Refinement Toward Equilibrium**|Antyanta Bangunharcana et.al.|[2304.03560](http://arxiv.org/abs/2304.03560)|**[link](https://github.com/antabangun/dualrefine)**|
|**2023-04-05**|**Semantic Validation in Structure from Motion**|Joseph Rowell et.al.|[2304.02420](http://arxiv.org/abs/2304.02420)|**[link](https://github.com/joerowelll/comp0132_rjxz25)**|
|**2023-03-31**|**Learning Internal Representations of 3D Transformations from 2D Projected Inputs**|Marissa Connor et.al.|[2303.17776](http://arxiv.org/abs/2303.17776)|null|
|**2023-03-30**|**3D Line Mapping Revisited**|Shaohui Liu et.al.|[2303.17504](http://arxiv.org/abs/2303.17504)|**[link](https://github.com/cvg/limap)**|
|**2023-03-27**|**TMO: Textured Mesh Acquisition of Objects with a Mobile Device by using Differentiable Rendering**|Jaehoon Choi et.al.|[2303.15060](http://arxiv.org/abs/2303.15060)|null|
|**2023-03-26**|**On the Importance of Accurate Geometry Data for Dense 3D Vision Tasks**|HyunJun Jung et.al.|[2303.14840](http://arxiv.org/abs/2303.14840)|**[link](https://github.com/junggy/hammer-dataset)**|
|**2023-03-24**|**Seeing Through the Glass: Neural 3D Reconstruction of Object Inside a Transparent Container**|Jinguang Tong et.al.|[2303.13805](http://arxiv.org/abs/2303.13805)|**[link](https://github.com/hirotong/reneus)**|
|**2023-03-24**|**Progressively Optimized Local Radiance Fields for Robust View Synthesis**|Andreas Meuleman et.al.|[2303.13791](http://arxiv.org/abs/2303.13791)|null|
|**2023-03-15**|**RefiNeRF: Modelling dynamic neural radiance fields with inconsistent or missing camera parameters**|Shuja Khalid et.al.|[2303.08695](http://arxiv.org/abs/2303.08695)|null|
|**2023-03-09**|**Revisiting Rotation Averaging: Uncertainties and Robust Losses**|Ganlin Zhang et.al.|[2303.05195](http://arxiv.org/abs/2303.05195)|**[link](https://github.com/zhangganlin/globalsfmpy)**|
|**2023-02-28**|**Nonlinear Intensity, Scale and Rotation Invariant Matching for Multimodal Images**|Zhongli Fan et.al.|[2302.14239](http://arxiv.org/abs/2302.14239)|**[link](https://github.com/zhongli-fan/nisr)**|
|**2023-03-25**|**BLiRF: Bandlimited Radiance Fields for Dynamic Scene Modeling**|Sameera Ramasinghe et.al.|[2302.13543](http://arxiv.org/abs/2302.13543)|null|
|**2023-02-21**|**EC-SfM: Efficient Covisibility-based Structure-from-Motion for Both Sequential and Unordered Images**|Zhichao Ye et.al.|[2302.10544](http://arxiv.org/abs/2302.10544)|**[link](https://github.com/openxrlab/xrsfm)**|
|**2023-02-18**|**Bridge Damage Cause Estimation Using Multiple Images Based on Visual Question Answering**|Tatsuro Yamane et.al.|[2302.09208](http://arxiv.org/abs/2302.09208)|null|
|**2023-02-12**|**Uncertainty-Driven Dense Two-View Structure from Motion**|Weirong Chen et.al.|[2302.00523](http://arxiv.org/abs/2302.00523)|null|
|**2023-01-28**|**AdaSfM: From Coarse Global to Fine Incremental Adaptive Structure from Motion**|Yu Chen et.al.|[2301.12135](http://arxiv.org/abs/2301.12135)|null|
|**2023-01-20**|**A vision-based autonomous UAV inspection framework for unknown tunnel construction sites with dynamic obstacles**|Zhefan Xu et.al.|[2301.08422](http://arxiv.org/abs/2301.08422)|null|
|**2023-03-21**|**Robust Dynamic Radiance Fields**|Yu-Lun Liu et.al.|[2301.02239](http://arxiv.org/abs/2301.02239)|null|
|**2022-12-24**|**Polarimetric Multi-View Inverse Rendering**|Jinyu Zhao et.al.|[2212.12721](http://arxiv.org/abs/2212.12721)|null|
|**2022-12-13**|**Accidental Turntables: Learning 3D Pose by Watching Objects Turn**|Zezhou Cheng et.al.|[2212.06300](http://arxiv.org/abs/2212.06300)|null|
|**2022-12-04**|**3D Object Aided Self-Supervised Monocular Depth Estimation**|Songlin Wei et.al.|[2212.01768](http://arxiv.org/abs/2212.01768)|null|
|**2023-03-15**|**High-Res Facial Appearance Capture from Polarized Smartphone Images**|Dejan Azinović et.al.|[2212.01160](http://arxiv.org/abs/2212.01160)|null|
|**2023-03-28**|**FeatureBooster: Boosting Feature Descriptors with a Lightweight Neural Network**|Xinjiang Wang et.al.|[2211.15069](http://arxiv.org/abs/2211.15069)|**[link](https://github.com/sjtu-visys/featurebooster)**|
|**2022-11-24**|**JigsawPlan: Room Layout Jigsaw Puzzle Extreme Structure from Motion using Diffusion Models**|Sepidehsadat Hosseini et.al.|[2211.13785](http://arxiv.org/abs/2211.13785)|null|
|**2022-11-24**|**SfM-TTR: Using Structure from Motion for Test-Time Refinement of Single-View Depth Networks**|Sergio Izquierdo et.al.|[2211.13551](http://arxiv.org/abs/2211.13551)|null|
|**2022-11-22**|**Level-S $^2$ fM: Structure from Motion on Neural Level Set of Implicit Surfaces**|Yuxi Xiao et.al.|[2211.12018](http://arxiv.org/abs/2211.12018)|null|
|**2022-11-21**|**Towards Live 3D Reconstruction from Wearable Video: An Evaluation of V-SLAM, NeRF, and Videogrammetry Techniques**|David Ramirez et.al.|[2211.11836](http://arxiv.org/abs/2211.11836)|null|
|**2022-11-14**|**Controllable GAN Synthesis Using Non-Rigid Structure-from-Motion**|René Haas et.al.|[2211.07195](http://arxiv.org/abs/2211.07195)|null|
|**2022-10-13**|**Quantifying and analyzing rock trait distributions of rocky fault scarps using a deep learning approach**|Zhiang Chen et.al.|[2210.07349v1](http://arxiv.org/abs/2210.07349v1)|null|
|**2022-10-11**|**DeepMLE: A Robust Deep Maximum Likelihood Estimator for Two-view Structure from Motion**|Yuxi Xiao et.al.|[2210.05517v1](http://arxiv.org/abs/2210.05517v1)|null|
|**2022-10-07**|**Leveraging Structure from Motion to Localize Inaccessible Bus Stops**|Indu Panigrahi et.al.|[2210.03646v1](http://arxiv.org/abs/2210.03646v1)|**[link](https://github.com/ind1010/SfM_for_BusEdge)**|
|**2022-10-01**|**Structure-Aware NeRF without Posed Camera via Epipolar Constraint**|Shu Chen et.al.|[2210.00183v1](http://arxiv.org/abs/2210.00183v1)|**[link](https://github.com/xtu-pr-lab/sanerf)**|
|**2022-10-05**|**FAST-LIO, Then Bayesian ICP, Then GTSFM**|Jerred Chen et.al.|[2210.00146v2](http://arxiv.org/abs/2210.00146v2)|null|
|**2022-09-20**|**BuFF: Burst Feature Finder for Light-Constrained 3D Reconstruction**|Ahalya Ravendran et.al.|[2209.09470v1](http://arxiv.org/abs/2209.09470v1)|null|
|**2022-09-19**|**A Hybrid Cable-Driven Robot for Non-Destructive Leafy Plant Monitoring and Mass Estimation using Structure from Motion**|Gerry Chen et.al.|[2209.08690v1](http://arxiv.org/abs/2209.08690v1)|null|
|**2022-09-14**|**End-to-End Multi-View Structure-from-Motion with Hypercorrelation Volumes**|Qiao Chen et.al.|[2209.06926v1](http://arxiv.org/abs/2209.06926v1)|null|
|**2022-09-07**|**Deployment of Aerial Robots during the Flood Disaster in Erftstadt / Blessem in July 2021**|Hartmut Surmann et.al.|[2209.03084v1](http://arxiv.org/abs/2209.03084v1)|null|
|**2022-08-27**|**Weakly and Semi-Supervised Detection, Segmentation and Tracking of Table Grapes with Limited and Noisy Data**|Thomas A. Ciarfuglia et.al.|[2208.13001v1](http://arxiv.org/abs/2208.13001v1)|null|
|**2022-08-12**|**Handling Constrained Optimization in Factor Graphs for Autonomous Navigation**|Barbara Bazzana et.al.|[2208.06325v1](http://arxiv.org/abs/2208.06325v1)|null|
|**2022-08-04**|**Globally Consistent Video Depth and Pose Estimation with Efficient Test-Time Training**|Yao-Chih Lee et.al.|[2208.02709v1](http://arxiv.org/abs/2208.02709v1)|**[link](https://github.com/yaochih/gcvd-release)**|
|**2022-07-31**|**One Object at a Time: Accurate and Robust Structure From Motion for Robots**|Aravind Battaje et.al.|[2208.00487v1](http://arxiv.org/abs/2208.00487v1)|null|
|**2022-07-23**|**Detection and Initial Assessment of Lunar Landing Sites Using Neural Networks**|Daniel Posada et.al.|[2207.11413v1](http://arxiv.org/abs/2207.11413v1)|null|
|**2022-07-25**|**MeshLoc: Mesh-Based Visual Localization**|Vojtech Panek et.al.|[2207.10762v2](http://arxiv.org/abs/2207.10762v2)|**[link](https://github.com/tsattler/meshloc_release)**|
|**2022-07-19**|**ParticleSfM: Exploiting Dense Point Trajectories for Localizing Moving Cameras in the Wild**|Wang Zhao et.al.|[2207.09137v1](http://arxiv.org/abs/2207.09137v1)|**[link](https://github.com/bytedance/particle-sfm)**|
|**2022-07-16**|**Organic Priors in Non-Rigid Structure from Motion**|Suryansh Kumar et.al.|[2207.06262v3](http://arxiv.org/abs/2207.06262v3)|null|
|**2022-07-06**|**A Novel Hybrid Endoscopic Dataset for Evaluating Machine Learning-based Photometric Image Enhancement Models**|Axel Garcia-Vega et.al.|[2207.02396v1](http://arxiv.org/abs/2207.02396v1)|null|
|**2022-06-24**|**Parallel Structure from Motion for UAV Images via Weighted Connected Dominating Set**|San Jiang et.al.|[2206.11499v2](http://arxiv.org/abs/2206.11499v2)|null|
|**2022-06-13**|**TC-SfM: Robust Track-Community-Based Structure-from-Motion**|Lei Wang et.al.|[2206.05866v1](http://arxiv.org/abs/2206.05866v1)|null|
|**2022-06-10**|**EigenFairing: 3D Model Fairing using Image Coherence**|Pragyana Mishra et.al.|[2206.05309v1](http://arxiv.org/abs/2206.05309v1)|null|
|**2022-06-01**|**Semantic Room Wireframe Detection from a Single View**|David Gillsjö et.al.|[2206.00491v1](http://arxiv.org/abs/2206.00491v1)|**[link](https://github.com/davidgillsjo/srw-net)**|
|**2022-05-31**|**Geo-Neus: Geometry-Consistent Neural Implicit Surfaces Learning for Multi-view Reconstruction**|Qiancheng Fu et.al.|[2205.15848v1](http://arxiv.org/abs/2205.15848v1)|null|
|**2022-05-09**|**Is my Depth Ground-Truth Good Enough? HAMMER -- Highly Accurate Multi-Modal Dataset for DEnse 3D Scene Regression**|HyunJun Jung et.al.|[2205.04565v1](http://arxiv.org/abs/2205.04565v1)|null|
|**2022-05-07**|**Optimizing Terrain Mapping and Landing Site Detection for Autonomous UAVs**|Pedro F. Proença et.al.|[2205.03522v1](http://arxiv.org/abs/2205.03522v1)|null|
|**2022-05-06**|**EVIMO2: An Event Camera Dataset for Motion Segmentation, Optical Flow, Structure from Motion, and Visual Inertial Odometry in Indoor Scenes with Monocular or Stereo Algorithms**|Levi Burner et.al.|[2205.03467v1](http://arxiv.org/abs/2205.03467v1)|null|
|**2022-04-20**|**Learned Monocular Depth Priors in Visual-Inertial Initialization**|Yunwen Zhou et.al.|[2204.09171v1](http://arxiv.org/abs/2204.09171v1)|null|
|**2022-04-10**|**Deep Non-rigid Structure-from-Motion: A Sequence-to-Sequence Translation Perspective**|Hui Deng et.al.|[2204.04730v1](http://arxiv.org/abs/2204.04730v1)|null|
|**2022-04-08**|**Constrained Bundle Adjustment for Structure From Motion Using Uncalibrated Multi-Camera Systems**|Debao Huang et.al.|[2204.04145v1](http://arxiv.org/abs/2204.04145v1)|null|
|**2022-04-07**|**SurroundDepth: Entangling Surrounding Views for Self-Supervised Multi-Camera Depth Estimation**|Yi Wei et.al.|[2204.03636v1](http://arxiv.org/abs/2204.03636v1)|**[link](https://github.com/weiyithu/surrounddepth)**|
|**2022-04-06**|**Georeferencing of Photovoltaic Modules from Aerial Infrared Videos using Structure-from-Motion**|Lukas Bommes et.al.|[2204.02733v1](http://arxiv.org/abs/2204.02733v1)|**[link](https://github.com/lukasbommes/pv-hawk)**|
|**2022-04-05**|**Depth-Guided Sparse Structure-from-Motion for Movies and TV Shows**|Sheng Liu et.al.|[2204.02509v1](http://arxiv.org/abs/2204.02509v1)|**[link](https://github.com/amazon-research/small-baseline-camera-tracking)**|
|**2022-03-31**|**Fast, Accurate and Memory-Efficient Partial Permutation Synchronization**|Shaohan Li et.al.|[2203.16505v2](http://arxiv.org/abs/2203.16505v2)|null|
|**2022-03-28**|**Visual Odometry for RGB-D Cameras**|Afonso Fontes et.al.|[2203.15119v1](http://arxiv.org/abs/2203.15119v1)|null|
|**2022-03-28**|**Optimizing Elimination Templates by Greedy Parameter Search**|Evgeniy Martyushev et.al.|[2203.14901v1](http://arxiv.org/abs/2203.14901v1)|**[link](https://github.com/martyushev/eliminationtemplates)**|
|**2022-03-23**|**Event-Based Dense Reconstruction Pipeline**|Kun Xiao et.al.|[2203.12270v1](http://arxiv.org/abs/2203.12270v1)|null|
|**2022-03-21**|**DiffPoseNet: Direct Differentiable Camera Pose Estimation**|Chethan M. Parameshwara et.al.|[2203.11174v1](http://arxiv.org/abs/2203.11174v1)|null|
|**2022-03-02**|**Asynchronous Optimisation for Event-based Visual Odometry**|Daqi Liu et.al.|[2203.01037v1](http://arxiv.org/abs/2203.01037v1)|null|
|**2022-03-02**|**Distributed Riemannian Optimization with Lazy Communication for Collaborative Geometric Estimation**|Yulun Tian et.al.|[2203.00851v1](http://arxiv.org/abs/2203.00851v1)|null|
|**2022-02-18**|**MultiRes-NetVLAD: Augmenting Place Recognition Training with Low-Resolution Imagery**|Ahmad Khaliq et.al.|[2202.09146v1](http://arxiv.org/abs/2202.09146v1)|**[link](https://github.com/ahmedest61/multires-netvlad)**|
|**2022-01-20**|**GeoFill: Reference-Based Image Inpainting of Scenes with Complex Geometry**|Yunhan Zhao et.al.|[2201.08131v1](http://arxiv.org/abs/2201.08131v1)|null|
|**2022-01-13**|**Scalable Cluster-Consistency Statistics for Robust Multi-Object Matching**|Yunpeng Shi et.al.|[2201.04797v1](http://arxiv.org/abs/2201.04797v1)|**[link](https://github.com/yunpeng-shi/fcc)**|
|**2022-01-10**|**High-resolution Ecosystem Mapping in Repetitive Environments Using Dual Camera SLAM**|Brian M. Hopkinson et.al.|[2201.03364v1](http://arxiv.org/abs/2201.03364v1)|**[link](https://github.com/bmhopkinson/hyslam)**|
|**2022-01-06**|**De-rendering 3D Objects in the Wild**|Felix Wimbauer et.al.|[2201.02279v1](http://arxiv.org/abs/2201.02279v1)|**[link](https://github.com/brummi/derender3d)**|
|**2021-12-29**|**On the Instability of Relative Pose Estimation and RANSAC's Role**|Hongyi Fan et.al.|[2112.14651v1](http://arxiv.org/abs/2112.14651v1)|null|
|**2021-12-16**|**Road-aware Monocular Structure from Motion and Homography Estimation**|Wei Sui et.al.|[2112.08635v1](http://arxiv.org/abs/2112.08635v1)|null|
|**2021-12-10**|**Critical configurations for three projective views**|Martin Bråtelund et.al.|[2112.05478v1](http://arxiv.org/abs/2112.05478v1)|null|
|**2021-12-09**|**Critical configurations for two projective views, a new approach**|Martin Bråtelund et.al.|[2112.05074v1](http://arxiv.org/abs/2112.05074v1)|null|
|**2021-12-06**|**Dense Depth Priors for Neural Radiance Fields from Sparse Input Views**|Barbara Roessle et.al.|[2112.03288v1](http://arxiv.org/abs/2112.03288v1)|**[link](https://github.com/barbararoessle/dense_depth_priors_nerf)**|
|**2021-12-10**|**MegBA: A High-Performance and Distributed Library for Large-Scale Bundle Adjustment**|Jie Ren et.al.|[2112.01349v2](http://arxiv.org/abs/2112.01349v2)|**[link](https://github.com/megviirobot/megba)**|
|**2021-11-11**|**Multi-Resolution Elevation Mapping and Safe Landing Site Detection with Applications to Planetary Rotorcraft**|Pascal Schoppmann et.al.|[2111.06271v1](http://arxiv.org/abs/2111.06271v1)|null|
|**2021-11-10**|**Damage Estimation and Localization from Sparse Aerial Imagery**|Rene Garcia Franceschini et.al.|[2111.03708v2](http://arxiv.org/abs/2111.03708v2)|null|
|**2021-11-03**|**Event and Activity Recognition in Video Surveillance for Cyber-Physical Systems**|Swarnabja Bhaumik et.al.|[2111.02064v1](http://arxiv.org/abs/2111.02064v1)|null|
|**2021-10-14**|**Modeling dynamic target deformation in camera calibration**|Annika Hagemann et.al.|[2110.07322v1](http://arxiv.org/abs/2110.07322v1)|null|
|**2021-10-13**|**Hyperspectral 3D Mapping of Underwater Environments**|Maxime Ferrera et.al.|[2110.06571v1](http://arxiv.org/abs/2110.06571v1)|null|
|**2021-09-24**|**Automatic Map Update Using Dashcam Videos**|Aziza Zhanabatyrova et.al.|[2109.12131v1](http://arxiv.org/abs/2109.12131v1)|null|
|**2021-09-16**|**Rotation Averaging in a Split Second: A Primal-Dual Method and a Closed-Form for Cycle Graphs**|Gabriel Moreira et.al.|[2109.08046v1](http://arxiv.org/abs/2109.08046v1)|**[link](https://github.com/gabmoreira/maks)**|
|**2021-09-06**|**Single-Camera 3D Head Fitting for Mixed Reality Clinical Applications**|Tejas Mane et.al.|[2109.02740v1](http://arxiv.org/abs/2109.02740v1)|null|
|**2021-09-02**|**Dynamic Scene Novel View Synthesis via Deferred Spatio-temporal Consistency**|Beatrix-Emőke Fülöp-Balogh et.al.|[2109.01018v1](http://arxiv.org/abs/2109.01018v1)|null|
|**2021-09-01**|**On the Limits of Pseudo Ground Truth in Visual Camera Re-localisation**|Eric Brachmann et.al.|[2109.00524v1](http://arxiv.org/abs/2109.00524v1)|**[link](https://github.com/tsattler/visloc_pseudo_gt_limitations)**|
|**2021-08-31**|**DensePose 3D: Lifting Canonical Surface Maps of Articulated Objects to the Third Dimension**|Roman Shapovalov et.al.|[2109.00033v1](http://arxiv.org/abs/2109.00033v1)|null|
|**2021-08-29**|**Solving Viewing Graph Optimization for Simultaneous Position and Rotation Registration**|Seyed-Mahdi Nasiri et.al.|[2108.12876v1](http://arxiv.org/abs/2108.12876v1)|null|
|**2021-08-23**|**Burst Imaging for Light-Constrained Structure-From-Motion**|Ahalya Ravendran et.al.|[2108.09895v1](http://arxiv.org/abs/2108.09895v1)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Visual Localization

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2023-03-22**|**Reliable and Efficient Evaluation of Adversarial Robustness for Deep Hashing-Based Retrieval**|Xunguang Wang et.al.|[2303.12658](http://arxiv.org/abs/2303.12658)|null|
|**2023-03-21**|**CompoDiff: Versatile Composed Image Retrieval With Latent Diffusion**|Geonmo Gu et.al.|[2303.11916](http://arxiv.org/abs/2303.11916)|null|
|**2023-03-21**|**LIMITR: Leveraging Local Information for Medical Image-Text Representation**|Gefen Dawidowicz et.al.|[2303.11755](http://arxiv.org/abs/2303.11755)|null|
|**2023-03-21**|**Data-efficient Large Scale Place Recognition with Graded Similarity Supervision**|Maria Leyva-Vallina et.al.|[2303.11739](http://arxiv.org/abs/2303.11739)|**[link](https://github.com/marialeyvallina/generalized_contrastive_loss)**|
|**2023-03-20**|**Picture that Sketch: Photorealistic Image Generation from Abstract Sketches**|Subhadeep Koley et.al.|[2303.11162](http://arxiv.org/abs/2303.11162)|null|
|**2023-03-19**|**Deep Declarative Dynamic Time Warping for End-to-End Learning of Alignment Paths**|Ming Xu et.al.|[2303.10778](http://arxiv.org/abs/2303.10778)|**[link](https://github.com/mingu6/declarativedtw)**|
|**2023-03-17**|**MRIS: A Multi-modal Retrieval Approach for Image Synthesis on Diverse Modalities**|Boqi Chen et.al.|[2303.10249](http://arxiv.org/abs/2303.10249)|null|
|**2023-03-17**|**IRGen: Generative Modeling for Image Retrieval**|Yidan Zhang et.al.|[2303.10126](http://arxiv.org/abs/2303.10126)|null|
|**2023-03-16**|**Data Roaming and Early Fusion for Composed Image Retrieval**|Matan Levy et.al.|[2303.09429](http://arxiv.org/abs/2303.09429)|null|
|**2023-03-16**|**Towards a Smaller Student: Capacity Dynamic Distillation for Efficient Image Retrieval**|Yi Xie et.al.|[2303.09230](http://arxiv.org/abs/2303.09230)|null|
|**2023-03-16**|**Metric-Free Exploration for Topological Mapping by Task and Motion Imitation in Feature Space**|Yuhang He et.al.|[2303.09192](http://arxiv.org/abs/2303.09192)|null|
|**2023-03-16**|**Unsupervised Facial Expression Representation Learning with Contrastive Local Warping**|Fanglei Xue et.al.|[2303.09034](http://arxiv.org/abs/2303.09034)|null|
|**2023-03-15**|**A Triplet-loss Dilated Residual Network for High-Resolution Representation Learning in Image Retrieval**|Saeideh Yousefzadeh et.al.|[2303.08398](http://arxiv.org/abs/2303.08398)|null|
|**2023-03-14**|**Data-Free Sketch-Based Image Retrieval**|Abhra Chaudhuri et.al.|[2303.07775](http://arxiv.org/abs/2303.07775)|null|
|**2023-03-14**|**PATS: Patch Area Transportation with Subdivision for Local Feature Matching**|Junjie Ni et.al.|[2303.07700](http://arxiv.org/abs/2303.07700)|null|
|**2023-03-10**|**Robotic Applications of Pre-Trained Vision-Language Models to Various Recognition Behaviors**|Kento Kawaharazuka et.al.|[2303.05674](http://arxiv.org/abs/2303.05674)|null|
|**2023-03-09**|**Dominating Set Database Selection for Visual Place Recognition**|Anastasiia Kornilova et.al.|[2303.05123](http://arxiv.org/abs/2303.05123)|null|
|**2023-03-07**|**Graph Neural Networks in Vision-Language Image Understanding: A Survey**|Henry Senior et.al.|[2303.03761](http://arxiv.org/abs/2303.03761)|null|
|**2023-03-07**|**Sketch-based Medical Image Retrieval**|Kazuma Kobayashi et.al.|[2303.03633](http://arxiv.org/abs/2303.03633)|null|
|**2023-03-06**|**Visual Place Recognition: A Tutorial**|Stefan Schubert et.al.|[2303.03281](http://arxiv.org/abs/2303.03281)|**[link](https://github.com/stschubert/vpr_tutorial)**|
|**2023-03-06**|**MABNet: Master Assistant Buddy Network with Hybrid Learning for Image Retrieval**|Rohit Agarwal et.al.|[2303.03050](http://arxiv.org/abs/2303.03050)|**[link](https://github.com/rohit102497/mabnet)**|
|**2023-03-06**|**Improving Transformer-based Image Matching by Cascaded Capturing Spatially Informative Keypoints**|Chenjie Cao et.al.|[2303.02885](http://arxiv.org/abs/2303.02885)|null|
|**2023-03-05**|**Composing Mood Board with User Feedback in Concept Space**|Shin Sano et.al.|[2303.02547](http://arxiv.org/abs/2303.02547)|null|
|**2023-03-04**|**FAME-ViL: Multi-Tasking Vision-Language Model for Heterogeneous Fashion Tasks**|Xiao Han et.al.|[2303.02483](http://arxiv.org/abs/2303.02483)|**[link](https://github.com/brandonhanx/fame-vil)**|
|**2023-03-09**|**Self-Supervised Learning for Place Representation Generalization across Appearance Changes**|Mohamed Adel Musallam et.al.|[2303.02370](http://arxiv.org/abs/2303.02370)|null|
|**2023-03-03**|**MixVPR: Feature Mixing for Visual Place Recognition**|Amar Ali-bey et.al.|[2303.02190](http://arxiv.org/abs/2303.02190)|**[link](https://github.com/amaralibey/mixvpr)**|
|**2023-03-01**|**A Complementarity-Based Switch-Fuse System for Improved Visual Place Recognition**|Maria Waheed et.al.|[2303.00714](http://arxiv.org/abs/2303.00714)|null|
|**2023-03-01**|**ORCHNet: A Robust Global Feature Aggregation approach for 3D LiDAR-based Place recognition in Orchards**|T. Barros et.al.|[2303.00477](http://arxiv.org/abs/2303.00477)|**[link](https://github.com/cybonic/orchnet)**|
|**2023-03-03**|**Renderable Neural Radiance Map for Visual Navigation**|Obin Kwon et.al.|[2303.00304](http://arxiv.org/abs/2303.00304)|null|
|**2023-03-01**|**Region Prediction for Efficient Robot Localization on Large Maps**|Matteo Scucchia et.al.|[2303.00295](http://arxiv.org/abs/2303.00295)|null|
|**2023-02-28**|**OEKG: The Open Event Knowledge Graph**|Simon Gottschalk et.al.|[2302.14688](http://arxiv.org/abs/2302.14688)|null|
|**2023-02-28**|**Global Proxy-based Hard Mining for Visual Place Recognition**|Amar Ali-bey et.al.|[2302.14217](http://arxiv.org/abs/2302.14217)|**[link](https://github.com/amaralibey/gpm)**|
|**2023-02-27**|**Efficient Informed Proposals for Discrete Distributions via Newton's Series Approximation**|Yue Xiang et.al.|[2302.13929](http://arxiv.org/abs/2302.13929)|**[link](https://github.com/dongyaozhu/newton-proposal-for-discrete-sampling)**|
|**2023-02-26**|**Data-Efficient Sequence-Based Visual Place Recognition with Highly Compressed JPEG Images**|Mihnea-Alexandru Tomita et.al.|[2302.13314](http://arxiv.org/abs/2302.13314)|null|
|**2023-02-26**|**Learning cross space mapping via DNN using large scale click-through logs**|Wei Yu et.al.|[2302.13275](http://arxiv.org/abs/2302.13275)|null|
|**2023-02-25**|**DeepBrainPrint: A Novel Contrastive Framework for Brain MRI Re-Identification**|Lemuel Puglisi et.al.|[2302.13057](http://arxiv.org/abs/2302.13057)|null|
|**2023-02-23**|**Teaching CLIP to Count to Ten**|Roni Paiss et.al.|[2302.12066v1](http://arxiv.org/abs/2302.12066v1)|null|
|**2023-02-22**|**Steerable Equivariant Representation Learning**|Sangnie Bhardwaj et.al.|[2302.11349v1](http://arxiv.org/abs/2302.11349v1)|null|
|**2023-02-21**|**iQPP: A Benchmark for Image Query Performance Prediction**|Eduard Poesina et.al.|[2302.10126v2](http://arxiv.org/abs/2302.10126v2)|**[link](https://github.com/eduard6421/iqpp)**|
|**2023-02-20**|**Ontology-aware Network for Zero-shot Sketch-based Image Retrieval**|Haoxiang Zhang et.al.|[2302.10040v1](http://arxiv.org/abs/2302.10040v1)|null|
|**2023-02-20**|**TBPos: Dataset for Large-Scale Precision Visual Localization**|Masud Fahim et.al.|[2302.09825v1](http://arxiv.org/abs/2302.09825v1)|null|
|**2023-02-17**|**Towards Unifying Medical Vision-and-Language Pre-training via Soft Prompts**|Zhihong Chen et.al.|[2302.08958v1](http://arxiv.org/abs/2302.08958v1)|**[link](https://github.com/zhjohnchan/ptunifier)**|
|**2023-02-22**|**Fashion Image Retrieval with Multi-Granular Alignment**|Jinkuan Zhu et.al.|[2302.08902v2](http://arxiv.org/abs/2302.08902v2)|null|
|**2023-02-15**|**Unsupervised Hashing via Similarity Distribution Calibration**|Kam Woh Ng et.al.|[2302.07669v1](http://arxiv.org/abs/2302.07669v1)|**[link](https://github.com/kamwoh/sdc)**|
|**2023-02-13**|**Render-and-Compare: Cross-View 6 DoF Localization from Noisy Prior**|Shen Yan et.al.|[2302.06287v1](http://arxiv.org/abs/2302.06287v1)|null|
|**2023-02-13**|**Contour Context: Abstract Structural Distribution for 3D LiDAR Loop Detection and Metric Pose Estimation**|Binqian Jiang et.al.|[2302.06149v1](http://arxiv.org/abs/2302.06149v1)|**[link](https://github.com/lewisjiang/contour-context)**|
|**2023-02-13**|**Correspondence-Free Domain Alignment for Unsupervised Cross-Domain Image Retrieval**|Xu Wang et.al.|[2302.06081v1](http://arxiv.org/abs/2302.06081v1)|null|
|**2023-02-11**|**Sketch Less Face Image Retrieval: A New Challenge**|Dawei Dai et.al.|[2302.05576v1](http://arxiv.org/abs/2302.05576v1)|**[link](https://github.com/ddw2aigroup2cqupt/slfir)**|
|**2023-02-10**|**Is multi-modal vision supervision beneficial to language?**|Avinash Madasu et.al.|[2302.05016v1](http://arxiv.org/abs/2302.05016v1)|null|
|**2023-02-06**|**Pic2Word: Mapping Pictures to Words for Zero-shot Composed Image Retrieval**|Kuniaki Saito et.al.|[2302.03084v1](http://arxiv.org/abs/2302.03084v1)|**[link](https://github.com/google-research/composed_image_retrieval)**|
|**2023-02-06**|**Probabilistic Contrastive Learning Recovers the Correct Aleatoric Uncertainty of Ambiguous Inputs**|Michael Kirchhof et.al.|[2302.02865v1](http://arxiv.org/abs/2302.02865v1)|**[link](https://github.com/mkirchhof/probabilistic_contrastive_learning)**|
|**2023-02-03**|**Simple, Effective and General: A New Backbone for Cross-view Image Geo-localization**|Yingying Zhu et.al.|[2302.01572v1](http://arxiv.org/abs/2302.01572v1)|**[link](https://github.com/yanghongji2007/saig)**|
|**2023-02-04**|**Bayesian Metric Learning for Uncertainty Quantification in Image Retrieval**|Frederik Warburg et.al.|[2302.01332v2](http://arxiv.org/abs/2302.01332v2)|**[link](https://github.com/frederikwarburg/bayesian-metric-learning)**|
|**2023-01-31**|**Grounding Language Models to Images for Multimodal Generation**|Jing Yu Koh et.al.|[2301.13823v1](http://arxiv.org/abs/2301.13823v1)|**[link](https://github.com/kohjingyu/fromage)**|
|**2023-01-31**|**UPop: Unified and Progressive Pruning for Compressing Vision-Language Transformers**|Dachuan Shi et.al.|[2301.13741v1](http://arxiv.org/abs/2301.13741v1)|null|
|**2023-01-23**|**Lexi: Self-Supervised Learning of the UI Language**|Pratyay Banerjee et.al.|[2301.10165v1](http://arxiv.org/abs/2301.10165v1)|**[link](https://github.com/microsoft/uicaption)**|
|**2023-01-17**|**Distribution Aligned Feature Clustering for Zero-Shot Sketch-Based Image Retrieval**|Yuchen Wu et.al.|[2301.06685v1](http://arxiv.org/abs/2301.06685v1)|null|
|**2023-01-19**|**High-bandwidth Close-Range Information Transport through Light Pipes**|Joowon Lim et.al.|[2301.06496v2](http://arxiv.org/abs/2301.06496v2)|null|
|**2023-01-13**|**A LiDAR-Inertial-Visual SLAM System with Loop Detection**|Kangcheng Liu et.al.|[2301.05604v1](http://arxiv.org/abs/2301.05604v1)|null|
|**2023-01-12**|**GH-Feat: Learning Versatile Generative Hierarchical Features from GANs**|Yinghao Xu et.al.|[2301.05315v1](http://arxiv.org/abs/2301.05315v1)|null|
|**2023-01-10**|**Pix2Map: Cross-modal Retrieval for Inferring Street Maps from Images**|Xindi Wu et.al.|[2301.04224v1](http://arxiv.org/abs/2301.04224v1)|null|
|**2023-01-10**|**Collaborative Semantic Communication at the Edge**|Wing Fei Lo et.al.|[2301.03996v1](http://arxiv.org/abs/2301.03996v1)|null|
|**2023-01-10**|**Online Backfilling with No Regret for Large-Scale Image Retrieval**|Seonguk Seo et.al.|[2301.03767v1](http://arxiv.org/abs/2301.03767v1)|null|
|**2023-01-06**|**CyberLoc: Towards Accurate Long-term Visual Localization**|Liu Liu et.al.|[2301.02403v1](http://arxiv.org/abs/2301.02403v1)|null|
|**2023-01-05**|**A Probabilistic Framework for Visual Localization in Ambiguous Scenes**|Fereidoon Zangeneh et.al.|[2301.02086v1](http://arxiv.org/abs/2301.02086v1)|**[link](https://github.com/efreidun/vapor)**|
|**2022-12-31**|**4Seasons: Benchmarking Visual SLAM and Long-Term Localization for Autonomous Driving in Challenging Conditions**|Patrick Wenzel et.al.|[2301.01147v1](http://arxiv.org/abs/2301.01147v1)|null|
|**2022-12-30**|**HPointLoc: Point-based Indoor Place Recognition using Synthetic RGB-D Images**|Dmitry Yudin et.al.|[2212.14649v1](http://arxiv.org/abs/2212.14649v1)|**[link](https://github.com/metra4ok/hpointloc)**|
|**2022-12-27**|**Noise-aware Learning from Web-crawled Image-Text Data for Image Captioning**|Wooyoung Kang et.al.|[2212.13563v1](http://arxiv.org/abs/2212.13563v1)|**[link](https://github.com/kakaobrain/noc)**|
|**2022-12-23**|**SuperGF: Unifying Local and Global Features for Visual Localization**|Wenzheng Song et.al.|[2212.13105v1](http://arxiv.org/abs/2212.13105v1)|null|
|**2022-12-24**|**GraffMatch: Global Matching of 3D Lines and Planes for Wide Baseline LiDAR Registration**|Parker C. Lusk et.al.|[2212.12745v1](http://arxiv.org/abs/2212.12745v1)|null|
|**2022-12-19**|**From a Bird's Eye View to See: Joint Camera and Subject Registration without the Camera Calibration**|Zekun Qian et.al.|[2212.09298v1](http://arxiv.org/abs/2212.09298v1)|null|
|**2022-12-14**|**The Infinite Index: Information Retrieval on Generative Text-To-Image Models**|Niklas Deckers et.al.|[2212.07476v1](http://arxiv.org/abs/2212.07476v1)|null|
|**2022-12-14**|**Shared Coupling-bridge for Weakly Supervised Local Feature Learning**|Jiayuan Sun et.al.|[2212.07047v1](http://arxiv.org/abs/2212.07047v1)|**[link](https://github.com/sunjiayuanro/scfeat)**|
|**2022-12-08**|**Group Generalized Mean Pooling for Vision Transformer**|Byungsoo Ko et.al.|[2212.04114v1](http://arxiv.org/abs/2212.04114v1)|null|
|**2022-12-12**|**Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models**|Gowthami Somepalli et.al.|[2212.03860v3](http://arxiv.org/abs/2212.03860v3)|null|
|**2022-12-07**|**LSVL: Large-scale season-invariant visual localization for UAVs**|Jouko Kinnari et.al.|[2212.03581v1](http://arxiv.org/abs/2212.03581v1)|null|
|**2022-12-06**|**ADIR: Adaptive Diffusion for Image Reconstruction**|Shady Abu-Hussein et.al.|[2212.03221v1](http://arxiv.org/abs/2212.03221v1)|null|
|**2022-12-08**|**Privacy-Preserving Visual Localization with Event Cameras**|Junho Kim et.al.|[2212.03177v2](http://arxiv.org/abs/2212.03177v2)|**[link](https://github.com/82magnolia/event_localization)**|
|**2022-12-06**|**Semantic Communication for Internet of Vehicles: A Multi-User Cooperative Approach**|Wenjun Xu et.al.|[2212.03037v1](http://arxiv.org/abs/2212.03037v1)|null|
|**2022-12-06**|**Attention-Enhanced Cross-modal Localization Between 360 Images and Point Clouds**|Zhipeng Zhao et.al.|[2212.02757v1](http://arxiv.org/abs/2212.02757v1)|null|
|**2022-12-04**|**Fast and Lightweight Scene Regressor for Camera Relocalization**|Thuan B. Bui et.al.|[2212.01830v1](http://arxiv.org/abs/2212.01830v1)|**[link](https://github.com/ais-lab/feat2map)**|
|**2022-12-02**|**Information Retrieval from the Digitized Books**|Riya Gupta et.al.|[2212.00999v1](http://arxiv.org/abs/2212.00999v1)|null|
|**2022-12-09**|**StructVPR: Distill Structural Knowledge with Weighting Samples for Visual Place Recognition**|Yanqing Shen et.al.|[2212.00937v2](http://arxiv.org/abs/2212.00937v2)|null|
|**2022-11-30**|**Self-Supervised Feature Learning for Long-Term Metric Visual Localization**|Yuxuan Chen et.al.|[2212.00122v1](http://arxiv.org/abs/2212.00122v1)|null|
|**2022-11-30**|**SGDraw: Scene Graph Drawing Interface Using Object-Oriented Representation**|Tianyu Zhang et.al.|[2211.16697v1](http://arxiv.org/abs/2211.16697v1)|null|
|**2022-11-28**|**SLAN: Self-Locator Aided Network for Cross-Modal Understanding**|Jiang-Tian Zhai et.al.|[2211.16208v1](http://arxiv.org/abs/2211.16208v1)|null|
|**2022-11-29**|**RankDNN: Learning to Rank for Few-shot Learning**|Qianyu Guo et.al.|[2211.15320v2](http://arxiv.org/abs/2211.15320v2)|**[link](https://github.com/guoqianyu-alberta/rankdnn)**|
|**2022-11-28**|**Safety-quantifiable Line Feature-based Monocular Visual Localization with 3D Prior Map**|Xi Zheng et.al.|[2211.15127v1](http://arxiv.org/abs/2211.15127v1)|null|
|**2022-11-28**|**FeatureBooster: Boosting Feature Descriptors with a Lightweight Neural Network**|Xinjiang Wang et.al.|[2211.15069v1](http://arxiv.org/abs/2211.15069v1)|null|
|**2022-11-27**|**BEV-Locator: An End-to-end Visual Semantic Localization Network Using Multi-View Images**|Zhihuang Zhang et.al.|[2211.14927v1](http://arxiv.org/abs/2211.14927v1)|null|
|**2022-11-27**|**A Faster, Lighter and Stronger Deep Learning-Based Approach for Place Recognition**|Rui Huang et.al.|[2211.14864v1](http://arxiv.org/abs/2211.14864v1)|null|
|**2022-11-26**|**Visual Place Recognition**|Bailu Guo et.al.|[2211.14533v1](http://arxiv.org/abs/2211.14533v1)|null|
|**2022-11-26**|**Instance-level Heterogeneous Domain Adaptation for Limited-labeled Sketch-to-Photo Retrieval**|Fan Yang et.al.|[2211.14515v1](http://arxiv.org/abs/2211.14515v1)|**[link](https://github.com/fandulu/IHDA)**|
|**2022-11-30**|**Roboflow 100: A Rich, Multi-Domain Object Detection Benchmark**|Floriana Ciaglia et.al.|[2211.13523v3](http://arxiv.org/abs/2211.13523v3)|**[link](https://github.com/roboflow-ai/roboflow-100-benchmark)**|
|**2022-11-23**|**InDiReCT: Language-Guided Zero-Shot Deep Metric Learning for Images**|Konstantin Kobs et.al.|[2211.12760v1](http://arxiv.org/abs/2211.12760v1)|**[link](https://github.com/lsx-uniwue/indirect)**|
|**2022-11-29**|**Wild-Places: A Large-Scale Dataset for Lidar Place Recognition in Unstructured Natural Environments**|Joshua Knights et.al.|[2211.12732v2](http://arxiv.org/abs/2211.12732v2)|null|
|**2022-11-23**|**FE-Fusion-VPR: Attention-based Multi-Scale Network Architecture for Visual Place Recognition by Fusing Frames and Events**|Kuanxu Hou et.al.|[2211.12244v2](http://arxiv.org/abs/2211.12244v2)|null|
|**2022-11-22**|**Multimorbidity Content-Based Medical Image Retrieval Using Proxies**|Yunyan Xing et.al.|[2211.12185v1](http://arxiv.org/abs/2211.12185v1)|null|
|**2022-11-22**|**Vision-based localization methods under GPS-denied conditions**|Zihao Lu et.al.|[2211.11988v1](http://arxiv.org/abs/2211.11988v1)|null|
|**2022-11-21**|**ESLAM: Efficient Dense SLAM System Based on Hybrid Representation of Signed Distance Fields**|Mohammad Mahdi Johari et.al.|[2211.11704v1](http://arxiv.org/abs/2211.11704v1)|null|
|**2022-11-21**|**LISA: Localized Image Stylization with Audio via Implicit Neural Representation**|Seung Hyun Lee et.al.|[2211.11381v1](http://arxiv.org/abs/2211.11381v1)|null|
|**2022-11-21**|**NeuMap: Neural Coordinate Mapping by Auto-Transdecoder for Camera Localization**|Shitao Tang et.al.|[2211.11177v1](http://arxiv.org/abs/2211.11177v1)|**[link](https://github.com/tangshitao/neumap)**|
|**2022-11-16**|**Improving Feature-based Visual Localization by Geometry-Aided Matching**|Hailin Yu et.al.|[2211.08712v1](http://arxiv.org/abs/2211.08712v1)|**[link](https://github.com/openxrlab/xrlocalization)**|
|**2022-11-15**|**LiePoseNet: Heterogeneous Loss Function Based on Lie Group for Significant Speed-up of PoseNet Training Process**|Mikhail Kurenkov et.al.|[2211.08480v1](http://arxiv.org/abs/2211.08480v1)|null|
|**2022-11-14**|**Degeneracy removal of spin bands in antiferromagnets with non-interconvertible spin motif pair**|Lin-Ding Yuan et.al.|[2211.07803v1](http://arxiv.org/abs/2211.07803v1)|null|
|**2022-11-14**|**Supervised Fine-tuning Evaluation for Long-term Visual Place Recognition**|Farid Alijani et.al.|[2211.07696v1](http://arxiv.org/abs/2211.07696v1)|null|
|**2022-11-14**|**Composed Image Retrieval with Text Feedback via Multi-grained Uncertainty Regularization**|Yiyang Chen et.al.|[2211.07394v1](http://arxiv.org/abs/2211.07394v1)|**[link](https://github.com/Monoxide-Chen/uncertainty_retrieval)**|
|**2022-11-14**|**Zero-shot Image Captioning by Anchor-augmented Vision-Language Space Alignment**|Junyang Wang et.al.|[2211.07275v1](http://arxiv.org/abs/2211.07275v1)|null|
|**2022-11-14**|**ContextCLIP: Contextual Alignment of Image-Text pairs on CLIP visual representations**|Chanda Grover et.al.|[2211.07122v1](http://arxiv.org/abs/2211.07122v1)|null|
|**2022-11-14**|**Few-shot Metric Learning: Online Adaptation of Embedding for Retrieval**|Deunsol Jung et.al.|[2211.07116v1](http://arxiv.org/abs/2211.07116v1)|null|
|**2022-11-12**|**Partial Visual-Semantic Embedding: Fashion Intelligence System with Sensitive Part-by-Part Learning**|Ryotaro Shimizu et.al.|[2211.06688v1](http://arxiv.org/abs/2211.06688v1)|null|
|**2022-11-09**|**Visual Named Entity Linking: A New Dataset and A Baseline**|Wenxiang Sun et.al.|[2211.04872v1](http://arxiv.org/abs/2211.04872v1)|**[link](https://github.com/ict-bigdatalab/vnel)**|
|**2022-11-07**|**Ultrafast Image Retrieval from a Holographic Memory Disc for High-Speed Operation of a Shift, Scale, and Rotation Invariant Target Recognition System**|Julian Gamboa et.al.|[2211.03881v1](http://arxiv.org/abs/2211.03881v1)|null|
|**2022-11-06**|**A Geometrically Constrained Point Matching based on View-invariant Cross-ratios, and Homography**|Yueh-Cheng Huang et.al.|[2211.03007v1](http://arxiv.org/abs/2211.03007v1)|null|
|**2022-11-02**|**Optimizing Fiducial Marker Placement for Improved Visual Localization**|Qiangqiang Huang et.al.|[2211.01513v1](http://arxiv.org/abs/2211.01513v1)|**[link](https://github.com/doublestrong/omp)**|
|**2022-11-02**|**A comparison of uncertainty estimation approaches for DNN-based camera localization**|Matteo Vaghi et.al.|[2211.01234v1](http://arxiv.org/abs/2211.01234v1)|null|
|**2022-11-02**|**M-SpeechCLIP: Leveraging Large-Scale, Pre-Trained Models for Multilingual Speech to Image Retrieval**|Layne Berry et.al.|[2211.01180v1](http://arxiv.org/abs/2211.01180v1)|null|
|**2022-11-11**|**Why is Winoground Hard? Investigating Failures in Visuolinguistic Compositionality**|Anuj Diwan et.al.|[2211.00768v3](http://arxiv.org/abs/2211.00768v3)|**[link](https://github.com/ajd12342/why-winoground-hard)**|
|**2022-11-07**|**Fashion-Specific Attributes Interpretation via Dual Gaussian Visual-Semantic Embedding**|Ryotaro Shimizu et.al.|[2210.17417v2](http://arxiv.org/abs/2210.17417v2)|null|
|**2022-10-27**|**Structuring User-Generated Content on Social Media with Multimodal Aspect-Based Sentiment Analysis**|Miriam Anschütz et.al.|[2210.15377v1](http://arxiv.org/abs/2210.15377v1)|**[link](https://github.com/miriull/multimodal_absa_elbphilharmonie)**|
|**2022-10-27**|**Leveraging Computer Vision Application in Visual Arts: A Case Study on the Use of Residual Neural Network to Classify and Analyze Baroque Paintings**|Daniel Kvak et.al.|[2210.15300v1](http://arxiv.org/abs/2210.15300v1)|null|
|**2022-10-27**|**Towards Practicality of Sketch-Based Visual Understanding**|Ayan Kumar Bhunia et.al.|[2210.15146v1](http://arxiv.org/abs/2210.15146v1)|null|
|**2022-10-27**|**MMFL-Net: Multi-scale and Multi-granularity Feature Learning for Cross-domain Fashion Retrieval**|Chen Bao et.al.|[2210.15128v1](http://arxiv.org/abs/2210.15128v1)|null|
|**2022-10-26**|**FaD-VLP: Fashion Vision-and-Language Pre-training towards Unified Retrieval and Captioning**|Suvir Mirchandani et.al.|[2210.15028v1](http://arxiv.org/abs/2210.15028v1)|null|
|**2022-10-26**|**FairCLIP: Social Bias Elimination based on Attribute Prototype Learning and Representation Neutralization**|Junyang Wang et.al.|[2210.14562v1](http://arxiv.org/abs/2210.14562v1)|null|
|**2022-11-02**|**A Framework for Collaborative Multi-Robot Mapping using Spectral Graph Wavelets**|Lukas Bernreiter et.al.|[2210.13856v2](http://arxiv.org/abs/2210.13856v2)|null|
|**2022-10-27**|**Learning by Hallucinating: Vision-Language Pre-training with Weak Supervision**|Tzu-Jui Julius Wang et.al.|[2210.13591v2](http://arxiv.org/abs/2210.13591v2)|null|
|**2022-10-24**|**Reliability-Aware Prediction via Uncertainty Learning for Person Image Retrieval**|Zhaopeng Dou et.al.|[2210.13440v1](http://arxiv.org/abs/2210.13440v1)|**[link](https://github.com/dcp15/ual)**|
|**2022-10-23**|**Neural Eigenfunctions Are Structured Representation Learners**|Zhijie Deng et.al.|[2210.12637v1](http://arxiv.org/abs/2210.12637v1)|**[link](https://github.com/thudzj/NEigenmaps)**|
|**2022-10-21**|**Boosting vision transformers for image retrieval**|Chull Hwan Song et.al.|[2210.11909v1](http://arxiv.org/abs/2210.11909v1)|**[link](https://github.com/dealicious-inc/dtop)**|
|**2022-10-20**|**Communication breakdown: On the low mutual intelligibility between human and neural captioning**|Roberto Dessì et.al.|[2210.11512v1](http://arxiv.org/abs/2210.11512v1)|null|
|**2022-10-19**|**Image Semantic Relation Generation**|Mingzhe Du et.al.|[2210.11253v1](http://arxiv.org/abs/2210.11253v1)|null|
|**2022-10-20**|**General Image Descriptors for Open World Image Retrieval using ViT CLIP**|Marcos V. Conde et.al.|[2210.11141v1](http://arxiv.org/abs/2210.11141v1)|**[link](https://github.com/ivanaer/g-universal-clip)**|
|**2022-10-20**|**DeepRING: Learning Roto-translation Invariant Representation for LiDAR based Place Recognition**|Sha Lu et.al.|[2210.11029v1](http://arxiv.org/abs/2210.11029v1)|null|
|**2022-10-19**|**Cross-Modal Fusion Distillation for Fine-Grained Sketch-Based Image Retrieval**|Abhra Chaudhuri et.al.|[2210.10486v1](http://arxiv.org/abs/2210.10486v1)|**[link](https://github.com/abhrac/xmodal-vit)**|
|**2022-10-19**|**GSV-Cities: Toward Appropriate Supervised Visual Place Recognition**|Amar Ali-bey et.al.|[2210.10239v1](http://arxiv.org/abs/2210.10239v1)|**[link](https://github.com/amaralibey/gsv-cities)**|
|**2022-10-18**|**A Real-Time Fusion Framework for Long-term Visual Localization**|Yuchen Yang et.al.|[2210.09757v1](http://arxiv.org/abs/2210.09757v1)|null|
|**2022-10-17**|**Bridging the Gap between Local Semantic Concepts and Bag of Visual Words for Natural Scene Image Retrieval**|Yousef Alqasrawi et.al.|[2210.08875v1](http://arxiv.org/abs/2210.08875v1)|null|
|**2022-10-17**|**SGRAM: Improving Scene Graph Parsing via Abstract Meaning Representation**|Woo Suk Choi et.al.|[2210.08675v1](http://arxiv.org/abs/2210.08675v1)|null|
|**2022-10-16**|**Learning Self-Regularized Adversarial Views for Self-Supervised Vision Transformers**|Tao Tang et.al.|[2210.08458v1](http://arxiv.org/abs/2210.08458v1)|**[link](https://github.com/trent-tangtao/autoview)**|
|**2022-10-14**|**Cross-Scale Context Extracted Hashing for Fine-Grained Image Binary Encoding**|Xuetong Xue et.al.|[2210.07572v1](http://arxiv.org/abs/2210.07572v1)|**[link](https://github.com/netease-media/csce-net)**|
|**2022-10-14**|**Boosting Performance of a Baseline Visual Place Recognition Technique by Predicting the Maximally Complementary Technique**|Connor Malone et.al.|[2210.07509v1](http://arxiv.org/abs/2210.07509v1)|null|
|**2022-10-11**|**Large-to-small Image Resolution Asymmetry in Deep Metric Learning**|Pavel Suma et.al.|[2210.05463v1](http://arxiv.org/abs/2210.05463v1)|**[link](https://github.com/pavelsuma/raml)**|
|**2022-10-09**|**Fusing Event-based Camera and Radar for SLAM Using Spiking Neural Networks with Continual STDP Learning**|Ali Safa et.al.|[2210.04236v1](http://arxiv.org/abs/2210.04236v1)|null|
|**2022-10-05**|**Medical Image Retrieval via Nearest Neighbor Search on Pre-trained Image Features**|Deepak Gupta et.al.|[2210.02401v1](http://arxiv.org/abs/2210.02401v1)|**[link](https://github.com/deepaknlp/dls)**|
|**2022-10-05**|**Granularity-aware Adaptation for Image Retrieval over Multiple Tasks**|Jon Almazán et.al.|[2210.02254v1](http://arxiv.org/abs/2210.02254v1)|null|
|**2022-10-05**|**Improving Visual-Semantic Embedding with Adaptive Pooling and Optimization Objective**|Zijian Zhang et.al.|[2210.02206v1](http://arxiv.org/abs/2210.02206v1)|**[link](https://github.com/96-zachary/vse_2ad)**|
|**2022-10-04**|**Supervised Metric Learning for Retrieval via Contextual Similarity Optimization**|Christopher Liao et.al.|[2210.01908v1](http://arxiv.org/abs/2210.01908v1)|**[link](https://github.com/chris210634/metric-learning-using-contextual-similarity)**|
|**2022-10-04**|**Wi-Closure: Reliable and Efficient Search of Inter-robot Loop Closures Using Wireless Sensing**|Weiying Wang et.al.|[2210.01320v1](http://arxiv.org/abs/2210.01320v1)|null|
|**2022-10-03**|**Merging Classification Predictions with Sequential Information for Lightweight Visual Place Recognition in Changing Environments**|Bruno Arcanjo et.al.|[2210.00834v1](http://arxiv.org/abs/2210.00834v1)|null|
|**2022-10-02**|**Loc-VAE: Learning Structurally Localized Representation from 3D Brain MR Images for Content-Based Image Retrieval**|Kei Nishimaki et.al.|[2210.00506v1](http://arxiv.org/abs/2210.00506v1)|null|
|**2022-09-29**|**Guided Unsupervised Learning by Subaperture Decomposition for Ocean SAR Image Retrieval**|Nicolae-Cătălin Ristea et.al.|[2209.15034v1](http://arxiv.org/abs/2209.15034v1)|null|
|**2022-09-28**|**TVLT: Textless Vision-Language Transformer**|Zineng Tang et.al.|[2209.14156v1](http://arxiv.org/abs/2209.14156v1)|**[link](https://github.com/zinengtang/tvlt)**|
|**2022-09-28**|**SEMICON: A Learning-to-hash Solution for Large-scale Fine-grained Image Retrieval**|Yang Shen et.al.|[2209.13833v1](http://arxiv.org/abs/2209.13833v1)|**[link](https://github.com/njust-vipgroup/semicon)**|
|**2022-09-28**|**Learning Deep Representations via Contrastive Learning for Instance Retrieval**|Tao Wu et.al.|[2209.13832v1](http://arxiv.org/abs/2209.13832v1)|null|
|**2022-09-28**|**Mr. Right: Multimodal Retrieval on Representation of ImaGe witH Text**|Cheng-An Hsieh et.al.|[2209.13764v1](http://arxiv.org/abs/2209.13764v1)|**[link](https://github.com/hsiehjackson/mr.right)**|
|**2022-09-27**|**Learning-Based Dimensionality Reduction for Computing Compact and Effective Local Feature Descriptors**|Hao Dong et.al.|[2209.13586v1](http://arxiv.org/abs/2209.13586v1)|**[link](https://github.com/prbonn/descriptor-dr)**|
|**2022-09-27**|**Exploring the Algorithm-Dependent Generalization of AUPRC Optimization with List Stability**|Peisong Wen et.al.|[2209.13262v1](http://arxiv.org/abs/2209.13262v1)|**[link](https://github.com/kid-7391/soprc)**|
|**2022-09-26**|**NDD: A 3D Point Cloud Descriptor Based on Normal Distribution for Loop Closure Detection**|Ruihao Zhou et.al.|[2209.12513v1](http://arxiv.org/abs/2209.12513v1)|**[link](https://github.com/zhouruihao1001/ndd)**|
|**2022-09-25**|**Personalized Saliency in Task-Oriented Semantic Communications: Image Transmission and Performance Analysis**|Jiawen Kang et.al.|[2209.12274v1](http://arxiv.org/abs/2209.12274v1)|null|
|**2022-09-24**|**Closing the Loop: Graph Networks to Unify Semantic Objects and Visual Features for Multi-object Scenes**|Jonathan J. Y. Kim et.al.|[2209.11894v1](http://arxiv.org/abs/2209.11894v1)|null|
|**2022-09-23**|**Image-to-Image Translation for Autonomous Driving from Coarsely-Aligned Image Pairs**|Youya Xia et.al.|[2209.11673v1](http://arxiv.org/abs/2209.11673v1)|null|
|**2022-09-23**|**Query-based Hard-Image Retrieval for Object Detection at Test Time**|Edward Ayers et.al.|[2209.11559v1](http://arxiv.org/abs/2209.11559v1)|**[link](https://github.com/fiveai/hardest)**|
|**2022-09-23**|**Unsupervised Hashing with Semantic Concept Mining**|Rong-Cheng Tu et.al.|[2209.11475v1](http://arxiv.org/abs/2209.11475v1)|**[link](https://github.com/rongchengtu1/uhscm)**|
|**2022-09-22**|**UNav: An Infrastructure-Independent Vision-Based Navigation System for People with Blindness and Low vision**|Anbang Yang et.al.|[2209.11336v1](http://arxiv.org/abs/2209.11336v1)|null|
|**2022-09-21**|**Visual Localization and Mapping in Dynamic and Changing Environments**|João Carlos Virgolino Soares et.al.|[2209.10710v1](http://arxiv.org/abs/2209.10710v1)|null|
|**2022-09-20**|**PADLoC: LiDAR-Based Deep Loop Closure Detection and Registration using Panoptic Attention**|José Arce et.al.|[2209.09699v1](http://arxiv.org/abs/2209.09699v1)|**[link](https://github.com/robot-learning-freiburg/PADLoC)**|
|**2022-09-19**|**Deep Metric Learning with Chance Constraints**|Yeti Z. Gurbuz et.al.|[2209.09060v1](http://arxiv.org/abs/2209.09060v1)|**[link](https://github.com/yetigurbuz/ccp-dml)**|
|**2022-09-18**|**HGI-SLAM: Loop Closure With Human and Geometric Importance Features**|Shuhul Mujoo et.al.|[2209.08608v1](http://arxiv.org/abs/2209.08608v1)|null|
|**2022-09-18**|**Data-driven Loop Closure Detection in Bathymetric Point Clouds for Underwater SLAM**|Jiarui Tan et.al.|[2209.08578v1](http://arxiv.org/abs/2209.08578v1)|**[link](https://github.com/tjr16/bathy_nn_learning)**|
|**2022-09-17**|**Data Efficient Visual Place Recognition Using Extremely JPEG-Compressed Images**|Mihnea-Alexandru Tomita et.al.|[2209.08343v1](http://arxiv.org/abs/2209.08343v1)|null|
|**2022-09-15**|**Efficient Planar Pose Estimation via UWB Measurements**|Haodong Jiang et.al.|[2209.06779v2](http://arxiv.org/abs/2209.06779v2)|**[link](https://github.com/SLAMLab-CUHKSZ/Efficient-Pose-Estimation-via-UWB-measurements)**|
|**2022-09-14**|**Transformers and CNNs both Beat Humans on SBIR**|Omar Seddati et.al.|[2209.06629v1](http://arxiv.org/abs/2209.06629v1)|null|
|**2022-09-14**|**Tac2Structure: Object Surface Reconstruction Only through Multi Times Touch**|J. Lu et.al.|[2209.06545v1](http://arxiv.org/abs/2209.06545v1)|**[link](https://github.com/ljy-zju/tac2structure)**|
|**2022-09-14**|**iSimLoc: Visual Global Localization for Previously Unseen Environments with Simulated Images**|Peng Yin et.al.|[2209.06376v1](http://arxiv.org/abs/2209.06376v1)|null|
|**2022-09-09**|**General Place Recognition Survey: Towards the Real-world Autonomy Age**|Peng Yin et.al.|[2209.04497v1](http://arxiv.org/abs/2209.04497v1)|**[link](https://github.com/MetaSLAM/GPRS)**|
|**2022-09-09**|**Retinal Image Restoration and Vessel Segmentation using Modified Cycle-CBAM and CBAM-UNet**|Alnur Alimanov et.al.|[2209.04234v1](http://arxiv.org/abs/2209.04234v1)|**[link](https://github.com/AAleka/Cycle-CBAM-and-CBAM-UNet/tree/main/UNet)**|
|**2022-09-13**|**Segment Augmentation and Differentiable Ranking for Logo Retrieval**|Feyza Yavuz et.al.|[2209.02482v2](http://arxiv.org/abs/2209.02482v2)|null|
|**2022-09-12**|**ScaleFace: Uncertainty-aware Deep Metric Learning**|Roman Kail et.al.|[2209.01880v2](http://arxiv.org/abs/2209.01880v2)|**[link](https://github.com/stat-ml/face-evaluation)**|
|**2022-09-04**|**CloudVision: DNN-based Visual Localization of Autonomous Robots using Prebuilt LiDAR Point Cloud**|Evgeny Yudin et.al.|[2209.01605v1](http://arxiv.org/abs/2209.01605v1)|null|
|**2022-08-31**|**EViT: Privacy-Preserving Image Retrieval via Encrypted Vision Transformer in Cloud Computing**|Qihua Feng et.al.|[2208.14657v1](http://arxiv.org/abs/2208.14657v1)|**[link](https://github.com/onlinehuazai/evit)**|
|**2022-08-25**|**A Deep Perceptual Measure for Lens and Camera Calibration**|Yannick Hold-Geoffroy et.al.|[2208.12300v1](http://arxiv.org/abs/2208.12300v1)|null|
|**2022-08-25**|**A Privacy-Preserving and End-to-End-Based Encrypted Image Retrieval Scheme**|Zhixun Lu et.al.|[2208.11876v1](http://arxiv.org/abs/2208.11876v1)|null|
|**2022-08-23**|**Satellite Image Search in AgoraEO**|Ahmet Kerem Aksoy et.al.|[2208.10830v1](http://arxiv.org/abs/2208.10830v1)|null|
|**2022-08-20**|**Fuse and Attend: Generalized Embedding Learning for Art and Sketches**|Ujjal Kr Dutta et.al.|[2208.09698v1](http://arxiv.org/abs/2208.09698v1)|null|
|**2022-08-19**|**Self-Supervised Visual Place Recognition by Mining Temporal and Feature Neighborhoods**|Chao Chen et.al.|[2208.09315v1](http://arxiv.org/abs/2208.09315v1)|null|
|**2022-08-19**|**TTT-UCDR: Test-time Training for Universal Cross-Domain Retrieval**|Soumava Paul et.al.|[2208.09198v1](http://arxiv.org/abs/2208.09198v1)|**[link](https://github.com/mvp18/ttt-ucdr)**|
|**2022-08-17**|**Visual Cross-View Metric Localization with Dense Uncertainty Estimates**|Zimin Xia et.al.|[2208.08519v1](http://arxiv.org/abs/2208.08519v1)|**[link](https://github.com/tudelft-iv/crossviewmetriclocalization)**|
|**2022-08-17**|**Understanding Attention for Vision-and-Language Tasks**|Feiqi Cao et.al.|[2208.08104v1](http://arxiv.org/abs/2208.08104v1)|**[link](https://github.com/adlnlp/attention_vl)**|
|**2022-08-14**|**Visual Localization via Few-Shot Scene Region Classification**|Siyan Dong et.al.|[2208.06933v1](http://arxiv.org/abs/2208.06933v1)|**[link](https://github.com/siyandong/src)**|
|**2022-08-14**|**HyP $^2$ Loss: Beyond Hypersphere Metric Space for Multi-label Image Retrieval**|Chengyin Xu et.al.|[2208.06866v1](http://arxiv.org/abs/2208.06866v1)|**[link](https://github.com/jerryxu0129/hyp2-loss)**|
|**2022-08-13**|**Finding Point with Image: An End-to-End Benchmark for Vision-based UAV Localization**|Ming Dai et.al.|[2208.06561v1](http://arxiv.org/abs/2208.06561v1)|null|
|**2022-08-16**|**Category-Level Pose Retrieval with Contrastive Features Learnt with Occlusion Augmentation**|Georgios Kouros et.al.|[2208.06195v2](http://arxiv.org/abs/2208.06195v2)|**[link](https://github.com/gkouros/contrastive-pose-retrieval)**|
|**2022-08-12**|**Instance Image Retrieval by Learning Purely From Within the Dataset**|Zhongyan Zhang et.al.|[2208.06119v1](http://arxiv.org/abs/2208.06119v1)|null|
|**2022-08-07**|**CVLNet: Cross-View Semantic Correspondence Learning for Video-based Camera Localization**|Yujiao Shi et.al.|[2208.03660v1](http://arxiv.org/abs/2208.03660v1)|null|
|**2022-08-05**|**A Sketch Is Worth a Thousand Words: Image Retrieval with Text and Sketch**|Patsorn Sangkloy et.al.|[2208.03354v1](http://arxiv.org/abs/2208.03354v1)|null|
|**2022-08-05**|**ChiQA: A Large Scale Image-based Real-World Question Answering Dataset for Multi-Modal Understanding**|Bingning Wang et.al.|[2208.03030v1](http://arxiv.org/abs/2208.03030v1)|**[link](https://github.com/benywon/ChiQA)**|
|**2022-08-04**|**Pattern Spotting and Image Retrieval in Historical Documents using Deep Hashing**|Caio da S. Dias et.al.|[2208.02397v1](http://arxiv.org/abs/2208.02397v1)|null|
|**2022-07-27**|**On the robustness of self-supervised representations for multi-view object classification**|David Torpey et.al.|[2208.00787v1](http://arxiv.org/abs/2208.00787v1)|null|
|**2022-07-26**|**Multimodal Neural Machine Translation with Search Engine Based Image Retrieval**|ZhenHao Tang et.al.|[2208.00767v1](http://arxiv.org/abs/2208.00767v1)|null|
|**2022-07-30**|**Towards Privacy-Preserving, Real-Time and Lossless Feature Matching**|Qiang Meng et.al.|[2208.00214v1](http://arxiv.org/abs/2208.00214v1)|**[link](https://github.com/irvingmeng/securevector)**|
|**2022-07-30**|**DAS: Densely-Anchored Sampling for Deep Metric Learning**|Lizhao Liu et.al.|[2208.00119v1](http://arxiv.org/abs/2208.00119v1)|**[link](https://github.com/lizhaoliu-Lec/DAS)**|
|**2022-07-29**|**Curriculum Learning for Data-Efficient Vision-Language Alignment**|Tejas Srinivasan et.al.|[2207.14525v1](http://arxiv.org/abs/2207.14525v1)|null|
|**2022-07-29**|**Neural Density-Distance Fields**|Itsuki Ueda et.al.|[2207.14455v1](http://arxiv.org/abs/2207.14455v1)|**[link](https://github.com/ueda0319/neddf)**|
|**2022-07-27**|**Abstracting Sketches through Simple Primitives**|Stephan Alaniz et.al.|[2207.13543v1](http://arxiv.org/abs/2207.13543v1)|**[link](https://github.com/explainableml/sketch-primitives)**|
|**2022-07-27**|**Satellite Image Based Cross-view Localization for Autonomous Vehicle**|Shan Wang et.al.|[2207.13506v1](http://arxiv.org/abs/2207.13506v1)|null|
|**2022-07-26**|**RenderNet: Visual Relocalization Using Virtual Viewpoints in Large-Scale Indoor Environments**|Jiahui Zhang et.al.|[2207.12579v1](http://arxiv.org/abs/2207.12579v1)|null|
|**2022-07-25**|**A hybrid-qudit representation of digital RGB images**|Sreetama Das et.al.|[2207.12550v1](http://arxiv.org/abs/2207.12550v1)|null|
|**2022-07-19**|**ALTO: A Large-Scale Dataset for UAV Visual Place Recognition and Localization**|Ivan Cisneros et.al.|[2207.12317v1](http://arxiv.org/abs/2207.12317v1)|**[link](https://github.com/metaslam/alto)**|
|**2022-07-22**|**PLD-SLAM: A Real-Time Visual SLAM Using Points and Line Segments in Dynamic Scenes**|BaoSheng Zhang et.al.|[2207.10916v1](http://arxiv.org/abs/2207.10916v1)|null|
|**2022-07-25**|**MeshLoc: Mesh-Based Visual Localization**|Vojtech Panek et.al.|[2207.10762v2](http://arxiv.org/abs/2207.10762v2)|**[link](https://github.com/tsattler/meshloc_release)**|
|**2022-07-20**|**Revisiting Hotels-50K and Hotel-ID**|Aarash Feizi et.al.|[2207.10200v1](http://arxiv.org/abs/2207.10200v1)|**[link](https://github.com/aarashfeizi/revisited-hotels)**|
|**2022-07-20**|**Feature Representation Learning for Unsupervised Cross-domain Image Retrieval**|Conghui Hu et.al.|[2207.09721v1](http://arxiv.org/abs/2207.09721v1)|**[link](https://github.com/conghuihu/ucdir)**|
|**2022-07-19**|**SeasoNet: A Seasonal Scene Classification, segmentation and Retrieval dataset for satellite Imagery over Germany**|Dominik Koßmann et.al.|[2207.09507v1](http://arxiv.org/abs/2207.09507v1)|null|
|**2022-07-19**|**Context Unaware Knowledge Distillation for Image Retrieval**|Bytasandram Yaswanth Reddy et.al.|[2207.09070v1](http://arxiv.org/abs/2207.09070v1)|**[link](https://github.com/satoru2001/cukdfir)**|
|**2022-07-17**|**FashionViL: Fashion-Focused Vision-and-Language Representation Learning**|Xiao Han et.al.|[2207.08150v1](http://arxiv.org/abs/2207.08150v1)|**[link](https://github.com/brandonhanx/mmf)**|
|**2022-07-14**|**AutoMerge: A Framework for Map Assembling and Smoothing in City-scale Environments**|Peng Yin et.al.|[2207.06965v1](http://arxiv.org/abs/2207.06965v1)|null|
|**2022-07-14**|**Semi-supervised Vector-Quantization in Visual SLAM using HGCN**|Amir Zarringhalam et.al.|[2207.06738v1](http://arxiv.org/abs/2207.06738v1)|null|
|**2022-07-14**|**Self-supervised Vector-Quantization in Visual SLAM using Deep Convolutional Autoencoders**|Amir Zarringhalam et.al.|[2207.06732v1](http://arxiv.org/abs/2207.06732v1)|null|
|**2022-07-19**|**Structure PLP-SLAM: Efficient Sparse Mapping and Localization using Point, Line and Plane for Monocular, RGB-D and Stereo Cameras**|Fangwen Shu et.al.|[2207.06058v2](http://arxiv.org/abs/2207.06058v2)|**[link](https://github.com/peterfws/structure-plp-slam)**|
|**2022-07-12**|**CPO: Change Robust Panorama to Point Cloud Localization**|Junho Kim et.al.|[2207.05317v1](http://arxiv.org/abs/2207.05317v1)|null|
|**2022-07-05**|**Hierarchical Average Precision Training for Pertinent Image Retrieval**|Elias Ramzi et.al.|[2207.04873v1](http://arxiv.org/abs/2207.04873v1)|**[link](https://github.com/elias-ramzi/happier)**|
|**2022-07-11**|**A clinically motivated self-supervised approach for content-based image retrieval of CT liver images**|Kristoffer Knutsen Wickstrøm et.al.|[2207.04812v1](http://arxiv.org/abs/2207.04812v1)|**[link](https://github.com/wickstrom/clinical-self-supervised-cbir-ct-liver)**|
|**2022-07-09**|**BOSS: Bottom-up Cross-modal Semantic Composition with Hybrid Counterfactual Training for Robust Content-based Image Retrieval**|Wenqiao Zhang et.al.|[2207.04211v1](http://arxiv.org/abs/2207.04211v1)|null|
|**2022-07-08**|**Learning Sequential Descriptors for Sequence-based Visual Place Recognition**|Riccardo Mereu et.al.|[2207.03868v1](http://arxiv.org/abs/2207.03868v1)|**[link](https://github.com/vandal-vpr/vg-transformers)**|
|**2022-07-08**|**GEMS: Scene Expansion using Generative Models of Graphs**|Rishi Agarwal et.al.|[2207.03729v1](http://arxiv.org/abs/2207.03729v1)|null|
|**2022-07-05**|**Object-Level Targeted Selection via Deep Template Matching**|Suraj Kothawade et.al.|[2207.01778v1](http://arxiv.org/abs/2207.01778v1)|null|
|**2022-07-06**|**Adaptive Fine-Grained Sketch-Based Image Retrieval**|Ayan Kumar Bhunia et.al.|[2207.01723v2](http://arxiv.org/abs/2207.01723v2)|**[link](https://github.com/ayankumarbhunia/adaptive-fgsbir)**|
|**2022-07-04**|**Embedding contrastive unsupervised features to cluster in- and out-of-distribution noise in corrupted image datasets**|Paul Albert et.al.|[2207.01573v1](http://arxiv.org/abs/2207.01573v1)|**[link](https://github.com/paulalbert31/sncf)**|
|**2022-07-08**|**Contrastive Cross-Modal Knowledge Sharing Pre-training for Vision-Language Representation Learning and Retrieval**|Keyu Wen et.al.|[2207.00733v2](http://arxiv.org/abs/2207.00733v2)|null|
|**2022-07-01**|**DALG: Deep Attentive Local and Global Modeling for Image Retrieval**|Yuxin Song et.al.|[2207.00287v1](http://arxiv.org/abs/2207.00287v1)|null|
|**2022-07-04**|**BadHash: Invisible Backdoor Attacks against Deep Hashing with Clean Label**|Shengshan Hu et.al.|[2207.00278v2](http://arxiv.org/abs/2207.00278v2)|**[link](https://github.com/cgcl-codes/badhash)**|
|**2022-06-28**|**Improving Worst Case Visual Localization Coverage via Place-specific Sub-selection in Multi-camera Systems**|Stephen Hausler et.al.|[2206.13883v1](http://arxiv.org/abs/2206.13883v1)|null|
|**2022-07-08**|**How Many Events do You Need? Event-based Visual Place Recognition Using Sparse But Varying Pixels**|Tobias Fischer et.al.|[2206.13673v2](http://arxiv.org/abs/2206.13673v2)|**[link](https://github.com/tobias-fischer/sparse-event-vpr)**|
|**2022-06-25**|**FreSCo: Frequency-Domain Scan Context for LiDAR-based Place Recognition with Translation and Rotation Invariance**|Yongzhi Fan et.al.|[2206.12628v1](http://arxiv.org/abs/2206.12628v1)|**[link](https://github.com/soytony/fresco)**|
|**2022-06-25**|**Inverted Semantic-Index for Image Retrieval**|Ying Wang et.al.|[2206.12623v1](http://arxiv.org/abs/2206.12623v1)|null|
|**2022-06-17**|**RetrievalGuard: Provably Robust 1-Nearest Neighbor Image Retrieval**|Yihan Wu et.al.|[2206.11225v1](http://arxiv.org/abs/2206.11225v1)|null|
|**2022-06-22**|**ICC++: Explainable Image Retrieval for Art Historical Corpora using Image Composition Canvas**|Prathmesh Madhu et.al.|[2206.11115v1](http://arxiv.org/abs/2206.11115v1)|null|
|**2022-06-20**|**Self-Supervised Consistent Quantization for Fully Unsupervised Image Retrieval**|Guile Wu et.al.|[2206.09806v1](http://arxiv.org/abs/2206.09806v1)|null|
|**2022-06-18**|**Attention-based Dynamic Subspace Learners for Medical Image Analysis**|Sukesh Adiga V et.al.|[2206.09068v1](http://arxiv.org/abs/2206.09068v1)|null|
|**2022-06-17**|**Efficient WiFi LiDAR SLAM for Autonomous Robots in Large Environments**|Khairuldanial Ismail et.al.|[2206.08733v1](http://arxiv.org/abs/2206.08733v1)|null|
|**2022-06-06**|**Learning Treatment Plan Representations for Content Based Image Retrieval**|Charles Huang et.al.|[2206.02912v1](http://arxiv.org/abs/2206.02912v1)|null|
|**2022-06-19**|**NORPPA: NOvel Ringed seal re-identification by Pelage Pattern Aggregation**|Ekaterina Nepovinnykh et.al.|[2206.02498v3](http://arxiv.org/abs/2206.02498v3)|**[link](https://github.com/kwadraterry/norppa)**|
|**2022-06-05**|**Autoregressive Model for Multi-Pass SAR Change Detection Based on Image Stacks**|B. G. Palm et.al.|[2206.02278v1](http://arxiv.org/abs/2206.02278v1)|null|
|**2022-05-28**|**FaIRCoP: Facial Image Retrieval using Contrastive Personalization**|Devansh Gupta et.al.|[2205.15870v1](http://arxiv.org/abs/2205.15870v1)|null|
|**2022-05-31**|**Investigating the Role of Image Retrieval for Visual Localization -- An exhaustive benchmark**|Martin Humenberger et.al.|[2205.15761v1](http://arxiv.org/abs/2205.15761v1)|**[link](https://github.com/naver/kapture-localization)**|
|**2022-05-27**|**Improving Road Segmentation in Challenging Domains Using Similar Place Priors**|Connor Malone et.al.|[2205.14112v1](http://arxiv.org/abs/2205.14112v1)|null|
|**2022-05-31**|**LAMP 2.0: A Robust Multi-Robot SLAM System for Operation in Challenging Large-Scale Underground Environments**|Yun Chang et.al.|[2205.13135v2](http://arxiv.org/abs/2205.13135v2)|**[link](https://github.com/nebula-autonomy/nebula-multirobot-dataset)**|
|**2022-05-26**|**Fine-grained Image Captioning with CLIP Reward**|Jaemin Cho et.al.|[2205.13115v1](http://arxiv.org/abs/2205.13115v1)|**[link](https://github.com/j-min/clip-caption-reward)**|
|**2022-05-25**|**Deep Dense Local Feature Matching and Vehicle Removal for Indoor Visual Localization**|Kyung Ho Park et.al.|[2205.12544v1](http://arxiv.org/abs/2205.12544v1)|null|
|**2022-05-24**|**OnePose: One-Shot Object Pose Estimation without CAD Models**|Jiaming Sun et.al.|[2205.12257v1](http://arxiv.org/abs/2205.12257v1)|**[link](https://github.com/zju3dv/OnePose)**|
|**2022-05-23**|**VPAIR -- Aerial Visual Place Recognition and Localization in Large-scale Outdoor Environments**|Michael Schleiss et.al.|[2205.11567v1](http://arxiv.org/abs/2205.11567v1)|**[link](https://github.com/aervisloc/vpair)**|
|**2022-05-23**|**VQA-GNN: Reasoning with Multimodal Semantic Graph for Visual Question Answering**|Yanan Wang et.al.|[2205.11501v1](http://arxiv.org/abs/2205.11501v1)|null|
|**2022-05-23**|**Deep Image Retrieval is not Robust to Label Noise**|Stanislav Dereka et.al.|[2205.11195v1](http://arxiv.org/abs/2205.11195v1)|null|
|**2022-05-22**|**Geo-Localization via Ground-to-Satellite Cross-View Image Retrieval**|Zelong Zeng et.al.|[2205.10878v1](http://arxiv.org/abs/2205.10878v1)|**[link](https://github.com/ZelongZeng/PLCD)**|
|**2022-05-20**|**Visually-Augmented Language Modeling**|Weizhi Wang et.al.|[2205.10178v1](http://arxiv.org/abs/2205.10178v1)|**[link](https://github.com/victorwz/valm)**|
|**2022-05-18**|**Deep Features for CBIR with Scarce Data using Hebbian Learning**|Gabriele Lagani et.al.|[2205.08935v1](http://arxiv.org/abs/2205.08935v1)|null|
|**2022-05-19**|**Text Detection & Recognition in the Wild for Robot Localization**|Zobeir Raisi et.al.|[2205.08565v2](http://arxiv.org/abs/2205.08565v2)|null|
|**2022-05-12**|**One Model, Multiple Modalities: A Sparsely Activated Approach for Text, Sound, Image, Video and Code**|Yong Dai et.al.|[2205.06126v1](http://arxiv.org/abs/2205.06126v1)|null|
|**2022-05-11**|**Review on Panoramic Imaging and Its Applications in Scene Understanding**|Shaohua Gao et.al.|[2205.05570v1](http://arxiv.org/abs/2205.05570v1)|null|
|**2022-05-18**|**Identical Image Retrieval using Deep Learning**|Sayan Nath et.al.|[2205.04883v2](http://arxiv.org/abs/2205.04883v2)|**[link](https://github.com/sayannath/identical-image-retrieval)**|
|**2022-05-09**|**Introspective Deep Metric Learning**|Chengkun Wang et.al.|[2205.04449v1](http://arxiv.org/abs/2205.04449v1)|**[link](https://github.com/wangck20/idml)**|
|**2022-05-11**|**Improved Evaluation and Generation of Grid Layouts using Distance Preservation Quality and Linear Assignment Sorting**|Kai Uwe Barthel et.al.|[2205.04255v2](http://arxiv.org/abs/2205.04255v2)|**[link](https://github.com/visual-computing/las_flas)**|
|**2022-05-08**|**Adversarial Learning of Hard Positives for Place Recognition**|Wenxuan Fang et.al.|[2205.03871v1](http://arxiv.org/abs/2205.03871v1)|null|
|**2022-05-10**|**AdaTriplet: Adaptive Gradient Triplet Loss with Automatic Margin Learning for Forensic Medical Image Matching**|Khanh Nguyen et.al.|[2205.02849v2](http://arxiv.org/abs/2205.02849v2)|**[link](https://github.com/oulu-imeds/adatriplet)**|
|**2022-04-29**|**Privacy-Preserving Model Upgrades with Bidirectional Compatible Training in Image Retrieval**|Shupeng Su et.al.|[2204.13919v1](http://arxiv.org/abs/2204.13919v1)|null|
|**2022-04-29**|**Leaner and Faster: Two-Stage Model Compression for Lightweight Text-Image Retrieval**|Siyu Ren et.al.|[2204.13913v1](http://arxiv.org/abs/2204.13913v1)|**[link](https://github.com/drsy/motis)**|
|**2022-04-28**|**Spatio-Temporal Graph Localization Networks for Image-based Navigation**|Takahiro Niwa et.al.|[2204.13237v1](http://arxiv.org/abs/2204.13237v1)|null|
|**2022-04-27**|**The Revisiting Problem in Simultaneous Localization and Mapping: A Survey on Visual Loop Closure Detection**|Konstantinos A. Tsintotas et.al.|[2204.12831v1](http://arxiv.org/abs/2204.12831v1)|null|
|**2022-04-25**|**SceneTrilogy: On Scene Sketches and its Relationship with Text and Photo**|Pinaki Nath Chowdhury et.al.|[2204.11964v1](http://arxiv.org/abs/2204.11964v1)|null|
|**2022-04-23**|**On Leveraging Variational Graph Embeddings for Open World Compositional Zero-Shot Learning**|Muhammad Umer Anwaar et.al.|[2204.11848v1](http://arxiv.org/abs/2204.11848v1)|null|
|**2022-04-24**|**Progressive Learning for Image Retrieval with Hybrid-Modality Queries**|Yida Zhao et.al.|[2204.11212v1](http://arxiv.org/abs/2204.11212v1)|null|
|**2022-04-23**|**Training and challenging models for text-guided fashion image retrieval**|Eric Dodds et.al.|[2204.11004v1](http://arxiv.org/abs/2204.11004v1)|**[link](https://github.com/yahoo/maaf)**|
|**2022-04-18**|**Centralized Adversarial Learning for Robust Deep Hashing**|Xunguang Wang et.al.|[2204.10779v1](http://arxiv.org/abs/2204.10779v1)|null|
|**2022-04-22**|**Transferring ConvNet Features from Passive to Active Robot Self-Localization: The Use of Ego-Centric and World-Centric Views**|Kanya Kurauchi et.al.|[2204.10497v1](http://arxiv.org/abs/2204.10497v1)|null|
|**2022-04-21**|**Exploring a Fine-Grained Multiscale Method for Cross-Modal Remote Sensing Image Retrieval**|Zhiqiang Yuan et.al.|[2204.09868v1](http://arxiv.org/abs/2204.09868v1)|**[link](https://github.com/xiaoyuan1996/AMFMN)**|
|**2022-04-21**|**Remote Sensing Cross-Modal Text-Image Retrieval Based on Global and Local Information**|Zhiqiang Yuan et.al.|[2204.09860v1](http://arxiv.org/abs/2204.09860v1)|**[link](https://github.com/xiaoyuan1996/galr)**|
|**2022-04-20**|**Uncertainty-based Cross-Modal Retrieval with Probabilistic Representations**|Leila Pishdad et.al.|[2204.09268v1](http://arxiv.org/abs/2204.09268v1)|null|
|**2022-04-19**|**Unsupervised Contrastive Hashing for Cross-Modal Retrieval in Remote Sensing**|Georgii Mikriukov et.al.|[2204.08707v1](http://arxiv.org/abs/2204.08707v1)|null|
|**2022-04-18**|**Multiple-environment Self-adaptive Network for Aerial-view Geo-localization**|Tingyu Wang et.al.|[2204.08381v1](http://arxiv.org/abs/2204.08381v1)|null|
|**2022-04-15**|**Condition-Invariant and Compact Visual Place Description by Convolutional Autoencoder**|Hanjing Ye et.al.|[2204.07350v1](http://arxiv.org/abs/2204.07350v1)|**[link](https://github.com/medlartea/cae-vpr)**|
|**2022-04-14**|**Composite Code Sparse Autoencoders for first stage retrieval**|Carlos Lassance et.al.|[2204.07023v1](http://arxiv.org/abs/2204.07023v1)|null|
|**2022-04-13**|**Reuse your features: unifying retrieval and feature-metric alignment**|Javier Morlana et.al.|[2204.06292v1](http://arxiv.org/abs/2204.06292v1)|null|
|**2022-04-12**|**Probabilistic Compositional Embeddings for Multimodal Image Retrieval**|Andrei Neculai et.al.|[2204.05845v1](http://arxiv.org/abs/2204.05845v1)|**[link](https://github.com/andreineculai/mpc)**|
|**2022-04-12**|**Three-Stream Joint Network for Zero-Shot Sketch-Based Image Retrieval**|Yu-Wei Zhan et.al.|[2204.05666v1](http://arxiv.org/abs/2204.05666v1)|null|
|**2022-04-12**|**HiTPR: Hierarchical Transformer for Place Recognition in Point Cloud**|Zhixing Hou et.al.|[2204.05481v1](http://arxiv.org/abs/2204.05481v1)|null|
|**2022-04-11**|**Optimized SC-F-LOAM: Optimized Fast LiDAR Odometry and Mapping Using Scan Context**|Lizhou Liao et.al.|[2204.04932v1](http://arxiv.org/abs/2204.04932v1)|**[link](https://github.com/SlamCabbage/Optimized-SC-F-LOAM)**|
|**2022-04-10**|**Beyond Cross-view Image Retrieval: Highly Accurate Vehicle Localization Using Satellite Image**|Yujiao Shi et.al.|[2204.04752v1](http://arxiv.org/abs/2204.04752v1)|**[link](https://github.com/shiyujiao/highlyaccurate)**|
|**2022-04-08**|**A Generic Image Retrieval Method for Date Estimation of Historical Document Collections**|Adrià Molina et.al.|[2204.04028v1](http://arxiv.org/abs/2204.04028v1)|null|
|**2022-04-08**|**SnapMode: An Intelligent and Distributed Large-Scale Fashion Image Retrieval Platform Based On Big Data and Deep Generative Adversarial Network Technologies**|Narges Norouzi et.al.|[2204.03998v1](http://arxiv.org/abs/2204.03998v1)|null|
|**2022-04-05**|**Leveraging Equivariant Features for Absolute Pose Regression**|Mohamed Adel Musallam et.al.|[2204.02163v1](http://arxiv.org/abs/2204.02163v1)|null|
|**2022-04-04**|**"This is my unicorn, Fluffy": Personalizing frozen vision-language representations**|Niv Cohen et.al.|[2204.01694v1](http://arxiv.org/abs/2204.01694v1)|**[link](https://github.com/nvlabs/pervlbenchmark)**|
|**2022-04-01**|**Bi-directional Loop Closure for Visual SLAM**|Ihtisham Ali et.al.|[2204.01524v1](http://arxiv.org/abs/2204.01524v1)|null|
|**2022-04-01**|**LASER: LAtent SpacE Rendering for 2D Visual Localization**|Zhixiang Min et.al.|[2204.00157v1](http://arxiv.org/abs/2204.00157v1)|**[link](https://github.com/zillow/laser)**|
|**2022-03-31**|**Semantic Pose Verification for Outdoor Visual Localization with Self-supervised Contrastive Learning**|Semih Orhan et.al.|[2203.16945v1](http://arxiv.org/abs/2203.16945v1)|null|
|**2022-03-30**|**AmsterTime: A Visual Place Recognition Benchmark Dataset for Severe Domain Shift**|Burak Yildiz et.al.|[2203.16291v1](http://arxiv.org/abs/2203.16291v1)|**[link](https://github.com/seyrankhademi/AmsterTime)**|
|**2022-03-29**|**Long-term Visual Map Sparsification with Heterogeneous GNN**|Ming-Fang Chang et.al.|[2203.15182v1](http://arxiv.org/abs/2203.15182v1)|null|
|**2022-04-01**|**A Simulation Benchmark for Vision-based Autonomous Navigation**|Lauri Suomela et.al.|[2203.13048v2](http://arxiv.org/abs/2203.13048v2)|**[link](https://github.com/lasuomela/carla_vloc_benchmark)**|
|**2022-03-24**|**Is Geometry Enough for Matching in Visual Localization?**|Qunjie Zhou et.al.|[2203.12979v1](http://arxiv.org/abs/2203.12979v1)|**[link](https://github.com/dvl-tum/gomatch)**|
|**2022-03-21**|**MatchFormer: Interleaving Attention in Transformers for Feature Matching**|Qing Wang et.al.|[2203.09645v2](http://arxiv.org/abs/2203.09645v2)|**[link](https://github.com/jamycheung/matchformer)**|
|**2022-03-10**|**ReF -- Rotation Equivariant Features for Local Feature Matching**|Abhishek Peri et.al.|[2203.05206v1](http://arxiv.org/abs/2203.05206v1)|null|
|**2022-03-09**|**Object-Based Visual Camera Pose Estimation From Ellipsoidal Model and 3D-Aware Ellipse Prediction**|Matthieu Zins et.al.|[2203.04613v1](http://arxiv.org/abs/2203.04613v1)|null|
|**2022-03-08**|**Tune your Place Recognition: Self-Supervised Domain Calibration via Robust SLAM**|Pierre-Yves Lajoie et.al.|[2203.04446v1](http://arxiv.org/abs/2203.04446v1)|**[link](https://github.com/mistlab/vpr-calibration-and-uncertainty)**|
|**2022-03-07**|**ZippyPoint: Fast Interest Point Detection, Description, and Matching through Mixed Precision Discretization**|Simon Maurer et.al.|[2203.03610v1](http://arxiv.org/abs/2203.03610v1)|null|
|**2022-03-07**|**Multi-Modal Lidar Dataset for Benchmarking General-Purpose Localization and Mapping Algorithms**|Qingqing Li et.al.|[2203.03454v1](http://arxiv.org/abs/2203.03454v1)|**[link](https://github.com/tiers/tiers-lidars-dataset)**|
|**2022-03-01**|**SwitchHit: A Probabilistic, Complementarity-Based Switching System for Improved Visual Place Recognition in Changing Environments**|Maria Waheed et.al.|[2203.00591v1](http://arxiv.org/abs/2203.00591v1)|null|
|**2022-02-28**|**Deep Camera Pose Regression Using Pseudo-LiDAR**|Ali Raza et.al.|[2203.00080v1](http://arxiv.org/abs/2203.00080v1)|null|
|**2022-02-25**|**RELMOBNET: A Robust Two-Stage End-To-End Training Approach For MOBILENETV3 Based Relative Camera Pose Estimation**|Praveen Kumar Rajendran et.al.|[2202.12838v1](http://arxiv.org/abs/2202.12838v1)|null|
|**2022-02-24**|**Highly-Efficient Binary Neural Networks for Visual Place Recognition**|Bruno Ferrarini et.al.|[2202.12375v1](http://arxiv.org/abs/2202.12375v1)|null|
|**2022-02-18**|**MultiRes-NetVLAD: Augmenting Place Recognition Training with Low-Resolution Imagery**|Ahmad Khaliq et.al.|[2202.09146v1](http://arxiv.org/abs/2202.09146v1)|**[link](https://github.com/ahmedest61/multires-netvlad)**|
|**2022-02-14**|**Tightly Coupled Learning Strategy for Weakly Supervised Hierarchical Place Recognition**|Y. Shen et.al.|[2202.06470v1](http://arxiv.org/abs/2202.06470v1)|null|
|**2022-02-11**|**Patch-NetVLAD+: Learned patch descriptor and weighted matching strategy for place recognition**|Yingfeng Cai et.al.|[2202.05738v1](http://arxiv.org/abs/2202.05738v1)|null|
|**2022-02-09**|**Object-Guided Day-Night Visual Localization in Urban Scenes**|Assia Benbihi et.al.|[2202.04445v1](http://arxiv.org/abs/2202.04445v1)|null|
|**2022-02-08**|**A Novel Image Descriptor with Aggregated Semantic Skeleton Representation for Long-term Visual Place Recognition**|Nie Jiwei et.al.|[2202.03677v1](http://arxiv.org/abs/2202.03677v1)|null|
|**2022-02-25**|**CFP-SLAM: A Real-time Visual SLAM Based on Coarse-to-Fine Probability in Dynamic Environments**|Xinggang Hu et.al.|[2202.01938v2](http://arxiv.org/abs/2202.01938v2)|null|
|**2022-02-03**|**Danish Airs and Grounds: A Dataset for Aerial-to-Street-Level Place Recognition and Localization**|Andrea Vallone et.al.|[2202.01821v1](http://arxiv.org/abs/2202.01821v1)|null|
|**2022-02-02**|**Training Semantic Descriptors for Image-Based Localization**|Ibrahim Cinaroglu et.al.|[2202.01212v1](http://arxiv.org/abs/2202.01212v1)|null|
|**2022-01-31**|**Hydra: A Real-time Spatial Perception Engine for 3D Scene Graph Construction and Optimization**|Nathan Hughes et.al.|[2201.13360v1](http://arxiv.org/abs/2201.13360v1)|null|
|**2022-01-31**|**Rigidity Preserving Image Transformations and Equivariance in Perspective**|Lucas Brynte et.al.|[2201.13065v1](http://arxiv.org/abs/2201.13065v1)|null|
|**2022-01-25**|**Learning Semantics for Visual Place Recognition through Multi-Scale Attention**|Valerio Paolicelli et.al.|[2201.09701v2](http://arxiv.org/abs/2201.09701v2)|**[link](https://github.com/valeriopaolicelli/SegVPR)**|
|**2022-01-22**|**Phase-SLAM: Phase Based Simultaneous Localization and Mapping for Mobile Structured Light Illumination Systems**|Xi Zheng et.al.|[2201.09048v1](http://arxiv.org/abs/2201.09048v1)|**[link](https://github.com/zhengxi-git/phase-slam)**|
|**2022-01-15**|**A Critical Analysis of Image-based Camera Pose Estimation Techniques**|Meng Xu et.al.|[2201.05816v1](http://arxiv.org/abs/2201.05816v1)|null|
|**2022-01-14**|**SRVIO: Super Robust Visual Inertial Odometry for dynamic environments and challenging Loop-closure conditions**|Ali Samadzadeh et.al.|[2201.05386v1](http://arxiv.org/abs/2201.05386v1)|**[link](https://github.com/aa-samad/srvio)**|
|**2021-12-23**|**NinjaDesc: Content-Concealing Visual Descriptors via Adversarial Learning**|Tony Ng et.al.|[2112.12785v1](http://arxiv.org/abs/2112.12785v1)|null|
|**2021-12-16**|**CrossLoc: Scalable Aerial Localization Assisted by Multimodal Synthetic Data**|Qi Yan et.al.|[2112.09081v1](http://arxiv.org/abs/2112.09081v1)|**[link](https://github.com/topo-epfl/crossloc)**|
|**2021-12-05**|**RADA: Robust Adversarial Data Augmentation for Camera Localization in Challenging Weather**|Jialu Wang et.al.|[2112.02469v1](http://arxiv.org/abs/2112.02469v1)|null|
|**2021-11-25**|**MegLoc: A Robust and Accurate Visual Localization Pipeline**|Shuxue Peng et.al.|[2111.13063v1](http://arxiv.org/abs/2111.13063v1)|null|
|**2021-10-08**|**Semantic Image Alignment for Vehicle Localization**|Markus Herb et.al.|[2110.04162v1](http://arxiv.org/abs/2110.04162v1)|null|
|**2021-10-05**|**Season-invariant GNSS-denied visual localization for UAVs**|Jouko Kinnari et.al.|[2110.01967v1](http://arxiv.org/abs/2110.01967v1)|**[link](https://github.com/aalto-intelligent-robotics/sivl)**|
|**2021-09-30**|**Forming a sparse representation for visual place recognition using a neurorobotic approach**|Sylvain Colomer et.al.|[2109.14916v1](http://arxiv.org/abs/2109.14916v1)|null|
|**2021-09-22**|**Audio-Visual Grounding Referring Expression for Robotic Manipulation**|Yefei Wang et.al.|[2109.10571v1](http://arxiv.org/abs/2109.10571v1)|null|
|**2021-09-20**|**Efficient shape mapping through dense touch and vision**|Sudharshan Suresh et.al.|[2109.09884v1](http://arxiv.org/abs/2109.09884v1)|**[link](https://github.com/cmurobotouch/ycb-sight)**|
|**2021-09-15**|**S3LAM: Structured Scene SLAM**|Mathieu Gonzalez et.al.|[2109.07339v1](http://arxiv.org/abs/2109.07339v1)|null|
|**2021-09-13**|**Monocular Camera Localization for Automated Vehicles Using Image Retrieval**|Eunhyek Joa et.al.|[2109.06296v1](http://arxiv.org/abs/2109.06296v1)|null|
|**2021-09-10**|**Line as a Visual Sentence: Context-aware Line Descriptor for Visual Localization**|Sungho Yoon et.al.|[2109.04753v1](http://arxiv.org/abs/2109.04753v1)|**[link](https://github.com/yosungho/LineTR)**|
|**2021-09-09**|**CrowdDriven: A New Challenging Dataset for Outdoor Visual Localization**|Ara Jafarzadeh et.al.|[2109.04527v1](http://arxiv.org/abs/2109.04527v1)|null|
|**2021-09-09**|**Keeping an Eye on Things: Deep Learned Features for Long-Term Visual Localization**|Mona Gridseth et.al.|[2109.04041v1](http://arxiv.org/abs/2109.04041v1)|**[link](https://github.com/utiasasrl/deep_learned_visual_features)**|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Keypoint Detection

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2023-03-22**|**Object Pose Estimation with Statistical Guarantees: Conformal Keypoint Detection and Geometric Uncertainty Propagation**|Heng Yang et.al.|[2303.12246](http://arxiv.org/abs/2303.12246)|null|
|**2023-03-21**|**RN-Net: Reservoir Nodes-Enabled Neuromorphic Vision Sensing Network**|Sangmin Yoo et.al.|[2303.10770](http://arxiv.org/abs/2303.10770)|null|
|**2023-03-17**|**ShaRPy: Shape Reconstruction and Hand Pose Estimation from RGB-D with Uncertainty**|Vanessa Wirth et.al.|[2303.10042](http://arxiv.org/abs/2303.10042)|null|
|**2023-03-15**|**Descriptor Distillation for Efficient Multi-Robot SLAM**|Xiyue Guo et.al.|[2303.08420](http://arxiv.org/abs/2303.08420)|null|
|**2023-03-15**|**From Local Binary Patterns to Pixel Difference Networks for Efficient Visual Representation Learning**|Zhuo Su et.al.|[2303.08414](http://arxiv.org/abs/2303.08414)|null|
|**2023-03-16**|**KGNv2: Separating Scale and Pose Prediction for Keypoint-based 6-DoF Grasp Synthesis on RGB-D input**|Yiye Chen et.al.|[2303.05617](http://arxiv.org/abs/2303.05617)|null|
|**2023-03-07**|**External Camera-based Mobile Robot Pose Estimation for Collaborative Perception with Smart Edge Sensors**|Simon Bultmann et.al.|[2303.03797](http://arxiv.org/abs/2303.03797)|null|
|**2023-02-26**|**PaRK-Detect: Towards Efficient Multi-Task Satellite Imagery Road Extraction via Patch-Wise Keypoints Detection**|Shenwei Xie et.al.|[2302.13263](http://arxiv.org/abs/2302.13263)|null|
|**2023-02-24**|**Hybrid machine-learned homogenization: Bayesian data mining and convolutional neural networks**|Julian Lißner et.al.|[2302.12545](http://arxiv.org/abs/2302.12545)|null|
|**2023-02-21**|**Deep Reinforcement Learning Based on Local GNN for Goal-conditioned Deformable Object Rearranging**|Yuhong Deng et.al.|[2302.10446](http://arxiv.org/abs/2302.10446)|null|
|**2023-02-12**|**A Correct-and-Certify Approach to Self-Supervise Object Pose Estimators via Ensemble Self-Training**|Jingnan Shi et.al.|[2302.06019](http://arxiv.org/abs/2302.06019)|null|
|**2023-02-11**|**Rethinking Vision Transformer and Masked Autoencoder in Multimodal Face Anti-Spoofing**|Zitong Yu et.al.|[2302.05744](http://arxiv.org/abs/2302.05744)|null|
|**2023-02-09**|**MAPS: A Noise-Robust Progressive Learning Approach for Source-Free Domain Adaptive Keypoint Detection**|Yuhe Ding et.al.|[2302.04589](http://arxiv.org/abs/2302.04589)|null|
|**2023-02-03**|**Explicit Box Detection Unifies End-to-End Multi-Person Pose Estimation**|Jie Yang et.al.|[2302.01593](http://arxiv.org/abs/2302.01593)|**[link](https://github.com/idea-research/ed-pose)**|
|**2023-02-03**|**Simple, Effective and General: A New Backbone for Cross-view Image Geo-localization**|Yingying Zhu et.al.|[2302.01572](http://arxiv.org/abs/2302.01572)|**[link](https://github.com/yanghongji2007/saig)**|
|**2023-01-21**|**Vision Aided Environment Semantics Extraction and Its Application in mmWave Beam Selection**|Feiyang Wen et.al.|[2301.08973](http://arxiv.org/abs/2301.08973)|null|
|**2023-01-18**|**OnePose++: Keypoint-Free One-Shot Object Pose Estimation without CAD Models**|Xingyi He et.al.|[2301.07673](http://arxiv.org/abs/2301.07673)|null|
|**2023-01-12**|**Towards High Performance One-Stage Human Pose Estimation**|Ling Li et.al.|[2301.04842v1](http://arxiv.org/abs/2301.04842v1)|null|
|**2022-12-31**|**Rethinking Rotation Invariance with Point Cloud Registration**|Jianhui Yu et.al.|[2301.00149v1](http://arxiv.org/abs/2301.00149v1)|null|
|**2023-02-06**|**Fruit Ripeness Classification: a Survey**|Matteo Rizzo et.al.|[2212.14441v2](http://arxiv.org/abs/2212.14441v2)|null|
|**2022-12-28**|**NeMo: 3D Neural Motion Fields from Multiple Video Instances of the Same Action**|Kuan-Chieh Wang et.al.|[2212.13660v1](http://arxiv.org/abs/2212.13660v1)|null|
|**2022-12-24**|**HandsOff: Labeled Dataset Generation With No Additional Human Annotations**|Austin Xu et.al.|[2212.12645v1](http://arxiv.org/abs/2212.12645v1)|null|
|**2022-12-13**|**Learning to Detect Good Keypoints to Match Non-Rigid Objects in RGB Images**|Welerson Melo et.al.|[2212.09589v1](http://arxiv.org/abs/2212.09589v1)|**[link](https://github.com/verlab/learningtodetect_sibgrapi_2022)**|
|**2022-12-15**|**Learning Markerless Robot-Depth Camera Calibration and End-Effector Pose Estimation**|Bugra C. Sefercik et.al.|[2212.07567v1](http://arxiv.org/abs/2212.07567v1)|null|
|**2023-02-01**|**DDM-NET: End-to-end learning of keypoint feature Detection, Description and Matching for 3D localization**|Xiangyu Xu et.al.|[2212.04575v2](http://arxiv.org/abs/2212.04575v2)|null|
|**2022-12-07**|**ViTPose+: Vision Transformer Foundation Model for Generic Body Pose Estimation**|Yufei Xu et.al.|[2212.04246v1](http://arxiv.org/abs/2212.04246v1)|**[link](https://github.com/vitae-transformer/vitpose)**|
|**2022-12-15**|**Designing Feature Vector Representations: A case study from Chemistry**|Signe Sidwall Thygesen et.al.|[2212.03731v2](http://arxiv.org/abs/2212.03731v2)|null|
|**2022-12-09**|**DiffuPose: Monocular 3D Human Pose Estimation via Denoising Diffusion Probabilistic Model**|Jeongjun Choi et.al.|[2212.02796v2](http://arxiv.org/abs/2212.02796v2)|null|
|**2022-12-05**|**Images Speak in Images: A Generalist Painter for In-Context Visual Learning**|Xinlong Wang et.al.|[2212.02499v1](http://arxiv.org/abs/2212.02499v1)|**[link](https://github.com/baaivision/painter)**|
|**2022-12-06**|**R2FD2: Fast and Robust Matching of Multimodal Remote Sensing Image via Repeatable Feature Detector and Rotation-invariant Feature Descriptor**|Bai Zhu et.al.|[2212.02277v2](http://arxiv.org/abs/2212.02277v2)|null|
|**2022-11-28**|**FeatureBooster: Boosting Feature Descriptors with a Lightweight Neural Network**|Xinjiang Wang et.al.|[2211.15069v1](http://arxiv.org/abs/2211.15069v1)|null|
|**2022-11-29**|**BALF: Simple and Efficient Blur Aware Local Feature Detector**|Zhenjun Zhao et.al.|[2211.14731v2](http://arxiv.org/abs/2211.14731v2)|null|
|**2022-11-21**|**Conjugate Product Graphs for Globally Optimal 2D-3D Shape Matching**|Paul Roetzer et.al.|[2211.11589v1](http://arxiv.org/abs/2211.11589v1)|null|
|**2022-11-07**|**Learning Feature Descriptors for Pre- and Intra-operative Point Cloud Matching for Laparoscopic Liver Registration**|Zixin Yang et.al.|[2211.03688v1](http://arxiv.org/abs/2211.03688v1)|null|
|**2022-10-31**|**Tree Detection and Diameter Estimation Based on Deep Learning**|Vincent Grondin et.al.|[2210.17424v1](http://arxiv.org/abs/2210.17424v1)|**[link](https://github.com/norlab-ulaval/perceptreev1)**|
|**2022-10-26**|**Learning a Task-specific Descriptor for Robust Matching of 3D Point Clouds**|Zhiyuan Zhang et.al.|[2210.14899v1](http://arxiv.org/abs/2210.14899v1)|null|
|**2022-10-23**|**Few-Shot Meta Learning for Recognizing Facial Phenotypes of Genetic Disorders**|Ömer Sümer et.al.|[2210.12705v1](http://arxiv.org/abs/2210.12705v1)|null|
|**2022-10-21**|**Real-time Detection of 2D Tool Landmarks with Synthetic Training Data**|Bram Vanherle et.al.|[2210.11991v1](http://arxiv.org/abs/2210.11991v1)|null|
|**2022-10-09**|**Fusing Event-based Camera and Radar for SLAM Using Spiking Neural Networks with Continual STDP Learning**|Ali Safa et.al.|[2210.04236v1](http://arxiv.org/abs/2210.04236v1)|null|
|**2022-10-04**|**Centroid Distance Keypoint Detector for Colored Point Clouds**|Hanzhe Teng et.al.|[2210.01298v1](http://arxiv.org/abs/2210.01298v1)|**[link](https://github.com/ucr-robotics/ced_detector)**|
|**2022-09-28**|**Category-Level Global Camera Pose Estimation with Multi-Hypothesis Point Cloud Correspondences**|Jun-Jee Chao et.al.|[2209.14419v1](http://arxiv.org/abs/2209.14419v1)|null|
|**2022-09-28**|**USEEK: Unsupervised SE(3)-Equivariant 3D Keypoints for Generalizable Manipulation**|Zhengrong Xue et.al.|[2209.13864v1](http://arxiv.org/abs/2209.13864v1)|null|
|**2022-10-16**|**Suture Thread Spline Reconstruction from Endoscopic Images for Robotic Surgery with Reliability-driven Keypoint Detection**|Neelay Joglekar et.al.|[2209.13657v2](http://arxiv.org/abs/2209.13657v2)|**[link](https://github.com/ucsdarclab/thread-reconstruction)**|
|**2022-09-27**|**Learning-Based Dimensionality Reduction for Computing Compact and Effective Local Feature Descriptors**|Hao Dong et.al.|[2209.13586v1](http://arxiv.org/abs/2209.13586v1)|**[link](https://github.com/prbonn/descriptor-dr)**|
|**2022-09-26**|**Performance Evaluation of 3D Keypoint Detectors and Descriptors on Coloured Point Clouds in Subsea Environments**|Kyungmin Jung et.al.|[2209.12881v1](http://arxiv.org/abs/2209.12881v1)|null|
|**2022-10-07**|**Long-Lived Accurate Keypoints in Event Streams**|Philippe Chiberre et.al.|[2209.10385v2](http://arxiv.org/abs/2209.10385v2)|null|
|**2022-09-20**|**Integrative Feature and Cost Aggregation with Transformers for Dense Correspondence**|Sunghwan Hong et.al.|[2209.08742v2](http://arxiv.org/abs/2209.08742v2)|null|
|**2022-09-15**|**Online Marker-free Extrinsic Camera Calibration using Person Keypoint Detections**|Bastian Pätzold et.al.|[2209.07393v1](http://arxiv.org/abs/2209.07393v1)|**[link](https://github.com/ais-bonn/extrcamcalib_personkeypoints)**|
|**2022-09-07**|**Deep Learning-Based Automatic Diagnosis System for Developmental Dysplasia of the Hip**|Yang Li et.al.|[2209.03440v1](http://arxiv.org/abs/2209.03440v1)|null|
|**2022-08-27**|**Learning to SLAM on the Fly in Unknown Environments: A Continual Learning Approach for Drones in Visually Ambiguous Scenes**|Ali Safa et.al.|[2208.12997v1](http://arxiv.org/abs/2208.12997v1)|null|
|**2022-08-24**|**Self-Supervised Endoscopic Image Key-Points Matching**|Manel Farhat et.al.|[2208.11424v1](http://arxiv.org/abs/2208.11424v1)|**[link](https://github.com/abenhamadou/Self-Supervised-Endoscopic-Image-Key-Points-Matching)**|
|**2022-08-19**|**Blind-Spot Collision Detection System for Commercial Vehicles Using Multi Deep CNN Architecture**|Muhammad Muzammel et.al.|[2208.08224v2](http://arxiv.org/abs/2208.08224v2)|null|
|**2022-08-08**|**MetaGraspNet: A Large-Scale Benchmark Dataset for Scene-Aware Ambidextrous Bin Picking via Physics-based Metaverse Synthesis**|Maximilian Gilles et.al.|[2208.03963v1](http://arxiv.org/abs/2208.03963v1)|null|
|**2022-08-07**|**CVLNet: Cross-View Semantic Correspondence Learning for Video-based Camera Localization**|Yujiao Shi et.al.|[2208.03660v1](http://arxiv.org/abs/2208.03660v1)|null|
|**2022-07-29**|**Explicit Occlusion Reasoning for Multi-person 3D Human Pose Estimation**|Qihao Liu et.al.|[2208.00090v1](http://arxiv.org/abs/2208.00090v1)|null|
|**2022-07-25**|**Translating a Visual LEGO Manual to a Machine-Executable Plan**|Ruocheng Wang et.al.|[2207.12572v1](http://arxiv.org/abs/2207.12572v1)|null|
|**2022-07-21**|**Multi-modal Retinal Image Registration Using a Keypoint-Based Vessel Structure Aligning Network**|Aline Sindel et.al.|[2207.10506v1](http://arxiv.org/abs/2207.10506v1)|null|
|**2022-07-15**|**Human keypoint detection for close proximity human-robot interaction**|Jan Docekal et.al.|[2207.07742v1](http://arxiv.org/abs/2207.07742v1)|null|
|**2022-07-15**|**Adversarial Focal Loss: Asking Your Discriminator for Hard Examples**|Chen Liu et.al.|[2207.07739v1](http://arxiv.org/abs/2207.07739v1)|null|
|**2022-07-13**|**Rapid Person Re-Identification via Sub-space Consistency Regularization**|Qingze Yin et.al.|[2207.05933v1](http://arxiv.org/abs/2207.05933v1)|null|
|**2022-07-07**|**RWT-SLAM: Robust Visual SLAM for Highly Weak-textured Environments**|Qihao Peng et.al.|[2207.03539v1](http://arxiv.org/abs/2207.03539v1)|null|
|**2022-08-15**|**Semi-supervised Human Pose Estimation in Art-historical Images**|Matthias Springstein et.al.|[2207.02976v3](http://arxiv.org/abs/2207.02976v3)|**[link](https://github.com/tibhannover/iart-semi-pose)**|
|**2022-07-01**|**Weakly-supervised High-fidelity Ultrasound Video Synthesis with Feature Decoupling**|Jiamin Liang et.al.|[2207.00474v1](http://arxiv.org/abs/2207.00474v1)|null|
|**2022-06-24**|**Motion Estimation for Large Displacements and Deformations**|Qiao Chen et.al.|[2206.12464v1](http://arxiv.org/abs/2206.12464v1)|null|
|**2022-06-24**|**Deep embedded clustering algorithm for clustering PACS repositories**|Teo Manojlović et.al.|[2206.12417v1](http://arxiv.org/abs/2206.12417v1)|null|
|**2022-06-21**|**KTN: Knowledge Transfer Network for Learning Multi-person 2D-3D Correspondences**|Xuanhan Wang et.al.|[2206.10090v1](http://arxiv.org/abs/2206.10090v1)|**[link](https://github.com/stoa-xh91/humandensepose)**|
|**2022-06-20**|**Self-Supervised Consistent Quantization for Fully Unsupervised Image Retrieval**|Guile Wu et.al.|[2206.09806v1](http://arxiv.org/abs/2206.09806v1)|null|
|**2022-06-15**|**A Unified Sequence Interface for Vision Tasks**|Ting Chen et.al.|[2206.07669v1](http://arxiv.org/abs/2206.07669v1)|**[link](https://github.com/google-research/pix2seq)**|
|**2022-06-09**|**Beyond RGB: Scene-Property Synthesis with Neural Radiance Fields**|Mingtong Zhang et.al.|[2206.04669v1](http://arxiv.org/abs/2206.04669v1)|null|
|**2022-06-03**|**SNAKE: Shape-aware Neural 3D Keypoint Field**|Chengliang Zhong et.al.|[2206.01724v1](http://arxiv.org/abs/2206.01724v1)|**[link](https://github.com/zhongcl-thu/snake)**|
|**2022-05-17**|**MulT: An End-to-End Multitask Learning Transformer**|Deblina Bhattacharjee et.al.|[2205.08303v1](http://arxiv.org/abs/2205.08303v1)|null|
|**2022-05-10**|**ConfLab: A Rich Multimodal Multisensor Dataset of Free-Standing Social Interactions In-the-Wild**|Chirag Raman et.al.|[2205.05177v1](http://arxiv.org/abs/2205.05177v1)|**[link](https://github.com/tudelft-spc-lab/conflab)**|
|**2022-04-28**|**Polarimetric imaging for the detection of synthetic models of SARS-CoV-2: a proof of concept**|Emilio Gomez-Gonzalez et.al.|[2204.14050v1](http://arxiv.org/abs/2204.14050v1)|null|
|**2022-05-02**|**GRIT: General Robust Image Task Benchmark**|Tanmay Gupta et.al.|[2204.13653v2](http://arxiv.org/abs/2204.13653v2)|**[link](https://github.com/allenai/grit_official)**|
|**2022-05-24**|**ViTPose: Simple Vision Transformer Baselines for Human Pose Estimation**|Yufei Xu et.al.|[2204.12484v2](http://arxiv.org/abs/2204.12484v2)|**[link](https://github.com/vitae-transformer/vitpose)**|
|**2022-04-26**|**Unified GCNs: Towards Connecting GCNs with CNNs**|Ziyan Zhang et.al.|[2204.12300v1](http://arxiv.org/abs/2204.12300v1)|null|
|**2022-04-19**|**Self-Supervised Equivariant Learning for Oriented Keypoint Detection**|Jongmin Lee et.al.|[2204.08613v1](http://arxiv.org/abs/2204.08613v1)|**[link](https://github.com/bluedream1121/REKD)**|
|**2022-04-17**|**The Z-axis, X-axis, Weight and Disambiguation Methods for Constructing Local Reference Frame in 3D Registration: An Evaluation**|Bao Zhao et.al.|[2204.08024v1](http://arxiv.org/abs/2204.08024v1)|null|
|**2022-04-15**|**2D Human Pose Estimation: A Survey**|Haoming Chen et.al.|[2204.07370v1](http://arxiv.org/abs/2204.07370v1)|null|
|**2022-04-11**|**Towards Homogeneous Modality Learning and Multi-Granularity Information Exploration for Visible-Infrared Person Re-Identification**|Haojie Liu et.al.|[2204.04842v1](http://arxiv.org/abs/2204.04842v1)|null|
|**2022-04-07**|**Cloning Outfits from Real-World Images to 3D Characters for Generalizable Person Re-Identification**|Yanan Wang et.al.|[2204.02611v2](http://arxiv.org/abs/2204.02611v2)|**[link](https://github.com/yanan-wang-cs/clonedperson)**|
|**2022-04-02**|**SkeleVision: Towards Adversarial Resiliency of Person Tracking with Multi-Task Learning**|Nilaksh Das et.al.|[2204.00734v1](http://arxiv.org/abs/2204.00734v1)|**[link](https://github.com/nilakshdas/skelevision)**|
|**2022-04-01**|**MS-HLMO: Multi-scale Histogram of Local Main Orientation for Remote Sensing Image Registration**|Chenzhong Gao et.al.|[2204.00260v1](http://arxiv.org/abs/2204.00260v1)|null|
|**2022-03-29**|**Assessing Evolutionary Terrain Generation Methods for Curriculum Reinforcement Learning**|David Howard et.al.|[2203.15172v1](http://arxiv.org/abs/2203.15172v1)|null|
|**2022-03-28**|**REGTR: End-to-end Point Cloud Correspondences with Transformers**|Zi Jian Yew et.al.|[2203.14517v1](http://arxiv.org/abs/2203.14517v1)|**[link](https://github.com/yewzijian/regtr)**|
|**2022-03-27**|**UMT: Unified Multi-modal Transformers for Joint Video Moment Retrieval and Highlight Detection**|Ye Liu et.al.|[2203.12745v2](http://arxiv.org/abs/2203.12745v2)|**[link](https://github.com/tencentarc/umt)**|
|**2022-03-21**|**MatchFormer: Interleaving Attention in Transformers for Feature Matching**|Qing Wang et.al.|[2203.09645v2](http://arxiv.org/abs/2203.09645v2)|**[link](https://github.com/jamycheung/matchformer)**|
|**2022-03-16**|**PosePipe: Open-Source Human Pose Estimation Pipeline for Clinical Research**|R. James Cotton et.al.|[2203.08792v1](http://arxiv.org/abs/2203.08792v1)|**[link](https://github.com/peabody124/posepipeline)**|
|**2022-03-11**|**DRTAM: Dual Rank-1 Tensor Attention Module**|Hanxing Chi et.al.|[2203.05893v1](http://arxiv.org/abs/2203.05893v1)|null|
|**2022-03-07**|**Weakly Supervised Learning of Keypoints for 6D Object Pose Estimation**|Meng Tian et.al.|[2203.03498v1](http://arxiv.org/abs/2203.03498v1)|null|
|**2022-02-10**|**Motion-Aware Transformer For Occluded Person Re-identification**|Mi Zhou et.al.|[2202.04243v2](http://arxiv.org/abs/2202.04243v2)|null|
|**2022-02-03**|**Sim2Real Object-Centric Keypoint Detection and Description**|Chengliang Zhong et.al.|[2202.00448v2](http://arxiv.org/abs/2202.00448v2)|null|
|**2022-01-16**|**Cross-Centroid Ripple Pattern for Facial Expression Recognition**|Monu Verma et.al.|[2201.05958v1](http://arxiv.org/abs/2201.05958v1)|null|
|**2022-01-14**|**Reproducing BowNet: Learning Representations by Predicting Bags of Visual Words**|Harry Nguyen et.al.|[2201.03556v2](http://arxiv.org/abs/2201.03556v2)|**[link](https://github.com/StoneY1/Reproducing-BowNet)**|
|**2022-01-10**|**TFS Recognition: Investigating MPH]{Thai Finger Spelling Recognition: Investigating MediaPipe Hands Potentials**|Jinnavat Sanalohit et.al.|[2201.03170v1](http://arxiv.org/abs/2201.03170v1)|null|
|**2022-01-06**|**A Keypoint Detection and Description Network Based on the Vessel Structure for Multi-Modal Retinal Image Registration**|Aline Sindel et.al.|[2201.02242v1](http://arxiv.org/abs/2201.02242v1)|null|
|**2021-12-28**|**Skin feature point tracking using deep feature encodings**|Jose Ramon Chang et.al.|[2112.14159v1](http://arxiv.org/abs/2112.14159v1)|null|
|**2021-12-23**|**Data-efficient learning for 3D mirror symmetry detection**|Yancong Lin et.al.|[2112.12579v1](http://arxiv.org/abs/2112.12579v1)|null|
|**2021-12-22**|**Improved 2D Keypoint Detection in Out-of-Balance and Fall Situations -- combining input rotations and a kinematic model**|Michael Zwölfer et.al.|[2112.12193v1](http://arxiv.org/abs/2112.12193v1)|null|
|**2021-12-22**|**Looking Beyond Corners: Contrastive Learning of Visual Representations for Keypoint Detection and Description Extraction**|Henrique Siqueira et.al.|[2112.12002v1](http://arxiv.org/abs/2112.12002v1)|**[link](https://github.com/siqueira-hc/corrnet)**|
|**2021-12-19**|**Parallel Multi-Scale Networks with Deep Supervision for Hand Keypoint Detection**|Renjie Li et.al.|[2112.10275v1](http://arxiv.org/abs/2112.10275v1)|null|
|**2021-12-19**|**GPU optimization of the 3D Scale-invariant Feature Transform Algorithm and a Novel BRIEF-inspired 3D Fast Descriptor**|Jean-Baptiste Carluer et.al.|[2112.10258v1](http://arxiv.org/abs/2112.10258v1)|**[link](https://github.com/carluerjb/3d_sift_cuda)**|
|**2021-12-16**|**Masked Feature Prediction for Self-Supervised Visual Pre-Training**|Chen Wei et.al.|[2112.09133v1](http://arxiv.org/abs/2112.09133v1)|**[link](https://github.com/facebookresearch/SlowFast)**|
|**2021-12-13**|**DenseGAP: Graph-Structured Dense Correspondence Learning with Anchor Points**|Zhengfei Kuang et.al.|[2112.06910v1](http://arxiv.org/abs/2112.06910v1)|null|
|**2021-12-12**|**Few-shot Keypoint Detection with Uncertainty Learning for Unseen Species**|Changsheng Lu et.al.|[2112.06183v1](http://arxiv.org/abs/2112.06183v1)|**[link](https://github.com/alanlusun/few-shot-keypoint-detection)**|
|**2021-12-13**|**Few-Shot Keypoint Detection as Task Adaptation via Latent Embeddings**|Mel Vecerik et.al.|[2112.04910v2](http://arxiv.org/abs/2112.04910v2)|null|
|**2021-12-06**|**ALIKE: Accurate and Lightweight Keypoint Detection and Descriptor Extraction**|Xiaoming Zhao et.al.|[2112.02906v1](http://arxiv.org/abs/2112.02906v1)|**[link](https://github.com/Shiaoming/ALIKE)**|
|**2021-11-25**|**Attend to Who You Are: Supervising Self-Attention for Keypoint Detection and Instance-Aware Association**|Sen Yang et.al.|[2111.12892v1](http://arxiv.org/abs/2111.12892v1)|**[link](https://github.com/yangsenius/ssa)**|
|**2021-11-08**|**Template NeRF: Towards Modeling Dense Shape Correspondences from Category-Specific Object Images**|Jianfei Guo et.al.|[2111.04237v1](http://arxiv.org/abs/2111.04237v1)|null|
|**2021-11-04**|**Voxel-based 3D Detection and Reconstruction of Multiple Objects from a Single Image**|Feng Liu et.al.|[2111.03098v1](http://arxiv.org/abs/2111.03098v1)|null|
|**2021-11-01**|**Learning Event-based Spatio-Temporal Feature Descriptors via Local Synaptic Plasticity: A Biologically-realistic Perspective of Computer Vision**|Ali Safa et.al.|[2111.00791v2](http://arxiv.org/abs/2111.00791v2)|null|
|**2021-10-30**|**Geometry-Aware Hierarchical Bayesian Learning on Manifolds**|Yonghui Fan et.al.|[2111.00184v1](http://arxiv.org/abs/2111.00184v1)|null|
|**2021-10-26**|**CoFiNet: Reliable Coarse-to-fine Correspondences for Robust Point Cloud Registration**|Hao Yu et.al.|[2110.14076v1](http://arxiv.org/abs/2110.14076v1)|**[link](https://github.com/haoyu94/coarse-to-fine-correspondences)**|
|**2021-10-23**|**HWTool: Fully Automatic Mapping of an Extensible C++ Image Processing Language to Hardware**|James Hegarty et.al.|[2110.12106v1](http://arxiv.org/abs/2110.12106v1)|null|
|**2021-10-18**|**Keypoint-Based Bimanual Shaping of Deformable Linear Objects under Environmental Constraints using Hierarchical Action Planning**|Shengzeng Huo et.al.|[2110.08962v1](http://arxiv.org/abs/2110.08962v1)|null|
|**2021-10-11**|**High-order Tensor Pooling with Attention for Action Recognition**|Piotr Koniusz et.al.|[2110.05216v1](http://arxiv.org/abs/2110.05216v1)|null|
|**2021-10-10**|**Digging Into Self-Supervised Learning of Feature Descriptors**|Iaroslav Melekhov et.al.|[2110.04773v1](http://arxiv.org/abs/2110.04773v1)|null|
|**2021-10-04**|**BPFNet: A Unified Framework for Bimodal Palmprint Alignment and Fusion**|Zhaoqun Li et.al.|[2110.01179v1](http://arxiv.org/abs/2110.01179v1)|**[link](https://github.com/dxbdxx/bpfnet)**|
|**2021-10-01**|**Machine learning aided noise filtration and signal classification for CREDO experiment**|Łukasz Bibrzycki et.al.|[2110.00297v1](http://arxiv.org/abs/2110.00297v1)|null|
|**2021-09-28**|**PDC-Net+: Enhanced Probabilistic Dense Correspondence Network**|Prune Truong et.al.|[2109.13912v2](http://arxiv.org/abs/2109.13912v2)|**[link](https://github.com/PruneTruong/DenseMatching)**|
|**2021-09-27**|**HarrisZ $^+$ : Harris Corner Selection for Next-Gen Image Matching Pipelines**|Fabio Bellavia et.al.|[2109.12925v3](http://arxiv.org/abs/2109.12925v3)|null|
|**2021-09-24**|**Catadioptric Stereo on a Smartphone**|Kristijan Bartol et.al.|[2109.11872v1](http://arxiv.org/abs/2109.11872v1)|null|
|**2021-09-20**|**Semi-supervised Dense Keypointsusing Unlabeled Multiview Images**|Zhixuan Yu et.al.|[2109.09299v1](http://arxiv.org/abs/2109.09299v1)|null|
|**2021-08-31**|**A Novel Dataset for Keypoint Detection of quadruped Animals from Images**|Prianka Banik et.al.|[2108.13958v1](http://arxiv.org/abs/2108.13958v1)|**[link](https://github.com/prinik/awa-pose)**|
|**2021-08-27**|**A Matching Algorithm based on Image Attribute Transfer and Local Features for Underwater Acoustic and Optical Images**|Xiaoteng Zhou et.al.|[2108.12151v1](http://arxiv.org/abs/2108.12151v1)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Image Matching

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2023-03-15**|**Rethinking Optical Flow from Geometric Matching Consistent Perspective**|Qiaole Dong et.al.|[2303.08384](http://arxiv.org/abs/2303.08384)|**[link](https://github.com/dqiaole/matchflow)**|
|**2023-03-14**|**PATS: Patch Area Transportation with Subdivision for Local Feature Matching**|Junjie Ni et.al.|[2303.07700](http://arxiv.org/abs/2303.07700)|null|
|**2023-03-07**|**Parsing Line Segments of Floor Plan Images Using Graph Neural Networks**|Mingxiang Chen et.al.|[2303.03851](http://arxiv.org/abs/2303.03851)|null|
|**2023-03-06**|**Improving Transformer-based Image Matching by Cascaded Capturing Spatially Informative Keypoints**|Chenjie Cao et.al.|[2303.02885](http://arxiv.org/abs/2303.02885)|null|
|**2023-03-10**|**ParaFormer: Parallel Attention Transformer for Efficient Feature Matching**|Xiaoyong Lu et.al.|[2303.00941](http://arxiv.org/abs/2303.00941)|null|
|**2023-03-01**|**RIFT2: Speeding-up RIFT with A New Rotation-Invariance Technique**|Jiayuan Li et.al.|[2303.00319](http://arxiv.org/abs/2303.00319)|**[link](https://github.com/ljy-rs/rift2-multimodal-matching-rotation)**|
|**2023-02-28**|**Nonlinear Intensity, Scale and Rotation Invariant Matching for Multimodal Images**|Zhongli Fan et.al.|[2302.14239](http://arxiv.org/abs/2302.14239)|**[link](https://github.com/zhongli-fan/nisr)**|
|**2023-02-25**|**BrainCLIP: Bridging Brain and Visual-Linguistic Representation via CLIP for Generic Natural Visual Stimulus Decoding from fMRI**|Yulong Liu et.al.|[2302.12971](http://arxiv.org/abs/2302.12971)|null|
|**2023-02-24**|**Classification of structural building damage grades from multi-temporal photogrammetric point clouds using a machine learning model trained on virtual laser scanning data**|Vivien Zahs et.al.|[2302.12591](http://arxiv.org/abs/2302.12591)|null|
|**2023-02-20**|**A Large Scale Homography Benchmark**|Daniel Barath et.al.|[2302.09997](http://arxiv.org/abs/2302.09997)|null|
|**2023-02-12**|**OAMatcher: An Overlapping Areas-based Network for Accurate Local Feature Matching**|Kun Dai et.al.|[2302.05846](http://arxiv.org/abs/2302.05846)|**[link](https://github.com/dk-hu/oamatcher)**|
|**2023-02-10**|**General, Single-shot, Target-less, and Automatic LiDAR-Camera Extrinsic Calibration Toolbox**|Kenji Koide et.al.|[2302.05094](http://arxiv.org/abs/2302.05094)|**[link](https://github.com/koide3/direct_visual_lidar_calibration)**|
|**2023-02-03**|**Simple, Effective and General: A New Backbone for Cross-view Image Geo-localization**|Yingying Zhu et.al.|[2302.01572](http://arxiv.org/abs/2302.01572)|**[link](https://github.com/yanghongji2007/saig)**|
|**2023-01-27**|**Harmonizing Flows: Unsupervised MR harmonization based on normalizing flows**|Farzad Beizaee et.al.|[2301.11551](http://arxiv.org/abs/2301.11551)|**[link](https://github.com/farzad-bz/harmonizing-flows)**|
|**2023-01-25**|**Local Feature Extraction from Salient Regions by Feature Map Transformation**|Yerim Jung et.al.|[2301.10413v1](http://arxiv.org/abs/2301.10413v1)|null|
|**2023-01-24**|**Feature-based Image Matching for Identifying Individual Kākā**|Fintan O'Sullivan et.al.|[2301.06678v2](http://arxiv.org/abs/2301.06678v2)|null|
|**2023-01-18**|**Instance Segmentation Based Graph Extraction for Handwritten Circuit Diagram Images**|Johannes Bayer et.al.|[2301.03155v2](http://arxiv.org/abs/2301.03155v2)|null|
|**2023-01-08**|**DeepMatcher: A Deep Transformer-based Network for Robust and Accurate Local Feature Matching**|Tao Xie et.al.|[2301.02993v1](http://arxiv.org/abs/2301.02993v1)|**[link](https://github.com/XT-1997/DeepMatcher)**|
|**2023-01-07**|**Deep Learning-Based UAV Aerial Triangulation without Image Control Points**|Jiageng Zhong et.al.|[2301.02869v1](http://arxiv.org/abs/2301.02869v1)|null|
|**2023-01-06**|**The UNCOVER Survey: A first-look HST+JWST catalog of 50,000 galaxies near Abell 2744 and beyond**|John R. Weaver et.al.|[2301.02671v1](http://arxiv.org/abs/2301.02671v1)|null|
|**2023-02-13**|**Translating Text Synopses to Video Storyboards**|Xu Gu et.al.|[2301.00135v2](http://arxiv.org/abs/2301.00135v2)|null|
|**2022-12-23**|**SuperGF: Unifying Local and Global Features for Visual Localization**|Wenzheng Song et.al.|[2212.13105v1](http://arxiv.org/abs/2212.13105v1)|null|
|**2022-12-26**|**Transformer and GAN Based Super-Resolution Reconstruction Network for Medical Images**|Weizhi Du et.al.|[2212.13068v1](http://arxiv.org/abs/2212.13068v1)|null|
|**2022-12-20**|**Seafloor-Invariant Caustics Removal from Underwater Imagery**|Panagiotis Agrafiotis et.al.|[2212.10167v1](http://arxiv.org/abs/2212.10167v1)|null|
|**2022-12-15**|**DeepLSD: Line Segment Detection and Refinement with Deep Image Gradients**|Rémi Pautrat et.al.|[2212.07766v1](http://arxiv.org/abs/2212.07766v1)|**[link](https://github.com/cvg/deeplsd)**|
|**2022-12-14**|**Shared Coupling-bridge for Weakly Supervised Local Feature Learning**|Jiayuan Sun et.al.|[2212.07047v1](http://arxiv.org/abs/2212.07047v1)|**[link](https://github.com/sunjiayuanro/scfeat)**|
|**2022-12-05**|**Real Time Incremental Image Mosaicking Without Use of Any Camera Parameter**|Suleyman Melih Portakal et.al.|[2212.02302v1](http://arxiv.org/abs/2212.02302v1)|null|
|**2022-12-05**|**ObjectMatch: Robust Registration using Canonical Object Correspondences**|Can Gümeli et.al.|[2212.01985v1](http://arxiv.org/abs/2212.01985v1)|null|
|**2022-12-07**|**Universe Points Representation Learning for Partial Multi-Graph Matching**|Zhakshylyk Nurlanov et.al.|[2212.00780v2](http://arxiv.org/abs/2212.00780v2)|null|
|**2022-11-30**|**Self-Supervised Feature Learning for Long-Term Metric Visual Localization**|Yuxuan Chen et.al.|[2212.00122v1](http://arxiv.org/abs/2212.00122v1)|null|
|**2022-11-28**|**FeatureBooster: Boosting Feature Descriptors with a Lightweight Neural Network**|Xinjiang Wang et.al.|[2211.15069v1](http://arxiv.org/abs/2211.15069v1)|null|
|**2022-11-19**|**Person Text-Image Matching via Text-Feature Interpretability Embedding and External Attack Node Implantation**|Fan Li et.al.|[2211.08657v2](http://arxiv.org/abs/2211.08657v2)|**[link](https://github.com/lhf12278/saa)**|
|**2022-11-20**|**Detecting Line Segments in Motion-blurred Images with Events**|Huai Yu et.al.|[2211.07365v2](http://arxiv.org/abs/2211.07365v2)|**[link](https://github.com/lh9171338/FE-LSD)**|
|**2022-11-15**|**Fast Key Points Detection and Matching for Tree-Structured Images**|Hao Wang et.al.|[2211.03242v2](http://arxiv.org/abs/2211.03242v2)|null|
|**2022-10-25**|**A Comparative Study on Deep-Learning Methods for Dense Image Matching of Multi-angle and Multi-date Remote Sensing Stereo Images**|Hessah Albanwan et.al.|[2210.14031v1](http://arxiv.org/abs/2210.14031v1)|null|
|**2022-10-11**|**DeepMLE: A Robust Deep Maximum Likelihood Estimator for Two-view Structure from Motion**|Yuxi Xiao et.al.|[2210.05517v1](http://arxiv.org/abs/2210.05517v1)|null|
|**2022-10-07**|**Mars Rover Localization Based on A2G Obstacle Distribution Pattern Matching**|Lang Zhou et.al.|[2210.03398v1](http://arxiv.org/abs/2210.03398v1)|**[link](https://github.com/Mars-Rover-Localization/A2G-Localization)**|
|**2022-09-27**|**Learning-Based Dimensionality Reduction for Computing Compact and Effective Local Feature Descriptors**|Hao Dong et.al.|[2209.13586v1](http://arxiv.org/abs/2209.13586v1)|**[link](https://github.com/prbonn/descriptor-dr)**|
|**2022-09-25**|**ECO-TR: Efficient Correspondences Finding Via Coarse-to-Fine Refinement**|Dongli Tan et.al.|[2209.12213v1](http://arxiv.org/abs/2209.12213v1)|null|
|**2022-09-22**|**DRKF: Distilled Rotated Kernel Fusion for Efficiently Boosting Rotation Invariance in Image Matching**|Chao Li et.al.|[2209.10907v1](http://arxiv.org/abs/2209.10907v1)|null|
|**2022-11-15**|**Uncertainty-aware Efficient Subgraph Isomorphism using Graph Topology**|Arpan Kusari et.al.|[2209.09090v2](http://arxiv.org/abs/2209.09090v2)|null|
|**2022-09-16**|**SRFeat: Learning Locally Accurate and Globally Consistent Non-Rigid Shape Correspondence**|Lei Li et.al.|[2209.07806v1](http://arxiv.org/abs/2209.07806v1)|**[link](https://github.com/craigleili/srfeat)**|
|**2022-08-30**|**ASpanFormer: Detector-Free Image Matching with Adaptive Span Transformer**|Hongkai Chen et.al.|[2208.14201v1](http://arxiv.org/abs/2208.14201v1)|**[link](https://github.com/apple/ml-aspanformer)**|
|**2022-08-25**|**A Gis Aided Approach for Geolocalizing an Unmanned Aerial System Using Deep Learning**|Jianli Wei et.al.|[2208.12251v1](http://arxiv.org/abs/2208.12251v1)|**[link](https://github.com/osupcvlab/ubiheredrone2021)**|
|**2022-08-25**|**UAS Navigation in the Real World Using Visual Observation**|Yuci Han et.al.|[2208.12125v1](http://arxiv.org/abs/2208.12125v1)|null|
|**2022-08-24**|**Self-Supervised Endoscopic Image Key-Points Matching**|Manel Farhat et.al.|[2208.11424v1](http://arxiv.org/abs/2208.11424v1)|**[link](https://github.com/abenhamadou/Self-Supervised-Endoscopic-Image-Key-Points-Matching)**|
|**2022-08-22**|**Equivariant Hypergraph Neural Networks**|Jinwoo Kim et.al.|[2208.10428v1](http://arxiv.org/abs/2208.10428v1)|**[link](https://github.com/jw9730/ehnn)**|
|**2022-09-22**|**Understanding Attention for Vision-and-Language Tasks**|Feiqi Cao et.al.|[2208.08104v2](http://arxiv.org/abs/2208.08104v2)|**[link](https://github.com/adlnlp/attention_vl)**|
|**2022-08-16**|**Hierarchical Attention Network for Few-Shot Object Detection via Meta-Contrastive Learning**|Dongwoo Park et.al.|[2208.07039v2](http://arxiv.org/abs/2208.07039v2)|**[link](https://github.com/infinity7428/hANMCL)**|
|**2022-08-04**|**Learning Modal-Invariant and Temporal-Memory for Video-based Visible-Infrared Person Re-Identification**|Xinyu Lin et.al.|[2208.02450v1](http://arxiv.org/abs/2208.02450v1)|**[link](https://github.com/vcm-project233/mitml)**|
|**2022-08-04**|**OmniCity: Omnipotent City Understanding with Multi-level and Multi-view Images**|Weijia Li et.al.|[2208.00928v2](http://arxiv.org/abs/2208.00928v2)|null|
|**2022-07-29**|**Testing Relational Understanding in Text-Guided Image Generation**|Colin Conwell et.al.|[2208.00005v1](http://arxiv.org/abs/2208.00005v1)|null|
|**2022-07-21**|**Pose for Everything: Towards Category-Agnostic Pose Estimation**|Lumin Xu et.al.|[2207.10387v1](http://arxiv.org/abs/2207.10387v1)|**[link](https://github.com/luminxu/pose-for-everything)**|
|**2022-07-20**|**Explaining Deepfake Detection by Analysing Image Matching**|Shichao Dong et.al.|[2207.09679v1](http://arxiv.org/abs/2207.09679v1)|**[link](https://github.com/megvii-research/fst-matching)**|
|**2022-07-18**|**Adaptive Assignment for Geometry Aware Local Feature Matching**|Dihe Huang et.al.|[2207.08427v1](http://arxiv.org/abs/2207.08427v1)|null|
|**2022-07-16**|**Semi-Supervised Keypoint Detector and Descriptor for Retinal Image Matching**|Jiazhen Liu et.al.|[2207.07932v1](http://arxiv.org/abs/2207.07932v1)|**[link](https://github.com/ruc-aimc-lab/superretina)**|
|**2022-07-06**|**Virtual staining of defocused autofluorescence images of unlabeled tissue using deep neural networks**|Yijie Zhang et.al.|[2207.02946v1](http://arxiv.org/abs/2207.02946v1)|null|
|**2022-07-01**|**TopicFM: Robust and Interpretable Feature Matching with Topic-assisted**|Khang Truong Giang et.al.|[2207.00328v1](http://arxiv.org/abs/2207.00328v1)|**[link](https://github.com/truongkhang/topicfm)**|
|**2022-06-16**|**Virtual Correspondence: Humans as a Cue for Extreme-View Geometry**|Wei-Chiu Ma et.al.|[2206.08365v1](http://arxiv.org/abs/2206.08365v1)|null|
|**2022-06-15**|**Self-Supervised Learning of Image Scale and Orientation**|Jongmin Lee et.al.|[2206.07259v1](http://arxiv.org/abs/2206.07259v1)|**[link](https://github.com/bluedream1121/self-sca-ori)**|
|**2022-05-27**|**Image Keypoint Matching using Graph Neural Networks**|Nancy Xu et.al.|[2205.14275v1](http://arxiv.org/abs/2205.14275v1)|null|
|**2022-05-27**|**Fine-tuning deep learning models for stereo matching using results from semi-global matching**|Hessah Albanwan et.al.|[2205.14051v1](http://arxiv.org/abs/2205.14051v1)|null|
|**2022-05-23**|**TransforMatcher: Match-to-Match Attention for Semantic Correspondence**|Seungwook Kim et.al.|[2205.11634v1](http://arxiv.org/abs/2205.11634v1)|**[link](https://github.com/wookiekim/transformatcher)**|
|**2022-05-16**|**ReDFeat: Recoupling Detection and Description for Multimodal Feature Learning**|Yuxin Deng et.al.|[2205.07439v1](http://arxiv.org/abs/2205.07439v1)|null|
|**2022-05-06**|**BDIS: Bayesian Dense Inverse Searching Method for Real-Time Stereo Surgical Image Matching**|Jingwei Song et.al.|[2205.03133v1](http://arxiv.org/abs/2205.03133v1)|**[link](https://github.com/jingweisong/bdis-v2)**|
|**2022-05-10**|**AdaTriplet: Adaptive Gradient Triplet Loss with Automatic Margin Learning for Forensic Medical Image Matching**|Khanh Nguyen et.al.|[2205.02849v2](http://arxiv.org/abs/2205.02849v2)|**[link](https://github.com/oulu-imeds/adatriplet)**|
|**2022-04-27**|**Gleo-Det: Deep Convolution Feature-Guided Detector with Local Entropy Optimization for Salient Points**|Chao Li et.al.|[2204.12884v1](http://arxiv.org/abs/2204.12884v1)|null|
|**2022-04-22**|**SUES-200: A Multi-height Multi-scene Cross-view Image Benchmark Across Drone and Satellite**|Runzhe Zhu et.al.|[2204.10704v1](http://arxiv.org/abs/2204.10704v1)|**[link](https://github.com/Reza-Zhu/SUES-200-Benchmark)**|
|**2022-04-20**|**Uncertainty-based Cross-Modal Retrieval with Probabilistic Representations**|Leila Pishdad et.al.|[2204.09268v1](http://arxiv.org/abs/2204.09268v1)|null|
|**2022-04-19**|**OpenGlue: Open Source Graph Neural Net Based Pipeline for Image Matching**|Ostap Viniavskyi et.al.|[2204.08870v1](http://arxiv.org/abs/2204.08870v1)|**[link](https://github.com/ucuapps/openglue)**|
|**2022-04-19**|**Self-Supervised Equivariant Learning for Oriented Keypoint Detection**|Jongmin Lee et.al.|[2204.08613v1](http://arxiv.org/abs/2204.08613v1)|**[link](https://github.com/bluedream1121/REKD)**|
|**2022-04-22**|**Efficient Linear Attention for Fast and Accurate Keypoint Matching**|Suwichaya Suwanwimolkul et.al.|[2204.07731v3](http://arxiv.org/abs/2204.07731v3)|null|
|**2022-04-08**|**Lightweight starshade position sensing with convolutional neural networks and simulation-based inference**|Andrew Chen et.al.|[2204.03853v1](http://arxiv.org/abs/2204.03853v1)|**[link](https://github.com/astro-data-lab/starshade-xy)**|
|**2022-03-30**|**AmsterTime: A Visual Place Recognition Benchmark Dataset for Severe Domain Shift**|Burak Yildiz et.al.|[2203.16291v1](http://arxiv.org/abs/2203.16291v1)|**[link](https://github.com/seyrankhademi/AmsterTime)**|
|**2022-03-29**|**Photographic Visualization of Weather Forecasts with Generative Adversarial Networks**|Christian Sigg et.al.|[2203.15601v1](http://arxiv.org/abs/2203.15601v1)|null|
|**2022-03-29**|**Sparse Image based Navigation Architecture to Mitigate the need of precise Localization in Mobile Robots**|Pranay Mathur et.al.|[2203.15272v1](http://arxiv.org/abs/2203.15272v1)|null|
|**2022-03-28**|**Optimizing Elimination Templates by Greedy Parameter Search**|Evgeniy Martyushev et.al.|[2203.14901v1](http://arxiv.org/abs/2203.14901v1)|**[link](https://github.com/martyushev/eliminationtemplates)**|
|**2022-03-28**|**S2-Net: Self-supervision Guided Feature Representation Learning for Cross-Modality Images**|Shasha Mei et.al.|[2203.14581v1](http://arxiv.org/abs/2203.14581v1)|null|
|**2022-03-26**|**Accurate 3-DoF Camera Geo-Localization via Ground-to-Satellite Image Matching**|Yujiao Shi et.al.|[2203.14148v1](http://arxiv.org/abs/2203.14148v1)|**[link](https://github.com/shiyujiao/ibl)**|
|**2022-03-24**|**Keypoints Tracking via Transformer Networks**|Oleksii Nasypanyi et.al.|[2203.12848v1](http://arxiv.org/abs/2203.12848v1)|**[link](https://github.com/lexanagibator228/keypoints-tracking-via-transformer-networks)**|
|**2022-03-21**|**MatchFormer: Interleaving Attention in Transformers for Feature Matching**|Qing Wang et.al.|[2203.09645v2](http://arxiv.org/abs/2203.09645v2)|**[link](https://github.com/jamycheung/matchformer)**|
|**2022-03-14**|**There's no difference: Convolutional Neural Networks for transient detection without template subtraction**|Tatiana Acero-Cuellar et.al.|[2203.07390v1](http://arxiv.org/abs/2203.07390v1)|**[link](https://github.com/taceroc/dia_nodia)**|
|**2022-03-25**|**Cross Language Image Matching for Weakly Supervised Semantic Segmentation**|Jinheng Xie et.al.|[2203.02668v2](http://arxiv.org/abs/2203.02668v2)|**[link](https://github.com/cvi-szu/clims)**|
|**2022-03-01**|**CLIP-GEN: Language-Free Training of a Text-to-Image Generator with CLIP**|Zihao Wang et.al.|[2203.00386v1](http://arxiv.org/abs/2203.00386v1)|null|
|**2022-03-09**|**Time-resolved Imaging of Stochastic Cascade Reactions over a Submillisecond to Second Time Range at the Angstrom Level**|Toshiki Shimizu et.al.|[2202.13332v2](http://arxiv.org/abs/2202.13332v2)|null|
|**2022-02-16**|**Cross-view and Cross-domain Underwater Localization based on Optical Aerial and Acoustic Underwater Images**|Matheus M. Dos Santos et.al.|[2202.07817v1](http://arxiv.org/abs/2202.07817v1)|null|
|**2022-02-14**|**CATs++: Boosting Cost Aggregation with Convolutions and Transformers**|Seokju Cho et.al.|[2202.06817v1](http://arxiv.org/abs/2202.06817v1)|**[link](https://github.com/SunghwanHong/Cost-Aggregation-transformers)**|
|**2022-02-11**|**Improving Image-recognition Edge Caches with a Generative Adversarial Network**|Guilherme B. Souza et.al.|[2202.05929v1](http://arxiv.org/abs/2202.05929v1)|null|
|**2022-02-08**|**Learning Optical Flow with Adaptive Graph Reasoning**|Ao Luo et.al.|[2202.03857v1](http://arxiv.org/abs/2202.03857v1)|**[link](https://github.com/la30/agflow)**|
|**2022-02-03**|**Sim2Real Object-Centric Keypoint Detection and Description**|Chengliang Zhong et.al.|[2202.00448v2](http://arxiv.org/abs/2202.00448v2)|null|
|**2022-01-27**|**Efficient divide-and-conquer registration of UAV and ground LiDAR point clouds through canopy shape context**|Jie Shao et.al.|[2201.11296v1](http://arxiv.org/abs/2201.11296v1)|null|
|**2021-12-24**|**Multi-initialization Optimization Network for Accurate 3D Human Pose and Shape Estimation**|Zhiwei Liu et.al.|[2112.12917v1](http://arxiv.org/abs/2112.12917v1)|null|
|**2021-12-20**|**Scale-Net: Learning to Reduce Scale Differences for Large-Scale Invariant Image Matching**|Yujie Fu et.al.|[2112.10485v1](http://arxiv.org/abs/2112.10485v1)|null|
|**2021-12-19**|**GPU optimization of the 3D Scale-invariant Feature Transform Algorithm and a Novel BRIEF-inspired 3D Fast Descriptor**|Jean-Baptiste Carluer et.al.|[2112.10258v1](http://arxiv.org/abs/2112.10258v1)|**[link](https://github.com/carluerjb/3d_sift_cuda)**|
|**2021-12-14**|**More Control for Free! Image Synthesis with Semantic Diffusion Guidance**|Xihui Liu et.al.|[2112.05744v2](http://arxiv.org/abs/2112.05744v2)|null|
|**2021-12-08**|**Label-free virtual HER2 immunohistochemical staining of breast tissue using deep learning**|Bijie Bai et.al.|[2112.05240v1](http://arxiv.org/abs/2112.05240v1)|null|
|**2021-12-01**|**FaSS-MVS -- Fast Multi-View Stereo with Surface-Aware Semi-Global Matching from UAV-borne Monocular Imagery**|Boitumelo Ruf et.al.|[2112.00821v1](http://arxiv.org/abs/2112.00821v1)|null|
|**2021-12-01**|**CLIPstyler: Image Style Transfer with a Single Text Condition**|Gihyun Kwon et.al.|[2112.00374v1](http://arxiv.org/abs/2112.00374v1)|**[link](https://github.com/paper11667/clipstyler)**|
|**2021-11-29**|**Nonlinear Intensity Underwater Sonar Image Matching Method Based on Phase Information and Deep Convolution Features**|Xiaoteng Zhou et.al.|[2111.15514v1](http://arxiv.org/abs/2111.15514v1)|null|
|**2021-11-29**|**Zero-Shot Image-to-Text Generation for Visual-Semantic Arithmetic**|Yoad Tewel et.al.|[2111.14447v1](http://arxiv.org/abs/2111.14447v1)|**[link](https://github.com/yoadtew/zero-shot-image-to-text)**|
|**2021-11-29**|**Heterogeneous Visible-Thermal and Visible-Infrared Face Recognition using Unit-Class Loss and Cross-Modality Discriminator**|Usman Cheema et.al.|[2111.14339v1](http://arxiv.org/abs/2111.14339v1)|null|
|**2021-11-17**|**Probabilistic Spatial Distribution Prior Based Attentional Keypoints Matching Network**|Xiaoming Zhao et.al.|[2111.09006v2](http://arxiv.org/abs/2111.09006v2)|null|
|**2021-11-17**|**Nonlinear Intensity Sonar Image Matching based on Deep Convolution Features**|Xiaoteng Zhou et.al.|[2111.08994v3](http://arxiv.org/abs/2111.08994v3)|null|
|**2021-10-30**|**A Deep Search for Faint Chandra X-ray Sources, Radio Sources, and Optical Counterparts in NGC 6752**|Haldan N. Cohn et.al.|[2111.00357v1](http://arxiv.org/abs/2111.00357v1)|null|
|**2021-10-01**|**Robustly Removing Deep Sea Lighting Effects for Visual Mapping of Abyssal Plains**|Kevin Köser et.al.|[2110.00480v1](http://arxiv.org/abs/2110.00480v1)|null|
|**2021-09-29**|**Visually Grounded Concept Composition**|Bowen Zhang et.al.|[2109.14115v1](http://arxiv.org/abs/2109.14115v1)|null|
|**2021-09-27**|**HarrisZ $^+$ : Harris Corner Selection for Next-Gen Image Matching Pipelines**|Fabio Bellavia et.al.|[2109.12925v3](http://arxiv.org/abs/2109.12925v3)|null|
|**2021-09-20**|**Viewpoint Invariant Dense Matching for Visual Geolocalization**|Gabriele Berton et.al.|[2109.09827v1](http://arxiv.org/abs/2109.09827v1)|**[link](https://github.com/gmberton/geo_warp)**|
|**2021-09-20**|**Image Subtraction in Fourier Space**|Lei Hu et.al.|[2109.09334v1](http://arxiv.org/abs/2109.09334v1)|**[link](https://github.com/thomasvrussell/sfft)**|
|**2021-09-10**|**Line as a Visual Sentence: Context-aware Line Descriptor for Visual Localization**|Sungho Yoon et.al.|[2109.04753v1](http://arxiv.org/abs/2109.04753v1)|**[link](https://github.com/yosungho/LineTR)**|
|**2021-09-08**|**Matching in the Dark: A Dataset for Matching Image Pairs of Low-light Scenes**|Wenzheng Song et.al.|[2109.03585v2](http://arxiv.org/abs/2109.03585v2)|null|
|**2021-08-27**|**A Matching Algorithm based on Image Attribute Transfer and Local Features for Underwater Acoustic and Optical Images**|Xiaoteng Zhou et.al.|[2108.12151v1](http://arxiv.org/abs/2108.12151v1)|null|
|**2021-08-27**|**Matching Underwater Sonar Images by the Learned Descriptor Based on Style Transfer Method**|Xiaoteng Zhou et.al.|[2108.12072v1](http://arxiv.org/abs/2108.12072v1)|null|
|**2021-08-26**|**Efficient Joint Object Matching via Linear Programming**|Antonio De Rosa et.al.|[2108.11911v1](http://arxiv.org/abs/2108.11911v1)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## NeRF

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-17**|**IPR-NeRF: Ownership Verification meets Neural Radiance Field**|Win Kent Ong et.al.|[2401.09495](http://arxiv.org/abs/2401.09495)|null|
|**2024-01-17**|**ICON: Incremental CONfidence for Joint Pose and Radiance Field Optimization**|Weiyao Wang et.al.|[2401.08937](http://arxiv.org/abs/2401.08937)|null|
|**2024-01-18**|**ProvNeRF: Modeling per Point Provenance in NeRFs as a Stochastic Process**|Kiyohiro Nakayama et.al.|[2401.08140](http://arxiv.org/abs/2401.08140)|null|
|**2024-01-16**|**Forging Vision Foundation Models for Autonomous Driving: Challenges, Methodologies, and Opportunities**|Xu Yan et.al.|[2401.08045](http://arxiv.org/abs/2401.08045)|**[link](https://github.com/zhanghm1995/forge_vfm4ad)**|
|**2024-01-11**|**TriNeRFLet: A Wavelet Based Multiscale Triplane NeRF Representation**|Rajaei Khatib et.al.|[2401.06191](http://arxiv.org/abs/2401.06191)|null|
|**2024-01-11**|**Fast High Dynamic Range Radiance Fields for Dynamic Scenes**|Guanjun Wu et.al.|[2401.06052](http://arxiv.org/abs/2401.06052)|null|
|**2024-01-11**|**CoSSegGaussians: Compact and Swift Scene Segmenting 3D Gaussians**|Bin Dou et.al.|[2401.05925](http://arxiv.org/abs/2401.05925)|null|
|**2024-01-11**|**GO-NeRF: Generating Virtual Objects in Neural Radiance Fields**|Peng Dai et.al.|[2401.05750](http://arxiv.org/abs/2401.05750)|null|
|**2024-01-10**|**Diffusion Priors for Dynamic View Synthesis from Monocular Videos**|Chaoyang Wang et.al.|[2401.05583](http://arxiv.org/abs/2401.05583)|null|
|**2024-01-10**|**InseRF: Text-Driven Generative Object Insertion in Neural 3D Scenes**|Mohamad Shahbazi et.al.|[2401.05335](http://arxiv.org/abs/2401.05335)|null|
|**2024-01-10**|**CTNeRF: Cross-Time Transformer for Dynamic Neural Radiance Field from Monocular Video**|Xingyu Miao et.al.|[2401.04861](http://arxiv.org/abs/2401.04861)|null|
|**2024-01-08**|**A Survey on 3D Gaussian Splatting**|Guikun Chen et.al.|[2401.03890](http://arxiv.org/abs/2401.03890)|null|
|**2024-01-08**|**NeRFmentation: NeRF-based Augmentation for Monocular Depth Estimation**|Casimir Feldmann et.al.|[2401.03771](http://arxiv.org/abs/2401.03771)|null|
|**2024-01-06**|**RustNeRF: Robust Neural Radiance Field with Low-Quality Images**|Mengfei Li et.al.|[2401.03257](http://arxiv.org/abs/2401.03257)|null|
|**2024-01-06**|**Hi-Map: Hierarchical Factorized Radiance Field for High-Fidelity Monocular Dense Mapping**|Tongyan Hua et.al.|[2401.03203](http://arxiv.org/abs/2401.03203)|null|
|**2024-01-05**|**Progress and Prospects in 3D Generative AI: A Technical Overview including 3D human**|Song Bai et.al.|[2401.02620](http://arxiv.org/abs/2401.02620)|null|
|**2024-01-05**|**FED-NeRF: Achieve High 3D Consistency and Temporal Coherence for Face Video Editing on Dynamic NeRF**|Hao Zhang et.al.|[2401.02616](http://arxiv.org/abs/2401.02616)|**[link](https://github.com/zhang1023/fed-nerf)**|
|**2024-01-05**|**Characterizing Satellite Geometry via Accelerated 3D Gaussian Splatting**|Van Minh Nguyen et.al.|[2401.02588](http://arxiv.org/abs/2401.02588)|null|
|**2024-01-03**|**SIGNeRF: Scene Integrated Generation for Neural Radiance Fields**|Jan-Niklas Dihlmann et.al.|[2401.01647](http://arxiv.org/abs/2401.01647)|null|
|**2024-01-02**|**Street Gaussians for Modeling Dynamic Urban Scenes**|Yunzhi Yan et.al.|[2401.01339](http://arxiv.org/abs/2401.01339)|null|
|**2024-01-02**|**Noise-NeRF: Hide Information in Neural Radiance Fields using Trainable Noise**|Qinglong Huang et.al.|[2401.01216](http://arxiv.org/abs/2401.01216)|null|
|**2024-01-02**|**3D Visibility-aware Generalizable Neural Radiance Fields for Interacting Hands**|Xuan Huang et.al.|[2401.00979](http://arxiv.org/abs/2401.00979)|null|
|**2024-01-01**|**Sharp-NeRF: Grid-based Fast Deblurring Neural Radiance Fields Using Sharpness Prior**|Byeonghyeon Lee et.al.|[2401.00825](http://arxiv.org/abs/2401.00825)|**[link](https://github.com/benhenryl/sharpnerf)**|
|**2024-01-02**|**GD^2-NeRF: Generative Detail Compensation via GAN and Diffusion for One-shot Generalizable Neural Radiance Fields**|Xiao Pan et.al.|[2401.00616](http://arxiv.org/abs/2401.00616)|null|
|**2023-12-30**|**Inpaint4DNeRF: Promptable Spatio-Temporal NeRF Inpainting with Generative Diffusion Models**|Han Jiang et.al.|[2401.00208](http://arxiv.org/abs/2401.00208)|null|
|**2023-12-29**|**Informative Rays Selection for Few-Shot Neural Radiance Fields**|Marco Orsingher et.al.|[2312.17561](http://arxiv.org/abs/2312.17561)|null|
|**2023-12-27**|**City-on-Web: Real-time Neural Rendering of Large-scale Scenes on the Web**|Kaiwen Song et.al.|[2312.16457](http://arxiv.org/abs/2312.16457)|null|
|**2023-12-29**|**DL3DV-10K: A Large-Scale Scene Dataset for Deep Learning-based 3D Vision**|Lu Ling et.al.|[2312.16256](http://arxiv.org/abs/2312.16256)|null|
|**2023-12-24**|**SUNDIAL: 3D Satellite Understanding through Direct, Ambient, and Complex Lighting Decomposition**|Nikhil Behari et.al.|[2312.16215](http://arxiv.org/abs/2312.16215)|null|
|**2023-12-23**|**INFAMOUS-NeRF: ImproviNg FAce MOdeling Using Semantically-Aligned Hypernetworks with Neural Radiance Fields**|Andrew Hou et.al.|[2312.16197](http://arxiv.org/abs/2312.16197)|null|
|**2023-12-26**|**LangSplat: 3D Language Gaussian Splatting**|Minghan Qin et.al.|[2312.16084](http://arxiv.org/abs/2312.16084)|**[link](https://github.com/minghanqin/LangSplat)**|
|**2023-12-26**|**2D-Guided 3D Gaussian Segmentation**|Kun Lan et.al.|[2312.16047](http://arxiv.org/abs/2312.16047)|null|
|**2023-12-26**|**Pano-NeRF: Synthesizing High Dynamic Range Novel Views with Geometry from Sparse Low Dynamic Range Panoramic Images**|Zhan Lu et.al.|[2312.15942](http://arxiv.org/abs/2312.15942)|null|
|**2023-12-23**|**Human101: Training 100+FPS Human Gaussians in 100s from 1 View**|Mingwei Li et.al.|[2312.15258](http://arxiv.org/abs/2312.15258)|**[link](https://github.com/longxiang-ai/human101)**|
|**2023-12-23**|**Efficient Deformable Tissue Reconstruction via Orthogonal Neural Plane**|Chen Yang et.al.|[2312.15253](http://arxiv.org/abs/2312.15253)|**[link](https://github.com/loping151/forplane)**|
|**2023-12-23**|**CaLDiff: Camera Localization in NeRF via Pose Diffusion**|Rashik Shrestha et.al.|[2312.15242](http://arxiv.org/abs/2312.15242)|null|
|**2023-12-22**|**PoseGen: Learning to Generate 3D Human Pose Dataset with NeRF**|Mohsen Gholami et.al.|[2312.14915](http://arxiv.org/abs/2312.14915)|**[link](https://github.com/mgholamikn/PoseGen)**|
|**2023-12-22**|**Density Uncertainty Quantification with NeRF-Ensembles: Impact of Data and Scene Constraints**|Miriam Jäger et.al.|[2312.14664](http://arxiv.org/abs/2312.14664)|null|
|**2023-12-21**|**PlatoNeRF: 3D Reconstruction in Plato's Cave via Single-View Two-Bounce Lidar**|Tzofi Klinghoffer et.al.|[2312.14239](http://arxiv.org/abs/2312.14239)|null|
|**2023-12-21**|**Virtual Pets: Animatable Animal Generation in 3D Scenes**|Yen-Chi Cheng et.al.|[2312.14154](http://arxiv.org/abs/2312.14154)|null|
|**2023-12-21**|**Carve3D: Improving Multi-view Reconstruction Consistency for Diffusion Models with RL Finetuning**|Desai Xie et.al.|[2312.13980](http://arxiv.org/abs/2312.13980)|null|
|**2023-12-21**|**SyncDreamer for 3D Reconstruction of Endangered Animal Species with NeRF and NeuS**|Ahmet Haydar Ornek et.al.|[2312.13832](http://arxiv.org/abs/2312.13832)|null|
|**2023-12-22**|**Gaussian Splatting with NeRF-based Color and Opacity**|Dawid Malarz et.al.|[2312.13729](http://arxiv.org/abs/2312.13729)|**[link](https://github.com/gmum/ViewingDirectionGaussianSplatting)**|
|**2023-12-21**|**DyBluRF: Dynamic Deblurring Neural Radiance Fields for Blurry Monocular Video**|Minh-Quan Viet Bui et.al.|[2312.13528](http://arxiv.org/abs/2312.13528)|null|
|**2023-12-21**|**Visual Tomography: Physically Faithful Volumetric Models of Partially Translucent Objects**|David Nakath et.al.|[2312.13494](http://arxiv.org/abs/2312.13494)|null|
|**2023-12-20**|**NeRF-VO: Real-Time Sparse Visual Odometry with Neural Radiance Fields**|Jens Naumann et.al.|[2312.13471](http://arxiv.org/abs/2312.13471)|null|
|**2023-12-22**|**Ternary-type Opacity and Hybrid Odometry for RGB-only NeRF-SLAM**|Junru Lin et.al.|[2312.13332](http://arxiv.org/abs/2312.13332)|null|
|**2023-12-20**|**ShowRoom3D: Text to High-Quality 3D Room Generation Using 3D Priors**|Weijia Mao et.al.|[2312.13324](http://arxiv.org/abs/2312.13324)|null|
|**2023-12-20**|**UniSDF: Unifying Neural Representations for High-Fidelity 3D Reconstruction of Complex Scenes with Reflections**|Fangjinhua Wang et.al.|[2312.13285](http://arxiv.org/abs/2312.13285)|null|
|**2023-12-20**|**Reducing Shape-Radiance Ambiguity in Radiance Fields with a Closed-Form Color Estimation Method**|Qihang Fang et.al.|[2312.12726](http://arxiv.org/abs/2312.12726)|**[link](https://github.com/qihanggh/closed-form-color-field)**|
|**2023-12-19**|**ZS-SRT: An Efficient Zero-Shot Super-Resolution Training Method for Neural Radiance Fields**|Xiang Feng et.al.|[2312.12122](http://arxiv.org/abs/2312.12122)|null|
|**2023-12-20**|**LHManip: A Dataset for Long-Horizon Language-Grounded Manipulation Tasks in Cluttered Tabletop Environments**|Federico Ceola et.al.|[2312.12036](http://arxiv.org/abs/2312.12036)|**[link](https://github.com/fedeceola/lhmanip)**|
|**2023-12-20**|**MixRT: Mixed Neural Representations For Real-Time NeRF Rendering**|Chaojian Li et.al.|[2312.11841](http://arxiv.org/abs/2312.11841)|null|
|**2023-12-19**|**Text-Image Conditioned Diffusion for Consistent Text-to-3D Generation**|Yuze He et.al.|[2312.11774](http://arxiv.org/abs/2312.11774)|null|
|**2023-12-20**|**FastSR-NeRF: Improving NeRF Efficiency on Consumer Devices with A Simple Super-Resolution Pipeline**|Chien-Yu Lin et.al.|[2312.11537](http://arxiv.org/abs/2312.11537)|null|
|**2023-12-15**|**Customize-It-3D: High-Quality 3D Creation from A Single Image Using Subject-Specific Knowledge Prior**|Nan Huang et.al.|[2312.11535](http://arxiv.org/abs/2312.11535)|null|
|**2023-12-18**|**GAvatar: Animatable 3D Gaussian Avatars with Implicit Mesh Learning**|Ye Yuan et.al.|[2312.11461](http://arxiv.org/abs/2312.11461)|null|
|**2023-12-18**|**AE-NeRF: Audio Enhanced Neural Radiance Field for Few Shot Talking Head Synthesis**|Dongze Li et.al.|[2312.10921](http://arxiv.org/abs/2312.10921)|null|
|**2023-12-17**|**PNeRFLoc: Visual Localization with Point-based Neural Radiance Fields**|Boming Zhao et.al.|[2312.10649](http://arxiv.org/abs/2312.10649)|null|
|**2023-12-19**|**Learning Dense Correspondence for NeRF-Based Face Reenactment**|Songlin Yang et.al.|[2312.10422](http://arxiv.org/abs/2312.10422)|null|
|**2023-12-15**|**SlimmeRF: Slimmable Radiance Fields**|Shiran Yuan et.al.|[2312.10034](http://arxiv.org/abs/2312.10034)|**[link](https://github.com/shiran-yuan/slimmerf)**|
|**2023-12-15**|**LAENeRF: Local Appearance Editing for Neural Radiance Fields**|Lukas Radl et.al.|[2312.09913](http://arxiv.org/abs/2312.09913)|null|
|**2023-12-15**|**SLS4D: Sparse Latent Space for 4D Novel View Synthesis**|Qi-Yuan Feng et.al.|[2312.09743](http://arxiv.org/abs/2312.09743)|null|
|**2023-12-15**|**Towards Transferable Targeted 3D Adversarial Attack in the Physical World**|Yao Huang et.al.|[2312.09558](http://arxiv.org/abs/2312.09558)|null|
|**2023-12-18**|**LatentEditor: Text Driven Local Editing of 3D Scenes**|Umar Khalid et.al.|[2312.09313](http://arxiv.org/abs/2312.09313)|**[link](https://github.com/umarkhalidAI/LatentEditor)**|
|**2023-12-14**|**Stable Score Distillation for High-Quality 3D Generation**|Boshi Tang et.al.|[2312.09305](http://arxiv.org/abs/2312.09305)|null|
|**2023-12-14**|**ZeroRF: Fast Sparse View 360° Reconstruction with Zero Pretraining**|Ruoxi Shi et.al.|[2312.09249](http://arxiv.org/abs/2312.09249)|null|
|**2023-12-15**|**3DGS-Avatar: Animatable Avatars via Deformable 3D Gaussian Splatting**|Zhiyin Qian et.al.|[2312.09228](http://arxiv.org/abs/2312.09228)|null|
|**2023-12-15**|**ColNeRF: Collaboration for Generalizable Sparse Input Neural Radiance Field**|Zhangkai Ni et.al.|[2312.09095](http://arxiv.org/abs/2312.09095)|**[link](https://github.com/eezkni/colnerf)**|
|**2023-12-15**|**Aleth-NeRF: Illumination Adaptive NeRF with Concealing Field Assumption**|Ziteng Cui et.al.|[2312.09093](http://arxiv.org/abs/2312.09093)|**[link](https://github.com/cuiziteng/Aleth-NeRF)**|
|**2023-12-14**|**iComMa: Inverting 3D Gaussians Splatting for Camera Pose Estimation via Comparing and Matching**|Yuan Sun et.al.|[2312.09031](http://arxiv.org/abs/2312.09031)|null|
|**2023-12-14**|**Scene 3-D Reconstruction System in Scattering Medium**|Zhuoyifan Zhang et.al.|[2312.09005](http://arxiv.org/abs/2312.09005)|null|
|**2023-12-14**|**CF-NeRF: Camera Parameter Free Neural Radiance Fields with Incremental Learning**|Qingsong Yan et.al.|[2312.08760](http://arxiv.org/abs/2312.08760)|null|
|**2023-12-14**|**SpectralNeRF: Physically Based Spectral Rendering with Neural Radiance Field**|Ru Li et.al.|[2312.08692](http://arxiv.org/abs/2312.08692)|**[link](https://github.com/liru0126/spectralnerf)**|
|**2023-12-13**|**ProNeRF: Learning Efficient Projection-Aware Ray Sampling for Fine-Grained Implicit Neural Radiance Fields**|Juan Luis Gonzalez Bello et.al.|[2312.08136](http://arxiv.org/abs/2312.08136)|null|
|**2023-12-13**|**Neural Radiance Fields for Transparent Object Using Visual Hull**|Heechan Yoon et.al.|[2312.08118](http://arxiv.org/abs/2312.08118)|null|
|**2023-12-13**|**uSF: Learning Neural Semantic Field with Uncertainty**|Vsevolod Skorokhodov et.al.|[2312.08012](http://arxiv.org/abs/2312.08012)|**[link](https://github.com/sevashasla/usf)**|
|**2023-12-12**|**COLMAP-Free 3D Gaussian Splatting**|Yang Fu et.al.|[2312.07504](http://arxiv.org/abs/2312.07504)|null|
|**2023-12-12**|**Unifying Correspondence, Pose and NeRF for Pose-Free Novel View Synthesis from Stereo Pairs**|Sunghwan Hong et.al.|[2312.07246](http://arxiv.org/abs/2312.07246)|**[link](https://github.com/KU-CVLAB/CoPoNeRF)**|
|**2023-12-12**|**WaterHE-NeRF: Water-ray Tracing Neural Radiance Fields for Underwater Scene Reconstruction**|Jingchun Zhou et.al.|[2312.06946](http://arxiv.org/abs/2312.06946)|null|
|**2023-12-10**|**TeTriRF: Temporal Tri-Plane Radiance Fields for Efficient Free-Viewpoint Video**|Minye Wu et.al.|[2312.06713](http://arxiv.org/abs/2312.06713)|null|
|**2023-12-09**|**Robo360: A 3D Omnispective Multi-Material Robotic Manipulation Dataset**|Litian Liang et.al.|[2312.06686](http://arxiv.org/abs/2312.06686)|null|
|**2023-12-11**|**CorresNeRF: Image Correspondence Priors for Neural Radiance Fields**|Yixing Lao et.al.|[2312.06642](http://arxiv.org/abs/2312.06642)|**[link](https://github.com/yxlao/corres-nerf)**|
|**2023-12-11**|**DreamControl: Control-Based Text-to-3D Generation with 3D Self-Prior**|Tianyu Huang et.al.|[2312.06439](http://arxiv.org/abs/2312.06439)|**[link](https://github.com/tyhuang0428/dreamcontrol)**|
|**2023-12-10**|**NeVRF: Neural Video-based Radiance Fields for Long-duration Sequences**|Minye Wu et.al.|[2312.05855](http://arxiv.org/abs/2312.05855)|null|
|**2023-12-10**|**IL-NeRF: Incremental Learning for Neural Radiance Fields with Camera Pose Alignment**|Letian Zhang et.al.|[2312.05748](http://arxiv.org/abs/2312.05748)|null|
|**2023-12-09**|**CoGS: Controllable Gaussian Splatting**|Heng Yu et.al.|[2312.05664](http://arxiv.org/abs/2312.05664)|null|
|**2023-12-09**|**R2-Talker: Realistic Real-Time Talking Head Synthesis with Hash Grid Landmarks Encoding and Progressive Multilayer Conditioning**|Zhiling Ye et.al.|[2312.05572](http://arxiv.org/abs/2312.05572)|null|
|**2023-12-08**|**Multi-view Inversion for 3D-aware Generative Adversarial Networks**|Florian Barthel et.al.|[2312.05330](http://arxiv.org/abs/2312.05330)|null|
|**2023-12-08**|**TriHuman : A Real-time and Controllable Tri-plane Representation for Detailed Human Geometry and Appearance Synthesis**|Heming Zhu et.al.|[2312.05161](http://arxiv.org/abs/2312.05161)|null|
|**2023-12-08**|**Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting**|Xiaofeng Yang et.al.|[2312.04820](http://arxiv.org/abs/2312.04820)|null|
|**2023-12-08**|**Reality's Canvas, Language's Brush: Crafting 3D Avatars from Monocular Video**|Yuchen Rao et.al.|[2312.04784](http://arxiv.org/abs/2312.04784)|null|
|**2023-12-07**|**MuRF: Multi-Baseline Radiance Fields**|Haofei Xu et.al.|[2312.04565](http://arxiv.org/abs/2312.04565)|**[link](https://github.com/autonomousvision/murf)**|
|**2023-12-07**|**EAGLES: Efficient Accelerated 3D Gaussians with Lightweight EncodingS**|Sharath Girish et.al.|[2312.04564](http://arxiv.org/abs/2312.04564)|null|
|**2023-12-07**|**Correspondences of the Third Kind: Camera Pose Estimation from Object Reflection**|Kohei Yamashita et.al.|[2312.04527](http://arxiv.org/abs/2312.04527)|null|
|**2023-12-07**|**Multi-View Unsupervised Image Generation with Cross Attention Guidance**|Llukman Cerkezi et.al.|[2312.04337](http://arxiv.org/abs/2312.04337)|null|
|**2023-12-07**|**Towards 4D Human Video Stylization**|Tiantian Wang et.al.|[2312.04143](http://arxiv.org/abs/2312.04143)|**[link](https://github.com/tiantianwang/4d_video_stylization)**|
|**2023-12-07**|**Identity-Obscured Neural Radiance Fields: Privacy-Preserving 3D Facial Reconstruction**|Jiayi Kong et.al.|[2312.04106](http://arxiv.org/abs/2312.04106)|null|
|**2023-12-06**|**Inpaint3D: 3D Scene Content Generation using 2D Inpainting Diffusion**|Kira Prabhu et.al.|[2312.03869](http://arxiv.org/abs/2312.03869)|null|
|**2023-12-06**|**Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle**|Youtian Lin et.al.|[2312.03431](http://arxiv.org/abs/2312.03431)|null|
|**2023-12-06**|**Artist-Friendly Relightable and Animatable Neural Heads**|Yingyan Xu et.al.|[2312.03420](http://arxiv.org/abs/2312.03420)|null|
|**2023-12-06**|**Evaluating the point cloud of individual trees generated from images based on Neural Radiance fields (NeRF) method**|Hongyu Huang et.al.|[2312.03372](http://arxiv.org/abs/2312.03372)|null|
|**2023-12-06**|**RING-NeRF: A Versatile Architecture based on Residual Implicit Neural Grids**|Doriand Petit et.al.|[2312.03357](http://arxiv.org/abs/2312.03357)|null|
|**2023-12-06**|**SO-NeRF: Active View Planning for NeRF using Surrogate Objectives**|Keifer Lee et.al.|[2312.03266](http://arxiv.org/abs/2312.03266)|null|
|**2023-12-06**|**Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields**|Shijie Zhou et.al.|[2312.03203](http://arxiv.org/abs/2312.03203)|null|
|**2023-12-05**|**HybridNeRF: Efficient Neural Rendering via Adaptive Volumetric Surfaces**|Haithem Turki et.al.|[2312.03160](http://arxiv.org/abs/2312.03160)|null|
|**2023-12-05**|**ReconFusion: 3D Reconstruction with Diffusion Priors**|Rundi Wu et.al.|[2312.02981](http://arxiv.org/abs/2312.02981)|null|
|**2023-12-05**|**GauHuman: Articulated Gaussian Splatting from Monocular Human Videos**|Shoukang Hu et.al.|[2312.02973](http://arxiv.org/abs/2312.02973)|**[link](https://github.com/skhu101/gauhuman)**|
|**2023-12-05**|**Alchemist: Parametric Control of Material Properties with Diffusion Models**|Prafull Sharma et.al.|[2312.02970](http://arxiv.org/abs/2312.02970)|null|
|**2023-12-05**|**MVHumanNet: A Large-scale Dataset of Multi-view Daily Dressing Human Captures**|Zhangyang Xiong et.al.|[2312.02963](http://arxiv.org/abs/2312.02963)|null|
|**2023-12-05**|**C-NERF: Representing Scene Changes as Directional Consistency Difference-based NeRF**|Rui Huang et.al.|[2312.02751](http://arxiv.org/abs/2312.02751)|**[link](https://github.com/c-nerf/c-nerf)**|
|**2023-12-05**|**Prompt2NeRF-PIL: Fast NeRF Generation via Pretrained Implicit Latent**|Jianmeng Liu et.al.|[2312.02568](http://arxiv.org/abs/2312.02568)|null|
|**2023-12-04**|**PointNeRF++: A multi-scale, point-based Neural Radiance Field**|Weiwei Sun et.al.|[2312.02362](http://arxiv.org/abs/2312.02362)|null|
|**2023-12-04**|**Calibrated Uncertainties for Neural Radiance Fields**|Niki Amini-Naieni et.al.|[2312.02350](http://arxiv.org/abs/2312.02350)|null|
|**2023-12-04**|**Re-Nerfing: Enforcing Geometric Constraints on Neural Radiance Fields through Novel Views Synthesis**|Felix Tristram et.al.|[2312.02255](http://arxiv.org/abs/2312.02255)|null|
|**2023-12-03**|**WavePlanes: A compact Wavelet representation for Dynamic Neural Radiance Fields**|Adrian Azzarelli et.al.|[2312.02218](http://arxiv.org/abs/2312.02218)|**[link](https://github.com/azzarelli/waveplanes)**|
|**2023-12-02**|**Volumetric Rendering with Baked Quadrature Fields**|Gopal Sharma et.al.|[2312.02202](http://arxiv.org/abs/2312.02202)|null|
|**2023-12-02**|**StableDreamer: Taming Noisy Score Distillation Sampling for Text-to-3D**|Pengsheng Guo et.al.|[2312.02189](http://arxiv.org/abs/2312.02189)|null|
|**2023-12-04**|**ColonNeRF: Neural Radiance Fields for High-Fidelity Long-Sequence Colonoscopy Reconstruction**|Yufei Shi et.al.|[2312.02015](http://arxiv.org/abs/2312.02015)|null|
|**2023-12-04**|**Customize your NeRF: Adaptive Source Driven 3D Scene Editing via Local-Global Iterative Training**|Runze He et.al.|[2312.01663](http://arxiv.org/abs/2312.01663)|null|
|**2023-12-03**|**SANeRF-HQ: Segment Anything for NeRF in High Quality**|Yichen Liu et.al.|[2312.01531](http://arxiv.org/abs/2312.01531)|null|
|**2023-12-03**|**VideoRF: Rendering Dynamic Radiance Fields as 2D Feature Video Streams**|Liao Wang et.al.|[2312.01407](http://arxiv.org/abs/2312.01407)|null|
|**2023-12-05**|**Self-Evolving Neural Radiance Fields**|Jaewoo Jung et.al.|[2312.01003](http://arxiv.org/abs/2312.01003)|null|
|**2023-12-01**|**Gaussian Grouping: Segment and Edit Anything in 3D Scenes**|Mingqiao Ye et.al.|[2312.00732](http://arxiv.org/abs/2312.00732)|**[link](https://github.com/lkeab/gaussian-grouping)**|
|**2023-11-30**|**LucidDreaming: Controllable Object-Centric 3D Generation**|Zhaoning Wang et.al.|[2312.00588](http://arxiv.org/abs/2312.00588)|null|
|**2023-12-01**|**FSGS: Real-Time Few-shot View Synthesis using Gaussian Splatting**|Zehao Zhu et.al.|[2312.00451](http://arxiv.org/abs/2312.00451)|null|
|**2023-11-30**|**PyNeRF: Pyramidal Neural Radiance Fields**|Haithem Turki et.al.|[2312.00252](http://arxiv.org/abs/2312.00252)|**[link](https://github.com/hturki/pynerf)**|
|**2023-11-30**|**SparseGS: Real-Time 360° Sparse View Synthesis using Gaussian Splatting**|Haolin Xiong et.al.|[2312.00206](http://arxiv.org/abs/2312.00206)|null|
|**2023-11-30**|**Contrastive Denoising Score for Text-guided Latent Diffusion Image Editing**|Hyelin Nam et.al.|[2311.18608](http://arxiv.org/abs/2311.18608)|null|
|**2023-11-30**|**ZeST-NeRF: Using temporal aggregation for Zero-Shot Temporal NeRFs**|Violeta Menéndez González et.al.|[2311.18491](http://arxiv.org/abs/2311.18491)|null|
|**2023-11-30**|**Anisotropic Neural Representation Learning for High-Quality Neural Rendering**|Y. Wang et.al.|[2311.18311](http://arxiv.org/abs/2311.18311)|null|
|**2023-11-30**|**CosAvatar: Consistent and Animatable Portrait Video Tuning with Text Prompt**|Haiyao Xiao et.al.|[2311.18288](http://arxiv.org/abs/2311.18288)|null|
|**2023-11-30**|**Compact3D: Compressing Gaussian Splat Radiance Field Models with Vector Quantization**|KL Navaneet et.al.|[2311.18159](http://arxiv.org/abs/2311.18159)|**[link](https://github.com/ucdvision/compact3d)**|
|**2023-11-29**|**GaussianShader: 3D Gaussian Splatting with Shading Functions for Reflective Surfaces**|Yingwenqi Jiang et.al.|[2311.17977](http://arxiv.org/abs/2311.17977)|null|
|**2023-11-29**|**AvatarStudio: High-fidelity and Animatable 3D Avatar Creation from Text**|Jianfeng Zhang et.al.|[2311.17917](http://arxiv.org/abs/2311.17917)|null|
|**2023-11-29**|**FisherRF: Active View Selection and Uncertainty Quantification for Radiance Fields using Fisher Information**|Wen Jiang et.al.|[2311.17874](http://arxiv.org/abs/2311.17874)|null|
|**2023-11-29**|**Cinematic Behavior Transfer via NeRF-based Differentiable Filming**|Xuekun Jiang et.al.|[2311.17754](http://arxiv.org/abs/2311.17754)|null|
|**2023-11-29**|**SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis**|Ziqiao Peng et.al.|[2311.17590](http://arxiv.org/abs/2311.17590)|**[link](https://github.com/ZiqiaoPeng/SyncTalk)**|
|**2023-11-29**|**NeRFTAP: Enhancing Transferability of Adversarial Patches on Face Recognition using Neural Radiance Fields**|Xiaoliang Liu et.al.|[2311.17332](http://arxiv.org/abs/2311.17332)|null|
|**2023-11-28**|**LightGaussian: Unbounded 3D Gaussian Compression with 15x Reduction and 200+ FPS**|Zhiwen Fan et.al.|[2311.17245](http://arxiv.org/abs/2311.17245)|**[link](https://github.com/VITA-Group/LightGaussian)**|
|**2023-11-28**|**Continuous Pose for Monocular Cameras in Neural Implicit Representation**|Qi Ma et.al.|[2311.17119](http://arxiv.org/abs/2311.17119)|**[link](https://github.com/qimaqi/continuous-pose-in-nerf)**|
|**2023-11-30**|**REF $^2$ -NeRF: Reflection and Refraction aware Neural Radiance Field**|Wooseok Kim et.al.|[2311.17116](http://arxiv.org/abs/2311.17116)|null|
|**2023-11-28**|**UC-NeRF: Neural Radiance Field for Under-Calibrated multi-view cameras in autonomous driving**|Kai Cheng et.al.|[2311.16945](http://arxiv.org/abs/2311.16945)|null|
|**2023-11-28**|**The Sky's the Limit: Re-lightable Outdoor Scenes via a Sky-pixel Constrained Illumination Prior and Outside-In Visibility**|James A. D. Gardner et.al.|[2311.16937](http://arxiv.org/abs/2311.16937)|**[link](https://github.com/jadgardner/neusky)**|
|**2023-11-28**|**SplitNeRF: Split Sum Approximation Neural Field for Joint Geometry, Illumination, and Material Estimation**|Jesus Zarzar et.al.|[2311.16671](http://arxiv.org/abs/2311.16671)|null|
|**2023-11-28**|**DGNR: Density-Guided Neural Point Rendering of Large Driving Scenes**|Zhuopeng Li et.al.|[2311.16664](http://arxiv.org/abs/2311.16664)|null|
|**2023-11-28**|**SCALAR-NeRF: SCAlable LARge-scale Neural Radiance Fields for Scene Reconstruction**|Yu Chen et.al.|[2311.16657](http://arxiv.org/abs/2311.16657)|null|
|**2023-11-28**|**Rethinking Directional Integration in Neural Radiance Fields**|Congyue Deng et.al.|[2311.16504](http://arxiv.org/abs/2311.16504)|null|
|**2023-11-27**|**Deceptive-Human: Prompt-to-NeRF 3D Human Generation with 3D-Consistent Synthetic Images**|Shiu-hong Kao et.al.|[2311.16499](http://arxiv.org/abs/2311.16499)|**[link](https://github.com/danielshkao/deceptivehuman)**|
|**2023-11-26**|**GS-IR: 3D Gaussian Splatting for Inverse Rendering**|Zhihao Liang et.al.|[2311.16473](http://arxiv.org/abs/2311.16473)|**[link](https://github.com/lzhnb/gs-ir)**|
|**2023-11-27**|**Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling**|Zhe Li et.al.|[2311.16096](http://arxiv.org/abs/2311.16096)|**[link](https://github.com/lizhe00/animatablegaussians)**|
|**2023-11-27**|**SOAC: Spatio-Temporal Overlap-Aware Multi-Sensor Calibration using Neural Radiance Fields**|Quentin Herau et.al.|[2311.15803](http://arxiv.org/abs/2311.15803)|null|
|**2023-11-27**|**CaesarNeRF: Calibrated Semantic Representation for Few-shot Generalizable Neural Rendering**|Haidong Zhu et.al.|[2311.15510](http://arxiv.org/abs/2311.15510)|**[link](https://github.com/haidongz-usc/CaesarNeRF)**|
|**2023-11-26**|**Efficient Encoding of Graphics Primitives with Simplex-based Structures**|Yibo Wen et.al.|[2311.15439](http://arxiv.org/abs/2311.15439)|null|
|**2023-11-26**|**Obj-NeRF: Extract Object NeRFs from Multi-view Images**|Zhiyi Li et.al.|[2311.15291](http://arxiv.org/abs/2311.15291)|null|
|**2023-11-26**|**NeuRAD: Neural Rendering for Autonomous Driving**|Adam Tonderski et.al.|[2311.15260](http://arxiv.org/abs/2311.15260)|**[link](https://github.com/georghess/neurad)**|
|**2023-11-24**|**Animate124: Animating One Image to 4D Dynamic Scene**|Yuyang Zhao et.al.|[2311.14603](http://arxiv.org/abs/2311.14603)|null|
|**2023-11-24**|**GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting**|Yiwen Chen et.al.|[2311.14521](http://arxiv.org/abs/2311.14521)|null|
|**2023-11-23**|**ECRF: Entropy-Constrained Neural Radiance Fields Compression with Frequency Domain Optimization**|Soonbin Lee et.al.|[2311.14208](http://arxiv.org/abs/2311.14208)|null|
|**2023-11-23**|**Tube-NeRF: Efficient Imitation Learning of Visuomotor Policies from MPC using Tube-Guided Data Augmentation and NeRFs**|Andrea Tagliabue et.al.|[2311.14153](http://arxiv.org/abs/2311.14153)|null|
|**2023-11-23**|**Towards Transferable Multi-modal Perception Representation Learning for Autonomy: NeRF-Supervised Masked AutoEncoder**|Xiaohao Xu et.al.|[2311.13750](http://arxiv.org/abs/2311.13750)|null|
|**2023-11-22**|**Compact 3D Gaussian Representation for Radiance Field**|Joo Chan Lee et.al.|[2311.13681](http://arxiv.org/abs/2311.13681)|null|
|**2023-11-22**|**Boosting3D: High-Fidelity Image-to-3D by Boosting 2D Diffusion Prior to 3D Prior with Progressive Learning**|Kai Yu et.al.|[2311.13617](http://arxiv.org/abs/2311.13617)|null|
|**2023-11-27**|**Animatable 3D Gaussians for High-fidelity Synthesis of Human Motions**|Keyang Ye et.al.|[2311.13404](http://arxiv.org/abs/2311.13404)|null|
|**2023-11-22**|**Depth-Regularized Optimization for 3D Gaussian Splatting in Few-Shot Images**|Jaeyoung Chung et.al.|[2311.13398](http://arxiv.org/abs/2311.13398)|null|
|**2023-11-22**|**3D Face Style Transfer with a Hybrid Solution of NeRF and Mesh Rasterization**|Jianwei Feng et.al.|[2311.13168](http://arxiv.org/abs/2311.13168)|null|
|**2023-11-22**|**PIE-NeRF: Physics-based Interactive Elastodynamics with NeRF**|Yutao Feng et.al.|[2311.13099](http://arxiv.org/abs/2311.13099)|null|
|**2023-11-29**|**SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering**|Antoine Guédon et.al.|[2311.12775](http://arxiv.org/abs/2311.12775)|null|
|**2023-11-21**|**Hyb-NeRF: A Multiresolution Hybrid Encoding for Neural Radiance Fields**|Yifan Wang et.al.|[2311.12490](http://arxiv.org/abs/2311.12490)|null|
|**2023-11-18**|**Towards Function Space Mesh Watermarking: Protecting the Copyright of Signed Distance Fields**|Xingyu Zhu et.al.|[2311.12059](http://arxiv.org/abs/2311.12059)|null|
|**2023-11-20**|**GP-NeRF: Generalized Perception NeRF for Context-Aware 3D Scene Understanding**|Hao Li et.al.|[2311.11863](http://arxiv.org/abs/2311.11863)|null|
|**2023-11-20**|**Entangled View-Epipolar Information Aggregation for Generalizable Neural Radiance Fields**|Zhiyuan Min et.al.|[2311.11845](http://arxiv.org/abs/2311.11845)|**[link](https://github.com/tatakai1/evenerf)**|
|**2023-11-19**|**GaussianDiffusion: 3D Gaussian Splatting for Denoising Diffusion Probabilistic Models with Structured Noise**|Xinhai Li et.al.|[2311.11221](http://arxiv.org/abs/2311.11221)|null|
|**2023-11-18**|**SNI-SLAM: Semantic Neural Implicit SLAM**|Siting Zhu et.al.|[2311.11016](http://arxiv.org/abs/2311.11016)|null|
|**2023-11-18**|**Structure-Aware Sparse-View X-ray 3D Reconstruction**|Yuanhao Cai et.al.|[2311.10959](http://arxiv.org/abs/2311.10959)|**[link](https://github.com/caiyuanhao1998/sax-nerf)**|
|**2023-11-17**|**Removing Adverse Volumetric Effects From Trained Neural Radiance Fields**|Andreas L. Teigen et.al.|[2311.10523](http://arxiv.org/abs/2311.10523)|null|
|**2023-11-18**|**EvaSurf: Efficient View-Aware Implicit Textured Surface Reconstruction on Mobile Devices**|Jingnan Gao et.al.|[2311.09806](http://arxiv.org/abs/2311.09806)|null|
|**2023-11-16**|**Reconstructing Continuous Light Field From Single Coded Image**|Yuya Ishikawa et.al.|[2311.09646](http://arxiv.org/abs/2311.09646)|null|
|**2023-11-15**|**Single-Image 3D Human Digitization with Shape-Guided Diffusion**|Badour AlBahar et.al.|[2311.09221](http://arxiv.org/abs/2311.09221)|null|
|**2023-11-15**|**DMV3D: Denoising Multi-View Diffusion using 3D Large Reconstruction Model**|Yinghao Xu et.al.|[2311.09217](http://arxiv.org/abs/2311.09217)|null|
|**2023-11-15**|**Spiking NeRF: Representing the Real-World Geometry by a Discontinuous Representation**|Zhanfeng Liao et.al.|[2311.09077](http://arxiv.org/abs/2311.09077)|null|
|**2023-11-13**|**$L_0$-Sampler: An $L_{0}$ Model Guided Volume Sampling for NeRF**|Liangchen Li et.al.|[2311.07044](http://arxiv.org/abs/2311.07044)|null|
|**2023-11-11**|**Aria-NeRF: Multimodal Egocentric View Synthesis**|Jiankai Sun et.al.|[2311.06455](http://arxiv.org/abs/2311.06455)|null|
|**2023-11-23**|**Instant3D: Fast Text-to-3D with Sparse-View Generation and Large Reconstruction Model**|Jiahao Li et.al.|[2311.06214](http://arxiv.org/abs/2311.06214)|null|
|**2023-11-10**|**A Neural Height-Map Approach for the Binocular Photometric Stereo Problem**|Fotios Logothetis et.al.|[2311.05958](http://arxiv.org/abs/2311.05958)|null|
|**2023-11-09**|**BakedAvatar: Baking Neural Fields for Real-Time Head Avatar Synthesis**|Hao-Bin Duan et.al.|[2311.05521](http://arxiv.org/abs/2311.05521)|null|
|**2023-11-09**|**Control3D: Towards Controllable Text-to-3D Generation**|Yang Chen et.al.|[2311.05461](http://arxiv.org/abs/2311.05461)|null|
|**2023-11-08**|**LRM: Large Reconstruction Model for Single Image to 3D**|Yicong Hong et.al.|[2311.04400](http://arxiv.org/abs/2311.04400)|null|
|**2023-11-14**|**ADFactory: An Effective Framework for Generalizing Optical Flow with Nerf**|Han Ling et.al.|[2311.04246](http://arxiv.org/abs/2311.04246)|null|
|**2023-11-07**|**High-fidelity 3D Reconstruction of Plants using Neural Radiance Field**|Kewei Hu et.al.|[2311.04154](http://arxiv.org/abs/2311.04154)|null|
|**2023-11-07**|**Fast Sun-aligned Outdoor Scene Relighting based on TensoRF**|Yeonjin Chang et.al.|[2311.03965](http://arxiv.org/abs/2311.03965)|null|
|**2023-11-08**|**UP-NeRF: Unconstrained Pose-Prior-Free Neural Radiance Fields**|Injae Kim et.al.|[2311.03784](http://arxiv.org/abs/2311.03784)|**[link](https://github.com/mlvlab/UP-NeRF)**|
|**2023-11-06**|**Osprey: Multi-Session Autonomous Aerial Mapping with LiDAR-based SLAM and Next Best View Planning**|Rowan Border et.al.|[2311.03484](http://arxiv.org/abs/2311.03484)|null|
|**2023-11-06**|**Animating NeRFs from Texture Space: A Framework for Pose-Dependent Rendering of Human Performances**|Paul Knoll et.al.|[2311.03140](http://arxiv.org/abs/2311.03140)|null|
|**2023-11-06**|**InstructPix2NeRF: Instructed 3D Portrait Editing from a Single Image**|Jianhui Li et.al.|[2311.02826](http://arxiv.org/abs/2311.02826)|**[link](https://github.com/mybabyyh/instructpix2nerf)**|
|**2023-11-03**|**Estimating 3D Uncertainty Field: Quantifying Uncertainty for Neural Radiance Fields**|Jianxiong Shen et.al.|[2311.01815](http://arxiv.org/abs/2311.01815)|null|
|**2023-11-03**|**PDF: Point Diffusion Implicit Function for Large-scale Scene Neural Representation**|Yuhan Ding et.al.|[2311.01773](http://arxiv.org/abs/2311.01773)|null|
|**2023-11-03**|**Efficient Cloud Pipelines for Neural Radiance Fields**|Derek Jacoby et.al.|[2311.01659](http://arxiv.org/abs/2311.01659)|null|
|**2023-11-02**|**Novel View Synthesis from a Single RGBD Image for Indoor Scenes**|Congrui Hetang et.al.|[2311.01065](http://arxiv.org/abs/2311.01065)|null|
|**2023-10-31**|**FPO++: Efficient Encoding and Rendering of Dynamic Neural Radiance Fields by Analyzing and Enhancing Fourier PlenOctrees**|Saskia Rabich et.al.|[2310.20710](http://arxiv.org/abs/2310.20710)|null|
|**2023-10-31**|**NeRF Revisited: Fixing Quadrature Instability in Volume Rendering**|Mikaela Angelina Uy et.al.|[2310.20685](http://arxiv.org/abs/2310.20685)|null|
|**2023-10-30**|**Generative Neural Fields by Mixtures of Neural Implicit Functions**|Tackgeun You et.al.|[2310.19464](http://arxiv.org/abs/2310.19464)|null|
|**2023-11-04**|**TiV-NeRF: Tracking and Mapping via Time-Varying Representation with Dynamic Neural Radiance Fields**|Chengyao Duan et.al.|[2310.18917](http://arxiv.org/abs/2310.18917)|null|
|**2023-10-28**|**INCODE: Implicit Neural Conditioning with Prior Knowledge Embeddings**|Amirhossein Kazerouni et.al.|[2310.18846](http://arxiv.org/abs/2310.18846)|**[link](https://github.com/xmindflow/INCODE)**|
|**2023-10-27**|**ZeroNVS: Zero-Shot 360-Degree View Synthesis from a Single Real Image**|Kyle Sargent et.al.|[2310.17994](http://arxiv.org/abs/2310.17994)|null|
|**2023-10-27**|**Reconstructive Latent-Space Neural Radiance Fields for Efficient 3D Scene Representations**|Tristan Aumentado-Armstrong et.al.|[2310.17880](http://arxiv.org/abs/2310.17880)|null|
|**2023-10-27**|**HyperFields: Towards Zero-Shot Generation of NeRFs from Text**|Sudarshan Babu et.al.|[2310.17075](http://arxiv.org/abs/2310.17075)|null|
|**2023-11-06**|**4D-Editor: Interactive Object-level Editing in Dynamic Neural Radiance Fields via Semantic Distillation**|Dadong Jiang et.al.|[2310.16858](http://arxiv.org/abs/2310.16858)|null|
|**2023-10-26**|**LightSpeed: Light and Fast Neural Light Fields on Mobile Devices**|Aarush Gupta et.al.|[2310.16832](http://arxiv.org/abs/2310.16832)|**[link](https://github.com/lightspeed-r2l/lightspeed)**|
|**2023-10-28**|**PERF: Panoramic Neural Radiance Field from a Single Panorama**|Guangcong Wang et.al.|[2310.16831](http://arxiv.org/abs/2310.16831)|**[link](https://github.com/perf-project/PeRF)**|
|**2023-10-25**|**Open-NeRF: Towards Open Vocabulary NeRF Decomposition**|Hao Zhang et.al.|[2310.16383](http://arxiv.org/abs/2310.16383)|null|
|**2023-10-25**|**UAV-Sim: NeRF-based Synthetic Data Generation for UAV-based Perception**|Christopher Maxey et.al.|[2310.16255](http://arxiv.org/abs/2310.16255)|null|
|**2023-10-24**|**Cross-view Self-localization from Synthesized Scene-graphs**|Ryogo Yamamoto et.al.|[2310.15504](http://arxiv.org/abs/2310.15504)|null|
|**2023-10-23**|**CAwa-NeRF: Instant Learning of Compression-Aware NeRF Features**|Omnia Mahmoud et.al.|[2310.14695](http://arxiv.org/abs/2310.14695)|null|
|**2023-10-23**|**VQ-NeRF: Vector Quantization Enhances Implicit Neural Representations**|Yiying Yang et.al.|[2310.14487](http://arxiv.org/abs/2310.14487)|null|
|**2023-10-20**|**ManifoldNeRF: View-dependent Image Feature Supervision for Few-shot Neural Radiance Fields**|Daiju Kanaoka et.al.|[2310.13670](http://arxiv.org/abs/2310.13670)|null|
|**2023-10-20**|**Sync-NeRF: Generalizing Dynamic NeRFs to Unsynchronized Videos**|Seoha Kim et.al.|[2310.13356](http://arxiv.org/abs/2310.13356)|**[link](https://github.com/seoha-kim/Sync-NeRF)**|
|**2023-10-20**|**UE4-NeRF:Neural Radiance Field for Real-Time Rendering of Large-Scale Scene**|Jiaming Gu et.al.|[2310.13263](http://arxiv.org/abs/2310.13263)|null|
|**2023-11-05**|**VQ-NeRF: Neural Reflectance Decomposition and Editing with Vector Quantization**|Hongliang Zhong et.al.|[2310.11864](http://arxiv.org/abs/2310.11864)|null|
|**2023-10-18**|**Towards Abdominal 3-D Scene Rendering from Laparoscopy Surgical Videos using NeRFs**|Khoa Tuan Nguyen et.al.|[2310.11645](http://arxiv.org/abs/2310.11645)|null|
|**2023-10-16**|**TraM-NeRF: Tracing Mirror and Near-Perfect Specular Reflections through Neural Radiance Fields**|Leif Van Holland et.al.|[2310.10650](http://arxiv.org/abs/2310.10650)|**[link](https://github.com/Rubikalubi/TraM-NeRF)**|
|**2023-10-16**|**DynVideo-E: Harnessing Dynamic NeRF for Large-Scale Motion- and View-Change Human-Centric Video Editing**|Jia-Wei Liu et.al.|[2310.10624](http://arxiv.org/abs/2310.10624)|null|
|**2023-10-16**|**Self-supervised Fetal MRI 3D Reconstruction Based on Radiation Diffusion Generation Model**|Junpeng Tan et.al.|[2310.10209](http://arxiv.org/abs/2310.10209)|null|
|**2023-10-15**|**ProteusNeRF: Fast Lightweight NeRF Editing using 3D-Aware Image Context**|Binglun Wang et.al.|[2310.09965](http://arxiv.org/abs/2310.09965)|null|
|**2023-10-15**|**Active Perception using Neural Radiance Fields**|Siming He et.al.|[2310.09892](http://arxiv.org/abs/2310.09892)|**[link](https://github.com/grasp-lyrl/active-perception-using-neural-radiance-fields)**|
|**2023-10-15**|**CBARF: Cascaded Bundle-Adjusting Neural Radiance Fields from Imperfect Camera Poses**|Hongyu Fu et.al.|[2310.09776](http://arxiv.org/abs/2310.09776)|null|
|**2023-10-11**|**Dynamic Appearance Particle Neural Radiance Field**|Ancheng Lin et.al.|[2310.07916](http://arxiv.org/abs/2310.07916)|null|
|**2023-10-12**|**PoRF: Pose Residual Field for Accurate Neural Surface Reconstruction**|Jia-Wang Bian et.al.|[2310.07449](http://arxiv.org/abs/2310.07449)|null|
|**2023-10-11**|**rpcPRF: Generalizable MPI Neural Radiance Field for Satellite Camera**|Tongtong Zhang et.al.|[2310.07179](http://arxiv.org/abs/2310.07179)|null|
|**2023-10-10**|**Leveraging Neural Radiance Fields for Uncertainty-Aware Visual Localization**|Le Chen et.al.|[2310.06984](http://arxiv.org/abs/2310.06984)|null|
|**2023-10-10**|**High-Fidelity 3D Head Avatars Reconstruction through Spatially-Varying Expression Conditioned Neural Radiance Field**|Minghan Qin et.al.|[2310.06275](http://arxiv.org/abs/2310.06275)|null|
|**2023-10-09**|**A Real-time Method for Inserting Virtual Objects into Neural Radiance Fields**|Keyang Ye et.al.|[2310.05837](http://arxiv.org/abs/2310.05837)|null|
|**2023-10-09**|**Neural Impostor: Editing Neural Radiance Fields with Explicit Shape Manipulation**|Ruiyang Liu et.al.|[2310.05391](http://arxiv.org/abs/2310.05391)|null|
|**2023-10-08**|**LocoNeRF: A NeRF-based Approach for Local Structure from Motion for Precise Localization**|Artem Nenashev et.al.|[2310.05134](http://arxiv.org/abs/2310.05134)|null|
|**2023-10-08**|**Geometry Aware Field-to-field Transformations for 3D Semantic Segmentation**|Dominik Hollidt et.al.|[2310.05133](http://arxiv.org/abs/2310.05133)|null|
|**2023-10-06**|**Improving Neural Radiance Field using Near-Surface Sampling with Point Cloud Generation**|Hye Bin Yoo et.al.|[2310.04152](http://arxiv.org/abs/2310.04152)|null|
|**2023-10-05**|**Drag View: Generalizable Novel View Synthesis with Unposed Imagery**|Zhiwen Fan et.al.|[2310.03704](http://arxiv.org/abs/2310.03704)|null|
|**2023-10-05**|**Targeted Adversarial Attacks on Generalizable Neural Radiance Fields**|Andras Horvath et.al.|[2310.03578](http://arxiv.org/abs/2310.03578)|null|
|**2023-10-05**|**BID-NeRF: RGB-D image pose estimation with inverted Neural Radiance Fields**|Ágoston István Csehi et.al.|[2310.03563](http://arxiv.org/abs/2310.03563)|null|
|**2023-10-04**|**Shielding the Unseen: Privacy Protection through Poisoning NeRF with Spatial Deformation**|Yihan Wu et.al.|[2310.03125](http://arxiv.org/abs/2310.03125)|null|
|**2023-10-04**|**T $^3$ Bench: Benchmarking Current Progress in Text-to-3D Generation**|Yuze He et.al.|[2310.02977](http://arxiv.org/abs/2310.02977)|**[link](https://github.com/THU-LYJ-Lab/T3Bench)**|
|**2023-10-04**|**ED-NeRF: Efficient Text-Guided Editing of 3D Scene using Latent Space NeRF**|Jangho Park et.al.|[2310.02712](http://arxiv.org/abs/2310.02712)|null|
|**2023-10-05**|**USB-NeRF: Unrolling Shutter Bundle Adjusted Neural Radiance Fields**|Moyang Li et.al.|[2310.02687](http://arxiv.org/abs/2310.02687)|null|
|**2023-10-03**|**EvDNeRF: Reconstructing Event Data with Dynamic Neural Radiance Fields**|Anish Bhattacharya et.al.|[2310.02437](http://arxiv.org/abs/2310.02437)|**[link](https://github.com/anish-bhattacharya/evdnerf)**|
|**2023-10-03**|**Adaptive Multi-NeRF: Exploit Efficient Parallelism in Adaptive Multiple Scale Neural Radiance Field Rendering**|Tong Wang et.al.|[2310.01881](http://arxiv.org/abs/2310.01881)|null|
|**2023-10-03**|**MIMO-NeRF: Fast Neural Rendering with Multi-input Multi-output Neural Radiance Fields**|Takuhiro Kaneko et.al.|[2310.01821](http://arxiv.org/abs/2310.01821)|null|
|**2023-10-02**|**PC-NeRF: Parent-Child Neural Radiance Fields under Partial Sensor Data Loss in Autonomous Driving Environments**|Xiuzhong Hu et.al.|[2310.00874](http://arxiv.org/abs/2310.00874)|**[link](https://github.com/biter0088/pc-nerf)**|
|**2023-10-01**|**How Many Views Are Needed to Reconstruct an Unknown Object Using NeRF?**|Sicong Pan et.al.|[2310.00684](http://arxiv.org/abs/2310.00684)|**[link](https://github.com/psc0628/nerf-prv)**|
|**2023-10-01**|**Enabling Neural Radiance Fields (NeRF) for Large-scale Aerial Images -- A Multi-tiling Approaching and the Geometry Assessment of NeRF**|Ningli Xu et.al.|[2310.00530](http://arxiv.org/abs/2310.00530)|null|
|**2023-09-30**|**MMPI: a Flexible Radiance Field Representation by Multiple Multi-plane Images Blending**|Yuze He et.al.|[2310.00249](http://arxiv.org/abs/2310.00249)|null|
|**2023-09-29**|**Multi-task View Synthesis with Neural Radiance Fields**|Shuhong Zheng et.al.|[2309.17450](http://arxiv.org/abs/2309.17450)|**[link](https://github.com/zsh2000/muvienerf)**|
|**2023-09-29**|**Forward Flow for Novel View Synthesis of Dynamic Scenes**|Xiang Guo et.al.|[2309.17390](http://arxiv.org/abs/2309.17390)|null|
|**2023-09-29**|**HAvatar: High-fidelity Head Avatar via Facial Model Conditioned Neural Radiance Field**|Xiaochen Zhao et.al.|[2309.17128](http://arxiv.org/abs/2309.17128)|null|
|**2023-09-28**|**Preface: A Data-driven Volumetric Prior for Few-shot Ultra High-resolution Face Synthesis**|Marcel C. Bühler et.al.|[2309.16859](http://arxiv.org/abs/2309.16859)|null|
|**2023-09-28**|**MatrixCity: A Large-scale City Dataset for City-scale Neural Rendering and Beyond**|Yixuan Li et.al.|[2309.16553](http://arxiv.org/abs/2309.16553)|null|
|**2023-10-04**|**FG-NeRF: Flow-GAN based Probabilistic Neural Radiance Field for Independence-Assumption-Free Uncertainty Estimation**|Songlin Wei et.al.|[2309.16364](http://arxiv.org/abs/2309.16364)|null|
|**2023-09-21**|**ORTexME: Occlusion-Robust Human Shape and Pose via Temporal Average Texture and Mesh Encoding**|Yu Cheng et.al.|[2309.12183](http://arxiv.org/abs/2309.12183)|null|
|**2023-09-21**|**Fast Satellite Tensorial Radiance Field for Multi-date Satellite Imagery of Large Size**|Tongtong Zhang et.al.|[2309.11767](http://arxiv.org/abs/2309.11767)|null|
|**2023-09-21**|**MarkNerf:Watermarking for Neural Radiance Field**|Lifeng Chen et.al.|[2309.11747](http://arxiv.org/abs/2309.11747)|null|
|**2023-09-20**|**Light Field Diffusion for Single-View Novel View Synthesis**|Yifeng Xiong et.al.|[2309.11525](http://arxiv.org/abs/2309.11525)|null|
|**2023-09-21**|**Controllable Dynamic Appearance for Neural 3D Portraits**|ShahRukh Athar et.al.|[2309.11009](http://arxiv.org/abs/2309.11009)|null|
|**2023-09-20**|**Spiking NeRF: Making Bio-inspired Neural Networks See through the Real World**|Xingting Yao et.al.|[2309.10987](http://arxiv.org/abs/2309.10987)|null|
|**2023-09-19**|**Locally Stylized Neural Radiance Fields**|Hong-Wing Pang et.al.|[2309.10684](http://arxiv.org/abs/2309.10684)|null|
|**2023-09-19**|**Steganography for Neural Radiance Fields by Backdooring**|Weina Dong et.al.|[2309.10503](http://arxiv.org/abs/2309.10503)|null|
|**2023-09-18**|**Instant Photorealistic Style Transfer: A Lightweight and Adaptive Approach**|Rong Liu et.al.|[2309.10011](http://arxiv.org/abs/2309.10011)|null|
|**2023-09-17**|**NeRF-VINS: A Real-time Neural Radiance Field Map-based Visual-Inertial Navigation System**|Saimouli Katragadda et.al.|[2309.09295](http://arxiv.org/abs/2309.09295)|null|
|**2023-09-16**|**DynaMoN: Motion-Aware Fast And Robust Camera Localization for Dynamic NeRF**|Mert Asim Karaoglu et.al.|[2309.08927](http://arxiv.org/abs/2309.08927)|null|
|**2023-09-15**|**Robust e-NeRF: NeRF from Sparse & Noisy Events under Non-Uniform Motion**|Weng Fei Low et.al.|[2309.08596](http://arxiv.org/abs/2309.08596)|**[link](https://github.com/wengflow/robust-e-nerf)**|
|**2023-09-14**|**MC-NeRF: Muti-Camera Neural Radiance Fields for Muti-Camera Image Acquisition Systems**|Yu Gao et.al.|[2309.07846](http://arxiv.org/abs/2309.07846)|null|
|**2023-09-14**|**DT-NeRF: Decomposed Triplane-Hash Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis**|Yaoyu Su et.al.|[2309.07752](http://arxiv.org/abs/2309.07752)|null|
|**2023-09-14**|**CoRF : Colorizing Radiance Fields using Knowledge Distillation**|Ankit Dhiman et.al.|[2309.07668](http://arxiv.org/abs/2309.07668)|null|
|**2023-09-13**|**Text-Guided Generation and Editing of Compositional 3D Avatars**|Hao Zhang et.al.|[2309.07125](http://arxiv.org/abs/2309.07125)|null|
|**2023-09-13**|**Dynamic NeRFs for Soccer Scenes**|Sacha Lewin et.al.|[2309.06802](http://arxiv.org/abs/2309.06802)|null|
|**2023-09-12**|**Federated Learning for Large-Scale Scene Modeling with Neural Radiance Fields**|Teppei Suzuki et.al.|[2309.06030](http://arxiv.org/abs/2309.06030)|null|
|**2023-09-11**|**PAg-NeRF: Towards fast and efficient end-to-end panoptic 3D representations for agricultural robotics**|Claus Smitt et.al.|[2309.05339](http://arxiv.org/abs/2309.05339)|null|
|**2023-09-10**|**Text-driven Editing of 3D Scenes without Retraining**|Shuangkang Fang et.al.|[2309.04917](http://arxiv.org/abs/2309.04917)|null|
|**2023-09-09**|**Mirror-Aware Neural Humans**|Daniel Ajisafe et.al.|[2309.04750](http://arxiv.org/abs/2309.04750)|null|
|**2023-09-08**|**Dynamic Mesh-Aware Radiance Fields**|Yi-Ling Qiao et.al.|[2309.04581](http://arxiv.org/abs/2309.04581)|null|
|**2023-09-08**|**DeformToon3D: Deformable 3D Toonification from Neural Radiance Fields**|Junzhe Zhang et.al.|[2309.04410](http://arxiv.org/abs/2309.04410)|null|
|**2023-09-14**|**SimpleNeRF: Regularizing Sparse Input Neural Radiance Fields with Simpler Solutions**|Nagabhushan Somraj et.al.|[2309.03955](http://arxiv.org/abs/2309.03955)|null|
|**2023-09-07**|**BluNF: Blueprint Neural Field**|Robin Courant et.al.|[2309.03933](http://arxiv.org/abs/2309.03933)|null|
|**2023-09-07**|**Text2Control3D: Controllable 3D Avatar Generation in Neural Radiance Fields using Geometry-Guided Text-to-Image Diffusion Model**|Sungwon Hwang et.al.|[2309.03550](http://arxiv.org/abs/2309.03550)|null|
|**2023-09-06**|**Bayes' Rays: Uncertainty Quantification for Neural Radiance Fields**|Lily Goli et.al.|[2309.03185](http://arxiv.org/abs/2309.03185)|**[link](https://github.com/BayesRays/BayesRays)**|
|**2023-09-06**|**ResFields: Residual Neural Fields for Spatiotemporal Signals**|Marko Mihajlovic et.al.|[2309.03160](http://arxiv.org/abs/2309.03160)|**[link](https://github.com/markomih/ResFields)**|
|**2023-09-06**|**Instant Continual Learning of Neural Radiance Fields**|Ryan Po et.al.|[2309.01811](http://arxiv.org/abs/2309.01811)|null|
|**2023-09-04**|**Adv3D: Generating 3D Adversarial Examples in Driving Scenarios with NeRF**|Leheng Li et.al.|[2309.01351](http://arxiv.org/abs/2309.01351)|null|
|**2023-09-01**|**SparseSat-NeRF: Dense Depth Supervised Neural Radiance Fields for Sparse Satellite Images**|Lulin Zhang et.al.|[2309.00277](http://arxiv.org/abs/2309.00277)|**[link](https://github.com/lulinzhang/sps-nerf)**|
|**2023-09-04**|**Improving NeRF Quality by Progressive Camera Placement for Unrestricted Navigation in Complex Environments**|Georgios Kopanas et.al.|[2309.00014](http://arxiv.org/abs/2309.00014)|null|
|**2023-09-03**|**GHuNeRF: Generalizable Human NeRF from a Monocular Video**|Chen Li et.al.|[2308.16576](http://arxiv.org/abs/2308.16576)|null|
|**2023-08-30**|**From Pixels to Portraits: A Comprehensive Survey of Talking Head Generation Techniques and Applications**|Shreyank N Gowda et.al.|[2308.16041](http://arxiv.org/abs/2308.16041)|null|
|**2023-08-30**|**Drone-NeRF: Efficient NeRF Based 3D Scene Reconstruction for Large-Scale Drone Survey**|Zhihao Jia et.al.|[2308.15733](http://arxiv.org/abs/2308.15733)|null|
|**2023-08-29**|**Efficient Ray Sampling for Radiance Fields Reconstruction**|Shilei Sun et.al.|[2308.15547](http://arxiv.org/abs/2308.15547)|null|
|**2023-08-29**|**Pose-Free Neural Radiance Fields via Implicit Pose Regularization**|Jiahui Zhang et.al.|[2308.15049](http://arxiv.org/abs/2308.15049)|null|
|**2023-08-28**|**CLNeRF: Continual Learning Meets NeRF**|Zhipeng Cai et.al.|[2308.14816](http://arxiv.org/abs/2308.14816)|**[link](https://github.com/intellabs/clnerf)**|
|**2023-08-26**|**InsertNeRF: Instilling Generalizability into NeRF with HyperNet Modules**|Yanqi Bao et.al.|[2308.13897](http://arxiv.org/abs/2308.13897)|**[link](https://github.com/bbbbby-99/insertnerf)**|
|**2023-08-24**|**NOVA: NOvel View Augmentation for Neural Composition of Dynamic Objects**|Dakshit Agrawal et.al.|[2308.12560](http://arxiv.org/abs/2308.12560)|**[link](https://github.com/dakshitagrawal/nova)**|
|**2023-08-23**|**Blending-NeRF: Text-Driven Localized Editing in Neural Radiance Fields**|Hyeonseop Song et.al.|[2308.11974](http://arxiv.org/abs/2308.11974)|null|
|**2023-08-25**|**Pose Modulated Avatars from Video**|Chunjin Song et.al.|[2308.11951](http://arxiv.org/abs/2308.11951)|null|
|**2023-08-22**|**Enhancing NeRF akin to Enhancing LLMs: Generalizable NeRF Transformer with Mixture-of-View-Experts**|Wenyan Cong et.al.|[2308.11793](http://arxiv.org/abs/2308.11793)|**[link](https://github.com/vita-group/gnt-move)**|
|**2023-08-22**|**SAMSNeRF: Segment Anything Model (SAM) Guides Dynamic Surgical Scene Reconstruction by Neural Radiance Field (NeRF)**|Ange Lou et.al.|[2308.11774](http://arxiv.org/abs/2308.11774)|null|
|**2023-08-22**|**Novel-view Synthesis and Pose Estimation for Hand-Object Interaction from Sparse Views**|Wentian Qu et.al.|[2308.11198](http://arxiv.org/abs/2308.11198)|null|
|**2023-08-22**|**Efficient View Synthesis with Neural Radiance Distribution Field**|Yushuang Wu et.al.|[2308.11130](http://arxiv.org/abs/2308.11130)|null|
|**2023-08-30**|**CamP: Camera Preconditioning for Neural Radiance Fields**|Keunhong Park et.al.|[2308.10902](http://arxiv.org/abs/2308.10902)|null|
|**2023-08-20**|**Strata-NeRF : Neural Radiance Fields for Stratified Scenes**|Ankit Dhiman et.al.|[2308.10337](http://arxiv.org/abs/2308.10337)|null|
|**2023-08-19**|**HollowNeRF: Pruning Hashgrid-Based NeRFs with Trainable Collision Mitigation**|Xiufeng Xie et.al.|[2308.10122](http://arxiv.org/abs/2308.10122)|null|
|**2023-08-19**|**AltNeRF: Learning Robust Neural Radiance Field via Alternating Depth-Pose Optimization**|Kun Wang et.al.|[2308.10001](http://arxiv.org/abs/2308.10001)|null|
|**2023-08-19**|**Semantic-Human: Neural Rendering of Humans from Monocular Video with Human Parsing**|Jie Zhang et.al.|[2308.09894](http://arxiv.org/abs/2308.09894)|null|
|**2023-08-18**|**MonoNeRD: NeRF-like Representations for Monocular 3D Object Detection**|Junkai Xu et.al.|[2308.09421](http://arxiv.org/abs/2308.09421)|**[link](https://github.com/cskkxjk/mononerd)**|
|**2023-08-18**|**DReg-NeRF: Deep Registration for Neural Radiance Fields**|Yu Chen et.al.|[2308.09386](http://arxiv.org/abs/2308.09386)|**[link](https://github.com/aibluefisher/dreg-nerf)**|
|**2023-08-17**|**Watch Your Steps: Local Image and Scene Editing by Text Instructions**|Ashkan Mirzaei et.al.|[2308.08947](http://arxiv.org/abs/2308.08947)|null|
|**2023-08-21**|**Ref-DVGO: Reflection-Aware Direct Voxel Grid Optimization for an Improved Quality-Efficiency Trade-Off in Reflective Scene Reconstruction**|Georgios Kouros et.al.|[2308.08530](http://arxiv.org/abs/2308.08530)|**[link](https://github.com/gkouros/ref-dvgo)**|
|**2023-08-16**|**SceNeRFlow: Time-Consistent Reconstruction of General Dynamic Scenes**|Edith Tretschk et.al.|[2308.08258](http://arxiv.org/abs/2308.08258)|null|
|**2023-08-16**|**Neural radiance fields in the industrial and robotics domain: applications, research opportunities and use cases**|Eugen Šlapak et.al.|[2308.07118](http://arxiv.org/abs/2308.07118)|**[link](https://github.com/maftej/iisnerf)**|
|**2023-08-14**|**S3IM: Stochastic Structural SIMilarity and Its Unreasonable Effectiveness for Neural Fields**|Zeke Xie et.al.|[2308.07032](http://arxiv.org/abs/2308.07032)|**[link](https://github.com/madaoer/s3im_nerf)**|
|**2023-08-11**|**Focused Specific Objects NeRF**|Yuesong Li et.al.|[2308.05970](http://arxiv.org/abs/2308.05970)|null|
|**2023-08-11**|**VERF: Runtime Monitoring of Pose Estimation with Neural Radiance Fields**|Dominic Maggio et.al.|[2308.05939](http://arxiv.org/abs/2308.05939)|null|
|**2023-08-09**|**WaveNeRF: Wavelet-based Generalizable Neural Radiance Fields**|Muyu Xu et.al.|[2308.04826](http://arxiv.org/abs/2308.04826)|null|
|**2023-08-14**|**A General Implicit Framework for Fast NeRF Composition and Rendering**|Xinyu Gao et.al.|[2308.04669](http://arxiv.org/abs/2308.04669)|null|
|**2023-08-08**|**Digging into Depth Priors for Outdoor Neural Radiance Fields**|Chen Wang et.al.|[2308.04413](http://arxiv.org/abs/2308.04413)|null|
|**2023-07-27**|**Improved Neural Radiance Fields Using Pseudo-depth and Fusion**|Jingliang Li et.al.|[2308.03772](http://arxiv.org/abs/2308.03772)|null|
|**2023-08-07**|**Mirror-NeRF: Learning Neural Radiance Fields for Mirrors with Whitted-Style Ray Tracing**|Junyi Zeng et.al.|[2308.03280](http://arxiv.org/abs/2308.03280)|null|
|**2023-08-05**|**Where and How: Mitigating Confusion in Neural Radiance Fields from Sparse Inputs**|Yanqi Bao et.al.|[2308.02908](http://arxiv.org/abs/2308.02908)|**[link](https://github.com/bbbbby-99/wah-nerf)**|
|**2023-08-05**|**Learning Unified Decompositional and Compositional NeRF for Editable Novel View Synthesis**|Yuxin Wang et.al.|[2308.02840](http://arxiv.org/abs/2308.02840)|null|
|**2023-08-05**|**NeRFs: The Search for the Best 3D Representation**|Ravi Ramamoorthi et.al.|[2308.02751](http://arxiv.org/abs/2308.02751)|null|
|**2023-08-04**|**ES-MVSNet: Efficient Framework for End-to-end Self-supervised Multi-View Stereo**|Qiang Zhou et.al.|[2308.02191](http://arxiv.org/abs/2308.02191)|null|
|**2023-08-02**|**Incorporating Season and Solar Specificity into Renderings made by a NeRF Architecture using Satellite Images**|Michael Gableman et.al.|[2308.01262](http://arxiv.org/abs/2308.01262)|**[link](https://github.com/enterprisecv-6/season-nerf)**|
|**2023-08-01**|**High-Fidelity Eye Animatable Neural Radiance Fields for Human Face**|Hengfei Wang et.al.|[2308.00773](http://arxiv.org/abs/2308.00773)|null|
|**2023-08-01**|**Context-Aware Talking-Head Video Editing**|Songlin Yang et.al.|[2308.00462](http://arxiv.org/abs/2308.00462)|null|
|**2023-07-28**|**Dynamic PlenOctree for Adaptive Sampling Refinement in Explicit NeRF**|Haotian Bai et.al.|[2307.15333](http://arxiv.org/abs/2307.15333)|null|
|**2023-07-27**|**Seal-3D: Interactive Pixel-Level Editing for Neural Radiance Fields**|Xiangyu Wang et.al.|[2307.15131](http://arxiv.org/abs/2307.15131)|**[link](https://github.com/windingwind/seal-3d)**|
|**2023-07-27**|**MARS: An Instance-aware, Modular and Realistic Simulator for Autonomous Driving**|Zirui Wu et.al.|[2307.15058](http://arxiv.org/abs/2307.15058)|**[link](https://github.com/open-air-sun/mars)**|
|**2023-07-27**|**NeRF-Det: Learning Geometry-Aware Volumetric Representation for Multi-View 3D Object Detection**|Chenfeng Xu et.al.|[2307.14620](http://arxiv.org/abs/2307.14620)|**[link](https://github.com/facebookresearch/nerf-det)**|
|**2023-07-26**|**Points-to-3D: Bridging the Gap between Sparse Points and Shape-Controllable Text-to-3D Generation**|Chaohui Yu et.al.|[2307.13908](http://arxiv.org/abs/2307.13908)|null|
|**2023-07-24**|**Dyn-E: Local Appearance Editing of Dynamic Neural Radiance Fields**|Shangzhan Zhang et.al.|[2307.12909](http://arxiv.org/abs/2307.12909)|null|
|**2023-07-24**|**CarPatch: A Synthetic Benchmark for Radiance Field Evaluation on Vehicle Components**|Davide Di Nucci et.al.|[2307.12718](http://arxiv.org/abs/2307.12718)|null|
|**2023-07-23**|**TransHuman: A Transformer-based Human Representation for Generalizable Neural Human Rendering**|Xiao Pan et.al.|[2307.12291](http://arxiv.org/abs/2307.12291)|null|
|**2023-07-29**|**CopyRNeRF: Protecting the CopyRight of Neural Radiance Fields**|Ziyuan Luo et.al.|[2307.11526](http://arxiv.org/abs/2307.11526)|null|
|**2023-07-21**|**FaceCLIPNeRF: Text-driven 3D Face Manipulation using Deformable Neural Radiance Fields**|Sungwon Hwang et.al.|[2307.11418](http://arxiv.org/abs/2307.11418)|null|
|**2023-07-21**|**Tri-MipRF: Tri-Mip Representation for Efficient Anti-Aliasing Neural Radiance Fields**|Wenbo Hu et.al.|[2307.11335](http://arxiv.org/abs/2307.11335)|null|
|**2023-07-20**|**Urban Radiance Field Representation with Deformable Neural Mesh Primitives**|Fan Lu et.al.|[2307.10776](http://arxiv.org/abs/2307.10776)|null|
|**2023-07-20**|**Lighting up NeRF via Unsupervised Decomposition and Enhancement**|Haoyuan Wang et.al.|[2307.10664](http://arxiv.org/abs/2307.10664)|**[link](https://github.com/onpix/LLNeRF)**|
|**2023-07-19**|**An Improved NeuMIP with Better Accuracy**|Bowen Xue et.al.|[2307.10135](http://arxiv.org/abs/2307.10135)|null|
|**2023-07-19**|**Magic NeRF Lens: Interactive Fusion of Neural Radiance Fields for Virtual Facility Inspection**|Ke Li et.al.|[2307.09860](http://arxiv.org/abs/2307.09860)|**[link](https://github.com/uhhhci/immersive-ngp)**|
|**2023-07-14**|**Transient Neural Radiance Fields for Lidar View Synthesis and 3D Reconstruction**|Anagh Malik et.al.|[2307.09555](http://arxiv.org/abs/2307.09555)|null|
|**2023-07-18**|**Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis**|Jiahe Li et.al.|[2307.09323](http://arxiv.org/abs/2307.09323)|**[link](https://github.com/fictionarry/er-nerf)**|
|**2023-07-16**|**Cross-Ray Neural Radiance Fields for Novel-view Synthesis from Unconstrained Image Collections**|Yifan Yang et.al.|[2307.08093](http://arxiv.org/abs/2307.08093)|**[link](https://github.com/yifyang993/cr-nerf-pytorch)**|
|**2023-07-15**|**Improving NeRF with Height Data for Utilization of GIS Data**|Hinata Aoki et.al.|[2307.07729](http://arxiv.org/abs/2307.07729)|null|
|**2023-07-11**|**SAR-NeRF: Neural Radiance Fields for Synthetic Aperture Radar Multi-View Representation**|Zhengxin Lei et.al.|[2307.05087](http://arxiv.org/abs/2307.05087)|null|
|**2023-07-07**|**NOFA: NeRF-based One-shot Facial Avatar Reconstruction**|Wangbo Yu et.al.|[2307.03441](http://arxiv.org/abs/2307.03441)|null|
|**2023-07-07**|**RGB-D Mapping and Tracking in a Plenoxel Radiance Field**|Andreas L. Teigen et.al.|[2307.03404](http://arxiv.org/abs/2307.03404)|null|
|**2023-07-16**|**FlipNeRF: Flipped Reflection Rays for Few-shot Novel View Synthesis**|Seunghyeon Seo et.al.|[2306.17723](http://arxiv.org/abs/2306.17723)|null|
|**2023-07-03**|**Sphere2Vec: A General-Purpose Location Representation Learning over a Spherical Surface for Large-Scale Geospatial Predictions**|Gengchen Mai et.al.|[2306.17624](http://arxiv.org/abs/2306.17624)|null|
|**2023-06-28**|**Envisioning a Next Generation Extended Reality Conferencing System with Efficient Photorealistic Human Rendering**|Chuanyue Shen et.al.|[2306.16541](http://arxiv.org/abs/2306.16541)|null|
|**2023-06-27**|**Unsupervised Polychromatic Neural Representation for CT Metal Artifact Reduction**|Qing Wu et.al.|[2306.15203](http://arxiv.org/abs/2306.15203)|null|
|**2023-06-22**|**Blended-NeRF: Zero-Shot Object Generation and Blending in Existing Neural Radiance Fields**|Ori Gordon et.al.|[2306.12760](http://arxiv.org/abs/2306.12760)|null|
|**2023-06-21**|**Local 3D Editing via 3D Distillation of CLIP Knowledge**|Junha Hyung et.al.|[2306.12570](http://arxiv.org/abs/2306.12570)|null|
|**2023-06-21**|**Benchmarking and Analyzing 3D-aware Image Synthesis with a Modularized Codebase**|Qiuyu Wang et.al.|[2306.12423](http://arxiv.org/abs/2306.12423)|**[link](https://github.com/qiuyu96/carver)**|
|**2023-06-21**|**DreamTime: An Improved Optimization Strategy for Text-to-3D Content Creation**|Yukun Huang et.al.|[2306.12422](http://arxiv.org/abs/2306.12422)|null|
|**2023-06-20**|**NeRF synthesis with shading guidance**|Chenbin Li et.al.|[2306.11556](http://arxiv.org/abs/2306.11556)|null|
|**2023-06-24**|**MA-NeRF: Motion-Assisted Neural Radiance Fields for Face Synthesis from Sparse Images**|Weichen Zhang et.al.|[2306.10350](http://arxiv.org/abs/2306.10350)|null|
|**2023-06-15**|**Edit-DiffNeRF: Editing 3D Neural Radiance Fields using 2D Diffusion Model**|Lu Yu et.al.|[2306.09551](http://arxiv.org/abs/2306.09551)|null|
|**2023-06-16**|**UrbanIR: Large-Scale Urban Scene Inverse Rendering from a Single Video**|Zhi-Hao Lin et.al.|[2306.09349](http://arxiv.org/abs/2306.09349)|null|
|**2023-06-13**|**DORSal: Diffusion for Object-centric Representations of Scenes $\textit{et al.}$**|Allan Jabri et.al.|[2306.08068](http://arxiv.org/abs/2306.08068)|null|
|**2023-06-13**|**Binary Radiance Fields**|Seungjoo Shin et.al.|[2306.07581](http://arxiv.org/abs/2306.07581)|null|
|**2023-07-10**|**From NeRFLiX to NeRFLiX++: A General NeRF-Agnostic Restorer Paradigm**|Kun Zhou et.al.|[2306.06388](http://arxiv.org/abs/2306.06388)|null|
|**2023-06-15**|**NERFBK: A High-Quality Benchmark for NERF-Based 3D Reconstruction**|Ali Karami et.al.|[2306.06300](http://arxiv.org/abs/2306.06300)|null|
|**2023-06-09**|**HyP-NeRF: Learning Improved NeRF Priors using a HyperNetwork**|Bipasha Sen et.al.|[2306.06093](http://arxiv.org/abs/2306.06093)|null|
|**2023-06-09**|**GANeRF: Leveraging Discriminators to Optimize Neural Radiance Fields**|Barbara Roessle et.al.|[2306.06044](http://arxiv.org/abs/2306.06044)|null|
|**2023-06-09**|**RePaint-NeRF: NeRF Editting via Semantic Masks and Diffusion Models**|Xingchen Zhou et.al.|[2306.05668](http://arxiv.org/abs/2306.05668)|null|
|**2023-06-08**|**LU-NeRF: Scene and Pose Estimation by Synchronizing Local Unposed NeRFs**|Zezhou Cheng et.al.|[2306.05410](http://arxiv.org/abs/2306.05410)|null|
|**2023-06-08**|**Enhance-NeRF: Multiple Performance Evaluation for Neural Radiance Fields**|Qianqiu Tan et.al.|[2306.05303](http://arxiv.org/abs/2306.05303)|**[link](https://github.com/tanqianq/enhance-nerf)**|
|**2023-06-06**|**Towards Visual Foundational Models of Physical Scenes**|Chethan Parameshwara et.al.|[2306.03727](http://arxiv.org/abs/2306.03727)|null|
|**2023-06-06**|**Human 3D Avatar Modeling with Implicit Neural Representation: A Brief Survey**|Mingyang Sun et.al.|[2306.03576](http://arxiv.org/abs/2306.03576)|null|
|**2023-06-05**|**H2-Mapping: Real-time Dense Mapping Using Hierarchical Hybrid Representation**|Chenxing Jiang et.al.|[2306.03207](http://arxiv.org/abs/2306.03207)|**[link](https://github.com/sysu-star/h2-mapping)**|
|**2023-06-05**|**BeyondPixels: A Comprehensive Review of the Evolution of Neural Radiance Fields**|AKM Shahariar Azad Rabby et.al.|[2306.03000](http://arxiv.org/abs/2306.03000)|null|
|**2023-06-05**|**ZIGNeRF: Zero-shot 3D Scene Representation with Invertible Generative Neural Radiance Fields**|Kanghyeok Ko et.al.|[2306.02741](http://arxiv.org/abs/2306.02741)|null|
|**2023-06-01**|**FDNeRF: Semantics-Driven Face Reconstruction, Prompt Editing and Relighting with Diffusion Models**|Hao Zhang et.al.|[2306.00783](http://arxiv.org/abs/2306.00783)|**[link](https://github.com/billyxyb/fdnerf)**|
|**2023-06-01**|**Analyzing the Internals of Neural Radiance Fields**|Lukas Radl et.al.|[2306.00696](http://arxiv.org/abs/2306.00696)|**[link](https://github.com/r4dl/nerfinternals)**|
|**2023-06-02**|**AvatarStudio: Text-driven Editing of 3D Dynamic Human Head Avatars**|Mohit Mendiratta et.al.|[2306.00547](http://arxiv.org/abs/2306.00547)|null|
|**2023-05-30**|**DäRF: Boosting Radiance Fields from Sparse Inputs with Monocular Depth Adaptation**|Jiuhn Song et.al.|[2305.19201](http://arxiv.org/abs/2305.19201)|null|
|**2023-05-30**|**Template-free Articulated Neural Point Clouds for Reposable View Synthesis**|Lukas Uzolas et.al.|[2305.19065](http://arxiv.org/abs/2305.19065)|**[link](https://github.com/lukasuz/articulated-point-nerf)**|
|**2023-05-31**|**HiFA: High-fidelity Text-to-3D with Advanced Diffusion Guidance**|Junzhe Zhu et.al.|[2305.18766](http://arxiv.org/abs/2305.18766)|null|
|**2023-05-31**|**Towards a Robust Framework for NeRF Evaluation**|Adrian Azzarelli et.al.|[2305.18079](http://arxiv.org/abs/2305.18079)|null|
|**2023-05-31**|**Volume Feature Rendering for Fast Neural Radiance Field Reconstruction**|Kang Han et.al.|[2305.17916](http://arxiv.org/abs/2305.17916)|null|
|**2023-06-06**|**PlaNeRF: SVD Unsupervised 3D Plane Regularization for NeRF Large-Scale Scene Reconstruction**|Fusang Wang et.al.|[2305.16914](http://arxiv.org/abs/2305.16914)|null|
|**2023-05-25**|**ZeroAvatar: Zero-shot 3D Avatar Generation from a Single Image**|Zhenzhen Weng et.al.|[2305.16411](http://arxiv.org/abs/2305.16411)|null|
|**2023-05-25**|**Interactive Segment Anything NeRF with Feature Imitation**|Xiaokang Chen et.al.|[2305.16233](http://arxiv.org/abs/2305.16233)|null|
|**2023-05-25**|**ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation**|Zhengyi Wang et.al.|[2305.16213](http://arxiv.org/abs/2305.16213)|**[link](https://github.com/threestudio-project/threestudio)**|
|**2023-05-31**|**Deceptive-NeRF: Enhancing NeRF Reconstruction using Pseudo-Observations from Diffusion Models**|Xinhang Liu et.al.|[2305.15171](http://arxiv.org/abs/2305.15171)|null|
|**2023-05-24**|**InpaintNeRF360: Text-Guided 3D Inpainting on Unbounded Neural Radiance Fields**|Dongqing Wang et.al.|[2305.15094](http://arxiv.org/abs/2305.15094)|null|
|**2023-05-24**|**OD-NeRF: Efficient Training of On-the-Fly Dynamic Neural Radiance Fields**|Zhiwen Yan et.al.|[2305.14831](http://arxiv.org/abs/2305.14831)|null|
|**2023-05-24**|**3D Open-vocabulary Segmentation with Foundation Models**|Kunhao Liu et.al.|[2305.14093](http://arxiv.org/abs/2305.14093)|**[link](https://github.com/kunhao-liu/3d-ovs)**|
|**2023-05-22**|**NeRFuser: Large-Scale Scene Representation by NeRF Fusion**|Jiading Fang et.al.|[2305.13307](http://arxiv.org/abs/2305.13307)|**[link](https://github.com/ripl/nerfuser)**|
|**2023-05-22**|**Registering Neural Radiance Fields as 3D Density Images**|Han Jiang et.al.|[2305.12843](http://arxiv.org/abs/2305.12843)|null|
|**2023-05-19**|**Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields**|Jingbo Zhang et.al.|[2305.11588](http://arxiv.org/abs/2305.11588)|null|
|**2023-05-18**|**MVPSNet: Fast Generalizable Multi-view Photometric Stereo**|Dongxu Zhao et.al.|[2305.11167](http://arxiv.org/abs/2305.11167)|null|
|**2023-05-18**|**ConsistentNeRF: Enhancing Neural Radiance Fields with 3D Consistency for Sparse View Synthesis**|Shoukang Hu et.al.|[2305.11031](http://arxiv.org/abs/2305.11031)|**[link](https://github.com/skhu101/consistentnerf)**|
|**2023-05-17**|**MultiPlaneNeRF: Neural Radiance Field with Non-Trainable Representation**|Dominik Zimny et.al.|[2305.10579](http://arxiv.org/abs/2305.10579)|**[link](https://github.com/gmum/multiplanenerf)**|
|**2023-05-24**|**OR-NeRF: Object Removing from 3D Scenes Guided by Multiview Segmentation with Neural Radiance Fields**|Youtan Yin et.al.|[2305.10503](http://arxiv.org/abs/2305.10503)|**[link](https://github.com/cuteyyt/or-nerf)**|
|**2023-05-16**|**NerfBridge: Bringing Real-time, Online Neural Radiance Field Training to Robotics**|Javier Yu et.al.|[2305.09761](http://arxiv.org/abs/2305.09761)|**[link](https://github.com/javieryu/nerf_bridge)**|
|**2023-05-15**|**MV-Map: Offboard HD-Map Generation with Multi-view Consistency**|Ziyang Xie et.al.|[2305.08851](http://arxiv.org/abs/2305.08851)|**[link](https://github.com/ziyang-xie/mv-map)**|
|**2023-05-12**|**BundleRecon: Ray Bundle-Based 3D Neural Reconstruction**|Weikun Zhang et.al.|[2305.07342](http://arxiv.org/abs/2305.07342)|null|
|**2023-05-10**|**Generative AI meets 3D: A Survey on Text-to-3D in AIGC Era**|Chenghao Li et.al.|[2305.06131](http://arxiv.org/abs/2305.06131)|null|
|**2023-05-10**|**NeRF $^\textbf{2}$ : Neural Radio-Frequency Radiance Fields**|Xiaopeng Zhao et.al.|[2305.06118](http://arxiv.org/abs/2305.06118)|null|
|**2023-05-09**|**Instant-NeRF: Instant On-Device Neural Radiance Field Training via Algorithm-Accelerator Co-Designed Near-Memory Processing**|Yang Zhao et.al.|[2305.05766](http://arxiv.org/abs/2305.05766)|null|
|**2023-05-09**|**PET-NeuS: Positional Encoding Tri-Planes for Neural Surfaces**|Yiqun Wang et.al.|[2305.05594](http://arxiv.org/abs/2305.05594)|**[link](https://github.com/yiqun-wang/pet-neus)**|
|**2023-05-08**|**NerfAcc: Efficient Sampling Accelerates NeRFs**|Ruilong Li et.al.|[2305.04966](http://arxiv.org/abs/2305.04966)|null|
|**2023-05-08**|**AvatarReX: Real-time Expressive Full-body Avatars**|Zerong Zheng et.al.|[2305.04789](http://arxiv.org/abs/2305.04789)|null|
|**2023-05-07**|**HashCC: Lightweight Method to Improve the Quality of the Camera-less NeRF Scene Generation**|Jan Olszewski et.al.|[2305.04296](http://arxiv.org/abs/2305.04296)|null|
|**2023-05-07**|**Multi-Space Neural Radiance Fields**|Ze-Xin Yin et.al.|[2305.04268](http://arxiv.org/abs/2305.04268)|null|
|**2023-05-04**|**NeRF-QA: Neural Radiance Fields Quality Assessment Database**|Pedro Martin et.al.|[2305.03176](http://arxiv.org/abs/2305.03176)|null|
|**2023-05-04**|**NeuralEditor: Editing Neural Radiance Fields via Manipulating Point Clouds**|Jun-Kun Chen et.al.|[2305.03049](http://arxiv.org/abs/2305.03049)|null|
|**2023-05-04**|**Radiance Field Gradient Scaling for Unbiased Near-Camera Training**|Julien Philip et.al.|[2305.02756](http://arxiv.org/abs/2305.02756)|**[link](https://github.com/gradient-scaling/gradient-scaling.github.io)**|
|**2023-05-04**|**Semantic-aware Generation of Multi-view Portrait Drawings**|Biao Ma et.al.|[2305.02618](http://arxiv.org/abs/2305.02618)|**[link](https://github.com/aiart-hdu/sage)**|
|**2023-05-02**|**Neural LiDAR Fields for Novel View Synthesis**|Shengyu Huang et.al.|[2305.01643](http://arxiv.org/abs/2305.01643)|null|
|**2023-05-03**|**LatentAvatar: Learning Latent Expression Code for Expressive Neural Head Avatar**|Yuelang Xu et.al.|[2305.01190](http://arxiv.org/abs/2305.01190)|null|
|**2023-05-02**|**Federated Neural Radiance Fields**|Lachlan Holden et.al.|[2305.01163](http://arxiv.org/abs/2305.01163)|null|
|**2023-05-01**|**GeneFace++: Generalized and Stable Real-Time Audio-Driven 3D Talking Face Generation**|Zhenhui Ye et.al.|[2305.00787](http://arxiv.org/abs/2305.00787)|null|
|**2023-04-30**|**Neural Radiance Fields (NeRFs): A Review and Some Recent Developments**|Mohamed Debbagh et.al.|[2305.00375](http://arxiv.org/abs/2305.00375)|null|
|**2023-04-28**|**ViP-NeRF: Visibility Prior for Sparse Input Neural Radiance Fields**|Nagabhushan Somraj et.al.|[2305.00041](http://arxiv.org/abs/2305.00041)|**[link](https://github.com/NagabhushanSN95/ViP-NeRF)**|
|**2023-04-28**|**NeRF-LiDAR: Generating Realistic LiDAR Point Clouds with Neural Radiance Fields**|Junge Zhang et.al.|[2304.14811](http://arxiv.org/abs/2304.14811)|null|
|**2023-04-27**|**Learning a Diffusion Prior for NeRFs**|Guandao Yang et.al.|[2304.14473](http://arxiv.org/abs/2304.14473)|null|
|**2023-04-27**|**ActorsNeRF: Animatable Few-shot Human Rendering with Generalizable NeRFs**|Jiteng Mu et.al.|[2304.14401](http://arxiv.org/abs/2304.14401)|null|
|**2023-05-03**|**Combining HoloLens with Instant-NeRFs: Advanced Real-Time 3D Mobile Mapping**|Dennis Haitz et.al.|[2304.14301](http://arxiv.org/abs/2304.14301)|null|
|**2023-04-27**|**Compositional 3D Human-Object Neural Animation**|Zhi Hou et.al.|[2304.14070](http://arxiv.org/abs/2304.14070)|null|
|**2023-04-26**|**Super-NeRF: View-consistent Detail Generation for NeRF super-resolution**|Yuqi Han et.al.|[2304.13518](http://arxiv.org/abs/2304.13518)|null|
|**2023-04-26**|**VGOS: Voxel Grid Optimization for View Synthesis from Sparse Inputs**|Jiakai Sun et.al.|[2304.13386](http://arxiv.org/abs/2304.13386)|**[link](https://github.com/sjojok/vgos)**|
|**2023-04-25**|**Local Implicit Ray Function for Generalizable Radiance Field Representation**|Xin Huang et.al.|[2304.12746](http://arxiv.org/abs/2304.12746)|null|
|**2023-04-27**|**MF-NeRF: Memory Efficient NeRF with Mixed-Feature Hash Table**|Yongjae Lee et.al.|[2304.12587](http://arxiv.org/abs/2304.12587)|**[link](https://github.com/nfyfamr/mf-nerf)**|
|**2023-04-24**|**Instant-3D: Instant Neural Radiance Field Training Towards On-Device AR/VR 3D Reconstruction**|Sixu Li et.al.|[2304.12467](http://arxiv.org/abs/2304.12467)|null|
|**2023-04-24**|**TextMesh: Generation of Realistic 3D Meshes From Text Prompts**|Christina Tsalicoglou et.al.|[2304.12439](http://arxiv.org/abs/2304.12439)|null|
|**2023-04-26**|**Segment Anything in 3D with NeRFs**|Jiazhong Cen et.al.|[2304.12308](http://arxiv.org/abs/2304.12308)|null|
|**2023-04-24**|**Explicit Correspondence Matching for Generalizable Neural Radiance Fields**|Yuedong Chen et.al.|[2304.12294](http://arxiv.org/abs/2304.12294)|**[link](https://github.com/donydchen/matchnerf)**|
|**2023-04-25**|**Gen-NeRF: Efficient and Generalizable Neural Radiance Fields via Algorithm-Hardware Co-Design**|Yonggan Fu et.al.|[2304.11842](http://arxiv.org/abs/2304.11842)|null|
|**2023-04-20**|**Learning Neural Duplex Radiance Fields for Real-Time View Synthesis**|Ziyu Wan et.al.|[2304.10537](http://arxiv.org/abs/2304.10537)|null|
|**2023-04-20**|**Nerfbusters: Removing Ghostly Artifacts from Casually Captured NeRFs**|Frederik Warburg et.al.|[2304.10532](http://arxiv.org/abs/2304.10532)|**[link](https://github.com/ethanweber/nerfbusters)**|
|**2023-04-20**|**ReLight My NeRF: A Dataset for Novel View Synthesis and Relighting of Real World Objects**|Marco Toschi et.al.|[2304.10448](http://arxiv.org/abs/2304.10448)|null|
|**2023-04-20**|**LiDAR-NeRF: Novel LiDAR View Synthesis via Neural Radiance Fields**|Tang Tao et.al.|[2304.10406](http://arxiv.org/abs/2304.10406)|null|
|**2023-04-20**|**Revisiting Implicit Neural Representations in Low-Level Vision**|Wentian Xu et.al.|[2304.10250](http://arxiv.org/abs/2304.10250)|**[link](https://github.com/wentxul/linr)**|
|**2023-04-20**|**Multiscale Representation for Real-Time Anti-Aliasing Neural Rendering**|Dongting Hu et.al.|[2304.10075](http://arxiv.org/abs/2304.10075)|null|
|**2023-04-20**|**Neural Radiance Fields: Past, Present, and Future**|Ansh Mittal et.al.|[2304.10050](http://arxiv.org/abs/2304.10050)|null|
|**2023-04-19**|**Tetra-NeRF: Representing Neural Radiance Fields Using Tetrahedra**|Jonas Kulhanek et.al.|[2304.09987](http://arxiv.org/abs/2304.09987)|**[link](https://github.com/jkulhanek/tetra-nerf)**|
|**2023-04-20**|**Reference-guided Controllable Inpainting of Neural Radiance Fields**|Ashkan Mirzaei et.al.|[2304.09677](http://arxiv.org/abs/2304.09677)|null|
|**2023-04-18**|**SurfelNeRF: Neural Surfel Radiance Fields for Online Photorealistic Reconstruction of Indoor Scenes**|Yiming Gao et.al.|[2304.08971](http://arxiv.org/abs/2304.08971)|null|
|**2023-04-18**|**NeAI: A Pre-convoluted Representation for Plug-and-Play Neural Ambient Illumination**|Yiyu Zhuang et.al.|[2304.08757](http://arxiv.org/abs/2304.08757)|null|
|**2023-04-17**|**MoDA: Modeling Deformable 3D Objects from Casual Videos**|Chaoyue Song et.al.|[2304.08279](http://arxiv.org/abs/2304.08279)|**[link](https://github.com/chaoyuesong/moda)**|
|**2023-04-17**|**NeRF-Loc: Visual Localization with Conditional Neural Radiance Field**|Jianlin Liu et.al.|[2304.07979](http://arxiv.org/abs/2304.07979)|**[link](https://github.com/jenningsl/nerf-loc)**|
|**2023-04-16**|**Likelihood-Based Generative Radiance Field with Latent Space Energy-Based Model for 3D-Aware Disentangled Image Representation**|Yaxuan Zhu et.al.|[2304.07918](http://arxiv.org/abs/2304.07918)|null|
|**2023-04-16**|**CAT-NeRF: Constancy-Aware Tx $^2$ Former for Dynamic Body Modeling**|Haidong Zhu et.al.|[2304.07915](http://arxiv.org/abs/2304.07915)|**[link](https://github.com/haidongz-usc/CAT-NeRF)**|
|**2023-04-16**|**SeaThru-NeRF: Neural Radiance Fields in Scattering Media**|Deborah Levy et.al.|[2304.07743](http://arxiv.org/abs/2304.07743)|null|
|**2023-04-14**|**UVA: Towards Unified Volumetric Avatar for View Synthesis, Pose rendering, Geometry and Texture Editing**|Jinlong Fan et.al.|[2304.06969](http://arxiv.org/abs/2304.06969)|null|
|**2023-04-17**|**Single-Stage Diffusion NeRF: A Unified Approach to 3D Generation and Reconstruction**|Hansheng Chen et.al.|[2304.06714](http://arxiv.org/abs/2304.06714)|null|
|**2023-04-13**|**Zip-NeRF: Anti-Aliased Grid-Based Neural Radiance Fields**|Jonathan T. Barron et.al.|[2304.06706](http://arxiv.org/abs/2304.06706)|null|
|**2023-04-13**|**NeRFVS: Neural Radiance Fields for Free View Synthesis via Geometry Scaffolds**|Chen Yang et.al.|[2304.06287](http://arxiv.org/abs/2304.06287)|null|
|**2023-04-12**|**NutritionVerse-Thin: An Optimized Strategy for Enabling Improved Rendering of 3D Thin Food Models**|Chi-en Amy Tai et.al.|[2304.05620](http://arxiv.org/abs/2304.05620)|null|
|**2023-04-11**|**Improving Neural Radiance Fields with Depth-aware Optimization for Novel View Synthesis**|Shu Chen et.al.|[2304.05218](http://arxiv.org/abs/2304.05218)|**[link](https://github.com/xtu-pr-lab/sfmnerf)**|
|**2023-04-11**|**One-Shot High-Fidelity Talking-Head Synthesis with Deformable Neural Radiance Field**|Weichuang Li et.al.|[2304.05097](http://arxiv.org/abs/2304.05097)|null|
|**2023-04-11**|**MRVM-NeRF: Mask-Based Pretraining for Neural Radiance Fields**|Ganlin Yang et.al.|[2304.04962](http://arxiv.org/abs/2304.04962)|null|
|**2023-04-10**|**Neural Image-based Avatars: Generalizable Radiance Fields for Human Avatar Modeling**|Youngjoong Kwon et.al.|[2304.04897](http://arxiv.org/abs/2304.04897)|null|
|**2023-04-07**|**Event-based Camera Tracker by $\nabla$ t NeRF**|Mana Masuda et.al.|[2304.04559](http://arxiv.org/abs/2304.04559)|null|
|**2023-04-10**|**Neural Residual Radiance Fields for Streamably Free-Viewpoint Videos**|Liao Wang et.al.|[2304.04452](http://arxiv.org/abs/2304.04452)|null|
|**2023-04-10**|**Inferring Fluid Dynamics via Inverse Rendering**|Jinxian Liu et.al.|[2304.04446](http://arxiv.org/abs/2304.04446)|null|
|**2023-04-10**|**Instance Neural Radiance Field**|Benran Hu et.al.|[2304.04395](http://arxiv.org/abs/2304.04395)|null|
|**2023-04-12**|**NeRF applied to satellite imagery for surface reconstruction**|Federico Semeraro et.al.|[2304.04133](http://arxiv.org/abs/2304.04133)|**[link](https://github.com/fsemerar/satnerf)**|
|**2023-04-08**|**PVD-AL: Progressive Volume Distillation with Active Learning for Efficient Conversion Between Different NeRF Architectures**|Shuangkang Fang et.al.|[2304.04012](http://arxiv.org/abs/2304.04012)|null|
|**2023-04-07**|**Lift3D: Synthesize 3D Training Data by Lifting 2D GAN to 3D Generative Radiance Field**|Leheng Li et.al.|[2304.03526](http://arxiv.org/abs/2304.03526)|null|
|**2023-04-06**|**Beyond NeRF Underwater: Learning Neural Reflectance Fields for True Color Correction of Marine Imagery**|Tianyi Zhang et.al.|[2304.03384](http://arxiv.org/abs/2304.03384)|null|
|**2023-04-06**|**LANe: Lighting-Aware Neural Fields for Compositional Scene Synthesis**|Akshay Krishnan et.al.|[2304.03280](http://arxiv.org/abs/2304.03280)|null|
|**2023-04-06**|**Neural Fields meet Explicit Geometric Representation for Inverse Rendering of Urban Scenes**|Zian Wang et.al.|[2304.03266](http://arxiv.org/abs/2304.03266)|null|
|**2023-04-06**|**DITTO-NeRF: Diffusion-based Iterative Text To Omni-directional 3D Model**|Hoigi Seo et.al.|[2304.02827](http://arxiv.org/abs/2304.02827)|null|
|**2023-04-05**|**Image Stabilization for Hololens Camera in Remote Collaboration**|Gowtham Senthil et.al.|[2304.02736](http://arxiv.org/abs/2304.02736)|null|
|**2023-04-04**|**Generating Continual Human Motion in Diverse 3D Scenes**|Aymen Mir et.al.|[2304.02061](http://arxiv.org/abs/2304.02061)|null|
|**2023-04-04**|**MonoHuman: Animatable Human Neural Field from Monocular Video**|Zhengming Yu et.al.|[2304.02001](http://arxiv.org/abs/2304.02001)|null|
|**2023-04-06**|**DreamAvatar: Text-and-Shape Guided 3D Human Avatar Generation via Diffusion Models**|Yukang Cao et.al.|[2304.00916](http://arxiv.org/abs/2304.00916)|null|
|**2023-04-01**|**JacobiNeRF: NeRF Shaping with Mutual Information Gradients**|Xiaomeng Xu et.al.|[2304.00341](http://arxiv.org/abs/2304.00341)|**[link](https://github.com/xxm19/jacobinerf)**|
|**2023-03-31**|**VDN-NeRF: Resolving Shape-Radiance Ambiguity via View-Dependence Normalization**|Bingfan Zhu et.al.|[2303.17968](http://arxiv.org/abs/2303.17968)|null|
|**2023-03-30**|**NeRF-Supervised Deep Stereo**|Fabio Tosi et.al.|[2303.17603](http://arxiv.org/abs/2303.17603)|**[link](https://github.com/fabiotosi92/nerf-supervised-deep-stereo)**|
|**2023-03-30**|**SynBody: Synthetic Dataset with Layered Human Models for 3D Human Perception and Modeling**|Zhitao Yang et.al.|[2303.17368](http://arxiv.org/abs/2303.17368)|null|
|**2023-03-30**|**NeILF++: Inter-Reflectable Light Fields for Geometry and Material Estimation**|Jingyang Zhang et.al.|[2303.17147](http://arxiv.org/abs/2303.17147)|null|
|**2023-03-30**|**Enhanced Stable View Synthesis**|Nishant Jain et.al.|[2303.17094](http://arxiv.org/abs/2303.17094)|null|
|**2023-03-29**|**TriVol: Point Cloud Rendering via Triple Volumes**|Tao Hu et.al.|[2303.16485](http://arxiv.org/abs/2303.16485)|**[link](https://github.com/dvlab-research/trivol)**|
|**2023-03-29**|**Point2Pix: Photo-Realistic Point Cloud Rendering via Neural Radiance Fields**|Tao Hu et.al.|[2303.16482](http://arxiv.org/abs/2303.16482)|null|
|**2023-03-28**|**Flow supervision for Deformable NeRF**|Chaoyang Wang et.al.|[2303.16333](http://arxiv.org/abs/2303.16333)|null|
|**2023-03-28**|**SparseNeRF: Distilling Depth Ranking for Few-shot Novel View Synthesis**|Guangcong Wang et.al.|[2303.16196](http://arxiv.org/abs/2303.16196)|null|
|**2023-03-28**|**VMesh: Hybrid Volume-Mesh Representation for Efficient View Synthesis**|Yuan-Chen Guo et.al.|[2303.16184](http://arxiv.org/abs/2303.16184)|null|
|**2023-03-30**|**Adaptive Voronoi NeRFs**|Tim Elsner et.al.|[2303.16001](http://arxiv.org/abs/2303.16001)|null|
|**2023-03-28**|**F $^{2}$ -NeRF: Fast Neural Radiance Field Training with Free Camera Trajectories**|Peng Wang et.al.|[2303.15951](http://arxiv.org/abs/2303.15951)|null|
|**2023-03-27**|**JAWS: Just A Wild Shot for Cinematic Transfer in Neural Radiance Fields**|Xi Wang et.al.|[2303.15427](http://arxiv.org/abs/2303.15427)|null|
|**2023-03-27**|**Generalizable Neural Voxels for Fast Human Radiance Fields**|Taoran Yi et.al.|[2303.15387](http://arxiv.org/abs/2303.15387)|null|
|**2023-03-27**|**NeUDF: Learning Unsigned Distance Fields from Multi-view Images for Reconstructing Non-watertight Models**|Fei Hou et.al.|[2303.15368](http://arxiv.org/abs/2303.15368)|null|
|**2023-03-27**|**3D-Aware Multi-Class Image-to-Image Translation with NeRFs**|Senmao Li et.al.|[2303.15012](http://arxiv.org/abs/2303.15012)|**[link](https://github.com/sen-mao/3di2i-translation)**|
|**2023-03-26**|**Clean-NeRF: Reformulating NeRF to account for View-Dependent Observations**|Xinhang Liu et.al.|[2303.14707](http://arxiv.org/abs/2303.14707)|null|
|**2023-03-25**|**SUDS: Scalable Urban Dynamic Scenes**|Haithem Turki et.al.|[2303.14536](http://arxiv.org/abs/2303.14536)|null|
|**2023-03-25**|**DBARF: Deep Bundle-Adjusting Generalizable Neural Radiance Fields**|Yu Chen et.al.|[2303.14478](http://arxiv.org/abs/2303.14478)|null|
|**2023-03-25**|**NeRF-DS: Neural Radiance Fields for Dynamic Specular Objects**|Zhiwen Yan et.al.|[2303.14435](http://arxiv.org/abs/2303.14435)|**[link](https://github.com/jokeryan/nerf-ds)**|
|**2023-03-24**|**Grid-guided Neural Radiance Fields for Large Urban Scenes**|Linning Xu et.al.|[2303.14001](http://arxiv.org/abs/2303.14001)|null|
|**2023-03-23**|**TriPlaneNet: An Encoder for EG3D Inversion**|Ananta R. Bhattarai et.al.|[2303.13497](http://arxiv.org/abs/2303.13497)|null|
|**2023-03-23**|**Plotting Behind the Scenes: Towards Learnable Game Engines**|Willi Menapace et.al.|[2303.13472](http://arxiv.org/abs/2303.13472)|null|
|**2023-03-23**|**Set-the-Scene: Global-Local Training for Generating Controllable NeRF Scenes**|Dana Cohen-Bar et.al.|[2303.13450](http://arxiv.org/abs/2303.13450)|null|
|**2023-03-23**|**SINE: Semantic-driven Image-based NeRF Editing with Prior-guided Editing Field**|Chong Bao et.al.|[2303.13277](http://arxiv.org/abs/2303.13277)|null|
|**2023-03-23**|**Transforming Radiance Field with Lipschitz Network for Photorealistic 3D Scene Stylization**|Zicheng Zhang et.al.|[2303.13232](http://arxiv.org/abs/2303.13232)|null|
|**2023-03-23**|**Semantic Ray: Learning a Generalizable Semantic Field with Cross-Reprojection Attention**|Fangfu Liu et.al.|[2303.13014](http://arxiv.org/abs/2303.13014)|null|
|**2023-03-22**|**NeRF-GAN Distillation for Efficient 3D-Aware Generation with Convolutions**|Mohamad Shahbazi et.al.|[2303.12865](http://arxiv.org/abs/2303.12865)|null|
|**2023-03-22**|**SHERF: Generalizable Human NeRF from a Single Image**|Shoukang Hu et.al.|[2303.12791](http://arxiv.org/abs/2303.12791)|**[link](https://github.com/skhu101/sherf)**|
|**2023-03-22**|**Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions**|Ayaan Haque et.al.|[2303.12789](http://arxiv.org/abs/2303.12789)|null|
|**2023-03-22**|**FeatureNeRF: Learning Generalizable NeRFs by Distilling Foundation Models**|Jianglong Ye et.al.|[2303.12786](http://arxiv.org/abs/2303.12786)|null|
|**2023-03-24**|**Balanced Spherical Grid for Egocentric View Synthesis**|Changwoon Choi et.al.|[2303.12408](http://arxiv.org/abs/2303.12408)|**[link](https://github.com/changwoonchoi/EgoNeRF)**|
|**2023-03-21**|**Pre-NeRF 360: Enriching Unbounded Appearances for Neural Radiance Fields**|Ahmad AlMughrabi et.al.|[2303.12234](http://arxiv.org/abs/2303.12234)|null|
|**2023-03-21**|**3D-CLFusion: Fast Text-to-3D Rendering with Contrastive Latent Diffusion**|Yu-Jhe Li et.al.|[2303.11938](http://arxiv.org/abs/2303.11938)|null|
|**2023-03-22**|**ExtremeNeRF: Few-shot Neural Radiance Fields Under Unconstrained Illumination**|SeokYeong Lee et.al.|[2303.11728](http://arxiv.org/abs/2303.11728)|null|
|**2023-03-20**|**DehazeNeRF: Multiple Image Haze Removal and 3D Shape Reconstruction using Neural Radiance Fields**|Wei-Ting Chen et.al.|[2303.11364](http://arxiv.org/abs/2303.11364)|null|
|**2023-03-20**|**ContraNeRF: Generalizable Neural Radiance Fields for Synthetic-to-real Novel View Synthesis via Contrastive Learning**|Hao Yang et.al.|[2303.11052](http://arxiv.org/abs/2303.11052)|null|
|**2023-03-19**|**SKED: Sketch-guided Text-based 3D Editing**|Aryan Mikaeili et.al.|[2303.10735](http://arxiv.org/abs/2303.10735)|null|
|**2023-03-19**|**NeRF-LOAM: Neural Implicit Representation for Large-Scale Incremental LiDAR Odometry and Mapping**|Junyuan Deng et.al.|[2303.10709](http://arxiv.org/abs/2303.10709)|**[link](https://github.com/junyuandeng/nerf-loam)**|
|**2023-03-18**|**3D Data Augmentation for Driving Scenes on Camera**|Wenwen Tong et.al.|[2303.10340](http://arxiv.org/abs/2303.10340)|null|
|**2023-03-17**|**$α$ Surf: Implicit Surface Reconstruction for Semi-Transparent and Thin Objects with Decoupled Geometry and Opacity**|Tianhao Wu et.al.|[2303.10083](http://arxiv.org/abs/2303.10083)|null|
|**2023-03-17**|**Single-view Neural Radiance Fields with Depth Teacher**|Yurui Chen et.al.|[2303.09952](http://arxiv.org/abs/2303.09952)|null|
|**2023-03-21**|**PartNeRF: Generating Part-Aware Editable 3D Shapes without 3D Supervision**|Konstantinos Tertikas et.al.|[2303.09554](http://arxiv.org/abs/2303.09554)|null|
|**2023-03-16**|**LERF: Language Embedded Radiance Fields**|Justin Kerr et.al.|[2303.09553](http://arxiv.org/abs/2303.09553)|null|
|**2023-03-16**|**NeRFMeshing: Distilling Neural Radiance Fields into Geometrically-Accurate 3D Meshes**|Marie-Julie Rakotosaona et.al.|[2303.09431](http://arxiv.org/abs/2303.09431)|null|
|**2023-03-17**|**NeRFtrinsic Four: An End-To-End Trainable NeRF Jointly Optimizing Diverse Intrinsic and Extrinsic Camera Parameters**|Hannah Schieber et.al.|[2303.09412](http://arxiv.org/abs/2303.09412)|**[link](https://github.com/hannahhaensen/nerftrinsic_four)**|
|**2023-03-16**|**Reliable Image Dehazing by NeRF**|Zheyan Jin et.al.|[2303.09153](http://arxiv.org/abs/2303.09153)|null|
|**2023-03-15**|**Mesh Strikes Back: Fast and Efficient Human Reconstruction from RGB videos**|Rohit Jena et.al.|[2303.08808](http://arxiv.org/abs/2303.08808)|null|
|**2023-03-15**|**Re-ReND: Real-time Rendering of NeRFs across Devices**|Sara Rojas et.al.|[2303.08717](http://arxiv.org/abs/2303.08717)|null|
|**2023-03-15**|**RefiNeRF: Modelling dynamic neural radiance fields with inconsistent or missing camera parameters**|Shuja Khalid et.al.|[2303.08695](http://arxiv.org/abs/2303.08695)|null|
|**2023-03-15**|**Harnessing Low-Frequency Neural Fields for Few-Shot View Synthesis**|Liangchen Song et.al.|[2303.08370](http://arxiv.org/abs/2303.08370)|**[link](https://github.com/lsongx/halo)**|
|**2023-03-14**|**MELON: NeRF with Unposed Images Using Equivalence Class Estimation**|Axel Levy et.al.|[2303.08096](http://arxiv.org/abs/2303.08096)|null|
|**2023-03-16**|**Let 2D Diffusion Model Know 3D-Consistency for Robust Text-to-3D Generation**|Junyoung Seo et.al.|[2303.07937](http://arxiv.org/abs/2303.07937)|null|
|**2023-03-16**|**NEF: Neural Edge Fields for 3D Parametric Curve Reconstruction from Multi-view Images**|Yunfan Ye et.al.|[2303.07653](http://arxiv.org/abs/2303.07653)|null|
|**2023-03-14**|**Frequency-Modulated Point Cloud Rendering with Easy Editing**|Yi Zhang et.al.|[2303.07596](http://arxiv.org/abs/2303.07596)|**[link](https://github.com/yizhangphd/freqpcr)**|
|**2023-03-13**|**FreeNeRF: Improving Few-shot Neural Rendering with Free Frequency Regularization**|Jiawei Yang et.al.|[2303.07418](http://arxiv.org/abs/2303.07418)|**[link](https://github.com/jiawei-yang/freenerf)**|
|**2023-03-13**|**NeRFLiX: High-Quality Neural View Synthesis by Learning a Degradation-Driven Inter-viewpoint MiXer**|Kun Zhou et.al.|[2303.06919](http://arxiv.org/abs/2303.06919)|null|
|**2023-03-11**|**Just Flip: Flipped Observation Generation and Optimization for Neural Radiance Fields to Cover Unobserved View**|Minjae Lee et.al.|[2303.06335](http://arxiv.org/abs/2303.06335)|**[link](https://github.com/minjae-lulu/just-flip)**|
|**2023-03-10**|**NeRFlame: FLAME-based conditioning of NeRF for 3D face rendering**|Wojciech Zając et.al.|[2303.06226](http://arxiv.org/abs/2303.06226)|**[link](https://github.com/wojtekz4/nerflame)**|
|**2023-03-10**|**You Only Train Once: Multi-Identity Free-Viewpoint Neural Human Rendering from Monocular Videos**|Jaehyeok Kim et.al.|[2303.05835](http://arxiv.org/abs/2303.05835)|null|
|**2023-03-10**|**Aleth-NeRF: Low-light Condition View Synthesis with Concealing Fields**|Ziteng Cui et.al.|[2303.05807](http://arxiv.org/abs/2303.05807)|null|
|**2023-03-10**|**Self-NeRF: A Self-Training Pipeline for Few-Shot Neural Radiance Fields**|Jiayang Bai et.al.|[2303.05775](http://arxiv.org/abs/2303.05775)|null|
|**2023-03-14**|**Hardware Acceleration of Neural Graphics**|Muhammad Husnain Mubarik et.al.|[2303.05735](http://arxiv.org/abs/2303.05735)|null|
|**2023-03-10**|**MovingParts: Motion-based 3D Part Discovery in Dynamic Radiance Field**|Kaizhi Yang et.al.|[2303.05703](http://arxiv.org/abs/2303.05703)|null|
|**2023-03-09**|**PAC-NeRF: Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification**|Xuan Li et.al.|[2303.05512](http://arxiv.org/abs/2303.05512)|null|
|**2023-03-08**|**FastSurf: Fast Neural RGB-D Surface Reconstruction using Per-Frame Intrinsic Refinement and TSDF Fusion Prior Learning**|Seunghwan Lee et.al.|[2303.04508](http://arxiv.org/abs/2303.04508)|**[link](https://github.com/ROKIT-Healthcare/FastSurf)**|
|**2023-03-08**|**DroNeRF: Real-time Multi-agent Drone Pose Optimization for Computing Neural Radiance Fields**|Dipam Patel et.al.|[2303.04322](http://arxiv.org/abs/2303.04322)|null|
|**2023-03-07**|**NEPHELE: A Neural Platform for Highly Realistic Cloud Radiance Rendering**|Haimin Luo et.al.|[2303.04086](http://arxiv.org/abs/2303.04086)|null|
|**2023-03-05**|**Semantic-aware Occlusion Filtering Neural Radiance Fields in the Wild**|Jaewon Lee et.al.|[2303.03966](http://arxiv.org/abs/2303.03966)|null|
|**2023-03-07**|**Multiscale Tensor Decomposition and Rendering Equation Encoding for View Synthesis**|Kang Han et.al.|[2303.03808](http://arxiv.org/abs/2303.03808)|null|
|**2023-03-10**|**Nerflets: Local Radiance Fields for Efficient Structure-Aware 3D Scene Representation from 2D Supervision**|Xiaoshuai Zhang et.al.|[2303.03361](http://arxiv.org/abs/2303.03361)|null|
|**2023-03-07**|**Efficient Large-scale Scene Representation with a Hybrid of High-resolution Grid and Plane Features**|Yuqi Zhang et.al.|[2303.03003](http://arxiv.org/abs/2303.03003)|**[link](https://github.com/zyqz97/gp-nerf)**|
|**2023-03-03**|**Delicate Textured Mesh Recovery from NeRF via Adaptive Surface Refinement**|Jiaxiang Tang et.al.|[2303.02091](http://arxiv.org/abs/2303.02091)|null|
|**2023-03-03**|**Multi-Plane Neural Radiance Fields for Novel View Synthesis**|Youssef Abdelkareem et.al.|[2303.01736](http://arxiv.org/abs/2303.01736)|null|
|**2023-03-01**|**S-NeRF: Neural Radiance Fields for Street Views**|Ziyang Xie et.al.|[2303.00749](http://arxiv.org/abs/2303.00749)|null|
|**2023-02-28**|**IntrinsicNGP: Intrinsic Coordinate based Hash Encoding for Human NeRF**|Bo Peng et.al.|[2302.14683](http://arxiv.org/abs/2302.14683)|null|
|**2023-02-27**|**BaLi-RF: Bandlimited Radiance Fields for Dynamic Scene Modeling**|Sameera Ramasinghe et.al.|[2302.13543](http://arxiv.org/abs/2302.13543)|null|
|**2023-02-26**|**Efficient physics-informed neural networks using hash encoding**|Xinquan Huang et.al.|[2302.13397](http://arxiv.org/abs/2302.13397)|null|
|**2023-02-24**|**CATNIPS: Collision Avoidance Through Neural Implicit Probabilistic Scenes**|Timothy Chen et.al.|[2302.12931](http://arxiv.org/abs/2302.12931)|null|
|**2023-02-24**|**Learning Neural Volumetric Representations of Dynamic Humans in Minutes**|Chen Geng et.al.|[2302.12237](http://arxiv.org/abs/2302.12237)|null|
|**2023-02-23**|**DiffusioNeRF: Regularizing Neural Radiance Fields with Denoising Diffusion Models**|Jamie Wynn et.al.|[2302.12231](http://arxiv.org/abs/2302.12231)|null|
|**2023-02-20**|**NerfDiff: Single-image View Synthesis with NeRF-guided Distillation from 3D-aware Diffusion**|Jiatao Gu et.al.|[2302.10109](http://arxiv.org/abs/2302.10109)|null|
|**2023-02-19**|**LC-NeRF: Local Controllable Face Generation in Neural Randiance Field**|Wenyang Zhou et.al.|[2302.09486](http://arxiv.org/abs/2302.09486)|null|
|**2023-02-17**|**MixNeRF: Modeling a Ray with Mixture Density for Novel View Synthesis from Sparse Inputs**|Seunghyeon Seo et.al.|[2302.08788](http://arxiv.org/abs/2302.08788)|null|
|**2023-02-14**|**VQ3D: Learning a 3D-Aware Generative Model on ImageNet**|Kyle Sargent et.al.|[2302.06833v1](http://arxiv.org/abs/2302.06833v1)|null|
|**2023-02-13**|**3D-aware Blending with Generative NeRFs**|Hyunsu Kim et.al.|[2302.06608v1](http://arxiv.org/abs/2302.06608v1)|null|
|**2023-02-11**|**3D Colored Shape Reconstruction from a Single RGB Image through Diffusion**|Bo Li et.al.|[2302.05573v1](http://arxiv.org/abs/2302.05573v1)|null|
|**2023-02-08**|**Nerfstudio: A Modular Framework for Neural Radiance Field Development**|Matthew Tancik et.al.|[2302.04264v1](http://arxiv.org/abs/2302.04264v1)|null|
|**2023-02-07**|**AV-NeRF: Learning Neural Fields for Real-World Audio-Visual Scene Synthesis**|Susan Liang et.al.|[2302.02088v2](http://arxiv.org/abs/2302.02088v2)|null|
|**2023-02-03**|**Semantic 3D-aware Portrait Synthesis and Manipulation Based on Compositional Neural Radiance Field**|Tianxiang Ma et.al.|[2302.01579v1](http://arxiv.org/abs/2302.01579v1)|null|
|**2023-02-03**|**Robust Camera Pose Refinement for Multi-Resolution Hash Encoding**|Hwan Heo et.al.|[2302.01571v1](http://arxiv.org/abs/2302.01571v1)|null|
|**2023-02-03**|**INV: Towards Streaming Incremental Neural Videos**|Shengze Wang et.al.|[2302.01532v1](http://arxiv.org/abs/2302.01532v1)|null|
|**2023-02-02**|**Factor Fields: A Unified Framework for Neural Fields and Beyond**|Anpei Chen et.al.|[2302.01226v1](http://arxiv.org/abs/2302.01226v1)|null|
|**2023-02-02**|**RobustNeRF: Ignoring Distractors with Robust Losses**|Sara Sabour et.al.|[2302.00833v1](http://arxiv.org/abs/2302.00833v1)|null|
|**2023-01-31**|**GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis**|Zhenhui Ye et.al.|[2301.13430v1](http://arxiv.org/abs/2301.13430v1)|null|
|**2023-01-30**|**Equivariant Architectures for Learning in Deep Weight Spaces**|Aviv Navon et.al.|[2301.12780v1](http://arxiv.org/abs/2301.12780v1)|**[link](https://github.com/AvivNavon/DWSNets)**|
|**2023-01-27**|**HyperNeRFGAN: Hypernetwork approach to 3D NeRF GAN**|Adam Kania et.al.|[2301.11631v1](http://arxiv.org/abs/2301.11631v1)|**[link](https://github.com/gmum/hypernerfgan)**|
|**2023-01-27**|**A Comparison of Tiny-nerf versus Spatial Representations for 3d Reconstruction**|Saulo Abraham Gante et.al.|[2301.11522v1](http://arxiv.org/abs/2301.11522v1)|null|
|**2023-01-27**|**SNeRL: Semantic-aware Neural Radiance Fields for Reinforcement Learning**|Dongseok Shim et.al.|[2301.11520v1](http://arxiv.org/abs/2301.11520v1)|null|
|**2023-01-26**|**Text-To-4D Dynamic Scene Generation**|Uriel Singer et.al.|[2301.11280v1](http://arxiv.org/abs/2301.11280v1)|null|
|**2023-01-26**|**GeCoNeRF: Few-shot Neural Radiance Fields via Geometric Consistency**|Minseop Kwak et.al.|[2301.10941v1](http://arxiv.org/abs/2301.10941v1)|null|
|**2023-01-23**|**HexPlane: A Fast Representation for Dynamic Scenes**|Ang Cao et.al.|[2301.09632v1](http://arxiv.org/abs/2301.09632v1)|null|
|**2023-01-22**|**3D Reconstruction of Non-cooperative Resident Space Objects using Instant NGP-accelerated NeRF and D-NeRF**|Trupti Mahendrakar et.al.|[2301.09060v1](http://arxiv.org/abs/2301.09060v1)|null|
|**2023-01-18**|**NeRF in the Palm of Your Hand: Corrective Augmentation for Robotics via Novel-View Synthesis**|Allan Zhou et.al.|[2301.08556v1](http://arxiv.org/abs/2301.08556v1)|null|
|**2023-01-19**|**RecolorNeRF: Layer Decomposed Radiance Field for Efficient Color Editing of 3D Scenes**|Bingchen Gong et.al.|[2301.07958v1](http://arxiv.org/abs/2301.07958v1)|null|
|**2023-01-18**|**Behind the Scenes: Density Fields for Single View Reconstruction**|Felix Wimbauer et.al.|[2301.07668v1](http://arxiv.org/abs/2301.07668v1)|**[link](https://github.com/Brummi/BehindTheScenes)**|
|**2023-01-17**|**A Large-Scale Outdoor Multi-modal Dataset and Benchmark for Novel View Synthesis and Implicit Scene Reconstruction**|Chongshan Lu et.al.|[2301.06782v1](http://arxiv.org/abs/2301.06782v1)|null|
|**2023-01-13**|**Laser: Latent Set Representations for 3D Generative Modeling**|Pol Moreno et.al.|[2301.05747v1](http://arxiv.org/abs/2301.05747v1)|null|
|**2023-01-10**|**Benchmarking Robustness in Neural Radiance Fields**|Chen Wang et.al.|[2301.04075v1](http://arxiv.org/abs/2301.04075v1)|null|
|**2023-01-08**|**Towards Open World NeRF-Based SLAM**|Daniil Lisus et.al.|[2301.03102v1](http://arxiv.org/abs/2301.03102v1)|null|
|**2023-01-10**|**Traditional Readability Formulas Compared for English**|Bruce W. Lee et.al.|[2301.02975v2](http://arxiv.org/abs/2301.02975v2)|null|
|**2023-01-09**|**Class-Continuous Conditional Generative Neural Radiance Field**|Jiwook Kim et.al.|[2301.00950v2](http://arxiv.org/abs/2301.00950v2)|**[link](https://github.com/tom919654/C3G-NeRF)**|
|**2023-01-11**|**Detachable Novel Views Synthesis of Dynamic Scenes Using Distribution-Driven Neural Radiance Fields**|Boyu Zhang et.al.|[2301.00411v2](http://arxiv.org/abs/2301.00411v2)|**[link](https://github.com/luciferbobo/d4nerf)**|
|**2022-12-26**|**MonoNeRF: Learning a Generalizable Dynamic Radiance Field from Monocular Videos**|Fengrui Tian et.al.|[2212.13056v1](http://arxiv.org/abs/2212.13056v1)|null|
|**2022-12-25**|**PaletteNeRF: Palette-based Color Editing for NeRFs**|Qiling Wu et.al.|[2212.12871v1](http://arxiv.org/abs/2212.12871v1)|null|
|**2022-12-22**|**Removing Objects From Neural Radiance Fields**|Silvan Weder et.al.|[2212.11966v1](http://arxiv.org/abs/2212.11966v1)|null|
|**2022-12-21**|**Incremental Learning for Neural Radiance Field with Uncertainty-Filtered Knowledge Distillation**|Mengqi Guo et.al.|[2212.10950v1](http://arxiv.org/abs/2212.10950v1)|null|
|**2022-12-21**|**PaletteNeRF: Palette-based Appearance Editing of Neural Radiance Fields**|Zhengfei Kuang et.al.|[2212.10699v1](http://arxiv.org/abs/2212.10699v1)|null|
|**2022-12-20**|**Correspondence Distillation from NeRF-based GAN**|Yushi Lan et.al.|[2212.09735v2](http://arxiv.org/abs/2212.09735v2)|null|
|**2022-12-19**|**StyleTRF: Stylizing Tensorial Radiance Fields**|Rahul Goel et.al.|[2212.09330v1](http://arxiv.org/abs/2212.09330v1)|null|
|**2022-12-18**|**SPARF: Large-Scale Learning of 3D Sparse Radiance Fields from Few Input Images**|Abdullah Hamdi et.al.|[2212.09100v1](http://arxiv.org/abs/2212.09100v1)|**[link](https://github.com/ajhamdi/sparf_pytorch)**|
|**2022-12-18**|**Masked Wavelet Representation for Compact Neural Radiance Fields**|Daniel Rho et.al.|[2212.09069v1](http://arxiv.org/abs/2212.09069v1)|**[link](https://github.com/daniel03c1/masked_wavelet_nerf)**|
|**2022-12-15**|**SteerNeRF: Accelerating NeRF Rendering via Smooth Viewpoint Trajectory**|Sicheng Li et.al.|[2212.08476v1](http://arxiv.org/abs/2212.08476v1)|null|
|**2022-12-16**|**MEIL-NeRF: Memory-Efficient Incremental Learning of Neural Radiance Fields**|Jaeyoung Chung et.al.|[2212.08328v1](http://arxiv.org/abs/2212.08328v1)|null|
|**2022-12-15**|**NeRF-Art: Text-Driven Neural Radiance Fields Stylization**|Can Wang et.al.|[2212.08070v1](http://arxiv.org/abs/2212.08070v1)|**[link](https://github.com/cassiePython/NeRF-Art)**|
|**2022-12-15**|**Real-Time Neural Light Field on Mobile Devices**|Junli Cao et.al.|[2212.08057v1](http://arxiv.org/abs/2212.08057v1)|null|
|**2022-12-14**|**NoPe-NeRF: Optimising Neural Radiance Field with No Pose Prior**|Wenjing Bian et.al.|[2212.07388v1](http://arxiv.org/abs/2212.07388v1)|null|
|**2022-12-08**|**GazeNeRF: 3D-Aware Gaze Redirection with Neural Radiance Fields**|Alessandro Ruzzi et.al.|[2212.04823v1](http://arxiv.org/abs/2212.04823v1)|null|
|**2022-12-09**|**4K-NeRF: High Fidelity Neural Radiance Fields at Ultra High Resolutions**|Zhongshu Wang et.al.|[2212.04701v1](http://arxiv.org/abs/2212.04701v1)|**[link](https://github.com/frozoul/4k-nerf)**|
|**2022-12-07**|**EditableNeRF: Editing Topologically Varying Neural Radiance Fields by Key Points**|Chengwei Zheng et.al.|[2212.04247v1](http://arxiv.org/abs/2212.04247v1)|null|
|**2022-12-08**|**NeRFEditor: Differentiable Style Decomposition for Full 3D Scene Editing**|Chunyi Sun et.al.|[2212.03848v2](http://arxiv.org/abs/2212.03848v2)|null|
|**2022-12-07**|**Non-uniform Sampling Strategies for NeRF on 360{\textdegree} images**|Takashi Otonari et.al.|[2212.03635v1](http://arxiv.org/abs/2212.03635v1)|null|
|**2022-12-07**|**SSDNeRF: Semantic Soft Decomposition of Neural Radiance Fields**|Siddhant Ranade et.al.|[2212.03406v1](http://arxiv.org/abs/2212.03406v1)|null|
|**2022-12-06**|**NeRDi: Single-View NeRF Synthesis with Language-Guided Diffusion as General Image Priors**|Congyue Deng et.al.|[2212.03267v1](http://arxiv.org/abs/2212.03267v1)|null|
|**2022-12-05**|**SceneRF: Self-Supervised Monocular 3D Scene Reconstruction with Radiance Fields**|Anh-Quan Cao et.al.|[2212.02501v1](http://arxiv.org/abs/2212.02501v1)|**[link](https://github.com/astra-vision/SceneRF)**|
|**2022-12-05**|**Canonical Fields: Self-Supervised Learning of Pose-Canonicalized Neural Fields**|Rohith Agaram et.al.|[2212.02493v1](http://arxiv.org/abs/2212.02493v1)|null|
|**2022-12-06**|**D-TensoRF: Tensorial Radiance Fields for Dynamic Scenes**|Hankyu Jang et.al.|[2212.02375v2](http://arxiv.org/abs/2212.02375v2)|null|
|**2022-12-07**|**GARF:Geometry-Aware Generalized Neural Radiance Field**|Yue Shi et.al.|[2212.02280v2](http://arxiv.org/abs/2212.02280v2)|null|
|**2022-12-05**|**INGeo: Accelerating Instant Neural Scene Reconstruction with Noisy Geometry Priors**|Chaojian Li et.al.|[2212.01959v1](http://arxiv.org/abs/2212.01959v1)|null|
|**2022-12-03**|**MaRF: Representing Mars as Neural Radiance Fields**|Lorenzo Giusti et.al.|[2212.01672v1](http://arxiv.org/abs/2212.01672v1)|null|
|**2022-12-03**|**StegaNeRF: Embedding Invisible Information within Neural Radiance Fields**|Chenxin Li et.al.|[2212.01602v1](http://arxiv.org/abs/2212.01602v1)|null|
|**2022-12-02**|**RT-NeRF: Real-Time On-Device Neural Radiance Fields Towards Immersive AR/VR Rendering**|Chaojian Li et.al.|[2212.01120v1](http://arxiv.org/abs/2212.01120v1)|null|
|**2022-12-02**|**3D-TOGO: Towards Text-Guided Cross-Category 3D Object Generation**|Zutao Jiang et.al.|[2212.01103v1](http://arxiv.org/abs/2212.01103v1)|null|
|**2022-12-02**|**QFF: Quantized Fourier Features for Neural Field Representations**|Jae Yong Lee et.al.|[2212.00914v1](http://arxiv.org/abs/2212.00914v1)|null|
|**2022-12-01**|**ViewNeRF: Unsupervised Viewpoint Estimation Using Category-Level Neural Radiance Fields**|Octave Mariotti et.al.|[2212.00436v1](http://arxiv.org/abs/2212.00436v1)|null|
|**2022-11-30**|**NeRFInvertor: High Fidelity NeRF-GAN Inversion for Single-shot Real Image Animation**|Yu Yin et.al.|[2211.17235v1](http://arxiv.org/abs/2211.17235v1)|null|
|**2022-11-29**|**NeuralLift-360: Lifting An In-the-wild 2D Photo to A 3D Object with 360° Views**|Dejia Xu et.al.|[2211.16431v1](http://arxiv.org/abs/2211.16431v1)|null|
|**2022-11-29**|**Compressing Volumetric Radiance Fields to 1 MB**|Lingzhi Li et.al.|[2211.16386v1](http://arxiv.org/abs/2211.16386v1)|**[link](https://github.com/algohunt/vqrf)**|
|**2022-11-28**|**In-Hand 3D Object Scanning from an RGB Sequence**|Shreyas Hampali et.al.|[2211.16193v1](http://arxiv.org/abs/2211.16193v1)|null|
|**2022-11-30**|**One is All: Bridging the Gap Between Neural Radiance Fields Architectures with Progressive Volume Distillation**|Shuangkang Fang et.al.|[2211.15977v2](http://arxiv.org/abs/2211.15977v2)|**[link](https://github.com/megvii-research/AAAI2023-PVD)**|
|**2022-11-28**|**High-fidelity Facial Avatar Reconstruction from Monocular Video with Generative Priors**|Yunpeng Bai et.al.|[2211.15064v1](http://arxiv.org/abs/2211.15064v1)|null|
|**2022-11-27**|**SuNeRF: Validation of a 3D Global Reconstruction of the Solar Corona Using Simulated EUV Images**|Kyriaki-Margarita Bintsi et.al.|[2211.14879v1](http://arxiv.org/abs/2211.14879v1)|null|
|**2022-11-27**|**3D Scene Creation and Rendering via Rough Meshes: A Lighting Transfer Avenue**|Yujie Li et.al.|[2211.14823v1](http://arxiv.org/abs/2211.14823v1)|null|
|**2022-11-27**|**Sampling Neural Radiance Fields for Refractive Objects**|Jen-I Pan et.al.|[2211.14799v1](http://arxiv.org/abs/2211.14799v1)|**[link](https://github.com/alexkeroro86/samplenerfro)**|
|**2022-11-25**|**3DDesigner: Towards Photorealistic 3D Object Generation and Editing with Text-guided Diffusion Models**|Gang Li et.al.|[2211.14108v1](http://arxiv.org/abs/2211.14108v1)|null|
|**2022-11-25**|**ShadowNeuS: Neural SDF Reconstruction by Shadow Ray Supervision**|Jingwang Ling et.al.|[2211.14086v1](http://arxiv.org/abs/2211.14086v1)|null|
|**2022-11-25**|**Dynamic Neural Portraits**|Michail Christos Doukas et.al.|[2211.13994v1](http://arxiv.org/abs/2211.13994v1)|null|
|**2022-11-25**|**Unsupervised Continual Semantic Adaptation through Neural Rendering**|Zhizheng Liu et.al.|[2211.13969v1](http://arxiv.org/abs/2211.13969v1)|null|
|**2022-11-25**|**TPA-Net: Generate A Dataset for Text to Physics-based Animation**|Yuxing Qiu et.al.|[2211.13887v1](http://arxiv.org/abs/2211.13887v1)|null|
|**2022-11-24**|**ScanNeRF: a Scalable Benchmark for Neural Radiance Fields**|Luca De Luigi et.al.|[2211.13762v1](http://arxiv.org/abs/2211.13762v1)|null|
|**2022-11-24**|**Immersive Neural Graphics Primitives**|Ke Li et.al.|[2211.13494v1](http://arxiv.org/abs/2211.13494v1)|**[link](https://github.com/uhhhci/immersive-ngp)**|
|**2022-11-23**|**CGOF++: Controllable 3D Face Synthesis with Conditional Generative Occupancy Fields**|Keqiang Sun et.al.|[2211.13251v1](http://arxiv.org/abs/2211.13251v1)|null|
|**2022-11-26**|**ClimateNeRF: Physically-based Neural Rendering for Extreme Climate Synthesis**|Yuan Li et.al.|[2211.13226v2](http://arxiv.org/abs/2211.13226v2)|null|
|**2022-11-23**|**ManVatar : Fast 3D Head Avatar Reconstruction Using Motion-Aware Neural Voxels**|Yuelang Xu et.al.|[2211.13206v1](http://arxiv.org/abs/2211.13206v1)|null|
|**2022-11-23**|**BAD-NeRF: Bundle Adjusted Deblur Neural Radiance Fields**|Peng Wang et.al.|[2211.12853v1](http://arxiv.org/abs/2211.12853v1)|null|
|**2022-11-23**|**PANeRF: Pseudo-view Augmentation for Improved Neural Radiance Fields Based on Few-shot Inputs**|Young Chun Ahn et.al.|[2211.12758v1](http://arxiv.org/abs/2211.12758v1)|null|
|**2022-11-23**|**ActiveRMAP: Radiance Field for Active Mapping And Planning**|Huangying Zhan et.al.|[2211.12656v1](http://arxiv.org/abs/2211.12656v1)|null|
|**2022-11-22**|**Zero NeRF: Registration with Zero Overlap**|Casey Peat et.al.|[2211.12544v1](http://arxiv.org/abs/2211.12544v1)|null|
|**2022-11-22**|**Depth-Supervised NeRF for Multi-View RGB-D Operating Room Images**|Beerend G. A. Gerats et.al.|[2211.12436v1](http://arxiv.org/abs/2211.12436v1)|null|
|**2022-11-22**|**Real-time Neural Radiance Talking Portrait Synthesis via Audio-spatial Decomposition**|Jiaxiang Tang et.al.|[2211.12368v1](http://arxiv.org/abs/2211.12368v1)|null|
|**2022-11-22**|**Exact-NeRF: An Exploration of a Precise Volumetric Parameterization for Neural Radiance Fields**|Brian K. S. Isaac-Medina et.al.|[2211.12285v1](http://arxiv.org/abs/2211.12285v1)|null|
|**2022-11-22**|**SPIn-NeRF: Multiview Segmentation and Perceptual Inpainting with Neural Radiance Fields**|Ashkan Mirzaei et.al.|[2211.12254v1](http://arxiv.org/abs/2211.12254v1)|null|
|**2022-11-22**|**Deblurred Neural Radiance Field with Physical Scene Priors**|Dogyoon Lee et.al.|[2211.12046v1](http://arxiv.org/abs/2211.12046v1)|**[link](https://github.com/dogyoonlee/dp-nerf)**|
|**2022-11-22**|**ONeRF: Unsupervised 3D Object Segmentation from Multiple Views**|Shengnan Liang et.al.|[2211.12038v1](http://arxiv.org/abs/2211.12038v1)|null|
|**2022-11-21**|**Towards Live 3D Reconstruction from Wearable Video: An Evaluation of V-SLAM, NeRF, and Videogrammetry Techniques**|David Ramirez et.al.|[2211.11836v1](http://arxiv.org/abs/2211.11836v1)|null|
|**2022-11-21**|**SPARF: Neural Radiance Fields from Sparse and Noisy Poses**|Prune Truong et.al.|[2211.11738v1](http://arxiv.org/abs/2211.11738v1)|null|
|**2022-11-21**|**ESLAM: Efficient Dense SLAM System Based on Hybrid Representation of Signed Distance Fields**|Mohammad Mahdi Johari et.al.|[2211.11704v1](http://arxiv.org/abs/2211.11704v1)|null|
|**2022-11-21**|**Shape, Pose, and Appearance from a Single Image via Bootstrapped Radiance Field Inversion**|Dario Pavllo et.al.|[2211.11674v1](http://arxiv.org/abs/2211.11674v1)|**[link](https://github.com/google-research/nerf-from-image)**|
|**2022-11-18**|**Magic3D: High-Resolution Text-to-3D Content Creation**|Chen-Hsuan Lin et.al.|[2211.10440v1](http://arxiv.org/abs/2211.10440v1)|null|
|**2022-11-17**|**AligNeRF: High-Fidelity Neural Radiance Fields via Alignment-Aware Training**|Yifan Jiang et.al.|[2211.09682v1](http://arxiv.org/abs/2211.09682v1)|null|
|**2022-11-16**|**CoNFies: Controllable Neural Face Avatars**|Heng Yu et.al.|[2211.08610v1](http://arxiv.org/abs/2211.08610v1)|null|
|**2022-11-14**|**Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures**|Gal Metzer et.al.|[2211.07600v1](http://arxiv.org/abs/2211.07600v1)|**[link](https://github.com/eladrich/latent-nerf)**|
|**2022-11-12**|**3D-Aware Encoding for Style-based Neural Radiance Fields**|Yu-Jhe Li et.al.|[2211.06583v1](http://arxiv.org/abs/2211.06583v1)|null|
|**2022-11-11**|**ParticleNeRF: A Particle-Based Encoding for Online Neural Radiance Fields in Dynamic Scenes**|Jad Abou-Chakra et.al.|[2211.04041v2](http://arxiv.org/abs/2211.04041v2)|null|
|**2022-11-07**|**Common Pets in 3D: Dynamic New-View Synthesis of Real-Life Deformable Categories**|Samarth Sinha et.al.|[2211.03889v1](http://arxiv.org/abs/2211.03889v1)|null|
|**2022-11-03**|**nerf2nerf: Pairwise Registration of Neural Radiance Fields**|Lily Goli et.al.|[2211.01600v1](http://arxiv.org/abs/2211.01600v1)|null|
|**2022-10-27**|**ProbNeRF: Uncertainty-Aware Inference of 3D Shapes from 2D Images**|Matthew D. Hoffman et.al.|[2210.17415v1](http://arxiv.org/abs/2210.17415v1)|null|
|**2022-10-27**|**Boosting Point Clouds Rendering via Radiance Mapping**|Xiaoyang Huang et.al.|[2210.15107v1](http://arxiv.org/abs/2210.15107v1)|**[link](https://github.com/seanywang0408/radiancemapping)**|
|**2022-10-24**|**Learning Neural Radiance Fields from Multi-View Geometry**|Marco Orsingher et.al.|[2210.13041v1](http://arxiv.org/abs/2210.13041v1)|null|
|**2022-10-23**|**Compressing Explicit Voxel Grid Representations: fast NeRFs become also small**|Chenxi Lola Deng et.al.|[2210.12782v1](http://arxiv.org/abs/2210.12782v1)|null|
|**2022-11-06**|**Joint Rigid Motion Correction and Sparse-View CT via Self-Calibrating Neural Field**|Qing Wu et.al.|[2210.12731v2](http://arxiv.org/abs/2210.12731v2)|null|
|**2022-10-21**|**An Exploration of Neural Radiance Field Scene Reconstruction: Synthetic, Real-world and Dynamic Scenes**|Benedict Quartey et.al.|[2210.12268v1](http://arxiv.org/abs/2210.12268v1)|null|
|**2022-11-06**|**Neural Fields for Robotic Object Manipulation from a Single Image**|Valts Blukis et.al.|[2210.12126v2](http://arxiv.org/abs/2210.12126v2)|null|
|**2022-10-21**|**HDHumans: A Hybrid Approach for High-fidelity Digital Humans**|Marc Habermann et.al.|[2210.12003v1](http://arxiv.org/abs/2210.12003v1)|null|
|**2022-10-21**|**RGB-Only Reconstruction of Tabletop Scenes for Collision-Free Manipulator Control**|Zhenggang Tang et.al.|[2210.11668v1](http://arxiv.org/abs/2210.11668v1)|null|
|**2022-10-21**|**Coordinates Are NOT Lonely -- Codebook Prior Helps Implicit Neural 3D Representations**|Fukun Yin et.al.|[2210.11170v2](http://arxiv.org/abs/2210.11170v2)|**[link](https://github.com/fukunyin/coco-nerf)**|
|**2022-10-18**|**Parallel Inversion of Neural Radiance Fields for Robust Pose Estimation**|Yunzhi Lin et.al.|[2210.10108v1](http://arxiv.org/abs/2210.10108v1)|null|
|**2022-10-18**|**ARAH: Animatable Volume Rendering of Articulated Human SDFs**|Shaofei Wang et.al.|[2210.10036v1](http://arxiv.org/abs/2210.10036v1)|null|
|**2022-10-20**|**Differentiable Physics Simulation of Dynamics-Augmented Neural Objects**|Simon Le Cleac'h et.al.|[2210.09420v2](http://arxiv.org/abs/2210.09420v2)|null|
|**2022-10-15**|**SPIDR: SDF-based Neural Point Fields for Illumination and Deformation**|Ruofan Liang et.al.|[2210.08398v1](http://arxiv.org/abs/2210.08398v1)|null|
|**2022-10-15**|**IBL-NeRF: Image-Based Lighting Formulation of Neural Radiance Fields**|Changwoon Choi et.al.|[2210.08202v1](http://arxiv.org/abs/2210.08202v1)|null|
|**2022-10-17**|**3D GAN Inversion with Pose Optimization**|Jaehoon Ko et.al.|[2210.07301v2](http://arxiv.org/abs/2210.07301v2)|**[link](https://github.com/KU-CVLAB/3DGAN-Inversion)**|
|**2022-10-13**|**Multiplane NeRF-Supervised Disentanglement of Depth and Camera Pose from Videos**|Yang Fu et.al.|[2210.07181v1](http://arxiv.org/abs/2210.07181v1)|null|
|**2022-10-12**|**GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF**|Qiyu Dai et.al.|[2210.06575v1](http://arxiv.org/abs/2210.06575v1)|null|
|**2022-10-12**|**Reconstructing Personalized Semantic Facial NeRF Models From Monocular Video**|Xuan Gao et.al.|[2210.06108v1](http://arxiv.org/abs/2210.06108v1)|**[link](https://github.com/USTC3DV/NeRFBlendShape-code)**|
|**2022-10-11**|**X-NeRF: Explicit Neural Radiance Field for Multi-Scene 360 $^{\circ}$ Insufficient RGB-D Views**|Haoyi Zhu et.al.|[2210.05135v1](http://arxiv.org/abs/2210.05135v1)|**[link](https://github.com/haoyizhu/xnerf)**|
|**2022-10-10**|**NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields**|Arunkumar Byravan et.al.|[2210.04932v1](http://arxiv.org/abs/2210.04932v1)|null|
|**2022-10-10**|**EVA3D: Compositional 3D Human Generation from 2D Image Collections**|Fangzhou Hong et.al.|[2210.04888v1](http://arxiv.org/abs/2210.04888v1)|**[link](https://github.com/hongfz16/EVA3D)**|
|**2022-10-13**|**NerfAcc: A General NeRF Acceleration Toolbox**|Ruilong Li et.al.|[2210.04847v2](http://arxiv.org/abs/2210.04847v2)|**[link](https://github.com/kair-bair/nerfacc)**|
|**2022-10-10**|**SiNeRF: Sinusoidal Neural Radiance Fields for Joint Pose Estimation and Scene Reconstruction**|Yitong Xia et.al.|[2210.04553v1](http://arxiv.org/abs/2210.04553v1)|**[link](https://github.com/yitongx/sinerf)**|
|**2022-10-09**|**Robustifying the Multi-Scale Representation of Neural Radiance Fields**|Nishant Jain et.al.|[2210.04233v1](http://arxiv.org/abs/2210.04233v1)|null|
|**2022-10-09**|**Estimating Neural Reflectance Field from Radiance Field using Tree Structures**|Xiu Li et.al.|[2210.04217v1](http://arxiv.org/abs/2210.04217v1)|null|
|**2022-10-09**|**Data augmentation for NeRF: a geometric consistent solution based on view morphing**|Matteo Bortolon et.al.|[2210.04214v1](http://arxiv.org/abs/2210.04214v1)|null|
|**2022-10-09**|**Towards Efficient Neural Scene Graphs by Learning Consistency Fields**|Yeji Song et.al.|[2210.04127v1](http://arxiv.org/abs/2210.04127v1)|null|
|**2022-10-08**|**ViewFool: Evaluating the Robustness of Visual Recognition to Adversarial Viewpoints**|Yinpeng Dong et.al.|[2210.03895v1](http://arxiv.org/abs/2210.03895v1)|**[link](https://github.com/heathcliff-saku/viewfool_)**|
|**2022-10-04**|**SelfNeRF: Fast Training NeRF for Human from Monocular Self-rotating Video**|Bo Peng et.al.|[2210.01651v1](http://arxiv.org/abs/2210.01651v1)|null|
|**2022-10-03**|**NARF22: Neural Articulated Radiance Fields for Configuration-Aware Rendering**|Stanley Lewis et.al.|[2210.01166v1](http://arxiv.org/abs/2210.01166v1)|null|
|**2022-10-02**|**IntrinsicNeRF: Learning Intrinsic Neural Radiance Fields for Editable Novel View Synthesis**|Weicai Ye et.al.|[2210.00647v1](http://arxiv.org/abs/2210.00647v1)|**[link](https://github.com/zju3dv/intrinsicnerf)**|
|**2022-10-02**|**Unsupervised Multi-View Object Segmentation Using Radiance Field Propagation**|Xinhang Liu et.al.|[2210.00489v1](http://arxiv.org/abs/2210.00489v1)|null|
|**2022-10-01**|**NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review**|Kyle Gao et.al.|[2210.00379v1](http://arxiv.org/abs/2210.00379v1)|null|
|**2022-10-01**|**Structure-Aware NeRF without Posed Camera via Epipolar Constraint**|Shu Chen et.al.|[2210.00183v1](http://arxiv.org/abs/2210.00183v1)|**[link](https://github.com/xtu-pr-lab/sanerf)**|
|**2022-09-30**|**Improving 3D-aware Image Synthesis with A Geometry-aware Discriminator**|Zifan Shi et.al.|[2209.15637v1](http://arxiv.org/abs/2209.15637v1)|null|
|**2022-09-30**|**Understanding Pure CLIP Guidance for Voxel Grid NeRF Models**|Han-Hung Lee et.al.|[2209.15172v1](http://arxiv.org/abs/2209.15172v1)|null|
|**2022-09-29**|**DreamFusion: Text-to-3D using 2D Diffusion**|Ben Poole et.al.|[2209.14988v1](http://arxiv.org/abs/2209.14988v1)|null|
|**2022-09-29**|**SymmNeRF: Learning to Explore Symmetry Prior for Single-View View Synthesis**|Xingyi Li et.al.|[2209.14819v1](http://arxiv.org/abs/2209.14819v1)|**[link](https://github.com/xingyi-li/symmnerf)**|
|**2022-10-03**|**360FusionNeRF: Panoramic Neural Radiance Fields with Joint Guidance**|Shreyas Kulkarni et.al.|[2209.14265v2](http://arxiv.org/abs/2209.14265v2)|**[link](https://github.com/metaslam/360fusionnerf)**|
|**2022-09-27**|**OmniNeRF: Hybriding Omnidirectional Distance and Radiance fields for Neural Surface Reconstruction**|Jiaming Shen et.al.|[2209.13433v1](http://arxiv.org/abs/2209.13433v1)|null|
|**2022-09-27**|**Orbeez-SLAM: A Real-time Monocular Visual SLAM with ORB Features and NeRF-realized Mapping**|Chi-Ming Chung et.al.|[2209.13274v1](http://arxiv.org/abs/2209.13274v1)|**[link](https://github.com/MarvinChung/Orbeez-slam)**|
|**2022-09-27**|**WaterNeRF: Neural Radiance Fields for Underwater Scenes**|Advaith Venkatramanan Sethuraman et.al.|[2209.13091v1](http://arxiv.org/abs/2209.13091v1)|null|
|**2022-09-26**|**Baking in the Feature: Accelerating Volumetric Segmentation by Rendering Feature Maps**|Kenneth Blomqvist et.al.|[2209.12744v1](http://arxiv.org/abs/2209.12744v1)|null|
|**2022-09-25**|**Enforcing safety for vision-based controllers via Control Barrier Functions and Neural Radiance Fields**|Mukun Tong et.al.|[2209.12266v1](http://arxiv.org/abs/2209.12266v1)|null|
|**2022-09-24**|**NeRF-Loc: Transformer-Based Object Localization Within Neural Radiance Fields**|Jiankai Sun et.al.|[2209.12068v1](http://arxiv.org/abs/2209.12068v1)|null|
|**2022-09-19**|**Loc-NeRF: Monte Carlo Localization using Neural Radiance Fields**|Dominic Maggio et.al.|[2209.09050v1](http://arxiv.org/abs/2209.09050v1)|**[link](https://github.com/mit-spark/loc-nerf)**|
|**2022-09-23**|**NeRF-SOS: Any-View Self-supervised Object Segmentation on Complex Scenes**|Zhiwen Fan et.al.|[2209.08776v4](http://arxiv.org/abs/2209.08776v4)|**[link](https://github.com/vita-group/nerf-sos)**|
|**2022-09-19**|**Density-aware NeRF Ensembles: Quantifying Predictive Uncertainty in Neural Radiance Fields**|Niko Sünderhauf et.al.|[2209.08718v1](http://arxiv.org/abs/2209.08718v1)|null|
|**2022-09-18**|**ActiveNeRF: Learning where to See with Uncertainty Estimation**|Xuran Pan et.al.|[2209.08546v1](http://arxiv.org/abs/2209.08546v1)|null|
|**2022-09-18**|**LATITUDE: Robotic Global Localization with Truncated Dynamic Low-pass Filter in City-scale NeRF**|Zhenxin Zhu et.al.|[2209.08498v1](http://arxiv.org/abs/2209.08498v1)|**[link](https://github.com/jike5/LATITUDE)**|
|**2022-09-16**|**iDF-SLAM: End-to-End RGB-D SLAM with Neural Implicit Mapping and Deep Feature Tracking**|Yuhang Ming et.al.|[2209.07919v1](http://arxiv.org/abs/2209.07919v1)|null|
|**2022-09-12**|**StructNeRF: Neural Radiance Fields for Indoor Scenes with Structural Hints**|Zheng Chen et.al.|[2209.05277v1](http://arxiv.org/abs/2209.05277v1)|null|
|**2022-09-09**|**Generative Deformable Radiance Fields for Disentangled Image Synthesis of Topology-Varying Objects**|Ziyu Wang et.al.|[2209.04183v1](http://arxiv.org/abs/2209.04183v1)|null|
|**2022-09-08**|**im2nerf: Image to Neural Radiance Field in the Wild**|Lu Mi et.al.|[2209.04061v1](http://arxiv.org/abs/2209.04061v1)|null|
|**2022-09-08**|**PixTrack: Precise 6DoF Object Pose Tracking using NeRF Templates and Feature-metric Alignment**|Prajwal Chidananda et.al.|[2209.03910v1](http://arxiv.org/abs/2209.03910v1)|null|
|**2022-09-07**|**Neural Feature Fusion Fields: 3D Distillation of Self-Supervised 2D Image Representations**|Vadim Tschernezki et.al.|[2209.03494v1](http://arxiv.org/abs/2209.03494v1)|null|
|**2022-08-29**|**Volume Rendering Digest (for NeRF)**|Andrea Tagliasacchi et.al.|[2209.02417v1](http://arxiv.org/abs/2209.02417v1)|null|
|**2022-09-06**|**CLONeR: Camera-Lidar Fusion for Occupancy Grid-aided Neural Representations**|Alexandra Carlson et.al.|[2209.01194v2](http://arxiv.org/abs/2209.01194v2)|null|
|**2022-09-01**|**On Quantizing Implicit Neural Representations**|Cameron Gordon et.al.|[2209.01019v1](http://arxiv.org/abs/2209.01019v1)|null|
|**2022-08-31**|**Dual-Space NeRF: Learning Animatable Avatars and Scene Lighting in Separate Spaces**|Yihao Zhi et.al.|[2208.14851v1](http://arxiv.org/abs/2208.14851v1)|**[link](https://github.com/zyhbili/Dual-Space-NeRF)**|
|**2022-08-30**|**A Portable Multiscopic Camera for Novel View and Time Synthesis in Dynamic Scenes**|Tianjia Zhang et.al.|[2208.14433v1](http://arxiv.org/abs/2208.14433v1)|null|
|**2022-08-24**|**PeRFception: Perception using Radiance Fields**|Yoonwoo Jeong et.al.|[2208.11537v1](http://arxiv.org/abs/2208.11537v1)|**[link](https://github.com/POSTECH-CVLab/PeRFception)**|
|**2022-08-24**|**E-NeRF: Neural Radiance Fields from a Moving Event Camera**|Simon Klenk et.al.|[2208.11300v1](http://arxiv.org/abs/2208.11300v1)|**[link](https://github.com/knelk/enerf)**|
|**2022-08-18**|**Neural Capture of Animatable 3D Human from Monocular Video**|Gusi Te et.al.|[2208.08728v1](http://arxiv.org/abs/2208.08728v1)|null|
|**2022-08-16**|**Casual Indoor HDR Radiance Capture from Omnidirectional Images**|Pulkit Gera et.al.|[2208.07903v1](http://arxiv.org/abs/2208.07903v1)|null|
|**2022-08-15**|**DM-NeRF: 3D Scene Geometry Decomposition and Manipulation from 2D Images**|Bing Wang et.al.|[2208.07227v1](http://arxiv.org/abs/2208.07227v1)|**[link](https://github.com/vlar-group/dm-nerf)**|
|**2022-08-11**|**RelPose: Predicting Probabilistic Relative Rotation for Single Objects in the Wild**|Jason Y. Zhang et.al.|[2208.05963v1](http://arxiv.org/abs/2208.05963v1)|null|
|**2022-08-11**|**FDNeRF: Few-shot Dynamic Neural Radiance Fields for Face Reconstruction and Expression Editing**|Jingbo Zhang et.al.|[2208.05751v1](http://arxiv.org/abs/2208.05751v1)|**[link](https://github.com/fdnerf/fdnerf)**|
|**2022-08-04**|**360Roam: Real-Time Indoor Roaming Using Geometry-Aware ${360^\circ}$ Radiance Fields**|Huajian Huang et.al.|[2208.02705v1](http://arxiv.org/abs/2208.02705v1)|null|
|**2022-08-02**|**T4DT: Tensorizing Time for Learning Temporal 3D Visual Data**|Mikhail Usvyatsov et.al.|[2208.01421v1](http://arxiv.org/abs/2208.01421v1)|**[link](https://github.com/aelphy/t4dt)**|
|**2022-08-01**|**DoF-NeRF: Depth-of-Field Meets Neural Radiance Fields**|Zijin Wu et.al.|[2208.00945v1](http://arxiv.org/abs/2208.00945v1)|**[link](https://github.com/zijinwuzijin/dof-nerf)**|
|**2022-08-06**|**MobileNeRF: Exploiting the Polygon Rasterization Pipeline for Efficient Neural Field Rendering on Mobile Architectures**|Zhiqin Chen et.al.|[2208.00277v2](http://arxiv.org/abs/2208.00277v2)|**[link](https://github.com/google-research/jax3d)**|
|**2022-07-30**|**Distilled Low Rank Neural Radiance Field with Quantization for Light Field Compression**|Jinglei Shi et.al.|[2208.00164v1](http://arxiv.org/abs/2208.00164v1)|null|
|**2022-08-01**|**End-to-end View Synthesis via NeRF Attention**|Zelin Zhao et.al.|[2207.14741v2](http://arxiv.org/abs/2207.14741v2)|null|
|**2022-07-29**|**Neural Density-Distance Fields**|Itsuki Ueda et.al.|[2207.14455v1](http://arxiv.org/abs/2207.14455v1)|**[link](https://github.com/ueda0319/neddf)**|
|**2022-07-27**|**Is Attention All NeRF Needs?**|Mukund Varma T et.al.|[2207.13298v1](http://arxiv.org/abs/2207.13298v1)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## BEV

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-13**|**DA-BEV: Unsupervised Domain Adaptation for Bird's Eye View Perception**|Kai Jiang et.al.|[2401.08687](http://arxiv.org/abs/2401.08687)|null|
|**2024-01-17**|**LightHouse: A Survey of AGI Hallucination**|Feng Wang et.al.|[2401.06792](http://arxiv.org/abs/2401.06792)|**[link](https://github.com/zurichrain/agi-hallucination)**|
|**2023-12-26**|**VirtualPainting: Addressing Sparsity with Virtual Points and Distance-Aware Data Augmentation for 3D Object Detection**|Sudip Dhakal et.al.|[2312.16141](http://arxiv.org/abs/2312.16141)|null|
|**2023-12-24**|**End-to-End 3D Object Detection using LiDAR Point Cloud**|Gaurav Raut et.al.|[2312.15377](http://arxiv.org/abs/2312.15377)|null|
|**2023-12-23**|**BEV-CV: Birds-Eye-View Transform for Cross-View Geo-Localisation**|Tavis Shore et.al.|[2312.15363](http://arxiv.org/abs/2312.15363)|null|
|**2024-01-10**|**Optimizing Ego Vehicle Trajectory Prediction: The Graph Enhancement Approach**|Sushil Sharma et.al.|[2312.13104](http://arxiv.org/abs/2312.13104)|null|
|**2023-12-19**|**M-BEV: Masked BEV Perception for Robust Autonomous Driving**|Siran Chen et.al.|[2312.12144](http://arxiv.org/abs/2312.12144)|**[link](https://github.com/sranc3/m-bev)**|
|**2023-12-18**|**Diffusion-Based Particle-DETR for BEV Perception**|Asen Nachkov et.al.|[2312.11578](http://arxiv.org/abs/2312.11578)|null|
|**2023-12-18**|**Multi-Correlation Siamese Transformer Network with Dense Connection for 3D Single Object Tracking**|Shihao Feng et.al.|[2312.11051](http://arxiv.org/abs/2312.11051)|**[link](https://github.com/liangp/mcstn-3dsot)**|
|**2023-12-11**|**VoxelKP: A Voxel-based Network Architecture for Human Keypoint Estimation in LiDAR Data**|Jian Shi et.al.|[2312.08871](http://arxiv.org/abs/2312.08871)|**[link](https://github.com/shijianjian/voxelkp)**|
|**2023-12-13**|**C-BEV: Contrastive Bird's Eye View Training for Cross-View Image Retrieval and 3-DoF Pose Estimation**|Florian Fervers et.al.|[2312.08060](http://arxiv.org/abs/2312.08060)|null|
|**2023-12-13**|**Instance-aware Multi-Camera 3D Object Detection with Structural Priors Mining and Self-Boosting Learning**|Yang Jiao et.al.|[2312.08004](http://arxiv.org/abs/2312.08004)|null|
|**2023-12-09**|**Enhancing Situational Awareness in Surveillance: Leveraging Data Visualization Techniques for Machine Learning-based Video Analytics Outcomes**|Babak Rahimi Ardabili et.al.|[2312.05629](http://arxiv.org/abs/2312.05629)|null|
|**2023-12-08**|**An Autonomous Driving model with BEV-V2X Perception, Trajectory Prediction and Driving Planning in Complex Traffic Intersections**|Fukang Li et.al.|[2312.05104](http://arxiv.org/abs/2312.05104)|null|
|**2023-12-04**|**COTR: Compact Occupancy TRansformer for Vision-based 3D Occupancy Prediction**|Qihang Ma et.al.|[2312.01919](http://arxiv.org/abs/2312.01919)|null|
|**2023-12-04**|**BEVNeXt: Reviving Dense BEV Frameworks for 3D Object Detection**|Zhenxin Li et.al.|[2312.01696](http://arxiv.org/abs/2312.01696)|null|
|**2024-01-01**|**Towards Full-scene Domain Generalization in Multi-agent Collaborative Bird's Eye View Segmentation for Connected and Autonomous Driving**|Senkang Hu et.al.|[2311.16754](http://arxiv.org/abs/2311.16754)|**[link](https://github.com/dg-cavs/dg-coperception)**|
|**2023-11-27**|**Technical Report for Argoverse Challenges on 4D Occupancy Forecasting**|Pengfei Zheng et.al.|[2311.15660](http://arxiv.org/abs/2311.15660)|null|
|**2023-11-27**|**Technical Report for Argoverse Challenges on Unified Sensor-based Detection, Tracking, and Forecasting**|Zhepeng Wang et.al.|[2311.15615](http://arxiv.org/abs/2311.15615)|null|
|**2023-11-29**|**SelfOcc: Self-Supervised Vision-Based 3D Occupancy Prediction**|Yuanhui Huang et.al.|[2311.12754](http://arxiv.org/abs/2311.12754)|**[link](https://github.com/huang-yh/selfocc)**|
|**2023-11-13**|**The Last Decade in Review: Tracing the Evolution of Safety Assurance Cases through a Comprehensive Bibliometric Analysis**|Mithila Sivakumar et.al.|[2311.07495](http://arxiv.org/abs/2311.07495)|null|
|**2023-11-12**|**Deep Perspective Transformation Based Vehicle Localization on Bird's Eye View**|Abtin Mahyar et.al.|[2311.06796](http://arxiv.org/abs/2311.06796)|**[link](https://github.com/ipm-hpc/perspective-bev-transformer)**|
|**2023-11-09**|**TLCFuse: Temporal Multi-Modality Fusion Towards Occlusion-Aware Semantic Segmentation-Aided Motion Planning**|Gustavo Salazar-Gomez et.al.|[2311.05319](http://arxiv.org/abs/2311.05319)|null|
|**2023-11-08**|**PRED: Pre-training via Semantic Rendering on LiDAR Point Clouds**|Hao Yang et.al.|[2311.04501](http://arxiv.org/abs/2311.04501)|null|
|**2023-10-26**|**BEVContrast: Self-Supervision in BEV Space for Automotive Lidar Point Clouds**|Corentin Sautier et.al.|[2310.17281](http://arxiv.org/abs/2310.17281)|**[link](https://github.com/valeoai/bevcontrast)**|
|**2024-01-08**|**ScalableMap: Scalable Map Learning for Online Long-Range Vectorized HD Map Construction**|Jingyi Yu et.al.|[2310.13378](http://arxiv.org/abs/2310.13378)|**[link](https://github.com/jingy1yu/scalablemap)**|
|**2023-10-20**|**EarlyBird: Early-Fusion for Multi-View Tracking in the Bird's Eye View**|Torben Teepe et.al.|[2310.13350](http://arxiv.org/abs/2310.13350)|**[link](https://github.com/tteepe/EarlyBird)**|
|**2023-11-28**|**DynamicBEV: Leveraging Dynamic Queries and Temporal Context for 3D Object Detection**|Jiawei Yao et.al.|[2310.05989](http://arxiv.org/abs/2310.05989)|null|
|**2023-10-09**|**Asynchrony-Robust Collaborative Perception via Bird's Eye View Flow**|Sizhe Wei et.al.|[2309.16940](http://arxiv.org/abs/2309.16940)|null|
|**2023-09-28**|**LEF: Late-to-Early Temporal Fusion for LiDAR 3D Object Detection**|Tong He et.al.|[2309.16870](http://arxiv.org/abs/2309.16870)|null|
|**2023-09-28**|**Navigating Healthcare Insights: A Birds Eye View of Explainability with Knowledge Graphs**|Satvik Garg et.al.|[2309.16593](http://arxiv.org/abs/2309.16593)|null|
|**2023-09-28**|**BEVHeight++: Toward Robust Visual Centric 3D Object Detection**|Lei Yang et.al.|[2309.16179](http://arxiv.org/abs/2309.16179)|null|
|**2023-12-27**|**Learning Dense Flow Field for Highly-accurate Cross-view Camera Localization**|Zhenbo Song et.al.|[2309.15556](http://arxiv.org/abs/2309.15556)|null|
|**2023-09-27**|**Cross-Dataset Experimental Study of Radar-Camera Fusion in Bird's-Eye View**|Lukas Stäcker et.al.|[2309.15465](http://arxiv.org/abs/2309.15465)|null|
|**2023-09-25**|**UniBEV: Multi-modal 3D Object Detection with Uniform BEV Encoders for Robustness against Missing Sensor Modalities**|Shiming Wang et.al.|[2309.14516](http://arxiv.org/abs/2309.14516)|null|
|**2023-09-24**|**Advancements in 3D Lane Detection Using LiDAR Point Clouds: From Data Collection to Model Development**|Runkai Zhao et.al.|[2309.13596](http://arxiv.org/abs/2309.13596)|null|
|**2023-11-08**|**BroadBEV: Collaborative LiDAR-camera Fusion for Broad-sighted Bird's Eye View Map Construction**|Minsu Kim et.al.|[2309.11119](http://arxiv.org/abs/2309.11119)|null|
|**2023-09-19**|**A Novel Deep Neural Network for Trajectory Prediction in Automated Vehicles Using Velocity Vector Field**|MReza Alipour Sormoli et.al.|[2309.10948](http://arxiv.org/abs/2309.10948)|**[link](https://github.com/Amir-Samadi/VVF-TP)**|
|**2023-09-25**|**LineMarkNet: Line Landmark Detection for Valet Parking**|Zizhang Wu et.al.|[2309.10475](http://arxiv.org/abs/2309.10475)|null|
|**2023-09-19**|**Multi-camera Bird's Eye View Perception for Autonomous Driving**|David Unger et.al.|[2309.09080](http://arxiv.org/abs/2309.09080)|null|
|**2023-09-22**|**OccupancyDETR: Making Semantic Scene Completion as Straightforward as Object Detection**|Yupeng Jia et.al.|[2309.08504](http://arxiv.org/abs/2309.08504)|**[link](https://github.com/jypjypjypjyp/occupancydetr)**|
|**2023-09-15**|**AVM-SLAM: Semantic Visual SLAM with Multi-Sensor Fusion in a Bird's Eye View for Automated Valet Parking**|Ye Li et.al.|[2309.08180](http://arxiv.org/abs/2309.08180)|**[link](https://github.com/yale-cv/avm-slam)**|
|**2023-10-09**|**FusionFormer: A Multi-sensory Fusion in Bird's-Eye-View and Temporal Consistent Transformer for 3D Object Detection**|Chunyong Hu et.al.|[2309.05257](http://arxiv.org/abs/2309.05257)|null|
|**2023-09-11**|**Towards Viewpoint Robustness in Bird's Eye View Segmentation**|Tzofi Klinghoffer et.al.|[2309.05192](http://arxiv.org/abs/2309.05192)|null|
|**2023-08-31**|**PointOcc: Cylindrical Tri-Perspective View for Point-based 3D Semantic Occupancy Prediction**|Sicheng Zuo et.al.|[2308.16896](http://arxiv.org/abs/2308.16896)|**[link](https://github.com/wzzheng/pointocc)**|
|**2023-08-29**|**Complementing Onboard Sensors with Satellite Map: A New Perspective for HD Map Construction**|Wenjie Gao et.al.|[2308.15427](http://arxiv.org/abs/2308.15427)|null|
|**2023-08-28**|**Semi-Supervised Learning for Visual Bird's Eye View Semantic Segmentation**|Junyu Zhu et.al.|[2308.14525](http://arxiv.org/abs/2308.14525)|null|
|**2023-08-27**|**Automatic coarse co-registration of point clouds from diverse scan geometries: a test of detectors and descriptors**|Francesco Pirotti et.al.|[2308.14047](http://arxiv.org/abs/2308.14047)|null|
|**2023-12-10**|**SOGDet: Semantic-Occupancy Guided Multi-view 3D Object Detection**|Qiu Zhou et.al.|[2308.13794](http://arxiv.org/abs/2308.13794)|**[link](https://github.com/zhouqiu/sogdet)**|
|**2023-08-21**|**QD-BEV : Quantization-aware View-guided Distillation for Multi-view 3D Object Detection**|Yifan Zhang et.al.|[2308.10515](http://arxiv.org/abs/2308.10515)|null|
|**2023-08-30**|**UniM $^2$ AE: Multi-modal Masked Autoencoders with Unified 3D Representation for 3D Perception in Autonomous Driving**|Jian Zou et.al.|[2308.10421](http://arxiv.org/abs/2308.10421)|**[link](https://github.com/hollow-503/unim2ae)**|
|**2023-09-05**|**SparseBEV: High-Performance Sparse 3D Object Detection from Multi-Camera Videos**|Haisong Liu et.al.|[2308.09244](http://arxiv.org/abs/2308.09244)|**[link](https://github.com/mcg-nju/sparsebev)**|
|**2023-08-16**|**Automatic Vision-Based Parking Slot Detection and Occupancy Classification**|Ratko Grbić et.al.|[2308.08192](http://arxiv.org/abs/2308.08192)|null|
|**2023-09-04**|**MS3D++: Ensemble of Experts for Multi-Source Unsupervised Domain Adaptation in 3D Object Detection**|Darren Tsai et.al.|[2308.05988](http://arxiv.org/abs/2308.05988)|**[link](https://github.com/darrenjkt/ms3d)**|
|**2023-08-20**|**LATR: 3D Lane Detection from Monocular Images with Transformer**|Yueru Luo et.al.|[2308.04583](http://arxiv.org/abs/2308.04583)|**[link](https://github.com/jmoonr/latr)**|
|**2023-08-17**|**FB-BEV: BEV Representation from Forward-Backward View Transformations**|Zhiqi Li et.al.|[2308.02236](http://arxiv.org/abs/2308.02236)|**[link](https://github.com/nvlabs/fb-bev)**|
|**2023-11-13**|**Echoes Beyond Points: Unleashing the Power of Raw Radar Data in Multi-modality Fusion**|Yang Liu et.al.|[2307.16532](http://arxiv.org/abs/2307.16532)|**[link](https://github.com/tusen-ai/echofusion)**|
|**2023-07-25**|**HeightFormer: Explicit Height Modeling without Extra Data for Camera-only 3D Object Detection in Bird's Eye View**|Yiming Wu et.al.|[2307.13510](http://arxiv.org/abs/2307.13510)|null|
|**2023-07-18**|**GroupLane: End-to-End 3D Lane Detection with Channel-wise Grouping**|Zhuoling Li et.al.|[2307.09472](http://arxiv.org/abs/2307.09472)|null|
|**2023-07-17**|**Monocular 3D Object Detection with LiDAR Guided Semi Supervised Active Learning**|Aral Hekimoglu et.al.|[2307.08415](http://arxiv.org/abs/2307.08415)|null|
|**2023-07-11**|**Parametric Depth Based Feature Representation Learning for Object Detection and Segmentation in Bird's Eye View**|Jiayu Yang et.al.|[2307.04106](http://arxiv.org/abs/2307.04106)|null|
|**2023-09-19**|**Practical Collaborative Perception: A Framework for Asynchronous and Multi-Agent 3D Object Detection**|Minh-Quan Dao et.al.|[2307.01462](http://arxiv.org/abs/2307.01462)|**[link](https://github.com/quan-dao/practical-collab-perception)**|
|**2023-10-03**|**LXL: LiDAR Excluded Lean 3D Object Detection with 4D Imaging Radar and Camera Fusion**|Weiyi Xiong et.al.|[2307.00724](http://arxiv.org/abs/2307.00724)|null|
|**2023-06-21**|**Misinformation as Information Pollution**|Ashkan Kazemi et.al.|[2306.12466](http://arxiv.org/abs/2306.12466)|null|
|**2023-07-02**|**ScenarioNet: Open-Source Platform for Large-Scale Traffic Scenario Simulation and Modeling**|Quanyi Li et.al.|[2306.12241](http://arxiv.org/abs/2306.12241)|**[link](https://github.com/metadriverse/scenarionet)**|
|**2023-06-17**|**MachMap: End-to-End Vectorized Solution for Compact HD-Map Construction**|Limeng Qiao et.al.|[2306.10301](http://arxiv.org/abs/2306.10301)|null|
|**2023-06-16**|**Coaching a Teachable Student**|Jimuyang Zhang et.al.|[2306.10014](http://arxiv.org/abs/2306.10014)|null|
|**2023-06-12**|**MaskedFusion360: Reconstruct LiDAR Data by Querying Camera Features**|Royden Wagner et.al.|[2306.07087](http://arxiv.org/abs/2306.07087)|**[link](https://github.com/kit-mrt/masked-fusion-360)**|
|**2023-06-08**|**UAP-BEV: Uncertainty Aware Planning using Bird's Eye View generated from Surround Monocular Images**|Vikrant Dewangan et.al.|[2306.04939](http://arxiv.org/abs/2306.04939)|null|
|**2023-06-08**|**An Efficient Transformer for Simultaneous Learning of BEV and Lane Representations in 3D Lane Detection**|Ziye Chen et.al.|[2306.04927](http://arxiv.org/abs/2306.04927)|null|
|**2023-06-07**|**NeMO: Neural Map Growing System for Spatiotemporal Fusion in Bird's-Eye-View and BDD-Map Benchmark**|Xi Zhu et.al.|[2306.04540](http://arxiv.org/abs/2306.04540)|null|
|**2023-06-01**|**CALICO: Self-Supervised Camera-LiDAR Contrastive Pre-training for BEV Perception**|Jiachen Sun et.al.|[2306.00349](http://arxiv.org/abs/2306.00349)|null|
|**2023-06-07**|**Occ-BEV: Multi-Camera Unified Pre-training via 3D Scene Reconstruction**|Chen Min et.al.|[2305.18829](http://arxiv.org/abs/2305.18829)|**[link](https://github.com/chaytonmin/occ-bev)**|
|**2023-05-25**|**RC-BEVFusion: A Plug-In Module for Radar-Camera Bird's Eye View Feature Fusion**|Lukas Stäcker et.al.|[2305.15883](http://arxiv.org/abs/2305.15883)|null|
|**2023-05-23**|**Leveraging BEV Representation for 360-degree Visual Place Recognition**|Xuecheng Xu et.al.|[2305.13814](http://arxiv.org/abs/2305.13814)|**[link](https://github.com/maverickpeter/vdisco)**|
|**2023-05-21**|**Unsupervised Multi-view Pedestrian Detection**|Mengyin Liu et.al.|[2305.12457](http://arxiv.org/abs/2305.12457)|null|
|**2023-05-15**|**Artificial intelligence to advance Earth observation: a perspective**|Devis Tuia et.al.|[2305.08413](http://arxiv.org/abs/2305.08413)|null|
|**2023-05-12**|**MotionBEV: Attention-Aware Online LiDAR Moving Object Segmentation with Bird's Eye View based Appearance and Motion Features**|Bo Zhou et.al.|[2305.07336](http://arxiv.org/abs/2305.07336)|**[link](https://github.com/xiekkki/motionbev)**|
|**2023-05-04**|**Aligning Bird-Eye View Representation of Point Cloud Sequences using Scene Flow**|Minh-Quan Dao et.al.|[2305.02909](http://arxiv.org/abs/2305.02909)|**[link](https://github.com/quan-dao/pc-corrector)**|
|**2023-05-11**|**FlowMap: Path Generation for Automated Vehicles in Open Space Using Traffic Flow**|Wenchao Ding et.al.|[2305.01622](http://arxiv.org/abs/2305.01622)|null|
|**2023-06-29**|**Group Equivariant BEV for 3D Object Detection**|Hongwei Liu et.al.|[2304.13390](http://arxiv.org/abs/2304.13390)|null|
|**2023-04-23**|**Walking Your LiDOG: A Journey Through Multiple Domains for LiDAR Semantic Segmentation**|Cristiano Saltori et.al.|[2304.11705](http://arxiv.org/abs/2304.11705)|null|
|**2023-04-13**|**RoboBEV: Towards Robust Bird's Eye View Perception under Corruptions**|Shaoyuan Xie et.al.|[2304.06719](http://arxiv.org/abs/2304.06719)|**[link](https://github.com/Daniel-xsy/RoboBEV)**|
|**2023-04-11**|**OccFormer: Dual-path Transformer for Vision-based 3D Semantic Occupancy Prediction**|Yunpeng Zhang et.al.|[2304.05316](http://arxiv.org/abs/2304.05316)|**[link](https://github.com/zhangyp15/occformer)**|
|**2023-04-06**|**VPFusion: Towards Robust Vertical Representation Learning for 3D Object Detection**|Yuhao Huang et.al.|[2304.02867](http://arxiv.org/abs/2304.02867)|null|
|**2023-04-06**|**Experimental verification of band convergence in Sr and Na codoped PbTe**|Yuya Hattori et.al.|[2304.02844](http://arxiv.org/abs/2304.02844)|null|
|**2023-04-04**|**Socio-economic landscape of digital transformation & public NLP systems: A critical review**|Satyam Mohla et.al.|[2304.01651](http://arxiv.org/abs/2304.01651)|null|
|**2023-04-04**|**FedBEVT: Federated Learning Bird's Eye View Perception Transformer in Road Traffic Systems**|Rui Song et.al.|[2304.01534](http://arxiv.org/abs/2304.01534)|null|
|**2023-04-19**|**DORT: Modeling Dynamic Objects in Recurrent for Multi-Camera 3D Object Detection and Tracking**|Qing Lian et.al.|[2303.16628](http://arxiv.org/abs/2303.16628)|**[link](https://github.com/smartbot-pjlab/dort)**|
|**2023-03-24**|**AssetField: Assets Mining and Reconfiguration in Ground Feature Plane Representation**|Yuanbo Xiangli et.al.|[2303.13953](http://arxiv.org/abs/2303.13953)|null|
|**2023-03-21**|**LiDARFormer: A Unified Transformer-based Multi-task Network for LiDAR Perception**|Zixiang Zhou et.al.|[2303.12194](http://arxiv.org/abs/2303.12194)|null|
|**2023-04-04**|**A Simple Attempt for 3D Occupancy Estimation in Autonomous Driving**|Wanshui Gan et.al.|[2303.10076](http://arxiv.org/abs/2303.10076)|**[link](https://github.com/ganwanshui/simpleoccupancy)**|
|**2023-04-11**|**BEVHeight: A Robust Framework for Vision-based Roadside 3D Object Detection**|Lei Yang et.al.|[2303.08498](http://arxiv.org/abs/2303.08498)|**[link](https://github.com/adlab-autodrive/bevheight)**|
|**2023-03-15**|**DiffBEV: Conditional Diffusion Model for Bird's Eye View Perception**|Jiayu Zou et.al.|[2303.08333](http://arxiv.org/abs/2303.08333)|**[link](https://github.com/jiayuzou2020/diffbev)**|
|**2023-03-13**|**OverlapNetVLAD: A Coarse-to-Fine Framework for LiDAR-based Place Recognition**|Chencan Fu et.al.|[2303.06881](http://arxiv.org/abs/2303.06881)|**[link](https://github.com/fcchit/overlapnetvlad)**|
|**2023-03-12**|**BCSSN: Bi-direction Compact Spatial Separable Network for Collision Avoidance in Autonomous Driving**|Haichuan Li et.al.|[2303.06714](http://arxiv.org/abs/2303.06714)|null|
|**2023-03-07**|**Operationalizing AI in Future Networks: A Bird's Eye View from the System Perspective**|Tianzhu Zhang et.al.|[2303.04073](http://arxiv.org/abs/2303.04073)|null|
|**2023-03-07**|**F2BEV: Bird's Eye View Generation from Surround-View Fisheye Camera Images for Automated Driving**|Ekta U. Samani et.al.|[2303.03651](http://arxiv.org/abs/2303.03651)|null|
|**2023-03-03**|**BSH-Det3D: Improving 3D Object Detection with BEV Shape Heatmap**|You Shen et.al.|[2303.02000](http://arxiv.org/abs/2303.02000)|**[link](https://github.com/mystorm16/bsh-det3d)**|
|**2023-03-03**|**Towards Domain Generalization for Multi-view 3D Object Detection in Bird-Eye-View**|Shuo Wang et.al.|[2303.01686](http://arxiv.org/abs/2303.01686)|null|
|**2023-03-02**|**I2P-Rec: Recognizing Images on Large-scale Point Cloud Maps through Bird's Eye View Projections**|Yixuan Li et.al.|[2303.01043](http://arxiv.org/abs/2303.01043)|null|
|**2023-03-15**|**BEVPlace: Learning LiDAR-based Place Recognition using Bird's Eye View Images**|Lun Luo et.al.|[2302.14325](http://arxiv.org/abs/2302.14325)|**[link](https://github.com/zjuluolun/bevplace)**|
|**2023-02-26**|**Pillar R-CNN for Point Cloud 3D Object Detection**|Guangsheng Shi et.al.|[2302.13301](http://arxiv.org/abs/2302.13301)|null|
|**2023-02-25**|**DA-BEV: Depth Aware BEV Transformer for 3D Object Detection**|Hao Zhang et.al.|[2302.13002](http://arxiv.org/abs/2302.13002)|null|
|**2023-02-19**|**FusionMotion: Multi-Sensor Asynchronous Fusion for Continuous Occupancy Prediction via Neural-ODE**|Yining Shi et.al.|[2302.09585](http://arxiv.org/abs/2302.09585)|**[link](https://github.com/synsin0/fusionmotion)**|
|**2023-02-17**|**SBcoyote: An Extensible Python-Based Reaction Editor and Viewer**|Jin Xu et.al.|[2302.09151](http://arxiv.org/abs/2302.09151)|**[link](https://github.com/sys-bio/sbcoyote)**|
|**2023-03-07**|**3M3D: Multi-view, Multi-path, Multi-representation for 3D Object Detection**|Jongwoo Park et.al.|[2302.08231](http://arxiv.org/abs/2302.08231)|null|
|**2023-03-07**|**Surround-View Vision-based 3D Detection for Autonomous Driving: A Survey**|Apoorv Singh et.al.|[2302.06650](http://arxiv.org/abs/2302.06650)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Registration

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2023-09-21**|**Human Following in Mobile Platforms with Person Re-Identification**|Mario Srouji et.al.|[2309.12479](http://arxiv.org/abs/2309.12479)|null|
|**2023-10-22**|**SEM-GAT: Explainable Semantic Pose Estimation using Learned Graph Attention**|Efimia Panagiotaki et.al.|[2308.03718](http://arxiv.org/abs/2308.03718)|**[link](https://github.com/cognitive-robots/sem-gat)**|
|**2023-06-01**|**A Probabilistic Relaxation of the Two-Stage Object Pose Estimation Paradigm**|Onur Beker et.al.|[2306.00892](http://arxiv.org/abs/2306.00892)|null|
|**2023-03-02**|**Indescribable Multi-modal Spatial Evaluator**|Lingke Kong et.al.|[2303.00369](http://arxiv.org/abs/2303.00369)|**[link](https://github.com/kid-liet/imse)**|
|**2022-12-06**|**Self-Supervised Correspondence Estimation via Multiview Registration**|Mohamed El Banani et.al.|[2212.03236](http://arxiv.org/abs/2212.03236)|**[link](https://github.com/facebookresearch/syncmatch)**|
|**2021-08-06**|**On Bundle Adjustment for Multiview PointCloud Registration**|Huaiyang Huang et.al.|[2108.02976](http://arxiv.org/abs/2108.02976)|null|
|**2021-04-12**|**3D3L: Deep Learned 3D Keypoint Detection and Description for LiDARs**|Dominic Streiff et.al.|[2103.13808](http://arxiv.org/abs/2103.13808)|**[link](https://github.com/ethz-asl/3d3l)**|
|**2021-03-25**|**Deep 6-DoF Tracking of Unknown Objects for Reactive Grasping**|Marc Tuscher et.al.|[2103.05401](http://arxiv.org/abs/2103.05401)|null|
|**2021-02-03**|**PHASER: a Robust and Correspondence-free Global Pointcloud Registration**|Lukas Bernreiter et.al.|[2102.02767](http://arxiv.org/abs/2102.02767)|**[link](https://github.com/ethz-asl/phaser)**|
|**2021-06-17**|**"What's This?" -- Learning to Segment Unknown Objects from Manipulation Sequences**|Wout Boerdijk et.al.|[2011.03279](http://arxiv.org/abs/2011.03279)|**[link](https://github.com/DLR-RM/DistinctNet)**|
|**2020-10-10**|**A Termination Criterion for Probabilistic PointClouds Registration**|Simone Fontana et.al.|[2010.04979](http://arxiv.org/abs/2010.04979)|null|
|**2017-04-25**|**Adaptive Cost Function for Pointcloud Registration**|Johan Ekekrantz et.al.|[1704.07910](http://arxiv.org/abs/1704.07910)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Localization

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-16**|**Multi-Technique Sequential Information Consistency For Dynamic Visual Place Recognition In Changing Environments**|Bruno Arcanjo et.al.|[2401.08263](http://arxiv.org/abs/2401.08263)|null|
|**2024-01-11**|**UAVD4L: A Large-Scale Dataset for UAV 6-DoF Localization**|Rouwan Wu et.al.|[2401.05971](http://arxiv.org/abs/2401.05971)|null|
|**2024-01-03**|**DDN-SLAM: Real-time Dense Dynamic Neural Implicit SLAM with Joint Semantic Encoding**|Mingrui Li et.al.|[2401.01545](http://arxiv.org/abs/2401.01545)|null|
|**2023-12-27**|**LIP-Loc: LiDAR Image Pretraining for Cross-Modal Localization**|Sai Shubodh Puligilla et.al.|[2312.16648](http://arxiv.org/abs/2312.16648)|null|
|**2023-12-24**|**Residual Learning for Image Point Descriptors**|Rashik Shrestha et.al.|[2312.15471](http://arxiv.org/abs/2312.15471)|null|
|**2023-12-23**|**CaLDiff: Camera Localization in NeRF via Pose Diffusion**|Rashik Shrestha et.al.|[2312.15242](http://arxiv.org/abs/2312.15242)|null|
|**2023-12-20**|**Aggregating Multiple Bio-Inspired Image Region Classifiers For Effective And Lightweight Visual Place Recognition**|Bruno Arcanjo et.al.|[2312.12995](http://arxiv.org/abs/2312.12995)|null|
|**2023-12-17**|**PNeRFLoc: Visual Localization with Point-based Neural Radiance Fields**|Boming Zhao et.al.|[2312.10649](http://arxiv.org/abs/2312.10649)|null|
|**2023-12-17**|**DistilVPR: Cross-Modal Knowledge Distillation for Visual Place Recognition**|Sijie Wang et.al.|[2312.10616](http://arxiv.org/abs/2312.10616)|**[link](https://github.com/sijieaaa/distilvpr)**|
|**2023-12-15**|**AEGIS-Net: Attention-guided Multi-Level Feature Aggregation for Indoor Place Recognition**|Yuhang Ming et.al.|[2312.09538](http://arxiv.org/abs/2312.09538)|**[link](https://github.com/yuhangming/aegis-net)**|
|**2023-12-14**|**Design Space Exploration of Low-Bit Quantized Neural Networks for Visual Place Recognition**|Oliver Grainge et.al.|[2312.09028](http://arxiv.org/abs/2312.09028)|null|
|**2023-12-12**|**Attacking the Loop: Adversarial Attacks on Graph-based Loop Closure Detection**|Jonathan J. Y. Kim et.al.|[2312.06991](http://arxiv.org/abs/2312.06991)|null|
|**2023-12-08**|**MagHT: a Magnetic Hough Transform for Fast Indoor Place Recognition**|Iad Abdul Raouf et.al.|[2312.05015](http://arxiv.org/abs/2312.05015)|null|
|**2023-12-04**|**Implicit Learning of Scene Geometry from Poses for Global Localization**|Mohammad Altillawi et.al.|[2312.02029](http://arxiv.org/abs/2312.02029)|null|
|**2023-12-03**|**G2D: From Global to Dense Radiography Representation Learning via Vision-Language Pre-training**|Che Liu et.al.|[2312.01522](http://arxiv.org/abs/2312.01522)|null|
|**2023-12-01**|**Global Localization: Utilizing Relative Spatio-Temporal Geometric Constraints from Adjacent and Distant Cameras**|Mohammad Altillawi et.al.|[2312.00500](http://arxiv.org/abs/2312.00500)|null|
|**2023-11-28**|**Scene Summarization: Clustering Scene Videos into Spatially Diverse Frames**|Chao Chen et.al.|[2311.17940](http://arxiv.org/abs/2311.17940)|null|
|**2023-11-29**|**360Loc: A Dataset and Benchmark for Omnidirectional Visual Localization with Cross-device Queries**|Huajian Huang et.al.|[2311.17389](http://arxiv.org/abs/2311.17389)|null|
|**2023-11-27**|**Text2Loc: 3D Point Cloud Localization from Natural Language**|Yan Xia et.al.|[2311.15977](http://arxiv.org/abs/2311.15977)|null|
|**2023-11-27**|**Optimal Transport Aggregation for Visual Place Recognition**|Sergio Izquierdo et.al.|[2311.15937](http://arxiv.org/abs/2311.15937)|**[link](https://github.com/serizba/salad)**|
|**2023-11-22**|**Applications of Spiking Neural Networks in Visual Place Recognition**|Somayeh Hussaini et.al.|[2311.13186](http://arxiv.org/abs/2311.13186)|**[link](https://github.com/qvpr/vprsnn)**|
|**2023-11-21**|**Towards Accurate Loop Closure Detection in Semantic SLAM with 3D Semantic Covisibility Graphs**|Zhentian Qian et.al.|[2311.12245](http://arxiv.org/abs/2311.12245)|null|
|**2023-11-15**|**Flow reconstruction and particle characterization from inertial Lagrangian tracks**|Ke Zhou et.al.|[2311.09076](http://arxiv.org/abs/2311.09076)|null|
|**2023-11-13**|**VGSG: Vision-Guided Semantic-Group Network for Text-based Person Search**|Shuting He et.al.|[2311.07514](http://arxiv.org/abs/2311.07514)|null|
|**2023-11-06**|**Long-Term Invariant Local Features via Implicit Cross-Domain Correspondences**|Zador Pataki et.al.|[2311.03345](http://arxiv.org/abs/2311.03345)|null|
|**2023-12-30**|**LCPR: A Multi-Scale Attention-Based LiDAR-Camera Fusion Network for Place Recognition**|Zijie Zhou et.al.|[2311.03198](http://arxiv.org/abs/2311.03198)|**[link](https://github.com/ZhouZijie77/LCPR)**|
|**2023-11-06**|**FocusTune: Tuning Visual Localization through Focus-Guided Sampling**|Son Tung Nguyen et.al.|[2311.02872](http://arxiv.org/abs/2311.02872)|**[link](https://github.com/sontung/focus-tune)**|
|**2023-12-05**|**DINO-Mix: Enhancing Visual Place Recognition with Foundational Vision Model and Feature Mixing**|Gaoshuang Huang et.al.|[2311.00230](http://arxiv.org/abs/2311.00230)|**[link](https://github.com/GaoShuang98/DINO-Mix)**|
|**2023-10-27**|**Split Covariance Intersection Filter Based Visual Localization With Accurate AprilTag Map For Warehouse Robot Navigation**|Susu Fang et.al.|[2310.17879](http://arxiv.org/abs/2310.17879)|null|
|**2023-10-25**|**FoundLoc: Vision-based Onboard Aerial Localization in the Wild**|Yao He et.al.|[2310.16299](http://arxiv.org/abs/2310.16299)|null|
|**2023-10-24**|**Cross-view Self-localization from Synthesized Scene-graphs**|Ryogo Yamamoto et.al.|[2310.15504](http://arxiv.org/abs/2310.15504)|null|
|**2023-10-23**|**SONIC: Sonar Image Correspondence using Pose Supervised Learning for Imaging Sonars**|Samiran Gode et.al.|[2310.15023](http://arxiv.org/abs/2310.15023)|null|
|**2023-10-20**|**What you see is what you get: Experience ranking with deep neural dataset-to-dataset similarity for topological localisation**|Matthew Gadd et.al.|[2310.13622](http://arxiv.org/abs/2310.13622)|**[link](https://github.com/mttgdd/vdna-experience-selection)**|
|**2023-10-20**|**FMRT: Learning Accurate Feature Matching with Reconciliatory Transformer**|Xinyu Zhang et.al.|[2310.13605](http://arxiv.org/abs/2310.13605)|null|
|**2023-10-20**|**CylinderTag: An Accurate and Flexible Marker for Cylinder-Shape Objects Pose Estimation Based on Projective Invariants**|Shaoan Wang et.al.|[2310.13320](http://arxiv.org/abs/2310.13320)|**[link](https://github.com/wsakobe/cylindertag)**|
|**2023-10-16**|**Camera-LiDAR Fusion with Latent Contact for Place Recognition in Challenging Cross-Scenes**|Yan Pan et.al.|[2310.10371](http://arxiv.org/abs/2310.10371)|null|
|**2023-10-16**|**Autonomous Mapping and Navigation using Fiducial Markers and Pan-Tilt Camera for Assisting Indoor Mobility of Blind and Visually Impaired People**|Dharmateja Adapa et.al.|[2310.10290](http://arxiv.org/abs/2310.10290)|null|
|**2023-10-12**|**Jointly Optimized Global-Local Visual Localization of UAVs**|Haoling Li et.al.|[2310.08082](http://arxiv.org/abs/2310.08082)|null|
|**2023-10-10**|**Leveraging Neural Radiance Fields for Uncertainty-Aware Visual Localization**|Le Chen et.al.|[2310.06984](http://arxiv.org/abs/2310.06984)|null|
|**2023-10-10**|**Distillation Improves Visual Place Recognition for Low-Quality Queries**|Anbang Yang et.al.|[2310.06906](http://arxiv.org/abs/2310.06906)|null|
|**2023-10-10**|**3DS-SLAM: A 3D Object Detection based Semantic SLAM towards Dynamic Indoor Environments**|Ghanta Sai Krishna et.al.|[2310.06385](http://arxiv.org/abs/2310.06385)|null|
|**2023-10-09**|**Collaborative Visual Place Recognition**|Yiming Li et.al.|[2310.05541](http://arxiv.org/abs/2310.05541)|null|
|**2023-10-08**|**AANet: Aggregation and Alignment Network with Semi-hard Positive Sample Mining for Hierarchical Place Recognition**|Feng Lu et.al.|[2310.05184](http://arxiv.org/abs/2310.05184)|**[link](https://github.com/Lu-Feng/AANet)**|
|**2023-10-08**|**LocoNeRF: A NeRF-based Approach for Local Structure from Motion for Precise Localization**|Artem Nenashev et.al.|[2310.05134](http://arxiv.org/abs/2310.05134)|null|
|**2023-10-12**|**ClusVPR: Efficient Visual Place Recognition with Clustering-based Weighted Transformer**|Yifan Xu et.al.|[2310.04099](http://arxiv.org/abs/2310.04099)|null|
|**2023-10-04**|**Active Visual Localization for Multi-Agent Collaboration: A Data-Driven Approach**|Matthew Hanlon et.al.|[2310.02650](http://arxiv.org/abs/2310.02650)|null|
|**2023-10-02**|**Leveraging Cutting Edge Deep Learning Based Image Matching for Reconstructing a Large Scene from Sparse Images**|Georg Bökman et.al.|[2310.01092](http://arxiv.org/abs/2310.01092)|null|
|**2023-10-05**|**PlaceNav: Topological Navigation through Place Recognition**|Lauri Suomela et.al.|[2309.17260](http://arxiv.org/abs/2309.17260)|null|
|**2023-09-29**|**Segment Anything Model is a Good Teacher for Local Feature Learning**|Jingqian Wu et.al.|[2309.16992](http://arxiv.org/abs/2309.16992)|**[link](https://github.com/vignywang/samfeat)**|
|**2023-09-27**|**Learning Dense Flow Field for Highly-accurate Cross-view Camera Localization**|Zhenbo Song et.al.|[2309.15556](http://arxiv.org/abs/2309.15556)|null|
|**2023-09-29**|**Multimodal Dataset for Localization, Mapping and Crop Monitoring in Citrus Tree Farms**|Hanzhe Teng et.al.|[2309.15332](http://arxiv.org/abs/2309.15332)|**[link](https://github.com/ucr-robotics/citrus-farm-dataset)**|
|**2023-09-26**|**Language-EXtended Indoor SLAM (LEXIS): A Versatile System for Real-time Visual Scene Understanding**|Christina Kassab et.al.|[2309.15065](http://arxiv.org/abs/2309.15065)|null|
|**2023-09-26**|**HeLiPR: Heterogeneous LiDAR Dataset for inter-LiDAR Place Recognition under Spatial and Temporal Variations**|Minwoo Jung et.al.|[2309.14590](http://arxiv.org/abs/2309.14590)|null|
|**2023-09-20**|**2D-3D Pose Tracking with Multi-View Constraints**|Huai Yu et.al.|[2309.11335](http://arxiv.org/abs/2309.11335)|null|
|**2023-09-19**|**VPRTempo: A Fast Temporally Encoded Spiking Neural Network for Visual Place Recognition**|Adam D. Hines et.al.|[2309.10225](http://arxiv.org/abs/2309.10225)|**[link](https://github.com/QVPR/VPRTempo)**|
|**2023-09-18**|**DynaPix SLAM: A Pixel-Based Dynamic SLAM Approach**|Chenghao Xu et.al.|[2309.09879](http://arxiv.org/abs/2309.09879)|null|
|**2023-09-18**|**RaLF: Flow-based Global and Metric Radar Localization in LiDAR Maps**|Abhijeet Nayak et.al.|[2309.09875](http://arxiv.org/abs/2309.09875)|null|
|**2023-09-16**|**Efficient Object Rearrangement via Multi-view Fusion**|Dehao Huang et.al.|[2309.08994](http://arxiv.org/abs/2309.08994)|null|
|**2023-09-16**|**DynaMoN: Motion-Aware Fast And Robust Camera Localization for Dynamic NeRF**|Mert Asim Karaoglu et.al.|[2309.08927](http://arxiv.org/abs/2309.08927)|null|
|**2023-09-16**|**Outram: One-shot Global Localization via Triangulated Scene Graph and Global Outlier Pruning**|Pengyu Yin et.al.|[2309.08914](http://arxiv.org/abs/2309.08914)|**[link](https://github.com/pamphlett/outram)**|
|**2023-09-18**|**Prompting Segmentation with Sound is Generalizable Audio-Visual Source Localizer**|Yaoting Wang et.al.|[2309.07929](http://arxiv.org/abs/2309.07929)|null|
|**2023-09-14**|**EP2P-Loc: End-to-End 3D Point to 2D Pixel Localization for Large-Scale Visual Localization**|Minjung Kim et.al.|[2309.07471](http://arxiv.org/abs/2309.07471)|**[link](https://github.com/minnjung/ep2p-loc)**|
|**2023-09-13**|**RadarLCD: Learnable Radar-based Loop Closure Detection Pipeline**|Mirko Usuelli et.al.|[2309.07094](http://arxiv.org/abs/2309.07094)|null|
|**2023-09-05**|**Magnetic Navigation using Attitude-Invariant Magnetic Field Information for Loop Closure Detection**|Natalia Pavlasek et.al.|[2309.02394](http://arxiv.org/abs/2309.02394)|null|
|**2023-08-31**|**Pose-Graph Attentional Graph Neural Network for Lidar Place Recognition**|Milad Ramezani et.al.|[2309.00168](http://arxiv.org/abs/2309.00168)|null|
|**2023-08-27**|**Deep Learning for Visual Localization and Mapping: A Survey**|Changhao Chen et.al.|[2308.14039](http://arxiv.org/abs/2308.14039)|null|
|**2023-08-25**|**Enhancing Landmark Detection in Cluttered Real-World Scenarios with Vision Transformers**|Mohammad Javad Rajabi et.al.|[2308.13671](http://arxiv.org/abs/2308.13671)|null|
|**2023-09-14**|**Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond**|Jinze Bai et.al.|[2308.12966](http://arxiv.org/abs/2308.12966)|**[link](https://github.com/qwenlm/qwen-vl)**|
|**2023-08-24**|**VNI-Net: Vector Neurons-based Rotation-Invariant Descriptor for LiDAR Place Recognition**|Gengxuan Tian et.al.|[2308.12870](http://arxiv.org/abs/2308.12870)|null|
|**2023-08-23**|**OFVL-MS: Once for Visual Localization across Multiple Indoor Scenes**|Tao Xie et.al.|[2308.11928](http://arxiv.org/abs/2308.11928)|**[link](https://github.com/mooncake199809/ufvl-net)**|
|**2023-08-22**|**LDP-Feat: Image Features with Local Differential Privacy**|Francesco Pittaluga et.al.|[2308.11223](http://arxiv.org/abs/2308.11223)|null|
|**2023-08-21**|**EigenPlaces: Training Viewpoint Robust Models for Visual Place Recognition**|Gabriele Berton et.al.|[2308.10832](http://arxiv.org/abs/2308.10832)|**[link](https://github.com/gmberton/eigenplaces)**|
|**2023-09-04**|**3D Model-free Visual Localization System from Essential Matrix under Local Planar Motion**|Yanmei Jiao et.al.|[2308.09566](http://arxiv.org/abs/2308.09566)|null|
|**2023-08-10**|**KS-APR: Keyframe Selection for Robust Absolute Pose Regression**|Changkun Liu et.al.|[2308.05459](http://arxiv.org/abs/2308.05459)|null|
|**2023-08-09**|**GeoAdapt: Self-Supervised Test-Time Adaption in LiDAR Place Recognition Using Geometric Priors**|Joshua Knights et.al.|[2308.04638](http://arxiv.org/abs/2308.04638)|**[link](https://github.com/csiro-robotics/geoadapt)**|
|**2023-08-02**|**Improving Generalization of Synthetically Trained Sonar Image Descriptors for Underwater Place Recognition**|Ivano Donadi et.al.|[2308.01058](http://arxiv.org/abs/2308.01058)|**[link](https://github.com/ivano-donadi/sdpr)**|
|**2023-08-01**|**AnyLoc: Towards Universal Visual Place Recognition**|Nikhil Keetha et.al.|[2308.00688](http://arxiv.org/abs/2308.00688)|**[link](https://github.com/AnyLoc/AnyLoc)**|
|**2023-07-28**|**D2S: Representing local descriptors and global scene coordinates for camera relocalization**|Bach-Thuan Bui et.al.|[2307.15250](http://arxiv.org/abs/2307.15250)|null|
|**2023-07-26**|**Deep Robust Multi-Robot Re-localisation in Natural Environments**|Milad Ramezani et.al.|[2307.13950](http://arxiv.org/abs/2307.13950)|null|
|**2023-07-23**|**Scale jump-aware pose graph relaxation for monocular SLAM with re-initializations**|Runze Yuan et.al.|[2307.12326](http://arxiv.org/abs/2307.12326)|null|
|**2023-07-28**|**SACReg: Scene-Agnostic Coordinate Regression for Visual Localization**|Jerome Revaud et.al.|[2307.11702](http://arxiv.org/abs/2307.11702)|null|
|**2023-07-19**|**Lazy Visual Localization via Motion Averaging**|Siyan Dong et.al.|[2307.09981](http://arxiv.org/abs/2307.09981)|null|
|**2023-07-18**|**3D-SeqMOS: A Novel Sequential 3D Moving Object Segmentation in Autonomous Driving**|Qipeng Li et.al.|[2307.09044](http://arxiv.org/abs/2307.09044)|null|
|**2023-07-19**|**Similarity Min-Max: Zero-Shot Day-Night Domain Adaptation**|Rundong Luo et.al.|[2307.08779](http://arxiv.org/abs/2307.08779)|null|
|**2023-07-17**|**Divide&Classify: Fine-Grained Classification for City-Wide Visual Place Recognition**|Gabriele Trivigno et.al.|[2307.08417](http://arxiv.org/abs/2307.08417)|null|
|**2023-07-17**|**NDT-Map-Code: A 3D global descriptor for real-time loop closure detection in lidar SLAM**|Lizhou Liao et.al.|[2307.08221](http://arxiv.org/abs/2307.08221)|**[link](https://github.com/SlamCabbage/NDTMC)**|
|**2023-07-20**|**Boosting 3-DoF Ground-to-Satellite Camera Localization Accuracy via Geometry-Guided Cross-View Transformer**|Yujiao Shi et.al.|[2307.08015](http://arxiv.org/abs/2307.08015)|null|
|**2023-07-14**|**Multi-Session, Localization-oriented and Lightweight LiDAR Mapping Using Semantic Lines and Planes**|Zehuan Yu et.al.|[2307.07126](http://arxiv.org/abs/2307.07126)|null|
|**2023-07-11**|**ResMatch: Residual Attention Learning for Local Feature Matching**|Yuxin Deng et.al.|[2307.05180](http://arxiv.org/abs/2307.05180)|**[link](https://github.com/acuooooo/resmatch)**|
|**2023-07-10**|**RaPlace: Place Recognition for Imaging Radar using Radon Transform and Mutable Threshold**|Hyesu Jang et.al.|[2307.04321](http://arxiv.org/abs/2307.04321)|**[link](https://github.com/hyesu-jang/raplace)**|
|**2023-07-04**|**Unsupervised Quality Prediction for Improved Single-Frame and Weighted Sequential Visual Place Recognition**|Helen Carson et.al.|[2307.01464](http://arxiv.org/abs/2307.01464)|null|
|**2023-07-04**|**Learning Feature Matching via Matchable Keypoint-Assisted Graph Neural Network**|Zizhuo Li et.al.|[2307.01447](http://arxiv.org/abs/2307.01447)|null|
|**2023-07-03**|**Cross-modal Place Recognition in Image Databases using Event-based Sensors**|Xiang Ji et.al.|[2307.01047](http://arxiv.org/abs/2307.01047)|null|
|**2023-06-30**|**DisPlacing Objects: Improving Dynamic Vehicle Detection via Visual Place Recognition under Adverse Conditions**|Stephen Hausler et.al.|[2306.17536](http://arxiv.org/abs/2306.17536)|null|
|**2023-06-30**|**Locking On: Leveraging Dynamic Vehicle-Imposed Motion Constraints to Improve Visual Localization**|Stephen Hausler et.al.|[2306.17529](http://arxiv.org/abs/2306.17529)|null|
|**2023-07-04**|**Irregular Change Detection in Sparse Bi-Temporal Point Clouds using Learned Place Recognition Descriptors and Point-to-Voxel Comparison**|Nikolaos Stathoulopoulos et.al.|[2306.15416](http://arxiv.org/abs/2306.15416)|null|
|**2023-06-22**|**What to Learn: Features, Image Transformations, or Both?**|Yuxuan Chen et.al.|[2306.13040](http://arxiv.org/abs/2306.13040)|null|
|**2023-06-21**|**Off the Radar: Uncertainty-Aware Radar Place Recognition with Introspective Querying and Map Maintenance**|Jianhao Yuan et.al.|[2306.12556](http://arxiv.org/abs/2306.12556)|null|
|**2023-06-18**|**LiDAR-Based Place Recognition For Autonomous Driving: A Survey**|Pengcheng Shi et.al.|[2306.10561](http://arxiv.org/abs/2306.10561)|null|
|**2023-06-15**|**Yes, we CANN: Constrained Approximate Nearest Neighbors for local feature-based visual localization**|Dror Aiger et.al.|[2306.09012](http://arxiv.org/abs/2306.09012)|null|
|**2023-06-05**|**SelFLoc: Selective Feature Fusion for Large-scale Point Cloud-based Place Recognition**|Qibo Qiu et.al.|[2306.01205](http://arxiv.org/abs/2306.01205)|null|
|**2023-05-31**|**Probabilistic Uncertainty Quantification of Prediction Models with Application to Visual Localization**|Junan Chen et.al.|[2305.20044](http://arxiv.org/abs/2305.20044)|null|
|**2023-05-29**|**Synfeal: A Data-Driven Simulator for End-to-End Camera Localization**|Daniel Coelho et.al.|[2305.18260](http://arxiv.org/abs/2305.18260)|**[link](https://github.com/danielcoelho112/synfeal)**|
|**2023-05-29**|**Nanoscale visualization of the thermally-driven evolution of antiferromagnetic domains in FeTe thin films**|Shrinkhala Sharma et.al.|[2305.18197](http://arxiv.org/abs/2305.18197)|null|
|**2023-05-29**|**TReR: A Lightweight Transformer Re-Ranking Approach for 3D LiDAR Place Recognition**|Tiago Barros et.al.|[2305.18013](http://arxiv.org/abs/2305.18013)|null|
|**2023-05-27**|**Pentagon-Match (PMatch): Identification of View-Invariant Planar Feature for Local Feature Matching-Based Homography Estimation**|Yueh-Cheng Huang et.al.|[2305.17463](http://arxiv.org/abs/2305.17463)|null|
|**2023-05-24**|**Robust Imaging Sonar-based Place Recognition and Localization in Underwater Environments**|Hogyun Kim et.al.|[2305.14773](http://arxiv.org/abs/2305.14773)|**[link](https://github.com/sparolab/sonar_context)**|
|**2023-05-23**|**Leveraging BEV Representation for 360-degree Visual Place Recognition**|Xuecheng Xu et.al.|[2305.13814](http://arxiv.org/abs/2305.13814)|**[link](https://github.com/maverickpeter/vdisco)**|
|**2023-05-20**|**DAC: Detector-Agnostic Spatial Covariances for Deep Local Features**|Javier Tirado-Garín et.al.|[2305.12250](http://arxiv.org/abs/2305.12250)|**[link](https://github.com/javrtg/dac)**|
|**2023-05-19**|**Learning Sequence Descriptor based on Spatiotemporal Attention for Visual Place Recognition**|Fenglin Zhang et.al.|[2305.11467](http://arxiv.org/abs/2305.11467)|null|
|**2023-05-13**|**Illumination-insensitive Binary Descriptor for Visual Measurement Based on Local Inter-patch Invariance**|Xinyu Lin et.al.|[2305.07943](http://arxiv.org/abs/2305.07943)|**[link](https://github.com/roylin1229/IIB_descriptor)**|
|**2023-05-11**|**Foundations of Spatial Perception for Robotics: Hierarchical Representations and Real-time Systems**|Nathan Hughes et.al.|[2305.07154](http://arxiv.org/abs/2305.07154)|**[link](https://github.com/mit-spark/hydra)**|
|**2023-05-09**|**Visual Place Recognition with Low-Resolution Images**|Mihnea-Alexandru Tomita et.al.|[2305.05776](http://arxiv.org/abs/2305.05776)|null|
|**2023-05-09**|**An Evaluation and Ranking of Different Voting Schemes for Improved Visual Place Recognition**|Maria Waheed et.al.|[2305.05705](http://arxiv.org/abs/2305.05705)|null|
|**2023-05-09**|**ColonMapper: topological mapping and localization for colonoscopy**|Javier Morlana et.al.|[2305.05546](http://arxiv.org/abs/2305.05546)|null|
|**2023-05-09**|**Eiffel Tower: A Deep-Sea Underwater Dataset for Long-Term Visual Localization**|Clémentin Boittiaux et.al.|[2305.05301](http://arxiv.org/abs/2305.05301)|**[link](https://github.com/clementinboittiaux/sfm-pipeline)**|
|**2023-05-09**|**Patch-DrosoNet: Classifying Image Partitions With Fly-Inspired Models For Lightweight Visual Place Recognition**|Bruno Arcanjo et.al.|[2305.05256](http://arxiv.org/abs/2305.05256)|null|
|**2023-05-08**|**Hierarchical Visual Localization Based on Sparse Feature Pyramid for Adaptive Reduction of Keypoint Map Size**|Andrei Potapov et.al.|[2305.04856](http://arxiv.org/abs/2305.04856)|null|
|**2023-05-08**|**Privacy-Preserving Representations are not Enough -- Recovering Scene Content from Camera Poses**|Kunal Chelani et.al.|[2305.04603](http://arxiv.org/abs/2305.04603)|**[link](https://github.com/kunalchelani/objectpositioningfromposes)**|
|**2023-05-05**|**HSCNet++: Hierarchical Scene Coordinate Classification and Regression for Visual Localization with Transformer**|Shuzhe Wang et.al.|[2305.03595](http://arxiv.org/abs/2305.03595)|null|
|**2023-05-03**|**Learning-based Relational Object Matching Across Views**|Cathrin Elich et.al.|[2305.02398](http://arxiv.org/abs/2305.02398)|null|
|**2023-05-03**|**AV-SAM: Segment Anything Model Meets Audio-Visual Localization and Segmentation**|Shentong Mo et.al.|[2305.01836](http://arxiv.org/abs/2305.01836)|null|
|**2023-04-28**|**SFD2: Semantic-guided Feature Detection and Description**|Fei Xue et.al.|[2304.14845](http://arxiv.org/abs/2304.14845)|**[link](https://github.com/feixue94/sfd2)**|
|**2023-04-26**|**Hydra-Multi: Collaborative Online Construction of 3D Scene Graphs with Multi-Robot Teams**|Yun Chang et.al.|[2304.13487](http://arxiv.org/abs/2304.13487)|null|
|**2023-04-23**|**IDLL: Inverse Depth Line based Visual Localization in Challenging Environments**|Wanting Li et.al.|[2304.11748](http://arxiv.org/abs/2304.11748)|null|
|**2023-04-17**|**(LC) $^2$ : LiDAR-Camera Loop Constraints For Cross-Modal Place Recognition**|Alex Junho Lee et.al.|[2304.08660](http://arxiv.org/abs/2304.08660)|null|
|**2023-04-17**|**NeRF-Loc: Visual Localization with Conditional Neural Radiance Field**|Jianlin Liu et.al.|[2304.07979](http://arxiv.org/abs/2304.07979)|**[link](https://github.com/jenningsl/nerf-loc)**|
|**2023-04-16**|**Language Guided Local Infiltration for Interactive Image Retrieval**|Fuxiang Huang et.al.|[2304.07747](http://arxiv.org/abs/2304.07747)|null|
|**2023-04-16**|**Long-term Visual Localization with Mobile Sensors**|Shen Yan et.al.|[2304.07691](http://arxiv.org/abs/2304.07691)|null|
|**2023-04-14**|**CoPR: Towards Accurate Visual Localization With Continuous Place-descriptor Regression**|Mubariz Zaffar et.al.|[2304.07426](http://arxiv.org/abs/2304.07426)|null|
|**2023-04-14**|**FM-Loc: Using Foundation Models for Improved Vision-based Localization**|Reihaneh Mirjalili et.al.|[2304.07058](http://arxiv.org/abs/2304.07058)|null|
|**2023-04-17**|**You are here! Finding position and orientation on a 2D map from a single image: The Flatlandia localization problem and dataset**|Matteo Toso et.al.|[2304.06373](http://arxiv.org/abs/2304.06373)|**[link](https://github.com/IIT-PAVIS/Flatlandia)**|
|**2023-04-12**|**Visual Localization using Imperfect 3D Models from the Internet**|Vojtech Panek et.al.|[2304.05947](http://arxiv.org/abs/2304.05947)|**[link](https://github.com/v-pnk/cadloc)**|
|**2023-04-12**|**Are Local Features All You Need for Cross-Domain Visual Place Recognition?**|Giovanni Barbarani et.al.|[2304.05887](http://arxiv.org/abs/2304.05887)|**[link](https://github.com/gbarbarani/re-ranking-for-vpr)**|
|**2023-04-12**|**SGL: Structure Guidance Learning for Camera Localization**|Xudong Zhang et.al.|[2304.05571](http://arxiv.org/abs/2304.05571)|null|
|**2023-04-14**|**Loop Closure Detection Based on Object-level Spatial Layout and Semantic Consistency**|Xingwu Ji et.al.|[2304.05146](http://arxiv.org/abs/2304.05146)|**[link](https://github.com/jixingwu/ss-lcd)**|
|**2023-04-08**|**SGIDN-LCD: An Appearance-based Loop Closure Detection Algorithm using Superpixel Grids and Incremental Dynamic Nodes**|Baosheng Zhang et.al.|[2304.03872](http://arxiv.org/abs/2304.03872)|null|
|**2023-04-06**|**$R^{2}$Former: Unified $R$etrieval and $R$ eranking Transformer for Place Recognition**|Sijie Zhu et.al.|[2304.03410](http://arxiv.org/abs/2304.03410)|null|
|**2023-04-06**|**Distributed formation-enforcing control for UAVs robust to observation noise in relative pose measurements**|Viktor Walter et.al.|[2304.03057](http://arxiv.org/abs/2304.03057)|**[link](https://github.com/ctu-mrs/difec-ron)**|
|**2023-04-04**|**OrienterNet: Visual Localization in 2D Public Maps with Neural Matching**|Paul-Edouard Sarlin et.al.|[2304.02009](http://arxiv.org/abs/2304.02009)|null|
|**2023-04-17**|**NPR: Nocturnal Place Recognition in Streets**|Bingxi Liu et.al.|[2304.00276](http://arxiv.org/abs/2304.00276)|null|
|**2023-03-31**|**CrossLoc3D: Aerial-Ground Cross-Source 3D Place Recognition**|Tianrui Guan et.al.|[2303.17778](http://arxiv.org/abs/2303.17778)|null|
|**2023-03-30**|**3D Line Mapping Revisited**|Shaohui Liu et.al.|[2303.17504](http://arxiv.org/abs/2303.17504)|**[link](https://github.com/cvg/limap)**|
|**2023-03-24**|**A-MuSIC: An Adaptive Ensemble System For Visual Place Recognition In Changing Environments**|Bruno Arcanjo et.al.|[2303.14247](http://arxiv.org/abs/2303.14247)|null|
|**2023-03-24**|**PanoVPR: Towards Unified Perspective-to-Equirectangular Visual Place Recognition via Sliding Windows across the Panoramic View**|Ze Shi et.al.|[2303.14095](http://arxiv.org/abs/2303.14095)|**[link](https://github.com/zafirshi/panovpr)**|
|**2023-03-24**|**CCL: Continual Contrastive Learning for LiDAR Place Recognition**|Jiafeng Cui et.al.|[2303.13952](http://arxiv.org/abs/2303.13952)|**[link](https://github.com/cloudcjf/ccl)**|
|**2023-03-25**|**Data-efficient Large Scale Place Recognition with Graded Similarity Supervision**|Maria Leyva-Vallina et.al.|[2303.11739](http://arxiv.org/abs/2303.11739)|**[link](https://github.com/marialeyvallina/generalized_contrastive_loss)**|
|**2023-03-19**|**Deep Declarative Dynamic Time Warping for End-to-End Learning of Alignment Paths**|Ming Xu et.al.|[2303.10778](http://arxiv.org/abs/2303.10778)|**[link](https://github.com/mingu6/declarativedtw)**|
|**2023-03-16**|**Metric-Free Exploration for Topological Mapping by Task and Motion Imitation in Feature Space**|Yuhang He et.al.|[2303.09192](http://arxiv.org/abs/2303.09192)|null|
|**2023-04-04**|**PATS: Patch Area Transportation with Subdivision for Local Feature Matching**|Junjie Ni et.al.|[2303.07700](http://arxiv.org/abs/2303.07700)|null|
|**2023-03-13**|**OverlapNetVLAD: A Coarse-to-Fine Framework for LiDAR-based Place Recognition**|Chencan Fu et.al.|[2303.06881](http://arxiv.org/abs/2303.06881)|**[link](https://github.com/fcchit/overlapnetvlad)**|
|**2023-03-11**|**Necessity Feature Correspondence Estimation for Large-scale Global Place Recognition and Relocalization**|Kyeongsu Kang et.al.|[2303.06308](http://arxiv.org/abs/2303.06308)|null|
|**2023-03-09**|**Dominating Set Database Selection for Visual Place Recognition**|Anastasiia Kornilova et.al.|[2303.05123](http://arxiv.org/abs/2303.05123)|null|
|**2023-03-06**|**Visual Place Recognition: A Tutorial**|Stefan Schubert et.al.|[2303.03281](http://arxiv.org/abs/2303.03281)|**[link](https://github.com/stschubert/vpr_tutorial)**|
|**2023-03-06**|**Improving Transformer-based Image Matching by Cascaded Capturing Spatially Informative Keypoints**|Chenjie Cao et.al.|[2303.02885](http://arxiv.org/abs/2303.02885)|null|
|**2023-03-09**|**Self-Supervised Learning for Place Representation Generalization across Appearance Changes**|Mohamed Adel Musallam et.al.|[2303.02370](http://arxiv.org/abs/2303.02370)|null|
|**2023-03-03**|**MixVPR: Feature Mixing for Visual Place Recognition**|Amar Ali-bey et.al.|[2303.02190](http://arxiv.org/abs/2303.02190)|**[link](https://github.com/amaralibey/mixvpr)**|
|**2023-03-02**|**BPT: Binary Point Cloud Transformer for Place Recognition**|Zhixing Hou et.al.|[2303.01166](http://arxiv.org/abs/2303.01166)|null|
|**2023-03-02**|**I2P-Rec: Recognizing Images on Large-scale Point Cloud Maps through Bird's Eye View Projections**|Yixuan Li et.al.|[2303.01043](http://arxiv.org/abs/2303.01043)|null|
|**2023-03-01**|**A Complementarity-Based Switch-Fuse System for Improved Visual Place Recognition**|Maria Waheed et.al.|[2303.00714](http://arxiv.org/abs/2303.00714)|null|
|**2023-03-01**|**ORCHNet: A Robust Global Feature Aggregation approach for 3D LiDAR-based Place recognition in Orchards**|T. Barros et.al.|[2303.00477](http://arxiv.org/abs/2303.00477)|**[link](https://github.com/cybonic/orchnet)**|
|**2023-03-23**|**Renderable Neural Radiance Map for Visual Navigation**|Obin Kwon et.al.|[2303.00304](http://arxiv.org/abs/2303.00304)|null|
|**2023-03-01**|**Region Prediction for Efficient Robot Localization on Large Maps**|Matteo Scucchia et.al.|[2303.00295](http://arxiv.org/abs/2303.00295)|null|
|**2023-03-15**|**BEVPlace: Learning LiDAR-based Place Recognition using Bird's Eye View Images**|Lun Luo et.al.|[2302.14325](http://arxiv.org/abs/2302.14325)|**[link](https://github.com/zjuluolun/bevplace)**|
|**2023-02-28**|**Global Proxy-based Hard Mining for Visual Place Recognition**|Amar Ali-bey et.al.|[2302.14217](http://arxiv.org/abs/2302.14217)|**[link](https://github.com/amaralibey/gpm)**|
|**2023-02-26**|**Data-Efficient Sequence-Based Visual Place Recognition with Highly Compressed JPEG Images**|Mihnea-Alexandru Tomita et.al.|[2302.13314](http://arxiv.org/abs/2302.13314)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Feature

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-17**|**To deform or not: treatment-aware longitudinal registration for breast DCE-MRI during neoadjuvant chemotherapy via unsupervised keypoints detection**|Luyi Han et.al.|[2401.09336](http://arxiv.org/abs/2401.09336)|**[link](https://github.com/fiy2w/treatment-aware-longitudinal-registration)**|
|**2024-01-08**|**Flowmind2Digital: The First Comprehensive Flowmind Recognition and Conversion Approach**|Huanyu Liu et.al.|[2401.03742](http://arxiv.org/abs/2401.03742)|null|
|**2024-01-02**|**6D-Diff: A Keypoint Diffusion Framework for 6D Object Pose Estimation**|Li Xu et.al.|[2401.00029](http://arxiv.org/abs/2401.00029)|null|
|**2023-12-27**|**Bezier-based Regression Feature Descriptor for Deformable Linear Objects**|Fangqing Chen et.al.|[2312.16502](http://arxiv.org/abs/2312.16502)|null|
|**2023-12-24**|**Residual Learning for Image Point Descriptors**|Rashik Shrestha et.al.|[2312.15471](http://arxiv.org/abs/2312.15471)|null|
|**2023-12-22**|**BonnBeetClouds3D: A Dataset Towards Point Cloud-based Organ-level Phenotyping of Sugar Beet Plants under Field Conditions**|Elias Marks et.al.|[2312.14706](http://arxiv.org/abs/2312.14706)|null|
|**2023-12-19**|**Adaptive Distribution Masked Autoencoders for Continual Test-Time Adaptation**|Jiaming Liu et.al.|[2312.12480](http://arxiv.org/abs/2312.12480)|null|
|**2023-12-19**|**An effective image copy-move forgery detection using entropy image**|Zhaowei Lu et.al.|[2312.11793](http://arxiv.org/abs/2312.11793)|null|
|**2023-12-11**|**VoxelKP: A Voxel-based Network Architecture for Human Keypoint Estimation in LiDAR Data**|Jian Shi et.al.|[2312.08871](http://arxiv.org/abs/2312.08871)|**[link](https://github.com/shijianjian/voxelkp)**|
|**2023-12-11**|**Keypoint-based Stereophotoclinometry for Characterizing and Navigating Small Bodies: A Factor Graph Approach**|Travis Driver et.al.|[2312.06865](http://arxiv.org/abs/2312.06865)|null|
|**2023-12-01**|**Tracking Object Positions in Reinforcement Learning: A Metric for Keypoint Detection (extended version)**|Emma Cramer et.al.|[2312.00592](http://arxiv.org/abs/2312.00592)|null|
|**2023-11-30**|**Utilizing Radiomic Feature Analysis For Automated MRI Keypoint Detection: Enhancing Graph Applications**|Sahar Almahfouz Nasser et.al.|[2311.18281](http://arxiv.org/abs/2311.18281)|null|
|**2023-11-29**|**Back to 3D: Few-Shot 3D Keypoint Detection with Back-Projected 2D Features**|Thomas Wimmer et.al.|[2311.18113](http://arxiv.org/abs/2311.18113)|null|
|**2023-11-28**|**Diffusion 3D Features (Diff3F): Decorating Untextured Shapes with Distilled Semantic Features**|Niladri Shekhar Dutt et.al.|[2311.17024](http://arxiv.org/abs/2311.17024)|null|
|**2023-11-28**|**Riemannian Self-Attention Mechanism for SPD Networks**|Rui Wang et.al.|[2311.16738](http://arxiv.org/abs/2311.16738)|null|
|**2023-11-27**|**A manometric feature descriptor with linear-SVM to distinguish esophageal contraction vigor**|Jialin Liu et.al.|[2311.15609](http://arxiv.org/abs/2311.15609)|null|
|**2023-11-21**|**Instance-aware 3D Semantic Segmentation powered by Shape Generators and Classifiers**|Bo Sun et.al.|[2311.12291](http://arxiv.org/abs/2311.12291)|null|
|**2023-11-20**|**CurriculumLoc: Enhancing Cross-Domain Geolocalization through Multi-Stage Refinement**|Boni Hu et.al.|[2311.11604](http://arxiv.org/abs/2311.11604)|**[link](https://github.com/npupilab/curriculumloc)**|
|**2023-11-17**|**Video-based Sequential Bayesian Homography Estimation for Soccer Field Registration**|Paul J. Claasen et.al.|[2311.10361](http://arxiv.org/abs/2311.10361)|null|
|**2023-11-13**|**Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning**|Tomáš Kunzo et.al.|[2311.07398](http://arxiv.org/abs/2311.07398)|null|
|**2023-11-11**|**CVTHead: One-shot Controllable Head Avatar with Vertex-feature Transformer**|Haoyu Ma et.al.|[2311.06443](http://arxiv.org/abs/2311.06443)|**[link](https://github.com/howiema/cvthead)**|
|**2023-11-08**|**3D Pose Estimation of Tomato Peduncle Nodes using Deep Keypoint Detection and Point Cloud**|Jianchao Ci et.al.|[2311.04699](http://arxiv.org/abs/2311.04699)|null|
|**2023-11-06**|**TAMPAR: Visual Tampering Detection for Parcel Logistics in Postal Supply Chains**|Alexander Naumann et.al.|[2311.03124](http://arxiv.org/abs/2311.03124)|**[link](https://github.com/a-nau/tampar)**|
|**2023-11-06**|**An invariant feature extraction for multi-modal images matching**|Chenzhong Gao et.al.|[2311.02842](http://arxiv.org/abs/2311.02842)|null|
|**2023-10-20**|**Feature Selection and Hyperparameter Fine-tuning in Artificial Neural Networks for Wood Quality Classification**|Mateus Roder et.al.|[2310.13490](http://arxiv.org/abs/2310.13490)|null|
|**2023-10-12**|**UniPose: Detecting Any Keypoints**|Jie Yang et.al.|[2310.08530](http://arxiv.org/abs/2310.08530)|**[link](https://github.com/IDEA-Research/UniPose)**|
|**2023-10-10**|**l-dyno: framework to learn consistent visual features using robot's motion**|Kartikeya Singh et.al.|[2310.06249](http://arxiv.org/abs/2310.06249)|null|
|**2023-12-11**|**Open-Vocabulary Animal Keypoint Detection with Semantic-feature Matching**|Hao Zhang et.al.|[2310.05056](http://arxiv.org/abs/2310.05056)|null|
|**2023-10-13**|**H-InDex: Visual Reinforcement Learning with Hand-Informed Representations for Dexterous Manipulation**|Yanjie Ze et.al.|[2310.01404](http://arxiv.org/abs/2310.01404)|null|
|**2023-10-04**|**Self-supervised Learning of Contextualized Local Visual Embeddings**|Thalles Santos Silva et.al.|[2310.00527](http://arxiv.org/abs/2310.00527)|**[link](https://github.com/sthalles/clove)**|
|**2023-10-22**|**ObVi-SLAM: Long-Term Object-Visual SLAM**|Amanda Adkins et.al.|[2309.15268](http://arxiv.org/abs/2309.15268)|null|
|**2023-09-19**|**LiDAR-Generated Images Derived Keypoints Assisted Point Cloud Registration Scheme in Odometry Estimation**|Haizhou Zhang et.al.|[2309.10436](http://arxiv.org/abs/2309.10436)|**[link](https://github.com/tiers/ws-lidar-as-camera-odom)**|
|**2023-09-18**|**RIDE: Self-Supervised Learning of Rotation-Equivariant Keypoint Detection and Invariant Description for Endoscopy**|Mert Asim Karaoglu et.al.|[2309.09563](http://arxiv.org/abs/2309.09563)|null|
|**2023-09-17**|**CryoAlign: feature-based method for global and local 3D alignment of EM density maps**|Bintao He et.al.|[2309.09217](http://arxiv.org/abs/2309.09217)|null|
|**2023-09-14**|**EP2P-Loc: End-to-End 3D Point to 2D Pixel Localization for Large-Scale Visual Localization**|Minjung Kim et.al.|[2309.07471](http://arxiv.org/abs/2309.07471)|**[link](https://github.com/minnjung/ep2p-loc)**|
|**2023-09-09**|**Mirror-Aware Neural Humans**|Daniel Ajisafe et.al.|[2309.04750](http://arxiv.org/abs/2309.04750)|null|
|**2023-09-07**|**InstructDiffusion: A Generalist Modeling Interface for Vision Tasks**|Zigang Geng et.al.|[2309.03895](http://arxiv.org/abs/2309.03895)|null|
|**2023-09-04**|**SKoPe3D: A Synthetic Dataset for Vehicle Keypoint Perception in 3D from Traffic Monitoring Cameras**|Himanshu Pahadia et.al.|[2309.01324](http://arxiv.org/abs/2309.01324)|null|
|**2023-09-12**|**Improving the matching of deformable objects by learning to detect keypoints**|Felipe Cadar et.al.|[2309.00434](http://arxiv.org/abs/2309.00434)|**[link](https://github.com/verlab/learningtodetect_prl_2023)**|
|**2023-12-12**|**SportsSloMo: A New Benchmark and Baselines for Human-centric Video Frame Interpolation**|Jiaben Chen et.al.|[2308.16876](http://arxiv.org/abs/2308.16876)|null|
|**2023-12-04**|**Learning Structure-from-Motion with Graph Attention Networks**|Lucas Brynte et.al.|[2308.15984](http://arxiv.org/abs/2308.15984)|null|
|**2023-08-29**|**A lightweight 3D dense facial landmark estimation model from position map data**|Shubhajit Basak et.al.|[2308.15170](http://arxiv.org/abs/2308.15170)|**[link](https://github.com/shubhajitbasak/dense3dfacelandmarks)**|
|**2023-08-27**|**Automatic coarse co-registration of point clouds from diverse scan geometries: a test of detectors and descriptors**|Francesco Pirotti et.al.|[2308.14047](http://arxiv.org/abs/2308.14047)|null|
|**2023-08-24**|**VNI-Net: Vector Neurons-based Rotation-Invariant Descriptor for LiDAR Place Recognition**|Gengxuan Tian et.al.|[2308.12870](http://arxiv.org/abs/2308.12870)|null|
|**2023-08-22**|**LDP-Feat: Image Features with Local Differential Privacy**|Francesco Pittaluga et.al.|[2308.11223](http://arxiv.org/abs/2308.11223)|null|
|**2023-08-20**|**Neural Interactive Keypoint Detection**|Jie Yang et.al.|[2308.10174](http://arxiv.org/abs/2308.10174)|**[link](https://github.com/idea-research/click-pose)**|
|**2023-08-19**|**ClothesNet: An Information-Rich 3D Garment Model Repository with Simulated Clothes Environment**|Bingyang Zhou et.al.|[2308.09987](http://arxiv.org/abs/2308.09987)|null|
|**2023-12-11**|**DeDoDe: Detect, Don't Describe -- Describe, Don't Detect for Local Feature Matching**|Johan Edstedt et.al.|[2308.08479](http://arxiv.org/abs/2308.08479)|**[link](https://github.com/parskatt/dedode)**|
|**2023-08-15**|**CoDeF: Content Deformation Fields for Temporally Consistent Video Processing**|Hao Ouyang et.al.|[2308.07926](http://arxiv.org/abs/2308.07926)|**[link](https://github.com/qiuyu96/codef)**|
|**2023-08-15**|**ChartDETR: A Multi-shape Detection Network for Visual Chart Recognition**|Wenyuan Xue et.al.|[2308.07743](http://arxiv.org/abs/2308.07743)|null|
|**2023-08-14**|**DELO: Deep Evidential LiDAR Odometry using Partial Optimal Transport**|Sk Aziz Ali et.al.|[2308.07153](http://arxiv.org/abs/2308.07153)|null|
|**2023-08-14**|**2D3D-MATR: 2D-3D Matching Transformer for Detection-free Registration between Images and Point Clouds**|Minhao Li et.al.|[2308.05667](http://arxiv.org/abs/2308.05667)|**[link](https://github.com/minhaolee/2d3dmatr)**|
|**2023-08-02**|**Automated Hit-frame Detection for Badminton Match Analysis**|Yu-Hang Chien et.al.|[2307.16000](http://arxiv.org/abs/2307.16000)|**[link](https://github.com/arthur900530/Automated-Hit-frame-Detection-for-Badminton-Match-Analysis)**|
|**2023-07-25**|**Mini-PointNetPlus: a local feature descriptor in deep learning model for 3d environment perception**|Chuanyu Luo et.al.|[2307.13300](http://arxiv.org/abs/2307.13300)|null|
|**2023-07-21**|**Reverse Knowledge Distillation: Training a Large Model using a Small One for Retinal Image Matching on Limited Data**|Sahar Almahfouz Nasser et.al.|[2307.10698](http://arxiv.org/abs/2307.10698)|**[link](https://github.com/SaharAlmahfouzNasser/MeDAL-Retina)**|
|**2023-07-19**|**SAMConvex: Fast Discrete Optimization for CT Registration using Self-supervised Anatomical Embedding and Correlation Pyramid**|Zi Li et.al.|[2307.09727](http://arxiv.org/abs/2307.09727)|**[link](https://github.com/alibaba-damo-academy/samconvex)**|
|**2023-07-01**|**SyMFM6D: Symmetry-aware Multi-directional Fusion for Multi-View 6D Object Pose Estimation**|Fabian Duffhauss et.al.|[2307.00306](http://arxiv.org/abs/2307.00306)|**[link](https://github.com/boschresearch/symfm6d)**|
|**2023-06-27**|**Detector-Free Structure from Motion**|Xingyi He et.al.|[2306.15669](http://arxiv.org/abs/2306.15669)|**[link](https://github.com/zju3dv/DetectorFreeSfM)**|
|**2023-06-26**|**CLERA: A Unified Model for Joint Cognitive Load and Eye Region Analysis in the Wild**|Li Ding et.al.|[2306.15073](http://arxiv.org/abs/2306.15073)|null|
|**2023-06-28**|**Topology Repairing of Disconnected Pulmonary Airways and Vessels: Baselines and a Dataset**|Ziqiao Weng et.al.|[2306.07089](http://arxiv.org/abs/2306.07089)|**[link](https://github.com/m3dv/pulmonary-tree-repairing)**|
|**2023-06-07**|**Learning Probabilistic Coordinate Fields for Robust Correspondences**|Weiyue Zhao et.al.|[2306.04231](http://arxiv.org/abs/2306.04231)|null|
|**2023-06-03**|**LDEB -- Label Digitization with Emotion Binarization and Machine Learning for Emotion Recognition in Conversational Dialogues**|Amitabha Dey et.al.|[2306.02193](http://arxiv.org/abs/2306.02193)|null|
|**2023-06-02**|**Self-supervised Interest Point Detection and Description for Fisheye and Perspective Images**|Marcela Mera-Trujillo et.al.|[2306.01938](http://arxiv.org/abs/2306.01938)|null|
|**2023-06-01**|**A Probabilistic Relaxation of the Two-Stage Object Pose Estimation Paradigm**|Onur Beker et.al.|[2306.00892](http://arxiv.org/abs/2306.00892)|null|
|**2023-05-30**|**Align, Perturb and Decouple: Toward Better Leverage of Difference Information for RSI Change Detection**|Supeng Wang et.al.|[2305.18714](http://arxiv.org/abs/2305.18714)|**[link](https://github.com/wangsp1999/cd-research)**|
|**2023-05-23**|**Diffusion Hyperfeatures: Searching Through Time and Space for Semantic Correspondence**|Grace Luo et.al.|[2305.14334](http://arxiv.org/abs/2305.14334)|null|
|**2023-05-15**|**Non-Separable Multi-Dimensional Network Flows for Visual Computing**|Viktoria Ehm et.al.|[2305.08628](http://arxiv.org/abs/2305.08628)|null|
|**2023-05-13**|**Illumination-insensitive Binary Descriptor for Visual Measurement Based on Local Inter-patch Invariance**|Xinyu Lin et.al.|[2305.07943](http://arxiv.org/abs/2305.07943)|**[link](https://github.com/roylin1229/IIB_descriptor)**|
|**2023-05-05**|**HD2Reg: Hierarchical Descriptors and Detectors for Point Cloud Registration**|Canhui Tang et.al.|[2305.03487](http://arxiv.org/abs/2305.03487)|**[link](https://github.com/hui-design/hd2reg)**|
|**2023-04-17**|**Human Pose Estimation in Monocular Omnidirectional Top-View Images**|Jingrui Yu et.al.|[2304.08186](http://arxiv.org/abs/2304.08186)|null|
|**2023-04-14**|**CoPR: Towards Accurate Visual Localization With Continuous Place-descriptor Regression**|Mubariz Zaffar et.al.|[2304.07426](http://arxiv.org/abs/2304.07426)|null|
|**2023-04-12**|**SiLK -- Simple Learned Keypoints**|Pierre Gleize et.al.|[2304.06194](http://arxiv.org/abs/2304.06194)|**[link](https://github.com/facebookresearch/silk)**|
|**2023-04-06**|**From Saliency to DINO: Saliency-guided Vision Transformer for Few-shot Keypoint Detection**|Changsheng Lu et.al.|[2304.03140](http://arxiv.org/abs/2304.03140)|null|
|**2023-03-29**|**NerVE: Neural Volumetric Edges for Parametric Curve Extraction from Point Cloud**|Xiangyu Zhu et.al.|[2303.16465](http://arxiv.org/abs/2303.16465)|null|
|**2023-03-24**|**PanoVPR: Towards Unified Perspective-to-Equirectangular Visual Place Recognition via Sliding Windows across the Panoramic View**|Ze Shi et.al.|[2303.14095](http://arxiv.org/abs/2303.14095)|**[link](https://github.com/zafirshi/panovpr)**|
|**2023-03-23**|**Semantic Image Attack for Visual Model Diagnosis**|Jinqi Luo et.al.|[2303.13010](http://arxiv.org/abs/2303.13010)|null|
|**2023-03-22**|**Object Pose Estimation with Statistical Guarantees: Conformal Keypoint Detection and Geometric Uncertainty Propagation**|Heng Yang et.al.|[2303.12246](http://arxiv.org/abs/2303.12246)|**[link](https://github.com/nvlabs/conformalkeypoint)**|
|**2023-05-29**|**RN-Net: Reservoir Nodes-Enabled Neuromorphic Vision Sensing Network**|Sangmin Yoo et.al.|[2303.10770](http://arxiv.org/abs/2303.10770)|null|
|**2023-03-17**|**ShaRPy: Shape Reconstruction and Hand Pose Estimation from RGB-D with Uncertainty**|Vanessa Wirth et.al.|[2303.10042](http://arxiv.org/abs/2303.10042)|null|
|**2023-03-15**|**Descriptor Distillation for Efficient Multi-Robot SLAM**|Xiyue Guo et.al.|[2303.08420](http://arxiv.org/abs/2303.08420)|null|
|**2023-03-15**|**From Local Binary Patterns to Pixel Difference Networks for Efficient Visual Representation Learning**|Zhuo Su et.al.|[2303.08414](http://arxiv.org/abs/2303.08414)|null|
|**2023-05-01**|**KGNv2: Separating Scale and Pose Prediction for Keypoint-based 6-DoF Grasp Synthesis on RGB-D input**|Yiye Chen et.al.|[2303.05617](http://arxiv.org/abs/2303.05617)|**[link](https://github.com/ivalab/kgn)**|
|**2023-03-07**|**External Camera-based Mobile Robot Pose Estimation for Collaborative Perception with Smart Edge Sensors**|Simon Bultmann et.al.|[2303.03797](http://arxiv.org/abs/2303.03797)|null|
|**2023-02-26**|**PaRK-Detect: Towards Efficient Multi-Task Satellite Imagery Road Extraction via Patch-Wise Keypoints Detection**|Shenwei Xie et.al.|[2302.13263](http://arxiv.org/abs/2302.13263)|null|
|**2023-02-24**|**Hybrid machine-learned homogenization: Bayesian data mining and convolutional neural networks**|Julian Lißner et.al.|[2302.12545](http://arxiv.org/abs/2302.12545)|null|
|**2023-02-21**|**Deep Reinforcement Learning Based on Local GNN for Goal-conditioned Deformable Object Rearranging**|Yuhong Deng et.al.|[2302.10446](http://arxiv.org/abs/2302.10446)|null|
|**2023-02-12**|**A Correct-and-Certify Approach to Self-Supervise Object Pose Estimators via Ensemble Self-Training**|Jingnan Shi et.al.|[2302.06019](http://arxiv.org/abs/2302.06019)|null|
|**2023-02-11**|**Rethinking Vision Transformer and Masked Autoencoder in Multimodal Face Anti-Spoofing**|Zitong Yu et.al.|[2302.05744](http://arxiv.org/abs/2302.05744)|null|
|**2023-02-09**|**MAPS: A Noise-Robust Progressive Learning Approach for Source-Free Domain Adaptive Keypoint Detection**|Yuhe Ding et.al.|[2302.04589](http://arxiv.org/abs/2302.04589)|null|
|**2023-02-03**|**Explicit Box Detection Unifies End-to-End Multi-Person Pose Estimation**|Jie Yang et.al.|[2302.01593](http://arxiv.org/abs/2302.01593)|**[link](https://github.com/idea-research/ed-pose)**|
|**2023-02-03**|**Simple, Effective and General: A New Backbone for Cross-view Image Geo-localization**|Yingying Zhu et.al.|[2302.01572](http://arxiv.org/abs/2302.01572)|**[link](https://github.com/yanghongji2007/saig)**|
|**2023-01-21**|**Vision Aided Environment Semantics Extraction and Its Application in mmWave Beam Selection**|Feiyang Wen et.al.|[2301.08973](http://arxiv.org/abs/2301.08973)|null|
|**2023-01-18**|**OnePose++: Keypoint-Free One-Shot Object Pose Estimation without CAD Models**|Xingyi He et.al.|[2301.07673](http://arxiv.org/abs/2301.07673)|null|
|**2023-01-12**|**Towards High Performance One-Stage Human Pose Estimation**|Ling Li et.al.|[2301.04842](http://arxiv.org/abs/2301.04842)|null|
|**2022-12-31**|**Rethinking Rotation Invariance with Point Cloud Registration**|Jianhui Yu et.al.|[2301.00149](http://arxiv.org/abs/2301.00149)|null|
|**2023-03-02**|**Fruit Ripeness Classification: a Survey**|Matteo Rizzo et.al.|[2212.14441](http://arxiv.org/abs/2212.14441)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Matching

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-18**|**Question-Answer Cross Language Image Matching for Weakly Supervised Semantic Segmentation**|Songhe Deng et.al.|[2401.09883](http://arxiv.org/abs/2401.09883)|**[link](https://github.com/cvi-szu/qa-clims)**|
|**2024-01-09**|**RomniStereo: Recurrent Omnidirectional Stereo Matching**|Hualie Jiang et.al.|[2401.04345](http://arxiv.org/abs/2401.04345)|**[link](https://github.com/halleyjiang/romnistereo)**|
|**2024-01-05**|**CoCoT: Contrastive Chain-of-Thought Prompting for Large Multimodal Models with Multiple Image Inputs**|Daoan Zhang et.al.|[2401.02582](http://arxiv.org/abs/2401.02582)|null|
|**2024-01-03**|**Local Adaptive Clustering Based Image Matching for Automatic Visual Identification**|Zhizhen Wang et.al.|[2401.01720](http://arxiv.org/abs/2401.01720)|null|
|**2024-01-03**|**A Transformer-Based Adaptive Semantic Aggregation Method for UAV Visual Geo-Localization**|Shishen Li et.al.|[2401.01574](http://arxiv.org/abs/2401.01574)|null|
|**2023-12-23**|**BEV-CV: Birds-Eye-View Transform for Cross-View Geo-Localisation**|Tavis Shore et.al.|[2312.15363](http://arxiv.org/abs/2312.15363)|null|
|**2023-12-22**|**Harnessing Diffusion Models for Visual Perception with Meta Prompts**|Qiang Wan et.al.|[2312.14733](http://arxiv.org/abs/2312.14733)|**[link](https://github.com/fudan-zvg/meta-prompts)**|
|**2024-01-05**|**MatchDet: A Collaborative Framework for Image Matching and Object Detection**|Jinxiang Lai et.al.|[2312.10983](http://arxiv.org/abs/2312.10983)|null|
|**2023-12-07**|**Visual Geometry Grounded Deep Structure From Motion**|Jianyuan Wang et.al.|[2312.04563](http://arxiv.org/abs/2312.04563)|null|
|**2023-12-04**|**Steerers: A framework for rotation equivariant keypoint descriptors**|Georg Bökman et.al.|[2312.02152](http://arxiv.org/abs/2312.02152)|**[link](https://github.com/georg-bn/rotation-steerers)**|
|**2023-11-30**|**DSeg: Direct Line Segments Detection**|Berger Cyrille et.al.|[2311.18344](http://arxiv.org/abs/2311.18344)|null|
|**2023-11-30**|**Utilizing Radiomic Feature Analysis For Automated MRI Keypoint Detection: Enhancing Graph Applications**|Sahar Almahfouz Nasser et.al.|[2311.18281](http://arxiv.org/abs/2311.18281)|null|
|**2023-11-29**|**LGFCTR: Local and Global Feature Convolutional Transformer for Image Matching**|Wenhao Zhong et.al.|[2311.17571](http://arxiv.org/abs/2311.17571)|null|
|**2023-11-08**|**Zero-shot Translation of Attention Patterns in VQA Models to Natural Language**|Leonard Salewski et.al.|[2311.05043](http://arxiv.org/abs/2311.05043)|**[link](https://github.com/explainableml/zs-a2t)**|
|**2023-11-06**|**An invariant feature extraction for multi-modal images matching**|Chenzhong Gao et.al.|[2311.02842](http://arxiv.org/abs/2311.02842)|null|
|**2023-10-23**|**RD-VIO: Robust Visual-Inertial Odometry for Mobile Augmented Reality in Dynamic Environments**|Jinyu Li et.al.|[2310.15072](http://arxiv.org/abs/2310.15072)|null|
|**2023-10-23**|**Player Re-Identification Using Body Part Appearences**|Mahesh Bhosale et.al.|[2310.14469](http://arxiv.org/abs/2310.14469)|null|
|**2023-10-20**|**FMRT: Learning Accurate Feature Matching with Reconciliatory Transformer**|Xinyu Zhang et.al.|[2310.13605](http://arxiv.org/abs/2310.13605)|null|
|**2023-11-14**|**RGM: A Robust Generalist Matching Model**|Songyan Zhang et.al.|[2310.11755](http://arxiv.org/abs/2310.11755)|**[link](https://github.com/aim-uofa/rgm)**|
|**2023-10-07**|**UFD-PRiME: Unsupervised Joint Learning of Optical Flow and Stereo Depth through Pixel-Level Rigid Motion Estimation**|Shuai Yuan et.al.|[2310.04712](http://arxiv.org/abs/2310.04712)|null|
|**2023-10-02**|**Leveraging Cutting Edge Deep Learning Based Image Matching for Reconstructing a Large Scene from Sparse Images**|Georg Bökman et.al.|[2310.01092](http://arxiv.org/abs/2310.01092)|null|
|**2023-09-29**|**Segment Anything Model is a Good Teacher for Local Feature Learning**|Jingqian Wu et.al.|[2309.16992](http://arxiv.org/abs/2309.16992)|**[link](https://github.com/vignywang/samfeat)**|
|**2023-09-27**|**KDD-LOAM: Jointly Learned Keypoint Detector and Descriptors Assisted LiDAR Odometry and Mapping**|Renlang Huang et.al.|[2309.15394](http://arxiv.org/abs/2309.15394)|null|
|**2023-10-13**|**A Critical Analysis of Internal Reliability for Uncertainty Quantification of Dense Image Matching in Multi-view Stereo**|Debao Huang et.al.|[2309.09379](http://arxiv.org/abs/2309.09379)|null|
|**2023-09-11**|**Towards Content-based Pixel Retrieval in Revisited Oxford and Paris**|Guoyuan An et.al.|[2309.05438](http://arxiv.org/abs/2309.05438)|**[link](https://github.com/anguoyuan/pixel_retrieval-segmented_instance_retrieval)**|
|**2023-09-09**|**Neural Semantic Surface Maps**|Luca Morreale et.al.|[2309.04836](http://arxiv.org/abs/2309.04836)|null|
|**2023-09-05**|**Doppelgangers: Learning to Disambiguate Images of Similar Structures**|Ruojin Cai et.al.|[2309.02420](http://arxiv.org/abs/2309.02420)|**[link](https://github.com/RuojinCai/Doppelgangers)**|
|**2023-08-14**|**Occ $^2$ Net: Robust Image Matching Based on 3D Occupancy Estimation for Occluded Regions**|Miao Fan et.al.|[2308.16160](http://arxiv.org/abs/2308.16160)|null|
|**2023-08-29**|**TKwinFormer: Top k Window Attention in Vision Transformers for Feature Matching**|Yun Liao et.al.|[2308.15144](http://arxiv.org/abs/2308.15144)|null|
|**2023-08-27**|**LDL: Line Distance Functions for Panoramic Localization**|Junho Kim et.al.|[2308.13989](http://arxiv.org/abs/2308.13989)|**[link](https://github.com/82magnolia/panoramic-localization)**|
|**2023-08-22**|**Scene-Aware Feature Matching**|Xiaoyong Lu et.al.|[2308.09949](http://arxiv.org/abs/2308.09949)|null|
|**2023-12-11**|**DeDoDe: Detect, Don't Describe -- Describe, Don't Detect for Local Feature Matching**|Johan Edstedt et.al.|[2308.08479](http://arxiv.org/abs/2308.08479)|**[link](https://github.com/parskatt/dedode)**|
|**2023-08-19**|**Global Features are All You Need for Image Retrieval and Reranking**|Shihao Shao et.al.|[2308.06954](http://arxiv.org/abs/2308.06954)|**[link](https://github.com/shihaoshao-gh/superglobal)**|
|**2023-08-02**|**ZRIGF: An Innovative Multimodal Framework for Zero-Resource Image-Grounded Dialogue Generation**|Bo Zhang et.al.|[2308.00400](http://arxiv.org/abs/2308.00400)|**[link](https://github.com/zhangbo-nlp/zrigf)**|
|**2023-07-28**|**Cross-Modal Concept Learning and Inference for Vision-Language Models**|Yi Zhang et.al.|[2307.15460](http://arxiv.org/abs/2307.15460)|null|
|**2023-07-22**|**CryptoMask : Privacy-preserving Face Recognition**|Jianli Bai et.al.|[2307.12010](http://arxiv.org/abs/2307.12010)|null|
|**2023-07-22**|**A Stronger Stitching Algorithm for Fisheye Images based on Deblurring and Registration**|Jing Hao et.al.|[2307.11997](http://arxiv.org/abs/2307.11997)|null|
|**2023-07-21**|**Reverse Knowledge Distillation: Training a Large Model using a Small One for Retinal Image Matching on Limited Data**|Sahar Almahfouz Nasser et.al.|[2307.10698](http://arxiv.org/abs/2307.10698)|**[link](https://github.com/SaharAlmahfouzNasser/MeDAL-Retina)**|
|**2023-08-08**|**Balancing Privacy and Progress in Artificial Intelligence: Anonymization in Histopathology for Biomedical Research and Education**|Neel Kanwal et.al.|[2307.09426](http://arxiv.org/abs/2307.09426)|null|
|**2023-08-01**|**Unsupervised Deep Graph Matching Based on Cycle Consistency**|Siddharth Tourani et.al.|[2307.08930](http://arxiv.org/abs/2307.08930)|null|
|**2023-12-26**|**Tightly-Coupled LiDAR-Visual SLAM Based on Geometric Features for Mobile Agents**|Ke Cao et.al.|[2307.07763](http://arxiv.org/abs/2307.07763)|null|
|**2023-07-09**|**Augmenters at SemEval-2023 Task 1: Enhancing CLIP in Handling Compositionality and Ambiguity for Zero-Shot Visual WSD through Prompt Augmentation and Text-To-Image Diffusion**|Jie S. Li et.al.|[2307.05564](http://arxiv.org/abs/2307.05564)|null|
|**2023-07-11**|**ResMatch: Residual Attention Learning for Local Feature Matching**|Yuxin Deng et.al.|[2307.05180](http://arxiv.org/abs/2307.05180)|**[link](https://github.com/acuooooo/resmatch)**|
|**2024-01-02**|**TIAM -- A Metric for Evaluating Alignment in Text-to-Image Generation**|Paul Grimal et.al.|[2307.05134](http://arxiv.org/abs/2307.05134)|**[link](https://github.com/grimalpaul/tiam)**|
|**2023-07-02**|**TopicFM+: Boosting Accuracy and Efficiency of Topic-Assisted Feature Matching**|Khang Truong Giang et.al.|[2307.00485](http://arxiv.org/abs/2307.00485)|**[link](https://github.com/truongkhang/topicfm)**|
|**2023-06-27**|**Detector-Free Structure from Motion**|Xingyi He et.al.|[2306.15669](http://arxiv.org/abs/2306.15669)|**[link](https://github.com/zju3dv/DetectorFreeSfM)**|
|**2023-08-18**|**PoseDiffusion: Solving Pose Estimation via Diffusion-aided Bundle Adjustment**|Jianyuan Wang et.al.|[2306.15667](http://arxiv.org/abs/2306.15667)|null|
|**2023-06-25**|**Enhancing Dynamic Image Advertising with Vision-Language Pre-training**|Zhoufutu Wen et.al.|[2306.14112](http://arxiv.org/abs/2306.14112)|null|
|**2023-06-23**|**LightGlue: Local Feature Matching at Light Speed**|Philipp Lindenberger et.al.|[2306.13643](http://arxiv.org/abs/2306.13643)|**[link](https://github.com/cvg/lightglue)**|
|**2023-06-19**|**Graph Self-Supervised Learning for Endoscopic Image Matching**|Manel Farhat et.al.|[2306.11141](http://arxiv.org/abs/2306.11141)|**[link](https://github.com/abenhamadou/graph-self-supervised-learning-for-endoscopic-image-matching)**|
|**2023-07-27**|**Fine-Tuned but Zero-Shot 3D Shape Sketch View Similarity and Retrieval**|Gianluca Berardi et.al.|[2306.08541](http://arxiv.org/abs/2306.08541)|null|
|**2023-06-09**|**Leaving the Lines Behind: Vision-Based Crop Row Exit for Agricultural Robot Navigation**|Rajitha de Silva et.al.|[2306.05869](http://arxiv.org/abs/2306.05869)|null|
|**2023-06-07**|**A2B: Anchor to Barycentric Coordinate for Robust Correspondence**|Weiyue Zhao et.al.|[2306.02760](http://arxiv.org/abs/2306.02760)|null|
|**2023-05-27**|**Pentagon-Match (PMatch): Identification of View-Invariant Planar Feature for Local Feature Matching-Based Homography Estimation**|Yueh-Cheng Huang et.al.|[2305.17463](http://arxiv.org/abs/2305.17463)|null|
|**2023-05-19**|**SIDAR: Synthetic Image Dataset for Alignment & Restoration**|Monika Kwiatkowski et.al.|[2305.12036](http://arxiv.org/abs/2305.12036)|**[link](https://github.com/niika/SIDAR)**|
|**2023-05-18**|**LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation**|Yujie Lu et.al.|[2305.11116](http://arxiv.org/abs/2305.11116)|**[link](https://github.com/yujielu10/llmscore)**|
|**2023-05-16**|**A Method for Training-free Person Image Picture Generation**|Tianyu Chen et.al.|[2305.09817](http://arxiv.org/abs/2305.09817)|null|
|**2023-05-15**|**Image Matching by Bare Homography**|Fabio Bellavia et.al.|[2305.08946](http://arxiv.org/abs/2305.08946)|null|
|**2023-05-12**|**CLIP-Count: Towards Text-Guided Zero-Shot Object Counting**|Ruixiang Jiang et.al.|[2305.07304](http://arxiv.org/abs/2305.07304)|**[link](https://github.com/songrise/clip-count)**|
|**2023-05-10**|**SENDD: Sparse Efficient Neural Depth and Deformation for Tissue Tracking**|Adam Schmidt et.al.|[2305.06477](http://arxiv.org/abs/2305.06477)|null|
|**2023-05-10**|**Level-line Guided Edge Drawing for Robust Line Segment Detection**|Xinyu Lin et.al.|[2305.05883](http://arxiv.org/abs/2305.05883)|**[link](https://github.com/roylin1229/gedrlsd)**|
|**2023-05-09**|**ColonMapper: topological mapping and localization for colonoscopy**|Javier Morlana et.al.|[2305.05546](http://arxiv.org/abs/2305.05546)|null|
|**2023-04-29**|**A Comprehensive Review of Image Line Segment Detection and Description: Taxonomies, Comparisons, and Challenges**|Xinyu Lin et.al.|[2305.00264](http://arxiv.org/abs/2305.00264)|null|
|**2023-06-11**|**SFD2: Semantic-guided Feature Detection and Description**|Fei Xue et.al.|[2304.14845](http://arxiv.org/abs/2304.14845)|**[link](https://github.com/feixue94/sfd2)**|
|**2023-04-17**|**DeepSim-Nets: Deep Similarity Networks for Stereo Image Matching**|Mohamed Ali Chebbi et.al.|[2304.08056](http://arxiv.org/abs/2304.08056)|**[link](https://github.com/dalichebbi/deepsimnets)**|
|**2023-04-16**|**Long-term Visual Localization with Mobile Sensors**|Shen Yan et.al.|[2304.07691](http://arxiv.org/abs/2304.07691)|null|
|**2023-04-12**|**SiLK -- Simple Learned Keypoints**|Pierre Gleize et.al.|[2304.06194](http://arxiv.org/abs/2304.06194)|**[link](https://github.com/facebookresearch/silk)**|
|**2023-04-16**|**ALIKED: A Lighter Keypoint and Descriptor Extraction Network via Deformable Transformation**|Xiaoming Zhao et.al.|[2304.03608](http://arxiv.org/abs/2304.03608)|**[link](https://github.com/Shiaoming/ALIKED)**|
|**2023-04-04**|**GlueStick: Robust Image Matching by Sticking Points and Lines Together**|Rémi Pautrat et.al.|[2304.02008](http://arxiv.org/abs/2304.02008)|**[link](https://github.com/cvg/gluestick)**|
|**2023-04-03**|**PoseMatcher: One-shot 6D Object Pose Estimation by Deep Feature Matching**|Pedro Castro et.al.|[2304.01382](http://arxiv.org/abs/2304.01382)|null|
|**2023-04-02**|**Enhancing Deformable Local Features by Jointly Learning to Detect and Describe Keypoints**|Guilherme Potje et.al.|[2304.00583](http://arxiv.org/abs/2304.00583)|**[link](https://github.com/verlab/DALF_CVPR_2023)**|
|**2023-04-13**|**Structured Epipolar Matcher for Local Feature Matching**|Jiahao Chang et.al.|[2303.16646](http://arxiv.org/abs/2303.16646)|null|
|**2023-03-29**|**Adaptive Spot-Guided Transformer for Consistent Local Feature Matching**|Jiahuan Yu et.al.|[2303.16624](http://arxiv.org/abs/2303.16624)|null|
|**2023-03-28**|**ASIC: Aligning Sparse in-the-wild Image Collections**|Kamal Gupta et.al.|[2303.16201](http://arxiv.org/abs/2303.16201)|null|
|**2023-03-25**|**Learning Rotation-Equivariant Features for Visual Correspondence**|Jongmin Lee et.al.|[2303.15472](http://arxiv.org/abs/2303.15472)|null|
|**2023-03-27**|**Learnable Graph Matching: A Practical Paradigm for Data Association**|Jiawei He et.al.|[2303.15414](http://arxiv.org/abs/2303.15414)|**[link](https://github.com/jiaweihe1996/GMTracker)**|
|**2023-03-24**|**Efficient and Accurate Co-Visible Region Localization with Matching Key-Points Crop (MKPC): A Two-Stage Pipeline for Enhancing Image Matching Performance**|Hongjian Song et.al.|[2303.13794](http://arxiv.org/abs/2303.13794)|null|
|**2023-03-15**|**Rethinking Optical Flow from Geometric Matching Consistent Perspective**|Qiaole Dong et.al.|[2303.08384](http://arxiv.org/abs/2303.08384)|**[link](https://github.com/dqiaole/matchflow)**|
|**2023-04-04**|**PATS: Patch Area Transportation with Subdivision for Local Feature Matching**|Junjie Ni et.al.|[2303.07700](http://arxiv.org/abs/2303.07700)|null|
|**2023-03-07**|**Parsing Line Segments of Floor Plan Images Using Graph Neural Networks**|Mingxiang Chen et.al.|[2303.03851](http://arxiv.org/abs/2303.03851)|null|
|**2023-03-06**|**Improving Transformer-based Image Matching by Cascaded Capturing Spatially Informative Keypoints**|Chenjie Cao et.al.|[2303.02885](http://arxiv.org/abs/2303.02885)|null|
|**2023-03-10**|**ParaFormer: Parallel Attention Transformer for Efficient Feature Matching**|Xiaoyong Lu et.al.|[2303.00941](http://arxiv.org/abs/2303.00941)|null|
|**2023-03-01**|**RIFT2: Speeding-up RIFT with A New Rotation-Invariance Technique**|Jiayuan Li et.al.|[2303.00319](http://arxiv.org/abs/2303.00319)|**[link](https://github.com/ljy-rs/rift2-multimodal-matching-rotation)**|
|**2023-02-28**|**Nonlinear Intensity, Scale and Rotation Invariant Matching for Multimodal Images**|Zhongli Fan et.al.|[2302.14239](http://arxiv.org/abs/2302.14239)|**[link](https://github.com/zhongli-fan/nisr)**|
|**2023-02-25**|**BrainCLIP: Bridging Brain and Visual-Linguistic Representation via CLIP for Generic Natural Visual Stimulus Decoding from fMRI**|Yulong Liu et.al.|[2302.12971](http://arxiv.org/abs/2302.12971)|null|
|**2023-02-24**|**Classification of structural building damage grades from multi-temporal photogrammetric point clouds using a machine learning model trained on virtual laser scanning data**|Vivien Zahs et.al.|[2302.12591](http://arxiv.org/abs/2302.12591)|null|
|**2023-02-20**|**A Large Scale Homography Benchmark**|Daniel Barath et.al.|[2302.09997](http://arxiv.org/abs/2302.09997)|**[link](https://github.com/danini/homography-benchmark)**|
|**2023-02-12**|**OAMatcher: An Overlapping Areas-based Network for Accurate Local Feature Matching**|Kun Dai et.al.|[2302.05846](http://arxiv.org/abs/2302.05846)|**[link](https://github.com/dk-hu/oamatcher)**|
|**2023-02-10**|**General, Single-shot, Target-less, and Automatic LiDAR-Camera Extrinsic Calibration Toolbox**|Kenji Koide et.al.|[2302.05094](http://arxiv.org/abs/2302.05094)|**[link](https://github.com/koide3/direct_visual_lidar_calibration)**|
|**2023-02-03**|**Simple, Effective and General: A New Backbone for Cross-view Image Geo-localization**|Yingying Zhu et.al.|[2302.01572](http://arxiv.org/abs/2302.01572)|**[link](https://github.com/yanghongji2007/saig)**|
|**2023-01-27**|**Harmonizing Flows: Unsupervised MR harmonization based on normalizing flows**|Farzad Beizaee et.al.|[2301.11551](http://arxiv.org/abs/2301.11551)|**[link](https://github.com/farzad-bz/harmonizing-flows)**|
|**2023-01-25**|**Local Feature Extraction from Salient Regions by Feature Map Transformation**|Yerim Jung et.al.|[2301.10413](http://arxiv.org/abs/2301.10413)|null|
|**2023-01-24**|**Feature-based Image Matching for Identifying Individual Kākā**|Fintan O'Sullivan et.al.|[2301.06678](http://arxiv.org/abs/2301.06678)|null|
|**2023-01-18**|**Instance Segmentation Based Graph Extraction for Handwritten Circuit Diagram Images**|Johannes Bayer et.al.|[2301.03155](http://arxiv.org/abs/2301.03155)|null|
|**2023-01-08**|**DeepMatcher: A Deep Transformer-based Network for Robust and Accurate Local Feature Matching**|Tao Xie et.al.|[2301.02993](http://arxiv.org/abs/2301.02993)|**[link](https://github.com/XT-1997/DeepMatcher)**|
|**2023-01-07**|**Deep Learning-Based UAV Aerial Triangulation without Image Control Points**|Jiageng Zhong et.al.|[2301.02869](http://arxiv.org/abs/2301.02869)|null|
|**2023-01-06**|**The UNCOVER Survey: A first-look HST+JWST catalog of 50,000 galaxies near Abell 2744 and beyond**|John R. Weaver et.al.|[2301.02671](http://arxiv.org/abs/2301.02671)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Relocalization

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-16**|**Multi-Technique Sequential Information Consistency For Dynamic Visual Place Recognition In Changing Environments**|Bruno Arcanjo et.al.|[2401.08263](http://arxiv.org/abs/2401.08263)|null|
|**2023-12-20**|**Aggregating Multiple Bio-Inspired Image Region Classifiers For Effective And Lightweight Visual Place Recognition**|Bruno Arcanjo et.al.|[2312.12995](http://arxiv.org/abs/2312.12995)|null|
|**2023-12-17**|**DistilVPR: Cross-Modal Knowledge Distillation for Visual Place Recognition**|Sijie Wang et.al.|[2312.10616](http://arxiv.org/abs/2312.10616)|**[link](https://github.com/sijieaaa/distilvpr)**|
|**2023-12-15**|**AEGIS-Net: Attention-guided Multi-Level Feature Aggregation for Indoor Place Recognition**|Yuhang Ming et.al.|[2312.09538](http://arxiv.org/abs/2312.09538)|**[link](https://github.com/yuhangming/aegis-net)**|
|**2023-12-14**|**Design Space Exploration of Low-Bit Quantized Neural Networks for Visual Place Recognition**|Oliver Grainge et.al.|[2312.09028](http://arxiv.org/abs/2312.09028)|null|
|**2023-12-08**|**MagHT: a Magnetic Hough Transform for Fast Indoor Place Recognition**|Iad Abdul Raouf et.al.|[2312.05015](http://arxiv.org/abs/2312.05015)|null|
|**2023-11-28**|**Scene Summarization: Clustering Scene Videos into Spatially Diverse Frames**|Chao Chen et.al.|[2311.17940](http://arxiv.org/abs/2311.17940)|null|
|**2023-11-27**|**Text2Loc: 3D Point Cloud Localization from Natural Language**|Yan Xia et.al.|[2311.15977](http://arxiv.org/abs/2311.15977)|null|
|**2023-11-27**|**Optimal Transport Aggregation for Visual Place Recognition**|Sergio Izquierdo et.al.|[2311.15937](http://arxiv.org/abs/2311.15937)|**[link](https://github.com/serizba/salad)**|
|**2023-11-22**|**Applications of Spiking Neural Networks in Visual Place Recognition**|Somayeh Hussaini et.al.|[2311.13186](http://arxiv.org/abs/2311.13186)|**[link](https://github.com/qvpr/vprsnn)**|
|**2023-12-30**|**LCPR: A Multi-Scale Attention-Based LiDAR-Camera Fusion Network for Place Recognition**|Zijie Zhou et.al.|[2311.03198](http://arxiv.org/abs/2311.03198)|**[link](https://github.com/ZhouZijie77/LCPR)**|
|**2023-12-05**|**DINO-Mix: Enhancing Visual Place Recognition with Foundational Vision Model and Feature Mixing**|Gaoshuang Huang et.al.|[2311.00230](http://arxiv.org/abs/2311.00230)|**[link](https://github.com/GaoShuang98/DINO-Mix)**|
|**2023-10-25**|**FoundLoc: Vision-based Onboard Aerial Localization in the Wild**|Yao He et.al.|[2310.16299](http://arxiv.org/abs/2310.16299)|null|
|**2023-10-24**|**Cross-view Self-localization from Synthesized Scene-graphs**|Ryogo Yamamoto et.al.|[2310.15504](http://arxiv.org/abs/2310.15504)|null|
|**2023-10-23**|**SONIC: Sonar Image Correspondence using Pose Supervised Learning for Imaging Sonars**|Samiran Gode et.al.|[2310.15023](http://arxiv.org/abs/2310.15023)|null|
|**2023-10-20**|**What you see is what you get: Experience ranking with deep neural dataset-to-dataset similarity for topological localisation**|Matthew Gadd et.al.|[2310.13622](http://arxiv.org/abs/2310.13622)|**[link](https://github.com/mttgdd/vdna-experience-selection)**|
|**2023-10-16**|**Camera-LiDAR Fusion with Latent Contact for Place Recognition in Challenging Cross-Scenes**|Yan Pan et.al.|[2310.10371](http://arxiv.org/abs/2310.10371)|null|
|**2023-10-10**|**Distillation Improves Visual Place Recognition for Low-Quality Queries**|Anbang Yang et.al.|[2310.06906](http://arxiv.org/abs/2310.06906)|null|
|**2023-10-09**|**Collaborative Visual Place Recognition**|Yiming Li et.al.|[2310.05541](http://arxiv.org/abs/2310.05541)|null|
|**2023-10-08**|**AANet: Aggregation and Alignment Network with Semi-hard Positive Sample Mining for Hierarchical Place Recognition**|Feng Lu et.al.|[2310.05184](http://arxiv.org/abs/2310.05184)|**[link](https://github.com/Lu-Feng/AANet)**|
|**2023-10-12**|**ClusVPR: Efficient Visual Place Recognition with Clustering-based Weighted Transformer**|Yifan Xu et.al.|[2310.04099](http://arxiv.org/abs/2310.04099)|null|
|**2023-10-05**|**PlaceNav: Topological Navigation through Place Recognition**|Lauri Suomela et.al.|[2309.17260](http://arxiv.org/abs/2309.17260)|null|
|**2023-09-29**|**Multimodal Dataset for Localization, Mapping and Crop Monitoring in Citrus Tree Farms**|Hanzhe Teng et.al.|[2309.15332](http://arxiv.org/abs/2309.15332)|**[link](https://github.com/ucr-robotics/citrus-farm-dataset)**|
|**2023-09-26**|**Language-EXtended Indoor SLAM (LEXIS): A Versatile System for Real-time Visual Scene Understanding**|Christina Kassab et.al.|[2309.15065](http://arxiv.org/abs/2309.15065)|null|
|**2023-09-26**|**HeLiPR: Heterogeneous LiDAR Dataset for inter-LiDAR Place Recognition under Spatial and Temporal Variations**|Minwoo Jung et.al.|[2309.14590](http://arxiv.org/abs/2309.14590)|null|
|**2023-09-19**|**VPRTempo: A Fast Temporally Encoded Spiking Neural Network for Visual Place Recognition**|Adam D. Hines et.al.|[2309.10225](http://arxiv.org/abs/2309.10225)|**[link](https://github.com/QVPR/VPRTempo)**|
|**2023-09-18**|**RaLF: Flow-based Global and Metric Radar Localization in LiDAR Maps**|Abhijeet Nayak et.al.|[2309.09875](http://arxiv.org/abs/2309.09875)|null|
|**2023-09-13**|**RadarLCD: Learnable Radar-based Loop Closure Detection Pipeline**|Mirko Usuelli et.al.|[2309.07094](http://arxiv.org/abs/2309.07094)|null|
|**2023-11-23**|**Pose-Graph Attentional Graph Neural Network for Lidar Place Recognition**|Milad Ramezani et.al.|[2309.00168](http://arxiv.org/abs/2309.00168)|null|
|**2023-08-25**|**Enhancing Landmark Detection in Cluttered Real-World Scenarios with Vision Transformers**|Mohammad Javad Rajabi et.al.|[2308.13671](http://arxiv.org/abs/2308.13671)|null|
|**2023-08-24**|**VNI-Net: Vector Neurons-based Rotation-Invariant Descriptor for LiDAR Place Recognition**|Gengxuan Tian et.al.|[2308.12870](http://arxiv.org/abs/2308.12870)|null|
|**2023-08-21**|**EigenPlaces: Training Viewpoint Robust Models for Visual Place Recognition**|Gabriele Berton et.al.|[2308.10832](http://arxiv.org/abs/2308.10832)|**[link](https://github.com/gmberton/auto_vpr)**|
|**2023-11-29**|**GeoAdapt: Self-Supervised Test-Time Adaptation in LiDAR Place Recognition Using Geometric Priors**|Joshua Knights et.al.|[2308.04638](http://arxiv.org/abs/2308.04638)|**[link](https://github.com/csiro-robotics/geoadapt)**|
|**2023-09-24**|**Improving Generalization of Synthetically Trained Sonar Image Descriptors for Underwater Place Recognition**|Ivano Donadi et.al.|[2308.01058](http://arxiv.org/abs/2308.01058)|**[link](https://github.com/ivano-donadi/sdpr)**|
|**2023-11-29**|**AnyLoc: Towards Universal Visual Place Recognition**|Nikhil Keetha et.al.|[2308.00688](http://arxiv.org/abs/2308.00688)|**[link](https://github.com/AnyLoc/AnyLoc)**|
|**2023-07-26**|**Deep Robust Multi-Robot Re-localisation in Natural Environments**|Milad Ramezani et.al.|[2307.13950](http://arxiv.org/abs/2307.13950)|null|
|**2023-07-23**|**Scale jump-aware pose graph relaxation for monocular SLAM with re-initializations**|Runze Yuan et.al.|[2307.12326](http://arxiv.org/abs/2307.12326)|null|
|**2023-11-05**|**Similarity Min-Max: Zero-Shot Day-Night Domain Adaptation**|Rundong Luo et.al.|[2307.08779](http://arxiv.org/abs/2307.08779)|null|
|**2023-12-06**|**Divide&Classify: Fine-Grained Classification for City-Wide Visual Place Recognition**|Gabriele Trivigno et.al.|[2307.08417](http://arxiv.org/abs/2307.08417)|**[link](https://github.com/ga1i13o/divide-and-classify)**|
|**2023-07-17**|**NDT-Map-Code: A 3D global descriptor for real-time loop closure detection in lidar SLAM**|Lizhou Liao et.al.|[2307.08221](http://arxiv.org/abs/2307.08221)|**[link](https://github.com/SlamCabbage/NDTMC)**|
|**2023-07-14**|**Multi-Session, Localization-oriented and Lightweight LiDAR Mapping Using Semantic Lines and Planes**|Zehuan Yu et.al.|[2307.07126](http://arxiv.org/abs/2307.07126)|null|
|**2023-07-10**|**RaPlace: Place Recognition for Imaging Radar using Radon Transform and Mutable Threshold**|Hyesu Jang et.al.|[2307.04321](http://arxiv.org/abs/2307.04321)|**[link](https://github.com/hyesu-jang/raplace)**|
|**2023-07-04**|**Unsupervised Quality Prediction for Improved Single-Frame and Weighted Sequential Visual Place Recognition**|Helen Carson et.al.|[2307.01464](http://arxiv.org/abs/2307.01464)|null|
|**2023-07-03**|**Cross-modal Place Recognition in Image Databases using Event-based Sensors**|Xiang Ji et.al.|[2307.01047](http://arxiv.org/abs/2307.01047)|null|
|**2023-06-30**|**DisPlacing Objects: Improving Dynamic Vehicle Detection via Visual Place Recognition under Adverse Conditions**|Stephen Hausler et.al.|[2306.17536](http://arxiv.org/abs/2306.17536)|null|
|**2023-07-04**|**Irregular Change Detection in Sparse Bi-Temporal Point Clouds using Learned Place Recognition Descriptors and Point-to-Voxel Comparison**|Nikolaos Stathoulopoulos et.al.|[2306.15416](http://arxiv.org/abs/2306.15416)|null|
|**2023-06-21**|**Off the Radar: Uncertainty-Aware Radar Place Recognition with Introspective Querying and Map Maintenance**|Jianhao Yuan et.al.|[2306.12556](http://arxiv.org/abs/2306.12556)|null|
|**2023-07-29**|**LiDAR-Based Place Recognition For Autonomous Driving: A Survey**|Yongjun Zhang et.al.|[2306.10561](http://arxiv.org/abs/2306.10561)|null|
|**2023-06-05**|**SelFLoc: Selective Feature Fusion for Large-scale Point Cloud-based Place Recognition**|Qibo Qiu et.al.|[2306.01205](http://arxiv.org/abs/2306.01205)|null|
|**2023-05-29**|**TReR: A Lightweight Transformer Re-Ranking Approach for 3D LiDAR Place Recognition**|Tiago Barros et.al.|[2305.18013](http://arxiv.org/abs/2305.18013)|null|
|**2023-05-24**|**Robust Imaging Sonar-based Place Recognition and Localization in Underwater Environments**|Hogyun Kim et.al.|[2305.14773](http://arxiv.org/abs/2305.14773)|**[link](https://github.com/sparolab/sonar_context)**|
|**2023-05-23**|**Leveraging BEV Representation for 360-degree Visual Place Recognition**|Xuecheng Xu et.al.|[2305.13814](http://arxiv.org/abs/2305.13814)|**[link](https://github.com/maverickpeter/vdisco)**|
|**2023-07-26**|**Learning Sequence Descriptor based on Spatio-Temporal Attention for Visual Place Recognition**|Fenglin Zhang et.al.|[2305.11467](http://arxiv.org/abs/2305.11467)|null|
|**2023-05-09**|**Visual Place Recognition with Low-Resolution Images**|Mihnea-Alexandru Tomita et.al.|[2305.05776](http://arxiv.org/abs/2305.05776)|null|
|**2023-05-09**|**An Evaluation and Ranking of Different Voting Schemes for Improved Visual Place Recognition**|Maria Waheed et.al.|[2305.05705](http://arxiv.org/abs/2305.05705)|null|
|**2023-05-09**|**ColonMapper: topological mapping and localization for colonoscopy**|Javier Morlana et.al.|[2305.05546](http://arxiv.org/abs/2305.05546)|null|
|**2023-05-09**|**Patch-DrosoNet: Classifying Image Partitions With Fly-Inspired Models For Lightweight Visual Place Recognition**|Bruno Arcanjo et.al.|[2305.05256](http://arxiv.org/abs/2305.05256)|null|
|**2023-05-03**|**Learning-based Relational Object Matching Across Views**|Cathrin Elich et.al.|[2305.02398](http://arxiv.org/abs/2305.02398)|null|
|**2023-04-17**|**(LC) $^2$ : LiDAR-Camera Loop Constraints For Cross-Modal Place Recognition**|Alex Junho Lee et.al.|[2304.08660](http://arxiv.org/abs/2304.08660)|null|
|**2023-04-14**|**CoPR: Towards Accurate Visual Localization With Continuous Place-descriptor Regression**|Mubariz Zaffar et.al.|[2304.07426](http://arxiv.org/abs/2304.07426)|null|
|**2023-04-14**|**FM-Loc: Using Foundation Models for Improved Vision-based Localization**|Reihaneh Mirjalili et.al.|[2304.07058](http://arxiv.org/abs/2304.07058)|null|
|**2023-04-12**|**Are Local Features All You Need for Cross-Domain Visual Place Recognition?**|Giovanni Barbarani et.al.|[2304.05887](http://arxiv.org/abs/2304.05887)|**[link](https://github.com/gbarbarani/re-ranking-for-vpr)**|
|**2023-04-06**|**$R^{2}$Former: Unified $R$etrieval and $R$ eranking Transformer for Place Recognition**|Sijie Zhu et.al.|[2304.03410](http://arxiv.org/abs/2304.03410)|null|
|**2023-04-17**|**NPR: Nocturnal Place Recognition in Streets**|Bingxi Liu et.al.|[2304.00276](http://arxiv.org/abs/2304.00276)|null|
|**2023-03-31**|**CrossLoc3D: Aerial-Ground Cross-Source 3D Place Recognition**|Tianrui Guan et.al.|[2303.17778](http://arxiv.org/abs/2303.17778)|null|
|**2023-03-24**|**A-MuSIC: An Adaptive Ensemble System For Visual Place Recognition In Changing Environments**|Bruno Arcanjo et.al.|[2303.14247](http://arxiv.org/abs/2303.14247)|null|
|**2023-03-24**|**PanoVPR: Towards Unified Perspective-to-Equirectangular Visual Place Recognition via Sliding Windows across the Panoramic View**|Ze Shi et.al.|[2303.14095](http://arxiv.org/abs/2303.14095)|**[link](https://github.com/zafirshi/panovpr)**|
|**2023-06-14**|**CCL: Continual Contrastive Learning for LiDAR Place Recognition**|Jiafeng Cui et.al.|[2303.13952](http://arxiv.org/abs/2303.13952)|**[link](https://github.com/cloudcjf/ccl)**|
|**2023-03-25**|**Data-efficient Large Scale Place Recognition with Graded Similarity Supervision**|Maria Leyva-Vallina et.al.|[2303.11739](http://arxiv.org/abs/2303.11739)|**[link](https://github.com/marialeyvallina/generalized_contrastive_loss)**|
|**2023-03-19**|**Deep Declarative Dynamic Time Warping for End-to-End Learning of Alignment Paths**|Ming Xu et.al.|[2303.10778](http://arxiv.org/abs/2303.10778)|**[link](https://github.com/mingu6/declarativedtw)**|
|**2023-03-16**|**Metric-Free Exploration for Topological Mapping by Task and Motion Imitation in Feature Space**|Yuhang He et.al.|[2303.09192](http://arxiv.org/abs/2303.09192)|null|
|**2023-03-13**|**OverlapNetVLAD: A Coarse-to-Fine Framework for LiDAR-based Place Recognition**|Chencan Fu et.al.|[2303.06881](http://arxiv.org/abs/2303.06881)|**[link](https://github.com/fcchit/overlapnetvlad)**|
|**2023-03-11**|**Necessity Feature Correspondence Estimation for Large-scale Global Place Recognition and Relocalization**|Kyeongsu Kang et.al.|[2303.06308](http://arxiv.org/abs/2303.06308)|null|
|**2023-03-09**|**Dominating Set Database Selection for Visual Place Recognition**|Anastasiia Kornilova et.al.|[2303.05123](http://arxiv.org/abs/2303.05123)|null|
|**2023-03-06**|**Visual Place Recognition: A Tutorial**|Stefan Schubert et.al.|[2303.03281](http://arxiv.org/abs/2303.03281)|**[link](https://github.com/stschubert/vpr_tutorial)**|
|**2023-03-09**|**Self-Supervised Learning for Place Representation Generalization across Appearance Changes**|Mohamed Adel Musallam et.al.|[2303.02370](http://arxiv.org/abs/2303.02370)|null|
|**2023-03-03**|**MixVPR: Feature Mixing for Visual Place Recognition**|Amar Ali-bey et.al.|[2303.02190](http://arxiv.org/abs/2303.02190)|**[link](https://github.com/amaralibey/mixvpr)**|
|**2023-03-02**|**BPT: Binary Point Cloud Transformer for Place Recognition**|Zhixing Hou et.al.|[2303.01166](http://arxiv.org/abs/2303.01166)|null|
|**2023-03-02**|**I2P-Rec: Recognizing Images on Large-scale Point Cloud Maps through Bird's Eye View Projections**|Yixuan Li et.al.|[2303.01043](http://arxiv.org/abs/2303.01043)|null|
|**2023-03-01**|**A Complementarity-Based Switch-Fuse System for Improved Visual Place Recognition**|Maria Waheed et.al.|[2303.00714](http://arxiv.org/abs/2303.00714)|null|
|**2023-03-01**|**ORCHNet: A Robust Global Feature Aggregation approach for 3D LiDAR-based Place recognition in Orchards**|T. Barros et.al.|[2303.00477](http://arxiv.org/abs/2303.00477)|**[link](https://github.com/cybonic/orchnet)**|
|**2023-03-01**|**Region Prediction for Efficient Robot Localization on Large Maps**|Matteo Scucchia et.al.|[2303.00295](http://arxiv.org/abs/2303.00295)|null|
|**2023-03-15**|**BEVPlace: Learning LiDAR-based Place Recognition using Bird's Eye View Images**|Lun Luo et.al.|[2302.14325](http://arxiv.org/abs/2302.14325)|**[link](https://github.com/zjuluolun/bevplace)**|
|**2023-02-28**|**Global Proxy-based Hard Mining for Visual Place Recognition**|Amar Ali-bey et.al.|[2302.14217](http://arxiv.org/abs/2302.14217)|**[link](https://github.com/amaralibey/gpm)**|
|**2023-02-26**|**Data-Efficient Sequence-Based Visual Place Recognition with Highly Compressed JPEG Images**|Mihnea-Alexandru Tomita et.al.|[2302.13314](http://arxiv.org/abs/2302.13314)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## IMU

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2023-09-18**|**Learning Inertial Parameter Identification of Unknown Object with Humanoid Robot using Sim-to-Real Adaptation**|Donghoon Baek et.al.|[2309.09810](http://arxiv.org/abs/2309.09810)|null|
|**2023-03-03**|**RIOT: Recursive Inertial Odometry Transformer for Localisation from Low-Cost IMU Measurements**|James Brotchie et.al.|[2303.01641](http://arxiv.org/abs/2303.01641)|null|
|**2022-11-14**|**Learnable Spatio-Temporal Map Embeddings for Deep Inertial Localization**|Dennis Melamed et.al.|[2211.07635](http://arxiv.org/abs/2211.07635)|null|
|**2022-11-10**|**Unsupervised Deep Learning-based clustering for Human Activity Recognition**|Hamza Amrani et.al.|[2211.05483](http://arxiv.org/abs/2211.05483)|**[link](https://github.com/hamzaamrani/Deep-Inertial-Sensory-Clustering)**|
|**2022-11-08**|**Deep IMU Bias Inference for Robust Visual-Inertial Odometry with Factor Graphs**|Russell Buchanan et.al.|[2211.04517](http://arxiv.org/abs/2211.04517)|null|
|**2023-02-28**|**Learned Inertial Odometry for Autonomous Drone Racing**|Giovanni Cioffi et.al.|[2210.15287](http://arxiv.org/abs/2210.15287)|**[link](https://github.com/uzh-rpg/learned_inertial_model_odometry)**|
|**2023-08-04**|**Benchmarking Visual-Inertial Deep Multimodal Fusion for Relative Pose Regression and Odometry-aided Absolute Pose Regression**|Felix Ott et.al.|[2208.00919](http://arxiv.org/abs/2208.00919)|null|
|**2022-05-06**|**IMU Based Deep Stride Length Estimation With Self-Supervised Learning**|Jien-De Sui et.al.|[2205.02977](http://arxiv.org/abs/2205.02977)|null|
|**2023-10-17**|**DIDO: Deep Inertial Quadrotor Dynamical Odometry**|Kunyi Zhang et.al.|[2203.03149](http://arxiv.org/abs/2203.03149)|**[link](https://github.com/zhangkunyi/dido)**|
|**2021-11-08**|**Inertial Newton Algorithms Avoiding Strict Saddle Points**|Camille Castera et.al.|[2111.04596](http://arxiv.org/abs/2111.04596)|null|
|**2021-11-01**|**Learning Inertial Odometry for Dynamic Legged Robot State Estimation**|Russell Buchanan et.al.|[2111.00789](http://arxiv.org/abs/2111.00789)|null|
|**2021-09-19**|**Deep Inertial Navigation using Continuous Domain Adaptation and Optimal Transport**|Mohammed Alloulah et.al.|[2106.15178](http://arxiv.org/abs/2106.15178)|null|
|**2021-02-08**|**IDOL: Inertial Deep Orientation-Estimation and Localization**|Scott Sun et.al.|[2102.04024](http://arxiv.org/abs/2102.04024)|**[link](https://github.com/KlabCMU/IDOL)**|
|**2021-01-18**|**Deep Inertial Odometry with Accurate IMU Preintegration**|Rooholla Khorrambakht et.al.|[2101.07061](http://arxiv.org/abs/2101.07061)|null|
|**2020-10-09**|**MARS: Mixed Virtual and Real Wearable Sensors for Human Activity Recognition with Multi-Domain Deep Learning Model**|Ling Pei et.al.|[2009.09404](http://arxiv.org/abs/2009.09404)|null|
|**2022-03-18**|**IMU Preintegrated Features for Efficient Deep Inertial Odometry**|R. Khorrambakht et.al.|[2007.02929](http://arxiv.org/abs/2007.02929)|null|
|**2020-07-10**|**TLIO: Tight Learned Inertial Odometry**|Wenxin Liu et.al.|[2007.01867](http://arxiv.org/abs/2007.01867)|null|
|**2019-05-28**|**Importance of user inputs while using incremental learning to personalize human activity recognition models**|Pekka Siirtola et.al.|[1905.11775](http://arxiv.org/abs/1905.11775)|null|
|**2020-06-01**|**Inertial Block Proximal Methods for Non-Convex Non-Smooth Optimization**|Le Thi Khanh Hien et.al.|[1903.01818](http://arxiv.org/abs/1903.01818)|null|
|**2018-10-10**|**Deep Inertial Poser: Learning to Reconstruct Human Pose from Sparse Inertial Measurements in Real Time**|Yinghao Huang et.al.|[1810.04703](http://arxiv.org/abs/1810.04703)|**[link](https://github.com/eth-ait/dip18)**|
|**2018-09-20**|**OxIOD: The Dataset for Deep Inertial Odometry**|Changhao Chen et.al.|[1809.07491](http://arxiv.org/abs/1809.07491)|null|
|**2017-01-10**|**Inertial Regularization and Selection (IRS): Sequential Regression in High-Dimension and Sparsity**|Chitta Ranjan et.al.|[1610.07216](http://arxiv.org/abs/1610.07216)|null|
|**2016-09-19**|**An Opinion Dynamics Model with Increasing Self-Confidence**|Chu Wang et.al.|[1609.05732](http://arxiv.org/abs/1609.05732)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Transformer

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2004-07-18**|**Electrodynamics under a Possible Alternative to the Lorentz Transformation**|Gabriel D. Puccini et.al.|[physics/0407096](http://arxiv.org/abs/physics/0407096)|null|
|**1997-07-02**|**A Derivation of Three-Dimensional Inertial Transformations**|Francois Goy et.al.|[gr-qc/9707004](http://arxiv.org/abs/gr-qc/9707004)|null|
|**2003-01-21**|**Gravitation as Anholonomy**|R. Aldrovandi et.al.|[gr-qc/0301077](http://arxiv.org/abs/gr-qc/0301077)|null|
|**2023-03-03**|**RIOT: Recursive Inertial Odometry Transformer for Localisation from Low-Cost IMU Measurements**|James Brotchie et.al.|[2303.01641](http://arxiv.org/abs/2303.01641)|null|
|**2023-10-11**|**MMTSA: Multimodal Temporal Segment Attention Network for Efficient Human Activity Recognition**|Ziqi Gao et.al.|[2210.09222](http://arxiv.org/abs/2210.09222)|null|
|**2022-12-08**|**Transformer Inertial Poser: Real-time Human Motion Reconstruction from Sparse IMUs with Simultaneous Terrain Generation**|Yifeng Jiang et.al.|[2203.15720](http://arxiv.org/abs/2203.15720)|**[link](https://github.com/jyf588/transformer-inertial-poser)**|
|**2021-05-28**|**Inertial Sensor Data To Image Encoding For Human Action Recognition**|Zeeshan Ahmad et.al.|[2105.13533](http://arxiv.org/abs/2105.13533)|null|
|**2021-03-17**|**Inertial based Integration with Transformed INS Mechanization in Earth Frame**|Lubin Chang et.al.|[2103.02229](http://arxiv.org/abs/2103.02229)|null|
|**2021-05-07**|**The group structure of dynamical transformations between quantum reference frames**|Angel Ballesteros et.al.|[2012.15769](http://arxiv.org/abs/2012.15769)|null|
|**2018-01-29**|**Visual-Inertial Odometry-enhanced Geometrically Stable ICP for Mapping Applications using Aerial Robots**|Tung Dang et.al.|[1801.08228](http://arxiv.org/abs/1801.08228)|null|
|**2017-10-19**|**SqueezeSeg: Convolutional Neural Nets with Recurrent CRF for Real-Time Road-Object Segmentation from 3D LiDAR Point Cloud**|Bichen Wu et.al.|[1710.07368](http://arxiv.org/abs/1710.07368)|null|
|**2016-04-27**|**Observability-Aware Trajectory Optimization for Self-Calibration with Application to UAVs**|Karol Hausman et.al.|[1604.07905](http://arxiv.org/abs/1604.07905)|null|
|**2013-11-25**|**Clifford Algebra and Space-Time Transformations: Lorentz Transformation and Inertial Transformation**|R. de Oliveira et.al.|[1311.6378](http://arxiv.org/abs/1311.6378)|null|
|**2008-03-06**|**Special Relativity in Quantum Phase Space**|Daniela Dragoman et.al.|[0803.0972](http://arxiv.org/abs/0803.0972)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Occupancy

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2023-07-08**|**Spatio-Temporal Avoidance of Predicted Occupancy in Human-Robot Collaboration**|Jared Flowers et.al.|[2307.03909](http://arxiv.org/abs/2307.03909)|null|
|**2023-07-07**|**LXL: LiDAR Excluded Lean 3D Object Detection with 4D Imaging Radar and Camera Fusion**|Weiyi Xiong et.al.|[2307.00724](http://arxiv.org/abs/2307.00724)|null|
|**2023-06-28**|**SeMLaPS: Real-time Semantic Mapping with Latent Prior Networks and Quasi-Planar Segmentation**|Jingwen Wang et.al.|[2306.16585](http://arxiv.org/abs/2306.16585)|null|
|**2023-06-08**|**UAP-BEV: Uncertainty Aware Planning using Bird's Eye View generated from Surround Monocular Images**|Vikrant Dewangan et.al.|[2306.04939](http://arxiv.org/abs/2306.04939)|null|
|**2023-06-06**|**GMMap: Memory-Efficient Continuous Occupancy Map Using Gaussian Mixture Model**|Peter Zhi Xuan Li et.al.|[2306.03740](http://arxiv.org/abs/2306.03740)|null|
|**2023-05-31**|**Volume Feature Rendering for Fast Neural Radiance Field Reconstruction**|Kang Han et.al.|[2305.17916](http://arxiv.org/abs/2305.17916)|null|
|**2023-05-26**|**How To Not Train Your Dragon: Training-free Embodied Object Goal Navigation with Semantic Frontiers**|Junting Chen et.al.|[2305.16925](http://arxiv.org/abs/2305.16925)|null|
|**2023-05-24**|**OD-NeRF: Efficient Training of On-the-Fly Dynamic Neural Radiance Fields**|Zhiwen Yan et.al.|[2305.14831](http://arxiv.org/abs/2305.14831)|null|
|**2023-05-23**|**Exploiting Radio Fingerprints for Simultaneous Localization and Mapping**|Ran Liu et.al.|[2305.13635](http://arxiv.org/abs/2305.13635)|null|
|**2023-05-25**|**Deep Radar Inverse Sensor Models for Dynamic Occupancy Grid Maps**|Zihang Wei et.al.|[2305.12409](http://arxiv.org/abs/2305.12409)|null|
|**2023-05-11**|**Real-Time Joint Simulation of LiDAR Perception and Motion Planning for Automated Driving**|Zhanhong Huang et.al.|[2305.06966](http://arxiv.org/abs/2305.06966)|null|
|**2023-05-10**|**ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation**|Vishnu Dutt Sharma et.al.|[2305.05519](http://arxiv.org/abs/2305.05519)|null|
|**2023-04-07**|**Combined Registration and Fusion of Evidential Occupancy Grid Maps for Live Digital Twins of Traffic**|Raphael van Kempen et.al.|[2304.03578](http://arxiv.org/abs/2304.03578)|null|
|**2023-03-20**|**Dual-Weight Particle Filter for Radar-Based Dynamic Bayesian Grid Maps**|Max Peter Ronecker et.al.|[2303.11390](http://arxiv.org/abs/2303.11390)|null|
|**2023-03-18**|**Social Occlusion Inference with Vectorized Representation for Autonomous Driving**|Bochao Huang et.al.|[2303.10385](http://arxiv.org/abs/2303.10385)|null|
|**2023-03-07**|**Deep Occupancy-Predictive Representations for Autonomous Driving**|Eivind Meyer et.al.|[2303.04218](http://arxiv.org/abs/2303.04218)|**[link](https://github.com/commonroad/crgeo-learning)**|
|**2023-03-02**|**Grid-Centric Traffic Scenario Perception for Autonomous Driving: A Comprehensive Review**|Yining Shi et.al.|[2303.01212](http://arxiv.org/abs/2303.01212)|null|
|**2023-02-28**|**ROG-Map: An Efficient Robocentric Occupancy Grid Map for Large-scene and High-resolution LiDAR-based Motion Planning**|Yunfan Ren et.al.|[2302.14819](http://arxiv.org/abs/2302.14819)|**[link](https://github.com/hku-mars/rog-map)**|
|**2023-02-24**|**CATNIPS: Collision Avoidance Through Neural Implicit Probabilistic Scenes**|Timothy Chen et.al.|[2302.12931](http://arxiv.org/abs/2302.12931)|null|
|**2023-05-29**|**Active Velocity Estimation using Light Curtains via Self-Supervised Multi-Armed Bandits**|Siddharth Ancha et.al.|[2302.12597](http://arxiv.org/abs/2302.12597)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Occupancy Map

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-17**|**POP-3D: Open-Vocabulary 3D Occupancy Prediction from Images**|Antonin Vobecky et.al.|[2401.09413](http://arxiv.org/abs/2401.09413)|null|
|**2024-01-05**|**Comparative Evaluation of RGB-D SLAM Methods for Humanoid Robot Localization and Mapping**|Amirhosein Vedadi et.al.|[2401.02816](http://arxiv.org/abs/2401.02816)|null|
|**2023-12-15**|**Drones Guiding Drones: Cooperative Navigation of a Less-Equipped Micro Aerial Vehicle in Cluttered Environments**|Václav Pritzl et.al.|[2312.09786](http://arxiv.org/abs/2312.09786)|null|
|**2023-12-10**|**Graph-based Prediction and Planning Policy Network (GP3Net) for scalable self-driving in dynamic environments using Deep Reinforcement Learning**|Jayabrata Chowdhury et.al.|[2312.05784](http://arxiv.org/abs/2312.05784)|null|
|**2023-12-06**|**VLFM: Vision-Language Frontier Maps for Zero-Shot Semantic Navigation**|Naoki Yokoyama et.al.|[2312.03275](http://arxiv.org/abs/2312.03275)|null|
|**2023-11-16**|**Safety Aware Autonomous Path Planning Using Model Predictive Reinforcement Learning for Inland Waterways**|Astrid Vanneste et.al.|[2311.09878](http://arxiv.org/abs/2311.09878)|null|
|**2023-11-07**|**Spatio-Temporal Anomaly Detection with Graph Networks for Data Quality Monitoring of the Hadron Calorimeter**|Mulugeta Weldezgina Asres et.al.|[2311.04190](http://arxiv.org/abs/2311.04190)|null|
|**2023-10-03**|**Predicting Future Spatiotemporal Occupancy Grids with Semantics for Autonomous Driving**|Maneekwan Toyungyernsub et.al.|[2310.01723](http://arxiv.org/abs/2310.01723)|null|
|**2023-11-16**|**Active SLAM Utility Function Exploiting Path Entropy**|Muhammad Farhan Ahmed et.al.|[2309.16490](http://arxiv.org/abs/2309.16490)|null|
|**2023-09-18**|**Efficient and Accurate Mapping of Subsurface Anatomy via Online Trajectory Optimization for Robot Assisted Surgery**|Brian Y. Cho et.al.|[2309.10154](http://arxiv.org/abs/2309.10154)|null|
|**2023-09-17**|**Heuristic-based Incremental Probabilistic Roadmap for Efficient UAV Exploration in Dynamic Environments**|Zhefan Xu et.al.|[2309.09121](http://arxiv.org/abs/2309.09121)|null|
|**2023-09-22**|**OccupancyDETR: Making Semantic Scene Completion as Straightforward as Object Detection**|Yupeng Jia et.al.|[2309.08504](http://arxiv.org/abs/2309.08504)|**[link](https://github.com/jypjypjypjyp/occupancydetr)**|
|**2023-09-15**|**Object-oriented mapping in dynamic environments**|Matti Pekkanen et.al.|[2309.08324](http://arxiv.org/abs/2309.08324)|null|
|**2023-09-12**|**MedShapeNet -- A Large-Scale Dataset of 3D Medical Shapes for Computer Vision**|Jianning Li et.al.|[2308.16139](http://arxiv.org/abs/2308.16139)|**[link](https://github.com/jianningli/medshapenet-feedback)**|
|**2023-08-18**|**DReg-NeRF: Deep Registration for Neural Radiance Fields**|Yu Chen et.al.|[2308.09386](http://arxiv.org/abs/2308.09386)|**[link](https://github.com/aibluefisher/dreg-nerf)**|
|**2023-08-14**|**UniWorld: Autonomous Driving Pre-training via World Models**|Chen Min et.al.|[2308.07234](http://arxiv.org/abs/2308.07234)|**[link](https://github.com/chaytonmin/uniworld)**|
|**2023-08-10**|**Robust Lifelong Indoor LiDAR Localization using the Area Graph**|Fujing Xie et.al.|[2308.05593](http://arxiv.org/abs/2308.05593)|null|
|**2023-08-10**|**Occupancy Grid Map to Pose Graph-based Map: Robust BIM-based 2D-LiDAR Localization for Lifelong Indoor Navigation in Changing and Dynamic Environments**|Miguel Arturo Vega Torres et.al.|[2308.05443](http://arxiv.org/abs/2308.05443)|**[link](https://github.com/migvega/ogm2pgbm)**|
|**2023-08-08**|**Vehicle Motion Forecasting using Prior Information and Semantic-assisted Occupancy Grid Maps**|Rabbia Asghar et.al.|[2308.04303](http://arxiv.org/abs/2308.04303)|null|
|**2023-07-17**|**Uncertainty-Aware Acoustic Localization and Mapping for Underwater Robots**|Jingyu Song et.al.|[2307.08647](http://arxiv.org/abs/2307.08647)|null|
|**2023-10-05**|**Occupancy Grid Mapping without Ray-Casting for High-resolution LiDAR Sensors**|Yixi Cai et.al.|[2307.08493](http://arxiv.org/abs/2307.08493)|**[link](https://github.com/hku-mars/d-map)**|
|**2023-07-08**|**Spatio-Temporal Avoidance of Predicted Occupancy in Human-Robot Collaboration**|Jared Flowers et.al.|[2307.03909](http://arxiv.org/abs/2307.03909)|null|
|**2023-10-03**|**LXL: LiDAR Excluded Lean 3D Object Detection with 4D Imaging Radar and Camera Fusion**|Weiyi Xiong et.al.|[2307.00724](http://arxiv.org/abs/2307.00724)|null|
|**2023-10-13**|**SeMLaPS: Real-time Semantic Mapping with Latent Prior Networks and Quasi-Planar Segmentation**|Jingwen Wang et.al.|[2306.16585](http://arxiv.org/abs/2306.16585)|null|
|**2023-06-08**|**UAP-BEV: Uncertainty Aware Planning using Bird's Eye View generated from Surround Monocular Images**|Vikrant Dewangan et.al.|[2306.04939](http://arxiv.org/abs/2306.04939)|**[link](https://github.com/Vikr-182/UAP-BEV)**|
|**2023-10-10**|**GMMap: Memory-Efficient Continuous Occupancy Map Using Gaussian Mixture Model**|Peter Zhi Xuan Li et.al.|[2306.03740](http://arxiv.org/abs/2306.03740)|**[link](https://github.com/mit-lean/gmmap)**|
|**2023-05-31**|**Volume Feature Rendering for Fast Neural Radiance Field Reconstruction**|Kang Han et.al.|[2305.17916](http://arxiv.org/abs/2305.17916)|null|
|**2023-05-26**|**How To Not Train Your Dragon: Training-free Embodied Object Goal Navigation with Semantic Frontiers**|Junting Chen et.al.|[2305.16925](http://arxiv.org/abs/2305.16925)|null|
|**2023-05-24**|**OD-NeRF: Efficient Training of On-the-Fly Dynamic Neural Radiance Fields**|Zhiwen Yan et.al.|[2305.14831](http://arxiv.org/abs/2305.14831)|null|
|**2023-05-23**|**Exploiting Radio Fingerprints for Simultaneous Localization and Mapping**|Ran Liu et.al.|[2305.13635](http://arxiv.org/abs/2305.13635)|null|
|**2023-05-25**|**Deep Radar Inverse Sensor Models for Dynamic Occupancy Grid Maps**|Zihang Wei et.al.|[2305.12409](http://arxiv.org/abs/2305.12409)|null|
|**2023-08-30**|**Real-Time Joint Simulation of LiDAR Perception and Motion Planning for Automated Driving**|Zhanhong Huang et.al.|[2305.06966](http://arxiv.org/abs/2305.06966)|null|
|**2023-05-10**|**ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation**|Vishnu Dutt Sharma et.al.|[2305.05519](http://arxiv.org/abs/2305.05519)|null|
|**2023-08-23**|**Combined Registration and Fusion of Evidential Occupancy Grid Maps for Live Digital Twins of Traffic**|Raphael van Kempen et.al.|[2304.03578](http://arxiv.org/abs/2304.03578)|null|
|**2023-03-20**|**Dual-Weight Particle Filter for Radar-Based Dynamic Bayesian Grid Maps**|Max Peter Ronecker et.al.|[2303.11390](http://arxiv.org/abs/2303.11390)|null|
|**2023-08-16**|**Social Occlusion Inference with Vectorized Representation for Autonomous Driving**|Bochao Huang et.al.|[2303.10385](http://arxiv.org/abs/2303.10385)|null|
|**2023-03-07**|**Deep Occupancy-Predictive Representations for Autonomous Driving**|Eivind Meyer et.al.|[2303.04218](http://arxiv.org/abs/2303.04218)|null|
|**2023-03-02**|**Grid-Centric Traffic Scenario Perception for Autonomous Driving: A Comprehensive Review**|Yining Shi et.al.|[2303.01212](http://arxiv.org/abs/2303.01212)|null|
|**2023-02-28**|**ROG-Map: An Efficient Robocentric Occupancy Grid Map for Large-scene and High-resolution LiDAR-based Motion Planning**|Yunfan Ren et.al.|[2302.14819](http://arxiv.org/abs/2302.14819)|**[link](https://github.com/hku-mars/rog-map)**|
|**2023-12-20**|**Accurate Gaussian-Process-based Distance Fields with applications to Echolocation and Mapping**|Cedric Le Gentil et.al.|[2302.13005](http://arxiv.org/abs/2302.13005)|null|
|**2023-11-25**|**CATNIPS: Collision Avoidance Through Neural Implicit Probabilistic Scenes**|Timothy Chen et.al.|[2302.12931](http://arxiv.org/abs/2302.12931)|null|
|**2023-05-29**|**Active Velocity Estimation using Light Curtains via Self-Supervised Multi-Armed Bandits**|Siddharth Ancha et.al.|[2302.12597](http://arxiv.org/abs/2302.12597)|null|
|**2023-02-19**|**FusionMotion: Multi-Sensor Asynchronous Fusion for Continuous Occupancy Prediction via Neural-ODE**|Yining Shi et.al.|[2302.09585](http://arxiv.org/abs/2302.09585)|**[link](https://github.com/synsin0/fusionmotion)**|
|**2023-02-13**|**gpcgc: a green point cloud geometry coding method**|Qingyang Zhou et.al.|[2302.06062](http://arxiv.org/abs/2302.06062)|null|
|**2023-02-03**|**SphereMap: Dynamic Multi-Layer Graph Structure for Rapid Safety-Aware UAV Planning**|Tomáš Musil et.al.|[2302.01833](http://arxiv.org/abs/2302.01833)|null|
|**2023-01-22**|**Improving Autonomous Vehicle Mapping and Navigation in Work Zones Using Crowdsourcing Vehicle Trajectories**|Hanlin Chen et.al.|[2301.09194](http://arxiv.org/abs/2301.09194)|null|
|**2023-01-20**|**Occlusion Reasoning for Skeleton Extraction of Self-Occluded Tree Canopies**|Chung Hee Kim et.al.|[2301.08387](http://arxiv.org/abs/2301.08387)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

## Occupancy Predict

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-01-17**|**POP-3D: Open-Vocabulary 3D Occupancy Prediction from Images**|Antonin Vobecky et.al.|[2401.09413](http://arxiv.org/abs/2401.09413)|null|
|**2024-01-13**|**UniVision: A Unified Framework for Vision-Centric 3D Perception**|Yu Hong et.al.|[2401.06994](http://arxiv.org/abs/2401.06994)|null|
|**2024-01-10**|**Occupancy Prediction for Building Energy Systems with Latent Force Models**|Thore Wietzke et.al.|[2401.05074](http://arxiv.org/abs/2401.05074)|**[link](https://github.com/thorewietzke/occupancy-benchmark-dataset)**|
|**2023-12-29**|**Fully Sparse 3D Panoptic Occupancy Prediction**|Haisong Liu et.al.|[2312.17118](http://arxiv.org/abs/2312.17118)|null|
|**2023-12-22**|**Room Occupancy Prediction: Exploring the Power of Machine Learning and Temporal Insights**|Siqi Mao et.al.|[2312.14426](http://arxiv.org/abs/2312.14426)|null|
|**2023-12-19**|**Regulating Intermediate 3D Features for Vision-Centric Autonomous Driving**|Junkai Xu et.al.|[2312.11837](http://arxiv.org/abs/2312.11837)|**[link](https://github.com/cskkxjk/vampire)**|
|**2023-12-19**|**RadOcc: Learning Cross-Modality Occupancy Knowledge through Rendering Assisted Distillation**|Haiming Zhang et.al.|[2312.11829](http://arxiv.org/abs/2312.11829)|null|
|**2023-12-14**|**OccNeRF: Self-Supervised Multi-Camera Occupancy Prediction with Neural Radiance Fields**|Chubin Zhang et.al.|[2312.09243](http://arxiv.org/abs/2312.09243)|**[link](https://github.com/linshan-bin/occnerf)**|
|**2023-12-09**|**OctreeOcc: Efficient and Multi-Granularity Occupancy Prediction Using Octree Queries**|Yuhang Lu et.al.|[2312.03774](http://arxiv.org/abs/2312.03774)|**[link](https://github.com/4DVLab/OctreeOcc)**|
|**2023-12-04**|**COTR: Compact Occupancy TRansformer for Vision-based 3D Occupancy Prediction**|Qihang Ma et.al.|[2312.01919](http://arxiv.org/abs/2312.01919)|null|
|**2023-11-29**|**SelfOcc: Self-Supervised Vision-Based 3D Occupancy Prediction**|Yuanhui Huang et.al.|[2311.12754](http://arxiv.org/abs/2311.12754)|**[link](https://github.com/huang-yh/selfocc)**|
|**2023-11-18**|**FlashOcc: Fast and Memory-Efficient Occupancy Prediction via Channel-to-Height Plugin**|Zichen Yu et.al.|[2311.12058](http://arxiv.org/abs/2311.12058)|null|
|**2023-11-19**|**SOccDPT: Semi-Supervised 3D Semantic Occupancy from Dense Prediction Transformers trained under memory constraints**|Aditya Nalgunda Ganesh et.al.|[2311.11371](http://arxiv.org/abs/2311.11371)|null|
|**2023-11-03**|**EmerNeRF: Emergent Spatial-Temporal Scene Decomposition via Self-Supervision**|Jiawei Yang et.al.|[2311.02077](http://arxiv.org/abs/2311.02077)|null|
|**2023-10-03**|**Predicting Future Spatiotemporal Occupancy Grids with Semantics for Autonomous Driving**|Maneekwan Toyungyernsub et.al.|[2310.01723](http://arxiv.org/abs/2310.01723)|null|
|**2023-09-25**|**Scene Informer: Anchor-based Occlusion Inference and Trajectory Prediction in Partially Observable Environments**|Bernard Lange et.al.|[2309.13893](http://arxiv.org/abs/2309.13893)|**[link](https://github.com/sisl/sceneinformer)**|
|**2023-09-25**|**SPOT: Scalable 3D Pre-training via Occupancy Prediction for Autonomous Driving**|Xiangchao Yan et.al.|[2309.10527](http://arxiv.org/abs/2309.10527)|**[link](https://github.com/pjlab-adg/3dtrans)**|
|**2023-09-18**|**RenderOcc: Vision-Centric 3D Occupancy Prediction with 2D Rendering Supervision**|Mingjie Pan et.al.|[2309.09502](http://arxiv.org/abs/2309.09502)|**[link](https://github.com/pmj110119/renderocc)**|
|**2023-08-31**|**PointOcc: Cylindrical Tri-Perspective View for Point-based 3D Semantic Occupancy Prediction**|Sicheng Zuo et.al.|[2308.16896](http://arxiv.org/abs/2308.16896)|**[link](https://github.com/wzzheng/pointocc)**|
|**2023-08-02**|**Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving**|Ben Agro et.al.|[2308.01471](http://arxiv.org/abs/2308.01471)|null|
|**2023-08-14**|**FusionAD: Multi-modality Fusion for Prediction and Planning Tasks of Autonomous Driving**|Tengju Ye et.al.|[2308.01006](http://arxiv.org/abs/2308.01006)|**[link](https://github.com/westlake-autolab/fusionad)**|
|**2023-07-12**|**OG: Equip vision occupancy with instance segmentation and visual grounding**|Zichao Dong et.al.|[2307.05873](http://arxiv.org/abs/2307.05873)|null|
|**2023-07-04**|**FB-OCC: 3D Occupancy Prediction based on Forward-Backward View Transformation**|Zhiqi Li et.al.|[2307.01492](http://arxiv.org/abs/2307.01492)|**[link](https://github.com/nvlabs/fb-bev)**|
|**2023-06-28**|**Point2Point : A Framework for Efficient Deep Learning on Hilbert sorted Point Clouds with applications in Spatio-Temporal Occupancy Prediction**|Athrva Atul Pandhare et.al.|[2306.16306](http://arxiv.org/abs/2306.16306)|null|
|**2023-06-20**|**Multi-Scale Occ: 4th Place Solution for CVPR 2023 3D Occupancy Prediction Challenge**|Yangyang Ding et.al.|[2306.11414](http://arxiv.org/abs/2306.11414)|null|
|**2023-06-16**|**PanoOcc: Unified Occupancy Representation for Camera-based 3D Panoptic Segmentation**|Yuqi Wang et.al.|[2306.10013](http://arxiv.org/abs/2306.10013)|**[link](https://github.com/robertwyq/panoocc)**|
|**2023-06-15**|**UniOcc: Unifying Vision-Centric 3D Occupancy Prediction with Geometric and Semantic Rendering**|Mingjie Pan et.al.|[2306.09117](http://arxiv.org/abs/2306.09117)|null|
|**2023-06-15**|**Motion Perceiver: Real-Time Occupancy Forecasting for Embedded Systems**|Bryce Ferenczi et.al.|[2306.08879](http://arxiv.org/abs/2306.08879)|null|
|**2024-01-11**|**BEV-IO: Enhancing Bird's-Eye-View 3D Detection with Instance Occupancy**|Zaibin Zhang et.al.|[2305.16829](http://arxiv.org/abs/2305.16829)|null|
|**2023-06-14**|**OVO: Open-Vocabulary Occupancy**|Zhiyu Tan et.al.|[2305.16133](http://arxiv.org/abs/2305.16133)|**[link](https://github.com/dzcgaara/OVO)**|
|**2023-05-25**|**Learning Occupancy for Monocular 3D Object Detection**|Liang Peng et.al.|[2305.15694](http://arxiv.org/abs/2305.15694)|**[link](https://github.com/spengliang/occupancym3d)**|
|**2023-05-15**|**GeoMAE: Masked Geometric Target Prediction for Self-supervised Point Cloud Pre-Training**|Xiaoyu Tian et.al.|[2305.08808](http://arxiv.org/abs/2305.08808)|**[link](https://github.com/tsinghua-mars-lab/geomae)**|
|**2023-05-05**|**Occupancy Prediction-Guided Neural Planner for Autonomous Driving**|Haochen Liu et.al.|[2305.03303](http://arxiv.org/abs/2305.03303)|**[link](https://github.com/georgeliu233/opgp)**|
|**2023-12-13**|**Occ3D: A Large-Scale 3D Occupancy Prediction Benchmark for Autonomous Driving**|Xiaoyu Tian et.al.|[2304.14365](http://arxiv.org/abs/2304.14365)|**[link](https://github.com/Tsinghua-MARS-Lab/Occ3D)**|
|**2023-04-11**|**OccFormer: Dual-path Transformer for Vision-based 3D Semantic Occupancy Prediction**|Yunpeng Zhang et.al.|[2304.05316](http://arxiv.org/abs/2304.05316)|**[link](https://github.com/zhangyp15/occformer)**|
|**2023-08-27**|**SurroundOcc: Multi-Camera 3D Occupancy Prediction for Autonomous Driving**|Yi Wei et.al.|[2303.09551](http://arxiv.org/abs/2303.09551)|**[link](https://github.com/weiyithu/surroundocc)**|
|**2023-03-07**|**Deep Occupancy-Predictive Representations for Autonomous Driving**|Eivind Meyer et.al.|[2303.04218](http://arxiv.org/abs/2303.04218)|null|
|**2023-04-30**|**Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting**|Tarasha Khurana et.al.|[2302.13130](http://arxiv.org/abs/2302.13130)|**[link](https://github.com/tarashakhurana/4d-occ-forecasting)**|
|**2023-02-22**|**Using infinite server queues with partial information for occupancy prediction**|Nikki Sonenberg et.al.|[2302.11395](http://arxiv.org/abs/2302.11395)|null|
|**2023-02-19**|**FusionMotion: Multi-Sensor Asynchronous Fusion for Continuous Occupancy Prediction via Neural-ODE**|Yining Shi et.al.|[2302.09585](http://arxiv.org/abs/2302.09585)|**[link](https://github.com/synsin0/fusionmotion)**|
|**2023-03-02**|**Tri-Perspective View for Vision-Based 3D Semantic Occupancy Prediction**|Yuanhui Huang et.al.|[2302.07817](http://arxiv.org/abs/2302.07817)|**[link](https://github.com/wzzheng/tpvformer)**|
|**2022-10-18**|**Differentiable Raycasting for Self-supervised Occupancy Forecasting**|Tarasha Khurana et.al.|[2210.01917](http://arxiv.org/abs/2210.01917)|**[link](https://github.com/tarashakhurana/emergent-occ-forecasting)**|
|**2023-08-24**|**LOPR: Latent Occupancy PRediction using Generative Models**|Bernard Lange et.al.|[2210.01249](http://arxiv.org/abs/2210.01249)|**[link](https://github.com/sisl/lopr)**|
|**2022-09-27**|**Dynamics-Aware Spatiotemporal Occupancy Prediction in Urban Environments**|Maneekwan Toyungyernsub et.al.|[2209.13172](http://arxiv.org/abs/2209.13172)|null|
|**2022-09-22**|**Dynamic charging management for electric vehicle demand responsive transport**|Tai-Yu Ma et.al.|[2209.10830](http://arxiv.org/abs/2209.10830)|null|
|**2022-08-11**|**Modeling Price Elasticity for Occupancy Prediction in Hotel Dynamic Pricing**|Fanwei Zhu et.al.|[2208.03135](http://arxiv.org/abs/2208.03135)|null|
|**2022-12-01**|**Occupancy Planes for Single-view RGB-D Human Reconstruction**|Xiaoming Zhao et.al.|[2208.02817](http://arxiv.org/abs/2208.02817)|**[link](https://github.com/xiaoming-zhao/oplanes)**|
|**2023-10-09**|**Occupancy-MAE: Self-supervised Pre-training Large-scale LiDAR Point Clouds with Masked Occupancy Autoencoders**|Chen Min et.al.|[2206.09900](http://arxiv.org/abs/2206.09900)|**[link](https://github.com/chaytonmin/occupancy-mae)**|
|**2022-06-02**|**StopNet: Scalable Trajectory and Occupancy Prediction for Urban Autonomous Driving**|Jinkyu Kim et.al.|[2206.00991](http://arxiv.org/abs/2206.00991)|null|
|**2022-05-06**|**Predicting Future Occupancy Grids in Dynamic Environment with Spatio-Temporal Learning**|Khushdeep Singh Mann et.al.|[2205.03212](http://arxiv.org/abs/2205.03212)|**[link](https://github.com/ksm26/spatiotemporal-predictions)**|
|**2023-08-03**|**ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation**|Vishnu Dutt Sharma et.al.|[2203.04177](http://arxiv.org/abs/2203.04177)|null|
|**2022-03-08**|**Occupancy Flow Fields for Motion Forecasting in Autonomous Driving**|Reza Mahjourian et.al.|[2203.03875](http://arxiv.org/abs/2203.03875)|null|
|**2021-12-27**|**Vegetation Stratum Occupancy Prediction from Airborne LiDAR 3D Point Clouds**|Ekaterina Kalinicheva et.al.|[2112.13583](http://arxiv.org/abs/2112.13583)|null|

<p align=right>(<a href=#updated-on-20240120>back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/Vincentqyw/cv-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/Vincentqyw/cv-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/Vincentqyw/cv-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/Vincentqyw/cv-arxiv-daily/issues

