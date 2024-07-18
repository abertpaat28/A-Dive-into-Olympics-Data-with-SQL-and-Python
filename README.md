---

I leveraged an Olympics [Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) from Kaggle website and then enriched it with country details from a MariaDB SQL database.  
I explored the data to uncover interesting insights and create interactive visualizations. You may view the python [code](https://github.com/abertpaat28/A-Dive-into-Olympics-Data-with-SQL-and-Python/blob/main/python%20notebook.ipynb) here. 🏆

![image](https://github.com/user-attachments/assets/c0c097ea-af21-406d-b119-483b51cca7ed)

---
**Here’s an overview of the tasks I performed:**  
- Combine different data sources using SQL & Python  
- Perform basic exploratory analysis using pandas  
- Learn how to use Plotly to easily create interactive visualizations  

---
## ⚙️ Python Functions
`info()` to inspect the data types and the number of non-null  
`isna()` and `.sum()` to easily inspect the number of missing values per column  
`value_counts()` inspect the unique items by frequency  
`to_frame()` to convert a pandas Series into a DataFrame  
`str.split()` to split a string into a list of substrings based on the specified delimiter  
`unique()` to retrieve the unique values  
`merge()` to combine DataFrames  
`groupby()` to group data based on one or more columns  
`count()` to group data based on specified criteria  
`query()` to filter rows based on conditions  
`sort_values()` to sort DataFrames based on specified column(s)  
`show()` to display data or visualizations  
`first()` to select the first occurrence of a value  
`px.line()` to create line plots  
`px.chloropleth()` is a powerful visualization tool that displays statistical information on a geographic map, where each region (such as a county or state) is colored based on a numeric variable  


## 🛢 SQL Functions
`SELECT` to retrieve data from one or more tables  
`AS` to assign an alias (alternate name) to column or table  
`FROM` to specify the table(s) from which we want to retrieve the data  
`JOIN` to combine rows from two or more tables based on a related column  
`ON` is used with the JOIN keyword. It specifies the condition for joining the tables based on a common column  

