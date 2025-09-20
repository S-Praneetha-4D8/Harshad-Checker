num=int(input('enter a number:'))
copy=num
sum=0
while copy!=0:    #copy>0
    r=copy%10
    sum+=r
    copy//=10
print('sum=',sum)
if num%sum==0:
    print("harshad/niven")
else:
    print("not Harshad/niven")
