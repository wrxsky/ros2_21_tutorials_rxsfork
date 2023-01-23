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

