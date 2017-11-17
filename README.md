L=[first,*args]
def min1(L):
    res=first
    for i in L[1:]:
        if res>i:
            res=i
            
 L1=[2,5,9,-1,35,6]
 print(min1(L1))
    
