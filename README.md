sp = [1, 6, -7, 0, 37]
sp1 = [8, 9, 12, -2, 6, 1]
sp2 = []
for i in sp:
    sp2.append(i)
for i in sp1:
    sp2.append(i)
print(sp2)
sp2 = []
for i in sp:
    sp2.append(i)
for i in sp1:
    if (i not in sp2):
        sp2.append(i)
print(sp2)
sp2 = []
for i in sp:
    if (i in sp1):
        sp2.append(i)
print(sp2)
sp2 = []
for i in sp:
    if (i not in sp1):
        sp2.append(i)
for i in sp1:
    if (i not in sp):
        sp2.append(i)
print(sp2)
sp2 = []
mini = min(sp)
maxi = max(sp)
mini1 = min(sp1)
maxi1 = max(sp1)
sp2.append(mini)
sp2.append(maxi)
sp2.append(mini1)
sp2.append(maxi1)
print(*sp2)
