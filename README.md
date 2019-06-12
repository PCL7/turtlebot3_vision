# turtlebot3_vision

Remote pc:
Extract the src.zip into a catkin workspace.
Download opencv, if not already installed.
$catkin_make

On the remote pc:
$roscore

On Turtlebot on one window:
$roslaunch turtlebot3_bringup turtlebot3_robot.launch
On Turtlebot on another window:
$roslaunch raspicam_node camerav2_1280x960.launch

On remote pc on two seperate windows:
$rosrun turtle_vision c_comm.py

$rosrun turtle_vision ttm.py



