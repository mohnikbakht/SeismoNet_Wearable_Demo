# Cardio Wireless Wearable Patch (C)

Seismocardiogram (SCG) is the measure of the thoracic vibrations produced by the heart’s contraction and the ejection of blood from the ventricles into the vascular tree. Today, the SCG can readily be detected by placing a low-noise accelerometer on the chest. 

Electrocardiogram (ECG) signal reflects the electrical activity of the heart observed from the strategic points of the human body and represented by quasi-periodic voltage signal.

These signals fiducial points correspond to characteristic events in the cardiac cycle. For the SCG, the labels correspond to the physiological event they are believed to represent: MC, mitral valve closure; IVC, isovolumetric contraction; AO, aortic valve opening; RE, rapid ejection; AC, aortic valve closure; MO, mitral valve open- ing; and RF, rapid filling.

Here we developed a series of wireless wearable patches enabling easy recordings of ECG and SCG signals for cardiovascular health related studies. Further, a multinode platform is developed where multiple patches can record at the same time with a wirelessly synced RTC timer.

## The Hardware

In all patches Nordic’s nRF52840 SoC was used to enable wireless communication using Bluetooth LE. The nRF52840 is built around a 32-bit ARM Cortex-M4 CPU, which makes it capable of interfacing with the sensors and storage units (microSD card) as well as Bluetooth data transfer. We used Bluetooth LE technology to minimize power consumption and maintain low power characteristics while transmitting data to keep the devices running for a longer period of time. To advance the measurement abilities, we developed a multi-node platform where multiple wireless nodes (patches) can record SCG and ECG signals with synchronized real-time clock (RTC) timers and store them locally on a microSD card and/or transmit them to a laptop, phone, or Google Glass through Bluetooth. This brings more flexibility in terms of sensor node placement as no wiring is required.

The figure below shows the ECG/SCG patch, enables recording and storing/streaming of both SCG and ECG signals.\
<img src="https://github.com/mohnikbakht/Cardio_Wearable_Patch_Demo/blob/main/Images/ECG_SCG_Patch.png" alt="Image of The ECG/SCG Patch" width="800"/>

The figure below shows the SCG patch in two different packages which only records SCG signals.
a) Flexible package:
<img src="https://github.com/mohnikbakht/Cardio_Wearable_Patch_Demo/blob/main/Images/SCG%20patch.jpg" alt="Image of The ECG/SCG Patch" width="350"/>
b) Rigid package:
<img src="https://github.com/mohnikbakht/Cardio_Wearable_Patch_Demo/blob/main/Images/SCG_patch_2.png" alt="Image of The ECG/SCG Patch" width="350"/>

A signle firmware is written for all patches in C (using #if directives) and in a way that they can connect and communicate with each other for the multi-node applications. 

## Sample Data

## User Interfaces

We designed graphical interfaces on three different platforms for these wearables that enable easy interface for data collection:
1) Windows App (C#) -> [link to Our Windows App Demo!](https://github.com/mohnikbakht/Windows_App_Demo)
2) Phone App (React-Native) -> [link to Our Phone App Demo!](https://github.com/mohnikbakht/React_Native_Phone_App_Demo)
3) Google Glass App (Kotlin) -> [link to Our Glass App Demo!](https://github.com/mohnikbakht/Google_Glass_App_Demo)
