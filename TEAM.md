# 👥 Team Roles & Responsibilities

This document outlines the team structure, roles, and responsibilities for the **Object Detection in Hazy and Foggy Conditions on NVIDIA Jetson Nano** project.

---

## 🏫 Institution

**School of Electrical Engineering and Computer Science (SEECS)**  
National University of Sciences and Technology (NUST), Islamabad, Pakistan

---

## 👨‍💻 Project Team

### Wassi Haider Kabir
**Role:** Team Lead / Embedded Engineer

| Responsibility | Description |
|----------------|-------------|
| Project Management | Coordinate team activities, manage project board |
| Embedded Development | Jetson Nano deployment and optimization |
| TensorRT Optimization | Model quantization (FP16/INT8) |
| Hardware Testing | Real-time inference benchmarking |

**Focus Areas:**
- NVIDIA Jetson Nano 4GB configuration
- TensorRT acceleration
- Power consumption optimization
- FPS benchmarking

---

### Muhammad Ashar Javid
**Role:** Simulation Engineer

| Responsibility | Description |
|----------------|-------------|
| Model Training | Train dehazing-detection models |
| Benchmarking | Evaluate model accuracy (mAP) |
| Dataset Preparation | Prepare foggy/hazy datasets |
| Performance Analysis | Compare model architectures |

**Focus Areas:**
- YOLOv5/YOLOv7/YOLOX implementations
- Dehazing network integration
- Training pipeline optimization
- Accuracy metrics evaluation

---

### Hamza Irshad Bhatti
**Role:** Simulation Engineer

| Responsibility | Description |
|----------------|-------------|
| Dataset Management | Collect and preprocess datasets |
| Model Evaluation | Test models on various conditions |
| Fog Simulation | Create synthetic foggy images |
| Results Analysis | Document performance metrics |

**Focus Areas:**
- RTTS and RESIDE dataset handling
- Synthetic fog generation
- Cross-dataset validation
- Statistical analysis

---

### Ammar
**Role:** Documentation Specialist

| Responsibility | Description |
|----------------|-------------|
| Literature Review | Research and document related work |
| IEEE Reports | Prepare formal reports and papers |
| Repository Docs | Maintain README and guides |
| Reference Management | Organize and verify citations |

**Focus Areas:**
- Literature review (2019-2025)
- IEEE formatting and standards
- Technical writing
- Citation verification

---

## 👨‍🏫 Oversight Members

### Ms. Tehniyat Siddiqui
**Role:** Lab Engineer

| Responsibility | Description |
|----------------|-------------|
| Technical Guidance | Provide lab and hardware support |
| Progress Monitoring | Review project board weekly |
| Resource Access | Facilitate lab equipment access |

**Access Level:** Read & Comment on Project Board

---

### Dr. Tauseef ur Rehman
**Role:** Instructor / Academic Supervisor

| Responsibility | Description |
|----------------|-------------|
| Academic Oversight | Guide research direction |
| Milestone Reviews | Evaluate progress at checkpoints |
| Quality Assurance | Ensure academic standards |

**Access Level:** Read & Comment on Project Board

---

## 📊 Role-Based Task Assignment

### Task Categories by Role

| Task Type | Primary Role | Secondary Role |
|-----------|--------------|----------------|
| Model Training | Simulation | Embedded |
| Dataset Preparation | Simulation | Documentation |
| Literature Review | Documentation | Simulation |
| Jetson Deployment | Embedded | Simulation |
| Report Writing | Documentation | All |
| Performance Testing | Embedded | Simulation |
| Code Development | Simulation | Embedded |

---

## 📅 Responsibilities Matrix (RACI)

| Task | Wassi (Lead) | Ashar (Sim) | Hamza (Sim) | Ammar (Doc) |
|------|--------------|-------------|-------------|-------------|
| Project Planning | **R/A** | C | C | I |
| Literature Review | A | C | C | **R** |
| Dataset Preparation | I | **R** | **R** | I |
| Model Training | C | **R** | **R** | I |
| Jetson Deployment | **R** | C | I | I |
| Documentation | A | C | C | **R** |
| Board Updates | **R/A** | R | R | R |

**Legend:** R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## 🔄 Communication Protocol

### Weekly Sync
- Update project board status
- Report blockers and progress
- Plan upcoming week's tasks

### Milestone Reviews
- Present completed work to oversight
- Get feedback and guidance
- Document lessons learned

### Issue Communication
- Use GitHub Issues for task tracking
- Tag relevant team members
- Update status in project board

---

## 📞 Contact Information

| Member | Role | GitHub |
|--------|------|--------|
| Wassi Haider Kabir | Team Lead | @wassihaiderkabir |
| Muhammad Ashar Javid | Simulation | *Update with GitHub username* |
| Hamza Irshad Bhatti | Simulation | *Update with GitHub username* |
| Ammar | Documentation | *Update with GitHub username* |

> **Note:** Team members should update this table with their GitHub usernames after creating accounts.

---

## 🎯 Project Goals

1. **Phase 1:** Complete literature review and feasibility study ✅
2. **Phase 2:** Implement dehazing-detection pipeline
3. **Phase 3:** Deploy and benchmark on Jetson Nano
4. **Phase 4:** Document results and publish findings

---

*Last Updated: December 2025*
