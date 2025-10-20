# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
~~~
import pandas as pd
import numpy as np
data = eval(input())
labels=eval(input())
df = pd.DataFrame(data, index=labels)
print(df)
~~~

## Output



<img width="1130" height="389" alt="Screenshot 2025-10-20 185900" src="https://github.com/user-attachments/assets/41e9ded3-f6c4-4aa2-9513-64794751ee6a" /><img width="1134" height="394" alt="Screenshot 2025-10-20 185918" src="https://github.com/user-attachments/assets/41d530e0-4f74-4eca-8be2-a0990e5294d1" /><img width="1134" height="398" alt="Screenshot 2025-10-20 185933" src="https://github.com/user-attachments/assets/86d212be-00a1-4b24-a663-0367009ec8a9" />



## Result
Thus , the program has been executed succesfully.
