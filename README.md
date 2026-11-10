# Water Tank Filling and Draining Automation System – Manual & Automatic Modes

## Project Overview

This project demonstrates a PLC-based Water Tank Filling and Draining Automation System with two operating modes: **Manual Mode** and **Automatic Mode**.

The system is designed to control the filling and draining of a water tank using level sensors, control logic, and motor/pump or valve operations. It provides both operator-controlled operation and automated process control to improve efficiency, reduce manual intervention, and prevent tank overflow or dry running.

## Project Objectives

- Automate the water tank filling and draining process using PLC logic.
- Implement Manual and Automatic operating modes.
- Monitor water levels using level sensors.
- Control filling and draining operations based on tank conditions.
- Prevent tank overflow and unsafe pump operation.
- Understand industrial automation concepts through a practical application.

## Operating Modes

### 1. Manual Mode

In Manual Mode, the operator has direct control over the filling and draining operations.

**Working:**
- The operator can manually start and stop the filling operation.
- The operator can manually start and stop the draining operation.
- Level sensor conditions are used as safety interlocks.
- Filling is stopped when the maximum water level is reached.
- Draining is stopped when the minimum water level is reached.

### 2. Automatic Mode

In Automatic Mode, the PLC controls the entire process based on level sensor inputs and programmed logic.

**Working:**
1. The PLC monitors the water level inside the tank.
2. When the water level reaches the low-level condition, the filling operation starts.
3. The tank continues filling until the high-level sensor is activated.
4. The filling operation stops automatically.
5. The draining operation starts according to the programmed sequence.
6. When the water level reaches the low-level condition, draining stops.
7. The cycle repeats automatically.

## System Components

- PLC Controller
- High-Level Sensor
- Low-Level Sensor
- Water Pump / Motor
- Inlet and Outlet Control Valves (if implemented)
- Start and Stop Push Buttons
- Manual / Automatic Mode Selector
- PLC Programming Software

## Control Logic

The PLC receives signals from the level sensors and operator inputs and executes the programmed control logic.

| Input | Function |
|---|---|
| Start Push Button | Starts the system |
| Stop Push Button | Stops the system |
| Manual Mode Selector | Selects manual operation |
| Automatic Mode Selector | Selects automatic operation |
| Low-Level Sensor | Detects minimum water level |
| High-Level Sensor | Detects maximum water level |

| Output | Function |
|---|---|
| Filling Pump / Inlet Valve | Controls water filling |
| Draining Pump / Outlet Valve | Controls water draining |

## Key Features

- Dual operating modes: Manual and Automatic
- PLC-based process control
- Water-level monitoring
- Automatic filling and draining sequence
- Tank overflow prevention
- Pump protection through level-based interlocks
- Improved process control and reduced manual intervention

## Skills Demonstrated

- PLC Programming
- Industrial Automation
- Digital Inputs and Outputs
- Ladder Logic (LAD)
- Process Control
- Sensor-Based Automation
- Interlocking Logic
- Manual and Automatic Control Systems
- PLC Simulation

## Applications

- Industrial water storage systems
- Manufacturing plants
- Water treatment systems
- Automated liquid handling systems
- Industrial process automation

## Project Outcome

Successfully developed a PLC-based control system concept for managing water tank filling and draining operations through Manual and Automatic modes. The project demonstrates the application of PLC programming, sensor integration, control logic, and industrial automation principles.

---

**Project Category:** Industrial Automation  
**Project Type:** PLC-Based Automation  
**Control System:** Manual & Automatic  
**Programming Language:** Ladder Logic (LAD)  
**Software:** [Add the PLC programming software used]
