EXPERIMENT 14:

AIM:
To perform data analysis using Python by applying various operations such as data exploration, filtering, 
grouping, aggregation, and relationship analysis to extract meaningful information from the dataset.


THEORY:
Data analysis is the process of examining, organizing, transforming, and interpreting data to discover useful information and support decision-making. In this experiment,
Python is used as the primary tool for analysis, particularly with the help of the Pandas library.

Pandas provides efficient data structures and functions that simplify handling large and complex datasets.

1. Data Representation Using Pandas

In Pandas, data is represented using:

Series: A one-dimensional labeled array capable of holding any data type
DataFrame: A two-dimensional structure consisting of rows and columns

These structures allow easy manipulation and analysis of structured data.

2. Data Importing and Exploration

Data is typically imported using functions like:

pd.read_csv()

Initial exploration includes:

Viewing first few records using head()
Checking structure with info()
Understanding statistical properties with describe()

This step helps in understanding the dataset before applying analysis.

3. Data Cleaning and Preparation

Real-world data may contain inconsistencies such as:

Missing values
Duplicate entries
Incorrect formats

These are handled using:

dropna() – removes missing values
fillna() – fills missing values
drop_duplicates() – removes duplicate records

Data cleaning improves accuracy and reliability.

4. Data Selection and Filtering

Specific data can be accessed using:

Column selection: df['column']
Row/column indexing: loc[], iloc[]

Filtering conditions help extract relevant subsets of data.

5. Grouping and Aggregation

Grouping divides the dataset into categories based on column values:

df.groupby('column')

Aggregation functions include:

sum()
mean()
count()
max() / min()

This helps in summarizing and comparing grouped data.

6. Frequency Analysis

For categorical variables:

value_counts() calculates frequency
Normalization provides percentage distribution

This helps understand how data is distributed across categories.

7. Cross-Tabulation and Relationship Analysis

Cross-tabulation is used to analyze relationships between variables:

pd.crosstab(df['col1'], df['col2'])

It provides a clear view of how different categories interact.

8. Data Interpretation

After performing analysis, results are interpreted to:

Identify trends
Detect patterns
Compare categories
Draw conclusions
9. Applications of Data Analysis

Data analysis is used in:

Business analytics
Education systems
Market research
Scientific research

It helps in making informed decisions based on data.

10. Advantages of Python in Data Analysis
Easy-to-use syntax
Powerful libraries like Pandas
Efficient handling of large datasets
Supports automation and reproducibility


CONCLUSION:
The experiment successfully demonstrated the use of Python for performing data analysis. Various operations such as data exploration, cleaning, filtering, grouping, 
and cross-tabulation were applied to extract meaningful insights.

It was observed that:

Python simplifies complex data operations
Grouping and aggregation help in summarizing data effectively
Cross-tabulation reveals relationships between variables

Thus, Python, along with Pandas, is an effective and powerful tool for analyzing structured data and deriving useful conclusions.
