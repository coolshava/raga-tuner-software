# raga-tuner-software
Documentation and future files for raga tuner software.

The idea behind this came from my reemerging interest in taking up the study of Indian classical music. There are apps that can determine the absolute pitch for tuning instruments such as guitars, but Indian music (Hindustani in particular) has a relative pitch system, in which all the solfege notes are relative to the tonic, Sa. 
More interestingly, when consulting the ancient treatises, the intervals between notes are not equal, as in the Western equal temperament scale, but use just intonation, with various intervals being considered as microtones. 

Functionality:
Take in an input pitch, set it as the tonic, and for any other input pitch, determine, rather than the absolute pitch/frequency (or in addition to it) the relative interval with the tonic, and its classification in Hindustani music within the 22 shruti scale.

Options for visual output:
A graph similar to that of the Android app VocalPitchMonitor, similar to that of an oscilloscope or continual graph, could work, to record an entire practice session. However, a simpler GUI could include, similar to most tuner apps,
* a dial or other way of displaying only the current note
* a button to set a note as the tonic
* a display showing the European name and frequency of the current tonic
* a display showing the currently received note and its relation to the tonic.

Language: MATLAB or C++ as I learn more functionality. It would be awesome to put this on a hardware board eventually but my abilities are currently well beneath that.

Feature creep is expected and already happening but this is a student project, being undertaken by someone with basically no software experience, so expect progress to be slow. Any exercises in MATLAB or C++ that are used for parts of this will be posted here. I will be working on a sketch of the gui, and some pseudocode but anyone who would like to offer advice is welcome to do so.
