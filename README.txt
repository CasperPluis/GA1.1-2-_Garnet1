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
