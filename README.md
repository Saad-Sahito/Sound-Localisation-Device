# Sound-Localisation-Device

DESIGN FIGURE FOR LOCALISZATION DEVICE:
Prototype specification of our localization device:
Sound Filtration = FFT - frequency filtering - iFFT (filter 50 - 500 Hz)
Localization = Combining audio data - MUSIC DOA - Angle
Triangulation = Angles to Distance (Angle method, Sound Intensity method)
Precision Checker = Approximation of best case value for given angles and distances

For the data reading, denoising and sound direction detecting parts, we simply use the software to implement our design.
For beamforming, localization and output and user interface components, we used Simulink to present our idea. 
1.	The data reading component can be simulated by using C code to read in audio signals from microphones. 
2.	The beamforming component can be simulated by using Simulink's signal processing blocks to apply a filter to the audio signals, and then combining them into a single signal.
3.	The localization component can be simulated by using python to calculate the direction of the sound source.


AUTHOR CONTRIBUTION STATEMENTS
Saad Nisar: Theory & FSM Design & Beamforming Simulink implementation & Presentation
Wei-Chia Hsu: Theory & project background research & Data reading implementation & Report making
Yaoyu Liu：Theory & Model-Based design & PowerPoint making & Presentation
Cheng-yu Lin：Theory & Midterm presentation & Data Denoising implementation & Report making
