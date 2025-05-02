# dictionary operations
person={'name':'mani','age':20,'city':'banglore'}
print(person)
print("accessing and modify the person age:")
person["age"]=20
print(person)
print("adding and removing items")
person['email']='mani@gmail.com'  
print(person)
del person['city']
print(person)
print("all keys & values")
print(person.keys())
print(person.values())
print(person.items())                                                                          
