# CS 6140 Final Project

Fall 2022

Group 8

[![Watch the video](https://img.youtube.com/vi/k_K2xKfLOgk/default.jpg)](https://youtu.be/k_K2xKfLOgk)

## Files

### Data
- The `data/` directory contains all the data files: 
  - `COVID19_European data.xlsx` is the raw data file taken from [https://data.mendeley.com/datasets/2ghxnrkr9p/4](https://data.mendeley.com/datasets/2ghxnrkr9p/4)
  - `raw_data.csv` is the data extracted from this file
  - `pop_data_df.csv` and `pop_env_data_df.csv` are the full data sets
  - The rest of the files are these data sets split into training and testing sets
- The notebook `data_preprocessing.ipynb` takes the file `raw_data.csv` and generates the processed data files

### Models
- Each file contains a Jupyter notebook that implements a model and generates figures and coefficients of regression

### Reports
- `final_report.docx` is the report for the project

## Instructions
Once the repository is cloned, each notebook can be fully run with `sklearn` and associated packages
