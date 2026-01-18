# UIDAI Biometric Failure Risk Analysis

## 📌 Problem Statement
Children enrolled in Aadhaar between ages 5–9 often do not update their biometrics
as they grow. This leads to outdated biometric records and creates identification
challenges in adulthood.

This project identifies districts with high biometric failure risk by combining
Aadhaar enrollment and biometric update datasets.

---

## 📊 Datasets Used
- Aadhaar Enrollment Data (age-wise)
- Aadhaar Biometric Update Data

## 📊 Data Source

The datasets used in this project are publicly available from the
UIDAI Open Data portal via data.gov.in.

Due to GitHub file size limitations, raw CSV files are not included.

🔗 Official Source:

https://event.data.gov.in/hackathon_registration/?registration_id=MTA0OTcz

---

## 🧪 Methodology
- District-level aggregation of enrollment and biometric data
- Feature engineering to derive biometric failure
- Univariate, bivariate, and trivariate analysis
- Heatmap visualization
- Z-score based anomaly detection

---

## 🔍 Key Insights
- Districts with low adult biometric updates show higher child biometric failure
- Children enrolled at age 5–9 are least likely to update biometrics
- High-risk districts need targeted biometric update campaigns

---

## 🚨 Anomaly Detection
Districts with biometric failure rates significantly higher than average
are flagged as high-risk regions.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Project Structure

UIDAI_Project
├── data/
├── README.md
├── requirements.txt
└── notebook/

---

## 👤 Author
Nidhi Kumawat  
UIDAI Data Hackathon 2026

---

## ⚠️ Note
Raw CSV files are not uploaded due to GitHub size limits.
Please download datasets from the official UIDAI portal.
