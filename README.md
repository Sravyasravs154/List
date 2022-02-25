# a=list()
n=int(input('enter size'))
print("enter number")
for i in range(int(n)):
    k=int(input(" "))
    a=append(k)
    
o=[]
e=[]
for i in a:
    if i%2==0:
        e.append(i)
    else:
        o.append(i)
for i in range(len(o)):
   print(o[i],end=' ')
print('  ',end='')
for i in range(len(e)):
   print(e[i],end=' ')
