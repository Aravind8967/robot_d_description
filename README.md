# robot_d_description

It is a 4 wheeled robot which has the
imu
camera 
ultrasonic
cmd_vel

you can download this repository by fallowing bellow steps

cd catkin_ws/src

git clone https://github.com/Aravind8967/robot_d_description.git

cd ..

catkin_make

------------ To see the robot command is ----------------------

roslaunch robot_d_description gazebo.launch

---------------------------- to move the robot command is ----------

rosrun teleop_twist_keyboard teleop_twist_keyboard.py

these are the command to see

this robot has cmd_vel imu laser camera also functionality

---------- you can check publishing topic by ------------

rostopic list

you can check this by publishing

--------------- for imu ----- 

rostopic echo /imu

---------- for odom ----------- 

rostopic echo /odom
