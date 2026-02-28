# data_cleaning_python

🧹 Real-World Data Cleaning Project

This project focuses on cleaning and preparing a real-world Online Retail Dataset using Python.

Raw data is often messy and inconsistent. Before performing analysis or building machine learning models, it is essential to preprocess and clean the dataset.

This notebook demonstrates step-by-step data cleaning techniques used in real industry workflows.

📌 Project Objectives

Handle missing values

Standardize inconsistent text data

Convert incorrect data types

Remove duplicates

Clean numeric fields stored as text

Normalize country names

Filter and sort data for analysis

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Scikit-learn (SimpleImputer)

⚙️ Data Cleaning Steps Performed
1. Handling Missing Values

Used SimpleImputer to fill:

Product Name → Most Frequent

Brand → Most Frequent

Raw Weight → Median

Unit Price → Median

2. Cleaning Raw Weight Column

Problems:

Mixed formats (e.g. "500 gram", "250 Gram", etc.)

Solutions:

Converted text to lowercase

Replaced "gram" → "g"

Removed spaces

Converted to numeric values

3. Data Type Conversion

Converted:

OrderDate → DateTime format

4. Removing Duplicate Records

Duplicate entries were detected and removed to improve dataset quality.

5. Country Name Normalization

Standardized country names with different spellings such as:

Maroc → Morocco

Marruecos → Morocco

Argelia → Algeria

6. Data Filtering

Examples performed:

Filter by Brand

Filter by Price

Filter by Country

Multiple condition filtering using AND

7. Data Sorting

Sorted dataset by Unit Price for better analysis.

📊 Outcome

After cleaning:

✔️ Dataset became structured
✔️ Missing values handled
✔️ Text inconsistencies fixed
✔️ Ready for analysis or ML modeling

🚀 Future Improvements

Outlier Detection

Feature Engineering

Data Visualization

ML Model Integration

📁 File Included

data_cleaning_new.ipynb → Complete Data Cleaning Workflow
