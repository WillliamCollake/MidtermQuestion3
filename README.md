# MidtermQuestion3
Problem 3
def evalQuadratic(a, b, c, x):
return a*x*x + b*x + c
def twoQuadratic(a1, b1, c1, x1, a2, b2, c2, x2):
x = evalQuadratic(a1, b1, c1, x1)
y = evalQuadratic(a2, b2, c2, x2)

print (x+y)
