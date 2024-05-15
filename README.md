# PCB-Design-Application
## Name: Sri Vignesh G
## Reg No: 212223040204
# Aim
To design a reliable system capable of detecting and identifying mobile phone transmissions in eagle software.

# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory

Cell phone detector circuits operate on the principle of detecting electromagnetic waves emitted by mobile phones. Mobile phones emit radio frequency (RF) signals during various operations like making calls, sending messages, or connecting to networks. These RF signals fall within a specific frequency range allocated for cellular communication.

The detector circuit typically consists of an antenna to capture RF signals, which are then fed into a signal amplifier to boost their strength for processing. Bandpass filtering is employed to isolate the desired frequency range corresponding to mobile phone signals, while rejecting other noise and interference.

Once the RF signal is amplified and filtered, it undergoes mixing with a local oscillator signal. This mixing process facilitates frequency conversion, allowing the RF signal to be demodulated and extracted for further analysis.

Threshold detection mechanisms are often integrated into the circuit to distinguish between the presence and absence of mobile phone signals. This involves setting a threshold level above which detected signals are considered indicative of cell phone activity.

To enhance sensitivity and reduce false positives, techniques such as noise suppression and sensitivity adjustment may be employed. Noise suppression techniques aim to minimize the impact of background noise and interference, ensuring accurate detection. Sensitivity adjustment allows the circuit to adapt to different signal strengths and environmental conditions, optimizing performance.

Overall, cell phone detector circuits combine elements of RF detection, signal processing, and threshold-based decision-making to reliably identify the presence of mobile phone signals within their vicinity. These circuits find applications in various settings, including security-sensitive areas where unauthorized cell phone usage needs to be monitored and controlled.


# Working 

1. **Signal Reception**: The circuit's antenna captures electromagnetic signals emitted by mobile phones within its range.

2. **Signal Amplification**: These captured signals are weak and need to be strengthened for processing. An amplifier boosts the signal's strength to make it more detectable.

3. **Frequency Filtering**: The amplified signal contains a range of frequencies. A filter is applied to isolate the specific frequency bands associated with mobile phone transmissions, while filtering out noise and interference from other sources.

4. **Frequency Conversion**: The filtered signals are mixed with a local oscillator signal. This mixing process facilitates frequency conversion, allowing the signal to be demodulated and analyzed.

5. **Threshold Detection**: The demodulated signal is compared to a predetermined threshold level. If the signal strength exceeds this threshold, it indicates the presence of a mobile phone transmission.

6. **Alert or Response Mechanism**: Upon detection of a signal surpassing the threshold, the circuit triggers an alert mechanism, such as sounding an alarm or activating a notification system. This alerts the operator to the presence of a mobile phone in the monitored area.

7. **Sensitivity Adjustment**: Sensitivity adjustments may be incorporated to fine-tune the circuit's performance, allowing it to adapt to different signal strengths and environmental conditions.

By combining these stages, a cell phone detector circuit can effectively identify and alert users to the presence of mobile phone transmissions within its vicinity.



# Circuit Diagram
![WhatsApp Image 2024-04-25 at 14 58 33_f9773071](https://github.com/SriVignesh-G/PCB-Design-Application/assets/147576510/94bc50cb-8240-41b1-b729-6252a4fb64aa)



# Output

## Schematic diagram
![Screenshot 2024-05-09 161811](https://github.com/SriVignesh-G/PCB-Design-Application/assets/147576510/13a8bcf2-6e77-44e4-92da-7a1a7f46c9ac)




## Layout diagram
![Screenshot 2024-05-09 161744](https://github.com/SriVignesh-G/PCB-Design-Application/assets/147576510/2ff7bfd1-4327-4714-aa7e-6a9d30f5ffbb)



# Result
Thus, the reliable system capable of detecting and identifying mobile phone transmissions was designed successfully in eagle software

