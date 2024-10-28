---
title: "Readout electronics for SiPM arrays"
excerpt: "This project is still ongoing,the following will present the latest progress of the project.<br/><img src='/images/powerBoard.heic'>"
collection: portfolio
---
We used a single crystal paired with a single SiPM to verify the method of encoding positional information using a resistor network.Through a resistor network, 64 SiPM signals can be encoded into four output channels. The SiPM signal from each position creates a specific distribution of weights across the four output ports, enabling the identification of the signal’s origin based on this principle.
<br/><img src='/images/crystalArray.heic'>
<br/><img src='/images/resistorArray.png'>
An interesting design utilizes a magnetic connector to create a power baseboard, allowing small modules to easily attach and receive power. The power board can supply up to three different voltage level, this is very useful for modular designs.
<br/><img src='/images/powerBoard.heic'>
We use a 14-bit ADC to sample the SiPM signals, and the board below is a prototype of the ADC circuit. Test results show that this circuit board operates correctly.
<br/><img src='/images/adc.heic'>
To filter effective signals, a well-designed trigger circuit logic is essential. This small board includes a 7ns comparator and a 12-bit DAC, allowing the trigger threshold to be adjusted using buttons on the development board. To reduce false triggers from simulated noise interference, we added a degree of hysteresis to the comparator.
<br/><img src='/images/dac.heic'>