import random
choices = ["Rock", "Paper","Scissors"]
computer = random.choice(choices)
player = False
cpu =0
user=0
while True:
player = input("Rock, Paper or  Scissors?").capitalize()
    ## Conditions of Rock,Paper and Scissors
    if player == computer:
        print("Tie!")
    elif player == "Rock":
        if computer == "Paper":
            print("You lose!", computer, "covers", player)
            cpu+=1
        else:
            print("You win!", player, "smashes", computer)
            player+=1
    elif player == "Paper":
        if computer == "Scissors":
            print("You lose!", computer, "cut", player)
            cpu+=1
        else:
            print("You win!", player, "covers", computer)
            player+=1
    elif player == "Scissors":
        if computer == "Rock":
            print("You lose...", computer, "smashes", player)
            cpu+=1
        else:
            print("You win!", player, "cut", computer)
            player+=1
    elif player=='End':
        print("Final Scores:")
        print(f"CPU:{cpu}")
        print(f"Player:{player}")
        break
