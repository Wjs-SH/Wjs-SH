# Hi, I'm SeongHwan Jeon 👋

**Robot Automation Engineering @ Dong-Eui University** · Busan, Korea

I build autonomous mobile robots with **ROS 2**, **LiDAR SLAM & localization**, and **robot perception**,
testing them on real sensor data and in simulation.

🏅 Outstanding Paper Award ×2 · KIIT 2026 Summer Conference

[![Email](https://img.shields.io/badge/Email-iuriwjs1@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:iuriwjs1@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion&logoColor=white)](https://app.notion.com/p/SEONGHWAN-JEON-727099ab664482b6aa57011110ba948e)

## 🛠️ Tech Stack

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
<br>
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/Jetson_Orin_NX-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-404040?style=for-the-badge&logo=unrealengine&logoColor=white)

## 🚀 Projects

| [**Wjs-LIO_SAM**](https://github.com/Wjs-SH/Wjs-LIO_SAM) | [**Wjs-FAST_LIO**](https://github.com/Wjs-SH/Wjs-FAST_LIO) |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Wjs-SH/Wjs-LIO_SAM/main/docs/images/4F_liosam_rviz_hall.jpg" width="400"> | <img src="https://raw.githubusercontent.com/Wjs-SH/Wjs-FAST_LIO/main/docs/images/4F_map_rviz_top.jpg" width="400"> |
| LIO-SAM · Unitree Go2 + Hesai XT16 | FAST-LIO · leg-velocity fusion |

### 🗺️ SLAM & Localization

- **[Floorplan-SemanticMap](https://github.com/Wjs-SH/Floorplan-SemanticMap)** — navigation & semantic maps (rooms, room numbers, doors) from building guide-map photos with OCR + VLM · `Python` `OpenCV` `VLM`
- **[Floorplan-Localization](https://github.com/Wjs-SH/Floorplan-Localization)** — localizing a Go2 and identifying its floor on guide-map maps with accumulated LiDAR + VLM cues · `3D LiDAR` `VLM` `Python`
- **[Wjs-LIO_SAM](https://github.com/Wjs-SH/Wjs-LIO_SAM)** — LIO-SAM on a walking Unitree Go2 with Hesai XT16; full 3F/4F corridor runs, 4F loop end–start 0.32 m · `C++` `ROS 2 Humble`
- **[Wjs-FAST_LIO](https://github.com/Wjs-SH/Wjs-FAST_LIO)** — FAST-LIO with Hesai support, gait-vibration handling and leg-velocity fusion; corridor length within 1% of tape measure · `C++` `ROS 2 Humble`

### 🤖 Mobile Robots

- **Autonomous Guide & Delivery AMR** — speech (STT) destination input, autonomous driving in a real building · `ROS 2` `Python` `C++`
- **[cart_ros2](https://github.com/Wjs-SH/cart_ros2)** — ROS 2 stack for a differential-drive cart: Roboteq motor control, RPLidar scan merging, IMU, Cartographer / SLAM Toolbox mapping · `ROS 2` `C++`
- **PID-Based Autonomous Wheelchair** — PID motor control, odometry, SLAM, navigation, path recovery and fall prevention · `PID` `Embedded`
- **TurtleBot3 Maze Exploration** — global path search with goal-based re-navigation in a real maze · `ROS 2` `2D LiDAR`
- **TurtleBot3 Line Following** — camera line tracing over a full track · `ROS 2` `OpenCV`

### 👁️ Perception & AI

- **V-SENTRY: VLM-Based Industrial Safety Inspection Robot** — situation analysis & hazard assessment in a virtual plant (industry collaboration) · `Unitree Go2` `VLM` `Isaac Sim` `Unreal Engine`
- 🏅 **Pedestrian Avoidance for Indoor Mobile Robots** — avoidance decisions from SegFormer masks aligned with 2D LiDAR · `SegFormer` `2D LiDAR`
- **4-Camera & 2D LiDAR Unified BEV System** — four cameras and a 2D LiDAR fused into one bird's-eye view · `SegFormer` `Sensor Fusion`
- 🏅 **Intent-Aware LLM Response System** — asks intermediate questions to pin down user intent in public guidance settings · `LLM`

Videos, reports and slides for each project → [Notion portfolio](https://app.notion.com/p/SEONGHWAN-JEON-727099ab664482b6aa57011110ba948e)
