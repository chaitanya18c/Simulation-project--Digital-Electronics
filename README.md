# TITTLE

# THEORY
Verilog allows designers to describe the behavior and structure of digital circuits, 
making it easier to design,
simulate, and verify complex digital systems.
It enables engineers to specify the functionality and interconnections of various hardware components, 
such as logic gates, flip-flops, registers, and memories, which collectively form digital systems like microprocessors, ASICs (Application-Specific Integrated Circuits), FPGAs (Field-Programmable Gate Arrays), and other electronic systems.

# LOGIC DIAGRAM
![WhatsApp Image 2023-06-15 at 20 23 03](https://github.com/chaitanya18c/Simulation-project--Digital-Electronics/assets/119392724/0ab188c9-2088-4e02-80a0-c23d5609bb8c)

# NETLIST DIAGRAM
![WhatsApp Image 2023-06-15 at 20 23 03](https://github.com/chaitanya18c/Simulation-project--Digital-Electronics/assets/119392724/5b7f5753-117b-4e19-bd53-5a21337f7db8)

# TIMING DIAGRAM


# PROGRAM
```
module skill_2 (a, b, c, T1, T2);
input a,b,c;
output T1, T2;
wire adash, bdash, cdash, x, y, z;
not (adash, a); not (bdash, b);
not (cdash, c);
and (x, adash,bdash);
and (y, adash, cdash); or (T1,x,y);
and (z,b,c);
or (T2, a, z);
endmodule
```
# REFERENCE
