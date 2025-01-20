[[!1.2 Types of Processor]]

Key Uses of GPUs

- **3D Modelling**: Rendering lighting effects, textures, and shadows in 3D environments.
- **Data Modelling**: Handling large datasets and complex operations like sorting and filtering data.
- **Financial Modelling**: Simulating scenarios in risk modelling and option pricing.
- **Data Mining**: Analyzing large amounts of data to find patterns and perform statistical analysis.
- **Machine Learning**: Training models on large datasets and speeding up predictions on new data.

Key Benefits of Multicore Processors

- **Speed**: Tasks can be divided into subtasks that can be executed simultaneously, reducing execution time.
- **Improved Performance**: Simultaneous computation on different data subsets enhances performance in applications like machine learning.
- **Better Resource Utilization**: More effective use of computer resources as multiple cores can be utilized for different tasks.
- **Multitasking**: Each core can handle different tasks, improving responsiveness and reducing the impact of background tasks.

Key Limitations of Parallel Processing

- **Limit on Maximum Speed**: There is a limit to the maximum speed improvement achievable through parallel processing if parts of the program cannot be parallelized.
- **Complex Programming**: Writing code for parallel processing is more complex than for serial processing, requiring careful synchronization and data sharing.
- **Debugging Difficulty**: Debugging parallel programs is more challenging due to the timing of events.
- **Communication Overhead**: Communication between processors can consume significant time and resources, potentially negating the benefits of parallel processing.

Facts to Memorize

- CISC processors are typically used in laptops and desktops.
- RISC processors are typically used in smartphones and tablets.
- GPUs can have up to 76 cores.
- SIMD (Single Instruction Multiple Data) processing allows multiple processing elements to perform the same operation on multiple data points simultaneously.

Reference Information

- CISC (Complex Instruction Set Computer) has a larger instruction set with complex instructions.
- RISC (Reduced Instruction Set Computer) has a smaller instruction set with simpler instructions.
- Parallel processing can be achieved with multicore systems or multiple processors (CPU and GPU).

Problem-Solving Steps

To effectively utilize parallel processing in programming, follow these steps:

1. **Identify Tasks**: Break down the main task into smaller subtasks that can be executed independently.
2. **Assess Parallelizability**: Determine which tasks can be run in parallel and which must be executed serially.
3. **Synchronize Tasks**: Ensure that tasks that depend on each other are synchronized properly to avoid data inconsistencies.
4. **Implement Parallel Code**: Use appropriate programming constructs (like threads or parallel libraries) to implement the parallel execution of tasks.
5. **Test and Debug**: Thoroughly test the parallel implementation to identify and fix any issues, keeping in mind that debugging parallel code can be more complex than serial code.

Key Terms/Concepts

- **CISC (Complex Instruction Set Computer)**: A type of processor with a large instruction set that includes complex instructions, often taking multiple clock cycles to execute.
- **RISC (Reduced Instruction Set Computer)**: A type of processor with a smaller instruction set that uses simpler instructions, typically executing in one clock cycle, making it suitable for pipelining.
- **GPU (Graphics Processing Unit)**: A specialized processor designed to handle graphics processing, capable of performing many calculations simultaneously, which is beneficial for tasks like 3D modeling and machine learning.
- **Multicore Processor**: A processor with multiple processing units (cores) that can execute instructions independently and simultaneously, enhancing performance through parallel processing.