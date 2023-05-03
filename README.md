# teb_local_planner_tutorials
## Running Instructions:
1. Install dependencies:
    ```shell
    sudo apt install ros-melodic-navigation
    sudo apt-get install ros-melodic-slam-gmapping
    sudo apt-get install ros-melodic-teb-local-planner
    ```
3. Suppose you have made a catkin workspace named `catkin_ws`.
4. Once you are finished with all the dependencies, you can git clone this package from github into your ROS workspace and `catkin_make` it. 
    ```shell
    cd ~/catkin_ws/src
    git clone https://github.com/haotiangu/teb_local_planner_tutorials.git
    cd ~/catkin_ws
    catkin_make
    cd ~/catkin_ws/src 
    git clone https://github.com/AMRobots/stage_ros.git
    cd ../
    catkin_make --only-pkg-with-deps stage_ros
    ```
