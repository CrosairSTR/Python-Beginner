# Printing 

## Syntax --
Print("")

### !Code Example : 
  print("Hello World!!")

### !Output :
  Hello World!!

## Keep in Mind
1. Python executes code in order

### !Code Example #1: 
  print("    /|")
  print("   / |")
  print("  /  |")
  print(" /   |")
  print("/____|")

### Output #1:
    /|
   / |
  /  |
 /   |
/____|

### !Code Example #2:
  print("/____|")
  print("    /|")
  print("   / |")
  print("  /  |")
  print(" /   |")

### !Output #2:
/____|
    /|
   / |
  /  |
 /   |

# Variables & Data Types

## Naming Convention
1. Starts with lowercase 
  Ex: name
2. If there are 2 or more words, The words are seperated with underscore [_]
  Ex: character_name

## Advantages
1. Variables have to be defined just once and can be used multiple times.
2. If we want to change a word and we have it in a variable, if we just change the variable all it's uses will be automatically updated.

## Using Variables Multiple Times
1. Variables can be used again by adding the "+" symbol

### !Code Example #1: 
  name = "George"
  age = "70"

  print("There was a man named " + name + ",")
  print("He was " + age + " years old.")
  print("He really liked the name " + name + ",")
  print("But didn't like being " + age + ".")

### Output #1: 
  There was a man named George,
  He was 70 years old.
  He really liked the name George,
  But didn't like being 70.

## Different Types
### String
  It starts and ends with quotation marks [""]
    Ex: name = "Tom"

### Numbers
  It doesn't need quotation marks
    Ex: age = 50
  We can also define decimal numbers as
    Ex: decimal_number = 50.67895

### Boolean Values
  It is either True or False.
    Ex: is_male = True
          OR
    Ex: is_male = False