# ComplexityEEG
Multiscale Entropy Analysis on EEG signal during sleep deprivation studies

This repository contains Matlab code for doing the MSE analysis and plotting the different data (includeing psychomotor vigilance tests).
The basic idea is to use the SampEn code on different time scales.
IMPORTANT: Currently, the code does not include coarse-graining the time signal. Therefore, it is not a classical MSE analysis.

There are currently two sleep deprivation experiments in the source raw data. 
The first experiment, from the Palmachim AFB, inlcudes 8 subjects, measured over 6 sessions. The subjects underwent 32 hours of continous
sleep deprivation. They were measured every 6 hours and after an 8 hour sleep recovery period. Each measurement included 4 minutes of rest
with eyes open and 3 minutes of PVT. PVT data is stored in the same folders.

The second experiment, from the Hatzerim AFB, include 6 subjects, measured over 4 session. Here, the subjects were allowed 3 hours of sleep
for two consecutive nights and a full 8 hour sleep the third night. EEG measurements were taken every evening (at 19:00) for the three 
relevant evenings and once again after the recovery sleep. Again, 4 minutes of rest and 3 minutes of PVT.
