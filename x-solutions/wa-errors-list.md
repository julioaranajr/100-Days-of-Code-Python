# List of Errors - Knowledge Base

## Week A

### Error 1

SyntaxError: unterminated string literal (detected at line 1)

```bash
Traceback (most recent call last):
  File "main.py", line 2
    print(Hello world")
                     ^
SyntaxError: unterminated string literal (detected at line 2)

```

solution: # Add the missing quotation mark at the beginning of the string

```python
print("Hello world")
```

Explanation: The string is missing the opening quotation mark.

### Error 2

IndentationError: unexpected indent

```python
Traceback (most recent call last):
  File "main.py", line 4
    print("Hello world")
IndentationError: unexpected indent
```

solution: # Remove the extra space at the beginning of the line

```python
print("Hello world")
```

Explanation: The second print statement has an extra space at the beginning of the line. This is causing the error

### Error 3

SyntaxError: unterminated string literal (detected at line 1)

```python
Traceback (most recent call last):
  File "main.py", line 1
    print("Hello world"
         ^
SyntaxError: '(' was never closed
```

solution: # Add the missing quotation mark at the end of the string

```python
print("Hello world")
```

Explanation: The string is missing the closing quotation mark.
