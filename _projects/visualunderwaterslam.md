---
title: "<br/><img src='/images/projects/visualunderwaterslam/icon.png' width='50'> ROB 530: Visual Underwater SLAM"
excerpt: "**Relevant skills: Python, GTSAM, ROS, SLAM** 
This project implements underwater visual inertial SLAM as the final project for UM Robotics' ROB 530: Mobile Robotics. The problem is formulated in GTSAM as pose-graph SLAM with ORB features for underwater landmarks. It was tested on a dataset collected by a BlueROV2 robot."
collection: projects
---

This project implements underwater visual inertial SLAM, as the final project for UM Robotics' [ROB 530: Mobile Robotics](https://github.com/UMich-CURLY-teaching/UMich-ROB-530-public). The problem is formulated in GTSAM as pose-graph SLAM with ORB features for underwater landmarks. The pose graph uses IMU and DVL measurements as factors to connect position/velocity states. Landmarks from the ORB features are connected to relevant states. The corrected path is computed from the graph using the Levenberg-Marquard optimizer. A example of a portion of the graph is shown below:

<img src="/images/projects/visualunderwaterslam/graph.png">

Our data was collected on a BlueROV2 robot, which unfortunately cannot be public at this time. You can see more details in the GitHub repo, report, and video linked below.


Links:
* [GitHub Repo](https://github.com/hvak/visual-underwater-slam)
* [Detailed Report](https://hvak.io/files/ROB_530_FINAL_PROJECT_REPORT.pdf)
* [Video](https://www.youtube.com/watch?v=LLFDb0DvM18)