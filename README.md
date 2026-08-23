Data Preprocessing - Machine Learning Assignment
​This repository contains the Python code and implementation for a complete Data Preprocessing Pipeline as part of a Machine Learning assignment. The workflow covers everything from raw data cleaning to feature scaling using Jupyter Notebook.
​🛠️ Project Workflow & Steps
​Data Loading & Exploration:
​Loaded the employee dataset (employee.csv).
​Inspected data structures, unique values, and identified missing records.
​Data Cleaning & Handling Missing Values:
​Handled missing values (NaNs) by filling numerical columns with the median and categorical columns with the mode.
​Removed duplicate rows to ensure data integrity.
​Exploratory Data Analysis (EDA) & Visualization:
​Filtered data based on specific conditions (e.g., age and salary filters).
​Generated visualizations using Seaborn and Matplotlib (such as scatter plots and count plots) to analyze distributions and employee counts by location.
​Data Encoding:
​Converted categorical variables into numerical representations using One-Hot Encoding (pd.get_dummies) and Label Encoding.
​Feature Scaling:
​Standardized and normalized numerical features using:
​StandardScaler (Z-score normalization)
​MinMaxScaler (Min-Max normalization)
​💻 Technologies Used
​Python
​Jupyter Notebook
​Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
​🚀 How to Run the Code
​Clone this repository or download the .ipynb file.
​Ensure you have Jupyter Notebook and the required libraries installed (pandas, numpy, scikit-learn, matplotlib, seaborn).
​Place your dataset (employee.csv) in the same directory.
​Run the cells sequentially to see the step-by-step data preprocessing results.
