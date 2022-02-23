# feb-23-ass-1
Assignment-1
l=[]
n=int(input('enter n'))
for i in range (n):
    e=int(input())
    l.append(e)
min=l[0]
for i in range (1,n):
    if l[i]<min:
        min=l[i]
print('min num is',min)
max=l[0]
for i in range (1,n):
    if l[i]>max:
        max=l[i]
print('max num is',max)
