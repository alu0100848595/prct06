#! encoding: UTF-8
#! /usr/bin/python 
def aproxpi(fin):
 f=1
 while n>0 and f==1:
  f+=1
  suma=0
  for i in range (1,n+1):
   a=float(i-1)/fin
   b=float (i)/fin
   x_i=float(i-0.5)/fin
   fx_i=float (4)/(1+x_i*x_i)
   suma+=fx_i
  aprox=suma/fin
 return aprox
n=int(raw_input("Introduzca el numero de intervalos:"))
veces=int(raw_input("Introduzca el numero de veces:"))
l=[]
for i in range (1,veces+1):
 n*=veces
 s=aproxpi(n+1)
 l=l+[s]
print l