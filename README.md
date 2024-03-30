# Ohmmeter
A battery powered auto-ranging ohmmeter (Measurement range: 1Ω – 2MΩ), made for the Microprocessor Systems Design class in one quarter. The overall design specifications of the assignment were to measure up to 1MΩ and achieve an accuracy of 0.05% or better among the middle ranges of 100Ω to 10kΩ.

**Update (3/28/2024):**
 The project files and schematics for Revision B were added. Please see the [commit extended description](https://github.com/ThomasCrisafulli/Ohmmeter/commit/056860dc55eb1752448fc8f3667a36f3e23dcd25) for details.

![Finished Ohmmeter PCB](https://user-images.githubusercontent.com/122324428/211429192-8cd7d599-cb19-4cc0-996d-7d6baa555dbd.png)
*Figure 1. Measuring an Accurate 5kOhm resistor.*

The device works by injecting a known current across the resistor under test and measuring the voltage across it. The currents used to test the resistors are selectable and found in the bulleted list under Specifications→Six Ranges. These currents are generated using a adjustable constant current source referenced to a high-precision voltage source and switched using low-leakage-current analog switch ICs.

**Project Features:**
* 16-bit signed ADC, with 3 Stage programmable gain amplifier, operating in differential sampling mode for increased accuracy and improved noise rejection.
* Six Ranges, with resistance scales of 130.0Ω, 1.000kΩ, 6.100kΩ, 40.00kΩ, 235.0kΩ, and 2.000MΩ.
* Maximum measurable value of 2.5MΩ.
* BNC connector and coaxial cable for noise rejection
* Zeroing capability.
* Input protection and noise filtering through the use of TVS diodes and low-pass filters.
* 5 Hz screen refresh rate.
* Powered by an 18650 3.7V Li-Ion Battery, with a battery life of over 75 hours (assuming a capacity of 3 Ah).

**Notice:**

The software for the project still needs to be cleaned up and refactored a bit before it will be posted here.

