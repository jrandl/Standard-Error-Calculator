# Standard-Error-Calculator
This is a calculator that can compute the Standard Error. Input p or the percentage in decimals. Input n or the total number as a whole number.

from math import *

print('Please enter p or percent in decimal:')
p = float(input())
print('Please enter n or size:')
n = int(input())
se: float = sqrt(((p * (1 - p)) / n))
print(se)
