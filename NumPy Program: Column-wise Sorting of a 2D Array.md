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
```
import numpy as np
r= int(input())
c= int(input())
el= []
for i in range(r):
    a = list(map(int, input().split()))
    el.append(a)
arr = np.array(el)
s= np.sort(arr, axis=0)
print("Original Array:")
print(arr)
print("Sorted Array:")
print(s)


```

## Output
<img width="412" height="288" alt="image" src="https://github.com/user-attachments/assets/0e783cb4-143a-46cc-8355-18b72b29f4a6" />

## Result
Thus,to write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
