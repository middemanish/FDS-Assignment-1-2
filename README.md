# Fundamentals of Data Science — Case Studies

This repository contains two case studies completed as part of the **Fundamentals of Data Science (22CSC59)** coursework for the academic year 2026–27.

## Case Studies

### 1. Wine Quality Assessment Using Physicochemical Properties

**Notebook:** `Wine_Quality_Case_Study.ipynb`  
**Report:** `Report_Wine_Quality_Assessment.pdf`

Analyzes the physicochemical properties of red wine using statistical analysis, exploratory data analysis, correlation analysis, and multiple linear regression to identify factors associated with wine quality and predict quality scores.

**Techniques:** Descriptive statistics, data visualization, correlation analysis, multiple linear regression, MAE, MSE, RMSE, R², and VIF.

### 2. Clustering Analysis on East-West Airlines Customers

**Notebook:** `EastWest_Clustering_Analysis.ipynb`  
**Report:** `Report_EastWest_Airlines_Clustering.pdf`

Segments frequent-flyer customers based on travel activity, mileage balances, bonus transactions, credit card activity, and membership history using different clustering algorithms.

**Techniques:** Data preprocessing, outlier detection, feature scaling, exploratory data analysis, PCA, K-Means, Hierarchical Clustering, DBSCAN, and silhouette analysis.

## Repository Structure

```text
Machine-Learning-Case-Studies/
├── README.md
├── Wine_Quality_Case_Study.ipynb
├── EastWest_Clustering_Analysis.ipynb
├── winequality-red.csv
├── winequality-white.csv
├── winequality.names
├── EastWestAirlines.xlsx
├── Report_Wine_Quality_Assessment.pdf
└── Report_EastWest_Airlines_Clustering.pdf
```

### Dataset Files

- `winequality-red.csv` — Red wine quality dataset used in the analysis.
- `winequality-white.csv` — White wine quality dataset.
- `winequality.names` — Dataset description and attribute information.
- `EastWestAirlines.xlsx` — Airline customer data and column descriptions.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- SciPy
- Scikit-learn
- Statsmodels

## Getting Started

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels openpyxl jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open either notebook and execute its cells sequentially. Ensure the required dataset files are available at the paths specified in the notebooks.

## Learning Outcomes

- Perform statistical analysis and exploratory data analysis.
- Build and evaluate regression models.
- Apply data preprocessing and feature scaling.
- Compare clustering algorithms and evaluate cluster quality.
- Interpret results and derive practical insights.

---

**Course:** Fundamentals of Data Science (22CSC59)  
**Academic Year:** 2026–27  
**Section:** CSE-3
