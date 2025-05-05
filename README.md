# CS128-SP25-Assignment-4:
## Executing Your Robot Motion Plan on Thymio Robot

For this assignment, you are going to navigate your Thymio robot using the robot motion plan you have found from your last assignment (A#3: graph search algorithms to perform robot motion planning).
## The Data :bar_chart: 
You will use given files:
* _map of the robot world_ (attached in this repository under the 'map/' directory): The map consists of multiple blocks, each dimensioned to provide adequate space for positioning the Thymio robot within its boundaries.
  * _map_block1_block11.pdf.pdf_
  * _map_block12_block22.pdf.pdf_
  * _map_block23_block33.pdf.pdf_ 

* _a4_starter.aesl_ (ASEBA file for Thymio attached in this repository)

The objective of this assignment is to develop navigation code—either using Block-based programming or ASEBA—that enables the robot to follow the optimal path from its __initial state__ to the __goal state__. This optimal path should correspond to the one previously computed on the map using __A* search__ algorithm. Additionally, you could navigate along the path found from your __Best-First Search__.
![Robot world map](https://github.com/alimoorreza/CS128-SP25-Assignment-4/blob/main/map/robot_world_map.png)

## The Exercises:

**Part 1 (Finish The Robot World Map): [2 points]** Please print the map of the robot world. You may print the individual sections separately and assemble them to complete the full map. Printed copies of these map sections will be provided by the instructor. It is **mandatory to complete** the stitching of the map using duct tape before beginning the implementation of your navigation algorithm for Thymio.
 * _map_block1_block11.pdf.pdf_
 * _map_block12_block22.pdf.pdf_
 * _map_block23_block33.pdf.pdf_ 
 
**Part 2 (Finish the Thymio Coding in the Robot World Map): [4 points]** Implementations for navigating the Thymio robot must be completed. You may use either the Thymio’s onboard buttons or hand gestures to control its movement from the initial state to the goal state. The navigation path followed by the robot should align with the optimal path previously determined using the __A* search__ algorithm. There are no constraints on how the navigation is executed, provided that the robot successfully reaches the __goal state__ by following the optimal route identified by the __A* algorithm__. For instance, if you choose to program button-based controls, your ASEBA or block-based code may include separate segments to handle the following motion commands:
 * _button.right_: start rotating clockwise the Thymio and stop when the button.center is pressed
 * _button.left_: start rotating counter-clockwise the Thymio and stop when the button.center is pressed
 * _button.forward_: start moving forward the Thymio and stop when the button.center is pressed
 
**Part 3 (Record a video demonstration of your Thymio Navigating in the Robot World Map): [2 points]** Once you've completed Parts 1 and 2, please record a video demonstration of your work and upload it along with your solution code. Since this is a group assignment, only one video per group is needed.
 

Lastly, as always, use a Markup cell to put your name at the top of the file.

## Rubric :ballot_box_with_check:

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded  | Notes |
| --------- | ------------------- | --------- |
| 1: Part1::_Map contruction_                  |      /2  |    | 
| 2: Part2::_Thymio code_                                           |      /4  |    |
| 3: Part3::_Video demonstration_        |      /2  |    |  
| <b>Total                                       |     /8 | </b>   |
