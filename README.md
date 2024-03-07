n=int(input())
a=list(map(int,input().split()))
res=0
for i in range(n):
  if a[i]%2==0:
    res=res+i
print(res)
