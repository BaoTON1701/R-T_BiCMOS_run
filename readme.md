# R&T BiCMOS Run 2

<div align="left">
  <img src="image/logo/RetT.PNG" width="200" />
</div>

Description: The development of this circuit is part of a broader R&D effort. With this specific LNA design, we aimed to optimize the performance of a low-noise amplifier intended for cryogenic operation (77 K). The optimization focused on reducing both white and flicker noise, mainly by adjusting the transistor dimensions and bias current. A low-frequency noise level down to $1 nV/ \sqrt{Hz}$ at frequencies as low as 1 Hz is targeted.
At the same time, the amplifier must cover a bandwidth greater than 10 MHz, provide a voltage gain of approximately 100 V/V, and feature both DC-coupled input and output stages. The thermal drift of the gain is also addressed by using a proportional-to-temperature current source ($ I_C \propto$ T) to compensate for the intrinsic inverse temperature dependence of the voltage gain ($\propto g_m=qIc/kT$).

## Schematic 

### Block diagram 
<div align="center">
  <img src="image/schema/block_dia.png" width="500" />
</div>

### LNA Schematic 
<div align="center">
  <img src="image/schema/LNA.png" width="500" />
</div>

## Layout 
<div align="center">
  <img src="image/layout/full_layout.png" width="500" />
</div>

Technology: IHP130 SG13S 

Die size (Length in µm x Wide in µm):   1264 μm × 913 μm 
## Data sheet 

### 1. Gain 

<table>
  <tr>
    <td> <img src="image/plot/gain.png"  alt="1" width = 400px ></td>
    <td> <img src="image/plot/Gain_drift.png" alt="2" width = 400px ></td>
  </tr>
</table>

### 2. Input referred Noise

<div align="center">
  <img src="image/plot/Input_Referred_Noise.png" width="400" />
</div>

## Packaging 
For packaging this ASIC, we are going to use the QFN24 
<div align="center">
  <img src="image/packaging/BondingR&TRun2.PNG" width="300" />
</div>


