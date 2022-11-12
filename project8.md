# MIPS CPU Design
## Intro
---
This project is a class project of **CSCI-2500 Computer Organization** @ RPI.\
Yuxin was working alone on this project.

## Problem Overview
---
This project aimed at designing a modern 32 bit CPU that operates on MIPS operation codes. It supports operations including *ADD, ADDI, SUB, SUBI, SW, LW, AND, OR, BEQ, SLT, J, JAL, JR*. The system structure is shown below.
<img src="/project8/Datapath.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
The CPU was simulated in C code, but the whole system contains only ***and, or, not gates***. Thus it is possible to build it physically.

## Some Design Details

### Control
<img src="/project8/Control.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
The gate above shows the implementation of *Jump*. We want to output `TRUE` if
and only if the Op Code is `000010` or `000011`, but not `000000`. Using K-map,
we can easily find that `Jump = not(5)*not(4)*not(3)*not(2)*or(1, 0)`. More commands are shown in the table below.
<img src="/project8/controlbits.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">

### ALU
The ALU handle the operations including *ADD, SUB, AND, OR, SLT*.
<img src="/project8/ALUControl.png" style="width:50%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
Using the similar approach, the circuit can be constructed.
<img src="/project8/ALU.png" style="width:100%;align-items: center;margin-left: auto;margin-right: auto;display: block;">
