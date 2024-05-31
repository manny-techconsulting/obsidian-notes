## Break

The ``break`` statement breaks out the innermost ``for`` or ``while`` loop.
The ``else`` statement **does not run** if the loop was terminated by a break.

```python
for i in range(10):
	print(i)
	if i == 5:
		break
else:
	print("Done") ## Does not run since terminated by break
```

## Continue

The ``continue`` statement continues with the next iteration of the loop.

```python
for i in range(10):
	if i != 0:
		print(i)
		continue
	print(F'Here is a zero:\t{i}')
```

## Pass

The ``pass`` statement does nothing.

It can be used when a statement is required syntactically but the program requires no action.
This is commonly used for creating minimal classes.

```python
class Empty:
	pass
```

## Match

A ``match`` statement takes an expression and compares its value to successive patterns given as one or more case blocks.

Only the first pattern that matches gets executed and it can also extract components (sequence elements or object attributes) from the value into variables.

Note the last block: the “variable name” `_` acts as a _wildcard_ and never fails to match. If no case matches, none of the branches is executed.

You can combine several literals in a single pattern using `|` (“or”):

```python
def http_error(status):
    match status:
        case 400:
            return "Bad request"
        case 404:
            return "Not found"
        case 418:
            return "I'm a teapot"
        case 401 | 403 | 404:
	        return "Not Allowed"
        case _:
            return "Something's wrong with the internet"

print(http_error(403))
```


