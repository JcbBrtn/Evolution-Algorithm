# Evolution
This is a battle arena for fighters with different attributes such as, attack, damage, defense, health, and initative.
The actions for each fighter's turn is determined by a self made Neural Network. (NeuralNetwork.py)
For each round, the ones who live move on to reproduce and repopulate the population.
Each child is mutated slightly to attempt to optimize the Neural network to create the ultimate fighter.

The mutation of children mutates the stats and the neural network.
When fighting, each action has a penalty marked against it when used. Decreasing the value of the weight of the output. This means that fighters should not get stuck in a pattern of repeating action. Instead they will exprole new options until they feel that they can return to their desired action.

The UI is mainly test based. Use 'help' to get a list of all commands that can be done. The commands are:

  'help' get a list of accepted commands.
  
  'list' list all fighters, from here enter first names or last names for more details, or enter 'back' to return to main function routine.
  
  'new #' creates a number of new fighters equal to the number inputed. make sure it's even to allow algoritm to work correctly.

  'step # bool' steps through the evolution process the number of times entered. the boolean entered dictates whether the fights are commented or not.
    WARNING: commenting the fights slows down the program extremely.
  
  'stats' shows all stats of current fighters in the arena (i.e. min, max, average)
  
  'tournament' Enters all fighters currently in the array into a tournament to decide which fighter is the strongest. You are unable to step after a tournament is ran until new fighters enter the arena.
  
  'sample' gives a random sample fighter from the group of currently avaiable fighters.
  
  
Happy Evolution!
  -Jacob Barton
