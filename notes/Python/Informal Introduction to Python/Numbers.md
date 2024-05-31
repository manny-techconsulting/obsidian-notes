The interpreter acts as a simple calculator: you can type an expression at it and it will write the value. 

Expression syntax is straightforward: the operators `+`, `-`, `*` and `/` can be used to perform arithmetic; parentheses (`()`) can be used for grouping. 

## Basic Arithmetic

**Addition**

```python
2 + 2
```


**Subtraction**
```python
5 - 6
```


**Multiplication**
```python
3 * 4
```


**Division**
```python
6 / 5
```

The ``/`` operator always returns a *<span style="color:rgb(0, 176, 240)">float</span>*. To do floor division and return an <span style="color:rgb(0, 176, 240)">int</span> use the ``//`` operator. To return the remainder, use the ``%`` operator.

**Floor Division**
```python
6 // 5
```

**Mod**
```python
7 % 3
```


## Additional Operations

| Operation        | Result                                                                            | Notes  | Full Docs                                                                         |
| ---------------- | --------------------------------------------------------------------------------- | ------ | --------------------------------------------------------------------------------- |
| `x + y`          | sum of _x_ and _y_                                                                |        |                                                                                   |
| `x - y`          | difference of _x_ and _y_                                                         |        |                                                                                   |
| `x * y`          | product of _x_ and _y_                                                            |        |                                                                                   |
| `x / y`          | quotient of _x_ and _y_                                                           |        |                                                                                   |
| `x // y`         | floored quotient of _x_ and _y_                                                   | (1)(2) |                                                                                   |
| `x % y`          | remainder of `x / y`                                                              | (2)    |                                                                                   |
| `-x`             | _x_ negated                                                                       |        |                                                                                   |
| `+x`             | _x_ unchanged                                                                     |        |                                                                                   |
| `abs(x)`         | absolute value or magnitude of _x_                                                |        | [`abs()`](https://docs.python.org/3/library/functions.html#abs "abs")             |
| `int(x)`         | _x_ converted to integer                                                          | (3)(6) | [`int()`](https://docs.python.org/3/library/functions.html#int "int")             |
| `float(x)`       | _x_ converted to floating point                                                   | (4)(6) | [`float()`](https://docs.python.org/3/library/functions.html#float "float")       |
| `complex(re,im)` | a complex number with real part _re_, imaginary part _im_. _im_ defaults to zero. | (6)    | [`complex()`](https://docs.python.org/3/library/functions.html#complex "complex") |
| `c.conjugate()`  | conjugate of the complex number _c_                                               |        |                                                                                   |
| `divmod(x, y)`   | the pair `(x // y, x % y)`                                                        | (2)    | [`divmod()`](https://docs.python.org/3/library/functions.html#divmod "divmod")    |
| `pow(x, y)`      | _x_ to the power _y_                                                              | (5)    | [`pow()`](https://docs.python.org/3/library/functions.html#pow "pow")             |
| `x ** y`         | _x_ to the power _y_                                                              | (5)    |                                                                                   |