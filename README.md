# 🐍  PYTHON-LEARNING
### My Python journey
---
### Table of Content
1. [Basic Print Statements](#-basic-print-statements)
2. [Single vs Double Quotes](#-single-vs-double-quotes)
3. [Multi-line Printing](#-multi-line-printing)
4. [Variables - Information Storage](#-variables---information-storage)





## 🖨️ Basic Print Statements

### Simple Print
```python
print("Hello, World!")
print("I am learning Python!")
print("This is awesome!")
```
**Key Points:**
- `print()` displays text on screen
- Empty `print()` creates blank lines
- Special characters and emojis make output fun!

---
### Print with Spacing
```python
print("My Information:")
print()  # Creates a blank line
print("Name: Alex")
print("Age: 16")
print()  # Another blank line
print("Thank you!")
```

### Special Characters & Emojis
```python
print("★ Special Characters ★")
print("→ Arrow pointing right")
print("♦ Diamond symbol")
print("🎉 Party emoji")
print("▓▓▓ Block characters")
```

## 📝 Single vs Double Quotes

### Both Work the Same
```python
print("This uses double quotes")
print('This uses single quotes')
```

### Smart Quote Choice
```python
# Use single quotes when text contains double quotes
print('My favorite food is "Fried Rice"')

# Use double quotes when text contains single quotes  
print("It's a lovely weather outside!")

### Multi line code
```python
print("My Daily Schedule:")
print("8:00 AM - Wake up")
print("9:00 AM - Breakfast")
print("10:00 AM - Study Python")
print("12:00 PM - Lunch")
print("2:00 PM - More Python practice!")
```

### New line character

```
print("Grocery List:\n🥛 Milk\n🍞 Bread\n🥚 Eggs\n🍎 Apples")
print("Today's Goals:\n✓ Learn Python basics\n✓ Practice coding\n✓ Have fun!")
```
### Creating and Using Basic Variables
```
name = "Alex"  # String variable
age = 16       # Number variable
is_student = True  # Boolean variable (True/False)

print("Basic Variable Usage:")
print("My name is", name)
print("I am", age, "years old")
print("Am I a student?", is_student)
```
### Modifying and Updating Variables
```
score = 0
print("Starting score:", score)

score = score + 10  # Add to the score
print("After bonus:", score)

score = score * 2   # Double the score
print("After doubling:", score)
```

```
name = "Python Beginner"
print("Status:", name)
name = "Python Expert"  # Variables can be updated
print("New status:", name)
```

### Variables in Calculations and Formatting
```
birth_year = 2008
current_year = 2024
calculated_age = current_year - birth_year

print("If you were born in", birth_year)
print("In", current_year, "you would be", calculated_age, "years old")
```

### Learn how input() waits for user response
```
name = input("What is your name? ")
print("Hello,", name, "! Nice to meet you!")

age = input("How old are you? ")
print("Wow,", age, "is a great age!")
```
###  Multi-Question Interactive Survey
```
print("\n🎮 Welcome to the Interest Survey! 🎮")

movie = input("What's your favorite movie? ")
food = input("What's your favorite food? ")
subject = input("What's your favorite school subject? ")

print(f"""
🌟 Your Interest Profile 🌟
━━━━━━━━━━━━━━━━━━━━━━━━━━━
🎬 Favorite Movie: {movie}
🍕 Favorite Food: {food}
📚 Favorite Subject: {subject}
━━━━━━━━━━━━━━━━━━━━━━━━━━━
Thanks for sharing!
""")
```
### Discovering data type
```
user_input = input("Enter any number: ")
print("You entered:", user_input)
print("Type of your input:", type(user_input))
```
### Data Type Behaviors
```
print("\n🔍 How Data Types Behave:")

# Strings can be combined
greeting = "Hello" + " " + "World"
print("String combination:", greeting)
```

```python
number_math = 10 + 15
print("Number calculation:", number_math)
```
```
print("String + String:", "5" + "3")  # This gives "53"
print("Number + Number:", 5 + 3)      # This gives 8
print("String × Number:", "Hi! " * 3)  # This repeats the string
```


### Convert strings to numbers for math

```python
num1 = int(input("Enter first number"))
num2 = int(input("Enter first number"))

addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

print(f"{num1} + {num2} = {addition}")
print(f"{num1} - {num2} = {subtraction}")
print(f"{num1} × {num2} = {multiplication}")
```

### Learn about float conversion for precise calculations


```python
print("\n💰 Financial Calculator")

price = input("Enter the price: $")
tax_rate = input("Enter tax rate (like 0.08 for 8%): ")
tip_percentage = input("Enter tip percentage (like 0.15 for 15%): ")
```
### Convert to floats for decimal calculations


```python
price_float = float(price)
tax_float = float(tax_rate)
tip_float = float(tip_percentage)

tax_amount = price_float * tax_float
tip_amount = price_float * tip_float
total = price_float + tax_amount + tip_amount

print(f"Price: ${price_float:.2f}")
print(f"Tax: ${tax_amount:.2f}")
print(f"Tip: ${tip_amount:.2f}")
print(f"Total: ${total:.2f}")
```

### To make decision
```
age = int(input("how old are you?"))

if age >=18:
  print("you can vote!")
if age  < 18:
  print("you are not old enough to vote yet.")
```


### Using if statements
```python
if grade >=90:
  print("Excellent! you got an A! ")
elif grade >= 80: #else if
  print("Great job! you got a B! ")
elif grade >= 70:
  print("Good work! you got a C! ")
elif grade >= 60:
  print("You passed with a D. ")
else: #catches the remaining condition
  print("you have to work harder. ")
  ```

