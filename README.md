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

#### Synthesis RTL Schematic :
![WhatsApp Image 2024-11-24 at 22 51 06_a6566640](https://github.com/user-attachments/assets/f47c3e8f-dcd3-40b5-8b07-7dbd9f7196c7)


#### Area report:
![WhatsApp Image 2024-11-24 at 22 51 06_50727698](https://github.com/user-attachments/assets/18098289-e890-4076-a7eb-97c7a38fd390)


#### Power Report:
![WhatsApp Image 2024-11-24 at 22 51 06_ee3d904c](https://github.com/user-attachments/assets/c17123f7-add5-4d2f-8f57-2b113a44d77d)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
