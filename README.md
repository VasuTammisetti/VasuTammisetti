<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:6e40c9&height=180&section=header&text=Vasu%20Tammisetti&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=AI%20Research%20Engineer%20%7C%20Doctoral%20Researcher%20%7C%20ADAS%20Perception&descAlignY=58&descSize=15&animation=fadeIn" width="100%"/>

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
| **Experience** | 8+ years in AI/ML & Computer Vision |
| **Publications** | 3 peer-reviewed (MDPI Applied Sciences & Electronics, 2024) |
| **Focus** | Sensor Fusion, 3D Detection, Meta-Learning, ADAS, Edge AI, VLMs |
| **Models** | Meta-YOLO v8-v11, PointPillars, LLaVA, Meta-DETR, DINOv2, BEVFusion |
| **Sensors** | XENSIV Radar (BGT60TR13C, BGT60ATR24C), REAL3 LiDAR (IRS2381C, IRS2875C) |
| **Hardware** | MFN100 NPU, AURIX TC4x, NVIDIA Jetson |
| **Stack** | PyTorch, TensorRT, ONNX, ROS2, Docker, Jenkins, C++, CUDA |

---

## Currently Working On

- VLM-based ADAS Perception -- Zero-shot driving scene understanding using LLaVA with Camera-LiDAR fusion
- PhD Dissertation -- Meta-Learning for Adaptive ADAS Perception (University of Granada, defense 2026)
- Sensor Fusion Research -- Camera-Radar-LiDAR fusion for robust 3D object detection

---

## Featured Projects

| | Project | What It Does | Key Results |
|:---:|---------|-------------|-------------|
| 1 | [**VLM-LiDAR-Camera ADAS**](https://github.com/VasuTammisetti/VLM-LiDAR-Camera-ADAS-perception) | Zero-shot scene understanding using LLaVA with Camera-LiDAR depth fusion on KITTI | Zero annotations, 4-bit quantized, Docker + Jenkins CI/CD |
| 2 | [**Multi-Modal 3D Detection**](https://github.com/VasuTammisetti/Multi-Modal_3D_Object_Detection_from_KITTI_Augmenting_LiDAR_with_Camera_Semantics) | LiDAR + Camera late fusion for 3D object detection with BEV visualization | YOLOv8 + PointPillars, Pure PyTorch, KITTI benchmark |
| 3 | [**LiDAR-Camera Depth Fusion**](https://github.com/VasuTammisetti/LiDAR_Camera-MiDAS-_Fusion_For-Better_Deapth-Map) | Dense metric depth via MiDaS + LiDAR median scaling | Sparse-to-dense, Metric-accurate, Real-time |
| 4 | [**Meta-YOLOv8 Traffic Detection**](https://github.com/VasuTammisetti/Meta-Learning-Enhanced-YOLOv8-for-Precision-Traffic-Light-Color-Detection-in-ADAS) | Meta-learning enhanced YOLOv8 for traffic light detection | 89% mAP, Few-shot adaptive, Published research |
| 5 | [**ROS2 Docker CV**](https://github.com/VasuTammisetti/ROS2_Docker_CV) | Containerized computer vision pipeline in ROS2 | Production-ready, Docker orchestrated |
| 6 | [**Meta ML Deployment**](https://github.com/VasuTammisetti/Meta_ML_model_deployment_using_pycaret) | Meta-learning model deployment pipeline using PyCaret | AutoML, End-to-end MLOps |
| 7 | [**Python AI Agent**](https://github.com/VasuTammisetti/PythonAIAgent) | Agentic AI pipeline with LangChain and RAG | LangChain, RAG, Autonomous agents |

---

## Research Highlights

<table>
<tr>
<td width="50%">

### Key Achievements

- **VLM for ADAS (NEW)** -- Built a zero-shot perception system using Vision Language Models (LLaVA) that analyzes driving scenes with Camera-LiDAR fusion, eliminating the need for costly annotation pipelines. This bridges the gap between foundation models and safety-critical autonomous driving, enabling scene understanding, hazard detection, and driving recommendations without any task-specific training.
- **Industry-first** brake/signal classifier -- **89% mAP** on MFN100 NPU
- **95% stereo depth accuracy** at 5-50m range at 30 FPS
- **40% tracking robustness** improvement via meta-learning
- **85% deployment time reduction** in production pipelines
- **Sub-50ms** end-to-end latency on edge hardware

</td>
<td width="50%">

### Why VLMs for ADAS Matter

Traditional ADAS perception requires thousands of annotated images per object class and weeks of model training. Vision Language Models change this paradigm:

- **Zero-shot capability** -- Understands new driving scenarios without retraining
- **Natural language output** -- Produces human-readable scene descriptions instead of just bounding boxes
- **Multi-task in one model** -- Object detection, hazard assessment, and driving recommendations from a single forward pass
- **Annotation-free** -- Eliminates the most expensive bottleneck in ADAS development
- **Foundation model leverage** -- Builds on billions of parameters pre-trained on diverse visual knowledge

This represents the future direction of perception systems in autonomous driving, where foundation models complement traditional detection pipelines for richer situational awareness.

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
<td>PyTorch, TensorRT, ONNX, YOLOv8-v11, LLaVA, DINOv2, Meta-DETR, PointPillars, BEVFusion</td>
</tr>
<tr>
<td><b>Sensor Fusion</b></td>
<td>REAL3 LiDAR, XENSIV Radar, Stereo Camera, Kalman Filter, Late/Early Fusion, BEV</td>
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

<img src="https://github-readme-stats.vercel.app/api?username=VasuTammisetti&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VasuTammisetti&layout=compact&theme=tokyonight&hide_border=true" height="150"/>

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

<div align="center">

*Open to ML Engineering, ADAS Perception, Sensor Fusion, Computer Vision, and Robotics roles in Germany *

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6e40c9,50:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/>

</div>
