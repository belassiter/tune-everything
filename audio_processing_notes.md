Just some random notes on audio processing

# FFT
Converts data from time space to frequency space
https://en.wikipedia.org/wiki/Fast_Fourier_transform

# HPS (Harmonic Product Spectrum)
Identifies and removes overtones, emphasizing the fundamental pitch
Helps clean up 
http://musicweb.ucsd.edu/~trsmyth/analysis/Harmonic_Product_Spectrum.html

# Autocorrelation
https://stackoverflow.com/questions/7489531/autocorrelation-heuristics-for-a-tuner

# Quantization
There's an inherent issue with quantization for pitch data. 
- Typically FFTs are quantized by frequency increments.
- That means your pitch quantization is different for different octaves (i.e. 1 cent is a different number of Hz in different octaves)
- I remember having to do some shenanigans to get this to work

# Scrolling speed
~5 seconds to cross a tablet-sized portrait screen seems good
