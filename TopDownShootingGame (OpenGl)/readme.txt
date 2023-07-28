Developer:  Haojin Xun

Environment: OpenGl, C++

Date: 2022-04-12

Game Control:

 W - Forward
 S - Backward
 A - Left
 D - Right

 J - Shoot
 K - Flamer

 R - restart

Game Requirements:
	1.Game Mechanics: the player has to pick up and clean all the green virus in order to win the game (10) before they got destroy by the enemies.

	2.Enemies: 2 types of different enemies. Enemy1 is following the player movement. Enemy2 is going horizontallu, also has the portal ability.
	
	3.Weapons: 2 types of different weapons with different damages. (Laser and Flamer)

	4.Particle systems(2): 
		the first particle system is used for the second weapon called flamer, weapon_particle_fragment_shader is the corresponding file
		the second particle system is used for the booster following the player's spaceship.

	5.Collectible items: there are 3 types of collectable (1 is for sccoring, 2 for power up items)

	6.moavement and transformations:
		all movements are handle through transforamtion.
		hierarchical transformation is pressent

	7. Collision detection:
		handle all cases sucessfully.
	
	8. Game World:
		scrolling for larger game world feeling.

	9. UI:
		Hud shows how to play the game and prompts when player fails or wins.
	
	10. Code Readability and Organization:
		All sections in the codes are well commented!

Features:
 1. "Portal effect", they are implementing in the update class of enemy and player object.cpp.
 2. "Randomize enemy number", they are implementing in the smallEnemyWave(void) scoreItemSpawn(void) and powerUpSpawn(void) functons in the game.cpp.
 3. "Health Icon", a health system through displaying the health icon objects based on player's current health. If player pick up the red virus, they will be given 1 more health.
 4. "restart" functions - press R to restart the game.
