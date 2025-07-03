# Task-5
Titanic Dataset - Visual and Statistical Exploration
📂 Project Overview
This project is a comprehensive data exploration and analysis of the Titanic dataset using Python. The primary goal is to extract meaningful insights using statistical summaries and visualizations to understand the factors that influenced survival outcomes on the Titanic.

🎯 Objective
Perform descriptive and exploratory data analysis (EDA) on the Titanic dataset.

Apply visual and statistical techniques to uncover patterns, trends, and relationships.

Present a detailed analysis using Python in Jupyter Notebook and a final PDF report summarizing key findings.

🛠️ Tools and Technologies
Python (Pandas, Matplotlib, Seaborn)

Jupyter Notebook (for step-by-step analysis)

PDF Report (compiled findings and visual insights)

📁 Dataset
Titanic Dataset (train.csv)

Key features: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.

🔍 Project Process
1. Data Understanding
Used .info(), .describe(), .value_counts(), and .isnull().sum() to explore data types, distributions, and missing values.

Identified missing data in Age, Cabin, and Embarked columns.

2. Data Cleaning
Missing values were handled by focusing on columns with sufficient data for analysis.

Performed type checks and ensured numeric columns were suitable for correlation analysis.

3. Statistical Exploration
Explored survival rates across Sex, Passenger Class, and Age groups.

Used histograms to understand the distribution of Age and Fare.

Created boxplots to compare Age across different classes and survival outcomes.

Analyzed the relationship between survival and categorical features like Sex and Pclass using countplots.

4. Visual Exploration
Plotted scatterplots to explore the relationship between Fare, Age, and Survival.

Used pairplots to map multi-variable relationships.

Generated a correlation heatmap using cleaned numerical data to examine the strength of associations between features.

📈 Key Findings
Higher survival rates were seen among females and first-class passengers.

Fare and Passenger Class were strongly correlated.

Passengers who paid higher fares had better chances of survival.

Younger passengers generally had higher survival probabilities.

Cancellations and class had visible impacts on passenger outcomes.

📑 Deliverables
Jupyter Notebook: Full Python code with step-by-step analysis, visuals, and observations.

PDF Report: Summarized findings and supporting visualizations.

✅ Learning Outcomes
Developed strong skills in exploratory data analysis (EDA).

Learned to use Python libraries like Pandas, Matplotlib, and Seaborn for visual and statistical exploration.

Gained experience in identifying patterns, trends, and outliers in real-world datasets.

