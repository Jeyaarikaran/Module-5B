## NumPy Program:Create a numPy program for the following problem statement.

## 🎯 Aim :
To read nine space-separated integers from user input and convert them into a 3×3 NumPy array.

## 🧠 Algorithm :
1.Import the NumPy module.

2.Take a single line of input (nine integers separated by spaces).

3.Convert the input string to a list of integers using map().

4.Use np.array() to convert the list to a NumPy array.

5.Use .reshape(3, 3) to convert it into a 3×3 array.

6.Print the resulting array.

## 🧾 Program :
```.py
import numpy as np
a=list(map(int,input().split()))
arr=np.array(a)
new=arr.reshape((3,3))
print(new)
```


## Output :
![image](https://github.com/user-attachments/assets/c4931f77-d694-4eaf-a1ef-0a03813add20)


## Result :
The program successfully takes a list of 9 integers and converts it into a 3×3 NumPy array.
