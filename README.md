# Self-Driving Car Project



**Date**: 2023-10-05  
**Name**: Jyothi Prasanna Kambam  
**Student ID**: 500233773  
**Project Title**: PART 1 - Implement the Self Driving Car Tutorial - 5%  
**Subject**: 2025W-T3 CSDD2002 - Emerging Dev. Technologies 01 (M11 Group 1)

## Overview
This project simulates a self-driving car using various algorithms and visualizations. 
The main components include:

- **index.html**: User interface for the simulation.
- **car.js**: Defines the `Car` class, which manages the car's behavior, movement, and interactions with the environment. 
It utilizes a neural network for decision-making and includes methods for updating the car's position, assessing damage, and drawing the car on the canvas.
- **controls.js**: Manages user input for car movement, allowing for keyboard controls. 
It listens for key events to update the car's direction and speed.
- **network.js**: Implements a neural network that processes sensor data to make driving decisions. It uses layers to learn and predict the best actions for the car.
- **road.js**: Defines the road layout, including lanes and borders. It manages the placement of obstacles and ensures the car stays within the road boundaries.
- **sensor.js**: Simulates sensors that detect the environment around the car. 
It provides data on obstacles and road conditions to assist in navigation.
- **utils.js**: Contains various utility functions used throughout the project for calculations and data manipulation.
- **visualizer.js**: Handles the rendering of the simulation, including the car, road, and other visual elements. It updates the canvas based on the car's position and state.

## Features
- Adjustable mutation amount for the car's behavior.
- Ability to set the number of cars in the simulation.
- Real-time visualization of the car's performance.

## Usage
1. Open `index.html` in a web browser.
2. Adjust the settings using the dropdown menus.
3. Observe the behavior of the self-driving car in the simulation.


## Acknowledgments
This project was inspired by the tutorial found at [this video](https://www.youtube.com/watch?v=Rs_rAxEsAvI).
The code is based on the tutorial's implementation, with modifications to suit the project's requirements.
# self-driving-car-js
