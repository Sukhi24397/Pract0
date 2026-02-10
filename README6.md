Experiment 6:
 Study of conditional statements in python 

 AIM:
 
 To study and understand conditional statements in Python and to learn how decision-making is performed using if, if-else, and if-elif-else statements.

Theory :

Conditional statements in Python are used to control the flow of execution of a program based on certain conditions. They allow a program to make decisions and execute specific blocks of code only when particular conditions are satisfied.
In Python, a condition is an expression that evaluates to either True or False. These conditions are formed using relational operators such as greater than (>), less than (<), equal to (==), not equal to (!=), greater than or equal to (>=), and less than or equal to (<=). Multiple conditions can be combined using logical operators like and, or, and not.
Python follows indentation rules to define blocks of code for conditional statements. Proper indentation is mandatory; otherwise, the program will result in an error. This makes Python code more readable and structured compared to other programming languages.
Types of Conditional Statements:

if Statement:

The if statement is the simplest form of conditional statement. It executes a block of code only when the given condition evaluates to True. If the condition is False, the block of code is skipped.
if–else Statement:

The if–else statement provides an alternative path of execution. When the condition is true, the if block is executed; otherwise, the else block is executed. This helps in handling two possible outcomes.
if–elif–else Statement:

The if–elif–else statement is used when there are multiple conditions to be tested. Python checks the conditions from top to bottom and executes the block associated with the first condition that evaluates to True. If none of the conditions are true, the else block is executed.
Nested if Statement:

A nested if statement is an if statement placed inside another if or else block. It is used when decisions depend on multiple levels of conditions.
Importance of Conditional Statements

Enable decision-making in programs
Improve program efficiency and flexibility
Used in real-life applications such as grading systems, eligibility checks, and automation
Make programs more interactive and logical
Thus, conditional statements form a fundamental concept in Python programming and are essential for developing intelligent and responsive programs.

#1a. Check whether a number is positive, negative, or zero
num=int(input("enter a number"))
if num>0:
 print("positive")
elif num<0:
  print("negative")
else:
 print("zero")\

Algorithm: 
1.Start
2.Input an integer number num from the user.
3.Check if num > 0
4.If true, display “Positive”.
Else if num < 0
5.If true, display “Negative”.
6.Else
Display “Zero”.
7.Stop


#2. check whether a number is even or odd
num=int(input("enter a number: "))
if num%2==0:
   print("even")
else:
   print("odd")

Algorithm: 
1.Start
2.Input an integer number num from the user.
3.Check if num % 2 == 0
If true, display “Even”.
4.Else
Display “Odd”.
5.Stop



  
#3. find the largest of two numbers
a= int(input("enter first number:"))
b= int(input("enter second number:"))
c= int(input("enter third number:"))
if a>=b and a>=c:
  print("largest:",a)
elif b>=a and b>=c:
  print("largest:",b)
else:
  print("largest:",c) 

  Algorithm: 
1.Start
2.Input three integer numbers a, b, and c.
3.Check if a ≥ b and a ≥ c
If true, display a as the largest number.
4.Else if b ≥ a and b ≥ c
If true, display b as the largest number.
5.Else
Display c as the largest number.
6.Stop


     #4. get input from user for a subject and calculate grade using if-elif-else
marks=int(input("enter marks:"))
if marks>=90:
  print("grade A")
elif marks>=75:
  print("grade B")
elif marks>=60:
  print("grade C")
elif marks>=40:
  print("grade D")
else:
  print("fail") 

  Algorithm: 
1.Start
2.Input marks obtained by the student.
3.Check if marks ≥ 90
If true, display “Grade A”.
4.Else if marks ≥ 75
Display “Grade B”.
5.Else if marks ≥ 60
Display “Grade C”.
6.Else if marks ≥ 40
Display “Grade D”.
7.Else
Display “Fail”.
8.Stop


#5. check whether a year is a leap year
year= int(input("enter year:"))
if(year%400==0)or(year%4==0 and year%100!=0):
  print("leap year")
else:
  print("not a leap year")


     Algorithm: 
