1) Create a 3D unity project then put Asset Zip folder to inside. 

Start broker with separate terminal.
1) cd catkin_ws/ 
2) source devel/setup.bash 
3) roslaunch beginner_tutorials websocket.launch 

Start it. Unity project. Then Start publisher with separate terminal.
1) cd python_catkin
2) rosrun tutorials publisher_node.py

NOTE: 

-You can check **publisher** in file **python_catkin/src/tutorials/scripts/publisher_node.py**

-You can subscriber in unity project "**ShapeRos/Assets/RosSharp/Scripts/RosBridgeClient/RosCommuncation/PoseStampedSubscriber.cs**"

Youtube Link : https://www.youtube.com/watch?v=wWOS9T5MOnU
