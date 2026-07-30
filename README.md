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
| **Focus** | Sensor Fusion, 3D Detection, Meta-Learning, ADAS, Edge AI, VLMs, Vision-Language-Action (VLA), Robotics Perception (ROS 2, SLAM) |
| **Models** | Meta-YOLO v8-v11, PointPillars, LLaVA, SigLIP, Meta-DETR, DINOv2, BEVFusion |
| **Sensors** | XENSIV Radar (BGT60TR13C, BGT60ATR24C), REAL3 LiDAR (IRS2381C, IRS2875C) |
| **Hardware** | MFN100 NPU, NVIDIA Jetson |
| **Stack** | PyTorch, TensorRT, ONNX, ROS2, Docker, Jenkins, C++, CUDA |

---

## Currently Working On

- Chain-of-Thought VLA for Driving -- A "reason-before-act" agent that detects objects in 3D, reasons in language about *why* to act, then predicts the actual driving trajectory and longitudinal control (nuScenes)
- VLM-based ADAS Perception -- Zero-shot driving scene understanding using LLaVA with Camera-LiDAR fusion
- Robotics Perception -- A ROS 2 mobile robot with LiDAR SLAM, YOLOv8 detection, and a LLaVA VLM running live, bringing the ADAS perception stack onto a robot platform
- Sensor Fusion Research -- Camera-Radar-LiDAR fusion for robust 3D object detection

---

