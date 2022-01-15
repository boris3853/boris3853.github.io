---
title: IC Performance Parameter
tags: Digital Logic
---
- [SN7303 NAND Gates IC](https://www.ti.com/lit/ds/symlink/sn54ls03.pdf?ts=1640783174878&ref_url=https%253A%252F%252Fen.wikipedia.org%252F)

## 1. Propagation Delay Time
- length of time taken for input change to reach to the output
- **t<sub>PHL</sub>** : propogation delay time when output change to H to L
- **t<sub>PLH</sub>** : propogation delay time when output change to L to H

![image](https://user-images.githubusercontent.com/60434800/147748814-7fef782f-f7fc-47d8-b52e-888677d18049.png)

- On the example, Average t<sub>PLH</sub> = 5ns & t<sub>PHL</sub> = 4.5ns ( When R<sub>L</sub> = 280Ω, C<sub>L</sub> = 15pF )

## 2. Power Dissipation
- Amount of power needed to operate IC</br>

![image](https://user-images.githubusercontent.com/60434800/147751153-bec7906c-cb92-4671-a170-13628e02a2c2.png)
- On the example, Average I<sub>CCH</sub> = 4mA, I<sub>CCL</sub> = 12mA
  - I<sub>CC</sub> =  (I<sub>CCH</sub> + I<sub>CCL</sub>) / 2 = 8mA
  - P = V<sub>CC</sub> * I<sub>CC</sub> = 5V * 8mA = 40mW

## 3. Noise Immunity 
- Measure of Noise Margin
- **Noise Margin** : amount of threshold which can discrete proper signal
  - V<sub>NH</sub> = V<sub>OH</sub>(min) - V<sub>IH</sub>(min)
  - V<sub>NL</sub> = V<sub>OL</sub>(max) - V<sub>IL</sub>(max)


## 4. fan-in / fan-out
- **fan-in** :The number of inputs that single logic gate can handle
- **fan-out** :The number of outputs driven by output of another single logic gate
  - fan-out = min((I<sub>OH</sub>(max) / I<sub>IH</sub>(max) , (I<sub>OL</sub>(max) / I<sub>IL</sub>(max))

## 5. Sink-Current / Source Current

## 6. Pull-up Resistor / Pull-down Resistor

