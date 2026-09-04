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