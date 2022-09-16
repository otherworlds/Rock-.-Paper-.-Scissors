import numbers
import random

print("rock...paper...scissor")

user = input("please return your choise?")

number = random.randint(1,3)

player = ""

if number == 1 :
    player = "rock"
    print("player choise rock")

elif number == 2 :
    player = "paper"
    print("player choise paper")

elif number == 3 :
    player = "scissor"
    print("player choise scissor")

if player == "rock"  and user == "paper":
    print("user win")

elif player == "rock" and user == "scissor":
    print("player win")

elif player == "pepar" and user == "rock":
    print("player win")

elif player == "pepar" and user == "scissor":
     print("user win") 

elif player == "scissor" and user =="rock":
     print("user win")

elif player == "scissor" and user =="pepar":
    print("player win")  
