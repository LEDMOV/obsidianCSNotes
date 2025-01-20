[[!4.1 Data Types]]

Key Data Types

|Data Type|Description|Examples|
|---|---|---|
|Integer|Represents whole numbers, both positive and negative|10, -5, 0|
|Real|Represents numbers with fractional parts|3.14, -2.5, 0.0|
|Char|Represents a single character|'a', 'B', '5', '$'|
|String|Represents a sequence of characters|"Hello World", "1234", "@#$%"|
|Boolean|Represents true or false values|True, False|

Key Operations

- **Casting**: The process of converting one data type to another, essential for performing operations on user input that is often in string format.
- **Binary Addition**: The process of summing binary numbers, where carrying over occurs when the sum exceeds 1.
- **Binary Subtraction**: Can be performed using two's complement to handle negative numbers.

Key Representations

|Representation|Description|
|---|---|
|ASCII|A character encoding standard using 7-bits to represent 128 characters, primarily for English.|
|UNICODE|A character encoding standard that can use up to 32-bits, allowing for a wide variety of characters from different languages and scripts.|

Key Concepts in Floating Point

- **Mantissa**: The significant digits of a floating-point number.
- **Exponent**: The power of 2 by which the mantissa is multiplied.
- **Normalisation**: The process of adjusting the mantissa and exponent to ensure the floating-point number is in a standard format.

Facts to Memorize

- ASCII uses 7-bits to encode each character, providing for 128 distinct characters.
- Unicode can use up to 32-bits, allowing for a wide variety of characters from different languages and scripts.
- The maximum value of an 8-bit signed binary number is 127, and the minimum is -128.
- The hexadecimal system (base-16) consists of 10 digits (0-9) and 6 letters (A-F).
- The two's complement method is used for representing negative binary numbers.

Reference Information

- ASCII Table: A reference for character encoding in ASCII.
- Hexadecimal Lookup Table: A quick reference for converting numbers between denary, binary, and hexadecimal values.
- Binary to Denary Conversion Method: A systematic approach to convert binary numbers to denary.
- Denary to Binary Conversion Method: A systematic approach to convert denary numbers to binary.

Concept Comparisons

|Concept|ASCII|Unicode|
|---|---|---|
|Encoding System|7-Bits|16-bits or 32-bits|
|Number of Characters|128 characters|65,536 characters (16-bit)|
|Uses|Represents characters in the English language.|Represents characters across the world.|
|Benefits|More storage-efficient.|Can represent more characters, including emojis.|
|Drawbacks|Limited to 128 characters.|Uses more storage space than ASCII.|

Problem-Solving Steps

##### Converting Denary to Binary

1. Write out the binary number system (128, 64, 32, 16, 8, 4, 2, 1).
2. Start from the left and find the highest number less than or equal to the denary number.
3. Place a '1' in that column and subtract the value from the denary number.
4. Repeat until the denary number is reduced to zero, filling in '0's for columns not used.

##### Converting Binary to Denary

1. Write down the binary number.
2. Assign powers of 2 to each bit from right to left (2^0, 2^1, 2^2, ...).
3. For each '1' in the binary number, add the corresponding power of 2 to get the denary value.