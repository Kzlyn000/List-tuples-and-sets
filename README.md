# List-tuples-and-sets
# Python Data Structures

 # Welcome to the Python Data Structures repository. In this repository, you'll find Python code examples and explanations for working with various data structures, including Lists, Tuples, Sets, and Dictionaries. Each data structure is explored with code snippets and explanations to help you understand how to work with them in Python.

## List

# A list is an ordered sequence of elements that is represented using square brackets `[]`. You can add, remove, and modify elements in a list. Here are some common operations:

 # - Create a list:
  ```python
  food = ["pizza", "burger", "rice", "noodles"]
print(food[0])  # Output: pizza
food.append("cake")
food.extend(["sandwich", "pasta"])
food.remove("tea")
food.index('cake')  # Output: 4
food[1:3]  # Output: ['burger', 'rice']
Tuple
# A tuple is an ordered collection of elements, represented using parentheses (). Tuples are immutable, meaning their contents cannot be changed once defined. Here are some tuple operations:


# Create a tuple:
int_tuple = (2, 1, 3, 4, 5)
int_tuple[0]  # Output: 2
int_tuple.count(4)  # Output: 1
int_tuple.index(3)  # Output: 2
"Australia" in int_tuple  # Output: False

# Set
A set is an unordered collection of unique elements. Sets are defined using curly braces {}. Here are some set operations:

Create a set:
countries = {'USA', 'China', 'Philippine', 'India'}
countries.add("Germany")
countries.discard("Germany")
country_1.union(country_2)
country_1.intersection(country_2)
country_1.difference(country_2)

# Dictionary
A dictionary is a collection of key-value pairs, where each key is unique. Dictionaries are defined using curly braces {} with key-value pairs separated by colons :. Here are some dictionary operations:

Create a dictionary:
emp_dict = {'Name': 'John', 'age': 25, 'Dept': 'sales'}
emp_dict['Name']  # Output: 'John'
emp_dict['age'] = 29
emp_dict.keys()
emp_dict.values()
del emp_dict['age']
Company = {'emp1': {'name': 'Daniel', 'year': 2018}, ...}
