# Theory Report

## Missing Values
Missing values happen when some patient details are not recorded. In healthcare data, this may happen because of manual entry mistakes, skipped lab tests, or incomplete forms.

## Imputation Techniques Used
- Simple Imputer (Numerical): replaces missing numerical values using the median.
- Simple Imputer (Categorical): replaces missing region values using the most frequent category.
- Most Frequent Imputation: replaces missing gender values with the mode.
- Missing Indicator + Random Sample Imputation: adds a binary flag for missingness and fills values using random samples from observed data.
- KNN Imputer: estimates missing values using similar patient records.
- MICE: fills missing values by modeling relationships between multiple variables.

## Outliers
Outliers are extremely high or low values that do not follow the usual pattern. In medical datasets, they may appear because of measurement errors, device problems, or incorrect data entry.

## Outlier Handling Methods Used
- Z-score Method: removes records with values far from the mean.
- IQR Method: removes records outside the interquartile range limits.
- Percentile Method: caps values below the 1st percentile and above the 99th percentile.
- Winsorization: caps extreme values while keeping all records in the dataset.

## Final Note
After handling missing values and outliers, the dataset becomes more reliable for machine learning. A few simple engineered features can also improve the usefulness of the cleaned data.
