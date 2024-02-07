# Indexing-numpy-ML
Indexing using an index array.
//#Indexing using an index array
import numpy as np
#Create a sequence of intergers from 10 to 1 with a step -2
a = np.arange(10,1,-2) # store in variable a
print("\n sequential with a negative step:\n",a)  # print sequential
#Indexes are specified inside the np.array method.
newarr = a[np.array([3,1,2])] #storing in new arr
print("\nElements at these indices are:\n",newarr)# print array
o/p
A sequential array with a negative step:
[10 8 6 4 2]
Elements at these indices are:
[4 8 6]