## Featured Projects
| | Project | What It Does | Key Results |
|:---:|---------|-------------|-------------|
| 1 | [**ROS 2 Diff-Drive SLAM + Perception**](https://github.com/VasuTammisetti/ros2-diffdrive-slam) | A mobile robot built from scratch in ROS 2 Jazzy + Gazebo Harmonic: custom URDF, ros2_control driving, 2D LiDAR SLAM (slam_toolbox), YOLOv8n detection, and a LLaVA VLM for scene understanding -- all running live | LiDAR SLAM + YOLO + VLM on one robot, ros2_control, GPU-budgeted perception |
| 2 | [**BEV Map Fusion -- Camera·LiDAR·HD-Map**](https://github.com/VasuTammisetti/BEV-map-fusion) | Fuses 6 surround cameras, LiDAR, and an HD-map prior into a unified ego-centric drivable BEV on nuScenes: lane prior + lift-splat camera road + LiDAR depth correction + uncertainty-weighted fusion | Camera·LiDAR·map fusion, per-cell confidence weighting, single Colab T4 |
| 3 | [**CoT-VLA -- Chain-of-Thought VLA**](https://github.com/VasuTammisetti/CoT-Chain-of-thought-_VLA_ADAS) | Reason-before-act driving agent on nuScenes: 3D detection -> LLaVA chain-of-thought reasoning -> trained trajectory head -> safety & longitudinal control scoring | Trajectory ADE ~2.9m, ~82% steering accuracy, LLaVA-1.6 4-bit + SigLIP action head |
| 4 | [**VLM-LiDAR-Camera ADAS**](https://github.com/VasuTammisetti/VLM-LiDAR-Camera-ADAS-perception) | Zero-shot scene understanding using LLaVA with Camera-LiDAR depth fusion on KITTI | Zero annotations, 4-bit quantized, Docker + Jenkins CI/CD |
| 5 | [**Multi-Modal 3D Detection**](https://github.com/VasuTammisetti/Multi-Modal_3D_Object_Detection_from_KITTI_Augmenting_LiDAR_with_Camera_Semantics) | LiDAR + Camera late fusion for 3D object detection with BEV visualization | YOLOv8 + PointPillars, Pure PyTorch, KITTI benchmark |
| 6 | [**LiDAR-Camera Depth Fusion**](https://github.com/VasuTammisetti/LiDAR_Camera-MiDAS-_Fusion_For-Better_Deapth-Map) | Dense metric depth via MiDaS + LiDAR median scaling | Sparse-to-dense, Metric-accurate, Real-time |
| 7 | [**Meta-YOLOv8 Traffic Detection**](https://github.com/VasuTammisetti/Meta-Learning-Enhanced-YOLOv8-for-Precision-Traffic-Light-Color-Detection-in-ADAS) | Meta-learning enhanced YOLOv8 for traffic light detection | 89% mAP, Few-shot adaptive, Published research |
| 8 | [**ROS2 Docker CV**](https://github.com/VasuTammisetti/ROS2_Docker_CV) | Containerized computer vision pipeline in ROS2 | Production-ready, Docker orchestrated |
| 9 | [**Meta ML Deployment**](https://github.com/VasuTammisetti/Meta_ML_model_deployment_using_pycaret) | Meta-learning model deployment pipeline using PyCaret | AutoML, End-to-end MLOps |
| 10 | [**Python AI Agent**](https://github.com/VasuTammisetti/PythonAIAgent) | Agentic AI pipeline with LangChain and RAG | LangChain, RAG, Autonomous agents |

## Spotlight: ROS 2 Mobile Robot -- SLAM + Perception Stack

A differential-drive robot built from scratch in **ROS 2 Jazzy + Gazebo Harmonic** that runs a full perception stack live: **2D LiDAR SLAM** for mapping and localization, **YOLOv8n** for real-time object detection, and a **LLaVA vision-language model** for on-demand scene understanding through a ROS service.

| Layer | Component | Role |
|-------|-----------|------|
| **Map** | slam_toolbox (2D LiDAR) | occupancy grid + localization, with loop closure |
| **Detect** | YOLOv8n (GPU, FP16) | real-time bounding boxes, 80 COCO classes |
| **Understand** | LLaVA-1.6-Mistral-7B (4-bit) | natural-language scene description on demand |
| **Drive** | ros2_control diff_drive_controller | velocity control, wheel odometry, TF |

The robot is described in URDF, driven with ros2_control, and maps a walled room while its camera detects and describes what it sees. The LLaVA model is served over FastAPI and queried from a ROS service, so scene understanding runs on demand rather than every frame. Built and profiled on an 8 GB RTX 2070, the project runs detection and the VLM as separate perception modes to stay within the VRAM budget -- a deliberate engineering trade-off rather than assuming unlimited hardware. It carries the ADAS perception stack (LiDAR, YOLO, LLaVA) onto a live robot platform.

## Spotlight: Chain-of-Thought VLA for Autonomous Driving

A compact autonomous-driving agent that **reasons before it acts**. For each front-camera keyframe it detects surrounding objects in 3D, asks a vision-language model *why* it should do something, predicts the actual driving trajectory with a trained action head, and scores the safety and longitudinal control of the decision -- the full **perceive -> reason -> act -> assess** loop, end to end.

| Stage | Component | Output |
|-------|-----------|--------|
| **Perceive** | nuScenes ground-truth 3D boxes | objects with class + metric distance |
| **Reason** | LLaVA-1.6-Mistral-7B (4-bit) | chain-of-thought: what it sees and why |
| **Act** | SigLIP + cross-attention head (trained) | 9-waypoint trajectory + speed + steering |
| **Assess** | safety score + kinematics | risk 0-100, TTC, deceleration, EV regen level |

The split is deliberate: LLaVA reasons in language but is unreliable at numeric waypoints, so a trained head owns the geometry while LLaVA owns the explanation. Evaluated on the held-out nuScenes-mini test scenes, the trajectory head reaches **~2.9m ADE** over a 4.5s horizon against the car's real recorded path, with **~82%** chain-of-thought steering agreement and an average safety score of **~70/100**. These are honest small-data numbers -- the value is the complete, explainable pipeline rather than state-of-the-art scale.

---

## Research Highlights

<table>
<tr>
<td width="50%">

### Key Achievements

- **ROS 2 Robotics Perception (NEW)** -- Built a mobile robot from scratch in ROS 2 + Gazebo with LiDAR SLAM, YOLOv8 detection, ros2_control driving, and a live LLaVA VLM, bringing the ADAS perception stack onto a robot platform within an 8 GB GPU budget.
- **Chain-of-Thought VLA** -- Built a reason-before-act driving agent on nuScenes that pairs LLaVA chain-of-thought reasoning with a trained SigLIP action head, outputting real driving trajectories, steering and longitudinal control (not just bounding boxes). ~2.9m trajectory ADE and ~82% steering agreement on held-out scenes.
- **VLM for ADAS** -- Built a zero-shot perception system using Vision Language Models (LLaVA) that analyzes driving scenes with Camera-LiDAR fusion, eliminating the need for costly annotation pipelines. This bridges the gap between foundation models and safety-critical autonomous driving, enabling scene understanding, hazard detection, and driving recommendations without any task-specific training.
- **Industry-first** brake/signal classifier -- **89% mAP** on MFN100 NPU
- **95% stereo depth accuracy** at 5-50m range at 30 FPS
- **40% tracking robustness** improvement via meta-learning
- **85% deployment time reduction** in production pipelines
- **Sub-50ms** end-to-end latency on edge hardware

</td>
<td width="50%">

### Why VLMs & VLAs for ADAS Matter

Traditional ADAS perception requires thousands of annotated images per object class and weeks of model training. Vision Language Models -- and the Vision-Language-Action models built on top of them -- change this paradigm:

- **Zero-shot capability** -- Understands new driving scenarios without retraining
- **Reasoning, not just detection** -- VLA models explain *why* an action is chosen, then output the action itself (trajectory, steering, control)
- **Natural language output** -- Produces human-readable scene descriptions instead of just bounding boxes
- **Multi-task in one loop** -- Object detection, hazard assessment, planning and control from one pipeline
- **Annotation-free perception** -- Eliminates the most expensive bottleneck in ADAS development
- **Foundation model leverage** -- Builds on billions of parameters pre-trained on diverse visual knowledge

This represents the future direction of perception and planning in autonomous driving, where foundation models complement traditional detection pipelines for richer situational awareness and explainable decisions.

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
<td>ROS 2 Jazzy, Gazebo Harmonic, slam_toolbox (2D SLAM), ros2_control, URDF/xacro, TF2, RViz</td>
</tr>
<tr>
<td><b>Sensor Fusion</b></td>
<td>REAL3 LiDAR, XENSIV Radar, Stereo Camera, Kalman Filter, Late/Early Fusion, BEV</td>
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
<td>Docker, Jenkins, Kubernetes, MLflow, AWS SageMaker, GCP GKE</td>
</tr>
<tr>
<td><b>Robotics / AI</b></td>
<td>ROS2, LangGraph, LangChain, RAG, Agentic AI Frameworks</td>
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
  <img src="https://img.shields.io/badge/Public%20Repos-9+-70a5fd?style=for-the-badge&logo=github&logoColor=white"/>
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
