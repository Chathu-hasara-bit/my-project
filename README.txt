Hello world
Python programming
#Find factorial of a number
N=int(input('Enter no:'))
Fac=1
if N<0:
    Print ("Factorial does not exist")
else:
    for i in range(1,N+1):
        Fac=Fac*i
    print ("Factorial of the",N,"is",Fac)
