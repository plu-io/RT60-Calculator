# RT60-Calculator

This calculator uses recordings of the decay of white/pink noise in a room to determine the RT60 values at third-octave frequency bands from 400Hz to 10kHz.

When ran, it looks for folders with .wav files. Each folder is treated as a separate sample, and each sample can have as few or as many .wav files as desired. Each sample has a resulting set of RT60 values that will be both printed and exported to an .xls file.

At the moment, the .wav files should be no less than 6.1 seconds in length, and the first 2 seconds should be steady noise. At 2 seconds, the steady noise should be stopped and the remaining time should only be noise decay.

There is an optional plot mode (PLOTFREQ = True) that will display each frequency band and the calculated RT60 slope of all samples.

What is this actually good for? If you have recordings of before and after the installation of sound treatment, you can calculate the acoustic absorption coefficient of the sound treatment. You can create a model of a room or space for reverb plugins in your favorite audio editor. You can take multiple readings in the same space to determine how consistent the reverberation is in different listening positions.
