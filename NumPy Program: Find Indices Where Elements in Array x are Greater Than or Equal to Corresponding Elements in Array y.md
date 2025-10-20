# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
~~~
import numpy as np
x=eval(input())
y=eval(input())
a=np.array(x)
b=np.array(y)
g=np.where(a>b)
equal=np.where(a==b)
print(g)
print(equal)
~~~

## Output
![WhatsApp Image 2025-10-20 at 18 39 20_b5546eb5](https://github.com/user-attachments/assets/53d089ac-2d75-42ec-8270-831ad94bbb27)

## Result
Thus , the program has been executed succesfully.
