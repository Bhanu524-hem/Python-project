# Python-project
import random
rock='🪨'
paper='📄'
scissor='✂️'
game_choice=[rock,paper,scissor]
u=int(input("enter the user input: "))
print(game_choice[u])
if u>=3 or u<0:
    print("invalid input,you lost")
else:
    print("computer input:")
    c=random.randint(0,2)
    print(game_choice[c])
    print(c)
    if u==c:
      print("it is draw")
    elif c>u:
      print(" you lost")
    elif u>c:
      print("yow win")
    elif u==0 & c==2:
      print("you win")
    else:
      print(" you lost")
