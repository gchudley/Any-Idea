# Any-Idea

Brown University DATA1030 project repository for team Any Idea.

- **Project Mentor:** Sarah Bao
- **Team members:** George	Chudley, Jinhong Jiang, Linrui Zhao, Wenxin Lyu

## Research Purpose

TBD

## Original Data Source and Documentation

The original dataset is published by the New York City Department of Buildings
through NYC Open Data. This project uses records for **calendar year 2024**.

- [Original dataset: NYC Building Energy and Water Data Disclosure for Local Law 84](https://data.cityofnewyork.us/Environment/NYC-Building-Energy-and-Water-Data-Disclosure-for-/5zyy-y8am/about_data)
- [Official data documentation: NYC Building Energy and Water Data Dictionary (Excel)](https://data.cityofnewyork.us/api/views/5zyy-y8am/files/d11b2da1-2b2b-4da8-a3a2-24dea9f10833?download=true)
- [Original data API endpoint](https://data.cityofnewyork.us/resource/5zyy-y8am.json)

## Repository Structure

The directory structure is:

```text
.
├── data/       # Raw and preprocessed datasets
├── figures/    # Generated plots and visualizations
├── results/    # Predictions, saved models, and evaluation results
├── report/     # Midterm report PDF and final presentation slides
├── src/        # All of the Python scripts and Jupyter notebooks
├── .gitignore
├── LICENSE
└── README.md
```

## Environment and Reproducibility

The local development environment is the Conda environment `data1030` which is recommended by this course. The project environment uses **Python 3.14.6**.

[environment.yml](environment.yml) records the project's installed dependency versions.

For comparison with the course environment and for additional environment checks,
see the following external resources:

- [DATA1030 Fall 2026 course repository](https://github.com/BrownDSI/DATA1030-fall2026)
- [Course Conda environment configuration: data1030.yml](https://github.com/BrownDSI/DATA1030-fall2026/blob/main/data1030.yml)
- [Course environment verification notebook: test_environment.ipynb](https://github.com/BrownDSI/DATA1030-fall2026/blob/main/test_environment.ipynb)
