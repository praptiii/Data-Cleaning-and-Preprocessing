# Data Cleaning and Preprocessing – Task 1

## Dataset
I have used the **Customer Personality Analysis** dataset (source: Kaggle).

- `original_dataset.csv` – Raw dataset with inconsistencies and missing values.
- `cleaned_dataset.csv` – Final version after applying cleaning and preprocessing.
- `customer.ipynb` – Python code used for cleaning the dataset.

## Cleaning Steps Performed

The following steps were applied using Python and pandas:

1. **Identifying and Handling Missing Values** - Dropped the rows with missing values in the `Income` column.

2. **Removing Duplicate Rows** - Eliminated any duplicate rows to ensure data consistency.
   
3. **Standardized Text Values** - Cleaned `education` and `marital_status` values (lowercased and trimmed whitespace).

4. **Converted Date Formats** - Parsed the `dt_customer` column to `datetime` objects.

5. **Standardized Column Names** - Renamed all column headers to lowercase with underscores (e.g., `Year_Birth` → `year_birth`).

6. **Corrected Data Types** - Converted `income` to `float` and `year_birth` to `int`.
