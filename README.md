# curly-octo-waffle
print("Welcome to my Python Quiz" )
answer = input("Are you ready for a tiny adventure? (yes/no) :")
score = 0
total_questions = 3

if answer.lower()=="yes":
    answer = input("Question 1: What is your favorite season? :" )
    if answer.lower()=="fall":
        score += 1
        print("Correct" )

    else:
        print("Wrong Answer" )

    answer=input("Question 2: Did you go to coding bootcamp? :" )
    if answer.lower()=="yes":
        score += 1
        print("Correct" )

    else:
        print("Wrong Answer" )

    answer=input("Question 3: What is the name of the coding application I am currently using? :" )
    if answer.lower()=="pycharm":
            score += 1
            print("Correct" )

    else:
        print("Wrong Answer" )

print("Thank you for allowing my tiny quiz to entertain you for a minute. You got",score, "questions right." )
mark=(score/total_questions)*100
print("Marks obtained: ", mark )
print("Goodbye! Till next time" )
