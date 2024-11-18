# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic :
![WhatsApp Image 2024-11-18 at 13 22 13_8140f451](https://github.com/user-attachments/assets/0cffdbae-836b-41da-9a14-21394e1ab8b9)
### Area report:
![WhatsApp Image 2024-11-18 at 13 22 34_064d5cbf](https://github.com/user-attachments/assets/65676679-35fd-4a75-a43f-110bdb7c4966)
### Power Report:
![WhatsApp Image 2024-11-18 at 13 22 24_3658223c](https://github.com/user-attachments/assets/405a1244-966e-4a27-b957-bcb9542e0696)
### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
