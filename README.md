# Parsing Gazebo for FEAGI
#### Lukas Finn, Timothy Marshall, Brenden Vaccaro, Benson Beck
During this semester, our team has worked on enabling FEAGI's artificial general intelligence (AGI) to control a wide variety of robotic simulations that originate from Gazebo, a platform designed for simulating the control of robots and their environments.	We created a parsing program to convert simulation data from Gazebo into a readable format for FEAGI to configure and interpret so that their AGI can successfully control the simulation's robots.
# Using FEAGI With Gazebo
Our team was focused on creating a parsing program that converts Gazebo SDF files into readable JSON output to be used by the FEAGI Configurator, which will then generate necessary data for the Gazebo Controller. Gazebo allows for the use of many different inputs/sensors and outputs/actuators in their simulations, and all simulation data is stored in SDF files. The formatting of the data in these SDF files are not uniform, as projects will have different goals and types of robots. In order for the FEAGI Configurator to understand any given simulation, it needs to be fed a standardized JSON format. We successfully created a parser that adapts to simulations of all kinds and produces a proper JSON configuration tree that the Configurator can use to produce a JSON listing capabilities for the Gazebo Controller.

This project has allowed for robotic simulations of all types to successfully be controlled by FEAGI's artificial general intelligence.
