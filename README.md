# Speech & Audio Interview Questions
Feel free to dive into any section that interests you :-)

![Diagram](images/diagram-v1.png)

<details>

<summary>Table of contents</summary>

- [Speech \& Audio Algorithms and Machine Learning](#speech--audio-algorithms-and-machine-learning)
- [Table of contents](#table-of-contents)
- [Acoustics ](#acoustics-)
  - [Sound ](#sound-)
  - [Reverberation ](#reverberation-)
- [Electronics ](#electronics-)
- [Signal Processing ](#signal-processing-)
  - [Digital Filtering ](#digital-filtering-)
  - [Audio Features ](#audio-features-)
  - [Audio Transforms ](#audio-transforms-)
  - [Compression ](#compression-)
  - [Noise Reduction ](#noise-reduction-)
- [Deep Learning ](#deep-learning-)
  - [Sound Classification ](#sound-classification-)
  - [Speech Enhancement ](#speech-enhancement-)
  - [Speaker Recognition ](#speaker-recognition-)
  - [Speech Recognition ](#speech-recognition-)
</details>

# Acoustics <a name="acoustics"></a>

## Sound <a name="sound"></a>

* What is the difference between sound power and sound intensity?
* How do we convert sound pressure between dB SPL and pascals (Pa)?
* What’s the difference between dB SPL and dB(A)?
* How do density and elasticity of a medium affect sound speed?
* What is the Doppler effect, and how does it work?

## Reverberation <a name="reverb"></a>

* What is room impulse response (RIR), and how is it measured?
* What are the effects of reverberation in room acoustics?
* How is reverberation measured (RT60)?
* How can we simulate reverberation digitally?
* What methods are used to analyze time delay in audio signals?

# Electronics <a name="electronics"></a>

* What should you consider when choosing a microphone?
* How do you calibrate a microphone?
* What is an Anti-Aliasing filter?
* What are typical sampling rates and bit ranges for audio?
* What are the common interfaces used in digital audio systems?

# Signal Processing <a name="signal_processing"></a>

## Digital Filtering <a name="digital_filter"></a>

* How do FIR and IIR filters differ?
* What does the filtfilt function do?
* How does a preamplifier work in a microphone setup?
* How is zero-phase filtering done, and what are its benefits?
* How can we test the stability of digital filters?

## Audio Features <a name="features"></a>

* What is signal energy, and how do we calculate it?
* What are the uses of ZCR and FFT in audio analysis?
* How can we estimate the pitch of speech?
* What are common audio features, and how do we extract them?
* How can we test the similarity between two audio signals?

## Audio Transforms <a name="audio_transforms"></a>

* What is STFT, and how is it done?
* What are the key considerations when implementing STFT?
* What is MFCC used for in audio processing?

## Compression <a name="compression"></a>

* How does the number of quantizer levels change the dynamic range?
* How does AD-PCM work?
* What is LPC, and how does it represent speech?
* How is mu-law quantization different from linear quantization?

## Noise Reduction <a name="noise_reduction"></a>

* How does spectral subtraction work?
* What is the Wiener filtering method?
* When is wavelet-based denoising useful?
* What is Speech Presence Probability (SPP), and how is it used?
* How is adaptive filtering used for noise reduction and echo cancellation?

# Deep Learning <a name="deep_learning"></a>

## Sound Classification <a name="classification"></a>

* What are the challenges in sound classification?
* How is deep learning used in sound classification?
* What metrics evaluate classification models?

## Speech Enhancement <a name="enhancement"></a>

* What deep networks are common for speech enhancement?
* How is phase handled in speech enhancement?
* Why might MSE not be the best loss function?
* What metrics evaluate speech enhancement models?

## Speaker Recognition <a name="speaker"></a>

* What’s the difference between diarization, identification, and verification?
* What networks are used for speaker recognition?
* What are speaker embeddings, and how are they used?
* How are x-vectors different from i-vectors?

## Speech Recognition <a name="recognition"></a>

* What methods are used for speech recognition?
* How is audio prepared for speech recognition?
* How are speech recognition models evaluated?
* How does Whisper use weak supervision?
* What is the Whisper model architecture?
* What are the key features and differences between Wav2Vec models?
* How does CTC encoding help Wav2Vec?
* What’s the role of Beam Search in Wav2Vec?
