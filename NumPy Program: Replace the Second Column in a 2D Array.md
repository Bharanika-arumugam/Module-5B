# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that find the sum of Second column in a given numpy array.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.

3.Reshape the NumPy array into a 4×3 matrix.

4.Extract the second column of the reshaped matrix.

5.Compute the sum of all elements in that second column.

6.Display the reshaped matrix.

7.Display the sum of the second column.

8.End

## 🧾 Program
``` python
import numpy as np
arr = np.array(eval(input()))
a=arr.reshape(4,3)
column_sums=sum(a[:,1])
print(a)
print(column_sums)
```
## Output
![image](https://github.com/user-attachments/assets/7786746f-e9e2-4c59-8355-f1533cc56671)

## Result
Thus the python program to  find the sum of Second column in a given numpy array is executed successfully.
