#  Titanic Dataset - Exploratory Data Analysis (EDA)

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the publicly available **Titanic dataset** to understand the factors influencing passenger survival.
The analysis focuses on data cleaning, statistical exploration, and visualization to uncover meaningful patterns and relationships within the dataset.

This project demonstrates practical data analysis workflow aligned with real-world **Data Science and Analytics internship tasks**.



##  Project Objectives

* Load and explore a publicly available dataset
* Identify and handle missing values
* Perform statistical analysis on structured data
* Visualize data distributions and relationships
* Discover key survival patterns using graphical analysis
* Generate insights through exploratory analysis

---

## Dataset Information

The dataset contains passenger information from the Titanic disaster, including demographic details and travel attributes.

**Key Features Include:**

* Passenger Class (`Pclass`)
* Gender (`Sex`)
* Age
* Fare
* Family Relations (`SibSp`, `Parch`)
* Embarkation Port (`Embarked`)
* Survival Status (`Survived`)

Dataset Source: Public Titanic Dataset (Kaggle)

---

##  Tools & Technologies Used

* **Python**
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Interactive analysis environment
* **VS Code** — Development environment

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Imported dataset using Pandas
* Verified structure and column integrity

### 2️⃣ Dataset Understanding

* Examined dataset dimensions and data types
* Generated descriptive statistical summaries

### 3️⃣ Missing Value Analysis

* Detected missing values across features
* Visualized missing data patterns using heatmaps

### 4️⃣ Data Cleaning

* Filled missing `Age` values using median imputation
* Handled categorical missing values in `Embarked`
* Removed high-missing-value column (`Cabin`)
* Generated cleaned dataset for further analysis

### 5️⃣ Exploratory Data Analysis

Performed univariate and bivariate analysis including:

* Survival distribution
* Gender vs Survival comparison
* Passenger Class vs Survival relationship
* Age distribution analysis

### 6️⃣ Correlation Analysis

* Generated correlation heatmap
* Identified relationships between numerical variables

---

##  Key Insights

* Female passengers had significantly higher survival rates compared to males.
* First-class passengers showed greater survival probability than lower classes.
* Younger passengers demonstrated slightly improved survival trends.
* Fare exhibited positive correlation with survival likelihood.
* Socioeconomic status influenced evacuation outcomes.

---

##  Project Structure


Exploratory_Data_Analysis_Titanic/
│
├── data/
│   │
│   ├── raw/
│   │   └── Titanic_Dataset.csv
│   │
│   └── processed/
│       └── cleaned_titanic.csv
│
├── notebooks/
│   └── Titanic_EDA.ipynb
│
├── images/
│   ├── survival_distribution.png
│   ├── gender_survival.png
│   ├── class_survival.png
│   ├── age_distribution.png
│   └── correlation_heatmap.png
│
├── requirements.txt
│
└── README.md

---

## Results

The project successfully demonstrates how Exploratory Data Analysis can transform raw data into meaningful insights through structured preprocessing and visualization techniques.

---

##  Conclusion

Exploratory Data Analysis plays a critical role in understanding datasets prior to predictive modeling.
This project highlights essential data science skills including data preprocessing, visualization, statistical reasoning, and analytical storytelling — forming a strong foundation for real-world analytics and machine learning workflows.

---

## Future Improvements

* Feature engineering for predictive modeling
* Machine Learning survival prediction models
* Interactive dashboards using Plotly or Power BI
* Deployment-ready analytical reporting

---


