# 🌍 ResilientAI

**A Community-Centered Early Warning and Decision System for Climate Disasters in the Lake Chad Basin**

ResilientAI is an open-source project that uses machine learning, geospatial data, and local languages to predict floods, send early alerts, and support real-time community response in climate-vulnerable regions like Maiduguri, Nigeria.

## 🚨 Problem

In 2024, floods from Lake Chad devastated parts of Borno State, displacing over 100,000 people. There was no local early warning system, and communities were left without guidance.

## 💡 Solution

ResilientAI leverages:
- 🌧️ Satellite rainfall data (e.g., GPM, Sentinel)
- 🤖 Machine learning (LSTM, CNN) for flood prediction
- 🌐 FastAPI backend + React dashboard
- 📲 Multilingual alerts via SMS/USSD (Hausa, Kanuri)
- 🧭 Real-time flood maps and risk zones

## 📦 Features

- 📡 Predicts floods 3–5 days ahead
- 🗺️ Maps flood risk zones
- 🔔 Sends alerts to mobile phones in local languages
- 🧑🏾‍🤝‍🧑🏽 Co-designed with local youth and emergency responders

## 🧰 Tech Stack

| Layer         | Tools Used                             |
|---------------|----------------------------------------|
| Data          | Google Earth Engine, MODIS, GPM        |
| ML/AI         | Python, TensorFlow, scikit-learn       |
| Backend       | FastAPI, PostgreSQL (PostGIS)          |
| Frontend      | React, Leaflet.js                      |
| Alerts        | Twilio / Africa’s Talking              |
| Hosting       | Render, Railway, or Fly.io             |

## 🏁 Getting Started

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/resilientai.git
cd resilientai
```

2. **Set up environment**
```bash
pip install -r requirements.txt
```

3. **Run API locally**
```bash
uvicorn main_api:app --reload
```

4. **Train your first model**
```bash
python train_model.py
```

5. **Test prediction**
```bash
curl -X POST http://localhost:8000/predict -H "Content-Type: application/json" -d '{"rainfall_sequence":[4.2, 3.8, 5.1, 6.0, 5.6]}'
```

## 🧪 Folder Structure

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

## 🌱 Future Plans

- 🌾 Add drought, displacement, and cholera modules
- 🗺️ Expand to Chad, Niger, and Cameroon
- 🛠️ Create offline dashboard for rural use
- 🔓 Launch open-source toolkit and API

## 🤝 Collaborators & Credits

- **Lead Developer**: Abba Imam
- **Partners**: UniMaid, NEMA, Red Cross, Africa AI Lab
- **Supporters**: WFSIE, Google.org, UNDP (pending)

## 📬 Contact

Have feedback, want to contribute or fund?  
📧 abbaimam@example.com | 🌍 github.com/yourusername

## 🧡 License

This project is licensed under the MIT License – see the `LICENSE` file for details.