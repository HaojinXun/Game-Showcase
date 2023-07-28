Game Title: Pizza Man

Developer: Haojin Xun

Environment: OpenGL, C++

Date: 2022 Fall

Game Idea: To create a game that stimulates a day in a pizza delivery man's life, allowing a player to interact with simple objects and accomplish small goals while exploring the environment by walking around. The game would expect a player to control the main character to deliver food to different locations by walking into the village, it also expects the environment has many different objects such as trees, houses, benches, streetlamps, and mountains.

Walkthrough:
	The POV of the game is designed to be a first-person view as it is built based on a walking similator theme. The player is expected to use a mouse to change their orientation views; they could also use the directional keys since it is slower. The directioal movement of the player requires them to take control of the ‘W’, ‘A’, ‘S’, ‘D’ keys, and press ‘spacebar’ to jump and ‘Left-Shift’ to sprint the character. It would benefit the player to sprint if the time is catching up on a pizza delivery. The jump is designed to avoid any obsticle in the way. To accept orders and finish orders; the player is required to click the left moues button to pickup an order and click the right mouse button to place the food at people’s front doors. Additionally, the player will also need to look at the terminal to get the full income information in the game because of the text render part is not finished due to the efficiency of only one of the group members was coding. In the current version of the game, the terminal will serve as a necessary tool to help the player retrieves information about their income and delivery time. First, the player will need to pick up a pizza order from the pizza store and deliver the random order to one of the houses in the small village. To find the address, they will press ‘M’ to open the map and check people’s names and press ‘C’ to close the map. As they are arrived at the front door of the receiver, they will click the right mouse button to place the food nearby the front door and finished the order; that is when the income of the player may increase. The player would consider using their “sprinting” when there is no cool down since income of the order will become half if the order is delivered late. And then the play will need to go back to the pizza store to continue other random orders. The game will finish if the player is bankrupted or successfully deliever pizzas to all houses in the village; a bankrupt could happen since cooking a pizza will require a cost of 5 dollars in the game. Once the game is over, the player could press ‘R’ to restar the game. Additionally, the player can press ‘F’ to switch the screen mode to windowed or full screen.

Content:
	1. The game has a decent size of flat surface terrain with collision detection on the bottom and the surrounding.
	2. There are at least 15 to 17 textured objects in the scene, such as:
		a. The grass
		b. The rocky road
		c. The stone wall
		d. The benches
		e. The pizza models
		f. Sky Box
		g. The gates that placed at the entries of the village
		h. A Pizza Store
		i. Three different textured models of houses
		j. Two types of trees
		k. A map object

	3. One screen-space effect was used after the “sprinting”; it is called the “dizzy” or “blurry” effects. Press ‘Left-Shift’ to trigger sprinting. We were thinking about the implement a game ending screen space effect where the screen showing red edges in a pattern, and I also had an idea of a screen space effect where you can have use it to represent the timer of the delivery, but they are not able to finish due to inefficient coding members in the team.
	4. The game implements two particle systems; a snowing effect that follows the player and a smoking effect that appear above the chimney of the normal wooden houses.
	5. The game implements one tree-like hierarchical object.
	6. Player-centric camera is fullfilled; players can use their mouse to freely change their orientation while the map and the pizza could be following the orientation of the camera as well; the camera represents the view from the player’s vision.
	7. A skybox is implemented with the cube map; the skybox was edited with blender and used unique .glsl files to make it looks seamless.
	8. The game has a full run that allows player to restart the game. It contains an opening instruction in the terminal and a scoring system and the finished stages (bankruptcy or orders completed).
	9. Randomness on the order (including the destinations).
