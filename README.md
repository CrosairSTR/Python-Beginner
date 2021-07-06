# Printing in Python

## Syntax
```python
print("")
```

### Code Example --
```python
print("Hello World!!")
```
### Output --
![Output#1](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-1.PNG "Output 1")

## Keep in Mind
   1. Python executes code in order

### Code Example --
```python
print("    /|")
print("   / |")
print("  /  |")
print(" /   |")
print("/____|")
```
### Output --
![Output#2](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-2.PNG "Output 2")

### Code Example --
```python
print("/____|")
print("    /|")
print("   / |")
print("  /  |")
print(" /   |")
```

### Output --
![Output#3](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-3.PNG "Output 3")

# Variables and data Types
## Naming Convention
   1. Starts with Lowercase  
      ``` python
      name
      ```
   2. If there are 2 or more words, The words are seperated with underscore [_]  
      ```python
      character_name
      ```

## Advantages
   1. Variables have to be defined just once and can be used multiple times.
   2. If we want to change a word and we have it in a variable, if we just change the variable all it's uses will be automatically updated.

## Using Variables Multiple Times
   1. Variables can be used again by adding the "+" symbol

### Code Example [Syntax and using '+'] --
```python
name = "George"
age = "70"

print("There was a man named " + name + ",")
print("He was " + age + " years old.")
print("He really liked the name " + name + ",")
print("But didn't like being " + age + ".")
```

### Output --
![Output#4](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-4.PNG "Output 4")

### Code Example [Easiness of Changing] --
```python
name = "John"
age = "100"

print("There was a man named " + name + ",")
print("He was " + age + " years old.")
print("He really liked the name " + name + ",")
print("But didn't like being " + age + ".")
```
### Output --
![Output#5](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-5.PNG "Output 5")

### Code Example [Changing the Variable in between] --
```python
name = "John"
age = "100"

print("There was a man named " + name + ",")
print("He was " + age + " years old.")

name = "Tom"
age = "1500"

print("He really liked the name " + name + ",")
print("But didn't like being " + age + ".")
```
### Output --
![Output#6](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-6.PNG "Output 6")

## Different Types
### String
   + It starts and ends with quotation marks [""]  
       ``` python
       name = "Tom"
       ```

### Numbers
   + It doesn't need quotation marks  
       ``` python
       age = 50
       ```
   + We can also define decimal numbers as  
       ``` python
       decimal_number = 50.67895
       ```

### Boolean Values
   + It is either True or False.  
       ``` python
       is_male = True  
       is_male = False
       ```

# Working With Strings

## Newline Character
   * The Newline Character is '\n'
   * It inserts a line break

### Code Example --

```python
print("Hello\nWorld")
```

### Output -- 
![Output#7](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-7.PNG "Output 7")

### Code Example [insert a double quote without python yelling at us]

``` python
print("\"Hello\"World\"")
```
### Output --

![Output#8](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-8.PNG "Output 8")

### Code Example [Concatenation of Strings]
```python
greeting = "Hello"

print(greeting + " Sahaya" + " Noel")
```
### Output --
![Output#9](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-9.PNG "Output 9")

### Code Example [Making string Lowercase] --
```python
greeting = "Hello"

print(greeting.lower())
```

### Output --
![Output#10](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-10.PNG "Output 10")

### Code Example [Making string Uppercase] --
```python
greeting = "Hello"

print(greeting.upper())
```

### Output --
![Output#11](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-11.PNG "Output 11")

### Code Example [Checking if a string is lower or upper case] --
```python
greeting = "Hello"

print(greeting.isupper()) # Prints boolean value. Value is False as "Hello" is not totally uppercase

print(greeting.islower()) # Prints False again as 'greeting is not totally lowercase'

print(greeting.upper().isupper()) # Using two string methods at the same time. Prints 'True'
```

### Output --
![Output#12](https://github.com/coder-sahaya-noel/Python-Beginner/blob/main/images/Output-12.PNG "Output 12")