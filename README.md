
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,45:1B3A6B,100:7C3AED&height=250&section=header&text=GYEOMETRY&fontSize=65&fontColor=FFFFFF&fontAlignY=38&animation=fadeIn&desc=Seeing%20the%20Small.%20Exploring%20the%20Unknown.&descAlignY=60&descSize=19" width="100%" alt="Gyeometry Header" />

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=65E5FF&center=true&vCenter=true&width=780&lines=Undergraduate+Researcher+at+Hanbat+National+University;Tiny+Object+Detection+%7C+Aerial+Imagery;Open-Set+Segmentation+%7C+Forward-Looking+Sonar" alt="Typing Animation" />
</a>

<br>

<img src="https://img.shields.io/badge/Computer_Vision-1B3A6B?style=for-the-badge&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/Deep_Learning-7C3AED?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/AI_Research-087E8B?style=for-the-badge&logo=googlescholar&logoColor=white" />

</div>

<br>

---

## 📬 Contact

<div align="center">

**Feel free to reach out for research discussions, collaborations, or opportunities.**

<br>

<a href="mailto:kimkyum03@gmail.com">
<img src="https://img.shields.io/badge/Gmail-kimkyum03%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
</a>

</div>

<br>

---

## 👋 About Me

Hi! I'm **Gyeom Kim**, an undergraduate researcher in **Computer Engineering** at **Hanbat National University**, South Korea.

My research focuses on **Computer Vision and Deep Learning**, particularly tiny object detection and open-set semantic segmentation.

I'm interested in understanding **why models fail**, identifying their limitations, and developing better approaches through systematic experimentation.

- 🎓 **Education:** Hanbat National University, Computer Engineering
- 🔬 **Research:** Tiny Object Detection & Open-Set Semantic Segmentation
- 🧪 **Approach:** Failure Analysis, Model Improvement & Experimental Validation
- 🎯 **Interest:** Robust Visual Recognition under Challenging Conditions

<br>

## 🔭 Research Interests

<table>
<tr>
<td width="50%" valign="top">

<h3>🔍 Tiny Object Detection</h3>

<strong>Detecting objects that are easy to miss.</strong>

<ul>
<li>Aerial imagery analysis</li>
<li>DETR-based object detection</li>
<li>High-resolution feature refinement</li>
<li>Very tiny object localization</li>
</ul>

</td>
<td width="50%" valign="top">

<h3>🌊 Open-Set Segmentation</h3>

<strong>Recognizing what models have never seen.</strong>

<ul>
<li>Forward-looking sonar imagery</li>
<li>Unknown object discovery</li>
<li>Open-set semantic segmentation</li>
<li>Uncertainty and failure analysis</li>
</ul>

</td>
</tr>
</table>

<br>

---

## 📚 Publications & Manuscripts

### 🟢 Accepted

**[C1] Density-Aware Query Score Adjustment for Tiny Object Detection**

**Gyeom Kim**, Ki-won Eom, Seong-min Pyo, Haneol Jang

*2026 KIBME Summer Conference, July 2026*

