---
id: 18dec6ce-6434-4067-bf3e-e37b20828075
title: '2020-09-10'
desc: ''
updated: 1599707783063
created: 1599707783063
stub: false
---

# Circuit Analysis
![](/assets/images/2020-09-10-11-18-53.png)
1. Check the resistance for ratio 
   - example: 8Ω -> 8V per ampere [[ Ohm's Law | a.phy.current-electricity.ohm's-law]]
2. How much voltage it gained from the battery (All? Partial?)
3. How much current flow through it has been caused by the voltage?
   
## Examples
![](/assets/images/2020-09-10-11-22-31.png)
    - In series circuit, see all resistors as one, **Current in any place are the same**
    - so 20Ω + 30Ω = 50Ω
    - 50Ω means 50V will cause 1A of current
      - **Hence, 10V (given) will cause 1/5A = 0.2A current flowing**
![](/assets/images/2020-09-10-11-24-21.png)
  - For $R_1$
    -  $V = I_1 R_1 = 0.2 times 20 = 4V$
  -  For $R_2$
     -  30V/1A
     -  ?V ($30 times \frac{1}{5} = 6V$)
     -  0.2A
  -  V1 + V2 = 6V + 4V = 10V = V

## Effective Resistance ($R_ef)
    - same with **Equivalent Resistance** 
    - Irrelevant if it is connected to any source
    - Seen by the battery
   - Calculation 
     - **Voltage of the battery /  total Current flows out from battery** 
        - R = V/I  [[Ohm's Law | a.phy.current-electricity.ohm's-law]]

## Current in a Parallel Circuit
![](/assets/images/2020-09-10-11-31-13.png)
    - R1
      - 3V/A = 3Ω
      - 12V (all voltage from battery) given, hence **4A** produced
    - R2
      - 6V/A = 6Ω
      - 12 V 
      - ==> **2A**
    - Total Resistance?
      - $V_{battery}$
      - How many amperes flowed?
        - 4A + 2A = 6A
        - 12V/6A = 2Ω ($R_eff$)
 ![](/assets/images/2020-09-10-11-35-01.png)
    - Power of R1?
      - V * I = 12V * 4A = 48 W 
    -  $P_{R_2}$
        - V * I = 12V * 2A = 24W
   - Battery?
     - P = 12V * 6A = 72W
    - Energy spent in 30s?
      - R1  
        - 48W * 30s = 1440J
      - R2
        - 24W * 30s = 720J
      - Battery?
        - 72W * 30s = 2160J
- **Effective Resistance won't change even the voltage of the battery changes**
  
## Faster Way?
![](/assets/images/2020-09-10-11-43-04.png)
![](/assets/images/2020-09-10-11-44-17.png)
Since We know I, I1 and I2,
    - By Applying Ohm's law, $I = \frac{V}{R}$
    - and **$\frac{1}{R_{eff}} = \frac{1}{R_1} + \frac{1}{R_2}$**

### Example 1: Series Circuit
![](/assets/images/2020-09-10-11-49-44.png)

### Example 2: Parallel Circuit
![](/assets/images/2020-09-10-11-51-50.png)
![](/assets/images/2020-09-10-11-55-44.png)
![](/assets/images/2020-09-10-11-55-55.png)
![](/assets/images/2020-09-10-11-56-06.png)