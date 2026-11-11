# Upay-Cashflow-Copilot


## 🚀 Project Overview

The upay Smart Cash-Flow Copilot predicts whether a user's wallet balance may fall below **500 BDT** during the last 10 days of the month. It provides risk alerts, understandable reasons, and optional financial suggestions to help users manage their money more effectively.

## ✨ Key Features

- **Cash-Flow Prediction:** Predicts potential wallet balance shortages.
- **Risk Alerts:** Displays Low, Medium, and High risk levels.
- **AI Explainability:** Uses SHAP to explain prediction results.
- **Smart Suggestions:** Provides buffer recommendations, cash-out fee insights, and savings plans.
- **Bangla & English:** Supports bilingual user messages.
- **What-If Analysis:** Allows users to explore different balance scenarios.
- **Financial Summary:** Shows spending patterns by category and week.

## 🛠️ Technologies Used

- Python
- FastAPI
- XGBoost
- SHAP
- HTML, CSS, JavaScript
- Pandas
- Scikit-learn

## 🤖 AI & Machine Learning

- XGBoost for cash-flow risk prediction.
- SHAP for model explainability.
- A helper model for estimating the lowest future balance.
- Rule-based logic for financial suggestions.

## 📊 Dataset

- 1,000 simulated users.
- 6 months of transaction data.
- Time-based training and testing.
- No real customer or upay production data used.

## ⚙️ Installation & Setup

```bash
git clone https://github.com/mahmudulhasanprotik47/upay-cashflow-copilot.git

cd upay-cashflow-copilot

python -m venv .venv

python -m pip install -r requirements.txt

python -m src.data.generator

python -m src.api.service

python -m uvicorn src.api.main:app --host 127.0.0.1 --port 8000
```

Then open http://127.0.0.1:8000/ in a browser.

## 🎯 Project Objective

To make digital wallet management smarter by providing early financial warnings, understandable insights, and practical suggestions that support better financial decisions.

## 👥 Team TriStack

Daffodil International University

- Mahmudul Hasan
- Fahim Montasir
- Ahsanur Rahman Nakib

**Event:** AI Hackathon 2026 – DIU CPC × upay

**Track:** Customer Innovation & Financial Independence

