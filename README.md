# Date:
# Ex.No: 10 Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1: 
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
##### Developed by : MONISH N
##### Register Number: 212223240097
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-11-11 204106](https://github.com/user-attachments/assets/da800279-7b64-4e2b-9f18-6415ebb887dd)

![Screenshot 2024-11-11 204116](https://github.com/user-attachments/assets/e9b1cc9f-7c36-4ca1-b393-cdb86b32aec6)

## RESULT: 
Thus the program is written to read the csv file.
