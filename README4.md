Experiment – 4
Title
Implementation of Set  in Python

Aim
To study and implement set data structure in Python .

Objectives
	•	To understand the concept of sets
	•	To perform set creation and basic operations
	•	To apply mathematical set operations
	
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

Algorithm: 
1.Start
2.Create a set named fruits containing elements "apple", "banana", and "cherry".
3.Store the elements in the set (duplicate elements, if any, are automatically removed).
4.Display the set using the print() function.
5.Stop

Program 2: Removing Duplicate Values
numbers = {1, 2, 3, 2, 4, 1}
print("Unique numbers:", numbers)

Algorithm: 
1.Start
2.Create a set named numbers with elements including duplicate values.
3.Automatically remove duplicate elements while creating the set.
4.Store only unique elements in the set.
5.display the set using the print() function.
6.Stop


Program 3: Set Operations
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

print("Union:", A | B)
print("Intersection:", A & B)
print("Difference:", A - B)
print("Symmetric Difference:", A ^ B)

Algorithm: 
1.Start
2.Create two sets A and B with given elements.
3.Find the union of sets A and B using A | B`.
4.Find the intersection of sets A and B using A & B`.
5.Find the difference of sets A and B using A - B`.
6.Find the symmetric difference of sets A and B using A ^ B`.
7.Display the results of all set operations.
8.Stop


Program 4: Set Methods
s = {10, 20, 30}
s.add(40)
s.remove(20)

print("Updated Set:", s)

Algorithm: 
1.Start
2.Create a set s with elements {10, 20, 30}.
3.Add a new element 40 to the set using the add() method.
4.Remove the element 20 from the set using the remove() method.
5.Display the updated set.
6.Stop


Applications of Set
	•	Removing duplicate records
	•	Membership testing
	•	Mathematical computations


	Conclusion:
Sets efficiently handle unique data and support mathematical operations, making them useful for data processing tasks.

