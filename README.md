# Walking-Dead
Survive the zombie apocalypse, battling undead threats.

/*************************** THE WALKING DEAD: SURVIVAL GAME ***************************/

Welcome to "The Walking Dead: Survival Game" - a text-based zombie survival game in C.

Instructions:

1. 'O' represents you - the last human alive on this planet, and 'X' represents zombies longing to kill the human.

2. Your task is to keep yourself alive as long as you can.

3. Zombies will keep following you, moving one step at a time.

Rules:

1. You will gain 2 energy per move. Note: You can have a maximum of 8 energy at a time.

2. You can use 1 energy to move to an adjacent block or use all your energy to unleash an attack that kills zombies in a 5*5 square with you as the center.

3. You need at least 6 energy to unleash your attack.

4. You can also stay in the same place and save energy.

5. Once a zombie comes in contact with you (i.e., a zombie is present in an adjacent block to you), YOU DIE!!!!

SURVIVE AS LONG AS YOU CAN!!!!!!!

/*********************************** GAMEPLAY **************************************/

The game consists of a grid where 'O' represents your position, and 'X' represents the zombies. Zombies move one step at a time.

Commands:
- 'W' - Move up
- 'A' - Move left
- 'S' - Move down
- 'D' - Move right
- 'P' - Stay in the same place and save energy
- 'K' - Unleash an attack, if you have at least 6 energy

/*********************************** SCORING **************************************/

Your score is determined by the number of moves you survive. Try to achieve the highest score!

/*********************************** HOW TO COMPILE **************************************/

Compile the game using a C compiler. For example:
gcc walking_dead.c -o walking_dead
Run the compiled executable to start playing:
./walking_dead

/*********************************** GAME OVER **************************************/

The game ends when a zombie comes in contact with you. Your final score will be displayed.

/*********************************** ENJOY THE GAME ***********************************/

