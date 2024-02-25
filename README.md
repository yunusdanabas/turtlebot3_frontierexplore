# turtlebot3_frontierexplore
Using explore_lite package for multi TurtleBot3

When I first started learning ROS, I implemented a simple project for practical purposes. 
It involves using a single or multiple TurtleBot3 robots with the explore_lite package to perform frontier-based exploration. 
When the node is running, the robot will greedily explore its environment until no frontiers can be found. 
In the case of multiple robots, the maps generated by each robot are merged into a single map, and all exploration operations are performed based on this shared map.




