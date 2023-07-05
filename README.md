# BlockGame
# cook your dish here
t=int(input())
while t:
    x=list(input())
    if(list(x)==list(reversed(x))):
        print('wins')
    else:
        print('loses')
    t-=1
        
