# Cubescape
A Simple 3D Procedurally Generated Maze Map Game that was made as my final thesis project for my Game Development major when I was in University

Game is located inside the folder, click on the Unreal Engine application icon name "Cubescape" and it'll launch soon after. There are character sprite animation rotations that havent been fixed and some objects sometimes get stuck between other objects. The focus of this project was the procedurally generated map in a 2D space with the structure of a "dice" where each side of the "dice" map are connected to each other.

As the player our objective is to reach the goal by navigating through the map and moving from one side to another if necessary. The "dice" map will rotate accordingly depending on which side of the "dice" map we came from, most of the maps that are generated have been made to be solvable by making use of a combination of Genetic Algorithm and a modified A* Algorithm that also simulates gravity to help with ensuring each map generated is solvable and is unique and never the same structure. 

Several things to note since there are no explanations in the game:
1. there are switches that are linked to doors with the same number and that is what the interact button "E" is used for. A switch looks like a transparent tile with a number on it, and a door is a brown tile with a numebr on it as well. As long as both switches and door have the exact same number it means they are linked.
2. There are "crates" that will fall according to gravity and can move/transition from one side to another
3. There are "crumbling" tiles that will dissapear after standing on them for a few seconds do be careful sometimes it may end up making you stuck and unable to proceed with the level

Note: If you do get stuck or a bug occurs or if you end up falling in a deep hole for standing too long on a "crumbling" tile and get stuck, just press B and start a new level. The algorithm might not take into account every single variable that can happen so there might be cases where the player is unable to proceed.
