# CS128-SP25-Assignment-4:
## Executing Your Robot Motion Plan on Thymio Robot

For this assignment, you are going to navigate your Thymio robot using the robot motion plan you have found from your last assignment (A#3: graph search algorithms to perform robot motion planning).
## The Data :bar_chart: 
You will use two given text files as inputs:
* _robot_motion_planning_map.pdf_ (attached in this repository)
* _a4_starter.aesl_ (ASEBA file for Thymio attached in this repository)

The goal of this assignment is to write the navigation code (using Block coding or ASEBA coding) to make the robot follow the optimal path your received from the robot's _initial state_ to the _goal state_. Recall that you have computed the optimal path in the map using of __Best First Search__ and __A* Search__.

## The Exercises:

**Part 1 (Finish The Robot World Map): [2 points]** You must finish class __PriorityQueueRobotNav__.  Implementations for most of the methods are provided. I will be looking for the following to be included in your submission:
* _remove()_ method: This should remove a node from the __FRINGE__ based on priority. The *Node object* with the minimum *f_value* should be returned when this method is invoked. Node class is given with full implementation and you don't need to change anything. You should do the following to finish _remove()_ method:
  * Find the index of *Node object* with the minimum *f_value*
  * Eliminate that *Node object* from *self.priority_queue*
  * Finally, return that *Node object*
 
**Part 2 (Finish the Thymio Coding in the Robot World Map): [4 points]** You must finish <span style="color:blue">class __RobotWorld__ </span>. Implementations for many of the methods are provided. I will be looking for the following to be included in your submission:
* _plan_robot_motion()_ method: This method should do the following:
  * Get the h_value for _init_node_ from the 'robot_2d_h'. You can use 2D indexing of the form: 'robot_2d_h[init_node.y][init_node.x]'
  * Set the h_value, g_value, and f_value of 'init_node' by calling the appropriate methods
  * Mark 'robot_2d_visited[...][...]' as a visited location. For example, you can use a value of 1 to mark as visited. All 2D locations are marked as unvisited with a value of 0 by default
  * Set parent of *init_node* to None
**Part 3 (Record a video demonstration of your Thymio Navigating in the Robot World Map): [2 points]** You must finish
 


Lastly, as always, use a Markup cell to put your name at the top of the file.

## Rubric :ballot_box_with_check:

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded  | Notes |
| --------- | ------------------- | --------- |
| 1: Part1::_remove()_                  |      /2  |    | 
| 2: Part2::_remove()_                                           |      /4  |    |
| 3: Part3::_remove()_        |      /2  |    |  
| <b>Total                                       |     /8 | </b>   |
