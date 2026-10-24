Digital Comparator 7485 Experiment

A practical electronics laboratory experiment designed to perform logical comparisons (A > B, A = B, A < B) between two 4-bit binary numbers using the 7485 magnitude comparator IC[span_0](start_span)[span_0](end_span).

Components and hardware used:
- Digital IC: 7485 4-Bit Magnitude Comparator (16-pin DIP)[span_1](start_span)[span_1](end_span)
- Breadboard: Pin-type educational testing board[span_2](start_span)[span_2](end_span)
- Output Indicators: 3 LEDs for comparison outputs (A>B, A=B, A<B)[span_3](start_span)[span_3](end_span)
- Power Supply: DC Power Supply (5V Vcc)[span_4](start_span)[span_4](end_span)
- Wiring: Jumper wires[span_5](start_span)[span_5](end_span)

Circuit connections and pinout:
- Pin 16 (Vcc): Connected to the positive DC power supply (+5V)[span_6](start_span)[span_6](end_span)
- Pin 8 (GND): Connected to the negative/ground terminal[span_7](start_span)[span_7](end_span)
- Inputs (A and B 4-bit numbers):
  * Input values for A connected to pins 10, 12, 13, 15 (A0 to A3)[span_8](start_span)[span_8](end_span)
  * Input values for B connected to pins 9, 11, 14, 1 (B0 to B3)[span_9](start_span)[span_9](end_span)
- Outputs: Connected to pins 5, 6, 7 (A>B, A=B, A<B) to drive LED indicators[span_10](start_span)[span_10](end_span)
- Cascading Inputs: Pins 2, 3, 4 (I_A<B, I_A=B, I_A>B) left unconnected for standalone operation[span_11](start_span)[span_11](end_span)

Logic Verification and Operation:
The 4-bit magnitude comparator evaluates binary inputs A and B and activates the corresponding output LED to verify whether number A is greater than, less than, or equal to number B[span_12](start_span)[span_12](end_span).