1.Start
2.Input the year from the user.
Check if
the year is divisible by 400
OR
the year is divisible by 4 and not divisible by 100.
3.If the above condition is true,
Display “Leap Year”.
4.Else,
Display “Not a Leap Year”.
5.Stop


#write a python program to increament the given date
# Input date
day = int(input("Enter day: "))
month = int(input("Enter month: "))
year = int(input("Enter year: "))

# Check leap year
if (year % 400 == 0) or (year % 4 == 0 and year % 100 != 0):
    leap = True
else:
    leap = False

# Increment date
if month == 2:
    if (leap and day == 29) or (not leap and day == 28):
        day = 1
        month = 3
    else:
        day += 1

elif month in [1, 3, 5, 7, 8, 10]:
    if day == 31:
        day = 1
        month += 1
    else:
        day += 1

elif month in [4, 6, 9, 11]:
    if day == 30:
        day = 1
        month += 1
    else:
        day += 1

elif month == 12:
    if day == 31:
        day = 1
        month = 1
        year += 1
    else:
        day += 1

# Output
print("Next date is:", day, "/", month, "/", year) 


Algorithm:
1.Start
2.Input day, month, and year from the user.
3.Check whether the given year is a leap year:
If the year is divisible by 400 or
If the year is divisible by 4 and not divisible by 100,
then set leap = True,
Else set leap = False.
4.Check the month:
If month is February (2):
If it is a leap year and day = 29, set day = 1 and month = 3.
If it is not a leap year and day = 28, set day = 1 and month = 3.
Otherwise, increment day by 1.
Else if month has 31 days (January, March, May, July, August, October):
If day = 31, set day = 1 and increment month by 1.
Else, increment day by 1.
Else if month has 30 days (April, June, September, November):
If day = 30, set day = 1 and increment month by 1.
Else, increment day by 1.
Else if month is December (12):
If day = 31, set day = 1, month = 1, and increment year by 1.
Else, increment day by 1.
5.Display the incremented date.
6.Stop


#write a python program to find vowels or consonants
ch=input("enter a character:")
if ch in'aeiouAEIOU':
   print("vowel")
else:
   print("consonant")



    Algorithm:
1.Start
2.Input a character ch from the user.
3.Check if ch belongs to the set {a, e, i, o, u, A, E, I, O, U}.
4.If the condition is true,
Display “Vowel”.
5.Else,
Display “Consonant”.
6.Stop



'''Problem statement:
write a python program to calculate the gross salary of an employee
if basic 10000:HRA <=20%,DA=80%
if basic 20000:HRA <=25%,da=90%
Otherwise:HRA 


Algorithm: 
1.Start
2.Input the basic salary of the employee.
3.Check the basic salary:
If basic salary ≤ 10000
Calculate HRA = 20% of basic salary
Calculate DA = 80% of basic salary
Else if basic salary ≤ 20000
Calculate HRA = 25% of basic salary
Calculate DA = 90% of basic salary
Else
Calculate HRA = 30% of basic salary
Calculate DA = 95% of basic salary
4.Calculate Gross Salary using the formula:
Gross Salary = Basic Salary + HRA + DA
5.Display the gross salary.
6.Stop


''' Write a python program to calculate income tax based on annual income:
up to 2,50,000:NO tax
2,50,001-5,00,000:5%
5,00,001-10,00,000:30%
income=float(input("enter annual income:"))
     

income= float (input("enter annual income:"))
if income<=250000:
  tax=0

elif income<=500000:
  tax=(income-250000)*0.05

elif income<=1000000:
  tax=(250000*0.05)+(income-500000)*0.20

else:
    tax=(250000*0.50)+(500000*0.20)+(income-1000000)*0.30

print("Income Tax =", tax) 


Algorithm: 
1.Start
2.Input the annual income of the person.
3.Check the income slabs:
If income ≤ 2,50,000
Set tax = 0.
Else if income ≤ 5,00,000
Calculate
tax = (income − 2,50,000) × 5%.
Else if income ≤ 10,00,000
Calculate
tax = (2,50,000 × 5%) + (income − 5,00,000) × 20%.
Else
Calculate
tax = (2,50,000 × 5%) + (5,00,000 × 20%) + (income − 10,00,000) × 30%.
4.Display the calculated income tax.
5.Stop


