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

## PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

## CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="779" height="440" alt="image" src="https://github.com/user-attachments/assets/a14d8bc1-9dc7-4a49-98b0-f5320f450a63" />

## CIRCUIT DIAGRAM:
<img width="1246" height="995" alt="image" src="https://github.com/user-attachments/assets/81e96bf7-3fad-4b42-90c4-f039260bb15d" />

## MODEL GRAPH 
<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



## DESIGN AND ANALYSIS:
<img width="1280" height="598" alt="image" src="https://github.com/user-attachments/assets/9553152c-f5f7-40ff-afa0-eebbe71e7929" />

![WhatsApp Image 2026-03-28 at 10 45 16 AM](https://github.com/user-attachments/assets/efcf42f7-c99b-4a10-a567-0535f0eae852)



## Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ


## PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
<img width="1280" height="658" alt="image" src="https://github.com/user-attachments/assets/659877b6-5112-4e1b-a0f9-9760862414ae" />

	
## CALCULATION
<img width="1045" height="1098" alt="image" src="https://github.com/user-attachments/assets/37c4bd1c-f9fc-4a1b-8c82-784d134e8b38" />

---
## OUT PUT WAVEFORM  
<img width="916" height="1280" alt="image" src="https://github.com/user-attachments/assets/04d14c02-0de0-4dfd-b69d-4cac100eb8fc" />


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


<img width="704" height="397" alt="image" src="https://github.com/user-attachments/assets/1b4b170f-cf21-4fa9-9dc7-96db30b3c153" />

---
## CIRCUIT DIAGRAM
<img width="1280" height="798" alt="image" src="https://github.com/user-attachments/assets/394ab465-6bf3-4814-b8f6-3b217af6c461" />

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
## DESIGN AND ANALYSIS:
<img width="1280" height="598" alt="image" src="https://github.com/user-attachments/assets/2055c629-4153-4b99-8d2c-a7e1e581feca" />

<img width="1974" height="2784" alt="image" src="https://github.com/user-attachments/assets/848cb134-778e-45fb-a244-4c180f5b8948" />

## PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![WhatsApp Image 2026-03-28 at 10 50 46 AM](https://github.com/user-attachments/assets/9c228cd6-77e7-4e1e-9038-6801a12ad923)

## CALCULATION
![WhatsApp Image 2026-03-28 at 10 51 16 AM](https://github.com/user-attachments/assets/6844a894-d291-4980-88a2-429c0fb51b91)


---
## OUT PUT WAVEFORM 
![WhatsApp Image 2026-03-28 at 10 42 12 AM](https://github.com/user-attachments/assets/f0e862ec-9600-48b4-b2cb-d02db88dde71)



---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="706" height="522" alt="image" src="https://github.com/user-attachments/assets/917f2544-3735-4a23-a9b7-1264966d0d20" />

## CIRCUIT DIAGRAM
![WhatsApp Image 2026-03-28 at 10 52 54 AM](https://github.com/user-attachments/assets/61c47150-20ee-490a-a170-5c3c79a5afba)

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN AND ANALYSIS
![WhatsApp Image 2026-03-28 at 10 55 15 AM](https://github.com/user-attachments/assets/1f6e512d-eed7-45d0-b3ab-d3fb9e8cbdc9)

![WhatsApp Image 2026-03-28 at 10 55 35 AM](https://github.com/user-attachments/assets/d5a90857-9cf3-4848-80c5-ec6b4af3569e)

![WhatsApp Image 2026-03-28 at 10 55 49 AM](https://github.com/user-attachments/assets/fcacbdad-4b56-409a-a1a5-3bfdbbd2af9f)


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

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
![WhatsApp Image 2026-03-28 at 10 53 51 AM](https://github.com/user-attachments/assets/46b32c2f-42ad-4ab4-96a6-557c83a18db0)


---

## CALCULATION
![WhatsApp Image 2026-03-28 at 10 54 16 AM](https://github.com/user-attachments/assets/1ef1e165-4797-4848-9318-564afd4dca90)

## OUT PUT WAVEFORM  
![WhatsApp Image 2026-03-28 at 10 54 16 AM](https://github.com/user-attachments/assets/249d1862-cfd2-401c-a877-28f4dc8f10d1)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1006" height="1087" alt="image" src="https://github.com/user-attachments/assets/636c08f9-7940-470e-a89e-4891d57a9ac7" />
## CIRCUIT DIAGRAM
![WhatsApp Image 2026-03-28 at 10 59 54 AM](https://github.com/user-attachments/assets/24c6eaee-b3bf-4187-8b39-051e912e626f)

## MODEL GRAPH
![WhatsApp Image 2026-03-28 at 11 00 15 AM](https://github.com/user-attachments/assets/085bad8a-3ec7-4b34-81ba-eda77deeaec3)

## DESIGN AND ANALYSIS
![WhatsApp Image 2026-03-28 at 11 02 12 AM](https://github.com/user-attachments/assets/49a6c159-6a3c-42d9-8fc9-3a25b04d57d3)

![WhatsApp Image 2026-03-28 at 11 04 39 AM](https://github.com/user-attachments/assets/1e86d36e-3ade-45e9-9a17-1761050654e5)


## PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2026-03-28 at 11 00 32 AM](https://github.com/user-attachments/assets/ba29ab81-35be-419b-ab2f-b096d9ac674f)


---
## CALCULATION
![WhatsApp Image 2026-03-28 at 11 00 51 AM](https://github.com/user-attachments/assets/6ac47a3d-d2e1-47cf-9330-f285a04d36ac)

## OUT PUT WAVEFORM  
![WhatsApp Image 2026-03-28 at 11 01 14 AM](https://github.com/user-attachments/assets/bee43f92-3a89-4809-bf5f-9551cecc90f5)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
