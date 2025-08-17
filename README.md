Smart Loan Recovery

Author: Sapna Mohanta
Case Study Submission – TVS Credit EPIC

📌 Problem Understanding

NBFCs often face challenges with inefficient loan collection methods, which result in poor recovery rates and dissatisfied customers.

This project demonstrates how AI, predictive analytics, and intelligent automation can transform loan collections by:

Predicting customer repayment risk.

Recommending personalized recovery strategies.

Engaging customers empathetically through an AI-powered chatbot.

🚀 Approach

Predictive Model (Simulated ML in JS)

Calculates a Risk Score for each customer based on missed payments, sentiment, and behavioral features.

Strategy Engine

Uses the risk score to recommend a tailored recovery strategy (e.g., friendly reminder vs. urgent call-to-action).

Persona-Based Chatbot (LLM-powered)

Adapts its tone and messaging style to the customer’s persona.

Uses Gemini API for generating drafts, repayment plan suggestions, and strategic engagement.

Interactive Frontend

Visualizes customer risk distribution via Chart.js.

Provides intuitive, modern UI with Tailwind CSS + Phosphor Icons.

🛠️ Technology Stack
Frontend

HTML → Core structure for web pages.

Tailwind CSS → Utility-first CSS framework for clean, responsive UI.

JavaScript → Main logic and interactivity.

Chart.js → Data visualization (risk score charts).

Phosphor Icons → Enhances the UI with intuitive icons.

Backend / ML Simulation

Simulated ML Model in JavaScript → Calculates customer risk scores (rule-based for demo).

Gemini API (LLM) → Powers the Strategic Engagement Chat, generates communication drafts, and repayment plan suggestions.

(Note: In production, this could be upgraded to Python ML models with Scikit-learn/XGBoost + server deployment.)

🎯 Expected Benefits

30% improved efficiency in collections through automation.

Higher recovery rates using targeted, data-driven strategies.

Better customer experience via empathetic, persona-based engagement.

📊 Evaluation Metric

AUC-ROC → Selected as the primary evaluation metric, since it handles imbalanced datasets well and shows how effectively the model differentiates between likely defaulters vs. payers.

📂 Repository Structure
smart-loan-recovery/
│── data/                  # dataset (to be added later)
│── notebooks/             # EDA / ML exploration
│── src/                   # core JS code (risk scoring, strategy engine, chatbot)
│── outputs/               # generated reports/metrics
│── requirements.txt       # dependencies (planned for full version)
│── README.md              # project documentation
└── LICENSE

📌 Status

✅ Repo initialized with structure & docs.
🚧 Full implementation + dataset integration to follow.

🔗 References

McKinsey – The Future of Collections
Kaggle – Credit Risk Modeling
Chart.js Documentation
Tailwind CSS
Google Gemini
