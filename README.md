# Titanic-EDA-Internship-Task-2
Exploratory Data Analysis (EDA) of the Titanic dataset completed as Internship Task 2. This project investigates passenger demographics, survival patterns, data quality issues, statistical relationships, and key factors influencing survival using Python, Pandas, Matplotlib, and Seaborn.
# Titanic Dataset - Exploratory Data Analysis (EDA)

## Internship Task 2

This repository contains an Exploratory Data Analysis (EDA) project performed on the Titanic dataset as part of an internship assignment.

The objective of this analysis is to explore the dataset, understand its structure, identify trends and patterns, detect anomalies, evaluate data quality, and validate assumptions using statistical analysis and visualizations.

---

## Project Objectives

- Explore the Titanic dataset structure.
- Understand passenger demographics.
- Identify factors affecting passenger survival.
- Detect missing values and data quality issues.
- Find trends, patterns, and anomalies.
- Validate assumptions using statistical methods.
- Generate insights and recommendations.

---

## Dataset Description

The Titanic dataset contains passenger information including:

- Passenger ID
- Survival Status
- Passenger Class
- Name
- Sex
- Age
- Fare
- Cabin
- Ticket Information
- Embarkation Details

The dataset is widely used for data analysis and machine learning practice.

---

## Business Questions

### Survival Analysis

1. Does gender affect survival?
2. Does passenger class affect survival?
3. Are younger passengers more likely to survive?
4. Does ticket fare impact survival chances?
5. Does family size influence survival?

### Passenger Demographics

1. What is the age distribution of passengers?
2. What is the male-to-female ratio?
3. Which passenger class contains the most passengers?

### Data Quality

1. Are there missing values?
2. Are there duplicate records?
3. Are there outliers in Age and Fare?
4. Are data types correctly assigned?

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Imported dataset using Pandas.
- Displayed initial records.
- Reviewed dataset dimensions.

### 2. Data Understanding

- Checked dataset shape.
- Examined columns.
- Verified data types.

### 3. Data Quality Assessment

- Missing value analysis.
- Duplicate record detection.
- Descriptive statistics review.

### 4. Exploratory Data Analysis

- Survival analysis by gender.
- Survival analysis by passenger class.
- Age distribution analysis.
- Fare distribution analysis.
- Outlier detection.

### 5. Statistical Validation

- Hypothesis testing.
- Survival impact assessment.
- Class and gender relationship analysis.

---

## Key Findings

### Gender Impact

- Female passengers had significantly higher survival rates than male passengers.

### Passenger Class Impact

- First-class passengers survived more frequently than third-class passengers.

### Age Distribution

- Most passengers were between 20 and 40 years old.

### Fare Distribution

- Fare distribution is highly right-skewed.
- A small number of passengers paid exceptionally high fares.

### Outliers

Detected outliers in:

- Fare
- Age

Examples include:

- Babies under 1 year old
- Elderly passengers above 70 years old
- Passengers with extremely high ticket fares

---

## Data Quality Issues

- 86 missing values in Age.
- 327 missing values in Cabin.
- 1 missing value in Fare.
- Extreme Fare outliers present.

### Recommendation

- Remove Cabin column due to excessive missing values.
- Impute missing Age values.
- Impute missing Fare values.
- Handle outliers before predictive modeling.

---

## Statistical Conclusions

- Gender significantly affects survival.
- Passenger class significantly affects survival.
- Age does not show a statistically significant effect on survival in this dataset.

---

## Screenshots

Store all project screenshots inside the `screenshots/` folder.

Example:

```
screenshots/
├── dataset-overview.png
├── missing-values.png
├── survival-by-gender.png
├── passenger-class-analysis.png
├── age-distribution.png
├── fare-distribution.png
└── hypothesis-testing-results.png
```

---


## Final Conclusion

This project successfully explored the Titanic dataset and identified important factors affecting passenger survival. Gender and passenger class were found to be strong indicators of survival, while age showed limited statistical significance. The analysis also revealed several data quality issues that should be addressed before developing predictive machine learning models.

---

## Author

Muhammad Usama

Internship Task 2 – Exploratory Data Analysis (EDA)
