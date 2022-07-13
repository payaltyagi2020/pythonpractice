# pythonpractice
for i in range(8):
    for j in range(26):
        if (j in range(3,5)) or (j in(9,10,15,16,18,19)):
            print("*",end=" ")
        elif (i in(0,1)  and j in range(0,8)) or (i in(3,4) and j in range(11,15)) or (i in(0,1,6,7) and j in range(20,26)) or (i in(3,4) and j in (20,21) ):
             print("*",end=" ")    
        else :
            print(" ",end=" ")
    print()
