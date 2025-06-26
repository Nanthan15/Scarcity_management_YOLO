# Scarcity Management YOLO 🧠📉📦

Scarcity Management YOLO is an AI system using YOLO for real-time object detection (water leaks) and LSTM for forecasting water shortages. It monitors current water levels and predicts future scarcity using computer vision and time-series analysis..

---

## 💡 Features

- 🔍 **YOLOv5** object detection to monitor shelves/counters for stock presence.
- 🔄 **LSTM** forecasting for future scarcity based on time-series patterns.
- 🌐 **Flask API** to serve ML predictions.
- 🛠️ **Django** for web dashboard and management.
- 📊 Data visualization and alert systems.

---

## 🧰 Tech Stack

| Layer         | Technology      |
|---------------|-----------------|
| Object Detection | YOLOv5 (PyTorch) |
| Forecasting    | LSTM (Keras / PyTorch) |
| ML Serving     | Flask (REST API) |
| Web Dashboard  | Django |
| Frontend       | HTML, CSS, JS (optional: React/Chart.js) |
| Database       | SQLite/PostgreSQL |

---

## 🛠 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Scarcity_Management_YOLO.git
cd Scarcity_Management_YOLO
```

2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Run Django backend
```bash
cd backend
python manage.py migrate
python manage.py runserver
```

