
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM
-
<img width="619" height="392" alt="image" src="https://github.com/user-attachments/assets/604a5c5e-d9e4-4534-8f87-36c5cf81feec" />


---




## TABULATION  
-
![WhatsApp Image 2025-11-17 at 20 51 58_6f627377](https://github.com/user-attachments/assets/769259a3-a0e0-44db-8c78-f14b9f6a1f4a)


---

## MODEL GRAPH
-
<img width="805" height="386" alt="image" src="https://github.com/user-attachments/assets/4e5fcf06-59f8-4cf9-8df9-fa46746fba3e" />

---

## OUTPUT GRAPH
-
![WhatsApp Image 2025-11-17 at 20 54 14_b28f5d4c](https://github.com/user-attachments/assets/76afe4ba-f62d-4b58-b20c-acf26f32b651)
---


## RESULT
-
Thus, the frequency response of the digital fiber optic link was successfully verified. The measured bandwidth of the digital fiber optic link is approximately 100 kHz, confirming the expected performance characteristics of digital optical transmission.

