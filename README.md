# AI-task2
**************************

1- Install Arduino in ubunto 16.04
- Download Arduino IDE for linux 64 bit: https://www.arduino.cc/en/software

  <img width="321" alt="‏لقطة الشاشة ١٤٤٦-٠٢-٠٩ في ١٠ ٢٣ ٤٦ م" src="https://github.com/user-attachments/assets/539f7531-88b6-4498-bda3-a33fe7ac9eca">


  *************
 2- go to the Files > downloads > right click on the comressed file and then click on extract here.


 
<img width="560" alt="‏لقطة الشاشة ١٤٤٦-٠٢-٠٩ في ١٠ ٢٥ ٣٢ م" src="https://github.com/user-attachments/assets/8f5abb2b-6279-45bb-87cd-f16d6d2251bb">

****************

3- go to the arduino file then right click > open in terminal


<img width="832" alt="‏لقطة الشاشة ١٤٤٦-٠٢-٠٩ في ١٠ ٢٦ ٣٣ م" src="https://github.com/user-attachments/assets/56fb41eb-ecf8-4d75-9e76-babcd5d4bb0f">


*******************************

4- type the following command to install Arduino

```ruby
sudo ./installl.sh
```

*************

Go to Terminal and run the following commands

```ruby
i. mkdir -p ~/catkin_ws/src

ii. cd ~/catkin_ws/

iii. catkin_make

iv. cd ~/catkin_ws/src

v. git clone https://github.com/smart-methods/arduino_robot_arm.git 

vi. cd ~/catkin_ws

vii. rosdep install --from-paths src --ignore-src -r -y

viii. sudo apt-get install ros-kinetic-moveit

ix. sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui

x. sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher

xi. sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control

xii. sudo nano ~/.bashrc

xiii. at the end of the (bashrc) file add the follwing line (source /home/ziyad/catkin_ws/devel/setup.bash)
then ctrl + o then ctrl + x (note:use your device name instead of "ziyad")

xiv. source ~/.bashrc

xv. roslaunch robot_arm_pkg check_motors.launch
```

****************
 The following program should run as shown below

 <img width="586" alt="‏لقطة الشاشة ١٤٤٦-٠٢-٠٩ في ١٠ ٣٠ ٣٢ م" src="https://github.com/user-attachments/assets/ba43240b-0026-41e9-a7a7-c0953911a1ad">


*********************


<img width="992" alt="‏لقطة الشاشة ١٤٤٦-٠٢-٠٩ في ١٠ ٣٠ ٥٦ م" src="https://github.com/user-attachments/assets/d7e879fe-d015-4659-8ce9-d119e2498bc1">




 
