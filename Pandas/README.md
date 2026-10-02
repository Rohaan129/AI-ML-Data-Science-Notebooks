# Pandas Practice Notebook

A hands-on walkthrough of Pandas, from creating Series and DataFrames to cleaning, reshaping, aggregating, reading and writing data, and plotting. Each topic pairs a short explanation with runnable code.

## What's inside

| Section | Topics |
|---|---|
| Basics | Series, DataFrames, loading data, selecting and filtering |
| Rows & Columns | Adding, selecting and dropping rows and columns |
| Indexing & Selecting | `[]`, `.loc[]`, `.iloc[]`, `.at[]`, `.query()`, slicing |
| Missing Data | `isnull()`, `notnull()`, `fillna()`, `replace()`, `interpolate()`, `dropna()` |
| Iteration | `iterrows()`, `itertuples()`, `items()`, column iteration |
| Index Methods | `set_index()`, `reset_index()`, Series index attribute |
| Filtering | Boolean indexing with multiple conditions, `query()`, `eval()` |
| Combining Data | `concat()`, `merge()`, `join()` and join types |
| Sorting & Pivot Tables | `sort_values()`, `sort_index()`, `pivot_table()` |
| Reading & Writing Files | CSV (`read_csv` parameters, `to_csv`), JSON (including nested), Excel, text files (`read_table`, `read_fwf`) |
| Data Cleaning | `drop_duplicates()`, `astype()`, `to_datetime()`, dropping empty columns, mixed data types |
| String Operations | `.str` methods (lower, upper, strip, split, replace, count, find, ...) |
| Normalization | Max-abs, min-max and z-score scaling |
| GroupBy & Aggregation | Split-apply-combine, `agg()`, `transform()`, `filter()` |
| Correlation | `corr()` with Pearson and Spearman methods |
| Visualization | Line, area, bar, histogram, scatter, box, hexbin, KDE, pie plots |
| Time Series | Date ranges and basic time series manipulation |

## Running it

From the repo root:

```bash
pip install -r requirements.txt
cd Pandas
jupyter notebook Pandas.ipynb
```

## Data files

The notebook loads these files by name, so they must sit in this folder next to `Pandas.ipynb`:

| File | Used in |
|---|---|
| `data.csv` | Intro: loading data |
| `nba.csv` | Rows/columns, indexing, iteration, slicing |
| `employees.csv` | Missing data |
| `people_data.csv` | `read_csv()` parameters |
| `data.json` | Reading JSON |
| `students.xlsx` | Working with Excel |
| `gfg.txt`, `GeeksforGeeks.txt` | Reading text files |
| `df1`, `df2` | Plotting with Pandas |

Other files the notebook produces itself while running (`file1.csv`, `users.csv`, `your_name.csv`, `output.json`, `Output File.xlsx`, and so on) don't need to be included.

## Credits

Several examples and datasets (such as `nba.csv` and `people_data.csv`) come from GeeksforGeeks tutorials and were reworked into my own notes.
