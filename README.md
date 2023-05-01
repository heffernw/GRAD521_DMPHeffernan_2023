# GRAD521_DMPHeffernan_2023

Data Managment Plan for research project Thermal Conductivity of Different Metal Powders

Context of the Project:
My thesis involves finding the thermal conductivity of various metal powders for 3D printing applications. To accomplish this, I built a test stand utilizing a laser, different interstitial gasses, a coil heater, vacuum chamber, and multiple thermocouples. In short, I place 2.4 cm³ of metal powder into a test tube, surround it with a coil heater, pull a vacuum in my sealed chamber, fill it with helium, and heat the powder with the coil heater to a desired temperature. Then, for 5 minutes and 10 seconds, I hit it with a pulsing laser and measure the heat fluctuations with a thermocouple implanted into the powder. The data collection is run by the LabView program, and the data collected is time and temperature data from both the thermocouple in the powder, which records about 25 samples at a rate of 15 Hz. This data is outputted to an Excel file, and then put into a Matlab code that calculates the thermal conductivity of the powder by first calculating the Fourier Number, followed by the thermal emissivity of the powder, and then calculating the thermal conductivity. Each data set is no more than 300 KB per test.



