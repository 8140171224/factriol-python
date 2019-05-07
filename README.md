# define function fact(n):
    def fact(n):
# variable  f  is equal to  value 1 
    f = 1
# For loop for Factorial in Python
    for i in range(1, n+1):
        f = f*i
    return f
# x is value for main.py
    x = 4
# call function
    result = fact(x)
    print(result)
