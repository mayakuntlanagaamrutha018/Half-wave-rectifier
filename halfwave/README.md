# Half-Wave Rectifier using Verilog

## Description

This project implements the basic behavior of a half-wave rectifier using Verilog HDL.

A half-wave rectifier allows the positive half of an input signal to pass through while blocking the negative half.

## Working Principle

If the input voltage is positive:

    Vout = Vin

If the input voltage is zero or negative:

    Vout = 0

## Files

- `half_wave_rectifier.v` - Verilog design
- `half_wave_rectifier_tb.v` - Testbench
- `.gitignore` - Git ignored files

## Example

| Vin | Vout |
|----:|-----:|
| -8  | 0 |
| -4  | 0 |
| 0   | 0 |
| 3   | 3 |
| 6   | 6 |
| 10  | 10 |
| -5  | 0 |

## Applications

- AC to DC conversion concepts
- Power supply circuits
- Signal processing
- Rectifier circuit studies
- Digital modeling of electronic circuits

## Simulation Tools

The project can be simulated using:

- ModelSim
- QuestaSim
- Vivado
- Icarus Verilog
- EDA Playground

