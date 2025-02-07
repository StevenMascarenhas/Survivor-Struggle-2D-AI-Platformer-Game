# Survivor-Struggle-2D-AI-Platformer-Game
Survivor’s Struggle is a 2D platformer game where players navigate through the map with intelligent enemy AI, including spiders, archers, creepers, and a powerful boss with unique abilities. The player must strategically use health power-ups, melee attacks, and shoot bullets to survive and overcome challenges.

The player has basic movements like idle, running, attacking by shooting bullets, and using a sword to hit enemies. The player can also get hurt from attacks and dies when their health runs out. In Survivor Struggle, the main goal is to make the enemy AI more intelligent, ensuring the game is engaging and challenging for the player while remaining fair. Based on the player’s behavior, enemies like the spider, archer, and creeper adapt to the environment and react to the player’s presence in different ways.

To showcase complex enemy behavior, I worked with finite state machines [FSM’s] for the Creeper and Boss AI and the A* pathfinding AI technique for the Bird AI. The key states that made the enemies feel complete included idle, patrol, look for player, player detected, charge, explode, and dead states for the Creeper, and run, attack, enrage, enrage run, and enrage attack states for the Boss AI. Using A* pathfinding, the Bird AI follows a predetermined path.


![image](https://github.com/user-attachments/assets/3a82acad-10c6-497b-857a-1bd9e502c461)

![image](https://github.com/user-attachments/assets/bd046190-0a68-4b8b-8697-4582544a1a70)




[Survivor_Struggle_Report.pdf](https://github.com/user-attachments/files/18712112/Survivor_Struggle_Report.pdf)

