# Titanic Exploratory Data Analysis (EDA)

---

## Project Overview

This repository contains an Exploratory Data Analysis (EDA) of the famous Titanic dataset. The goal of this project is to understand the various factors that influenced survival rates during the Titanic disaster using statistical analysis and data visualization techniques.

## Dataset

The dataset used in this project is a cleaned version of the Titanic dataset, sourced from Kaggle. It includes passenger information such as `Survived`, `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and one-hot encoded `Embarked` ports.

## Analysis & Key Findings

This EDA covers:

* **Data Loading & Initial Inspection**: Understanding the dataset's structure, data types, and checking for missing values.
* **Summary Statistics**: Generating descriptive statistics for numerical and categorical features.
* **Distribution Analysis**: Visualizing the distributions of individual features using histograms, boxplots, and bar plots.
* **Feature Relationships**: Exploring correlations between numerical features and analyzing the impact of categorical features on survival rates through heatmaps, pairplots, and various bivariate plots (bar plots, violin plots, KDE plots).
* **Pattern Identification & Inferences**: Drawing conclusions about key factors influencing survival, such as gender, passenger class, and age.
* **Feature Engineering (Extra)**: Creation and analysis of a `FamilySize` feature, and exploration of survival rates across `Age` and `Fare` bins.

Key findings indicate that **gender (females had a significantly higher survival rate)** and **passenger class (higher classes had better survival chances)** were strong predictors of survival. Fare and age also played crucial roles.

## Technologies Used

* **Python**
* **Pandas**: For data manipulation and analysis.
* **Matplotlib**: For static data visualizations.
* **Seaborn**: For enhanced statistical data visualizations.
* **Plotly Express**: For interactive plots.
* **Google Colab**: The environment used for development.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SiddardhaShayini/Titanic-EDA.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Titanic-EDA
    ```
3.  **Open the Jupyter Notebook (or Google Colab):**
    The main analysis is within a Jupyter Notebook (or equivalent `.ipynb` file if you plan to upload it).
    ```bash
    # If you have Jupyter installed
    jupyter notebook
    ```
    Alternatively, you can upload the notebook directly to Google Colab.

4.  **Run all cells:** Execute all cells in the notebook to reproduce the analysis and visualizations.

---

## ✍️ Author

- Siddardha Shayini

---

