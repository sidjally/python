## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
	Python is used to build in wide variety of application domains as well the code is converted into bytecode that is then executed by Python virtual machine
	
Q2. Why is Python called a dynamically typed language?

	Type of the variable is determined during run time.

Q3. List some pros and cons of Python programming language?

	Python is a popular programming language that offers ease of use,readibility. Limitations are it is sometimes slower
	compared to other compiled languages, memory management issues , dynamic typing and version compatibility.

Q4. In what all domains can we use Python?

	developing websites and software,task automation , data analyis and visualisations.

Q5. What are variable and how can we declare them?

	variable are used to store values in memory locations.
	x = 45
	
Q6. How can we take an input from the user in Python?
	We can take input from user by using input keyword.
	x = input("Please provide your name")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
	String 
Q8. What is type casting?
	To convert one data type to another. 
	e.g. convert string data type to number
	
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
a,b = input("Enter two values").split(",")
print("Number of 1",a)
print("Number of 2",b)
Q10. What are keywords?
keywords are reserved words that cannot be used as a variable name
Q11. Can we use keywords as a variable? Support your answer with reason.
No. As keywords are used reserved for python. 
Q12. What is indentation? What's the use of indentaion in Python?
Identation refers to the spaces at the beginning of a code line.It is used to help python interpreter that the group of statements belong to a particular block.
and to 
Q13. How can we throw some output in Python?
by using print function
Q14. What are operators in Python?
	Arithmetic, comparison 
