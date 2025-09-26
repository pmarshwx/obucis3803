<center>

# **Fall 2025 &mdash; CIS 3803<br>Introduction to Data Science**
### Week 4: Data Visualization

</center>

**Date:** 22 September 2025  
**Time:** 6:00–9:00 PM  
**Instructor:** Dr. Patrick T. Marsh  
**Course Verse:** “It is the glory of God to conceal a matter; to search out a matter is the glory of kings.” &mdash; *Proverbs 25:2 (NIV)*


****

## **Learning goals**


## **Today's Outline**

****

## **Opening Devotional and Reflection**

*"If any of you lacks wisdom, you should ask God, who gives generously to all without finding fault, and it will be given to you."*

*&mdash; James 1:5 (NIV)*

The most effective data visualizations tell a simple, true story (e.g., 'Tip increases with bill size'). In your life right now, what is one complex or confusing 'data set' (a relationship, a decision, a habit) you are facing? What steps can you take to "filter," "plot," or "visualize" that issue in a simple, clear way to find the underlying truth and take action?

*****

## **Data Visualization &mdash; Definitions**

**Data visualization** is the graphical representation of data. It uses visual elements like charts, graphs, and maps to help people understand and analyze trends, patterns, and insights in data.



### **Data Types and Their Visualization**

- **Nominal Data:** Categorical data that has no intrinsic order (e.g., gender, country). It's best visualized with bar charts, pie charts, or word clouds.

- **Ordinal Data:** Categorical data that has a clear order but no measurable difference between categories (e.g., education level: high school, bachelor's, master's). Bar charts and column charts are good for this.

- **Interval Data:** Numerical data where the difference between values is meaningful, but there's no true zero point (e.g., temperature in Celsius or Fahrenheit). Line charts and histograms are useful here.

- **Ratio Data:** Numerical data with a meaningful difference between values and a true zero point (e.g., height, weight, income). All types of statistical charts, from scatterplots to histograms, can be used.



### **Histograms & Skewness**

A **histogram** is a bar chart-like representation of the distribution of numerical data. The bars, called bins, represent ranges of values, and their height indicates the frequency of data points within that range. A **normal histogram** has a bell-shaped curve, which is a characteristic of a normal distribution where most data points cluster around the mean.

**Skewness** describes the asymmetry of a data distribution.

- A distribution is **skewed left** (or negatively skewed) if its tail extends to the left side, meaning the majority of data points are concentrated on the right. .

- A distribution is **skewed right** (or positively skewed) if its tail extends to the right side, meaning most data points are on the left. .

- A distribution is **symmetric** if both sides are mirror images of each other. The mean, median, and mode are all at the center.

#### **Data Distribution & Central Tendency**

- A **bimodal** distribution has two peaks, indicating two distinct clusters of data.

- A **multimodal** distribution has more than two peaks.



### **Plots & Charts**

#### **Chart Types by Function**

- **Composition Charts:** Show how a whole is divided into parts (e.g., pie charts, stacked bar charts).

- **Comparison Charts:** Compare values across different categories (e.g., bar charts, column charts).

- **Distribution Charts:** Show the spread and shape of a dataset (e.g., histograms, density plots, box plots).

- **Relationship Charts:** Illustrate the connection between two or more variables (e.g., scatterplots, bubble charts).

- **Geospatial Charts:** Visualize data with a geographic component (e.g., choropleth maps, bubble maps).

#### **Specific Kinds of Charts**

- A **density plot** is a smoothed version of a histogram that shows the distribution of a continuous variable. It uses a kernel density estimate to create a smooth curve.

- A **box plot** (or box-and-whisker plot) displays the five-number summary of a dataset: minimum, first quartile, median, third quartile, and maximum. It's useful for visualizing the distribution and identifying outliers.

- A **violin plot** is similar to a box plot but also shows the kernel density estimate of the data's distribution, providing more detail on the data's shape.

- A **bar chart** uses rectangular bars to represent categorical data. The length or height of the bars corresponds to the values they represent.

- A **column chart** is a type of bar chart where the bars are displayed vertically.

- A **word cloud** (or tag cloud) visualizes text data. The size of each word is proportional to its frequency or importance.

