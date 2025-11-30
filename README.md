## EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
## 4. **EX.NO:**  EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
## DATE: 25-10-2025
## AIM:
---
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
## THEORY:
---
RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---
## APPARATUS REQUIRED
| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1.5K,15K, 450kΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 
---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR

![WhatsApp Image 2025-12-01 at 00 48 36_cefc3f33](https://github.com/user-attachments/assets/45a73336-99e8-4dce-b9b7-c6d22abeb85d)


---
## MODEL GRAPH
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/3389b740-b70e-4148-9bf9-e5319627260f" />
## DESIGN
## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 1.5 k
Therefore, Choose R = 1.5k
To prevent loading,
R1   10 R
R1 =15 R = 1.5 k. Rf = 29R1=450kΩ
---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-12-01 at 00 50 03_0360f375](https://github.com/user-attachments/assets/4204d777-af70-43e7-98d1-a319192a422e)


---
## OUTPUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-01 at 00 55 43_8034d01c](https://github.com/user-attachments/assets/1c5a715c-bb5e-45c2-94d1-e6d1072e536a)

---
## THEORY
 ## WIEN BRIDGE
 ## DATE: 01-11-2025
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED
| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1.57K, 1.5K, 15K, 30kΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |
---
## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR

![WhatsApp Image 2025-12-01 at 00 57 22_5e1cad92](https://github.com/user-attachments/assets/600da84a-69fc-403e-bb6c-f32234dd5964)

---
## MODEL GRAPH
<img width="414" height="325" alt="image" src="https://github.com/user-attachments/assets/1cc285f7-05c7-4b65-af59-b28cf039fcd3" />
---
## DESIGN
## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.57KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---
## PROCEDURE
1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


---
##  TABULATION/OBSERVATION

<img width="1253" height="450" alt="image" src="https://github.com/user-attachments/assets/34d113b9-75d3-40d4-a403-8038a58f4ac6" />


---
## OUTPUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-01 at 01 00 14_74bd0b84](https://github.com/user-attachments/assets/e106df82-a847-4d1a-b2fb-4ffbbb1e6daf)


---
## RESULT:
Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
