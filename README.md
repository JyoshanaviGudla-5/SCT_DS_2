# Titanic Survival Analysis - SCT_DS_2

### 📌 Project Overview
This project is part of the SkillCraft Technology Data Science Internship - Task 02. The goal is to analyze the Titanic passenger dataset to identify key factors that influenced survival rates during the disaster.

### 🎯 Objective
To perform Exploratory Data Analysis (EDA) and answer key questions:
1.  Did gender impact survival chances?
2.  Did passenger class impact survival chances?
3.  Clean and prepare the data for future machine learning models.

### 🛠️ Tools & Libraries Used
- **Language**: Python
- **Environment**: Google Colab
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

### 📂 Dataset
The dataset used is the `train.csv` file from the famous [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data). It contains details like passenger age, sex, class, fare, and whether they survived.

### ⚙️ Key Steps Performed
1.  **Data Loading**: Loaded the dataset and checked for basic info.
2.  **Data Cleaning**:
    - Filled missing `Age` values with the mean age.
    - Dropped the `Cabin` column due to excessive missing data.
    - Filled missing `Embarked` values with the most common port.
3.  **Exploratory Data Analysis (EDA)**:
    - Analyzed survival rate based on `Sex`.
    - Analyzed survival rate based on `Pclass`.
    - Visualized the data using a count plot.

### 📊 Key Findings
1.  **Gender**: Females had a significantly higher survival rate of 74.2% compared to males at 18.9%. The "women and children first" protocol was evident.
2.  **Passenger Class**: 1st class passengers had the highest survival rate at 63.0%. 3rd class passengers had the lowest at 24.2%. Socio-economic status played a major role.

### 🚀 How to Run
1.  Open the `SCT_DS_2_Titanic.ipynb` notebook in Google Colab.
2.  Upload the `train.csv` file when prompted.
3.  Run all cells from top to bottom to reproduce the analysis and visualizations.

### 📈 Future Scope
- Feature Engineering: Create new features like `FamilySize` from `SibSp` and `Parch`.
- Model Building: Use machine learning models like Logistic Regression or Random Forest to predict survival.
