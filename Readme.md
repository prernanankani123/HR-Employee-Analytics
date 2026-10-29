# HR Employee Analytics

HR Employee Analytics is a Python-based data analytics project that explores employee data to identify workforce trends and patterns in salary, job positions, departments, performance scores, employee satisfaction, and engagement. The project uses **Pandas, Matplotlib, and Seaborn** to perform data cleaning, data preprocessing, Exploratory Data Analysis (EDA), statistical analysis, and data visualization.

The analysis examines salary distribution, compares salaries across positions and departments, and explores relationships between selected employee attributes. The objective is to transform raw employee data into meaningful insights, strengthen practical data analysis skills, and demonstrate how data-driven insights can support informed Human Resource (HR) decision-making.

## Objectives
- Analyze salary distribution across job positions and departments.
- Explore employee performance, satisfaction, and engagement.
- Examine relationships between salary and other employee attributes.
- Identify workforce patterns using data visualization.
- Generate insights to support data-driven HR decisions.

## Business Questions
The analysis investigates questions such as:
- How are employee salaries distributed?
- How does salary vary across departments and employee status?
- Is employee performance associated with salary?
- Is there a visible relationship between employee engagement and salary?
- How does salary vary with the number of special projects handled?

## Tools and Skills
- **Python** — data analysis
- **Pandas** — data manipulation and cleaning
- **Matplotlib** — data visualization
- **Seaborn** — statistical charts and relationship analysis
- **Exploratory Data Analysis (EDA)** — identifying patterns and trends
- **Data preprocessing** — inspecting data types and missing values

## Dataset
- **Dataset Name:** HRDataset
- **Records:** 311 employees
- **Features:** 36 columns
- **Data:** Salary, Position, Department, PerformanceScore, EmpSatisfaction, EngagementSurvey, and other employee attributes.

## Project Workflow

### 1. Data Collection and Initial Exploration

- Loaded the HR employee dataset into Python using Pandas.
- Reviewed the dataset structure, including rows, columns, and column names.
- Examined data types and summary statistics to understand employee attributes.
- Identified important variables related to salary, job positions, departments, performance, and engagement.

### 2. Data Cleaning and Preprocessing

- Checked the dataset for missing values and duplicate records.
- Reviewed data types and converted date columns into the appropriate datetime format.
- Examined missing termination dates and other incomplete employee information.
- Prepared the dataset for further analysis while avoiding assumptions about missing values.

### 3. Exploratory Data Analysis (EDA)

- Examined the distribution of employee salaries.
- Compared salaries across different job positions and departments.
- Explored employee distribution across departments and employment statuses.
- Investigated the relationship between salary and performance scores.
- Analyzed employee engagement in relation to salary.
- Examined salary patterns based on the number of special projects handled.

### 4. Statistical Analysis and Visualization

- Used descriptive statistics to summarize numerical employee data.
- Created histograms to understand salary distribution.
- Used bar charts to compare employee groups and average salaries.
- Applied box plots to examine salary variation and potential outliers.
- Created scatter plots to explore relationships between numerical variables.
- Used correlation analysis and heatmaps to investigate relationships among selected numerical attributes.

### 5. Findings and Business Insights

- Identified differences in salary across job positions and departments.
- Observed a weak positive association between salary and performance score.
- Examined the relationship between employee engagement and salary.
- Identified the Production department as the largest workforce group in the dataset.
- Found that salary differences did not follow a consistent pattern across special project counts.
- Summarized the findings to support further investigation and data-informed HR decisions.
  
## Repository Contents
- `HR Employee Analytics.ipynb` — Jupyter Notebook containing the Python code, analysis, and visualizations.
- `HR Employee Analytics.html` — HTML version of the notebook for viewing the analysis and charts in a browser.
- `HRDataset.csv` — Employee dataset used for the analysis, if permitted to redistribute.
- `README.md` — Project documentation.
  
## Limitations and Future Scope
- The project focuses on exploratory analysis rather than predictive modeling.
- Observed relationships do not establish cause and effect.
- Future work could include employee attrition analysis, deeper workforce comparisons, and an interactive HR dashboard using Power BI.

## Conclusion

This project demonstrates the application of Python-based data analytics to examine employee salary patterns, job positions, departmental distribution, performance scores, and employee engagement. Using Pandas, Matplotlib, and Seaborn, the analysis involved data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to identify workforce trends and relationships between employee attributes. The findings highlight the value of data-driven analysis in understanding workforce patterns and supporting informed human resource (HR) decision-making.
  

