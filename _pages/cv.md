---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Resume](http://hvak.github.io/files/Hersh_Vakharia_Resume.pdf)

Education
======
* M.S. in Robotics, University of Michigan, 2024
  * GPA: 4.00/4.00
  * Perception and Sensing Focus
* B.S. in Computer Engineering, University of Michigan, 2022
  * Minor in Mathematics
  * GPA: 3.67/4.00
  * Coursework: Robotics, Embedded Systems, Computer Vision, Linear Algebra

Work experience
======
* **Research Assistant**, *UMich Robotics - Ford Center for Autonomous Vehicles*, 08/2022 - Present
  * Exploring fuzzy measure based multi-modal and multi-resolution sensor fusion techniques

* **Software Engineer Intern**, *Microsoft - Imaging and Provisioning Team*, 05/2023 - 08/2023
  * Developed website in Blazor/C# capable of imaging/provisioning Microsoft Surface devices
  * Developed system for website to communicate with locally running Windows service

* **Software Engineer Intern**, *Microsoft - Surface Cross Platform UEFI Team*, 05/2022 - 08/2022
  * Developed a UEFI image based on open-source EDK2 platforms
  * Tested and debugged UEFI on Surface hardware
  
* **Firmware Engineer Intern**, *Microsoft - Surface Duo Developer Experience Team*, 05/2021 - 08/2021
  * Developed dual-screen Android sample apps for Surface Duo using Jetpack Window Manager
  * Wrote blog entries and appeared on Twitch streams to showcase technical details of sample apps
  * Created Surface Duo travel-planning app experience to demonstrate dual-screen use cases

* **Embedded Systems Engineering Intern**, *Lucid Drone Technologies*, 05/2020 - 08/2020
  * Developed C++ ROS package to read MPU6050 IMU data via I2C
  * Engineered a ROS Camera-IMU synchronization sensor for Robust Visual Inertial Odometry Framework
  * Calibrated IMU, camera (extrinsic and intrinsic), and Cam-IMU sync using Kalibr toolset
  
* **Team Lead / Sensors Lead / Sensors Member**, *University of Michigan Autonomous Robotic Vehicle Team*, 09/2018 - 04/2022
  * Team Lead - led team of 40 members in design and development of autonomous robotic vehicle for the 2022 Intelligent Ground Vehicle Competition at Oakland University, managed relations with university, advisors, and sponsors
  * Sensors Lead - led sensors subteam in development and documentation of robot's perception stack, ran technical ROS workshops
  * Sensors Member - Developed sensor fusion of LIDAR, IMU, wheel encoder, and GPS data in ROS and C++ for computing odometry and SLAM (Google Cartographer)
  
Skills
======
* Programming Languages
  * C, C++, Python, C#, MATLAB
* Hardware
  * Arduino, Raspberry Pi, NVIDIA Jetson, STM32, Intel RealSense, Serial Communication Protocols
* Frameworks
  * Robot Operating System (ROS), MoveIt, Gazebo, PyTorch, CUDA, OpenCV, Android SDK
* Other
  * Linux, Git, SLAM, Docker

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

