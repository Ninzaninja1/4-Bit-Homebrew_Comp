# 4-Bit-Homebrew_Comp
A Homebrew computer built mainly using only the fundamental logic gates. This is a 4-Bit computer using the SAP-1 architecture.

I am using the application Digital by hneemann ([link](https://github.com/hneemann/Digital)) to simulate the computer.

## Progress
Here are some screenshots of the progress:

- RAM Module, consisting of RAM, MAR and MDR:

![Github Image](src/RAM_Module_IC.png)

- ALU Simple:

![Github Image](src/ALU_IC_Simple.png)

- ALU from just logic gates:

![Github Image](src/ALU_IC.png)

- Full Assembly using ICs:
    - Combining all the work together and put in into 1 file with the control unit. I replaced all the combinational logic with EEEPROMS instead which made it all very neat and easy to change.

![Github Image](src/Full_Assembly_IC.png) 

## Logic gates
Here are the preliminary designs made from logic gates, which give a better understanding of what is actually happening behing all the ICs:

- ALU with 4 Full adders with the ability of outputing the Zero, Negative and Overflow flags 

![Github Image](src/ALU_Logic_Gates.png)

- A Binary Counter. This can also load a specific number if needed

![Github Image](src/Binary_Counter_w_Load.png)

- The complete RAM Module (RAM, MDR & Mar) which uses the 74LS189 Chip

![Github Image](src/RAM_Module_Logic_Gates.png)
