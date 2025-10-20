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
```
import pandas as pd
import numpy as np
exam_data = {'name': ['Kimnamjoon', 'Suga', 'Jungkook', 'Jimin', 'J Hope'],'score': [12.5, 9, 16.5, np.nan, 9],
    'attempts': [0, 3, 2, 3, 2],'qualify': ['yes', 'no', 'yes', 'no', 'no']}
labels=[1,2,3,4,5]
print(pd.DataFrame(exam_data,index=labels))
```

## Output
<img width="765" height="151" alt="image" src="https://github.com/user-attachments/assets/d7b4d9a5-e001-492d-bbf0-77fc19472c48" />

## Result
Thus,to create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is executed successfully.
