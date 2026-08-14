NumPy contains the `sqrt` function, which calculates and returns the elementwise square root of an array. The original array is not modified, and a new array is returned.

```py-cell
import numpy as np

x = np.array([1, 4, 9, 16])
np.sqrt(x)
print(x)
```