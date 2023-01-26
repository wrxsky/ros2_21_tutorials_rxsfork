# rx ros2 note

## all

- mogrify -format jpg *.png


## K6 pacakge

### rosdep (rosdepc)
- sudo rosdepc init
- rosdepc update
- rosdepc install -i --from-path src --rosdistro humble -y

### create package
- ros2 pkg create --build-type ament_python learning_pkg_python
- ros2 pkg create --build-type ament_cmake learning_pkg_c


## K18 Learning Gazebo
- ros2 launch learning_urdf display.launch.py
- ros2 launch learning_urdf display.launch.py model:=/home/runxin/Documents/itk_ws/gazebo_urdf_try/src/learning_urdf/urdf/mbot_with_kinect.urdf

- ros2 launch learning_gazebo load_urdf_into_gazebo.launch.py
- ros2 launch learning_gazebo load_mbot_camera_into_gazebo.launch.py
- ros2 launch learning_gazebo load_mbot_rgbd_into_gazebo.launch.py

- 
- ros2 run teleop_twist_keyboard teleop_twist_keyboard 

- ros2 launch ros_ign_gazebo_demos rgbd_camera_bridge.launch.py 



