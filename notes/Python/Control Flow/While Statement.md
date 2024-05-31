The ``while`` statement will execute as long as a condition is true.

```python
i = 10
while i != 0:
	print(i)
	i-=1
```

With the ``else`` statement, we can run a piece of code once the condition becomes false.

```python
list = [0,1,2,3,4]
while len(list) != 0:
	print(list.pop())
else:
	print("List is Empty")
```