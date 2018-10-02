

```python
Country = { 1: "Pakistan",  2: "England",  3: "South-Africa" }
Country[4]="Afghanistan"
profile = { "Name" : "Mehar"}
profile["ID"]="1716-2015"
print ( "\n")
print (Country ,"\n")
print (profile)
del Country[2]            #Removing
del profile["ID"]
print ( "\n")
print (Country)
print (profile)

Country[4]="Ireland"            #Changing
print (Country)
```

    
    
    {1: 'Pakistan', 2: 'England', 3: 'South-Africa', 4: 'Afghanistan'} 
    
    {'Name': 'Mehar', 'ID': '1716-2015'}
    
    
    {1: 'Pakistan', 3: 'South-Africa', 4: 'Afghanistan'}
    {'Name': 'Mehar'}
    {1: 'Pakistan', 3: 'South-Africa', 4: 'Ireland'}
    
