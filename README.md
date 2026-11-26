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
    
    print(“[9] = FUNCTIONS IN PYTHON”)

    print(“----------------------------------------“)

choice = input(“Choose a lesson or activity (1-11): “)


    if choice == “1”:

        print(“\n=== INTRODUCTION TO PROGRAMMING ===“)

        print(“Programming is giving instructions to a computer.”)

        print(“Python is a programming language.”)

        print(“It is used to create programs and applications.”)

    elif choice == “2”:

        print(“\n=== PYTHON BASIC SYNTAX ===“)

        print(“Syntax refers to the rules of Python.”)

        print(“Example:”)

        print(‘print(“Hello World”)’)

        print(“Remember:”)

        print(“1. Use correct spelling.”)

        print(“2. Use proper indentation.”)

        print(“3. Use quotation marks for text.”)

   elif choice == “3”:

        print(“\n=== BASIC DATA TYPES IN PYTHON ===“)

        print(“int = Integer (whole number)”)

        print(“float = Decimal number”)

        print(“str = String (text)”)

        print(“bool = Boolean (True or False)”)

        print(“Example:”)

        print(‘age = 18’)

        print(‘name = “Sandra”’)

        print(‘height = 5.2’)

        print(‘student = True’)

    elif choice == “4”:

        print(“\n=== ARITHMETIC OPERATORS ===“)

        print(“Addition (+) = 10 + 5”)

        print(“Subtraction (-) = 10 - 5”)

        print(“Multiplication (*) = 10 * 5”)

        print(“Division (/) = 10 / 5”)

        print(“Modulus (%) = 10 % 3”)

        print(“Exponent (**) = 2 ** 3”)

        print(“Floor Division (//) = 10 // 3”)
  
    elif choice == “5”:

        print(“\n=== BASIC INPUT AND OUTPUT ===“)

        print(“input() is used to get information from the user.”)

        print(“print() is used to display information.”)

        print(“Example:”)

        print(‘name = input(“Enter your name: “)’)

        print(‘print(“Hello”, name)’)

    elif choice == “6”:

        print(“\n=== CONDITIONAL STATEMENTS ===“)

        print(“Conditional statements make decisions.”)

        print(“IF = Checks a condition.”)

        print(“ELIF = Checks another condition.”)

        print(“ELSE = Executes when conditions are false.”)

        print(“\nExample:”)

        print(“grade = 90”)

        print(“if grade >= 90:”)

        print(‘    print(“Excellent”)’)

        print(‘elif grade >= 75:’)

        print(‘  print(“Passed”)’)

        print(‘else:’)

        print(‘   print(“Failed”)')
    
    elif choice == “7”:

        print(“\n=== LOGICAL OPERATORS ===“)

        print(“AND = Both conditions must be True.”)

        print(“OR = At least one condition must be True.”)

        print(“NOT = Reverses the result.”)

        print(“\nExample:”)

        print(“age = 18”)

        print(“has_id = True”)

        print(“if age >= 18 or has_id == True:”)

        print(‘   print(“Condition accepted”)’)

        print(“else:”)

        print(‘   print(“Condition not accepted”)’)

    elif choice == “8”:

        print(“\n=== ITERATION AND LOOPS ===“)

        print(“Loops repeat a block of code.”)

        print(“\nFOR LOOP Example:”)

        print(‘for number in range(1, 6):’)

        print(‘    print(number)’)

        print(“\nWHILE LOOP Example:”)

        print(‘count = 1’)

        print(‘while count <= 5:’)

        print(‘    print(count)’)

        print(‘    count += 1’)

  elif choice == “9”:

        print(“\n================================“)

        print(“       FUNCTIONS IN PYTHON”)

        print(“================================“)

        print(“A function is a reusable block of code.”)

        print(“It helps organize a program and avoid repeating code.”)

        print(“Functions are created using the def keyword.”)

        print(“A function can receive information and return a result.”)

        print(“\nExample:”)

        print(“def greet(name):”)

        print(‘    print(“Hello”, name)’)

        print(‘greet(“Sandra”)’)

        print(“\nOutput:”)

        print(“Hello Sandra”)

    elif choice == “10”:

        print(“\n================================“)

        print(“       PYTHON QUIZ CHALLENGE”)

        print(“================================“)

        print(“Test your knowledge and earn points!”)

        score = 0

        questions = [

            (“1. What function displays text?”,

             “a. print”, “b. break”, “c. input”, “c”),

            (“2. What statement checks a condition?”,

             “a. print”, “b. if”, “c. for”, “b”),

            (“3. What operator means at least one is true?”,

             “a. and”, “b. not”, “c. or”, “c”),

            (“4. What loop repeats while a condition is true?”,

             “a. while”, “b. print”, “c. input”, “a”),

            (“5. What statement stops a loop?”,

             “a. elif”, “b. break”, “c. else”, “b”),

            (“6. What keyword is used to create a function?”,

             “a. def”, “b. print”, “c. input”, “a”),

            (“7. Which data type is used for text?”,

             “a. str”, “b. int”, “c. float”, “a”)
          
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

        else:

            print(“Don’t give up! Review your lesson!”)