# Data Pre-Processing for Baseline Analysis

## Objective
The goal of this project is to pre-process a housing dataset to establish and iteratively improve baselines for predicting house prices using machine learning. This involves cleaning the data, handling missing values, scaling numerical features, and applying various encoding techniques.

## Steps Involved
1. **Data Import and Exploration**:
   - Load the dataset and explore its structure.
   - Identify and handle missing values.
   
2. **Data Cleaning**:
   - Correct inaccuracies and standardize formats.

3. **Data Transformation**:
   - Normalize and scale numerical features.
   - Encode categorical variables.

4. **Baseline Establishment and Improvement**:
   - Implement initial baselines using simple models.
   - Evaluate and iteratively improve baselines with different feature engineering and encoding techniques.

## Variables Used
- **YearBuilt**: Original construction date
- **LotFrontage**: Linear feet of street connected to property
- **MasVnrType**: Masonry veneer type
- **OverallQual**: Rates the overall material and finish of the house
- **GrLivArea**: Above grade (ground) living area square feet
- **GarageCars**: Size of garage in car capacity
- **SalePrice**: Target variable for predicting house prices

## Tools and Technologies
- **Python**: For data pre-processing and analysis
- **Pandas** and **NumPy**: For data manipulation
- **Scikit-Learn**: For baseline modeling
- **Jupyter Notebook**: For interactive coding and documentation

## Outcome
The iterative process began with a baseline accuracy of 63.5% after addressing missing values, improving to 67.6% with feature encoding. Further enhancements using ordinal encoding and feature scaling led to a final accuracy of 87.3%.
