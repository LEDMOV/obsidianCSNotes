[[!4.3 Boolean Algebra]]

Fundamental Theories

|Theory/Model|Description|
|---|---|
|**Boolean Algebra**|A mathematical structure that captures the rules of logic operations and simplifies logical expressions.|
|**Karnaugh Mapping**|A technique for simplifying Boolean expressions by visual grouping of terms in a grid format.|
|**De Morgan's Theorems**|Rules that provide a method for simplifying expressions involving negations of ANDs and ORs.|

Key Components

- **AND Gate**: Outputs TRUE only if both inputs are TRUE.
- **OR Gate**: Outputs TRUE if at least one input is TRUE.
- **NOT Gate**: Inverts the input value.
- **XOR Gate**: Outputs TRUE if the inputs are different.
- **Half Adder**: A circuit that adds two single-bit numbers and produces a sum and carry output.

Key Procedures/Protocols

- **Evaluating Boolean Expressions**: Follow the order of operations: NOT, AND, OR, using parentheses to clarify.
- **Creating Karnaugh Maps**: Fill in the KMap based on the output of the Boolean expression, group 1s, and derive the simplified expression.
- **Simplifying Boolean Expressions**: Use rules such as De Morgan's Law, distribution, and absorption to reduce complex expressions.

Key Investigations

- **Truth Tables**: A table used to determine the output of a Boolean expression for all possible input combinations.
- **Logic Circuit Design**: The process of creating circuits that perform specific logical functions using gates.

Facts to Memorize

- Boolean operators: TRUE = 1, FALSE = 0
- Order of operations: NOT > AND > OR
- De Morgan's Laws:
    - NOT(A AND B) = (NOT A) OR (NOT B)
    - NOT(A OR B) = (NOT A) AND (NOT B)
- Truth table for AND:
    - A AND B = 1 only if both A and B are 1
- Truth table for OR:
    - A OR B = 1 if at least one of A or B is 1
- Truth table for XOR:
    - A XOR B = 1 if A and B are different
- Half Adder outputs: C = A AND B, S = A XOR B
- Full Adder outputs: S = (A XOR B) XOR C, C = (A AND B) OR (C AND (A XOR B))

Reference Information

- Logic Gates: AND, OR, NOT, XOR
- Karnaugh Maps: Visual tool for simplifying Boolean expressions
- Flip Flops: Used for storing binary data, particularly in memory circuits
- Half Adder: Adds two single-bit numbers, outputs sum and carry
- Full Adder: Adds three bits (two inputs and a carry), outputs sum and carry

Key Terms/Concepts

- **Boolean Logic**: A form of algebra where all values are either TRUE or FALSE, often represented as 1 or 0.
- **Logic Gates**: Electronic devices that perform a basic logical function on one or more binary inputs to produce a single binary output.
- **Karnaugh Map**: A visual method for simplifying Boolean algebra expressions by grouping together terms with common factors.
- **De Morgan's Law**: A pair of transformation rules that relate conjunctions and disjunctions of Boolean variables through negation.
- **Flip Flop**: A digital memory circuit that can maintain a binary state until changed by an input signal.