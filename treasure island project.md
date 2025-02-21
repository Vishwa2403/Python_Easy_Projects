from token import LEFTSHIFT

print(r'''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
choice1 = input("You're at a cross road. Where do you want to go? Type Left or Right")
if choice1 == "Left":
    choice2 = input("You're at a River. Where do you want to go? Type Swim or Wait")
    if choice2 == "Swim":
        choice3 = input("You arrive at the island unharmed. "
                "There is house with 3 doors. One red, "
                "one yellow and one blue. "
                "Which colour do you choose?")
        if choice3 == "Yellow":
                print("Congratulations! You've Won!")
        elif choice3 == "Red":
                print("Burned by fire. Game Over.")
        elif choice3 == "Blue":
                print("Eaten by beasts. Game Over.")
        else:
                print("Game Over")
    elif choice2 == "Wait":
        print("Attacked by trout. Game Over.")
    else:
        print("Attacked by trout. Game Over.")
elif choice1 == "Right":
        print("Fall into a hole. Game Over.")
else:
        print("Fall into a hole. Game Over.")
