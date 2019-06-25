# Austin Police Department Crime Incidents Analysis

This analysis cromprises structured and unstructured machine learning techniques on APD crime incidents data. We use various techniques including random forests, logistic regression, adaptive boosting, linear regression OLS, linear regression SGD, and MLP Regression.

* Classification and regression models:  crime_class_regr.ipynb 
* Clustering:  crime_clust.ipynb

## Requirements

Python 3.*
	
Anaconda Python distribution (recommended)

## Installation

### 1. Install Anaconda

Reference:  
 	macOS:    https://docs.continuum.io/anaconda/install/mac-os.html  
 	Windows:  https://docs.continuum.io/anaconda/install/windows  

### 2. Create conda environment from the crime-requirements.yml file

Reference: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

Example Code:  `conda env create -f crime-requirements.yml --name crime-env`

### 3. Activate the new environment

Example Code:  
	macOS: `conda activate crime-env`  
 	Windows: `activate crime-env`  

### 4. Launch Jupyter Notebooks

Reference: https://jupyter-notebook.readthedocs.io/en/stable/

Example:  `jupyter notebook`