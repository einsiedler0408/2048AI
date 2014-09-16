2048AI
======
Open the 2048AI.sln with Visual Studio, it’s a web project.<br />  
Press F5 to start the program, it’s a normal 2048 game, plus 3 buttons:<br />

AutoRun to End: call the AI to play the game until there’s no move.<br />
Stop: Stop the AI auto execution.<br /> 
AutoRun One Step: call the AI to play one step.<br />

The AI can be found in api.ashx.cs:<br />
private int AINextMove(int[,] grids) 

Here the input an array which stores the game state, and the return value is the move direction. See parameter comments.
