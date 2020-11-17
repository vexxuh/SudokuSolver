# Sudoku-Solver
This is a sudoku solver using the backtracking algorithm. It includes a graphical GUI as well as a simple text based version .

# Running the Solution
Run solver-gui.py to play sudoku in the graphical version. 

# Instructions
Click a box and hit the number on your keybaord to "pencil in a number". To confirm that value press the ENTER key on that box. To delete a pencil in you can click DEL. Finally to solve the board press SPACE, sit back and watch the algorithm run. 

# Thought Process
I know that to solve these puzzles there has to be a way to go forward and backward through selections so the algorithm that works best for this situation is the backtracking algorithm. I first started with a basic text based version then added the features necessary to build a GUI for the project. The idea is very easy in concept but took a bit of time to get all of the GUI functionality to work correctly. The problem I broke down was first creating and configuring the algorithms, solver-test.py. Then I would work with the sudoku solver in a simple text file format, solver-text.py. Finally I would build those other two concept classes into the solver-gui.py which would have the full scope of my project in it. 

# Creating a new Board
If you want to make your own board for this class keep a few things in mind. In the solver-gui.py there is list that represents the board called board = [[...],[...], ...] which is 9 1 dimensional lists. In sudoku there are no "0" values since the the game uses the number 1-9 so to represent the numbers I used the 0 value as a blank space to know where the player would have to insert a number for the game. So if you wish to, in the current state of how I created the game, to make your own board or use one you found online, you have to enter all blank spaces as zeros. 

# Final Notes
One last thing that should be kept in mind. I have ran the program through several cases where there is an unsolvable board and the game should give back an "unsolvable key word" which would mean that the user entered the data incorrectly into the grid. Please note this when playing just incase your board can't be solved if you have made your own. I will be updating this project in the next few weeks with an updated way to make your sudoku games by allowing boards to be made externally without having to use the code editor to modify the game. So a board can just be loaded on the spot or you can create your own board to solve. I hope that you enjoy!
