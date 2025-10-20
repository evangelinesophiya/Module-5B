# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
~~~
import pandas as pd
dict1 = eval(input())
dict2 = eval(input())
df1 = pd.DataFrame(dict1)
df2 = pd.DataFrame(dict2)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
joined_df = pd.concat([df1, df2], axis=1)

print("\nJoin the said two dataframes along columns:")
print(joined_df)
~~~

## Output
<img width="1119" height="676" alt="Screenshot 2025-10-20 154259" src="https://github.com/user-attachments/assets/c6a75b2d-26b5-4301-b9e1-b3cc6f33c907" /><img width="863" height="668" alt="Screenshot 2025-10-20 154312" src="https://github.com/user-attachments/assets/fe46b262-5c5b-4ad5-88e5-2a0507d72a2c" />


## Result
Thus , the program has been executed succesfully.
