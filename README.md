# Stepik_-
Практические задания

import numpy as np

arr = np.array([[10, 60]
                ,[7, 50]
                ,[12, 75]])

X = arr[:, 1]
y = arr[:, 0]

b1, b0 = np.polyfit(X, y, 1)
print(b0, b1)
