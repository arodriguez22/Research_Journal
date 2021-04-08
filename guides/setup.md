### Set Up The Enviornment Ubuntu 18.04 ROS Melodic

## Need to install
1. Research Journal
2. ROS
3. Follow the [tutorial package](https://github.com/dartmouthrobotics/ros_tutorial_package)
	to install ROS, catkin, and necessary repos
4. Follow [guide](https://docs.google.com/document/d/1AgHEoISfurCphe3-cNENub1hV4N7bBuUsl3nxiSbwGM/edit) for CS class
	install kingfisher and necessary packages


# Step 1: install research journal
	find the directory you want to clone the repo and type:
	`https://github.com/arodriguez22/Research_Journal.git`
	
	DONT FORGET TO PULL BEFORE EDITING


# Step 2: install ROS(from website)
	1. Setup sources:
		`sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`
	2. Set up keys:
		`sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654`
	3. Install:
		`sudo apt update`
		`sudo apt install ros-melodic-desktop-full`
	4. Enviornment Setup:
		`echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc'	

# Step 3: follow tutorial package
	
	1. Create directory
		`mkdir -p catkin_ws/src`
		`cd catkin_ws/src`
	2. install dependencies (go back and add):
		`sudo apt-get build-dep python-matplotlib` 
