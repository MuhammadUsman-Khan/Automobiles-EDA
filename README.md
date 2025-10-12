# Automobiles EDA

[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-blue)](https://colab.research.google.com/drive/1mSFnuqSvH7x-gB5-kfErnTXcD4jPT5kK?usp=sharing)  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()  

---

## 📖 Project Overview

This repository contains a full **Exploratory Data Analysis (EDA)** of an automobile dataset.  
The goal is to analyze and visualize relationships among key vehicle attributes such as **price**, **horsepower**, **fuel efficiency (mpg)**, **engine size**, **curb weight**, and more.  
The notebook is available on **Google Colab** for immediate viewing and execution.  

👉 [Open the Automobiles EDA Notebook on Colab](https://colab.research.google.com/drive/1mSFnuqSvH7x-gB5-kfErnTXcD4jPT5kK?usp=sharing)

---

## 🧩 Objectives & Key Questions

- What are the distributions of continuous features like price, horsepower, weight, mpg?  
- Which features correlate strongly with car price?  
- How does engine size relate to fuel efficiency or horsepower?  
- Are there outliers or anomalies in the dataset?  
- Can we spot interesting patterns or clusters among the cars?  

---

## 📂 Repository Structure

Automobiles-EDA/ 

├── README.md  
└── Automobiles_EDA.ipynb


---

## 🛠️ Tools & Technologies

- **Python**  
- **Pandas**, **NumPy** — for data manipulation and numeric operations  
- **Matplotlib**, **Seaborn** — for creating visualizations  
- **Google Colab** — for interactive analysis  

---

## 📊 Recommended Visualizations & Techniques

- **Histogram / KDE Plot** — to examine distributions (e.g. price, curb weight, mpg)  
- **Boxplot / Violin Plot** — to compare distributions across categories (if any)  
- **Scatter Plot + Regression Line (lmplot)** — to explore relationships (e.g. horsepower vs price)  
- **Pairplot** — for multivariate numerical relationships  
- **Heatmap** — correlation matrix among features  
- **Bar Charts / Countplots** — where categorical features exist (e.g. number of cylinders, fuel type)  

---

## 🔑 Key Insights

- **Ford** has the **highest sales** among all manufacturers.  
- Within Ford, the **F-Series** model records the **highest sales**.  
- **Mercedes-Benz** leads in **resales** among all manufacturers.  
- The **Carrera Cabrio** by **Porsche** has the **highest resales** among all models.  
- **Porsche** cars possess the **highest horsepower** among manufacturers.  
- The **Viper** by **Dodge** has the **highest horsepower** among all models.  
- There is an **inverse relationship** between **horsepower** and **fuel efficiency** — higher horsepower means lower fuel efficiency.  
- **Engine size** is **negatively correlated** with **fuel efficiency** — larger engines reduce fuel efficiency.  
- **Normal cars** have **higher fuel efficiency** compared to **passenger cars**.  
- Cars with **higher fuel efficiency** tend to have **lower prices**.  
- Cars with **bigger engine sizes** generally have **higher prices**.  
- A car’s **wheelbase, width, length, and curb weight** are **positively correlated** with its **price**.
  
---

## 🚀 How to Run Locally

### 1. Clone the repository:

   ```
   git clone https://github.com/MuhammadUsman-Khan/Automobiles-EDA.git
   ```
### Change directory:

```
cd Automobiles-EDA
```
### Ensure the dataset (CSV or other data file) used in the notebook is in the same directory, or update file paths accordingly.

### Open the notebook locally:

```
jupyter notebook Automobiles_EDA.ipynb
```
Or open the Colab link above to run it online.

Execute the notebook cells in order to reproduce the analysis and visualizations.

## 🤝 Contributing
Contributions of additional visualizations, code cleanup, or deeper analysis are welcome!

Fork this repository

Create a new branch (git checkout -b feature-branch)

Make your changes and commit them

Push to your fork and open a Pull Request
