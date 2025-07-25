# 💼 Employee Salary Classification Web App

A powerful and interactive ML-based web app to predict whether an employee earns **more than 50K** or **less than or equal to 50K** annually based on multiple features. Built using **Streamlit**, it supports both **single prediction** and **batch prediction** via CSV uploads.

---

## 🔍 Problem Statement

Use the **Adult Income Dataset** to classify whether an individual earns `>50K` or `<=50K` based on demographic and professional details. This classic **binary classification** problem is widely used in the ML community.

---

## 🧠 Features Used

| 🔢 Feature            | 🧾 Description                           |
|----------------------|-------------------------------------------|
| `age`                | Age of the individual                     |
| `education`          | Highest educational qualification         |
| `occupation`         | Type of job/role                          |
| `hours-per-week`     | Average working hours per week            |
| `experience`         | Total years of experience                 |

➡️ **Additional batch-only fields**:
- Marital Status
- Gender
- Race
- Relationship
- Capital Gain / Loss
- Native Country
- Workclass

---

## 🛠️ Tech Stack

- 🐍 **Python 3**
- 📊 **Pandas, NumPy**
- 🤖 **Scikit-learn (Random Forest Classifier)**
- 🎯 **Joblib** – Save and load models
- 🌐 **Streamlit** – Interactive Web UI
- 📈 **Matplotlib / Seaborn** – Visualization

---

## 🚀 Run Locally

```bash
# 1. Clone this repo
git clone https://github.com/your-username/employee-salary-prediction.git
cd employee-salary-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the app
streamlit run app.py
