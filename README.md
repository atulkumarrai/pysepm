# pysepm - Speech Enhancement Performance Measures (Quality and Intelligibility) Implemented in Python
Python implementation of objective quality and intelligibilty measures mentioned in Philipos C. Loizou's great [Speech Enhancement Book](https://www.crcpress.com/Speech-Enhancement-Theory-and-Practice-Second-Edition/Loizou/p/book/9781138075573). The Python implementations are checked with the MATLAB implementations attached to the book (see [Link](https://crcpress.com/downloads/K14513/K14513_CD_Files.zip))


# Requirements

    gcc compiler
    cython
    numpy
    scipy
    pystoi
    pypesq 
# Implemented Measures
## Speech Quality Measures
+ Segmental Signal-to-Noise Ratio (SNRseg)
+ Frequency-weighted Segmental SNR (fwSNRseg)
+ Log-likelihood Ratio (LLR)
+ Weighted Spectral Slope (WSS)
+ Perceptual Evaluation of Speech Quality (PESQ)
+ Composite Objective Speech Quality (composite)
+ Cepstrum Distance Objective Speech Quality Measure (CD)

## Speech Intelligibility Measures
+ Short-time objective intelligibility (STOI)
+ Coherence and speech intelligibility index (CSII)
+ Normalized-covariance measure (NCM)

## Dereverberation Measures (TODO)
+ Bark spectral distortion (BSD) 
+ Scale-invariant signal to distortion ratio (SI-SDR)
# Install with pip
Install pysepm:
```
pip3 install https://github.com/schmiph2/pysepm/archive/master.zip
```


# TODO:
+ systematic tests for all measures
+ change resample method used (e.g. in NCM) to fit matlab implementation
