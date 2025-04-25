# teja
a=1
b=2
a,b=b,a
print(a,b)
\\
nestnum=[[1,2],[3,4],[5,6]]
print(nestnum[1])
print(nestnum[2][0])
print(nestnum[1][1])
\\
a=-23
b=2
print("a:",a)
print("b:",b)
temp=a
a=b
b=temp
print("a:",a)
print("b:",b)
\\
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a+b
b=a-b
a=a-b
print("after swapping:")
print("a:",a)
print("b:",b)
\\
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print("after swapping")
print("a:",a)
print("b:",b)
\\
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print("after swapping")
print("a:",a)
print("b:",b)
\\
fruits=['apple','mango','cherry']
print(fruits)
print(fruits[1])
fruits[2]='banana'
print(fruits)
print(fruits[-1:-2])
\\
nums=[0,1,2,3,4,5,9,8,7,6]
print(len(nums))
#slicing method
nums=[0,1,2,3,4,5]
print(len(nums))
print(nums[3:6])
print(nums[:3])
print(nums[::2])
print(nums[::-1])
print(4 in nums)
