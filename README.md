# Python in Audio Research
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

The python ecosystem [is huge](http://anvaka.github.io/pm/#/galaxy/python?cx=-2700&cy=377&cz=5622&lx=-0.0869&ly=-0.2315&lz=-0.0338&lw=0.9684&ml=150&s=1.75&l=1&v=2015-09-27T13-00-00Z)

The idea of this repository is to create a comprehensive, curated list of python software and packages related to scientific research in audio.

## Related lists

There is already [this list](https://wiki.python.org/moin/PythonInMusic), but it not up to date and includes too many packages of special interest that are mostly not relevant for scientific applications. [Awesome-Python](https://github.com/vinta/awesome-python) is large curated list of python packages. However the audio section is very small.

### Audio Related Packages

#### Read/Write

* [(Py)Soundfile](https://github.com/bastibe/PySoundFile) - is an audio library based on libsndfile, CFFI, and NumPy
* [(Py)Soundcard](https://github.com/bastibe/PySoundCard) - is an audio library based on PortAudio for realtime audio processing
* [pySox](https://github.com/rabitt/pysox) - Python wrapper around sox
* [pyAV](https://mikeboers.github.io/PyAV) - PyAV is a Pythonic binding for FFmpeg or Libav
* [tinytag](https://github.com/devsnd/tinytag) - reading music meta data of MP3, OGG, FLAC and Wave files.
* [audiolazy](https://github.com/danilobellini/audiolazy) - Expressive Digital Signal Processing (DSP) package for Python.
* [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
* [python-sounddevice](https://github.com/spatialaudio/python-sounddevice) another portaudio wrapper

#### Transformations, General DSP

* FFT (part of scipy.fftpack (fast) and numpy (slower))
* [pyFFTW3](https://github.com/pyFFTW/pyFFTW) - wrapper around FFTW
* [NSGT](https://github.com/grrrr/nsgt) - non-stationary gabor transform, constant-q
* [MDCT](https://github.com/nils-werner/mdct) - MDCT transform
* [STFT](https://github.com/nils-werner/stft) - standalone STFT package
* [Gammatone](https://github.com/detly/gammatone) - Gammatone filterbank implementation
* [Resampy](https://github.com/bmcfee/resampy) - sample rate conversion.
* [PyRubberband](https://github.com/bmcfee/pyrubberband) - A python wrapper for [rubberband](http://breakfastquay.com/rubberband/) to do pitch-shifting and time-stretching.
* [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
* [pytftb](https://github.com/scikit-signal/pytftb) - A Python implementation of the MATLAB Time-Frequency Toolbox by Auger, Flandrin, Goncalves and Lemoine
* [PyWavelets](https://github.com/scikit-signal/pywt) - Discrete Wavelet Transform in Python
* [AudioTK](https://github.com/mbrucher/AudioTK) - DSP filter toolbox, mostly filters

#### Feature extraction

* [pyYAAFE](http://yaafe.sourceforge.net) - Python bindings for YAAFE
* [aubio](http://aubio.org/) - feature extractor, written in C, python interface
* [audiolazy](https://github.com/danilobellini/audiolazy) - Realtime Audio Processing lib, general purpose
* [muda](https://github.com/bmcfee/muda) -  Musical Data Augmentation

#### Speech Processing

* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - feature Extraction, Classification, Diarization
* [SIDEKIT](http://lium.univ-lemans.fr/sidekit/) - Speaker and Language recognition.
* [py-webrtcvad](https://github.com/wiseman/py-webrtcvad) -  interface to the WebRTC Voice Activity Detector
* [talkbox](http://scikits.appspot.com/talkbox) - General speech/signal processing algorithms. ⚠️ Not maintained.
* [SpeechRecognition](https://github.com/Uberi/speech_recognition) -  wrapper for several ASR engines and APIs, online and offline

#### Perceptial/Auditory Models

* [Loudness](https://github.com/deeuu/loudness) - perceived loudness, includes Zwicker, Moore/Glasberg model
* [Sound Field Synthesis Toolbox](Sound Field Synthesis Toolbox for Python)
* [BrianHears](http://www.briansimulator.org/docs/index.html) - General Auditory Models
* [cochlea](https://github.com/mrkrd/cochlea) - Inner ear models

#### Source Separation

* [NUSSL](https://github.com/interactiveaudiolab/nussl) - common source separation algorithms + framework
* [pyFASST](https://github.com/wslihgt/pyfasst) - Flexible Audio Source Separation Toolbox
* [commonfate](https://github.com/aliutkus/commonfate) - Common Fate Transform
* [beta_ntf](https://code.google.com/archive/p/beta-ntf/) - Non-Negative Tensor factorisation using PARAFAC
* [Simfa, NMF flavors](http://nimfa.biolab.si) - Several NMF flavors
* [NTFLib](https://github.com/stitchfix/NTFLib) - Sparse Beta-Divergence Tensor Factorization Library

#### Music Information Retrieval

* [librosa](https://github.com/librosa/librosa) - general audio and music analysis
* [mir_eval](https://github.com/craffel/mir_eval) - common heuristic accuracy scores for various MIR tasks.
* [essentia](http://essentia.upf.edu) - C++ based feature extractor + general purpose audio/MIR related DSP algorithms like pitch tracking, beat detection.
* [Madmom](https://github.com/CPJKU/madmom) MIR packages with strong focus on beat detection, onset detection and chord recognition.
* [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
* [Catchy](https://github.com/jvbalen/catchy) - Corpus Analysis Tools for Computational Hook Discovery

#### Symbolic Music / MIDI / Musicology

* [Music21](http://web.mit.edu/music21/) - a Toolkit for Computer-Aided Musicology
* [Mido](https://mido.readthedocs.io/en/latest/) - Realtime MIDI wrapper
* [Pretty-MIDI](https://github.com/craffel/pretty-midi) Utility functions for handling MIDI data in a nice/intuitive way
* [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.

#### Realtime applications

* [PYO](https://github.com/belangeo/pyo) - realtime audio engine similar supercollider

#### Web + Audio

* [TimeSide](https://github.com/Parisson/TimeSide) - Open web audio processing framework.

#### Packages to access public APIs / Parse Datasets

* [Youtube-Downloader](https://github.com/rg3/youtube-dl) - Download youtube videos (and the audio)
* [Soundcloud API](https://github.com/soundcloud/soundcloud-python) - A Python wrapper around the Soundcloud API
* [beets](http://beets.io/) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
* [dsdtools](https://github.com/faroit/dsdtools) - parse and process the demixing secrets dataset
* [medleydb](https://github.com/marl/medleydb) - parse medleydb audio + annotations

#### Bindings/Wrappers to other languages

* [VamPy Host](https://code.soundsoftware.ac.uk/projects/vampy-host) - interface compiled vamp plugins
* [PyAU](https://github.com/simlmx/pyau) - Python Audio Unit Host
* [rpy2](http://rpy2.bitbucket.org/) call R from python
* [Matlab_Wrapper](https://github.com/mrkrd/matlab_wrapper) runs code in matlab and returns results to python
* [CFFI]() - easily interface c libraries
* [pybind11](https://pypi.python.org/pypi/pybind11) - interface c++ code

## Tutorials/Books

* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) Excellent Book, look for the Tutorial notebooks
* [MIR Notebooks](http://musicinformationretrieval.com/)
* [http://www.scipy-lectures.org/index.html](Deep Introduction to Numpy and Scipy)
* [From Python to Numpy](http://www.labri.fr/perso/nrougier/from-python-to-numpy/)
* https://github.com/spatialaudio/selected-topics-in-audio-signal-processing-exercises
* https://github.com/unpingco/Python-for-Signal-Processing

### License

[![](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)
