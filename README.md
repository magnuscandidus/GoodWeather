# GoodWeather
# cook your dish here
t=int(input())
while t:
    x=list(map(int,input().split()))
    y=0
    n=0
    for i in range (len(x)):
        if(x[i]==1):
            y+=1
        else:
            n+=1
    if(y>n):
        print('yes')
    else:
        print('no')
    t-=1
