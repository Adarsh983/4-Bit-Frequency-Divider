# 4-Bit Frequency Divider

## Introduction

This repository contains the Verilog implementation of a Frequency Divider Circuit, which can divide the frequency of an input signal by any 4-bit number. The Frequency Divider Circuit is a fundamental digital circuit used in various applications, including clock generation, data processing, and communication systems.

## How It Works

The Frequency Divider Circuit takes an input signal with a certain frequency and divides it by the value represented by a 4-bit number. The circuit uses Verilog hardware description language (HDL) to specify the functionality and behavior of the circuit.

The basic principle of operation is to count the number of input signal cycles and generate an output pulse after a specific number of cycles as determined by the 4-bit number. For instance, if the 4-bit number is 'n', the output pulse will occur after every 'n' cycles of the input signal, effectively reducing the output frequency by a factor of 'n'.

![image](https://github.com/Adarsh983/4-Bit-Frequency-Divider/assets/98532282/f50295f1-974c-4d89-946a-63c02aa1d310)
![image](https://github.com/Adarsh983/4-Bit-Frequency-Divider/assets/98532282/352c2124-a1bf-424f-99b2-95d6002d55f0)
<div align="center"><h6>Circuit simulation for n = 2 and n = 3 respectively</h6></div>



## File Description

<div>frequencydivider.v : Contains the design implementation of the circuit.</div>
testbench.v : Contains the testbench for the implemented design.

