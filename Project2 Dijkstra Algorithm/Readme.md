
## Library used: 
process_time for cpmputing the running time 
numpy for coverting map into matrix array
matplotlib for showing the animation 
math for representing the 8 motions

## To run:
1. Dijkstra_point.py:
Run Dijkstra_point.py. 
Enter the starting point and the goal point in the console panel. 
If either of them is inside of the obstacles or outside of the boundry(300x200), the program will return the error. 
If inputs are correct, the program will start seaching from bottom left after it finds the solution and drwa the optimal path after reaching the goal point. 
2. Dijkstra_rigid.py:
Run Dijkstra_rigid.py. 
Enter the starting point and goal pointin the console panel. Robot radius and clearence are fixed as 2 and 2. 
If they're inside of the obstacles or outside of the boundry(300x200), the program will return the error. 
If inputs are correct, the program will start seaching from bottom left after it finds the solution and drwa the optimal path after reaching the goal point. 

## The grid size parameter is to speed up the searching. If you change the grid size equal to 2, the time to completion will be 933.25s. 


