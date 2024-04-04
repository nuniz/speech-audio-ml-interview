# Speech & Audio Algorithms and Machine Learning

Feel free to dive into any section that interests you or aligns with your focus.

# Table of contents

- [Speech \& Audio Algorithms and Machine Learning](#speech--audio-algorithms-and-machine-learning)
- [Table of contents](#table-of-contents)
- [Acoustics ](#acoustics-)
  - [Sound ](#sound-)
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

# Acoustics <a name="acoustics"></a>

## Sound <a name="sound"></a>

* What is sound intensity, and how do acoustic instruments measure it?
* How do you convert sound pressure between dB SPL and pascals (Pa)?
* Discuss the difference between dB SPL and dB(A) scales. 
* How do the density and elasticity of a medium affect the speed of sound?
* Discuss the concept of reverberation and its implications in room acoustics.
* What methods are used to measure reverberation (RT60)?

# Electronics <a name="electronics"></a>

* What factors would you consider when selecting a microphone?
* Describe the microphone calibration process.
* Describe the process of converting analog signals into digital data.
* What is the role of an Anti-Aliasing filter?
* What are the typical sampling rates and range of bits commonly used in audio?
* What digital protocols are used in microphones, such as I2S (Inter-IC Sound) and PCM (Pulse Code Modulation)?

# Signal Processing <a name="signal_processing"></a>

## Digital Filtering <a name="digital_filter"></a>

* What are the key differences between Finite Impulse Response (FIR) and Infinite Impulse Response (IIR) filters?
* Explain the usage of the filtfilt function.
* How can zero-phase filtering be implemented, and what advantages does it offer?
* What are the various methods for testing the stability of digital filters?

## Audio Features <a name="features"></a>

* What is energy in the context of speech signals, and how is it computed?
* What are the advantages of using the zero-crossing rate (ZCR) compared to the Fast Fourier Transform (FFT)?
* What methods are commonly used to estimate the pitch of a speech signal?
* What are some common audio features, and how are they extracted?
* How can we test the similarity between two audio signals?
* How does the GCC-PHAT algorithm differ from cross-correlation?

## Audio Transforms <a name="audio_transforms"></a>

* Explain the Short-Time Fourier Transform (STFT) and its implementation.
* Why do we use zero padding in STFT?
* Why do we use overlap and windowing in STFT?
* What are the trade-offs when determining the STFT parameters?
* What do people usually use Mel-frequency cepstral coefficients (MFCC) for in audio processing?

## Compression <a name="compression"></a>

* How does the number of quantizer levels affect the dynamic range?
* Describe the operation of an adaptive differential pulse code modulation (AD-PCM).
* What is linear predictive coding (LPC), and how does it represent speech signals?
* How does the mu-law quantization differ from linear quantization, and what advantages does it offer?

## Noise Reduction <a name="noise_reduction"></a>

* How does spectral subtraction reduce noise work?
* What is the Wiener filtering method?
* When are wavelet-based denoising techniques effective?
* What is Speech Presence Probability (SPP), and how is it used in noise reduction?
* How is adaptive filtering used in noise reduction and echo cancellation?

# Deep Learning <a name="deep_learning"></a>

## Sound Classification <a name="classification"></a>

* What challenges are faced in sound classification tasks?
* How can deep learning be applied to sound classification?
* What metrics assess classification model performance?

## Speech Enhancement <a name="enhancement"></a>

* What deep network architectures are common for speech enhancement?
* How is the phase treated in speech enhancement?
* What loss functions are typical in speech enhancement, and why might Mean Squared Error (MSE) have limitations?
* Which objective metrics evaluate speech enhancement, and how do they differ?

## Speaker Recognition <a name="speaker"></a>

* Distinguish between speaker diarization, identification, and verification.
* What are typical deep network architectures for speaker recognition?
* What are speaker embeddings, and how are they extracted and used?
* What are x-vectors, and how do they differ from i-vectors?

## Speech Recognition <a name="recognition"></a>

* What methods are used in speech recognition?
* How is audio data preprocessed for speech recognition?
* What evaluation methods are used for speech recognition models?
* How does Whisper employ weak supervision, and what is its architecture?
* Describe training and optimization for Whisper models.
* What distinguishes Wav2Vec2 from Wav2Vec?
* How does CTC encoding address limitations in decoding Wav2Vec outputs?
* Explain the role of Beam Search in Wav2Vec models.
