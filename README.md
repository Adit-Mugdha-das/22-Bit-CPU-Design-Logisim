🎨 22-Bit CPU Design Using Logisim
🛠️ Overview
This project demonstrates the design and implementation of a 22-bit CPU using Logisim, a graphical logic circuit simulator. The CPU features modular components, including an Arithmetic Logic Unit (ALU), a Control Unit, and memory modules (ROM and RAM). It supports:

✅ Arithmetic calculations
✅ Bitwise logic operations
✅ Memory management
🚀 Key Features
🔢 1. Arithmetic Logic Unit (ALU)
Performs:
➕ Addition
➖ Subtraction
🔗 Bitwise Operations: AND, OR, NAND, NOR.
Includes universal gates for logical computations.
🎛️ 2. Control Unit
Decodes and executes instructions from ROM.
Controls data flow between CPU components.
📝 3. Instruction Set
Custom opcodes for various operations:
Bitwise AND: 0
Addition: 1
Subtraction: 4
NAND: 7
Halt: 9
🗂️ 4. Memory Management
RAM: Temporarily stores data during execution.
ROM: Preloaded with instruction codes.
💻 Instruction Format
Opcode (4 bits): Specifies the operation.
Data Bits (Remaining bits): Encodes operand and address.
Instruction Examples
🔧 Operation	📜 Machine Code
Load	18000f
Add	04000c
Store	08000a
Halt	240000
⚙️ How It Works
Instruction Execution:
Fetch instructions from ROM.
Decode opcode and execute with the ALU or memory.
Data Flow:
Seamless data flow between components.
Simulation:
Built and tested using Logisim with real-time clock control.
🛠️ Technologies Used
Logisim: Circuit design and simulation.
Multiplexers: Operation selection.
Logic Gates: Logical and arithmetic operations.
ROM/RAM: Instruction and data storage.
