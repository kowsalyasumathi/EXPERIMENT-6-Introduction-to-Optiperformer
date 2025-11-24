
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
Download and install OptiPerformer software on your computer and run a sample file.

## EQUIPMENTS REQUIRED:
Optisystem Software – OptiPerformer 22.0

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions


1. Download and install OptiPerformer from the optiwave.com web site.
2.	Copy the ‘Introduction_OptiPerformer.osp’ file to your PC
3.	Start OptiPerformer
4.	Use either the File menu or the Open File button to open the Fiber Optic System File.
5.	Study the layout, which includes some text and boxes to identify the three components of the fiber optic system. The “transmitter” section includes a binary source (PRBS or pseudo-random bit sequence generator), an electrical pulse generator, a laser diode and an external modulator. The receiver section includes a photodiode, a low-pass filter and a decision circuit, which includes a BER analyzer. We will cover these components in more detail later in the course.
6.	Run the simulation by pushing the start button. The progress of the simulation will be displayed
and the message “Calculation Finished!” will appear when the simulation runs to completion.
7.	Double click on the optical power meter and the BER analyzer and move the windows as necessary for clarity. Check the box next to “Show Eye Diagram” in the BER window. The optical power meter shows the power at the input to the photodiode in both watts and dBm. The BER window displays the “eye diagram” and several quantities including the “Max Q
Factor” and the “Min BER”.
8.	The simulation is set to run 5 “iterations”, with the fiber length varying from 50 to 150 km in 5 steps. The index is displayed in the upper right corner of the layout. To step through the iterations, use the forward and reverse buttons in the lower left of the window. Note the change in received power and BER display (eye diagram, Q factor and BER) with fiber length.
---

<img width="710" height="387" alt="image" src="https://github.com/user-attachments/assets/c4378f50-a1b1-4698-88ea-e0783a41aa9f" />

---
## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
|------|-------------------|------------------------|----------------------|--------------|---------|-------------|-------------------------------------|
|   1  |   50              |        46.88           |      -13.289         |      104.972 |  0      | 9.709       |   0.5468                            |
|   2  |  70               |        19.595          |      -17.079         |      66.1512 |   0     | 3.807       |   0.5468                            |
---

Block Diagram

<img width="744" height="427" alt="image" src="https://github.com/user-attachments/assets/03bc0a41-a555-4c34-ac88-e3496c3a00ce" />

## Graphs

<img width="1909" height="975" alt="image" src="https://github.com/user-attachments/assets/08a670eb-dabf-4070-a10e-210fffc3a5e7" />

<img width="728" height="785" alt="image" src="https://github.com/user-attachments/assets/f2d98e71-d102-455a-b643-25848059cd90" />


---

## RESULT

Thus the optical communication system was successfully simulated using OptiPerformer. As the fiber length increased from 50 km to 150 km, the following trends were observed:
