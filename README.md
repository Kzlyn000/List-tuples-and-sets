# List-tuples-and-sets
Python Data Structures

 Welcome to the Python Data Structures repository. In this repository, you'll find Python code examples and explanations for working with various data structures, including Lists, Tuples, Sets, and Dictionaries. Each data structure is explored with code snippets and explanations to help you understand how to work with them in Python.

Lists, Tuples, Sets and Dictionaries
1) List
[ ]
#List - ordered sequence of elements, always uses [] to represent the list. Each item is seperated by ,.

food = ["pizza","burger","rice", "noodles"]
print(food)
account_circle
['pizza', 'burger', 'rice', 'noodles']
[ ]
print(food[0])
account_circle
pizza
[ ]
# to add element in list
food.append("cake")
print(food)
account_circle
['pizza', 'burger', 'rice', 'noodles', 'cake']
[ ]
food.append("sandwhich")
print(food)
account_circle
['pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich']
[ ]
food.extend(["sandwhich","pasta"])
print(food)
account_circle
['pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich', 'sandwhich', 'pasta']
[ ]
food.extend(["sandwhich","pasta"])
food
account_circle
['pizza',
 'burger',
 'rice',
 'noodles',
 'cake',
 'sandwhich',
 'sandwhich',
 'pasta',
 'sandwhich',
 'pasta']
[ ]
print(food*2)
account_circle
['pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich', 'sandwhich', 'pasta', 'sandwhich', 'pasta', 'pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich', 'sandwhich', 'pasta', 'sandwhich', 'pasta']
[ ]
food + ["coffee","tea"]
food
account_circle
['pizza',
 'burger',
 'rice',
 'noodles',
 'cake',
 'sandwhich',
 'sandwhich',
 'pasta',
 'sandwhich',
 'pasta']
[ ]
food = food + ["coffee","tea"]
food
account_circle
['pizza',
 'burger',
 'rice',
 'noodles',
 'cake',
 'sandwhich',
 'sandwhich',
 'pasta',
 'sandwhich',
 'pasta',
 'coffee',
 'tea']
[ ]
food[1:3]
account_circle
['burger', 'rice']
[ ]
food[3]= 'Sweet'
food
account_circle
['pizza',
 'burger',
 'rice',
 'Sweet',
 'cake',
 'sandwhich',
 'sandwhich',
 'pasta',
 'sandwhich',
 'pasta',
 'coffee',
 'tea']
[ ]
food.index('cake')
account_circle
4
[ ]
food.insert(3,'Paratha')
food
account_circle
['pizza',
 'burger',
 'rice',
 'Paratha',
 'Sweet',
 'cake',
 'sandwhich',
 'sandwhich',
 'pasta',
 'sandwhich',
 'pasta',
 'coffee',
 'tea']
[ ]
drinks = food.remove('tea')
print(drinks)
account_circle
None
[ ]
onlyfood = food.remove('tea')
print(onlyfood)
account_circle

[ ]
xyz = food.remove("coffee")
print(xyz)
account_circle
None
[ ]
print(food)
account_circle
['pizza', 'burger', 'rice', 'Paratha', 'Sweet', 'cake', 'sandwhich', 'sandwhich', 'pasta', 'sandwhich', 'pasta']
[ ]
menu = ['pizza', 'burger', 'rice', 'noodles', 'icecream', 'juice']
print(menu)
account_circle
['pizza', 'burger', 'rice', 'noodles', 'icecream', 'juice']
[ ]
print('initial menu', menu)
menu.reverse()
print('reversed menu', menu)
print(type(reversed(menu)))
account_circle
initial menu ['juice', 'icecream', 'noodles', 'rice', 'burger', 'pizza']
reversed menu ['pizza', 'burger', 'rice', 'noodles', 'icecream', 'juice']
<class 'list_reverseiterator'>
[ ]
print('initial menu', menu)
menu.sort()
print('sorted menu',menu)
account_circle
initial menu ['pizza', 'burger', 'rice', 'noodles', 'icecream', 'juice']
sorted menu ['burger', 'icecream', 'juice', 'noodles', 'pizza', 'rice']
[ ]
del menu[-2]
menu
account_circle
['burger', 'icecream', 'juice', 'noodles', 'rice']
[ ]
print(menu[2:4])
account_circle
['juice', 'noodles']
[ ]
menu.remove(['juice','noodles'])
print(menu)
account_circle

