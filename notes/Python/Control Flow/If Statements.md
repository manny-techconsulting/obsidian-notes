Perhaps the most well-known statement type is the `if` statement:
```python
val = int(input("Enter an integer: "))
if val % 2 == 0:
	print("Even")
else:
	print("Odd")
```

There can be zero or more ``else`` parts, and the  ``else`` part is optional. The keyword `'elif'` is short for ‘else if’, and is useful to avoid excessive indentation. An  `if` … `elif` … `elif` … sequence is a substitute for the `switch`or `case` statements found in other languages.