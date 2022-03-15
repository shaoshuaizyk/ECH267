# ECH267
Course Project For 2022 Winter ECH 267 

To reproduce the results in the report, follow the instructions: 
1. Search for cost function expressions in the code. Commenting and uncommenting the corresponding lines(one is in the for loop and the other is outside the for loop) could change the scenarios. Shorter cost function is for the pure trajectory tracking while the longer one is additional with obstacle avoidance; 
2. Changing the initial conditions with heading north and heading northeast. Warning: starting from heading east could cause the failure of the solver and your computer might get stuck. 
3. Some parameters, like I mentioned in the report, the value of C, penalty of the speed error Q_e(4, 4), receding horizon M. By increasing those values, you could see the interesting result as I mentioned in the report: the robot stops in front of the obstacle. Happy playing with my messy code!
