## Breadboard Diagram
![98173ghdu](https://github.com/user-attachments/assets/c7b9ef93-c15f-410e-b077-3d9df48f7108)

This Arduino project monitors temperature, light levels, and a user-defined temperature threshold using a potentiometer (A0), thermistor (A1), and LDR (A2). The system triggers a buzzer (pin 9) when the temperature exceeds the threshold set by the potentiometer. In the loop(), the program reads values from the three sensors:
-Potentiometer sets the temperature threshold (mapped between 0-100°C).
-Thermistor measures the actual temperature (mapped between -40°C to 125°C).
-LDR measures light intensity.
If the temperature exceeds the threshold, the buzzer activates with a frequency based on the light level (dimmer light = lower frequency, brighter light = higher frequency). The values are printed to the Serial Monitor for real-time observation. The system updates every 500ms
