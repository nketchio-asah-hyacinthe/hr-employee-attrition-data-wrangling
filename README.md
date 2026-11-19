# HR Employee Attrition Data Wrangling

A beginner pandas project applying data-wrangling skills from IBM's Data Analysis with Python, and Coursera's Practical Data Wrangling with Python and Pandas guided project to a public HR dataset.

This is a learning project focused on inspecting data and practicing introductory transformations. It is not a prediction model or a completed client data-cleaning job.

## Project details

- **Rows and columns:** 1,470 rows and 35 columns
- **Output column:** `Attrition`
- **Input columns:** all 34 other source columns
- **Missing values found:** 0
- **Exact duplicate rows found:** 0

## Files

- `HR_Employee_Attrition_Data_Wrangling.ipynb` — the guided notebook
- `HR-Employee-Attrition.csv` — the dataset used by the notebook

The notebook expects the CSV in the same folder as the notebook.

## Techniques demonstrated

- Inspecting rows, columns, data types, and summary statistics
- Checking for missing values and exact duplicate rows
- Identifying `Attrition` as the output and the remaining 34 columns as inputs
- Creating indicator columns
- Practicing normalization and standardization
- Grouping monthly income into example bins
- Applying a function to estimate annualized income

## Scope and limitations

The supplied dataset has no missing values or exact duplicate rows, so the notebook demonstrates data-quality checks but does not fix an actual missing-value or duplicate-row problem. Encoding, scaling, binning, and annualized income are practice demonstrations. The notebook does not train a model or establish that any factor causes attrition. It is not intended for employment decisions.

`EmployeeNumber` is an identifier. `EmployeeCount` and `StandardHours` are constant in this dataset; they remain in the input list to match the project specification.

## Dataset source and CC0

Dataset: [HR Analytics on Kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction). The Kaggle listing identifies the dataset as **CC0: Public Domain**. Dataset credit is included as a courtesy. See the [CC0 1.0 deed](https://creativecommons.org/publicdomain/zero/1.0/).

CC0 applies to the dataset only. It does not automatically apply to this notebook or README. This project does not add a separate license for those materials. It is an independent educational project and is not endorsed by Kaggle, IBM, or Coursera.
