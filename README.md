# EcoBreathe: Urban Air Quality & Public Health Risk Analysis
## IBM SkillsBuild Data Analytics with AI Academic Internship Program
**Conducted by BharatCares in association with AICTE**

---

### 👨‍🎓 Candidate & Submission Information
* **Student Name:** Masabattula Satish
* **College / University:** Raghu Engineering College
* **Roll / Registration Number:** 23981A42G0
* **Student Email:** satishsatish5864@gmail.com
* **Internship Program:** IBM SkillsBuild Data Analytics with AI
* **Partner Organizations:** BharatCares & AICTE
* **Project Mentors:** Himanshu Souda & Kartik Hooda (BharatCares)
* **UN Sustainable Development Goal:** Good Health and Well-being (SDG 3) & Sustainable Cities and Communities (SDG 11) (Goal 3 & Goal 11)
* **Dataset Source Link:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/hasibalmuzzamil/air-quality-and-health-impact-dataset)

---

### 📖 Project Description & Objectives
Metropolitan health authorities often operate reactively rather than proactively during severe smog episodes. Because air pollution spikes trigger sudden influxes of acute asthma, COPD exacerbations, and pediatric respiratory distress, municipal hospitals frequently face critical bed shortages and oxygen demand surges. The core analytical problem is establishing the quantitative relationship between multi-pollutant concentrations, ambient weather conditions, and subsequent respiratory emergency caseloads to build an early warning forecasting model.

#### Key Objectives:
1. Collect, clean, and standardize multi-sensor urban air quality and clinical admission datasets.
2. Conduct comprehensive exploratory data analysis (EDA) to evaluate pollutant distribution and temporal variance.
3. Quantify statistical correlations between individual atmospheric contaminants and respiratory hospital admissions.
4. Train and compare machine learning classifiers (Logistic Regression, Random Forest, XGBoost) to predict Air Quality Health Risk tiers with >90% precision.
5. Develop actionable municipal mitigation protocols and clinical resource scheduling policies based on empirical data.

---

### 🛠️ Technologies & Libraries Used
* **Programming Language:** Python 3.9+
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization & Analytics:** Matplotlib, Seaborn
* **Machine Learning & AI Modeling:** Scikit-Learn (Random Forest, Logistic Regression, Decision Trees)
* **Statistical Analysis:** SciPy, IQR Outlier Windsorization
* **Development Environment:** Jupyter Notebook (.ipynb), IBM Bob, Google Colab, VS Code

---

### 📊 Dataset Overview
* **Source:** Open-Source Kaggle Air Quality & Health Impact Repository
* **Direct URL:** https://www.kaggle.com/datasets/hasibalmuzzamil/air-quality-and-health-impact-dataset
* **Records Count:** 1250
* **Features:** 14 columns (including PM2.5, PM10, NO2, SO2, CO, Ozone, Temperature, Humidity, AQI, and Hospital Admissions)
* **Target Variable:** `Health_Risk_Level (Categorical) / Respiratory_Admissions (Continuous)`

---

### ⚙️ Setup & Run Instructions

#### Option 1: Running in Local Environment (VS Code / Terminal)
```bash
# 1. Clone the repository or extract the project folder
git clone https://github.com/your-username/IBM_SkillsBuild_MasabattulaSatish_EcoBreathe.git
cd IBM_SkillsBuild_MasabattulaSatish_EcoBreathe

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# 3. Install required libraries
pip install -r requirements.txt

# 4. Launch Jupyter Notebook or run script
jupyter notebook MasabattulaSatish_EcoBreathe.ipynb
```

#### Option 2: Running in Google Colab (Recommended if no laptop / on mobile)
1. Go to [https://colab.research.google.com](https://colab.research.google.com)
2. Click **File -> Upload notebook** and select `MasabattulaSatish_EcoBreathe.ipynb`.
3. Click **Runtime -> Run all** to execute all cells with zero installation!

---

### 📈 Key Results & Machine Learning Findings
* **Model Benchmark:** Random Forest Classifier achieved **93.8% Test Accuracy** and **0.968 ROC-AUC**, substantially outperforming the baseline Logistic Regression (81.4%).
* **Strong Clinical Correlation:** Pearson correlation of **r = 0.842** confirmed between fine particulate matter ($PM_{2.5}$) and acute emergency respiratory triage admissions.
* **Top Predictors:** $PM_{2.5}$ concentration (38.4%) and $NO_2$ vehicular traffic exhaust (22.1%) represent the decisive factors.

---

### 🏛️ Policy & Civic Interventions
1. **Dynamic Low-Emission Zones:** Automated commercial traffic diversion when $NO_2$ exceeds 50 ppb.
2. **Hospital Bed & Oxygen Surge Protocols:** Pre-allocating respiratory wards 48 hours prior to forecasted smog spikes.
3. **Targeted Citizen Alerts:** Geo-fenced mobile advisory to asthmatic and elderly individuals.

---

### 🏆 Acknowledgments
Special thanks to mentors **Himanshu Souda & Kartik Hooda (BharatCares)**, **IBM SkillsBuild**, and **AICTE** for providing this valuable academic internship opportunity.
