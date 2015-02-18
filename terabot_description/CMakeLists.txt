cmake_minimum_required(VERSION 2.8.3)
project(terabot_description)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS 
	message_runtime 
	std_msgs 
	roscpp
	std_srvs
	std_msgs
	tf
)


catkin_package(

)


## Specify additional locations of header files
## Your package locations should be listed before other locations
# include_directories(include)
include_directories(
  ${catkin_INCLUDE_DIRS}
)

