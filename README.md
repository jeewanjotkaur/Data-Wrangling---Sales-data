**Cafe Sales Data Wrangling Project**

**Project Overview**

This project demonstrates data wrangling and preprocessing skills using a publicly available café sales dataset. The focus is cleaning messy raw data, standardizing formats, handling missing values, and preparing the dataset for further analysis.

Note: This project does not include analysis or modeling; it is purely focused on data wrangling.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Dataset**

**Source**: Kaggle – Cafe Sales Dataset

**License**: CC BY-SA 4.0

**Link**: [Kaggle Cafe Sales Dataset](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

The original dataset contained inconsistencies such as:

* Missing or blank values

* Mixed date formats

* Inconsistent category labels

* Duplicate entries
  
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Project Structure**

    DATA WRANGLING - SALES DATA/
  
    ├── data/
    
        ├── raw_cafe_sales.csv        # Original dataset from Kaggle
    
        └── cleaned_cafe_sales.csv    # clean dataset
    
    
    ├── notebooks/
    
        └── DataWrangling.ipynb       # Jupyter notebook with wrangling steps

    
    └── README.md                     # Project documentation


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Tools & Libraries**


Python 3.x

Pandas – data manipulation and cleaning

NumPy – numerical operations

OpenPyXL / CSV – handling spreadsheet data

Jupyter Notebook – documenting cleaning steps


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Data Wrangling Steps**


**Inspect data** – checked column names, data types, missing values

**Handle missing values** – filled, dropped, or standardized placeholders

**Standardize formats** – dates, text capitalization, numeric types

**Fix duplicates** – removed redundant rows

**Normalize categories** – unified inconsistent labels (e.g., "Espresso" vs "espresso")

**Export cleaned dataset** – saved as cleaned_cafe_sales.csv for future use


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**How to Use**


Clone the repository

Navigate to the project folder:

cd DATA wRANGLING - SALES DATA

Open the Jupyter notebook:

jupyter notebook notebooks/DataWrangling.ipynb

Run the notebook to see the data cleaning steps applied.
