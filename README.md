# 1sttry
import numpy as np
a=b=np.zeros(32000000)
c=0
for k in range(4000):
    for l in range(4000):
        c += 1
        n=k*k+l*l
        a[n]=1
        b[c]=n
#c=0
b=np.unique(b)
