# to print positive numbers
n=int(input("enter no. of digits=" ))
lst1=[]
for i in range(n):
   value=int(input("enter any number="))
   lst1.append(value)
print("original_list=",lst1)
lst2=[]
for i in lst1:
    if(i>0):
        lst2.append(i)
print("positive_list=",lst2) 
