# VINS_lists
list some awesome VINS algorithms and implementations. VINS (Visual-inertial navigation system; Vision aided inertial navigation system)

---
last update: 2016-12-31 
---

## VINS Algorithms

### Loosely coupled (LC)
Vision sensor and inertial measurement unit (IMU) are two seperate modules, providing the robot's pose or part of it. Fusion algorithm integrates these two outputs in a optimal way.
Advantages:
+ Decouple the vision part in a black-box, allowing the IMU part processes the fusion in real-time;
+ Few, if any, states will be augmented, which will lead to fast speed;
+ The decoupled system together with other aiding sensors can form a mudular multisensor system and be incoorparated easily, for example, in a decentrized filter framework. 

#### Monocular

#### Stereo

### Tightly coupled (TC)
Advantages:
+ No scale ambiguity problem when using the monocular camera;
+ More systematic uncertainty propagation with easier measurement uncertainty determination than that of pose uncertainty in LC;
+ More accurate results

#### Monocular
+ (1) MSCKF and variants
+ (2) SLAM filter-based
+ (3) Non-linear Optimization

#### Stereo 
(1) Trifocal tensor


## Research Teams
+ [Multiple Autonomous Robotic Systems (MARS) Laboratory, University of Minnesota](http://mars.cs.umn.edu/index.php)
+ [Robotics, Perception and Real Time Group, University of Zaragoza](http://robots.unizar.es/)
+ [Computer Vision Group, Technical University of Munich](https://vision.in.tum.de/research/vslam)
+

## Courses
+ [CSIC-UPC: KF, EKF and SLAM course in MATLAB](http://www.iri.upc.edu/people/jsola/JoanSola/eng/course.html)
+ [TUM: Machine Learning for Robotics and Computer Vision (IN3200)](https://vision.in.tum.de/teaching/ws2016/mlcv16)

## Open Source Software, Toolbox, Tools
+ [SLAM TOOLBOX FOR MATLAB](http://www.iri.upc.edu/people/jsola/JoanSola/eng/toolbox.html)
+ [RT-SLAM: Real-time EKF-SLAM in C++](https://www.openrobots.org/wiki/rtslam/)
+ [Point Cloud Library](http://pointclouds.org/)
+ [InerVis Toolbox for Matlab](http://home.deec.uc.pt/~jlobo/InerVis_WebIndex/InerVis_Toolbox.html)
+ [Kalibr: Intrinsic, extrinsic and temporal camera and IMU calibration](https://github.com/ethz-asl/kalibr)

## Useful Website: Personal, Wiki, Organization
+ [OpenSLAM](https://openslam.org/)
+ [SLAMCN](http://www.slamcn.org/index.php/%E9%A6%96%E9%A1%B5)
+ [Joan Sola](http://www.joansola.eu)
+ [OpenRobots](https://www.openrobots.org/wiki)
+ [awesome-SLAM-list](https://github.com/OpenSLAM/awesome-SLAM-list)
+ 


## Datasets
+ [ASL Datasets Repository](http://projects.asl.ethz.ch/datasets/doku.php)
+ [The EuRoC MAV Dataset](http://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)
+ [A summary of other dataset](http://projects.asl.ethz.ch/datasets/doku.php?id=related_links)
