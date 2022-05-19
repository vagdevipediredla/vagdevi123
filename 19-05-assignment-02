import numpy as np
n=int(input("enter range:"))
primes=[]
for a in range(2,n+1):
    maxint=int(np.sqrt(a))+1
    for i in range(2,maxint):
        if (a%i==0):
            break
        else:
            primes.append(a)
print(sum(primes))
