**Name: Anvi Singh Tank**

**PRN: 25070123019**

**Batch: ENTC A1**

**Title**

**Implementation and Study of Pandas Library in Python**

**Aim**

To study and implement the Pandas library in Python for data manipulation, analysis, and cleaning using Series and DataFrame structures.

**Objectives**

- To understand the core data structures: Series and DataFrame.
- To perform basic operations like creating, accessing, and updating data.
- To apply data manipulation techniques such as adding and dropping columns.
- To perform basic statistical analysis and conditional filtering on datasets.
- To understand the role of metadata attributes like shape, size, and dimensions.

**Theory**

Pandas is an open-source Python library that provides high-performance data structures designed to make working with "relational" or "labeled" data easy and intuitive. It is built on top of NumPy and serves as the standard tool for data preparation in the Python ecosystem.

Core Data Structures

- Series: A one-dimensional labeled array capable of holding any data type, such as integers, strings, or floating-point numbers.
- DataFrame: A two-dimensional, size-mutable, and potentially heterogeneous tabular data structure. It is essentially a collection of Series objects sharing the same index.

Pandas provides specific attributes to understand the structure and properties of a dataset:

- Shape: Represented as a tuple, it indicates the total number of rows and columns (e.g.(3, 2)).
- Dimensions (ndim): This attribute indicates the number of axes; DataFrames are 2D while Series are 1D.
- Size: This represents the total number of elements in the object, calculated as rows multiplied by columns.
- Columns: This attribute returns the labels of the columns, which is essential for accessing specific data subsets.

**Data Operations**

1. Updating and Modifying Data

DataFrames are mutable, allowing for real-time modifications:

- Accessing and Updating: Individual values can be modified using coordinate-based indexing like .loc[] (label-based) to target specific rows and columns.
- Adding Columns: New data can be integrated by assigning a list or Series to a new column label.
- Dropping Columns: The drop() method removes unnecessary data. Specifying axis=1 targets columns, while inplace=True modifies the original object directly.

2. Filtering Data

Filtering involves selecting a subset of data based on logical criteria, often referred to as Boolean Indexing:

- Conditional Selection: By passing a comparison operator (like > 99), Pandas creates a mask that selects only the rows where the condition is true.
- Applications: This is used to extract specific records, such as identifying high-performing students or outliers in a dataset.

3. Statistical Analysis

Pandas includes optimized, vectorized methods for descriptive statistics. Methods like mean(), max(), and min() can be applied to columns to provide immediate insights into numerical trends without the need for manual loops.

**Applications of Pandas**

- Data Cleaning: Handling missing values (NaN) and correcting data types.
- Financial Modeling: Analyzing historical trends and stock market data.
- Preprocessing: Preparing raw data for input into Machine Learning models.
- Database Management: Processing records queried from SQL databases.

**Conclusion**

The study of Pandas demonstrates its efficiency in managing structured data through Series and DataFrames. By utilizing metadata attributes like shape and size, we can audit data integrity, while modifying and filtering techniques allow for precise data extraction. Its built-in statistical functions make it superior to standard Python structures for analytical workflows.
