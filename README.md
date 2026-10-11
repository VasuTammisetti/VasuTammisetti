<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:6e40c9&height=180&section=header&text=Vasu%20Tammisetti&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=AI%20Research%20Engineer%20%7C%20Doctoral%20Researcher%20%7C%20ADAS%20Perception%20%26%20Robotics&descAlignY=58&descSize=15&animation=fadeIn" width="100%"/>

<p>
  <img src="https://img.shields.io/badge/Infineon_Technologies-ADAS_Research-009999?style=for-the-badge&logo=infineon&logoColor=white"/>
  <img src="https://img.shields.io/badge/PhD-University_of_Granada-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Germany-Munich-black?style=for-the-badge&logo=google-maps&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenVINO-00C7FD?style=flat-square&logo=intel&logoColor=white"/>
  <img src="https://img.shields.io/badge/NNCF-0071C5?style=flat-square&logo=intel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLOv8-00FFAA?style=flat-square&logo=yolo&logoColor=black"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

</div>

---

## About Me

| | |
|:---|:---|
| **Role** | AI Research Engineer & Doctoral Researcher |
| **Company** | Infineon Technologies AG, Munich, Germany |
| **PhD** | Meta-Learning for ADAS Perception @ University of Granada |
| **Experience** | 9 years in AI/ML & Computer Vision |
| **Publications** | 3 peer-reviewed (MDPI Applied Sciences & Electronics, 2024) |
| **Focus** | Sensor Fusion, 3D Detection, Meta-Learning, ADAS, Edge AI, VLMs, Vision-Language-Action (VLA), Robotics (ROS 2, SLAM, Nav2, mobile robot autonomy) |
| **Models** | Meta-YOLO v8-v11, PointPillars, LLaVA, SigLIP, Meta-DETR, DINOv2, BEVFusion |
| **Sensors** | XENSIV Radar (BGT60TR13C, BGT60ATR24C), REAL3 LiDAR (IRS2381C, IRS2875C) |
| **Hardware** | MFN100 NPU, NVIDIA Jetson |
| **Stack** | PyTorch, TensorRT, ONNX, ROS2, Docker, Jenkins, C++, CUDA |

---

## Currently Working On

- **Predictive autonomy with VIO for mobile robots.** A ROS 2 robot that drives through a busy factory hall, predicts where the people and a tugger cart are going, and plans around them. It localizes with visual-inertial odometry (RGB-D camera + IMU) fused with wheel odometry in an EKF, corrected by LiDAR against the map. Loosely and tightly coupled VIO.
- **Chain-of-Thought VLA for driving.** A "reason before act" agent that detects objects in 3D, explains in language *why* it should act, then predicts the driving trajectory and longitudinal control (nuScenes).
- **VLM-based ADAS perception.** Zero-shot driving scene understanding with LLaVA and camera-LiDAR fusion.
- **Sensor fusion research.** Camera, radar and LiDAR fusion for 3D object detection.

---

## Featured Projects

