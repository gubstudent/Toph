# [Add Them Up](https://toph.co/p/add-them-up)
> Read two integer variables, calculate their sum, and print it.
### Input
The input will contain two integers AA and BB (-20000000 < A, B < 20000000−20000000<A,B<20000000).

### Output
Print the sum of the two integers.

### Solution
```python
add = input().split()
a,b = add
print(int(a)+int(b))
```
### split()
The **split()** method breaks up a string at the specified separator and returns a list of strings.

The syntax of *split()* method is:
```
.split(separator, maxsplit)
```
The *split()* method takes a maximum of 2 parameters:
* separator (optional)- Delimiter at which splits occur. If not provided, the string is splitted at whitespaces.
* maxsplit (optional) - Maximum number of splits. If not provided, there is no limit on the number of splits.

Learn more about [split()](https://www.programiz.com/python-programming/methods/string/split).
