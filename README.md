# my-project
N=int(input('Enter no:'))
Fac=1
if N<0:
    Print ("Factorial does not exist")
elif N==0 :
    Print("Factorial = 1")
else:
    for i in range(1,N+1):
        Fac=Fac*i
    print ("Factorial",N,"=",Fac)
