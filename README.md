# ctime

ctime is a python library for how long does the function takes for execute completally

---

## Usage

```python
import ctime

@ctime.ctime() # Optional args: simplified, printable
def function():
    ... # Your code
    
function()
```

`Function "function_name" took X seconds.`