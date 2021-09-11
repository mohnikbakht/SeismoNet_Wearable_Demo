# Cardio Wireless Wearable Patch

Seismocardiogram (SCG) is the measure of the thoracic vibrations produced by the heart’s contraction and the ejection of blood from the ventricles into the vascular tree. Today, the SCG can readily be detected by placing a low-noise accelerometer on the chest. 

Electrocardiogram (ECG) signal reflects the electrical activity of the heart observed from the strategic points of the human body and represented by quasi-periodic voltage signal.

These signals fiducial points correspond to characteristic events in the cardiac cycle. For the SCG, the labels correspond to the physiological event they are believed to represent: MC, mitral valve closure; IVC, isovolumetric contraction; AO, aortic valve opening; RE, rapid ejection; AC, aortic valve closure; MO, mitral valve open- ing; and RF, rapid filling.

Here we developed a series of wireless wearable patches enabling easy recordings of ECG and SCG signals for cardiovascular health related studies. Further, a multinode platform is developed where multiple patches can record at the same time with a wirelessly synced RTC timer.

## The Hardware

In all patches Nordic’s nRF52840 SoC was used to enable wireless communication using Bluetooth LE. The nRF52840 is built around a 32-bit ARM Cortex-M4 CPU, which makes it capable of interfacing with the sensors and storage units (microSD card) as well as Bluetooth data transfer. We used Bluetooth LE technology to minimize power consumption and maintain low power characteristics while transmitting data to keep the devices running for a longer period of time. To advance the measurement abilities, we developed a multi-node platform where multiple wireless nodes (patches) can record SCG and ECG signals with synchronized real-time clock (RTC) timers and store them locally on a microSD card and/or transmit them to a laptop, phone, or Google Glass through Bluetooth. This brings more flexibility in terms of sensor node placement as no wiring is required.

## Sample Data

## User Interfaces
