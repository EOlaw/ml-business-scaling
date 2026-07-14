# Machine Learning for Business Growth Simulation

## 📘 Overview
This project simulates a **real-world data science job scenario** where a Machine Learning model is used to **analyze customer data, predict conversions, and provide insights to scale a business**.  
It is based on a fictional consulting company, **Meridian Analytics**, which provides IT, data science, and life literacy consulting services.

The simulation walks through every step of the ML workflow — from **data collection** and **EDA** to **modeling** and **business recommendations**.

---

## 🏢 Company Background
**Meridian Analytics** is a data-driven consulting firm founded in 2023. The company helps organizations make informed decisions through analytics and machine learning, while integrating values of purpose, stewardship, and growth.

They recently launched an online consultation platform and aim to:
- Increase **conversion rates** from free to paid consultations.  
- Identify **high-value clients** to target with personalized campaigns.  
- Optimize **marketing spending** across digital channels.  

---

## 🎯 Project Objective
The goal is to leverage **Machine Learning** to:
1. Predict which users are most likely to convert to paying clients.
2. Identify key factors influencing user engagement and retention.
3. Recommend strategies to **scale the business efficiently**.

---

## 🧠 Datasets
Three CSV datasets are included:

### `users.csv`
| Column | Description |
|---------|--------------|
| user_id | Unique user identifier |
| age | Age of user |
| gender | Gender of user |
| region | User’s region (North, South, East, etc.) |
| signup_date | Date the user signed up |
| referral_source | Channel that brought the user in (Google, Instagram, etc.) |

### `consultations.csv`
| Column | Description |
|---------|--------------|
| consultation_id | Unique consultation identifier |
| user_id | Linked user |
| consultant_id | Linked consultant |
| date | Consultation date |
| duration | Duration (minutes) |
| price | Price paid |
| completed | Whether the consultation was completed |

### `marketing.csv`
| Column | Description |
|---------|--------------|
| campaign_id | Unique marketing campaign ID |
| channel | Platform used (Google, Instagram, etc.) |
| spend | Campaign cost |
| clicks | Number of clicks |
| conversions | Number of successful sign-ups |
| date | Date of campaign |

---

## 🧩 Project Steps
1. **Data Loading & Cleaning:** Importing and preparing datasets for analysis.  
2. **Exploratory Data Analysis (EDA):** Understanding patterns in user demographics and behavior.  
3. **Feature Engineering:** Combining consultation activity with user profiles.  
4. **Model Building:** Using a Random Forest Classifier to predict user conversion likelihood.  
5. **Evaluation:** Assessing model performance using accuracy, AUC, and feature importance.  
6. **Business Insights:** Recommending actionable strategies based on model outputs.

---

## 🧰 Tools & Technologies
- **Python 3.11+**
- **pandas, numpy**
- **scikit-learn**
- **matplotlib, seaborn**
- **Jupyter Notebook**

---

## 📊 Results Summary
- Identified key predictive features: `referral_source`, `region`, `total_spent`, and `completion_rate`.
- Achieved a strong ROC AUC score on test data.
- Recommended targeted marketing for high-converting channels and personalized engagement strategies.

---

## 📈 Business Impact
Through this simulation:
- Businesses can **predict customer conversion** before investing in marketing.
- Resources can be **allocated intelligently** across top-performing acquisition channels.
- Strategies can be **automated** for user segmentation and personalized outreach.

---

## 📂 Files
| File | Description |
|------|--------------|
| `users.csv` | User demographic data |
| `consultations.csv` | Consultation activity data |
| `marketing.csv` | Marketing performance data |
| `ML_Business_Scaling_Simulation.ipynb` | Full ML workflow notebook |
| `README.md` | Project documentation |

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/EOlaw/ml-business-scaling.git
   cd business-growth-ml-simulation
