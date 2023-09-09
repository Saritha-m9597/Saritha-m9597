def recur_factorial(n):
  if (n == 1):
    return 1
  else:
    return n * recur_factorial(n-1)
num = int(input("enter a number"))
print("factorial is", recur_factorial(num))
