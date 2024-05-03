# Magical Arena 

# Description
This project simulates a simple magical combat arena where two players engage in turn based fight until one player's health reach zero.

# Running the code
1. Prerequisites:
   Java Development kit(JDK)
   A text editor or IDE (Eclipse)
   
2. Clone or Download the Repository:
   Use git to clone the repository locally or download the ZIP archive.

3. Compile and Run:
   if using command line:
   Bash
   cd MagicalArena
   javac MagicalArena.java Player.java     # Compile the java files
   java MagicalArena                       # Run the program

if using an IDE: Follow your IDE's specific instruction for compiling and running java code.


# Gameplay
The program begins by creating two players with predefined health, strength, and attack values. The players fight in turns, rolling a die to determine attack and defense rolls. The attacker's damage is calculated as attack * attackRoll, while the defender's strength reduces the damage by defenseStrength = strength * defenseRoll. Only positive damage is dealt.

The fight continues until one player's health depletes to zero. The winner is declared based on who has remaining health.

# Unite Test
Unit tests are included in the tests directory. These tests verify the functionality of individual components, such as the rollDie method, damage calculation in fight, and player health management.

# License
This code is distributed under the Eclipse Public License 2.0

   
   