- A **treemap** displays hierarchical data as nested rectangles. The size of each rectangle is proportional to its value.

- A **scatterplot** plots individual data points as dots on a two-dimensional graph, showing the relationship between two variables.

- A **line chart** connects a series of data points with a line. It's used to show trends over time.

- A **bubble chart** is a type of scatterplot where a third variable is represented by the size of the bubble.

- A **heatmap** uses color to represent data values in a matrix, with different shades or hues indicating the magnitude of the data.

- A **geographic map** visualizes data points on a map, often using color or size to represent data values in different regions.

- **Scatterplot Matrix (SPLOM):** A grid of scatterplots, with each plot showing the relationship between a pair of variables. It's useful for visualizing all pairwise correlations in a dataset.

- **Parallel Coordinates Plot:** A chart that plots each data point as a line across several vertical axes. It's effective for visualizing high-dimensional data and spotting clusters or trends.

- **Radial Chart:** Also known as a radar or spider chart, it plots data points on a set of axes originating from the same center point. It's often used for comparing multiple variables for a single entity or comparing different entities on the same variables. .

- **Sunburst Chart:** A multilevel pie chart that visualizes hierarchical data. The innermost circle represents the top of the hierarchy, and outer rings are divided into segments that correspond to subcategories.



### **Interactive Visualization**

- **Dashboards:** A single-page graphical interface that provides an at-a-glance overview of key performance indicators (KPIs) and data-driven insights. They often contain multiple visualizations that can be filtered and drilled down for more detail.

- **Drill-down:** The ability to move from a summarized view of data to a more detailed view by clicking on a visual element. For example, clicking on a state in a map to see data for each city.

- **Filtering:** The process of hiding or displaying a subset of data points based on specific criteria. It allows users to focus on data relevant to their needs.

- **Animation:** The use of motion to show changes in data over time or to guide a viewer's attention.



### **Statistical Terms**

- A **response variable** (or **dependent variable**) is the variable that is being measured or tested in an experiment.

- An **explanatory variable** (or **independent variable**) is the variable that is being manipulated or changed in an experiment.

- A **percentile** is a measure used in statistics indicating the value below which a given percentage of observations in a group of observations falls. For example, the 25th percentile is the value below which 25% of the data can be found.

- A **quartile** divides a dataset into four equal parts.

    - The **first quartile** ($Q_1$) is the 25th percentile.

    - The **second quartile** ($Q_2$) is the median (50th percentile).

    - The **third quartile** ($Q_3$) is the 75th percentile.

- The **interquartile range** (IQR) is the range between the first and third quartiles ($Q_3−Q_1$). It measures the spread of the middle 50% of the data.

- The **minimal value** is the lowest value in a dataset.

- The **maximum value** is the highest value in a dataset.



### **Misleading Data Practices**

- **Misrepresenting data** is a term for the deceptive use of statistics to create a false impression.

- **Truncated axes** is when the y-axis of a chart does not start at zero, exaggerating the differences between data points.

- **Cherry-picking** is the act of selecting data that supports a particular argument while ignoring data that contradicts it.

- **Misleading use of color** is the use of colors in a way that suggests a false relationship or emotional response. For example, using red for positive values and green for negative.

- **Misinterpretation of association and causation** is a logical fallacy where one assumes that because two variables are correlated (associated), one must cause the other.

- **Mislabeling** involves providing inaccurate or confusing labels on a chart or graph, which can lead to misinterpretation.



### **Data-Related Concepts**

- **Data democratization** is the process of making data accessible to everyone in an organization, regardless of their technical knowledge.

- **Data storytelling** is the practice of using data to create a compelling narrative or story, often to influence decision-making.

- An **infographic** is a visual representation of information, data, or knowledge intended to present complex information quickly and clearly.

- **Data journalism** is a specialized field of journalism that uses data to report news and create compelling stories.



### **Artificial Intelligence & Natural Language Processing**

- **Artificial intelligence (AI)** is a broad field of computer science focused on creating machines that can perform tasks that typically require human intelligence, such as learning, problem-solving, and decision-making. 🤖

- **Natural language processing (NLP)** is a subfield of AI that focuses on enabling computers to understand, interpret, and generate human language.

