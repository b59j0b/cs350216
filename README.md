java c
Assignment 2: Signals and Systems 
IMPORTANT: In previous assignments, students sometimes only supplied screenshots from ESystem as answers to the questions. This is not enough. While they looked good in most cases, this would not be enough in an exam. You need to provide an explanation to the question, even if that explanation can be sometimes be short.
1                        Spectra of different waveforms 
a.   What does the spectrum of the input sine wave at 1 kHz look like? 
b.   What does the spectrum of a pulse train with a fundamental frequency of 200 Hz look like? How does the input waveform. and spectrum change if the repetition frequency is changed to 100 Hz? To 50 Hz? To 25 Hz? To 5 Hz? 
c.   What does the spectrum of a single pulse look like? Try to explain this result using your answers to the previous question. 
d.   What does the spectrum of white noise look like in the program? Ideally, what should it look like? Why is white noise called “white”? 
e.   If the amplitude spectrum of white noise and an impulse are the same, what must be different about them? 
f.   Select the chirp and listen to it. What is its spectrum? What other waves is this similar to? 
2                        A simple amplifier 
a.   Set the system to be an amplifier of +0dB. What does this system do to signals? For sine waves, does that depend on the frequency of the sinusoid? 
b.   Set the system to be an amplifier of +6dB. What does this system do to signals? 
3                        A simple resonator 
a.   Set the system to be a simple resonator with a resonant frequency of 1000 Hz and a bandwidth of 100 Hz. If you didn’t set these numbers yourself, how would you determine them from the frequency response? 
b.   Set the system to be a simple resonator at 1000 Hz with a bandwidth of 100 Hz. Set the input signal to be a pulse train with a fundamental frequency of 100 Hz. Explain the shape of the output spectrum. 
c.   Why are some harmonics amplified more than others? 
d.   Set the system to be a simple resonator at 2 kHz with a bandwidth of 300 Hz. Set the input signal to be white noise. Explain the shape of the output spectrum. 
e.   What speech sound has the most similar quality to this? 
f.   Change the resonant frequency to 4 kHz. What speech sound is most similar now? 
4                        A simple low-pass filter 
a.   Set the system to be a low-pass filter at 1000 Hz. What would this system theoretically do to amplitude components of an input signal above 1000 Hz? 
b.   Set the input signal to be a sawtooth. Explain the shape of the output spectrum. Is the signal or system responsible for the presence of harmonics? Is the signal or system responsible for the envelope of the output spectrum? 
c.   Set the input signal to be a chirp, white noise and an impulse in turn. What’s the common factor in the output spectra? What practical implications does this have? 
5                        A band-pass filte代 写Assignment 2: Signals and SystemsPython
代做程序编程语言r for signal analysis 
a.   Set the input signal to be a pulse train with a fundamental frequency of 200 Hz. Set the system to be a band-pass filter between 950 Hz and 1050 Hz. What part of the input signal can be seen in the output signal? 
b.   Change the band-pass filter so that it is between 850 Hz and 950 Hz. Why is there very little energy in the output spectrum? 
c.   How do a) and b) show us how we might use band-pass filters to analyse a sound? 
6                        Effect of filtering on a speech signal 
a.   Record a file in Praat in which you say the word ‘six’. Save it as a file (e.g. ‘six.wav’) and upload it in ESystem 
b.   Set the system to be a low-pass filter at 1000 Hz.. Listen to the input and output signals. How would you describe the change in quality caused by the filter? 
c.   Set the system to be a high-pass filter at 1500 Hz. How has this filter affected the quality of the signal? 
d.   Set the system to be a band-pass filter between 300 Hz and 3500 Hz. How would you describe the change in timbre now? What does this quality remind you of? 
7                        Making a vowel sound 
a.   Set the input to be a sawtooth waveform. at 125Hz. Set the system to have a vowel-like frequency response with F1=500 Hz, F2=1500 Hz, F3=2500 Hz. What vowel does the output sound like? 
b.   Try to find resonator values that sound more like the ‘ee’ in ‘beet’ and the ‘o’ in ‘pot’. Hint: Put F1 low and F2 high for ‘ee’ (between 300 Hz and 2600 Hz). Put F1 high and F2 low for ‘o’ (centred around 1000 Hz). Ensure that the frequencies don’t overlap, so that F1c.   In human speech production of vowels like this, the input can be considered to come from the vibrating vocal folds in the larynx, which give off something like a sawtooth wave. In that case, what is the output signal, and what is the system? What changes in the system to give different vowels? 
8                        Adding up system responses 
Consider a cascade of three systems with the following amplitude responses. Draw the amplitude response of the complete cascade. What would be the amplitude response of the cascade if the position of Systems 1 and 2 were reversed?

9                        Noise through systems Try and draw the input and output spectra of white noise with an amplitude of 20 dB passed through the first system in the cascade of question 8.10                        Filtering individual sounds A sound consists of two frequencies of 1000 and 1050 Hz. This is picked up by a microphone in an environment that has lots of low-frequency hum (for pratical purposes, with all its energy below 500 Hz). Describe an equipment layout that would allow a psychoacoustician to select the low- or high-frequency sinusoid alone and lead the low-frequency one to the left ear and the high-frequency one to the right ear.


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
