# py-18
printing H shape pattern using python
n=5
for i in range(n):
	for j in range(n):
		if(j==n-1) or (i==n//2 or j==0 ):
		   print("*",end=" ")
		else:
			print(" ",end=" ")
	print()
