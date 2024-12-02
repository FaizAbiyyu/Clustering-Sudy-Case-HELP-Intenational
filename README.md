
# Clustering Study Case: HELP International

This repository contains an analysis of socio-economic and health factors to classify countries and suggest prioritization for humanitarian aid by HELP International, an NGO focused on poverty alleviation and disaster relief.

## Objective

The aim is to use clustering algorithms (K-Means and Hierarchical Clustering) to group countries based on their development levels and socio-economic needs. This helps the NGO's leadership to decide where to allocate their recently raised $10 million in funding most effectively.

## Contents

- **`Country-data.csv`**: The primary dataset containing socio-economic and health indicators for various countries.
- **`Data Dictionary.csv`**: A description of the columns in the dataset.
- **`HELP International Case Study.ipynb`**: The Jupyter Notebook with the implementation of the clustering models and analysis.
- **`Help International Case Study.pdf`**: A report summarizing the project outcomes and recommendations.
- **`README.md`**: Project documentation (this file).

## Methodology

1. **Data Preprocessing**:
   - Handling missing values.
   - Standardizing numerical variables for better clustering performance.

2. **Clustering Techniques**:
   - **K-Means Clustering**: Identifying optimal clusters using the elbow method.
   - **Hierarchical Clustering**: Dendrogram analysis to validate K-Means results.

3. **Insights**:
   - Identifying clusters of countries based on socio-economic and health needs.
   - Recommending priority countries for funding based on cluster characteristics.

## Tools Used

- **Python**: Primary programming language for analysis.
- **Jupyter Notebook**: Environment for exploratory data analysis and visualization.
- Libraries:
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib`, `seaborn` for visualization.
  - `scikit-learn` for machine learning.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/FaizAbiyyu/Clustering-Sudy-Case-HELP-Intenational.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook HELP International Case Study.ipynb
   ```
4. Follow the instructions in the notebook to reproduce the analysis.

