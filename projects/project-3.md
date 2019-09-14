---
layout: project
type: project
image: images/vhdl.PNG
title: Single Stage LegV8 CPU
permalink: projects/LegV8
# All dates must be YYYY-MM-DD format!
date: 2014-04-12
labels:
  - Verilog
  - LegV8
  - FPGA
summary: Building a simple single stage legv8 CPU in Verilog.
---

## Introduction

This project was my attempt at building a single stage legv8 CPU using Verilog. Verilog is a hardware description language (HDL) used to model electronic systems. In this project we were given a diagram of a LegV8 CPU, a short program, and some small modules such as a mux that was prebuilt to build a CPU capable of decoding the instruction and performing operations similar to a CPU. Our instructor provided some simple examples on how to build a memory module, verilog examples, and other various material to complete our task.

## Building the CPU
 
By completing this project helped me better understand how a CPU works, deep down inside its register and gates. It gave me a deep look into how programs are translated into opcodes and register data which all take different paths inside a CPU depending on the operation, one step at a time. First, we will be using verilog to build our CPU. Since our topic did not cover examples of branch prediction nor did we have much time to complete a pipeline CPU, our CPU only operated in single strage, that is a single instruction is ran through the entire path which took about 4 clock cycles to complete.

## Result
 
This project has helped me understand the hardware side of computer engineering, as learning how FPGA function using verilog. verilog is also very different from how computer programs works, as verilog describe hardware and thus doesn’t run the code line by line, rather describe and map how the FPGA will act.
 
Source: https://www.edaplayground.com/x/3uC3


