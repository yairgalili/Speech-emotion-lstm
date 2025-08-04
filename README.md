# speech emotion lstm

We extract features from the audio and train lstm tensorflow model for estimating the emotion for the audio.


We will only extract these features:

1) Mel-Frequency Cepstral Coefficients: captures the shape of the spectral envelope of a signal
2) Zero Crossing Rate: captures the number of times a signal changes sign per second
3) Root Mean Square Energy: captures the root mean square amplitude of the audio signal 
