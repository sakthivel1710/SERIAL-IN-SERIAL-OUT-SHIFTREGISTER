# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**
<img width="464" height="503" alt="Screenshot 2025-10-16 165743" src="https://github.com/user-attachments/assets/6344b775-e2b3-4bb0-9fa2-405829c216ec" />


/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:

*/

**RTL LOGIC FOR SISO Shift Register**
<img width="872" height="507" alt="Screenshot 2025-10-16 165837" src="https://github.com/user-attachments/assets/07ccfded-7843-4008-a281-45a93b01f2e3" />


**TIMING DIGRAMS FOR SISO Shift Register**
<img width="803" height="450" alt="Screenshot 2025-10-16 165901" src="https://github.com/user-attachments/assets/fa5b9a48-0087-4eb3-b41b-0bf075c406ae" />



**RESULTS**
thus the basic logic gates are studies and the truth tables are verified
