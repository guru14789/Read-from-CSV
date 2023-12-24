# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2: 
Read the CSV file using read_csv method.
### Step 3: 
Use head and tail method to get the required contents from the file.
### Step 4: 
Use len() method to get the number of rows and columns
### Step 5: 
Print the output.

## PROGRAM:
```
Developed by: SREEKUMAR S
Register N0: 23008070

import pandas as pd
df = pd.read_csv("C:\\Users\\admin\\Downloads\\nba (1).csv")
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-24 212304](https://github.com/guru14789/Read-from-CSV/assets/151705853/ef3e8648-631a-4e6b-8217-3a6074104f90)

## RESULT:
Thus a Python program is written to read the contents of a CSV file.
