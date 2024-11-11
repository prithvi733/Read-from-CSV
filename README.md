# EX-12 Read-from-CSV

## AIM:
To read the csv file and bring it in the output

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
Print the output
## PROGRAM:
```
#Developed by:Prithviraj.V
#Register Number: 212222100038

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/cd143a2e-8d26-4c24-9778-54b205cbf765)

![image](https://github.com/user-attachments/assets/a1433690-1405-407e-92c8-f79b67401c70)


## RESULT:
The above data is the required result brought by reading the csv file.
