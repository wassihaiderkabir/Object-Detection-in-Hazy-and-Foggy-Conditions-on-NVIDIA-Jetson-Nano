# 🌫️ Object Detection in Hazy and Foggy Conditions on NVIDIA Jetson Nano

## 📘 Project Overview
This repository contains the **Phase 1: Literature Review & Feasibility** work for the research project conducted at the **School of Electrical Engineering and Computer Science (SEECS), National University of Sciences and Technology (NUST), Islamabad, Pakistan**.  
The study focuses on enhancing **object detection under haze and fog** using **lightweight deep-learning models** optimized for deployment on **NVIDIA Jetson Nano (4 GB)** embedded hardware.

The project explores how modern dehazing-aware detection architectures—such as **AOD-YOLOv5s**, **TSMD-Net**, **YOLOv5s-Fog**, and **IDOD-YOLOv7**—achieve real-time inference and high detection accuracy despite limited compute resources.

---

## 👥 Authors
- **Wassi Haider Kabir**  
- **Muhammad Ashar Javid**  
- **Hamza Irshad Bhatti**  
- **Ammar**  
School of Electrical Engineering and Computer Science (SEECS)  
National University of Sciences and Technology (NUST), Islamabad, Pakistan  

---

## 🧠 Research Summary
The literature review consolidates research from **2019–2025** on haze/fog detection, highlighting:
- **AOD-YOLOv5s (Li et al., 2024)** — Hybrid dehazing and YOLOv5 integration with 76.8 % mAP, 42 % parameter reduction.  
- **TSMD-Net (Raju & Srinivas, 2024)** — Dual-attention dehazing network validated on Jetson Nano (16.3 M params, 1.9 s per frame).  
- **YOLOv5s-Fog (Meng et al., 2023)** — Swin-Transformer attention improving mAP + 5.4 %.  
- **IDOD-YOLOv7 (Qiu et al., 2023)** — SAIP-based joint enhancement and detection network achieving +7.9 % mAP and 71 FPS.

All reviewed models maintain < 70 GFLOPs and < 20 M parameters, confirming feasibility for **Jetson Nano** deployment with FP16/INT8 quantization.

---

## ⚙️ Repository Structure
📁 /docs
├── Literature_Review_Phase1.pdf # Final IEEE-formatted review
├── Feasibility_Summary.txt # Jetson Nano deployment notes
└── references/ # Verified cited papers (PDFs/links)

📁 /src
└── (Phase 2 implementation – to be added)

📁 /results
└── (future inference benchmarks)


---

## 🔍 Key Highlights
- ✅ Comprehensive IEEE-formatted **literature review** (2019–2025)  
- 🧠 Focus on **joint dehazing and object detection** under adverse weather  
- ⚙️ Verified feasibility on **Jetson Nano 4 GB**  
- 📚 Repository includes **verified papers and sources**  
- 🚀 Ready foundation for **Phase 2 implementation & benchmarking**

---

## 📚 Verified References
| No. | Paper | Source |
|----:|-------|--------|
| [1] | **Qiu et al. (2023)** – *IDOD-YOLOv7: Image-Dehazing YOLOv7 for Object Detection in Low-Light Foggy Traffic Environments* | *Sensors 23 (13): 1347* |
| [2] | **Li et al. (2024)** – *Object Detection in Hazy Environments Based on an All-in-One Dehazing Network and YOLOv5* | *Electronics 13 (1862)* |
| [3] | **Raju & Srinivas (2024)** – *TSMD-Net: Two-Stage Mixed Dehazing Network* | *Digital Signal Processing 155 (104710)* |
| [4] | **Meng et al. (2023)** – *YOLOv5s-Fog: An Improved Model for Object Detection in Foggy Weather* | *Sensors 23 (11): 5321* |

---

## 💻 Hardware Feasibility (Jetson Nano 4 GB)
| Parameter | Specification |
|------------|----------------|
| GPU | 128-core Maxwell GPU |
| RAM | 4 GB LPDDR4 |
| Target Models | YOLOv5s-Fog, IDOD-YOLOv7 |
| Precision | FP16 / INT8 (TensorRT optimized) |
| Target FPS | 10–15 FPS |
| Power | 5 V ⎓ 4 A |

---

## 🧾 Mandatory Declaration
> ChatGPT (Deep Research Mode) was used to search, verify, and summarize peer-reviewed research papers and generate the narrative literature review.  
> All sources were opened and confirmed by the team.  
> Verified papers are available in the `/docs/references/` folder.

---

## 🧩 Future Work (Phase 2)
- Implement selected dehazing–detection pipelines (IDOD-YOLOv7 / AOD-YOLOv5).  
- Quantize and deploy on **Jetson Nano 4 GB** using TensorRT.  
- Record FPS, mAP, and power consumption under fog simulation.  
- Publish comparative results in `/results/`.

