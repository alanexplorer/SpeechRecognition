# Voice control for ROS turtlebot with pocketsphinx (br-pt) #

## Installation Support Library:

sudo apt-get install ros-kinetic-audio-common

sudo apt-get install libasound2

sudo apt-get install gstreamer0.10-*

sudo apt-get install python-gst0.10

## Install pocketsphinx:

sudo apt-get install pocketsphinx*

## Install pocketsphinx acoustic model:

cd catkin_ws/src

git clone https://github.com/alanexplorer/SpeechRecognition.git

cd pocketsphinx/

## Installation Support Library:

dpkg -i libsphinxbase1_0.8-6_amd64.deb

dpkg -i libpocketsphinx1_0.8-5_amd64.deb

dpkg -i gstreamer0.10-pocketsphinx_0.8-5_amd64.deb

cd ..

catkin_make

## how run 

terminal 1 : roslaunch turtlebot_gazebo turtlebot_world.launch

terminal 2 : rosrun SpeechRecognition voice_control.py

## video:

https://www.youtube.com/watch?v=_06GwtonBrY




