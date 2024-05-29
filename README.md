# Wholesale Data Analysis
My coding project uses Pandas to explore, transform , summarize, and analyze wholesale customer data. 

## Throughout this experience we learned how to:
1) Use describe and columns functions
2) Filter queries in simpler and more specific ways
   * `loc` and `iloc`: filter data by condition/index
   * `value_counts`: counts occurances of each unique value
   * `head(n)`: only display first `n` rows
   * 'nlargest(number, column)': retrieve top number values in column
   * 'concat': combines DataFrames or Series objects along the x or y axis
   * 'reset_index':
4) Manipulate data by inserting, deleting, updating
   * `df['new_col'] = df['col1'] * df['col2']: create new column from existing columns.
   * `drop`: remove rows/columns
   * 'sort_values': return a new dataframe with sorted data  
5) Summarize and present data in human readable
   * `df['col'].apply(formatter)`: pass name of function or lambda to format `col`
   * Used a for loop to redefine the names of the columns
6) Creating DataFrames
   * `read_csv('csv_file')`: create dataframe from `csv_file`
   * `df[['col1', 'col2', 'col3']]`: create new dataframe with 3 columns from existing frame.
