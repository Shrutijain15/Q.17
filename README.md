# Q.17-a-
num=int(input("Enter a number : "))
temp=num
rev=0
while(num>0):
  dig=num%10
  rev=rev*10+dig
  num=num//10

if(temp==rev):
  print("the no is palindrome")
else:
  print("not a palindrome")
