This is a simulation of a game of combat between two characters. The outcome of the game is the death / survival of one character. Each character had numerical parameters such as 
attack power and health. Dice throws add randomness. A turn is a called battle.

The program records the battles, and number of deaths. These are normalized to create probabilities. 

The characters approach one another, amd the parameters change based on the distance between them - ranged attacks (gun, arrow) versus melee attacks (sword, mace). 

Three seperate distances are used. The program outputs figures from matplotlib (line graphs)

**Sample Output:**

Binomial simulation of deaths between a Space Soldier (Machine Pistol plus Knifesword) and a Souless Robot (Guass Rifle)
Battle Simulations: 10000000

Ranged Far (14 - 8 inches)
Robot Deaths:   66.9% Battles Mean: 3.62 var: 15.83
Soldier Deaths: 33.1% Battles Mean: 2.72 var: 18.52

Range Near (7 - 2 inches)
Robot Deaths:   45.0% Battles Mean: 1.67 var: 5.70
Soldier Deaths: 55.0% Battles Mean: 2.92 var: 4.10

Melee (within 1 inch)
Robot Deaths:   73.8% Battles Mean: 2.42 var: 5.36
Soldier Deaths: 26.2% Battles Mean: 1.36 var: 7.51
 
