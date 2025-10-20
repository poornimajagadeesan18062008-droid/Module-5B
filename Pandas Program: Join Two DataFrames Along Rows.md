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
```
import pandas as pd
student_data1 = {
    'id': [1, 2, 3],
    'name': ['KimNamjoon', 'MinYoongi', 'Kimtaehyung'],
    'marks': [85, 90, 78]
}
df1 = pd.DataFrame(student_data1)
student_data2 = {
    'id': [4, 5, 6],
    'name': ['JungHoseok', 'Seok Jin', 'JeonJungkook'],
    'marks': [88, 92, 80]
}
df2 = pd.DataFrame(student_data2)
combined_df = pd.concat([df1, df2], axis=0,ignore_index=True)
print("Combined DataFrame:\n")
print(combined_df)

```


## Output
<img width="576" height="211" alt="image" src="https://github.com/user-attachments/assets/96fa04bf-503a-47b7-a334-dd0e84827d99" />

## Result
Thus,to write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is executed successfully.
