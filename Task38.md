

```python
details = {
  "nickname": "Mehar",
  "married": "no",
  "careers": ["Web Developer", "Software Engineer", "CEO"],
}
if "Web Developer" in details["careers"]:
  print("yes!")
else:
  print("no")
```

    yes!
    


```python
details = {
  "nickname": "Mehar",
  "married": "yes",
  "careers": ["Web Developer", "Web Designer", "Singer", "Actor"],
}
if details["married"] == "yes" and "Web Developer" in details["careers"]:
    print("Yes!")
else:
    print("no")
```

    Yes!
    
