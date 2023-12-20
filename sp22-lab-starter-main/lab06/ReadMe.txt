************************************************************************************************
For Lab_06_Exercise2
There are 6 branch instructions, including beq, bge, bgeu, blt, bltu and bne.Among them, bge and blt are uesd for signed numbers, bgeu and bltu are used for unsigned numbers.
They have the same opcode , but the funct3 are different

instruction--Funct3--object--output
beq--000--all--random
bne--001--all--random
blt--100--signed--0
bge--101--signed--0
bltu--110--unsigned--1
bgeu--111--unsigned--1

So if funct3 is not greater than 101(5),just output 0.


************************************************************************************************
For Lab_06_Exercise_3
You can read the slides of lecture 11 first.

critical path: the minimum clock cycle time.
Min clock cycle = The time it takes for the input of one state element to reach the input of the next state element.
clk-to-q delay + longest combinational delay + setup time

Here is my solution.
1)the propagation delay of an adder block is 45ns;
2)the propagation delay of a multiplication is 60ns;
3)register CLK-to-Q delay is 10ns;
4)setup time is 10ns;
5)hold time is 5ns(useless);

the minimum clocl cycle time = 1) + 2) + 3) + 4) = 45 + 60 + 10 + 10 = 125ns 
