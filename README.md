# BOOLEAN_FUNCTION_MINIMIZATION

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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Abishek.P.V 
RegisterNumber: 212222230003


```
library IEEE;
use IEEE.STD_LOGIC_1164.ALL;

entity booleanexp is 
    Port ( INO1 : in STD_LOGIC;    --- OR gate input
	        INO2 : in STD_LOGIC;    --- OR gate input
			  OO  : out STD_LOGIC);   --- OR gate output
end booleanexp;

architecture Behavioral of booleanexp is 
begin
OO <= INO1 or INO2;   --- 2 input OR gate
end Behavioral;
```
![Screenshot 2024-04-04 085332](https://github.com/pvabishek/BOOLEAN_FUNCTION_MINIMIZATION/assets/119405626/6ba5f68f-199a-4214-bd94-6f2cee090184)


**RTL realization**
![Screenshot 2024-04-04 085416](https://github.com/pvabishek/BOOLEAN_FUNCTION_MINIMIZATION/assets/119405626/2cfc9458-aa6c-45ab-ae47-a764c0d049da)

**Output:**
![Screenshot 2024-04-04 085437](https://github.com/pvabishek/BOOLEAN_FUNCTION_MINIMIZATION/assets/119405626/8f6aa7d6-7c17-431c-b474-5ea85ffdbf22)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

