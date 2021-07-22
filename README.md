# regex-101

## Literal Character
/hat/ matches "hat"
Case-sensitive by default
```
hat
Hat
hAt
haT
hattric
h a t
```

## Literal Character
/pa/
```
papa
paparazzi 
```

## Metacharacters
- .  any character but newline; one single charecter

/5.00/
~~~
5.00
5500
5-00
5x00 
~~~

## Escaping metacharacter

/\./

/5\.00/     -> this time exact match
~~~
5.00
5500
5-00
5x00 
~~~

## Control characters

\t, \r, \n
u\na
~~~
you
are
~~~

## Character Set

[hz]at - square braces represent a single charecter
```
hat
Hat
hAt
haT
hattric
h a t
```


## Character Range

[a-z]at -represent a range
```
hat
Hat
hAt
haT
hattric
h a t
```
