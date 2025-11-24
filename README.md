# BOOLEAN_FUNCTION_MINIMIZATION

Name: Kanishka G

Reference number:25011903

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

i) 

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)

module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


**RTL realization**

**Output:**
<img width="760" height="437" alt="Screenshot 2025-11-23 123853" src="https://github.com/user-attachments/assets/9bd169fe-96fa-4ebe-9879-f498a3f7c4eb" />


**RTL**
![ex2](https://github.com/user-attachments/assets/d069b760-c223-4ff5-93e3-1d53d6f63b04)
![ex2 2](https://github.com/user-attachments/assets/9a06547c-364d-449a-8a57-8eb0945e365e)



**Timing Diagram**
![waveform2](https://github.com/user-attachments/assets/a1c545b1-071f-43d3-93c5-782de8d02331)
![waveform2 2](https://github.com/user-attachments/assets/b0590f37-bdc8-4930-a1d8-c19a9d7bf006)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

