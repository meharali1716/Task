

```python
province = ("Sindh", "Punjab","kpk","Bloachistan","Gilgit-Baltistan","Azad Kashmir")

print(province)

del province[1]

province.remove("kpk")
```

    ('Sindh', 'Punjab', 'kpk', 'Bloachistan', 'Gilgit-Baltistan', 'Azad Kashmir')
    


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-16-694d321f7a74> in <module>()
          3 print(province)
          4 
    ----> 5 del province[1]
          6 
          7 province.remove("kpk")
    

    TypeError: 'tuple' object doesn't support item deletion

