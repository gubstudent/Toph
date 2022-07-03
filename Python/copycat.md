# [Copycat](https://toph.co/p/copycat)
> Read an integer variable and print it.

### Input
The input will contain an integer AA (-200000000 < A < 200000000−200000000<A<200000000).

### Output
Print the integer.

 Input | Output
|--------------------|--------------------|
| 2| 2|

### Solution
```python
num = int(input())
print("{}".format(num))
```

### int()
The int() method returns an integer object from any number or string.

The *syntax* of **int()** method is:
```
int(x=0, base=10)
```
**int()** method takes two arguments:

* x - Number or string to be converted to integer object.
> The default argument is zero.
* base - Base of the number in x.
> Can be 0 (code literal) or 2-36.

Learn more about [int()](https://www.programiz.com/python-programming/methods/built-in/int).

### input()
**input()** function is used to take user input. By default, it returns the user input in form of a string.

The *syntax* of **input()** method is:
```
input(prompt)
```
The **input()** function takes a single optional argument:

* prompt (Optional) - a string that is written to standard output (usually screen) without trailing newline

Learn more about [input()](https://www.programiz.com/python-programming/methods/built-in/input).


### format()
The **format()** method returns a formatted representation of the given value controlled by the format specifier.

The *syntax* of the **format()** method is:
```
format(value[, format_spec])
```
The **format()** function takes two parameters:

* value - value that needs to be formatted
* format_spec - The specification on how the value should be formatted.

The format specifier could be in the format:
```
[[fill]align][sign][#][0][width][,][.precision][type]
where, the options are
fill        ::=  any character
align       ::=  "<" | ">" | "=" | "^"
sign        ::=  "+" | "-" | " "
width       ::=  integer
precision   ::=  integer
type        ::=  "b" | "c" | "d" | "e" | "E" | "f" | "F" | "g" | "G" | "n" | "o" | "s" | "x" | "X" | "%"
```
Learn more about [format()](https://www.programiz.com/python-programming/methods/built-in/format).
