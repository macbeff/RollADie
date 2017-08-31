SBU = 15
while SBU == 15:
    Roll=input("Type 'roll' and hit enter if you would like to roll dice or 'stop' if you would like to stop. ")
    if Roll=="roll":
        import random
        x=random.randint(1,6)
        y=random.randint(1,6)
        z=x+y
        print("You rolled a", x, "and a", y, "for a total of", z)
    elif Roll=="stop":
        break
    else:
        print("Better luck next time!")
            
