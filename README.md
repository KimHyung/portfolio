# PORTFOLIO
![status](https://img.shields.io/badge/looking_for_job-yellowgreen.svg)
 
## INTRODUCE
<img src = "https://avatars.githubusercontent.com/u/18005412?v=4" width="20%">

- Name: Hyungseok,Kim
- Email : kty5989@gmail.com
- Github : [github.com/KimHyung](https://github.com/KimHyung)

```
Interested in autonomous system, path planning, robotics.
```
---
## Education
-   Kyungpook National University(2019~2021), School of Electronics and Electrical Engineering(M.S)
-   Kyungpook National University(2012~2019), School of Electronics Engineering(B.S)

#### 학위기간동안...

- N-wheeled robot의 동역학, 차량제어 그리고 자율주행 시스템에 대해 공부하였고 자율주행에 필요한 센서 또는 시스템 구성요소에 대한 전반적인 지식을 쌓았습니다. 

- 개발한 알고리즘을 실제 로봇에 적용하기전에 Gazebo, Carla, Autoware 그리고 Airsim 등 다양한 시뮬레이터를 이용하여 알고리즘의 성능을 검증 및 테스트 할 수 있습니다.

- 개발한 알고리즘을 실제환경에서 실험하기 위해 turtlebot3, LEO, OMO robot과 같은 다양한 로봇 플랫폼을 사용하였습니다.

- YOLO--based, RCNN-based, openCV-based 와 같은 객체 인식 및 추적 알고리즘에 대해 공부하였고 실습하였습니다.
---
## Publications
### International
- Hyungseok Kim, Hyungjin Kim, Seon-il Lee, Heyonbeom Lee, "Autonomous Exploration in a Cluttered Environment for a Mobile Robot With 2D-Map Segmentation and Object Detection",  IEEE Robotics and Automation Letters, vol. 7, no. 3, pp. 6343-6350, July 2022
### Conferences
- Seon-il Lee, Hyungseok Kim, Uikyum Kim, Heyonbeom Lee, "Concave Wall Surface Tracking for Aerial Manipulator Using Contact Force Estimation Algorithm", 20th International Conference on Control, Automation and Systems, Busan, Korea (Oct.2020)
- Hyungseok Kim, Hyeonbeom Lee, "Autonomous exploration with efficient frontier detection", KROS 2020, pyeongchang, Korea, (Aug.2020)
### Domestic
-  김형석, 이현범 "효율적인 프론티어 선정을 통한 모바일 로봇의 자율 탐사 및 의미지도 작성 기술", 제어.로봇.시스템학회 논문지, 2020
---

## Skills
-   Language : C, C++, Python
-   Frameworks : ROS
-  Etc : Git, Slack, Jira

---
## TODO
-   ROS2
  
---
## Projects
---
### 자율주행 임시운행 허가
-   ***Introduce :*** WSCE 
-   ***Term :*** 2022.08 ~ 2022.09
-   ***My Role :***

        1. SLAM
        - NDT, LOAM, HDL
        - Pure Localization
        2. TF 
        - WORLD, MAP, CAR, Base_link, Sensors
        3.시나리오 구현
        4. Wireless Network Configuration (Viewer) ↔  Extender ↔ (Car)

---
---
### 자율주행 임시운행 허가
-   ***Introduce :*** 카니발 차량 자율주행 임시운행 허가증 
-   ***Term :*** 2021.08 ~ 2022.08
-   ***My Role :***

        1.CAN msg Analysis 
        - ViCANDO, PCAN View, KVASER
        - ECAN, CCAN, ICU, BCAN, DCAN, MFC LCAN
        - MDPS, RSPA, Jerk, Radar, Lamp
        - CRC Table & Algorithm

        2.Hardware
        - GPS (Novatel, SBG,  NMEA, Honeywell 0360, ByNAV X1
        - CAN Gateway(HDMI2CSI, )
        - Velodyne LiDARx3(32ch, 16ch x2) configuration, TF setup
        - CAN Relay

        3.Jetson NX
        - ubuntu kernel HW tree (implement video lib lt6911uxc) 
        - Jetson NX Implement
        - gps/rtk(power level issue), RTCM
        - Serial, UART
        - GPIO (lamp control)

        4. Software
        - PCL (detector, tracker)
        - HD MAP 관심 경로 추출
        - 2 jetson + 1 pc network environment setup
        - Path MAP

-   ***Result :*** 임시운행 허가증 획득.
<!-- -   ***more detatils*** :  [github.com/KimHyung/autonomous_exploration](https://github.com/KimHyung/autonomous_exploration) -->


---
---

### Autonomous exploration
-   ***Introduce :*** Autonomous exploration strategy for a mobile robot with 2d-map segmentation and object detection in the cluttered environment.
-   ***Term :*** 2020.09~2021.7
-   ***Related technology :*** ros, frontier-based exploration, 2d-map segmentation, cost-function, yoloV3, costmap, pcl.
-   ***more detatils*** :  [github.com/KimHyung/autonomous_exploration](https://github.com/KimHyung/autonomous_exploration)
-   ***Result :*** IROS 2021 submit.

<img src = "./projects/2021_autonomous_exploration/images/1.jpg" width="60%">
<img src = "./projects/2021_autonomous_exploration/images/2.jpg" width="60%">

---
---

### 2020_autonomous_driving_contest
-   ***Introduce :*** 도로인프라와 연계된 실도로 기반 자율주행 경진대회, 차량 무선통신 인프라(WAVE)와 연계하여 실도로 기반의 “자율주행 픽업서비스” 미션 수행, Autoware.ai(ros1) 기반으로 자율주행 시스템을 개발하였고 실차(Soul – Hyundai)에 적용하였습니다.
-   ***Term :*** 2019.10~2020.10
-   ***Related technology :*** ros, c++, autoware, ndt-based slam, vector map, hybrid A*, pure-pursuit, v2x.
-   ***My role :*** path planning, path tracking, system integration, vector map creation.(contribution: 35%)
-   ***more detatils*** : <strike>[github.com/KimHyung/autoware_carla](https://github.com/KimHyung/autoware_carla)</strike>
-   ***Result :*** [contest video](https://www.youtube.com/watch?v=usnD_GxowE0).

<img src = "./projects/2020_autonomous_driving_contest/images/1.png" width="70%">

---
---

### 2019_capstone_design(smart sidewalk block)
-   ***Introduce :*** ‘무게센서 보도 블록을 이용한 스마트 신호등’은 무게센서를 이용해서 신호등의 사이클 타임을 제어하여 효율적으로 교통을 관리하며, 시각장애인이 보다 편리하고 안전하게 횡단보도를 이용할 수 있도록 도와주는 시스템이다.
-   ***Term :*** 2018.3~2019.1
-   ***Related technology :*** arduino, C, sensor data processing system.
-   ***My role :*** Team leader, PM, sensor data processing system.(contribution: 40%)
-   ***more detatils*** :  [특허정보-kportal, 10-2225213-0000](http://kportal.kipris.or.kr/kportal/search/total_search.do)
-   ***Result :*** 국내특허 출원.

<img src = "./projects/2019_capstone_design/images/1.png" width="30.7%">
<img src = "./projects/2019_capstone_design/images/2.png" width="45%">

---
---

### 2017_embeded_software_contest (자율주행 모형자동차 부문)
-   ***Introduce :*** KESSIA, KEIT가 주관하고 현대자동차가 후원하는 제 15회 임베디드 소프트웨어 공모전 자율주행 모형자동차 부문에 참여하였다. 모형자동차에 부착된 비전센서를 데이터를 기반으로 openCV라이브러리를 통해 차선, 정지선, 신호등 등을 인식하여 주행하는 자율주행 시스템을 개발하였다. 
-   ***Term :*** 2017.5~2017.12
-   ***Related technology :*** C, openCV, ECU.
-   ***My role :*** Team leader, PM, vision-based autonomous algorithm.(contribution: 40%)
-   ***Result :*** 결선 진출.
<img src = "./projects/2017_embeded_software_contest/images/4.png" width="">
---
---
##### 더 궁금한 사항이 있으시면 kty5989@gmail.com 으로 연락주세요.
##### 
---
 
