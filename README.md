# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

![image](https://github.com/user-attachments/assets/aa43c6fd-cd59-4b74-b38b-ccf1b6632d1b)

#### Synthesis RTL Schematic :

![image](https://github.com/user-attachments/assets/48b0fd74-bbc8-45dc-a4be-4421b6712b1c)

#### Area report:

![image](https://github.com/user-attachments/assets/6235d0e0-32fb-4b11-8915-ef2557cd7e86)

#### Power Report:

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
