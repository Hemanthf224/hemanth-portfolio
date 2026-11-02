<div align="center">

# Mudiam Hemanth Reddy
### AI & Systems Engineer | High-Performance Computing & Distributed Systems

[![GitHub](https://img.shields.io/badge/GitHub-Hemanthf224-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hemanthf224)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hemanth_Reddy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hemanth-reddy-9517b0340/)
[![Email](https://img.shields.io/badge/Email-hemanthredy48823%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hemanthredy48823@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-Download_PDF-00E5FF?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=black)](M%20HEMANTH%20REDDY.pdf)

<br/>

[![Status](https://img.shields.io/badge/STATUS-Available_for_SWE_%26_AI_Roles-10B981?style=flat-square&labelColor=0A0E17)](mailto:hemanthredy48823@gmail.com)
[![Education](https://img.shields.io/badge/AMRITA-B.Tech_AI_%26_DS_(8.26_CGPA)-3B82F6?style=flat-square&labelColor=0A0E17)](https://www.amrita.edu)
[![Core Stack](https://img.shields.io/badge/CORE_STACK-C++%20%7C%20CUDA%20%7C%20Python%20%7C%20Spark%20%7C%20FastAPI-6366F1?style=flat-square&labelColor=0A0E17)](https://github.com/Hemanthf224)
[![Architecture](https://img.shields.io/badge/PORTFOLIO-Zero_Build_React_18_%2B_Framer_Motion-A855F7?style=flat-square&labelColor=0A0E17)](index.html)

<br/>

> *"Bridging low-level hardware acceleration (CUDA, C++) with distributed big data pipelines (Spark, Kafka) and low-latency machine learning microservices."*

</div>

---

## 📌 Table of Contents

- [Overview & Technical Focus](#-overview--technical-focus)
- [Key Engineering Impact & Metrics](#-key-engineering-impact--metrics)
- [Featured Engineering Projects](#-featured-engineering-projects)
  - [1. AI Network Intrusion Detection System (SDN-OSHLD)](#1-ai-network-intrusion-detection-system-sdn-oshld)
  - [2. Distributed Real-Time Mobility & Fare Engine](#2-distributed-real-time-mobility--fare-engine)
  - [3. Adaptive GPU Graph Traversal Engine (CUDA / C++)](#3-adaptive-gpu-graph-traversal-engine-cuda--c)
  - [4. Electric Vehicle Stability via NMPC (TVC + RWS)](#4-electric-vehicle-stability-via-nmpc-tvc--rws)
- [System Architecture & Technical Arsenal](#-system-architecture--technical-arsenal)
- [Professional Experience & Education](#-professional-experience--education)
- [Portfolio Features & Design System](#-portfolio-features--design-system)
- [Quickstart & Local Preview](#-quickstart--local-preview)
- [Contact & Connect](#-contact--connect)

---

## 💻 Overview & Technical Focus

I am an **AI & Systems Engineer** with hands-on experience designing and implementing high-throughput, low-latency computational systems:

* **High-Performance Computing (HPC)**: Writing parallel GPU kernels in CUDA and C++ with memory coalescing, thread-pool task scheduling, and PyBind11 zero-copy bridges.
* **Distributed Big Data Engineering**: Designing batch and streaming pipelines in Apache Spark and Kafka to process tens of millions of records over Hadoop HDFS.
* **Applied Machine Learning & Microservices**: Building production-shaped FastAPI services that serve trained tree ensembles, gradient boosting models, and explainability layers (SHAP) under 100ms latency budgets.

---

## 📊 Key Engineering Impact & Metrics

```
┌───────────────────────────┬───────────────────────────┬───────────────────────────┬───────────────────────────┐
│   99.2% ACCURACY          │   17 GB+ DATA STREAMED    │   CUDA PARALLEL KERNELS   │   8.26 CGPA (AMRITA)      │
│   Network Intrusion Detection │   11M+ Records via Spark  │   BFS, PageRank, SSSP     │   B.Tech AI & Data Science│
│   CICIDS2017 & FastAPI    │   & Kafka Event Bus       │   NVIDIA GPU Accelerated  │   Strong CS Fundamentals  │
└───────────────────────────┴───────────────────────────┴───────────────────────────┴───────────────────────────┘
```

---

## 🚀 Featured Engineering Projects

### 1. AI Network Intrusion Detection System (SDN-OSHLD)
> **Asynchronous machine learning intrusion detection service deployed via Docker container for software-defined network traffic.**

```
[ Raw Network Telemetry ] ──► [ Feature Extraction ] ──► [ Ensemble Classifier ] ──► [ FastAPI Async REST ] ──► [ OpenFlow Switch ]
     Packet Capture (PCAP)       Flow Normalization         99.2% Accuracy Model        <100ms Latency SLA         Threat Throttled
```

* **Problem**: Software-defined networks are vulnerable to high-throughput DDoS and lateral penetration. Traditional signature firewalls struggle against novel zero-day attack sequences.
* **Architecture**: Trained tree-ensemble classifiers across three benchmark network flows. Packaged into an asynchronous FastAPI microservice containerized in Docker to ingest, extract telemetry features, and return classification flags with sub-100ms latency.
* **Tech Stack**: `Python`, `Scikit-learn`, `Pandas`, `FastAPI`, `Docker`, `REST API`
* **Benchmarks**: `99.2% Accuracy` | `<100ms Latency` | `3 Benchmark Datasets`

---

### 2. Distributed Real-Time Mobility & Fare Engine
> **End-to-end distributed data engineering pipeline processing 17 GB of urban mobility telemetry to forecast ride demand, dynamic surge multipliers, and ETA.**

```
[ 17GB NYC TLC Feed ] ──► [ Kafka Topic Stream ] ──► [ Apache Spark MLlib ] ──► [ HDFS Data Lake ] ──► [ Real-Time Surge & ETA ]
     Live Event Queue          Partition Consumer         Distributed Workers       Parquet Optimized         Sub-second API Served
```

* **Problem**: Ingesting high-velocity streaming ride telemetry and computing dynamic surge pricing and ETA across millions of events causes memory exhaustion on single-node instances.
* **Architecture**: Staged raw datasets on Hadoop HDFS and built distributed Spark MLlib regression pipelines over 11,000,000+ ride records. Integrated Apache Kafka event streams to simulate real-time fleet telemetry with live weather and spatial zone feature joins.
* **Tech Stack**: `Apache Spark`, `Hadoop HDFS`, `Kafka`, `Scala`, `Spark MLlib`, `Parquet`
* **Benchmarks**: `17 GB Data` | `11,000,000+ Records` | `Distributed Cluster Workers`

---

### 3. Adaptive GPU Graph Traversal Engine (CUDA / C++)
> **High-throughput parallel graph analytics engine executing BFS, PageRank, and SSSP on NVIDIA hardware.**

```
[ CSR Adjacency Matrix ] ──► [ CUDA Kernel Blocks ] ──► [ Worker Pool Scheduler ] ──► [ PyBind11 C++ Bridge ] ──► [ Live Dashboard ]
     Compressed Storage         Warp-Level Primitives      Failure-Tolerant Queue      Zero-Copy Memory Tensor     Telemetry Metrics
```

* **Problem**: Massive graph traversals suffer from severe CPU cache thrashing, irregular memory access patterns, and single-thread execution bottlenecks.
* **Architecture**: Custom CUDA kernels optimizing warp-level primitives and memory coalescing. Designed a C++ thread-pool scheduler with worker failure tolerance, bridged directly to a Python backend using PyBind11 for real-time telemetry streaming.
* **Tech Stack**: `C++`, `CUDA`, `PyBind11`, `FastAPI`, `Parallel Computing`
* **Benchmarks**: `CUDA Warp Acceleration` | `3 Core Graph Algorithms` | `Zero-Copy Memory Bridge`

---

### 4. Electric Vehicle Stability via NMPC (TVC + RWS)
> **MATLAB/Simulink framework uniting Torque Vectoring Control (TVC) and Rear-Wheel Steering (RWS) for extreme collision avoidance stability.**

```
[ Steering & Yaw Inputs ] ──► [ 2-DOF Vehicle Plant ] ──► [ PMP Solver (NMPC) ] ──► [ Differential Torque ] ──► [ Dynamic Yaw Lock ]
     Driver Maneuver             Fiala Non-Linear Tire       Low-Latency Horizon        Rear-Wheel Steer Angle     Extreme Maneuver Stability
```

* **Problem**: Dynamic sideslip divergence and vehicle rollover during high-speed emergency collision avoidance maneuvers under non-linear tire saturation.
* **Architecture**: Formulated a 2-DOF vehicle dynamic model incorporating non-linear Fiala tire mechanics, dynamic axle weight transfer, and reference yaw generation. Developed a low-latency Pontryagin's Minimum Principle (PMP) solver with soft sideslip constraints, validated under ISO double lane-change benchmarks.
* **Tech Stack**: `MATLAB`, `Simulink`, `Nonlinear MPC`, `Vehicle Dynamics`
* **Benchmarks**: `PMP Fast Solver` | `2-DOF Dynamic Plant` | `ISO Double Lane Change & Fishhook`

---

## 🛠️ System Architecture & Technical Arsenal

| Domain | Core Technologies & Primitives | Practical Applications |
|:---|:---|:---|
| **High-Performance & GPU Systems** | `C++`, `CUDA`, `PyBind11`, `POSIX Threads`, `Memory Coalescing` | GPU kernel optimizations, thread-pool scheduling, zero-copy Python tensor bindings. |
| **Distributed Big Data & Streaming** | `Apache Spark`, `Hadoop HDFS`, `Apache Kafka`, `Scala`, `Parquet` | 17GB+ distributed batch ETL, Spark MLlib models, streaming telemetry ingestion. |
| **Machine Learning & Modeling** | `Python`, `Scikit-learn`, `LightGBM`, `XGBoost`, `SHAP`, `SMOTE` | Multi-class attack classification, real-time financial fraud detection, explainable AI. |
| **Backend & Infrastructure** | `FastAPI`, `REST APIs`, `Docker`, `Linux / Bash`, `Git / GitHub` | Sub-100ms ASGI microservices, containerized deployments, automated CI/CD workflows. |

---

## 📜 Professional Experience & Education

### Experience
* **AI & Data Science Intern** — *XYlofy AI* (2026 • Remote)
  * Architected an end-to-end real-time financial fraud detection pipeline evaluating suspicious transactions.
  * Benchmarked LightGBM, XGBoost, and Isolation Forest; tuned decision thresholds for severe class imbalance.
  * Engineered SHAP explainability visualizations integrated into an interactive Streamlit risk assessment dashboard.

### Education
* **B.Tech in Artificial Intelligence & Data Science** — *Amrita Vishwa Vidyapeetham* (2024 — 2028)
  * **Current CGPA**: `8.26 / 10.0`
  * **Core Computer Science**: Data Structures & Algorithms, Operating Systems, Database Management Systems, Computer Networks.
  * **Advanced Electives**: Machine Learning, Deep Learning, Distributed Computing, Linear Algebra & Probability.
* **Intermediate (Class 12 - MPC)** — *Narayana Junior College, Telangana* (`94.2%`)

### Honors & Certifications
* **NVIDIA Deep Learning Institute**: Certificate in *Getting Started with AI on Jetson Nano*.
* **XYlofy AI**: *AI & Data Analytics Internship Certificate*.
* **National-Level Hackathon**: Team Lead & Finalist.
* **GenAI Powered Data Analytics**: Certified Simulation Completion.

---

## 🎨 Portfolio Features & Design System

The portfolio is built with a modern **Linear / Vercel design system**:
* **Zero-Build Standalone Architecture**: Runs natively in the browser via React 18, Babel Standalone, and Framer Motion—no massive `node_modules` folder required.
* **Interactive Developer Sandbox**: Live mock terminal executing simulated API requests (`POST /api/v1/detect-intrusion`), Spark cluster telemetry queries, and CUDA benchmark timings.
* **Interactive Tech Stack Matrix**: Categorized technology filtering with animated proficiency meters and engineering context.
* **Multi-Theme Engine**:
  * 🖤 **Obsidian (Default)**: Deep midnight slate with electric cyan accents.
  * ⚪ **Clean Light**: Minimalist paper white with cobalt blue accents.
  * 🟣 **Electric Violet**: Deep space navy with vivid purple accents.
  * 🟢 **Terminal Green**: Hacker terminal monochrome black and phosphor green.

---

## 🚀 Quickstart & Local Preview

Because the portfolio uses a standalone zero-build architecture, you can launch it instantly with any local HTTP server:

```bash
# Clone the repository
git clone https://github.com/Hemanthf224/hemanth-portfolio.git

# Enter project directory
cd hemanth-portfolio

# Launch with Python (built-in)
python -m http.server 3000
```
Open `http://localhost:3000` in your web browser.

---

## 📬 Contact & Connect

I am actively open to software engineering internships, AI systems roles, and high-performance computing collaborations:

<div align="center">

[![Email Me](https://img.shields.io/badge/Email-hemanthredy48823%40gmail.com-00E5FF?style=for-the-badge&logo=gmail&logoColor=black)](mailto:hemanthredy48823@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hemanth-reddy-9517b0340/)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hemanthf224)

<br/>

**Mudiam Hemanth Reddy**  
*AI & Systems Engineer* • Amrita Vishwa Vidyapeetham

</div>
