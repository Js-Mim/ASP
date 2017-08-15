# ASP
[![DOI](https://zenodo.org/badge/94981060.svg)](https://zenodo.org/badge/latestdoi/94981060)

### You have just found Audio Signal Processing tools for Python (ASP).
It covers a range of utilities for I/O handling and Time-Frequency Decompositions and soon enough audio source separation methods.
Currently supported functionallity :
- WAV/MP3/AAC Reading and Writing
- Time Frequency Methods : MDCT/MDST/PQMF/STFT/FrFFT(Fractional FFT)
- Cepstral Analysis : Uniform Discrete Cepstrum
- Misc Operations : Bark Scaling, W-Disjoint Orthogonality Measure, Gini Index Sparsity Measure, Time-frequency Masking, Noise to Mask Ratio, Psychoacoustic Model (based on non-linear superposition) 

For code usage, please refer to each class. Examples are given inside method or in the "main()" call.

### Requirements :
- NumPy version   '1.10.4' or later
- SciPy version   '0.17.0' or later (Crucial for avoiding poor reconstruction for the complex PQMF)
- cPickle version '1.71' or later
- pyglet           For audio playback routines
- ffmpeg binary    For reading/writing routines

### Acknowledgements :
The research leading to these results has received funding from the European Union's H2020 Framework Programme (H2020-MSCA-ITN-2014) under grant agreement no.642685 MacSeNet.

