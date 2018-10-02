

```python
first_names = ["Mehar ", "Ali ", "Sohail ", "Usama ", "Nafees "] 
last_names = ["Khan", "Niazi", "Bloch", "Arain"] 
full_names = []   
for a_first_name in first_names:  
    for a_last_name in last_names:  
        full_names.append(a_first_name + " " + a_last_name) 
        print (full_names)
```

    ['Mehar  Khan']
    ['Mehar  Khan', 'Mehar  Niazi']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi', 'Usama  Bloch']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi', 'Usama  Bloch', 'Usama  Arain']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi', 'Usama  Bloch', 'Usama  Arain', 'Nafees  Khan']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi', 'Usama  Bloch', 'Usama  Arain', 'Nafees  Khan', 'Nafees  Niazi']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi', 'Usama  Bloch', 'Usama  Arain', 'Nafees  Khan', 'Nafees  Niazi', 'Nafees  Bloch']
    ['Mehar  Khan', 'Mehar  Niazi', 'Mehar  Bloch', 'Mehar  Arain', 'Ali  Khan', 'Ali  Niazi', 'Ali  Bloch', 'Ali  Arain', 'Sohail  Khan', 'Sohail  Niazi', 'Sohail  Bloch', 'Sohail  Arain', 'Usama  Khan', 'Usama  Niazi', 'Usama  Bloch', 'Usama  Arain', 'Nafees  Khan', 'Nafees  Niazi', 'Nafees  Bloch', 'Nafees  Arain']
    
