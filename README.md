# Crafting-a-health-potion
import random #importing Random Module
health=50 #Assigning initial health value for the player
difficulty=1 #Setting the difficulty level of the game.Here 1 is easy, 2 is medium, 3 is difficult.
potion_health=int(random.randint(25,50)/difficulty) #Assigning random value for the health potion by calling the randint funtion from the random module. 
health=health+potion_health #updating the players health based on potion health value
print(health) #printing the output
