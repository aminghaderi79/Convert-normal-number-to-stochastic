# Convert-normal-number-to-stochastic!
import numpy as np
import random
num = np.random.rand(1,8)
print(num)
x=8
v=0.5


a=np.zeros(x)
for i in range(x) :
   
 if (num[i].all() > float(v)) :
    a[i]=1
    
 else:
    a[i]=0

 num = random.random()    

print(a)
