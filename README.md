# SCT_DS_02
# Titanic — Exploratory Data Analysis (EDA) & Data Cleaning

**Short description:**  
A compact EDA project on the classic Titanic dataset (passenger list & survival), demonstrating data-cleaning steps, exploratory analysis, visualizations, and insights. This repository is intended as a reproducible notebook-based project ready to publish on GitHub.

---

## Project overview
This repo contains a Jupyter Notebook that cleans the Titanic dataset, performs exploratory data analysis to explore relationships between features (like `Pclass`, `Sex`, `Age`, `Fare`, `SibSp`, `Parch`, `Embarked`) and the target (`Survived`), and generates visualizations that highlight patterns and trends that influenced survival.

---

## Dataset
The dataset used is the Titanic passenger table (columns include `PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked`).  
Include your CSV in `data/titanic.csv` — the version used in this project is available in this repository.

---

## What I did (high-level)
- Loaded the Titanic CSV and inspected schema and missing values.
- Cleaned and engineered features (example: extracted `Title` from `Name`, created `FamilySize`, imputed missing values, encoded categorical variables).
- Performed EDA:
  - Univariate analysis (distributions of Age, Fare, Pclass, Sex).
  - Bivariate analysis (Survival rate by Sex, Pclass, Age groups, Embarked).
  - Multivariate exploration.
  - Visualizations: bar plots, histograms, boxplots, heatmap of correlations.
- Documented key insights and saved figures.

---

## Folder / File structure (suggested)
