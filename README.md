# BJT-Characteristics-Analysis

## Bipolar Junction Transistor (BJT) Characteristics Analysis ⚡
## Project Overview

In this project, I analyzed the working principles and characteristic curves of a BJT (Bipolar Junction Transistor). The main goal was to understand how a BJT behaves as a switch and as an amplifier, which is crucial for biomedical instrumentation (like ECG amplifiers).

## What is a BJT?

A Bipolar Junction Transistor (BJT) is a three-terminal semiconductor device that consists of two p-n junctions. It is capable of amplifying or switching electrical signals.
Terminals: Base (B), Collector (C), Emitter (E).
Types: NPN and PNP. (In this experiment, I used BC237 NPN Transistor).

## Circuit Setup & Methodology

To observe the characteristics, I constructed two main circuits:Input Characteristics: Observing the relationship between Base Current (Ib) and Base-Emitter Voltage (Ibe).Output Characteristics: Observing the relationship between Collector Current ($I_C$) and Collector-Emitter Voltage (Ice).
<img width="1095" height="758" alt="image" src="https://github.com/user-attachments/assets/b483ca31-389c-40db-b5f3-8b84e207e9bf" />

## Results & Analysis
![BJT Çıkış Karakteristik Grafiği] (Circuit_1_Graph.png)

1. Input Characteristics
As seen in the graph below, the BJT behaves like a diode at the input side. The current starts to flow significantly after the threshold voltage (approx. 0.7V for Silicon).
2. Output CharacteristicsThis is the most critical part.
3. The graph shows three main regions:
4. Cut-off Region: No current flows (Switch OFF).
5. Active Region: Current is amplified. This is where Amplifiers work.
6. Saturation Region: Maximum current flows (Switch ON).

## Biomedical Application Insight

Why does a Biomedical Engineer need to know BJT? Most physiological signals (ECG, EEG, EMG) are extremely weak (microvolts). To process these signals, we need Amplifiers. BJTs are the fundamental building blocks of these amplification circuits. Understanding the "Active Region" of a BJT is key to designing medical sensors.
   
