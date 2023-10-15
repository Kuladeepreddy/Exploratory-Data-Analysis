# Project Title

## Introduction

This project involves the analysis of health-related data from the National Health and Nutrition Examination Survey (NHANES). The dataset includes information about respondents' smoking habits, gender, age, education level, weight, height, and BMI. The analysis aims to explore relationships and patterns within the data.

## 1. Retrieving the Data

The dataset is loaded from a CSV file named 'NHANES.csv', and relevant columns are extracted for further analysis. The selected columns include SEQN, SMQ020, RIAGENDR, RIDAGEYR, DMDEDUC2, BMXWT, BMXHT, and BMXBMI.

## 2. Data Cleaning

### Duplicates
No duplicate rows are found in the dataset.

### Missing Values
Some columns have missing values. Rows with missing values are dropped, resulting in a cleaned dataset with 5406 entries.

### Outliers
Outliers are identified and removed for columns 'height', 'weight', and 'bmi' using the IQR (Interquartile Range) method.

## 3. Exploratory Data Analysis

### Descriptive Statistics
Basic statistics (count, mean, standard deviation, min, 25th percentile, median, 75th percentile, max) for numerical columns ('age', 'weight', 'height', 'bmi') are displayed.

### Visualizations
Histograms and boxplots are created to visualize the distribution of age, weight, height, and BMI in the cleaned dataset.

## 4. Results

After data cleaning and outlier removal, the dataset contains 5255 entries. The visualizations provide insights into the distribution of key variables, revealing patterns and potential relationships.
## Data Overview

The original dataset contains 5735 entries with 28 columns. After isolating relevant columns, the selected dataset consists of 8 columns: SEQN, SMQ020, RIAGENDR, RIDAGEYR, DMDEDUC2, BMXWT, BMXHT, and BMXBMI.

### Data Cleaning

- **Duplicates:** No duplicate rows were found in the dataset.
  
- **Missing Values:** Some columns have missing values. Rows with missing values are dropped, resulting in a cleaned dataset with 5406 entries.

- **Outliers:** Outliers in 'height', 'weight', and 'BMI' are removed using the IQR method, resulting in a final dataset with 5255 entries.

## Descriptive Statistics

### Cleaned Dataset Summary

The cleaned dataset has 5255 entries and 8 columns. Below are the basic statistics for numerical columns:

- **Age:**
  - Count: 5255
  - Mean: 49.39
  - Standard Deviation: 17.64
  - Min: 20
  - 25th Percentile: 34
  - Median: 49
  - 75th Percentile: 64
  - Max: 80

- **Weight:**
  - Count: 5255
  - Mean: 81.72
  - Standard Deviation: 21.78
  - Min: 32.4
  - 25th Percentile: 66.3
  - Median: 78.5
  - 75th Percentile: 93.2
  - Max: 198.9

- **Height:**
  - Count: 5255
  - Mean: 166.06
  - Standard Deviation: 10.11
  - Min: 129.7
  - 25th Percentile: 158.6
  - Median: 165.9
  - 75th Percentile: 173.4
  - Max: 202.7

- **BMI:**
  - Count: 5255
  - Mean: 29.54
  - Standard Deviation: 7.08
  - Min: 14.5
  - 25th Percentile: 24.5
  - Median: 28.5
  - 75th Percentile: 33.2
  - Max: 67.3




## Files

- `NHANES.csv`: The original dataset.
- `Analysis.ipynb`: Jupyter Notebook containing the code and analysis.
- `README.md`: Documentation providing an overview of the project.

## Usage

1. Ensure you have the required Python libraries installed (NumPy, Pandas, Matplotlib, Seaborn).
2. Run the Jupyter Notebook (`Analysis.ipynb`) to reproduce the analysis.

## Acknowledgments

- The dataset used in this analysis is sourced from the National Health and Nutrition Examination Survey (NHANES).

## License

This project is licensed under the [MIT License](LICENSE).

