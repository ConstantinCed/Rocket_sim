# TCV Landing Rocket Simulation and Animation

This repository contains code for simulating a TCV (Thrust Controlled Vehicle) landing rocket and animating it in Blender.

## Overview

1. **Rocket Simulation**: A Python script that simulates the behavior of a landing rocket using physics and PID controllers.
2. **Rocket Animation**: A Blender script that visualizes the simulated rocket landing by animating a 3D model based on the simulation data.

## Files

- `rocket_simulation.py`: Contains the code for simulating the TCV landing rocket.
- `rocket_animation.py`: Contains the code for animating the rocket in Blender using the simulation data.

## Usage

1. Run the `rocket_simulation.py` script to generate simulation data.
2. Use the `rocket_animation.py` script in Blender to animate the rocket based on the generated data.

## Requirements

- Python 3.x
- Blender 2.8x or higher


## Description

- The rocket simulation script calculates the rocket's altitude, velocity, thrust, angle, acceleration and other parameters during its flight.
- The Blender animation script creates a 3D model of the rocket and animates it according to the simulation data, including a dynamic flame effect based on the throttle.
