Python can manipulate text (represented by type [`str`](https://docs.python.org/3/library/stdtypes.html#str "str"), so-called “strings”) as well as numbers. 
This includes characters “`!`”, words “`rabbit`”, names “`Paris`”, sentences “`Got your back.`”, etc. “`Yay! :)`”. 
They can be enclosed in single quotes (`'...'`) or double quotes (`"..."`).
Note: Strings are **immuatable**.

## Escaping Characters

To quote a quote, we need to “escape” it, by preceding it with `\`. Alternatively, we can use the other type of quotation marks:

## Raw Strings

If you don’t want characters prefaced by `\` to be interpreted as special characters, you can use _raw strings_ by adding an `r` before the first quote:

There is one subtle aspect to raw strings: a raw string may not end in an odd number of `\` characters; see [the FAQ entry](https://docs.python.org/3/faq/programming.html#faq-programming-raw-string-backslash) for more information and workarounds.

## Output 

String literals can span multiple lines.
One way is using triple-quotes: `"""..."""` or `'''...'''`. 
End of lines are automatically included in the string, but it’s possible to prevent this by adding a `\` at the end of the line. The following example:

## Operations

Strings and variables can be concatenated (glued together) with the `+` operator. Strings may also repeated with `*` operator:

Two or more _string literals_ (i.e. the ones enclosed between quotes) next to each other are automatically concatenated.
This feature is particularly useful when you want to break long strings:

## Indexing

Strings can be _indexed_ (subscripted), with the first character having index 0. There is no separate character type; a character is simply a string of size one:

Indices may also be negative numbers, to start counting from the right:

## Formatted String Literals

Formatted string literals or f-strings using prefixes ``'f'`` or ``'F'``. 
These strings may contain replacement fields, which are expressions delimited by curly braces `{}`. 
While other string literals always have a constant value, formatted strings are really expressions evaluated at run time.

```python
name = "John Doe"
print(F"Hello, I am {name}")
```
