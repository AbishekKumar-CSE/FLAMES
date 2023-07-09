s1=input("Enter Your Name :")
s2=input("Enter Your's Name :")

F=[3,5,14,16,18]
L=[10,19]
A=[8,12,13,17]
M=[6,11,15]
E=[2,4,7,9,20]
S=[1]

lenn=s1+s2

l1=list(s1)
l2=list(s2)

tl=len(lenn)

cont=0

for i in l1:
    for j in l2:
        if i==j:
            cont+=2
            l2.remove(j)
            break
        
#print(l2)
#print(cont)
ls=tl-cont
#print(ls)
if ls in F:
    print(s2,"is your Friend \U0001F607")
elif ls in L:
    print(s2,"is your Lover \U0001F60D")
elif ls in A:
    print(s2,"is your Affection \U0001F929")
elif ls in M:
    print(s2,"gonna Marriage with you\U0001F618")
elif ls in E:
    print("I am your Enemy \U0001F92B")
else:
    print("Siblings")
