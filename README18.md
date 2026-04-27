# 📊 Experiment 18: Statistical & Specialized Data Visualization in Python

## 🎯 Aim
To explore and implement various statistical and specialized data visualization techniques using Python libraries such as Matplotlib, Seaborn, Pandas, and NumPy.

---

## 📚 Theory

Data visualization is an essential part of data analysis that helps in understanding patterns, trends,
and relationships in datasets. This experiment demonstrates multiple visualization techniques using Python.

---

### 🔹 Libraries Used

- **Matplotlib (`matplotlib.pyplot`)**  
  A core plotting library used for creating basic graphs and charts.

- **Seaborn (`seaborn`)**  
  Built on Matplotlib, used for advanced statistical visualizations with better aesthetics.

- **Pandas (`pandas`)**  
  Used for data manipulation and handling structured datasets.

- **NumPy (`numpy`)**  
  Used for numerical operations and generating random data.

---

### 🔹 Commands Used & Definitions

#### 📌 Data Handling

- `pd.DataFrame()`  
  Creates a DataFrame (table-like structure) for organizing data.

- `np.random.seed()`  
  Sets a seed value to ensure reproducibility of random numbers.

- `np.random.randint()`  
  Generates random integers within a specified range.

- `np.where(condition, x, y)`  
  Returns elements based on a condition.

---

#### 📌 Matplotlib Commands

- `plt.figure()`  
  Creates a new figure for plotting.

- `plt.fill_between(x, y)`  
  Creates an area plot by filling the region between x and y values.

- `plt.title()`  
  Sets the title of the plot.

- `plt.xlabel()` / `plt.ylabel()`  
  Labels the axes.

- `plt.show()`  
  Displays the plot.

- `plt.pie()`  
  Creates a pie chart.

- `plt.Circle()`  
  Draws a circle (used in donut charts).

- `plt.scatter()`  
  Creates a scatter plot.

---

#### 📌 Seaborn Commands

- `sns.set_style()`  
  Sets the visual theme of plots.

- `sns.boxplot()`  
  Creates a boxplot for statistical distribution and outlier detection.

- `sns.heatmap()`  
  Creates a heatmap for correlation matrices.

- `sns.scatterplot()`  
  Creates an enhanced scatter plot with color and size variations.

---

### 🔹 Visualization Techniques Implemented

1. **Area Plot**
   - Displays trends over a continuous range.
   - Implemented using `plt.fill_between()`.

2. **Pie Chart**
   - Shows proportional distribution of categories.
   - Implemented using `plt.pie()`.

3. **Donut Chart**
   - A modified pie chart with a hollow center.
   - Created using `plt.pie()` and `plt.Circle()`.

4. **Boxplot**
   - Displays distribution and identifies outliers.
   - Implemented using `sns.boxplot()`.

5. **Heatmap**
   - Shows correlation between variables.
   - Implemented using `sns.heatmap()`.

6. **Bubble Plot**
   - A scatter plot with variable point sizes.
   - Implemented using `plt.scatter()` and `sns.scatterplot()`.

---

## 🧾 Conclusion

This experiment demonstrates the use of Python visualization libraries to represent data effectively. Various plots such as area plots, pie charts, donut charts, boxplots, heatmaps, and bubble plots were created.

These techniques help in:
- Understanding trends and patterns
- Identifying outliers
- Analyzing relationships between variables

Overall, Python provides powerful and flexible tools for data visualization, making analysis more intuitive and insightful.

---

