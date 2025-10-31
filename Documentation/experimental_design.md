# Experimental Design & Process

## Summary
The circuit should generate a parity bit (green LED indicator) when the number of bits active in the circuit is odd.

## Theoretical Truth Table for Parity Generator
| Input A | Input B | Output AB | Input C | Output ABC |
| :-----: | :-----: | :-------: | :-----: | :--------: |
| 0 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 0 | 1 | 1 | 0 | 1 |
| 0 | 0 | 0 | 1 | 1 |
| 1 | 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 | 0 |
| 0 | 1 | 1 | 1 | 0 |
| 1 | 1 | 0 | 1 | 1 |

## Circuit Logic Diagram
<img src="../Media/circuit%20configuration.png" alt="Circuit Logic Diagram" width="600">

## Simulated Breadboard (TinkerCAD)
<img src="../Media/Final%20Project%20-%203Bit%20Even%20Parity%20Generator.png" alt="TinkerCAD Simulation" width="800">

## Breadboard Documentation
<img src="../Media/Annotated%20Breadboards.png" alt="Annotated Breadboard" width="800">

## Example with Generated Bit
<img src="../Media/Example%20of%20Odd.jpg" alt="Circuit w/ LED ON" width="600">

## Example without Generated Bit
<img src="../Media/Example%20of%20Even.jpg" alt="Circuit w/ LED OFF" width="600">

### References
Anjana. (2013). Even and Odd Parity Generator and Checker using the Reversible logic
gates. International Journal of Computer Science and Engineering Communications,
1(1), 62–66.

Farinella, D. (2024, December 3). RF Shielding: Everything You Need to Know. E􀆯ective RF
Shielding Materials: Guide to EMI/RFI Shields. https://www.e-fab.com/whatmaterials-
are-best-for-rf-shields/

Virtual Labs. (n.d.). Even/Odd Parity Generator. https://ade-iitr.vlabs.ac.in/exp/paritygenerator/
theory.html
