# Solution to Simple Calculator ✨🚀

The focus will be on `calculator.py` for adding funtion body and after that test each function with equivalent `test_FUNCTION_NAME.py`. So there are two main steps for the solution which are:

### 🔹Step 1️🔹

* Add
```python
def add(x, y):
    return x + y
```

* Subtract
```python
def subtract(x, y):
    return x - y
```

* Multiply
```python
def multiply(x, y):
    return x * y
```

* Divide
```python
def divide(x, y):
    if y == 0:
        return "Invalid value for denominator, cant't divide by 0!"
    return x / y
```

* Square
```python
def square(x):
    return x ** 2
```

* Power
```python
def power(x, y):
    return x ** y
```

* Square Root
```python
def sqrt(x):
    return x ** (1/2)
```

### 🔹Step 2🔹

Start testing the functions in `calculator.py` by using pytest; use pip to install `requirements.txt`.

```bash
$ py.test test_add.py 
$ py.test test_subtract.py
$ py.test test_multiply.py
$ py.test test_divide.py
$ py.test test_square.py
$ py.test test_power.py
$ py.test test_sqrt.py
```
