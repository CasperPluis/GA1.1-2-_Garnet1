### Subtraction Function

The `subtract()` function subtracts one number from another. It can be used whenever the difference between two numbers is needed.

The function may break or give an error if non-numeric values, such as text, are provided.

Example:

```python
def subtract(a, b):
    result = a - b
    return result

subtract(10, 4)  # Returns 6
```
## add(a, b)

Adds two numbers together and returns the result.

**Parameters:**
- `a`: first number (int or float)
- `b`: second number (int or float)

**Returns:** the sum of `a` and `b`

**When it might break:**
- Passing non-numeric types (e.g. strings, lists) will raise a `TypeError`
- Very large numbers may lose precision due to floating-point limitations

**Example:**
```python
add(2, 3)      # returns 5
add(-3, 5)     # returns 2
add(5, 8)      # returns 13
```
#Multiply 

The function is used when calculating the product between two numbers 

#when it might break 
If a or b is non-numeric types (e.g. strings, lists) will raise a `TypeError`

Example:
''' python
def multiply(a,b):
    result = a * b
    return result

multiply(1,2)  #returns 2
'''
