# Human Resources Data Analytics and Predictive Modeling

**DEPI Graduation Project**

## 1. Project Name

**Human Resources Data Analytics and Predictive Modeling**

## 2. Project Idea

The project aims to analyze Human Resources (HR) data to understand workforce characteristics, employee performance, job satisfaction, and employee attrition. It transforms raw HR data into meaningful insights using data cleaning, database management, exploratory data analysis, and machine learning techniques.

The project follows an end-to-end data analytics workflow using PostgreSQL, Python, pandas, scikit-learn, and Tableau. It focuses on identifying workforce trends, evaluating employee performance, exploring factors associated with attrition, and presenting findings through interactive dashboards to support data-driven HR decision-making.

### Project Objectives

- Build a structured relational database for HR data.
- Clean, preprocess, and validate datasets.
- Analyze employee demographics, salaries, departments, and job roles.
- Investigate performance ratings, employee satisfaction, and attrition.
- Develop suitable predictive models and evaluate their performance.
- Create an interactive Tableau dashboard.
- Provide actionable insights and recommendations based on data analysis.

## 3. Team Members

Add the full names of all team members below.

| No. | Team Member Name |
|---:|---|
| 1 | [Full Name] |
| 2 | [Full Name] |
| 3 | [Full Name] |
| 4 | [Full Name] |
| 5 | [Full Name] |

## 4. Work Plan

The project is organized into four weeks, following a structured data analytics workflow.

### Week 1: Data Modeling, Cleaning, and Preprocessing

**Objective:** Prepare reliable and analysis-ready HR datasets.

Tasks:
- Understand the dataset and its metadata.
- Inspect data types, missing values, duplicate records, and data quality issues.
- Design and implement a relational database using PostgreSQL.
- Define primary keys, foreign keys, and table relationships.
- Import the datasets and validate the database structure.
- Clean and preprocess the data using Python and pandas.
- Document the data model and data quality results.

**Deliverables:**
- PostgreSQL database and SQL scripts.
- Entity Relationship Diagram (ERD).
- Cleaned datasets.
- Data quality report and cleaning log.
- Data preprocessing Jupyter Notebook.

### Week 2: Exploratory Data Analysis (EDA)

**Objective:** Discover meaningful patterns and answer HR business questions.

Tasks:
- Analyze employee demographics and workforce distribution.
- Explore salary, departments, job roles, and years of service.
- Analyze performance ratings and satisfaction levels.
- Investigate employee attrition patterns.
- Use SQL and Python to answer business questions.
- Create visualizations and document key findings.

**Deliverables:**
- SQL analysis queries.
- Exploratory data analysis notebook.
- Charts, findings, and analytical summaries.

### Week 3: Predictive Modeling and Evaluation

**Objective:** Apply machine learning to investigate suitable HR prediction problems.

Tasks:
- Define an appropriate prediction target based on data availability.
- Select relevant features and prepare the modeling dataset.
- Split the data into training and testing sets.
- Establish a baseline and train suitable machine learning models.
- Evaluate model performance using appropriate metrics.
- Interpret the results and document limitations.

**Deliverables:**
- Predictive modeling notebook.
- Trained and evaluated model.
- Model performance results and visualizations.
- Summary of findings and limitations.

### Week 4: Tableau Dashboard and Final Presentation

**Objective:** Communicate project findings through interactive visualizations and a professional presentation.

Tasks:
- Select and validate the final KPIs.
- Prepare analysis-ready data for Tableau.
- Design and build an interactive HR dashboard.
- Validate charts, filters, and KPI calculations.
- Summarize the most important findings.
- Prepare the final report and presentation.

**Deliverables:**
- Interactive Tableau dashboard.
- Final project report.
- Final presentation.
- Project documentation and organized repository.

## 5. Roles & Responsibilities

The following is a proposed division of responsibilities for a five-member team. The team should update the names and assignments to reflect the actual work distribution.

| Team Member | Proposed Role | Responsibilities |
|---|---|---|
| Member 1 | Data Engineer & Database Developer | Database design, PostgreSQL tables, SQL scripts, primary and foreign keys, data imports, and data integrity checks. |
| Member 2 | Data Cleaning & Preprocessing Analyst | Dataset profiling, missing value and duplicate checks, data cleaning, preprocessing, and data quality documentation using Python and pandas. |
| Member 3 | Data Analyst | Exploratory data analysis, SQL queries, HR business questions, statistical summaries, and analytical visualizations. |
| Member 4 | Machine Learning Engineer | Feature preparation, model selection, training, evaluation, and interpretation of predictive results. |
| Member 5 | Business Intelligence Developer & Project Coordinator | Tableau dashboard, KPI design, final report, presentation, project organization, and coordination of deliverables. |

### Shared Responsibilities

All team members are responsible for:
- Understanding the project objectives and dataset.
- Reviewing and validating the team's results.
- Maintaining clear documentation.
- Using version control where appropriate.
- Communicating progress and supporting integration of the final deliverables.
- Following responsible data handling and privacy practices.

## 6. Key Performance Indicators (KPIs)

The project will investigate the following HR indicators, subject to the available data and validation of their definitions.

