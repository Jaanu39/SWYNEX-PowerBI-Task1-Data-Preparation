# SWYNEX Power BI Internship – Task 1

## E-Commerce Customer Behavior – Data Preparation Using Power Query

### 📌 Project Overview

This project was completed as part of **Task 1 of my Power BI Internship at SWYNEX Technologies**.

The objective of this task was to prepare a business dataset for analysis by performing data cleaning, transformation, validation, and feature creation using **Power BI Power Query**.

### 📊 Dataset

**Dataset:** Online Shoppers Purchasing Intention Dataset  
**Source:** UCI Machine Learning Repository  
**Records:** 12,330 online shopping sessions  
**Features:** 18

The dataset contains information about online shopper behavior, including page visits, page duration, bounce rate, exit rate, page value, visitor type, traffic type, weekend activity, and revenue.

### 🛠️ Tools Used

- Power BI Desktop
- Power Query
- GitHub

### 🔄 Data Preparation

The following transformations were performed using Power Query:

1. Imported the dataset into Power BI.
2. Promoted the first row as column headers.
3. Verified and assigned appropriate data types.
4. Renamed columns to improve readability and consistency.
5. Checked data quality using **Column Quality** and **Column Distribution**.
6. Verified that the dataset contained no errors or empty values.
7. Applied **Trim** and **Clean** transformations to text fields such as `Month` and `Visitor_Type`.
8. Created a new column called `Total_Pages_Viewed`.
9. Created a new column called `Total_Page_Duration`.
10. Validated the final transformed dataset.

### 📈 Derived Columns

#### Total_Pages_Viewed

Calculates the total number of pages viewed during a shopping session.

```text
Administrative_Pages
+ Informational_Pages
+ Product_Related_Pages
```

#### Total_Page_Duration

Calculates the total time spent across the different page categories during a shopping session.

```text
Administrative_Duration
+ Informational_Duration
+ Product_Related_Duration
```

### ✅ Data Quality Validation

The final dataset was validated using Power Query's Column Quality feature.

- **Valid:** 100%
- **Errors:** 0%
- **Empty:** 0%

### 📷 Project Evidence

The repository contains screenshots demonstrating:

- Final data quality validation
- Power Query transformation steps

### 🎯 Outcome

The dataset was successfully cleaned, standardized, transformed, and prepared for further analysis in Power BI.

This task provided practical experience in:

- Data cleaning
- Power Query
- Data transformation
- Data quality validation
- Feature creation
- Preparing business data for analysis

### 📁 Repository Contents

```text
SWYNEX-PowerBI-Task1-Data-Preparation/
│
├── SWYNEX_Task1_Data_Preparation.pbix
├── data_quality_final.png
├── power_query_transformations.png
└── README.md
```

### 📚 Dataset Attribution

**Online Shoppers Purchasing Intention Dataset**

UCI Machine Learning Repository

**License:** CC BY 4.0
