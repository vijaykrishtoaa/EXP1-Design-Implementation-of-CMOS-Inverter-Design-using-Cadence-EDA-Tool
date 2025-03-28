# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

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
![WhatsApp Image 2025-03-28 at 13 15 19_78ea6adf](https://github.com/user-attachments/assets/6852a7c1-a27d-4b6e-aacc-390453dacce2)

   
#### 2. Transient Response Setup:
![WhatsApp Image 2025-03-28 at 13 15 13_79fdbe7b](https://github.com/user-attachments/assets/c899a7d1-6adf-43fa-b511-9fdadfb69616)

    
#### 3. Voltage Transfer Characteristic (VTC)  Setup:

  ![WhatsApp Image 2025-03-28 at 13 15 18_aa3abb3f](https://github.com/user-attachments/assets/6059d8bd-b8f0-4e97-a9a3-445d77140376)

## Output
#### 1.Transient Analysis Output
![WhatsApp Image 2025-03-28 at 13 15 13_1d120356](https://github.com/user-attachments/assets/04495205-43df-452c-bcf3-d2f218017c00)

 
#### 2.DC Analysis Output
![WhatsApp Image 2025-03-28 at 13 15 15_93410a5f](https://github.com/user-attachments/assets/69485871-bc68-4144-a82e-88aee1189a31)



## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











