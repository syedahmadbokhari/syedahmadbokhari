# Syed Muhammad Ahmad Bokhari — AI & Data Professional

**First Class Honours** · BSc Applied Artificial Intelligence (University of Bradford, 2026)  
📍 Bradford, UK · UK Resident (Post-Study Work Visa) · Open to relocate

---

## 👋 About Me

Recent AI/Applied AI graduate specialising in **Data Engineering**, **ML Systems**, and **Environmental AI**.

I build production-grade data pipelines, computer vision systems, and AI-powered analytics tools. My final year project was deployed with the University of Bradford as a live CCTV monitoring system for real-time illegal dumping detection.

Currently seeking **Data Analyst**, **Data Engineer**, or **ML Engineering** roles in the UK (Bradford area, willing to relocate).

---

## 🛠️ Tech Stack

**Languages:** Python, SQL (Advanced), TypeScript  
**Data Engineering:** Apache Airflow, dbt, DuckDB, PostgreSQL, AWS S3  
**ML/Analytics:** XGBoost, scikit-learn, TensorFlow, PyTorch, Pandas, SHAP  
**Computer Vision:** YOLOv8, MobileNetV3, ByteTrack, OpenCV  
**Backend & Deployment:** FastAPI, Flask, SQLAlchemy, Redis, Streamlit, Docker, GitHub Actions  
**Databases:** PostgreSQL, DuckDB, SQLite, pgvector  
**Certifications:** dbt Associate, dbt Core

---

## ⭐ Flagship Project

### [AI for Environmental Monitoring & Urban Planning](https://github.com/syedahmadbokhari/AI-for-Environmental-Monitoring-and-Urban-Planning)

> **BSc Applied AI Final Year Project — Deployed with University of Bradford**

A real-time AI system that transforms passive CCTV infrastructure into an intelligent environmental monitoring tool. It automatically detects illegal littering and dumping events, tracks objects across frames, and alerts authorities — all without facial recognition (GDPR compliant, ALTAI ethical AI framework).

#### 🔧 System Pipeline
```
CCTV Feed → Motion Detection → ByteTrack Tracking → MobileNetV3 Classifier → Alert → Dashboard
```

#### ✨ Key Features
- 🎯 **MobileNetV3** waste classifier (PyTorch) — lightweight, optimised for real-time edge inference on CCTV hardware
- 🔍 **ByteTrack** multi-object tracking with Kalman filtering for persistent object IDs across frames
- 🚨 **Stationary object logic** — flags objects that remain in place beyond a time threshold as dumping events
- 📡 **Flask REST API** with MJPEG video streaming and live Server-Sent Events (SSE) for real-time alerts
- 🗺️ **Streamlit dashboard** with GIS map visualisation, runtime event logging, and accountability tracking
- ✅ **GDPR compliant** — no facial recognition, full data minimisation, transparent audit trail
- 🤝 **ALTAI ethical AI framework** applied throughout design and evaluation

#### 📁 Project Structure
```
core/         ← Detection pipeline & classifier modules
dashboard/    ← Flask backend + Streamlit frontend
models/       ← Trained MobileNetV3 checkpoints
training/     ← Model training notebooks
data/         ← Raw & processed datasets
docs/         ← Design & evaluation reports
archive/      ← Historical prototypes (v0–v7)
```

#### 🛠️ Full Tech Stack
| Layer | Technology |
|---|---|
| Language | Python |
| Computer Vision | OpenCV, YOLOv8 |
| Deep Learning | PyTorch, MobileNetV3, torchvision |
| Object Tracking | ByteTrack (Kalman filtering) |
| Backend | Flask (REST API, MJPEG, SSE) |
| Dashboard | Streamlit + GIS visualisation |
| Deployment | University of Bradford (live CCTV) |

---

## 📊 Other Notable Projects

### [UK Crime Data Pipeline](https://github.com/syedahmadbokhari/UK-Crime-Data-Pipeline)
End-to-end data platform ingesting 21k+ monthly UK police records  
S3 → dbt → Airflow → FastAPI → Streamlit · JWT auth · Redis caching · RAG with pgvector · 20+ tests · CI/CD

### [Breast Cancer Survival Model](https://github.com/syedahmadbokhari/breast-cancer-analysis)
Production ML pipeline with SHAP explainability, model calibration, and survival analysis  
scikit-learn · XGBoost · Pandas · Streamlit

### [Retail Data Platform](https://github.com/syedahmadbokhari/sql-data-analysis)
Cloud-native analytics with dimensional modelling, recommendation engine, and 51 unit tests  
dbt · DuckDB · AWS S3 · Streamlit · pytest · moto

### [CLIP: Zero-Shot vs Linear Probe](https://github.com/syedahmadbokhari/clip-zero-shot-vs-linear-prob)
Benchmarking zero-shot CLIP against linear probe fine-tuning across vision datasets  
PyTorch · OpenAI CLIP · scikit-learn

### [Reinforcement Learning Game Agent](https://github.com/syedahmadbokhari/Reinforcement-Learning-Game-Agent)
Policy gradient and deep Q-network implementations  
PyTorch · OpenAI Gym

---

## 🏆 Engineering Highlights

- Real-time computer vision pipeline deployed on live University of Bradford CCTV infrastructure
- 8-task Airflow DAG with incremental loading, data validation, and alerting
- Production REST API: async SQLAlchemy, cursor pagination, rate limiting, Redis caching
- LLM-grounded report generation with semantic search via pgvector (Gemini AI)
- dbt marts with schema tests, lineage tracking, and documentation
- Multi-stage Docker builds with CI/CD via GitHub Actions
- Geospatial analytics and crime hotspot mapping


---

## 📧 Let's Connect

- **Email:** ahmadbokhari323@gmail.com
- **LinkedIn:** [linkedin.com/in/syedahmadbokhari](https://www.linkedin.com/in/syedahmadbokhari)
- **Location:** Bradford, UK · UK Resident (Post-Study Work Visa)
