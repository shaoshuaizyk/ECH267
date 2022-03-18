# ECH267
Course Project For 2022 Winter ECH 267 

To reproduce the results in the report, follow the instructions: 
1. At the beginning of the code, there is an obstacle flag called "OBSTACLE": True means the scenario with an obstacle at coordinate (1, 2), False means a pure trajectory tracking scenario; 
2. At the beginning of the code, there is a varible called "HEADING", setting the value as "NORTH", "EAST", "NORTHEAST", "WEST", "NORTHWEST" would change the initial heading as north, east, northeast, west, northwest respectively, the default value is "NORTH". Warning: starting from heading east or west could cause the failure of the solver and your computer might get stuck. 
3. Some parameters, like I mentioned in the report, the value of C, penalty of the speed error Q_e(4, 4), receding horizon M. By increasing those values, you could see the interesting result as I mentioned in the report: the robot stops in front of the obstacle. Happy playing with my messy code!
