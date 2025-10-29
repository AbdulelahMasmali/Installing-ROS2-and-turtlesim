# Installing-ROS2-and-turtlesim

1. install humble hawksbill, installation steps i fallowed is in this link
https://docs.google.com/presentation/d/1XiIcqTIu_gaOxQyO9sP2DArzsQITcMc2/edit?slide=id.p36#slide=id.p36

2. run these codes in terminal:
  sudo apt update
  sudo apt install ros-humble-turtlesim

3. to check if the package is installed i run this code (ros2 pkg executables turtlesim).
  if i get this output:
                      turtlesim draw_square
                      turtlesim mimic
                      turtlesim turtle_teleop_key
                      turtlesim turtlesim_node

      
it's installed successfully

4. now we run it useing this code (ros2 run turtlesim turtlesim_node)
   it opens turtlesim
   
  then open anther terminal to control the turtle.
  run this codes 
   this code first for source ( source /opt/ros/humble/setup.bash )
   then this code next ( ros2 run turtlesim turtle_teleop_key )


5. after doing all the steps i can move the turtle with arrows
