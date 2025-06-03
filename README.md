# LiDAR-camera-calibration-summary
## LiDAR-camera calibration algorithms

Summary of the current mainstream open-source LiDAR-camera calibration algorithms. We provide the algorithm's web links, sensor types, corresponding literature sources, and the calibration framework category to which it belongs. This summary will be continuously updated to provide a convenient and concise radar and camera calibration checklist for radar and camera calibration researchers. Suggestions are welcome, and we will strive to do better. 
* ACSC: Automatic calibration for non-repetitive scanning solid-state LiDAR and camera systems [open-source link](https://github.com/HViktorTsoi/ACSC.git)
* Automatic extrinsic calibration method for lidar and camera sensor setups [open-source link](https://github.com/beltransen/velo2cam_calibration )
* Joint camera intrinsic and lidar-camera extrinsic calibration [open-source link](https://github.com/ankitdhall/lidar_camera_calibration)
* OpenCalib: A Multi-sensor Calibration Toolbox for Autonomous Driving [open-source link](https://github.com/PJLab-ADG/SensorsCalibration)
* Optimising the selection of samples for robust lidar camera calibration [open-source link](https://github.com/acfr/cam−lidar−calibration)
* Pixel-level extrinsic self calibration of high resolution lidar and camera in targetless environments [open-source link](https://github.com/hku-mars/livox−camera−calib) 
* General, single-shot, target-less, and automatic lidar-camera extrinsic calibration toolbox [open-source link](https://github.com/koide3/direct_visual_lidar_calibration)
* Automatic camera and range sensor calibration using a single shot [open-source link](https://www.cvlibs.net/software/libcbdetect)
* Optimal vehicle path planning using quadratic optimization for baidu apollo open platform [open-source link](https://github.com/ApolloAuto/apollo/tree/master/modules/calibration)
* A generic camera model and calibration method for conventional, wide-angle, and fish-eye lenses [open-source link](https://github.com/tier4/CalibrationTools)
* Automatic extrinsic calibration between a camera and a 3D Lidar using 3D point and plane correspondences [open-source link](https://ww2.mathworks.cn/help/lidar/ug/lidar-and-camera-calibration.htm)
* 3D LIDAR-camera extrinsic calibration using an arbitrary trihedron [open-source link](https://github.com/heethesh/lidar−camera−calibration)
* Extrinsic calibration of a 3d laser scanner and an omnidirectional camera [open-source link](https://github.com/SubMishMar/cam−lidar−calib)
* Reflectance intensity assisted automatic and accurate extrinsic calibration of 3d lidar and panoramic camera using a printed chessboard [open-source link](https://github.com/mfxox/ILCC)
* Extrinsic calibration of lidar and camera with polygon [open-source link](https://github.com/ram-lab/plyca)
* Improvements to target-based 3D LiDAR to camera calibration [open-source link](https://github.com/UMich-BipedLab/extrinsic−lidar−camera−calibration)
* Camvox: A low-cost and accurate lidar-assisted visual slam system [open-source link](https://github.com/xuankuzcr/CamVox)
* CalibNet: Geometrically supervised extrinsic calibration using 3D spatial transformer networks [open-source link](https://epiception.github.io/CalibNet)
* Calnet: Lidar-camera online calibration with channel attention and liquid time-constant network [open-source link](https://github.com/XD319328/CALNet)
* LCCNet: LiDAR and camera self-calibration using cost volume network [open-source link](https://github.com/LvXudong-HIT/LCCN)
* RGBDTCalibNet: End-to-end Online Extrinsic Calibration between a 3D LiDAR, an RGB Camera and a Thermal Camera [open-source link](https://github.com/sanatmh-arolkar/RGBDTCalibNet.git)
* RGGNet: Tolerance aware LiDAR-camera online calibration with geometric deep learning and generative model [open-source link](https://github.com/KleinYuan/RGGNet)

## Datasets that can be used to validate radar and camera calibration algorithms
We have summarized the datasets that can be used to verify the calibration effects of radar and camera. To facilitate researchers’ use, we provide not only the dataset links but also the dataset collection platform and the sensors.
* KITTI [Dataset link](https://www.cvlibs.net/datasets/kitti/) Vision meets robotics: The kitti dataset
* Bovisa [Dataset link](http://www.rawseeds.org/home/) Rawseeds: Robotics advancement through web-publishing of sensorial and elaborated extensive data sets
* Malaga [Dataset link](https://daniilidis-group.github.io/mvsec/download/) The M{\'a}laga urban dataset: High-rate stereo and LiDAR in a realistic urban scenario
* NCLT [Dataset link](http://robots.engin.umich.edu/nclt/) University of Michigan North Campus long-term vision and lidar dataset
* HDD [Dataset link](https://usa.honda-ri.com/hdd) Toward driving scene understanding: A dataset for learning driver behavior and causal reasoning
* MVSEC [Dataset link](https://daniilidis-group.github.io/mvsec/) The multivehicle stereo event camera dataset: An event camera dataset for 3D perception
* Brno Urban [Dataset link](https://github.com/Robotics-BUT/Brno-Urban-Dataset) Brno urban dataset-the new data for self-driving agents and mapping tasks
* ApolloScap [Dataset link](https://apolloscape.auto/) The apolloscape open dataset for autonomous driving and its application
* Argovers [Dataset link](https://www.argoverse.org/) Argoverse: 3d tracking and forecasting with rich maps
* Waymo [Dataset link](https://waymo.com/open/) Scalability in perception for autonomous driving: Waymo open dataset
* WoodScap [Dataset link](https://github.com/valeoai/WoodScape) Woodscape: A multi-task, multi-camera fisheye dataset for autonomous driving
* UrbanLoco [Dataset link](https://github.com/weisongwen/UrbanLoc) UrbanLoco: A full sensor suite dataset for mapping and localization in urban scenes
* Pit30M [Dataset link](https://www.a2d2.audi/a2d2/en.html) Pit30m: A benchmark for global localization in the age of self-driving cars
* A2D2 [Dataset link](https://www.a2d2.audi/a2d2/en.html) A2d2: Audi autonomous driving dataset
* A*3D [Dataset link](https://paperswithcode.com/dataset/a-3d) A* 3d dataset: Towards autonomous driving in challenging environments
* CADC [Dataset link](https://paperswithcode.com/dataset/cadc) Canadian adverse driving conditions dataset
* Cityscape [Dataset link](https://www.cityscapes-dataset.com/) The cityscapes dataset for semantic urban scene understanding
* Ford Multi-AV [Dataset link](https://paperswithcode.com/dataset/ford-av-dataset) Ford multi-AV seasonal dataset
* Lyft Perception/Lyft Predictio [Dataset link](https://level-5.global/register/) One thousand and one hours: Self-driving motion prediction dataset
* nuScene [Dataset link](https://www.nuscenes.org/) nuscenes: A multimodal dataset for autonomous driving
* Pandase [Dataset link](https://scale.com/resources/download/pandaset) Pandaset: Advanced sensor suite dataset for autonomous driving
* RobotCa [Dataset link](https://robotcar-dataset.robots.ox.ac.uk/) The oxford radar robotcar dataset: A radar extension to the oxford robotcar dataset
* USVinland [Dataset link](https://github.com/ORCA-Uboat/USVInland-Datas) Are we ready for unmanned surface vehicles in inland waterways? The usvinland multisensor dataset and benchmark
* NAVER LABS Localization Datasets [Dataset link](https://www.naverlabs.com/datasets) Large-scale localization datasets in crowded indoor spaces
* Dsec [Dataset link](https://dsec.ifi.uzh.ch) Dsec: A stereo event camera dataset for driving scenarios
* TUK Campus [Dataset link](http://www.agrosy.informatik.uni-kl.de/) Drive on pedestrian walk. TUK campus dataset
* M2DGR [Dataset link](https://github.com/SJTU-ViSYS/M2DGR) M2dgr: A multi-sensor and multi-scenario slam dataset for ground robots
* WADS(Winter) [Dataset link](https://digitalcommons.mtu.edu/wads/) Dsor: A scalable statistical filter for removing falling snow from lidar point clouds in severe winter weather
* ONCE  [Dataset link](https://once-for-auto-driving.github.io/) One million scenes for autonomous driving: Once dataset
* SELMA [Dataset link](https://scanlab.dei.unipd.it/selma-dataset/) Selma: Semantic large-scale multimodal acquisitions in variable weather, daytime and viewpoints
* Rope3D [Dataset link](https://thudair.baai.ac.cn/rope) Rope3D: TheRoadside Perception Dataset for Autonomous Driving and Monocular 3D Object Detection Task
* Argoverse [Dataset link](https://www.argoverse.org/av2.htm) Argoverse 2: Next generation datasets for self-driving perception and forecasting
* NTU VIRAL [Dataset link](https://ntu-aris.github.io/ntu−viral−dataset/) Ntu viral: A visual-inertial-ranging-lidar dataset, from an aerial vehicle viewpoint
* MUN-FRL [Dataset link](https://mun-frl-vil-dataset.readthedocs.io/en/lates) MUN-FRL: A Visual-Inertial-LiDAR Dataset for Aerial Autonomous Navigation and Mapping
* S3E [Dataset link](https://pengyu-team.github.io/S3E/) S3E: A Multi-Robot Multimodal Dataset for Collaborative SLAM
