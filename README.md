# KeyPad-VerilogHDL-Basys3

This is a Verilog HDL implementation of a Keypad driver for the Basys3 FPGA board. The code is designed to interface with a 4x4 matrix keypad, allowing users to input values by pressing various buttons on the keypad. The output is then displayed on a seven-segment LED display.

## Installation

To use this project, you will need a Basys3 FPGA board and the necessary software tools to program the board. You will also need to clone this repository and open the Verilog HDL files in your preferred development environment.

## Usage

Once you have the project set up and loaded onto your Basys3 board, you can use the keypad to input various values. The code currently supports numeric values (0-9) as well as the addition (+) and multiplication (*) operators. When you press a button on the keypad, the corresponding value will be displayed on the seven-segment LED display.

## Getting Started

1. Clone this repository:
    git clone https://github.com/zeynepozcelk/KeyPad-VerilogHDL-Basys3.git
3. Open Vivado and create a new project.
4. Add the KeyPad.v, SevenSegmentDisplay.v, and Basys3_Master.xdc files to your project.
5. Generate the bitstream and program the Basys3 board.

## Contributing

This project is open to contributions and suggestions. If you have ideas for how to improve the code or add new features, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
