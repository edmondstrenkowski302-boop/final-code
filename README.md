# PYTHON TUTORIAL 

print("==============================")

print("        PYTHON TUTORIAL")

print("==============================")

choice = ""

while choice != "0":
    print()
    print("===== MAIN MENU =====")
    print("1. Part 1 - What is Python?")
    print("2. Part 2 - Printing Output")
    print("3. Part 3 - Basic Data Types")
    print("4. Part 4 - Logical Operators")
    print("5. Part 5 - Conditional Statements")
    print("6. Quiz")
    print("0. End the program")
    choice = input("Choose: ")

    # ---------------- PART 1 ----------------
    if choice == "1":
        print()
        print("--- Part 1: What is Python? ---")
        print("Python is a programming language created by")
        print("Guido van Rossum in 1991.")
        print("It is simple, easy to read, and easy to learn.")

    # ---------------- PART 2 ----------------
    elif choice == "2":
        print()
        print("--- Part 2: Printing Output ---")
        print("Use print() to show text on the screen.")
        print("Hello, World!")       # text needs quotes
        print(100)                   # numbers do not need quotes
        print("Hello", "Edmond")      # a comma prints many things at once

    # ---------------- PART 3 ----------------
    elif choice == "3":
        print()
        print("--- Part 3: Basic Data Types ---")
        my_whole = 25              # int (whole number)
        my_decimal = 3.14          # float (decimal number)
        my_text = "Edmond"         # str (text)
        my_truth = True            # bool (True or False)
        print(my_whole, type(my_whole))
        print(my_decimal, type(my_decimal))
        print(my_text, type(my_text))
        print(my_truth, type(my_truth))

    # ---------------- PART 4 ----------------
    elif choice == "4":
        print()
        print("--- Part 4: Logical Operators ---")
        a = True
        b = False
        print("a =", a)
        print("b =", b)
        print("a and b :", a and b)   # True only if BOTH are True
        print("a or b  :", a or b)    # True if at least ONE is True
        print("not a   :", not a)     # reverses the result

    # ---------------- PART 5 -------------------------
    elif choice == "5":
        print()
        print("--- Part 5: Conditional Statements ---")
        # if runs if the condition is True
        # elif checks another condition
        # else runs if nothing else was True
        age = 18
        print("age =", age)
        if age >= 18:
            print("Adult")
        else:
            print("Minor")

        age = 12
        print("age =", age)
        if age >= 18:
            print("Adult")
        elif age >= 13:
            print("Teenager")
        else:
            print("Child")

    # ---------------- QUIZ ------------------
    elif choice == "6":
        print()
        print("--- Quiz ---")
        print("You get 2 tries for every question.")
        score = 0

        # Question 1
        print()
        print("Question 1: Who created Python?")
        print("A. Guido van Rossum")
        print("B. Bill Gates")
        print("C. Mark Zuckerberg")
        tries = 0
        while tries < 2:
            answer = input("Your answer (A/B/C): ")
            if answer == "A":
                print("Thats Correct Wonderful")
                score = score + 1
                break
            tries = tries + 1
            if tries == 1:
                print("ohh thats incorrect try again!")
            else:
                print("ohh thats incorrect. The correct answer is A.")

        # Question 2
        print()
        print("Question 2: Which function prints output in Python?")
        print("A. echo()")
        print("B. print()")
        print("C. display()")
        tries = 0
        while tries < 2:
            answer = input("Your answer (A/B/C): ")
            if answer == "B":
                print("Thats Correct Wonderful")
                score = score + 1
                break
            tries = tries + 1
            if tries == 1:
                print("ohh thats incorrect try again!")
            else:
                print("ohh thats incorrect. The correct answer is B.")

        # Question 3
        print()
        print("Question 3: Which one is a string (str)?")
        print("A. \"Hello\"")
        print("B. 10")
        print("C. True")
        tries = 0
        while tries < 2:
            answer = input("Your answer (A/B/C): ")
            if answer == "A":
                print("Thats Correct Wonderful")
                score = score + 1
                break
            tries = tries + 1
            if tries == 1:
                print("ohh thats incorrect try again!")
            else:
                print("ohh thats incorrect. The correct answer is A.")

        # Question 4
        print()
        print("Question 4: What is the result of True and False?")
        print("A. True")
        print("B. False")
        print("C. Error")
        tries = 0
        while tries < 2:
            answer = input("Your answer (A/B/C): ")
            if answer == "B":
                print("Thats Correct Wonderful")
                score = score + 1
                break
            tries = tries + 1
            if tries == 1:
                print("ohh thats incorrect try again!")
            else:
                print("ohh thats incorrect. The correct answer is B.")

        # Question 5
        print()
        print("Question 5: Which keyword checks another condition after an if?")
        print("A. if")
        print("B. elif")
        print("C. else")
        tries = 0
        while tries < 2:
            answer = input("Your answer (A/B/C): ")
            if answer == "B":
                print("Thats Correct Wonderful")
                score = score + 1
                break
            tries = tries + 1
            if tries == 1:
                print("ohh thats incorrect try again!")
            else:
                print("ohh thats incorrect. The correct answer is B.")

        # Final score
        print()
        print("==============================")
        print("Your Score:", score, "/ 5")
        if score == 5:
            print("Excellent! Perfect score!")
        elif score == 4:
            print("Good job!!")
        elif score == 3:
            print("Nice! Good job!")
        else:
            print("Try again!!")
        print("==============================")

    # ---------------- END ----------------
    elif choice == "0":
        print("Goodbye! Happy coding!")

    else:
        print("Please type 1, 2, 3, 4, 5, 6, or 0.")
