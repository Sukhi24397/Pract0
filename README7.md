EXPERIMENT 7:

AIM:

To study and understand the use of looping statements in Python for executing a block of code repeatedly based on a given condition.

THEORY:

Loops in Python are control flow statements that allow a block of code to be executed repeatedly until a specific condition is satisfied.
They help in reducing redundancy in programs by eliminating the need to write the same statements multiple times.
Python supports two main types of loops: for loop and while loop, each used for different purposes.
The for loop is used when the number of iterations is known in advance. It is commonly used to iterate over sequences such as lists, tuples, strings, dictionaries, and ranges.
The range() function is often used with the for loop to generate a sequence of numbers for iteration.
The while loop is used when the number of iterations is not known beforehand and depends on a condition. The loop continues to execute as long as the condition evaluates to True.
If the condition in a while loop never becomes false, it results in an infinite loop, which can be avoided by proper condition handling.
Python provides nested loops, where one loop is placed inside another loop. Nested loops are useful for working with multi-dimensional data such as matrices and patterns.
Loop control statements are used to change the normal flow of execution of loops:
break is used to terminate the loop immediately.
continue is used to skip the current iteration and move to the next one.
pass is used as a placeholder when no action is required.
Python also supports the else clause with loops, which executes when the loop completes normally without encountering a break statement.
Proper indentation is mandatory in Python loops, as it defines the block of code to be executed within the loop.
Loops play an important role in data processing, searching, sorting, and performing repetitive calculations.
Using loops improves program efficiency, readability, and maintainability.


#PROBLEM:
n = int(input("Enter a number:"))
fact = 1
while n>0:
  fact *= n
  n -= 1
print("Factorial =", fact) 

ALGORITHM: 
Start.
Read an integer n from the user.
Initialize a variable fact to 1.
While n is greater than 0, do the following:
Multiply fact by n and store the result in fact.
Decrease the value of n by 1.
Repeat step 4 until n becomes 0.
Display the value of fact as the factorial of the given number.
Stop.

#PROBLEM:
limit = int(input("Enter limit:"))
a = 0
b = 1
while a <= limit:
  print(a, end=" ")
  a, b = b, a + b 

ALGORITHM: 
Start.
Read an integer limit from the user.
Initialize the first term a as 0 and the second term b as 1.
While a is less than or equal to limit, perform the following steps:
Display the value of a.
Update the values of a and b as a = b and b = a + b (using simultaneous assignment).
Repeat step 4 until the value of a becomes greater than limit.
Stop.  

#PROBLEM:
# Reverse of a number

num = int(input("Enter a number:"))
rev = 0
while num > 0:
  digit = num % 10
  rev = rev * 10 + digit
  num //=10
print("Reversed number =", rev) 

