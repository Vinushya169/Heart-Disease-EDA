# ❤️ Heart Disease - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project presents a detailed Exploratory Data Analysis (EDA) on a synthetic heart disease dataset. The main objective is to analyze various medical factors that contribute to heart disease and to derive meaningful insights through statistical analysis and data visualizations.

This project was completed as a part of academic data analysis coursework to understand real-world health data handling, preprocessing, and visualization.

## 📁 Repository Structure
Heart-Disease-EDA/
│
├── Heart_Disease_EDA_Report.docx          # Detailed EDA Report with graphs
├── synthetic_heart_disease_dataset.csv    # Synthetic dataset
└── http://README.md                              # Project documentation

## 📊 Dataset Description
The dataset `synthetic_heart_disease_dataset.csv` is a synthetic dataset created for educational purposes that mimics real-world heart disease data.

**Dataset Features:**
- **Age:** Age of the patient
- **Sex:** Gender (Male/Female)
- **Chest Pain Type:** Type of chest pain (Typical Angina, Atypical Angina, Non-Anginal Pain, Asymptomatic)
- **Resting BP:** Resting Blood Pressure (in mm Hg)
- **Cholesterol:** Serum Cholesterol level (in mg/dl)
- **Fasting Blood Sugar:** > 120 mg/dl (Yes/No)
- **Resting ECG:** Resting Electrocardiographic results
- **Max Heart Rate:** Maximum heart rate achieved
- **Exercise Induced Angina:** Exercise induced angina (Yes/No)
- **Oldpeak:** ST depression induced by exercise relative to rest
- **ST Slope:** Slope of the peak exercise ST segment
- **Target:** Presence of heart disease (0 = No, 1 = Yes)

Total Records: ~1000+ entries (synthetic)

## 🔍 EDA Process Followed

### 1. Data Understanding
- Imported dataset and checked shape, data types
- Identified numerical and categorical columns
- Checked for missing values and duplicates

### 2. Data Cleaning
- Handled missing values
- Checked outliers in Cholesterol, BP, Heart Rate
- Converted categorical variables to suitable format

### 3. Univariate Analysis
- Age distribution of patients
- Gender distribution
- Cholesterol and Blood Pressure distribution
- Target variable distribution (Heart disease present vs absent)

### 4. Bivariate & Multivariate Analysis
- Correlation heatmap for numerical features
- Age vs Max Heart Rate
- Cholesterol vs Heart Disease
- Chest Pain Type vs Heart Disease
- Exercise Induced Angina vs Heart Disease
- ST Slope and Oldpeak analysis

### 5. Visualizations Created
- Histogram & KDE plots
- Box plots for outlier detection
- Count plots for categorical features
- Correlation heatmap
- Scatter plots
- Bar charts for disease prevalence

All visualizations are documented in the `.docx` report with interpretations.

## 💡 Key Insights Obtained

1.  **Age Factor:** Higher age group (50-70) shows higher prevalence of heart disease.
2.  **Gender Factor:** Males are more prone to heart disease compared to females in this dataset.
3.  **Cholesterol:** High cholesterol levels (>240 mg/dl) are associated with increased risk.
4.  **Chest Pain:** Asymptomatic and Atypical Angina types show strong correlation with heart disease presence.
5.  **Max Heart Rate:** Lower max heart rate achieved during exercise indicates higher risk.
6.  **Exercise Induced Angina:** Patients with exercise-induced angina have higher probability of heart disease.
7.  **Oldpeak & ST Slope:** Higher Oldpeak values and flat ST slope indicate abnormal heart condition.

## 🛠️ Tools & Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook / Google Colab
- **Documentation:** Microsoft Word
- **Version Control:** Git & GitHub

## 🚀 How to Run This Project

1.  Clone the repository:
    ```bash
    git clone https://github.com/Vinushya169/Heart-Disease-EDA.git
2.  Open the CSV file in Jupyter Notebook / VS Code
3.  Install required libraries:
    pip install pandas numpy matplotlib seaborn
4.  Start exploring!

## 📄 Detailed Report
A complete report with all graphs, explanations, and conclusions is available in `Heart_Disease_EDA_Report.docx`. Please refer to it for in-depth analysis.

## 🔮 Future Scope
- Building a Machine Learning model for Heart Disease Prediction
- Creating an interactive dashboard using Power BI / Streamlit
- Comparing synthetic vs real-world dataset performance
- Deploying a prediction web app

## 👩‍🎓 Author
*Vinushya*
B.E Computer Science and Enigneering
Heart Disease EDA Project
-------
*Note:* This dataset is synthetic and created for educational purposes only. It should not be used for actual medical diagnosis.

⭐ If you found this repository helpful, please give it a star!
