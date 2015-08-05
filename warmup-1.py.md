#warmup-1

##sleep_in
``` 
def sleep_in(weekday, vacation):
    return ( not weekday or vacation )
```

##monkey_trouble
```
def monkey_trouble(a_smile, b_smile):
    return ( not a_smile ^ b_smile )
```

##sum_double
```
def sum_double(a, b):
    return ( 4*a if a==b else a+b )
```

##diff21
```
def diff21(n):
    return ( abs(n-21) if n<=21 else abs(n-21)*2 )
```

##parrot_trouble
```
def parrot_trouble(talking, hour):
    return ( talking and ( hour<7 or hour>20 ) )
```

##makes10
```
def makes10(a, b):
    return ( a+b==10 or a==10 or b==10 )
```

##near_hundred
```
def near_hundred(n):
    abs (n)
    return (abs(100-n)<=10 or abs(200-n)<=10)
```

##pos_neg
```
def pos_neg(a, b, negative):
    return ( ( a*b<=0 and not negative ) or ( a<=0 and b<=0 ) and negative)
```

##not_string
```
def not_string(str):
    return ( str if str[:3]=='not' else 'not '+str )
```

##missing_char
```
def missing_char(str, n):
    return( str.replace( str[n],"" ) )
```

##front_back
```
def front_back(str):
  lng = len(str)
  return ( str[::-1] if lng<=2 else ( str[lng-1:lng] + str[1:lng-1] + str[0] ) )
```

##front3
```
def front3(str):
  return str[0:3]*3
```
