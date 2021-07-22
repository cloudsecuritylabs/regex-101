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

[a-z]at -represent a range , not a number range however. do not use [60-100]
```
hat
Hat
hAt
haT
hattric
h a t
```

## Negative Character Set

[^s]at - ^ tells s can't be there at the beginning.
```
hat
Hat
hAt
haT
hattric
h a t
```

## greedy charecters
~~~
\d digits [0-9]
\w word char [a-zA-Z0-9]
\s whitespace [\t\r\n]
\D not a digit [^0-9]
\W not word char [^a-zA-Z0-9]
\S Not Whitespace [^\t\r\n]
~~~

## Repetation metacharacters

~~~
* preceding item, 0 or more times
+ preceding item, 1 or more times
? preceding item, 0 or 1 time (optional)
~~~


## Quantified Repetation

~~~
{min, max}
\d{5,9}
\d{5}
\d{0,} same as \d*
/\d{3}-\d{3}-\d{4}
~~~


## Lazy Repetation

~~~
\d*?
\d+?
~~~

## Grouping Metacharacters ()
