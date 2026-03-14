📌 Description

This project implements a 4-bit Binary to Hexadecimal converter using VHDL.
The circuit receives four binary inputs (b3, b2, b1, b0) and produces the equivalent 4-bit hexadecimal output.
The conversion works by transforming the binary input into an integer value and then converting it back to a logical vector representation.
This type of implementation can be used in digital systems, FPGA designs, and digital logic simulations.

🎯 Project Goal

The purpose of this project is to:
Demonstrate data conversion in VHDL
Practice using IEEE libraries
Understand numeric type conversions
Apply digital logic concepts using Hardware Description Languages


⚙️ Technologies Used

VHDL
IEEE.STD_LOGIC_1164
IEEE.NUMERIC_STD
These libraries provide the necessary data types and functions for digital signal manipulation and numeric conversions.

🔄 Conversion Process

The 4 binary bits are concatenated with "000" to create a larger vector.
This vector is converted into an integer value using to_integer.
The integer value is processed inside a case structure.
The result is converted back to std_logic_vector.

📂 Code Structure
The code is divided into three main parts:

1️⃣ Libraries
Imports the libraries required for digital logic and numeric operations.
2️⃣ Entity
Defines the inputs and outputs of the circuit.
3️⃣ Architecture
Implements the conversion logic using a process and a case statement.

🚀 How to Use

Copy the code into a file:
BinarytoHex.vhd
Compile it using a hardware simulation or FPGA development tool, such as:
ModelSim
Intel Quartus
Xilinx Vivado
GHDL
Test different input combinations to verify the conversion.

