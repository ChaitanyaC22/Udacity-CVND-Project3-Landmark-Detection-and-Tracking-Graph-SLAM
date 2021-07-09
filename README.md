# Udacity-CVND-Project3-Landmark-Detection-and-Tracking-Graph-SLAM

## Objective

Implement SLAM, a robust method for tracking an object over time and mapping out its surrounding environment using elements of probability, motion models, linear algerbra.


## About the Project

The goal of the project is to implement SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! A map of an environment is created from only sensor and motion data gathered by a robot, over time. SLAM gives a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.*


## Example

The image below demonstrates an example of the 2D world. It illustrates the robot's final pose and landmarks: <br>
[![image](https://github.com/ChaitanyaC22/Udacity-CVND-Project3-Landmark-Detection-and-Tracking-Graph-SLAM/blob/chai_main/images/robot_world.png)](https://github.com/ChaitanyaC22/Udacity-CVND-Project3-Landmark-Detection-and-Tracking-Graph-SLAM/blob/chai_main/images/robot_world.png)

## Project Instructions

The project is broken up into three Python notebooks.

**Notebook 1** : Robot Moving and Sensing

**Notebook 2** : Omega and Xi, Constraints

**Notebook 3** : Landmark Detection and Tracking

In this project, we have implemented SLAM in stages after understanding each and every step in the process. Complete robot sense(), move() and other supplemental functions can be located in the `robot_class.py` file. 
