# Optiperformer_Introduction
# Introduction to OptiPerformer

## Objective
Download and install OptiPerformer software on your computer and run a sample file.

## Overview
Optiwave introduces **OptiPerformer**, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios that can be used by students.

In this exercise, you will download and install OptiPerformer on your PC/laptop.  
Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course.

Once you have installed OptiPerformer, you can copy the first file (named: `Introduction_OptiPerformer.osp`) to your PC and run the simulation.  
The first file is a basic fiber optic system consisting of a transmitter, a fiber, and a receiver.  
The system is instrumented with:
- An **optical power meter** at the input to the receiver (or the output of the fiber)  
- A **bit error rate (BER) analyzer**

---

## Instructions
1. **Download and install** OptiPerformer from the [optiwave.com](https://optiwave.com) website.  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Start OptiPerformer.  
4. Use either the **File menu** or the **Open File button** to open the Fiber Optic System File.  
5. Study the layout, which includes text and boxes to identify the three components of the fiber optic system:  
   - **Transmitter section**: binary source (PRBS generator), electrical pulse generator, laser diode, external modulator  
   - **Receiver section**: photodiode, low-pass filter, decision circuit (includes BER analyzer)  
6. Run the simulation by pressing the **Start button**.  
   - The progress of the simulation will be displayed.  
   - The message *“Calculation Finished!”* will appear when the simulation completes.  
7. Double-click on the **optical power meter** and the **BER analyzer**.  
   - Move the windows as necessary for clarity.  
   - Check the box next to *“Show Eye Diagram”* in the BER window.  
   - The optical power meter shows power at the input to the photodiode in both **watts** and **dBm**.  
   - The BER window displays the **eye diagram**, **Max Q Factor**, and **Min BER**.  
8. The simulation is set to run **5 iterations**, with fiber length varying from **50 km to 150 km** in 5 steps.  
   - The index is displayed in the upper right corner of the layout.  
   - Use the **forward** and **reverse buttons** in the lower left of the window to step through iterations.  
   - Note the change in received power and BER display (eye diagram, Q factor, BER) with fiber length.  

---

## Report
1. Cover sheet per the attached example.  
2. Tabulation of **received power, Q factor, and BER** for the 5 different fiber lengths.  
3. Plot of **received power, Q factor, and BER versus fiber length**.  
4. Description of the **change in the eye diagram** with increasing fiber length.  
