# 🌍 Multivariate Visualization and Analysis of Global Health Inequality

This repository contains the source code, data preprocessing scripts, and visual analysis notebooks for **“Multivariate Visualization and Analysis of Global Health Inequality.”**
The project investigates global health disparities through multivariate data visualization and statistical analysis, using data science techniques to uncover structural patterns in worldwide health outcomes.

📄 The full project report is included in this repository as [`Project Report.pdf`](https://github.com/kaylaanglc/global-health-inequality-viz/blob/ec1fd109f879e5f48dbbf95b89b9edaf0f1af188/Project%20Report.pdf)

---

## 🧭 Overview

The project explores **global inequality in health outcomes** using a multivariate approach to identify key predictors of life expectancy and uncover hidden relationships among health indicators.

It addresses five main research questions:

1. Regional and income-level disparities in health outcomes.
2. The most predictive indicators of health status.
3. Trends in global health inequality over time.
4. Grouping of countries based on multivariate health profiles.
5. Combined effects of multiple health factors on life expectancy.

---

## 🧰 Tools & Libraries

Developed in **Python (Jupyter Notebook)** with the following key libraries:

* `pandas`, `numpy` — data cleaning & manipulation
* `matplotlib`, `seaborn` — static 2D plots
* `plotly` — interactive visualizations (choropleth, 3D surface)
* `scikit-learn` — PCA and K-means clustering
* `statsmodels` — OLS regression modeling

---

## 🗂️ Project Structure

```
📦 global-health-inequality-viz
├── major_project_code/
│   ├── 01_preprocessing.ipynb        # Data cleaning and preprocessing
│   ├── 02_eda.ipynb                  # Exploratory data analysis
│   ├── 03_time_series_analysis.ipynb # Temporal trend visualizations
│   ├── 04_barplot_ttest.ipynb        # Regional and income-level comparison (bar plots & t-tests)
│   ├── 05_pcs_kmeans.ipynb           # PCA and K-means clustering analysis
│   ├── 06_regression_analysis.ipynb  # OLS regression modeling
│   ├── 07_chloropleth.ipynb          # Choropleth map visualization
│   ├── 08_mesh_plot.ipynb            # 3D mesh surface visualization
│   ├── world_health_data.csv         # Original dataset
│   ├── cleaned_world_health_data.csv # Cleaned and preprocessed dataset
│   └── CLASS.xlsx                    # Additional reference data
├── Project Report.pdf 
```

---

## 📊 Key Visualizations

* Choropleth map of global life expectancy
* Correlation heatmap of health indicators
* OLS regression summary plots
* PCA scatter plot with K-means clusters
* 3D mesh surface of life expectancy vs. health factors

---

## 🧠 Insights

* Maternal, infant, and child mortality rates are the strongest negative predictors of life expectancy.
* Health expenditure improves outcomes but shows diminishing returns in high-mortality settings.
* Clustering reveals data-driven groupings that transcend income and region.
* 3D surface analysis illustrates nonlinear interactions between spending and outcomes.

---

## ⚙️ Dataset

**Source:** [Global Health Indicators Dataset – Kaggle](https://www.kaggle.com/datasets/bushraqurban/world-health-indicators-dataset)
Includes 180+ countries with annual data on life expectancy, mortality, health expenditure, fertility, immunization, and more.

---

## 📚 Acknowledgements

* Dataset: Bushra Qurban (Kaggle, 2023)
* Tools: Python, Jupyter Notebook, Plotly, Scikit-learn

