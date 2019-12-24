
# The calculation of the standard deviation using two different methods
First method

list = [1, 5 ,2 ,7 ,1 ,9 ,3 ,8 ,5, 9]
result = (sum([(x-(sum(list) / len(list)))^2 for x in list ])/(len(list)-1))^0.5

Second method involves the use NumPy module 

import numpy as np
a = [1, 5, 2, 7, 1, 9, 3, 8, 5, 9]
print(np.std(a,ddof=1))
