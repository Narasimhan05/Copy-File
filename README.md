# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
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
### Program for copying the contents from one file to another file
### Developed by: NARASIMHAN S
#RegisterNumber: 212223230133
```
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:

![image](https://github.com/Narasimhan05/Copy-File/assets/132819871/c8a10e07-a552-43c8-8fb0-0320cb38ebaa)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
