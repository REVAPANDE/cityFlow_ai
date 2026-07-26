# 🚦 TraffiIQ – AI Traffic Intelligence Platform

> **AI-Powered Smart City Traffic Forecasting & Analytics Dashboard**

<p align="center">

<a href="https://city-flow-ai-gv91-livid.vercel.app/" target="_blank">
<img src="https://img.shields.io/badge/🌐%20Live%20Demo-Open%20Application-6D28D9?style=for-the-badge" />
</a>

<a href="https://github.com/REVAPANDE/cityFlow_ai" target="_blank">
<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" />
</a>

<img src="https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react"/>
<img src="https://img.shields.io/badge/TypeScript-5.x-blue?style=for-the-badge&logo=typescript"/>
<img src="https://img.shields.io/badge/TailwindCSS-4.x-38B2AC?style=for-the-badge&logo=tailwindcss"/>
<img src="https://img.shields.io/badge/Vite-Latest-646CFF?style=for-the-badge&logo=vite"/>

</p>

---

## 🌐 Live Demo

### 👉 https://city-flow-ai-gv91-livid.vercel.app/

---

## 📂 GitHub Repository

### 👉 https://github.com/REVAPANDE/cityFlow_ai

---

# 📖 Overview

TraffiIQ is an AI-powered traffic forecasting and analytics platform designed to demonstrate how Machine Learning can improve urban traffic management through predictive analytics.

Instead of reacting after congestion occurs, the platform forecasts future traffic conditions, compares multiple machine learning models, visualizes traffic trends, and provides intelligent recommendations for traffic authorities.

The current implementation is a **frontend research prototype** using realistic simulated machine learning outputs. Its modular architecture allows seamless integration with a FastAPI backend and real trained ML models in future development.

---

# 🎯 Problem Statement

Rapid urbanization has significantly increased traffic congestion in metropolitan cities, resulting in:

- Longer travel times
- Fuel wastage
- Increased carbon emissions
- Delayed emergency response
- Inefficient traffic signal management
- Reduced road network efficiency

Traditional traffic management systems are primarily reactive, responding only after congestion has already developed.

TraffiIQ addresses this challenge by leveraging Machine Learning to forecast short-term traffic conditions, enabling traffic authorities to make proactive decisions such as adaptive signal control, route optimization, and congestion mitigation before traffic reaches critical levels.

---

# ✨ Features

- 📊 Interactive Executive Dashboard
- 📈 Traffic Analytics & Visualizations
- 🤖 Machine Learning Model Comparison
- 🚦 Live Traffic Prediction Simulator
- 📂 Dataset Explorer
- ⚙️ Feature Engineering Visualization
- 💡 Smart Traffic Recommendations
- 📑 Reports Dashboard
- ⚙️ System Settings
- 📱 Fully Responsive Design

---

# 🏗️ System Workflow

```text
Historical Traffic Dataset
            │
            ▼
Data Cleaning
            │
            ▼
Feature Engineering
            │
            ▼
Train/Test Split
            │
            ▼
Model Training
(Random Forest • XGBoost • SVR)
            │
            ▼
Cross Validation
            │
            ▼
Model Evaluation
            │
            ▼
Best Model Selection
            │
            ▼
Traffic Prediction
            │
            ▼
Analytics Dashboard
            │
            ▼
Smart Recommendations
```

---

# 🧠 Machine Learning Pipeline

The system follows a complete supervised Machine Learning workflow.

### 1. Data Collection

Historical traffic observations are collected.

### 2. Data Preprocessing

- Missing value handling
- Data cleaning
- Normalization

### 3. Feature Engineering

The following features are engineered:

- Hour
- Day of Week
- Holiday
- Temperature
- Rainfall
- Cloud Cover
- Lag_1
- Lag_3
- Lag_6
- Rolling Mean
- Rolling Standard Deviation
- Peak Hour
- Weekend
- Weather Index

### 4. Train-Test Split

80% Training

20% Testing

### 5. Model Training

Three regression algorithms are trained.

- Random Forest
- XGBoost
- Support Vector Regression

### 6. Model Evaluation

Models are evaluated using

- MAE
- RMSE
- R² Score
- Training Time
- Inference Time

### 7. Model Selection

The best-performing model is deployed.

---

# 🤖 Machine Learning Models

## 🌳 Random Forest

Random Forest is an ensemble learning algorithm that constructs multiple decision trees using different subsets of the training dataset.

The final prediction is obtained by averaging the predictions from all trees.

### Advantages

- Robust against noise
- Handles nonlinear relationships
- Less prone to overfitting
- Provides feature importance

---

## 🚀 XGBoost (Selected Model)

XGBoost is a gradient boosting algorithm that sequentially builds decision trees, where each tree attempts to correct the prediction errors made by previous trees.

It offers high predictive performance while maintaining computational efficiency.

### Advantages

- High prediction accuracy
- Fast inference
- Built-in regularization
- Excellent performance on structured datasets

---

## 📉 Support Vector Regression (SVR)

Support Vector Regression predicts continuous values by finding an optimal regression function while minimizing prediction error.

### Advantages

- Suitable for nonlinear regression
- Strong theoretical foundation
- Effective for smaller datasets

---

# 📊 Model Comparison

| Metric | Random Forest | XGBoost | SVR |
|---------|--------------:|---------:|----:|
| Validation Score | 0.91 | **0.95** | 0.88 |
| MAE | 3.8 | **2.9** | 4.5 |
| RMSE | 5.2 | **4.1** | 6.0 |
| Training Time | 18 sec | 24 sec | 41 sec |
| Inference Time | 18 ms | **12 ms** | 27 ms |

