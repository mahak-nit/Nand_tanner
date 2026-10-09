CMOS NAND Gate Implementation Using Tanner EDA

Project Overview:
This project demonstrates the implementation and simulation of a CMOS NAND gate using Tanner EDA tools. The CMOS circuit structure is designed in S-Edit, the SPICE netlist is written in T-Edit, and the output waveform is analyzed in W-Edit.

Objectives:
* To understand the working principle of a CMOS NAND gate.
* To design the transistor-level CMOS structure using S-Edit.
* To write and simulate the SPICE netlist.
* To analyze the input and output waveforms.

Tools Used:
* S-Edit: To design the CMOS NAND gate schematic.
* T-Edit: To write and prepare the SPICE netlist.
* T-Spice: To simulate the circuit using the netlist.
* W-Edit: To visualize and analyze the simulation waveforms.

Circuit Design:
A CMOS NAND gate is implemented using two PMOS transistors connected in parallel in the pull-up network and two NMOS transistors connected in series in the pull-down network.
The gate has two inputs, A and B, and one output, Y.
Boolean Expression
Y = ~(A · B)

Truth Table:
| Input A | Input B | Output Y |
| 0       | 0       | 1        |
| 0       | 1       | 1        |
| 1       | 0       | 1        |
| 1       | 1       | 0        |

Implementation Steps:
1. S-Edit: Create the transistor-level CMOS NAND gate schematic using PMOS and NMOS transistors.
2. T-Edit: Write the SPICE netlist containing the transistor connections, model parameters, input voltage sources, and simulation commands.
3. T-Spice: Run the simulation to obtain the circuit response.
4. W-Edit: Open the simulation output and plot the input signals A and B and the output signal Y.
5. Analysis: Verify the simulated output against the NAND gate truth table.

Expected Result:
The output remains HIGH for all input combinations except when both inputs are HIGH, in which case the output becomes LOW.
The simulated waveform is used to verify the correct operation of the CMOS NAND gate.

Learning Outcomes
* Understanding CMOS pull-up and pull-down networks.
* Learning transistor-level schematic design.
* Understanding SPICE netlist structure and circuit simulation.
* Analyzing digital input and output waveforms.

Author:
Mahak
Electronics and Communication Engineering
National Institute of Technology, Hamirpur