[ ]
print(menu)
account_circle
['burger', 'icecream', 'juice', 'noodles', 'rice']
[ ]
menu.remove('juice')
print(menu)
account_circle
['burger', 'icecream', 'noodles', 'rice']
[ ]
print(menu)
account_circle
['burger', 'icecream', 'noodles', 'rice']
[ ]
menu.remove('icecream','noodles')
print(menu)
account_circle

[ ]
menu_2 = ['pizza','burger', 'rice', 'noodles','icecream']
print(menu_2)
  
account_circle
['pizza', 'burger', 'rice', 'noodles', 'icecream']
[ ]
menu_2.pop()
account_circle

[ ]
menu_2.clear()
print(menu_2)
account_circle
[]
2) Tuples
[ ]
# Tuples - same as list, both contains sequence of items, mixed data types, and it contains individual elements also it is
# immutable, it represents by ().

empty = ()
print("empty tuple",empty)
account_circle
empty tuple ()
[ ]
# to create int tuple
int = (2,1,3,4,5)
print(int)
account_circle
(2, 1, 3, 4, 5)
[ ]
#mix tuple
mix = (4,"Python",4.2)
print(mix)
account_circle
(4, 'Python', 4.2)
[ ]
# nested tuple
nested = ('python', ["int","data","float"], 100)
print(nested)
account_circle
('python', ['int', 'data', 'float'], 100)
[ ]
str1 = "Python Prog",
print(str1)
account_circle
('Python Prog',)
[ ]
Country = ("USA", "China", "Philippine", "India")
print(Country)
account_circle
('USA', 'China', 'Philippine', 'India')
[ ]
Country[2]="Singapore"
print(Country)
account_circle

[ ]
del Country[1] 
account_circle

[ ]
Country + ("Singapore","Japan")
print(Country)
Country1 = Country + ("Singapore","Japan")
print(Country1)
account_circle
('USA', 'China', 'Philippine', 'India')
('USA', 'China', 'Philippine', 'India', 'Singapore', 'Japan')
[ ]
Country1.count('China')
account_circle
1
[ ]
ex1 = ('a','p','y','t','h','o','n','a','y')
print(ex1.count('a'))
account_circle
2
[ ]
print(ex1.index('y'))
account_circle
2
[ ]
# to check an item available in tuple or not
print("Australia" in Country1)
account_circle
False
[ ]
print("Singapore" in Country1)
account_circle
True
[ ]
del Country1
[ ]
print(Country1)
account_circle

[ ]

3. Sets
[ ]
# Sets - collection of items which are not in order 
# but we cannot change the items in set but we can the add or remove
# Elements cannot be duplicated
# also there is no indexing or slicing
# useig {}, Union, Intersections, difference
[ ]
temp = [['Mary',101,26],
        ['Alex',102,27]]
