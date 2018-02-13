# branch yaptım

def fib(x):
  a,b,c=1,0,1
  d=[]
  while a<x:
    b,c=c,b+c
    a+=1
    d.append(c)
  print(d)
  
