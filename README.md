# Game Dev Challenge 

## Objective
						
Use Unity to create a simple game to show your understanding of OOP, Unity3d, problem solving and data driven applications. The game's purpose is to build a 3D snake game! The snake grows by a length of 1 every time it eats a food on the map. 1 food spawns on the map at the start of the game and every time the snake eats the food - a new food piece gets spawned somewhere else on the map. The game is over when the snake collides with the edge of the map or itself. You and you only may complete this specification in any way or solution you please. Third party utilities are allowed (ie: XML loading library) but all code for the game should be written by you and only you.  Use the latest version of Unity available for creating the project. 


## Specifications

### Scenes 

1. Main Scene
   - Starting scene in the game 
   - "Start Game" button loads the game scene 
   - "Top Score" - shows the player's all time highest score 

2. Game Scene
   - Where the actual game is played
   - On game over - show a popup displaying the current score achieved. 
   - After hitting "Ok" on the game over popup, the player should be moved back to Main Scene
   
### Food 

A data configuration (.txt, csv, xml, .json – your choice!) will contain the parameters of the food that are spawned in the game. This game should have only two defined types of food, but implementation should be flexible for an __unlimited__ types of food pieces!

Parameters for food : __color__ and __points__ gained after eating it.

### Map
Map should be a limited, flat plane. Food should be spawned randomly on this map. Type for each food should also be chosen randomly when spawning it. (Types are defined in static data file – mentioned above).

### Scoring

Once the snake's head collides with a food, the score will increment by the defined amount in the parameters set by the data for that type of food. If you eat food of the same color as the previous one, that food’s score will be multiplied by the current streak of “colliding with the same color”. The streak should be displayed on the screen along with your score. The streak resets when you eat a food of a different color than the previous one. 

#### Example 
Lets say the design defines 2 different food types - Red (15 points) and Blue (20 points)
- Eats blue – gets 20 points
- Eats blue – gets 40 points (20 multiplied by streak = 2)			
- Eats blue – gets 60 points (20 multiplied by streak = 3)	
- Eats red – gets 15 points (Streak is reset)
- Eats red – gets 30 points (15 multiplied by streak = 2)		
- Eats blue – gets 20 points (Streak reset)

## Submission 

- Create a new github repository on your account  
- Name it __Assignment_YourName__
- Once you have finished your awesome game push your changes to github 
- Include a readme file in your repository which explains the design for your code and solution in details - name this file __Readme.md__
- If you are using some external tools/assets - highlight this in your text file and explain why you used them and what would you have done if these were not available to use
- Once complete send the link to your repository back to admissions@outscal.com along with your resume and what role you are applying for.  

## Good luck! Happy coding! 


