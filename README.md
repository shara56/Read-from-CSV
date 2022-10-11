# Read-from-CSV

## AIM:
To read and process the CSV file
## ALGORITHM:
### Step 1:Import pandas as pd
### Step 2:Open the file in read mode
### Step 3:Print the first 9 and the tail
### Step 4:Print the rows
### Step 5:Print the columns

## PROGRAM:
```python
#Developed by: Sharangini TK
#Register num: 22003363
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![CSV](https://user-images.githubusercontent.com/113497104/195035408-dd31d74d-c6bf-480d-ba3b-6d57b27d172b.png)

## RESULT:
Hence the program is executed.
