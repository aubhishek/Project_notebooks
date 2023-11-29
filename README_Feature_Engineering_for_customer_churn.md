
# Data Storytelling & Feature Engineering AZ V6

## Overview
This Jupyter Notebook is adapted from an existing notebook focused on automated feature engineering using Featuretools. It demonstrates how to build relevant features for a set of labels using data up to a specified cutoff time. The notebook employs Featuretools, an open-source Python library, to automate the feature engineering process in a relational dataset.

## Workflow
1. **Introduction to Automated Feature Engineering:**
   - Utilizing Featuretools for building features from a relational dataset.
   - Filtering data based on cutoff times to build relevant features.

2. **Installation of Required Libraries:**
   - Instructions for installing specific versions of pandas, Featuretools, dask, distributed, tornado, and other required libraries.

3. **Feature Engineering Process:**
   - Developing a reusable framework to automatically create a feature matrix for training machine learning models.

## Libraries and Dependencies
- `pandas`
- `featuretools`
- `dask`
- `distributed`
- `tornado`
- Other dependencies as required by the specific versions of the above libraries.

## Installation

### Setting Up the Environment
Before running the notebook, ensure the required libraries are installed. You can install them using pip and conda:

```bash
pip install pandas==1.1.1 featuretools==0.4.0 dask==0.19.4 distributed==1.23.3 tornado==5.0.0
conda install -c conda-forge featuretools==0.27.0
```

### Note
- Ensure `pip` and `conda` are updated to their latest versions.
- Some packages may have additional dependencies that will be automatically installed.

## Contributing
- Aubhishek Zaman, PhD

## License
- All rights reserved to Aubhishek Zaman, PhD

## Acknowledgements
- This notebook is adapted from [Featuretools Predict Customer Churn](https://github.com/Featuretools/predict-customer-churn/blob/master/churn/3.%20Feature%20Engineering.ipynb).
