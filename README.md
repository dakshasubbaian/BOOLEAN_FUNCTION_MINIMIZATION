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

Developed by: DAKSHA SUBBAIAN

RegisterNumber:212223230036

```
module func(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule

module func1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule
```

**RTL realization**

**Output:**

**RTL**
![digi exp 2](https://github.com/user-attachments/assets/e8fef789-ba5e-4383-9599-ca81901efd08)
![digi exp2 ](https://github.com/user-attachments/assets/ca9fe667-91fe-4649-8917-8568195d8539)

**Timing Diagram**
![digi exp 2 3](https://github.com/user-attachments/assets/05eae18b-7a9b-4249-9835-39f9fc659f16)
![digi 2 4](https://github.com/user-attachments/assets/c8b4126b-4c2c-43c9-8a60-7a857a76e8a4)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

