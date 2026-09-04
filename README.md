# Netflix Dataset – Data Cleaning and Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing a raw Netflix dataset using **Python and Pandas**.

The objective is to identify and handle missing values, duplicate records, inconsistent text formatting, and data type issues to prepare the dataset for further analysis.

## Tools Used

* Python
* Pandas
* Jupyter Notebook
* VS Code

## Files in This Repository

* `netflix.csv` – Original raw Netflix dataset
* `netflix_cleaned.csv` – Cleaned and preprocessed Netflix dataset
* `cleaning.ipynb` – Jupyter Notebook containing the data cleaning and preprocessing code
* `README.md` – Project documentation

## Data Cleaning and Preprocessing

The following steps were performed:

1. Checked the dataset shape and column names.
2. Checked for missing values.
3. Handled missing values in the dataset.
4. Checked for duplicate rows and removed duplicates.
5. Standardized column names to lowercase and uniform formatting.
6. Removed unnecessary spaces from text values.
7. Checked categorical values such as `type` and `rating`.
8. Converted the `date_added` column from string format to datetime format.
9. Checked and verified the data types of all columns.
10. Saved the cleaned dataset as `netflix_cleaned.csv`.

## Final Dataset

* Rows: 5,837
* Columns: 12
* Duplicate Rows: 0

Missing `date_added` values from the original dataset were retained as missing because no valid dates were available to replace them.

## Conclusion

The Netflix dataset was successfully cleaned and preprocessed using **Python and Pandas**. The cleaned dataset is now ready for further data analysis and visualization.

##  Author
**Samrina**