-> mm=int(input("enter month:"))
yy=int(input("enter year:"))

if mm==1 or mm==3 or mm==5 or mm==7 or mm==8 or mm==10 or mm==12:
  max1 = 31

elif mm==4 or mm==6 or mm==9 or mm==11:
  max1=30

elif mm ==2:
  if(yy%4==0 and yy %100!=0)or (yy%400==0):
    max1=29
  else:
      max1=28


else:
  print("date is valid.")
  max1=None

if mm<1 or mm>12:
  print("date is invalid.")
else:
  dd=int (input("enter day:"))
  if dd<1 or dd>max1:
    print("date is invalid.")
  else:
    print("date in valid.")


Algorithm: 
1.Start
2.Input the month (mm) and year (yy).
3.Determine the maximum number of days (max1) in the given month:
If the month is January, March, May, July, August, October, or December, set max1 = 31.
Else if the month is April, June, September, or November, set max1 = 30.
Else if the month is February:
If the year is a leap year (divisible by 4 and not by 100, or divisible by 400), set max1 = 29.
Otherwise, set max1 = 28.
4.Check if the month value is valid:
If mm < 1 or mm > 12, display “Date is invalid” and stop.
5.Input the day (dd).
6.Check if the day value is valid:
If dd < 1 or dd > max1, display “Date is invalid”.
Else, display “Date is valid”.
7.Stop


-> print("Incremented Date if it is valid")

date = input("Enter the date in format (dd/mm/yyyy): ")
dd, mm, yy = map(int, date.split("/"))

# Find maximum days in the month
if mm == 1 or mm == 3 or mm == 5 or mm == 7 or mm == 8 or mm == 10 or mm == 12:
    max1 = 31

elif mm == 4 or mm == 6 or mm == 9 or mm == 11:
    max1 = 30

elif mm == 2:
    if (yy % 4 == 0 and yy % 100 != 0) or (yy % 400 == 0):
        max1 = 29
    else:
        max1 = 28

else:
    print("Date is invalid")
    exit()

# Validate date
if mm < 1 or mm > 12:
    print("Date is invalid")

elif dd < 1 or dd > max1:
    print("Date is invalid")

# Increment date
elif dd == max1 and mm != 12:
    dd = 1
    mm = mm + 1
    print("The incremented date is:", dd, mm, yy)

elif dd == 31 and mm == 12:
    dd = 1
    mm = 1
    yy = yy + 1
    print("The incremented date is:", dd, mm, yy)

else:
    dd = dd + 1
    print("The incremented date is:", dd, mm, yy)



      Algorithm: 
1.Start
2.Input the date from the user in the format dd/mm/yyyy.
3.Separate the input date into day (dd), month (mm), and year (yy).
4.Find the maximum number of days (max1) in the given month:
If mm is 1, 3, 5, 7, 8, 10, or 12, set max1 = 31.
Else if mm is 4, 6, 9, or 11, set max1 = 30.
Else if mm is 2:
If the year is a leap year (divisible by 4 and not by 100, or divisible by 400), set max1 = 29.
Otherwise, set max1 = 28.
Else, display “Date is invalid” and stop.
5.Validate the date:
If mm < 1 or mm > 12, display “Date is invalid” and stop.
If dd < 1 or dd > max1, display “Date is invalid” and stop.
6.Increment the date:
If dd = max1 and mm ≠ 12, set dd = 1 and increment mm by 1.
Else if dd = 31 and mm = 12, set dd = 1, mm = 1, and increment yy by 1.
Else, increment dd by 1.
7.Display the incremented date.
8.Stop


Conclusion:

Thus, the study of conditional statements in Python was successfully completed. We learned how if, if-else, and if-elif-else statements control the flow of a program based on conditions. Conditional statements make Python programs more flexible and efficient by allowing decision-making during execution.

