# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

1.Open Quartus II and create a new project wizard.

2.Create a Verilog HDL file and enter the JK Flip-Flop code.

3.Click Compile to check for errors and build the design.

4.Go to Tools > Netlist Viewers > RTL Viewer to view and save the RTL schematic.

5.Create a Vector Waveform File (.vwf) via File > New > University Program VWF.

6.Add input/output nodes using Node finder.

7.Apply different input combinations (J, K, Clock) in the waveform.

8.Run Simulation from Processing.

9.View and save the timing diagram showing the JK flip-flop behavior.

**PROGRAM**

![image](https://github.com/user-attachments/assets/0bb0415b-7421-40aa-ba9b-aa66997069d9)


/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: Dharshana A S RegisterNumber:212224220022
*/

**RTL LOGIC FOR FLIPFLOPS**

![image](https://github.com/user-attachments/assets/290a6fcb-a506-4896-a636-7207ce37b432)


**TIMING DIGRAMS FOR FLIP FLOPS**

![image](https://github.com/user-attachments/assets/5eda83e0-1da8-43a8-9a37-fea920e1c512)

**RESULTS**

Thus the JK flipflop using verilog and validating their functionality using their functional tables is implemented
