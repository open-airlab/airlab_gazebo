# airlab_gazebo
ROS package for simulating the AIRLab cage in Gazebo

![](https://raw.githubusercontent.com/open-airlab/airlab_gazebo/main/media/gazebo_cage.png)

Do you want to have the AIRLab cage in your Gazebo environment? Just launch it as:

    roslaunch airlab_gazebo airlab_cage.launch

To spawn the obstacles in the cage:

    roslaunch airlab_gazebo spawn_obstacles.launch

![](https://raw.githubusercontent.com/open-airlab/airlab_gazebo/main/media/obstacles.png)

You can find the proposed waypoints in `config/waypoints.yaml`