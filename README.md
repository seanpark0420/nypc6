a = input()
b = input()
cnt=0
for i in range(int(a)):
    f[i] = input()
for i in range(int(a)):
    for j in range(i):
        for k in range(j):
            if a == f[i]+f[j]+f[k]:
                cnt=cnt+1:
