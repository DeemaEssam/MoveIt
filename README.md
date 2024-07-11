# MoveIt
1. Prerequisites:
```ruby
sudo apt-get install ros-noetic-moveit
```
2. Install the MoveIt Package:
```ruby
cd ~/catkin_ws/src
git clone https://github.com/smart-methods/arduino_robot_arm
cd ~/catkin_ws
rosdep install --from-paths src --ignore-src -r -y
```
3. Running the MoveIt Package:

<img src="https://github.com/DeemaEssam/DeemaEssam.github.io/assets/106381596/770371d4-9671-45b3-8bf2-b20ad5f77df4" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="500" height="300" />

```ruby
catkin_make
```

<img src="https://github.com/DeemaEssam/DeemaEssam.github.io/assets/106381596/c696b707-9b0e-439b-8239-b062b0d0e956" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="500" height="300" />

```ruby
roslaunch moveit_pkg demo.launch
roslaunch moveit_pkg demo_gazebo.launch
```

https://github.com/GDHadeel/Robot-Arm-Control-with-Joint-State-Publisher-and-MoveIt/assets/106381596/9963e4a3-24d6-4f49-9620-fce99ef7cf6f
