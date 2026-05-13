# ♻️ ReStyleAI – AI-Powered Circular Fashion Platform

[![Python](https://img.shields.io/badge/Python-3.10+-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![AI Hackathon](https://img.shields.io/badge/AI%20Hackathon-2025%20Final%20Project-blueviolet?style=for-the-badge)]
[![GitHub stars](https://img.shields.io/github/stars/JoinDeeHub/ReStyleAI?style=for-the-badge)](https://github.com/JoinDeeHub/ReStyleAI/stargazers)

> **ReStyleAI** is an AI-powered platform that promotes **circular fashion** by helping users match their existing clothes with sustainable alternatives — reducing textile waste, supporting ethical production, and raising environmental awareness.

---

## 🌍 Problem Statement

> *"Every second, one garbage truck full of clothes is burned or buried."*

The fashion industry is one of the largest contributors to global pollution. ReStyleAI empowers users to make sustainable choices by intelligently recommending matching items based on uploaded clothing, material type, and weight — using AI/ML-powered matching and impact calculations.

---

## 🖼️ Demo

<img width="954" alt="ReStyleAI UI - Upload Screen" src="https://github.com/user-attachments/assets/f73acf96-f486-4db6-8350-ee2fcd5c1200" />
<img width="949" alt="ReStyleAI UI - Results Screen" src="https://github.com/user-attachments/assets/d7d1ab86-e195-43b6-8f4f-2d405b7a4581" />

---

## 🚀 Features

| Feature | Description |
|---|---|
| 📸 Upload Clothing | Drag & drop interface for garment images (JPG, PNG, JPEG up to 200MB) |
| 🧵 Material & Weight | Select fabric type and weight for accurate impact analysis |
| ♻️ AI Matching Engine | Top sustainable alternatives via image similarity + eco-impact scoring |
| 🌱 Impact Calculator | CO₂ saved, water saved, and carbon footprint breakdown |
| 💡 Circularity Score | Evaluates how eco-friendly your clothing choices are |
| 📊 Impact Equivalents | Real-world analogies to make sustainability tangible |

---

## 🧠 How It Works

```
User uploads image + selects material & weight
        │
        ▼
  Image Processing (PIL + Base64)
        │
        ▼
  AI Matching Engine queries fashion database
        │
        ▼
  Returns: sustainable matches + CO₂ saved + water saved + circularity score
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Streamlit + Custom CSS |
| Image Processing | PIL, Base64 Encoding |
| Backend | Python (FastAPI / Flask) |
| Matching Engine | Image URL + Material + Weight matching |
| Impact Engine | Custom logic based on material database |
| Containerization | Docker + Docker Compose |
| Cloud Deployment | GCP (deploy script included) |

---

## 📁 Project Structure

```
ReStyleAI/
├── backend/
│   ├── __init__.py
│   ├── main.py              # API entry point
│   ├── ai_engine.py         # Core AI matching logic
│   └── firebase_service.py  # Database integration
├── frontend/
│   ├── __init__.py
│   ├── app.py               # Streamlit UI
│   └── utils.py             # Utility functions
├── scripts/
│   ├── __init__.py
│   └── deploy_gcp.sh        # GCP deployment script
├── .env                     # Environment variables (not committed)
├── docker-compose.yml
├── Dockerfile
├── requirements.txt
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.10+
- Docker (optional)
- Git

### Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/JoinDeeHub/ReStyleAI.git
cd ReStyleAI

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up environment variables
cp .env.example .env
# Edit .env with your API keys

# 5. Run the app
streamlit run frontend/app.py
```

### Docker Setup

```bash
docker-compose up --build
```

App will be available at `http://localhost:8501`

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit changes: `git commit -m 'feat: add your feature'`
4. Push to branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🏆 Acknowledgements

- **Hope AI** – AI Hackathon 2025 organizers
- **Unsplash** – Sample fashion item images
- **Streamlit** – Rapid prototyping framework

---

## 📬 Contact

**Deepika Narendran** | Lead AI/DevOps Engineer

[![Email](https://img.shields.io/badge/Email-deepika2.ytb%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:deepika2.ytb@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deepika--narendran-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepika-narendran/)
[![GitHub](https://img.shields.io/badge/GitHub-JoinDeeHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/JoinDeeHub)

---

<p align="center">Made with 💚 for a sustainable future | © 2025 Deepika Narendran</p>
