
# Predicting Molecular Biomarkers for Cancer Therapeutic Response

## Overview
This Jupyter Notebook is dedicated to identifying transcriptomic/RNA expression biomarkers for drug response in cancer therapeutics. It aims to establish a correlation between gene expression features and drug response, leveraging data from patient-derived cell lines.

## Technical Details

### Data Processing and Analysis
- **Libraries Used:**
  - `pandas` for data manipulation and analysis.
  - `matplotlib` and `seaborn` for data visualization.
  - `scikit-learn` for machine learning models and tools.
- **Data Loading:**
  - Drug response data (`LogAC50`) and gene expression data are loaded from CSV files.
- **Initial Data Exploration:**
  - Methods like `head()` and `describe()` are used for preliminary examination of the datasets.

### Key Steps in the Notebook
1. **Data Wrangling:**
   - Merging and transforming datasets to align drug response data with gene expression data.
2. **Exploratory Data Analysis (EDA) and Cleanup:**
   - Handling missing values and datatype conversions.
   - Visual exploration of data distributions and relationships.
3. **Feature Selection and Dimensionality Reduction:**
   - Techniques like PCA (Principal Component Analysis) and NMF (Non-zero Matrix Factorization) are explored.
4. **Model Building:**
   - Implementation of Elastic Net Regularized Regression to predict drug response.

## Prerequisites
- Python 3.x
- Pandas, Matplotlib, Seaborn, scikit-learn

## Installation

This project requires Python 3.x and several Python libraries. If Python is not already installed, download and install it from [python.org](https://www.python.org/downloads/).

Once Python is set up, install the necessary libraries using pip, Python's package installer. Open your terminal or command prompt and execute the following commands:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
```

### Note
- Ensure that `pip` is updated to its latest version using `pip install --upgrade pip`.
- Some libraries may have dependencies that will be automatically installed by `pip`.

## Contributing
Aubhishek Zaman, PhD

## License
All rights reserved to Aubhishek Zaman, PhD

## Acknowledgements
Hassan Waqar
