# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner


## ALGORITHM:

### Step 1:

Import pandas as pd.
### Step 2:

Read the CSV file using read_csv method.
### Step 3:

Use len() method to get the number of rows and columns

### Step 4:

Use len() method to get the number of rows and colu
### Step 5:

Print the output.

## PROGRAM:

```python

To write a python program for reading content from a CSV file.
Developed by:  Jivan Karthec.B.S
Register Number: 22004763

import pandas as pd
df=pd.read_csv('Downloads/nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))

```

## OUTPUT:
![ggg](https://user-images.githubusercontent.com/121165867/214647545-720f5977-ea96-4ecf-a760-bc9fdb7f67c7.png)
![fff](https://user-images.githubusercontent.com/121165867/214647651-da272d51-b44f-45e5-93ee-bfefe6c644c5.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file
