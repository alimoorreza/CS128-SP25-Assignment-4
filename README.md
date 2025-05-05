# CS128-SP25-Assignment-4:
## Executing Your Robot Motion Plan on Thymio Robot

For this assignment, you are going to navigate your Thymio robot using the robot motion plan you have found from your last assignment (A#3: graph search algorithms to perform robot motion planning).
## The Data :bar_chart: 
You will use given files:
* _map of the robot world_ (attached in this repository under the 'map/' directory)
 * _map_block1_block11.pdf.pdf_
 * _map_block12_block22.pdf.pdf_
 * _map_block23_block33.pdf.pdf_ 
* _a4_starter.aesl_ (ASEBA file for Thymio attached in this repository)

The objective of this assignment is to develop navigation code—either using Block-based programming or ASEBA—that enables the robot to follow the optimal path from its __initial state__ to the __goal state__. This optimal path should correspond to the one previously computed on the map using __Best-First Search__ and __A* search__ algorithms.
![Robot world map](https://github.com/alimoorreza/CS128-SP25-Assignment-4/blob/main/map/robot_world_map.png)

## The Exercises:

**Part 1 (Finish The Robot World Map): [2 points]** Please print the map of the robot world. You may print the individual sections separately and assemble them to complete the full map. Printed copies of these map sections will be provided by the instructor. It is **mandatory to complete** the stitching of the map using duct tape before beginning the implementation of your navigation algorithm for Thymio.
 * _map_block1_block11.pdf.pdf_
 * _map_block12_block22.pdf.pdf_
 * _map_block23_block33.pdf.pdf_ 
 
**Part 2 (Finish the Thymio Coding in the Robot World Map): [4 points]** You must finish  implementations of Thymio robot navigation are provided. I will be looking for the following to be included in your submission:
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
