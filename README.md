# RubiksCubeSimulatior

U = top layer clockwise rotation of 90 degrees
D = bottom layer clockwise rotation of 90 degrees
F = front layer clockwise rotation of 90 degrees
B = back layer clockwise rotation of 90 degrees
R = right slice clockwise rotation of 90 degrees
L = left slice clockwise rotation of 90 degrees

x = entire cube clockwise rotation around x axis for 90 degrees
y = entire cube clockwise rotation around y axis for 90 degrees
z = entire cube clockwise rotation around z axis for 90 degrees

If LEFT SHIFT is held when pressing the above buttons, a counterclockwise rotation will be conducted



Rubik's Cube Solver
Press "S" will start the Rubik's Cube Solver
the program will automatically load in the cube in cube.txt
Keep Pressing "S", and the program will conduct the solution, until the cube is solved.
Use the mobile app and follow its instruction to take pictures of the 6 sides. It will output an Color String in the log.
Copy this color String into the cube.txt file for the solver to attempt to solve it.

User can modify the length of the solution by modifying SOLUTION_LENGTH, the shorter the solution
the longer it takes for Kociemba's Algorithm to find it (if a solution of such length exist)

User can also modify how fast the animation goes by modifying ANIMATION_SPEED.

User can ge the cube string from android app and paste it into cube.txt to let the solver solve it.

(make sure there is no extra nextline button in the cube.txt)
