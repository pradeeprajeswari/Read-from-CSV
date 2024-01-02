# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import the pandas library as "pd".

### Step 2:
Read the CSV file "nba.csv" using read_csv() method and assign it to the variable "df".

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.

### Step 5:
Print the output and end the program.

## PROGRAM:
```
#Program to read contents from a csv file
#Developed by : PRADEEP E
#RegisterNumaber : 212223230149
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```
## OUTPUT:
![Screenshot 2024-01-02 085302](https://github.com/pradeeprajeswari/Read-from-CSV/assets/145743112/656da74e-5a6c-47c9-99e0-1212d58aa98f)

## RESULT:
This python program run successfully.
