# Core Python

## REPL

if you are using pycharm press shift 2 times and search "Python Console" otherwise you must open your terminal and type "python"
then you can access to the python prompt.

This prompt allows you to insert fragments of python code and show you instant result, try with the below examples

`2 + 2`

`3 * 5`

Remember "_" operator, ths allows you to refer the last result you have, try with this code

`_`

`_ * 2`

Also, you are available to assign variables 

`x = 5`

this action won't show you a result but if you run this 

`x`

then will show you the value of that variable

Also, you can run function like print

`print("python")`

Remember python is a significant whitespace language, what I mean is **take care with the indentation !!**

**Read this `import this` in your python prompt**

Use help function `help()` as an argument you must provide the module or the element of the module you want to know

Import module `import math`

import function for module `from math import factorial`

import function for module with alias `from math import factorial as fac`

## Relational operators

| Operator | Meaning                          |
|----------|----------------------------------|
| ==       | value equality / equivalence     |
| !=       | value inequality / inequivalence |
| <        | grater than                      |
| <=       | less-than or equal               |
| >=       | greater-than or equal            |

## Control flow

### Sequential

default mode
```pycon
h = 42

print(42)

"42"
```

### Conditional statement
Branch execution based on the value of an expression

- If

```python
if True:
    print("It's true!")
    
"It's true!"
```
- Else

```python
h = 42

if h > 50:
    print("Greater than 50")
else:
    print("50 or smaller")
    
"50 or smaller"
```
- Elif
```pycon
h = 42

if h > 50:
    print("Greater than 50")
elif h < 20:
    print("Less than 20")
else:
    print("between 20 and 50")
"between 20 and 50"
```

### Looping
- While
```pycon
c = 5
while c != 0:
    print(c)
    c -= 1
    
5
4
3
2
1
```
- Break
```pycon
while True:
    response = input()
    if int(response) % 7 == 0:
        break
4
4
7
```