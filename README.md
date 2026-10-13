# Indian Crime Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing crime data in India using Python. It uses Exploratory Data Analysis (EDA) and data visualization to understand crime patterns across cities, years, victim demographics, crime domains, weapons used, and case closure status.

The objective is to transform raw crime data into meaningful insights that can help improve understanding of crime trends and support data-driven decision-making.

## 🎯 Objectives

- Analyze the overall distribution of recorded crime cases.
- Identify the cities with the highest and lowest recorded crime counts.
- Examine yearly crime trends.
- Understand crime distribution across different victim age groups.
- Analyze victim gender distribution.
- Explore the relationship between victim gender and crime domain.
- Identify the most common crime descriptions across cities.
- Determine the most frequently recorded weapon in the violent crime domain.
- Analyze the distribution of closed and not-closed cases.

## 📂 Dataset Description

**Dataset file:** `crime_dataset_india.csv`

The dataset contains 40,160 records and 15 original columns.

The dataset includes information related to crime reports, dates and times of occurrence, cities, crime descriptions, victim demographics, weapons used, police deployment, and case closure status.

### Important Dataset Columns

| Column | Description |
|---|---|
| Report Number | Identifier associated with a crime report |
| Date Reported | Date on which the crime was reported |
| Date of Occurrence | Date on which the crime occurred |
| Time of Occurrence | Recorded time and date of occurrence |
| City | City associated with the crime record |
| Crime Code | Code assigned to the crime |
| Crime Description | Description of the crime |
| Victim Age | Age of the victim |
| Victim Gender | Gender of the victim |
| Weapon Used | Weapon recorded in the crime report |
| Crime Domain | Classification of the crime |
| Police Deployed | Number of police personnel deployed |
| Case Closed | Recorded case closure status |
| Date Case Closed | Date on which the case was closed, where available |

## 🛠️ Tools and Technologies

- **Python** – Programming and analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive coding and analysis

## 🔍 Project Workflow

### 1. Data Loading and Exploration

- Imported the required Python libraries.
- Loaded the crime dataset using Pandas.
- Examined the dataset structure, columns, and sample records.
- Generated descriptive statistics.
- Checked for missing values.

### 2. Data Preparation

- Converted the occurrence date and time into a datetime format.
- Extracted the year from the occurrence date.
- Created age groups to categorize victims for demographic analysis.

### 3. Exploratory Data Analysis

The analysis explores the following areas:

- Total recorded crime cases.
- Top 10 cities by crime count.
- City with the lowest recorded crime count.
- Year-wise crime trends.
- Crime distribution by victim age group.
- Crime domain distribution.
- Victim gender distribution.
- Relationship between victim gender and crime domain.
- Top three crime descriptions in each city.
- Most frequently recorded weapon in the violent crime domain.
- Percentage of cases marked as closed or not closed.

## 📊 Data Visualization

The project uses charts to make crime patterns easier to understand.

| Visualization | Purpose |
|---|---|
| Bar Chart | Compare the top 10 cities by recorded crime count |
| Line Chart | Examine year-wise crime trends |
| Pie Chart | Show the distribution of victim age groups |
| Bar Chart | Compare crime domains |
| Pie Chart | Display victim gender distribution |
| Stacked Bar Chart | Compare crime domains across victim genders |
| Pie Chart | Visualize case closure status |

## 📁 Repository Structure

```text
Indian-Crime-Analysis/
│
├── Project_Crime.ipynb
├── crime_dataset_india.csv
└── README.md
```

## ⚙️ Installation and Setup

### Step 1: Clone the repository

```bash
git clone https://github.com/Kkhavar513/Indian-Crime-Analysis.git
```

### Step 2: Navigate to the project folder

```bash
cd Indian-Crime-Analysis
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the analysis

Open `Project_Crime.ipynb` and execute the cells in sequence.

Ensure that `crime_dataset_india.csv` is available in the same folder as the notebook.

## 💡 Key Learnings

- Gained practical experience in data cleaning and preprocessing.
- Applied Pandas and NumPy for data analysis.
- Used exploratory data analysis to investigate crime patterns.
- Created visualizations to communicate findings effectively.
- Explored demographic, geographic, and case-outcome information.
- Practiced translating data into meaningful analytical questions.

## ⚠️ Limitations

- The analysis reflects the available dataset and may not represent all crimes occurring in India.
- Recorded crime counts do not necessarily indicate the actual crime rate of a city.
- Missing or inconsistent data may affect analytical results.
- Case closure status alone does not indicate whether a case resulted in a conviction or how effectively it was investigated.
- The analysis identifies patterns and associations but does not establish causation.

## 🚀 Future Scope

- Develop an interactive crime analytics dashboard using Power BI or Tableau.
- Perform more detailed time-series analysis of crime trends.
- Explore geographic crime patterns through maps.
- Apply machine learning methods to investigate patterns in crime data.
- Analyze case closure duration and other case outcome indicators.

## 👩‍💻 Author

**Khushi Kharvar**

PGDM in Data Science & Analytics

**Areas of Interest:** Data Analytics, Python, Exploratory Data Analysis, and Data Visualization.

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback.
