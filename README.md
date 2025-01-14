# CPPND: Capstone ROS2 Hungerbot Simulator

This project simulates a system using ROS2 API's for topics, nodes, publishers and subscribers. A simplified, simulated [Turtlebot](https://www.turtlebot.com/) gobbles up food using its single laser sensor. The system is displayed in realtime using [SDL](https://www.libsdl.org/). It reimplements ROS2 API'S, not using any code from ROS, and doesn't attempt to simulate ROS packages or launch files. I focus on using C++'s concurrency and memory management features to implement ROS2-like nodes.

The starter repo for this project, which provides the basis for the visualization code I used, can be found at [udacity/CppND-Capstone-Snake-Game](https://github.com/udacity/CppND-Capstone-Snake-Game). The code for that repo was inspired by [this](https://codereview.stackexchange.com/questions/212296/snake-game-in-c-with-sdl) StackOverflow post. This is my capstone project for [Udacity's C++ Nanodegree](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213), using knowledge I'm gaining from the [The Construct's Robotics Developer Master Class](https://www.theconstructsim.com/robotics-developer/), which I will complete in August 2022.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  >Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source. 
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./hungerbot`.


## CC Attribution-ShareAlike 4.0 International


Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
