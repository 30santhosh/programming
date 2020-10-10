# programming
SE ASSIGNMENT:
Version 1.0:
Basic program for implementing quadratic equation.
a=5, b=20, c=10
d= (b*b)-(4*a*c) 
r1= (((-b)+sqrt (d))/(2*a)) 
r2= (((-b)-sqrt(d))/(2*a)) 
print ("the roots are: %f and %f" %(r1,r2))
Version 1.1:
Modified program of Version 1.0 as to know real roots and imaginary 
roots
a=1, b=4, c=5
d= (b*b)-(4*a*c)
if (d>0):
 print ("roots are real")
r1= (((-b)+sqrt(d))/(2*a))
 r2= (((-b)-sqrt(d))/(2*a))
 print ("the roots are: %f and %f" %(r1,r2))
elif(d<0):
 print ("roots are imaginary")
 r1=r2=(-b/(2*a))
 r=(sqrt(-d))/(2*a)
 print ("r1= %.2f + %.2f i and r2= %.2f - %.2f i"%(r1,r,r2,r))
Version 1.2:
Modified program of Version 1.1 to further know that the real roots 
are equal or distinct 
a=1, b=2, c=1
d= (b*b)-(4*a*c)
if (d>0):
 print("roots are real and distinct")
 r1=(((-b)+sqrt(d))/(2*a))
 r2=(((-b)-sqrt(d))/(2*a))
 print("the roots are: %f and %f" %(r1,r2))
elif(d<0):
 print("roots are imaginary")
 r1=r2=(-b/(2*a))
 r= (sqrt(-d))/(2*a)
 print("r1= %.2f + %.2f i and r2= %.2f - %.2f i"%(r1,r,r2,r))
else:
 print("roots are equal")
r1=r2=(-b/(2*a))
 print("r1= %.2f and r2= %.2f "%(r1,r2))
Version 1.3:
Modified program of Version 1.2 to specify divide by zero error if the 
divisor part is equals to zero
a=0, b=2, c=1
d=(b*b)-(4*a*c)
if(a==0):
 print("divide by zero error")
else:
 if(d>0):
 print("roots are real")
 r1=(((-b)+sqrt(d))/(2*a))
 r2=(((-b)-sqrt(d))/(2*a))
 print("the roots are: %f and %f" %(r1,r2))
 elif(d<0):
 print("roots are imaginary")
 r1=r2=(-b/(2*a))
 r=(sqrt(-d))/(2*a)
 print("r1= %.2f + %.2f i and r2= %.2f - %.2f i"%(r1,r,r2,r))
else:
 print("roots are equal")
 r1=r2=(-b/(2*a))
 print("r1= %.2f and r2= %.2f "%(r1,r2))
Version 1.4:
Modified program of Version 1.3 to accept inputs from user either as 
integer or floating point.
print("enter the values of a,b,c")
a=b=c=float(input())
d=(b*b)-(4*a*c)
if(a==0):
 print("divide by zero error")
else:
 if(d>0):
 print("roots are real")
 r1=(((-b)+sqrt(d))/(2*a))
 r2=(((-b)-sqrt(d))/(2*a))
 print("the roots are: %f and %f" %(r1,r2))
 elif(d<0):
 print("roots are imaginary")
 r1=r2=(-b/(2*a))
 x=(sqrt(-d))/(2*a)
print("r1= %.2f + %.2f i and r2= %.2f - %.2f i"%(r1,x,r2,x))
 else:
 print("roots are equal")
 r1=r2=(-b/(2*a))
 print("r1= %.2f and r2= %.2f "%(r1,r2))
