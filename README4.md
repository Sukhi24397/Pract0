Experiment – 4
Title
Implementation of Set  in Python

Aim
To study and implement set data structure in Python and perform various set and Dictionary operations.

Objectives
	•	To understand the concept of sets
	•	To perform set creation and basic operations
	•	To apply mathematical set operations
	•	To understand dictionary structure
	•	To perform insertion, deletion, and access of data
	•	To apply dictionary methods

Theory on Sets
A set in Python is an unordered collection of unique elements. Sets are defined using curly braces {} or the set() constructor.
Characteristics of Set
	•	Unordered
	•	No duplicate elements
	•	Mutable
	•	Does not support indexing
Sets are commonly used in real-life scenarios such as removing duplicates, membership testing, and mathematical operations.

Set Operations
	•	Union
	•	Intersection
	•	Difference
	•	Symmetric Difference

Program 1: Creating a Set and Displaying Elements
fruits = {"apple", "banana", "cherry"}
print("Fruits:", fruits)

Program 2: Removing Duplicate Values
numbers = {1, 2, 3, 2, 4, 1}
print("Unique numbers:", numbers)

Program 3: Set Operations
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

print("Union:", A | B)
print("Intersection:", A & B)
print("Difference:", A - B)
print("Symmetric Difference:", A ^ B)

Program 4: Set Methods
s = {10, 20, 30}
s.add(40)
s.remove(20)

print("Updated Set:", s)

Applications of Set
	•	Removing duplicate records
	•	Membership testing
	•	Mathematical computations
