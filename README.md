# Digital Stopwatch with Lap Monitoring Using Verilog HDL

## About the Project
This is our VLSI mini project developed using Verilog HDL for a Cyclone II FPGA board. The project implements a digital stopwatch with Start, Stop, Reset, and Lap functions. Since the FPGA board does not have a built-in numerical display, onboard LEDs are used to indicate selected output states.

## Tools Used
- Verilog HDL
- Quartus II
- ModelSim
- Cyclone II FPGA

## Features
- Start and stop the counting operation.
- Reset the stopwatch to its initial state.
- Capture lap readings without interrupting the main counter.
- Indicate selected output states using LEDs.
- Verify the design using ModelSim simulation.

## Working Principle
The FPGA clock provides the timing reference. The Verilog logic controls the counter according to the input signals. The Lap function stores the current count separately while the main counter continues running.

## Project Presentation
The PowerPoint presentation explaining the project is available in this repository.

## Future Improvements
- Add an external seven-segment display.
- Store multiple lap readings.
- Implement a countdown timer.

## Conclusion
This project provides practical experience in Verilog HDL, digital logic design, simulation, and FPGA implementation using Quartus II and ModelSim.
