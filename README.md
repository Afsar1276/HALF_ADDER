# HALF_ADDER
# AIM:
To simulate and synthesis half adder using vivado.
# APPARATUS REQUIRED:
vivado 2023.2 software.
# PROCEDURE:
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)
# VERILOG CODE:
# HALF_ADDER:
```
module HalfAdder(a,b,sum, carry);
input a,b;
output sum, carry;
xor (sun,a,b);
and (carry,a,b);
endmodule
```
# OUTPUT:
[image]![WhatsApp Image 2024-03-25 at 14 00 13_29a21409](https://github.com/Afsar1276/HALF_ADDER/assets/161407741/e1c44850-59d2-40e7-b2fb-f9c8defbcd8d)
# RESULT:
Thus the verilog program for half adder has been simulated and verified successfully.
