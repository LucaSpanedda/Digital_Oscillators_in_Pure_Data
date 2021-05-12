# Digital Oscillators in Pure Data via different synthesis methods

## table-lookup oscillators [0.00 - 0.99]
Table-lookup synthesis (or Wavetable-lookup synthesis) (Roads 1996) 
is a class of sound synthesis methods using the waveform tables by table-lookup, 
called "table-lookup oscillator" technique. 
The length of waveforms or samples may be varied by each sound synthesis method, 
from a single-cycle up to several minutes.

## additive synthesis oscillators [1.00 - 1.99]
Additive synthesis is a sound synthesis technique that creates timbre 
by adding sine waves together. 
The timbre of musical instruments can be considered 
in the light of Fourier theory to consist of multiple harmonic 
or inharmonic partials or overtones.

## zero padding granular synthesis oscillators [2.00 - 2.99]
Granular synthesis is a basic sound synthesis method that operates on the microsound time scale. 
It is based on the same principle as sampling. 
However, the samples are not played back conventionally, 
but are instead split into small pieces of around 1 to 50 ms. These small pieces are called grains.
Here we use the method of adding digital zero for reduce the grain size and enlarging the array size.
Zero padding is a simple concept; 
it simply refers to adding zeros to end of a time-domain signal to increase its length. 
The example 1 MHz and 1.05 MHz real-valued sinusoid waveforms we will be using throughout 
this article is shown in the following plot: The time-domain length of this waveform is 1000 samples.
