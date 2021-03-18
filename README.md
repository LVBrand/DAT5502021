# DAT550-2021 Final Project

## Overview

Musical Sheet/Tab Generator	

### Description:

Create neural network capable of "listening to music waveforms" and generate sheet musical notation equivalent in "abc" language.

#### Expected results:
- Train a deep neural network model able to provide given outputs from music waveforms with good accuracy

#### Goal:
To go from music waveforms to  abc format such as in https://piano2notes.com/file/7747aefc-c516-47b3-abdb-dbcda1649a65 (Does not generate abc but  music sheet)
Dataset:
http://theremin.music.uiowa.edu/MISpiano.html


### Utilities:
https://github.com/attejensen/abctool
https://github.com/g4brielvs/python-tomita

## Algorithms
- Spectrogram
- MFCC Spectrogram
    https://en.wikipedia.org/wiki/Mel-frequency_cepstrum#:~:text=From%20Wikipedia%2C%20the%20free%20encyclopedia,nonlinear%20mel%20scale%20of%20frequency.

## Python audio Libraries
- https://mido.readthedocs.io/en/latest/
- https://wiki.python.org/moin/PythonInMusic

## Tutorials
https://github.com/tensorflow/docs/tree/master/site/en/



## Candidate datasets
- https://www.kaggle.com/arshadgeek/piano-notes-transcription
- https://www.kaggle.com/juliancienfuegos/what-is-a-note
- https://www.kaggle.com/soumikrakshit/classical-music-midi
- https://magenta.tensorflow.org/datasets/maestro#v300

### MIDI FIle format specification
https://github.com/colxi/midi-parser-js/wiki/MIDI-File-Format-Specifications

## Kaggle Repository
https://www.kaggle.com/asahicantu/dat550-2021-final-project/

## Tasks
[] Try different preprocessing techniques and find out its differences



0. Transform Audio MIDI Files into waveforms
1. Iterate over best features to extract and process
2. Candidate algorithms to use
   1. Given an audio sample dataset, split a file into smaller time chunks
   2. Fourier transformation
   3. Frequency over time diagram
4. [] Get Audio Files Data
   1. Creating them  or get dataset
   2. 
5. [] Create feature extraction mechanism
6. [] 

 

