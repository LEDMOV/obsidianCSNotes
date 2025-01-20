[[!1.1 Structure & Function of the Processor]]

**Fundamental Theories**

- **Pipelining**: Improves CPU performance by allowing multiple instructions to be processed at different stages simultaneously, reducing idle time.
- **Von Neumann vs. Harvard Architecture**: Von Neumann architecture uses a unified memory for data and instructions, while Harvard architecture uses separate memories, allowing for faster processing.

**Key Performance Metrics**

- **Clock Speed**: Measured in Hertz (Hz), indicates how many cycles per second the CPU can perform. Higher clock speeds generally mean faster processing.
- **Number of Cores**: Refers to the number of processing units within the CPU. More cores allow for parallel processing, improving performance for multi-threaded tasks.
- **Cache**: A small amount of high-speed memory located close to the CPU, used to store frequently accessed data and instructions, improving retrieval speed.

**Key Events**

- **Introduction of Pipelining**: A significant advancement in CPU design that allowed for more efficient instruction processing.
- **Development of Harvard Architecture**: Enhanced performance by separating instruction and data memory, allowing concurrent access.

**Facts to Memorize**

- Clock speed: 1 Hz = 1 cycle per second
- Typical clock speed of a computer: 2.3 GHz = 2,300,000,000 Hz
- Common registers in CPU: PC, ACC, MAR, MDR, CIR
- Levels of cache: Level 1, Level 2, Level 3

**Reference Information**

- Fetch-Decode-Execute Cycle: Fetch, Decode, Execute
- Types of computer architecture: Von Neumann and Harvard
- Types of buses: Data bus, Address bus, Control bus

**Concept Comparisons**

|Feature|Von Neumann Architecture|Harvard Architecture|
|---|---|---|
|Memory|Unified Memory|Separated Memory|
|Bus|Single Shared Bus|Separate Buses for Data and Instructions|
|Control Units|Single Control Unit|Separate Control Units|
|Usage|Most modern computers|Specialized embedded systems|
|Performance|Limited by shared memory access|Improved performance due to concurrent access|

**Problem-Solving Steps**

To analyse the Fetch-Decode-Execute Cycle:

1. **Fetch**: Load the address from the PC into the MAR, fetch the instruction from memory, and load it into the MDR.
2. **Decode**: Transfer the instruction from the MDR to the CIR, split it into opcode and operand, and send it to the CU for decoding.
3. **Execute**: Depending on the instruction, use the appropriate registers (ACC, MAR, MDR) to perform the operation, such as loading data, storing data, or performing arithmetic operations.

**Key Terms/Concepts**

- **CPU (Central Processing Unit)**: The primary component of a computer responsible for processing data and executing instructions.
- **Fetch-Decode-Execute Cycle**: The process by which the CPU retrieves an instruction from memory, decodes it, and executes it.
- **Pipelining**: A technique that allows multiple instructions to be processed simultaneously at different stages of the fetch-decode-execute cycle.
- **Von Neumann Architecture**: A computer architecture model that uses a single memory space for both data and instructions.
- **Harvard Architecture**: A computer architecture model that uses separate memory spaces for data and instructions, allowing for simultaneous access.