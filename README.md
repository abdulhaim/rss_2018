# Robotics, Science & Systems -- Team 3 -- Spring 2018
Programmed small scale yet complex robot on the Robot Operating System (ROS) on RACECAR platform (with Velodyne LiDAR)

![Racecar](rss_2018/assets/images/about/team_photo.jpg)

## Topics 

``Wall Following:`` Drove autonomously 0.5 meters away from a given wall with safety controller

``Visual Servoing``: Implemented a PD control algorithm to park the race car in front of the cone; 
  implemented similar control algorithm to make racecar follow a bright orange line on the ground.

``Localization and Mapping:`` Implemented Monte Carlo Localization algorithm. Evaluated performance in the RACECAR simulation, RViz and the real car platform in MIT’s basement.

``Motion Planning and Control``: Implemented system that rapidly exploring random trees
  (modified as RRT*) for path planning and pure pursuit for simultaneous tracking.

``The Labyrinth``: Navigated a maze of randomly placed obstacles, with no prior knowledge of the environment, and without collisions by generating & updating a map of environment using SLAM, developing a path planning algorithm, and designing a trajectory controller for car to follow a path closely
