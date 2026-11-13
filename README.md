# Medical Charges Analysis

A Python project exploring how recorded medical charges differ by smoking status, age, BMI, sex, region and number of children. The analysis uses pandas, NumPy and Matplotlib.

[View the notebook and saved charts](Medical_Charges_Analysis.ipynb)

## Findings

- Among 1,338 records, mean charges were 32,050.23 for smokers and 8,434.27 for non-smokers, a ratio of about 3.8 to 1.
- Mean charges rose from 9,182.49 for ages 18–29 to 17,902.55 for ages 50–64.
- Overall mean charges (13,270.42) exceeded the median (9,382.03), so the notebook reports both.

These are descriptive comparisons within the supplied records. The sampling method and billing period are unknown, and USD is assumed. The comparisons do not establish causation.

## Run locally

1. Download [insurance.csv](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv) and save it next to the notebook.
2. In that folder, install the dependencies with `python -m pip install -r requirements.txt`.
3. Start Jupyter with `python -m jupyter notebook`, open the notebook and run all cells from top to bottom.

Dataset description: [Medical Cost Personal Datasets on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance). The raw CSV is available from the linked GitHub source.
