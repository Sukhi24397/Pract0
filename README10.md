EXPERIMENT 10:
INTORDUCTION TO PANDAS

Aim:
To understand the fundamentals of the Pandas library in Python, specifically focusing on the creation, manipulation, and basic statistical analysis of structured data using Series and DataFrames

THEORY:
Pandas is a fundamental Python library designed for high-performance data manipulation and analysis. It provides two primary data structures: the Series and the DataFrame.

1. Fundamental Data Structures
Series: A one-dimensional, indexed array capable of holding any data type (integers, strings, etc.). In your experiment, a Series was created using a list of integers (10, 20, 30, 40, 50).

DataFrame: A two-dimensional, size-mutable, tabular data structure with labeled axes (rows and columns). It is essentially a collection of Series objects sharing the same index.

2. Data Inspection and Metadata
Understanding the "shape" of data is critical before analysis. Your notebook utilizes several metadata attributes:

.shape: Returns a tuple representing the dimensionality (rows, columns).

.ndim: Returns the number of dimensions (e.g., 2 for a DataFrame).

.size: Calculates the total number of elements in the object.

.dtypes: Identifies the data type of each column, which is vital for ensuring numerical operations can be performed.

3. Data Indexing and Selection
Pandas provides sophisticated methods to access specific data points:

Label-based selection (.loc): This method is used to access a group of rows and columns by labels or a boolean array. For example, df.loc[0, "Name"] retrieves the name at index 0.

Integer-based selection (.iloc): This allows for selection by position, such as df.iloc[1, 1] to target the second row and second column.

4. Descriptive Statistics and Filtering
One of the primary strengths of Pandas is its ability to perform "vectorized" operations—performing calculations on entire columns at once without explicit loops.

Statistical Methods: Functions like .mean(), .min(), and .max() allow for rapid assessment of numerical distributions within a dataset.

Boolean Filtering: This involves passing a conditional statement (e.g., df["MARKS"] > 80) into the DataFrame to return only the rows where that condition is true.

5. Data Transformation
The experiment demonstrates how DataFrames are dynamic:

Column Addition: New data can be assigned to a new column name (e.g., "grade").

Column Removal: The .drop() method allows for the removal of features that are no longer needed for analysis.

Conclusion:
In this experiment, the basic operations of the Pandas library were successfully implemented. Through the code execution, it was demonstrated how to:

Convert raw Python dictionaries into structured DataFrames.

Manipulate data by adding a "grade" column and updating individual student records using both label and index-based methods.

Perform basic statistical analysis to find the average and extreme values of the dataset.

Filter data efficiently, showcasing Pandas' ability to handle conditional queries which is essential for data science workflows.

The experiment concludes that Pandas is an essential tool for transforming raw data into an organized format ready for analysis.
