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
- How does employee position affect salary levels?
- Do employees with higher engagement scores tend to earn more?
- How does salary distribution vary across departments and employment status?
- What percentage of employees belong to each department category?
- How does salary vary with the number of special projects handled?
- Is Salary correlated with employee performance score?
- How is Salary related to other numerical employee factors?
  
## Tools and Skills
- **Python** — data analysis
- **Pandas** — data manipulation and cleaning
- **Matplotlib** — data visualization
- **Seaborn** — statistical charts and relationship analysis
- **Exploratory Data Analysis (EDA)** — identifying patterns and trends
- **Data preprocessing** — inspecting data types and missing values

## Dataset
- **Dataset Name:** HRDataset
- **Source:** Kaggle
- **Dataset Link:** [HRDataset](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set)
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

## Visualizations

The following visualizations help explore employee salary patterns, departmental distribution, and relationships between selected employee attributes.

### 1. Salary Distribution

A histogram is used to understand how employee salaries are distributed across the dataset.
<img width="457" height="253" alt="image" src="https://github.com/user-attachments/assets/f7d41a27-0772-46be-aec3-9bf0a42a93f5" />

**Observation:**
Employee salaries are spread across a range of values, indicating differences in compensation among employees.

### 2. Salary vs Position
A box plot compares employee salaries across different job positions.

<img width="453" height="298" alt="image" src="https://github.com/user-attachments/assets/726b8697-47db-491b-9af3-d4861585447d" />


**Observation:**
Salary levels vary across job positions, suggesting that compensation differs depending on the role.

### 3. Department-wise Employee Distribution
A pie chart shows the percentage of employees belonging to each department.
<img width="437" height="301" alt="image" src="https://github.com/user-attachments/assets/ec4c1442-7766-44ac-9ea6-1506fbdce641" />

**Observation:**
The Production department represents approximately 67.2% of the employees in the dataset, making it the largest department by employee count.

### 4. Correlation Heatmap
A heatmap displays correlations between selected numerical employee attributes.

<img width="389" height="311" alt="image" src="https://github.com/user-attachments/assets/d6d9abb9-72bf-4c97-a737-0f435537d90a" />


**Observation:**
The heatmap helps identify positive and negative relationships among numerical variables. Correlation indicates association and does not necessarily imply causation.

## Key Findings
- Employee salaries vary across job positions and departments.
- Salary has a weak positive correlation with performance score in this dataset.
- Employee engagement does not show a strong visible relationship with salary.
- The Production department represents the largest workforce group in the dataset.
- Salary differences across special project counts do not follow a consistent pattern.

## Business Insights
- Salary comparison: Differences across positions and departments show why salary should be reviewed in the context of employee role and department.
- Performance and salary: The weak positive correlation suggests that performance score alone does not explain salary differences in this dataset.
- Employee engagement: The lack of a strong visible relationship with salary suggests that engagement should be explored alongside other workplace factors rather than inferred from salary alone.
- Workforce distribution: The large share of employees in Production highlights the importance of understanding department-level workforce composition.
- Special projects: The inconsistent salary pattern across special project counts suggests that this variable alone may not explain salary differences.
  
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
  

