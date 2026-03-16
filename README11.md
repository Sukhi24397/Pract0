EXPERIMENT 11:
CREATE DATASET AND LOAD DATASET


Aim:
To demonstrate advanced data handling techniques in Python using the Pandas library, specifically focusing on data cleaning, handling missing values, merging multiple datasets, and performing group-based statistical aggregations.

Pandas is a fundamental Python library used extensively in data science for high-performance data manipulation and analysis. Its name is derived from "Panel Data," referring to multidimensional structured data sets. It serves as the primary tool for the Exploratory Data Analysis (EDA) and Data Cleaning phases of the data science lifecycle.

1. Fundamental Data Structures
Pandas operates primarily through two data structures:

Series: A one-dimensional, labeled array capable of holding any data type (integers, strings, floating-point numbers). It is essentially a single column of data with an associated index.

DataFrame: A two-dimensional, size-mutable, tabular data structure. It is analogous to a spreadsheet or SQL table, consisting of rows and columns. A DataFrame can be viewed as a container for multiple Series objects that share a common index.

2. Metadata and Structural Analysis
Before manipulating data, it is critical to understand its structure through metadata attributes:

.shape: Provides a tuple representing the number of rows and columns (e.g., (3, 2)).

.ndim: Indicates the number of dimensions (a DataFrame has 2 dimensions).

.size: Returns the total number of elements in the object (rows multiplied by columns).

.dtypes: Shows the data type of each column, ensuring numerical operations are valid for the given data.

3. Advanced Data Selection (Indexing)
Pandas offers specialized methods for retrieving and updating data points precisely:

Label-based selection (.loc): Used to access data using the names of rows and columns (e.g., accessing 'Name' at index 0).

Integer-based selection (.iloc): Used for selection by numerical position (e.g., df.iloc[1, 1] to access the value in the second row and second column).

4. Data Cleaning and Handling Missing Values
In real-world data, missing values (represented as NaN or Null) are common. Pandas provides robust tools to handle these:

isnull(): Identifies cells with missing data.

fillna(): Replaces missing values with a placeholder, such as a zero or the mean of the column, to ensure statistical continuity.

dropna(): Removes rows or columns containing missing values entirely.

5. Data Transformation and Aggregation
The library allows for complex modifications to the dataset:

Conditional Filtering: Extracting subsets of data that meet specific criteria (e.g., df[df["MARKS"] > 80]).

Vectorized Statistics: Performing calculations like .mean(), .min(), and .max() across entire columns without the need for manual loops.

Grouping and Merging: Using groupby() to aggregate data based on categories and merge() to combine different DataFrames into a single cohesive dataset.



Conclusion:
The experiment successfully showcased the versatility of the Pandas library in managing complex data workflows. By implementing functions like merge() and groupby(), it was observed that Pandas can efficiently consolidate disparate datasets and extract meaningful group-level insights. Furthermore, the application of data cleaning methods like fillna() ensured that the dataset remained robust for statistical analysis, proving that Pandas is an indispensable tool for the "Data Cleaning" and "Transformation" phases of the data science lifecycle.
