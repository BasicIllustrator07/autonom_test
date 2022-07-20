# lcube_test_description



## Build
git clone this repo in worksapce src directory <br />
```source /opt/ros/foxy/setup.bash && cd ~/ws && . install/setup.bash```  <br />
```colcon build --symlink-install```  

***
## Run
```source /opt/ros/foxy/setup.bash && cd ~/ws && . install/setup.bash``` <br />
```. /usr/share/gazebo/setup.sh``` <br />
```ros2 launch lcube_test_description launch_sdf_into_gazebo.launch.py```
