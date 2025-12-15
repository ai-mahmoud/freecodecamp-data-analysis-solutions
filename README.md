# 🧠 FreeCodeCamp: Data Analysis with Python

![Badge](https://img.shields.io/badge/Certificate-Completed-brightgreen?style=for-the-badge)
![Badge](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![Badge](https://img.shields.io/badge/FreeCodeCamp-Data%20Analysis%20with%20Python-black?style=for-the-badge)

---

## 🎓 Certificate

[View Official Certificate →](https://www.freecodecamp.org/certification/dr4who/data-analysis-with-python-v7)

---

## 🧾 Overview

This repository contains my work for the **FreeCodeCamp Data Analysis with Python** certification.  
It includes both the guided exercises and the required projects, each demonstrating Python-based data analysis techniques using **Pandas**, **NumPy**, and **Matplotlib**.

All work was completed in **Jupyter Notebooks** on a local Anaconda environment.

---

## 🧠 Skills Practiced

- Reading and cleaning real-world datasets  
- Exploratory data analysis (EDA)  
- Visualizing trends and correlations  
- Statistical calculations (mean, variance, standard deviation)  
- Data transformation with Pandas and NumPy  
- Building reproducible analytical workflows  

---

## 🧩 Repository Structure 
```
  learning/
└── freecodecamp/
    └── data_analysis/
        ├── 2 - Pandas Series exercises.ipynb
        ├── 3 - NumPy exercises.ipynb
        ├── 4 - Pandas DataFrames exercises.ipynb
        ├── Exercises_1.ipynb
        ├── sales_data.csv
        ├── README.md
        └── projects/
            ├── data/
            │   ├── adult.data.csv
            │   ├── epa-sea-level.csv
            │   ├── fcc-forum-pageviews.csv
            │   └── medical_examination.csv
            ├── demographic-data-analyzer.ipynb
            ├── mean_variance_std.ipynb
            ├── medical.ipynb
            ├── pageviews.ipynb
            └── sea_level_predictor.ipynb
```

---

## 🧪 Projects

| Project | Description |
|----------|--------------|
| 📊 **Demographic Data Analyzer** | Cleaned and analyzed census data to find population insights. |
| 🧮 **Mean-Variance-Standard Deviation Calculator** | Implemented a matrix statistics calculator using NumPy. |
| 🩺 **Medical Data Visualizer** | Explored medical data, visualized BMI and cholesterol relationships with Seaborn. |
| 📈 **Page View Time Series Visualizer** | Analyzed and plotted web traffic data trends with Matplotlib. |
| 🌊 **Sea Level Predictor** | Built a linear regression model to predict sea level rise through 2050. |

---

## ⚙️ Tools and Libraries

| Category | Tools |
|-----------|--------|
| **Language** | Python 3.x |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook (Anaconda) |
| **Version Control** | Git & GitHub |

---

## 🧩 Example Snippet

```python
import pandas as pd
import matplotlib.pyplot as plt
from scipy.stats import linregress

# Sea Level Prediction Example
df = pd.read_csv('projects/data/epa-sea-level.csv')
plt.scatter(df['Year'], df['CSIRO Adjusted Sea Level'])
slope, intercept, _, _, _ = linregress(df['Year'], df['CSIRO Adjusted Sea Level'])
years = range(1880, 2051)
plt.plot(years, intercept + slope * pd.Series(years), color='red')
plt.title('Rise in Sea Level (1880–2050)')
plt.xlabel('Year')
plt.ylabel('Sea Level (inches)')
plt.show()
```

---

## 📚 Exercises Included

| Notebook                                  | Focus                                   |
| ----------------------------------------- | --------------------------------------- |
| **Exercises_1.ipynb**                     | Introductory Python data analysis tasks |
| **2 - Pandas Series exercises.ipynb**     | Data manipulation using Pandas Series   |
| **3. NumPy exercises.ipynb**              | Numerical operations and arrays         |
| **4 - Pandas DataFrames exercises.ipynb** | DataFrames and advanced transformations |

---

## 📫 Contact

**Mahmoud (dr4who)**  
__Data Scientist & AI Enthusiast__  
🔗 [GitHub Profile](https://github.com/dr4who)  
🎓 [FreeCodeCamp Profile](https://www.freecodecamp.org/dr4who)  

---

⭐ *If this repo helped you learn or revise data analysis, consider leaving a star!*

---
