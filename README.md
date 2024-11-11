## Date:
# Exp-12: Read-from-CSV

## AIM: 
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1: Load the CSV into a DataFrame.
### Step 2: Print the number of contents to be displayed using df.head().
### Step 3: The number of rows returned is defined in Pandas option settings.
### Step 4: Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
Developed by : SURIYA M

Register Number: 212223110055
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/f2809d30-cc28-4fa7-be69-3883bdb5eacd)
![image](https://github.com/user-attachments/assets/77e8cc67-7344-476f-8a8c-e5a41df83576)




## RESULT:

Thus the program is written to read the csv file.
