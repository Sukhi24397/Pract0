EXPERIMENT 8:

Aim:
To study and understand the use of for loops in Python and implement them in different programs such as:

Printing numbers (odd and even)

Finding sum of first N numbers

Displaying a 3×3 matrix

Performing matrix multiplication

Generating digit combinations

Printing pattern programs (triangle and pyramid

Theory:

The for loop in Python is a control structure used to execute a block of statements repeatedly for a fixed number of times or for each element in a sequence. 
It is mainly used when the number of iterations is known in advance.
The general syntax of a for loop is for variable in sequence: followed by a block of statements. In Python, the range() function is commonly used with the for loop to generate a sequence of numbers. The range(start, stop, step) function allows control over the starting value, ending value (exclusive), and increment or decrement value. The for loop works by assigning each value from the sequence to the loop variable one by one and executing the given statements until all values are exhausted.
For loops can also be nested, meaning a loop can be placed inside another loop.
Nested for loops are especially useful in working with two-dimensional data structures such as matrices. In matrix operations like matrix display and matrix multiplication, multiple loops are required to access rows and columns systematically. 
Matrix multiplication requires three nested loops to multiply corresponding elements and store the result in a new matrix.
Additionally, conditional statements can be used inside for loops to control the flow of execution, such as avoiding repetition while generating combinations of digits.
For loops are also widely used in pattern printing programs like triangles and pyramids, where repetition and proper spacing are controlled using loop variables and string multiplication.
Thus, the for loop is a fundamental and powerful feature in Python that helps in performing repetitive tasks efficiently, making programs shorter, clearer, and more structured.

PROBLEM:
#print odd numbers 1 to 10
for i in range(1,11,2):
  print(i) 

  Algorithm: Print Odd Numbers from 1 to 10

Start

Initialize the loop variable i to 1.

Repeat the following steps while i is less than or equal to 10:

Display the value of i.

Increase the value of i by 2.

Stop

PROBLEM:
#print even numbers 1 to 10
for i in range (2,11,2):
  print(i) 

  Algorithm: Print Even Numbers from 1 to 10

Start

Initialize the loop variable i to 2.

Check if i is less than or equal to 10.

If true, print the value of i.

Increase the value of i by 2.

Repeat steps 3 to 5 until i becomes greater than 10.

Stop

PROBLEM:
#add first N numbers
n = int(input("enter N:"))
total = 0
for i in range(1, n+1):
  total+=i
print("sum=",total) 

Algorithm: Add First N Natural Numbers

Start

Declare a variable total and initialize it to 0.

Read the value of N from the user.

Set the loop variable i to 1.

Check if i is less than or equal to N.

If true, add i to total.

Increase the value of i by 1.

Repeat steps 5 to 7 until i becomes greater than N.

Display the value of total.

Stop

PROBLEM:
#3*3 matrix display
A= [[1,2,3],
[4,5,6],
[7,8,9]]
for i in range(3):
      for j in range(3):
        print(A[i][j],end=" ")
      print()  

Algorithm: Display a 3 × 3 Matrix

Start

Define a 3 × 3 matrix A with elements.

Initialize row index i = 0.

Repeat steps 5 to 9 while i < 3:

    Initialize column index j = 0.

    Repeat steps 7 to 8 while j < 3:

        Print the element A[i][j] with a space.

        Increase j by 1.

    Print a new line after completing one row.

   Increase i by 1.

Stop

PROBLEM:
#Multiplication of two matrix
A=[[1,2,3],
   [4,5,6],
   [1,2,1]]
B=[[1,1,1],
   [6,5,4],
   [3,2,1]]
Result=[[0,0,0],
        [0,0,0],
        [0,0,0]]

for i in range(3):      #rows of A
    for j in range(3):  #columns of B
        for k in range(3):
            Result[i][j]+=A[i][k]*B[k][j]
for row in Result:
            print(row)


 Algorithm: Multiplication of Two 3 × 3 Matrices

Start

Define matrix A of order 3 × 3.

Define matrix B of order 3 × 3.

Create a result matrix Result of order 3 × 3 and initialize all elements to 0.

Set row index i = 0.

Repeat steps 7 to 12 while i < 3:

    Set column index j = 0.

    Repeat steps 9 to 11 while j < 3:

        Set k = 0.

        Repeat while k < 3:
            Multiply A[i][k] and B[k][j] and add the result to Result[i][j].
            Increase k by 1.

        Increase j by 1.

    Increase i by 1.

Display all elements of the Result matrix row by row.

Stop

PROBLEM:
#Python program to accept three digits and print all possible combination


d1=1
d2=2
d3=3
d=[d1,d2,d3]

#123,132,213,231,312,321

for i in range(0,3):
  for j in range(0,3):
    for k in range(0,3):
      if(d[i]!=d[j]and d[j]!=d[k]and d[k]!=d[i]):
        print(d[i],d[j],d[k]) 

 Algorithm: Print All Possible Combinations of Three Digits

Start

Initialize three digits d1, d2, and d3.

Store the digits in a list d.

Set index i = 0.

Repeat steps 6 to 12 while i < 3:

    Set index j = 0.

    Repeat steps 8 to 11 while j < 3:

        Set index k = 0.

        Repeat while k < 3:

            If d[i], d[j], and d[k] are all different (no repetition), then print d[i] d[j] d[k].

            Increase k by 1.

        Increase j by 1.

   Increase i by 1.

Stop

PROBLEM:
#write a python code to make right angle traingle
for i in range(5,0,-1):
    print("*"*i)  

 Algorithm: Print Right-Angled Triangle Pattern

Start

Initialize the number of rows as 5.

Set loop variable i = 5.

Check if i is greater than 0.

If true, print * symbol i times in the same line.

Move to the next line.

Decrease the value of i by 1.

Repeat steps 4 to 7 until i becomes 0.

Stop

PROBLEM:
#pyramid pattern
rows=5
for i in range(1,rows+1):
 print(" "*(rows-i)+ "* "*i)  

 Algorithm: Print Pyramid Pattern

Start

Initialize the number of rows as rows = 5.

Set loop variable i = 1.

Check if i is less than or equal to rows.

If true, print spaces equal to (rows − i).

Then print * (star with space) repeated i times.

Move to the next line.

Increase the value of i by 1.

Repeat steps 4 to 8 until i becomes greater than rows.

Stop

Conclusion :

The for loop is an essential control structure in Python that allows repeated execution of statements over a sequence.
It is widely used in numerical operations, matrix manipulation, pattern generation, and logical problem-solving.
Understanding for loops and nested loops is fundamental for developing efficient and structured programs.
