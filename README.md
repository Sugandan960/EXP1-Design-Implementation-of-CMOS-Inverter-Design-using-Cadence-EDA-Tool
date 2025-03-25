# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools
Sugandan.N 
212222060260
## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:

 ![image](https://github.com/user-attachments/assets/29fa2c52-0797-4fb1-9012-5679ad96deee)

#### 2. Transient Response Setup:
![image](https://github.com/user-attachments/assets/cdefd2bf-721a-41e4-8557-e13802c05250)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:
![image](https://github.com/user-attachments/assets/31a6cd90-cd55-4df2-85ea-39cbe47de40e)

## Output
#### 1.Transient Analysis Output
![image](https://github.com/user-attachments/assets/642a266e-ea1d-4fff-a9ab-14c6b5eb200e)

#### 2.DC Analysis Output

![image](https://github.com/user-attachments/assets/7b5c192d-1c39-430c-bdee-c563342497bc)

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











