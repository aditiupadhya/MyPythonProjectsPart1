# quiz_python
quiz game using python
print("Welcome to my computer quiz")

playing = input("do you want to play?")

if playing.lower() != "yes":
    print("Aditi is GReat!  \n Bye!!")
    quit()
else:
    print("okay lets play")
    score = 0

answer1 = input("what does CPU stand for?")
if answer1.lower() == "central processing unit":
    print('correct')
    score += 1
else:
    print("incorrect")
    score += 0

answer2 = input("what does GPU stand for?")
if answer2.lower() == "graphics processing unit":
    print('correct')
    score += 1
else:
    print("incorrect")
    score += 0

answer3 = input("what does RAM stand for?")
if answer3.lower() == "random access memory":
    print('correct')
    score += 1
else:
    print("incorrect")
    score += 0

answer4 = input("what does PSU stand for?")
if answer4.lower() == "power supply unit":
    print('correct')
    score += 1
else:
    print("incorrect")
    score +=0

if score <= 3 :
    expression = "try again!! "
else:
    expression ="great"


print(str(expression) +" your score is " + str((score/4)*100) + " %")
print ("you wish to play again?")
       
#print(int(answer1))
#print(((answer1 + answer2 + answer3 + answer4) /4) * 100  )

