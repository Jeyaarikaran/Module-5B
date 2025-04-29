# NumPy Program: To Convert a 1-D array into a 2-D array with 3 rows
## 🎯 Aim :
To convert a 1-D NumPy array into a 2-D array with 3 rows.
## 🧠 Algorithm :
1.Import the NumPy library.

2.Define a 1-D NumPy array with 9 elements.

3.Use the reshape() function to convert it into a 2-D array with 3 rows and appropriate columns.

4.Print the original and reshaped arrays.


## 🧾 Program :
```.py
import numpy as np
l=eval(input())
print("The original array:")
arr=np.array(l)

print(f" {arr}")
print("\n3 x 3 Array:")
new=arr.reshape(3,3)
print(f" {new}")
```


## Output :
![image](https://github.com/user-attachments/assets/768e3cd3-b615-4bc5-b7d3-b0dedb26af6c)


## Result :
The program successfully converts a 1-D array into a 2-D array with 3 rows and displays it.
