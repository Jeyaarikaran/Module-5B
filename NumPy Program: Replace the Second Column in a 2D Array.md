# Pandas Program:T o carry out the Division mathematics operations for the following two series a1 and a2

## 🎯 Aim:
To perform element-wise division between two Pandas Series using vectorized operations.


## 🧠 Algorithm
1.Import the pandas library.

2.Create two series, a1 and a2, from the given lists.

3.Perform division using a1 / a2.

4.Display the result.
## 🧾 Program :
```.py
import pandas as pd
a=eval(input())
b=eval(input())
print("Division of Series1 by Series2:")
a1=pd.Series(a)
a2=pd.Series(b)
print(a1/a2)
```


## Output :
![image](https://github.com/user-attachments/assets/50afc751-d0a5-43dd-bcd9-be3b384da38d)


## Result :
The program correctly performs element-wise division of the two series and displays the floating-point results.

