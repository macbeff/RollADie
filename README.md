# RollADie
# The user can type "roll" in order to roll a die
x = 15
Roll="abc"
while x == 15:
    Roll=input("Type 'roll' and hit enter if you would like to roll a die or 'stop' if you would like to stop. ")
    if Roll=="roll":
        import random
        print(random.randint(1,6))
    elif Roll=="stop":
        break
    else:
        print("Better luck next time!")
            
