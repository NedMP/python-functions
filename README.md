# python-functions
---
### Four types of functions
IN: False | OUT: True
```python
def outOnly():
    hello = "Hello, world!" 
    return hello

print(outOnly())
```
`\> Hello, world!`
RETURN var = hello

IN: True | OUT: False
```python
def inOnly(str):
    print(str)

inOnly("Hello, world!)
```
`\> Hello, world!`
INPUT str = "Hello, world!", return nothing

IN: True | OUT: True
```python
def inOut(str):
    return str + ", world!"

print(inOut("Hello"))
```
`\> Hello, world!`
INPUT str = "Hello", RETURN str + ", world!"

IN: False | OUT: False
```python
def notInOut():
    print("Hello, world!")

notInOut()
```
`\> Hello, world!`
Only runs the print statement, no data is passed to or from the function 