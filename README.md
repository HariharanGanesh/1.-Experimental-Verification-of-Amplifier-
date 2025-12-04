#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1
RF=20Kohm
R1=2kohm

PIN DIAGRAM
![WhatsApp Image 2025-11-30 at 21 49 26_b12472fa](https://github.com/user-attachments/assets/b8bac694-253c-475b-a069-a7ae857bfc42)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-30 at 21 49 27_2d4a234e](https://github.com/user-attachments/assets/1c0f1349-29a1-4911-a34e-2ae82818e191)


MODEL GRAPH 

![WhatsApp Image 2025-11-30 at 21 49 27_466a395f](https://github.com/user-attachments/assets/567475ee-8288-412f-8c90-e44564df1ee0)



DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =20 R1
Choose R1 = 2kΩ, Rf=20kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![WhatsApp Image 2025-11-30 at 21 49 27_7354026d](https://github.com/user-attachments/assets/f347b41f-79d4-459f-aac7-e80bd029111c)

 


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 21 53 27_886f9449](https://github.com/user-attachments/assets/7aa194f5-4e1e-4455-8a25-18737bf1527b)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 21 57 43_a43c968a](https://github.com/user-attachments/assets/f2536c59-c83c-4b32-9bb9-59125f94aca5)




---

## MODEL GRAPH

![WhatsApp Image 2025-11-30 at 21 57 45_dce50754](https://github.com/user-attachments/assets/55f9ba38-be68-49bb-beeb-3b1544932ee1)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![WhatsApp Image 2025-11-30 at 21 57 45_0f8dac86](https://github.com/user-attachments/assets/5967f7a3-d1fc-433d-b824-9972552fa102)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 21 58 02_518c977b](https://github.com/user-attachments/assets/72439c63-e39b-47a0-ada8-ea7fe9b11cb4)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 22 01 31_580f1590](https://github.com/user-attachments/assets/e6e299ca-e1b2-47bb-a15b-098461a81573)

## MODEL GRAPH
![WhatsApp Image 2025-11-30 at 22 01 48_b5d10c84](https://github.com/user-attachments/assets/18c83b6c-f8bc-461f-9209-7acf69663efb)


---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 1
⇒  Rf = 20R1   
Choose  R1 = 20kOhm, Rf = 20kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-30 at 22 02 36_412bdebd](https://github.com/user-attachments/assets/4244b4ba-56b8-405d-bf29-f30a954683ae)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 22 03 41_443abf57](https://github.com/user-attachments/assets/7c66f1ae-be1a-48e8-b8c6-115f4dad673d)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-11-30 at 22 05 34_70190d3d](https://github.com/user-attachments/assets/876541fb-44ba-4350-983b-49a940e4927f)

## MODEL GRAPH
![WhatsApp Image 2025-11-30 at 22 06 23_3a730131](https://github.com/user-attachments/assets/88cc0039-7f85-4700-a520-51d767b2550a)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

![WhatsApp Image 2025-11-30 at 22 06 05_036ff1c8](https://github.com/user-attachments/assets/47b0d4bc-34f0-4309-9e66-78f5d45611c5)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 22 07 04_0c0f08eb](https://github.com/user-attachments/assets/9c616364-7706-466d-a52e-e6f0ca21ebeb)

## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
