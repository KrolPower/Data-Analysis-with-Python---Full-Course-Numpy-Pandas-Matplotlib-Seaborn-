# Data-Analysis-with-Python---Full-Course-for-Beginners-Numpy-Pandas-Matplotlib-Seaborn-
This is my project work from Free Code Camps' Data Analysis Course



## What is Data Analysis
Data analysis is the process of inspecting, cleansing, transforming, and modeling data with the goal of discovering useful information, informing conclusion and supporting decision-making.


## Stack Learned:
- Python


# Part 1: Introduction
## Why Python for Data Analysis?
### Why would we choose Python over R or Julia?
- Very simple and intuitive to learn  
- “correct” language  
- Powerful libraries (not just for Data Analysis)  
- Free and open source  
- Amazing community, docs and conferences  


### When to choose R?
- When R Studio is needed  
- When dealing with advanced statistical methods  
- When extreme performance is needed  


## The Data Analysis Process
### 1: Data Extraction
- SQL
- Scrapping
- File Formats
- CSV
- JSON
- XML
- Consulting APIs
- Buying Data
- Distributed Databases

### 2: Data Cleaning
- Missing values and empty data
- Data imputation
- Incorrect types
- Incorrect or invalid values
- Outliers and non relevant data
- Statistical sanitization

### 3: Data Wrangling
- Hierarchical Data
- Handling categorical data
- Reshaping and transforming structures
- Indexing data for quick access
- Merging, combining and joining data

### 4: Analysis
- Exploration
- Building statistical models
- Visualization and representations
- Correlation vs Causation analysis
- Hypothesis testing
- Statistical analysis
- Reporting

### 5: Action
- Building Machine Learning Models
- Feature Engineering
- Moving ML into production
- Building ETL pipelines
- Live dashboard and reporting
- Decision making and real-life tests


# Part 2: Real Life Example of a Python/Pandas Data Analysis project
## A demonstration of a real life data analysis project using Python, Pandas, SQL and Seaborn.

### What's the mean of `Customers_Age`?
```python
sales['Customer_Age'].mean()
```

### Go ahead and show a <b>density (KDE)</b> and a <b>box plot</b> with the `Customer_Age` data:
```python
sales['Customer_Age'].plot(kind='kde', figsize=(14,6))
```
![Density(KDE)](/Lecture_02/Images/2_1.png)

```python
sales['Customer_Age'].plot(kind='box', vert=False, figsize=(14,6))
```
![Box Plot](/Lecture_02/Images/2_2.png)


### What's the mean of `Order_Quantity`?
```python
sales['Order_Quantity'].mean()
```


### Go ahead and show a <b>histogram</b> and a <b>box plot</b> with the `Order_Quantity` data:
```python
sales['Order_Quantity'].plot(kind='hist', bins=30, figsize=(14,6))
```
![Histogram](/Lecture_02/Images/2_3.png)


```python
sales['Order_Quantity'].plot(kind='box', vert=False, figsize=(14,6))
```
![Histogram](/Lecture_02/Images/2_4.png)


### How many sales per year do we have?
```python
sales['Year'].value_counts()
```

### Go ahead and show a <b>pie plot</b> with the previous data:
```python
sales['Year'].value_counts().plot(kind='pie', figsize=(6,6))
```
![Pie Plot](/Lecture_02/Images/2_5.png)
















# Part 3: Jupyter Notebooks Tutorial
## A step by step tutorial to learn how to use Juptyer Notebooks












































# Part 4: Intro to NumPy
## Learn why NumPy was such an important library for the data-processing world in Python. Learn about low level details of computations and memory storage, and why tools like Excel will always be limited when processing large volumes of data.


# Part 5: Intro to Pandas
## Pandas is arguably the most important library for Data Processing in the Python world. Learn how it works and how its main data structure, the Data Frame, compares to other tools like spreadsheets or DFs used for Big Data


# Part 6: Data Cleaning
## Learn the different types of issues that we'll face with our data: null values, invalid values, statistical outliers, etc, and how to clean them.



# Part 7: Reading Data from other sources




# Part 8: Python Recap
## If your Python or coding skills are rusty, check out this section for a quick recap of Python main features and control flow structures.



