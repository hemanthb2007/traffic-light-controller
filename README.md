Traffic Light Controller Using Verilog HDL

Project Overview

The Traffic Light Controller Using Verilog HDL is a digital electronics project designed to control traffic signals automatically in a predefined sequence. The system operates three traffic lights: Red, Yellow, and Green.

The controller is designed using a Finite State Machine (FSM), which changes the traffic light states based on clock pulses and timing conditions. Verilog HDL is used to implement the design, and simulation is performed to verify its functionality.

Objectives

- To design a traffic light controller using Verilog HDL.
- To control Red, Yellow, and Green signals in a fixed sequence.
- To understand the working of Finite State Machines (FSM).
- To implement sequential logic using Verilog.
- To verify the design through simulation and waveform analysis.

Working Principle

The traffic light controller operates in three main states:

State| Traffic Signal| Operation
State 0| RED| Vehicles must stop
State 1| GREEN| Vehicles can move
State 2| YELLOW| Vehicles should prepare to stop

The controller follows this repeating sequence:

RED → GREEN → YELLOW → RED

The state transitions are controlled using clock pulses and timing conditions.

State Encoding

State| A| B
RED| 0| 0
GREEN| 0| 1
YELLOW| 1| 0

 Technologies Used

- Verilog HDL
- EDA Playground
- Digital Logic Design
- Testbench Simulation

 Simulation and Verification

The design is tested using a Verilog testbench.

The testbench provides:

- Clock signal
- Reset signal
- Simulation time

The output waveforms are observed to verify that the Red, Green, and Yellow signals change in the correct sequence.

Expected Output

The expected traffic signal sequence is:

1. RED – ON
2. GREEN – ON
3. YELLOW – ON
4. The sequence repeats continuously.

Only one traffic signal should be active at a time.

Applications

- Road traffic signal systems.
- Automated traffic management.
- Road intersections.
- Smart city applications.
- Digital control systems.

Learning Outcomes

Through this project, we gain practical knowledge of:

- Verilog Hardware Description Language.
- Finite State Machine design.
- Sequential logic circuits.
- Testbench development.
- Digital circuit simulation and waveform analysis.

Conclusion

The Traffic Light Controller was successfully designed using Verilog HDL and verified through simulation. The system demonstrates the use of FSM-based sequential logic to control traffic signals in a predefined sequence. This project provides practical experience in digital system design and hardware description languages.

Author

Hemanth B

Electronics and Communication Engineering (ECE)
