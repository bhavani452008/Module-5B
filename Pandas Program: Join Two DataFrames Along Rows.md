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
import numpy as np
data = {
  'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 
           'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
  'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
  'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
  'qualify': ['yes', 'no', 'yes', 'no', 'no', 
              'yes', 'yes', 'no', 'no', 'yes']
}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']
df = pd.DataFrame(data, index=labels)
print(df)
```

## Output
<img width="933" height="407" alt="image" src="https://github.com/user-attachments/assets/1add3698-c7df-466d-8944-f92dac82816d" />


## Result