print(temp)
account_circle
[['Mary', 101, 26], ['Alex', 102, 27]]
[ ]
countries = {'USA', 'China', 'Philippine', 'India', 'Singapore', 'Japan'}
print(countries)
print(type(countries))
account_circle
{'Japan', 'Philippine', 'China', 'India', 'USA', 'Singapore'}
<class 'set'>
[ ]
print(len(countries))
account_circle
6
[ ]
# adding an element
countries.add("Germany")
print(countries)
account_circle
{'Japan', 'Philippine', 'China', 'India', 'USA', 'Singapore', 'Germany'}
[ ]
#deleting the element
countries.discard("Germany")
print(countries)
account_circle
{'Japan', 'Philippine', 'China', 'India', 'USA', 'Singapore'}
[ ]
# Other Sets Operations
country_1 = {'USA', 'China', 'India', 'Japan', 'Singapore', 'Philippine'}
country_2 = {"India",'Singapore','Germany','Indonesia'}
Setof_Country= country_1.union(country_2)
print(Setof_Country)
account_circle
{'Japan', 'China', 'Germany', 'Philippine', 'India', 'USA', 'Indonesia', 'Singapore'}
[ ]
print(country_1 | country_2)
account_circle
{'Japan', 'China', 'Germany', 'Philippine', 'India', 'USA', 'Indonesia', 'Singapore'}
[ ]
# intersection
print(country_1.intersection(country_2))
account_circle
{'Singapore', 'India'}
[ ]
print(country_1 & country_2)
account_circle
{'Singapore', 'India'}
[ ]
print(country_2.difference(country_1))
print(country_1.difference(country_2))
account_circle
{'Germany', 'Indonesia'}
{'Japan', 'Philippine', 'China', 'USA'}
[ ]
set_ex = {11,22,67,54}
output_set = 78 in set_ex
print(output_set)
account_circle
False
[ ]
output_set = 78 not in set_ex
print(output_set)
account_circle
True
[ ]
# Upfating the set
country_2 = {"India",'Singapore','Germany','Indonesia'}
update_set = {'Africa','Malaysia','India'}
country_2.update(update_set)
print(country_2)
account_circle
{'Africa', 'India', 'Indonesia', 'Singapore', 'Germany', 'Malaysia'}
[ ]
country_2.clear()
print(country_2)
account_circle
set()
4) Dictionary
[ ]
# Dictionary - collection of elements, keys and values pair, key and value are separated by :.
# it is mutable and unordered, 
# if we want to access the elements then we use key
[ ]
emp_dict = {'Name':'john','age':25,'Dept':'sales'}
print(emp_dict)
account_circle
{'Name': 'john', 'age': 25, 'Dept': 'sales'}
[ ]
print(emp_dict['Name'])
account_circle
john
[ ]
emp_dict['age']=29
print(emp_dict['age'])
account_circle
29
[ ]
print(len(emp_dict))
account_circle
3
[ ]
key = emp_dict.keys()
print(key)
account_circle
dict_keys(['Name', 'age', 'Dept'])
[ ]
emp_dict
account_circle
{'Name': 'john', 'age': 29, 'Dept': 'sales'}
[ ]
emp_dict = {'Name':'john','age':25,'Dept':'sales','Dept': 'HR'}
print(emp_dict)
account_circle
{'Name': 'john', 'age': 25, 'Dept': 'HR'}
[ ]
print(type(emp_dict))
account_circle
<class 'dict'>
[ ]
emp = dict(name='Mary',age=25,id=101)
print(emp)
account_circle
{'name': 'Mary', 'age': 25, 'id': 101}
[ ]
v = emp.values()
print(v)
print(emp.items())
print()
account_circle
dict_values(['Mary', 25, 101])
dict_items([('name', 'Mary'), ('age', 25), ('id', 101)])

[ ]
# Nested Dictionary

Company = {'emp1':{'name':'Daniel','year':2018},
           'emp2':{'name':'Jimmy','year':2020},
           'emp3':{'name':'John','year':2022}}
print(Company)
account_circle
{'emp1': {'name': 'Daniel', 'year': 2018}, 'emp2': {'name': 'Jimmy', 'year': 2020}, 'emp3': {'name': 'John', 'year': 2022}}
[ ]
del emp['age']
print(emp)
account_circle
{'name': 'Mary', 'id': 101}
[ ]
print(emp.pop('id'))
account_circle
101
[ ]
emp.clear()
[ ]
del emp
print(emp)
account_circle

[ ]
empName = Company['emp1']['name']
print(empName)
account_circle
Daniel
[ ]

