Experiment – 5
Title
Implementation Dictionary in Python

Aim
To study and implement  in Python and perform Dictionary operations.

Theory on dictionary
A dictionary is an unordered collection of key-value pairs. Each key must be unique, while values may be duplicated.
Syntax:
dictionary = {key: value}
Dictionaries are widely used in real-life applications such as student records, phone books, and configuration data.

Characteristics of Dictionary
	•	Key-value based
	•	Mutable
	•	Keys are unique
	•	Values can be modified

Program 1: Creating and Accessing Dictionary
student = {
    "roll": 101,
    "name": "Amit",
    "branch": "CSE"
}

print("Name:", student["name"])

Algorithm:
1.Start
2.Initialize a dictionary named products with product names as keys and their prices as values.
3.Display the original dictionary.
4.Select the product whose price needs to be updated (e.g., "book").
5.Assign the new price to the selected product key in the dictionary.
6.Display the updated dictionary.
7.Stop

Program 2: Adding and Updating Elements
student["year"] = "Second"
student["name"] = "Rahul"

print(student)

Algorithm:
1.Start
2.Create a dictionary named student.
3.Add a new key "year" with value "Second" to the dictionary.
4.Add or update the key "name" with value "Rahul".
5.Display the updated dictionary.
6.Stop

Program 3: Removing Elements
student.pop("branch")
print("After removal:", student)

Algorithm:
1.Start
2.Create a dictionary named student with required key–value pairs.
3.Use the pop() method to remove the key "branch" from the dictionary.
4.Store and delete the corresponding value of the removed key.
5.Display the dictionary after removal.
6.Stop

Program 4: Dictionary Methods
print("Keys:", student.keys())
print("Values:", student.values())
print("Items:", student.items())


Algorithm:
1.Start
2.Create a dictionary named student with key–value pairs.
3.Use the keys() method to display all keys of the dictionary.
4.Use the values() method to display all values of the dictionary.
5.Use the items() method to display all key–value pairs.
6.Stop

Applications of Dictionary
	•	Student information systems
	•	Phone directories
	•	Database records
	•	Configuration files


Conclusion:
Dictionaries provide efficient storage and retrieval of data using keys, making them essential for real-world applications.
