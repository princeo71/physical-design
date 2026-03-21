# Session 1: Introduction to Digital System

## Topics Covered
- Definition of digital system and comparison with analog system  
- Binary digits (bits), logic levels (0 and 1), voltage ranges  
- Basic logic gates: AND, OR, NOT, NAND, NOR, XOR, XNOR  
- Truth tables and logic symbols for basic gates  
- Real‑life examples of digital systems (calculators, microcontrollers, FPGAs, etc.)

## Key Concepts
- A digital system processes information using discrete levels (usually 0 and 1).  
- Logic gates are the basic building blocks used to implement Boolean functions.  
- Each gate has a symbol, a truth table, and an equivalent Boolean expression.  
- Combinational logic outputs depend only on current inputs (no memory).  
- Advantages of digital systems: noise immunity, easy storage, programmability, scalability.

## Notes
- Logic 0 and logic 1 are **logical** levels; actual voltage ranges depend on the technology (CMOS, TTL, etc.).  
- Basic gates can be combined to realize any complex Boolean function.  
- NAND and NOR are universal gates, meaning any logic circuit can be built using only NAND or only NOR.  
- Pay attention to active‑high vs active‑low signals when reading circuit diagrams.  
- For study, always write the truth table first before simplifying expressions.

## Examples
- Example 1:  
  Design a 2‑input AND gate truth table and Boolean expression.  
  Inputs: A, B; Output: Y  
  Truth table:  
  - A=0, B=0 → Y=0  
  - A=0, B=1 → Y=0  
  - A=1, B=0 → Y=0  
  - A=1, B=1 → Y=1  
  Boolean expression: Y = A · B

- Example 2:  
  Construct the truth table for a 2‑input XOR gate and describe when the output is 1.  
  Output is 1 when inputs are different (A ≠ B).




