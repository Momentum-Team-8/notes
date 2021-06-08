# Python Lists

## 💡 To run this code, type `python` at the command line prompt.

That will start a Python REPL where you can run Python code! Good practice would be to type this in there and see what you get.

Don't type the `>>>`. That is showing you the start of the prompt in the Python REPL.

#### Collections enclosed by [], trailing comma is used, indexed like JS arrays

```py
>>> nerf_guns = ['Rampage', 'Shockwave RD-15', 'Mediator',]
>>> my_list[0]
'Rampage'
```

### Frequently used list methods

```py
>>> nerf_guns.append('Jolt')
>>> nerf_guns
['Rampage', 'Shockwave RD-15', 'Mediator', 'Jolt']
>>> nerf_guns.pop() # this gives you back the thing you popped off the list, and alters the list
'Jolt'
>>> nerf_guns
['Rampage', 'Shockwave RD-15', 'Mediator',]
>>> nerf_guns.remove('Mediator') # this does not return the thing you removed, but it does change the list
>>> ['Rampage', 'Shockwave RD-15']
```

---

## Python Dictionaries

#### Similar to JS objects, key: value pairs enclosed by {}

Notice that you need to put quotation marks around the keys, unlike in JS objects (but like JSON!).

Trailing commas also 👍 in dictionaries, as in lists.

```py
>>> fruit_amounts = {
    'apples': 3,
    'bananas': 4,
    'papayas': 2,
    }
```

### Obtain values by their keys, NOT their position

You need brackets and a string as a key. Dot notation will not work like it does in JS.

```py
>>> fruit_amounts['apples']
3
```

---

### Add or reassign values to dictionaries like this:

```py
>>> fruit_amounts['pears'] = 5
>>> fruit_amounts['bananas'] = 10
>>> fruit_amounts
{'apples': 3, 'bananas': 10, 'papayas': 2, 'pears': 5}
```

---

## Python Tuples

#### Ordered collections enclosed by (), tuples are immutable (can't be changed)

```py
>>> dimensions = (2, 4, 10)
```

### Obtain data using index, as with lists

```py
>>> dimensions[1]
4
```

---

### Unpack tuples by assigning each value to a variable

```py
>>> length, width, height = (2, 4, 10)
>>> length
2
>> width
4
>>> height
10
```

---
