
This is how we do it.

```Python
def fibonacci():
    a, b = 1, 1
    while True:
        yield a
        a, b = b, a + b
```
