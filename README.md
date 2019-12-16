# RPI DUCKIETOWN FALL 2019: Lane following
Group Members: Guanjie Zhao, Run Wang, Helen Yuan
Duckiebot: rng

## Introduction

This repository is a fork of the original at http://github.com/duckietown/Software

In this repository we will collect all the software, middleware, drivers, ROS modules, and so on, that would allow to run our cars.  

Video: https://www.youtube.com/watch?v=5eXh7ZY_gTE

## Running the code

Follow the installation in the rpiRobotics repository for setting up the Duckiebot and your laptop: https://docs.google.com/document/d/1J0EYZkcoZcbjndBVh_g7ouEWFcPu9WZ6be_LVghDoII/edit#

To get files in this repository:
	$ git clone https://github.com/hyuan0v0/rpiduckietown.git

Start the lane following node with the command:
	$ roslaunch duckietown lane_controller.launch veh:=${VEHICLE_NAME}

To see the camera once the command above runs:
	$ rqt_image_view