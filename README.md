# mFrac
**A Simple Fraction Python Library**

**Feature:**  
This Library implements 'frac' class.  
You can add, subtract, multiplicate, divide Fractions.

**how to install**: *pip install -i https://test.pypi.org/simple/ mfrac*


**Example Code:**

```python
from mfrac import frac
n = frac(1, 2)           #create 1/2
m = frac(m=3, n=2)       #you can set numerator to n, denominator to m
x = frac(8, 2).reduc()   #reduction of 2/8 (=1/4)
print(n+m)               #print "5/6"
print(1-m)               #print "1/3"
print(m*2)               #print "4/3"
print(n/2)               #print "1/4"
```
