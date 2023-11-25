

locale  # check for UTF-8

sudo apt update && sudo apt install locales
sudo locale-gen en_US en_US.UTF-8
sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
export LANG=en_US.UTF-8

locale  # verify settings



sudo apt install software-properties-common
sudo add-apt-repository universe


sudo apt update && sudo apt install curl -y
sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key -o /usr/share/keyrings/ros-archive-keyring.gpg

echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/ros-archive-keyring.gpg] http://packages.ros.org/ros2/ubuntu $(. /etc/os-release && echo $UBUNTU_CODENAME) main" | sudo tee /etc/apt/sources.list.d/ros2.list > /dev/null


sudo apt update && sudo apt install ros-dev-tools


sudo apt update
sudo apt upgrade


sudo apt install ros-iron-desktop



# Replace ".bash" with your shell if you're not using bash
# Possible values are: setup.bash, setup.sh, setup.zsh
echo "source /opt/ros/iron/setup.bash" >> ~/.bashrc
source /opt/ros/iron/setup.bash




sudo apt-get update && sudo apt-get install -y \
     ros-iron-ros2-controllers \
     ros-iron-gazebo-ros \
     ros-iron-gazebo-ros-pkgs \
     ros-iron-ros2-control \
     ros-iron-gazebo-ros2-control \
     ros-iron-joint-state-publisher-gui \
     ros-iron-joy \
     ros-iron-joy-teleop \
     ros-iron-turtlesim \
     ros-iron-robot-localization \
     ros-iron-tf-transformations \
     ros-iron-plotjuggler \
     ros-iron-plotjuggler-ros




sudo apt-get install python3-pip
