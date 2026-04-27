Experiment 19:

🎯 Aim

To implement and analyze advanced data visualization techniques using Python libraries such as Matplotlib,
Seaborn, Pandas, and NumPy for better understanding of data patterns and relationships.

📚 Theory

Data visualization helps convert raw data into meaningful insights using graphical representations. In this experiment, various plotting and data handling techniques are used to explore datasets and highlight patterns, correlations, and distributions.

🔹 Libraries Used:
Matplotlib (matplotlib.pyplot)
Used for creating basic plots like line charts, scatter plots, bar graphs, etc.
Seaborn (seaborn)
Provides high-level statistical visualizations with improved design and built-in themes.
Pandas (pandas)
Used for data manipulation, cleaning, and analysis using DataFrames.
NumPy (numpy)
Used for numerical operations and generating sample/random data.

🔹 Commands Used & Their Definitions:
📌 Data Handling Commands
pd.read_csv()
Loads data from a CSV file into a DataFrame.
pd.DataFrame()
Creates a structured table for storing data.
df.head()
Displays the first few rows of the dataset.
df.describe()
Provides statistical summary (mean, std, min, max, etc.).
df.info()
Shows dataset structure, data types, and non-null values.
df.columns
Returns column names of the dataset.
df['column']
Accesses a specific column.

📌 NumPy Commands:
np.array()
Creates an array.
np.random.rand()
Generates random numbers between 0 and 1.
np.random.randint()
Generates random integers.
np.linspace(start, stop, n)
Generates evenly spaced numbers between a range.

📌 Matplotlib Commands:
plt.figure()
Creates a new figure for plotting.
plt.plot()
Draws a line plot.
plt.bar()
Creates a bar chart.
plt.scatter()
Creates a scatter plot.
plt.hist()
Creates a histogram for distribution.
plt.title()
Sets the title of the graph.
plt.xlabel() / plt.ylabel()
Labels axes.
plt.legend()
Displays legend for plots.
plt.grid()
Adds gridlines.
plt.show()
Displays the plot.

📌 Seaborn Commands:
sns.set_style()
Sets the theme/style of plots.
sns.lineplot()
Creates a line plot with statistical aggregation.
sns.barplot()
Creates a bar chart with confidence intervals.
sns.histplot()
Displays distribution of data.
sns.boxplot()
Shows distribution with quartiles and outliers.
sns.heatmap()
Displays correlation matrix visually.
sns.scatterplot()
Creates scatter plots with additional features (color, size, hue).

🧾 Conclusion:

In this experiment, various advanced data visualization techniques were implemented using Python libraries. 
Different plots such as line plots, bar charts, scatter plots, histograms, boxplots, and heatmaps were used to analyze 
and interpret data effectively.

These visualizations help in:
Understanding trends and patterns
Identifying relationships between variables
Detecting outliers and anomalies
Making data-driven decisions

Overall, the experiment demonstrates how powerful Python libraries can simplify complex data analysis and
improve interpretability through visual representation.
