NumPy contains the `sqrt` function, which calculates and returns the elementwise square root of an array. The original array is not modified, and a new array is returned. For example, for an array of positive numbers:

```py-cell
import numpy as np

x = np.array([1, 4, 9, 16])
print(np.sqrt(x))
print(x)
```

The values returned will be floats even if all square roots are expressible as integers.

# Negative Numbers

If any numbers are negative, the `sqrt` function will return `nan` for those values.

```py-cell
import numpy as np

x = np.array([-1, 0, 1])
print(np.sqrt(x))
```