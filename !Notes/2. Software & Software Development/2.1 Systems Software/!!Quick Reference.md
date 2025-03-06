[[!2.1 Systems Software]]

Key Functions of Operating Systems

| Function            | Description                                                                    |
| ------------------- | ------------------------------------------------------------------------------ |
| Resource Management | Manages CPU, memory, disk drives, and printers, allocating resources to tasks. |
| File Management     | Handles storage, retrieval, and manipulation of data files.                    |
| Interrupt Handling  | Manages interrupts to ensure smooth operation of the system.                   |
| Security            | Provides features like password protection, firewalls, and virus scanning.     |
| User Interface      | Offers graphical (GUI) or command-line (CLI) interfaces for user interaction.  |

Key Types of Operating Systems

| Type                            | Description                                                                |
| ------------------------------- | -------------------------------------------------------------------------- |
| Distributed Operating Systems   | Run on multiple machines as a single unit for efficient task distribution. |
| Embedded Operating Systems      | Designed for specific tasks in devices not primarily computers.            |
| Multi-tasking Operating Systems | Allow multiple tasks to run concurrently on a single processor.            |
| Multi-user Operating Systems    | Support multiple users accessing resources concurrently.                   |
| Real-Time Operating Systems     | Ensure tasks are processed within specific timeframes.                     |

Key Memory Management Techniques

|Technique|Description|Benefits|Drawbacks|
|---|---|---|---|
|Paging|Divides memory into fixed-size blocks (pages).|Facilitates efficient memory management.|Can lead to internal fragmentation.|
|Segmentation|Divides memory into variable-sized segments based on logical data types.|Space-efficient allocation.|Can result in external fragmentation.|
|Virtual Memory|Uses secondary storage as an extension of primary memory.|Allows multitasking with limited RAM.|Slower access compared to physical memory.|

Facts to Memorize

- BIOS stands for Basic Input/Output System.
- The main functions of an operating system include resource management, file management, interrupt handling, security, providing a platform for software to run, providing a user interface, and providing utilities.
- Virtual memory allows a computer to use hard drive space as an extension of RAM.
- Paging can lead to internal fragmentation, while segmentation can lead to external fragmentation.

Reference Information

- Common operating systems: Windows, MacOS, Linux, Android, iOS.
- Types of scheduling algorithms: Pre-emptive (e.g., Round Robin, Shortest Remaining Time First) and Non-pre-emptive (e.g., First Come First Serve, Shortest Job First).
- Types of operating systems: Distributed, Embedded, Multi-tasking, Multi-user, Real-Time.

Problem-Solving Steps

To describe how the operating system uses virtual memory:

1. Identify when the system is low on primary memory.
2. Explain how the OS offloads less-critical data from RAM to virtual memory.
3. Describe how this creates space for higher-priority processes.
4. Mention the trade-off of slower access speeds when using virtual memory.

Key Terms/Concepts

- **Operating System (OS)**: Software that manages computer hardware and provides services for computer programs.
- **Device Driver**: Software that allows the operating system to communicate with hardware devices.
- **Virtual Machine (VM)**: An emulation of a computer system that runs inside another operating system.
- **BIOS (Basic Input/Output System)**: Firmware that initializes hardware during the booting process and provides runtime services for operating systems.
- **Memory Management**: The process of controlling and coordinating computer memory, including allocation and deallocation of memory space.