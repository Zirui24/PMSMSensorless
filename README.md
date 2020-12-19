# PMSM-Sensorless
A simulation about PMSM sensorless control based on simulink
This simulation is about Sliding Mode Obverser.This is a very common control scheme of positionless motor in the industry.
There are two types of SMO:
1.  First Order SMO:it is easy to achieve but need a filter to get the rotor position
2.  Super Twisting SMO:Solving the sign function and saturation function makes the observation make the Angle vibration of observation smaller and smoother.In addition, the low-pass filtering and phase compensation necessary for the traditional first-order sliding mode are deleted, and the dynamic response of the whole system is higher because there is no filter involved


Personally, I prefer higher order sliding mode