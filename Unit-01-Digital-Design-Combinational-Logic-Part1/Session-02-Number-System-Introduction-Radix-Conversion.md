# Session 02: Number System Introduction & Radix Conversion

## Learning Outcomes
- Understand the different types of number systems.
- Learn how to convert between various number systems.
- Gain insights into practical applications of number systems in digital design.

## Introduction
In this session, we will explore the concept of number systems, which forms the foundation of digital design. Number systems are essential as they represent data in a form that a digital system can process.

## Types of Number Systems
1. **Decimal (Base 10)**: The standard system used by humans, utilizing digits from 0 to 9.
2. **Binary (Base 2)**: The fundamental number system used by computers, consisting of only 0 and 1.
3. **Octal (Base 8)**: Uses digits from 0 to 7. Each octal digit represents three binary digits (bits).
4. **Hexadecimal (Base 16)**: Uses digits from 0 to 9 and letters A to F. Each hexadecimal digit represents four binary digits.

## Radix Conversion
### Decimal to Binary
- Method: Repeated division by 2.
- Example: Decimal 10 to Binary
  - 10 / 2 = 5 remainder 0
  - 5 / 2 = 2 remainder 1
  - 2 / 2 = 1 remainder 0
  - 1 / 2 = 0 remainder 1
  - **Binary: 1010**

### Binary to Decimal
- Method: Summation of powers of 2.
- Example: Binary 1010 to Decimal
  - (1 × 2^3) + (0 × 2^2) + (1 × 2^1) + (0 × 2^0) = 8 + 0 + 2 + 0 = **10**

### Decimal to Octal
### Octal to Decimal
### Decimal to Hexadecimal
### Hexadecimal to Decimal

| **Conversion**         | **Method**                    | **Example**                     |
|------------------------|-------------------------------|---------------------------------|
| Decimal to Binary      | Repeated division by 2        | 10 -> 1010                      |
| Binary to Decimal      | Summation of powers of 2      | 1010 -> 10                      |
| Decimal to Octal      | Repeated division by 8        | 10 -> 12                       |
| Octal to Decimal       | Summation of powers of 8      | 12 -> 10                       |
| Decimal to Hexadecimal | Repeated division by 16       | 10 -> A                        |
| Hexadecimal to Decimal | Summation of powers of 16     | A -> 10                         |

## Common Mistakes
- Confusing binary and decimal values.
- Forgetting place value in conversions.
- Misapplying the conversion methods.

## Practice Problems
1. Convert the decimal number 25 to binary.
2. Convert the binary number 11011 to decimal.
3. Convert the octal number 17 to decimal.
4. Convert the hexadecimal number 1F to decimal.

## Verification Methods
- Check conversions by re-converting to the original system.
- Use tools and calculators for complex numbers.

## Real-World Applications
- Number systems are used in programming, digital circuits, and data representation.
- Understanding these systems is crucial for designing efficient algorithms and digital systems that interact with computers.

---
### Original Detailed Examples
#### Example 1: Conversion of 5.75 from Decimal to Binary
5.75 is split into the integer and fractional parts. The integer part (5) converts to binary (101), and the fractional part (.75) converts by multiplying by 2 and taking whole numbers.

#### Example 2: Binary Arithmetic
Understanding binary arithmetic is crucial for computer operations. Operations like addition, subtraction, and multiplication are performed differently compared to decimal due to the binary system's limitations.