![Accepted](https://img.shields.io/badge/Status-Accepted-238636?style=flat-square)
![Conference](https://img.shields.io/badge/Type-Conference_Paper-1B3A6B?style=flat-square)

> Proposed an inference-time density-aware query score adjustment method, improving F1 by **0.3–0.5 percentage points** across Dome-DETR model scales while maintaining comparable mAP on AI-TODv2.

<br>

### 🟡 Under Review

**[C2] Improving Tiny Object Detection through High-Frequency Enhancement of High-Resolution Features**

**Gyeom Kim**, Ki-won Eom, Haneol Jang

*2026 KIBME Fall Conference*

![Under Review](https://img.shields.io/badge/Status-Under_Review-D29922?style=flat-square)
![Conference](https://img.shields.io/badge/Type-Conference_Paper-1B3A6B?style=flat-square)

> Proposed local high-frequency enhancement of high-resolution features, improving the mean AP across Very Tiny, Tiny, and Small groups by **3.3 percentage points** over SMWG-DETR.

<br>

**[J1] Improving Tiny Object Detection via High-Resolution Feature Refinement**

**Gyeom Kim**, Ki-won Eom, Haneol Jang

*Submitted to IKEEE*

![Under Review](https://img.shields.io/badge/Status-Under_Review-D29922?style=flat-square)
![Journal](https://img.shields.io/badge/Type-Journal_Manuscript-7C3AED?style=flat-square)

> Proposed learnable high-resolution feature refinement, achieving **+3.7 percentage points in mean AP** and **+5.6 percentage points in Very Tiny AP** over SMWG-DETR on AI-TODv2.

<br>

---

## 🔬 Research Experience

### 01. Tiny Object Detection in Aerial Imagery

![Object Detection](https://img.shields.io/badge/Object_Detection-1B3A6B?style=flat-square)
![DETR](https://img.shields.io/badge/DETR-7C3AED?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Research Focus:** Improving the detection and localization of extremely small objects in aerial imagery.

- Investigated limitations of DETR-based detectors for tiny objects using AI-TODv2.
- Explored density-aware query selection and high-resolution feature refinement.
- Conducted comparative experiments and failure analysis across different object sizes.

**Key Result:** Improved Very Tiny AP by **5.6 percentage points** compared with SMWG-DETR using high-resolution feature refinement.

<details>
<summary><b>🔎 Research Details & Experimental Approach</b></summary>

<br>

**1. Density-Aware Query Score Adjustment (DAQSA)**

- Analyzed query selection imbalance between sparse and dense object regions.
- Adjusted encoder query scores based on local density information.
- Evaluated the method across Dome-DETR-S, M, and L.
- Observed consistent F1 improvements while largely preserving mAP.

**2. High-Resolution Feature Enhancement**

- Investigated spatial information loss caused by feature downsampling.
- Introduced stride-4 high-resolution features into the detection pipeline.
- Extracted local high-frequency components using average-pooling residuals.
- Evaluated detection performance across Very Tiny, Tiny, and Small object groups.

**3. Learnable Feature Refinement**

- Extended high-frequency enhancement using lightweight depthwise and pointwise convolutions.
- Applied a learnable scaling parameter to control residual feature contributions.
- Compared performance against SMWG-DETR and other DETR-based detectors.
- Analyzed detection accuracy, localization quality, and computational cost.

**Evaluation Note**

The reported mean AP is the equally weighted arithmetic mean of AP across the Very Tiny, Tiny, and Small object groups, rather than overall COCO mAP.

</details>

<br>

### 02. Open-Set Semantic Segmentation for Forward-Looking Sonar

![Segmentation](https://img.shields.io/badge/Semantic_Segmentation-1B3A6B?style=flat-square)
![Open Set](https://img.shields.io/badge/Open--Set_Recognition-7C3AED?style=flat-square)
![Ongoing](https://img.shields.io/badge/Research-Ongoing-087E8B?style=flat-square)

**Research Focus:** Discovering previously unseen objects in underwater sonar imagery.

- Investigating open-set semantic segmentation using Forward-Looking Sonar (FLS) imagery.
- Analyzing the limitations of uncertainty-based unknown-object detection.
- Designing controlled experiments to isolate the causes of unknown-object detection failures.

**Current Direction:** Improving reliable unknown-object discovery while reducing false-positive predictions.

<details>
<summary><b>🔎 Research Details & Experimental Approach</b></summary>

<br>

**1. Baseline Analysis**

- Evaluated open-set segmentation performance under different unknown-object difficulty levels.
- Analyzed precision, recall, F1, AUROC, and AUPRC.
- Investigated false-positive predictions and failure cases in unknown-object detection.

**2. Unknown-Object Proposal Investigation**

- Examined cases where unknown-object candidates were never formed or were lost during inference.
- Evaluated alternative proposal-generation strategies.
- Analyzed trade-offs between unknown-object recovery and false-positive burden.

**3. Controlled Experiments**

- Designed direct-supervision experiments to investigate the upper bound of known/unknown separability.
- Compared native open-set inference with explicitly supervised unknown-object recognition.
- Studied the effect of backbone pretraining on known-class accuracy and unknown-object discovery.

**Research Status**

Ongoing research. Current results are used primarily for failure diagnosis and method development rather than claims of a finalized open-set solution.

</details>

<br>

---

## 🏅 AI Competitions

### 🌬️ 01. BARAM 2026 — Wind Power Forecasting

![DACON](https://img.shields.io/badge/Platform-DACON-1B3A6B?style=flat-square)
![Rank](https://img.shields.io/badge/Rank-103%20%2F%20985-238636?style=flat-square)
![Top](https://img.shields.io/badge/Top-10.5%25-7C3AED?style=flat-square)

**3rd Wind Power Forecasting AI Competition — BARAM 2026**

**Competition Result:** 103rd out of 985 (Top 10.5%)

**Project Overview:** Wind power generation forecasting using machine-learning models, feature engineering, and reliability-aware prediction methods.

**Key Contributions**
- Developed group-specific forecasting models using LightGBM.
- Conducted extensive feature engineering and comparative experiments.
- Improved public evaluation performance through reliability-aware prediction adjustments.

**Observed Public Leaderboard Improvements**

- Total Score: **0.6149 → 0.6269**
- FiCR: **0.3599 → 0.3806**

**Tech Stack:** `Python` · `LightGBM` · `Feature Engineering` · `Time-Series Forecasting`

<details>
<summary><b>🔎 Technical Details</b></summary>

<br>

- Explored multiple feature configurations and model combinations.
- Evaluated forecasting accuracy and reliability-oriented metrics.
- Investigated the relationship between prediction stability and competition score.
- Applied group-specific modeling and post-processing adjustments.
- Analyzed unsuccessful experiments to guide subsequent model selection.

</details>

🔗 [Competition Page](https://dacon.io/competitions/official/236727/overview/description)

<br>

### 🚗 02. Black-Box Video Forensics for Intentional Collision Analysis

![DACON](https://img.shields.io/badge/Platform-DACON-1B3A6B?style=flat-square)
![Rank](https://img.shields.io/badge/Leaderboard-114%20%2F%20321-D29922?style=flat-square)
![Video](https://img.shields.io/badge/Video_Analysis-7C3AED?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**AI Competition | DACON, 2026**

**Leaderboard Snapshot:** 114th out of 321 teams (final ranking unverified)

**Leaderboard Score:** **0.50266**

**Project Overview:** A multi-stage video analysis project addressing recaptured-video detection, collision-scene reasoning, and vehicle motion classification under offline inference constraints.

**Key Contributions**
- Investigated a multi-stage approach combining video classification, object tracking, and motion analysis.
- Evaluated stage-level predictions and reviewed accident-scene interpretation results.
- Conducted experimental validation, submission decisions, and data/model licensing checks.

**Tech Stack:** `Python` · `PyTorch` · `OpenCV` · `Swin Transformer` · `DINOv2` · `RAFT` · `YOLOP`

<details>
<summary><b>🔎 Technical Details & Challenges</b></summary>

<br>

**Stage 1 — Recaptured-Video Detection**

- Swin Transformer-based image classification.
- Temporal forensic features and auxiliary DINO-based analysis.
- Conservative decision rules for ambiguous recordings.

**Stage 2 — Collision Scene Analysis**

- Vehicle detection and lightweight object tracking.
- Trajectory features and geometric entry-time estimation.
- Road-corridor reasoning and contextual analysis.

**Stage 3 — Vehicle Motion Recognition**

- Optical-flow-based motion analysis.
- RANSAC-based camera motion estimation.
- RAFT-small flow features and DINOv2-based contextual correction.

**Technical Challenges**

- Integrating multiple models under a 60-minute offline inference constraint.
- Handling dependencies and checkpoint packaging for submission.
- Maintaining consistency across the three evaluation stages.
- Balancing model complexity, inference time, and prediction robustness.

**Verification Note**

The architecture summary is based on preserved project artifacts. The latest preserved package was not independently confirmed as a successfully scored submission. Model implementation was assisted by Codex, while experimental decisions, manual review, and validation were part of the project workflow.

</details>

🔗 [Competition Page](https://www.dacon.io/competitions/official/236753/overview/description)

<br>

---

## 💻 Selected Course Projects

### 🏆 01. Face Anti-Spoofing Image Classification

![Computer Vision](https://img.shields.io/badge/Computer_Vision-1B3A6B?style=flat-square)
![VLM](https://img.shields.io/badge/Vision--Language-7C3AED?style=flat-square)
![1st Place](https://img.shields.io/badge/Course_Competition-1st_Place-238636?style=flat-square)

**AI Course Team Competition | Hanbat National University, 2026**

**Result:** 1st place on the final private leaderboard as a 3-member team in a course-level competition involving approximately 80 students.

**Private Leaderboard Accuracy:** **99.41%**

- Developed an image-text feature-based approach for face anti-spoofing classification.
- Combined Prompt-Diff representations, MLP classification, test-time augmentation, and soft ensembling.

<details>
<summary><b>🔎 Implementation Details</b></summary>

<br>

- Utilized MoGA-ETA image-text representations.
- Constructed Prompt-Diff relation features for classification.
- Applied an MLP-based classification approach.
- Explored test-time augmentation and model ensembling.
- Evaluated performance using the competition's private leaderboard.

</details>

<br>

### ⚙️ 02. Embedded Vision & Smart Elevator Control

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-1B3A6B?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Regular Coursework Team Project | Hanbat National University**

**Project Overview:** An elevator control prototype integrating camera-based occupancy analysis with FPGA-controlled hardware.

**My Contributions**
- Implemented Raspberry Pi-based person detection and occupancy analysis.
- Developed occupancy-state decision logic and GPIO communication with FPGA hardware.

**System Architecture**

`Camera → Raspberry Pi → GPIO → FPGA → Elevator Control`

<details>
<summary><b>🔎 Implementation Details</b></summary>

<br>

- Captured and processed camera input on Raspberry Pi.
- Analyzed detected person regions to determine occupancy conditions.
- Communicated occupancy information through GPIO signals.
- Worked on motor-control functionality and hardware integration.
- Tested communication between the vision and elevator-control subsystems.

</details>

<br>

### 🔐 03. IoT Smart Door Lock with Face Recognition

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-1B3A6B?style=flat-square&logo=flask&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-7C3AED?style=flat-square)

**Regular Coursework Team Project | Hanbat National University**

**Project Overview:** A distributed IoT smart door lock prototype integrating face recognition, Raspberry Pi devices, and an Android management application.

**My Contributions**
- Built a Raspberry Pi server for user data and communication management.
- Developed an Android application for user registration and face-image management.
- Integrated the mobile application and server through HTTP APIs.

**System Architecture**

`Android App → Raspberry Pi 3 Server → Raspberry Pi 5 Edge Device → Door Lock`

<details>
<summary><b>🔎 System Features & Implementation</b></summary>

<br>

**System Features**
- OpenCV Haar Cascade-based face detection.
- MobileFaceNet-based facial feature extraction.
- Cosine similarity-based face verification.
- Sensor-triggered recognition and door-control logic.

**System Integration**
- Raspberry Pi 3 server for data management and API communication.
- Raspberry Pi 5 edge device for recognition and hardware control.
- Android Studio application for image upload and user management.
- Flask-based HTTP communication and synchronization.

</details>

<br>

### 🎮 04. Angry Humans — 3D Physics-Based Slingshot Game

![Unity](https://img.shields.io/badge/Unity-20232A?style=flat-square&logo=unity&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=sharp&logoColor=white)
![Game Physics](https://img.shields.io/badge/Game_Physics-1B3A6B?style=flat-square)
![Course Project](https://img.shields.io/badge/Course_Project-7C3AED?style=flat-square)

**Regular Coursework Team Project | Hanbat National University | 2-Member Team**

**Project Overview:** A Unity-based 3D slingshot puzzle game featuring projectile physics, destructible structures, and interactive mechanics.

**My Contributions**
- Implemented projectile motion, collision interactions, and structure destruction.
- Developed gravity-based trajectory prediction and mouse-drag launch controls.
- Implemented gameplay mechanics including portals, bombs, collectible coins, and skills.

**Technical Focus:** `Unity` · `C#` · `Game Physics` · `Gameplay Programming`

<details>
<summary><b>🔎 Implementation Details</b></summary>

<br>

- Calculated projectile trajectories using gravity-based motion equations.
- Visualized predicted trajectories using Unity LineRenderer.
- Implemented drag-based launch power and direction controls.
- Applied nonlinear power adjustment to improve control responsiveness.
- Developed boss cutscenes, camera behavior, and sound management.
- Integrated custom gameplay mechanics with Unity's physics system.

</details>

<br>

---

## 🛠️ Technical Skills

<div align="center">

### Programming Languages

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=sharp&logoColor=white" alt="C Sharp" />

<br>

### AI & Computer Vision

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/Torchvision-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="Torchvision" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/LightGBM-247A36?style=for-the-badge" alt="LightGBM" />

<br>

### Development Tools

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/CUDA--Enabled_GPU-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA-enabled GPU" />
<img src="https://img.shields.io/badge/Flask-303030?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />

<br>

### Game Development & Embedded Systems

<img src="https://img.shields.io/badge/Unity-20232A?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="Android Studio" />
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi" />
<img src="https://img.shields.io/badge/FPGA_Integration-1B3A6B?style=for-the-badge" alt="FPGA Integration" />

</div>

<br>

---

## 📊 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Gyeometry&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=65E5FF&text_color=FFFFFF&icon_color=A78BFA" alt="Gyeometry GitHub Stats" height="180" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gyeometry&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=65E5FF&text_color=FFFFFF" alt="Most Used Languages" height="180" />

</div>

<br>

---

<div align="center">

*"Understanding what a model misses is the first step toward making it better."*

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,45:1B3A6B,100:7C3AED&height=120&section=footer" width="100%" alt="Footer" />

