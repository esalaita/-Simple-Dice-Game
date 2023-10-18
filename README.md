# Simple-Dice-Game

Used the random library,  generating random dice values
Used the time library, introducing a delay for a more realistic dice roll effect
Implemented an if loop that continuously runs the game if the user wants to play
Prompted the user to decide whether to roll again (yes or Y) or end the game (no)
Handled different input cases for "yes" and "no" using conditionals


import random


x = "y"

while x == "y":
	
	# Generates a random number
	# between 1 and 6 (including
	# both 1 and 6)
	no = random.randint(1,6)
	
	if no == 1:
		print("[-----]")
		print("[	 ]")
		print("[ 0 ]")
		print("[	 ]")
		print("[-----]")
	if no == 2:
		print("[-----]")
		print("[ 0 ]")
		print("[	 ]")
		print("[ 0 ]")
		print("[-----]")
	if no == 3:
		print("[-----]")
		print("[	 ]")
		print("[0 0 0]")
		print("[	 ]")
		print("[-----]")
	if no == 4:
		print("[-----]")
		print("[0 0]")
		print("[	 ]")
		print("[0 0]")
		print("[-----]")
	if no == 5:
		print("[-----]")
		print("[0 0]")
		print("[ 0 ]")
		print("[0 0]")
		print("[-----]")
	if no == 6:
		print("[-----]")
		print("[0 0 0]")
		print("[	 ]")
		print("[0 0 0]")
		print("[-----]")
		
	x=input("press y to roll again and n to exit:")
	print("\n")
