# Read-from-CSV

## AIM:
To write a python program for read from CSV

## ALGORITHM:
### Step 1:
Get the file name as the input from the use
### Step 2:
Open the file using the import function
### Step 3:
Print the program
### Step 4:
End the program

## PROGRAM:
```python
Developed by : Rama E.K. Lekshmi
Ref No : 22009028
import pandas as import pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```
## OUTPUT:
![](csv.jpeg)

## RESULT:
Thus the program is written to read from the contents from CSV file executed successfully