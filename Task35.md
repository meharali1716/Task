

```python
Students = [
    {
    "Students_ID" : 0,
    "Name" : "Sohail",
    "Last_Name" : "Khan",
    },
      {
    "Students_ID" : 1,
    "Name" : "Shakeel",
    "Last_Name" : "Hiader",
    },                                  #Creating a list of dictionaries
      {
    "Students_ID" : 2,
    "Name" : "Usama",
    "Last_Name" : "Bin Riaz",
    },
      {
    "Students_ID" : 3,             
    "Name" : "Mehar Ali",
    "Last_Name" : "Khan",
    },
                                         #How to pick information out of a list of dictionaries
]

search = Students[3]
Search_Name= search["Name"]
print(Search_Name)
```

    Mehar Ali
    
