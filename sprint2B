import pandas as pd
import numpy as np

# 1) s1 adlı Series yaradın
s1 = pd.Series([10, 20, 30, 40])

# 2) s1-ə 'w', 'x', 'y', 'z' indekslərini təyin edin
s1.index = ['w', 'x', 'y', 'z']

# 3) dictionary-dən s2 adlı Series yaradın
s2 = pd.Series({'p': 5, 'q': 10, 'r': 15})

# 4) s2-dən 'q' indeksli elementi seçin
print("4)", s2['q'])

# 5) s1-dən 25-dən böyük elementləri seçin
print("5)", s1[s1 > 25])

# 6) s1-də 20-dən böyük elementləri 10-a bölün
print("6)", s1[s1 > 20] / 10)

# 7) ((1, 2), (3, 4)) listindən df1 adlı DataFrame yaradın
df1 = pd.DataFrame([(1, 2), (3, 4)])

# 8) df1-ə ('r1', 'r2') sətr və ('c1', 'c2') sütun adlarını təyin edin
df1.index = ['r1', 'r2']
df1.columns = ['c1', 'c2']

# 9) dictionary-dən df2 adlı DataFrame yaradın
df2 = pd.DataFrame({'A': [1, 2], 'B': [3, 4]})

# 10) df2-də 'A' sütunu 1-dən böyük olan sətirləri seçin
print("10)", df2[df2['A'] > 1])
