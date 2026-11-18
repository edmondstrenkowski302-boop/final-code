# Python Programming Tutorial
print("=" * 50)
print("           -PYTHON PROGRAMMING TUTORIAL- ")
print("=" * 50)

# ---------- PART 1 ----------
print("=" * 50)
print("LESSON 1: WHAT IS PYTHON?")
print("=" * 50)

print("Python is a programming language created by")
print("Guido van Rossum in 1991.")
print("It is simple, easy to read, and easy to learn.")
print()

# ---------- PART 2 ----------
print("=" * 50)
print("LESSON 2: PRINTING OUTPUT")
print("=" * 50)

print("Use print() to show text on the screen.")
print('Example: print("Hello, World!")')
print("Output:  Hello, World!")
print()

# ---------- PART 3 ----------
print("=" * 50)
print("LESSON 3: BASIC DATA TYPES")
print("=" * 50)

print("int   - whole number    (10, 25, 100)")
print("float - decimal number  (3.14, 2.5)")
print('str   - text            ("Hello", "Edmond")')
print("bool  - True or False")
print()

# ---------- PART 4 ----------
print("=" * 50)
print("LESSON 4: LOGICAL OPERATORS")
print("=" * 50)

print("and - True only if BOTH are True")
print("      True and False = False")
print("or  - True if at least ONE is True")
print("      True or False = True")
print("not - reverses the result")
print("      not True = False")
print()

# ---------- PART 5 ----------
print("=" * 50)
print("LESSON 5: CONDITIONAL STATEMENTS")
print("=" * 50)

print("if   - runs if the condition is True")
print("elif - checks another condition")
print("else - runs if nothing else was True")
print()
print("Example:")
print("  age = 18")
print("  if age >= 18:")
print('      print("Adult")')
print("  else:")
print('      print("Minor")')
print("Output: Adult")
print("=" * 50)


# ---------- QUIZ ----------
score = 0

# Question 1
print("\nQuestion 1: Who created Python?")
print("A. Guido van Rossum")
print("B. Bill Gates")
print("C. Mark Zuckerberg")
answer = input("Your answer (A/B/C): ").upper()
if answer == "A":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect! The correct answer is A. Guido van Rossum")

# Question 2
print("\nQuestion 2: Which function prints output in Python?")
print("A. echo()")
print("B. print()")
print("C. display()")
answer = input("Your answer (A/B/C): ").upper()
if answer == "B":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect! The correct answer is B. print()")

# Question 3
print("\nQuestion 3: Which one is a string (str)?")
print('A. "Hello"')
print("B. 10")
print("C. True")
answer = input("Your answer (A/B/C): ").upper()
if answer == "A":
    print("Correct!")
    score = score + 1
else:
    print('Incorrect! The correct answer is A. "Hello"')

# Question 4
print("\nQuestion 4: What is the result of True and False?")
print("A. True")
print("B. False")
print("C. Error")
answer = input("Your answer (A/B/C): ").upper()
if answer == "B":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect! The correct answer is B. False")

# Question 5
print("\nQuestion 5: Which keyword checks another condition after an if?")
print("A. if")
print("B. elif")
print("C. else")
answer = input("Your answer (A/B/C): ").upper()
if answer == "B":
    print("Correct!")
    score = score + 1
else:
    print("Incorrect! The correct answer is B. elif")


# ---------- FINAL SCORE ----------
print("\n" + "=" * 50)
print("Your Score:", score, "/ 5")

if score == 5:
    print("Excellent! Perfect score!")
elif score == 4:
    print("Good job! Konti na lang!")
elif score == 3:
    print("Nice! Good job!")
else:
    print("Try again! Kaya mo yan!")
print("=" * 50)
