# patterns-3
a=[]
for i in range(3):
  x=[]
  for j in range(3):
    x.append("*")
  a.append(x)
print(a)
for i in a:
  print(*i,sep=" ")
