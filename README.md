# Fundamental Brain Wave Extractor
Different patterns of brainwaves can be recognized by their amplitudes and frequencies. Brainwaves can then be categorized based on their level of activity or frequency. It’s important to remember, though, that brainwaves are not the source or the cause of brain states, or of our experiences of our own minds – they’re just some of the detectable reflections of the complex processes in the brain that produce our experience of being, thinking, and perceiving.

The five Brain Waves are:-
* Gamma Wave:- Above 31Hz, Associated State: Heightened perception, learning, problem-solving tasks
* Beta Wave:- 14Hz-30Hz, Associated State: Alert, normal alert consciousness, active thinking
* Alpha Wave:- 9Hz-14Hz, Associated State: Physically and mentally relaxed
* Theta Wave:- 4HZ-9Hz, Associated State: Creativity, insight, dreams, reduced consciousness
* Delta Wave:- Below 4Hz, Associated State: Sleep, dreaming

## Filtering Design System
Here we have implemented the basic multi-band filtering system for performance evaluation by using EEG Signal. The methodology used for the design of the digital filter is by using the Chebyshev Type-I filter and Bilinear Transformation. The specification parameters required to design the filters are:-

* Passband edge frequency(ies) error from the desired frequency range (Hz)
* Transition Bandwith (Hz)
* Passband Attenuation (dB)
* Stopband Attenuation (dB)
* Sampling Rate / Sampling Frequency (Hz)

There are two types of methods avaible either one can see specific extracted wave or all the waves to analyze the waveforms.

The sample results with below specifications:-
* Passband edge frequency(ies) error from the desired frequency range (Hz) = 1 Hz
* Transition Bandwith (Hz) = 3 Hz
* Passband Attenuation (dB) = 1 dB
* Stopband Attenuation (dB) = 40 dB
* Sampling Rate / Sampling Frequency (Hz) = 200 Hz

![Option-1 Sample](/test_image-1.png)
![Option-2 Sample](/test_image-2.png)

