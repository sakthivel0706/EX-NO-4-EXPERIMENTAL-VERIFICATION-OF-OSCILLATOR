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

![WhatsApp Image 2025-12-04 at 00 48 33_50ff4097](https://github.com/user-attachments/assets/bbf18509-4f1e-4b40-aab1-b32b9e564093)


---
## MODEL GRAPH
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/3389b740-b70e-4148-9bf9-e5319627260f" />

---
## DESIGN

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 1.5 k
Therefore, Choose R = 1.5k
To prevent loading,
R1   10 R
R1 =15 R = 1.5 k. Rf = 29R1=450kΩ

![WhatsApp Image 2025-12-04 at 00 53 08_6a0c8615](https://github.com/user-attachments/assets/ed34c2ad-73ad-4d71-ab3d-edfdf30f4899)

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION


![WhatsApp Image 2025-12-04 at 00 48 50_24909021](https://github.com/user-attachments/assets/7fb317b5-0bc4-41f6-91b6-7438b807c89f)


---
## OUTPUT WAVEFORM AND DISCUSSION 


![WhatsApp Image 2025-12-04 at 00 49 23_a02220fb](https://github.com/user-attachments/assets/2e43450d-d6d0-41e0-971e-63eb51021a04)

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


![WhatsApp Image 2025-12-04 at 00 49 58_8621f1f9](https://github.com/user-attachments/assets/2dfd0856-7d4d-4627-95b5-47331ba4ca71)

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

![WhatsApp Image 2025-12-04 at 00 52 11_b45eb5c0](https://github.com/user-attachments/assets/618e1c47-8a57-4e74-b006-290e133c44ed)

---
## PROCEDURE
1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


---
##  TABULATION/OBSERVATION


![WhatsApp Image 2025-12-04 at 00 50 11_3f511360](https://github.com/user-attachments/assets/a840e166-35be-409d-8213-1dfe934d9193)


---
## OUTPUT WAVEFORM AND DISCUSSION 


![WhatsApp Image 2025-12-04 at 00 50 42_c8921d6e](https://github.com/user-attachments/assets/59177562-a5cd-4adc-ad41-b00bfa302d10)


---
## RESULT:
Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
