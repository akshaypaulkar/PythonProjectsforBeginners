print("Hi welcome to the Akshayç Comuter Quiz Game!")

Play= input("Do you want to play the game? ")
print(Play)

if Play.lower()!="yes":
    print("Okay! Lets try next time")
    quit()
else:
    print("Great! Let's Begin... :)")
    score= 0

Question= input("What is the fullform of CPU? ")
print (Question)

if Question.lower()=="central processing unit":
    print("Correct")
    score =+ 10
else:
    print("Wrong")

Question= input("What is the fullform of RAM? ")
print (Question)

if Question.lower()=="random access memory":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("What is the fullform of ROM? ")
print (Question)

if Question.lower()=="read only memory":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("What is the fullform of USB? ")
print (Question)

if Question.lower()=="universal serial bus":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("What is the fullform of OS? ")
print (Question)

if Question.lower()=="operating system":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("Which OS is developed by Microsoft? ")
print (Question)

if Question.lower()=="windows":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("What is the fullform of WWW? ")
print (Question)

if Question.lower()=="world wide web":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("What is the fullform of URL? ")
print (Question)

if Question.lower()=="uniform resource locator":
    print("Correct")
    score += 10
else:
    print("Wrong")

Question= input("What is the fullform of HTML? ")
print (Question)

if Question.lower()=="hypertext markup language":
    print("Correct")
    score += 10
else:
    print("Wrong")


print ("Hey you have score "+str(score)+" marks")
print("Hey you have score " + str((score/100)*100) + " %.")


