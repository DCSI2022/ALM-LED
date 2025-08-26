# ALM-LED: Autonomous LiDAR Mapping in Underground Space with Luojia Explorer Anti-collision Drone
## 🤖 Luojia Explorer Anti-collision Drone System
![image](https://github.com/user-attachments/assets/e372784e-57c5-418e-91f2-0dc9b83d95ce)

## 📜 Project Status

This paper is currently under review.​​ Software implementations and codes are being organized. ​Code and datasets will be open-sourced upon paper acceptance.​​
 Stay tuned for updates! 

## 🔍 Overview

​ALM-LED​ is an Autonomous LiDAR Mapping method in Underground Space with Luojia Explorer Anti-collision Drone​. It integrates:

​1.An autonomous LiDAR mapping framework for underground spaces

This framework is composed of two primary components: a localization and mapping module, and a planning and control module. The former fuses multi-sensor data—including LiDAR, IMU, barometer, and magnetometer inputs—to achieve robust positioning in complex settings. The latter formulates a cost function constrained by smoothness, collision, and kinematic feasibility penalties, which guides the drone's autonomous navigation through underground spaces.

<img width="5355" height="1246" alt="总体方法框架" src="https://github.com/user-attachments/assets/c7ba98d3-92ae-49f3-afd5-853fe69bbdeb" />

​2.A novel, low-cost, and robust anti-collision drone system. 

The drone is characterized by its lightweight and compact form factor. Its safety mechanism combines a physical carbon fiber protective frame with an intelligent active obstacle avoidance system, facilitating stable flight through complex, cluttered spaces. By leveraging the autonomous mapping framework detailed in 1, the drone provides reliable and effective LiDAR mapping performance under GNSS-denied conditions.

![飞机飞场及组成](https://github.com/user-attachments/assets/cdb9575d-062d-444e-8556-ba970d1d770f)

## ​⚙ Hardware & Sensors

To be updated.

## ✔ Implementation process

To be updated.

## ​💻 Experiments
We conducted a comprehensive set of experiments in both simulated and real-world settings to evaluate the performance of our proposed method. ALM-LED demonstrated an average mapping efficiency of 109.51 m³/s in two simulations and 53.85 m³/s across four real-world scenarios. The resulting map accuracies were high, achieving centimeter-level precision in three cases (0.034 m [0.72‰], 0.088 m [0.37‰], 0.053 m [2.04‰]) and decimeter-level precision in another (0.31 m [0.73‰] in a 400m-long tunnel). These results confirm that the ALM-LED enables highly efficient and accurate autonomous mapping within underground spaces.

The drone is flying through the Luojia Mountain tunnel and building a point cloud map of the tunnel.

![珞珈山隧道飞行-压缩](https://github.com/user-attachments/assets/484e2921-1a32-493a-ae86-14ea07f69a61) ![珞珈山隧道地图漫游](https://github.com/user-attachments/assets/7a5546da-35a6-476e-a500-64773876ab5a)

## ​🏠 Indoor tests
We tested the drone's obstacle avoidance capabilities indoors using our planning and control method; without manual operation, the drone could stably avoid the obstacle and pass through the gate.

![穿越龙门压缩2-10M以下](https://github.com/user-attachments/assets/c33be9d3-74d9-4c5f-9493-fce20380faf2) ![8月26日 -越过障碍-压缩](https://github.com/user-attachments/assets/0b84f553-253e-4939-ae87-cb05f2d8216e)


 The remaining experimental results and videos will be updated upon paper acceptance.
