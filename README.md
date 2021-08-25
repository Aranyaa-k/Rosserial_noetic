# Setting up Rosserial for Arduino
The following are the steps to set up rosserial for arduino<br />
- Installation of Arduino IDE
- Installation of Rosserial noetic
- Clone repository
- Making the ROS packages in Arduino

## Installation of Arduino IDE 
Click on this [link](https://www.arduino.cc/en/software)<br /> 
The above link will take you to the official Arduino website from where you can choose to download the Arduino IDE based on your system configuration. <br />

Once the installation is complete extract the compressed folder into a desired folder on your system.

### Running the installation script
Open terminal in the extracted folder or change directory to the extracted folder in any terminal.<br /> 
Type in `./install.sh` in the terminal and hit enter. <br /> 

This completes the installation of the Arduino IDE 

## Installation of rosserial noetic
Use the below command line in the terminal to install rosserial noetic <br />
```sudo apt-get install ros-noetic-rosserial-arduino ```

## Clone repository
Clone this repository in src folder in catkin_ws using the following command line <br />
```clone rep https://github.com/Aranyaa-k/rosserial_noetic.git```<br />

Change directory to catkin_ws and run `catkin_make`

## Making the ROS packages in Arduino
After running `roscore` open new terminal and change directory to libraries in the extracted arduino folder and run the below command<br />
```rosrun rosserial_arduino make_libraries.py```


