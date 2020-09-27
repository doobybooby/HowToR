# Learn How To R
* It executes one line at a time, user must specify which line to execute
* "*#*" is used for comments

## Printing Char/Strings
* You can use "Quotation Marks" or 'Single Quotes' to print out a char/string.
* It doesn't matter which one you use

###### EX1
```R
"Hello World!" 
```
returns
```R
> "Hello World!"
[1] "Hello World!"
```

###### EX2
```R
'Bye World!"
```
returns
```R
> 'Bye World!'
[1] 'Bye World!'
```

## Types and Variables
* You assign a value by, variableName<- variableValue
* To check the type of a variable, *typeof(variable)* 
* Between int and double, it is default double

Atomic Data Type
1. Integer 
2. Double
3. Complex
4. Character (Char)
5. Logical (Boolean)
```R
# Integer
x <- 5L
x

# Double
y <- 7.9
y

# Complex
z <- 3+2i
z

# Char
c <- 'H'
c

# Logical
boo <- T
boo
```
Check the types
```R
typeof(x)
typeof(y)
typeof(z)
typeof(c)
typeof(boo)
```
Returns
```R
> typeof(x)
[1] "integer"

> typeof(y)
[1] "double"

> typeof(z)
[1] "complex"

> typeof(c)
[1] "character"

> typeof(boo)
[1] "logical"
```
## Integer
