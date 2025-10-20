# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
~~~
import numpy as np
d=eval(input())
arr=np.array(d)
print("Given array")
print(f" {arr}")

print(f"\n{np.sort(arr,axis=0)}")
~~~

## Output
![WhatsApp Image 2025-10-20 at 15 53 28_ccbaac98](https://github.com/user-attachments/assets/6c108513-51b9-4fbe-8ea1-3f3561128532)

## Result
Thus , the program has been executed succesfully.
