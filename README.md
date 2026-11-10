Digital Comparator 7485 Experiment

Practical electronics lab experiment to build and test a 4-bit digital comparator circuit on a breadboard using the 7485 IC to compare two binary numbers and monitor the logic results through LEDs.

Hardware components:
- Digital IC 7485 (4-bit magnitude comparator)
- DC Power Supply (+5V)
- Breadboard and connection wires
- Three LEDs for output indication (A>B, A=B, A<B)

Circuit wiring steps:
1. Power Connections: Connect the positive DC supply (+5V) to pin 16 (VCC) and the negative/ground to pin 8 (GND) on the breadboard. Cascading inputs (pins 1, 2, and 3) are left unconnected for standalone operation.
2. Binary Inputs: Connect the bits of binary number A to pins 10, 12, 13, and 15 (A0 to A3), and the bits of binary number B to pins 9, 11, 14, and 1 (B0 to B3).
3. Output Indicators: Connect three LEDs to the output pins 5, 6, and 7 representing the comparison conditions (A>B, A=B, and A<B).

Verification:
Test various 4-bit combinations for inputs A and B, and verify the logical comparison states on the LED indicators according to the truth table.
