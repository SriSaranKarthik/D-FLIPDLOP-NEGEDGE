# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**TRUTH TABLE**

![image](https://github.com/user-attachments/assets/e24deda2-6384-4885-8e3f-0e850763cc09)

**Procedure**

/* 1.Type the program in Quartus software using Verilog to implement the D flip-flop with negative edge-triggered clock.

2.Compile and run the program to ensure there are no syntax errors.

3.Generate the RTL schematic and save the logic diagram for documentation.

4.Create nodes for inputs (D, clk) and outputs (Q, Q_bar) in the simulation tool.

5.Simulate the design to generate the timing diagram for different input combinations.
 */

**PROGRAM**

![image](https://github.com/user-attachments/assets/837c45e2-bf8d-41c6-8666-f7f08a663085)

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:K.SriSaran Karthik RegisterNumber:24007192
*/

**RTL LOGIC FOR FLIPFLOPS**

![image](https://github.com/user-attachments/assets/fd58c033-bc43-44a1-96ea-191cacf7b974)


**TIMING DIGRAMS FOR FLIP FLOPS**

![image](https://github.com/user-attachments/assets/83144fc2-f269-4811-8775-f2cde6b8520c)

**RESULTS**

Thus, the D Flip-Flop with negative edge triggering is designed, and its functionality is validated using the truth table and timing diagrams.
