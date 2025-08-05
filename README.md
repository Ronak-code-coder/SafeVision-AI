
# 🚧 SafeVision AI – Real-Time Workplace Safety Monitoring System

SafeVision AI is a real-time, AI-powered workplace monitoring system that uses computer vision and NLP to detect safety violations (e.g., missing helmets, unsafe postures, misuse of equipment), generate alerts, and produce automated compliance reports.

## 🎯 Problem Statement

Manual safety inspections are often reactive and error-prone. In industrial settings, timely detection of safety violations can prevent injuries and fatalities. SafeVision AI brings proactive safety supervision to industrial environments.

## 🧠 Hugging Face Tasks Used

- **Object Detection**: Detect PPE gear, machinery, and personnel.
- **Image Segmentation**: Analyze postures and equipment zones.
- **Video Classification**: Monitor behavior for unsafe activities.
- **Image Classification**: Categorize safety compliance visually.
- **Text Generation**: Create automatic incident summaries.
- **Text Summarization**: Generate daily or weekly safety logs.
- **Question Answering**: Enable natural language safety queries.

## 🛠️ Tech Stack

### Frontend
- React.js / Next.js
- Tailwind CSS
- WebSocket for real-time alerts

### Backend
- FastAPI or Node.js (Express)
- OpenCV + Hugging Face Transformers
- PostgreSQL / MongoDB
- Redis (caching)

### DevOps & Infra
- Docker
- AWS EC2 (GPU), S3
- GitHub Actions for CI/CD

## 🗃️ Data Sources

- CCTV safety datasets (Kaggle / Open Datasets)
- Real-world workplace video/audio simulation

## 🔥 Features

- Real-time detection of safety violations
- Email/SMS alert system
- Compliance dashboard
- Incident heatmaps
- Daily/weekly auto-generated reports (PDF)
- Natural language safety query bot

## 🚀 How to Run

```bash
git clone https://github.com/your-username/SafeVision-AI.git
cd SafeVision-AI

# (Set up virtual env)
pip install -r requirements.txt

# Run backend
uvicorn app.main:app --reload

# Run frontend (in separate terminal)
cd frontend
npm install
npm run dev
```

## 📄 Project Proposal

[📥 Download the full proposal here](./SafeVisionAI_Project_Proposal.pdf)

## 📈 Future Enhancements

- Voice-based query interface (ASR + QA)
- Integration with wearable safety devices
- 3D detection using Text-to-3D or Image-to-3D
- Mobile version for supervisors

## 👨‍💻 Author

**Ronak Malpani**  
AI/ML | Computer Vision | Full Stack Engineer  
[LinkedIn](https://linkedin.com) • [GitHub](https://github.com)

---

> ✨ This project is a powerful, end-to-end example of applied AI and scalable system design for real-world use.
