Experiment–3


Title
Tuples in Python: Creation, Access, and Operations

Aim
To understand Python tuples and perform operations such as creation, indexing, slicing, and use of built-in functions.

Objectives
	•	To understand the concept of tuples in Python
	•	To study characteristics and advantages of tuples
	•	To perform indexing and slicing on tuples
	•	To apply built-in tuple functions
	•	To understand immutability of tuples

Theory
1. Introduction to Tuples
A tuple is an ordered collection of elements in Python, similar to a list, but immutable in nature. Tuples are written using parentheses ( ) and elements are separated by commas.
Example:
(10, 20, 30)

2. Characteristics of Tuples
	•	Ordered
	•	Indexed
	•	Immutable (cannot be changed after creation)
	•	Allows duplicate values
	•	Can store heterogeneous data types

3. Why Tuples are Used
	•	Faster than lists
	•	Data integrity (values cannot be modified)
	•	Used for fixed data such as coordinates, days of week, database records

4. Creating Tuples
Tuples can be created:
	•	With parentheses
	•	Without parentheses (tuple packing)
	•	Using the tuple() constructor
Special cases:
	•	Single element tuple must have a trailing comma (10,)

5. Indexing in Tuples
Tuple elements are accessed using index numbers, starting from 0.
Both:
	•	Positive indexing
	•	Negative indexing
are supported.

6. Slicing in Tuples
Slicing is used to extract a portion of a tuple.
General Syntax:
tuple_name[start : end : step]
Meaning of each part:
	•	start → index to begin slicing (included)
	•	end → index to stop slicing (excluded)
	•	step → gap between elements (optional)

7. Immutability of Tuples
Once a tuple is created:
	•	Elements cannot be added
	•	Elements cannot be removed
	•	Elements cannot be updated
Any attempt to modify results in an error.

8. Built-in Functions for Tuples
Function
Description
len()
Number of elements
max()
Maximum value
min()
Minimum value
sum()
Sum of elements
count()
Count occurrences
index()
Find index of element

Difference Between List and Tuple:
In Python, list and tuple are used to store multiple items in a single variable, but they differ in several ways.
A list is a mutable data type, which means its elements can be changed after creation. We can add, remove, or modify elements in a list. Lists are created using square brackets [ ]. Because lists are flexible, they are commonly used when data needs to be updated frequently.
A tuple is an immutable data type, which means its elements cannot be changed once created. Tuples are created using parentheses ( ). Since tuples are fixed, they are faster and use less memory compared to lists. Tuples are mainly used when the data should remain constant.
Thus, lists are suitable for dynamic data, while tuples are preferred for fixed and secure data storage.

Example:
List: marks = [75, 80, 85]
Tuple: marks = (75, 80, 85)




PROBLEM 1:
#result analysis
result=("maths",82,"A")

#unpack the tuple
subject,marks,grade=result

subject,marks,grade=result

#display the result details
print("subject:",subject)
print("marks:",marks)
print("grade:",grade)

#check for distinction
if marks>=75:
    print("Distinction")

ALGORITHM:
1.Start
2.Create a tuple named result containing:
Subject
Marks
Grade
3.Unpack the tuple into three variables:
subject
marks
grade
4.Display the subject.
5.Display the marks.
6.Display the grade.
7.Check if marks is greater than or equal to 75:
If yes, display "Distinction".
8.Stop

PROBLEM 2:

#Monitoring attendance
attendance=["P","A","P","P","A","P"]
print("total present days:",attendance.count("P"))
print("total absent days:",attendance.count("A"))
if "A" in attendance:
    print("employee was absent at least once")

    ALGORITHM:
1.Start
2.Create a list named attendance containing attendance status ("P" for Present, "A" for Absent).
3.Count the number of "P" in the list and display it as total present days.
4.Count the number of "A" in the list and display it as total absent days.
5.Check whether "A" is present in the attendance list:
If yes, display "Employee was absent at least once".
6.Stop
    


Conclusion:
Thus, Python tuples were studied and operations such as creation, indexing, slicing, packing, unpacking, and built-in functions were successfully implemented.


