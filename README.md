## Employee Data Analysis

This project performs Exploratory Data Analysis (EDA) on an employee dataset using Python, primarily leveraging the Pandas, NumPy, Matplotlib, and Seaborn libraries within a Jupyter Notebook environment.

### Dataset 

The analysis is based on the `Employee.csv` dataset which includes information about employees, such as:

  * Demographics (Age, Gender, Ethnicity)
  * Job Details (Job Title, Department, Business Unit)
  * Employment Information (Hire Date)
  * Compensation (Annual Salary, Bonus %)
  * Location (Country, City)

### Objectives 

  * Load, inspect, and understand the structure of the employee data.
  * Clean and preprocess the data (handle duplicates, clean data types, rename/drop columns).
  * Perform feature engineering (extracting Year and Month from Hire Date).
  * Conduct descriptive statistical analysis.
  * Visualize data distributions, relationships, and trends using histograms, box plots, pie charts, heatmaps, bar charts, line plots, and scatter plots.
  * Analyze key aspects like:
      * Demographic distributions (Age, Gender, Ethnicity).
      * Compensation patterns (Salary distribution, relation to Bonus %).
      * Departmental and Job Title breakdowns.
      * Geographical distribution (Country, City).
      * Hiring trends over time.

### Tools Used 🛠️

  * Python 3
  * Jupyter Notebook
  * Pandas (Data manipulation and analysis)
  * NumPy (Numerical operations)
  * Matplotlib (Plotting)
  * Seaborn (Enhanced data visualization)

### Analysis Steps

1.  **Data Loading & Initial Exploration:** Imported the dataset and performed initial checks (`.head()`, `.tail()`, `.info()`, `.shape`, `.dtypes`, `.describe()`).
2.  **Data Cleaning:**
      * Checked and handled duplicate entries.
      * Renamed columns for consistency.
      * Dropped irrelevant columns (`EEID`, `Exit Date`).
      * Cleaned and converted `Annual_Salary` and `Bonus_%` columns to numeric types.
      * Converted `Hire_Date` to datetime objects.
3.  **Feature Engineering:** Extracted `Hire_Year` and `Hire_Month` from the `Hire_Date`.
4.  **EDA & Visualization:** Generated various plots to understand:
      * Distributions of Age and Annual Salary.
      * Counts and proportions of Gender, Ethnicity, Departments, Job Titles.
      * Relationships between variables (e.g., Gender vs. Ethnicity, Bonus vs. Salary).
      * Average salaries across different groups (Gender, Department).
      * Hiring trends across years and months.
      * Employee distribution across countries and cities.

### How to Use 🚀

1.  Clone the repository.
2.  Ensure you have Python and the required libraries installed (`pandas`, `numpy`, `seaborn`, `matplotlib`). You can usually install them via pip:
    ```bash
    pip install pandas numpy seaborn matplotlib jupyter
    ```
3.  Open and run the `Project1.ipynb` notebook in a Jupyter environment.
