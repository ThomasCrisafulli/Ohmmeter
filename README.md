# Ohmmeter
A battery powered auto-ranging ohmmeter (Measurement range: 1Ω – 2MΩ), made for the Microprocessor Systems Design class in one quarter. The overall design specifications of the assignment were to measure up to 1MΩ and achieve an accuracy of 0.05% among the middle ranges of 1kΩ to 100kΩ.

![Finished Ohmmeter PCB](https://user-images.githubusercontent.com/122324428/211429192-8cd7d599-cb19-4cc0-996d-7d6baa555dbd.png)
*Figure 1. Measuring an Accurate 5kOhm resistor.*

**Specifications:**
* 16-bit signed ADC, with 3 Stage programmable gain amplifier, operating in differential sampling mode for increased accuracy.
* Six Ranges, with Current Steps of 12.50 mA, 1.736 mA, 310.9 µA, 48.04 µA, 8.012 µA, 129.4 nA.
* Maximum measurable value of 2.5MΩ.
* BNC connector and coaxial cable for noise rejection
* Zeroing Capability.
* Input protection and noise filtering through the use of TVS diodes and low-pass filters.
* 5 Hz screen refresh rate.
* Powered by an 18650 3.7V Li-Ion Battery, with a battery life of over 75 hours (Assuming a capacity of 3 Ah).