Q15. What is difference between / and // operators?
/ is used for divison of two numbers.
// is used to obtain smallest integer nearest to the quotient 
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
print(iNeuron*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

def evenodd(x):
	if x%2==0:
	 print("Number is even")
	else:
     print("Number is odd")

try:	 
	a=int(input("Please input any number : "))
	print(evenodd(a))
except:
    print("No characters are allowed")	

Q18. What are boolean operator?
Boolean operator are used when we require true or false results

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
1

0

False

1

Q20. What are conditional statements in Python?
Conditional statements allows us to make decisions based on variables or comparison.
Q21. What is use of 'if', 'elif' and 'else' keywords?
	 These are conditional statements and used in executing bunch of statements 
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
	try:
		a=input("Please provide the age: ")
		if a >= 18
		 print("I can vote")
		else:
		 print("I can't vote")	
	except:
		print("Provide the age in number")
		
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
a=[]
for i in range(0,len(numbers)-1):
 if numbers[i]%2==0:
  a.append(numbers[i])

sum(a)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
x = float(input("Enter first number : "))
y = float(input("Enter second number : "))
z = float(input("Enter third number : "))

if (x > y) and (x > z):
	print(x)
elif (y > x) and (y > z):
    print(y)
else:
	print(z)

	
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
a=[]
for i in numbers:
 if i > 150:
  if i > 500:
   break
 elif i%5==0:
  a.append(i)

print(a)  

Q26. What is a string? How can we declare string in Python?
	String are arrays of bytes representing Unicode characters.It is used for data manipulation.
	It can be declared with single or double quotes
	
Q27. How can we access the string using its index?
	 In square brackets by mentioning position
Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"

string[9:16]
```

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"

string[15:8:-1]
```

Q30. Resverse the string given in the above question.
string[::-1]
Q31. How can you delete entire string at once?
del(string)
Q32. What is escape sequence?
Escape sequence is used to insert characters which are not allowed in a string. back slash is used as escape character sequence
Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
print("\'iNeuron\'s Big Data Course'")

Q34. What is a list in Python?
Lists are used to store multiple items in a single variable
Q35. How can you create a list in Python?
a=["ws","rt","yt"]
Q36. How can we access the elements in a list?
a[0]
Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
lst[4][2]

Q38. Take a list as an input from the user and find the length of the list.
n = input("Enter the number of elements separated by comma").split(",")
print(len(n))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
lst.insert(2,"Big")

Q40. What is a tuple? How is it different from list?
Tuple is used for collection of data similar like list. It is different from list when values are required to be unchanged
and it used less memory 
Q41. How can you create a tuple in Python?
It is created with square brackets
a=t('1','4','a')
Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
Once tuple is created, we cannot add or delete values from tuple as it is immutable object
Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Yes, we can append 2 tuples.
e=('1','2','r')
e1=('12','4','rt')
e+e1
Q44. Take a tuple as an input and print the count of elements in it.
n = tuple(input("Enter the number of elements separated by comma").split(","))
print(len(n))
Q45. What are sets in Python?
set is a collection of data which is iterable, mutable and does not have duplicate elements
Q46. How can you create a set?
Using curl brackets.
a={'1','2','3'}
Q47. Create a set and add "iNeuron" in your set.
b=('iNeuron')
Q48. Try to add multiple values using add() function
b.add('u')
b.add('p')
Q49. How is update() different from add()?
in add() you can use only 1 element whereas in update() we can add multiple element.
Q50. What is clear() in sets?
it is used to remove all elements.
Q51. What is frozen set?
Frozen sets are immutable objects that only support methods and operators that produce a result without affecting the frozen sets.

Q52. How is frozen set different from set?
Frozenset are immutable whereas sets are mutuable.Sets cannot be used in dictionary whereas frozenset can.
Q53. What is union() in sets? Explain via code.
It will club both the sets
a={'1','2','3'}
b={'4','5','6'}
print(a.union(b))
Q54. What is intersection() in sets? Explain via code.
It gives common elements in the multiple sets.
a.intersection(b)

Q55. What is dictionary ibn Python?
It is a collection of key value pair. 
a=dict({x:'1',y:'2'})
Q56. How is dictionary different from all other data structures.
Dictionary stores keys and value of it in pairs, whereas other structures has value.
Q57. How can we delare a dictionary in Python?
we can declare dictionary in curl brackets.
Q58. What will the output of the following?
```
var = {}
print(type(var))
```
dict
Q59. How can we add an element in a dictionary?
by assiging values to the key.
dict1={}
dict1['etr']='Teor'
Q60. Create a dictionary and access all the values in that dictionary.
Dict1 ={"q1":"1","q2":"2","q3":"3"}
for i,j in Dict1.items():
 print(i,j)
Q61. Create a nested dictionary and access all the element in the inner dictionary.
Dict1 ={"q1":"1","q2":"2","q3":"3"}
Dict2 = {}
Dict2[0]=Dict1
Dict2[1]="Ert"

for i,j in Dict2.items():
 print(i,j)

Q62. What is the use of get() function?
It is used to retrieve the value of the keys.
Q63. What is the use of items() function?
items provides key and it's values 
Q64. What is the use of pop() function?
It is used to remove the key value from dict
Dict2 = {0: {'Q': 'P', 'E': t, 'Re': 'Pe'}, 1: 'Rock'}
Dict2.pop(0)

Q65. What is the use of popitems() function?
Popitems removes last values from the dictionary
Q66. What is the use of keys() function?
Keys method returns all the keys in the dictionary
Dict2 = {0: {'Q': 'P', 'E': t, 'Re': 'Pe'}, 1: 'Rock'}
print(Dict2.keys())
Q67. What is the use of values() function?
Values method returns all the values of the keys in the dictionary
Dict2 = {0: {'Q': 'P', 'E': t, 'Re': 'Pe'}, 1: 'Rock'}
print(Dict2.values())

Q68. What are loops in Python?
Loops can be used to execute multiple statements
Q69. How many type of loop are there in Python?
for & while loop
Q70. What is the difference between for and while loops?
for loop is based on iteration whereas while loop runs till the conditions is true
Q71. What is the use of continue statement?
Continue statement forces the execution to next iteration of the loop while skipping the rest of the code
Q72. What is the use of break statement?
break statement stops the execution when a condition is meet
Q73. What is the use of pass statement?
it is used when there is no code to write in loops,if functions to avoid errors
Q74. What is the use of range() function?
Rnge function is used to provide sequence of numbers using loops.
Q75. How can you loop over a dictionary?
By using for loop
Dict1 ={"q1":"1","q2":"2","q3":"3"}
Dict2 = {}
Dict2[0]=Dict1
Dict2[1]="Ert"

for i,j in Dict2.items():
 print(i,j)

### Coding problems
Q76. Write a Python program to find the factorial of a given number.
def fact(n):
 if n<0:
  return 0
 elif n ==0 or n ==1:
  return 1
 else:
  try:
   fa=1
   for i in range(1,n+1):
    fa=fa*i
		  
   print(fa)
  except:
   print("Please provide only integers")	

print(fact(n))


Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
def func_SI(P,R,T):
 P=float(P)
 R=float(R)
 T=float(T)
 try:
  SI=0
  SI=(P*R*T)/100
  return SI
 except:
  print("Please provide only integers")	

print(func_SI(300,5,3))

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
def func_CI(P,R,T):
 P=float(P)
 R=float(R)
 T=float(T)
 try:
  CI=0
  CI=P*(1+R/100)**t-P
  return CI
 except:
  print("Please provide only integers")	

print(func_CI(300,5,3))

Q79. Write a Python program to check if a number is prime or not.
def func_prime(n):
 if(n>1):
  for i in range(2,int(n/2)+1):
   if (n%i ==0):
    print(n,"is not a prime number")
    break
   else:
    print(n,"is a prime number")
 else:
  print(n,"is not a prime number")
  
Q80. Write a Python program to check Armstrong Number.

def fun_armstrong_chk(n):
 ns=str(n)
 a=len(ns)
 sum=0
 for i in ns:
  sum=sum+ int(i)**a
  
 if sum==n:
  return True
 else:
  return False
  
print(fun_armstrong_chk(1634))

Q81. Write a Python program to find the n-th Fibonacci Number.
def Fibonacci(n):
 if n < 0:
  print("Incorrect input")
 elif n == 0:
  return 0
 elif n == 1 or n == 2:
  return 1
 else:
  return Fibonacci(n-1) + Fibonacci(n-2)

print(Fibonacci(6))

Q82. Write a Python program to interchange the first and last element in a list.
def interchange(a):
 a1=len(a)
 x=a[0]
 y=a[a1-1]
 a[0]=y
 a[a1-1]=x
 return a

n=[1,2,4,5,6,7,8]
print( interchange(n))
Q83. Write a Python program to swap two elements in a list.
def swap_elements(n, n1,n2):
 n[n1],n[n2]=n[n2],n[n1]
 return n
 
x = [1,2,3,4,5,6,7,8]

print(swap_elements(x,2,6))

Q84. Write a Python program to find N largest element from a list.
def max_elements(lst,N):
 d_lst=[]
 for i in range(0,N):
  m1=0
  
  for j in range(len(lst)):
   if lst[j]>m1:
    m1=lst[j]

  lst.remove(lst[j])
  d_lst.append(lst[j])
  
 print(d_lst)
 
 N=4
 list1=[2,6,3,7,57,35,192]
 
  
Q85. Write a Python program to find cumulative sum of a list.

def cummulative_fn(list1):
 d_list=[]
 j=0
 for i in range(0,len(list1)):
  j+=list1[i]
  d_list.append(j)

 print(d_list)
 
 list1=[2,6,3,7,57,35,192]
 
 print(cummulative_fn(list1))
 
Q86. Write a Python program to check if a string is palindrome or not.
def fn_palindrome(a):
...  if a == a[::-1]:
...   return f"{a} is palindrome"
...  else:
...   return f"{a} is palindrome"


Q87. Write a Python program to remove i'th element from a string.
def remove_element(i):
 str1 = "Python is tough"
 str2 = ""
 for j in range(len(str1)):
  if j == i:
   continue
  else:
   str2 = str2 +str1[j]
 
 return str2

print(remove_element(4))
   
Q88. Write a Python program to check if a substring is present in a given string.
def chk_str(str1,str2):
 if str1.count(str2) > 0:
  print(f'"{str2} is a substring of {str1}"')
 else:
  print(f'"{str2} is not a substring of {str1}"')

s1="Lord is my shepard"
s2="shepard"

chk_str(s1,s2)

Q89. Write a Python program to find words which are greater than given length k.
def chk_string_greater_k(str1,k):
 e_str=[]
 sp_str = str1.split()
 for i in sp_str:
  if len(i) > k:
   e_str.append(i)

 return e_str

chk_string_greater_k("Lord is my shepard",3)

Q90. Write a Python program to extract unquire dictionary values.

dict1 = {'A' : [1, 3, 5, 4],
             'B' : [4, 6, 8, 10],
             'C' : [6, 12, 4 ,8],
             'D' : [5, 7, 2]}

print("The original dictionary is : " ,dict1)
res = list(sorted({u for val in dict1.values() for u in val}))
print(res) 

Q91. Write a Python program to merge two dictionary.
def fn_merge(d1,d2):
 return(d1.update(d2))

d1={'a':1,'b':2}
d2={'c':3,'d':4}

print(fn_merge(d1,d2))

print(d1)

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
a1=[('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
print(dict(a1))


Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
res = [(x,pow(x,3)) for x in list]
print(res)
Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
t1 = [(a,b) for a in test_tuple1 for b in test_tuple2]
t2 = [(a,b) for a in test_tuple2 for b in test_tuple1]

t1+t2

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```