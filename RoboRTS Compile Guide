### create ros work space

```
mkdir -p ~/catkin_ws/src # create ros source floder

cd ~/catkin_ws/src

catkin_init_workspace # initial work space

cd ~/catkin_ws/

catkin_make # compile source code

echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc # load env path
```

### clone RoboRTS package

```
cd ~/catkin_ws/src

git clone git@github.com:Freedom-Guo/RoboRTS.git
```

### compile RoboRTS package

```
cd ..

catkin_make
```

- ERROR

	- pcl_conversions

	```
	sudo apt-get install ros-melodic-pcl-conversions
	```
	
	- pcl_ros

	```
	sudo apt-get install ros-melodic-pcl-ros
	```
	
	- g2o

	```
	# env configuration
	sudo apt-get install libsuitesparse-dev
	
	sudo apt-get install qtdeclarative5-dev
	
	sudo apt-get install qt5-qmake
	
	sudo apt-get install libqglviewer-headers
	```

	```
	# install g2o
	cd

	git clone git@github.com:Freedom-Guo/g2o.git
	
	cd g2o/
	
	mkdir build
	
	cd build
	
	cmake ..
	
	make -j8
	
	sudo make install
	```
	
	- glog

	```
	# env configuration
	
	sudo apt-get install autoconf automake libtool
	```
	
	```
	# install glog
	
	git clone git@github.com:Freedom-Guo/glog.git
	
	cd glog
	
	mkdir build
	
	cd build
	
	cmake ..
	
	make -j 24
	
	sudo make install
	```
	
### 
