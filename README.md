[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2024.05.08
> Usage instructions: [here](./docs/README.md#usage)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#slam>SLAM</a></li>
    <li><a href=#bev>BEV</a></li>
    <li><a href=#gaussian-splatting>Gaussian Splatting</a></li>
    <li><a href=#registration>Registration</a></li>
    <li><a href=#localization>Localization</a></li>
    <li><a href=#feature>Feature</a></li>
    <li><a href=#matching>Matching</a></li>
    <li><a href=#sfm>SFM</a></li>
    <li><a href=#imu>IMU</a></li>
    <li><a href=#transformer>Transformer</a></li>
    <li><a href=#nerf>NeRF</a></li>
    <li><a href=#occupancy>Occupancy</a></li>
  </ol>
</details>

## SLAM

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-05-07**|**Bayesian Simultaneous Localization and Multi-Lane Tracking Using Onboard Sensors and a SD Map**|Yuxuan Xia et.al.|[2405.04290](http://arxiv.org/abs/2405.04290)|null|
|**2024-05-07**|**IMU-Aided Event-based Stereo Visual Odometry**|Junkai Niu et.al.|[2405.04071](http://arxiv.org/abs/2405.04071)|**[link](https://github.com/nail-hnu/esvio_aa)**|
|**2023-12-27**|**Wheel Odometry-Based Localization for Autonomous Wheelchair**|P Paryanto et.al.|[2405.02290](http://arxiv.org/abs/2405.02290)|null|
|**2024-04-27**|**An Attention-Based Deep Learning Architecture for Real-Time Monocular Visual Odometry: Applications to GPS-free Drone Navigation**|Olivier Brochu Dufour et.al.|[2404.17745](http://arxiv.org/abs/2404.17745)|null|
|**2024-04-26**|**Camera Motion Estimation from RGB-D-Inertial Scene Flow**|Samuel Cerezo et.al.|[2404.17251](http://arxiv.org/abs/2404.17251)|null|
|**2024-04-23**|**Multi-Session SLAM with Differentiable Wide-Baseline Pose Optimization**|Lahav Lipson et.al.|[2404.15263](http://arxiv.org/abs/2404.15263)|**[link](https://github.com/princeton-vl/multislam_diffpose)**|
|**2024-04-18**|**SPOT: Point Cloud Based Stereo Visual Place Recognition for Similar and Opposing Viewpoints**|Spencer Carmichael et.al.|[2404.12339](http://arxiv.org/abs/2404.12339)|null|
|**2024-04-17**|**VBR: A Vision Benchmark in Rome**|Leonardo Brizi et.al.|[2404.11322](http://arxiv.org/abs/2404.11322)|**[link](https://github.com/rvp-group/vbr-devkit)**|
|**2024-04-14**|**Increasing SLAM Pose Accuracy by Ground-to-Satellite Image Registration**|Yanhao Zhang et.al.|[2404.09169](http://arxiv.org/abs/2404.09169)|null|
|**2024-04-06**|**Salient Sparse Visual Odometry With Pose-Only Supervision**|Siyu Chen et.al.|[2404.04677](http://arxiv.org/abs/2404.04677)|null|
|**2024-03-25**|**A Comparative Analysis of Visual Odometry in Virtual and Real-World Railways Environments**|Gianluca D'Amico et.al.|[2403.17084](http://arxiv.org/abs/2403.17084)|null|
|**2024-03-19**|**On Designing Consistent Covariance Recovery from a Deep Learning Visual Odometry Engine**|Jagatpreet Singh Nir et.al.|[2403.13170](http://arxiv.org/abs/2403.13170)|null|
|**2024-03-18**|**The POLAR Traverse Dataset: A Dataset of Stereo Camera Images Simulating Traverses across Lunar Polar Terrain under Extreme Lighting Conditions**|Margaret Hansen et.al.|[2403.12194](http://arxiv.org/abs/2403.12194)|null|
|**2024-03-18**|**An Accurate and Real-time Relative Pose Estimation from Triple Point-line Images by Decoupling Rotation and Translation**|Zewen Xu et.al.|[2403.11639](http://arxiv.org/abs/2403.11639)|null|
|**2024-03-16**|**Efficient Domain Adaptation for Endoscopic Visual Odometry**|Junyang Wu et.al.|[2403.10860](http://arxiv.org/abs/2403.10860)|null|
|**2024-03-14**|**Visual Inertial Odometry using Focal Plane Binary Features (BIT-VIO)**|Matthew Lisondra et.al.|[2403.09882](http://arxiv.org/abs/2403.09882)|null|
|**2024-03-02**|**Grid-based Fast and Structural Visual Odometry**|Zhang Zhihe et.al.|[2403.01110](http://arxiv.org/abs/2403.01110)|null|
|**2024-02-25**|**VOLoc: Visual Place Recognition by Querying Compressed Lidar Map**|Xudong Cai et.al.|[2402.15961](http://arxiv.org/abs/2402.15961)|**[link](https://github.com/master-cai/voloc)**|
|**2024-02-22**|**Secure Navigation using Landmark-based Localization in a GPS-denied Environment**|Ganesh Sapkota et.al.|[2402.14280](http://arxiv.org/abs/2402.14280)|null|
|**2024-02-19**|**Landmark-based Localization using Stereo Vision and Deep Learning in GPS-Denied Battlefield Environment**|Ganesh Sapkota et.al.|[2402.12551](http://arxiv.org/abs/2402.12551)|null|
|**2024-02-07**|**Online and Certifiably Correct Visual Odometry and Mapping**|Devansh R Agrawal et.al.|[2402.05254](http://arxiv.org/abs/2402.05254)|null|
|**2024-02-06**|**YOLOPoint Joint Keypoint and Object Detection**|Anton Backhaus et.al.|[2402.03989](http://arxiv.org/abs/2402.03989)|**[link](https://github.com/unibwtas/yolopoint)**|
|**2024-01-19**|**Motion Consistency Loss for Monocular Visual Odometry with Attention-Based Deep Learning**|André O. Françani et.al.|[2401.10857](http://arxiv.org/abs/2401.10857)|null|
|**2024-01-17**|**Event-Based Visual Odometry on Non-Holonomic Ground Vehicles**|Wanting Xu et.al.|[2401.09331](http://arxiv.org/abs/2401.09331)|**[link](https://github.com/gowanting/nhevo)**|
|**2024-01-11**|**On State Estimation in Multi-Sensor Fusion Navigation: Optimization and Filtering**|Feng Zhu et.al.|[2401.05836](http://arxiv.org/abs/2401.05836)|null|
|**2023-12-19**|**Loss it right: Euclidean and Riemannian Metrics in Learning-based Visual Odometry**|Olaya Álvarez-Tuñón et.al.|[2401.05396](http://arxiv.org/abs/2401.05396)|**[link](https://github.com/remaro-network/Loss_VO_right)**|
|**2024-01-07**|**Amirkabir campus dataset: Real-world challenges and scenarios of Visual Inertial Odometry (VIO) for visually impaired people**|Ali Samadzadeh et.al.|[2401.03604](http://arxiv.org/abs/2401.03604)|**[link](https://github.com/A3DV/VIRec)**|
|**2024-01-03**|**LEAP-VO: Long-term Effective Any Point Tracking for Visual Odometry**|Weirong Chen et.al.|[2401.01887](http://arxiv.org/abs/2401.01887)|null|
|**2023-12-28**|**SR-LIVO: LiDAR-Inertial-Visual Odometry and Mapping with Sweep Reconstruction**|Zikang Yuan et.al.|[2312.16800](http://arxiv.org/abs/2312.16800)|**[link](https://github.com/ZikangYuan/sr_livo)**|
|**2023-12-20**|**NeRF-VO: Real-Time Sparse Visual Odometry with Neural Radiance Fields**|Jens Naumann et.al.|[2312.13471](http://arxiv.org/abs/2312.13471)|null|
|**2023-12-22**|**Ternary-type Opacity and Hybrid Odometry for RGB-only NeRF-SLAM**|Junru Lin et.al.|[2312.13332](http://arxiv.org/abs/2312.13332)|null|
|**2023-12-20**|**Brain-Inspired Visual Odometry: Balancing Speed and Interpretability through a System of Systems Approach**|Habib Boloorchi Tabrizi et.al.|[2312.13162](http://arxiv.org/abs/2312.13162)|**[link](https://github.com/habib-Boloorchi/CIVO-Visual-Odometry-)**|
|**2023-12-20**|**Trajectory Approximation of Video Based on Phase Correlation for Forward Facing Camera**|Abdulkadhem A. Abdulkadhem et.al.|[2312.12680](http://arxiv.org/abs/2312.12680)|null|
|**2023-12-15**|**Deep Event Visual Odometry**|Simon Klenk et.al.|[2312.09800](http://arxiv.org/abs/2312.09800)|**[link](https://github.com/tum-vision/devo)**|
|**2024-04-17**|**SuperPrimitive: Scene Reconstruction at a Primitive Level**|Kirill Mazur et.al.|[2312.05889](http://arxiv.org/abs/2312.05889)|null|
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
|**2024-03-20**|**Exposing the Unseen: Exposure Time Emulation for Offline Benchmarking of Vision Algorithms**|Olivier Gamache et.al.|[2309.13139](http://arxiv.org/abs/2309.13139)|**[link](https://github.com/norlab-ulaval/borealhdr)**|
|**2023-09-20**|**Conformalized Multimodal Uncertainty Regression and Reasoning**|Domenico Parente et.al.|[2309.11018](http://arxiv.org/abs/2309.11018)|null|
|**2024-03-26**|**OCC-VO: Dense Mapping via 3D Occupancy-Based Visual Odometry for Autonomous Driving**|Heng Li et.al.|[2309.11011](http://arxiv.org/abs/2309.11011)|null|
|**2023-09-19**|**LiDAR-Generated Images Derived Keypoints Assisted Point Cloud Registration Scheme in Odometry Estimation**|Haizhou Zhang et.al.|[2309.10436](http://arxiv.org/abs/2309.10436)|**[link](https://github.com/tiers/ws-lidar-as-camera-odom)**|
|**2024-03-04**|**Dive Deeper into Rectifying Homography for Stereo Camera Online Self-Calibration**|Hongbo Zhao et.al.|[2309.10314](http://arxiv.org/abs/2309.10314)|null|
|**2024-03-20**|**End-to-end Learned Visual Odometry with Events and Frames**|Roberto Pellerito et.al.|[2309.09947](http://arxiv.org/abs/2309.09947)|null|
|**2023-09-14**|**An Explicit Method for Fast Monocular Depth Recovery in Corridor Environments**|Yehao Liu et.al.|[2309.07408](http://arxiv.org/abs/2309.07408)|null|
|**2024-05-03**|**Evaluating Visual Odometry Methods for Autonomous Driving in Rain**|Yu Xiang Tan et.al.|[2309.05249](http://arxiv.org/abs/2309.05249)|null|
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
|**2024-03-21**|**Learning a Depth Covariance Function**|Eric Dexheimer et.al.|[2303.12157](http://arxiv.org/abs/2303.12157)|null|
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
|**2023-01-03**|**LunarNav: Crater-based Localization for Long-range Autonomous Lunar Rover Navigation**|Shreyansh Daftry et.al.|[2301.01350](http://arxiv.org/abs/2301.01350)|null|
|**2022-12-31**|**4Seasons: Benchmarking Visual SLAM and Long-Term Localization for Autonomous Driving in Challenging Conditions**|Patrick Wenzel et.al.|[2301.01147](http://arxiv.org/abs/2301.01147)|null|
|**2022-12-25**|**A Combined Approach Toward Consistent Reconstructions of Indoor Spaces Based on 6D RGB-D Odometry and KinectFusion**|Nadia Figueroa et.al.|[2212.14772](http://arxiv.org/abs/2212.14772)|null|
|**2023-04-14**|**ESVIO: Event-based Stereo Visual Inertial Odometry**|Peiyu Chen et.al.|[2212.13184](http://arxiv.org/abs/2212.13184)|**[link](https://github.com/arclab-hku/event_based_vo-vio-slam)**|
|**2023-08-04**|**AirVO: An Illumination-Robust Point-Line Visual Odometry**|Kuan Xu et.al.|[2212.07595](http://arxiv.org/abs/2212.07595)|**[link](https://github.com/sair-lab/airvo)**|
|**2022-12-14**|**Autonomous Vehicle Navigation with LIDAR using Path Planning**|Rahul M K et.al.|[2212.07155](http://arxiv.org/abs/2212.07155)|null|
|**2022-11-28**|**Safety-quantifiable Line Feature-based Monocular Visual Localization with 3D Prior Map**|Xi Zheng et.al.|[2211.15127](http://arxiv.org/abs/2211.15127)|null|
|**2022-11-29**|**BALF: Simple and Efficient Blur Aware Local Feature Detector**|Zhenjun Zhao et.al.|[2211.14731](http://arxiv.org/abs/2211.14731)|null|
|**2022-11-27**|**Development of a Modular Real-time Shared-control System for a Smart Wheelchair**|Vaishanth Ramaraj et.al.|[2211.14711](http://arxiv.org/abs/2211.14711)|null|
|**2022-11-22**|**Vision-based localization methods under GPS-denied conditions**|Zihao Lu et.al.|[2211.11988](http://arxiv.org/abs/2211.11988)|null|
|**2022-11-01**|**Expansion of Visual Hints for Improved Generalization in Stereo Matching**|Andrea Pilzer et.al.|[2211.00392](http://arxiv.org/abs/2211.00392)|null|
|**2022-10-28**|**A geometry method for LED mapping**|Junlin Huang et.al.|[2210.13031](http://arxiv.org/abs/2210.13031)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## BEV

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-05-02**|**CoViS-Net: A Cooperative Visual Spatial Foundation Model for Multi-Robot Applications**|Jan Blumenkamp et.al.|[2405.01107](http://arxiv.org/abs/2405.01107)|null|
|**2024-05-02**|**Addressing Diverging Training Costs using Local Restoration for Precise Bird's Eye View Map Construction**|Minsu Kim et.al.|[2405.01016](http://arxiv.org/abs/2405.01016)|null|
|**2024-04-26**|**Scrutinizing Data from Sky: An Examination of Its Veracity in Area Based Traffic Contexts**|Yawar Ali et.al.|[2404.17212](http://arxiv.org/abs/2404.17212)|null|
|**2024-04-19**|**FipTR: A Simple yet Effective Transformer Framework for Future Instance Prediction in Autonomous Driving**|Xingtai Gui et.al.|[2404.12867](http://arxiv.org/abs/2404.12867)|null|
|**2024-04-18**|**6Img-to-3D: Few-Image Large-Scale Outdoor Driving Scene Reconstruction**|Théo Gieruc et.al.|[2404.12378](http://arxiv.org/abs/2404.12378)|**[link](https://github.com/continental/6img-to-3d)**|
|**2024-04-17**|**HybriMap: Hybrid Clues Utilization for Effective Vectorized HD Map Construction**|Chi Zhang et.al.|[2404.11155](http://arxiv.org/abs/2404.11155)|null|
|**2024-04-15**|**SparseOcc: Rethinking Sparse Latent Representation for Vision-Based Semantic Occupancy Prediction**|Pin Tang et.al.|[2404.09502](http://arxiv.org/abs/2404.09502)|null|
|**2024-04-10**|**PACP: Priority-Aware Collaborative Perception for Connected and Autonomous Vehicles**|Zhengru Fang et.al.|[2404.06891](http://arxiv.org/abs/2404.06891)|null|
|**2024-04-20**|**RoadBEV: Road Surface Reconstruction in Bird's Eye View**|Tong Zhao et.al.|[2404.06605](http://arxiv.org/abs/2404.06605)|**[link](https://github.com/ztsrxh/roadbev)**|
|**2024-04-09**|**DaF-BEVSeg: Distortion-aware Fisheye Camera based Bird's Eye View Segmentation with Occlusion Reasoning**|Senthil Yogamani et.al.|[2404.06352](http://arxiv.org/abs/2404.06352)|null|
|**2024-04-12**|**EasyTrack: Efficient and Compact One-stream 3D Point Clouds Tracker**|Baojie Fan et.al.|[2404.05960](http://arxiv.org/abs/2404.05960)|null|
|**2024-04-07**|**A Bird-Eye view on DNA Storage Simulators**|Sanket Doshi et.al.|[2404.04877](http://arxiv.org/abs/2404.04877)|null|
|**2024-04-03**|**SG-BEV: Satellite-Guided BEV Fusion for Cross-View Semantic Segmentation**|Junyan Ye et.al.|[2404.02638](http://arxiv.org/abs/2404.02638)|**[link](https://github.com/yejy53/sg-bev)**|
|**2024-04-01**|**Versatile Navigation under Partial Observability via Value-guided Diffusion Policy**|Gengyu Zhang et.al.|[2404.02176](http://arxiv.org/abs/2404.02176)|null|
|**2024-04-02**|**Improving Bird's Eye View Semantic Segmentation by Task Decomposition**|Tianhao Zhao et.al.|[2404.01925](http://arxiv.org/abs/2404.01925)|null|
|**2024-03-27**|**Imaging radar and LiDAR image translation for 3-DOF extrinsic calibration**|Sangwoo Jung et.al.|[2403.18358](http://arxiv.org/abs/2403.18358)|null|
|**2024-03-25**|**RCBEVDet: Radar-camera Fusion in Bird's Eye View for 3D Object Detection**|Zhiwei Lin et.al.|[2403.16440](http://arxiv.org/abs/2403.16440)|**[link](https://github.com/vdigpku/rcbevdet)**|
|**2024-03-22**|**IS-Fusion: Instance-Scene Collaborative Fusion for Multimodal 3D Object Detection**|Junbo Yin et.al.|[2403.15241](http://arxiv.org/abs/2403.15241)|**[link](https://github.com/yinjunbo/is-fusion)**|
|**2024-03-19**|**GerontoVis: Data Visualization at the Confluence of Aging**|Zack While et.al.|[2403.13173](http://arxiv.org/abs/2403.13173)|null|
|**2024-03-19**|**Lifting Multi-View Detection and Tracking to the Bird's Eye View**|Torben Teepe et.al.|[2403.12573](http://arxiv.org/abs/2403.12573)|**[link](https://github.com/tteepe/tracktacular)**|
|**2024-03-18**|**HVDistill: Transferring Knowledge from Images to Point Clouds via Unsupervised Hybrid-View Distillation**|Sha Zhang et.al.|[2403.11817](http://arxiv.org/abs/2403.11817)|**[link](https://github.com/zhangsha1024/HVDistill)**|
|**2024-03-20**|**GaussNav: Gaussian Splatting for Visual Navigation**|Xiaohan Lei et.al.|[2403.11625](http://arxiv.org/abs/2403.11625)|null|
|**2024-03-15**|**SimPB: A Single Model for 2D and 3D Object Detection from Multiple Cameras**|Yingqi Tang et.al.|[2403.10353](http://arxiv.org/abs/2403.10353)|null|
|**2024-03-13**|**CLIP-BEVFormer: Enhancing Multi-View Image-Based BEV Detector with Ground Truth Flow**|Chenbin Pan et.al.|[2403.08919](http://arxiv.org/abs/2403.08919)|null|
|**2024-03-12**|**Unleashing HyDRa: Hybrid Fusion, Depth Consistency and Radar for Unified 3D Perception**|Philipp Wolters et.al.|[2403.07746](http://arxiv.org/abs/2403.07746)|**[link](https://github.com/phi-wol/hydra)**|
|**2024-03-08**|**ActFormer: Scalable Collaborative Perception via Active Queries**|Suozhi Huang et.al.|[2403.04968](http://arxiv.org/abs/2403.04968)|null|
|**2024-03-06**|**Temporal Enhanced Floating Car Observers**|Jeremias Gerner et.al.|[2403.03825](http://arxiv.org/abs/2403.03825)|null|
|**2024-03-06**|**Popeye: A Unified Visual-Language Model for Multi-Source Ship Detection from Remote Sensing Imagery**|Wei Zhang et.al.|[2403.03790](http://arxiv.org/abs/2403.03790)|null|
|**2024-03-07**|**CMDA: Cross-Modal and Domain Adversarial Adaptation for LiDAR-Based 3D Object Detection**|Gyusam Chang et.al.|[2403.03721](http://arxiv.org/abs/2403.03721)|null|
|**2024-03-08**|**PillarGen: Enhancing Radar Point Cloud Density and Quality via Pillar-based Point Generation Network**|Jisong Kim et.al.|[2403.01663](http://arxiv.org/abs/2403.01663)|null|
|**2024-03-03**|**RoadRunner - Learning Traversability Estimation for Autonomous Off-road Driving**|Jonas Frey et.al.|[2402.19341](http://arxiv.org/abs/2402.19341)|null|
|**2024-02-23**|**Cohere3D: Exploiting Temporal Coherence for Unsupervised Representation Learning of Vision-based Autonomous Driving**|Yichen Xie et.al.|[2402.15583](http://arxiv.org/abs/2402.15583)|null|
|**2024-02-16**|**GIM: Learning Generalizable Image Matcher From Internet Videos**|Xuelun Shen et.al.|[2402.11095](http://arxiv.org/abs/2402.11095)|null|
|**2024-04-25**|**Collaborative Semantic Occupancy Prediction with Hybrid Feature Fusion in Connected Automated Vehicles**|Rui Song et.al.|[2402.07635](http://arxiv.org/abs/2402.07635)|null|
|**2024-02-11**|**Social Evolution of Published Text and The Emergence of Artificial Intelligence Through Large Language Models and The Problem of Toxicity and Bias**|Arifa Khan et.al.|[2402.07166](http://arxiv.org/abs/2402.07166)|null|
|**2024-02-08**|**uPLAM: Robust Panoptic Localization and Mapping Leveraging Perception Uncertainties**|Kshitij Sirohi et.al.|[2402.05840](http://arxiv.org/abs/2402.05840)|null|
|**2024-04-20**|**Pixel to Elevation: Learning to Predict Elevation Maps at Long Range using Images for Autonomous Offroad Navigation**|Chanyoung Chung et.al.|[2401.17484](http://arxiv.org/abs/2401.17484)|null|
|**2024-01-25**|**Unlocking Past Information: Temporal Embeddings in Cooperative Bird's Eye View Prediction**|Dominik Rößle et.al.|[2401.14325](http://arxiv.org/abs/2401.14325)|null|
|**2024-04-29**|**InverseMatrixVT3D: An Efficient Projection Matrix-Based Approach for 3D Occupancy Prediction**|Zhenxing Ming et.al.|[2401.12422](http://arxiv.org/abs/2401.12422)|**[link](https://github.com/danielming123/inversematrixvt3d)**|
|**2024-01-23**|**Icy Moon Surface Simulation and Stereo Depth Estimation for Sampling Autonomy**|Ramchander Bhaskara et.al.|[2401.12414](http://arxiv.org/abs/2401.12414)|**[link](https://github.com/nasa-jpl/guiss)**|
|**2024-01-21**|**Self-Supervised Bird's Eye View Motion Prediction with Cross-Modality Signals**|Shaoheng Fang et.al.|[2401.11499](http://arxiv.org/abs/2401.11499)|**[link](https://github.com/bshfang/self-supervised-motion)**|
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
|**2024-04-22**|**An Autonomous Driving Model Integrated with BEV-V2X Perception, Fusion Prediction of Motion and Occupancy, and Driving Planning, in Complex Traffic Intersections**|Fukang Li et.al.|[2312.05104](http://arxiv.org/abs/2312.05104)|null|
|**2024-04-11**|**COTR: Compact Occupancy TRansformer for Vision-based 3D Occupancy Prediction**|Qihang Ma et.al.|[2312.01919](http://arxiv.org/abs/2312.01919)|**[link](https://github.com/notacracker/cotr)**|
|**2024-03-24**|**BEVNeXt: Reviving Dense BEV Frameworks for 3D Object Detection**|Zhenxin Li et.al.|[2312.01696](http://arxiv.org/abs/2312.01696)|null|
|**2024-01-01**|**Towards Full-scene Domain Generalization in Multi-agent Collaborative Bird's Eye View Segmentation for Connected and Autonomous Driving**|Senkang Hu et.al.|[2311.16754](http://arxiv.org/abs/2311.16754)|**[link](https://github.com/dg-cavs/dg-coperception)**|
|**2023-11-27**|**Technical Report for Argoverse Challenges on 4D Occupancy Forecasting**|Pengfei Zheng et.al.|[2311.15660](http://arxiv.org/abs/2311.15660)|null|
|**2023-11-27**|**Technical Report for Argoverse Challenges on Unified Sensor-based Detection, Tracking, and Forecasting**|Zhepeng Wang et.al.|[2311.15615](http://arxiv.org/abs/2311.15615)|null|
|**2023-11-29**|**SelfOcc: Self-Supervised Vision-Based 3D Occupancy Prediction**|Yuanhui Huang et.al.|[2311.12754](http://arxiv.org/abs/2311.12754)|**[link](https://github.com/huang-yh/selfocc)**|
|**2023-11-13**|**The Last Decade in Review: Tracing the Evolution of Safety Assurance Cases through a Comprehensive Bibliometric Analysis**|Mithila Sivakumar et.al.|[2311.07495](http://arxiv.org/abs/2311.07495)|null|
|**2023-11-12**|**Deep Perspective Transformation Based Vehicle Localization on Bird's Eye View**|Abtin Mahyar et.al.|[2311.06796](http://arxiv.org/abs/2311.06796)|**[link](https://github.com/ipm-hpc/perspective-bev-transformer)**|
|**2023-11-09**|**TLCFuse: Temporal Multi-Modality Fusion Towards Occlusion-Aware Semantic Segmentation-Aided Motion Planning**|Gustavo Salazar-Gomez et.al.|[2311.05319](http://arxiv.org/abs/2311.05319)|null|
|**2023-11-08**|**PRED: Pre-training via Semantic Rendering on LiDAR Point Clouds**|Hao Yang et.al.|[2311.04501](http://arxiv.org/abs/2311.04501)|null|
|**2024-03-23**|**Bird's Eye View Based Pretrained World model for Visual Navigation**|Kiran Lekkala et.al.|[2310.18847](http://arxiv.org/abs/2310.18847)|null|
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
|**2024-04-02**|**UniBEV: Multi-modal 3D Object Detection with Uniform BEV Encoders for Robustness against Missing Sensor Modalities**|Shiming Wang et.al.|[2309.14516](http://arxiv.org/abs/2309.14516)|null|
|**2024-03-15**|**Advancements in 3D Lane Detection Using LiDAR Point Clouds: From Data Collection to Model Development**|Runkai Zhao et.al.|[2309.13596](http://arxiv.org/abs/2309.13596)|**[link](https://github.com/runkaizhao/liladet)**|
|**2023-11-08**|**BroadBEV: Collaborative LiDAR-camera Fusion for Broad-sighted Bird's Eye View Map Construction**|Minsu Kim et.al.|[2309.11119](http://arxiv.org/abs/2309.11119)|null|
|**2023-09-19**|**A Novel Deep Neural Network for Trajectory Prediction in Automated Vehicles Using Velocity Vector Field**|MReza Alipour Sormoli et.al.|[2309.10948](http://arxiv.org/abs/2309.10948)|**[link](https://github.com/Amir-Samadi/VVF-TP)**|
|**2023-09-25**|**LineMarkNet: Line Landmark Detection for Valet Parking**|Zizhang Wu et.al.|[2309.10475](http://arxiv.org/abs/2309.10475)|null|
|**2023-09-19**|**Multi-camera Bird's Eye View Perception for Autonomous Driving**|David Unger et.al.|[2309.09080](http://arxiv.org/abs/2309.09080)|null|
|**2023-09-22**|**OccupancyDETR: Making Semantic Scene Completion as Straightforward as Object Detection**|Yupeng Jia et.al.|[2309.08504](http://arxiv.org/abs/2309.08504)|**[link](https://github.com/jypjypjypjyp/occupancydetr)**|
|**2023-09-15**|**AVM-SLAM: Semantic Visual SLAM with Multi-Sensor Fusion in a Bird's Eye View for Automated Valet Parking**|Ye Li et.al.|[2309.08180](http://arxiv.org/abs/2309.08180)|**[link](https://github.com/yale-cv/avm-slam)**|
|**2023-10-09**|**FusionFormer: A Multi-sensory Fusion in Bird's-Eye-View and Temporal Consistent Transformer for 3D Object Detection**|Chunyong Hu et.al.|[2309.05257](http://arxiv.org/abs/2309.05257)|null|
|**2023-09-11**|**Towards Viewpoint Robustness in Bird's Eye View Segmentation**|Tzofi Klinghoffer et.al.|[2309.05192](http://arxiv.org/abs/2309.05192)|null|
|**2023-08-31**|**PointOcc: Cylindrical Tri-Perspective View for Point-based 3D Semantic Occupancy Prediction**|Sicheng Zuo et.al.|[2308.16896](http://arxiv.org/abs/2308.16896)|**[link](https://github.com/wzzheng/pointocc)**|
|**2023-08-28**|**Semi-Supervised Learning for Visual Bird's Eye View Semantic Segmentation**|Junyu Zhu et.al.|[2308.14525](http://arxiv.org/abs/2308.14525)|null|
|**2023-08-27**|**Automatic coarse co-registration of point clouds from diverse scan geometries: a test of detectors and descriptors**|Francesco Pirotti et.al.|[2308.14047](http://arxiv.org/abs/2308.14047)|null|
|**2024-01-06**|**SOGDet: Semantic-Occupancy Guided Multi-view 3D Object Detection**|Qiu Zhou et.al.|[2308.13794](http://arxiv.org/abs/2308.13794)|**[link](https://github.com/zhouqiu/sogdet)**|
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
|**2023-10-30**|**ScenarioNet: Open-Source Platform for Large-Scale Traffic Scenario Simulation and Modeling**|Quanyi Li et.al.|[2306.12241](http://arxiv.org/abs/2306.12241)|**[link](https://github.com/metadriverse/scenarionet)**|
|**2023-06-17**|**MachMap: End-to-End Vectorized Solution for Compact HD-Map Construction**|Limeng Qiao et.al.|[2306.10301](http://arxiv.org/abs/2306.10301)|null|
|**2023-06-16**|**Coaching a Teachable Student**|Jimuyang Zhang et.al.|[2306.10014](http://arxiv.org/abs/2306.10014)|**[link](https://github.com/h2xlab/CaT)**|
|**2023-06-12**|**MaskedFusion360: Reconstruct LiDAR Data by Querying Camera Features**|Royden Wagner et.al.|[2306.07087](http://arxiv.org/abs/2306.07087)|**[link](https://github.com/kit-mrt/masked-fusion-360)**|
|**2023-06-08**|**UAP-BEV: Uncertainty Aware Planning using Bird's Eye View generated from Surround Monocular Images**|Vikrant Dewangan et.al.|[2306.04939](http://arxiv.org/abs/2306.04939)|**[link](https://github.com/Vikr-182/UAP-BEV)**|
|**2023-06-08**|**An Efficient Transformer for Simultaneous Learning of BEV and Lane Representations in 3D Lane Detection**|Ziye Chen et.al.|[2306.04927](http://arxiv.org/abs/2306.04927)|null|
|**2023-06-07**|**NeMO: Neural Map Growing System for Spatiotemporal Fusion in Bird's-Eye-View and BDD-Map Benchmark**|Xi Zhu et.al.|[2306.04540](http://arxiv.org/abs/2306.04540)|null|
|**2023-11-27**|**CALICO: Self-Supervised Camera-LiDAR Contrastive Pre-training for BEV Perception**|Jiachen Sun et.al.|[2306.00349](http://arxiv.org/abs/2306.00349)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## Gaussian Splatting

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-05-07**|**$\textbf{Splat-MOVER}$ : Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**|Ola Shorinwa et.al.|[2405.04378](http://arxiv.org/abs/2405.04378)|null|
|**2024-05-06**|**A Construct-Optimize Approach to Sparse View Synthesis without Camera Pose**|Kaiwen Jiang et.al.|[2405.03659](http://arxiv.org/abs/2405.03659)|null|
|**2024-05-06**|**Gaussian Splatting: 3D Reconstruction and Novel View Synthesis, a Review**|Anurag Dalal et.al.|[2405.03417](http://arxiv.org/abs/2405.03417)|null|
|**2024-05-03**|**HoloGS: Instant Depth-based 3D Gaussian Splatting with Microsoft HoloLens 2**|Miriam Jäger et.al.|[2405.02005](http://arxiv.org/abs/2405.02005)|null|
|**2024-05-01**|**Spectrally Pruned Gaussian Fields with Neural Compensation**|Runyi Yang et.al.|[2405.00676](http://arxiv.org/abs/2405.00676)|**[link](https://github.com/runyiyang/sundae)**|
|**2024-05-01**|**RTG-SLAM: Real-time 3D Reconstruction at Scale using Gaussian Splatting**|Zhexi Peng et.al.|[2404.19706](http://arxiv.org/abs/2404.19706)|null|
|**2024-04-30**|**GS-LRM: Large Reconstruction Model for 3D Gaussian Splatting**|Kai Zhang et.al.|[2404.19702](http://arxiv.org/abs/2404.19702)|null|
|**2024-05-02**|**3D Gaussian Blendshapes for Head Avatar Animation**|Shengjie Ma et.al.|[2404.19398](http://arxiv.org/abs/2404.19398)|null|
|**2024-04-29**|**SAGS: Structure-Aware 3D Gaussian Splatting**|Evangelos Ververas et.al.|[2404.19149](http://arxiv.org/abs/2404.19149)|null|
|**2024-04-29**|**GSTalker: Real-time Audio-Driven Talking Face Generation via Deformable Gaussian Splatting**|Bo Chen et.al.|[2404.19040](http://arxiv.org/abs/2404.19040)|null|
|**2024-04-29**|**MeGA: Hybrid Mesh-Gaussian Head Avatar for High-Fidelity Rendering and Head Editing**|Cong Wang et.al.|[2404.19026](http://arxiv.org/abs/2404.19026)|null|
|**2024-04-29**|**DGE: Direct Gaussian 3D Editing by Consistent Multi-view Editing**|Minghao Chen et.al.|[2404.18929](http://arxiv.org/abs/2404.18929)|null|
|**2024-04-29**|**Bootstrap 3D Reconstructed Scenes from 3D Gaussian Splatting**|Yifei Gao et.al.|[2404.18669](http://arxiv.org/abs/2404.18669)|null|
|**2024-04-29**|**3D Gaussian Splatting with Deferred Reflection**|Keyang Ye et.al.|[2404.18454](http://arxiv.org/abs/2404.18454)|null|
|**2024-04-29**|**Reconstructing Satellites in 3D from Amateur Telescope Images**|Zhiming Chang et.al.|[2404.18394](http://arxiv.org/abs/2404.18394)|null|
|**2024-04-26**|**SLAM for Indoor Mapping of Wide Area Construction Environments**|Vincent Ress et.al.|[2404.17215](http://arxiv.org/abs/2404.17215)|null|
|**2024-04-25**|**Interactive3D: Create What You Want by Interactive 3D Generation**|Shaocong Dong et.al.|[2404.16510](http://arxiv.org/abs/2404.16510)|null|
|**2024-04-25**|**DIG3D: Marrying Gaussian Splatting with Deformable Transformer for Single Image 3D Reconstruction**|Jiamin Wu et.al.|[2404.16323](http://arxiv.org/abs/2404.16323)|null|
|**2024-04-25**|**GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting**|Kyusun Cho et.al.|[2404.16012](http://arxiv.org/abs/2404.16012)|**[link](https://github.com/ku-cvlab/gaussiantalker)**|
|**2024-04-25**|**OMEGAS: Object Mesh Extraction from Large Scenes Guided by Gaussian Segmentation**|Lizhi Wang et.al.|[2404.15891](http://arxiv.org/abs/2404.15891)|**[link](https://github.com/crystalwlz/omegas)**|
|**2024-04-23**|**TalkingGaussian: Structure-Persistent 3D Talking Head Synthesis via Gaussian Splatting**|Jiahe Li et.al.|[2404.15264](http://arxiv.org/abs/2404.15264)|null|
|**2024-04-23**|**FlowMap: High-Quality Camera Poses, Intrinsics, and Depth via Gradient Descent**|Cameron Smith et.al.|[2404.15259](http://arxiv.org/abs/2404.15259)|**[link](https://github.com/dcharatan/flowmap)**|
|**2024-04-22**|**Guess The Unseen: Dynamic 3D Scene Reconstruction from Partial 2D Glimpses**|Inhee Lee et.al.|[2404.14410](http://arxiv.org/abs/2404.14410)|null|
|**2024-04-22**|**CLIP-GS: CLIP-Informed Gaussian Splatting for Real-time and View-consistent 3D Semantic Understanding**|Guibiao Liao et.al.|[2404.14249](http://arxiv.org/abs/2404.14249)|**[link](https://github.com/gbliao/clip-gs)**|
|**2024-04-28**|**GaussianTalker: Speaker-specific Talking Head Synthesis via 3D Gaussian Splatting**|Hongyun Yu et.al.|[2404.14037](http://arxiv.org/abs/2404.14037)|null|
|**2024-04-21**|**GScream: Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal**|Yuxin Wang et.al.|[2404.13679](http://arxiv.org/abs/2404.13679)|null|
|**2024-04-19**|**Learn2Talk: 3D Talking Face Learns from 2D Talking Face**|Yixiang Zhuang et.al.|[2404.12888](http://arxiv.org/abs/2404.12888)|null|
|**2024-04-19**|**EfficientGS: Streamlining Gaussian Splatting for Large-Scale High-Resolution Scene Representation**|Wenkai Liu et.al.|[2404.12777](http://arxiv.org/abs/2404.12777)|null|
|**2024-04-22**|**Does Gaussian Splatting need SFM Initialization?**|Yalda Foroutan et.al.|[2404.12547](http://arxiv.org/abs/2404.12547)|null|
|**2024-04-22**|**Dynamic Gaussians Mesh: Consistent Mesh Reconstruction from Monocular Videos**|Isabella Liu et.al.|[2404.12379](http://arxiv.org/abs/2404.12379)|null|
|**2024-04-17**|**RainyScape: Unsupervised Rainy Scene Reconstruction using Decoupled Neural Rendering**|Xianqiang Lyu et.al.|[2404.11401](http://arxiv.org/abs/2404.11401)|null|
|**2024-04-18**|**DeblurGS: Gaussian Splatting for Camera Motion Blur**|Jeongtaek Oh et.al.|[2404.11358](http://arxiv.org/abs/2404.11358)|null|
|**2024-04-17**|**Novel View Synthesis for Cinematic Anatomy on Mobile and Immersive Displays**|Simon Niedermayr et.al.|[2404.11285](http://arxiv.org/abs/2404.11285)|null|
|**2024-04-16**|**Gaussian Opacity Fields: Efficient and Compact Surface Reconstruction in Unbounded Scenes**|Zehao Yu et.al.|[2404.10772](http://arxiv.org/abs/2404.10772)|null|
|**2024-04-16**|**Gaussian Splatting Decoder for 3D-aware Generative Adversarial Networks**|Florian Barthel et.al.|[2404.10625](http://arxiv.org/abs/2404.10625)|null|
|**2024-04-16**|**AbsGS: Recovering Fine Details for 3D Gaussian Splatting**|Zongxin Ye et.al.|[2404.10484](http://arxiv.org/abs/2404.10484)|null|
|**2024-04-16**|**SRGS: Super-Resolution 3D Gaussian Splatting**|Xiang Feng et.al.|[2404.10318](http://arxiv.org/abs/2404.10318)|null|
|**2024-04-15**|**LetsGo: Large-Scale Garage Modeling and Rendering via LiDAR-Assisted Gaussian Primitives**|Jiadi Cui et.al.|[2404.09748](http://arxiv.org/abs/2404.09748)|null|
|**2024-04-15**|**3D Gaussian Splatting as Markov Chain Monte Carlo**|Shakiba Kheradmand et.al.|[2404.09591](http://arxiv.org/abs/2404.09591)|null|
|**2024-04-15**|**CompGS: Efficient 3D Scene Representation via Compressed Gaussian Splatting**|Xiangrui Liu et.al.|[2404.09458](http://arxiv.org/abs/2404.09458)|null|
|**2024-04-15**|**DeferredGS: Decoupled and Editable Gaussian Splatting with Deferred Shading**|Tong Wu et.al.|[2404.09412](http://arxiv.org/abs/2404.09412)|null|
|**2024-04-14**|**DreamScape: 3D Scene Creation via Gaussian Splatting joint Correlation Modeling**|Xuening Yuan et.al.|[2404.09227](http://arxiv.org/abs/2404.09227)|null|
|**2024-04-22**|**EGGS: Edge Guided Gaussian Splatting for Radiance Fields**|Yuanhao Gong et.al.|[2404.09105](http://arxiv.org/abs/2404.09105)|null|
|**2024-04-16**|**LoopGaussian: Creating 3D Cinemagraph with Multi-view Images via Eulerian Motion Field**|Jiyang Li et.al.|[2404.08966](http://arxiv.org/abs/2404.08966)|null|
|**2024-04-15**|**OccGaussian: 3D Gaussian Splatting for Occluded Human Rendering**|Jingrui Ye et.al.|[2404.08449](http://arxiv.org/abs/2404.08449)|null|
|**2024-04-11**|**GoMAvatar: Efficient Animatable Human Modeling from Monocular Video Using Gaussians-on-Mesh**|Jing Wen et.al.|[2404.07991](http://arxiv.org/abs/2404.07991)|null|
|**2024-04-10**|**RealmDreamer: Text-Driven 3D Scene Generation with Inpainting and Depth Diffusion**|Jaidev Shriram et.al.|[2404.07199](http://arxiv.org/abs/2404.07199)|null|
|**2024-04-10**|**Gaussian-LIC: Photo-realistic LiDAR-Inertial-Camera SLAM with 3D Gaussian Splatting**|Xiaolei Lang et.al.|[2404.06926](http://arxiv.org/abs/2404.06926)|null|
|**2024-04-10**|**DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting**|Shijie Zhou et.al.|[2404.06903](http://arxiv.org/abs/2404.06903)|null|
|**2024-04-10**|**SplatPose & Detect: Pose-Agnostic 3D Anomaly Detection**|Mathis Kruse et.al.|[2404.06832](http://arxiv.org/abs/2404.06832)|**[link](https://github.com/m-kruse98/splatpose)**|
|**2024-04-10**|**Zero-shot Point Cloud Completion Via 2D Priors**|Tianxin Huang et.al.|[2404.06814](http://arxiv.org/abs/2404.06814)|null|
|**2024-04-12**|**SpikeNVS: Enhancing Novel View Synthesis from Blurry Images via Spike Camera**|Gaole Dai et.al.|[2404.06710](http://arxiv.org/abs/2404.06710)|null|
|**2024-04-14**|**3D Geometry-aware Deformable Gaussian Splatting for Dynamic View Synthesis**|Zhicheng Lu et.al.|[2404.06270](http://arxiv.org/abs/2404.06270)|null|
|**2024-04-09**|**Gaussian Pancakes: Geometrically-Regularized 3D Gaussian Splatting for Realistic Endoscopic Reconstruction**|Sierra Bonilla et.al.|[2404.06128](http://arxiv.org/abs/2404.06128)|**[link](https://github.com/smbonilla/gaussianpancakes)**|
|**2024-04-09**|**Revising Densification in Gaussian Splatting**|Samuel Rota Bulò et.al.|[2404.06109](http://arxiv.org/abs/2404.06109)|null|
|**2024-04-09**|**Hash3D: Training-free Acceleration for 3D Generation**|Xingyi Yang et.al.|[2404.06091](http://arxiv.org/abs/2404.06091)|**[link](https://github.com/Adamdad/hash3D)**|
|**2024-04-08**|**StylizedGS: Controllable Stylization for 3D Gaussian Splatting**|Dingxi Zhang et.al.|[2404.05220](http://arxiv.org/abs/2404.05220)|null|
|**2024-04-07**|**Dual-Camera Smooth Zoom on Mobile Phones**|Renlong Wu et.al.|[2404.04908](http://arxiv.org/abs/2404.04908)|null|
|**2024-04-13**|**GauU-Scene V2: Assessing the Reliability of Image-Based Metrics with Expansive Lidar Image Dataset Using 3DGS and NeRF**|Butian Xiong et.al.|[2404.04880](http://arxiv.org/abs/2404.04880)|null|
|**2024-04-06**|**Z-Splat: Z-Axis Gaussian Splatting for Camera-Sonar Fusion**|Ziyuan Qu et.al.|[2404.04687](http://arxiv.org/abs/2404.04687)|null|
|**2024-04-05**|**Robust Gaussian Splatting**|François Darmon et.al.|[2404.04211](http://arxiv.org/abs/2404.04211)|null|
|**2024-04-04**|**Per-Gaussian Embedding-Based Deformation for Deformable 3D Gaussian Splatting**|Jeongmin Bae et.al.|[2404.03613](http://arxiv.org/abs/2404.03613)|null|
|**2024-04-08**|**OmniGS: Omnidirectional Gaussian Splatting for Fast Radiance Field Reconstruction using Omnidirectional Images**|Longwei Li et.al.|[2404.03202](http://arxiv.org/abs/2404.03202)|null|
|**2024-04-04**|**GaSpCT: Gaussian Splatting for Novel CT Projection View Synthesis**|Emmanouil Nikolakakis et.al.|[2404.03126](http://arxiv.org/abs/2404.03126)|null|
|**2024-04-03**|**TCLC-GS: Tightly Coupled LiDAR-Camera Gaussian Splatting for Surrounding Autonomous Driving Scenes**|Cheng Zhao et.al.|[2404.02410](http://arxiv.org/abs/2404.02410)|null|
|**2024-04-02**|**Surface Reconstruction from Gaussian Splatting via Novel Stereo Views**|Yaniv Wolf et.al.|[2404.01810](http://arxiv.org/abs/2404.01810)|null|
|**2024-04-01**|**Mirror-3DGS: Incorporating Mirror Reflections into 3D Gaussian Splatting**|Jiarui Meng et.al.|[2404.01168](http://arxiv.org/abs/2404.01168)|null|
|**2024-04-07**|**CityGaussian: Real-time High-quality Large-Scale Scene Rendering with Gaussians**|Yang Liu et.al.|[2404.01133](http://arxiv.org/abs/2404.01133)|null|
|**2024-04-01**|**HAHA: Highly Articulated Gaussian Human Avatars with Textured Mesh Prior**|David Svitov et.al.|[2404.01053](http://arxiv.org/abs/2404.01053)|**[link](https://github.com/david-svitov/haha)**|
|**2024-04-01**|**MM3DGS SLAM: Multi-modal 3D Gaussian Splatting for SLAM Using Vision, Depth, and Inertial Measurements**|Lisong C. Sun et.al.|[2404.00923](http://arxiv.org/abs/2404.00923)|null|
|**2024-03-30**|**3DGSR: Implicit Surface Reconstruction with 3D Gaussian Splatting**|Xiaoyang Lyu et.al.|[2404.00409](http://arxiv.org/abs/2404.00409)|null|
|**2024-03-29**|**InstantSplat: Unbounded Sparse-view Pose-free Gaussian Splatting in 40 Seconds**|Zhiwen Fan et.al.|[2403.20309](http://arxiv.org/abs/2403.20309)|null|
|**2024-03-29**|**Snap-it, Tap-it, Splat-it: Tactile-Informed 3D Gaussian Splatting for Reconstructing Challenging Surfaces**|Mauro Comi et.al.|[2403.20275](http://arxiv.org/abs/2403.20275)|null|
|**2024-03-29**|**HGS-Mapping: Online Dense Mapping Using Hybrid Gaussian Representation in Urban Scenes**|Ke Wu et.al.|[2403.20159](http://arxiv.org/abs/2403.20159)|null|
|**2024-03-29**|**SGD: Street View Synthesis with Gaussian Splatting and Diffusion Prior**|Zhongrui Yu et.al.|[2403.20079](http://arxiv.org/abs/2403.20079)|null|
|**2024-03-29**|**HO-Gaussian: Hybrid Optimization of 3D Gaussian Splatting for Urban Scenes**|Zhuopeng Li et.al.|[2403.20032](http://arxiv.org/abs/2403.20032)|null|
|**2024-04-05**|**GaussianCube: Structuring Gaussian Splatting using Optimal Transport for 3D Generative Modeling**|Bowen Zhang et.al.|[2403.19655](http://arxiv.org/abs/2403.19655)|null|
|**2024-03-28**|**GauStudio: A Modular Framework for 3D Gaussian Splatting and Beyond**|Chongjie Ye et.al.|[2403.19632](http://arxiv.org/abs/2403.19632)|**[link](https://github.com/gap-lab-cuhk-sz/gaustudio)**|
|**2024-03-28**|**SA-GS: Scale-Adaptive Gaussian Splatting for Training-Free Anti-Aliasing**|Xiaowei Song et.al.|[2403.19615](http://arxiv.org/abs/2403.19615)|**[link](https://github.com/zsy1987/sa-gs)**|
|**2024-03-28**|**TOGS: Gaussian Splatting with Temporal Opacity Offset for Real-Time 4D DSA Rendering**|Shuai Zhang et.al.|[2403.19586](http://arxiv.org/abs/2403.19586)|null|
|**2024-02-20**|**GaussianObject: Just Taking Four Images to Get A High-Quality 3D Object with Gaussian Splatting**|Chen Yang et.al.|[2402.10259](http://arxiv.org/abs/2402.10259)|**[link](https://github.com/GaussianObject/GaussianObject)**|
|**2024-02-15**|**GES: Generalized Exponential Splatting for Efficient Radiance Field Rendering**|Abdullah Hamdi et.al.|[2402.10128](http://arxiv.org/abs/2402.10128)|null|
|**2024-02-13**|**IM-3D: Iterative Multiview Diffusion and Reconstruction for High-Quality 3D Generation**|Luke Melas-Kyriazi et.al.|[2402.08682](http://arxiv.org/abs/2402.08682)|null|
|**2024-02-11**|**GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting**|Xiaoyu Zhou et.al.|[2402.07207](http://arxiv.org/abs/2402.07207)|null|
|**2024-02-11**|**3D Gaussian as a New Vision Era: A Survey**|Ben Fei et.al.|[2402.07181](http://arxiv.org/abs/2402.07181)|null|
|**2024-02-09**|**ImplicitDeepfake: Plausible Face-Swapping through Implicit Deepfake Generation using NeRF and Gaussian Splatting**|Georgii Stanishevskii et.al.|[2402.06390](http://arxiv.org/abs/2402.06390)|**[link](https://github.com/quereste/implicit-deepfake)**|
|**2024-02-13**|**GS-CLIP: Gaussian Splatting for Contrastive Language-Image-3D Pretraining from Real-World Data**|Haoyuan Li et.al.|[2402.06198](http://arxiv.org/abs/2402.06198)|null|
|**2024-02-09**|**HeadStudio: Text to Animatable Head Avatars with 3D Gaussian Splatting**|Zhenglin Zhou et.al.|[2402.06149](http://arxiv.org/abs/2402.06149)|null|
|**2024-02-07**|**Mesh-based Gaussian Splatting for Real-time Large-scale Deformation**|Lin Gao et.al.|[2402.04796](http://arxiv.org/abs/2402.04796)|null|
|**2024-02-06**|**Rig3DGS: Creating Controllable Portraits from Casual Monocular Videos**|Alfredo Rivero et.al.|[2402.03723](http://arxiv.org/abs/2402.03723)|null|
|**2024-02-07**|**4D Gaussian Splatting: Towards Efficient Novel View Synthesis for Dynamic Scenes**|Yuanxing Duan et.al.|[2402.03307](http://arxiv.org/abs/2402.03307)|null|
|**2024-02-05**|**SGS-SLAM: Semantic Gaussian Splatting For Neural Dense SLAM**|Mingrui Li et.al.|[2402.03246](http://arxiv.org/abs/2402.03246)|null|
|**2024-02-15**|**GaMeS: Mesh-Based Adapting and Modification of Gaussian Splatting**|Joanna Waczyńska et.al.|[2402.01459](http://arxiv.org/abs/2402.01459)|**[link](https://github.com/waczjoan/gaussian-mesh-splatting)**|
|**2024-02-01**|**360-GS: Layout-guided Panoramic Gaussian Splatting For Indoor Roaming**|Jiayang Bai et.al.|[2402.00763](http://arxiv.org/abs/2402.00763)|null|
|**2024-02-02**|**Optimal Projection for 3D Gaussian Splatting**|Letian Huang et.al.|[2402.00752](http://arxiv.org/abs/2402.00752)|null|
|**2024-02-01**|**StopThePop: Sorted Gaussian Splatting for View-Consistent Real-time Rendering**|Lukas Radl et.al.|[2402.00525](http://arxiv.org/abs/2402.00525)|null|
|**2024-02-01**|**Segment Anything in 3D Gaussians**|Xu Hu et.al.|[2401.17857](http://arxiv.org/abs/2401.17857)|null|
|**2024-01-30**|**VR-GS: A Physical Dynamics-Aware Interactive Gaussian Splatting System in Virtual Reality**|Ying Jiang et.al.|[2401.16663](http://arxiv.org/abs/2401.16663)|null|
|**2024-01-31**|**Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting**|Yiming Huang et.al.|[2401.16416](http://arxiv.org/abs/2401.16416)|null|
|**2024-01-27**|**Gaussian Splashing: Dynamic Fluid Synthesis with Gaussian Splatting**|Yutao Feng et.al.|[2401.15318](http://arxiv.org/abs/2401.15318)|null|
|**2024-01-26**|**TIP-Editor: An Accurate 3D Editor Following Both Text-Prompts And Image-Prompts**|Jingyu Zhuang et.al.|[2401.14828](http://arxiv.org/abs/2401.14828)|null|
|**2024-01-25**|**GauU-Scene: A Scene Reconstruction Benchmark on Large Scale 3D Reconstruction Dataset Using Gaussian Splatting**|Butian Xiong et.al.|[2401.14032](http://arxiv.org/abs/2401.14032)|null|
|**2024-01-24**|**EndoGaussians: Single View Dynamic Gaussian Splatting for Deformable Endoscopic Tissues Reconstruction**|Yangsen Chen et.al.|[2401.13352](http://arxiv.org/abs/2401.13352)|null|
|**2024-01-30**|**PSAvatar: A Point-based Morphable Shape Model for Real-Time Head Avatar Animation with 3D Gaussian Splatting**|Zhongyuan Zhao et.al.|[2401.12900](http://arxiv.org/abs/2401.12900)|**[link](https://github.com/pcl3dv/PSAvatar)**|
|**2024-02-13**|**EndoGaussian: Real-time Gaussian Splatting for Dynamic Endoscopic Scene Reconstruction**|Yifan Liu et.al.|[2401.12561](http://arxiv.org/abs/2401.12561)|null|
|**2024-02-12**|**EndoGS: Deformable Endoscopic Tissues Reconstruction with Gaussian Splatting**|Lingting Zhu et.al.|[2401.11535](http://arxiv.org/abs/2401.11535)|**[link](https://github.com/hku-medai/endogs)**|
|**2024-01-27**|**GaussianBody: Clothed Human Reconstruction via 3d Gaussian Splatting**|Mengtian Li et.al.|[2401.09720](http://arxiv.org/abs/2401.09720)|null|
|**2024-01-16**|**Fast Dynamic 3D Object Generation from a Single-view Video**|Zijie Pan et.al.|[2401.08742](http://arxiv.org/abs/2401.08742)|null|
|**2024-01-16**|**Forging Vision Foundation Models for Autonomous Driving: Challenges, Methodologies, and Opportunities**|Xu Yan et.al.|[2401.08045](http://arxiv.org/abs/2401.08045)|**[link](https://github.com/zhanghm1995/forge_vfm4ad)**|
|**2024-01-11**|**Gaussian Shadow Casting for Neural Characters**|Luis Bolanos et.al.|[2401.06116](http://arxiv.org/abs/2401.06116)|null|
|**2024-01-11**|**TRIPS: Trilinear Point Splatting for Real-Time Radiance Field Rendering**|Linus Franke et.al.|[2401.06003](http://arxiv.org/abs/2401.06003)|**[link](https://github.com/lfranke/trips)**|
|**2024-01-30**|**CoSSegGaussians: Compact and Swift Scene Segmenting 3D Gaussians with Dual Feature Fusion**|Bin Dou et.al.|[2401.05925](http://arxiv.org/abs/2401.05925)|null|
|**2023-12-01**|**DISTWAR: Fast Differentiable Rendering on Raster-based Rendering Pipelines**|Sankeerth Durvasula et.al.|[2401.05345](http://arxiv.org/abs/2401.05345)|null|
|**2024-01-08**|**AGG: Amortized Generative 3D Gaussians for Single Image to 3D**|Dejia Xu et.al.|[2401.04099](http://arxiv.org/abs/2401.04099)|null|
|**2024-01-08**|**A Survey on 3D Gaussian Splatting**|Guikun Chen et.al.|[2401.03890](http://arxiv.org/abs/2401.03890)|null|
|**2024-01-05**|**Progress and Prospects in 3D Generative AI: A Technical Overview including 3D human**|Song Bai et.al.|[2401.02620](http://arxiv.org/abs/2401.02620)|null|
|**2024-01-05**|**Characterizing Satellite Geometry via Accelerated 3D Gaussian Splatting**|Van Minh Nguyen et.al.|[2401.02588](http://arxiv.org/abs/2401.02588)|null|
|**2024-01-04**|**PEGASUS: Physically Enhanced Gaussian Splatting Simulation System for 6DOF Object Pose Dataset Generation**|Lukas Meyer et.al.|[2401.02281](http://arxiv.org/abs/2401.02281)|null|
|**2024-01-03**|**FMGS: Foundation Model Embedded 3D Gaussian Splatting for Holistic 3D Scene Understanding**|Xingxing Zuo et.al.|[2401.01970](http://arxiv.org/abs/2401.01970)|null|
|**2024-01-01**|**Deblurring 3D Gaussian Splatting**|Byeonghyeon Lee et.al.|[2401.00834](http://arxiv.org/abs/2401.00834)|null|
|**2023-12-29**|**DreamGaussian4D: Generative 4D Gaussian Splatting**|Jiawei Ren et.al.|[2312.17142](http://arxiv.org/abs/2312.17142)|**[link](https://github.com/jiawei-ren/dreamgaussian4d)**|
|**2023-12-26**|**LangSplat: 3D Language Gaussian Splatting**|Minghan Qin et.al.|[2312.16084](http://arxiv.org/abs/2312.16084)|**[link](https://github.com/minghanqin/LangSplat)**|
|**2023-12-23**|**Human101: Training 100+FPS Human Gaussians in 100s from 1 View**|Mingwei Li et.al.|[2312.15258](http://arxiv.org/abs/2312.15258)|**[link](https://github.com/longxiang-ai/human101)**|
|**2023-12-22**|**Deformable 3D Gaussian Splatting for Animatable Human Avatars**|HyunJun Jung et.al.|[2312.15059](http://arxiv.org/abs/2312.15059)|null|
|**2023-12-29**|**SC-GS: Sparse-Controlled Gaussian Splatting for Editable Dynamic Scenes**|Yi-Hua Huang et.al.|[2312.14937](http://arxiv.org/abs/2312.14937)|**[link](https://github.com/yihua7/SC-GS)**|
|**2024-01-03**|**Align Your Gaussians: Text-to-4D with Dynamic 3D Gaussians and Composed Diffusion Models**|Huan Ling et.al.|[2312.13763](http://arxiv.org/abs/2312.13763)|null|
|**2024-02-18**|**Gaussian Splatting with NeRF-based Color and Opacity**|Dawid Malarz et.al.|[2312.13729](http://arxiv.org/abs/2312.13729)|**[link](https://github.com/gmum/ViewingDirectionGaussianSplatting)**|
|**2023-12-20**|**SWAGS: Sampling Windows Adaptively for Dynamic 3D Gaussian Splatting**|Richard Shaw et.al.|[2312.13308](http://arxiv.org/abs/2312.13308)|null|
|**2023-12-19**|**Compact 3D Scene Representation via Self-Organizing Gaussian Grids**|Wieland Morgenstern et.al.|[2312.13299](http://arxiv.org/abs/2312.13299)|null|
|**2023-12-20**|**Splatter Image: Ultra-Fast Single-View 3D Reconstruction**|Stanislaw Szymanowicz et.al.|[2312.13150](http://arxiv.org/abs/2312.13150)|**[link](https://github.com/szymanowiczs/splatter-image)**|
|**2023-12-21**|**pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction**|David Charatan et.al.|[2312.12337](http://arxiv.org/abs/2312.12337)|null|
|**2023-12-18**|**GAvatar: Animatable 3D Gaussian Avatars with Implicit Mesh Learning**|Ye Yuan et.al.|[2312.11461](http://arxiv.org/abs/2312.11461)|null|
|**2023-12-18**|**GauFRe: Gaussian Deformation Fields for Real-time Dynamic Novel View Synthesis**|Yiqing Liang et.al.|[2312.11458](http://arxiv.org/abs/2312.11458)|null|
|**2023-12-06**|**Gaussian-SLAM: Photo-realistic Dense SLAM with Gaussian Splatting**|Vladimir Yugay et.al.|[2312.10070](http://arxiv.org/abs/2312.10070)|null|
|**2023-12-15**|**Exploring the Feasibility of Generating Realistic 3D Models of Endangered Species Using DreamGaussian: An Analysis of Elevation Angle's Impact on Model Generation**|Selcuk Anil Karatopak et.al.|[2312.09682](http://arxiv.org/abs/2312.09682)|null|
|**2023-12-15**|**3DGS-Avatar: Animatable Avatars via Deformable 3D Gaussian Splatting**|Zhiyin Qian et.al.|[2312.09228](http://arxiv.org/abs/2312.09228)|null|
|**2023-12-16**|**Triplane Meets Gaussian Splatting: Fast and Generalizable Single-View 3D Reconstruction with Transformers**|Zi-Xin Zou et.al.|[2312.09147](http://arxiv.org/abs/2312.09147)|null|
|**2023-12-14**|**iComMa: Inverting 3D Gaussians Splatting for Camera Pose Estimation via Comparing and Matching**|Yuan Sun et.al.|[2312.09031](http://arxiv.org/abs/2312.09031)|null|
|**2023-12-13**|**DrivingGaussian: Composite Gaussian Splatting for Surrounding Dynamic Autonomous Driving Scenes**|Xiaoyu Zhou et.al.|[2312.07920](http://arxiv.org/abs/2312.07920)|null|
|**2023-12-12**|**COLMAP-Free 3D Gaussian Splatting**|Yang Fu et.al.|[2312.07504](http://arxiv.org/abs/2312.07504)|null|
|**2023-12-11**|**Gaussian Splatting SLAM**|Hidenobu Matsuki et.al.|[2312.06741](http://arxiv.org/abs/2312.06741)|null|
|**2023-12-10**|**ASH: Animatable Gaussian Splats for Efficient and Photoreal Human Rendering**|Haokai Pang et.al.|[2312.05941](http://arxiv.org/abs/2312.05941)|null|
|**2023-12-09**|**CoGS: Controllable Gaussian Splatting**|Heng Yu et.al.|[2312.05664](http://arxiv.org/abs/2312.05664)|null|
|**2023-12-08**|**Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting**|Xiaofeng Yang et.al.|[2312.04820](http://arxiv.org/abs/2312.04820)|null|
|**2023-12-07**|**EAGLES: Efficient Accelerated 3D Gaussians with Lightweight EncodingS**|Sharath Girish et.al.|[2312.04564](http://arxiv.org/abs/2312.04564)|null|
|**2023-12-07**|**MonoGaussianAvatar: Monocular Gaussian Point-based Head Avatar**|Yufan Chen et.al.|[2312.04558](http://arxiv.org/abs/2312.04558)|null|
|**2023-12-07**|**HiFi4G: High-Fidelity Human Performance Rendering via Compact Gaussian Splatting**|Yuheng Jiang et.al.|[2312.03461](http://arxiv.org/abs/2312.03461)|null|
|**2023-12-06**|**Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle**|Youtian Lin et.al.|[2312.03431](http://arxiv.org/abs/2312.03431)|null|
|**2023-12-06**|**Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields**|Shijie Zhou et.al.|[2312.03203](http://arxiv.org/abs/2312.03203)|null|
|**2023-12-05**|**GauHuman: Articulated Gaussian Splatting from Monocular Human Videos**|Shoukang Hu et.al.|[2312.02973](http://arxiv.org/abs/2312.02973)|**[link](https://github.com/skhu101/gauhuman)**|
|**2023-12-05**|**HeadGaS: Real-Time Animatable Head Avatars via 3D Gaussian Splatting**|Helisa Dhamo et.al.|[2312.02902](http://arxiv.org/abs/2312.02902)|null|
|**2023-12-04**|**GPS-Gaussian: Generalizable Pixel-wise 3D Gaussian Splatting for Real-time Human Novel View Synthesis**|Shunyuan Zheng et.al.|[2312.02155](http://arxiv.org/abs/2312.02155)|null|
|**2023-12-04**|**MANUS: Markerless Hand-Object Grasp Capture using Articulated 3D Gaussians**|Chandradeep Pokhariya et.al.|[2312.02137](http://arxiv.org/abs/2312.02137)|null|
|**2023-12-04**|**Mathematical Supplement for the $\texttt{gsplat}$ Library**|Vickie Ye et.al.|[2312.02121](http://arxiv.org/abs/2312.02121)|**[link](https://github.com/nerfstudio-project/gsplat)**|
|**2023-12-04**|**GaussianAvatars: Photorealistic Head Avatars with Rigged 3D Gaussians**|Shenhan Qian et.al.|[2312.02069](http://arxiv.org/abs/2312.02069)|**[link](https://github.com/ShenhanQian/GaussianAvatars)**|
|**2023-12-01**|**Segment Any 3D Gaussians**|Jiazhong Cen et.al.|[2312.00860](http://arxiv.org/abs/2312.00860)|null|
|**2023-12-01**|**NeuSG: Neural Implicit Surface Reconstruction with 3D Gaussian Splatting Guidance**|Hanlin Chen et.al.|[2312.00846](http://arxiv.org/abs/2312.00846)|null|
|**2023-12-01**|**Gaussian Grouping: Segment and Edit Anything in 3D Scenes**|Mingqiao Ye et.al.|[2312.00732](http://arxiv.org/abs/2312.00732)|**[link](https://github.com/lkeab/gaussian-grouping)**|
|**2023-12-01**|**FSGS: Real-Time Few-shot View Synthesis using Gaussian Splatting**|Zehao Zhu et.al.|[2312.00451](http://arxiv.org/abs/2312.00451)|null|
|**2023-11-30**|**SparseGS: Real-Time 360° Sparse View Synthesis using Gaussian Splatting**|Haolin Xiong et.al.|[2312.00206](http://arxiv.org/abs/2312.00206)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

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

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## Localization

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-03-08**|**Employing Universal Voting Schemes for Improved Visual Place Recognition Performance**|Maria Waheed et.al.|[2405.02297](http://arxiv.org/abs/2405.02297)|null|
|**2024-05-01**|**Radar-Based Localization For Autonomous Ground Vehicles In Suburban Neighborhoods**|Andrew J. Kramer et.al.|[2405.00600](http://arxiv.org/abs/2405.00600)|null|
|**2024-04-30**|**XFeat: Accelerated Features for Lightweight Image Matching**|Guilherme Potje et.al.|[2404.19174](http://arxiv.org/abs/2404.19174)|null|
|**2024-04-29**|**Towards Long-term Robotics in the Wild**|Stephen Hausler et.al.|[2404.18477](http://arxiv.org/abs/2404.18477)|null|
|**2024-04-27**|**FRAME: A Modular Framework for Autonomous Map-merging: Advancements in the Field**|Nikolaos Stathoulopoulos et.al.|[2404.18006](http://arxiv.org/abs/2404.18006)|null|
|**2024-04-20**|**High-fidelity Endoscopic Image Synthesis by Utilizing Depth-guided Neural Surfaces**|Baoru Huang et.al.|[2404.13437](http://arxiv.org/abs/2404.13437)|null|
|**2024-04-20**|**Collaborative Visual Place Recognition through Federated Learning**|Mattia Dutto et.al.|[2404.13324](http://arxiv.org/abs/2404.13324)|null|
|**2024-04-18**|**SPOT: Point Cloud Based Stereo Visual Place Recognition for Similar and Opposing Viewpoints**|Spencer Carmichael et.al.|[2404.12339](http://arxiv.org/abs/2404.12339)|null|
|**2024-04-16**|**SPVLoc: Semantic Panoramic Viewport Matching for 6D Camera Localization in Unseen Environments**|Niklas Gard et.al.|[2404.10527](http://arxiv.org/abs/2404.10527)|**[link](https://github.com/fraunhoferhhi/spvloc)**|
|**2024-04-20**|**CREST: Cross-modal Resonance through Evidential Deep Learning for Enhanced Zero-Shot Learning**|Haojian Huang et.al.|[2404.09640](http://arxiv.org/abs/2404.09640)|**[link](https://github.com/JethroJames/CREST)**|
|**2024-04-11**|**PRAM: Place Recognition Anywhere Model for Efficient Visual Localization**|Fei Xue et.al.|[2404.07785](http://arxiv.org/abs/2404.07785)|null|
|**2024-04-23**|**2DLIW-SLAM:2D LiDAR-Inertial-Wheel Odometry with Real-Time Loop Closure**|Bin Zhang et.al.|[2404.07644](http://arxiv.org/abs/2404.07644)|**[link](https://github.com/littledang/2dliw-slam)**|
|**2024-04-09**|**Training-Free Open-Vocabulary Segmentation with Offline Diffusion-Augmented Prototype Generation**|Luca Barsellotti et.al.|[2404.06542](http://arxiv.org/abs/2404.06542)|null|
|**2024-04-07**|**Scalable and Efficient Hierarchical Visual Topological Mapping**|Saravanabalagi Ramachandran et.al.|[2404.05023](http://arxiv.org/abs/2404.05023)|**[link](https://github.com/saravanabalagi/htmap_gt_loops)**|
|**2024-04-05**|**Towards introspective loop closure in 4D radar SLAM**|Maximilian Hilger et.al.|[2404.03940](http://arxiv.org/abs/2404.03940)|null|
|**2024-04-03**|**PoCo: Point Context Cluster for RGBD Indoor Place Recognition**|Jing Liang et.al.|[2404.02885](http://arxiv.org/abs/2404.02885)|null|
|**2024-04-02**|**PRISM-TopoMap: Online Topological Mapping with Place Recognition and Scan Matching**|Kirill Muravyev et.al.|[2404.01674](http://arxiv.org/abs/2404.01674)|**[link](https://github.com/kirillmouraviev/prism-topomap)**|
|**2024-04-02**|**TSCM: A Teacher-Student Model for Vision Place Recognition Using Cross-Metric Knowledge Distillation**|Yehui Shen et.al.|[2404.01587](http://arxiv.org/abs/2404.01587)|**[link](https://github.com/nubot-nudt/tscm)**|
|**2024-04-01**|**NVINS: Robust Visual Inertial Navigation Fused with NeRF-augmented Camera Pose Regressor and Uncertainty Quantification**|Juyeop Han et.al.|[2404.01400](http://arxiv.org/abs/2404.01400)|null|
|**2024-03-31**|**On the Estimation of Image-matching Uncertainty in Visual Place Recognition**|Mubariz Zaffar et.al.|[2404.00546](http://arxiv.org/abs/2404.00546)|null|
|**2024-03-31**|**NYC-Indoor-VPR: A Long-Term Indoor Visual Place Recognition Dataset with Semi-Automatic Annotation**|Diwei Sheng et.al.|[2404.00504](http://arxiv.org/abs/2404.00504)|null|
|**2024-03-30**|**SceneGraphLoc: Cross-Modal Coarse Visual Localization on 3D Scene Graphs**|Yang Miao et.al.|[2404.00469](http://arxiv.org/abs/2404.00469)|null|
|**2024-03-28**|**Towards Long Term SLAM on Thermal Imagery**|Colin Keil et.al.|[2403.19885](http://arxiv.org/abs/2403.19885)|**[link](https://github.com/neufieldrobotics/irslam_baseline)**|
|**2024-03-28**|**JIST: Joint Image and Sequence Training for Sequential Visual Place Recognition**|Gabriele Berton et.al.|[2403.19787](http://arxiv.org/abs/2403.19787)|**[link](https://github.com/ga1i13o/jist)**|
|**2024-03-27**|**ModaLink: Unifying Modalities for Efficient Image-to-PointCloud Place Recognition**|Weidong Xie et.al.|[2403.18762](http://arxiv.org/abs/2403.18762)|**[link](https://github.com/haomo-ai/modalink)**|
|**2024-03-26**|**Learning to Visually Localize Sound Sources from Mixtures without Prior Source Knowledge**|Dongjin Kim et.al.|[2403.17420](http://arxiv.org/abs/2403.17420)|**[link](https://github.com/visualaikhu/noprior_multissl)**|
|**2024-03-25**|**Enhancing Visual Place Recognition via Fast and Slow Adaptive Biasing in Event Cameras**|Gokul B. Nair et.al.|[2403.16425](http://arxiv.org/abs/2403.16425)|null|
|**2024-03-22**|**CRPlace: Camera-Radar Fusion with BEV Representation for Place Recognition**|Shaowei Fu et.al.|[2403.15183](http://arxiv.org/abs/2403.15183)|null|
|**2024-03-21**|**VXP: Voxel-Cross-Pixel Large-scale Image-LiDAR Place Recognition**|Yun-Jin Li et.al.|[2403.14594](http://arxiv.org/abs/2403.14594)|null|
|**2024-03-21**|**Evaluation and Deployment of LiDAR-based Place Recognition in Dense Forests**|Haedam Oh et.al.|[2403.14326](http://arxiv.org/abs/2403.14326)|null|
|**2024-05-06**|**ReFeree: Radar-based efficient global descriptor using a Feature and Free space for Place Recognition**|Byunghee Choi et.al.|[2403.14176](http://arxiv.org/abs/2403.14176)|null|
|**2024-03-20**|**Unifying Local and Global Multimodal Features for Place Recognition in Aliased and Low-Texture Environments**|Alberto García-Hernández et.al.|[2403.13395](http://arxiv.org/abs/2403.13395)|**[link](https://github.com/dlr-rm/umf)**|
|**2024-03-19**|**Learning Neural Volumetric Pose Features for Camera Localization**|Jingyu Lin et.al.|[2403.12800](http://arxiv.org/abs/2403.12800)|null|
|**2024-03-17**|**3DGS-ReLoc: 3D Gaussian Splatting for Map Representation and Visual ReLocalization**|Peng Jiang et.al.|[2403.11367](http://arxiv.org/abs/2403.11367)|null|
|**2024-03-20**|**Leveraging Neural Radiance Field in Descriptor Synthesis for Keypoints Scene Coordinate Regression**|Huy-Hoang Bui et.al.|[2403.10297](http://arxiv.org/abs/2403.10297)|**[link](https://github.com/ais-lab/descriptorsynthesis4feat2map)**|
|**2024-03-15**|**Local positional graphs and attentive local features for a data and runtime-efficient hierarchical place recognition pipeline**|Fangming Yuan et.al.|[2403.10283](http://arxiv.org/abs/2403.10283)|null|
|**2024-03-15**|**FBPT: A Fully Binary Point Transformer**|Zhixing Hou et.al.|[2403.09998](http://arxiv.org/abs/2403.09998)|null|
|**2024-03-14**|**The NeRFect Match: Exploring NeRF Features for Visual Localization**|Qunjie Zhou et.al.|[2403.09577](http://arxiv.org/abs/2403.09577)|null|
|**2024-03-14**|**VDNA-PR: Using General Dataset Representations for Robust Sequential Visual Place Recognition**|Benjamin Ramtoula et.al.|[2403.09025](http://arxiv.org/abs/2403.09025)|null|
|**2024-03-13**|**NeRF-Supervised Feature Point Detection and Description**|Ali Youssef et.al.|[2403.08156](http://arxiv.org/abs/2403.08156)|null|
|**2024-03-13**|**MinkUNeXt: Point Cloud-based Large-scale Place Recognition using 3D Sparse Convolutions**|J. J. Cabrera et.al.|[2403.07593](http://arxiv.org/abs/2403.07593)|**[link](https://github.com/juanjo-cabrera/minkunext)**|
|**2024-03-11**|**BEV2PR: BEV-Enhanced Visual Place Recognition with Structural Cues**|Fudong Ge et.al.|[2403.06600](http://arxiv.org/abs/2403.06600)|null|
|**2024-03-10**|**RTAB-Map as an Open-Source Lidar and Visual SLAM Library for Large-Scale and Long-Term Online Operation**|Mathieu Labbé et.al.|[2403.06341](http://arxiv.org/abs/2403.06341)|null|
|**2024-03-11**|**LHMap-loc: Cross-Modal Monocular Localization Using LiDAR Point Cloud Heat Map**|Xinrui Wu et.al.|[2403.05002](http://arxiv.org/abs/2403.05002)|**[link](https://github.com/irmvlab/lhmap-loc)**|
|**2024-03-07**|**mmPlace: Robust Place Recognition with Intermediate Frequency Signal of Low-cost Single-chip Millimeter Wave Radar**|Chengzhen Meng et.al.|[2403.04703](http://arxiv.org/abs/2403.04703)|null|
|**2024-03-05**|**OORD: The Oxford Offroad Radar Dataset**|Matthew Gadd et.al.|[2403.02845](http://arxiv.org/abs/2403.02845)|**[link](https://github.com/mttgdd/oord-dataset)**|
|**2024-04-01**|**CricaVPR: Cross-image Correlation-aware Representation Learning for Visual Place Recognition**|Feng Lu et.al.|[2402.19231](http://arxiv.org/abs/2402.19231)|**[link](https://github.com/lu-feng/cricavpr)**|
|**2024-03-05**|**VEnvision3D: A Synthetic Perception Dataset for 3D Multi-Task Model Research**|Jiahao Zhou et.al.|[2402.19059](http://arxiv.org/abs/2402.19059)|null|
|**2024-02-28**|**Representing 3D sparse map points and lines for camera relocalization**|Bach-Thuan Bui et.al.|[2402.18011](http://arxiv.org/abs/2402.18011)|**[link](https://github.com/ais-lab/pl2map)**|
|**2024-02-29**|**Active propulsion noise shaping for multi-rotor aircraft localization**|Gabriele Serussi et.al.|[2402.17289](http://arxiv.org/abs/2402.17289)|**[link](https://github.com/tamirshor7/ears_code)**|
|**2024-02-27**|**Explicit Interaction for Fusion-Based Place Recognition**|Jingyi Xu et.al.|[2402.17264](http://arxiv.org/abs/2402.17264)|**[link](https://github.com/bit-xjy/einet)**|
|**2024-03-21**|**NocPlace: Nocturnal Visual Place Recognition via Generative and Inherited Knowledge Transfer**|Bingxi Liu et.al.|[2402.17159](http://arxiv.org/abs/2402.17159)|**[link](https://github.com/binuxliu/nocplace)**|
|**2024-03-18**|**Deep Homography Estimation for Visual Place Recognition**|Feng Lu et.al.|[2402.16086](http://arxiv.org/abs/2402.16086)|**[link](https://github.com/lu-feng/dhe-vpr)**|
|**2024-02-25**|**VOLoc: Visual Place Recognition by Querying Compressed Lidar Map**|Xudong Cai et.al.|[2402.15961](http://arxiv.org/abs/2402.15961)|**[link](https://github.com/master-cai/voloc)**|
|**2024-04-03**|**Towards Seamless Adaptation of Pre-trained Models for Visual Place Recognition**|Feng Lu et.al.|[2402.14505](http://arxiv.org/abs/2402.14505)|**[link](https://github.com/Lu-Feng/SelaVPR)**|
|**2024-02-23**|**CoLRIO: LiDAR-Ranging-Inertial Centralized State Estimation for Robotic Swarms**|Shipeng Zhong et.al.|[2402.11790](http://arxiv.org/abs/2402.11790)|**[link](https://github.com/pengyu-team/co-lrio)**|
|**2024-02-16**|**Spike-EVPR: Deep Spiking Residual Network with Cross-Representation Aggregation for Event-Based Visual Place Recognition**|Chenming Hu et.al.|[2402.10476](http://arxiv.org/abs/2402.10476)|null|
|**2024-02-14**|**Loopy-SLAM: Dense Neural SLAM with Loop Closures**|Lorenzo Liso et.al.|[2402.09944](http://arxiv.org/abs/2402.09944)|null|
|**2024-02-15**|**Self-Supervised Learning of Visual Robot Localization Using LED State Prediction as a Pretext Task**|Mirko Nava et.al.|[2402.09886](http://arxiv.org/abs/2402.09886)|**[link](https://github.com/idsia-robotics/leds-as-pretext)**|
|**2024-02-14**|**Weatherproofing Retrieval for Localization with Generative AI and Geometric Consistency**|Yannis Kalantidis et.al.|[2402.09237](http://arxiv.org/abs/2402.09237)|null|
|**2024-03-20**|**Learning to Produce Semi-dense Correspondences for Visual Localization**|Khang Truong Giang et.al.|[2402.08359](http://arxiv.org/abs/2402.08359)|**[link](https://github.com/truongkhang/deviloc)**|
|**2024-02-10**|**Semantic Object-level Modeling for Robust Visual Camera Relocalization**|Yifan Zhu et.al.|[2402.06951](http://arxiv.org/abs/2402.06951)|null|
|**2024-02-09**|**PAS-SLAM: A Visual SLAM System for Planar Ambiguous Scenes**|Xinggang Hu et.al.|[2402.06131](http://arxiv.org/abs/2402.06131)|null|
|**2024-02-09**|**MoD-SLAM: Monocular Dense Mapping for Unbounded 3D Scene Reconstruction**|Heng Zhou et.al.|[2402.03762](http://arxiv.org/abs/2402.03762)|null|
|**2024-03-04**|**RecNet: An Invertible Point Cloud Encoding through Range Image Embeddings for Multi-Robot Map Sharing and Reconstruction**|Nikolaos Stathoulopoulos et.al.|[2402.02192](http://arxiv.org/abs/2402.02192)|null|
|**2024-02-01**|**BrainSLAM: SLAM on Neural Population Activity Data**|Kipp Freud et.al.|[2402.00588](http://arxiv.org/abs/2402.00588)|null|
|**2024-03-03**|**Night-Rider: Nocturnal Vision-aided Localization in Streetlight Maps Using Invariant Extended Kalman Filtering**|Tianxiao Gao et.al.|[2402.00330](http://arxiv.org/abs/2402.00330)|**[link](https://github.com/imrl/night-rider)**|
|**2024-01-31**|**Improved Scene Landmark Detection for Camera Localization**|Tien Do et.al.|[2401.18083](http://arxiv.org/abs/2401.18083)|**[link](https://github.com/microsoft/scenelandmarklocalization)**|
|**2024-01-29**|**Regressing Transformers for Data-efficient Visual Place Recognition**|María Leyva-Vallina et.al.|[2401.16304](http://arxiv.org/abs/2401.16304)|null|
|**2024-03-02**|**Open-RadVLAD: Fast and Robust Radar Place Recognition**|Matthew Gadd et.al.|[2401.15380](http://arxiv.org/abs/2401.15380)|**[link](https://github.com/mttgdd/open-radvlad)**|
|**2024-01-24**|**Dataset and Benchmark: Novel Sensors for Autonomous Vehicle Perception**|Spencer Carmichael et.al.|[2401.13853](http://arxiv.org/abs/2401.13853)|**[link](https://github.com/umautobots/nsavp_tools)**|
|**2024-01-23**|**PlaceFormer: Transformer-based Visual Place Recognition using Multi-Scale Patch Selection and Fusion**|Shyam Sundar Kannan et.al.|[2401.13082](http://arxiv.org/abs/2401.13082)|null|
|**2024-01-23**|**SemanticSLAM: Learning based Semantic Map Construction and Robust Camera Localization**|Mingyang Li et.al.|[2401.13076](http://arxiv.org/abs/2401.13076)|**[link](https://github.com/leomingyangli/semanticslam)**|
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
|**2023-12-27**|**Learning Dense Flow Field for Highly-accurate Cross-view Camera Localization**|Zhenbo Song et.al.|[2309.15556](http://arxiv.org/abs/2309.15556)|null|
|**2023-09-29**|**Multimodal Dataset for Localization, Mapping and Crop Monitoring in Citrus Tree Farms**|Hanzhe Teng et.al.|[2309.15332](http://arxiv.org/abs/2309.15332)|**[link](https://github.com/ucr-robotics/citrus-farm-dataset)**|
|**2023-09-26**|**Language-EXtended Indoor SLAM (LEXIS): A Versatile System for Real-time Visual Scene Understanding**|Christina Kassab et.al.|[2309.15065](http://arxiv.org/abs/2309.15065)|null|
|**2024-01-22**|**HeLiPR: Heterogeneous LiDAR Dataset for inter-LiDAR Place Recognition under Spatiotemporal Variations**|Minwoo Jung et.al.|[2309.14590](http://arxiv.org/abs/2309.14590)|null|
|**2023-09-20**|**2D-3D Pose Tracking with Multi-View Constraints**|Huai Yu et.al.|[2309.11335](http://arxiv.org/abs/2309.11335)|null|
|**2023-09-19**|**VPRTempo: A Fast Temporally Encoded Spiking Neural Network for Visual Place Recognition**|Adam D. Hines et.al.|[2309.10225](http://arxiv.org/abs/2309.10225)|**[link](https://github.com/QVPR/VPRTempo)**|
|**2023-09-18**|**DynaPix SLAM: A Pixel-Based Dynamic SLAM Approach**|Chenghao Xu et.al.|[2309.09879](http://arxiv.org/abs/2309.09879)|null|
|**2023-09-18**|**RaLF: Flow-based Global and Metric Radar Localization in LiDAR Maps**|Abhijeet Nayak et.al.|[2309.09875](http://arxiv.org/abs/2309.09875)|null|
|**2023-09-16**|**Efficient Object Rearrangement via Multi-view Fusion**|Dehao Huang et.al.|[2309.08994](http://arxiv.org/abs/2309.08994)|null|
|**2023-09-16**|**DynaMoN: Motion-Aware Fast And Robust Camera Localization for Dynamic NeRF**|Mert Asim Karaoglu et.al.|[2309.08927](http://arxiv.org/abs/2309.08927)|null|
|**2023-09-16**|**Outram: One-shot Global Localization via Triangulated Scene Graph and Global Outlier Pruning**|Pengyu Yin et.al.|[2309.08914](http://arxiv.org/abs/2309.08914)|**[link](https://github.com/pamphlett/outram)**|
|**2023-09-14**|**EP2P-Loc: End-to-End 3D Point to 2D Pixel Localization for Large-Scale Visual Localization**|Minjung Kim et.al.|[2309.07471](http://arxiv.org/abs/2309.07471)|**[link](https://github.com/minnjung/ep2p-loc)**|
|**2023-09-13**|**RadarLCD: Learnable Radar-based Loop Closure Detection Pipeline**|Mirko Usuelli et.al.|[2309.07094](http://arxiv.org/abs/2309.07094)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## Feature

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-04-30**|**A Light-weight Transformer-based Self-supervised Matching Network for Heterogeneous Images**|Wang Zhang et.al.|[2404.19311](http://arxiv.org/abs/2404.19311)|null|
|**2024-04-25**|**Adaptive Local Binary Pattern: A Novel Feature Descriptor for Enhanced Analysis of Kidney Abnormalities in CT Scan Images using ensemble based Machine Learning Approach**|Tahmim Hossain et.al.|[2404.14560](http://arxiv.org/abs/2404.14560)|null|
|**2024-04-19**|**SkelFormer: Markerless 3D Pose and Shape Estimation using Skeletal Transformers**|Vandad Davoodnia et.al.|[2404.12625](http://arxiv.org/abs/2404.12625)|null|
|**2024-04-17**|**Pixel-Wise Symbol Spotting via Progressive Points Location for Parsing CAD Images**|Junbiao Pang et.al.|[2404.10985](http://arxiv.org/abs/2404.10985)|null|
|**2024-03-28**|**Towards Long Term SLAM on Thermal Imagery**|Colin Keil et.al.|[2403.19885](http://arxiv.org/abs/2403.19885)|**[link](https://github.com/neufieldrobotics/irslam_baseline)**|
|**2024-03-28**|**Instance-Adaptive and Geometric-Aware Keypoint Learning for Category-Level 6D Object Pose Estimation**|Xiao Lin et.al.|[2403.19527](http://arxiv.org/abs/2403.19527)|**[link](https://github.com/leeiieeo/ag-pose)**|
|**2024-03-27**|**RoboKeyGen: Robot Pose and Joint Angles Estimation via Diffusion-based 3D Keypoint Generation**|Yang Tian et.al.|[2403.18259](http://arxiv.org/abs/2403.18259)|null|
|**2024-03-18**|**FE-DeTr: Keypoint Detection and Tracking in Low-quality Image Frames with Events**|Xiangyuan Wang et.al.|[2403.11662](http://arxiv.org/abs/2403.11662)|**[link](https://github.com/yuyangpoi/fe-detr)**|
|**2024-03-05**|**Self-supervised 3D Patient Modeling with Multi-modal Attentive Fusion**|Meng Zheng et.al.|[2403.03217](http://arxiv.org/abs/2403.03217)|null|
|**2024-02-22**|**A Self-supervised Pressure Map human keypoint Detection Approch: Optimizing Generalization and Computational Efficiency Across Datasets**|Chengzhang Yu et.al.|[2402.14241](http://arxiv.org/abs/2402.14241)|null|
|**2024-02-25**|**A Feature Matching Method Based on Multi-Level Refinement Strategy**|Shaojie Zhang et.al.|[2402.13488](http://arxiv.org/abs/2402.13488)|null|
|**2024-03-05**|**3D Kinematics Estimation from Video with a Biomechanical Model and Synthetic Training Data**|Zhi-Yi Lin et.al.|[2402.13172](http://arxiv.org/abs/2402.13172)|null|
|**2024-02-25**|**Region Feature Descriptor Adapted to High Affine Transformations**|Shaojie Zhang et.al.|[2402.09724](http://arxiv.org/abs/2402.09724)|null|
|**2024-01-29**|**Reconstructing Close Human Interactions from Multiple Views**|Qing Shuai et.al.|[2401.16173](http://arxiv.org/abs/2401.16173)|**[link](https://github.com/zju3dv/closemocap)**|
|**2024-01-17**|**To deform or not: treatment-aware longitudinal registration for breast DCE-MRI during neoadjuvant chemotherapy via unsupervised keypoints detection**|Luyi Han et.al.|[2401.09336](http://arxiv.org/abs/2401.09336)|**[link](https://github.com/fiy2w/treatment-aware-longitudinal-registration)**|
|**2024-01-08**|**Flowmind2Digital: The First Comprehensive Flowmind Recognition and Conversion Approach**|Huanyu Liu et.al.|[2401.03742](http://arxiv.org/abs/2401.03742)|**[link](https://github.com/cai-jianfeng/flowmind2digital)**|
|**2024-03-22**|**6D-Diff: A Keypoint Diffusion Framework for 6D Object Pose Estimation**|Li Xu et.al.|[2401.00029](http://arxiv.org/abs/2401.00029)|null|
|**2023-12-27**|**Bezier-based Regression Feature Descriptor for Deformable Linear Objects**|Fangqing Chen et.al.|[2312.16502](http://arxiv.org/abs/2312.16502)|null|
|**2023-12-24**|**Residual Learning for Image Point Descriptors**|Rashik Shrestha et.al.|[2312.15471](http://arxiv.org/abs/2312.15471)|null|
|**2023-12-22**|**BonnBeetClouds3D: A Dataset Towards Point Cloud-based Organ-level Phenotyping of Sugar Beet Plants under Field Conditions**|Elias Marks et.al.|[2312.14706](http://arxiv.org/abs/2312.14706)|null|
|**2024-03-27**|**Continual-MAE: Adaptive Distribution Masked Autoencoders for Continual Test-Time Adaptation**|Jiaming Liu et.al.|[2312.12480](http://arxiv.org/abs/2312.12480)|null|
|**2024-04-30**|**An Effective Image Copy-Move Forgery Detection Using Entropy Information**|Li Jiang et.al.|[2312.11793](http://arxiv.org/abs/2312.11793)|**[link](https://github.com/LUZW1998/CMFDUEI)**|
|**2023-12-11**|**VoxelKP: A Voxel-based Network Architecture for Human Keypoint Estimation in LiDAR Data**|Jian Shi et.al.|[2312.08871](http://arxiv.org/abs/2312.08871)|**[link](https://github.com/shijianjian/voxelkp)**|
|**2023-12-11**|**Keypoint-based Stereophotoclinometry for Characterizing and Navigating Small Bodies: A Factor Graph Approach**|Travis Driver et.al.|[2312.06865](http://arxiv.org/abs/2312.06865)|**[link](https://github.com/travisdriver/spc-factor-results)**|
|**2023-12-01**|**Tracking Object Positions in Reinforcement Learning: A Metric for Keypoint Detection (extended version)**|Emma Cramer et.al.|[2312.00592](http://arxiv.org/abs/2312.00592)|null|
|**2023-11-30**|**Utilizing Radiomic Feature Analysis For Automated MRI Keypoint Detection: Enhancing Graph Applications**|Sahar Almahfouz Nasser et.al.|[2311.18281](http://arxiv.org/abs/2311.18281)|null|
|**2024-03-27**|**Back to 3D: Few-Shot 3D Keypoint Detection with Back-Projected 2D Features**|Thomas Wimmer et.al.|[2311.18113](http://arxiv.org/abs/2311.18113)|**[link](https://github.com/wimmerth/back-to-3d-few-shot-keypoints)**|
|**2024-04-02**|**Diffusion 3D Features (Diff3F): Decorating Untextured Shapes with Distilled Semantic Features**|Niladri Shekhar Dutt et.al.|[2311.17024](http://arxiv.org/abs/2311.17024)|**[link](https://github.com/niladridutt/Diffusion-3D-Features)**|
|**2023-11-28**|**Riemannian Self-Attention Mechanism for SPD Networks**|Rui Wang et.al.|[2311.16738](http://arxiv.org/abs/2311.16738)|null|
|**2023-11-27**|**A manometric feature descriptor with linear-SVM to distinguish esophageal contraction vigor**|Jialin Liu et.al.|[2311.15609](http://arxiv.org/abs/2311.15609)|null|
|**2024-04-26**|**Enhancing Visual Grounding and Generalization: A Multi-Task Cycle Training Approach for Vision-Language Models**|Xiaoyu Yang et.al.|[2311.12327](http://arxiv.org/abs/2311.12327)|**[link](https://github.com/anonymgiant/vilam)**|
|**2023-11-21**|**Instance-aware 3D Semantic Segmentation powered by Shape Generators and Classifiers**|Bo Sun et.al.|[2311.12291](http://arxiv.org/abs/2311.12291)|null|
|**2023-11-20**|**CurriculumLoc: Enhancing Cross-Domain Geolocalization through Multi-Stage Refinement**|Boni Hu et.al.|[2311.11604](http://arxiv.org/abs/2311.11604)|**[link](https://github.com/npupilab/curriculumloc)**|
|**2024-05-04**|**Video-based Sequential Bayesian Homography Estimation for Soccer Field Registration**|Paul J. Claasen et.al.|[2311.10361](http://arxiv.org/abs/2311.10361)|null|
|**2024-02-26**|**Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning**|Tomáš Kunzo et.al.|[2311.07398](http://arxiv.org/abs/2311.07398)|null|
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
|**2024-03-13**|**SKoPe3D: A Synthetic Dataset for Vehicle Keypoint Perception in 3D from Traffic Monitoring Cameras**|Himanshu Pahadia et.al.|[2309.01324](http://arxiv.org/abs/2309.01324)|null|
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
|**2023-07-28**|**PanoVPR: Towards Unified Perspective-to-Equirectangular Visual Place Recognition via Sliding Windows across the Panoramic View**|Ze Shi et.al.|[2303.14095](http://arxiv.org/abs/2303.14095)|**[link](https://github.com/zafirshi/panovpr)**|
|**2023-03-23**|**Semantic Image Attack for Visual Model Diagnosis**|Jinqi Luo et.al.|[2303.13010](http://arxiv.org/abs/2303.13010)|null|
|**2023-03-22**|**Object Pose Estimation with Statistical Guarantees: Conformal Keypoint Detection and Geometric Uncertainty Propagation**|Heng Yang et.al.|[2303.12246](http://arxiv.org/abs/2303.12246)|**[link](https://github.com/nvlabs/conformalkeypoint)**|
|**2023-05-29**|**RN-Net: Reservoir Nodes-Enabled Neuromorphic Vision Sensing Network**|Sangmin Yoo et.al.|[2303.10770](http://arxiv.org/abs/2303.10770)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## Matching

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-04-30**|**A Light-weight Transformer-based Self-supervised Matching Network for Heterogeneous Images**|Wang Zhang et.al.|[2404.19311](http://arxiv.org/abs/2404.19311)|null|
|**2024-04-30**|**XFeat: Accelerated Features for Lightweight Image Matching**|Guilherme Potje et.al.|[2404.19174](http://arxiv.org/abs/2404.19174)|null|
|**2024-04-27**|**MinBackProp -- Backpropagating through Minimal Solvers**|Diana Sungatullina et.al.|[2404.17993](http://arxiv.org/abs/2404.17993)|**[link](https://github.com/disungatullina/minbackprop)**|
|**2024-04-25**|**Transformer-Based Local Feature Matching for Multimodal Image Registration**|Remi Delaunay et.al.|[2404.16802](http://arxiv.org/abs/2404.16802)|null|
|**2024-04-23**|**FINEMATCH: Aspect-based Fine-grained Image and Text Mismatch Detection and Correction**|Hang Hua et.al.|[2404.14715](http://arxiv.org/abs/2404.14715)|null|
|**2024-04-22**|**Scene Coordinate Reconstruction: Posing of Image Collections via Incremental Learning of a Relocalizer**|Eric Brachmann et.al.|[2404.14351](http://arxiv.org/abs/2404.14351)|null|
|**2024-04-17**|**A Semantic Segmentation-guided Approach for Ground-to-Aerial Image Matching**|Francesco Pro et.al.|[2404.11302](http://arxiv.org/abs/2404.11302)|**[link](https://github.com/pro1944191/semanticalignnet)**|
|**2024-04-16**|**Exploring selective image matching methods for zero-shot and few-sample unsupervised domain adaptation of urban canopy prediction**|John Francis et.al.|[2404.10626](http://arxiv.org/abs/2404.10626)|null|
|**2024-04-15**|**XoFTR: Cross-modal Feature Matching Transformer**|Önder Tuzcuoğlu et.al.|[2404.09692](http://arxiv.org/abs/2404.09692)|null|
|**2024-04-13**|**DeDoDe v2: Analyzing and Improving the DeDoDe Keypoint Detector**|Johan Edstedt et.al.|[2404.08928](http://arxiv.org/abs/2404.08928)|**[link](https://github.com/parskatt/dedode)**|
|**2024-04-09**|**Matching 2D Images in 3D: Metric Relative Pose from Metric Correspondences**|Axel Barroso-Laguna et.al.|[2404.06337](http://arxiv.org/abs/2404.06337)|**[link](https://github.com/nianticlabs/mickey)**|
|**2024-04-01**|**Marrying NeRF with Feature Matching for One-step Pose Estimation**|Ronghan Chen et.al.|[2404.00891](http://arxiv.org/abs/2404.00891)|null|
|**2024-04-01**|**3MOS: Multi-sources, Multi-resolutions, and Multi-scenes dataset for Optical-SAR image matching**|Yibin Ye et.al.|[2404.00838](http://arxiv.org/abs/2404.00838)|null|
|**2024-03-31**|**On the Estimation of Image-matching Uncertainty in Visual Place Recognition**|Mubariz Zaffar et.al.|[2404.00546](http://arxiv.org/abs/2404.00546)|null|
|**2024-03-30**|**Image-to-Image Matching via Foundation Models: A New Perspective for Open-Vocabulary Semantic Segmentation**|Yuan Wang et.al.|[2404.00262](http://arxiv.org/abs/2404.00262)|null|
|**2024-03-26**|**Staircase Localization for Autonomous Exploration in Urban Environments**|Jinrae Kim et.al.|[2403.17330](http://arxiv.org/abs/2403.17330)|null|
|**2024-03-23**|**MatchSeg: Towards Better Segmentation via Reference Image Matching**|Ruiqiang Xiao et.al.|[2403.15901](http://arxiv.org/abs/2403.15901)|**[link](https://github.com/keeplearning-again/matchseg)**|
|**2024-03-20**|**Unifying Local and Global Multimodal Features for Place Recognition in Aliased and Low-Texture Environments**|Alberto García-Hernández et.al.|[2403.13395](http://arxiv.org/abs/2403.13395)|**[link](https://github.com/dlr-rm/umf)**|
|**2024-03-19**|**HCPM: Hierarchical Candidates Pruning for Efficient Detector-Free Matching**|Ying Chen et.al.|[2403.12543](http://arxiv.org/abs/2403.12543)|null|
|**2024-03-16**|**Refining Knowledge Transfer on Audio-Image Temporal Agreement for Audio-Text Cross Retrieval**|Shunsuke Tsubaki et.al.|[2403.10756](http://arxiv.org/abs/2403.10756)|null|
|**2024-03-16**|**Vector search with small radiuses**|Gergely Szilvasy et.al.|[2403.10746](http://arxiv.org/abs/2403.10746)|null|
|**2024-03-15**|**Local positional graphs and attentive local features for a data and runtime-efficient hierarchical place recognition pipeline**|Fangming Yuan et.al.|[2403.10283](http://arxiv.org/abs/2403.10283)|null|
|**2024-03-15**|**Region-aware Distribution Contrast: A Novel Approach to Multi-Task Partially Supervised Learning**|Meixuan Li et.al.|[2403.10252](http://arxiv.org/abs/2403.10252)|null|
|**2024-03-14**|**Virtual birefringence imaging and histological staining of amyloid deposits in label-free tissue using autofluorescence microscopy and deep learning**|Xilin Yang et.al.|[2403.09100](http://arxiv.org/abs/2403.09100)|null|
|**2024-03-18**|**Matching Non-Identical Objects**|Yusuke Marumo et.al.|[2403.08227](http://arxiv.org/abs/2403.08227)|null|
|**2024-03-11**|**Efficient LoFTR: Semi-Dense Local Feature Matching with Sparse-Like Speed**|Yifan Wang et.al.|[2403.04765](http://arxiv.org/abs/2403.04765)|null|
|**2024-03-07**|**Scene Depth Estimation from Traditional Oriental Landscape Paintings**|Sungho Kang et.al.|[2403.03408](http://arxiv.org/abs/2403.03408)|null|
|**2024-02-21**|**Visual Style Prompting with Swapping Self-Attention**|Jaeseok Jeong et.al.|[2402.12974](http://arxiv.org/abs/2402.12974)|**[link](https://github.com/naver-ai/Visual-Style-Prompting)**|
|**2024-02-16**|**GIM: Learning Generalizable Image Matcher From Internet Videos**|Xuelun Shen et.al.|[2402.11095](http://arxiv.org/abs/2402.11095)|null|
|**2024-04-23**|**Are Semi-Dense Detector-Free Methods Good at Matching Local Features?**|Matthieu Vilain et.al.|[2402.08671](http://arxiv.org/abs/2402.08671)|null|
|**2024-03-20**|**Learning to Produce Semi-dense Correspondences for Visual Localization**|Khang Truong Giang et.al.|[2402.08359](http://arxiv.org/abs/2402.08359)|**[link](https://github.com/truongkhang/deviloc)**|
|**2024-01-31**|**Improved Scene Landmark Detection for Camera Localization**|Tien Do et.al.|[2401.18083](http://arxiv.org/abs/2401.18083)|**[link](https://github.com/microsoft/scenelandmarklocalization)**|
|**2024-03-11**|**Local Feature Matching Using Deep Learning: A Survey**|Shibiao Xu et.al.|[2401.17592](http://arxiv.org/abs/2401.17592)|**[link](https://github.com/vignywang/awesome-local-feature-matching)**|
|**2024-01-24**|**Linear Relative Pose Estimation Founded on Pose-only Imaging Geometry**|Qi Cai et.al.|[2401.13357](http://arxiv.org/abs/2401.13357)|null|
|**2024-01-19**|**SCENES: Subpixel Correspondence Estimation With Epipolar Supervision**|Dominik A. Kloepfer et.al.|[2401.10886](http://arxiv.org/abs/2401.10886)|null|
|**2024-01-18**|**Question-Answer Cross Language Image Matching for Weakly Supervised Semantic Segmentation**|Songhe Deng et.al.|[2401.09883](http://arxiv.org/abs/2401.09883)|**[link](https://github.com/cvi-szu/qa-clims)**|
|**2024-01-26**|**RomniStereo: Recurrent Omnidirectional Stereo Matching**|Hualie Jiang et.al.|[2401.04345](http://arxiv.org/abs/2401.04345)|**[link](https://github.com/halleyjiang/romnistereo)**|
|**2024-01-05**|**CoCoT: Contrastive Chain-of-Thought Prompting for Large Multimodal Models with Multiple Image Inputs**|Daoan Zhang et.al.|[2401.02582](http://arxiv.org/abs/2401.02582)|null|
|**2024-01-03**|**Local Adaptive Clustering Based Image Matching for Automatic Visual Identification**|Zhizhen Wang et.al.|[2401.01720](http://arxiv.org/abs/2401.01720)|null|
|**2024-01-03**|**A Transformer-Based Adaptive Semantic Aggregation Method for UAV Visual Geo-Localization**|Shishen Li et.al.|[2401.01574](http://arxiv.org/abs/2401.01574)|null|
|**2023-12-23**|**BEV-CV: Birds-Eye-View Transform for Cross-View Geo-Localisation**|Tavis Shore et.al.|[2312.15363](http://arxiv.org/abs/2312.15363)|null|
|**2023-12-22**|**Harnessing Diffusion Models for Visual Perception with Meta Prompts**|Qiang Wan et.al.|[2312.14733](http://arxiv.org/abs/2312.14733)|**[link](https://github.com/fudan-zvg/meta-prompts)**|
|**2024-01-05**|**MatchDet: A Collaborative Framework for Image Matching and Object Detection**|Jinxiang Lai et.al.|[2312.10983](http://arxiv.org/abs/2312.10983)|null|
|**2023-12-07**|**Visual Geometry Grounded Deep Structure From Motion**|Jianyuan Wang et.al.|[2312.04563](http://arxiv.org/abs/2312.04563)|null|
|**2024-04-02**|**Steerers: A framework for rotation equivariant keypoint descriptors**|Georg Bökman et.al.|[2312.02152](http://arxiv.org/abs/2312.02152)|**[link](https://github.com/georg-bn/rotation-steerers)**|
|**2023-11-30**|**DSeg: Direct Line Segments Detection**|Berger Cyrille et.al.|[2311.18344](http://arxiv.org/abs/2311.18344)|null|
|**2023-11-30**|**Utilizing Radiomic Feature Analysis For Automated MRI Keypoint Detection: Enhancing Graph Applications**|Sahar Almahfouz Nasser et.al.|[2311.18281](http://arxiv.org/abs/2311.18281)|null|
|**2023-11-29**|**LGFCTR: Local and Global Feature Convolutional Transformer for Image Matching**|Wenhao Zhong et.al.|[2311.17571](http://arxiv.org/abs/2311.17571)|**[link](https://github.com/zwh0527/lgfctr)**|
|**2023-11-08**|**Zero-shot Translation of Attention Patterns in VQA Models to Natural Language**|Leonard Salewski et.al.|[2311.05043](http://arxiv.org/abs/2311.05043)|**[link](https://github.com/explainableml/zs-a2t)**|
|**2023-11-06**|**An invariant feature extraction for multi-modal images matching**|Chenzhong Gao et.al.|[2311.02842](http://arxiv.org/abs/2311.02842)|null|
|**2024-02-16**|**RD-VIO: Robust Visual-Inertial Odometry for Mobile Augmented Reality in Dynamic Environments**|Jinyu Li et.al.|[2310.15072](http://arxiv.org/abs/2310.15072)|**[link](https://github.com/openxrlab/xrslam)**|
|**2023-10-23**|**Player Re-Identification Using Body Part Appearences**|Mahesh Bhosale et.al.|[2310.14469](http://arxiv.org/abs/2310.14469)|null|
|**2023-10-20**|**FMRT: Learning Accurate Feature Matching with Reconciliatory Transformer**|Xinyu Zhang et.al.|[2310.13605](http://arxiv.org/abs/2310.13605)|null|
|**2024-03-15**|**RGM: A Robust Generalizable Matching Model**|Songyan Zhang et.al.|[2310.11755](http://arxiv.org/abs/2310.11755)|**[link](https://github.com/aim-uofa/rgm)**|
|**2023-10-07**|**UFD-PRiME: Unsupervised Joint Learning of Optical Flow and Stereo Depth through Pixel-Level Rigid Motion Estimation**|Shuai Yuan et.al.|[2310.04712](http://arxiv.org/abs/2310.04712)|null|
|**2023-10-02**|**Leveraging Cutting Edge Deep Learning Based Image Matching for Reconstructing a Large Scene from Sparse Images**|Georg Bökman et.al.|[2310.01092](http://arxiv.org/abs/2310.01092)|null|
|**2024-03-11**|**Segment Anything Model is a Good Teacher for Local Feature Learning**|Jingqian Wu et.al.|[2309.16992](http://arxiv.org/abs/2309.16992)|**[link](https://github.com/vignywang/samfeat)**|
|**2023-09-27**|**KDD-LOAM: Jointly Learned Keypoint Detector and Descriptors Assisted LiDAR Odometry and Mapping**|Renlang Huang et.al.|[2309.15394](http://arxiv.org/abs/2309.15394)|null|
|**2023-10-13**|**A Critical Analysis of Internal Reliability for Uncertainty Quantification of Dense Image Matching in Multi-view Stereo**|Debao Huang et.al.|[2309.09379](http://arxiv.org/abs/2309.09379)|null|
|**2023-09-11**|**Towards Content-based Pixel Retrieval in Revisited Oxford and Paris**|Guoyuan An et.al.|[2309.05438](http://arxiv.org/abs/2309.05438)|**[link](https://github.com/anguoyuan/pixel_retrieval-segmented_instance_retrieval)**|
|**2024-03-08**|**Neural Semantic Surface Maps**|Luca Morreale et.al.|[2309.04836](http://arxiv.org/abs/2309.04836)|null|
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
|**2024-02-11**|**Unsupervised Deep Graph Matching Based on Cycle Consistency**|Siddharth Tourani et.al.|[2307.08930](http://arxiv.org/abs/2307.08930)|null|
|**2023-12-26**|**Tightly-Coupled LiDAR-Visual SLAM Based on Geometric Features for Mobile Agents**|Ke Cao et.al.|[2307.07763](http://arxiv.org/abs/2307.07763)|null|
|**2023-07-09**|**Augmenters at SemEval-2023 Task 1: Enhancing CLIP in Handling Compositionality and Ambiguity for Zero-Shot Visual WSD through Prompt Augmentation and Text-To-Image Diffusion**|Jie S. Li et.al.|[2307.05564](http://arxiv.org/abs/2307.05564)|null|
|**2023-07-11**|**ResMatch: Residual Attention Learning for Local Feature Matching**|Yuxin Deng et.al.|[2307.05180](http://arxiv.org/abs/2307.05180)|**[link](https://github.com/acuooooo/resmatch)**|
|**2024-01-02**|**TIAM -- A Metric for Evaluating Alignment in Text-to-Image Generation**|Paul Grimal et.al.|[2307.05134](http://arxiv.org/abs/2307.05134)|**[link](https://github.com/grimalpaul/tiam)**|
|**2023-07-02**|**TopicFM+: Boosting Accuracy and Efficiency of Topic-Assisted Feature Matching**|Khang Truong Giang et.al.|[2307.00485](http://arxiv.org/abs/2307.00485)|**[link](https://github.com/truongkhang/topicfm)**|
|**2023-06-27**|**Detector-Free Structure from Motion**|Xingyi He et.al.|[2306.15669](http://arxiv.org/abs/2306.15669)|**[link](https://github.com/zju3dv/DetectorFreeSfM)**|
|**2024-01-24**|**PoseDiffusion: Solving Pose Estimation via Diffusion-aided Bundle Adjustment**|Jianyuan Wang et.al.|[2306.15667](http://arxiv.org/abs/2306.15667)|null|
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
|**2024-01-13**|**Image Matching by Bare Homography**|Fabio Bellavia et.al.|[2305.08946](http://arxiv.org/abs/2305.08946)|null|
|**2023-08-10**|**CLIP-Count: Towards Text-Guided Zero-Shot Object Counting**|Ruixiang Jiang et.al.|[2305.07304](http://arxiv.org/abs/2305.07304)|**[link](https://github.com/songrise/clip-count)**|
|**2023-09-25**|**SENDD: Sparse Efficient Neural Depth and Deformation for Tissue Tracking**|Adam Schmidt et.al.|[2305.06477](http://arxiv.org/abs/2305.06477)|null|
|**2023-05-10**|**Level-line Guided Edge Drawing for Robust Line Segment Detection**|Xinyu Lin et.al.|[2305.05883](http://arxiv.org/abs/2305.05883)|**[link](https://github.com/roylin1229/gedrlsd)**|
|**2023-11-21**|**ColonMapper: topological mapping and localization for colonoscopy**|Javier Morlana et.al.|[2305.05546](http://arxiv.org/abs/2305.05546)|null|
|**2023-04-29**|**A Comprehensive Review of Image Line Segment Detection and Description: Taxonomies, Comparisons, and Challenges**|Xinyu Lin et.al.|[2305.00264](http://arxiv.org/abs/2305.00264)|null|
|**2023-06-11**|**SFD2: Semantic-guided Feature Detection and Description**|Fei Xue et.al.|[2304.14845](http://arxiv.org/abs/2304.14845)|**[link](https://github.com/feixue94/sfd2)**|
|**2023-10-20**|**Enhancing Textbooks with Visuals from the Web for Improved Learning**|Janvijay Singh et.al.|[2304.08931](http://arxiv.org/abs/2304.08931)|**[link](https://github.com/eth-nlped/textbook-enrichment)**|
|**2023-04-17**|**DeepSim-Nets: Deep Similarity Networks for Stereo Image Matching**|Mohamed Ali Chebbi et.al.|[2304.08056](http://arxiv.org/abs/2304.08056)|**[link](https://github.com/dalichebbi/deepsimnets)**|
|**2023-04-16**|**Long-term Visual Localization with Mobile Sensors**|Shen Yan et.al.|[2304.07691](http://arxiv.org/abs/2304.07691)|null|
|**2023-04-12**|**SiLK -- Simple Learned Keypoints**|Pierre Gleize et.al.|[2304.06194](http://arxiv.org/abs/2304.06194)|**[link](https://github.com/facebookresearch/silk)**|
|**2023-04-16**|**ALIKED: A Lighter Keypoint and Descriptor Extraction Network via Deformable Transformation**|Xiaoming Zhao et.al.|[2304.03608](http://arxiv.org/abs/2304.03608)|**[link](https://github.com/Shiaoming/ALIKED)**|
|**2023-10-20**|**GlueStick: Robust Image Matching by Sticking Points and Lines Together**|Rémi Pautrat et.al.|[2304.02008](http://arxiv.org/abs/2304.02008)|**[link](https://github.com/cvg/gluestick)**|
|**2023-04-03**|**PoseMatcher: One-shot 6D Object Pose Estimation by Deep Feature Matching**|Pedro Castro et.al.|[2304.01382](http://arxiv.org/abs/2304.01382)|null|
|**2023-04-02**|**Enhancing Deformable Local Features by Jointly Learning to Detect and Describe Keypoints**|Guilherme Potje et.al.|[2304.00583](http://arxiv.org/abs/2304.00583)|**[link](https://github.com/verlab/DALF_CVPR_2023)**|
|**2023-04-13**|**Structured Epipolar Matcher for Local Feature Matching**|Jiahao Chang et.al.|[2303.16646](http://arxiv.org/abs/2303.16646)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## SFM

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-05-07**|**Novel View Synthesis with Neural Radiance Fields for Industrial Robot Applications**|Markus Hillemann et.al.|[2405.04345](http://arxiv.org/abs/2405.04345)|null|
|**2024-05-07**|**Non-rigid Structure-from-Motion: Temporally-smooth Procrustean Alignment and Spatially-variant Deformation Modeling**|Jiawei Shi et.al.|[2405.04309](http://arxiv.org/abs/2405.04309)|null|
|**2024-05-03**|**HoloGS: Instant Depth-based 3D Gaussian Splatting with Microsoft HoloLens 2**|Miriam Jäger et.al.|[2405.02005](http://arxiv.org/abs/2405.02005)|null|
|**2024-04-22**|**Scene Coordinate Reconstruction: Posing of Image Collections via Incremental Learning of a Relocalizer**|Eric Brachmann et.al.|[2404.14351](http://arxiv.org/abs/2404.14351)|null|
|**2024-04-22**|**RESFM: Robust Equivariant Multiview Structure from Motion**|Fadi Khatib et.al.|[2404.14280](http://arxiv.org/abs/2404.14280)|null|
|**2024-04-22**|**Does Gaussian Splatting need SFM Initialization?**|Yalda Foroutan et.al.|[2404.12547](http://arxiv.org/abs/2404.12547)|null|
|**2024-04-17**|**A Subspace-Constrained Tyler's Estimator and its Applications to Structure from Motion**|Feng Yu et.al.|[2404.11590](http://arxiv.org/abs/2404.11590)|**[link](https://github.com/alexfengg/ste)**|
|**2024-04-18**|**DeblurGS: Gaussian Splatting for Camera Motion Blur**|Jeongtaek Oh et.al.|[2404.11358](http://arxiv.org/abs/2404.11358)|null|
|**2024-04-15**|**LetsGo: Large-Scale Garage Modeling and Rendering via LiDAR-Assisted Gaussian Primitives**|Jiadi Cui et.al.|[2404.09748](http://arxiv.org/abs/2404.09748)|null|
|**2024-04-12**|**MonoPatchNeRF: Improving Neural Radiance Fields with Patch-based Monocular Guidance**|Yuqun Wu et.al.|[2404.08252](http://arxiv.org/abs/2404.08252)|null|
|**2024-04-11**|**Boosting Self-Supervision for Single-View Scene Completion via Knowledge Distillation**|Keonhee Han et.al.|[2404.07933](http://arxiv.org/abs/2404.07933)|null|
|**2024-04-07**|**NeRF2Points: Large-Scale Point Cloud Generation From Street Views' Radiance Field Optimization**|Peng Tu et.al.|[2404.04875](http://arxiv.org/abs/2404.04875)|null|
|**2024-04-04**|**GaSpCT: Gaussian Splatting for Novel CT Projection View Synthesis**|Emmanouil Nikolakakis et.al.|[2404.03126](http://arxiv.org/abs/2404.03126)|null|
|**2024-03-29**|**InstantSplat: Unbounded Sparse-view Pose-free Gaussian Splatting in 40 Seconds**|Zhiwen Fan et.al.|[2403.20309](http://arxiv.org/abs/2403.20309)|null|
|**2024-03-29**|**HO-Gaussian: Hybrid Optimization of 3D Gaussian Splatting for Urban Scenes**|Zhuopeng Li et.al.|[2403.20032](http://arxiv.org/abs/2403.20032)|null|
|**2024-03-26**|**NeRF-HuGS: Improved Neural Radiance Fields in Non-static Scenes Using Heuristics-Guided Segmentation**|Jiahao Chen et.al.|[2403.17537](http://arxiv.org/abs/2403.17537)|null|
|**2024-03-25**|**INPC: Implicit Neural Point Clouds for Radiance Field Rendering**|Florian Hahlbohm et.al.|[2403.16862](http://arxiv.org/abs/2403.16862)|null|
|**2024-03-18**|**An Accurate and Real-time Relative Pose Estimation from Triple Point-line Images by Decoupling Rotation and Translation**|Zewen Xu et.al.|[2403.11639](http://arxiv.org/abs/2403.11639)|null|
|**2024-03-14**|**Relaxing Accurate Initialization Constraint for 3D Gaussian Splatting**|Jaewoo Jung et.al.|[2403.09413](http://arxiv.org/abs/2403.09413)|**[link](https://github.com/KU-CVLAB/RAIN-GS)**|
|**2024-03-13**|**Refractive COLMAP: Refractive Structure-from-Motion Revisited**|Mengkun She et.al.|[2403.08640](http://arxiv.org/abs/2403.08640)|null|
|**2024-03-13**|**NeRF-Supervised Feature Point Detection and Description**|Ali Youssef et.al.|[2403.08156](http://arxiv.org/abs/2403.08156)|null|
|**2024-03-11**|**SiLVR: Scalable Lidar-Visual Reconstruction with Neural Radiance Fields for Robotic Inspection**|Yifu Tao et.al.|[2403.06877](http://arxiv.org/abs/2403.06877)|null|
|**2024-03-24**|**BAGS: Blur Agnostic Gaussian Splatting through Multi-Scale Kernel Modeling**|Cheng Peng et.al.|[2403.04926](http://arxiv.org/abs/2403.04926)|**[link](https://github.com/snldmt/bags)**|
|**2024-02-22**|**GaussianPro: 3D Gaussian Splatting with Progressive Propagation**|Kai Cheng et.al.|[2402.14650](http://arxiv.org/abs/2402.14650)|null|
|**2024-02-25**|**A Robust Error-Resistant View Selection Method for 3D Reconstruction**|Shaojie Zhang et.al.|[2402.11431](http://arxiv.org/abs/2402.11431)|null|
|**2024-02-17**|**Dense Matchers for Dense Tracking**|Tomáš Jelínek et.al.|[2402.11287](http://arxiv.org/abs/2402.11287)|null|
|**2024-03-11**|**Local Feature Matching Using Deep Learning: A Survey**|Shibiao Xu et.al.|[2401.17592](http://arxiv.org/abs/2401.17592)|**[link](https://github.com/vignywang/awesome-local-feature-matching)**|
|**2024-01-22**|**HG3-NeRF: Hierarchical Geometric, Semantic, and Photometric Guided Neural Radiance Fields for Sparse View Inputs**|Zelin Gao et.al.|[2401.11711](http://arxiv.org/abs/2401.11711)|null|
|**2024-01-19**|**SCENES: Subpixel Correspondence Estimation With Epipolar Supervision**|Dominik A. Kloepfer et.al.|[2401.10886](http://arxiv.org/abs/2401.10886)|null|
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
|**2023-12-11**|**Keypoint-based Stereophotoclinometry for Characterizing and Navigating Small Bodies: A Factor Graph Approach**|Travis Driver et.al.|[2312.06865](http://arxiv.org/abs/2312.06865)|**[link](https://github.com/travisdriver/spc-factor-results)**|
|**2024-04-14**|**Gaussian Splatting SLAM**|Hidenobu Matsuki et.al.|[2312.06741](http://arxiv.org/abs/2312.06741)|null|
|**2024-04-17**|**SuperPrimitive: Scene Reconstruction at a Primitive Level**|Kirill Mazur et.al.|[2312.05889](http://arxiv.org/abs/2312.05889)|null|
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
|**2023-12-27**|**Pose-Free Generalizable Rendering Transformer**|Zhiwen Fan et.al.|[2310.03704](http://arxiv.org/abs/2310.03704)|null|
|**2023-10-02**|**Leveraging Cutting Edge Deep Learning Based Image Matching for Reconstructing a Large Scene from Sparse Images**|Georg Bökman et.al.|[2310.01092](http://arxiv.org/abs/2310.01092)|null|
|**2023-10-01**|**Propagating Semantic Labels in Video Data**|David Balaban et.al.|[2310.00783](http://arxiv.org/abs/2310.00783)|null|
|**2023-09-22**|**Scalable Semantic 3D Mapping of Coral Reefs with Deep Learning**|Jonathan Sauder et.al.|[2309.12804](http://arxiv.org/abs/2309.12804)|null|
|**2024-02-14**|**On-the-Fly SfM: What you capture is What you get**|Zongqian Zhan et.al.|[2309.11883](http://arxiv.org/abs/2309.11883)|**[link](https://github.com/RayShark0605/On_the_fly_SfM)**|
|**2023-09-19**|**Using an Uncrewed Surface Vehicle to Create a Volumetric Model of Non-Navigable Rivers and Other Shallow Bodies of Water**|Jayesh Tripathi et.al.|[2309.10269](http://arxiv.org/abs/2309.10269)|null|
|**2024-03-18**|**DynaMoN: Motion-Aware Fast and Robust Camera Localization for Dynamic Neural Radiance Fields**|Nicolas Schischka et.al.|[2309.08927](http://arxiv.org/abs/2309.08927)|null|
|**2023-09-08**|**Robot Localization and Mapping Final Report -- Sequential Adversarial Learning for Self-Supervised Deep Visual Odometry**|Akankshya Kar et.al.|[2309.04147](http://arxiv.org/abs/2309.04147)|null|
|**2023-09-01**|**SQLdepth: Generalizable Self-Supervised Fine-Structured Monocular Depth Estimation**|Youhong Wang et.al.|[2309.00526](http://arxiv.org/abs/2309.00526)|null|
|**2023-09-01**|**Dense Voxel 3D Reconstruction Using a Monocular Event Camera**|Haodong Chen et.al.|[2309.00385](http://arxiv.org/abs/2309.00385)|null|
|**2023-12-04**|**Learning Structure-from-Motion with Graph Attention Networks**|Lucas Brynte et.al.|[2308.15984](http://arxiv.org/abs/2308.15984)|null|
|**2023-08-26**|**Disjoint Pose and Shape for 3D Face Reconstruction**|Raja Kumar et.al.|[2308.13903](http://arxiv.org/abs/2308.13903)|null|
|**2023-08-30**|**CamP: Camera Preconditioning for Neural Radiance Fields**|Keunhong Park et.al.|[2308.10902](http://arxiv.org/abs/2308.10902)|null|
|**2023-08-18**|**Unsupervised 3D Pose Estimation with Non-Rigid Structure-from-Motion Modeling**|Haorui Ji et.al.|[2308.10705](http://arxiv.org/abs/2308.10705)|null|
|**2024-03-02**|**Large-scale environment mapping and immersive human-robot interaction for agricultural mobile robot teleoperation**|Tao Liu et.al.|[2308.07231](http://arxiv.org/abs/2308.07231)|null|
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
|**2024-01-24**|**PoseDiffusion: Solving Pose Estimation via Diffusion-aided Bundle Adjustment**|Jianyuan Wang et.al.|[2306.15667](http://arxiv.org/abs/2306.15667)|null|
|**2023-06-24**|**3D Reconstruction of Spherical Images based on Incremental Structure from Motion**|San Jiang et.al.|[2306.12770](http://arxiv.org/abs/2306.12770)|**[link](https://github.com/json87/spheresfm)**|
|**2023-10-13**|**NAVI: Category-Agnostic Image Collections with High-Quality 3D Shape and Pose Annotations**|Varun Jampani et.al.|[2306.09109](http://arxiv.org/abs/2306.09109)|null|
|**2023-12-29**|**Yes, we CANN: Constrained Approximate Nearest Neighbors for local feature-based visual localization**|Dror Aiger et.al.|[2306.09012](http://arxiv.org/abs/2306.09012)|**[link](https://github.com/google-research/google-research)**|
|**2023-06-10**|**3D reconstruction using Structure for Motion**|Kshitij Karnawat et.al.|[2306.06360](http://arxiv.org/abs/2306.06360)|**[link](https://github.com/kshitijkarnawat/structure-from-motion)**|
|**2023-06-02**|**Self-supervised Interest Point Detection and Description for Fisheye and Perspective Images**|Marcela Mera-Trujillo et.al.|[2306.01938](http://arxiv.org/abs/2306.01938)|null|
|**2023-05-31**|**FlowCam: Training Generalizable 3D Radiance Fields without Camera Poses via Pixel-Aligned Scene Flow**|Cameron Smith et.al.|[2306.00180](http://arxiv.org/abs/2306.00180)|null|
|**2023-05-19**|**SIDAR: Synthetic Image Dataset for Alignment & Restoration**|Monika Kwiatkowski et.al.|[2305.12036](http://arxiv.org/abs/2305.12036)|**[link](https://github.com/niika/SIDAR)**|
|**2023-05-09**|**Eiffel Tower: A Deep-Sea Underwater Dataset for Long-Term Visual Localization**|Clémentin Boittiaux et.al.|[2305.05301](http://arxiv.org/abs/2305.05301)|**[link](https://github.com/clementinboittiaux/sfm-pipeline)**|
|**2023-05-09**|**Rotation Synchronization via Deep Matrix Factorization**|Gk Tejus et.al.|[2305.05268](http://arxiv.org/abs/2305.05268)|**[link](https://github.com/gktejus/DMF-Synch)**|
|**2023-04-20**|**A Comparative Neural Radiance Field (NeRF) 3D Analysis of Camera Poses from HoloLens Trajectories and Structure from Motion**|Miriam Jäger et.al.|[2304.10664](http://arxiv.org/abs/2304.10664)|null|
|**2024-01-26**|**Fusing Structure from Motion and Simulation-Augmented Pose Regression from Optical Flow for Challenging Indoor Environments**|Felix Ott et.al.|[2304.07250](http://arxiv.org/abs/2304.07250)|null|
|**2023-04-12**|**Visual Localization using Imperfect 3D Models from the Internet**|Vojtech Panek et.al.|[2304.05947](http://arxiv.org/abs/2304.05947)|**[link](https://github.com/v-pnk/cadloc)**|
|**2024-01-12**|**Photometric Correction for Infrared Sensors**|Jincheng Zhang et.al.|[2304.03930](http://arxiv.org/abs/2304.03930)|null|
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

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## IMU

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-04-24**|**3D Freehand Ultrasound using Visual Inertial and Deep Inertial Odometry for Measuring Patellar Tracking**|Russell Buchanan et.al.|[2404.15847](http://arxiv.org/abs/2404.15847)|null|
|**2024-01-24**|**DoorINet: A Deep-Learning Inertial Framework for Door-Mounted IoT Applications**|Aleksei Zakharchenko et.al.|[2402.09427](http://arxiv.org/abs/2402.09427)|**[link](https://github.com/ansfl/doorinet)**|
|**2024-03-16**|**Learning Inertial Parameter Identification of Unknown Object with Humanoid Robot using Real-to-Sim Adaptation**|Donghoon Baek et.al.|[2309.09810](http://arxiv.org/abs/2309.09810)|null|
|**2023-03-03**|**RIOT: Recursive Inertial Odometry Transformer for Localisation from Low-Cost IMU Measurements**|James Brotchie et.al.|[2303.01641](http://arxiv.org/abs/2303.01641)|null|
|**2022-11-14**|**Learnable Spatio-Temporal Map Embeddings for Deep Inertial Localization**|Dennis Melamed et.al.|[2211.07635](http://arxiv.org/abs/2211.07635)|null|
|**2022-11-10**|**Unsupervised Deep Learning-based clustering for Human Activity Recognition**|Hamza Amrani et.al.|[2211.05483](http://arxiv.org/abs/2211.05483)|**[link](https://github.com/hamzaamrani/Deep-Inertial-Sensory-Clustering)**|
|**2022-11-08**|**Deep IMU Bias Inference for Robust Visual-Inertial Odometry with Factor Graphs**|Russell Buchanan et.al.|[2211.04517](http://arxiv.org/abs/2211.04517)|null|
|**2023-02-28**|**Learned Inertial Odometry for Autonomous Drone Racing**|Giovanni Cioffi et.al.|[2210.15287](http://arxiv.org/abs/2210.15287)|**[link](https://github.com/uzh-rpg/learned_inertial_model_odometry)**|
|**2023-08-04**|**Benchmarking Visual-Inertial Deep Multimodal Fusion for Relative Pose Regression and Odometry-aided Absolute Pose Regression**|Felix Ott et.al.|[2208.00919](http://arxiv.org/abs/2208.00919)|null|
|**2022-05-06**|**IMU Based Deep Stride Length Estimation With Self-Supervised Learning**|Jien-De Sui et.al.|[2205.02977](http://arxiv.org/abs/2205.02977)|null|
|**2023-10-17**|**DIDO: Deep Inertial Quadrotor Dynamical Odometry**|Kunyi Zhang et.al.|[2203.03149](http://arxiv.org/abs/2203.03149)|**[link](https://github.com/zhangkunyi/dido)**|
|**2024-02-12**|**Inertial Newton Algorithms Avoiding Strict Saddle Points**|Camille Castera et.al.|[2111.04596](http://arxiv.org/abs/2111.04596)|**[link](https://github.com/camcastera/innaavoidssaddles)**|
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

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

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

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## NeRF

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-05-07**|**DistGrid: Scalable Scene Reconstruction with Distributed Multi-resolution Hash Grid**|Sidun Liu et.al.|[2405.04416](http://arxiv.org/abs/2405.04416)|null|
|**2024-05-07**|**Novel View Synthesis with Neural Radiance Fields for Industrial Robot Applications**|Markus Hillemann et.al.|[2405.04345](http://arxiv.org/abs/2405.04345)|null|
|**2024-05-05**|**Blending Distributed NeRFs with Tri-stage Robust Pose Optimization**|Baijun Ye et.al.|[2405.02880](http://arxiv.org/abs/2405.02880)|null|
|**2024-05-05**|**MVIP-NeRF: Multi-view 3D Inpainting on NeRF Scenes via Diffusion Prior**|Honghua Chen et.al.|[2405.02859](http://arxiv.org/abs/2405.02859)|null|
|**2024-05-04**|**TK-Planes: Tiered K-Planes with High Dimensional Feature Vectors for Dynamic UAV-based Scenes**|Christopher Maxey et.al.|[2405.02762](http://arxiv.org/abs/2405.02762)|null|
|**2024-05-04**|**ActiveNeuS: Active 3D Reconstruction using Neural Implicit Surface Uncertainty**|Hyunseo Kim et.al.|[2405.02568](http://arxiv.org/abs/2405.02568)|null|
|**2024-05-03**|**Learning Robot Soccer from Egocentric Vision with Deep Reinforcement Learning**|Dhruva Tirumala et.al.|[2405.02425](http://arxiv.org/abs/2405.02425)|null|
|**2024-05-03**|**Rip-NeRF: Anti-aliasing Radiance Fields with Ripmap-Encoded Platonic Solids**|Junchen Liu et.al.|[2405.02386](http://arxiv.org/abs/2405.02386)|**[link](https://github.com/junchenliu77/rip-nerf)**|
|**2024-05-03**|**WateRF: Robust Watermarks in Radiance Fields for Protection of Copyrights**|Youngdong Jang et.al.|[2405.02066](http://arxiv.org/abs/2405.02066)|null|
|**2024-05-02**|**NeRF in Robotics: A Survey**|Guangming Wang et.al.|[2405.01333](http://arxiv.org/abs/2405.01333)|null|
|**2024-05-04**|**LidaRF: Delving into Lidar for Neural Radiance Field on Street Scenes**|Shanlin Sun et.al.|[2405.00900](http://arxiv.org/abs/2405.00900)|null|
|**2024-05-01**|**Depth Priors in Removal Neural Radiance Fields**|Zhihao Guo et.al.|[2405.00630](http://arxiv.org/abs/2405.00630)|null|
|**2024-05-01**|**NeRF-Guided Unsupervised Learning of RGB-D Registration**|Zhinan Yu et.al.|[2405.00507](http://arxiv.org/abs/2405.00507)|null|
|**2024-05-01**|**RTG-SLAM: Real-time 3D Reconstruction at Scale using Gaussian Splatting**|Zhexi Peng et.al.|[2404.19706](http://arxiv.org/abs/2404.19706)|null|
|**2024-04-30**|**NeRF-Insert: 3D Local Editing with Multimodal Control Signals**|Benet Oriol Sabat et.al.|[2404.19204](http://arxiv.org/abs/2404.19204)|null|
|**2024-04-29**|**SAGS: Structure-Aware 3D Gaussian Splatting**|Evangelos Ververas et.al.|[2404.19149](http://arxiv.org/abs/2404.19149)|null|
|**2024-04-29**|**GSTalker: Real-time Audio-Driven Talking Face Generation via Deformable Gaussian Splatting**|Bo Chen et.al.|[2404.19040](http://arxiv.org/abs/2404.19040)|null|
|**2024-04-29**|**Embedded Representation Learning Network for Animating Styled Video Portrait**|Tianyong Wang et.al.|[2404.19038](http://arxiv.org/abs/2404.19038)|null|
|**2024-04-29**|**Simple-RF: Regularizing Sparse Input Radiance Fields with Simpler Solutions**|Nagabhushan Somraj et.al.|[2404.19015](http://arxiv.org/abs/2404.19015)|null|
|**2024-04-28**|**S3-SLAM: Sparse Tri-plane Encoding for Neural Implicit SLAM**|Zhiyao Zhang et.al.|[2404.18284](http://arxiv.org/abs/2404.18284)|null|
|**2024-04-27**|**DPER: Diffusion Prior Driven Neural Representation for Limited Angle and Sparse View CT Reconstruction**|Chenhe Du et.al.|[2404.17890](http://arxiv.org/abs/2404.17890)|null|
|**2024-04-26**|**Geometry-aware Reconstruction and Fusion-refined Rendering for Generalizable Neural Radiance Fields**|Tianqi Liu et.al.|[2404.17528](http://arxiv.org/abs/2404.17528)|**[link](https://github.com/tqtqliu/gefu)**|
|**2024-04-25**|**Depth Supervised Neural Surface Reconstruction from Airborne Imagery**|Vincent Hackstein et.al.|[2404.16429](http://arxiv.org/abs/2404.16429)|null|
|**2024-04-24**|**NeRF-XL: Scaling NeRFs with Multiple GPUs**|Ruilong Li et.al.|[2404.16221](http://arxiv.org/abs/2404.16221)|null|
|**2024-04-24**|**ESR-NeRF: Emissive Source Reconstruction Using LDR Multi-view Images**|Jinseo Jeong et.al.|[2404.15707](http://arxiv.org/abs/2404.15707)|null|
|**2024-04-23**|**DreamCraft: Text-Guided Generation of Functional 3D Environments in Minecraft**|Sam Earle et.al.|[2404.15538](http://arxiv.org/abs/2404.15538)|null|
|**2024-04-10**|**Efficient EndoNeRF Reconstruction and Its Application for Data-driven Surgical Simulation**|Yuehao Wang et.al.|[2404.15339](http://arxiv.org/abs/2404.15339)|null|
|**2024-04-28**|**GaussianTalker: Speaker-specific Talking Head Synthesis via 3D Gaussian Splatting**|Hongyun Yu et.al.|[2404.14037](http://arxiv.org/abs/2404.14037)|null|
|**2024-04-22**|**NeRF-DetS: Enhancing Multi-View 3D Object Detection with Sampling-adaptive Network of Continuous NeRF-based Representation**|Chi Huang et.al.|[2404.13921](http://arxiv.org/abs/2404.13921)|null|
|**2024-04-23**|**CT-NeRF: Incremental Optimizing Neural Radiance Field and Poses with Complex Trajectory**|Yunlong Ran et.al.|[2404.13896](http://arxiv.org/abs/2404.13896)|null|
|**2024-04-26**|**Neural Radiance Field in Autonomous Driving: A Survey**|Lei He et.al.|[2404.13816](http://arxiv.org/abs/2404.13816)|null|
|**2024-04-26**|**ArtNeRF: A Stylized Neural Field for 3D-Aware Cartoonized Face Synthesis**|Zichen Tang et.al.|[2404.13711](http://arxiv.org/abs/2404.13711)|**[link](https://github.com/silence-tang/artnerf)**|
|**2024-04-21**|**Generalizable Novel-View Synthesis using a Stereo Camera**|Haechan Lee et.al.|[2404.13541](http://arxiv.org/abs/2404.13541)|null|
|**2024-04-20**|**High-fidelity Endoscopic Image Synthesis by Utilizing Depth-guided Neural Surfaces**|Baoru Huang et.al.|[2404.13437](http://arxiv.org/abs/2404.13437)|null|
|**2024-04-20**|**EC-SLAM: Real-time Dense Neural RGB-D SLAM System with Effectively Constrained Global Bundle Adjustment**|Guanghao Li et.al.|[2404.13346](http://arxiv.org/abs/2404.13346)|**[link](https://github.com/lightingooo/ec-slam)**|
|**2024-04-19**|**FlyNeRF: NeRF-Based Aerial Mapping for High-Quality 3D Scene Reconstruction**|Maria Dronova et.al.|[2404.12970](http://arxiv.org/abs/2404.12970)|null|
|**2024-04-22**|**Does Gaussian Splatting need SFM Initialization?**|Yalda Foroutan et.al.|[2404.12547](http://arxiv.org/abs/2404.12547)|null|
|**2024-04-18**|**MeshLRM: Large Reconstruction Model for High-Quality Mesh**|Xinyue Wei et.al.|[2404.12385](http://arxiv.org/abs/2404.12385)|null|
|**2024-04-18**|**AG-NeRF: Attention-guided Neural Radiance Fields for Multi-height Large-scale Outdoor Scene Rendering**|Jingfeng Guo et.al.|[2404.11897](http://arxiv.org/abs/2404.11897)|null|
|**2024-04-18**|**Cicero: Addressing Algorithmic and Architectural Bottlenecks in Neural Rendering by Radiance Warping and Memory Optimizations**|Yu Feng et.al.|[2404.11852](http://arxiv.org/abs/2404.11852)|null|
|**2024-04-17**|**SLAIM: Robust Dense Neural SLAM for Online Tracking and Mapping**|Vincent Cartillier et.al.|[2404.11419](http://arxiv.org/abs/2404.11419)|null|
|**2024-04-16**|**Gaussian Splatting Decoder for 3D-aware Generative Adversarial Networks**|Florian Barthel et.al.|[2404.10625](http://arxiv.org/abs/2404.10625)|null|
|**2024-04-16**|**Enhancing 3D Fidelity of Text-to-3D using Cross-View Correspondences**|Seungwook Kim et.al.|[2404.10603](http://arxiv.org/abs/2404.10603)|null|
|**2024-04-16**|**1st Place Solution for ICCV 2023 OmniObject3D Challenge: Sparse-View Reconstruction**|Hang Du et.al.|[2404.10441](http://arxiv.org/abs/2404.10441)|null|
|**2024-04-16**|**SRGS: Super-Resolution 3D Gaussian Splatting**|Xiang Feng et.al.|[2404.10318](http://arxiv.org/abs/2404.10318)|null|
|**2024-04-16**|**Plug-and-Play Acceleration of Occupancy Grid-based NeRF Rendering using VDB Grid and Hierarchical Ray Traversal**|Yoshio Kato et.al.|[2404.10272](http://arxiv.org/abs/2404.10272)|**[link](https://github.com/yosshi999/faster-occgrid)**|
|**2024-04-15**|**Taming Latent Diffusion Model for Neural Radiance Field Inpainting**|Chieh Hubert Lin et.al.|[2404.09995](http://arxiv.org/abs/2404.09995)|null|
|**2024-04-15**|**Video2Game: Real-time, Interactive, Realistic and Browser-Compatible Environment from a Single Video**|Hongchi Xia et.al.|[2404.09833](http://arxiv.org/abs/2404.09833)|null|
|**2024-04-15**|**DeferredGS: Decoupled and Editable Gaussian Splatting with Deferred Shading**|Tong Wu et.al.|[2404.09412](http://arxiv.org/abs/2404.09412)|null|
|**2024-04-14**|**VRS-NeRF: Visual Relocalization with Sparse Neural Radiance Field**|Fei Xue et.al.|[2404.09271](http://arxiv.org/abs/2404.09271)|**[link](https://github.com/feixue94/vrs-nerf)**|
|**2024-04-15**|**OccGaussian: 3D Gaussian Splatting for Occluded Human Rendering**|Jingrui Ye et.al.|[2404.08449](http://arxiv.org/abs/2404.08449)|null|
|**2024-04-12**|**GPN: Generative Point-based NeRF**|Haipeng Wang et.al.|[2404.08312](http://arxiv.org/abs/2404.08312)|**[link](https://github.com/forestsen/GPN)**|
|**2024-04-12**|**MonoPatchNeRF: Improving Neural Radiance Fields with Patch-based Monocular Guidance**|Yuqun Wu et.al.|[2404.08252](http://arxiv.org/abs/2404.08252)|null|
|**2024-04-11**|**Connecting NeRFs, Images, and Text**|Francesco Ballerini et.al.|[2404.07993](http://arxiv.org/abs/2404.07993)|null|
|**2024-04-11**|**Boosting Self-Supervision for Single-View Scene Completion via Knowledge Distillation**|Keonhee Han et.al.|[2404.07933](http://arxiv.org/abs/2404.07933)|null|
|**2024-04-23**|**NeuroNCAP: Photorealistic Closed-loop Safety Testing for Autonomous Driving**|William Ljungbergh et.al.|[2404.07762](http://arxiv.org/abs/2404.07762)|**[link](https://github.com/atonderski/neuro-ncap)**|
|**2024-04-11**|**G-NeRF: Geometry-enhanced Novel View Synthesis from Single-View Images**|Zixiong Huang et.al.|[2404.07474](http://arxiv.org/abs/2404.07474)|**[link](https://github.com/llrtt/G-NeRF)**|
|**2024-04-10**|**SplatPose & Detect: Pose-Agnostic 3D Anomaly Detection**|Mathis Kruse et.al.|[2404.06832](http://arxiv.org/abs/2404.06832)|**[link](https://github.com/m-kruse98/splatpose)**|
|**2024-04-10**|**MonoSelfRecon: Purely Self-Supervised Explicit Generalizable 3D Reconstruction of Indoor Scenes from Monocular RGB Views**|Runfa Li et.al.|[2404.06753](http://arxiv.org/abs/2404.06753)|null|
|**2024-04-10**|**Bayesian NeRF: Quantifying Uncertainty with Volume Density in Neural Radiance Fields**|Sibeak Lee et.al.|[2404.06727](http://arxiv.org/abs/2404.06727)|**[link](https://github.com/lab-of-ai-and-robotics/bayesian_nerf)**|
|**2024-04-12**|**SpikeNVS: Enhancing Novel View Synthesis from Blurry Images via Spike Camera**|Gaole Dai et.al.|[2404.06710](http://arxiv.org/abs/2404.06710)|null|
|**2024-04-09**|**Magic-Boost: Boost 3D Generation with Mutli-View Conditioned Diffusion**|Fan Yang et.al.|[2404.06429](http://arxiv.org/abs/2404.06429)|null|
|**2024-04-14**|**3D Geometry-aware Deformable Gaussian Splatting for Dynamic View Synthesis**|Zhicheng Lu et.al.|[2404.06270](http://arxiv.org/abs/2404.06270)|null|
|**2024-04-09**|**GHNeRF: Learning Generalizable Human Features with Efficient Neural Radiance Fields**|Arnab Dey et.al.|[2404.06246](http://arxiv.org/abs/2404.06246)|null|
|**2024-04-09**|**HFNeRF: Learning Human Biomechanic Features with Neural Radiance Fields**|Arnab Dey et.al.|[2404.06152](http://arxiv.org/abs/2404.06152)|null|
|**2024-04-08**|**Stylizing Sparse-View 3D Scenes with Hierarchical Neural Representation**|Y. Wang et.al.|[2404.05236](http://arxiv.org/abs/2404.05236)|null|
|**2024-04-08**|**StylizedGS: Controllable Stylization for 3D Gaussian Splatting**|Dingxi Zhang et.al.|[2404.05220](http://arxiv.org/abs/2404.05220)|null|
|**2024-04-08**|**Semantic Flow: Learning Semantic Field of Dynamic Scenes from Monocular Videos**|Fengrui Tian et.al.|[2404.05163](http://arxiv.org/abs/2404.05163)|**[link](https://github.com/tianfr/semantic-flow)**|
|**2024-04-07**|**CodecNeRF: Toward Fast Encoding and Decoding, Compact, and High-quality Novel-view Synthesis**|Gyeongjin Kang et.al.|[2404.04913](http://arxiv.org/abs/2404.04913)|null|
|**2024-04-13**|**GauU-Scene V2: Assessing the Reliability of Image-Based Metrics with Expansive Lidar Image Dataset Using 3DGS and NeRF**|Butian Xiong et.al.|[2404.04880](http://arxiv.org/abs/2404.04880)|null|
|**2024-04-07**|**NeRF2Points: Large-Scale Point Cloud Generation From Street Views' Radiance Field Optimization**|Peng Tu et.al.|[2404.04875](http://arxiv.org/abs/2404.04875)|null|
|**2024-04-06**|**DATENeRF: Depth-Aware Text-based Editing of NeRFs**|Sara Rojas et.al.|[2404.04526](http://arxiv.org/abs/2404.04526)|null|
|**2024-04-05**|**Robust Gaussian Splatting**|François Darmon et.al.|[2404.04211](http://arxiv.org/abs/2404.04211)|null|
|**2024-04-04**|**SC4D: Sparse-Controlled Video-to-4D Generation and Motion Transfer**|Zijie Wu et.al.|[2404.03736](http://arxiv.org/abs/2404.03736)|null|
|**2024-04-07**|**RaFE: Generative Radiance Fields Restoration**|Zhongkai Wu et.al.|[2404.03654](http://arxiv.org/abs/2404.03654)|null|
|**2024-04-04**|**OpenNeRF: Open Set 3D Neural Scene Segmentation with Pixel-Wise Features and Rendered Novel Views**|Francis Engelmann et.al.|[2404.03650](http://arxiv.org/abs/2404.03650)|null|
|**2024-04-04**|**VF-NeRF: Viewshed Fields for Rigid NeRF Registration**|Leo Segre et.al.|[2404.03349](http://arxiv.org/abs/2404.03349)|null|
|**2024-04-03**|**GenN2N: Generative NeRF2NeRF Translation**|Xiangyue Liu et.al.|[2404.02788](http://arxiv.org/abs/2404.02788)|null|
|**2024-04-03**|**LiDAR4D: Dynamic Neural Fields for Novel Space-time View LiDAR Synthesis**|Zehan Zheng et.al.|[2404.02742](http://arxiv.org/abs/2404.02742)|**[link](https://github.com/ispc-lab/lidar4d)**|
|**2024-04-03**|**Neural Radiance Fields with Torch Units**|Bingnan Ni et.al.|[2404.02617](http://arxiv.org/abs/2404.02617)|null|
|**2024-02-19**|**Binary Opacity Grids: Capturing Fine Geometric Detail for Mesh-Based View Synthesis**|Christian Reiser et.al.|[2402.12377](http://arxiv.org/abs/2402.12377)|null|
|**2024-02-19**|**Colorizing Monochromatic Radiance Fields**|Yean Cheng et.al.|[2402.12184](http://arxiv.org/abs/2402.12184)|null|
|**2024-02-17**|**Semantically-aware Neural Radiance Fields for Visual Scene Understanding: A Comprehensive Review**|Thang-Anh-Quan Nguyen et.al.|[2402.11141](http://arxiv.org/abs/2402.11141)|null|
|**2024-02-15**|**Evaluating NeRFs for 3D Plant Geometry Reconstruction in Field Conditions**|Muhammad Arbab Arshad et.al.|[2402.10344](http://arxiv.org/abs/2402.10344)|null|
|**2024-02-14**|**PC-NeRF: Parent-Child Neural Radiance Fields Using Sparse LiDAR Frames in Autonomous Driving Environments**|Xiuzhong Hu et.al.|[2402.09325](http://arxiv.org/abs/2402.09325)|**[link](https://github.com/biter0088/pc-nerf)**|
|**2024-02-13**|**Preconditioners for the Stochastic Training of Implicit Neural Representations**|Shin-Fang Chng et.al.|[2402.08784](http://arxiv.org/abs/2402.08784)|null|
|**2024-02-13**|**NeRF Analogies: Example-Based Visual Attribute Transfer for NeRFs**|Michael Fischer et.al.|[2402.08622](http://arxiv.org/abs/2402.08622)|null|
|**2024-02-13**|**H2O-SDF: Two-phase Learning for 3D Indoor Reconstruction using Object Surface Fields**|Minyoung Park et.al.|[2402.08138](http://arxiv.org/abs/2402.08138)|null|
|**2024-02-12**|**DeformNet: Latent Space Modeling and Dynamics Prediction for Deformable Object Manipulation**|Chenchang Li et.al.|[2402.07648](http://arxiv.org/abs/2402.07648)|null|
|**2024-02-11**|**BioNeRF: Biologically Plausible Neural Radiance Fields for View Synthesis**|Leandro A. Passos et.al.|[2402.07310](http://arxiv.org/abs/2402.07310)|**[link](https://github.com/leandropassosjr/bionerf)**|
|**2024-02-11**|**3D Gaussian as a New Vision Era: A Survey**|Ben Fei et.al.|[2402.07181](http://arxiv.org/abs/2402.07181)|null|
|**2024-02-09**|**ImplicitDeepfake: Plausible Face-Swapping through Implicit Deepfake Generation using NeRF and Gaussian Splatting**|Georgii Stanishevskii et.al.|[2402.06390](http://arxiv.org/abs/2402.06390)|**[link](https://github.com/quereste/implicit-deepfake)**|
|**2024-02-07**|**NeRF as Non-Distant Environment Emitter in Physics-based Inverse Rendering**|Jingwang Ling et.al.|[2402.04829](http://arxiv.org/abs/2402.04829)|null|
|**2024-02-07**|**OV-NeRF: Open-vocabulary Neural Radiance Fields with Vision and Language Foundation Models for 3D Semantic Understanding**|Guibiao Liao et.al.|[2402.04648](http://arxiv.org/abs/2402.04648)|null|
|**2024-02-11**|**BirdNeRF: Fast Neural Reconstruction of Large-Scale Scenes From Aerial Imagery**|Huiqing Zhang et.al.|[2402.04554](http://arxiv.org/abs/2402.04554)|null|
|**2024-02-06**|**Improved Generalization of Weight Space Networks via Augmentations**|Aviv Shamsian et.al.|[2402.04081](http://arxiv.org/abs/2402.04081)|null|
|**2024-02-05**|**ViewFusion: Learning Composable Diffusion Models for Novel View Synthesis**|Bernard Spiegl et.al.|[2402.02906](http://arxiv.org/abs/2402.02906)|**[link](https://github.com/bronemos/view-fusion)**|
|**2024-02-02**|**ConRF: Zero-shot Stylization of 3D Scenes with Conditioned Radiation Fields**|Xingyu Miao et.al.|[2402.01950](http://arxiv.org/abs/2402.01950)|**[link](https://github.com/xingy038/conrf)**|
|**2024-02-02**|**Robust Inverse Graphics via Probabilistic Inference**|Tuan Anh Le et.al.|[2402.01915](http://arxiv.org/abs/2402.01915)|null|
|**2024-02-02**|**HyperPlanes: Hypernetwork Approach to Rapid NeRF Adaptation**|Paweł Batorski et.al.|[2402.01524](http://arxiv.org/abs/2402.01524)|**[link](https://github.com/gmum/hyperplanes)**|
|**2024-02-02**|**Di-NeRF: Distributed NeRF for Collaborative Learning with Unknown Relative Poses**|Mahboubeh Asadi et.al.|[2402.01485](http://arxiv.org/abs/2402.01485)|null|
|**2024-02-15**|**GaMeS: Mesh-Based Adapting and Modification of Gaussian Splatting**|Joanna Waczyńska et.al.|[2402.01459](http://arxiv.org/abs/2402.01459)|**[link](https://github.com/waczjoan/gaussian-mesh-splatting)**|
|**2024-02-02**|**Efficient Dynamic-NeRF Based Volumetric Video Coding with Rate Distortion Optimization**|Zhiyu Zhang et.al.|[2402.01380](http://arxiv.org/abs/2402.01380)|null|
|**2024-02-06**|**Taming Uncertainty in Sparse-view Generalizable NeRF via Indirect Diffusion Guidance**|Yaokun Li et.al.|[2402.01217](http://arxiv.org/abs/2402.01217)|null|
|**2024-02-01**|**ViCA-NeRF: View-Consistency-Aware 3D Editing of Neural Radiance Fields**|Jiahua Dong et.al.|[2402.00864](http://arxiv.org/abs/2402.00864)|**[link](https://github.com/dongjiahua/vica-nerf)**|
|**2024-02-01**|**Emo-Avatar: Efficient Monocular Video Style Avatar through Texture Rendering**|Pinxin Liu et.al.|[2402.00827](http://arxiv.org/abs/2402.00827)|null|
|**2024-01-31**|**CARFF: Conditional Auto-encoded Radiance Field for 3D Scene Forecasting**|Jiezhi Yang et.al.|[2401.18075](http://arxiv.org/abs/2401.18075)|null|
|**2024-02-01**|**Segment Anything in 3D Gaussians**|Xu Hu et.al.|[2401.17857](http://arxiv.org/abs/2401.17857)|null|
|**2024-01-30**|**Physical Priors Augmented Event-Based 3D Reconstruction**|Jiaxu Wang et.al.|[2401.17121](http://arxiv.org/abs/2401.17121)|**[link](https://github.com/mercerai/paev3d)**|
|**2024-01-31**|**Endo-4DGS: Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting**|Yiming Huang et.al.|[2401.16416](http://arxiv.org/abs/2401.16416)|null|
|**2024-01-29**|**Divide and Conquer: Rethinking the Training Paradigm of Neural Radiance Fields**|Rongkai Ma et.al.|[2401.16144](http://arxiv.org/abs/2401.16144)|null|
|**2024-01-26**|**3D Reconstruction and New View Synthesis of Indoor Environments based on a Dual Neural Radiance Field**|Zhenyu Bao et.al.|[2401.14726](http://arxiv.org/abs/2401.14726)|null|
|**2024-01-25**|**Learning Robust Generalizable Radiance Field with Visibility and Feature Augmented Point Representation**|Jiaxu Wang et.al.|[2401.14354](http://arxiv.org/abs/2401.14354)|null|
|**2024-01-27**|**Sketch2NeRF: Multi-view Sketch-guided Text-to-3D Generation**|Minglin Chen et.al.|[2401.14257](http://arxiv.org/abs/2401.14257)|null|
|**2024-01-24**|**EndoGaussians: Single View Dynamic Gaussian Splatting for Deformable Endoscopic Tissues Reconstruction**|Yangsen Chen et.al.|[2401.13352](http://arxiv.org/abs/2401.13352)|null|
|**2024-01-23**|**NeRF-AD: Neural Radiance Field with Attention-based Disentanglement for Talking Face Synthesis**|Chongke Bi et.al.|[2401.12568](http://arxiv.org/abs/2401.12568)|null|
|**2024-01-23**|**Exploration and Improvement of Nerf-based 3D Scene Editing Techniques**|Shun Fang et.al.|[2401.12456](http://arxiv.org/abs/2401.12456)|null|
|**2024-01-23**|**Methods and strategies for improving the novel view synthesis quality of neural radiation field**|Shun Fang et.al.|[2401.12451](http://arxiv.org/abs/2401.12451)|null|
|**2024-01-22**|**Single-View 3D Human Digitalization with Large Reconstruction Models**|Zhenzhen Weng et.al.|[2401.12175](http://arxiv.org/abs/2401.12175)|null|
|**2024-01-22**|**Scaling Face Interaction Graph Networks to Real World Scenes**|Tatiana Lopez-Guevara et.al.|[2401.11985](http://arxiv.org/abs/2401.11985)|null|
|**2024-01-22**|**HG3-NeRF: Hierarchical Geometric, Semantic, and Photometric Guided Neural Radiance Fields for Sparse View Inputs**|Zelin Gao et.al.|[2401.11711](http://arxiv.org/abs/2401.11711)|null|
|**2024-01-23**|**IPR-NeRF: Ownership Verification meets Neural Radiance Field**|Win Kent Ong et.al.|[2401.09495](http://arxiv.org/abs/2401.09495)|null|
|**2024-01-17**|**ICON: Incremental CONfidence for Joint Pose and Radiance Field Optimization**|Weiyao Wang et.al.|[2401.08937](http://arxiv.org/abs/2401.08937)|null|
|**2024-01-18**|**ProvNeRF: Modeling per Point Provenance in NeRFs as a Stochastic Process**|Kiyohiro Nakayama et.al.|[2401.08140](http://arxiv.org/abs/2401.08140)|null|
|**2024-01-16**|**Forging Vision Foundation Models for Autonomous Driving: Challenges, Methodologies, and Opportunities**|Xu Yan et.al.|[2401.08045](http://arxiv.org/abs/2401.08045)|**[link](https://github.com/zhanghm1995/forge_vfm4ad)**|
|**2024-01-15**|**6-DoF Grasp Pose Evaluation and Optimization via Transfer Learning from NeRFs**|Gergely Sóti et.al.|[2401.07935](http://arxiv.org/abs/2401.07935)|null|
|**2024-01-11**|**TriNeRFLet: A Wavelet Based Multiscale Triplane NeRF Representation**|Rajaei Khatib et.al.|[2401.06191](http://arxiv.org/abs/2401.06191)|null|
|**2024-01-11**|**Fast High Dynamic Range Radiance Fields for Dynamic Scenes**|Guanjun Wu et.al.|[2401.06052](http://arxiv.org/abs/2401.06052)|null|
|**2024-01-30**|**CoSSegGaussians: Compact and Swift Scene Segmenting 3D Gaussians with Dual Feature Fusion**|Bin Dou et.al.|[2401.05925](http://arxiv.org/abs/2401.05925)|null|
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

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

## Occupancy

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-05-07**|**DriveWorld: 4D Pre-trained Scene Understanding via World Models for Autonomous Driving**|Chen Min et.al.|[2405.04390](http://arxiv.org/abs/2405.04390)|null|
|**2024-05-04**|**Vision-based 3D occupancy prediction in autonomous driving: a review and outlook**|Yanan Zhang et.al.|[2405.02595](http://arxiv.org/abs/2405.02595)|**[link](https://github.com/zya3d/awesome-3d-occupancy-prediction)**|
|**2024-05-03**|**Accurate Pose Prediction on Signed Distance Fields for Mobile Ground Robots in Rough Terrain**|Martin Oehler et.al.|[2405.02121](http://arxiv.org/abs/2405.02121)|null|
|**2024-04-24**|**ActiveRIR: Active Audio-Visual Exploration for Acoustic Environment Modeling**|Arjun Somayazulu et.al.|[2404.16216](http://arxiv.org/abs/2404.16216)|null|
|**2024-04-24**|**Decentralized Multi-Agent Trajectory Planning in Dynamic Environments with Spatiotemporal Occupancy Grid Maps**|Siyuan Wu et.al.|[2404.15602](http://arxiv.org/abs/2404.15602)|null|
|**2024-04-23**|**OccGen: Generative Multi-modal 3D Occupancy Prediction for Autonomous Driving**|Guoqing Wang et.al.|[2404.15014](http://arxiv.org/abs/2404.15014)|null|
|**2024-04-22**|**OccFeat: Self-supervised Occupancy Feature Prediction for Pretraining BEV Segmentation Networks**|Sophia Sirko-Galouchenko et.al.|[2404.14027](http://arxiv.org/abs/2404.14027)|null|
|**2024-04-18**|**Not All Voxels Are Equal: Hardness-Aware Semantic Scene Completion with Self-Distillation**|Song Wang et.al.|[2404.11958](http://arxiv.org/abs/2404.11958)|**[link](https://github.com/songw-zju/HASSC)**|
|**2024-04-16**|**Plug-and-Play Acceleration of Occupancy Grid-based NeRF Rendering using VDB Grid and Hierarchical Ray Traversal**|Yoshio Kato et.al.|[2404.10272](http://arxiv.org/abs/2404.10272)|**[link](https://github.com/yosshi999/faster-occgrid)**|
|**2024-04-15**|**SparseOcc: Rethinking Sparse Latent Representation for Vision-Based Semantic Occupancy Prediction**|Pin Tang et.al.|[2404.09502](http://arxiv.org/abs/2404.09502)|null|
|**2024-04-11**|**Boosting Self-Supervision for Single-View Scene Completion via Knowledge Distillation**|Keonhee Han et.al.|[2404.07933](http://arxiv.org/abs/2404.07933)|null|
|**2024-04-07**|**Multi-Type Map Construction via Semantics-Aware Autonomous Exploration in Unknown Indoor Environments**|Jianfang Mao et.al.|[2404.04879](http://arxiv.org/abs/2404.04879)|null|
|**2024-04-09**|**Co-Occ: Coupling Explicit Feature Fusion with Volume Rendering Regularization for Multi-Modal 3D Semantic Occupancy Prediction**|Jingyi Pan et.al.|[2404.04561](http://arxiv.org/abs/2404.04561)|null|
|**2024-04-05**|**Under-Canopy Navigation using Aerial Lidar Maps**|Lucas Carvalho de Lima et.al.|[2404.03911](http://arxiv.org/abs/2404.03911)|null|
|**2024-04-02**|**OFMPNet: Deep End-to-End Model for Occupancy and Flow Prediction in Urban Environment**|Youshaa Murhij et.al.|[2404.02263](http://arxiv.org/abs/2404.02263)|**[link](https://github.com/youshaamurhij/ofmpnet)**|
|**2024-04-02**|**PRISM-TopoMap: Online Topological Mapping with Place Recognition and Scan Matching**|Kirill Muravyev et.al.|[2404.01674](http://arxiv.org/abs/2404.01674)|**[link](https://github.com/kirillmouraviev/prism-topomap)**|
|**2024-04-01**|**QuAD: Query-based Interpretable Neural Motion Planning for Autonomous Driving**|Sourav Biswas et.al.|[2404.01486](http://arxiv.org/abs/2404.01486)|null|
|**2024-03-31**|**An Active Perception Game for Robust Autonomous Exploration**|Siming He et.al.|[2404.00769](http://arxiv.org/abs/2404.00769)|null|
|**2024-04-20**|**End-to-End Autonomous Driving through V2X Cooperation**|Haibao Yu et.al.|[2404.00717](http://arxiv.org/abs/2404.00717)|**[link](https://github.com/air-thu/univ2x)**|
|**2024-03-25**|**Optimizing LiDAR Placements for Robust Driving Perception in Adverse Conditions**|Ye Li et.al.|[2403.17009](http://arxiv.org/abs/2403.17009)|**[link](https://github.com/ywyeli/place3d)**|
|**2024-03-22**|**CoNVOI: Context-aware Navigation using Vision Language Models in Outdoor and Indoor Environments**|Adarsh Jagan Sathyamoorthy et.al.|[2403.15637](http://arxiv.org/abs/2403.15637)|null|
|**2024-03-22**|**SymboSLAM: Semantic Map Generation in a Multi-Agent System**|Brandon Curtis Colelough et.al.|[2403.15504](http://arxiv.org/abs/2403.15504)|null|
|**2024-03-21**|**ODTFormer: Efficient Obstacle Detection and Tracking with Stereo Cameras Based on Transformer**|Tianye Ding et.al.|[2403.14626](http://arxiv.org/abs/2403.14626)|null|
|**2024-03-21**|**SurroundSDF: Implicit 3D Scene Understanding Based on Signed Distance Field**|Lizhe Liu et.al.|[2403.14366](http://arxiv.org/abs/2403.14366)|null|
|**2024-03-21**|**Volumetric Environment Representation for Vision-Language Navigation**|Rui Liu et.al.|[2403.14158](http://arxiv.org/abs/2403.14158)|**[link](https://github.com/defaultrui/vln-ver)**|
|**2024-03-18**|**StereoNavNet: Learning to Navigate using Stereo Cameras with Auxiliary Occupancy Voxels**|Hongyu Li et.al.|[2403.12039](http://arxiv.org/abs/2403.12039)|null|
|**2024-03-18**|**SceneSense: Diffusion Models for 3D Occupancy Synthesis from Partial Observation**|Alec Reed et.al.|[2403.11985](http://arxiv.org/abs/2403.11985)|null|
|**2024-03-19**|**Urban Scene Diffusion through Semantic Occupancy Map**|Junge Zhang et.al.|[2403.11697](http://arxiv.org/abs/2403.11697)|null|
|**2024-03-14**|**VIRUS-NeRF -- Vision, InfraRed and UltraSonic based Neural Radiance Fields**|Nicolaj Schmid et.al.|[2403.09477](http://arxiv.org/abs/2403.09477)|null|
|**2024-03-14**|**PreSight: Enhancing Autonomous Vehicle Perception with City-Scale NeRF Priors**|Tianyuan Yuan et.al.|[2403.09079](http://arxiv.org/abs/2403.09079)|**[link](https://github.com/yuantianyuan01/presight)**|
|**2024-03-13**|**MonoOcc: Digging into Monocular Semantic Occupancy Prediction**|Yupeng Zheng et.al.|[2403.08766](http://arxiv.org/abs/2403.08766)|**[link](https://github.com/ucaszyp/monoocc)**|
|**2024-04-29**|**Real-time 3D semantic occupancy prediction for autonomous vehicles using memory-efficient sparse convolution**|Samuel Sze et.al.|[2403.08748](http://arxiv.org/abs/2403.08748)|null|
|**2024-03-13**|**UniLiDAR: Bridge the domain gap among different LiDARs for continual learning**|Zikun Xu et.al.|[2403.08512](http://arxiv.org/abs/2403.08512)|null|
|**2024-03-15**|**OccFiner: Offboard Occupancy Refinement with Hybrid Propagation**|Hao Shi et.al.|[2403.08504](http://arxiv.org/abs/2403.08504)|null|
|**2024-03-13**|**Empowering Robotics with Large Language Models: osmAG Map Comprehension with LLMs**|Fujing Xie et.al.|[2403.08228](http://arxiv.org/abs/2403.08228)|**[link](https://github.com/hiyouga/llama-factory)**|
|**2024-03-13**|**Perceive With Confidence: Statistical Safety Assurances for Navigation with Learning-Based Perception**|Anushri Dixit et.al.|[2403.08185](http://arxiv.org/abs/2403.08185)|null|
|**2024-03-08**|**OccFusion: Depth Estimation Free Multi-sensor Fusion for 3D Occupancy Prediction**|Ji Zhang et.al.|[2403.05329](http://arxiv.org/abs/2403.05329)|null|
|**2024-03-07**|**Real-Time Planning Under Uncertainty for AUVs Using Virtual Maps**|Ivana Collado-Gonzalez et.al.|[2403.04936](http://arxiv.org/abs/2403.04936)|null|
|**2024-03-07**|**Control-Barrier-Aided Teleoperation with Visual-Inertial SLAM for Safe MAV Navigation in Complex Environments**|Siqi Zhou et.al.|[2403.04331](http://arxiv.org/abs/2403.04331)|null|
|**2024-03-05**|**A Safety-Critical Framework for UGVs in Complex Environments: A Data-Driven Discrepancy-Aware Approach**|Skylar X. Wei et.al.|[2403.03215](http://arxiv.org/abs/2403.03215)|null|
|**2024-03-05**|**FastOcc: Accelerating 3D Occupancy Prediction by Fusing the 2D Bird's-Eye View and Perspective View**|Jiawei Hou et.al.|[2403.02710](http://arxiv.org/abs/2403.02710)|null|
|**2024-03-04**|**Tightly-Coupled LiDAR-Visual-Inertial SLAM and Large-Scale Volumetric Occupancy Mapping**|Simon Boche et.al.|[2403.02280](http://arxiv.org/abs/2403.02280)|null|
|**2024-04-22**|**OccFusion: A Straightforward and Effective Multi-Sensor Fusion Framework for 3D Occupancy Prediction**|Zhenxing Ming et.al.|[2403.01644](http://arxiv.org/abs/2403.01644)|null|
|**2024-02-28**|**OccTransformer: Improving BEVFormer for 3D camera-only occupancy prediction**|Jian Liu et.al.|[2402.18140](http://arxiv.org/abs/2402.18140)|null|
|**2024-04-02**|**SDGE: Stereo Guided Depth Estimation for 360 $^\circ$ Camera Sets**|Jialei Xu et.al.|[2402.11791](http://arxiv.org/abs/2402.11791)|null|
|**2024-04-25**|**Collaborative Semantic Occupancy Prediction with Hybrid Feature Fusion in Connected Automated Vehicles**|Rui Song et.al.|[2402.07635](http://arxiv.org/abs/2402.07635)|null|
|**2024-02-04**|**Hybrid-Prediction Integrated Planning for Autonomous Driving**|Haochen Liu et.al.|[2402.02426](http://arxiv.org/abs/2402.02426)|null|
|**2024-02-02**|**Dynamic Occupancy Grids for Object Detection: A Radar-Centric Approach**|Max Peter Ronecker et.al.|[2402.01488](http://arxiv.org/abs/2402.01488)|null|
|**2024-04-04**|**Unified Spatio-Temporal Tri-Perspective View Representation for 3D Semantic Occupancy Prediction**|Sathira Silva et.al.|[2401.13785](http://arxiv.org/abs/2401.13785)|null|
|**2024-04-29**|**InverseMatrixVT3D: An Efficient Projection Matrix-Based Approach for 3D Occupancy Prediction**|Zhenxing Ming et.al.|[2401.12422](http://arxiv.org/abs/2401.12422)|**[link](https://github.com/danielming123/inversematrixvt3d)**|
|**2024-01-17**|**POP-3D: Open-Vocabulary 3D Occupancy Prediction from Images**|Antonin Vobecky et.al.|[2401.09413](http://arxiv.org/abs/2401.09413)|null|
|**2024-01-13**|**UniVision: A Unified Framework for Vision-Centric 3D Perception**|Yu Hong et.al.|[2401.06994](http://arxiv.org/abs/2401.06994)|null|
|**2024-02-06**|**Occupancy Prediction for Building Energy Systems with Latent Force Models**|Thore Wietzke et.al.|[2401.05074](http://arxiv.org/abs/2401.05074)|**[link](https://github.com/thorewietzke/occupancy-benchmark-dataset)**|
|**2024-01-05**|**Comparative Evaluation of RGB-D SLAM Methods for Humanoid Robot Localization and Mapping**|Amirhosein Vedadi et.al.|[2401.02816](http://arxiv.org/abs/2401.02816)|null|
|**2024-04-08**|**Fully Sparse 3D Occupancy Prediction**|Haisong Liu et.al.|[2312.17118](http://arxiv.org/abs/2312.17118)|**[link](https://github.com/mcg-nju/sparseocc)**|
|**2023-12-22**|**Room Occupancy Prediction: Exploring the Power of Machine Learning and Temporal Insights**|Siqi Mao et.al.|[2312.14426](http://arxiv.org/abs/2312.14426)|null|
|**2023-12-19**|**Regulating Intermediate 3D Features for Vision-Centric Autonomous Driving**|Junkai Xu et.al.|[2312.11837](http://arxiv.org/abs/2312.11837)|**[link](https://github.com/cskkxjk/vampire)**|
|**2023-12-19**|**RadOcc: Learning Cross-Modality Occupancy Knowledge through Rendering Assisted Distillation**|Haiming Zhang et.al.|[2312.11829](http://arxiv.org/abs/2312.11829)|null|
|**2024-03-19**|**Drones Guiding Drones: Cooperative Navigation of a Less-Equipped Micro Aerial Vehicle in Cluttered Environments**|Václav Pritzl et.al.|[2312.09786](http://arxiv.org/abs/2312.09786)|null|
|**2024-03-30**|**OccNeRF: Advancing 3D Occupancy Prediction in LiDAR-Free Environments**|Chubin Zhang et.al.|[2312.09243](http://arxiv.org/abs/2312.09243)|**[link](https://github.com/linshan-bin/occnerf)**|
|**2023-12-10**|**Graph-based Prediction and Planning Policy Network (GP3Net) for scalable self-driving in dynamic environments using Deep Reinforcement Learning**|Jayabrata Chowdhury et.al.|[2312.05784](http://arxiv.org/abs/2312.05784)|null|
|**2024-03-19**|**OctreeOcc: Efficient and Multi-Granularity Occupancy Prediction Using Octree Queries**|Yuhang Lu et.al.|[2312.03774](http://arxiv.org/abs/2312.03774)|**[link](https://github.com/4DVLab/OctreeOcc)**|
|**2023-12-06**|**VLFM: Vision-Language Frontier Maps for Zero-Shot Semantic Navigation**|Naoki Yokoyama et.al.|[2312.03275](http://arxiv.org/abs/2312.03275)|null|
|**2024-04-11**|**COTR: Compact Occupancy TRansformer for Vision-based 3D Occupancy Prediction**|Qihang Ma et.al.|[2312.01919](http://arxiv.org/abs/2312.01919)|**[link](https://github.com/notacracker/cotr)**|
|**2023-11-29**|**SelfOcc: Self-Supervised Vision-Based 3D Occupancy Prediction**|Yuanhui Huang et.al.|[2311.12754](http://arxiv.org/abs/2311.12754)|**[link](https://github.com/huang-yh/selfocc)**|
|**2023-11-18**|**FlashOcc: Fast and Memory-Efficient Occupancy Prediction via Channel-to-Height Plugin**|Zichen Yu et.al.|[2311.12058](http://arxiv.org/abs/2311.12058)|**[link](https://github.com/Yzichen/FlashOCC)**|
|**2023-11-19**|**SOccDPT: Semi-Supervised 3D Semantic Occupancy from Dense Prediction Transformers trained under memory constraints**|Aditya Nalgunda Ganesh et.al.|[2311.11371](http://arxiv.org/abs/2311.11371)|null|
|**2023-11-16**|**Safety Aware Autonomous Path Planning Using Model Predictive Reinforcement Learning for Inland Waterways**|Astrid Vanneste et.al.|[2311.09878](http://arxiv.org/abs/2311.09878)|null|
|**2023-11-07**|**Spatio-Temporal Anomaly Detection with Graph Networks for Data Quality Monitoring of the Hadron Calorimeter**|Mulugeta Weldezgina Asres et.al.|[2311.04190](http://arxiv.org/abs/2311.04190)|null|
|**2023-11-03**|**EmerNeRF: Emergent Spatial-Temporal Scene Decomposition via Self-Supervision**|Jiawei Yang et.al.|[2311.02077](http://arxiv.org/abs/2311.02077)|null|
|**2024-04-11**|**Predicting Future Spatiotemporal Occupancy Grids with Semantics for Autonomous Driving**|Maneekwan Toyungyernsub et.al.|[2310.01723](http://arxiv.org/abs/2310.01723)|null|
|**2023-11-16**|**Active SLAM Utility Function Exploiting Path Entropy**|Muhammad Farhan Ahmed et.al.|[2309.16490](http://arxiv.org/abs/2309.16490)|null|
|**2024-03-09**|**Scene Informer: Anchor-based Occlusion Inference and Trajectory Prediction in Partially Observable Environments**|Bernard Lange et.al.|[2309.13893](http://arxiv.org/abs/2309.13893)|**[link](https://github.com/sisl/sceneinformer)**|
|**2023-09-25**|**SPOT: Scalable 3D Pre-training via Occupancy Prediction for Autonomous Driving**|Xiangchao Yan et.al.|[2309.10527](http://arxiv.org/abs/2309.10527)|**[link](https://github.com/pjlab-adg/3dtrans)**|
|**2023-09-18**|**Efficient and Accurate Mapping of Subsurface Anatomy via Online Trajectory Optimization for Robot Assisted Surgery**|Brian Y. Cho et.al.|[2309.10154](http://arxiv.org/abs/2309.10154)|null|
|**2024-03-04**|**RenderOcc: Vision-Centric 3D Occupancy Prediction with 2D Rendering Supervision**|Mingjie Pan et.al.|[2309.09502](http://arxiv.org/abs/2309.09502)|**[link](https://github.com/pmj110119/renderocc)**|
|**2023-09-17**|**Heuristic-based Incremental Probabilistic Roadmap for Efficient UAV Exploration in Dynamic Environments**|Zhefan Xu et.al.|[2309.09121](http://arxiv.org/abs/2309.09121)|**[link](https://github.com/zhefan-xu/cerlab-uav-autonomy)**|
|**2023-09-22**|**OccupancyDETR: Making Semantic Scene Completion as Straightforward as Object Detection**|Yupeng Jia et.al.|[2309.08504](http://arxiv.org/abs/2309.08504)|**[link](https://github.com/jypjypjypjyp/occupancydetr)**|
|**2023-09-15**|**Object-oriented mapping in dynamic environments**|Matti Pekkanen et.al.|[2309.08324](http://arxiv.org/abs/2309.08324)|null|
|**2023-08-31**|**PointOcc: Cylindrical Tri-Perspective View for Point-based 3D Semantic Occupancy Prediction**|Sicheng Zuo et.al.|[2308.16896](http://arxiv.org/abs/2308.16896)|**[link](https://github.com/wzzheng/pointocc)**|
|**2023-08-18**|**DReg-NeRF: Deep Registration for Neural Radiance Fields**|Yu Chen et.al.|[2308.09386](http://arxiv.org/abs/2308.09386)|**[link](https://github.com/aibluefisher/dreg-nerf)**|
|**2023-08-14**|**UniWorld: Autonomous Driving Pre-training via World Models**|Chen Min et.al.|[2308.07234](http://arxiv.org/abs/2308.07234)|**[link](https://github.com/chaytonmin/uniworld)**|
|**2023-08-10**|**Robust Lifelong Indoor LiDAR Localization using the Area Graph**|Fujing Xie et.al.|[2308.05593](http://arxiv.org/abs/2308.05593)|null|
|**2023-08-10**|**Occupancy Grid Map to Pose Graph-based Map: Robust BIM-based 2D-LiDAR Localization for Lifelong Indoor Navigation in Changing and Dynamic Environments**|Miguel Arturo Vega Torres et.al.|[2308.05443](http://arxiv.org/abs/2308.05443)|**[link](https://github.com/migvega/ogm2pgbm)**|
|**2023-08-08**|**Vehicle Motion Forecasting using Prior Information and Semantic-assisted Occupancy Grid Maps**|Rabbia Asghar et.al.|[2308.04303](http://arxiv.org/abs/2308.04303)|null|
|**2023-08-02**|**Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving**|Ben Agro et.al.|[2308.01471](http://arxiv.org/abs/2308.01471)|null|
|**2023-08-14**|**FusionAD: Multi-modality Fusion for Prediction and Planning Tasks of Autonomous Driving**|Tengju Ye et.al.|[2308.01006](http://arxiv.org/abs/2308.01006)|**[link](https://github.com/westlake-autolab/fusionad)**|
|**2023-07-17**|**Uncertainty-Aware Acoustic Localization and Mapping for Underwater Robots**|Jingyu Song et.al.|[2307.08647](http://arxiv.org/abs/2307.08647)|null|
|**2023-10-05**|**Occupancy Grid Mapping without Ray-Casting for High-resolution LiDAR Sensors**|Yixi Cai et.al.|[2307.08493](http://arxiv.org/abs/2307.08493)|**[link](https://github.com/hku-mars/d-map)**|
|**2023-07-12**|**OG: Equip vision occupancy with instance segmentation and visual grounding**|Zichao Dong et.al.|[2307.05873](http://arxiv.org/abs/2307.05873)|null|
|**2023-07-08**|**Spatio-Temporal Avoidance of Predicted Occupancy in Human-Robot Collaboration**|Jared Flowers et.al.|[2307.03909](http://arxiv.org/abs/2307.03909)|null|
|**2023-07-04**|**FB-OCC: 3D Occupancy Prediction based on Forward-Backward View Transformation**|Zhiqi Li et.al.|[2307.01492](http://arxiv.org/abs/2307.01492)|**[link](https://github.com/nvlabs/fb-bev)**|
|**2023-10-03**|**LXL: LiDAR Excluded Lean 3D Object Detection with 4D Imaging Radar and Camera Fusion**|Weiyi Xiong et.al.|[2307.00724](http://arxiv.org/abs/2307.00724)|null|
|**2023-10-13**|**SeMLaPS: Real-time Semantic Mapping with Latent Prior Networks and Quasi-Planar Segmentation**|Jingwen Wang et.al.|[2306.16585](http://arxiv.org/abs/2306.16585)|null|
|**2023-06-28**|**Point2Point : A Framework for Efficient Deep Learning on Hilbert sorted Point Clouds with applications in Spatio-Temporal Occupancy Prediction**|Athrva Atul Pandhare et.al.|[2306.16306](http://arxiv.org/abs/2306.16306)|null|
|**2023-06-20**|**Multi-Scale Occ: 4th Place Solution for CVPR 2023 3D Occupancy Prediction Challenge**|Yangyang Ding et.al.|[2306.11414](http://arxiv.org/abs/2306.11414)|null|
|**2023-06-16**|**PanoOcc: Unified Occupancy Representation for Camera-based 3D Panoptic Segmentation**|Yuqi Wang et.al.|[2306.10013](http://arxiv.org/abs/2306.10013)|**[link](https://github.com/robertwyq/panoocc)**|
|**2023-06-15**|**UniOcc: Unifying Vision-Centric 3D Occupancy Prediction with Geometric and Semantic Rendering**|Mingjie Pan et.al.|[2306.09117](http://arxiv.org/abs/2306.09117)|null|
|**2024-02-02**|**Motion Perceiver: Real-Time Occupancy Forecasting for Embedded Systems**|Bryce Ferenczi et.al.|[2306.08879](http://arxiv.org/abs/2306.08879)|**[link](https://github.com/5had3z/motion-perceiver)**|
|**2023-06-08**|**UAP-BEV: Uncertainty Aware Planning using Bird's Eye View generated from Surround Monocular Images**|Vikrant Dewangan et.al.|[2306.04939](http://arxiv.org/abs/2306.04939)|**[link](https://github.com/Vikr-182/UAP-BEV)**|
|**2024-01-20**|**GMMap: Memory-Efficient Continuous Occupancy Map Using Gaussian Mixture Model**|Peter Zhi Xuan Li et.al.|[2306.03740](http://arxiv.org/abs/2306.03740)|**[link](https://github.com/mit-lean/gmmap)**|
|**2023-05-31**|**Volume Feature Rendering for Fast Neural Radiance Field Reconstruction**|Kang Han et.al.|[2305.17916](http://arxiv.org/abs/2305.17916)|null|
|**2023-05-26**|**How To Not Train Your Dragon: Training-free Embodied Object Goal Navigation with Semantic Frontiers**|Junting Chen et.al.|[2305.16925](http://arxiv.org/abs/2305.16925)|null|
|**2024-01-11**|**BEV-IO: Enhancing Bird's-Eye-View 3D Detection with Instance Occupancy**|Zaibin Zhang et.al.|[2305.16829](http://arxiv.org/abs/2305.16829)|null|
|**2023-06-14**|**OVO: Open-Vocabulary Occupancy**|Zhiyu Tan et.al.|[2305.16133](http://arxiv.org/abs/2305.16133)|**[link](https://github.com/dzcgaara/OVO)**|
|**2023-05-25**|**Learning Occupancy for Monocular 3D Object Detection**|Liang Peng et.al.|[2305.15694](http://arxiv.org/abs/2305.15694)|**[link](https://github.com/spengliang/occupancym3d)**|
|**2023-05-24**|**OD-NeRF: Efficient Training of On-the-Fly Dynamic Neural Radiance Fields**|Zhiwen Yan et.al.|[2305.14831](http://arxiv.org/abs/2305.14831)|null|
|**2023-05-23**|**Exploiting Radio Fingerprints for Simultaneous Localization and Mapping**|Ran Liu et.al.|[2305.13635](http://arxiv.org/abs/2305.13635)|null|
|**2023-05-25**|**Deep Radar Inverse Sensor Models for Dynamic Occupancy Grid Maps**|Zihang Wei et.al.|[2305.12409](http://arxiv.org/abs/2305.12409)|null|
|**2023-05-15**|**GeoMAE: Masked Geometric Target Prediction for Self-supervised Point Cloud Pre-Training**|Xiaoyu Tian et.al.|[2305.08808](http://arxiv.org/abs/2305.08808)|**[link](https://github.com/tsinghua-mars-lab/geomae)**|
|**2023-08-30**|**Real-Time Joint Simulation of LiDAR Perception and Motion Planning for Automated Driving**|Zhanhong Huang et.al.|[2305.06966](http://arxiv.org/abs/2305.06966)|null|
|**2023-05-10**|**ProxMaP: Proximal Occupancy Map Prediction for Efficient Indoor Robot Navigation**|Vishnu Dutt Sharma et.al.|[2305.05519](http://arxiv.org/abs/2305.05519)|null|
|**2023-05-05**|**Occupancy Prediction-Guided Neural Planner for Autonomous Driving**|Haochen Liu et.al.|[2305.03303](http://arxiv.org/abs/2305.03303)|**[link](https://github.com/georgeliu233/opgp)**|
|**2023-12-13**|**Occ3D: A Large-Scale 3D Occupancy Prediction Benchmark for Autonomous Driving**|Xiaoyu Tian et.al.|[2304.14365](http://arxiv.org/abs/2304.14365)|**[link](https://github.com/Tsinghua-MARS-Lab/Occ3D)**|
|**2023-04-11**|**OccFormer: Dual-path Transformer for Vision-based 3D Semantic Occupancy Prediction**|Yunpeng Zhang et.al.|[2304.05316](http://arxiv.org/abs/2304.05316)|**[link](https://github.com/zhangyp15/occformer)**|
|**2023-08-23**|**Combined Registration and Fusion of Evidential Occupancy Grid Maps for Live Digital Twins of Traffic**|Raphael van Kempen et.al.|[2304.03578](http://arxiv.org/abs/2304.03578)|null|
|**2023-03-20**|**Dual-Weight Particle Filter for Radar-Based Dynamic Bayesian Grid Maps**|Max Peter Ronecker et.al.|[2303.11390](http://arxiv.org/abs/2303.11390)|null|
|**2023-08-16**|**Social Occlusion Inference with Vectorized Representation for Autonomous Driving**|Bochao Huang et.al.|[2303.10385](http://arxiv.org/abs/2303.10385)|null|
|**2023-08-27**|**SurroundOcc: Multi-Camera 3D Occupancy Prediction for Autonomous Driving**|Yi Wei et.al.|[2303.09551](http://arxiv.org/abs/2303.09551)|**[link](https://github.com/weiyithu/surroundocc)**|
|**2023-03-07**|**Deep Occupancy-Predictive Representations for Autonomous Driving**|Eivind Meyer et.al.|[2303.04218](http://arxiv.org/abs/2303.04218)|null|
|**2023-03-02**|**Grid-Centric Traffic Scenario Perception for Autonomous Driving: A Comprehensive Review**|Yining Shi et.al.|[2303.01212](http://arxiv.org/abs/2303.01212)|null|
|**2023-02-28**|**ROG-Map: An Efficient Robocentric Occupancy Grid Map for Large-scene and High-resolution LiDAR-based Motion Planning**|Yunfan Ren et.al.|[2302.14819](http://arxiv.org/abs/2302.14819)|**[link](https://github.com/hku-mars/rog-map)**|
|**2023-04-30**|**Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting**|Tarasha Khurana et.al.|[2302.13130](http://arxiv.org/abs/2302.13130)|**[link](https://github.com/tarashakhurana/4d-occ-forecasting)**|
|**2023-12-20**|**Accurate Gaussian-Process-based Distance Fields with applications to Echolocation and Mapping**|Cedric Le Gentil et.al.|[2302.13005](http://arxiv.org/abs/2302.13005)|null|

<p align=right>(<a href=#updated-on-20240508>back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/Vincentqyw/cv-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/Vincentqyw/cv-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/Vincentqyw/cv-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/Vincentqyw/cv-arxiv-daily/issues