***** 

## **Data Visualization &mdash; Examples**

### **The Basics: Importing**

Matplotlib has two main interfaces for creating plots in Python: `pyplot` and `pylab`. The main difference between `pyplot` and `pylab` is their scope and purpose. `pyplot` is the recommended way to use Matplotlib, offering a state-based interface for creating plots, while `pylab` is a deprecated module that combined `pyplot` with NumPy, designed for convenience in a more interactive, MATLAB-like environment. I am including a brief overview of `pylab` for completeness since you may see examples "in the wild" that use it.

##### **`pyplot`**

The `pyplot` module is a collection of functions that make Matplotlib work like MATLAB. Each `pyplot` function makes some change to a figure, such as creating a figure, creating a plotting area in a figure, plotting some lines in a plotting area, or decorating the plot with labels.

The standard way to import and use it is:

```python

import matplotlib.pyplot as plt

```

`pyplot` maintains a current figure and plotting area, and the plotting functions act on that current state. This makes a great choice for creating simple plots quickly. It is considered the standard and msost Pythonic way to use Matplotlib.

##### **`pylab`**

The `pylab` module is a convenience module that imports both `matplotlib.pyplot` and `numpy` into a single namespace. The idea was to mimic the behavior of MATLAB's environment, where all plotting and numerical functions are readily available without explicit imports. 

The typical import was:

```python

from pylab import *

```

This import style brings hundreds of functions and variables into the global namespace, which is generally considered **bad practice** in Python because it can lead to name clashes and makes code harder to read and debug. For this reason, `pylab` is officially deprecated and its use is highlight discouraged. 


### Matplotlib

