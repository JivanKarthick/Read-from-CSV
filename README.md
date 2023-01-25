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

![output](/read.png)

## RESULT:
