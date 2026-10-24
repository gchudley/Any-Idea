# Brown University DATA1030 26Fall Group Project for Group Any-Idea

- *Project Mentor:* ***Sarah Bao***
- *Team members:* ***George Chudley, Jinhong Jiang, Linrui Zhao, and Wenxin Lyu***

# Overview

This project aims to use the NYC's 2024 building energy disclosure data for LL84 to develop machine learning models which predict property-level Site EUI (energy use intensity).

# Original Data Source and Official Data Documentation

The original dataset is published by the New York City Department of Buildings through NYC Open Data. 
This project uses records for **calendar year 2024**.

1. Original dataset: NYC Building Energy and Water Data Disclosure for Local Law 84 is here (https://data.cityofnewyork.us/Environment/NYC-Building-Energy-and-Water-Data-Disclosure-for-/5zyy-y8am/about_data).
2. Official data documentation: NYC Building Energy and Water Data Dictionary for Excel is here (https://data.cityofnewyork.us/api/views/5zyy-y8am/files/d11b2da1-2b2b-4da8-a3a2-24dea9f10833?download=true).

# Repository Structure

- `data` (Raw and preprocessed data files)
- `figures` (Data visualizations)
- `results` (Predictions, saved models and evaluation results)
- `report` (PDF version of the midterm report and final presentation slides)
- `src` (All of the jupyter notebooks)

# Environment Requirement

The preferred running environment is the **Conda** environment along with a **Python version 3.14.6**. 
A `data1030` virtual environment is recommended by this course and all of the jupyternotebooks could be run under that kernel with these following main package versions:

- python=3.14.6
- numpy=2.4.6
- matplotlib=3.11.0
- seaborn=0.13.2 
- pandas=3.0.3
- polars=1.41.2
- scikit-learn=1.9.0
- py-xgboost=3.2.0
- shap=0.52.0
- tabpfn=8.0.8
- requests=2.34.2
- scipy=1.18.1
- jupyterlab=4.6.3
- notebook=7.6.2
- ipykernel=7.3.0
- openpyxl=3.1.5

Also, there is an [environment.yml](environment.yml) file records this project's installed main dependency versions.
