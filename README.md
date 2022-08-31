# Rock-paper-scissor-python
import random
options=['Rock','Paper','Scissors']
choice=random.choice(options)
user=input('Enter your choice- Rock,Paper or Scissors')
print('User chose', user)
print('Computer chose', comp)
if user.lower()=="rock":
    if comp=="Scissor":
        print('User wins- Rock smashes Scissors')
    elif comp=="Paper":
        print('Computer wins - Paper covers Rock')
    else:
        print('Tie')
elif user.lower()=="Paper":
    if comp=="Scissor":
        print('Computer wins - Scissors cut Papers')
    elif comp=="Rock":
        print('User wins-Paper covers Rock')
    else:
        print('Tie')
elif user.lower()=="Scissors":
    if comp=="Paper":
        print('User wins-Scissors cut Papers')
    elif comp=="Rock":
        print('Computer wins-Rock smashes Scissors')
    else:
        print('Tie')
else:
    print('Invalid user choice')
¬¬¬¬

