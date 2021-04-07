# Generating-Sargam-using-Python


#### Playing Sa Re Ga Ma Pa in Python !

*The SARGAM has the frequencies as(in Hz)* -
SA - 261  
RE - 294  
GA - 330  
MA - 349  
PA - 392  
DHA - 440  
NI - 494  
SAN - 515

* Get timesteps for each sample, T is note duration in seconds. For CD recordings, the industry standard is to store each audio sample as a 16-bit value, at 44100 samples per second.  
sample_rate = 44100  
T = 0.25  

* The amplitudes of the visualized audio signal which is time-domain are not very informative, as they only talk about the loudness of audio recording. To better understand the audio signal, it is necessary to transform it into the frequency-domain! For the same, here we've achieved this using Fourier Transform.





**We can plot the spectrum and listen the audio by properly defining it's functions as given in the code.**

### Installation
pip install requirements.txt



