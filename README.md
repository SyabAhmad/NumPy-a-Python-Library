# playground-ta42be1o
Tech.io playground
# Welcome!

NumPy  a Python Library


```python runnable
print('Hello World: we will gonna talk about NumPy  which is a library of Python!')
```


# declaring new array and  printing array elements


```python runnable
import numpy as np
print("Numpy library in python")
# declaring new array
data = np.array([1,2,3,4,5,6,7])
# printing array elements
print(data)
```


# adding two arrays
```python runnable
# adding two arrays
data1 = np.array([7,4,3,2,1,8, 9])
data3 = data+data1
print(data3)
```

# full is used for creating multi D array of your own choice elements
```python runnable
# full is used for creating multi D array of your own choice elements
values = np.full([5,5],0)
print(values)

# all elemnts should be xero
values = np.zeros([9,9])
print(values)

# all elemnts should be ONES now
values = np.ones([3,3])
print(values)
print("\n\n")


dta = np.full([5,5],9)
print(dta)
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
