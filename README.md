# autonom_test

Simulation testbench for autonomous vehicles.

## Build
git clone this repo in worksapce src directory <br />
```source /opt/ros/foxy/setup.bash && cd ~/ws && . install/setup.bash```  <br />
```colcon build --symlink-install```  

***
## Run
```source /opt/ros/foxy/setup.bash && cd ~/ws && . install/setup.bash``` <br />
```. /usr/share/gazebo/setup.sh``` <br />
```ros2 launch autonom_test launch_sdf_into_gazebo.launch.py```

&nbsp;
&nbsp;
&nbsp;

![Alt text](sim.png)

![Alt text](simulation.png)
