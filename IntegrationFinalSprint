# Chelsea Bielby
# Welcome to my integration project! Here, I will showcase what I
# have learned in COP1500 thus far. :)
greeting = "Hi!" * 10
print(greeting)
print("Sorry, I get a little excited sometimes.")
print("Anyway, ", end="")
print("Welcome to my integration project!")
print("What is your name?")
name = input()
str1 = "Hi, "
str2 = "!! I am so glad to have you here!"
print(str1 + name + str2)
print("Enter the value of what interests you today.")
print("1. Math Magic")
print("2. A joke")
print("3. Random password generator")
print("4. Guess a number")
print("5. Guestbook")
print("6. Quit")
keepPlaying = True
while keepPlaying:
    pick = int(input())
    if pick == 1:
        print("Choose your favorite whole number and I'll tell you mine!")
        # The answer will always be 27 (a math "magic trick").
        #My favorite number.
        while True:
            try:
                num1 = int(input())
                num2 = num1 * 2
                # multiplies number chosen by 2
                num3 = num2 + 9
                # adds nine to result
                num4 = num3 - 3
                # subtracts 3 from result
                num5 = num4 / 2
                # divides result by 2
                num6 = num5 - num1
                # subtracts original number from result
                num7 = num6 ** 3
                # raises num7 to the third power
                num8 = num7 % 6
                # divided num8 by 6 and gives the remainder
                num9 = num8 ** 3
                # raises num8 to the third power
                num10 = num9 // 1
                # divides num 7 by 1 and gives the integer result
                print(num1, ": Great number!")
                print("Mine is ", format(num9, '2.0f'), "!", sep="")
                break
            except ValueError:
                print("Not a whole number. Try again: ")
        print("\nChoose another value from the main menu.")
        print("1. Math Magic")
        print("2. A joke")
        print("3. Random password generator")
        print("4. Guess a number")
        print("5. Guestbook")
        print("6. Quit")
    elif pick == 2:
        print("Why was 6 scared of 7?")
        ans = input()
        if ans == "because 7 8 9":
            print("Yes! Haha!")
            print("\nChoose another value from the main menu.")
        else:
            num = 7
            print("\nBecause", num, " ", end="")
            num += 1
            # += adds 1 to my assigned number of 7 and update the assignment
            # end = "" will assure that the answer prints on one line
            print(num, " ", end="")
            num += 1
            # Here, += will add 1 to 8 because of the previous update
            print(num, "Hehe!")
            print("\nChoose another value from the main menu.")
            print("1. Math Magic")
            print("2. A joke")
            print("3. Random password generator")
            print("4. Guess a number")
            print("5. Guestbook")
            print("6. Quit")
    elif pick == 3:
        import random
        # This password will contain 10 random characters. 3 uppercase letters,
        # 2 lowercase letters, 3 numbers & 2 punctuation signs.
        up1 = chr(random.randint(65, 90))
        up2 = chr(random.randint(65, 90))
        up3 = chr(random.randint(65, 90))
        low4 = chr(random.randint(97, 122))
        low5 = chr(random.randint(97, 122))
        num6 = chr(random.randint(48, 57))
        num7 = chr(random.randint(48, 57))
        num8 = chr(random.randint(48, 57))
        punc9 = chr(random.randint(33, 47))
        punc10 = chr(random.randint(33, 47))
        # While researching about what the random module is capable of, I came
        # across a simplified list of characters from ASC11

        def main():
            """Main assembles a password made up of lower and uppercase letters,
            numbers and various punctuation."""
            up = up1 + up2 + up3
            low = low4 + low5
            num = num6 + num7 + num8
            punc = punc9 + punc10
            password = up + low + num + punc
            password = shuffle(password)
            print("Your password is, ", password, end='')

        def shuffle(characters):
            """Shuffle takes an assembled password made up of lower and 
            uppercase letters, numbers and punctuation and shuffles it
            randomly."""
            firstpass = list(characters)
            random.shuffle(firstpass)
            # I also learned how to shuffle from researching what the random
            #module is capable of
            return "".join(firstpass)
            # I learned "join" from practicing on w3schools
        main()
        print("\n\nChoose another value from the main menu.")
        print("1. Math Magic")
        print("2. A joke")
        print("3. Random password generator")
        print("4. Guess a number")
        print("5. Guestbook")
        print("6. Quit")
    elif pick == 4:
        import random

        computer_number = random.randint(1, 11)
        # Computer chooses a random number and compares it to user input
        user_number = int(input("Guess a number between 1 and 10: "))
        guessingGame = True
        while guessingGame == True:
            if user_number < 1 or user_number > 10:
                print("Invalid Entry.")
                user_number = int(input("Enter a number between 1 and 10: "))
            elif user_number == computer_number:
                for x in range(3):
                    print("W")
                    print("Wo")
                    print("Woo")
                    print("Woo-")
                    print("Woo-H")
                    print("Woo-Ho")
                    print("Woo-Hoo")
                    print("Woo-Hoo!")
                    print("Woo-Hoo")
                    print("Woo-Ho")
                    print("Woo-H")
                    print("Woo-")
                    print("Woo")
                    print("Wo")
                    print("W")
                guessingGame = False
                print("You guessed the correct number!")
            elif user_number != computer_number:
                user_number = int(input("That's not it. Guess again: "))
            else:
                print("Invalid Entry.")
                user_number = int(input("Enter a number between 1 and 10: "))
        print("\nChoose another value from the main menu.")
        print("1. Math Magic")
        print("2. A joke")
        print("3. Random password generator")
        print("4. Guess a number")
        print("5. Guestbook")
        print("6. Quit")
    elif pick == 5:
        # This program will start fresh on each computer it is ran on.
        # Once it has been ran on a computer, it will continue to add
        #to the file.
        print("Sign the guestbook!")

        def guest_Book():
            """guest_Book takes user input, opens a file called guestbook,
            writes it into that file,closes it and then prints the entire
            file with the added name."""
            sign = input("Enter the name to be entered into the guestbook: ")
            file = open("guestbook.txt", 'a')
            # This line of code opens a new file called guestbook
            file.write(sign)
            # This line allows the input to be added to the file
            file.write("\n")
            file.close()
            # This line closes the file
            guestbook = open('guestbook.txt')
            gb = guestbook.read()
            # These two lines open and read the file
            n = len(open("guestbook.txt").readlines())
            # This line determines how many lines are in the file for a
            #future print statement
            if n == 1:
                print(gb + "has been here!")
            # This if/else statement prints "has" if there is only
            #one line in the file
            else:
                print(gb + "have been here!")
            # This if/else statement prints "have" if there is more than
            #one line in the file
        guest_Book()
        print("\nChoose another value from the main menu.")
        print("1. Math Magic")
        print("2. A joke")
        print("3. Random password generator")
        print("4. Guess a number")
        print("5. Guestbook")
        print("6. Quit")
    elif pick == 6:
        keepPlaying = False
        # I included the kill feature that I learned from Prof.
        #Vanselow's examples.
    else:
        print("That's not a valid entry. Try again.")
print("Thanks for stopping by! See you next time!")

