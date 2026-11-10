# Task 3 – Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing a raw dataset using Python. Data cleaning is an important step in Data Analytics because raw datasets may contain missing values, duplicate records, incorrect data types, and inconsistent values.

## Objectives
- Identify missing values in the dataset.
- Detect and remove duplicate records.
- Handle inconsistent and incorrect data.
- Convert columns into appropriate data types.
- Prepare clean data for further analysis.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy

## Data Cleaning Process

### 1. Import Libraries
Imported Pandas and NumPy libraries for data manipulation and preprocessing.

### 2. Load Dataset
Loaded the dataset using the Pandas `read_csv()` function.

### 3. Understand the Dataset
Used `head()`, `info()`, and `describe()` to understand the dataset structure and statistical information.

### 4. Handle Missing Values
Identified missing values using `isnull().sum()` and handled them using suitable techniques such as mean, median, or mode imputation.

### 5. Remove Duplicate Records
Detected duplicate records using `duplicated()` and removed them using `drop_duplicates()`.

### 6. Data Type Conversion
Checked and converted columns into appropriate data types wherever necessary.

### 7. Verify Cleaned Dataset
Rechecked missing values, duplicate records, and data types to ensure data quality.

## Key Python Functions Used
- `pd.read_csv()`
- `df.head()`
- `df.info()`
- `df.describe()`
- `df.isnull().sum()`
- `df.duplicated().sum()`
- `df.drop_duplicates()`
- `df.dtypes`

## Expected Outcomes
- A clean and structured dataset.
- Reduced missing and duplicate records.
- Consistent data types.
- Improved data quality.
- Dataset ready for Exploratory Data Analysis and further processing.

## Conclusion
Data cleaning and preprocessing help improve the quality and reliability of datasets. This task demonstrates the use of Python and Pandas to prepare raw data for accurate analysis and meaningful insights.

## Author
B.Tech Computer Science and Engineering Student

## Project Category
Data Analytics | Data Cleaning | Data Preprocessing
