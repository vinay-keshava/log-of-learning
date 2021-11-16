# 16-NOV-2021

### 1 - Python Interpreter
```
print("Hello Python Interpreter \n>>> ")
```
- Python interpreter can be exited using the functions exit() or quit().
- Three Modes of calling a python code script mode,interpretive mode,command mode.
  - Script mode  :$python3 filename.py
  - Interpretive Mode: To execute the file in the interpretive mode we use the -i option.
  - $python3 -i filename.py
```
#1.py
a=10
b=20
```
  - after the file is executed , the python interpretive prompt is opened to communicate using the variables in the interpreter.
  - Command Mode(-c)  #command mode is 
  - $python3 -c "print('hi')" #the command inside the inverted commass is executed. 
  - python3 -c "import math;print(math.pi)"
- Python uses UTF-8 (Unicode Transmission Format) 
### 2 - Python Strings
- Raw Strings 
```
print("Tommorow is a\national Holiday") #\n is taken as escape sequences
#Raw strings can be used to ignore escape sequences
print(r"Tommorow is a\national Holiday") 
# Here \n escape sequence is ignored
```
  - Python also supports Negative Indexing.
  - Python Strings are immutable objects ,assigning to the indexed position leads to TypeError;