ALGORITHM: 
Start.
Read an integer num from the user.
Initialize a variable rev to 0.
While num is greater than 0, perform the following steps:
Find the last digit of num using digit = num % 10.
Update rev by multiplying it by 10 and adding digit (rev = rev × 10 + digit).
Remove the last digit from num using integer division (num = num // 10).
Repeat step 4 until num becomes 0.
Display the value of rev as the reversed number.
Stop.

#PROBLEM:
# Check Palindrome number/string

num = int(input("Enter a number:"))
temp = num
rev = 0
while num > 0:
  rev = rev * 10 + num % 10
  num //=10
if temp == rev:
    print("Palindrome")
else:
    print("Not Palindrome") 

ALGORITHM: To Check Whether a Given Number is a Palindrome
Start.
Read an integer num from the user.
Store the value of num in a temporary variable temp.
Initialize a variable rev to 0.
While num is greater than 0, perform the following steps:
Find the last digit of num using num % 10.
Update rev as rev = rev × 10 + (num % 10).
Remove the last digit of num using integer division (num = num // 10).
Repeat step 5 until num becomes 0.
Compare temp and rev:
If temp is equal to rev, display "Palindrome".
Otherwise, display "Not Palindrome".
Stop.


#PROBLEM:
#check palindrome string
st = input("Enter a string:")
rev =st[::-1]
if st==rev:
  print("Palindrome")
else:
  print("Not Palindrome") 

ALGORITHM: To Check Whether a Given String is a Palindrome
Start.
Read a string st from the user.
Reverse the string using slicing and store it in the variable rev.
Compare the original string st with the reversed string rev:
If st is equal to rev, display "Palindrome".
Otherwise, display "Not Palindrome".
Stop.

#PROBLEM:
s = "madam"
i, j = 0, len(s) - 1
is_palindrome = True
while i < j:
  if s[i] != s[j]:
    is_palindrome = False
    break
  i += 1
  j -= 1
if is_palindrome:
   print("Yes")
else:
    print("No") 

 ALGORITHM: To Check Whether a Given String is a Palindrome Using While Loop
Start.
Initialize a string s with a given value.
Set two variables i = 0 and j = length of string − 1.
Initialize a flag variable is_palindrome to True.
While i is less than j, perform the following steps:
If the character at position i is not equal to the character at position j, then:
Set is_palindrome to False.
Exit the loop using break.
Otherwise, increment i by 1 and decrement j by 1.
After the loop ends, check the value of is_palindrome:
If is_palindrome is True, display "Yes".
Otherwise, display "No".
Stop.

#PROBLEM:
#Count digits in a number
num = int(input("Enter a number:"))
count = 0
while num > 0:
  count += 1
  num= num// 10

print("Number of digits =", count) 

ALGORITHM: To Count the Number of Digits in a Given Number
Start.
Read an integer num from the user.
Initialize a variable count to 0.
While num is greater than 0, perform the following steps:
Increment count by 1.
Remove the last digit of num using integer division (num = num // 10).
Repeat step 4 until num becomes 0.
Display the value of count as the number of digits in the given number.
Stop.

#PROBLEM:
#search element in list
nums = [10,20,30,40,50]
key = int(input("Enter element to search: "))
i = 0
while i < len(nums):
  if nums[i] == key:
    print("Element found at index", i)
    break

  i += 1

else:
  print("Element not found")  


  ALGORITHM: To Search an Element in a List Using While Loop
Start.
Initialize a list nums with given elements.
Read the element key to be searched from the user.
Initialize an index variable i to 0.
While i is less than the length of the list, perform the following steps:
If the element at index i is equal to key, then:
Display "Element found at index i".
Exit the loop using break.
Otherwise, increment i by 1.
If the loop completes without finding the element, execute the else block and display "Element not found".
Stop.


#PROBLEM:
#search element in list
nums = [10,20,30,40,50]
key = int(input("Enter element to search: "))
i = 0
while i < len(nums):
  if nums[i] == key:
    print("Element found at index", i)
    break

  i += 1

else:
  print("Element not found")  GIVE #print odd numbers
i = 0
while i < 10:
  i += 1
  if i % 2 == 0:
    continue
  print(i) 


  ALGORITHM 1: To Search an Element in a List Using While Loop
Start.
Initialize a list nums with given elements.
Read the element key to be searched from the user.
Initialize an index variable i to 0.
While i is less than the length of the list, perform the following steps:
If nums[i] is equal to key, then:
Display "Element found at index i".
Exit the loop using break.
Otherwise, increment i by 1.
If the loop completes without finding the element, execute the else block and display "Element not found".
Stop.

#PROBLEM:
#print odd numbers
i = 0
while i < 10:
  i += 1
  if i % 2 == 0:
    continue
  print(i) 


  ALGORITHM: To Print Odd Numbers from 1 to 10 Using While Loop
Start.
Initialize a variable i to 0.
While i is less than 10, perform the following steps:
Increment i by 1.
Check if i is even (i % 2 == 0):
If true, skip the current iteration using continue.
If i is odd, print the value of i.
Repeat step 3 until i becomes 10.
Stop.



CONCLUSION
Thus, loops in Python help in performing repetitive tasks efficiently and simplify program structure by reducing redundant code.
