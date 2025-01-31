22-Bit CPU Design Using Logisim
Overview
This project demonstrates the design and implementation of a 22-bit CPU using Logisim, a powerful graphical logic circuit simulator. The CPU is built with modular components, including an Arithmetic Logic Unit (ALU), a Control Unit, and memory modules (ROM and RAM). It supports fundamental operations such as arithmetic calculations, bitwise logic operations, and memory management. The project aims to showcase a simplified yet functional CPU architecture with an emphasis on learning and simulation.

Key Features
Arithmetic Logic Unit (ALU):

Performs addition, subtraction, and bitwise operations (AND, OR, NAND, NOR).
Includes universal gates for logical operations.
Control Unit:

Decodes and executes instructions stored in ROM.
Facilitates the flow of data between CPU components.
Instruction Set:

Custom opcodes for various operations:
Bitwise AND: 0
Addition: 1
Subtraction: 4
NAND: 7
Halt: 9
Instructions are executed sequentially or based on control signals.
Memory Management:

RAM: Stores temporary data during execution.
ROM: Contains preloaded instruction codes.
Customizable Instruction Format:

Opcode (4 bits): Specifies the operation.
Data Bits (Remaining bits): Encodes operand and address.
Instruction Examples
Below are sample instructions in machine code for various operations:

Operation	Machine Code
Load	18000f
Add	04000c
Store	08000a
Halt	240000
How It Works
Instruction Execution:
The CPU fetches instructions from ROM.
The Control Unit decodes the opcode and signals the ALU or memory to perform operations.
Data Flow:
Data flows between the ALU, memory, and registers based on the instruction set.
Simulation in Logisim:
The project is built and tested in Logisim, where clock cycles control the instruction flow.
Technologies Used
Logisim: For circuit design and simulation.
Multiplexers: To select specific operations within the ALU.
Logic Gates: For bitwise operations and control logic.
ROM/RAM: For instruction and data storage.
Future Improvements
Add support for advanced operations like multiplication and division.
Implement pipelining for better performance and instruction throughput.
Introduce caching to minimize memory access latency.
Contributors
Adit Mugdha Das
How to Use the Project
Clone this repository:
bash
Copy
Edit
git clone https://github.com/Adit-Mugdha-das/22-Bit-CPU-Design-Logisim.git
Open the .circ files in Logisim.
Load the ROM with the provided machine code.
Simulate the CPU by running the clock and observe the outputs in real-time.
