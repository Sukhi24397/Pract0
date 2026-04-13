EXPERIMENT 13:

AIM:
To analyze and interpret structured data using Python by applying techniques such as data manipulation,
grouping, summarization, and cross-tabulation in order to extract meaningful insights from the dataset.

THEORY:
Data analysis in Python involves inspecting, transforming, and modeling data to discover useful information and support decision-making.
In this experiment, structured datasets are analyzed using the powerful library Pandas, which provides flexible and efficient tools for handling both numerical and categorical data.

1. Data Structures in Pandas

Pandas provides two main data structures:

Series: One-dimensional labeled array
DataFrame: Two-dimensional tabular data structure with rows and columns

These structures allow easy storage, manipulation, and analysis of datasets.

2. Data Loading and Inspection

Before analysis, data is loaded into a DataFrame using functions like:

pd.read_csv()

Initial inspection is done using:

head() – displays first few rows
info() – gives summary of data types
describe() – provides statistical summary

This step helps in understanding the structure and quality of the dataset.

3. Data Cleaning

Real-world datasets often contain:

Missing values
Duplicate entries
Inconsistent data

Common techniques include:

dropna() – remove missing values
fillna() – replace missing values
drop_duplicates() – remove duplicates

Data cleaning ensures accuracy and reliability of analysis.

4. Data Selection and Filtering

Specific data can be selected using:

df['column_name']
df.loc[]
df.iloc[]

Filtering allows extraction of meaningful subsets based on conditions.

5. Grouping and Aggregation

Grouping is used to organize data into categories and perform operations on each group:

df.groupby('column_name')

Aggregation functions include:

sum()
mean()
count()

This helps in comparing different categories and identifying trends.

6. Frequency and Distribution Analysis

For categorical data:

value_counts() provides frequency of each category
Normalization gives percentage distribution

This helps in understanding how data is distributed across categories.

7. Cross-Tabulation

Cross-tabulation is used to study relationships between two variables:

pd.crosstab(df['col1'], df['col2'])

It creates a contingency table showing how variables interact.

8. Data Interpretation

After performing operations, the results are interpreted to:

Identify patterns
Compare categories
Draw meaningful conclusions
9. Importance of Data Analysis

Data analysis is widely used in:

Business decision-making
Academic research
Market analysis
Scientific studies

It helps convert raw data into actionable insights.

10. Advantages of Using Python
Simple and readable syntax
Powerful libraries like Pandas
Handles large datasets efficiently
Supports automation and reproducibility


CONCLUSION:
The experiment successfully demonstrated how to perform data analysis using Python. Various techniques such as data loading, cleaning, grouping,
and cross-tabulation were applied to extract meaningful insights from the dataset.

It was observed that:

Data can be efficiently organized and analyzed using Pandas
Grouping and aggregation help in identifying trends
Cross-tabulation reveals relationships between variables

Thus, Python proves to be a powerful and efficient tool for data analysis, enabling better understanding and interpretation of structured data.
