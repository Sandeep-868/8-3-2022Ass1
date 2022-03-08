# 8-3-2022Ass1
x=input()
x=x.lower()
l=list(x)
c=0
for i  in l:
    if i!='a' and i!='e' and i!='i' and i!='o' and i!='u' and i!=' ': 
        c+=1 
print(c)