| KPI | Definition | Business Purpose |
|---|---|---|
| Total Employees | Count of unique employees. | Understand workforce size. |
| Attrition Rate | Employees who left divided by the defined employee population, multiplied by 100. | Measure employee turnover. |
| Average Salary | Mean employee salary. | Understand compensation patterns. |
| Average Employee Age | Mean age of employees. | Describe workforce demographics. |
| Average Years at Company | Mean employee tenure in years. | Understand employee retention and experience. |
| Department Headcount | Number of employees in each department. | Compare workforce distribution across departments. |
| Average Performance Rating | Mean of the selected, documented performance rating measure. | Summarize performance evaluation results. |
| Average Job Satisfaction | Mean job satisfaction score. | Understand reported employee satisfaction. |
| Average Environment Satisfaction | Mean environment satisfaction score. | Examine employee perceptions of the work environment. |
| Average Work-Life Balance | Mean work-life balance score. | Assess reported work-life balance. |
| Training Participation | Employees who took training opportunities, or training participation according to a defined denominator. | Understand training engagement. |
| Promotion and Career Progression | Distribution of years since last promotion and years in the most recent role. | Examine career development patterns. |

### KPI Calculation Notes

- Attrition rate must use a clearly defined employee population and a consistent attrition-status definition.
- Satisfaction and rating scores should be interpreted according to the dataset's metadata and rating scales.
- Performance records may contain multiple reviews per employee. Employee-level and review-level metrics must not be mixed without an explicit aggregation rule.
- KPIs describe patterns in the available dataset and do not establish causation.
- Any prediction model must be evaluated separately from descriptive KPIs.

## 7. Instructor

**Instructor Name:** [Enter Instructor's Full Name]

**Program:** DEPI — Digital Egypt Pioneers Initiative

**Project Type:** Graduation Project

## 8. Project Files

The repository is organized as follows:

```text
DEPI_HR_Analysis/
│
├── data/
│   ├── raw/
│   │   ├── Employee.csv
│   │   ├── PerformanceRating.csv
│   │   ├── EducationLevel.csv
│   │   ├── RatingLevel.csv
│   │   └── SatisfiedLevel.csv
│   │
│   ├── processed/
│   │   ├── Employee_Cleaned.csv
│   │   ├── PerformanceRating_Cleaned.csv
│   │   ├── EducationLevel_Cleaned.csv
│   │   ├── RatingLevel_Cleaned.csv
│   │   └── SatisfiedLevel_Cleaned.csv
│   │
│   └── reports/
│       ├── Data_Quality_Report.csv
│       └── Cleaning_Log.csv
│
├── notebooks/
│   ├── 01_Data_Model_Cleaning_Preprocessing.ipynb
│   ├── 02_Exploratory_Data_Analysis.ipynb
│   └── 03_Predictive_Modeling.ipynb
│
├── sql/
│   ├── 01_Create_Tables.sql
│   └── 02_Data_Quality_Checks.sql
│
├── docs/
│   ├── Data_Dictionary.xlsx
│   └── Data_Model_Documentation.md
│
├── visualizations/
│   └── HR_Data_Model_ERD.png
│
├── dashboard/
│   └── Tableau_Dashboard.twbx
│
├── reports/
│   └── Final_Project_Report.pdf
│
├── presentation/
│   └── Final_Presentation.pptx
│
├── TEAM.txt
└── README.md
```

**Note:** The structure above represents the planned organization of the project. Files should be added as they are created and validated. Do not create empty or placeholder deliverables merely to imply that a task is complete.

### File Descriptions

- **`data/raw/`** — Original source datasets preserved without modification.
- **`data/processed/`** — Cleaned datasets prepared for analysis.
- **`data/reports/`** — Data quality results and documented cleaning actions.
- **`notebooks/`** — Python notebooks for preprocessing, exploratory analysis, and predictive modeling.
- **`sql/`** — SQL scripts for database creation and data validation.
- **`docs/`** — Data dictionary and data model documentation.
- **`visualizations/`** — ERD and other project visualizations.
- **`dashboard/`** — Final Tableau dashboard file.
- **`reports/`** — Final written project report.
- **`presentation/`** — Final presentation slides.
- **`TEAM.txt`** — Team member information and, if needed, role assignments.

## 9. Tools and Technologies

| Category | Tools |
|---|---|
| Database Management | PostgreSQL, pgAdmin 4 |
| Programming | Python |
| Data Cleaning and Analysis | pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | scikit-learn |
| Business Intelligence | Tableau |
| Development Environment | Jupyter Notebook |
| Version Control | Git, GitHub |
| Documentation | Markdown, Excel, PowerPoint |

## 10. Expected Outcomes

By the end of the project, the team aims to deliver:

1. A structured and validated relational HR database.
2. Documented data cleaning and preprocessing workflows.
3. An exploratory analysis of employee and performance patterns.
4. An evaluated predictive model for a suitable HR prediction problem.
5. An interactive Tableau dashboard presenting key HR KPIs.
6. A final report containing findings, limitations, and data-driven recommendations.
7. A well-organized project repository with reproducible analysis files.

## 11. Project Status

- [x] Create PostgreSQL database and five relational tables.
- [x] Import the five CSV datasets.
- [x] Verify imported row counts.
- [x] Verify eight foreign key constraints.
- [x] Generate the initial ERD in pgAdmin.
- [ ] Complete and document the preprocessing notebook and cleaned outputs.
- [ ] Finalize the data quality report and cleaning log.
- [ ] Complete exploratory data analysis.
- [ ] Develop and evaluate the predictive model.
- [ ] Complete the Tableau dashboard.
- [ ] Finalize the project report and presentation.

## 12. Conclusion

This project demonstrates an end-to-end HR data analytics workflow, from relational database design and data preprocessing to exploratory analysis, predictive modeling, and business intelligence reporting. Its goal is to transform structured HR data into reliable, interpretable insights that support informed workforce analysis and decision-making.