---

# 🏆 Why XGBoost?

XGBoost was selected because it demonstrated the best overall performance across all evaluation metrics.

Reasons include:

- Highest prediction accuracy
- Highest R² Score
- Lowest MAE
- Lowest RMSE
- Fastest inference
- Better generalization
- Lower computational overhead

---

# 📂 Dataset

The current prototype uses a realistic simulated urban traffic dataset.

### Dataset Statistics

| Property | Value |
|-----------|------|
| Samples | 48,204 |
| Features | 15 |
| Target | Traffic Volume |
| Frequency | Hourly |
| Train/Test Split | 80/20 |
| Missing Values | 0.4% |

---

# 📊 Dashboard Modules

## 🏠 Dashboard

Provides an overview of

- Prediction Accuracy
- Best Performing Model
- Historical Records
- Average Congestion
- Average Speed
- Predictions Today
- System Health

---

## 📈 Traffic Analytics

Visualizes

- Actual vs Predicted Traffic
- Weekly Traffic Trends
- Monthly Traffic Trends
- Congestion Heatmap
- Corridor Analysis
- Feature Importance
- Congestion Distribution

---

## 🤖 ML Models

Displays

- Training Summary
- Hyperparameters
- Validation Scores
- Cross Validation
- Model Registry

---

## 📊 Model Comparison

Compares

- Random Forest
- XGBoost
- SVR

using

- MAE
- RMSE
- R² Score
- Training Time
- Inference Time
- Radar Chart

---

## 📂 Dataset Explorer

Displays

- Dataset Statistics
- Correlation Matrix
- Feature Distribution
- Sample Dataset
- Train/Test Information

---

## ⚙️ Feature Engineering

Visualizes

- Engineered Features
- Feature Importance
- Feature Descriptions

---

## 🚦 Live Prediction

Allows users to simulate traffic conditions by entering

- Hour
- Temperature
- Rainfall
- Holiday
- Road Type
- Prediction Horizon

Returns

- Predicted Traffic Volume
- Congestion Level
- Average Speed
- Estimated Delay
- Prediction Confidence
- Operational Recommendation

---

## 💡 Smart Recommendations

Generates AI-powered recommendations including

- Increase Green Signal Timing
- Suggest Alternate Route
- Adaptive Signal Timing
- Emergency Vehicle Priority
- Congestion Alerts

---

# 🛠️ Tech Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Recharts
- Framer Motion
- Lucide React

## Planned Backend

- FastAPI
- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy

---

# 📁 Project Structure

```
cityFlow_ai
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── hooks/
│   ├── layouts/
│   ├── lib/
│   ├── routes/
│   ├── types/
│   └── utils/
│
├── package.json
├── vite.config.ts
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/REVAPANDE/cityFlow_ai.git
```

## Navigate

```bash
cd cityFlow_ai
```

## Install Dependencies

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

## Production Build

```bash
npm run build
```

---

# 🚀 Future Scope

- Integration with real traffic datasets
- FastAPI backend deployment
- Real-time ML predictions
- IoT sensor integration
- Computer Vision vehicle counting
- Google Maps Traffic API integration
- Adaptive traffic signal optimization
- Multi-city deployment
- Cloud-native architecture

---

# 📸 Screenshots
<img width="1899" height="921" alt="image" src="https://github.com/user-attachments/assets/71b548bd-78b6-4a65-b9d2-d5b12857b0b6" />
<img width="1898" height="904" alt="image" src="https://github.com/user-attachments/assets/9b06558f-90a4-4650-883b-f34be66ebf43" />
<img width="1896" height="906" alt="image" src="https://github.com/user-attachments/assets/48131135-4185-4fa5-a435-bde5e6cb82ce" />
<img width="1897" height="886" alt="image" src="https://github.com/user-attachments/assets/fd1dd18f-398a-4fea-8b67-653ae2b36cdd" />
<img width="1895" height="965" alt="image" src="https://github.com/user-attachments/assets/cb635b30-1ab9-42c7-b6db-47d68d787b25" />
<img width="1897" height="910" alt="image" src="https://github.com/user-attachments/assets/55c59dbb-fa3d-4a7a-a063-2ea25bffbd62" />
<img width="1902" height="896" alt="image" src="https://github.com/user-attachments/assets/80c5f63f-09fe-4710-8f1a-10289639a4df" />
<img width="1903" height="951" alt="image" src="https://github.com/user-attachments/assets/99e1d85a-c634-435d-8244-3566db1aeea8" />
<img width="1895" height="911" alt="image" src="https://github.com/user-attachments/assets/d43d312e-39dc-4702-82f4-5548ff0e9a4b" />
<img width="1893" height="896" alt="image" src="https://github.com/user-attachments/assets/a33be7b2-0ea0-42fd-9954-65e5f48760c7" />
<img width="1882" height="889" alt="image" src="https://github.com/user-attachments/assets/eca85dd0-3726-4984-b2a8-5cc5c149b94f" />


# ⚠️ Disclaimer

This project is a research prototype developed to demonstrate the architecture and workflow of an AI-powered traffic forecasting system.

The current implementation uses **realistic simulated datasets, traffic observations, predictions, and machine learning evaluation metrics** to showcase the complete end-to-end workflow. The modular architecture enables the existing mock API layer to be seamlessly replaced with a FastAPI backend serving trained machine learning models and real-time traffic data in future development.

---

# 🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you found this project useful, don't forget to star the repository!

**GitHub:** https://github.com/REVAPANDE/cityFlow_ai

**Live Demo:** https://city-flow-ai-gv91-livid.vercel.app/
