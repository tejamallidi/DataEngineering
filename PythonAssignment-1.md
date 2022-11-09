## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?
A. Python is easy to code resembling english and it will be in human understandable format and translates to assembly language equivalent during execution.

Q2. Why is Python called a dynamically typed language?
A. There is no restriction of declaring a specific data type to a variable. Hence we can re-assign any variable to a different data type.

Q3. List some pros and cons of Python programming language?
A. Easy to learn and use. Slightly slower than C++.

Q4. In what all domains can we use Python?
A. We can use python for web-development(backend), Data Science, Automation.

Q5. What are variable and how can we declare them?
A. Variable is a container to store a value of any data type. Example declaration -> num = 9

Q6. How can we take an input from the user in Python?
A. We can use input function to take user input -> input('Enter your name - ')

Q7. What is the default datatype of the value that has been taken as an input using input() function?
A. String is the default datatype of the value received from input function.

Q8. What is type casting?
A. Converting a variable of one datatype to another datatype is called type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A. Yes it is possible to take more than one value using a single input function by using split() on the input() => input().split(separator, maxsplit)

Q10. What are keywords?
A. Keywords are some pre-defined words used for a specific purpose in a programming language, which cannot be used as variable names.

Q11. Can we use keywords as a variable? Support your answer with reason.
A. We cannot use keywords as a varible name, since they will be interpreted for a specific purpose.

Q12. What is indentation? What's the use of indentaion in Python?
A. Indentation is defined number of spaces left (4 spaces in general) for each line of code to make the interpreter identify the code as intended.

Q13. How can we throw some output in Python?
A. We can use print() to display the output in the console.

Q14. What are operators in Python?
A. Operators are pre-defined symbols/keywords used for performing a specific operation. Example: Arthmetic operators(+,-,_,/,%), Logical operators(and,or,not), Comparison operators(<,>,!=,==,<=,>=) and others like Assignment operators(+=,-=,_=....)

Q15. What is difference between / and // operators?
A. / refers to float division(gives the quotient as a float number) and // refers to integer division(rounds the quotient to the lower bound)

Q16. Write a code that gives following as an output.
A. name='iNeuron' print(name\*4)

```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
A. num=int(input('Enter a number'))
if (num % 2) == 0:
print('even')
else:
print('odd')

Q18. What are boolean operator?
A. boolean operators or otherwise called as logical operators perform logical operations like and, or, not

Q19. What will the output of the following?

```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Need more info for this question.

Q20. What are conditional statements in Python?
A. "if, elif, else" are conditional statements

Q21. What is use of 'if', 'elif' and 'else' keywords?
A. To conditionally process the execution to meet a certain condition we use the above keywords.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
A. age=int(input('Enter your age'))
if age >= 18:
print('I can vote')
elif age < 18:
print("I can't vote")
Q23. Write a code that displays the sum of all the even numbers from the given list.

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

sum = 0
for num in numbers:
if num%2 == 0:
sum += num
print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A. num1 = int(input('Enter number1 '))
num2 = int(input('Enter number1 '))
num3 = int(input('Enter number1 '))
print(max(num1,num2,num3))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

A. for num in numbers:
if num > 500:
break
elif num > 150:
continue
elif num % 5 == 0:
print('Number divisible by 5 ', str(num))
