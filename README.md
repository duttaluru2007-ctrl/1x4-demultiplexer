# 1×4 Demultiplexer using Verilog

## Project Overview

This project implements a **1×4 Demultiplexer** using Verilog HDL. A demultiplexer routes one input signal to one of four output lines depending on the select inputs.

## Truth Table

| Select (S1 S0) | Output |
|---------------|--------|
| 00 | Y0 = D |
| 01 | Y1 = D |
| 10 | Y2 = D |
| 11 | Y3 = D |

## Block Diagram

(Add your block diagram image here.)

## Files

```
src/
    demux_1x4.v

testbench/
    demux_1x4_tb.v

simulation/
    waveform.png
    simulation_output.txt
```

## Simulation

Compile

```bash
iverilog -o demux demux_1x4.v demux_1x4_tb.v
```

Run

```bash
vvp demux
```

Open Waveform

```bash
gtkwave demux_1x4.vcd
```

## Output

When D = 1

| Select | Active Output |
|---------|---------------|
|00|Y0|
|01|Y1|
|10|Y2|
|11|Y3|

## Applications

- Data Routing
- Communication Systems
- Digital Switching
- Processor Design

## Author

Your Name