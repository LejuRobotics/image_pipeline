# USEAGE

mkdir -p ~/catkin_ws/src

cd ~/catkin_ws/src

git clone https://github.com/LejuRobotics/ros_image_pipeline.git

catkin_init_workspace 

cd ..

catkin_make clean

catkin_make install

source ~/catkin_ws/devel/setup.bash

rosrun image_view image_view image:=/camera/color/image_raw

