# count
num=[]
count = 0
for x in range(1,10):
	num.append(input())
print(num)	
for x in num:
	if int(x) > 10:
		count=count+1
print('total values greater than 10 are :',count)
