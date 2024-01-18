---
title: "<img src='/images/projects/visualunderwaterslam/icon.png' width='50'> ROB 530: Visual Underwater SLAM"
excerpt: "**Relevant skills: Python, GTSAM, ROS, SLAM** 
This project implements underwater visual inertial SLAM as the final project for UM Robotics' ROB 530: Mobile Robotics. The problem is formulated in GTSAM as pose-graph SLAM with ORB features for underwater landmarks. It was tested on a dataset collected by a BlueROV2 robot."
collection: projects
---

This project implements underwater visual inertial SLAM, as the final project for UM Robotics' [ROB 530: Mobile Robotics](https://github.com/UMich-CURLY-teaching/UMich-ROB-530-public).    

---

### Abstract
This work improves upon previous implementations of underwater simultaneous localization and mapping by incorporating visual data into the robot state estimation.  Previous works primarily rely on sensor measurements and control inputs to acquire an estimate of an ROV's position due to the sparsity of landmarks in an underwater environment; however, problems such as drift commonly occur in these environments which can cause the estimation to become inaccurate.  Our method utilizes Graph SLAM coupled with an ORB feature detector for landmark recognition in order to better localize the robot in a contained environment.  This was accomplished using the BlueROV2 robot platform.  This platform affords the use of an Inertial Measurement Unit (IMU), Doppler Velocity Logger (DVL), Depth sensor, and a stereoscopic camera as part of its sensor package.  These sensor readings contribute the factors to our graph solution. The BlueROV2's internal odometry estimates are used as nodes in the factor graph to provide starting point for optimization.  The graph SLAM optimization is undertaken using the GTSAM python library and compared against the original odometry data for verification.

---

An example of a portion of the graph is shown below:

<img src="/images/projects/visualunderwaterslam/graph.png">

Our data was collected on a BlueROV2 robot, which unfortunately cannot be public at this time. You can see more details in the GitHub repo, report, and video linked below.

---

Links:
* [GitHub Repo](https://github.com/hvak/visual-underwater-slam)
* [Detailed Report](https://hvak.io/files/ROB_530_FINAL_PROJECT_REPORT.pdf)
* [Video](https://www.youtube.com/watch?v=LLFDb0DvM18)