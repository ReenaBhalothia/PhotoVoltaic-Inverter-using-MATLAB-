# PhotoVoltaic-Inverter-using-MATLAB-
The project  involves the simulation and analysis of a 50KW grid tied photovoltaic inverter system using MATLAB/ simulink . the model is designed to convert DC power generated from a photovoltaic (PV) source into AC power that can be synchronized and fed into the utility grid . 
It demonstrates the core functionality of inverter-based renewable energy systems used in real-world solar power plants.
The system includes a DC power source (representing solar PV output), a power electronic inverter configured for DC-AC conversion, and a grid interface for synchronization with the main supply. Filtering components are included to reduce harmonic distortion and ensure waveform quality. The model simulates key aspects such as voltage and current waveforms, grid synchronization, and real power transfer to the grid.
## Project Overview

- Objective: To simulate a grid-connected photovoltaic inverter system using MATLAB/Simulink.
- System Capacity: 50 kW
- System Type: Grid-Tied (Without MPPT)
- Modeling Platform: MATLAB/Simulink

## Features

- Simulation of a complete photovoltaic inverter system.
- Grid synchronization capability.
- Conversion of DC to AC using a power electronic inverter.
- Visualization of voltage, current, and power characteristics.
- Basic protection and filtering included in the model.

## Components of the Model

- Photovoltaic Source (DC) – Represents the solar power input.
- Inverter (DC to AC)– Performs conversion of power suitable for grid feeding.
- Control Logic – Manages switching and grid interfacing.
- Grid Interface – Ensures proper phase and voltage matching with the grid.
- Filters – Smooth out waveform and reduce harmonics.

##  Simulation Outputs

- Voltage and current waveforms at inverter and grid end
- AC power delivered to the grid
- Grid phase and voltage matching performance

## File Information

- grid_tied_50kw_inverter.slx: Main Simulink model file.

##  How to Run

1. Open the .slx file in MATLAB (R2020 or later).
2. Set simulation parameters like stop time and solver.
3. Run the simulation.
4. Observe outputs via scopes and display blocks.
