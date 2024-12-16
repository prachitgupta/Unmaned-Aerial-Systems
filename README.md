# Unmaned-Aerial-Systems


This repository contains codes and scripts to interface with Ardupilot at various levels, offering flexibility for both high-level and low-level control tasks.

## Features
- **High-Level Interface with MAVROS:**
  - Controllers for both linear and nonlinear systems.
  - Designed to work seamlessly with Ardupilot for advanced applications.

- **Low-Level Interface Options:**
  - **Pymavlink Scripts:** Basic scripts for directly sending MAVLink messages to Ardupilot.
  - **Lua Scripting:** Embedded scripting support for low-latency control and mission customization.

## Requirements
- ROS installed for using MAVROS.
- Python with `pymavlink` package for directly sending mav commands.
- Ardupilot-compatible hardware for testing and deployment.
- Ardupilot SITL installed and configured

## Usage
1. **High-Level Control:**
   - Navigate to the `controllers` directory for linear and nonlinear controllers.
   - Ensure MAVROS is installed and configured.

2. **Low-Level Scripting:**
   - Refer to the `pymavlink_scripts` folder for Python-based MAVLink communication.
   - Use the `lua_scripts` directory for Ardupilot's embedded scripting.



