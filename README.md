# MATLAB Application for Vibration Analysis and Shock Absorber Design

This MATLAB application facilitates not only data analysis but also aids in the design and validation process of the vibration-damping system. The combination of time-domain and frequency-domain analysis, along with system parameter calculation, ensures a comprehensive solution for vibration analysis and shock absorber design.

## Data Visualization - Acceleration in Time Domain

In the first window, the acceleration data along the X, Y, and Z axes is plotted. This data is extracted from the CSV file obtained from the DAQ system. The selected file can be loaded, and the acceleration over time is visualized for all three axes.

*Figure 53: Time-domain acceleration plot for X, Y, and Z axes.*

## Frequency Spectrum - FFT Analysis

The second window provides a frequency domain analysis using FFT. The FFT plots display the frequency components of the vibration signals for the X, Y, and Z axes, allowing the identification of peaks corresponding to the natural frequency and its harmonics. This is crucial for further analysis and design of the damping system.

*Figure 54: Frequency spectrum (FFT) for X, Y, and Z axes, showing dominant frequency peaks.*

## System Parameters Calculation

In the third window, the system parameters related to the shock absorber are calculated. The user first loads a CSV file containing the vibration data, and the application automatically extracts key parameters such as the natural frequency and damping ratio obtained from the FFT analysis. By entering additional known parameters related to the system, such as the mass, piston diameter, mean coil diameter, shear modulus, and the number of active coils in the spring, the application calculates important values such as the spring constant, dynamic viscosity, and wire diameter of the spring. These parameters are critical for selecting or designing an appropriate shock absorber tailored to the system’s specific requirements.

*Figure 55: System parameters calculation window for the shock absorber.*

## System Comparison - Before and After Damping

The fourth window allows users to load the CSV files of the system’s acceleration data recorded before and after the installation of the damping solution. After selecting the files, the frequency spectra of the accelerations are plotted for comparison across all three axes (X, Y, and Z). This comparison highlights the reduction in vibration amplitude and any shifts in the natural frequency. The application also quantifies the damping effect by calculating the overall vibration reduction as a percentage.

*Figure 56: Comparison of frequency spectra before and after shock absorber installation.*

This feature provides a comprehensive visualization of how the shock absorber improves the system’s performance by reducing vibrations across all axes.
