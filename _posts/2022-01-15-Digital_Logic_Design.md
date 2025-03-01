---
title : Digital Logic Design
tags : Digital_Logic
---
## 수강 과목
ELEC247 Logic_Circuits    
COMP311 Logic_Circuit_Design

## Reference
[IT CookBook, 디지털 논리회로(개정3판) : 이론, 실습, 시뮬레이션](https://www.hanbit.co.kr/store/books/look.php?p_code=B4026954710)

## 논리회로 이론
### Binary Code
- **BCD Code (8421 Code)** : Only use 4 bits to represent each digit.
- **Excess-3 Code** : BCD Code + 0011<sub>(2)</sub>
- **Gray Code** : Two successive values differ in only one bit. (Used in Rotary Encoder)

### [Logic Gates]({% link _posts/2022-01-16-Logic_Gate.md %})
- AND
- OR
- NOT
- NAND
- NOR
- XOR & XNOR

### [IC Performance Parameter]({% link _posts/2022-01-16-Performance_Parameter.md %})
- Propagation Delay Time
- Power Dissipation
- Noise Immunity
- fan-in / fan-out

### Boolean Expression
- minterm 
- maxterm
- SOP(Sum Of Product)
- POS(Product of Sum)

### Gate-Level Minimization
- Karnaugh Map
- Quine-McCluskey algorithm
- Universal Gates(NAND, NOR)

### Combinational Logic Gates
- Adder
- Comparator
- Decoder
- Encoder
- Multiplexer
- Demultiplexer

### Flip Flop
- SR F/F
- D F/F
- JK F/F
- T F/F

### Sequential Logic Gates Design
- State Table
- State Equation
- Excitation Table

### Register
- Shift Register

### Counter
- Async Counter
- Sync Counter
- Ripple Counter
- Ring Counter
- Johnson Counter

### Memory and Programmable Device
- RAM
- ROM
- PLA
- PAL
- FPGA