We will work through and discuss the tutorials and user guide located on the [Matplotlib website](https://matplotlib.org/stable/users/index.html#users-guide-index).


### **`seaborn`**

Seaborn is a powerful data visualization library for Python that is built on top of Matplotlib. It's designed to create beautiful and informative statistical graphs with less written code by the user. 

#### **Key Features**
* **Aesthetic Appeal:** Seaborn offers high-level plotting functions that produce aesthetically pleasing and visually sophisticated statistical graphics right out of the box. Its default styles and color palettes are designed to look great without any extra effort. 🎨
* **Statistical Plotting:** The library excels at plotting common statistical visualizations. It has built-in functions for complex charts like **histograms**, **density plots**, **scatterplots**, **box plots**, and **violin plots**, making it easy to explore the distribution of your data and the relationships between variables.
* **Integration with Pandas:** Seaborn works seamlessly with **Pandas** DataFrames, allowing you to quickly visualize data from a tabular format without extensive preprocessing. You can simply pass column names as arguments to its plotting functions.
* **Complex Visualizations:** It provides tools to create complex visualizations like **heatmaps** and **clustermaps** for matrix data and **pair plots** to visualize relationships between all pairs of variables in a dataset.

In short, while **Matplotlib** provides the foundational tools for plotting, **Seaborn** offers a more user-friendly, high-level interface specifically for creating attractive and meaningful statistical plots. It saves you from writing a lot of the boilerplate code needed in Matplotlib to achieve the same results.

The typical way to import seaborn is as follows:

```python

import seaborn as sns

```

We will work through and discuss the tutorials and user guide located on the [Seaborn website](https://seaborn.pydata.org/tutorial.html).


```python
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

# Let's generate some sample data to work with
np.random.seed(0)
data = np.random.randn(1000)
categories = ['A', 'B', 'C', 'D', 'E']
values = np.random.randint(1, 10, 5)
```

### **Histograms and Density Plots**


```python
# Create a figure and a set of subplots
fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12, 5))

# Histogram
ax1.hist(data, bins=30, color='skyblue', edgecolor='black')
ax1.set_title('Histogram')
ax1.set_xlabel('Value')
ax1.set_ylabel('Frequency')

# Density Plot (using a seaborn kdeplot for convenience, as it's a common practice)
sns.kdeplot(data, ax=ax2, color='salmon', fill=True)
ax2.set_title('Density Plot')
ax2.set_xlabel('Value')
ax2.set_ylabel('Density')

plt.tight_layout()
plt.show()
```

##### **Using Seaborn**


```python
fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12, 5))

# Load a sample dataset from Seaborn for demonstration
tips = sns.load_dataset('tips')

# Histogram using displot()
sns.histplot(data=tips, x='total_bill', bins=20, kde=True, ax=ax1)
ax1.set_title('Histogram with KDE')

# Density Plot using kdeplot()
sns.kdeplot(data=tips, x='total_bill', fill=True, color='purple', ax=ax2)
ax2.set_title('Density Plot')

plt.tight_layout()
plt.show()
```

### **Box Plots and Violin Plots**


```python
fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12, 5))

# Box Plot
ax1.boxplot(data)
ax1.set_title('Box Plot')
ax1.set_ylabel('Value')

# Violin Plot
ax2.violinplot(data, showmedians=True)
ax2.set_title('Violin Plot')
ax2.set_ylabel('Value')

plt.tight_layout()
plt.show()
```

##### **Using Seaborn**


```python
fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12, 5))

# Box Plot
sns.boxplot(x='day', y='total_bill', data=tips, ax=ax1)
ax1.set_title('Box Plot of Total Bill by Day')

# Violin Plot
sns.violinplot(x='day', y='total_bill', data=tips, ax=ax2)
ax2.set_title('Violin Plot of Total Bill by Day')

plt.tight_layout()
plt.show()
```

### **Bar Charts and Column Charts**


```python
# Create a bar chart (horizontal)
plt.figure(figsize=(8, 6))
plt.barh(categories, values, color='lightgreen')
plt.title('Bar Chart')
plt.xlabel('Value')
plt.ylabel('Category')
plt.show()

# Create a column chart (vertical bar chart)
plt.figure(figsize=(8, 6))
plt.bar(categories, values, color='cornflowerblue')
plt.title('Column Chart')
plt.xlabel('Category')
plt.ylabel('Value')
plt.show()
```

##### **Using Seaborn**


```python
plt.figure(figsize=(8, 6))
# A vertical bar chart (column chart)
sns.barplot(x='day', y='total_bill', data=tips, errorbar=None)
plt.title('Column Chart of Average Total Bill by Day')
plt.show()

plt.figure(figsize=(8, 6))
# A horizontal bar chart
sns.barplot(x='total_bill', y='day', data=tips, errorbar=None)
plt.title('Bar Chart of Average Total Bill by Day')
plt.show()
```

### **Scatter Plots and Bubble Charts**


```python
# Generate some data for a scatter plot
x = np.random.rand(50) * 10
y = np.random.rand(50) * 10
colors = np.random.rand(50)
sizes = 100 * np.random.rand(50)

# Scatter Plot
plt.figure(figsize=(8, 6))
plt.scatter(x, y, c=colors, cmap='viridis', s=sizes, alpha=0.7)
plt.title('Bubble Chart (A Scatter Plot with Sizing)')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.colorbar(label='Color Value')
plt.show()
```

##### **Using Seaborn**


```python
plt.figure(figsize=(10, 6))
sns.scatterplot(
    x='total_bill',
    y='tip',
    data=tips,
    hue='smoker',  # Color points by smoker status
    size='size',   # Set point size based on the party size
    sizes=(20, 200),
    alpha=0.7
)
plt.title('Scatter Plot / Bubble Chart of Tips')
plt.show()
```

### **Line Charts**


```python
# Generate time series data
time = np.arange(0, 10, 0.1)
trend = np.sin(time) + np.random.randn(len(time)) * 0.1

# Line Chart
plt.figure(figsize=(10, 6))
plt.plot(time, trend, marker='o', linestyle='-', color='purple')
plt.title('Line Chart Showing Trend Over Time')
plt.xlabel('Time')
plt.ylabel('Value')
plt.grid(True)
plt.show()
```

##### **Using Seaborn**


```python
# Generate some time-series data
flights = sns.load_dataset('flights')
flights_pivot = flights.pivot_table(index='year', columns='month', values='passengers', observed=True)

plt.figure(figsize=(10, 6))
sns.lineplot(data=flights, x='year', y='passengers', errorbar='sd')
plt.title('Line Chart of Passengers Over Years')
plt.show()
```
