n=int(input('enter n value:'))
A=97
for i in range(1,n+1):
    for j in range(1,n+1):
        print(chr(A),end=" ")
        A += 1 
    print("\n")