| | Project | What It Does | Key Results |
|:---:|---------|-------------|-------------|
| 1 | [**Predictive Autonomy with VIO**](https://github.com/VasuTammisetti/vio-autonomy-ros2) | A ROS 2 robot patrols a factory hall with moving people and a cart. LiDAR, camera, IMU and wheel fusion, a Kalman tracker with 5 s forecasts, Nav2 planning around predicted paths, a direction-aware safety gate, and CI | 7 of 8 stations in a 2 lap patrol, closest person 0.78 m, odometry drift halved by an EKF fix |
| 2 | [**ROS 2 Diff-Drive SLAM + Perception**](https://github.com/VasuTammisetti/ros2-diffdrive-slam) | A mobile robot built from scratch in ROS 2 Jazzy and Gazebo Harmonic: custom URDF, ros2_control, 2D LiDAR SLAM (slam_toolbox), YOLOv8n detection and a LLaVA VLM for scene understanding, all running live | LiDAR SLAM, YOLO and a VLM on one robot within an 8 GB GPU |
| 3 | [**BEV Map Fusion: Camera, LiDAR, HD Map**](https://github.com/VasuTammisetti/BEV-map-fusion) | Fuses 6 surround cameras, LiDAR and an HD map prior into one drivable BEV around the ego car on nuScenes: lane prior, lift-splat camera road, LiDAR depth correction and uncertainty-weighted fusion | Per-cell confidence weighting, runs on a single Colab T4 |
| 4 | [**CoT-VLA (Chain-of-Thought VLA)**](https://github.com/VasuTammisetti/CoT-Chain-of-thought-_VLA_ADAS) | Reason before act driving agent on nuScenes: 3D detection, LLaVA chain-of-thought reasoning, a trained trajectory head, then safety and longitudinal control scoring | Trajectory ADE ~2.9 m, ~82% steering accuracy, LLaVA-1.6 4-bit + SigLIP action head |
| 5 | [**VLM-LiDAR-Camera ADAS**](https://github.com/VasuTammisetti/VLM-LiDAR-Camera-ADAS-perception) | Zero-shot scene understanding using LLaVA with camera-LiDAR depth fusion on KITTI | No annotations, 4-bit quantized, Docker + Jenkins CI/CD |
| 6 | [**Multi-Modal 3D Detection**](https://github.com/VasuTammisetti/Multi-Modal_3D_Object_Detection_from_KITTI_Augmenting_LiDAR_with_Camera_Semantics) | LiDAR + camera late fusion for 3D object detection with BEV visualization | YOLOv8 + PointPillars, pure PyTorch, KITTI benchmark |
| 7 | [**LiDAR-Camera Depth Fusion**](https://github.com/VasuTammisetti/LiDAR_Camera-MiDAS-_Fusion_For-Better_Deapth-Map) | Dense metric depth from MiDaS plus LiDAR median scaling | Sparse to dense, metric scale, real time |
| 8 | [**Meta-YOLOv8 Traffic Detection**](https://github.com/VasuTammisetti/Meta-Learning-Enhanced-YOLOv8-for-Precision-Traffic-Light-Color-Detection-in-ADAS) | Meta-learning enhanced YOLOv8 for traffic light detection | 89% mAP, few-shot, published research |
| 9 | [**ROS2 Docker CV**](https://github.com/VasuTammisetti/ROS2_Docker_CV) | Containerized computer vision pipeline in ROS2 | Runs in Docker containers |
| 10 | [**Meta ML Deployment**](https://github.com/VasuTammisetti/Meta_ML_model_deployment_using_pycaret) | Meta-learning model deployment pipeline using PyCaret | AutoML, end-to-end MLOps |
| 11 | [**Python AI Agent**](https://github.com/VasuTammisetti/PythonAIAgent) | Agentic AI pipeline with LangChain and RAG | LangChain, RAG, autonomous agents |

## Spotlight: Predictive Autonomy in a Factory Hall (ROS 2)

A robot patrols a simulated 20 x 15 m factory hall while three people and a tugger cart move around it. It localizes with LiDAR, an RGB-D camera, an IMU and wheel odometry, tracks every person and the cart with a Kalman filter, predicts where each one is heading, and Nav2 plans around those predictions. Every velocity command goes through a safety gate first. Nobody sends it goals, it runs the patrol on its own.

| Layer | Component | Role |
|-------|-----------|------|
| **Localize** | robot_localization EKF (wheels, gyro, rtabmap visual odometry) + slam_toolbox on a saved map | odometry plus map correction, no GPS |
| **Predict** | Kalman tracker per agent, 5 s forecast | where the people and the cart will be |
| **Plan** | Nav2 (NavFn + DWB), forecasts in their own STVL costmap layer | routes around where people are going |
| **Protect** | direction-aware safety gate | slows down or stops motion towards a person, still lets the robot back off |
| **Test** | GitHub Actions: 40 pytest tests in a ROS container, flake8, bandit, pip-audit | catches regressions on every push |

Most of the work went into measuring and fixing problems. The wheel controller reported its turn rate 6% too high, the robot tipped back 19.5 deg when it accelerated, the EKF trusted the wheels over the gyro (fixing that halved the drift), and the camera odometry arrived 150 to 200 ms late and was silently dropped. In the final 2 lap run the robot reached 7 of 8 stations and no person came closer than 0.78 m.

## Spotlight: ROS 2 Mobile Robot, SLAM + Perception Stack

A differential-drive robot built from scratch in **ROS 2 Jazzy + Gazebo Harmonic** that runs a full perception stack live: **2D LiDAR SLAM** for mapping and localization, **YOLOv8n** for real-time object detection, and a **LLaVA vision-language model** for scene understanding on demand through a ROS service.

| Layer | Component | Role |
|-------|-----------|------|
| **Map** | slam_toolbox (2D LiDAR) | occupancy grid + localization, with loop closure |
| **Detect** | YOLOv8n (GPU, FP16) | real-time bounding boxes, 80 COCO classes |
| **Understand** | LLaVA-1.6-Mistral-7B (4-bit) | natural-language scene description on demand |
| **Drive** | ros2_control diff_drive_controller | velocity control, wheel odometry, TF |

The robot is described in URDF, driven with ros2_control, and maps a walled room while its camera detects and describes what it sees. LLaVA is served over FastAPI and called from a ROS service, so it only runs when asked, not on every frame. Everything was built and profiled on an 8 GB RTX 2070, which isn't enough to run detection and the VLM at the same time, so they run as separate modes. It's the ADAS perception stack (LiDAR, YOLO, LLaVA) moved onto a robot.

## Spotlight: Chain-of-Thought VLA for Autonomous Driving

A compact driving agent that **reasons before it acts**. For each front-camera keyframe it detects the objects around it in 3D, asks a vision-language model *why* it should do something, predicts the actual trajectory with a trained action head, and scores the safety and longitudinal control of that decision. The whole **perceive, reason, act, assess** loop, end to end.

| Stage | Component | Output |
|-------|-----------|--------|
| **Perceive** | nuScenes ground-truth 3D boxes | objects with class + metric distance |
| **Reason** | LLaVA-1.6-Mistral-7B (4-bit) | chain-of-thought: what it sees and why |
| **Act** | SigLIP + cross-attention head (trained) | 9-waypoint trajectory + speed + steering |
| **Assess** | safety score + kinematics | risk 0-100, TTC, deceleration, EV regen level |

The split is on purpose. LLaVA is good at explaining but unreliable with numeric waypoints, so a trained head handles the geometry and LLaVA handles the explanation. On the held-out nuScenes-mini test scenes the trajectory head reaches **~2.9 m ADE** over a 4.5 s horizon against the car's real recorded path, with **~82%** chain-of-thought steering agreement and an average safety score of **~70/100**. These are small-data numbers. The point is the complete, explainable pipeline, not state-of-the-art scale.

---

## Research Highlights

<table>
<tr>
<td width="50%">

### Key Achievements

- **Predictive autonomy (NEW).** A ROS 2 robot that tracks people and a cart, forecasts their paths and plans around them in a busy factory hall, with sensor fusion I measured and debugged step by step. 7 of 8 stations in a 2 lap patrol, nobody closer than 0.78 m.
- **ROS 2 robotics perception.** A mobile robot built from scratch in ROS 2 + Gazebo with LiDAR SLAM, YOLOv8 detection, ros2_control and a live LLaVA VLM, all within an 8 GB GPU.
- **Chain-of-Thought VLA.** A reason before act driving agent on nuScenes that pairs LLaVA chain-of-thought reasoning with a trained SigLIP action head and outputs real trajectories, steering and longitudinal control. ~2.9 m trajectory ADE and ~82% steering agreement on held-out scenes.
- **VLM for ADAS.** A zero-shot perception system with LLaVA that analyses driving scenes using camera and LiDAR, without task-specific training or annotation. It handles scene understanding, hazard detection and driving recommendations.
- **Industry-first** brake/signal classifier, **89% mAP** on MFN100 NPU
- **95% stereo depth accuracy** at 5-50 m range at 30 FPS
- **40% tracking robustness** improvement via meta-learning
- **85% deployment time reduction** in production pipelines
- **Sub-50 ms** end-to-end latency on edge hardware

</td>
<td width="50%">

### Why VLMs & VLAs for ADAS

Classic ADAS perception needs thousands of labelled images per object class and weeks of training. Vision-language models, and the vision-language-action models built on them, change that:

- They handle new driving scenes zero-shot, without retraining
- A VLA explains *why* it picks an action, then outputs the action itself (trajectory, steering, control)
- They describe a scene in plain language, not only with bounding boxes
- One pipeline covers detection, hazard assessment, planning and control
- No per-task annotation, which is the most expensive part of ADAS development
- They build on models pre-trained on huge amounts of visual data

I see them as an addition to classic detection pipelines, not a replacement. They add context and explanations on top of what the detectors already do well.

</td>
</tr>
</table>

### Publications & Industry Collaboration

- **3 peer-reviewed papers** in ADAS perception and meta-learning (MDPI Applied Sciences & Electronics, 2024)
- Production ADAS validation with **Continental** & **TTTech**
- Hands-on with **XENSIV Radar** (BGT60TR13C, BGT60ATR24C) and **REAL3 LiDAR** (IRS2381C, IRS2875C)
- Edge deployment on **MFN100 NPU** and **AURIX TC4x**

---

## Tech Stack

<table>
<tr>
<td><b>ML / DL</b></td>
<td>PyTorch, TensorRT, ONNX, YOLOv8-v11, LLaVA, SigLIP, Sentence-BERT, DINOv2, Meta-DETR, PointPillars, BEVFusion</td>
</tr>
<tr>
<td><b>VLM / VLA</b></td>
<td>LLaVA-1.6, Chain-of-Thought reasoning, cross-attention action heads, 4-bit quantization, zero-shot scene understanding</td>
</tr>
<tr>
<td><b>Robotics</b></td>
<td>ROS 2 Jazzy, Gazebo Harmonic, Nav2, slam_toolbox, robot_localization (EKF), rtabmap visual odometry, STVL costmaps, ros2_control, URDF/xacro, TF2, RViz</td>
</tr>
<tr>
<td><b>Sensor Fusion</b></td>
<td>REAL3 LiDAR, XENSIV Radar, Stereo Camera, RGB-D, IMU, Kalman Filter, EKF, Late/Early Fusion, BEV</td>
</tr>
<tr>
<td><b>Datasets</b></td>
<td>KITTI, nuScenes</td>
</tr>
<tr>
<td><b>Edge / Hardware</b></td>
<td>MFN100 NPU, AURIX TC4x, NVIDIA Jetson, INT8/FP16 Quantization, TensorRT</td>
</tr>
<tr>
<td><b>MLOps / DevOps</b></td>
<td>Docker, Jenkins, GitHub Actions, Kubernetes, MLflow, AWS SageMaker, GCP GKE</td>
</tr>
<tr>
<td><b>AI Agents</b></td>
<td>LangGraph, LangChain, RAG, Agentic AI Frameworks</td>
</tr>
<tr>
<td><b>Languages</b></td>
<td>Python, C++, CUDA, Bash</td>
</tr>
</table>

---

## GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=VasuTammisetti&theme=tokyonight&hide_border=true" height="150"/>

<p>
  <img src="https://img.shields.io/github/stars/VasuTammisetti?style=for-the-badge&logo=github&logoColor=white&label=Total%20Stars&color=1a1b27"/>
  <img src="https://img.shields.io/github/followers/VasuTammisetti?style=for-the-badge&logo=github&logoColor=white&label=Followers&color=1a1b27"/>
  <img src="https://img.shields.io/badge/Public%20Repos-10+-70a5fd?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Languages-Python%20%7C%20C++%20%7C%20Jupyter-bf91f3?style=for-the-badge&logo=github&logoColor=white"/>
</p>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=VasuTammisetti&theme=tokyo-night&hide_border=true&area=true" width="100%"/>

</div>

---

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/vasutammisetti">
  <img src="https://img.shields.io/badge/LinkedIn-Vasu_Tammisetti-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://zenodo.org/records/19111017">
  <img src="https://img.shields.io/badge/Zenodo-Dataset-024dad?style=for-the-badge&logo=zenodo&logoColor=white"/>
</a>

</div>

---
