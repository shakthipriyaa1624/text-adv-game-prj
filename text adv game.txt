answer=input("Do you want to play this game?[yes/no]")
if answer == "yes":
    print("That's great!")
    print()
    answer=input("Do you want to explore a cave or jungle?[cave/jungle]")
    
    if answer=="cave":
        print("you go into the cave and see a sleeping bear")
        print()
        answer=input("Do you want to fight or run?[fight/run]")

        if answer == "fight":
            print("Bears are really strong! you loose")
        elif answer == "run":
            print("you ran away you win!")
        else:
            print("invalid option,you lose!")
            
    elif answer=="jungle":
        print("you meet a tiger and you get eaten! you loose")
        
    else:
        print("invalid option,you lose!")
else:
    print("But this is really awesome game!")
    
    
             
