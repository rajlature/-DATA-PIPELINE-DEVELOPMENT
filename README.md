# -DATA-PIPELINE-DEVELOPMENT

"COMPANY" :CODTECH IT SOLUTIONS

"NAME" : CHANNABASWARAJ GORAKH LATURE

INTERN ID : CT06WV11

*DOMAIN * : DATA SCIENCE

DURATION : 6 WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION

In this project, I developed an ETL (Extract, Transform, Load) pipeline using Python to automate the preprocessing of a structured dataset titled "ODI Cricket Data.csv". This dataset consists of performance statistics of players in One Day International (ODI) cricket matches, including both batting and bowling features. The goal of this pipeline was to clean, standardize, and prepare the data for further analysis, modeling, and visualization.
The tools used in this project include Pandas, Scikit-learn, and Python’s built-in functionalities. These are widely-used tools in the data science ecosystem, known for their reliability and ease of use when working with structured datasets.
The first step in the pipeline is the Extract phase, where the dataset is loaded into memory using pandas.read_csv(). This function enables efficient reading of CSV files and gives us access to powerful data manipulation functions available in Pandas.
The second stage is Transform, where the data is cleaned and made suitable for analysis or modeling. I began by identifying and separating numerical and categorical columns. For numerical columns, I handled missing values using the mean imputation strategy with Scikit-learn’s SimpleImputer. For categorical columns, I used most frequent imputation to fill in missing values, which is a good practice when dealing with categorical data in classification or grouping tasks.
Next, categorical features were label encoded using LabelEncoder from Scikit-learn. This step converts text labels into numerical codes, which are required for most machine learning models. After encoding, I applied feature scaling using StandardScaler to normalize the numerical data. This step ensures that all numerical columns contribute equally to distance-based models and improve convergence in gradient-based algorithms.
The third and final step is Load, where the transformed dataset is saved into a new CSV file named processed_odi_cricket_data.csv. This version of the dataset is clean, numeric, and scaled—ready for use in further stages such as modeling or visualization.

Applications and Future Use
This preprocessed data can now be used in several interesting ways:
Predictive Modeling: You can use machine learning algorithms (like logistic regression, random forest, or decision trees) to predict player performance, such as forecasting whether a player will win the "Player of the Match" award based on match stats.
Clustering: Using unsupervised learning (e.g., K-Means), you can group similar players based on performance stats. This is helpful for team selection or scouting.
Performance Analysis: Analysts can use this clean data for visual dashboards using tools like Streamlit or Tableau to highlight top players, trends across tournaments, or team comparisons.
Statistical Insights: You can calculate averages, win/loss ratios, and other KPIs to support data-driven decision-making in sports analytics.

OUTPUR:-

<img width="960" alt="Image" src="https://github.com/user-attachments/assets/061224ca-a22e-41e1-aabe-1b7b00ca600a" />

<img width="960" alt="Image" src="https://github.com/user-attachments/assets/d2833a39-e04f-4f12-baef-fe76f5163862" />

In conclusion, this ETL pipeline not only automates a crucial part of data preparation but also serves as a foundational step for a wide range of machine learning, statistical, and analytical applications in the domain of cricket analytics.
