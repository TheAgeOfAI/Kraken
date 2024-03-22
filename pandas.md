# Pandas

- Day 1-2: Introduction to Pandas: understanding Series and DataFrame objects, installing Pandas, and basic data manipulation operations.

- Day 3-4: Indexing and selecting data: using loc, iloc, and Boolean indexing to select rows and columns from DataFrames.

- Day 5-7: Data cleaning and preprocessing: handling missing values, removing duplicates, and performing basic data cleaning operations.

    import pandas as pd


### `DataFrame`

- A DataFrame is a 2-dimensional data structure that can store data of different types in columns.

- To create `DataFrame` we use:

```
    df = pd.DataFrame(
        {
            "Name": [
                "Braund, Mr. Owen Harris",
                "Allen, Mr. William Henry",
                "Bonnell, Miss. Elizabeth",
            ],
            "Age": [22, 35, 58],
            "Sex": ["male", "male", "female"],
        }
    )
```

- Each column in a `DataFrame` is a `Series`.

- To create a `Series` we use:

```
    ages = pd.Series([22, 35, 58], name="Age")
```

- To access a `Series` we use:

```
    df['Age']
```

- A pandas `Series` has no column label or row label.

### Methods

1. max()
    It can be used on Series or `DataFrame` to get max element.

2. describe()
    The describe() method provides a quick overview of the **numerical** data in a `DataFrame`

3. reas_csv()
    It is used to read data stored as a csv file into a pandas as a `DataFrame`.

    Similar methods are available to read data as a `DataFrame`.

    **read_sql(), read_json(), read_excel()** and so on...

4. df.head(N)

    To see the first N rows of `DataFrame`.

5. df.tail(N)

    To see the last N rows of `DataFrame`

6. df.dtypes

    For each of the columns, the used data type is enlisted.

7. to_excel()

    Used to convert `DataFrame` to an excel file.

    Unlike cvs it has a attribute sheet_name since excel file contain sheets.

    `df.to_excel("excel.xlsx", sheet_name="passengers", index=False)`

8. info()

    provides technical information about a `DataFrame`.

9. 
