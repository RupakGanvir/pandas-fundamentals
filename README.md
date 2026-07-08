# Pandas Fundamentals

A beginner-friendly Pandas learning repository covering the essential concepts required for Data Analysis, Machine Learning, and Artificial Intelligence.

---

## Topics Covered

- Creating DataFrames
- DataFrame Attributes (`head`, `tail`, `info`, `describe`, etc.)
- Indexing and Slicing
  - Using Column Names
  - Label-based Indexing (`loc`)
  - Position-based Indexing (`iloc`)
- Converting DataFrames to Arrays
- Basic Operations (`isnull`, `value_counts`, `unique`, Boolean Filtering)
- Reading Different Data Sources (`read_csv`, `StringIO`, `usecols`, `dtype`, `sep`)
- Saving Data to CSV (`to_csv`)
- Adding and Dropping Columns and Rows
- Sorting (`sort_values`, `sort_index`)
- Missing Data Handling (`dropna`, `fillna`, `ffill`, `bfill`, `interpolate`)
- Data Type Conversion (`astype`, `pd.to_numeric`)
- `apply()`, `map()` and `transform()`
- Merging and Joining DataFrames (`merge`, `concat`)
- GroupBy
- Aggregation (`agg`, custom aggregation functions)
- String Operations (`str` accessor)
- DateTime Handling (`pd.to_datetime`, `dt` accessor, `resample`, `rolling`)
- Window Functions (`rolling`, `expanding`, `ewm`)
- Pivot Tables and Cross-tabulation
- Key Takeaways

---

## Learning Outcomes

After completing this notebook, you will be able to:

- Create and manipulate Pandas DataFrames and Series efficiently.
- Index and slice data using column names, `loc`, and `iloc`.
- Load data from CSV files and in-memory sources with full control over dtypes and columns.
- Handle missing data using drop, fill, and interpolation strategies.
- Apply custom transformations using `apply()`, `map()`, and `transform()`.
- Combine DataFrames using SQL-style joins with `merge()` and stacking with `concat()`.
- Aggregate and summarize data using `GroupBy` and `agg()`.
- Work with string columns using the `str` accessor.
- Parse and manipulate datetime data using `pd.to_datetime()` and the `dt` accessor.
- Compute rolling, expanding, and exponentially weighted statistics for time-series analysis.
- Build pivot tables and cross-tabulations to summarize categorical data.
- Build a strong Pandas foundation for Scikit-learn, feature engineering, and data pipelines.

---

## Repository Structure

```text
.
├── Pandas_Fundamentals.ipynb
└── README.md
```

---

## Prerequisites

Install the required libraries:

```bash
pip install pandas numpy
```

or

```bash
conda install pandas numpy
```

---

## Author

**Rupak Ganvir**

---

⭐ If you found this repository helpful, consider giving it a star.
