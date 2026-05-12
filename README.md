# HO-Fusion
HO-Fusion: Multisensor Fusion Localization Using Factor Graph Optimization and Error-State Kalman Filter for Hash-Octree LiDAR-Inertial Odometry

---
## System Architecture
<img width="3028" height="928" alt="fusion_framework_overview" src="https://github.com/user-attachments/assets/80a4396a-6e20-49b2-8998-7848781526d5" />

---
## Menu

* [Dependency](#dependency)
* [Install](#install)
---

## Dependency

PCL >= 1.8, Eigen >= 3.3.4, GTSAM, livox_ros_driver, libgeographic

---
## Install
Use the following commands to download and compile the package.
```
mkdir ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/DD-Yan/HO-Fusion.git
cd ..
catkin_make -j4
source devel/setup.bash
```
