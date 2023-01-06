# Dumbness--
A weird programin language made in python

# Instant code using the interpreter
Instant code will be runned when the ENTER button is pressed,</br>
math equations can be entered,
```
dumb > 1+1
2
```
# Running a code file
To run a code file, use whatever file extension you want,
run the file using ```run(filepath)```
# Hello World
the print function prints
```py
print("Hello World")
```
# Variables
vars are made using the `var` keyword
```py
var number = 4
print(number)
```
# Comments
comments are only one-lined and created using th `#` keyword
```py
# This is a comment
```
# Functions
functions are defined using the `fun` keyword and their code is started with a `->` as diffrent from `:` in python and `{` and other languages
```py
code:
fun why() -> print("why")
why()
output:
why
```
function params are used the same way as in python:
```py
code:
fun egg(text) -> print("egg " + text)
egg("yolk")
output:
egg yolk
```
# Loops
loops are used with either `for <varriable> = <starting value> to <limit> do <code> enddo` or `while <expression> do <code> enddo`
## For loop
```py
code :
for i = 0 to 3 do
print("EGG YOLK")
enddo

output :
EGG YOLK
EGG YOLK
EGG YOLK
```
## While Loop
```py
code :
var i = 0
while i < 3 do
var i = i + 1
print(i)
enddo

output :
0
1
2
```

# Input
input is handled by using either `input` for strings, `input_int` for ints, or `input_float` for floats.
```py
code :
var text = input("Enter your text here : ")
var full_num = input_int("Enter a full number here : ")
var decimal_num = input_float("Enter a decimal number here : ")
print(text)
print(full_num)
print(decimal_num)

output : 
Enter your text here : <p style = "color: dark_green;">yeello</p>
Enter a full number here : <p style = "color: dark_green;">1</p>
Enter a decimal number here : <p style = "color: dark_green;">3.123</p>
yeello
1
3.123
0
