# Real-Time-Behavioral-Anomaly-Detection-and-Root-Cause-AI

🏥 Clinical Anomaly Detection & Explainable Risk Monitoring

📌 Overview

This project builds an end-to-end system for real-time patient monitoring, combining:

Time-series anomaly detection
Root cause analysis (RCA)
LLM-generated clinical insights

🚨 Problem

Clinical monitoring systems generate alerts but lack interpretability and context, leading to alarm fatigue and delayed interventions.

💡 Solution

We propose a system that:

Detects anomalies in patient vitals
Identifies contributing factors
Generates human-readable clinical summaries using LLMs
🏗️ Architecture
Data → Anomaly Detection → RCA → LLM → Dashboard/API
📊 Features
Multivariate anomaly detection (LSTM, Isolation Forest)
SHAP-based explainability
Clinical summary generation using LLM
Risk prediction (ICU transfer, deterioration)
Interactive dashboard

🧪 Example Output

🚨 Alert: Patient deterioration detected

Primary Driver:
- SpO2 dropped from 96% → 88%

Contributing Factors:
- Increased respiratory rate
- Elevated heart rate

🧠 AI Insight:

Patient may be experiencing respiratory distress.
Recommend evaluating for infection or airway obstruction.


⚙️ Tech Stack

Python, PyTorch, scikit-learn
FastAPI, Streamlit
SHAP, XGBoost
Docker
