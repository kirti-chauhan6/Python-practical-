# Python-practical- 1
import cmath

a = float(input("Enter coefficient a: "))
b = float(input("Enter coefficient b: "))
c = float(input("Enter coefficient c: "))

d = (b**2) - (4*a*c)

root1 = (-b + cmath.sqrt(d)) / (2*a)
root2 = (-b - cmath.sqrt(d)) / (2*a)

print(f"\nThe quadratic equation is: {a}x² + {b}x + {c} = 0")

print(f"The roots are: {root1} and {root2}")
