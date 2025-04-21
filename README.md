[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2025.04.21
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
|**2025-04-16**|**An Online Adaptation Method for Robust Depth Estimation and Visual Odometry in the Open World**|Xingwu Ji et.al.|[2504.11698](http://arxiv.org/abs/2504.11698)|**[link](https://github.com/jixingwu/sol-slam)**|
|**2025-04-03**|**MonoGS++: Fast and Accurate Monocular RGB Gaussian SLAM**|Renwu Li et.al.|[2504.02437](http://arxiv.org/abs/2504.02437)|null|
|**2025-04-02**|**ForestVO: Enhancing Visual Odometry in Forest Environments through ForestGlue**|Thomas Pritchard et.al.|[2504.01261](http://arxiv.org/abs/2504.01261)|**[link](https://github.com/aerialroboticsgroup/forest-vo)**|
|**2025-03-29**|**Incorporating GNSS Information with LIDAR-Inertial Odometry for Accurate Land-Vehicle Localization**|Jintao Cheng et.al.|[2503.23199](http://arxiv.org/abs/2503.23199)|null|
|**2025-04-03**|**Towards Mobile Sensing with Event Cameras on High-agility Resource-constrained Devices: A Survey**|Haoyang Wang et.al.|[2503.22943](http://arxiv.org/abs/2503.22943)|null|
|**2025-03-25**|**Scene-agnostic Pose Regression for Visual Localization**|Junwei Zheng et.al.|[2503.19543](http://arxiv.org/abs/2503.19543)|null|
|**2025-03-07**|**THE-SEAN: A Heart Rate Variation-Inspired Temporally High-Order Event-Based Visual Odometry with Self-Supervised Spiking Event Accumulation Networks**|Chaoran Xiong et.al.|[2503.05112](http://arxiv.org/abs/2503.05112)|null|
|**2025-03-06**|**MarsLGPR: Mars Rover Localization with Ground Penetrating Radar**|Anja Sheppard et.al.|[2503.04944](http://arxiv.org/abs/2503.04944)|null|
|**2025-03-06**|**Geometry-Constrained Monocular Scale Estimation Using Semantic Segmentation for Dynamic Scenes**|Hui Zhang et.al.|[2503.04235](http://arxiv.org/abs/2503.04235)|null|
|**2025-03-05**|**Direct Sparse Odometry with Continuous 3D Gaussian Maps for Indoor Environments**|Jie Deng et.al.|[2503.03373](http://arxiv.org/abs/2503.03373)|**[link](https://github.com/JD-hust/gs-dso)**|
|**2025-03-03**|**MUSt3R: Multi-view Network for Stereo 3D Reconstruction**|Yohann Cabon et.al.|[2503.01661](http://arxiv.org/abs/2503.01661)|null|
|**2025-03-04**|**DnD Filter: Differentiable State Estimation for Dynamic Systems using Diffusion Models**|Ziyu Wan et.al.|[2503.01274](http://arxiv.org/abs/2503.01274)|**[link](https://github.com/ziyunus/dndfilter)**|
|**2025-02-27**|**BEV-DWPVO: BEV-based Differentiable Weighted Procrustes for Low Scale-drift Monocular Visual Odometry on Ground**|Yufei Wei et.al.|[2502.20078](http://arxiv.org/abs/2502.20078)|null|
|**2025-02-26**|**SLAM in the Dark: Self-Supervised Learning of Pose, Depth and Loop-Closure from Thermal Images**|Yangfan Xu et.al.|[2502.18932](http://arxiv.org/abs/2502.18932)|null|
|**2025-02-19**|**Active Illumination for Visual Ego-Motion Estimation in the Dark**|Francesco Crocetti et.al.|[2502.13708](http://arxiv.org/abs/2502.13708)|null|
|**2025-02-19**|**pySLAM: An Open-Source, Modular, and Extensible Framework for SLAM**|Luigi Freda et.al.|[2502.11955](http://arxiv.org/abs/2502.11955)|**[link](https://github.com/luigifreda/pyslam)**|
|**2025-03-05**|**Vision-based Geo-Localization of Future Mars Rotorcraft in Challenging Illumination Conditions**|Dario Pisanti et.al.|[2502.09795](http://arxiv.org/abs/2502.09795)|null|
|**2025-02-12**|**LIR-LIVO: A Lightweight,Robust LiDAR/Vision/Inertial Odometry with Illumination-Resilient Deep Features**|Shujie Zhou et.al.|[2502.08676](http://arxiv.org/abs/2502.08676)|**[link](https://github.com/IF-A-CAT/LIR-LIVO)**|
|**2025-01-23**|**FAST-LIVO2 on Resource-Constrained Platforms: LiDAR-Inertial-Visual Odometry with Efficient Memory and Computation**|Bingyang Zhou et.al.|[2501.13876](http://arxiv.org/abs/2501.13876)|null|
|**2025-02-14**|**DynoSAM: Open-Source Smoothing and Mapping Framework for Dynamic SLAM**|Jesse Morris et.al.|[2501.11893](http://arxiv.org/abs/2501.11893)|**[link](https://github.com/acfr-rpg/dynosam)**|
|**2025-03-17**|**BRIGHT-VO: Brightness-Guided Hybrid Transformer for Visual Odometry with Multi-modality Refinement Module**|Dongzhihan Wang et.al.|[2501.08659](http://arxiv.org/abs/2501.08659)|null|
|**2025-04-07**|**MambaVO: Deep Visual Odometry Based on Sequential Matching Refinement and Training Smoothing**|Shuo Wang et.al.|[2412.20082](http://arxiv.org/abs/2412.20082)|null|
|**2025-03-08**|**Leveraging Consistent Spatio-Temporal Correspondence for Robust Visual Odometry**|Zhaoxing Zhang et.al.|[2412.16923](http://arxiv.org/abs/2412.16923)|null|
|**2024-12-18**|**4D Radar-Inertial Odometry based on Gaussian Modeling and Multi-Hypothesis Scan Matching**|Fernando Amodeo et.al.|[2412.13639](http://arxiv.org/abs/2412.13639)|**[link](https://github.com/robotics-upo/gaussian-rio)**|
|**2025-04-08**|**RoMeO: Robust Metric Visual Odometry**|Junda Cheng et.al.|[2412.11530](http://arxiv.org/abs/2412.11530)|null|
|**2024-12-12**|**eCARLA-scenes: A synthetically generated dataset for event-based optical flow prediction**|Jad Mansour et.al.|[2412.09209](http://arxiv.org/abs/2412.09209)|**[link](https://github.com/CIRS-Girona/ecarla-scenes)**|
|**2025-03-25**|**MCVO: A Generic Visual Odometry for Arbitrarily Arranged Multi-Cameras**|Huai Yu et.al.|[2412.03146](http://arxiv.org/abs/2412.03146)|**[link](https://github.com/junhaowang615/mcvo)**|
|**2024-12-04**|**An indoor DSO-based ceiling-vision odometry system for indoor industrial environments**|Abdelhak Bougouffa et.al.|[2412.02950](http://arxiv.org/abs/2412.02950)|null|
|**2024-12-17**|**InCrowd-VI: A Realistic Visual-Inertial Dataset for Evaluating SLAM in Indoor Pedestrian-Rich Spaces for Human Navigation**|Marziyeh Bamdad et.al.|[2411.14358](http://arxiv.org/abs/2411.14358)|**[link](https://github.com/banafshebamdad/InCrowd-VI)**|
|**2024-12-13**|**Robust Monocular Visual Odometry using Curriculum Learning**|Assaf Lahiany et.al.|[2411.13438](http://arxiv.org/abs/2411.13438)|null|
|**2024-11-15**|**BEV-ODOM: Reducing Scale Drift in Monocular Visual Odometry with BEV Representation**|Yufei Wei et.al.|[2411.10195](http://arxiv.org/abs/2411.10195)|null|
|**2024-11-24**|**Enhanced Monocular Visual Odometry with AR Poses and Integrated INS-GPS for Robust Localization in Urban Environments**|Ankit Shaw et.al.|[2411.08231](http://arxiv.org/abs/2411.08231)|null|
|**2024-11-07**|**MPVO: Motion-Prior based Visual Odometry for PointGoal Navigation**|Sayan Paul et.al.|[2411.04796](http://arxiv.org/abs/2411.04796)|null|
|**2024-10-30**|**LGU-SLAM: Learnable Gaussian Uncertainty Matching with Deformable Correlation Sampling for Deep Visual SLAM**|Yucheng Huang et.al.|[2410.23231](http://arxiv.org/abs/2410.23231)|**[link](https://github.com/uestc-nnlab/lgu-slam)**|
|**2024-10-29**|**LiVisSfM: Accurate and Robust Structure-from-Motion with LiDAR and Visual Cues**|Hanqing Jiang et.al.|[2410.22213](http://arxiv.org/abs/2410.22213)|null|
|**2025-03-03**|**ESVO2: Direct Visual-Inertial Odometry with Stereo Event Cameras**|Junkai Niu et.al.|[2410.09374](http://arxiv.org/abs/2410.09374)|**[link](https://github.com/nail-hnu/esvo2)**|
|**2025-03-25**|**IncEventGS: Pose-Free Gaussian Splatting from a Single Event Camera**|Jian Huang et.al.|[2410.08107](http://arxiv.org/abs/2410.08107)|**[link](https://github.com/wu-cvgl/inceventgs)**|
|**2024-09-20**|**Learning Visual Information Utility with PIXER**|Yash Turkar et.al.|[2409.13151](http://arxiv.org/abs/2409.13151)|null|
|**2025-02-24**|**ORB-SfMLearner: ORB-Guided Self-supervised Visual Odometry with Selective Online Adaptation**|Yanlin Jin et.al.|[2409.11692](http://arxiv.org/abs/2409.11692)|null|
|**2025-03-12**|**MAC-VO: Metrics-aware Covariance for Learning-based Stereo Visual Odometry**|Yuheng Qiu et.al.|[2409.09479](http://arxiv.org/abs/2409.09479)|null|
|**2025-01-29**|**GEVO: Memory-Efficient Monocular Visual Odometry Using Gaussians**|Dasong Gao et.al.|[2409.09295](http://arxiv.org/abs/2409.09295)|**[link](https://github.com/mit-lean/gevo)**|
|**2024-09-14**|**Panoramic Direct LiDAR-assisted Visual Odometry**|Zikang Yuan et.al.|[2409.09287](http://arxiv.org/abs/2409.09287)|**[link](https://github.com/ZikangYuan/panoramic_lidar_dso)**|
|**2024-09-02**|**Robust Vehicle Localization and Tracking in Rain using Street Maps**|Yu Xiang Tan et.al.|[2409.01038](http://arxiv.org/abs/2409.01038)|**[link](https://gitlab.com/marvl/map-fusion)**|
|**2024-12-23**|**Efficient Camera Exposure Control for Visual Odometry via Deep Reinforcement Learning**|Shuyang Zhang et.al.|[2408.17005](http://arxiv.org/abs/2408.17005)|**[link](https://github.com/shuyanguni/drl_exposure_ctrl)**|
|**2024-08-29**|**Creating a Segmented Pointcloud of Grapevines by Combining Multiple Viewpoints Through Visual Odometry**|Michael Adlerstein et.al.|[2408.16472](http://arxiv.org/abs/2408.16472)|null|
|**2024-08-28**|**Single-Photon 3D Imaging with Equi-Depth Photon Histograms**|Kaustubh Sadekar et.al.|[2408.16150](http://arxiv.org/abs/2408.16150)|null|
|**2024-08-28**|**ES-PTAM: Event-based Stereo Parallel Tracking and Mapping**|Suman Ghosh et.al.|[2408.15605](http://arxiv.org/abs/2408.15605)|**[link](https://github.com/tub-rip/es-ptam)**|
|**2024-08-28**|**FAST-LIVO2: Fast, Direct LiDAR-Inertial-Visual Odometry**|Chunran Zheng et.al.|[2408.14035](http://arxiv.org/abs/2408.14035)|**[link](https://github.com/hku-mars/fast-livo2)**|
|**2024-08-03**|**Deep Patch Visual SLAM**|Lahav Lipson et.al.|[2408.01654](http://arxiv.org/abs/2408.01654)|**[link](https://github.com/princeton-vl/dpvo)**|
|**2024-07-25**|**CodedVO: Coded Visual Odometry**|Sachin Shah et.al.|[2407.18240](http://arxiv.org/abs/2407.18240)|null|
|**2024-07-22**|**Reinforcement Learning Meets Visual Odometry**|Nico Messikommer et.al.|[2407.15626](http://arxiv.org/abs/2407.15626)|**[link](https://github.com/uzh-rpg/rl_vo)**|
|**2024-07-21**|**Semi-Supervised Pipe Video Temporal Defect Interval Localization**|Zhu Huang et.al.|[2407.15170](http://arxiv.org/abs/2407.15170)|null|
|**2024-07-18**|**Attenuation-Aware Weighted Optical Flow with Medium Transmission Map for Learning-based Visual Odometry in Underwater terrain**|Bach Nguyen Gia et.al.|[2407.13159](http://arxiv.org/abs/2407.13159)|**[link](https://github.com/bachzz/wflow-tartanvo)**|
|**2025-02-11**|**Is That Rain? Understanding Effects on Visual Odometry Performance for Autonomous UAVs and Efficient DNN-based Rain Classification at the Edge**|Andrea Albanese et.al.|[2407.12663](http://arxiv.org/abs/2407.12663)|null|
|**2024-07-01**|**Preserving Relative Localization of FoV-Limited Drone Swarm via Active Mutual Observation**|Lianjie Guo et.al.|[2407.01292](http://arxiv.org/abs/2407.01292)|**[link](https://github.com/zju-fast-lab/active-relative-localization)**|
|**2025-01-25**|**Imperative Learning: A Self-supervised Neuro-Symbolic Learning Framework for Robot Autonomy**|Chen Wang et.al.|[2406.16087](http://arxiv.org/abs/2406.16087)|null|
|**2024-06-16**|**Self-supervised Pretraining and Finetuning for Monocular Depth and Visual Odometry**|Boris Chidlovskii et.al.|[2406.11019](http://arxiv.org/abs/2406.11019)|null|
|**2024-06-12**|**From Variance to Veracity: Unbundling and Mitigating Gradient Variance in Differentiable Bundle Adjustment Layers**|Swaminathan Gurumurthy et.al.|[2406.07785](http://arxiv.org/abs/2406.07785)|**[link](https://github.com/swami1995/v2v)**|
|**2024-06-03**|**The Empirical Impact of Forgetting and Transfer in Continual Visual Odometry**|Paolo Cudrano et.al.|[2406.01797](http://arxiv.org/abs/2406.01797)|null|
|**2024-06-03**|**Self-Supervised Geometry-Guided Initialization for Robust Monocular Visual Odometry**|Takayuki Kanai et.al.|[2406.00929](http://arxiv.org/abs/2406.00929)|null|
|**2024-05-30**|**TAMBRIDGE: Bridging Frame-Centered Tracking and 3D Gaussian Splatting for Enhanced SLAM**|Peifeng Jiang et.al.|[2405.19614](http://arxiv.org/abs/2405.19614)|null|
|**2024-08-18**|**Advancements in Translation Accuracy for Stereo Visual-Inertial Initialization**|Han Song et.al.|[2405.15082](http://arxiv.org/abs/2405.15082)|null|
|**2024-06-08**|**EdgeLoc: A Communication-Adaptive Parallel System for Real-Time Localization in Infrastructure-Assisted Autonomous Driving**|Boyi Liu et.al.|[2405.12120](http://arxiv.org/abs/2405.12120)|null|
|**2024-09-10**|**MGS-SLAM: Monocular Sparse Tracking and Gaussian Mapping with Depth Smooth Regularization**|Pengcheng Zhu et.al.|[2405.06241](http://arxiv.org/abs/2405.06241)|null|
|**2024-05-07**|**Bayesian Simultaneous Localization and Multi-Lane Tracking Using Onboard Sensors and a SD Map**|Yuxuan Xia et.al.|[2405.04290](http://arxiv.org/abs/2405.04290)|null|
|**2024-05-07**|**IMU-Aided Event-based Stereo Visual Odometry**|Junkai Niu et.al.|[2405.04071](http://arxiv.org/abs/2405.04071)|**[link](https://github.com/nail-hnu/esvio_aa)**|
|**2024-04-27**|**An Attention-Based Deep Learning Architecture for Real-Time Monocular Visual Odometry: Applications to GPS-free Drone Navigation**|Olivier Brochu Dufour et.al.|[2404.17745](http://arxiv.org/abs/2404.17745)|null|
|**2024-04-26**|**Camera Motion Estimation from RGB-D-Inertial Scene Flow**|Samuel Cerezo et.al.|[2404.17251](http://arxiv.org/abs/2404.17251)|**[link](https://github.com/samuel-cerezo/SceneFlowFusion)**|
|**2024-04-23**|**Multi-Session SLAM with Differentiable Wide-Baseline Pose Optimization**|Lahav Lipson et.al.|[2404.15263](http://arxiv.org/abs/2404.15263)|**[link](https://github.com/princeton-vl/multislam_diffpose)**|
|**2024-04-18**|**SPOT: Point Cloud Based Stereo Visual Place Recognition for Similar and Opposing Viewpoints**|Spencer Carmichael et.al.|[2404.12339](http://arxiv.org/abs/2404.12339)|null|
|**2024-04-17**|**VBR: A Vision Benchmark in Rome**|Leonardo Brizi et.al.|[2404.11322](http://arxiv.org/abs/2404.11322)|**[link](https://github.com/rvp-group/vbr-devkit)**|
|**2024-04-14**|**Increasing SLAM Pose Accuracy by Ground-to-Satellite Image Registration**|Yanhao Zhang et.al.|[2404.09169](http://arxiv.org/abs/2404.09169)|**[link](https://github.com/yanhaozhang/slam-g2s-fusion)**|
|**2024-04-06**|**Salient Sparse Visual Odometry With Pose-Only Supervision**|Siyu Chen et.al.|[2404.04677](http://arxiv.org/abs/2404.04677)|null|
|**2024-03-25**|**A Comparative Analysis of Visual Odometry in Virtual and Real-World Railways Environments**|Gianluca D'Amico et.al.|[2403.17084](http://arxiv.org/abs/2403.17084)|null|
|**2024-03-19**|**On Designing Consistent Covariance Recovery from a Deep Learning Visual Odometry Engine**|Jagatpreet Singh Nir et.al.|[2403.13170](http://arxiv.org/abs/2403.13170)|null|
|**2024-03-18**|**The POLAR Traverse Dataset: A Dataset of Stereo Camera Images Simulating Traverses across Lunar Polar Terrain under Extreme Lighting Conditions**|Margaret Hansen et.al.|[2403.12194](http://arxiv.org/abs/2403.12194)|null|
|**2025-01-12**|**An Accurate and Real-time Relative Pose Estimation from Triple Point-line Images by Decoupling Rotation and Translation**|Zewen Xu et.al.|[2403.11639](http://arxiv.org/abs/2403.11639)|null|
|**2024-03-14**|**Visual Inertial Odometry using Focal Plane Binary Features (BIT-VIO)**|Matthew Lisondra et.al.|[2403.09882](http://arxiv.org/abs/2403.09882)|null|
|**2025-01-11**|**Splat-Nav: Safe Real-Time Robot Navigation in Gaussian Splatting Maps**|Timothy Chen et.al.|[2403.02751](http://arxiv.org/abs/2403.02751)|**[link](https://github.com/chengine/splatnav)**|
|**2024-03-02**|**Grid-based Fast and Structural Visual Odometry**|Zhang Zhihe et.al.|[2403.01110](http://arxiv.org/abs/2403.01110)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## BEV

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-16**|**Self-Supervised Traversability Learning with Online Prototype Adaptation for Off-Road Autonomous Driving**|Yafeng Bu et.al.|[2504.12109](http://arxiv.org/abs/2504.12109)|null|
|**2025-04-13**|**FastRSR: Efficient and Accurate Road Surface Reconstruction from Bird's Eye View**|Yuting Zhao et.al.|[2504.09535](http://arxiv.org/abs/2504.09535)|null|
|**2025-04-08**|**POD: Predictive Object Detection with Single-Frame FMCW LiDAR Point Cloud**|Yining Shi et.al.|[2504.05649](http://arxiv.org/abs/2504.05649)|null|
|**2025-04-07**|**TDFANet: Encoding Sequential 4D Radar Point Clouds Using Trajectory-Guided Deformable Feature Aggregation for Place Recognition**|Shouyi Lu et.al.|[2504.05103](http://arxiv.org/abs/2504.05103)|null|
|**2025-04-03**|**Attention-Aware Multi-View Pedestrian Tracking**|Reef Alturki et.al.|[2504.03047](http://arxiv.org/abs/2504.03047)|null|
|**2025-03-26**|**Switching on Antiferroelectrics**|G. Catalan et.al.|[2503.20423](http://arxiv.org/abs/2503.20423)|null|
|**2025-03-24**|**Predicting the Road Ahead: A Knowledge Graph based Foundation Model for Scene Understanding in Autonomous Driving**|Hongkuan Zhou et.al.|[2503.18730](http://arxiv.org/abs/2503.18730)|null|
|**2025-03-21**|**R2LDM: An Efficient 4D Radar Super-Resolution Framework Leveraging Diffusion Model**|Boyuan Zheng et.al.|[2503.17097](http://arxiv.org/abs/2503.17097)|null|
|**2025-03-26**|**MamBEV: Enabling State Space Models to Learn Birds-Eye-View Representations**|Hongyu Ke et.al.|[2503.13858](http://arxiv.org/abs/2503.13858)|**[link](https://github.com/amai-gsu/mambev)**|
|**2025-03-13**|**CoCMT: Communication-Efficient Cross-Modal Transformer for Collaborative Perception**|Rujia Wang et.al.|[2503.13504](http://arxiv.org/abs/2503.13504)|null|
|**2025-03-17**|**SparseAlign: A Fully Sparse Framework for Cooperative Object Detection**|Yunshuang Yuan et.al.|[2503.12982](http://arxiv.org/abs/2503.12982)|null|
|**2025-03-14**|**Aerial Vision-and-Language Navigation with Grid-based View Selection and Map Construction**|Ganlong Zhao et.al.|[2503.11091](http://arxiv.org/abs/2503.11091)|null|
|**2025-03-14**|**Active Learning from Scene Embeddings for End-to-End Autonomous Driving**|Wenhao Jiang et.al.|[2503.11062](http://arxiv.org/abs/2503.11062)|null|
|**2025-03-13**|**Unlocking Generalization Power in LiDAR Point Cloud Registration**|Zhenxuan Zeng et.al.|[2503.10149](http://arxiv.org/abs/2503.10149)|**[link](https://github.com/peakpang/ugp)**|
|**2025-03-11**|**SparseVoxFormer: Sparse Voxel-based Transformer for Multi-modal 3D Object Detection**|Hyeongseok Son et.al.|[2503.08092](http://arxiv.org/abs/2503.08092)|null|
|**2025-03-10**|**LEGO-Motion: Learning-Enhanced Grids with Occupancy Instance Modeling for Class-Agnostic Motion Prediction**|Kangan Qian et.al.|[2503.07367](http://arxiv.org/abs/2503.07367)|null|
|**2025-03-10**|**Controllable 3D Outdoor Scene Generation via Scene Graphs**|Yuheng Liu et.al.|[2503.07152](http://arxiv.org/abs/2503.07152)|**[link](https://github.com/yuhengliu02/control-3d-scene)**|
|**2025-03-05**|**Unified Human Localization and Trajectory Prediction with Monocular Vision**|Po-Chien Luan et.al.|[2503.03535](http://arxiv.org/abs/2503.03535)|**[link](https://github.com/vita-epfl/monotransmotion)**|
|**2025-03-04**|**TS-CGNet: Temporal-Spatial Fusion Meets Centerline-Guided Diffusion for BEV Mapping**|Xinying Hong et.al.|[2503.02578](http://arxiv.org/abs/2503.02578)|**[link](https://github.com/krabs-h/ts-cgnet)**|
|**2025-03-04**|**Diffusion-Based mmWave Radar Point Cloud Enhancement Driven by Range Images**|Ruixin Wu et.al.|[2503.02300](http://arxiv.org/abs/2503.02300)|null|
|**2025-03-06**|**Dur360BEV: A Real-world 360-degree Single Camera Dataset and Benchmark for Bird-Eye View Mapping in Autonomous Driving**|Wenke E et.al.|[2503.00675](http://arxiv.org/abs/2503.00675)|**[link](https://github.com/Tom-E-Durham/Dur360BEV)**|
|**2025-02-27**|**Visual Reasoning at Urban Intersections: FineTuning GPT-4o for Traffic Conflict Detection**|Sari Masri et.al.|[2502.20573](http://arxiv.org/abs/2502.20573)|null|
|**2025-02-27**|**Multi-Scale Neighborhood Occupancy Masked Autoencoder for Self-Supervised Learning in LiDAR Point Clouds**|Mohamed Abdelsamad et.al.|[2502.20316](http://arxiv.org/abs/2502.20316)|null|
|**2025-02-27**|**MITracker: Multi-View Integration for Visual Object Tracking**|Mengjie Xu et.al.|[2502.20111](http://arxiv.org/abs/2502.20111)|null|
|**2025-03-15**|**You Only Click Once: Single Point Weakly Supervised 3D Instance Segmentation for Autonomous Driving**|Guangfeng Jiang et.al.|[2502.19698](http://arxiv.org/abs/2502.19698)|null|
|**2025-02-26**|**BEV-LIO(LC): BEV Image Assisted LiDAR-Inertial Odometry with Loop Closure**|Haoxin Cai et.al.|[2502.19242](http://arxiv.org/abs/2502.19242)|**[link](https://github.com/hxca1/bev-lio-lc)**|
|**2025-02-21**|**Depth-aware Fusion Method based on Image and 4D Radar Spectrum for 3D Object Detection**|Yue Sun et.al.|[2502.15516](http://arxiv.org/abs/2502.15516)|null|
|**2025-04-10**|**RendBEV: Semantic Novel View Synthesis for Self-Supervised Bird's Eye View Segmentation**|Henrique Piñeiro Monteagudo et.al.|[2502.14792](http://arxiv.org/abs/2502.14792)|null|
|**2025-02-18**|**RobuRCDet: Enhancing Robustness of Radar-Camera Fusion in Bird's Eye View for 3D Object Detection**|Jingtong Yue et.al.|[2502.13071](http://arxiv.org/abs/2502.13071)|null|
|**2025-02-28**|**Range and Bird's Eye View Fused Cross-Modal Visual Place Recognition**|Jianyi Peng et.al.|[2502.11742](http://arxiv.org/abs/2502.11742)|**[link](https://github.com/cppcute-pm/RangeBEV)**|
|**2025-02-16**|**MC-BEVRO: Multi-Camera Bird Eye View Road Occupancy Detection for Traffic Monitoring**|Arpitsinh Vaghela et.al.|[2502.11287](http://arxiv.org/abs/2502.11287)|null|
|**2025-02-04**|**Improving Generalization Ability for 3D Object Detection by Learning Sparsity-invariant Features**|Hsin-Cheng Lu et.al.|[2502.02322](http://arxiv.org/abs/2502.02322)|**[link](https://github.com/tiffamy/3dod-lsf)**|
|**2025-01-24**|**STAMP: Scalable Task And Model-agnostic Collaborative Perception**|Xiangbo Gao et.al.|[2501.18616](http://arxiv.org/abs/2501.18616)|**[link](https://github.com/taco-group/stamp)**|
|**2025-01-30**|**Dual-BEV Nav: Dual-layer BEV-based Heuristic Path Planning for Robotic Navigation in Unstructured Outdoor Environments**|Jianfeng Zhang et.al.|[2501.18351](http://arxiv.org/abs/2501.18351)|null|
|**2025-01-28**|**SliceOcc: Indoor 3D Semantic Occupancy Prediction with Vertical Slice Representation**|Jianing Li et.al.|[2501.16684](http://arxiv.org/abs/2501.16684)|**[link](https://github.com/northsummer/sliceocc)**|
|**2025-01-16**|**ASTRA: A Scene-aware TRAnsformer-based model for trajectory prediction**|Izzeddin Teeti et.al.|[2501.09878](http://arxiv.org/abs/2501.09878)|null|
|**2025-01-15**|**Generative Planning with 3D-vision Language Pre-training for End-to-End Autonomous Driving**|Tengpeng Li et.al.|[2501.08861](http://arxiv.org/abs/2501.08861)|**[link](https://github.com/ltp1995/gpvl)**|
|**2025-01-14**|**Revisiting Birds Eye View Perception Models with Frozen Foundation Models: DINOv2 and Metric3Dv2**|Seamie Hayes et.al.|[2501.08118](http://arxiv.org/abs/2501.08118)|null|
|**2025-01-13**|**Efficiently Closing Loops in LiDAR-Based SLAM Using Point Cloud Density Maps**|Saurabh Gupta et.al.|[2501.07399](http://arxiv.org/abs/2501.07399)|null|
|**2025-01-12**|**"What's Happening"- A Human-centered Multimodal Interpreter Explaining the Actions of Autonomous Vehicles**|Xuewen Luo et.al.|[2501.05322](http://arxiv.org/abs/2501.05322)|null|
|**2025-01-09**|**AD-L-JEPA: Self-Supervised Spatial World Models with Joint Embedding Predictive Architecture for Autonomous Driving with LiDAR Data**|Haoran Zhu et.al.|[2501.04969](http://arxiv.org/abs/2501.04969)|**[link](https://github.com/haoranzhuexplorer/ad-l-jepa-release)**|
|**2025-01-09**|**Multidimensional integrable systems from contact geometry**|A. Sergyeyev et.al.|[2501.04474](http://arxiv.org/abs/2501.04474)|null|
|**2025-01-05**|**GCP: Guarded Collaborative Perception with Spatial-Temporal Aware Malicious Agent Detection**|Yihang Tao et.al.|[2501.02450](http://arxiv.org/abs/2501.02450)|null|
|**2025-03-11**|**GPT4Scene: Understand 3D Scenes from Videos with Vision-Language Models**|Zhangyang Qi et.al.|[2501.01428](http://arxiv.org/abs/2501.01428)|**[link](https://github.com/Qi-Zhangyang/GPT4Scene)**|
|**2024-12-30**|**TiGDistill-BEV: Multi-view BEV 3D Object Detection via Target Inner-Geometry Learning Distillation**|Shaoqing Xu et.al.|[2412.20911](http://arxiv.org/abs/2412.20911)|**[link](https://github.com/public-bots/tigdistill-bev)**|
|**2024-12-28**|**Geo-ConvGRU: Geographically Masked Convolutional Gated Recurrent Unit for Bird-Eye View Segmentation**|Guanglei Yang et.al.|[2412.20171](http://arxiv.org/abs/2412.20171)|null|
|**2025-03-26**|**TopoBDA: Towards Bezier Deformable Attention for Road Topology Understanding**|Muhammet Esat Kalfaoglu et.al.|[2412.18951](http://arxiv.org/abs/2412.18951)|null|
|**2024-12-24**|**Parallel Neural Computing for Scene Understanding from LiDAR Perception in Autonomous Racing**|Suwesh Prasad Sah et.al.|[2412.18165](http://arxiv.org/abs/2412.18165)|**[link](https://github.com/suwesh/parallel-perception-network)**|
|**2024-12-22**|**Anchor3DLane++: 3D Lane Detection via Sample-Adaptive Sparse 3D Anchor Regression**|Shaofei Huang et.al.|[2412.16889](http://arxiv.org/abs/2412.16889)|**[link](https://github.com/tusen-ai/anchor3dlane)**|
|**2024-12-18**|**TopView: Vectorising road users in a bird's eye view from uncalibrated street-level imagery with deep learning**|Mohamed R Ibrahim et.al.|[2412.16229](http://arxiv.org/abs/2412.16229)|null|
|**2025-02-04**|**A Black-Box Evaluation Framework for Semantic Robustness in Bird's Eye View Detection**|Fu Wang et.al.|[2412.13913](http://arxiv.org/abs/2412.13913)|**[link](https://github.com/trustai/robustbev)**|
|**2024-12-16**|**CP-Guard: Malicious Agent Detection and Defense in Collaborative Bird's Eye View Perception**|Senkang Hu et.al.|[2412.12000](http://arxiv.org/abs/2412.12000)|null|
|**2024-12-13**|**GaussianAD: Gaussian-Centric End-to-End Autonomous Driving**|Wenzhao Zheng et.al.|[2412.10371](http://arxiv.org/abs/2412.10371)|**[link](https://github.com/wzzheng/gaussianad)**|
|**2024-12-10**|**Fast Occupancy Network**|Mingjie Lu et.al.|[2412.07163](http://arxiv.org/abs/2412.07163)|null|
|**2024-12-02**|**Epipolar Attention Field Transformers for Bird's Eye View Semantic Segmentation**|Christian Witte et.al.|[2412.01595](http://arxiv.org/abs/2412.01595)|null|
|**2024-11-29**|**SpaRC: Sparse Radar-Camera Fusion for 3D Object Detection**|Philipp Wolters et.al.|[2411.19860](http://arxiv.org/abs/2411.19860)|null|
|**2024-11-22**|**TopoSD: Topology-Enhanced Lane Segment Perception with SDMap Prior**|Sen Yang et.al.|[2411.14751](http://arxiv.org/abs/2411.14751)|null|
|**2025-03-08**|**Video2BEV: Transforming Drone Videos to BEVs for Video-based Geo-localization**|Hao Ju et.al.|[2411.13610](http://arxiv.org/abs/2411.13610)|null|
|**2025-03-26**|**EVT: Efficient View Transformation for Multi-Modal 3D Object Detection**|Yongjin Lee et.al.|[2411.10715](http://arxiv.org/abs/2411.10715)|null|
|**2025-03-10**|**MTA: Multimodal Task Alignment for BEV Perception and Captioning**|Yunsheng Ma et.al.|[2411.10639](http://arxiv.org/abs/2411.10639)|null|
|**2024-11-15**|**BEV-ODOM: Reducing Scale Drift in Monocular Visual Odometry with BEV Representation**|Yufei Wei et.al.|[2411.10195](http://arxiv.org/abs/2411.10195)|null|
|**2024-11-12**|**Top-Down or Bottom-Up? Complexity Analyses of Synchronous Multiparty Session Types**|Thien Udomsrirungruang et.al.|[2411.07452](http://arxiv.org/abs/2411.07452)|null|
|**2024-11-11**|**Fast and Efficient Transformer-based Method for Bird's Eye View Instance Prediction**|Miguel Antunes-García et.al.|[2411.06851](http://arxiv.org/abs/2411.06851)|**[link](https://github.com/miguelag99/efficient-instance-prediction)**|
|**2024-11-19**|**LSSInst: Improving Geometric Modeling in LSS-Based BEV Perception with Instance Representation**|Weijie Ma et.al.|[2411.06173](http://arxiv.org/abs/2411.06173)|**[link](https://github.com/weijiemax/lssinst)**|
|**2024-10-31**|**Uncertainty Estimation for 3D Object Detection via Evidential Learning**|Nikita Durasov et.al.|[2410.23910](http://arxiv.org/abs/2410.23910)|null|
|**2025-04-10**|**PACER: Preference-conditioned All-terrain Costmap Generation**|Luisa Mao et.al.|[2410.23488](http://arxiv.org/abs/2410.23488)|null|
|**2024-10-28**|**BEVPose: Unveiling Scene Semantics through Pose-Guided Multi-Modal BEV Alignment**|Mehdi Hosseinzadeh et.al.|[2410.20969](http://arxiv.org/abs/2410.20969)|null|
|**2025-03-04**|**Evaluating the Robustness of LiDAR Point Cloud Tracking Against Adversarial Attack**|Shengjing Tian et.al.|[2410.20893](http://arxiv.org/abs/2410.20893)|null|
|**2024-10-21**|**Focus on BEV: Self-calibrated Cycle View Transformation for Monocular Birds-Eye-View Segmentation**|Jiawei Zhao et.al.|[2410.15932](http://arxiv.org/abs/2410.15932)|null|
|**2025-03-28**|**MambaBEV: An efficient 3D detection model with Mamba2**|Zihan You et.al.|[2410.12673](http://arxiv.org/abs/2410.12673)|null|
|**2024-10-14**|**ROA-BEV: 2D Region-Oriented Attention for BEV-based 3D Object**|Jiwei Chen et.al.|[2410.10298](http://arxiv.org/abs/2410.10298)|null|
|**2024-10-10**|**MGMapNet: Multi-Granularity Representation Learning for End-to-End Vectorized HD Map Construction**|Jing Yang et.al.|[2410.07733](http://arxiv.org/abs/2410.07733)|null|
|**2024-10-09**|**Progressive Multi-Modal Fusion for Robust 3D Object Detection**|Rohit Mohan et.al.|[2410.07475](http://arxiv.org/abs/2410.07475)|null|
|**2024-10-08**|**BEVLoc: Cross-View Localization and Matching via Birds-Eye-View Synthesis**|Christopher Klammer et.al.|[2410.06410](http://arxiv.org/abs/2410.06410)|**[link](https://github.com/rpl-cmu/bevloc)**|
|**2024-10-08**|**RNR-Nav: A Real-World Visual Navigation System Using Renderable Neural Radiance Maps**|Minsoo Kim et.al.|[2410.05621](http://arxiv.org/abs/2410.05621)|null|
|**2024-10-07**|**HE-Nav: A High-Performance and Efficient Navigation System for Aerial-Ground Robots in Cluttered Environments**|Junming Wang et.al.|[2410.05079](http://arxiv.org/abs/2410.05079)|null|
|**2024-10-03**|**Recent developments in relativistic hydrodynamic fluctuations**|Gokce Basar et.al.|[2410.02866](http://arxiv.org/abs/2410.02866)|null|
|**2024-11-22**|**MemFusionMap: Working Memory Fusion for Online Vectorized HD Map Construction**|Jingyu Song et.al.|[2409.18737](http://arxiv.org/abs/2409.18737)|null|
|**2024-09-26**|**CASPFormer: Trajectory Prediction from BEV Images with Deformable Attention**|Harsh Yadav et.al.|[2409.17790](http://arxiv.org/abs/2409.17790)|null|
|**2024-09-25**|**Real-World Data Inspired Interactive Connected Traffic Scenario Generation**|Junwei You et.al.|[2409.17429](http://arxiv.org/abs/2409.17429)|null|
|**2024-02-16**|**GIM: Learning Generalizable Image Matcher From Internet Videos**|Xuelun Shen et.al.|[2402.11095](http://arxiv.org/abs/2402.11095)|null|
|**2024-02-12**|**Collaborative Semantic Occupancy Prediction with Hybrid Feature Fusion in Connected Automated Vehicles**|Rui Song et.al.|[2402.07635](http://arxiv.org/abs/2402.07635)|null|
|**2024-02-11**|**Social Evolution of Published Text and The Emergence of Artificial Intelligence Through Large Language Models and The Problem of Toxicity and Bias**|Arifa Khan et.al.|[2402.07166](http://arxiv.org/abs/2402.07166)|null|
|**2024-02-08**|**uPLAM: Robust Panoptic Localization and Mapping Leveraging Perception Uncertainties**|Kshitij Sirohi et.al.|[2402.05840](http://arxiv.org/abs/2402.05840)|null|
|**2024-01-30**|**Pixel to Elevation: Learning to Predict Elevation Maps at Long Range using Images for Autonomous Offroad Navigation**|Chanyoung Chung et.al.|[2401.17484](http://arxiv.org/abs/2401.17484)|null|
|**2024-01-25**|**Unlocking Past Information: Temporal Embeddings in Cooperative Bird's Eye View Prediction**|Dominik Rößle et.al.|[2401.14325](http://arxiv.org/abs/2401.14325)|null|
|**2024-01-23**|**InverseMatrixVT3D: An Efficient Projection Matrix-Based Approach for 3D Occupancy Prediction**|Zhenxing Ming et.al.|[2401.12422](http://arxiv.org/abs/2401.12422)|**[link](https://github.com/danielming123/inversematrixvt3d)**|
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
|**2024-01-29**|**Advancements in 3D Lane Detection Using LiDAR Point Clouds: From Data Collection to Model Development**|Runkai Zhao et.al.|[2309.13596](http://arxiv.org/abs/2309.13596)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Gaussian Splatting

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-18**|**SLAM&Render: A Benchmark for the Intersection Between Neural Rendering, Gaussian Splatting and SLAM**|Samuel Cerezo et.al.|[2504.13713](http://arxiv.org/abs/2504.13713)|**[link](https://github.com/samuel-cerezo/SLAM-Render)**|
|**2025-04-18**|**Green Robotic Mixed Reality with Gaussian Splatting**|Chenxuan Liu et.al.|[2504.13697](http://arxiv.org/abs/2504.13697)|null|
|**2025-04-18**|**EG-Gaussian: Epipolar Geometry and Graph Network Enhanced 3D Gaussian Splatting**|Beizhen Zhao et.al.|[2504.13540](http://arxiv.org/abs/2504.13540)|null|
|**2025-04-17**|**Volume Encoding Gaussians: Transfer Function-Agnostic 3D Gaussians for Volume Rendering**|Landon Dyken et.al.|[2504.13339](http://arxiv.org/abs/2504.13339)|null|
|**2025-04-16**|**BEV-GS: Feed-forward Gaussian Splatting in Bird's-Eye-View for Road Reconstruction**|Wenhua Wu et.al.|[2504.13207](http://arxiv.org/abs/2504.13207)|null|
|**2025-04-15**|**EDGS: Eliminating Densification for Efficient Convergence of 3DGS**|Dmytro Kotovenko et.al.|[2504.13204](http://arxiv.org/abs/2504.13204)|null|
|**2025-04-17**|**Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation**|Sizhe Yang et.al.|[2504.13175](http://arxiv.org/abs/2504.13175)|null|
|**2025-04-18**|**ODHSR: Online Dense 3D Reconstruction of Humans and Scenes from Monocular Videos**|Zetong Zhang et.al.|[2504.13167](http://arxiv.org/abs/2504.13167)|null|
|**2025-04-17**|**Digital Twin Generation from Visual Data: A Survey**|Andrew Melnik et.al.|[2504.13159](http://arxiv.org/abs/2504.13159)|null|
|**2025-04-17**|**Training-Free Hierarchical Scene Understanding for Gaussian Splatting with Superpoint Graphs**|Shaohui Dai et.al.|[2504.13153](http://arxiv.org/abs/2504.13153)|**[link](https://github.com/atrovast/thgs)**|
|**2025-04-17**|**CompGS++: Compressed Gaussian Splatting for Static and Dynamic Scene Representation**|Xiangrui Liu et.al.|[2504.13022](http://arxiv.org/abs/2504.13022)|null|
|**2025-04-17**|**GSAC: Leveraging Gaussian Splatting for Photorealistic Avatar Creation with Unity Integration**|Rendong Zhang et.al.|[2504.12999](http://arxiv.org/abs/2504.12999)|null|
|**2025-04-17**|**Second-order Optimization of Gaussian Splats with Importance Sampling**|Hamza Pehlivan et.al.|[2504.12905](http://arxiv.org/abs/2504.12905)|null|
|**2025-04-17**|**AAA-Gaussians: Anti-Aliased and Artifact-Free 3D Gaussian Rendering**|Michael Steiner et.al.|[2504.12811](http://arxiv.org/abs/2504.12811)|null|
|**2025-04-17**|**CAGE-GS: High-fidelity Cage Based 3D Gaussian Splatting Deformation**|Yifei Tong et.al.|[2504.12800](http://arxiv.org/abs/2504.12800)|null|
|**2025-04-17**|**TSGS: Improving Gaussian Splatting for Transparent Surface Reconstruction via Normal and De-lighting Priors**|Mingwei Li et.al.|[2504.12799](http://arxiv.org/abs/2504.12799)|null|
|**2025-04-17**|**ARAP-GS: Drag-driven As-Rigid-As-Possible 3D Gaussian Splatting Editing with Diffusion Prior**|Xiao Han et.al.|[2504.12788](http://arxiv.org/abs/2504.12788)|null|
|**2025-04-16**|**CAGS: Open-Vocabulary 3D Scene Understanding with Context-Aware Gaussian Splatting**|Wei Sun et.al.|[2504.11893](http://arxiv.org/abs/2504.11893)|null|
|**2025-04-16**|**3DAffordSplat: Efficient Affordance Reasoning with 3D Gaussians**|Zeming Wei et.al.|[2504.11218](http://arxiv.org/abs/2504.11218)|**[link](https://github.com/hcplab-sysu/3daffordsplat)**|
|**2025-04-15**|**Easy3D: A Simple Yet Effective Method for 3D Interactive Segmentation**|Andrea Simonelli et.al.|[2504.11024](http://arxiv.org/abs/2504.11024)|null|
|**2025-04-15**|**3D Gabor Splatting: Reconstruction of High-frequency Surface Texture using Gabor Noise**|Haato Watanabe et.al.|[2504.11003](http://arxiv.org/abs/2504.11003)|null|
|**2025-04-17**|**GaSLight: Gaussian Splats for Spatially-Varying Lighting in HDR**|Christophe Bolduc et.al.|[2504.10809](http://arxiv.org/abs/2504.10809)|null|
|**2025-04-14**|**DNF-Avatar: Distilling Neural Fields for Real-time Animatable Avatar Relighting**|Zeren Jiang et.al.|[2504.10486](http://arxiv.org/abs/2504.10486)|null|
|**2025-04-15**|**LL-Gaussian: Low-Light Scene Reconstruction and Enhancement via Gaussian Splatting for Novel View Synthesis**|Hao Sun et.al.|[2504.10331](http://arxiv.org/abs/2504.10331)|null|
|**2025-04-14**|**ESCT3D: Efficient and Selectively Controllable Text-Driven 3D Content Generation with Gaussian Splatting**|Huiqi Wu et.al.|[2504.10316](http://arxiv.org/abs/2504.10316)|null|
|**2025-04-14**|**EBAD-Gaussian: Event-driven Bundle Adjusted Deblur Gaussian Splatting**|Yufei Deng et.al.|[2504.10012](http://arxiv.org/abs/2504.10012)|null|
|**2025-04-16**|**GaussVideoDreamer: 3D Scene Generation with Video Diffusion and Inconsistency-Aware Gaussian Splatting**|Junlin Hao et.al.|[2504.10001](http://arxiv.org/abs/2504.10001)|null|
|**2025-04-14**|**MCBlock: Boosting Neural Radiance Field Training Speed by MCTS-based Dynamic-Resolution Ray Sampling**|Yunpeng Tan et.al.|[2504.09878](http://arxiv.org/abs/2504.09878)|null|
|**2025-04-13**|**TextSplat: Text-Guided Semantic Fusion for Generalizable Gaussian Splatting**|Zhicong Wu et.al.|[2504.09588](http://arxiv.org/abs/2504.09588)|null|
|**2025-04-13**|**DropoutGS: Dropping Out Gaussians for Better Sparse-view Rendering**|Yexing Xu et.al.|[2504.09491](http://arxiv.org/abs/2504.09491)|null|
|**2025-04-12**|**A Constrained Optimization Approach for Gaussian Splatting from Coarsely-posed Images and Noisy Lidar Point Clouds**|Jizong Peng et.al.|[2504.09129](http://arxiv.org/abs/2504.09129)|null|
|**2025-04-12**|**BIGS: Bimanual Category-agnostic Interaction Reconstruction from Monocular Videos via 3D Gaussian Splatting**|Jeongwan On et.al.|[2504.09097](http://arxiv.org/abs/2504.09097)|null|
|**2025-04-12**|**You Need a Transition Plane: Bridging Continuous Panoramic 3D Reconstruction with Perspective Gaussian Splatting**|Zhijie Shen et.al.|[2504.09062](http://arxiv.org/abs/2504.09062)|null|
|**2025-04-15**|**BlockGaussian: Efficient Large-Scale Scene Novel View Synthesis via Adaptive Block-Based Gaussian Splatting**|Yongchang Wu et.al.|[2504.09048](http://arxiv.org/abs/2504.09048)|**[link](https://github.com/sunshinewyc/blockgaussian)**|
|**2025-04-11**|**FMLGS: Fast Multilevel Language Embedded Gaussians for Part-level Interactive Agents**|Xin Tan et.al.|[2504.08581](http://arxiv.org/abs/2504.08581)|null|
|**2025-04-11**|**Cut-and-Splat: Leveraging Gaussian Splatting for Synthetic Data Generation**|Bram Vanherle et.al.|[2504.08473](http://arxiv.org/abs/2504.08473)|**[link](https://github.com/edm-research/cut-and-splat)**|
|**2025-04-11**|**In-2-4D: Inbetweening from Two Single-View Images to 4D Generation**|Sauradip Nag et.al.|[2504.08366](http://arxiv.org/abs/2504.08366)|null|
|**2025-04-10**|**ContrastiveGaussian: High-Fidelity 3D Generation with Contrastive Learning and Gaussian Splatting**|Junbang Liu et.al.|[2504.08100](http://arxiv.org/abs/2504.08100)|**[link](https://github.com/yanllan-ljb/contrastivegaussian)**|
|**2025-04-10**|**InteractAvatar: Modeling Hand-Face Interaction in Photorealistic Avatars with Deformable Gaussians**|Kefan Chen et.al.|[2504.07949](http://arxiv.org/abs/2504.07949)|null|
|**2025-04-10**|**View-Dependent Uncertainty Estimation of 3D Gaussian Splatting**|Chenyu Han et.al.|[2504.07370](http://arxiv.org/abs/2504.07370)|null|
|**2025-04-09**|**Wheat3DGS: In-field 3D Reconstruction, Instance Segmentation and Phenotyping of Wheat Heads with Gaussian Splatting**|Daiwei Zhang et.al.|[2504.06978](http://arxiv.org/abs/2504.06978)|null|
|**2025-04-09**|**IAAO: Interactive Affordance Learning for Articulated Objects in 3D Environments**|Can Zhang et.al.|[2504.06827](http://arxiv.org/abs/2504.06827)|null|
|**2025-04-09**|**SVG-IR: Spatially-Varying Gaussian Splatting for Inverse Rendering**|Hanxiao Sun et.al.|[2504.06815](http://arxiv.org/abs/2504.06815)|null|
|**2025-04-09**|**GSta: Efficient Training Scheme with Siestaed Gaussians for Monocular 3D Scene Reconstruction**|Anil Armagan et.al.|[2504.06716](http://arxiv.org/abs/2504.06716)|null|
|**2025-04-09**|**Collision avoidance from monocular vision trained with novel view synthesis**|Valentin Tordjman--Levavasseur et.al.|[2504.06651](http://arxiv.org/abs/2504.06651)|null|
|**2025-04-10**|**Stochastic Ray Tracing of 3D Transparent Gaussians**|Xin Sun et.al.|[2504.06598](http://arxiv.org/abs/2504.06598)|null|
|**2025-04-08**|**Micro-splatting: Maximizing Isotropic Constraints for Refined Optimization in 3D Gaussian Splatting**|Jee Won Lee et.al.|[2504.05740](http://arxiv.org/abs/2504.05740)|null|
|**2025-04-07**|**View-Dependent Deformation Fields for 2D Editing of 3D Models**|Martin El Mqirmi et.al.|[2504.05544](http://arxiv.org/abs/2504.05544)|null|
|**2025-04-07**|**L3GS: Layered 3D Gaussian Splats for Efficient 3D Scene Delivery**|Yi-Zhen Tsai et.al.|[2504.05517](http://arxiv.org/abs/2504.05517)|**[link](https://github.com/mavens-lab/layered_3d_gaussian_splats)**|
|**2025-04-07**|**Let it Snow! Animating Static Gaussian Scenes With Dynamic Weather Effects**|Gal Fiebelman et.al.|[2504.05296](http://arxiv.org/abs/2504.05296)|null|
|**2025-04-07**|**PanoDreamer: Consistent Text to 360-Degree Scene Generation**|Zhexiao Xiong et.al.|[2504.05152](http://arxiv.org/abs/2504.05152)|null|
|**2025-04-16**|**3D Gaussian Particle Approximation of VDB Datasets: A Study for Scientific Visualization**|Isha Sharma et.al.|[2504.04857](http://arxiv.org/abs/2504.04857)|null|
|**2025-04-07**|**Embracing Dynamics: Dynamics-aware 4D Gaussian Splatting SLAM**|Zhicong Sun et.al.|[2504.04844](http://arxiv.org/abs/2504.04844)|**[link](https://github.com/zhicongsun/d4dgs-slam)**|
|**2025-04-07**|**DeclutterNeRF: Generative-Free 3D Scene Recovery for Occlusion Removal**|Wanzhou Liu et.al.|[2504.04679](http://arxiv.org/abs/2504.04679)|null|
|**2025-04-06**|**Tool-as-Interface: Learning Robot Policies from Human Tool Usage through Imitation Learning**|Haonan Chen et.al.|[2504.04612](http://arxiv.org/abs/2504.04612)|null|
|**2025-04-06**|**Thermoxels: a voxel-based method to generate simulation-ready 3D thermal models**|Etienne Chassaing et.al.|[2504.04448](http://arxiv.org/abs/2504.04448)|null|
|**2025-04-05**|**3R-GS: Best Practice in Optimizing Camera Poses Along with 3DGS**|Zhisheng Huang et.al.|[2504.04294](http://arxiv.org/abs/2504.04294)|null|
|**2025-04-05**|**Interpretable Single-View 3D Gaussian Splatting using Unsupervised Hierarchical Disentangled Representation Learning**|Yuyang Zhang et.al.|[2504.04190](http://arxiv.org/abs/2504.04190)|null|
|**2025-04-04**|**WildGS-SLAM: Monocular Gaussian Splatting SLAM in Dynamic Environments**|Jianhao Zheng et.al.|[2504.03886](http://arxiv.org/abs/2504.03886)|null|
|**2025-04-04**|**HumanDreamer-X: Photorealistic Single-image Human Avatars Reconstruction via Gaussian Restoration**|Boyuan Wang et.al.|[2504.03536](http://arxiv.org/abs/2504.03536)|null|
|**2025-04-08**|**Compressing 3D Gaussian Splatting by Noise-Substituted Vector Quantization**|Haishan Wang et.al.|[2504.03059](http://arxiv.org/abs/2504.03059)|**[link](https://github.com/aaltoml/nsvqgs)**|
|**2025-04-03**|**MonoGS++: Fast and Accurate Monocular RGB Gaussian SLAM**|Renwu Li et.al.|[2504.02437](http://arxiv.org/abs/2504.02437)|null|
|**2025-04-03**|**ConsDreamer: Advancing Multi-View Consistency for Zero-Shot Text-to-3D Generation**|Yuan Zhou et.al.|[2504.02316](http://arxiv.org/abs/2504.02316)|**[link](https://github.com/GAInuist/ConsDreamer)**|
|**2025-04-03**|**Digital-twin imaging based on descattering Gaussian splatting**|Suguru Shimomura et.al.|[2504.02278](http://arxiv.org/abs/2504.02278)|null|
|**2025-04-02**|**UAVTwin: Neural Digital Twins for UAVs using Gaussian Splatting**|Jaehoon Choi et.al.|[2504.02158](http://arxiv.org/abs/2504.02158)|null|
|**2025-04-02**|**WorldPrompter: Traversable Text-to-Scene Generation**|Zhaoyang Zhang et.al.|[2504.02045](http://arxiv.org/abs/2504.02045)|null|
|**2025-04-02**|**Diffusion-Guided Gaussian Splatting for Large-Scale Unconstrained 3D Reconstruction and Novel View Synthesis**|Niluthpol Chowdhury Mithun et.al.|[2504.01960](http://arxiv.org/abs/2504.01960)|null|
|**2025-04-03**|**Toward Real-world BEV Perception: Depth Uncertainty Estimation via Gaussian Splatting**|Shu-Wei Lu et.al.|[2504.01957](http://arxiv.org/abs/2504.01957)|null|
|**2025-04-02**|**BOGausS: Better Optimized Gaussian Splatting**|Stéphane Pateux et.al.|[2504.01844](http://arxiv.org/abs/2504.01844)|null|
|**2025-04-09**|**FIORD: A Fisheye Indoor-Outdoor Dataset with LIDAR Ground Truth for 3D Scene Reconstruction and Benchmarking**|Ulas Gunes et.al.|[2504.01732](http://arxiv.org/abs/2504.01732)|null|
|**2025-04-02**|**FlowR: Flowing from Sparse to Dense 3D Reconstructions**|Tobias Fischer et.al.|[2504.01647](http://arxiv.org/abs/2504.01647)|null|
|**2025-04-02**|**3DBonsai: Structure-Aware Bonsai Modeling Using Conditioned 3D Gaussian Splatting**|Hao Wu et.al.|[2504.01619](http://arxiv.org/abs/2504.01619)|null|
|**2025-04-02**|**RealityAvatar: Towards Realistic Loose Clothing Modeling in Animatable 3D Gaussian Avatars**|Yahui Li et.al.|[2504.01559](http://arxiv.org/abs/2504.01559)|null|
|**2025-04-02**|**High-fidelity 3D Object Generation from Single Image with RGBN-Volume Gaussian Reconstruction Model**|Yiyang Shen et.al.|[2504.01512](http://arxiv.org/abs/2504.01512)|null|
|**2025-04-02**|**Luminance-GS: Adapting 3D Gaussian Splatting to Challenging Lighting Conditions with View-Adaptive Curve Adjustment**|Ziteng Cui et.al.|[2504.01503](http://arxiv.org/abs/2504.01503)|**[link](https://github.com/cuiziteng/Luminance-GS)**|
|**2025-04-02**|**3D Gaussian Inverse Rendering with Approximated Global Illumination**|Zirui Wu et.al.|[2504.01358](http://arxiv.org/abs/2504.01358)|null|
|**2025-04-01**|**DropGaussian: Structural Regularization for Sparse-view Gaussian Splatting**|Hyunwoo Park et.al.|[2504.00773](http://arxiv.org/abs/2504.00773)|null|
|**2025-04-01**|**UnIRe: Unsupervised Instance Decomposition for Dynamic Urban Scene Reconstruction**|Yunxuan Mao et.al.|[2504.00763](http://arxiv.org/abs/2504.00763)|null|
|**2025-04-01**|**Monocular and Generalizable Gaussian Talking Head Animation**|Shengjie Gong et.al.|[2504.00665](http://arxiv.org/abs/2504.00665)|null|
|**2025-04-01**|**Robust LiDAR-Camera Calibration with 2D Gaussian Splatting**|Shuyi Zhou et.al.|[2504.00525](http://arxiv.org/abs/2504.00525)|**[link](https://github.com/shuyizhou495/robustcalibration)**|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Registration

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-09**|**A Pointcloud Registration Framework for Relocalization in Subterranean Environments**|David Akhihiero et.al.|[2504.07231](http://arxiv.org/abs/2504.07231)|null|
|**2024-12-08**|**AC-LIO: Towards Asymptotic and Consistent Convergence in LiDAR-Inertial Odometry**|Tianxiang Zhang et.al.|[2412.05873](http://arxiv.org/abs/2412.05873)|null|
|**2024-10-16**|**NAR-*ICP: Neural Execution of Classical ICP-based Pointcloud Registration Algorithms**|Efimia Panagiotaki et.al.|[2410.11031](http://arxiv.org/abs/2410.11031)|null|
|**2024-10-03**|**LiDAR Inertial Odometry And Mapping Using Learned Registration-Relevant Features**|Zihao Dong et.al.|[2410.02961](http://arxiv.org/abs/2410.02961)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Localization

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-16**|**Diffusion Based Robust LiDAR Place Recognition**|Benjamin Krummenacher et.al.|[2504.12412](http://arxiv.org/abs/2504.12412)|null|
|**2025-04-15**|**Visual Re-Ranking with Non-Visual Side Information**|Gustav Hanning et.al.|[2504.11134](http://arxiv.org/abs/2504.11134)|**[link](https://github.com/ghanning/gcsa)**|
|**2025-04-14**|**Focus on Local: Finding Reliable Discriminative Regions for Visual Place Recognition**|Changwei Wang et.al.|[2504.09881](http://arxiv.org/abs/2504.09881)|null|
|**2025-04-11**|**HAL-NeRF: High Accuracy Localization Leveraging Neural Radiance Fields**|Asterios Reppas et.al.|[2504.08901](http://arxiv.org/abs/2504.08901)|null|
|**2025-04-11**|**PNE-SGAN: Probabilistic NDT-Enhanced Semantic Graph Attention Network for LiDAR Loop Closure Detection**|Xiong Li et.al.|[2504.08280](http://arxiv.org/abs/2504.08280)|null|
|**2025-04-09**|**A Pointcloud Registration Framework for Relocalization in Subterranean Environments**|David Akhihiero et.al.|[2504.07231](http://arxiv.org/abs/2504.07231)|null|
|**2025-04-08**|**To Match or Not to Match: Revisiting Image Matching for Reliable Visual Place Recognition**|Davide Sferrazza et.al.|[2504.06116](http://arxiv.org/abs/2504.06116)|**[link](https://github.com/FarInHeight/To-Match-or-Not-to-Match)**|
|**2025-04-07**|**TDFANet: Encoding Sequential 4D Radar Point Clouds Using Trajectory-Guided Deformable Feature Aggregation for Place Recognition**|Shouyi Lu et.al.|[2504.05103](http://arxiv.org/abs/2504.05103)|null|
|**2025-04-06**|**Re-thinking Temporal Search for Long-Form Video Understanding**|Jinhui Ye et.al.|[2504.02259](http://arxiv.org/abs/2504.02259)|**[link](https://github.com/longvideohaystack/tstar)**|
|**2025-04-02**|**A Chefs KISS -- Utilizing semantic information in both ICP and SLAM framework**|Sven Ochs et.al.|[2504.02086](http://arxiv.org/abs/2504.02086)|null|
|**2025-03-31**|**LiM-Loc: Visual Localization with Dense and Accurate 3D Reference Maps Directly Corresponding 2D Keypoints to 3D LiDAR Point Clouds**|Masahiko Tsuji et.al.|[2503.23664](http://arxiv.org/abs/2503.23664)|null|
|**2025-03-27**|**UGNA-VPR: A Novel Training Paradigm for Visual Place Recognition Based on Uncertainty-Guided NeRF Augmentation**|Yehui Shen et.al.|[2503.21338](http://arxiv.org/abs/2503.21338)|**[link](https://github.com/nubot-nudt/ugna-vpr)**|
|**2025-03-25**|**Scene-agnostic Pose Regression for Visual Localization**|Junwei Zheng et.al.|[2503.19543](http://arxiv.org/abs/2503.19543)|null|
|**2025-04-15**|**Text-Driven 3D Lidar Place Recognition for Autonomous Driving**|Tianyi Shang et.al.|[2503.18035](http://arxiv.org/abs/2503.18035)|null|
|**2025-03-23**|**Selecting and Pruning: A Differentiable Causal Sequentialized State-Space Model for Two-View Correspondence Learning**|Xiang Fang et.al.|[2503.17938](http://arxiv.org/abs/2503.17938)|null|
|**2025-03-21**|**Autonomous Exploration-Based Precise Mapping for Mobile Robots through Stepwise and Consistent Motions**|Muhua Zhang et.al.|[2503.17005](http://arxiv.org/abs/2503.17005)|null|
|**2025-03-18**|**3D Densification for Multi-Map Monocular VSLAM in Endoscopy**|X. Anadón et.al.|[2503.14346](http://arxiv.org/abs/2503.14346)|null|
|**2025-03-18**|**A-SCoRe: Attention-based Scene Coordinate Regression for wide-ranging scenarios**|Huy-Hoang Bui et.al.|[2503.13982](http://arxiv.org/abs/2503.13982)|**[link](https://github.com/ais-lab/a-score)**|
|**2025-03-17**|**Multi-Platform Teach-and-Repeat Navigation by Visual Place Recognition Based on Deep-Learned Local Features**|Václav Truhlařík et.al.|[2503.13090](http://arxiv.org/abs/2503.13090)|null|
|**2025-03-16**|**ResLPR: A LiDAR Data Restoration Network and Benchmark for Robust Place Recognition Against Weather Corruptions**|Wenqing Kuang et.al.|[2503.12350](http://arxiv.org/abs/2503.12350)|null|
|**2025-03-14**|**L2RSI: Cross-view LiDAR-based Place Recognition for Large-scale Urban Scenes via Remote Sensing Imagery**|Ziwei Shi et.al.|[2503.11245](http://arxiv.org/abs/2503.11245)|null|
|**2025-03-12**|**Exploring the best way for UAV visual localization under Low-altitude Multi-view Observation Condition: a Benchmark**|Yibin Ye et.al.|[2503.10692](http://arxiv.org/abs/2503.10692)|**[link](https://github.com/uav-avl/benchmark)**|
|**2025-03-11**|**CQVPR: Landmark-aware Contextual Queries for Visual Place Recognition**|Dongyue Li et.al.|[2503.08170](http://arxiv.org/abs/2503.08170)|null|
|**2025-03-21**|**HOTFormerLoc: Hierarchical Octree Transformer for Versatile Lidar Place Recognition Across Ground and Aerial Views**|Ethan Griffiths et.al.|[2503.08140](http://arxiv.org/abs/2503.08140)|null|
|**2025-03-10**|**Improving Visual Place Recognition with Sequence-Matching Receptiveness Prediction**|Somayeh Hussaini et.al.|[2503.06840](http://arxiv.org/abs/2503.06840)|null|
|**2025-03-30**|**StructVPR++: Distill Structural and Semantic Knowledge with Weighting Samples for Visual Place Recognition**|Yanqing Shen et.al.|[2503.06601](http://arxiv.org/abs/2503.06601)|**[link](https://github.com/syqlyx/StructVPR)**|
|**2025-03-09**|**TextInPlace: Indoor Visual Place Recognition in Repetitive Structures with Scene Text Spotting and Verification**|Huaqi Tao et.al.|[2503.06501](http://arxiv.org/abs/2503.06501)|null|
|**2025-03-08**|**NeuraLoc: Visual Localization in Neural Implicit Map with Dual Complementary Features**|Hongjia Zhai et.al.|[2503.06117](http://arxiv.org/abs/2503.06117)|null|
|**2025-03-06**|**ForestLPR: LiDAR Place Recognition in Forests Attentioning Multiple BEV Density Images**|Yanqing Shen et.al.|[2503.04475](http://arxiv.org/abs/2503.04475)|**[link](https://github.com/shenyanqing1105/ForestLPR-CVPR2025)**|
|**2025-03-06**|**Geometry-Constrained Monocular Scale Estimation Using Semantic Segmentation for Dynamic Scenes**|Hui Zhang et.al.|[2503.04235](http://arxiv.org/abs/2503.04235)|null|
|**2025-03-06**|**Image-Based Relocalization and Alignment for Long-Term Monitoring of Dynamic Underwater Environments**|Beverley Gorry et.al.|[2503.04096](http://arxiv.org/abs/2503.04096)|**[link](https://github.com/bev-gorry/underloc)**|
|**2025-03-05**|**REGRACE: A Robust and Efficient Graph-based Re-localization Algorithm using Consistency Evaluation**|Débora N. P. Oliveira et.al.|[2503.03599](http://arxiv.org/abs/2503.03599)|null|
|**2025-03-20**|**CMMLoc: Advancing Text-to-PointCloud Localization with Cauchy-Mixture-Model Based Framework**|Yanlong Xu et.al.|[2503.02593](http://arxiv.org/abs/2503.02593)|**[link](https://github.com/kevin301342/cmmloc)**|
|**2025-03-04**|**TeTRA-VPR: A Ternary Transformer Approach for Compact Visual Place Recognition**|Oliver Grainge et.al.|[2503.02511](http://arxiv.org/abs/2503.02511)|null|
|**2025-03-04**|**Introspective Loop Closure for SLAM with 4D Imaging Radar**|Maximilian Hilger et.al.|[2503.02383](http://arxiv.org/abs/2503.02383)|null|
|**2025-03-04**|**Continual Multi-Robot Learning from Black-Box Visual Place Recognition Models**|Kenta Tsukahara et.al.|[2503.02256](http://arxiv.org/abs/2503.02256)|null|
|**2025-03-20**|**AirRoom: Objects Matter in Room Reidentification**|Runmao Yao et.al.|[2503.01130](http://arxiv.org/abs/2503.01130)|null|
|**2025-03-02**|**Efficient End-to-end Visual Localization for Autonomous Driving with Decoupled BEV Neural Matching**|Jinyu Miao et.al.|[2503.00862](http://arxiv.org/abs/2503.00862)|null|
|**2025-02-28**|**EVLoc: Event-based Visual Localization in LiDAR Maps via Event-Depth Registration**|Kuangyi Chen et.al.|[2503.00167](http://arxiv.org/abs/2503.00167)|**[link](https://github.com/EasonChen99/EVLoc)**|
|**2025-02-28**|**Fast 3D point clouds retrieval for Large-scale 3D Place Recognition**|Chahine-Nicolas Zede et.al.|[2502.21067](http://arxiv.org/abs/2502.21067)|null|
|**2025-02-28**|**SciceVPR: Stable Cross-Image Correlation Enhanced Model for Visual Place Recognition**|Shanshan Wan et.al.|[2502.20676](http://arxiv.org/abs/2502.20676)|null|
|**2025-02-28**|**EDENet: Echo Direction Encoding Network for Place Recognition Based on Ground Penetrating Radar**|Pengyu Zhang et.al.|[2502.20643](http://arxiv.org/abs/2502.20643)|**[link](https://github.com/Pyxel0524/EDE-LGPR)**|
|**2025-02-27**|**A2-GNN: Angle-Annular GNN for Visual Descriptor-free Camera Relocalization**|Yejun Zhang et.al.|[2502.20036](http://arxiv.org/abs/2502.20036)|**[link](https://github.com/yejunzhang/a2-gnn)**|
|**2025-02-26**|**BEV-LIO(LC): BEV Image Assisted LiDAR-Inertial Odometry with Loop Closure**|Haoxin Cai et.al.|[2502.19242](http://arxiv.org/abs/2502.19242)|**[link](https://github.com/hxca1/bev-lio-lc)**|
|**2025-02-26**|**SLAM in the Dark: Self-Supervised Learning of Pose, Depth and Loop-Closure from Thermal Images**|Yangfan Xu et.al.|[2502.18932](http://arxiv.org/abs/2502.18932)|null|
|**2025-02-25**|**MegaLoc: One Retrieval to Place Them All**|Gabriele Berton et.al.|[2502.17237](http://arxiv.org/abs/2502.17237)|**[link](https://github.com/gmberton/megaloc)**|
|**2025-02-23**|**SelaVPR++: Towards Seamless Adaptation of Foundation Models for Efficient Place Recognition**|Feng Lu et.al.|[2502.16601](http://arxiv.org/abs/2502.16601)|**[link](https://github.com/Lu-Feng/SelaVPR)**|
|**2025-03-07**|**Bridging Text and Vision: A Multi-View Text-Vision Registration Approach for Cross-Modal Place Recognition**|Tianyi Shang et.al.|[2502.14195](http://arxiv.org/abs/2502.14195)|**[link](https://github.com/nuozimiaowu/Text4VPR)**|
|**2025-02-19**|**3D Gaussian Splatting aided Localization for Large and Complex Indoor-Environments**|Vincent Ress et.al.|[2502.13803](http://arxiv.org/abs/2502.13803)|null|
|**2025-02-18**|**SHADeS: Self-supervised Monocular Depth Estimation Through Non-Lambertian Image Decomposition**|Rema Daher et.al.|[2502.12994](http://arxiv.org/abs/2502.12994)|null|
|**2025-02-19**|**IM360: Textured Mesh Reconstruction for Large-scale Indoor Mapping with 360 $^\circ$ Cameras**|Dongki Jung et.al.|[2502.12545](http://arxiv.org/abs/2502.12545)|null|
|**2025-02-17**|**From Gaming to Research: GTA V for Synthetic Data Generation for Robotics and Navigations**|Matteo Scucchia et.al.|[2502.12303](http://arxiv.org/abs/2502.12303)|null|
|**2025-02-28**|**Range and Bird's Eye View Fused Cross-Modal Visual Place Recognition**|Jianyi Peng et.al.|[2502.11742](http://arxiv.org/abs/2502.11742)|**[link](https://github.com/cppcute-pm/RangeBEV)**|
|**2025-02-11**|**Imit Diff: Semantics Guided Diffusion Transformer with Dual Resolution Fusion for Imitation Learning**|Yuhang Dong et.al.|[2502.09649](http://arxiv.org/abs/2502.09649)|null|
|**2025-03-04**|**SpeechCompass: Enhancing Mobile Captioning with Diarization and Directional Guidance via Multi-Microphone Localization**|Artem Dementyev et.al.|[2502.08848](http://arxiv.org/abs/2502.08848)|null|
|**2025-02-11**|**Ultrafast 4D scanning transmission electron microscopy for imaging of localized optical fields**|Petr Koutenský et.al.|[2502.07338](http://arxiv.org/abs/2502.07338)|null|
|**2025-02-07**|**Learning Street View Representations with Spatiotemporal Contrast**|Yong Li et.al.|[2502.04638](http://arxiv.org/abs/2502.04638)|null|
|**2025-02-21**|**HeRCULES: Heterogeneous Radar Dataset in Complex Urban Environment for Multi-session Radar SLAM**|Hanjun Kim et.al.|[2502.01946](http://arxiv.org/abs/2502.01946)|null|
|**2025-01-31**|**LiDAR Loop Closure Detection using Semantic Graphs with Graph Attention Networks**|Liudi Yang et.al.|[2501.19382](http://arxiv.org/abs/2501.19382)|**[link](https://github.com/crepuscularlight/semanticloopclosure)**|
|**2025-02-07**|**HeLiOS: Heterogeneous LiDAR Place Recognition via Overlap-based Learning and Local Spherical Transformer**|Minwoo Jung et.al.|[2501.18943](http://arxiv.org/abs/2501.18943)|null|
|**2025-01-24**|**Visual Localization via Semantic Structures in Autonomous Photovoltaic Power Plant Inspection**|Viktor Kozák et.al.|[2501.14587](http://arxiv.org/abs/2501.14587)|null|
|**2025-01-27**|**Visual-Lidar Map Alignment for Infrastructure Inspections**|Jake McLaughlin et.al.|[2501.14486](http://arxiv.org/abs/2501.14486)|**[link](https://github.com/jakemclaughlin6/vlma)**|
|**2025-01-17**|**FLORA: Formal Language Model Enables Robust Training-free Zero-shot Object Referring Analysis**|Zhe Chen et.al.|[2501.09887](http://arxiv.org/abs/2501.09887)|null|
|**2025-01-14**|**VINGS-Mono: Visual-Inertial Gaussian Splatting Monocular SLAM in Large Scenes**|Ke Wu et.al.|[2501.08286](http://arxiv.org/abs/2501.08286)|null|
|**2025-01-13**|**Efficiently Closing Loops in LiDAR-Based SLAM Using Point Cloud Density Maps**|Saurabh Gupta et.al.|[2501.07399](http://arxiv.org/abs/2501.07399)|null|
|**2025-01-09**|**Seeing with Partial Certainty: Conformal Prediction for Robotic Scene Recognition in Built Environments**|Yifan Xu et.al.|[2501.04947](http://arxiv.org/abs/2501.04947)|null|
|**2025-03-01**|**Balancing Accuracy and Efficiency for Large-Scale SLAM: A Minimal Subset Approach for Scalable Loop Closures**|Nikolaos Stathoulopoulos et.al.|[2501.01791](http://arxiv.org/abs/2501.01791)|**[link](https://github.com/ltu-rai/opt-key)**|
|**2025-04-10**|**R-SCoRe: Revisiting Scene Coordinate Regression for Robust Large-Scale Visual Localization**|Xudong Jiang et.al.|[2501.01421](http://arxiv.org/abs/2501.01421)|**[link](https://github.com/cvg/scrstudio)**|
|**2025-01-02**|**Training Medical Large Vision-Language Models with Abnormal-Aware Feedback**|Yucheng Zhou et.al.|[2501.01377](http://arxiv.org/abs/2501.01377)|null|
|**2024-12-28**|**GSplatLoc: Ultra-Precise Camera Localization via 3D Gaussian Splatting**|Atticus J. Zeller et.al.|[2412.20056](http://arxiv.org/abs/2412.20056)|**[link](https://github.com/atticuszeller/gsplatloc)**|
|**2025-03-14**|**MR-COGraphs: Communication-efficient Multi-Robot Open-vocabulary Mapping System via 3D Scene Graphs**|Qiuyi Gu et.al.|[2412.18381](http://arxiv.org/abs/2412.18381)|**[link](https://github.com/efc-robot/mr-cographs)**|
|**2025-03-06**|**Large-Scale UWB Anchor Calibration and One-Shot Localization Using Gaussian Process**|Shenghai Yuan et.al.|[2412.16880](http://arxiv.org/abs/2412.16880)|null|
|**2024-12-18**|**ConDo: Continual Domain Expansion for Absolute Pose Regression**|Zijun Li et.al.|[2412.13452](http://arxiv.org/abs/2412.13452)|**[link](https://github.com/zijunli7/condo)**|
|**2024-12-16**|**UniLoc: Towards Universal Place Recognition Using Any Single Modality**|Yan Xia et.al.|[2412.12079](http://arxiv.org/abs/2412.12079)|null|
|**2024-12-13**|**MVC-VPR: Mutual Learning of Viewpoint Classification and Visual Place Recognition**|Qiwen Gu et.al.|[2412.09199](http://arxiv.org/abs/2412.09199)|null|
|**2025-03-21**|**Reloc3r: Large-Scale Training of Relative Camera Pose Regression for Generalizable, Fast, and Accurate Visual Localization**|Siyan Dong et.al.|[2412.08376](http://arxiv.org/abs/2412.08376)|**[link](https://github.com/ffrivera0/reloc3r)**|
|**2024-12-11**|**Intelligent Control of Robotic X-ray Devices using a Language-promptable Digital Twin**|Benjamin D. Killeen et.al.|[2412.08020](http://arxiv.org/abs/2412.08020)|null|
|**2024-12-10**|**On Motion Blur and Deblurring in Visual Place Recognition**|Timur Ismagilov et.al.|[2412.07751](http://arxiv.org/abs/2412.07751)|null|
|**2024-12-09**|**An Efficient Scene Coordinate Encoding and Relocalization Method**|Kuan Xu et.al.|[2412.06488](http://arxiv.org/abs/2412.06488)|**[link](https://github.com/sair-lab/SeqACE)**|
|**2024-12-09**|**A Hyperdimensional One Place Signature to Represent Them All: Stackable Descriptors For Visual Place Recognition**|Connor Malone et.al.|[2412.06153](http://arxiv.org/abs/2412.06153)|null|
|**2024-02-19**|**CoLRIO: LiDAR-Ranging-Inertial Centralized State Estimation for Robotic Swarms**|Shipeng Zhong et.al.|[2402.11790](http://arxiv.org/abs/2402.11790)|null|
|**2024-02-16**|**Spike-EVPR: Deep Spiking Residual Network with Cross-Representation Aggregation for Event-Based Visual Place Recognition**|Chenming Hu et.al.|[2402.10476](http://arxiv.org/abs/2402.10476)|null|
|**2024-02-14**|**Loopy-SLAM: Dense Neural SLAM with Loop Closures**|Lorenzo Liso et.al.|[2402.09944](http://arxiv.org/abs/2402.09944)|null|
|**2024-02-15**|**Self-Supervised Learning of Visual Robot Localization Using LED State Prediction as a Pretext Task**|Mirko Nava et.al.|[2402.09886](http://arxiv.org/abs/2402.09886)|**[link](https://github.com/idsia-robotics/leds-as-pretext)**|
|**2024-02-14**|**Weatherproofing Retrieval for Localization with Generative AI and Geometric Consistency**|Yannis Kalantidis et.al.|[2402.09237](http://arxiv.org/abs/2402.09237)|null|
|**2024-02-13**|**Learning to Produce Semi-dense Correspondences for Visual Localization**|Khang Truong Giang et.al.|[2402.08359](http://arxiv.org/abs/2402.08359)|**[link](https://github.com/truongkhang/deviloc)**|
|**2024-02-10**|**Semantic Object-level Modeling for Robust Visual Camera Relocalization**|Yifan Zhu et.al.|[2402.06951](http://arxiv.org/abs/2402.06951)|null|
|**2024-02-09**|**PAS-SLAM: A Visual SLAM System for Planar Ambiguous Scenes**|Xinggang Hu et.al.|[2402.06131](http://arxiv.org/abs/2402.06131)|null|
|**2024-02-09**|**MoD-SLAM: Monocular Dense Mapping for Unbounded 3D Scene Reconstruction**|Heng Zhou et.al.|[2402.03762](http://arxiv.org/abs/2402.03762)|null|
|**2024-02-03**|**RecNet: An Invertible Point Cloud Encoding through Range Image Embeddings for Multi-Robot Map Sharing and Reconstruction**|Nikolaos Stathoulopoulos et.al.|[2402.02192](http://arxiv.org/abs/2402.02192)|null|
|**2024-02-01**|**BrainSLAM: SLAM on Neural Population Activity Data**|Kipp Freud et.al.|[2402.00588](http://arxiv.org/abs/2402.00588)|null|
|**2024-02-01**|**Night-Rider: Nocturnal Vision-aided Localization in Streetlight Maps Using Invariant Extended Kalman Filtering**|Tianxiao Gao et.al.|[2402.00330](http://arxiv.org/abs/2402.00330)|**[link](https://github.com/imrl/night-rider)**|
|**2024-01-31**|**Improved Scene Landmark Detection for Camera Localization**|Tien Do et.al.|[2401.18083](http://arxiv.org/abs/2401.18083)|**[link](https://github.com/microsoft/scenelandmarklocalization)**|
|**2024-01-29**|**Regressing Transformers for Data-efficient Visual Place Recognition**|María Leyva-Vallina et.al.|[2401.16304](http://arxiv.org/abs/2401.16304)|null|
|**2024-01-27**|**Open-RadVLAD: Fast and Robust Radar Place Recognition**|Matthew Gadd et.al.|[2401.15380](http://arxiv.org/abs/2401.15380)|**[link](https://github.com/mttgdd/open-radvlad)**|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Feature

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-15**|**UKDM: Underwater keypoint detection and matching using underwater image enhancement techniques**|Pedro Diaz-Garcia et.al.|[2504.11063](http://arxiv.org/abs/2504.11063)|null|
|**2025-04-15**|**Acquisition of high-quality images for camera calibration in robotics applications via speech prompts**|Timm Linder et.al.|[2504.11031](http://arxiv.org/abs/2504.11031)|null|
|**2025-04-11**|**Stereophotoclinometry Revisited**|Travis Driver et.al.|[2504.08252](http://arxiv.org/abs/2504.08252)|null|
|**2025-03-31**|**SuperEvent: Cross-Modal Learning of Event-based Keypoint Detection**|Yannick Burkhardt et.al.|[2504.00139](http://arxiv.org/abs/2504.00139)|null|
|**2025-03-29**|**Deep Visual Servoing of an Aerial Robot Using Keypoint Feature Extraction**|Shayan Sepahvand et.al.|[2503.23171](http://arxiv.org/abs/2503.23171)|null|
|**2025-03-25**|**Multiscale Feature Importance-based Bit Allocation for End-to-End Feature Coding for Machines**|Junle Liu et.al.|[2503.19278](http://arxiv.org/abs/2503.19278)|null|
|**2025-03-05**|**Periodontal Bone Loss Analysis via Keypoint Detection With Heuristic Post-Processing**|Ryan Banks et.al.|[2503.13477](http://arxiv.org/abs/2503.13477)|null|
|**2025-03-16**|**Histogram Transporter: Learning Rotation-Equivariant Orientation Histograms for High-Precision Robotic Kitting**|Jiadong Zhou et.al.|[2503.12541](http://arxiv.org/abs/2503.12541)|null|
|**2025-04-12**|**Keypoint Detection and Description for Raw Bayer Images**|Jiakai Lin et.al.|[2503.08673](http://arxiv.org/abs/2503.08673)|null|
|**2025-03-10**|**REF-VLM: Triplet-Based Referring Paradigm for Unified Visual Decoding**|Yan Tai et.al.|[2503.07413](http://arxiv.org/abs/2503.07413)|**[link](https://github.com/MacavityT/REF-VLM)**|
|**2025-03-11**|**DaD: Distilled Reinforcement Learning for Diverse Keypoint Detection**|Johan Edstedt et.al.|[2503.07347](http://arxiv.org/abs/2503.07347)|**[link](https://github.com/parskatt/dad)**|
|**2025-03-07**|**Automatic determination of quasicrystalline patterns from microscopy images**|Tano Kim Kender et.al.|[2503.05472](http://arxiv.org/abs/2503.05472)|**[link](https://github.com/QuantumMaterialsModelling/AiSurf-Automated-Identification-of-Surface-images)**|
|**2025-03-07**|**Spatial regularisation for improved accuracy and interpretability in keypoint-based registration**|Benjamin Billot et.al.|[2503.04499](http://arxiv.org/abs/2503.04499)|**[link](https://github.com/benbillot/spatial_regularisation)**|
|**2025-03-04**|**A Novel Streamline-based diffusion MRI Tractography Registration Method with Probabilistic Keypoint Detection**|Junyi Wang et.al.|[2503.02481](http://arxiv.org/abs/2503.02481)|null|
|**2025-03-01**|**Autonomous Dissection in Robotic Cholecystectomy**|Ki-Hwan Oh et.al.|[2503.00666](http://arxiv.org/abs/2503.00666)|null|
|**2025-02-28**|**CNSv2: Probabilistic Correspondence Encoded Neural Image Servo**|Anzhe Chen et.al.|[2503.00132](http://arxiv.org/abs/2503.00132)|null|
|**2025-02-27**|**Automatic Temporal Segmentation for Post-Stroke Rehabilitation: A Keypoint Detection and Temporal Segmentation Approach for Small Datasets**|Jisoo Lee et.al.|[2502.19766](http://arxiv.org/abs/2502.19766)|null|
|**2025-02-23**|**Rewards-based image analysis in microscopy**|Kamyar Barakati et.al.|[2502.18522](http://arxiv.org/abs/2502.18522)|null|
|**2025-02-19**|**2.5D U-Net with Depth Reduction for 3D CryoET Object Identification**|Yusuke Uchida et.al.|[2502.13484](http://arxiv.org/abs/2502.13484)|**[link](https://github.com/yu4u/kaggle-czii-4th)**|
|**2025-01-30**|**Transfer Learning for Keypoint Detection in Low-Resolution Thermal TUG Test Images**|Wei-Lun Chen et.al.|[2501.18453](http://arxiv.org/abs/2501.18453)|null|
|**2025-01-30**|**Video-based Surgical Tool-tip and Keypoint Tracking using Multi-frame Context-driven Deep Learning Models**|Bhargav Ghanekar et.al.|[2501.18361](http://arxiv.org/abs/2501.18361)|null|
|**2025-01-30**|**Lifelong 3D Mapping Framework for Hand-held & Robot-mounted LiDAR Mapping Systems**|Liudi Yang et.al.|[2501.18110](http://arxiv.org/abs/2501.18110)|null|
|**2025-01-21**|**Keypoint Detection Empowered Near-Field User Localization and Channel Reconstruction**|Mengyuan Li et.al.|[2501.11844](http://arxiv.org/abs/2501.11844)|null|
|**2025-01-20**|**MIFNet: Learning Modality-Invariant Features for Generalizable Multimodal Image Matching**|Yepeng Liu et.al.|[2501.11299](http://arxiv.org/abs/2501.11299)|null|
|**2025-01-13**|**Empirical Comparison of Four Stereoscopic Depth Sensing Cameras for Robotics Applications**|Lukas Rustler et.al.|[2501.07421](http://arxiv.org/abs/2501.07421)|null|
|**2025-01-13**|**Efficiently Closing Loops in LiDAR-Based SLAM Using Point Cloud Density Maps**|Saurabh Gupta et.al.|[2501.07399](http://arxiv.org/abs/2501.07399)|null|
|**2024-12-24**|**GIMS: Image Matching System Based on Adaptive Graph Construction and Graph Neural Network**|Xianfeng Song et.al.|[2412.18221](http://arxiv.org/abs/2412.18221)|**[link](https://github.com/songxf1024/gims)**|
|**2024-12-21**|**A Novel Approach to Tomato Harvesting Using a Hybrid Gripper with Semantic Segmentation and Keypoint Detection**|Shahid Ansari et.al.|[2412.16755](http://arxiv.org/abs/2412.16755)|null|
|**2024-12-19**|**Corn Ear Detection and Orientation Estimation Using Deep Learning**|Nathan Sprague et.al.|[2412.14954](http://arxiv.org/abs/2412.14954)|null|
|**2024-12-12**|**Agtech Framework for Cranberry-Ripening Analysis Using Vision Foundation Models**|Faith Johnson et.al.|[2412.09739](http://arxiv.org/abs/2412.09739)|null|
|**2024-12-09**|**An Efficient Scene Coordinate Encoding and Relocalization Method**|Kuan Xu et.al.|[2412.06488](http://arxiv.org/abs/2412.06488)|**[link](https://github.com/sair-lab/SeqACE)**|
|**2024-12-09**|**ZeroKey: Point-Level Reasoning and Zero-Shot 3D Keypoint Detection from Large Language Models**|Bingchen Gong et.al.|[2412.06292](http://arxiv.org/abs/2412.06292)|null|
|**2024-12-07**|**Securing Social Media Against Deepfakes using Identity, Behavioral, and Geometric Signatures**|Muhammad Umar Farooq et.al.|[2412.05487](http://arxiv.org/abs/2412.05487)|null|
|**2024-12-04**|**Measure Anything: Real-time, Multi-stage Vision-based Dimensional Measurement using Segment Anything**|Yongkyu Lee et.al.|[2412.03472](http://arxiv.org/abs/2412.03472)|**[link](https://github.com/StructuresComp/measure-anything)**|
|**2024-12-02**|**MamKPD: A Simple Mamba Baseline for Real-Time 2D Keypoint Detection**|Yonghao Dang et.al.|[2412.01422](http://arxiv.org/abs/2412.01422)|null|
|**2024-11-23**|**OCDet: Object Center Detection via Bounding Box-Aware Heatmap Prediction on Edge Devices with NPUs**|Chen Xin et.al.|[2411.15653](http://arxiv.org/abs/2411.15653)|**[link](https://github.com/chen-xin-94/ocdet)**|
|**2024-11-19**|**IoT-Based 3D Pose Estimation and Motion Optimization for Athletes: Application of C3D and OpenPose**|Fei Ren et.al.|[2411.12676](http://arxiv.org/abs/2411.12676)|null|
|**2024-11-04**|**Silver medal Solution for Image Matching Challenge 2024**|Yian Wang et.al.|[2411.01851](http://arxiv.org/abs/2411.01851)|null|
|**2024-11-04**|**KptLLM: Unveiling the Power of Large Language Model for Keypoint Comprehension**|Jie Yang et.al.|[2411.01846](http://arxiv.org/abs/2411.01846)|null|
|**2024-10-31**|**From Web Data to Real Fields: Low-Cost Unsupervised Domain Adaptation for Agricultural Robots**|Vasileios Tzouras et.al.|[2410.23906](http://arxiv.org/abs/2410.23906)|null|
|**2025-03-31**|**YOLO11 and Vision Transformers based 3D Pose Estimation of Immature Green Fruits in Commercial Apple Orchards for Robotic Thinning**|Ranjan Sapkota et.al.|[2410.19846](http://arxiv.org/abs/2410.19846)|null|
|**2024-10-04**|**Self-Supervised Keypoint Detection with Distilled Depth Keypoint Representation**|Aman Anand et.al.|[2410.14700](http://arxiv.org/abs/2410.14700)|null|
|**2024-11-27**|**Sim2real Cattle Joint Estimation in 3D point clouds**|Mohammad Okour et.al.|[2410.14419](http://arxiv.org/abs/2410.14419)|null|
|**2024-10-16**|**PND-Net: Plant Nutrition Deficiency and Disease Classification using Graph Convolutional Network**|Asish Bera et.al.|[2410.12742](http://arxiv.org/abs/2410.12742)|null|
|**2024-10-16**|**RAFA-Net: Region Attention Network For Food Items And Agricultural Stress Recognition**|Asish Bera et.al.|[2410.12718](http://arxiv.org/abs/2410.12718)|null|
|**2024-10-01**|**A Robust Multisource Remote Sensing Image Matching Method Utilizing Attention and Feature Enhancement Against Noise Interference**|Yuan Li et.al.|[2410.11848](http://arxiv.org/abs/2410.11848)|null|
|**2024-10-11**|**Facial Chick Sexing: An Automated Chick Sexing System From Chick Facial Image**|Marta Veganzones Rodriguez et.al.|[2410.09155](http://arxiv.org/abs/2410.09155)|null|
|**2024-10-08**|**Unsupervised Model Diagnosis**|Yinong Oliver Wang et.al.|[2410.06243](http://arxiv.org/abs/2410.06243)|null|
|**2024-10-08**|**Equi-GSPR: Equivariant SE(3) Graph Network Model for Sparse Point Cloud Registration**|Xueyang Kang et.al.|[2410.05729](http://arxiv.org/abs/2410.05729)|**[link](https://github.com/alexandor91/se3-equi-graph-registration)**|
|**2024-12-07**|**Key-Grid: Unsupervised 3D Keypoints Detection using Grid Heatmap Features**|Chengkai Hou et.al.|[2410.02237](http://arxiv.org/abs/2410.02237)|null|
|**2025-02-13**|**Gaussian-Det: Learning Closed-Surface Gaussians for 3D Object Detection**|Hongru Yan et.al.|[2410.01404](http://arxiv.org/abs/2410.01404)|null|
|**2024-09-30**|**OpenKD: Opening Prompt Diversity for Zero- and Few-shot Keypoint Detection**|Changsheng Lu et.al.|[2409.19899](http://arxiv.org/abs/2409.19899)|**[link](https://github.com/alanlusun/openkd)**|
|**2024-10-07**|**SKT: Integrating State-Aware Keypoint Trajectories with Vision-Language Models for Robotic Garment Manipulation**|Xin Li et.al.|[2409.18082](http://arxiv.org/abs/2409.18082)|null|
|**2025-03-18**|**Point Cloud Structural Similarity-based Underwater Sonar Loop Detection**|Donghwi Jung et.al.|[2409.14020](http://arxiv.org/abs/2409.14020)|**[link](https://github.com/donghwijung/point_cloud_structural_similarity_based_underwater_sonar_loop_detection)**|
|**2024-09-20**|**Keypoint Detection Technique for Image-Based Visual Servoing of Manipulators**|Niloufar Amiri et.al.|[2409.13668](http://arxiv.org/abs/2409.13668)|null|
|**2025-04-16**|**Analysis of Deep Learning-Based Colorization and Super-Resolution Techniques for Lidar Imagery**|Sier Ha et.al.|[2409.11532](http://arxiv.org/abs/2409.11532)|null|
|**2024-09-25**|**Precision Aquaculture: An Integrated Computer Vision and IoT Approach for Optimized Tilapia Feeding**|Rania Hossam et.al.|[2409.08695](http://arxiv.org/abs/2409.08695)|**[link](https://github.com/ahmedheakl/fish-counting)**|
|**2024-09-06**|**D4: Text-guided diffusion model-based domain adaptive data augmentation for vineyard shoot detection**|Kentaro Hirahara et.al.|[2409.04060](http://arxiv.org/abs/2409.04060)|null|
|**2024-10-01**|**Towards Practical Human Motion Prediction with LiDAR Point Clouds**|Xiao Han et.al.|[2408.08202](http://arxiv.org/abs/2408.08202)|null|
|**2024-07-31**|**Certifying Robustness of Learning-Based Keypoint Detection and Pose Estimation Methods**|Xusheng Luo et.al.|[2408.00117](http://arxiv.org/abs/2408.00117)|null|
|**2024-07-26**|**SHIC: Shape-Image Correspondences with no Keypoint Supervision**|Aleksandar Shtedritski et.al.|[2407.18907](http://arxiv.org/abs/2407.18907)|null|
|**2024-07-25**|**LION: Linear Group RNN for 3D Object Detection in Point Clouds**|Zhe Liu et.al.|[2407.18232](http://arxiv.org/abs/2407.18232)|**[link](https://github.com/happinesslz/LION)**|
|**2024-12-09**|**RADA: Robust and Accurate Feature Learning with Domain Adaptation**|Jingtai He et.al.|[2407.15791](http://arxiv.org/abs/2407.15791)|null|
|**2024-07-09**|**LVLM-empowered Multi-modal Representation Learning for Visual Place Recognition**|Teng Wang et.al.|[2407.06730](http://arxiv.org/abs/2407.06730)|null|
|**2024-07-04**|**PFGS: High Fidelity Point Cloud Rendering via Feature Splatting**|Jiaxu Wang et.al.|[2407.03857](http://arxiv.org/abs/2407.03857)|**[link](https://github.com/Mercerai/PFGS)**|
|**2024-07-03**|**A Radiometric Correction based Optical Modeling Approach to Removing Reflection Noise in TLS Point Clouds of Urban Scenes**|Li Fang et.al.|[2407.02830](http://arxiv.org/abs/2407.02830)|null|
|**2024-05-10**|**Light-SLAM: A Robust Deep-Learning Visual SLAM System Based on LightGlue under Challenging Lighting Conditions**|Zhiqi Zhao et.al.|[2407.02382](http://arxiv.org/abs/2407.02382)|null|
|**2024-07-02**|**Multi-Grained Contrast for Data-Efficient Unsupervised Representation Learning**|Chengchao Shen et.al.|[2407.02014](http://arxiv.org/abs/2407.02014)|**[link](https://github.com/visresearch/mgc)**|
|**2024-06-28**|**Beyond First-Order: A Multi-Scale Approach to Finger Knuckle Print Biometrics**|Chengrui Gao et.al.|[2406.19672](http://arxiv.org/abs/2406.19672)|null|
|**2024-12-05**|**A Certifiable Algorithm for Simultaneous Shape Estimation and Object Tracking**|Lorenzo Shaikewitz et.al.|[2406.16837](http://arxiv.org/abs/2406.16837)|**[link](https://github.com/mit-spark/certifiable_tracking)**|
|**2024-06-03**|**Scale-Free Image Keypoints Using Differentiable Persistent Homology**|Giovanni Barbarani et.al.|[2406.01315](http://arxiv.org/abs/2406.01315)|**[link](https://github.com/gbarbarani/MorseDet)**|
|**2024-06-23**|**W-Net: A Facial Feature-Guided Face Super-Resolution Network**|Hao Liu et.al.|[2406.00676](http://arxiv.org/abs/2406.00676)|null|
|**2024-05-25**|**Deep-PE: A Learning-Based Pose Evaluator for Point Cloud Registration**|Junjie Gao et.al.|[2405.16085](http://arxiv.org/abs/2405.16085)|null|
|**2024-06-01**|**Benchmarking Fish Dataset and Evaluation Metric in Keypoint Detection -- Towards Precise Fish Morphological Assessment in Aquaculture Breeding**|Weizhen Liu et.al.|[2405.12476](http://arxiv.org/abs/2405.12476)|**[link](https://github.com/weizhenliubioinform/fish-phenotype-detect)**|
|**2024-08-12**|**TP3M: Transformer-based Pseudo 3D Image Matching with Reference Image**|Liming Han et.al.|[2405.08434](http://arxiv.org/abs/2405.08434)|null|
|**2025-01-22**|**Vector-Symbolic Architecture for Event-Based Optical Flow**|Hongzhi You et.al.|[2405.08300](http://arxiv.org/abs/2405.08300)|null|
|**2024-08-21**|**RGBD-Glue: General Feature Combination for Robust RGB-D Point Cloud Registration**|Congjia Chen et.al.|[2405.07594](http://arxiv.org/abs/2405.07594)|null|
|**2024-05-08**|**Unsupervised Skin Feature Tracking with Deep Neural Networks**|Jose Chang et.al.|[2405.04943](http://arxiv.org/abs/2405.04943)|null|
|**2024-05-07**|**A Self-Supervised Method for Body Part Segmentation and Keypoint Detection of Rat Images**|László Kopácsi et.al.|[2405.04650](http://arxiv.org/abs/2405.04650)|null|
|**2024-04-30**|**A Light-weight Transformer-based Self-supervised Matching Network for Heterogeneous Images**|Wang Zhang et.al.|[2404.19311](http://arxiv.org/abs/2404.19311)|null|
|**2024-02-18**|**Region Feature Descriptor Adapted to High Affine Transformations**|Shaojie Zhang et.al.|[2402.09724](http://arxiv.org/abs/2402.09724)|null|
|**2024-01-29**|**Reconstructing Close Human Interactions from Multiple Views**|Qing Shuai et.al.|[2401.16173](http://arxiv.org/abs/2401.16173)|**[link](https://github.com/zju3dv/closemocap)**|
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
|**2023-07-28**|**PanoVPR: Towards Unified Perspective-to-Equirectangular Visual Place Recognition via Sliding Windows across the Panoramic View**|Ze Shi et.al.|[2303.14095](http://arxiv.org/abs/2303.14095)|**[link](https://github.com/zafirshi/panovpr)**|
|**2023-03-23**|**Semantic Image Attack for Visual Model Diagnosis**|Jinqi Luo et.al.|[2303.13010](http://arxiv.org/abs/2303.13010)|null|
|**2023-03-22**|**Object Pose Estimation with Statistical Guarantees: Conformal Keypoint Detection and Geometric Uncertainty Propagation**|Heng Yang et.al.|[2303.12246](http://arxiv.org/abs/2303.12246)|**[link](https://github.com/nvlabs/conformalkeypoint)**|
|**2023-05-29**|**RN-Net: Reservoir Nodes-Enabled Neuromorphic Vision Sensing Network**|Sangmin Yoo et.al.|[2303.10770](http://arxiv.org/abs/2303.10770)|null|

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Matching

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-18**|**Outlier-Robust Multi-Model Fitting on Quantum Annealers**|Saurabh Pandey et.al.|[2504.13836](http://arxiv.org/abs/2504.13836)|null|
|**2025-04-11**|**Geometric Consistency Refinement for Single Image Novel View Synthesis via Test-Time Adaptation of Diffusion Models**|Josef Bengtson et.al.|[2504.08348](http://arxiv.org/abs/2504.08348)|null|
|**2025-04-10**|**Image registration of 2D optical thin sections in a 3D porous medium: Application to a Berea sandstone digital rock image**|Jaehong Chung et.al.|[2504.06604](http://arxiv.org/abs/2504.06604)|**[link](https://github.com/jh-chung1/imgregister2dto3d)**|
|**2025-04-08**|**To Match or Not to Match: Revisiting Image Matching for Reliable Visual Place Recognition**|Davide Sferrazza et.al.|[2504.06116](http://arxiv.org/abs/2504.06116)|**[link](https://github.com/FarInHeight/To-Match-or-Not-to-Match)**|
|**2025-04-10**|**Learning Affine Correspondences by Integrating Geometric Constraints**|Pengju Sun et.al.|[2504.04834](http://arxiv.org/abs/2504.04834)|**[link](https://github.com/stilcrad/denseaffine)**|
|**2025-04-01**|**Scaling Prompt Instructed Zero Shot Composed Image Retrieval with Image-Only Data**|Yiqun Duan et.al.|[2504.00812](http://arxiv.org/abs/2504.00812)|null|
|**2025-03-31**|**CoMatch: Dynamic Covisibility-Aware Transformer for Bilateral Subpixel-Level Semi-Dense Image Matching**|Zizhuo Li et.al.|[2503.23925](http://arxiv.org/abs/2503.23925)|null|
|**2025-03-28**|**Pairwise Matching of Intermediate Representations for Fine-grained Explainability**|Lauren Shrack et.al.|[2503.22881](http://arxiv.org/abs/2503.22881)|**[link](https://github.com/pairx-explains/pairx)**|
|**2025-03-26**|**Multimodal Image Matching based on Frequency-domain Information of Local Energy Response**|Meng Yang et.al.|[2503.20827](http://arxiv.org/abs/2503.20827)|null|
|**2025-03-22**|**Normalized Matching Transformer**|Abtin Pourhadi et.al.|[2503.17715](http://arxiv.org/abs/2503.17715)|**[link](https://github.com/apollos1301/normmatchtrans)**|
|**2025-03-20**|**Loop Closure from Two Views: Revisiting PGO for Scalable Trajectory Estimation through Monocular Priors**|Tian Yi Lim et.al.|[2503.16275](http://arxiv.org/abs/2503.16275)|null|
|**2025-03-20**|**MapGlue: Multimodal Remote Sensing Image Matching**|Peihao Wu et.al.|[2503.16185](http://arxiv.org/abs/2503.16185)|**[link](https://github.com/peihaowu/mapglue)**|
|**2025-03-19**|**PAPI-Reg: Patch-to-Pixel Solution for Efficient Cross-Modal Registration between LiDAR Point Cloud and Camera Image**|Yuanchao Yue et.al.|[2503.15285](http://arxiv.org/abs/2503.15285)|null|
|**2025-04-07**|**Less Biased Noise Scale Estimation for Threshold-Robust RANSAC**|Johan Edstedt et.al.|[2503.13433](http://arxiv.org/abs/2503.13433)|null|
|**2025-03-17**|**SatDepth: A Novel Dataset for Satellite Image Matching**|Rahul Deshmukh et.al.|[2503.12706](http://arxiv.org/abs/2503.12706)|**[link](https://github.com/rahuldeshmukh43/satdepth)**|
|**2025-03-14**|**Refining Image Edge Detection via Linear Canonical Riesz Transforms**|Shuhui Yang et.al.|[2503.11148](http://arxiv.org/abs/2503.11148)|null|
|**2025-03-13**|**Speedy MASt3R**|Jingxing Li et.al.|[2503.10017](http://arxiv.org/abs/2503.10017)|null|
|**2025-04-12**|**Keypoint Detection and Description for Raw Bayer Images**|Jiakai Lin et.al.|[2503.08673](http://arxiv.org/abs/2503.08673)|null|
|**2025-03-06**|**Learning 3D Medical Image Models From Brain Functional Connectivity Network Supervision For Mental Disorder Diagnosis**|Xingcan Hu et.al.|[2503.04205](http://arxiv.org/abs/2503.04205)|null|
|**2025-03-07**|**Diff-Reg v2: Diffusion-Based Matching Matrix Estimation for Image Matching and 3D Registration**|Qianliang Wu et.al.|[2503.04127](http://arxiv.org/abs/2503.04127)|null|
|**2025-03-05**|**JamMa: Ultra-lightweight Local Feature Matching with Joint Mamba**|Xiaoyong Lu et.al.|[2503.03437](http://arxiv.org/abs/2503.03437)|null|
|**2025-02-28**|**CNSv2: Probabilistic Correspondence Encoded Neural Image Servo**|Anzhe Chen et.al.|[2503.00132](http://arxiv.org/abs/2503.00132)|null|
|**2025-02-27**|**A2-GNN: Angle-Annular GNN for Visual Descriptor-free Camera Relocalization**|Yejun Zhang et.al.|[2502.20036](http://arxiv.org/abs/2502.20036)|**[link](https://github.com/yejunzhang/a2-gnn)**|
|**2025-02-27**|**RUBIK: A Structured Benchmark for Image Matching across Geometric Challenges**|Thibaut Loiseau et.al.|[2502.19955](http://arxiv.org/abs/2502.19955)|null|
|**2025-02-26**|**BEV-LIO(LC): BEV Image Assisted LiDAR-Inertial Odometry with Loop Closure**|Haoxin Cai et.al.|[2502.19242](http://arxiv.org/abs/2502.19242)|**[link](https://github.com/hxca1/bev-lio-lc)**|
|**2025-02-25**|**PromptMID: Modal Invariant Descriptors Based on Diffusion and Vision Foundation Models for Optical-SAR Image Matching**|Han Nie et.al.|[2502.18104](http://arxiv.org/abs/2502.18104)|**[link](https://github.com/hanniewhu/promptmid)**|
|**2025-02-25**|**Improving Transformer Based Line Segment Detection with Matched Predicting and Re-ranking**|Xin Tong et.al.|[2502.17766](http://arxiv.org/abs/2502.17766)|null|
|**2025-03-04**|**Unposed Sparse Views Room Layout Reconstruction in the Age of Pretrain Model**|Yaxuan Huang et.al.|[2502.16779](http://arxiv.org/abs/2502.16779)|null|
|**2025-02-16**|**FeaKM: Robust Collaborative Perception under Noisy Pose Conditions**|Jiuwu Hao et.al.|[2502.11003](http://arxiv.org/abs/2502.11003)|**[link](https://github.com/uestchjw/feakm)**|
|**2025-02-24**|**Enhancing Ground-to-Aerial Image Matching for Visual Misinformation Detection Using Semantic Segmentation**|Emanuele Mule et.al.|[2502.06288](http://arxiv.org/abs/2502.06288)|**[link](https://github.com/MatteoPannacci/SemanticAlignNet-QUAD)**|
|**2025-04-02**|**Muographic Image Upsampling with Machine Learning for Built Infrastructure Applications**|William O'Donnell et.al.|[2502.02624](http://arxiv.org/abs/2502.02624)|null|
|**2025-02-01**|**MambaGlue: Fast and Robust Local Feature Matching With Mamba**|Kihwan Ryoo et.al.|[2502.00462](http://arxiv.org/abs/2502.00462)|**[link](https://github.com/url-kaist/mambaglue)**|
|**2025-03-23**|**Dense-SfM: Structure from Motion with Dense Consistent Matching**|JongMin Lee et.al.|[2501.14277](http://arxiv.org/abs/2501.14277)|null|
|**2025-01-20**|**MIFNet: Learning Modality-Invariant Features for Generalizable Multimodal Image Matching**|Yepeng Liu et.al.|[2501.11299](http://arxiv.org/abs/2501.11299)|null|
|**2025-01-13**|**MatchAnything: Universal Cross-Modality Image Matching with Large-Scale Pre-Training**|Xingyi He et.al.|[2501.07556](http://arxiv.org/abs/2501.07556)|null|
|**2025-01-13**|**Matching Free Depth Recovery from Structured Light**|Zhuohang Yu et.al.|[2501.07113](http://arxiv.org/abs/2501.07113)|null|
|**2025-01-02**|**Sparis: Neural Implicit Surface Reconstruction of Indoor Scenes from Sparse Views**|Yulun Wu et.al.|[2501.01196](http://arxiv.org/abs/2501.01196)|null|
|**2024-12-31**|**Towards Real-Time 2D Mapping: Harnessing Drones, AI, and Computer Vision for Advanced Insights**|Bharath Kumar Agnur et.al.|[2412.20210](http://arxiv.org/abs/2412.20210)|null|
|**2025-03-29**|**MINIMA: Modality Invariant Image Matching**|Jiangwei Ren et.al.|[2412.19412](http://arxiv.org/abs/2412.19412)|**[link](https://github.com/LSXI7/MINIMA)**|
|**2024-12-24**|**GIMS: Image Matching System Based on Adaptive Graph Construction and Graph Neural Network**|Xianfeng Song et.al.|[2412.18221](http://arxiv.org/abs/2412.18221)|**[link](https://github.com/songxf1024/gims)**|
|**2024-12-17**|**Bringing Multimodality to Amazon Visual Search System**|Xinliang Zhu et.al.|[2412.13364](http://arxiv.org/abs/2412.13364)|null|
|**2025-03-18**|**Appearance Matching Adapter for Exemplar-based Semantic Image Synthesis in-the-Wild**|Siyoon Jin et.al.|[2412.03150](http://arxiv.org/abs/2412.03150)|null|
|**2024-11-20**|**DT-LSD: Deformable Transformer-based Line Segment Detection**|Sebastian Janampa et.al.|[2411.13005](http://arxiv.org/abs/2411.13005)|**[link](https://github.com/SebastianJanampa/DT-LSD)**|
|**2025-03-01**|**Image Matching Filtering and Refinement by Planes and Beyond**|Fabio Bellavia et.al.|[2411.09484](http://arxiv.org/abs/2411.09484)|**[link](https://github.com/fb82/miho)**|
|**2024-11-11**|**XPoint: A Self-Supervised Visual-State-Space based Architecture for Multispectral Image Registration**|Ismail Can Yagmur et.al.|[2411.07430](http://arxiv.org/abs/2411.07430)|**[link](https://github.com/canyagmur/xpoint)**|
|**2024-11-07**|**The Impact of Semi-Supervised Learning on Line Segment Detection**|Johanna Engman et.al.|[2411.04596](http://arxiv.org/abs/2411.04596)|**[link](https://github.com/jo6815en/semi-lines)**|
|**2024-11-04**|**Silver medal Solution for Image Matching Challenge 2024**|Yian Wang et.al.|[2411.01851](http://arxiv.org/abs/2411.01851)|null|
|**2024-10-30**|**Variable Resolution Sampling and Deep Learning Image Recovery for Accelerated Multi-Spectral MRI Near Metal Implants**|Azadeh Sharafi et.al.|[2410.23329](http://arxiv.org/abs/2410.23329)|null|
|**2025-04-05**|**DreamRelation: Bridging Customization and Relation Generation**|Qingyu Shi et.al.|[2410.23280](http://arxiv.org/abs/2410.23280)|null|
|**2025-01-10**|**ETO:Efficient Transformer-based Local Feature Matching by Organizing Multiple Homography Hypotheses**|Junjie Ni et.al.|[2410.22733](http://arxiv.org/abs/2410.22733)|null|
|**2024-10-30**|**LoFLAT: Local Feature Matching using Focused Linear Attention Transformer**|Naijian Cao et.al.|[2410.22710](http://arxiv.org/abs/2410.22710)|null|
|**2024-10-26**|**Generative Adversarial Patches for Physical Attacks on Cross-Modal Pedestrian Re-Identification**|Yue Su et.al.|[2410.20097](http://arxiv.org/abs/2410.20097)|null|
|**2024-10-01**|**A Robust Multisource Remote Sensing Image Matching Method Utilizing Attention and Feature Enhancement Against Noise Interference**|Yuan Li et.al.|[2410.11848](http://arxiv.org/abs/2410.11848)|null|
|**2024-10-15**|**LoGS: Visual Localization via Gaussian Splatting with Fewer Training Images**|Yuzhou Cheng et.al.|[2410.11505](http://arxiv.org/abs/2410.11505)|null|
|**2024-10-12**|**Leveraging Semantic Cues from Foundation Vision Models for Enhanced Local Feature Correspondence**|Felipe Cadar et.al.|[2410.09533](http://arxiv.org/abs/2410.09533)|**[link](https://github.com/verlab/DescriptorReasoning_ACCV_2024)**|
|**2024-09-27**|**Exploiting Motion Prior for Accurate Pose Estimation of Dashboard Cameras**|Yipeng Lu et.al.|[2409.18673](http://arxiv.org/abs/2409.18673)|null|
|**2024-12-12**|**Game4Loc: A UAV Geo-Localization Benchmark from Game Data**|Yuxiang Ji et.al.|[2409.16925](http://arxiv.org/abs/2409.16925)|**[link](https://github.com/Yux1angJi/GTA-UAV)**|
|**2024-09-24**|**Automatic Registration of SHG and H&E Images with Feature-based Initial Alignment and Intensity-based Instance Optimization: Contribution to the COMULIS Challenge**|Marek Wodzinski et.al.|[2409.15931](http://arxiv.org/abs/2409.15931)|null|
|**2024-09-10**|**Weakly-supervised Camera Localization by Ground-to-satellite Image Registration**|Yujiao Shi et.al.|[2409.06471](http://arxiv.org/abs/2409.06471)|**[link](https://github.com/yujiaoshi/g2sweakly)**|
|**2024-09-05**|**Enabling Practical and Privacy-Preserving Image Processing**|Chao Wang et.al.|[2409.03568](http://arxiv.org/abs/2409.03568)|null|
|**2024-09-20**|**A General Albedo Recovery Approach for Aerial Photogrammetric Images through Inverse Rendering**|Shuang Song et.al.|[2409.03032](http://arxiv.org/abs/2409.03032)|**[link](https://github.com/gdaosu/albedo_aerial_photogrammetry)**|
|**2024-08-29**|**Super-Resolution works for coastal simulations**|Zhi-Song Liu et.al.|[2408.16553](http://arxiv.org/abs/2408.16553)|null|
|**2024-09-15**|**Mismatched: Evaluating the Limits of Image Matching Approaches and Benchmarks**|Sierra Bonilla et.al.|[2408.16445](http://arxiv.org/abs/2408.16445)|**[link](https://github.com/surgical-vision/colmap-match-converter)**|
|**2024-08-26**|**Affine steerers for structured keypoint description**|Georg Bökman et.al.|[2408.14186](http://arxiv.org/abs/2408.14186)|**[link](https://github.com/georg-bn/affine-steerers)**|
|**2024-08-25**|**TranSplat: Generalizable 3D Gaussian Splatting from Sparse Multi-View Images with Transformers**|Chuanrui Zhang et.al.|[2408.13770](http://arxiv.org/abs/2408.13770)|null|
|**2024-09-11**|**Coarse-to-fine Alignment Makes Better Speech-image Retrieval**|Lifeng Zhou et.al.|[2408.13119](http://arxiv.org/abs/2408.13119)|null|
|**2024-08-19**|**BrewCLIP: A Bifurcated Representation Learning Framework for Audio-Visual Retrieval**|Zhenyu Lu et.al.|[2408.10383](http://arxiv.org/abs/2408.10383)|null|
|**2024-08-14**|**RSD-DOG : A New Image Descriptor based on Second Order Derivatives**|Darshan Venkatrayappa et.al.|[2408.07687](http://arxiv.org/abs/2408.07687)|null|
|**2024-09-15**|**One Shot is Enough for Sequential Infrared Small Target Segmentation**|Bingbing Dan et.al.|[2408.04823](http://arxiv.org/abs/2408.04823)|**[link](https://github.com/d-iceice/one-shot-irsts)**|
|**2024-08-07**|**PRISM: PRogressive dependency maxImization for Scale-invariant image Matching**|Xudong Cai et.al.|[2408.03598](http://arxiv.org/abs/2408.03598)|null|
|**2024-08-05**|**ConDL: Detector-Free Dense Image Matching**|Monika Kwiatkowski et.al.|[2408.02766](http://arxiv.org/abs/2408.02766)|null|
|**2024-09-14**|**Improving Neural Surface Reconstruction with Feature Priors from Multi-View Image**|Xinlin Ren et.al.|[2408.02079](http://arxiv.org/abs/2408.02079)|**[link](https://github.com/maybeLx/MVS_NeuS)**|
|**2024-07-29**|**Image-text matching for large-scale book collections**|Artemis Llabrés et.al.|[2407.19812](http://arxiv.org/abs/2407.19812)|**[link](https://github.com/llabres/library-dataset)**|
|**2024-07-26**|**PIV3CAMS: a multi-camera dataset for multiple computer vision problems and its application to novel view-point synthesis**|Sohyeong Kim et.al.|[2407.18695](http://arxiv.org/abs/2407.18695)|null|
|**2024-12-09**|**RADA: Robust and Accurate Feature Learning with Domain Adaptation**|Jingtai He et.al.|[2407.15791](http://arxiv.org/abs/2407.15791)|null|
|**2024-07-17**|**GV-Bench: Benchmarking Local Feature Matching for Geometric Verification of Long-term Loop Closure Detection**|Jingwen Yu et.al.|[2407.11736](http://arxiv.org/abs/2407.11736)|**[link](https://github.com/jarvisyjw/gv-bench)**|
|**2024-07-16**|**REMM:Rotation-Equivariant Framework for End-to-End Multimodal Image Matching**|Han Nie et.al.|[2407.11637](http://arxiv.org/abs/2407.11637)|**[link](https://github.com/hanniewhu/remm)**|
|**2024-07-16**|**A Self-Correcting Strategy of the Digital Volume Correlation Displacement Field Based on Image Matching: Application to Poor Speckles Quality and Complex-Large Deformation**|Chengsheng Li et.al.|[2407.11287](http://arxiv.org/abs/2407.11287)|null|
|**2024-07-14**|**Raising the Ceiling: Conflict-Free Local Feature Matching with Dynamic View Switching**|Xiaoyong Lu et.al.|[2407.07789](http://arxiv.org/abs/2407.07789)|null|
|**2024-07-10**|**Mutual Information calculation on different appearances**|Jiecheng Liao et.al.|[2407.07410](http://arxiv.org/abs/2407.07410)|null|
|**2024-02-16**|**GIM: Learning Generalizable Image Matcher From Internet Videos**|Xuelun Shen et.al.|[2402.11095](http://arxiv.org/abs/2402.11095)|null|
|**2024-02-13**|**Are Semi-Dense Detector-Free Methods Good at Matching Local Features?**|Matthieu Vilain et.al.|[2402.08671](http://arxiv.org/abs/2402.08671)|null|
|**2024-02-13**|**Learning to Produce Semi-dense Correspondences for Visual Localization**|Khang Truong Giang et.al.|[2402.08359](http://arxiv.org/abs/2402.08359)|**[link](https://github.com/truongkhang/deviloc)**|
|**2024-01-31**|**Improved Scene Landmark Detection for Camera Localization**|Tien Do et.al.|[2401.18083](http://arxiv.org/abs/2401.18083)|**[link](https://github.com/microsoft/scenelandmarklocalization)**|
|**2024-01-31**|**Local Feature Matching Using Deep Learning: A Survey**|Shibiao Xu et.al.|[2401.17592](http://arxiv.org/abs/2401.17592)|null|
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
|**2023-12-04**|**Steerers: A framework for rotation equivariant keypoint descriptors**|Georg Bökman et.al.|[2312.02152](http://arxiv.org/abs/2312.02152)|**[link](https://github.com/georg-bn/rotation-steerers)**|
|**2023-11-30**|**DSeg: Direct Line Segments Detection**|Berger Cyrille et.al.|[2311.18344](http://arxiv.org/abs/2311.18344)|null|
|**2023-11-30**|**Utilizing Radiomic Feature Analysis For Automated MRI Keypoint Detection: Enhancing Graph Applications**|Sahar Almahfouz Nasser et.al.|[2311.18281](http://arxiv.org/abs/2311.18281)|null|
|**2023-11-29**|**LGFCTR: Local and Global Feature Convolutional Transformer for Image Matching**|Wenhao Zhong et.al.|[2311.17571](http://arxiv.org/abs/2311.17571)|null|
|**2023-11-08**|**Zero-shot Translation of Attention Patterns in VQA Models to Natural Language**|Leonard Salewski et.al.|[2311.05043](http://arxiv.org/abs/2311.05043)|**[link](https://github.com/explainableml/zs-a2t)**|
|**2023-11-06**|**An invariant feature extraction for multi-modal images matching**|Chenzhong Gao et.al.|[2311.02842](http://arxiv.org/abs/2311.02842)|null|
|**2024-02-16**|**RD-VIO: Robust Visual-Inertial Odometry for Mobile Augmented Reality in Dynamic Environments**|Jinyu Li et.al.|[2310.15072](http://arxiv.org/abs/2310.15072)|**[link](https://github.com/openxrlab/xrslam)**|
|**2023-10-23**|**Player Re-Identification Using Body Part Appearences**|Mahesh Bhosale et.al.|[2310.14469](http://arxiv.org/abs/2310.14469)|null|
|**2023-10-20**|**FMRT: Learning Accurate Feature Matching with Reconciliatory Transformer**|Xinyu Zhang et.al.|[2310.13605](http://arxiv.org/abs/2310.13605)|null|
|**2023-11-14**|**RGM: A Robust Generalist Matching Model**|Songyan Zhang et.al.|[2310.11755](http://arxiv.org/abs/2310.11755)|**[link](https://github.com/aim-uofa/rgm)**|
|**2023-10-07**|**UFD-PRiME: Unsupervised Joint Learning of Optical Flow and Stereo Depth through Pixel-Level Rigid Motion Estimation**|Shuai Yuan et.al.|[2310.04712](http://arxiv.org/abs/2310.04712)|null|
|**2023-10-02**|**Leveraging Cutting Edge Deep Learning Based Image Matching for Reconstructing a Large Scene from Sparse Images**|Georg Bökman et.al.|[2310.01092](http://arxiv.org/abs/2310.01092)|null|
|**2023-09-29**|**Segment Anything Model is a Good Teacher for Local Feature Learning**|Jingqian Wu et.al.|[2309.16992](http://arxiv.org/abs/2309.16992)|**[link](https://github.com/vignywang/samfeat)**|
|**2023-09-27**|**KDD-LOAM: Jointly Learned Keypoint Detector and Descriptors Assisted LiDAR Odometry and Mapping**|Renlang Huang et.al.|[2309.15394](http://arxiv.org/abs/2309.15394)|null|
|**2023-10-13**|**A Critical Analysis of Internal Reliability for Uncertainty Quantification of Dense Image Matching in Multi-view Stereo**|Debao Huang et.al.|[2309.09379](http://arxiv.org/abs/2309.09379)|null|
|**2023-09-11**|**Towards Content-based Pixel Retrieval in Revisited Oxford and Paris**|Guoyuan An et.al.|[2309.05438](http://arxiv.org/abs/2309.05438)|**[link](https://github.com/anguoyuan/pixel_retrieval-segmented_instance_retrieval)**|
|**2024-02-02**|**Neural Semantic Surface Maps**|Luca Morreale et.al.|[2309.04836](http://arxiv.org/abs/2309.04836)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## SFM

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-17**|**Volume Encoding Gaussians: Transfer Function-Agnostic 3D Gaussians for Volume Rendering**|Landon Dyken et.al.|[2504.13339](http://arxiv.org/abs/2504.13339)|null|
|**2025-04-15**|**EDGS: Eliminating Densification for Efficient Convergence of 3DGS**|Dmytro Kotovenko et.al.|[2504.13204](http://arxiv.org/abs/2504.13204)|null|
|**2025-04-12**|**A Constrained Optimization Approach for Gaussian Splatting from Coarsely-posed Images and Noisy Lidar Point Clouds**|Jizong Peng et.al.|[2504.09129](http://arxiv.org/abs/2504.09129)|null|
|**2025-04-11**|**Stereophotoclinometry Revisited**|Travis Driver et.al.|[2504.08252](http://arxiv.org/abs/2504.08252)|null|
|**2025-04-08**|**Implementation of a Zed 2i Stereo Camera for High-Frequency Shoreline Change and Coastal Elevation Monitoring**|José A. Pilartes-Congo et.al.|[2504.06464](http://arxiv.org/abs/2504.06464)|null|
|**2025-04-05**|**3R-GS: Best Practice in Optimizing Camera Poses Along with 3DGS**|Zhisheng Huang et.al.|[2504.04294](http://arxiv.org/abs/2504.04294)|null|
|**2025-04-04**|**An Algebraic Geometry Approach to Viewing Graph Solvability**|Federica Arrigoni et.al.|[2504.03637](http://arxiv.org/abs/2504.03637)|null|
|**2025-04-09**|**FIORD: A Fisheye Indoor-Outdoor Dataset with LIDAR Ground Truth for 3D Scene Reconstruction and Benchmarking**|Ulas Gunes et.al.|[2504.01732](http://arxiv.org/abs/2504.01732)|null|
|**2025-03-31**|**LITA-GS: Illumination-Agnostic Novel View Synthesis via Reference-Free 3D Gaussian Splatting and Physical Priors**|Han Zhou et.al.|[2504.00219](http://arxiv.org/abs/2504.00219)|null|
|**2025-03-22**|**3D Modeling: Camera Movement Estimation and path Correction for SFM Model using the Combination of Modified A-SIFT and Stereo System**|Usha Kumari et.al.|[2503.17668](http://arxiv.org/abs/2503.17668)|null|
|**2025-04-08**|**ProtoGS: Efficient and High-Quality Rendering with 3D Gaussian Prototypes**|Zhengqing Gao et.al.|[2503.17486](http://arxiv.org/abs/2503.17486)|null|
|**2025-03-21**|**ColabSfM: Collaborative Structure-from-Motion by Point Cloud Registration**|Johan Edstedt et.al.|[2503.17093](http://arxiv.org/abs/2503.17093)|null|
|**2025-03-20**|**From Monocular Vision to Autonomous Action: Guiding Tumor Resection via 3D Reconstruction**|Ayberk Acar et.al.|[2503.16263](http://arxiv.org/abs/2503.16263)|null|
|**2025-03-18**|**A-SCoRe: Attention-based Scene Coordinate Regression for wide-ranging scenarios**|Huy-Hoang Bui et.al.|[2503.13982](http://arxiv.org/abs/2503.13982)|**[link](https://github.com/ais-lab/a-score)**|
|**2025-03-17**|**Improving Geometric Consistency for 360-Degree Neural Radiance Fields in Indoor Scenarios**|Iryna Repinetska et.al.|[2503.13710](http://arxiv.org/abs/2503.13710)|null|
|**2025-03-17**|**Gaussian On-the-Fly Splatting: A Progressive Framework for Robust Near Real-Time 3DGS Optimization**|Yiwei Xu et.al.|[2503.13086](http://arxiv.org/abs/2503.13086)|null|
|**2025-03-11**|**A Framework for Reducing the Complexity of Geometric Vision Problems and its Application to Two-View Triangulation with Approximation Bounds**|Felix Rydell et.al.|[2503.08142](http://arxiv.org/abs/2503.08142)|null|
|**2025-03-11**|**DaD: Distilled Reinforcement Learning for Diverse Keypoint Detection**|Johan Edstedt et.al.|[2503.07347](http://arxiv.org/abs/2503.07347)|**[link](https://github.com/parskatt/dad)**|
|**2025-03-18**|**Endo-FASt3r: Endoscopic Foundation model Adaptation for Structure from motion**|Mona Sheikh Zeinoddin et.al.|[2503.07204](http://arxiv.org/abs/2503.07204)|null|
|**2025-03-27**|**VidBot: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation**|Hanzhi Chen et.al.|[2503.07135](http://arxiv.org/abs/2503.07135)|null|
|**2025-03-06**|**PLMP -- Point-Line Minimal Problems for Projective SfM**|Kim Kiehn et.al.|[2503.04351](http://arxiv.org/abs/2503.04351)|null|
|**2025-03-03**|**ecg2o: A Seamless Extension of g2o for Equality-Constrained Factor Graph Optimization**|Anas Abdelkarim et.al.|[2503.01311](http://arxiv.org/abs/2503.01311)|**[link](https://github.com/snt-arg/ecg2o)**|
|**2025-03-05**|**A Multi-Sensor Fusion Approach for Rapid Orthoimage Generation in Large-Scale UAV Mapping**|Jialei He et.al.|[2503.01202](http://arxiv.org/abs/2503.01202)|null|
|**2025-03-02**|**MTReD: 3D Reconstruction Dataset for Fly-over Videos of Maritime Domain**|Rui Yi Yong et.al.|[2503.00853](http://arxiv.org/abs/2503.00853)|null|
|**2025-03-02**|**PSRGS:Progressive Spectral Residual of 3D Gaussian for High-Frequency Recovery**|BoCheng Li et.al.|[2503.00848](http://arxiv.org/abs/2503.00848)|null|
|**2025-03-02**|**Multi-Cali Anything: Dense Feature Multi-Frame Structure-from-Motion for Large-Scale Camera Array Calibration**|Jinjiang You et.al.|[2503.00737](http://arxiv.org/abs/2503.00737)|**[link](https://github.com/yjjfish/multi-cali-anything)**|
|**2025-02-27**|**Best Foot Forward: Robust Foot Reconstruction in-the-wild**|Kyle Fogarty et.al.|[2502.20511](http://arxiv.org/abs/2502.20511)|null|
|**2025-03-04**|**Unposed Sparse Views Room Layout Reconstruction in the Age of Pretrain Model**|Yaxuan Huang et.al.|[2502.16779](http://arxiv.org/abs/2502.16779)|null|
|**2025-02-20**|**CDGS: Confidence-Aware Depth Regularization for 3D Gaussian Splatting**|Qilin Zhang et.al.|[2502.14684](http://arxiv.org/abs/2502.14684)|**[link](https://github.com/zqlin0521/cdgs-release)**|
|**2025-02-19**|**Structure-from-Sherds++: Robust Incremental 3D Reassembly of Axially Symmetric Pots from Unordered and Mixed Fragment Collections**|Seong Jong Yoo et.al.|[2502.13986](http://arxiv.org/abs/2502.13986)|null|
|**2025-02-19**|**IM360: Textured Mesh Reconstruction for Large-scale Indoor Mapping with 360 $^\circ$ Cameras**|Dongki Jung et.al.|[2502.12545](http://arxiv.org/abs/2502.12545)|null|
|**2025-02-10**|**FOCUS -- Multi-View Foot Reconstruction From Synthetically Trained Dense Correspondences**|Oliver Boyne et.al.|[2502.06367](http://arxiv.org/abs/2502.06367)|**[link](https://github.com/OllieBoyne/FOCUS)**|
|**2025-02-10**|**Building Rome with Convex Optimization**|Haoyu Han et.al.|[2502.04640](http://arxiv.org/abs/2502.04640)|null|
|**2025-02-04**|**SiLVR: Scalable Lidar-Visual Radiance Field Reconstruction with Uncertainty Quantification**|Yifu Tao et.al.|[2502.02657](http://arxiv.org/abs/2502.02657)|null|
|**2025-03-02**|**GP-GS: Gaussian Processes for Enhanced Gaussian Splatting**|Zhihao Guo et.al.|[2502.02283](http://arxiv.org/abs/2502.02283)|**[link](https://github.com/zhihaohaoran/GPGS)**|
|**2025-02-03**|**XR-VIO: High-precision Visual Inertial Odometry with Fast Initialization for XR Applications**|Shangjin Zhai et.al.|[2502.01297](http://arxiv.org/abs/2502.01297)|null|
|**2025-01-28**|**Automatic Calibration of a Multi-Camera System with Limited Overlapping Fields of View for 3D Surgical Scene Reconstruction**|Tim Flückiger et.al.|[2501.16221](http://arxiv.org/abs/2501.16221)|null|
|**2025-01-25**|**Towards Better Robustness: Progressively Joint Pose-3DGS Learning for Arbitrarily Long Videos**|Zhen-Hui Dong et.al.|[2501.15096](http://arxiv.org/abs/2501.15096)|null|
|**2025-01-24**|**MATCHA:Towards Matching Anything**|Fei Xue et.al.|[2501.14945](http://arxiv.org/abs/2501.14945)|null|
|**2025-01-24**|**Light3R-SfM: Towards Feed-forward Structure-from-Motion**|Sven Elflein et.al.|[2501.14914](http://arxiv.org/abs/2501.14914)|null|
|**2025-03-23**|**Dense-SfM: Structure from Motion with Dense Consistent Matching**|JongMin Lee et.al.|[2501.14277](http://arxiv.org/abs/2501.14277)|null|
|**2025-04-11**|**SplatMAP: Online Dense Monocular SLAM with 3D Gaussian Splatting**|Yue Hu et.al.|[2501.07015](http://arxiv.org/abs/2501.07015)|null|
|**2025-02-02**|**CULTURE3D: Cultural Landmarks and Terrain Dataset for 3D Applications**|Xinyi Zheng et.al.|[2501.06927](http://arxiv.org/abs/2501.06927)|**[link](https://github.com/openinterx/culture3d)**|
|**2025-01-11**|**Aug3D: Augmenting large scale outdoor datasets for Generalizable Novel View Synthesis**|Aditya Rauniyar et.al.|[2501.06431](http://arxiv.org/abs/2501.06431)|null|
|**2025-01-06**|**Targetless Intrinsics and Extrinsic Calibration of Multiple LiDARs and Cameras with IMU using Continuous-Time Estimation**|Yuezhang Lv et.al.|[2501.02821](http://arxiv.org/abs/2501.02821)|null|
|**2025-03-26**|**JOG3R: Towards 3D-Consistent Video Generators**|Chun-Hao Paul Huang et.al.|[2501.01409](http://arxiv.org/abs/2501.01409)|null|
|**2025-01-27**|**EasySplat: View-Adaptive Learning makes 3D Gaussian Splatting Easy**|Ao Gao et.al.|[2501.01003](http://arxiv.org/abs/2501.01003)|null|
|**2024-12-30**|**KeyGS: A Keyframe-Centric Gaussian Splatting Method for Monocular Image Sequences**|Keng-Wei Chang et.al.|[2412.20767](http://arxiv.org/abs/2412.20767)|null|
|**2024-12-23**|**Reconstructing People, Places, and Cameras**|Lea Müller et.al.|[2412.17806](http://arxiv.org/abs/2412.17806)|null|
|**2025-03-07**|**A Simple yet Effective Test-Time Adaptation for Zero-Shot Monocular Metric Depth Estimation**|Rémi Marsal et.al.|[2412.14103](http://arxiv.org/abs/2412.14103)|null|
|**2024-12-18**|**SplineGS: Robust Motion-Adaptive Spline for Real-Time Dynamic 3D Gaussians from Monocular Video**|Jongmin Park et.al.|[2412.09982](http://arxiv.org/abs/2412.09982)|null|
|**2024-12-10**|**Deep Non-rigid Structure-from-Motion Revisited: Canonicalization and Sequence Modeling**|Hui Deng et.al.|[2412.07230](http://arxiv.org/abs/2412.07230)|null|
|**2025-04-04**|**Doppelgangers++: Improved Visual Disambiguation with Geometric 3D Features**|Yuanbo Xiangli et.al.|[2412.05826](http://arxiv.org/abs/2412.05826)|null|
|**2024-12-06**|**MegaSaM: Accurate, Fast, and Robust Structure and Motion from Casual Dynamic Videos**|Zhengqi Li et.al.|[2412.04463](http://arxiv.org/abs/2412.04463)|null|
|**2024-12-02**|**SfM-Free 3D Gaussian Splatting via Hierarchical Training**|Bo Ji et.al.|[2412.01553](http://arxiv.org/abs/2412.01553)|**[link](https://github.com/jibo27/3dgs_hierarchical_training)**|
|**2024-12-02**|**MVImgNet2.0: A Larger-scale Dataset of Multi-view Images**|Xiaoguang Han et.al.|[2412.01430](http://arxiv.org/abs/2412.01430)|null|
|**2024-12-02**|**Look Ma, No Ground Truth! Ground-Truth-Free Tuning of Structure from Motion and Visual SLAM**|Alejandro Fontan et.al.|[2412.01116](http://arxiv.org/abs/2412.01116)|null|
|**2024-11-27**|**RoMo: Robust Motion Segmentation Improves Structure from Motion**|Lily Goli et.al.|[2411.18650](http://arxiv.org/abs/2411.18650)|null|
|**2024-11-24**|**ZeroGS: Training 3D Gaussian Splatting from Unposed Images**|Yu Chen et.al.|[2411.15779](http://arxiv.org/abs/2411.15779)|null|
|**2024-11-20**|**DATAP-SfM: Dynamic-Aware Tracking Any Point for Robust Structure from Motion in the Wild**|Weicai Ye et.al.|[2411.13291](http://arxiv.org/abs/2411.13291)|null|
|**2024-11-15**|**SPARS3R: Semantic Prior Alignment and Regularization for Sparse 3D Reconstruction**|Yutao Tang et.al.|[2411.12592](http://arxiv.org/abs/2411.12592)|**[link](https://github.com/snldmt/SPARS3R)**|
|**2024-11-15**|**The Oxford Spires Dataset: Benchmarking Large-Scale LiDAR-Visual Localisation, Reconstruction and Radiance Field Methods**|Yifu Tao et.al.|[2411.10546](http://arxiv.org/abs/2411.10546)|null|
|**2024-11-13**|**4D Gaussian Splatting in the Wild with Uncertainty-Aware Regularization**|Mijeong Kim et.al.|[2411.08879](http://arxiv.org/abs/2411.08879)|null|
|**2024-11-13**|**Biomass phenotyping of oilseed rape through UAV multi-view oblique imaging with 3DGS and SAM model**|Yutao Shen et.al.|[2411.08453](http://arxiv.org/abs/2411.08453)|null|
|**2025-01-20**|**From Transparent to Opaque: Rethinking Neural Implicit Surfaces with $α$ -NeuS**|Haoran Zhang et.al.|[2411.05362](http://arxiv.org/abs/2411.05362)|**[link](https://github.com/728388808/alpha-neus)**|
|**2024-10-29**|**LiVisSfM: Accurate and Robust Structure-from-Motion with LiDAR and Visual Cues**|Hanqing Jiang et.al.|[2410.22213](http://arxiv.org/abs/2410.22213)|null|
|**2025-02-18**|**A Robust and Efficient Visual-Inertial Initialization with Probabilistic Normal Epipolar Constraint**|Changshi Mu et.al.|[2410.19473](http://arxiv.org/abs/2410.19473)|**[link](https://github.com/mucs714/drt-pnec)**|
|**2024-10-30**|**Large Spatial Model: End-to-end Unposed Images to Semantic 3D**|Zhiwen Fan et.al.|[2410.18956](http://arxiv.org/abs/2410.18956)|**[link](https://github.com/NVlabs/LSM)**|
|**2024-10-23**|**PLGS: Robust Panoptic Lifting with 3D Gaussian Splatting**|Yu Wang et.al.|[2410.17505](http://arxiv.org/abs/2410.17505)|null|
|**2024-10-20**|**Neural Active Structure-from-Motion in Dark and Textureless Environment**|Kazuto Ichimaru et.al.|[2410.15378](http://arxiv.org/abs/2410.15378)|null|
|**2024-10-16**|**Gravity-aligned Rotation Averaging with Circular Regression**|Linfei Pan et.al.|[2410.12763](http://arxiv.org/abs/2410.12763)|**[link](https://github.com/colmap/glomap)**|
|**2024-10-15**|**SplatPose+: Real-time Image-Based Pose-Agnostic 3D Anomaly Detection**|Yizhe Liu et.al.|[2410.12080](http://arxiv.org/abs/2410.12080)|**[link](https://github.com/Yizhe-Liu/SplatPosePlus)**|
|**2024-10-15**|**LoGS: Visual Localization via Gaussian Splatting with Fewer Training Images**|Yuzhou Cheng et.al.|[2410.11505](http://arxiv.org/abs/2410.11505)|null|
|**2024-10-12**|**Leveraging Semantic Cues from Foundation Vision Models for Enhanced Local Feature Correspondence**|Felipe Cadar et.al.|[2410.09533](http://arxiv.org/abs/2410.09533)|**[link](https://github.com/verlab/DescriptorReasoning_ACCV_2024)**|
|**2024-10-09**|**Surgical Depth Anything: Depth Estimation for Surgical Scenes using Foundation Models**|Ange Lou et.al.|[2410.07434](http://arxiv.org/abs/2410.07434)|null|
|**2024-10-08**|**Are Minimal Radial Distortion Solvers Necessary for Relative Pose Estimation?**|Charalambos Tzamos et.al.|[2410.05984](http://arxiv.org/abs/2410.05984)|**[link](https://github.com/kocurvik/rd)**|
|**2024-10-04**|**Refinement of Monocular Depth Maps via Multi-View Differentiable Rendering**|Laura Fink et.al.|[2410.03861](http://arxiv.org/abs/2410.03861)|**[link](https://github.com/lorafib/ref_depth)**|
|**2024-10-01**|**Seamless Augmented Reality Integration in Arthroscopy: A Pipeline for Articular Reconstruction and Guidance**|Hongchao Shu et.al.|[2410.00386](http://arxiv.org/abs/2410.00386)|null|
|**2024-09-29**|**Robust Incremental Structure-from-Motion with Hybrid Features**|Shaohui Liu et.al.|[2409.19811](http://arxiv.org/abs/2409.19811)|null|
|**2024-09-27**|**MASt3R-SfM: a Fully-Integrated Solution for Unconstrained Structure-from-Motion**|Bardienus Duisterhof et.al.|[2409.19152](http://arxiv.org/abs/2409.19152)|null|
|**2024-02-18**|**A Robust Error-Resistant View Selection Method for 3D Reconstruction**|Shaojie Zhang et.al.|[2402.11431](http://arxiv.org/abs/2402.11431)|null|
|**2024-02-17**|**Dense Matchers for Dense Tracking**|Tomáš Jelínek et.al.|[2402.11287](http://arxiv.org/abs/2402.11287)|null|
|**2024-01-31**|**Local Feature Matching Using Deep Learning: A Survey**|Shibiao Xu et.al.|[2401.17592](http://arxiv.org/abs/2401.17592)|null|
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
|**2024-02-14**|**On-the-Fly SfM: What you capture is What you get**|Zongqian Zhan et.al.|[2309.11883](http://arxiv.org/abs/2309.11883)|**[link](https://github.com/RayShark0605/On_the_fly_SfM)**|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## IMU

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-03-17**|**WMINet: A Wheel-Mounted Inertial Learning Approach For Mobile-Robot Positioning**|Gal Versano et.al.|[2503.13568](http://arxiv.org/abs/2503.13568)|null|
|**2025-01-26**|**AirIO: Learning Inertial Odometry with Enhanced IMU Feature Observability**|Yuheng Qiu et.al.|[2501.15659](http://arxiv.org/abs/2501.15659)|null|
|**2024-07-23**|**Deep Learning Assisted Inertial Dead Reckoning and Fusion**|Dror Hurwitz et.al.|[2407.16387](http://arxiv.org/abs/2407.16387)|null|
|**2024-04-24**|**3D Freehand Ultrasound using Visual Inertial and Deep Inertial Odometry for Measuring Patellar Tracking**|Russell Buchanan et.al.|[2404.15847](http://arxiv.org/abs/2404.15847)|null|
|**2024-12-01**|**DoorINet: Door Heading Prediction through Inertial Deep Learning**|Aleksei Zakharchenko et.al.|[2402.09427](http://arxiv.org/abs/2402.09427)|**[link](https://github.com/ansfl/doorinet)**|
|**2023-09-18**|**Learning Inertial Parameter Identification of Unknown Object with Humanoid Robot using Sim-to-Real Adaptation**|Donghoon Baek et.al.|[2309.09810](http://arxiv.org/abs/2309.09810)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Transformer

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2004-07-18**|**Electrodynamics under a Possible Alternative to the Lorentz Transformation**|Gabriel D. Puccini et.al.|[physics/0407096](http://arxiv.org/abs/physics/0407096)|null|
|**1997-07-02**|**A Derivation of Three-Dimensional Inertial Transformations**|Francois Goy et.al.|[gr-qc/9707004](http://arxiv.org/abs/gr-qc/9707004)|null|
|**2003-01-21**|**Gravitation as Anholonomy**|R. Aldrovandi et.al.|[gr-qc/0301077](http://arxiv.org/abs/gr-qc/0301077)|null|
|**2025-03-31**|**SALT: A Flexible Semi-Automatic Labeling Tool for General LiDAR Point Clouds with Cross-Scene Adaptability and 4D Consistency**|Yanbo Wang et.al.|[2503.23980](http://arxiv.org/abs/2503.23980)|**[link](https://github.com/Cavendish518/SALT)**|
|**2024-12-20**|**iRadar: Synthesizing Millimeter-Waves from Wearable Inertial Inputs for Human Gesture Sensing**|Huanqi Yang et.al.|[2412.15980](http://arxiv.org/abs/2412.15980)|null|
|**2024-10-29**|**Inertial Transformations and the Nonexistence of Tachyons for Spacetime Dimension Greater than Two**|David Acton et.al.|[2410.22025](http://arxiv.org/abs/2410.22025)|null|
|**2024-12-10**|**LiGAR: LiDAR-Guided Hierarchical Transformer for Multi-Modal Group Activity Recognition**|Naga Venkata Sai Raviteja Chappa et.al.|[2410.21108](http://arxiv.org/abs/2410.21108)|null|
|**2023-03-03**|**RIOT: Recursive Inertial Odometry Transformer for Localisation from Low-Cost IMU Measurements**|James Brotchie et.al.|[2303.01641](http://arxiv.org/abs/2303.01641)|null|
|**2023-10-11**|**MMTSA: Multimodal Temporal Segment Attention Network for Efficient Human Activity Recognition**|Ziqi Gao et.al.|[2210.09222](http://arxiv.org/abs/2210.09222)|**[link](https://github.com/thuhci/MMTSA)**|
|**2022-12-08**|**Transformer Inertial Poser: Real-time Human Motion Reconstruction from Sparse IMUs with Simultaneous Terrain Generation**|Yifeng Jiang et.al.|[2203.15720](http://arxiv.org/abs/2203.15720)|**[link](https://github.com/jyf588/transformer-inertial-poser)**|
|**2021-05-28**|**Inertial Sensor Data To Image Encoding For Human Action Recognition**|Zeeshan Ahmad et.al.|[2105.13533](http://arxiv.org/abs/2105.13533)|null|
|**2021-03-17**|**Inertial based Integration with Transformed INS Mechanization in Earth Frame**|Lubin Chang et.al.|[2103.02229](http://arxiv.org/abs/2103.02229)|null|
|**2021-05-07**|**The group structure of dynamical transformations between quantum reference frames**|Angel Ballesteros et.al.|[2012.15769](http://arxiv.org/abs/2012.15769)|null|
|**2018-01-29**|**Visual-Inertial Odometry-enhanced Geometrically Stable ICP for Mapping Applications using Aerial Robots**|Tung Dang et.al.|[1801.08228](http://arxiv.org/abs/1801.08228)|null|
|**2017-10-19**|**SqueezeSeg: Convolutional Neural Nets with Recurrent CRF for Real-Time Road-Object Segmentation from 3D LiDAR Point Cloud**|Bichen Wu et.al.|[1710.07368](http://arxiv.org/abs/1710.07368)|null|
|**2016-04-27**|**Observability-Aware Trajectory Optimization for Self-Calibration with Application to UAVs**|Karol Hausman et.al.|[1604.07905](http://arxiv.org/abs/1604.07905)|null|
|**2013-11-25**|**Clifford Algebra and Space-Time Transformations: Lorentz Transformation and Inertial Transformation**|R. de Oliveira et.al.|[1311.6378](http://arxiv.org/abs/1311.6378)|null|
|**2008-03-06**|**Special Relativity in Quantum Phase Space**|Daniela Dragoman et.al.|[0803.0972](http://arxiv.org/abs/0803.0972)|null|

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## NeRF

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-18**|**SLAM&Render: A Benchmark for the Intersection Between Neural Rendering, Gaussian Splatting and SLAM**|Samuel Cerezo et.al.|[2504.13713](http://arxiv.org/abs/2504.13713)|**[link](https://github.com/samuel-cerezo/SLAM-Render)**|
|**2025-04-16**|**BEV-GS: Feed-forward Gaussian Splatting in Bird's-Eye-View for Road Reconstruction**|Wenhua Wu et.al.|[2504.13207](http://arxiv.org/abs/2504.13207)|null|
|**2025-04-17**|**GSAC: Leveraging Gaussian Splatting for Photorealistic Avatar Creation with Unity Integration**|Rendong Zhang et.al.|[2504.12999](http://arxiv.org/abs/2504.12999)|null|
|**2025-04-16**|**R-Meshfusion: Reinforcement Learning Powered Sparse-View Mesh Reconstruction with Diffusion Priors**|Haoyang Wang et.al.|[2504.11946](http://arxiv.org/abs/2504.11946)|null|
|**2025-04-15**|**LL-Gaussian: Low-Light Scene Reconstruction and Enhancement via Gaussian Splatting for Novel View Synthesis**|Hao Sun et.al.|[2504.10331](http://arxiv.org/abs/2504.10331)|null|
|**2025-04-14**|**MCBlock: Boosting Neural Radiance Field Training Speed by MCTS-based Dynamic-Resolution Ray Sampling**|Yunpeng Tan et.al.|[2504.09878](http://arxiv.org/abs/2504.09878)|null|
|**2025-04-14**|**NeRF-Based Transparent Object Grasping Enhanced by Shape Priors**|Yi Han et.al.|[2504.09868](http://arxiv.org/abs/2504.09868)|null|
|**2025-04-11**|**HAL-NeRF: High Accuracy Localization Leveraging Neural Radiance Fields**|Asterios Reppas et.al.|[2504.08901](http://arxiv.org/abs/2504.08901)|null|
|**2025-04-09**|**Wheat3DGS: In-field 3D Reconstruction, Instance Segmentation and Phenotyping of Wheat Heads with Gaussian Splatting**|Daiwei Zhang et.al.|[2504.06978](http://arxiv.org/abs/2504.06978)|null|
|**2025-04-09**|**S-EO: A Large-Scale Dataset for Geometry-Aware Shadow Detection in Remote Sensing Applications**|Masquil Elías et.al.|[2504.06920](http://arxiv.org/abs/2504.06920)|null|
|**2025-04-09**|**SVG-IR: Spatially-Varying Gaussian Splatting for Inverse Rendering**|Hanxiao Sun et.al.|[2504.06815](http://arxiv.org/abs/2504.06815)|null|
|**2025-04-08**|**Meta-Continual Learning of Neural Fields**|Seungyoon Woo et.al.|[2504.05806](http://arxiv.org/abs/2504.05806)|null|
|**2025-04-08**|**SE4Lip: Speech-Lip Encoder for Talking Head Synthesis to Solve Phoneme-Viseme Alignment Ambiguity**|Yihuan Huang et.al.|[2504.05803](http://arxiv.org/abs/2504.05803)|null|
|**2025-04-08**|**InvNeRF-Seg: Fine-Tuning a Pre-Trained NeRF for 3D Object Segmentation**|Jiangsan Zhao et.al.|[2504.05751](http://arxiv.org/abs/2504.05751)|null|
|**2025-04-07**|**DeclutterNeRF: Generative-Free 3D Scene Recovery for Occlusion Removal**|Wanzhou Liu et.al.|[2504.04679](http://arxiv.org/abs/2504.04679)|null|
|**2025-04-06**|**Thermoxels: a voxel-based method to generate simulation-ready 3D thermal models**|Etienne Chassaing et.al.|[2504.04448](http://arxiv.org/abs/2504.04448)|null|
|**2025-04-04**|**NeRFlex: Resource-aware Real-time High-quality Rendering of Complex Scenes on Mobile Devices**|Zhe Wang et.al.|[2504.03415](http://arxiv.org/abs/2504.03415)|null|
|**2025-04-03**|**MultiNeRF: Multiple Watermark Embedding for Neural Radiance Fields**|Yash Kulthe et.al.|[2504.02517](http://arxiv.org/abs/2504.02517)|null|
|**2025-04-03**|**LPA3D: 3D Room-Level Scene Generation from In-the-Wild Images**|Ming-Jia Yang et.al.|[2504.02337](http://arxiv.org/abs/2504.02337)|null|
|**2025-04-01**|**OccludeNeRF: Geometric-aware 3D Scene Inpainting with Collaborative Score Distillation in NeRF**|Jingyu Shi et.al.|[2504.02007](http://arxiv.org/abs/2504.02007)|null|
|**2025-04-02**|**Diffusion-Guided Gaussian Splatting for Large-Scale Unconstrained 3D Reconstruction and Novel View Synthesis**|Niluthpol Chowdhury Mithun et.al.|[2504.01960](http://arxiv.org/abs/2504.01960)|null|
|**2025-04-02**|**BOGausS: Better Optimized Gaussian Splatting**|Stéphane Pateux et.al.|[2504.01844](http://arxiv.org/abs/2504.01844)|null|
|**2025-04-09**|**FIORD: A Fisheye Indoor-Outdoor Dataset with LIDAR Ground Truth for 3D Scene Reconstruction and Benchmarking**|Ulas Gunes et.al.|[2504.01732](http://arxiv.org/abs/2504.01732)|null|
|**2025-04-02**|**RealityAvatar: Towards Realistic Loose Clothing Modeling in Animatable 3D Gaussian Avatars**|Yahui Li et.al.|[2504.01559](http://arxiv.org/abs/2504.01559)|null|
|**2025-04-02**|**Luminance-GS: Adapting 3D Gaussian Splatting to Challenging Lighting Conditions with View-Adaptive Curve Adjustment**|Ziteng Cui et.al.|[2504.01503](http://arxiv.org/abs/2504.01503)|**[link](https://github.com/cuiziteng/Luminance-GS)**|
|**2025-04-07**|**Neural Pruning for 3D Scene Reconstruction: Efficient NeRF Acceleration**|Tianqi Ding et.al.|[2504.00950](http://arxiv.org/abs/2504.00950)|null|
|**2025-04-09**|**NeuRadar: Neural Radiance Fields for Automotive Radar Point Clouds**|Mahan Rafidashti et.al.|[2504.00859](http://arxiv.org/abs/2504.00859)|null|
|**2025-03-31**|**NeRF-Based defect detection**|Tianqi et.al.|[2504.00270](http://arxiv.org/abs/2504.00270)|null|
|**2025-03-31**|**LITA-GS: Illumination-Agnostic Novel View Synthesis via Reference-Free 3D Gaussian Splatting and Physical Priors**|Han Zhou et.al.|[2504.00219](http://arxiv.org/abs/2504.00219)|null|
|**2025-03-31**|**ERUPT: Efficient Rendering with Unposed Patch Transformer**|Maxim V. Shugaev et.al.|[2503.24374](http://arxiv.org/abs/2503.24374)|null|
|**2025-03-29**|**NeuralGS: Bridging Neural Fields and 3D Gaussian Splatting for Compact 3D Representations**|Zhenyu Tang et.al.|[2503.23162](http://arxiv.org/abs/2503.23162)|null|
|**2025-03-26**|**Dual Audio-Centric Modality Coupling for Talking Head Generation**|Ao Fu et.al.|[2503.22728](http://arxiv.org/abs/2503.22728)|null|
|**2025-03-28**|**ABC-GS: Alignment-Based Controllable Style Transfer for 3D Gaussian Splatting**|Wenjie Liu et.al.|[2503.22218](http://arxiv.org/abs/2503.22218)|null|
|**2025-04-15**|**SC-NeRF: NeRF-based Point Cloud Reconstruction using a Stationary Camera for Agricultural Applications**|Kibon Ku et.al.|[2503.21958](http://arxiv.org/abs/2503.21958)|null|
|**2025-03-27**|**Refined Geometry-guided Head Avatar Reconstruction from Monocular RGB Video**|Pilseo Park et.al.|[2503.21886](http://arxiv.org/abs/2503.21886)|null|
|**2025-03-27**|**HS-SLAM: Hybrid Representation with Structural Supervision for Improved Dense SLAM**|Ziren Gong et.al.|[2503.21778](http://arxiv.org/abs/2503.21778)|null|
|**2025-04-01**|**RainyGS: Efficient Rain Synthesis with Physically-Based Gaussian Splatting**|Qiyu Dai et.al.|[2503.21442](http://arxiv.org/abs/2503.21442)|null|
|**2025-03-28**|**LandMarkSystem Technical Report**|Zhenxiang Ma et.al.|[2503.21364](http://arxiv.org/abs/2503.21364)|**[link](https://github.com/internlandmark/landmarksystem)**|
|**2025-03-27**|**UGNA-VPR: A Novel Training Paradigm for Visual Place Recognition Based on Uncertainty-Guided NeRF Augmentation**|Yehui Shen et.al.|[2503.21338](http://arxiv.org/abs/2503.21338)|**[link](https://github.com/nubot-nudt/ugna-vpr)**|
|**2025-03-25**|**CoMapGS: Covisibility Map-based Gaussian Splatting for Sparse Novel View Synthesis**|Youngkyoon Jang et.al.|[2503.20998](http://arxiv.org/abs/2503.20998)|null|
|**2025-03-26**|**AccidentSim: Generating Physically Realistic Vehicle Collision Videos from Real-World Accident Reports**|Xiangwen Zhang et.al.|[2503.20654](http://arxiv.org/abs/2503.20654)|null|
|**2025-03-26**|**EVolSplat: Efficient Volume-based Gaussian Splatting for Urban View Synthesis**|Sheng Miao et.al.|[2503.20168](http://arxiv.org/abs/2503.20168)|null|
|**2025-03-25**|**Learning Scene-Level Signed Directional Distance Function with Ellipsoidal Priors and Neural Residuals**|Zhirui Dai et.al.|[2503.20066](http://arxiv.org/abs/2503.20066)|null|
|**2025-03-25**|**MultimodalStudio: A Heterogeneous Sensor Dataset and Framework for Neural Rendering across Multiple Imaging Modalities**|Federico Lincetto et.al.|[2503.19673](http://arxiv.org/abs/2503.19673)|null|
|**2025-03-24**|**NexusGS: Sparse View Synthesis with Epipolar Depth Priors in 3D Gaussian Splatting**|Yulong Zheng et.al.|[2503.18794](http://arxiv.org/abs/2503.18794)|null|
|**2025-03-25**|**LookCloser: Frequency-aware Radiance Field for Tiny-Detail Scene**|Xiaoyu Zhang et.al.|[2503.18513](http://arxiv.org/abs/2503.18513)|null|
|**2025-03-30**|**NeRFPrior: Learning Neural Radiance Field as a Prior for Indoor Scene Reconstruction**|Wenyuan Zhang et.al.|[2503.18361](http://arxiv.org/abs/2503.18361)|null|
|**2025-03-23**|**End-to-End Implicit Neural Representations for Classification**|Alexander Gielisse et.al.|[2503.18123](http://arxiv.org/abs/2503.18123)|**[link](https://github.com/sandergielisse/mwt)**|
|**2025-03-23**|**Unraveling the Effects of Synthetic Data on End-to-End Autonomous Driving**|Junhao Ge et.al.|[2503.18108](http://arxiv.org/abs/2503.18108)|**[link](https://github.com/cancaries/SceneCrafter)**|
|**2025-03-23**|**PanopticSplatting: End-to-End Panoptic Gaussian Splatting**|Yuxuan Xie et.al.|[2503.18073](http://arxiv.org/abs/2503.18073)|null|
|**2025-03-21**|**Splat-LOAM: Gaussian Splatting LiDAR Odometry and Mapping**|Emanuele Giacomini et.al.|[2503.17491](http://arxiv.org/abs/2503.17491)|**[link](https://github.com/rvp-group/Splat-LOAM)**|
|**2025-03-21**|**FFaceNeRF: Few-shot Face Editing in Neural Radiance Fields**|Kwan Yun et.al.|[2503.17095](http://arxiv.org/abs/2503.17095)|**[link](https://github.com/kwanyun/FFaceNeRF)**|
|**2025-03-21**|**DroneSplat: 3D Gaussian Splatting for Robust 3D Reconstruction from In-the-Wild Drone Imagery**|Jiadong Tang et.al.|[2503.16964](http://arxiv.org/abs/2503.16964)|null|
|**2025-03-20**|**Digitally Prototype Your Eye Tracker: Simulating Hardware Performance using 3D Synthetic Data**|Esther Y. H. Lin et.al.|[2503.16742](http://arxiv.org/abs/2503.16742)|null|
|**2025-03-20**|**Enhancing Close-up Novel View Synthesis via Pseudo-labeling**|Jiatong Xia et.al.|[2503.15908](http://arxiv.org/abs/2503.15908)|**[link](https://github.com/JiatongXia/Pseudo-Labeling)**|
|**2025-03-19**|**SPNeRF: Open Vocabulary 3D Neural Scene Segmentation with Superpoints**|Weiwen Hu et.al.|[2503.15712](http://arxiv.org/abs/2503.15712)|null|
|**2025-03-19**|**DiffPortrait360: Consistent Portrait Diffusion for 360 View Synthesis**|Yuming Gu et.al.|[2503.15667](http://arxiv.org/abs/2503.15667)|**[link](https://github.com/freedomgu/diffportrait360)**|
|**2025-03-19**|**GO-N3RDet: Geometry Optimized NeRF-enhanced 3D Object Detector**|Zechuan Li et.al.|[2503.15211](http://arxiv.org/abs/2503.15211)|null|
|**2025-03-19**|**MultiBARF: Integrating Imagery of Different Wavelength Regions by Using Neural Radiance Fields**|Kana Kurata et.al.|[2503.15070](http://arxiv.org/abs/2503.15070)|null|
|**2025-03-19**|**3D Engine-ready Photorealistic Avatars via Dynamic Textures**|Yifan Wang et.al.|[2503.14943](http://arxiv.org/abs/2503.14943)|null|
|**2025-03-19**|**ClimateGS: Real-Time Climate Simulation with 3D Gaussian Style Transfer**|Yuezhen Xie et.al.|[2503.14845](http://arxiv.org/abs/2503.14845)|null|
|**2025-03-18**|**Segmentation-Guided Neural Radiance Fields for Novel Street View Synthesis**|Yizhou Li et.al.|[2503.14219](http://arxiv.org/abs/2503.14219)|null|
|**2025-03-17**|**Improving Geometric Consistency for 360-Degree Neural Radiance Fields in Indoor Scenarios**|Iryna Repinetska et.al.|[2503.13710](http://arxiv.org/abs/2503.13710)|null|
|**2025-03-17**|**TriDF: Triplane-Accelerated Density Fields for Few-Shot Remote Sensing Novel View Synthesis**|Jiaming Kang et.al.|[2503.13347](http://arxiv.org/abs/2503.13347)|null|
|**2025-03-17**|**DeGauss: Dynamic-Static Decomposition with Gaussian Splatting for Distractor-free 3D Reconstruction**|Rui Wang et.al.|[2503.13176](http://arxiv.org/abs/2503.13176)|null|
|**2025-03-17**|**DivCon-NeRF: Generating Augmented Rays with Diversity and Consistency for Few-shot View Synthesis**|Ingyun Lee et.al.|[2503.12947](http://arxiv.org/abs/2503.12947)|null|
|**2025-03-15**|**FA-BARF: Frequency Adapted Bundle-Adjusting Neural Radiance Fields**|Rui Qian et.al.|[2503.12086](http://arxiv.org/abs/2503.12086)|null|
|**2025-03-14**|**Industrial-Grade Sensor Simulation via Gaussian Splatting: A Modular Framework for Scalable Editing and Full-Stack Validation**|Xianming Zeng et.al.|[2503.11731](http://arxiv.org/abs/2503.11731)|null|
|**2025-03-13**|**Flow-NeRF: Joint Learning of Geometry, Poses, and Dense Flow within Unified Neural Representations**|Xunzhi Zheng et.al.|[2503.10464](http://arxiv.org/abs/2503.10464)|null|
|**2025-03-13**|**AI-assisted 3D Preservation and Reconstruction of Temple Arts**|Naai-Jung Shih et.al.|[2503.10031](http://arxiv.org/abs/2503.10031)|null|
|**2025-03-12**|**Hybrid Rendering for Multimodal Autonomous Driving: Merging Neural and Physics-Based Simulation**|Máté Tóth et.al.|[2503.09464](http://arxiv.org/abs/2503.09464)|null|
|**2025-03-11**|**GAS-NeRF: Geometry-Aware Stylization of Dynamic Radiance Fields**|Nhat Phuong Anh Vu et.al.|[2503.08483](http://arxiv.org/abs/2503.08483)|null|
|**2025-03-24**|**Uni-Gaussians: Unifying Camera and Lidar Simulation with Gaussians for Dynamic Driving Scenarios**|Zikang Yuan et.al.|[2503.08317](http://arxiv.org/abs/2503.08317)|null|
|**2025-03-11**|**GigaSLAM: Large-Scale Monocular SLAM with Hierachical Gaussian Splats**|Kai Deng et.al.|[2503.08071](http://arxiv.org/abs/2503.08071)|**[link](https://github.com/DengKaiCQ/GigaSLAM)**|
|**2025-03-11**|**NeRF-VIO: Map-Based Visual-Inertial Odometry with Initialization Leveraging Neural Radiance Fields**|Yanyu Zhang et.al.|[2503.07952](http://arxiv.org/abs/2503.07952)|null|
|**2025-03-10**|**Neural Radiance and Gaze Fields for Visual Attention Modeling in 3D Environments**|Andrei Chubarau et.al.|[2503.07828](http://arxiv.org/abs/2503.07828)|null|
|**2025-03-10**|**CATPlan: Loss-based Collision Prediction in End-to-End Autonomous Driving**|Ziliang Xiong et.al.|[2503.07425](http://arxiv.org/abs/2503.07425)|null|
|**2025-03-08**|**Feature-EndoGaussian: Feature Distilled Gaussian Splatting in Surgical Deformable Scene Reconstruction**|Kai Li et.al.|[2503.06161](http://arxiv.org/abs/2503.06161)|null|
|**2025-03-08**|**SecureGS: Boosting the Security and Fidelity of 3D Gaussian Splatting Steganography**|Xuanyu Zhang et.al.|[2503.06118](http://arxiv.org/abs/2503.06118)|null|
|**2025-03-08**|**NeuraLoc: Visual Localization in Neural Implicit Map with Dual Complementary Features**|Hongjia Zhai et.al.|[2503.06117](http://arxiv.org/abs/2503.06117)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

## Occupancy

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2025-04-18**|**LMPOcc: 3D Semantic Occupancy Prediction Utilizing Long-Term Memory Prior from Historical Traversals**|Shanshuai Yuan et.al.|[2504.13596](http://arxiv.org/abs/2504.13596)|null|
|**2025-04-18**|**Rethinking Temporal Fusion with a Unified Gradient Descent View for 3D Semantic Occupancy Prediction**|Dubing Chen et.al.|[2504.12959](http://arxiv.org/abs/2504.12959)|**[link](https://github.com/cdb342/gdfusion)**|
|**2025-04-17**|**Self-Supervised Pre-training with Combined Datasets for 3D Perception in Autonomous Driving**|Shumin Wang et.al.|[2504.12709](http://arxiv.org/abs/2504.12709)|null|
|**2025-04-14**|**Communication-aware Hierarchical Map Compression of Time-Varying Environments for Mobile Robots**|Daniel T. Larsson et.al.|[2504.10751](http://arxiv.org/abs/2504.10751)|null|
|**2025-04-14**|**AGO: Adaptive Grounding for Open World 3D Occupancy Prediction**|Peizheng Li et.al.|[2504.10117](http://arxiv.org/abs/2504.10117)|null|
|**2025-04-13**|**EmbodiedOcc++: Boosting Embodied 3D Occupancy Prediction with Plane Regularization and Uncertainty Sampler**|Hao Wang et.al.|[2504.09540](http://arxiv.org/abs/2504.09540)|null|
|**2025-04-12**|**IMPACT: Behavioral Intention-aware Multimodal Trajectory Prediction with Adaptive Context Trimming**|Jiawei Sun et.al.|[2504.09103](http://arxiv.org/abs/2504.09103)|null|
|**2025-04-10**|**DGOcc: Depth-aware Global Query-based Network for Monocular 3D Occupancy Prediction**|Xu Zhao et.al.|[2504.07524](http://arxiv.org/abs/2504.07524)|null|
|**2025-04-09**|**Towards Efficient Roadside LiDAR Deployment: A Fast Surrogate Metric Based on Entropy-Guided Visibility**|Yuze Jiang et.al.|[2504.06772](http://arxiv.org/abs/2504.06772)|null|
|**2025-04-09**|**Collision avoidance from monocular vision trained with novel view synthesis**|Valentin Tordjman--Levavasseur et.al.|[2504.06651](http://arxiv.org/abs/2504.06651)|null|
|**2025-04-07**|**Inverse++: Vision-Centric 3D Semantic Occupancy Prediction Assisted with 3D Object Detection**|Zhenxing Ming et.al.|[2504.04732](http://arxiv.org/abs/2504.04732)|null|
|**2025-04-03**|**MinkOcc: Towards real-time label-efficient semantic occupancy prediction**|Samuel Sze et.al.|[2504.02270](http://arxiv.org/abs/2504.02270)|null|
|**2025-03-26**|**Omnidirectional Depth-Aided Occupancy Prediction based on Cylindrical Voxel for Autonomous Driving**|Chaofan Wu et.al.|[2504.01023](http://arxiv.org/abs/2504.01023)|null|
|**2025-03-31**|**UniOcc: A Unified Benchmark for Occupancy Forecasting and Prediction in Autonomous Driving**|Yuping Wang et.al.|[2503.24381](http://arxiv.org/abs/2503.24381)|**[link](https://github.com/tasl-lab/uniocc)**|
|**2025-03-30**|**Improving Indoor Localization Accuracy by Using an Efficient Implicit Neural Map Representation**|Haofei Kuang et.al.|[2503.23480](http://arxiv.org/abs/2503.23480)|**[link](https://github.com/prbonn/enm-mcl)**|
|**2025-03-28**|**Mitigating Trade-off: Stream and Query-guided Aggregation for Efficient and Effective 3D Occupancy Prediction**|Seokha Moon et.al.|[2503.22087](http://arxiv.org/abs/2503.22087)|**[link](https://github.com/moonseokha/streamocc)**|
|**2025-03-23**|**M3Net: Multimodal Multi-task Learning for 3D Detection, Segmentation, and Occupancy Prediction in Autonomous Driving**|Xuesong Chen et.al.|[2503.18100](http://arxiv.org/abs/2503.18100)|null|
|**2025-03-21**|**Targetless 6DoF Calibration of LiDAR and 2D Scanning Radar Based on Cylindrical Occupancy**|Weimin Wang et.al.|[2503.17002](http://arxiv.org/abs/2503.17002)|null|
|**2025-03-20**|**SA-Occ: Satellite-Assisted 3D Occupancy Prediction in Real World**|Chen Chen et.al.|[2503.16399](http://arxiv.org/abs/2503.16399)|**[link](https://github.com/chenchen235/sa-occ)**|
|**2025-03-19**|**GASP: Unifying Geometric and Semantic Self-Supervised Pre-training for Autonomous Driving**|William Ljungbergh et.al.|[2503.15672](http://arxiv.org/abs/2503.15672)|null|
|**2025-03-19**|**3D Occupancy Prediction with Low-Resolution Queries via Prototype-aware View Transformation**|Gyeongrok Oh et.al.|[2503.15185](http://arxiv.org/abs/2503.15185)|null|
|**2025-03-15**|**A Simple and Explainable Model for Park-and-Ride Car Park Occupancy Prediction**|Andreas Kaltenbrunner et.al.|[2503.12044](http://arxiv.org/abs/2503.12044)|**[link](https://github.com/aig-upf/car-park)**|
|**2025-03-13**|**OCCUQ: Exploring Efficient Uncertainty Quantification for 3D Occupancy Prediction**|Severin Heidrich et.al.|[2503.10605](http://arxiv.org/abs/2503.10605)|**[link](https://github.com/ika-rwth-aachen/occuq)**|
|**2025-03-13**|**TGP: Two-modal occupancy prediction with 3D Gaussian and sparse points for 3D Environment Awareness**|Mu Chen et.al.|[2503.09941](http://arxiv.org/abs/2503.09941)|null|
|**2025-03-12**|**CleverDistiller: Simple and Spatially Consistent Cross-modal Distillation**|Hariprasath Govindarajan et.al.|[2503.09878](http://arxiv.org/abs/2503.09878)|null|
|**2025-03-11**|**TT-GaussOcc: Test-Time Compute for Self-Supervised Occupancy Prediction via Spatio-Temporal Gaussian Splatting**|Fengyi Zhang et.al.|[2503.08485](http://arxiv.org/abs/2503.08485)|null|
|**2025-03-11**|**TrackOcc: Camera-based 4D Panoptic Occupancy Tracking**|Zhuoguang Chen et.al.|[2503.08471](http://arxiv.org/abs/2503.08471)|**[link](https://github.com/tsinghua-mars-lab/trackocc)**|
|**2025-03-10**|**LTLCodeGen: Code Generation of Syntactically Correct Temporal Logic for Robot Task Planning**|Behrad Rabiei et.al.|[2503.07902](http://arxiv.org/abs/2503.07902)|null|
|**2025-03-10**|**Robusto-1 Dataset: Comparing Humans and VLMs on real out-of-distribution Autonomous Driving VQA from Peru**|Dunant Cusipuma et.al.|[2503.07587](http://arxiv.org/abs/2503.07587)|null|
|**2025-03-10**|**Learning A Zero-shot Occupancy Network from Vision Foundation Models via Self-supervised Adaptation**|Sihao Lin et.al.|[2503.07125](http://arxiv.org/abs/2503.07125)|null|
|**2025-03-09**|**On the Mutual Influence of Gender and Occupation in LLM Representations**|Haozhe An et.al.|[2503.06792](http://arxiv.org/abs/2503.06792)|null|
|**2025-03-07**|**Fake It To Make It: Virtual Multiviews to Enhance Monocular Indoor Semantic Scene Completion**|Anith Selvakumar et.al.|[2503.05086](http://arxiv.org/abs/2503.05086)|null|
|**2025-03-06**|**Manboformer: Learning Gaussian Representations via Spatial-temporal Attention Mechanism**|Ziyue Zhao et.al.|[2503.04863](http://arxiv.org/abs/2503.04863)|null|
|**2025-03-06**|**H3O: Hyper-Efficient 3D Occupancy Prediction with Heterogeneous Supervision**|Yunxiao Shi et.al.|[2503.04059](http://arxiv.org/abs/2503.04059)|null|
|**2025-02-26**|**RL-OGM-Parking: Lidar OGM-Based Hybrid Reinforcement Learning Planner for Autonomous Parking**|Zhitao Wang et.al.|[2502.18846](http://arxiv.org/abs/2502.18846)|null|
|**2025-02-23**|**Path Planning using Instruction-Guided Probabilistic Roadmaps**|Jiaqi Bao et.al.|[2502.16515](http://arxiv.org/abs/2502.16515)|null|
|**2025-02-20**|**LXLv2: Enhanced LiDAR Excluded Lean 3D Object Detection with Fusion of 4D Radar and Camera**|Weiyi Xiong et.al.|[2502.14503](http://arxiv.org/abs/2502.14503)|null|
|**2025-02-20**|**OG-Gaussian: Occupancy Based Street Gaussians for Autonomous Driving**|Yedong Shen et.al.|[2502.14235](http://arxiv.org/abs/2502.14235)|null|
|**2025-02-19**|**Inter3D: A Benchmark and Strong Baseline for Human-Interactive 3D Object Reconstruction**|Gan Chen et.al.|[2502.14004](http://arxiv.org/abs/2502.14004)|**[link](https://github.com/Inter3D-ui/Inter3D)**|
|**2025-02-16**|**MC-BEVRO: Multi-Camera Bird Eye View Road Occupancy Detection for Traffic Monitoring**|Arpitsinh Vaghela et.al.|[2502.11287](http://arxiv.org/abs/2502.11287)|null|
|**2025-02-13**|**Generalizable Reinforcement Learning with Biologically Inspired Hyperdimensional Occupancy Grid Maps for Exploration and Goal-Directed Path Planning**|Shay Snyder et.al.|[2502.09393](http://arxiv.org/abs/2502.09393)|null|
|**2025-02-11**|**Semi-Supervised Vision-Centric 3D Occupancy World Model for Autonomous Driving**|Xiang Li et.al.|[2502.07309](http://arxiv.org/abs/2502.07309)|**[link](https://github.com/getterupper/PreWorld)**|
|**2025-02-14**|**Occupancy-SLAM: An Efficient and Robust Algorithm for Simultaneously Optimizing Robot Poses and Occupancy Map**|Yingyu Wang et.al.|[2502.06292](http://arxiv.org/abs/2502.06292)|**[link](https://github.com/WANGYINGYU/Occupancy-SLAM)**|
|**2025-03-19**|**GaussRender: Learning 3D Occupancy with Gaussian Rendering**|Loïck Chambon et.al.|[2502.05040](http://arxiv.org/abs/2502.05040)|**[link](https://github.com/valeoai/gaussrender)**|
|**2025-01-29**|**Watch Your STEPP: Semantic Traversability Estimation using Pose Projected Features**|Sebastian Ægidius et.al.|[2501.17594](http://arxiv.org/abs/2501.17594)|null|
|**2025-01-28**|**SliceOcc: Indoor 3D Semantic Occupancy Prediction with Vertical Slice Representation**|Jianing Li et.al.|[2501.16684](http://arxiv.org/abs/2501.16684)|**[link](https://github.com/northsummer/sliceocc)**|
|**2025-01-27**|**Modular Framework for Uncertainty Prediction in Autonomous Vehicle Motion Forecasting within Complex Traffic Scenarios**|Han Wang et.al.|[2501.16480](http://arxiv.org/abs/2501.16480)|null|
|**2025-03-03**|**Doracamom: Joint 3D Detection and Occupancy Prediction with Multi-view 4D Radars and Cameras for Omnidirectional Perception**|Lianqing Zheng et.al.|[2501.15394](http://arxiv.org/abs/2501.15394)|null|
|**2025-01-26**|**MetaOcc: Surround-View 4D Radar and Camera Fusion Framework for 3D Occupancy Prediction with Dual Training Strategies**|Long Yang et.al.|[2501.15384](http://arxiv.org/abs/2501.15384)|**[link](https://github.com/lucasyang567/metaocc)**|
|**2025-01-24**|**TrajFlow: A Generative Framework for Occupancy Density Estimation Using Normalizing Flows**|Mitch Kosieradzki et.al.|[2501.14266](http://arxiv.org/abs/2501.14266)|**[link](https://github.com/kosieram21/trajflow)**|
|**2025-01-22**|**Map Prediction and Generative Entropy for Multi-Agent Exploration**|Alexander Spinos et.al.|[2501.13189](http://arxiv.org/abs/2501.13189)|null|
|**2025-01-22**|**Grid-based Submap Joining: An Efficient Algorithm for Simultaneously Optimizing Global Occupancy Map and Local Submap Frames**|Yingyu Wang et.al.|[2501.12764](http://arxiv.org/abs/2501.12764)|null|
|**2024-12-29**|**MR-Occ: Efficient Camera-LiDAR 3D Semantic Occupancy Prediction Using Hierarchical Multi-Resolution Voxel Representation**|Minjae Seong et.al.|[2412.20480](http://arxiv.org/abs/2412.20480)|null|
|**2024-12-28**|**Reinforcement Learning Driven Multi-Robot Exploration via Explicit Communication and Density-Based Frontier Search**|Gabriele Calzolari et.al.|[2412.20049](http://arxiv.org/abs/2412.20049)|null|
|**2024-12-19**|**GSRender: Deduplicated Occupancy Prediction via Weakly Supervised 3D Gaussian Splatting**|Qianpu Sun et.al.|[2412.14579](http://arxiv.org/abs/2412.14579)|null|
|**2024-12-18**|**Unified Understanding of Environment, Task, and Human for Human-Robot Interaction in Real-World Environments**|Yuga Yano et.al.|[2412.13726](http://arxiv.org/abs/2412.13726)|**[link](https://github.com/tamhome/tam_dynamic_map)**|
|**2024-12-18**|**Multi-View Pedestrian Occupancy Prediction with a Novel Synthetic Dataset**|Sithu Aung et.al.|[2412.13569](http://arxiv.org/abs/2412.13569)|null|
|**2025-03-24**|**GaussTR: Foundation Model-Aligned Gaussian Transformer for Self-Supervised 3D Spatial Understanding**|Haoyi Jiang et.al.|[2412.13193](http://arxiv.org/abs/2412.13193)|**[link](https://github.com/hustvl/gausstr)**|
|**2024-12-17**|**Enhancing Exploration Efficiency using Uncertainty-Aware Information Prediction**|Seunghwan Kim et.al.|[2412.12825](http://arxiv.org/abs/2412.12825)|null|
|**2025-01-10**|**ViPOcc: Leveraging Visual Priors from Vision Foundation Models for Single-View 3D Occupancy Prediction**|Yi Feng et.al.|[2412.11210](http://arxiv.org/abs/2412.11210)|**[link](https://github.com/fengyi233/ViPOcc)**|
|**2024-12-15**|**OccScene: Semantic Occupancy-based Cross-task Mutual Learning for 3D Scene Generation**|Bohan Li et.al.|[2412.11183](http://arxiv.org/abs/2412.11183)|null|
|**2025-01-23**|**OmniHD-Scenes: A Next-Generation Multimodal Dataset for Autonomous Driving**|Lianqing Zheng et.al.|[2412.10734](http://arxiv.org/abs/2412.10734)|null|
|**2024-12-13**|**GaussianWorld: Gaussian World Model for Streaming 3D Occupancy Prediction**|Sicheng Zuo et.al.|[2412.10373](http://arxiv.org/abs/2412.10373)|**[link](https://github.com/zuosc19/gaussianworld)**|
|**2024-12-13**|**GaussianAD: Gaussian-Centric End-to-End Autonomous Driving**|Wenzhao Zheng et.al.|[2412.10371](http://arxiv.org/abs/2412.10371)|**[link](https://github.com/wzzheng/gaussianad)**|
|**2025-02-27**|**ProtoOcc: Accurate, Efficient 3D Occupancy Prediction Using Dual Branch Encoder-Prototype Query Decoder**|Jungho Kim et.al.|[2412.08774](http://arxiv.org/abs/2412.08774)|**[link](https://github.com/spa-junghokim/protoocc)**|
|**2024-12-11**|**LOMA: Language-assisted Semantic Occupancy Network via Triplane Mamba**|Yubo Cui et.al.|[2412.08388](http://arxiv.org/abs/2412.08388)|null|
|**2024-12-11**|**Hierarchical Context Alignment with Disentangled Geometric and Temporal Modeling for Semantic Occupancy Prediction**|Bohan Li et.al.|[2412.08243](http://arxiv.org/abs/2412.08243)|null|
|**2024-12-11**|**Semantic Scene Completion Based 3D Traversability Estimation for Off-Road Terrains**|Zitong Chen et.al.|[2412.08195](http://arxiv.org/abs/2412.08195)|null|
|**2024-12-18**|**PVP: Polar Representation Boost for 3D Semantic Occupancy Prediction**|Yujing Xue et.al.|[2412.07616](http://arxiv.org/abs/2412.07616)|null|
|**2024-12-08**|**Lightweight Spatial Embedding for Vision-based 3D Occupancy Prediction**|Jinqing Zhang et.al.|[2412.05976](http://arxiv.org/abs/2412.05976)|null|
|**2024-12-06**|**Towards Flexible 3D Perception: Object-Centric Occupancy Completion Augments 3D Object Detection**|Chaoda Zheng et.al.|[2412.05154](http://arxiv.org/abs/2412.05154)|**[link](https://github.com/ghostish/objectcentricocccompletion)**|
|**2024-12-06**|**GaussianFormer-2: Probabilistic Gaussian Superposition for Efficient 3D Occupancy Prediction**|Yuanhui Huang et.al.|[2412.04384](http://arxiv.org/abs/2412.04384)|**[link](https://github.com/huang-yh/gaussianformer)**|
|**2024-12-06**|**EmbodiedOcc: Embodied 3D Occupancy Prediction for Vision-based Online Scene Understanding**|Yuqi Wu et.al.|[2412.04380](http://arxiv.org/abs/2412.04380)|**[link](https://github.com/ykiwu/embodiedocc)**|
|**2024-12-05**|**UNCOVER: Unknown Class Object Detection for Autonomous Vehicles in Real-time**|Lars Schmarje et.al.|[2412.03986](http://arxiv.org/abs/2412.03986)|null|
|**2024-12-03**|**LLM-Enhanced Path Planning: Safe and Efficient Autonomous Navigation with Instructional Inputs**|Pranav Doma et.al.|[2412.02655](http://arxiv.org/abs/2412.02655)|null|
|**2024-12-31**|**Global Tensor Motion Planning**|An T. Le et.al.|[2411.19393](http://arxiv.org/abs/2411.19393)|**[link](https://github.com/anindex/gtmp)**|
|**2024-11-25**|**Language Driven Occupancy Prediction**|Zhu Yu et.al.|[2411.16072](http://arxiv.org/abs/2411.16072)|**[link](https://github.com/pkqbajng/locc)**|
|**2024-11-22**|**VisionPAD: A Vision-Centric Pre-training Paradigm for Autonomous Driving**|Haiming Zhang et.al.|[2411.14716](http://arxiv.org/abs/2411.14716)|null|
|**2024-11-19**|**Multilayer occupancy grid for obstacle avoidance in an autonomous ground vehicle using RGB-D camera**|Jhair S. Gallego et.al.|[2411.12535](http://arxiv.org/abs/2411.12535)|null|
|**2024-11-19**|**GaussianPretrain: A Simple Unified 3D Gaussian Representation for Visual Pre-training in Autonomous Driving**|Shaoqing Xu et.al.|[2411.12452](http://arxiv.org/abs/2411.12452)|**[link](https://github.com/public-bots/gaussianpretrain)**|
|**2024-02-19**|**SDGE: Stereo Guided Depth Estimation for 360° Camera Sets**|Jialei Xu et.al.|[2402.11791](http://arxiv.org/abs/2402.11791)|null|
|**2024-02-12**|**Collaborative Semantic Occupancy Prediction with Hybrid Feature Fusion in Connected Automated Vehicles**|Rui Song et.al.|[2402.07635](http://arxiv.org/abs/2402.07635)|null|
|**2024-02-04**|**Hybrid-Prediction Integrated Planning for Autonomous Driving**|Haochen Liu et.al.|[2402.02426](http://arxiv.org/abs/2402.02426)|null|
|**2024-02-02**|**Dynamic Occupancy Grids for Object Detection: A Radar-Centric Approach**|Max Peter Ronecker et.al.|[2402.01488](http://arxiv.org/abs/2402.01488)|null|
|**2024-01-24**|**S2TPVFormer: Spatio-Temporal Tri-Perspective View for temporally coherent 3D Semantic Occupancy Prediction**|Sathira Silva et.al.|[2401.13785](http://arxiv.org/abs/2401.13785)|null|
|**2024-01-23**|**InverseMatrixVT3D: An Efficient Projection Matrix-Based Approach for 3D Occupancy Prediction**|Zhenxing Ming et.al.|[2401.12422](http://arxiv.org/abs/2401.12422)|**[link](https://github.com/danielming123/inversematrixvt3d)**|
|**2024-01-17**|**POP-3D: Open-Vocabulary 3D Occupancy Prediction from Images**|Antonin Vobecky et.al.|[2401.09413](http://arxiv.org/abs/2401.09413)|null|
|**2024-01-13**|**UniVision: A Unified Framework for Vision-Centric 3D Perception**|Yu Hong et.al.|[2401.06994](http://arxiv.org/abs/2401.06994)|null|
|**2024-02-06**|**Occupancy Prediction for Building Energy Systems with Latent Force Models**|Thore Wietzke et.al.|[2401.05074](http://arxiv.org/abs/2401.05074)|**[link](https://github.com/thorewietzke/occupancy-benchmark-dataset)**|
|**2024-01-05**|**Comparative Evaluation of RGB-D SLAM Methods for Humanoid Robot Localization and Mapping**|Amirhosein Vedadi et.al.|[2401.02816](http://arxiv.org/abs/2401.02816)|null|
|**2023-12-29**|**Fully Sparse 3D Panoptic Occupancy Prediction**|Haisong Liu et.al.|[2312.17118](http://arxiv.org/abs/2312.17118)|null|
|**2023-12-22**|**Room Occupancy Prediction: Exploring the Power of Machine Learning and Temporal Insights**|Siqi Mao et.al.|[2312.14426](http://arxiv.org/abs/2312.14426)|null|
|**2023-12-19**|**Regulating Intermediate 3D Features for Vision-Centric Autonomous Driving**|Junkai Xu et.al.|[2312.11837](http://arxiv.org/abs/2312.11837)|**[link](https://github.com/cskkxjk/vampire)**|
|**2023-12-19**|**RadOcc: Learning Cross-Modality Occupancy Knowledge through Rendering Assisted Distillation**|Haiming Zhang et.al.|[2312.11829](http://arxiv.org/abs/2312.11829)|null|
|**2023-12-15**|**Drones Guiding Drones: Cooperative Navigation of a Less-Equipped Micro Aerial Vehicle in Cluttered Environments**|Václav Pritzl et.al.|[2312.09786](http://arxiv.org/abs/2312.09786)|null|
|**2023-12-14**|**OccNeRF: Self-Supervised Multi-Camera Occupancy Prediction with Neural Radiance Fields**|Chubin Zhang et.al.|[2312.09243](http://arxiv.org/abs/2312.09243)|**[link](https://github.com/linshan-bin/occnerf)**|
|**2023-12-10**|**Graph-based Prediction and Planning Policy Network (GP3Net) for scalable self-driving in dynamic environments using Deep Reinforcement Learning**|Jayabrata Chowdhury et.al.|[2312.05784](http://arxiv.org/abs/2312.05784)|null|
|**2023-12-09**|**OctreeOcc: Efficient and Multi-Granularity Occupancy Prediction Using Octree Queries**|Yuhang Lu et.al.|[2312.03774](http://arxiv.org/abs/2312.03774)|**[link](https://github.com/4DVLab/OctreeOcc)**|
|**2023-12-06**|**VLFM: Vision-Language Frontier Maps for Zero-Shot Semantic Navigation**|Naoki Yokoyama et.al.|[2312.03275](http://arxiv.org/abs/2312.03275)|null|
|**2023-12-04**|**COTR: Compact Occupancy TRansformer for Vision-based 3D Occupancy Prediction**|Qihang Ma et.al.|[2312.01919](http://arxiv.org/abs/2312.01919)|null|
|**2023-11-29**|**SelfOcc: Self-Supervised Vision-Based 3D Occupancy Prediction**|Yuanhui Huang et.al.|[2311.12754](http://arxiv.org/abs/2311.12754)|**[link](https://github.com/huang-yh/selfocc)**|
|**2023-11-18**|**FlashOcc: Fast and Memory-Efficient Occupancy Prediction via Channel-to-Height Plugin**|Zichen Yu et.al.|[2311.12058](http://arxiv.org/abs/2311.12058)|**[link](https://github.com/Yzichen/FlashOCC)**|
|**2023-11-19**|**SOccDPT: Semi-Supervised 3D Semantic Occupancy from Dense Prediction Transformers trained under memory constraints**|Aditya Nalgunda Ganesh et.al.|[2311.11371](http://arxiv.org/abs/2311.11371)|null|
|**2023-11-16**|**Safety Aware Autonomous Path Planning Using Model Predictive Reinforcement Learning for Inland Waterways**|Astrid Vanneste et.al.|[2311.09878](http://arxiv.org/abs/2311.09878)|null|
|**2023-11-07**|**Spatio-Temporal Anomaly Detection with Graph Networks for Data Quality Monitoring of the Hadron Calorimeter**|Mulugeta Weldezgina Asres et.al.|[2311.04190](http://arxiv.org/abs/2311.04190)|null|
|**2023-11-03**|**EmerNeRF: Emergent Spatial-Temporal Scene Decomposition via Self-Supervision**|Jiawei Yang et.al.|[2311.02077](http://arxiv.org/abs/2311.02077)|null|
|**2023-10-03**|**Predicting Future Spatiotemporal Occupancy Grids with Semantics for Autonomous Driving**|Maneekwan Toyungyernsub et.al.|[2310.01723](http://arxiv.org/abs/2310.01723)|null|
|**2023-11-16**|**Active SLAM Utility Function Exploiting Path Entropy**|Muhammad Farhan Ahmed et.al.|[2309.16490](http://arxiv.org/abs/2309.16490)|null|
|**2024-02-16**|**Scene Informer: Anchor-based Occlusion Inference and Trajectory Prediction in Partially Observable Environments**|Bernard Lange et.al.|[2309.13893](http://arxiv.org/abs/2309.13893)|**[link](https://github.com/sisl/sceneinformer)**|
|**2023-09-25**|**SPOT: Scalable 3D Pre-training via Occupancy Prediction for Autonomous Driving**|Xiangchao Yan et.al.|[2309.10527](http://arxiv.org/abs/2309.10527)|**[link](https://github.com/pjlab-adg/3dtrans)**|
|**2023-09-18**|**Efficient and Accurate Mapping of Subsurface Anatomy via Online Trajectory Optimization for Robot Assisted Surgery**|Brian Y. Cho et.al.|[2309.10154](http://arxiv.org/abs/2309.10154)|null|
|**2023-09-18**|**RenderOcc: Vision-Centric 3D Occupancy Prediction with 2D Rendering Supervision**|Mingjie Pan et.al.|[2309.09502](http://arxiv.org/abs/2309.09502)|**[link](https://github.com/pmj110119/renderocc)**|
|**2023-09-17**|**Heuristic-based Incremental Probabilistic Roadmap for Efficient UAV Exploration in Dynamic Environments**|Zhefan Xu et.al.|[2309.09121](http://arxiv.org/abs/2309.09121)|null|
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

<p align=right>(<a href=#updated-on-20250421>back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/Vincentqyw/cv-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/Vincentqyw/cv-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/Vincentqyw/cv-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/Vincentqyw/cv-arxiv-daily/issues

