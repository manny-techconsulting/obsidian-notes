A slice is a potion of a sequence.

Slices notation has the following syntax:
```python
'''
Regular Slice
'''
a[start:stop]  # items start through stop-1
a[start:]      # items start through the rest of the array
a[:stop]       # items from the beginning through stop-1
a[:]           # a copy of the whole array
```

Extended Slices support the third ``step`` argument.
At times, the ``step`` argument is used exclusively; therefore, it has the notation ``[::step]``.

```python
'''
Extended Slice
'''
a[start:stop:step]
a[::step]
```