### Sample Simulation World

To help you get started, I’ve included a sample simulation. Reviewing the sample, its aspects, and the directory structure will help you build your own world in Gazebo. Please note that you have only visual access to the sample simulation as it's not provided to you in the Udacity Workspace or anywhere else.

We are providing you with a Udacity Workspace for your project. You can find this Workspace under the headline Gazebo in the Workspace. Whenever you feel ready, launch the Workspace, go to desktop, and start the project!


## Output Image

// insert image here

## Project Aspects

Inside the Gazebo world you can identify:

- Udacity Office: A building model designed on the Building Editor tool of Gazebo. The structure contains features, and colors.
- Green humanoid robot: Two instances of a model designed on the Model Editor tool of Gazebo.
- Tables: A model imported from the Gazebo online library.
- Terminal: A welcome message generated from a world plugin and printed to the terminal.


## Directory Structure

The sample simulation world folder has the following directory structure:

    .Project1                          # Build My World Project 
    ├── model                          # Model files 
    │   ├── Building
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── HumanoidRobot
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script      
    │   ├── welcome_message.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── UdacityOffice.world
    ├── CMakeLists.txt                 # Link libraries 
    └──                              

## Your task

Note that your project should have the same aspects and should follow the same directory structure as the sample project! Pick a place where you want to deploy your robot, for example: your apartment, your office, or your favorite restaurant. In addition, create any model of your choice and import a model from the Gazebo library. 
