NumPy contains several functions relating to basic numeric operations which will be carried out elementwise on arrays. 

# Powers

```py-cell
import numpy as np

a = np.array([-2, 0, 3])
print("Absolute Value:", np.abs(a)) # The magnitude of each element (with any negative signs removed)
print("Sign:", np.sign(a)) # The sign of each element (-1 for negative, 0 for zero, 1 for positive)
print("Round Down:", np.floor(a)) # The largest integer less than or equal to each element
print("Round Up:", np.ceil(a)) # The smallest integer greater than or equal to each element
print("Round Nearest:", np.rint(a)) # The nearest integer to each element
print("Truncation:", np.trunc(a)) # The integer part of each element

a = np.array([1, 4, 8.5])
print("Square Root:", np.sqrt(a)) # The (positive) square root of each element

a = np.array([1, 8, -4])
print("Cube Root:", np.cbrt(a)) # The (real) cube root of each element
print("Square:", np.square(a)) # The square of each element
```