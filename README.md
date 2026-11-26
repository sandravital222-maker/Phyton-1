while True:

    print(“\n========================================“)

    print(“       THE PYTHON TUTORIAL PROGRAM    “)

    print(“========================================“)

    print(“[1] = INTRODUCTION TO PROGRAMMING”)

    print(“[2] = PYTHON BASIC SYNTAX”)

    print(“[3] = BASIC DATA TYPES IN PYTHON”)

    print(“[4] = ARITHMETIC OPERATORS AND EXPRESSIONS”)

    print(“[5] = BASIC INPUT AND OUTPUT IN PYTHON”)

    print(“[6] = CONDITIONAL STATEMENTS IN PYTHON”)

    print(“[7] = LOGICAL OPERATORS”)

    print(“[8] = INTRODUCTION TO ITERATION AND LOOPS”)
    
    print(“----------------------------------------“)
    
    print(“[9] PYTHON QUIZ CHALLENGE”)

    print(“[10] EXIT”)
    
    print(“==========================================“)

    choice = input(“Choose a lesson or activity (1-10): “)

    if choice == “1”:

        print(“\n=== INTRODUCTION TO PROGRAMMING ===“)

        print(“Programming is giving instructions to a computer.”)

        print(“Python is a programming language.”)

        print(“It is used to create programs and applications.”)
   
        print(“\nPython syntax refers to the rules for writing code correctly.”)

        print(“ PRINT()”)

        print(“Meaning: Used to display text or output on the screen.”)

        print("Example: print('Hello World')")

        print(“ QUOTATION MARKS (‘ ‘ or “ “)”)

        print(“Meaning: Used to enclose text or string values.”)

        print(‘Example: name = “Sandra”’)

        print(" EQUAL SIGN (=)”)

        print(“Meaning: Used to assign a value to a variable.”)

        print(‘Example: age = 18’)

        print(“ DOUBLE EQUAL SIGN (==)”)

        print(“Meaning: Used to check if two values are equal.”)

        print(‘Example: if choice == “1”:’)

        print(“ COLON (:)”)

        print(“Meaning: Indicates the beginning of a code block.”)

        print(“Example: if age >= 18:”)

    elif choice == “2”:

        print(“\n=== PYTHON BASIC SYNTAX ===“)

        print(“Meaning:”)

        print(“Python syntax refers to the rules for writing Python code correctly.”)

        print(“ PRINT()”)

        print(“Meaning: Used to display text, messages, and results on the screen.”)

        print(‘Example: print(“Hello World”)’)

        print(" CORRECT SPELLING”)

        print(“Meaning: Python commands and keywords must be spelled correctly.”)

        print(“Purpose: Prevents spelling errors in the program.”)

        print(‘Example: print(“Hello”)’)

        print(“Incorrect spelling: pritn()”)

        print(“ PROPER INDENTATION”)

        print(“Meaning: Spaces at the beginning of a line of code.”)

        print(“Purpose: Shows which statements belong inside a code block.”)

        print(“Example:”)

        print(“if age >= 18:”)

        print(‘    print(“You are an adult”)’)
    
        print(“ QUOTATION MARKS”)

        print(“Meaning: Used to enclose text or string values.”)

        print(“Purpose: Tells Python that the information is a text.”)

        print(‘Example: name = “Sandra”’)

        print(“ PARENTHESES ()”)

        print(“Meaning: Used when calling a function or passing information.”)

        print(‘Example: print(“Hello World”)’)

        print(“ COLON (:)”)

        print(“Meaning: Indicates the beginning of a code block.”)

        print(“Example: if age >= 18:”)

        print(“REMEMBER:”)

        print(“Always follow the correct Python syntax.”)

        print(“Use correct spelling, proper indentation, and quotation marks.”)
     
    elif choice == “3”:

        print(“\n=== BASIC DATA TYPES IN PYTHON ===“)

        print(“ INT (Integer)”)

        print(“Meaning: Integer is a whole number without decimal points.”)

        print(“Example: age = 18”)

        print(“It is used for counting or representing whole numbers.”)

        print(“FLOAT (Floating-Point)”)

        print(“Meaning: Float is a number that has a decimal point.”)

        print(“Example: height = 5.2”)

        print(“It is used for measurements and decimal values.”)

        print(“ STR (String)”)

        print(“Meaning: String is a group of characters or text enclosed in quotation marks.”)
         
        print(‘Example: name = “Sandra”’)

        print(“It is used for names, words, and sentences.”)

        print(“ BOOL (Boolean)”)

        print(“Meaning: Boolean represents only two values: True or False.”)

        print(“Example: student = True”)

        print(“It is used for checking conditions and making decisions.”)

        print(“=== SUMMARY ===“)

        print(“INT = Whole numbers”)

        print(“FLOAT = Decimal numbers”)

        print(“STR = Text or characters”)

        print(“BOOL = True or False”)

    elif choice == “4”:

        print(“\n=== ARITHMETIC OPERATORS ===“)

        print(“ ADDITION (+)”)

        print(“Meaning: Used to add two or more numbers.”)

        print(“Example: 10 + 5 = 15”)

        print(“ SUBTRACTION (-)”)

        print(“Meaning: Used to subtract one number from another.”)

        print(“Example: 10 - 5 = 5”)

        print(“  MULTIPLICATION (*)”)

        print(“Meaning: Used to multiply two or more numbers.”)

        print(“Example: 10 * 5 = 50”)

        print(“  DIVISION (/)”)

        print(“Meaning: Used to divide one number by another.”)

        print(“Example: 10 / 5 = 2.0”)
     
        print(“ MODULUS (%)”)

        print(“Meaning: Returns the remainder after division.”)

        print(“Example: 10 % 3 = 1”)

        print(“  EXPONENT (**)”)

        print(“Meaning: Used to raise a number to a power.”)

        print(“Example: 2 ** 3 = 8”)

        print(“  FLOOR DIVISION (//)”)

        print(“Meaning: Divides two numbers and rounds the result down to the nearest whole number.”)

        print(“Example: 10 // 3 = 3”)
  
    elif choice == “5”:

        print(“\n=== BASIC INPUT AND OUTPUT ===“)

        print(“ INPUT()”)

        print(“Meaning: Used to get information from the user.”)

        print(“Purpose: Allows users to enter their own information.”)

        print(‘Example: name = input(“Enter your name: “)’)

        print(“ PRINT()”)

        print(“Meaning: Used to display information on the screen.”)

        print(“Purpose: Shows messages, results, and output.”)

        print(‘Example: print(“Hello World”)’)

        print(“=== EXAMPLE PROGRAM ===“)

        name = input(“Enter your name: “)

        print(“Hello”, name)

        print(“=== SAMPLE OUTPUT ===“)

        print(“Enter your name: Sandra”)

        print(“Hello Sandra”)

    elif choice == “6”:

        print(“\n=== CONDITIONAL STATEMENTS ===“)

        elif choice == “6”:

        print(“\n=== CONDITIONAL STATEMENTS ===“)

        print(“\nMeaning:”)

        print(“Conditional statements are used to make decisions in a program based on certain conditions.”)

        print(“ IF STATEMENT ”)

        print(“Meaning: Checks if a condition is True.”)

        print(“Purpose: Executes code when the condition is True.”)

        print(“Example: if grade >= 90:”)

        print(“ ELIF STATEMENT ”)

        print(“Meaning: Checks another condition if the previous condition is False.”)

        print(“Purpose: Allows the program to check multiple conditions.”)

        print(“Example: elif grade >= 85:”)

        print(“ ELSE STATEMENT ”)

        print(“Meaning: Executes when all previous conditions are False.”)

        print(“Purpose: Provides an alternative action.”)

        print(‘Example: else: print(“Try again”)’)

        print(“ Example:”)

        grade = 90

        if grade >= 90:

            print(“Excellent!”)

        elif grade >= 85:

            print(“Very Good!”)

        else:

            print(“Keep Practicing!”)
    
    elif choice == “7”:

        print(“\n=== LOGICAL OPERATORS ===“)

        print(“\nLogical operators are used to combine or reverse conditions.”)

        print(“ AND OPERATOR (and)”)

        print(“Meaning: Both conditions must be True.”)

        print(“Purpose: Checks if two conditions are both satisfied.”)

        print(“Example: age >= 18 and has_id == True”)

        print(“Result: True only if both conditions are True.”)

        print(“ OR OPERATOR (or)”)

        print(“Meaning: At least one condition must be True.”)

        print(“Purpose: Allows the program to proceed if one condition is satisfied.”)

        print(“Example: age >= 18 or has_id == True”)

        print(“Result: True if at least one condition is True.”)

        print(“ NOT OPERATOR (not)”)

        print(“Meaning: Reverses the result of a condition.”)

        print(“Purpose: Changes True to False and False to True.”)

        print(“Example: not has_id”)

        print(“Result: True if has_id is False.”)
 
        print(“=== EXAMPLE ===“)

        age = 18

        has_id = True

        print(“Age =“, age)

        print(“Has ID =“, has_id)

        if age >= 18 or has_id == True:

            print(“Condition accepted”)

    elif choice == “8”:

        print(“\n=== ITERATION AND LOOPS ===“)

        print(“\nMeaning:”)

        print(“Loops are used to repeat a block of code multiple times.”)

        print(“ FOR LOOP”)

        print(“Meaning: Repeats code for each item in a sequence.”)

        print(“Purpose: Used when you know how many times to repeat.”)

        print(“Example: for number in range(1, 6):”)

        print(“ RANGE()”)

        print(“Meaning: Generates a sequence of numbers.”)

        print(“Purpose: Specifies the numbers used in a loop.”)

        print(“Example: range(1, 6) generates numbers from 1 to 5.”)

        print(“ WHILE LOOP”)

        print(“Meaning: Repeats code while a condition is True.”)

        print(“Purpose: Used when repetition depends on a condition.”)

        print(“Example: while count <= 5:”)

        print(“ COUNTING VARIABLE”)

        print(“Meaning: A variable used to track or count repetitions.”)

        print(“Purpose: Helps control how many times a loop runs.”)

        print(“Example: count = 1”)

        print(“=== FOR LOOP EXAMPLE ===“)

        for number in range(1, 6):

            print(number)

        print(“=== WHILE LOOP EXAMPLE ===“)

        count = 1

        while count <= 5:

            print(count)

            count += 1
  
    elif choice == “9”:

        print(“\n================================“)

        print(“       PYTHON QUIZ CHALLENGE”)

        print(“================================“)

        print(“Test your knowledge and earn points!”)

        score = 0

        questions = [

            (“1. What function displays text?”,

             “a. print”, “b. break”, “c. input”, “c”),
             while True:
                 ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)

            (“2. What statement checks a condition?”,

             “a. print”, “b. if”, “c. for”, “b”),
             while True:
              ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)


            (“3. What operator means at least one is true?”,

             “a. and”, “b. not”, “c. or”, “c”),
             while True:
              ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)


            (“4. What loop repeats while a condition is true?”,

             “a. while”, “b. print”, “c. input”, “a”),
             while True:
              ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)


            (“5. What statement stops a loop?”,

             “a. elif”, “b. break”, “c. else”, “b”),
             while True:
              ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)
 

            (“6. What keyword is used to create a function?”,

             “a. def”, “b. print”, “c. input”, “a”),
              while True:
              ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)


            (“7. Which data type is used for text?”,

             “a. str”, “b. int”, “c. float”, “a”)
             while True:
              ans = input(“Answer: “).upper()
                 if ans == “A” or ans == “B” or ans == “C” or ans == “D”:
                    break
                 print(“Invalid input! Please enter A, B, C, or D.”)

          
        ]

        for question, option1, option2, option3, correct in questions:

            print(“\n” + question)

            print(option1)

            print(option2)

            print(option3)

            user_answer = input(“Your answer (a/b/c): “).lower()

            if user_answer == correct:

                print(“Correct! +1 point!”)

                score += 1

            else:

                print(“Wrong! The correct answer is”, correct)

        print(“\n================================“)

        print(“          QUIZ RESULTS”)

        print(“================================“)

        print(“Your score:”, score, “/“, len(questions))

        if score == 7:

            print(“PERFECT! You are a Python Superstar!”)

        elif score >= 4:

            print(“GOOD JOB! Keep practicing!”)

        elif choice == “0”:
            print(“Thank you “)
            break
        

          else:
            
               print(“Invalid choice! Please choose 0-10.”)