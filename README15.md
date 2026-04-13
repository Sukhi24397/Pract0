EXPERIMENT 15:

Aim

To perform data preprocessing techniques including data normalization and data type conversion (encoding) using Python libraries like Pandas and NumPy, 
and to understand their importance in preparing datasets for analysis and machine learning.


Theory:
Data preprocessing is an essential step in data analysis and machine learning. It involves transforming raw data into a clean and usable format.

1. Data Normalization

Normalization scales numerical data into a specific range so that all features contribute equally.

Min-Max Normalization
Rescales values between 0 and 1 using minimum and maximum values.
Z-Score Normalization
Transforms data based on mean and standard deviation, centering it around 0.
Decimal Scaling
Scales values by dividing them by a power of 10.
Column Normalization
Applies normalization to multiple columns simultaneously.

These methods help improve model performance by avoiding bias toward larger values.

2. Data Encoding (Categorical Conversion)

Categorical data must be converted into numerical form for algorithms.

Label Encoding (using scikit-learn)
Assigns a unique integer to each category.
One-Hot Encoding
Converts categories into binary columns (0/1).
Dummy Encoding
Similar to one-hot but removes one column to avoid redundancy (dummy variable trap).

These techniques allow machine learning models to interpret categorical variables effectively.

Conclusion:
In this experiment, we successfully applied various data normalization techniques and encoding methods to transform raw data into a structured format. 
Normalization ensured that numerical values were scaled properly, while encoding converted categorical data into machine-readable form. These preprocessing steps are crucial for improving the accuracy and efficiency of data analysis and machine learning models.
