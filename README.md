ECE281_CE2
==========


#Schematic Waveform

![](https://github.com/C16erikthompson/ECE281_CE2/blob/master/CE2Waveform.png?raw=true)

#Behavioral Waveform

![](https://github.com/C16erikthompson/ECE281_CE2/blob/master/CE2Waveform_Behavioral.png?raw=true)

# Truth Table  

| EN | I1 | I0 | Y0 | Y1 | Y2 | Y3
|---|:-:|:-:|:-:|:-:|:-:|--:
| 0 | 0 | 0 | 0 | 0 | 0 | 0  
| 0 | 0 | 1 | 0 | 0 | 0 | 0 
| 0 | 1 | 0 | 0 | 0 | 0 | 0 
| 0 | 1 | 1 | 0 | 0 | 0 | 0 
| 1 | 0 | 0 | 1 | 0 | 0 | 0  
| 1 | 0 | 1 | 0 | 1 | 0 | 0  
| 1 | 1 | 0 | 0 | 0 | 1 | 0  
| 1 | 1 | 1 | 0 | 0 | 0 | 1 

# Analysis And Comments

- The simulation results for the structural and behavioral code were identical, represented by the singular truth table
- None of the outputs read high until the EN input is high
- Only one output is high at any time after EN is high (order: Y0, Y1, Y2, Y3)
- Outputs determined by the four possible combination of I0 and I1
- Decoder translates input data into its original form
