# Data Manipulation with Numpy
## edutative.io 
### Code snippets and random code for learning
#### Numpy Arrays

```python
import numpy as np

arr = np.array([[0, 1, 2], [3, 4, 5]],
               dtype=np.float32)
print(repr(arr))
```
```console
array([[0., 1., 2.],
       [3., 4., 5.]], dtype=float32)
```

#### Numpy Basics

```pyhton
arr = np.arange(5)
print(repr(arr))

arr = np.arange(5.1)
print(repr(arr))

arr = np.arange(-1, 4)
print(repr(arr))

arr = np.arange(-1.5, 4, 2)
print(repr(arr))
```

```console
array([0, 1, 2, 3, 4])
array([0., 1., 2., 3., 4., 5.])
array([-1,  0,  1,  2,  3])
array([-1.5,  0.5,  2.5])
```