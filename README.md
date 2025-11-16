
# Exp 5 Experimental verification of frequency response of Digital fiber optic link
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

*(Insert block diagram here)*

---
![WhatsApp Image 2025-11-16 at 15 38 04_b9f63c99](https://github.com/user-attachments/assets/bed1f472-2e56-4b05-bddc-fa0831151b4c)



## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-16 at 15 38 23_615d6ca9](https://github.com/user-attachments/assets/7e9da357-9c4b-4bda-8894-7f02c0fc2bf6)

---

## MODEL GRAPH

*(Insert model graph here)*
![WhatsApp Image 2025-11-16 at 15 38 27_e4f56f15](https://github.com/user-attachments/assets/c3a870b0-2714-42cf-9533-c071515e8e4b)


---
## GRAPH
![WhatsApp Image 2025-11-16 at 15 39 10_cdb6a5f4](https://github.com/user-attachments/assets/8cfe56ba-5dcd-484a-b25d-244a1f11f524)


## RESULT

*(Summarize observations and conclusions here)*
