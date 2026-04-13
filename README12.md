EXPERIMENT 12:

AIM:
To perform categorical data analysis using Python by applying techniques such as frequency distribution, 
percentage distribution, grouping, and cross-tabulation to understand relationships between different
categorical variables like Grade, Gender, Department, Category, and Payment Method.

THEORY:
Categorical data analysis is a branch of data analysis that deals with variables representing qualitative attributes rather than numerical values. These variables describe characteristics such as gender, grade, department, product category, or payment method. Unlike numerical data, categorical data cannot be meaningfully averaged, but it can be analyzed using counts, proportions, and relationships.

In Python, the Pandas library is widely used for handling and analyzing categorical datasets. It provides efficient data structures like Series and DataFrame, along with built-in functions for summarizing and interpreting data.

1. Types of Categorical Data

Categorical data can be broadly classified into:

Nominal Data
Categories without any inherent order
Example: Gender (Male/Female), Payment Method (Cash/Card)
Ordinal Data
Categories with a meaningful order
Example: Grades (A, B, C), Satisfaction Levels (High, Medium, Low)

Understanding the type of categorical data helps in selecting appropriate analysis techniques.

2. Frequency Distribution

Frequency distribution is one of the fundamental techniques in categorical data analysis. It shows how often each category appears in the dataset.

In Pandas, this is computed using:

df['column_name'].value_counts()
It helps identify the most and least common categories.
3. Relative and Percentage Distribution

Instead of raw counts, data can also be expressed in terms of proportions or percentages:

Relative frequency:

df['column_name'].value_counts(normalize=True)

Percentage distribution:

df['column_name'].value_counts(normalize=True) * 100

This provides a better understanding of the dataset by showing the share of each category.

4. Cross-Tabulation (Contingency Table)

Cross-tabulation is used to analyze the relationship between two categorical variables. It creates a matrix showing the frequency distribution of variables.

In Pandas:

pd.crosstab(df['col1'], df['col2'])

For example:

Gender vs Grade
Category vs Payment Method

This helps in identifying patterns, associations, and dependencies between variables.

5. Grouping and Aggregation

Grouping involves splitting the dataset into groups based on one or more categorical variables and then performing operations on those groups.

Using:

df.groupby('column_name')

It is useful for:

Comparing categories
Summarizing grouped data
Finding trends within subgroups
6. Data Visualization for Categorical Data

Although not always mandatory, categorical data is often visualized using:

Bar charts
Pie charts

These visual tools make it easier to interpret distributions and relationships.

7. Importance of Categorical Data Analysis

Categorical data analysis is widely used in:

Education systems (student grades, departments)
Business analytics (customer preferences, payment methods)
Market research (product categories, user types)

It helps in:

Identifying trends and patterns
Making comparisons between groups
Supporting decision-making processes
8. Advantages of Using Python for Categorical Analysis
Efficient handling of large datasets
Easy-to-use functions for analysis
Integration with visualization libraries
Fast computation and reproducibility

CONCLUSION:
The experiment successfully demonstrated how to analyze categorical data using Python. By applying functions like frequency counts, percentage distributions, grouping, and cross-tabulation, meaningful insights were extracted from the datasets.

It was observed that:

The distribution of grades, departments, and genders can be easily summarized.
Relationships between variables (such as Gender vs Grade or Category vs Payment Method) can be clearly understood using cross-tabulation.
Python libraries like Pandas simplify complex data analysis tasks.

Thus, categorical data analysis using Python is an effective and efficient method for extracting insights from structured datasets.
