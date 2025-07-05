# 🌍 ResilientAI

![MIT License](https://img.shields.io/badge/license-MIT-green.svg)
![Project Status](https://img.shields.io/badge/status-in%20progress-yellow)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Issues](https://img.shields.io/github/issues/abbaimam3/resilientai)
![Last Commit](https://img.shields.io/github/last-commit/abbaimam3/resilientai)

**A Community-Centered Early Warning and Decision System for Climate Disasters in the Lake Chad Basin**

ResilientAI is an open-source project that uses machine learning, geospatial data, and local languages to predict floods, send early alerts, and support real-time community response in climate-vulnerable regions like Maiduguri, Nigeria.

---

## 🚨 Problem

In 2024, floods from Lake Chad devastated parts of Borno State, displacing over 100,000 people. There was no local early warning system, and communities were left without guidance.

## 💡 Solution

ResilientAI leverages:
- 🌧️ Satellite rainfall data (e.g., GPM, Sentinel)
- 🤖 Machine learning (LSTM, CNN) for flood prediction
- 🌐 FastAPI backend + React dashboard
- 📲 Multilingual alerts via SMS/USSD (Hausa, Kanuri)
- 🧭 Real-time flood maps and risk zones

---

## 🧰 Tech Stack

| Layer         | Tools Used                             |
|---------------|----------------------------------------|
| Data          | Google Earth Engine, MODIS, GPM        |
| ML/AI         | Python, TensorFlow, scikit-learn       |
| Backend       | FastAPI, PostgreSQL (PostGIS)          |
| Frontend      | React, Leaflet.js                      |
| Alerts        | Twilio / Africa’s Talking              |
| Hosting       | Render, Railway, or Fly.io             |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/abbaimam3/resilientai.git
cd resilientai

# Install dependencies
pip install -r requirements.txt

# Train a model
python train_model.py

# Start the API
uvicorn main_api:app --reload
```

---

## 📁 Project Structure

```bash
resilientai/
├── data_download.py        # Earth Engine data script
├── train_model.py          # ML model training
├── main_api.py             # FastAPI backend
├── models/                 # Trained model files
├── data/                   # Raw and processed datasets
├── frontend/               # React dashboard (coming soon)
├── requirements.txt
└── README.md
```

---

## 🌱 Future Roadmap

- Expand to cover Lake Chad Basin (Niger, Cameroon, Chad)
- Add drought and cholera risk modules
- Deploy offline dashboards for rural responders
- Local co-design workshops and training for youth volunteers

---

## 🤝 Collaborators & Credits

- **Lead Developer**: Abba Imam
- **Partners**: UniMaid, NEMA, Red Cross, Africa AI Lab
- **Supporters**: WFSIE, Google.org, UNDP (pending)

---

## 📬 Contact

📧 abbaimam3@gmail.com  
🌐 [https://github.com/abbaimam3](https://github.com/abbaimam3)

---

## 🧡 License

This project is licensed under the MIT License – see the `LICENSE` file for details.
