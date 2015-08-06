#warmup-2

##string_times
```
def string_times(str, n):
    return str*n
```

##front_times
```
def front_times(str, n):
    return str[:3]*n
```

##string_bits
```
string_bits=lambda str: str[0::2]
```

##string_splosion
```
def string_splosion(str):
    a = ''
    for i in range(len(str)):
        a = str[:i]
    return a
```

