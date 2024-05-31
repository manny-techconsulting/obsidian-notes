The `for` statement in Python differs a bit from what you may be used to in C or Pascal. 

Rather than always iterating over an arithmetic progression of numbers (like in Pascal), or giving the user the ability to define both the iteration step and halting condition (as C), Python’s `for` statement iterates over the items of any sequence (a list or a string), in the order that they appear in the sequence. 

##### for statement 
```python
words = ["i", "know", "words"]
for w in words:
	print(w + "!")
```

###### range 
If you do need to iterate over a sequence of numbers, the built-in function `range()` comes in handy. 

```python
sum = 0
for n in range(10):
	sum += n
print(sum)
```

To iterate over the indices of a sequence, you can combine ``range()`` and ``len()`` as follows:

```python
objs = ["Book", "Pencil", "Car"]
for i in range(len(objs)):
	print(i, objs[i])
```
###### enumerate
In most such cases, however, it is convenient to use the ``enumerate()`` function.

```python
seasons = ['Spring', 'Summer', 'Fall', 'Winter']
print(list(enumerate(seasons)))
```


