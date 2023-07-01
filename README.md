# KneeMS: A Low-Cost Wireless Wearable System to Monitor Knee Acoustic Emissions

Knee health assessment is crucial in reducing the risk of knee injuries, which can have a significant impact on individuals of all ages and activity levels. Knee acoustic emissions (KAEs) have emerged as a promising bio-signal for assessing knee health, which can be recorded using a wide-band microphone. However, the monitoring of KAE has been dependent on expensive and bulky systems, limiting the accessibility and scalability of the technology for a large population. 

In this work, we introduce a novel wireless knee wearable monitoring system (KneeMS) that is low-cost, sensitive, and designed to record knee acoustic emissions (KAEs). This small form factor wearable represents a promising advancement in KAEs monitoring technology as it is the first of its kind to combine low-cost, sensitivity, and wireless connectivity.

The frequency response of KneeMS was evaluated through spectral density (PSD) comparison against a previously validated benchtop system. A Pearson's r = 0.99 was achieved for PSD comparison between the sine sweep response of KneeMS and the benchtop system. A human participant study was conducted to validate the system's performance in the context of KAEs, showing that KneeMS performs comparably to the benchtop system in joint loading experiments. The study achieved a Pearson's r = 0.96 for root mean square (RMS) amplitude comparison between KneeMS and benchtop system. Moreover, the study showed that KneeMS exhibits an RMS ratio behavior similar to the benchtop for different  joint loading conditions. 
Thus, KneeMS offers a more efficient, scalable, and accessible solution for measuring KAEs. The system's portability and wireless connectivity enables continuous monitoring of KAEs, offering a solution for remote and longitunal monitoring for future studies on the use of KAEs for knee health monitoring. 

## Overview
Overview of the designed wireless knee wearable sensor  and sensor placement for the human participant study. (a) The patch with a 3D printed rigid housing for the main board and a flexible resin housing for the sensor board. (b) The patch consists of two printed circuit boards (PCBs) connected using an FFC connector. The main board includes an nRF52840 microcontroller, and a microSD card, charging circuit, and connectors to the sensors board. The microUSB allows for battery charging and data transfer. The sensors board includes a 3-axis MEMS vibration sensor (IIS3DWB). (c) The wireless patch is attached to the knee with a double-sided tape and the flexible connector (FFC) allows for easy motion of the knee. A Dytran accelerometer is placed side to side with the sensor to enable a comparison between our patch and Dytran for this human study.

<p align="center">
<img src="https://github.com/mohnikbakht/KneeMS_Demo/blob/main/figures/figure1.png" alt="overview figure" width="600"/>
</p>


## Validation Results

(a) A comparison between the frequency response of the two sensors using a sine sweep signal. (b, c) The results of the knee loading human participant study. Specifically, (b) a comparison of the RMS amplitudes of the two sensors for all six participants (each color represents a participant, the shape represents the knee, and the size represents the loading), and (c) The ratio of RMS amplitudes to 0\% body weight RMS baseline using the two sensors for all six participants and the three loadings. Median and 1st/3rd quartiles are presented.

<p align="center">
<img src="https://github.com/mohnikbakht/KneeMS_Demo/blob/main/figures/figure2.png" alt="results figure" width="600"/>
</p>

 ## Conclusion
 
In this work, we present KneeMS, a wireless wearable sensor capable of recording high quality KAEs. We performed a two-stage validation study during which we compared the KneeMS system to a gold standard benchtop system. First we compared the broadband frequency response of both systems, which showed to correlate well.
Secondly we performed a human participant study, and demonstrated that KneeMS performs comparably to the benchtop system, thus validating its utility to record high quality KAEs.
KneeMS offers a significantly lower cost compared to other systems, making it a more affordable option to record KAEs. Therefore, it offers a promising opportunity for more efficient and continuous knee health assessment with improved scalability and accessibility. Overall, this study highlights the potential of KneeMS to be used as a compact and wearable tool to record KAEs. This work is an important stepping stone for future studies that will focus on remote and longitudinal monitoring of KAEs for various purposes such as joint health monitoring or joint loading assessment.
