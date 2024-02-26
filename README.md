# basic-libraries
# Statistics Module:
import statistics as st
data = [5, 4, 1, 3, 2, 4, 5, 4, 5, 6]
print('Mean: ', st.mean(data))
print('Median: ', st.median(data))
print('Mode: ', st.mode(data))
print('Variance: ', round(st.variance(data),2))
print('Standard Deviation: ', round(st.stdev(data),2)) 

# Math module:
import math
#constants
print("Exponential value: ", math.e)
print("Pi value: ",math.pi)
print("Infinite value: ", math.inf)
print("Not a number value: ", math.nan)
#methods
print("Logarithmic: ", math.log(math.e))
print("factorial of 5 is", math.factorial(5))
print("GCD of 64 and 42 is", math.gcd(64,42))
print("Floor of 5.67 is", math.floor(5.67))
print("Ceil of 5.67 is", math.ceil(5.67)) 

# Numpy module:
import numpy as np
#Creating arrays
ar1d = np.arange(11,17)
ar2d = np.arange(11,36).reshape(5,5)
print("1-D array is:")
print(ar1d)
print("2-D array is:")
print(ar2d)
#Properties
print("ar1d shape, size, dimensions are", ar1d.shape, ar1d.size,
ar1d.ndim)
print("ar2d shape, size, dimensions are", ar2d.shape, ar2d.size,
ar2d.ndim)
#indexing
print("Indexing on ar1d:", ar1d[2],ar1d[-2])
print("Indexing on ar2d:", ar2d[2][1],ar2d[1][1])
#slicing
print("Slicing on ar1d:", ar1d[2:6])
print("Slicing on ar2d:")
print(ar2d[1:4,2:4])
