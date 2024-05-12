# Read-from-CSV

## AIM:
To read the contents from a csv file.

## ALGORITHM:
### Step 1:
Start the program.
### Step 2:
Create a file nba.csv in anaconda navigator.
### Step 3:
Write a program to read the contents in the csv file.
### Step 4:
Run the program.
### Step 5:
Print the output.

## PROGRAM:
 To write a python program for reading content from a csv file
 
                                               #Developed by: SADHANA SHREE B
                                               #Register number: 212223230177

                                           import pandas as pd
                                           df=pd.read_csv('nba.csv')
                                           print(df.head(10))
                                           print(df.tail())
                                           print("Number of rows:",len(df.axes[0]))
                                           print("Number of columns:",len(df.axes[1]))
## OUTPUT:
![Screenshot 2024-05-12 165312](https://github.com/SadhanaShreee/Read-from-CSV/assets/144517664/ff4dfb71-e86f-4e8e-9b5a-1b9f76b4424b)

## RESULT:
Hence, the contents are read successfully.
