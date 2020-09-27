# Learn How To R
* It executes one line at a time, user must specify which line to execute
* "*#*" is used for comments

## Types and Variables
* You assign a value by, variableName<- variableValue
* To check the type of a variable, *typeof(variable)* 
* Between int and double, it is default double
* You can either use "Quotation Marks" or 'Single Quotes' to print out a characters

Atomic Data Type
1. Integer 
2. Double
3. Complex
4. Character (Char/String)
5. Logical (Boolean)
  * ==, equal to
  * !=, not equal to
  * <, less than
  * \>, greater than
  * <=, less than or equal to
  * \>= greater than or equal to
  * !, not
  * |, or
  * &, and
  * isTrue(x)

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
# LOOPS
* If you want to print whitin the loop, print("Hello World")
* Make sure the loop is not infinite

## While Loop
* While(condition is True) {do something}

###### EX, while(counter is less than 12){Print counter. Add 1 to counter}
```R
counter <- 0
while(counter <12){
  print(counter)
  counter <- counter +1
}
```

## For Loop
* for(interation){do something}

###### EX, for(i in 1-5) {print i}
```R
for(i in 1:5){
  print(i)
}


# VECTORS
