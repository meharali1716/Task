

```python
foods = [ "Nihari", "Biryani", "Karahi", "Salad", "Kabab", "Polaow" ]

print(str(foods[0]) + " and  " + str(foods[5])+", both are delicious !")

foods.append("Qorma")

print(str(foods[0]) + " and " + str(foods[6])+", both are  amazing ! ")

foods.insert(0,"Cricket")

print(str(foods[0]) +" is not a food :/ ")

print(str(foods))
```

    Nihari and  Polaow, both are delicious !
    Nihari and Qorma, both are  amazing ! 
    Cricket is not a food :/ 
    ['Cricket', 'Nihari', 'Biryani', 'Karahi', 'Salad', 'Kabab', 'Polaow', 'Qorma']
    
