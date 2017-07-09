Heart Sound Stethoscope for Android
===================================

>  A fork of [Audio spectrum Analyzer for Android](https://code.google.com/p/audio-analyzer-for-android/) (See README.old for its original readme), 
	[Audio Spectrum Analyzer for Android](https://github.com/bewantbe/audio-analyzer-for-android) is released under the Apache License, Version 2.0. and 
	[Sample Equalizer](http://www.kevinboone.net/android_simple_eq.html) is released under the GNU Public Licence, v2.0.

  This software shows the frequency components' magnitude distribution (called spectrum) of the sound heard by your cell phone.

  This software, [Heart Sound Stethoscope for Android](https://github.com/algmaknick/heart-sound-stethoscope), is released under the Apache License, Version 2.0.


Features
--------

* Show [spectrum](http://en.wikipedia.org/wiki/Frequency_spectrum) or [spectrogram](http://en.wikipedia.org/wiki/Spectrogram) in real-time, with decent axis labels.
* Linear, Logarithm and (Musical) Note frequency axis support.
* You can put a cursor in the plot, for measurement or as a marker.
* Easy gestures to fine exam the spectrum: i.e. pinch for scaling and swipe for  view move.
* Show peak frequency in a moderate accuracy (FFT + interpolation).
* Show dB or [A-weighting dB (dBA)](http://en.wikipedia.org/wiki/A-weighting), although not suitable for serious application.
* Possible to take averages of several spectrum then plot, make the spectrum smoother.
* You may record the sound (while analyzing!) to a WAV file (PCM format). Then you can deal with it with your favorite tool.
* Support all recorder sources except those need root privilege (see list in Android reference: [MediaRecorder.AudioSource](http://developer.android.com/reference/android/media/MediaRecorder.AudioSource.html))
* Support all possible sampling rates that your phone is capable. e.g. useful to find out the native (or best) sampling format for you phone.
* Support listening of herat sound using wire or bluetooth connected headphones
* Support equalazing of sound 


Installation Requirements
-------------------------

* >= Android 2.2 (API Level 8). The recent version need Android 2.3 (API Level 9).
* External storage (e.g MicroSD card), if you want to record the sound.



Thanks
------

The code [Audio spectrum Analyzer for Android](https://code.google.com/p/audio-analyzer-for-android/), [Audio Spectrum Analyzer for Android](https://github.com/bewantbe/audio-analyzer-for-android), [Sample Equalizer](http://www.kevinboone.net/android_simple_eq.html) gives me oportunity to create working heart sound stethocope.

