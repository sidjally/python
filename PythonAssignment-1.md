## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

	Python is simple,easy to read syntax and logic can be built in fewer lines of code

Q2. Why is Python called a dynamically typed language?

	Type of the variable is determined only during runtime.
	

Q3. List some pros and cons of Python programming language?
	
	Pros - Beginner friendly,large community, flexible and extensible,extensive libraries,Highly scalable,IOT oppurtunities,portable
	Cons - Slower when compared java, security, high memory consumption
	
Q4. In what all domains can we use Python?
	
	Data Science, Machine learning,Deep learning,Artificial Intelligence,Networking, game development

Q5. What are variable and how can we declare them?
	
	Python variable are containers for storing data values. Basic unit of storage in a program
	Values are directly assigned to variable and type is determined at the time of execution
	e.g. x = 1

Q6. How can we take an input from the user in Python?

	x = input("What is your user id")

Q7. What is the default datatype of the value that has been taken as an input using input() function?

	String 

Q8. What is type casting?

	Conversion of one data type to another.
	e.g. convert string to number

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

	yes, we can have multiple inputs by using single input() with split function
		
		e.g. a,b = input("Enter 2  numbers").split()

Q10. What are keywords?
		
	 Python keywords are the reserved words which cannot be used as variable,function.	
		
Q11. Can we use keywords as a variable? Support your answer with reason.

	 No we cannot use keywords as a variable.These are used as function name, boolean.

Q12. What is indentation? What's the use of indentaion in Python?

	 Indentation refers to space at the beginning of a code line.It is used to indicate a block of code.
	 It is a way of telling a python interpreter that a group of statements belongs to a particular block of code
	 

Q13. How can we throw some output in Python?

		Using raise keyword
		raise TypeError("only numeric values are allowed")

Q14. What are operators in Python?

		Operators are used to perform operations on variable and values
		Arithmetic, comparison and logical

Q15. What is difference between / and // operators?
	 / is used for division which gives float type
	 // is also used for division which gives quotient round of to the closest number
		

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
print("iNeuron"*4)
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
		
try:

	nu=int(input("Please enter the number : "))
	
	if(nu % 2 ==0):
		print("Number is even !!")
	else:
		print("Number is odd ! ")

except:			
	print("Only integers are allowed !")			
			
		
Q18. What are boolean operator?
		These are used for logical operations like AND, OR for check conditions are met before execution of the program
			
Q19. What will the output of the following?
```
1 or 0 - 1

0 and 0 - 0

True and False and True  - False

1 or 0 or 0 - 1
```

Q20. What are conditional statements in Python?
		
		Program constructs that allow you to control the flow of the program based on the conditions defined
		
	

Q21. What is use of 'if', 'elif' and 'else' keywords?
		These are conditional statements to execute group of code

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
		
try:

	age=int(input("Please enter the number : "))
	
	if(age >= 18):
		print("I can vote !!")
	else:
		print("I can't vote ! ")

except:			
	print("Only integers are allowed !")
		
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum(list(filter(lambda x:(x%2==0),numbers)))

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
try:
	a =[]
	a1,a2,a3=int(input("Please enter the number 1 : ")).split()
	for i in (a1,a2,a3):
		a.append(i)
	
	print(max(a))
	
except:			
	print("Only integers are allowed !")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
nl=[]
n1 = list(filter(lambda x:x<=150,filter(lambda x:(x%5==0),numbers)))
print(nl)	
