# Algorithm

1. Create a sql file
2. Create a python script to read sql file
3. Create a python script to create a dataframe

# Python Script algorithm
## Function 1
1. Set an empty list: list = []
2. Read sql file: with open('path/file.sql','r',encoding='utf-8') as file:
3. loop to append the empty list
    ```bash
    for line in file:
      sql.append(line)
    ```
4. Convert to string the list: variable = """""".join(list)
5. Return variable: return variable

## Function 2
1. Create the dataframe: df = pd.read_sql_query(select_statement,connection)
2. return df
