# SolubilityCheck
# cook your dish here
t=int(input())
while t:
    x,a,b=map(int,input().split())
    print((a+(100-x)*b)*10)
    t-=1
