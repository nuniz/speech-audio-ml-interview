# Speech & Audio Algorithms and Machine Learning

This guide aims to assist you in preparing for interviews by providing a comprehensive set of questions covering various
aspects of the field.

# Table of contents

1. [Acoustics](#acoustics)
    - [Sound](#sound)
    - [Reverberation](#reverb)
    - [Filter Design](#filter)
3. [Electronics](#electronics)
4. [Signal Processing](#signal_processing)
    - [Digital Filtering](#digital_filter)
    - [Feature Extraction](#features)
    - [Localization](#localization)
    - [Audio Transforms](#audio_transforms)
    - [Compression](#compression)
    - [Noise Reduction](#noise_reduction)
5. [Deep Learning](#deep_learning)
    - [Sound Classification](#classification)
    - [Speech Enhancement](#enhancement)
    - [Speaker Recognition](#speaker)
    - [Speech Recognition](#recognition)

Feel free to dive into any section that interests you or aligns with your study focus.

# Acoustics <a name="acoustics"></a>

## Sound <a name="sound"></a>

* Explain the concept of sound intensity and how it is measured.
* How do you convert sound pressure from dB SPL to pascals (Pa)?
* Discuss the difference between dB SPL and dB(A) scales. 
* How does the density and elasticity of a medium influence the speed of sound?

## Reverberation <a name="reverb"></a>

* Discuss the concept of reverberation and its implications in room acoustics. 
* What methods are used to measure reverberation (RT60)?

## Filter Design <a name="filter"></a>

* Define acoustic impedance.
* Describe the operation of an acoustic resonator and its applications in filtering or amplifying specific frequency components of a sound signal.
* What are the main types of acoustic materials used for sound absorption?

# Electronics <a name="electronics"></a>

* What factors would you consider when selecting a microphone for a specific application?
* Describe the process of converting analog acoustic signals captured by a microphone into digital data.
* What is the role of an Anti-Aliasing filter?
* Explain the concept of microphone sensitivity and how it is measured.
* Explain the digital protocols used in microphones, such as I2S (Inter-IC Sound) and PCM (Pulse Code Modulation)?
* How do you calibrate electronic equipment used for acoustic measurements?
* How do you analyze the frequency response of a microphone?

# Signal Processing <a name="signal_processing"></a>

## Digital Filtering <a name="digital_filter"></a>

* Discuss the applications of LPF, BPF, HPF in practical scenarios.
* What are the key differences between Finite Impulse Response (FIR) and Infinite Impulse Response (IIR) filters?
* Explain the usage and significance of the filtfilt function.
* How can zero-phase filtering be implemented, and what advantages does it offer?
* What are the various methods for testing the stability of digital filters?

## Feature Extraction <a name="features"></a>

* What is energy in the context of speech signals, and how is it computed?
* Explain the concept of zero-crossing rate.
* What methods are commonly used to estimate the fundamental frequency (pitch) of a speech signal?
* What is linear predictive coding (LPC), and how does it represent speech signals?

## Localization <a name="localization"></a>

* How does the GCC PHAT algorithm differ from cross-correlation?
* Explain the computational complexity of GCC PHAT-based sound source localization algorithms and any strategies used to mitigate it in real-time systems?

## Audio Transforms <a name="audio_transforms"></a>

* Explain the Short-Time Fourier Transform (STFT) and its implementation.
* Provide examples of common window functions used in signal processing.
* Discuss the significance of overlap and its applications.
* Why is zero padding used in STFT, and how does it impact the analysis of signals?
* What trade-offs should be considered when determining the parameters such as time window, stride, and NFFT in STFT
  analysis?
* For what purpose are Mel-frequency cepstral coefficients (MFCC) typically employed in acoustic signal processing?

## Compression <a name="compression"></a>

* What are the typical sampling rates used in digital audio?
* What is the range of bits per sample commonly used for digital audio?
* How does the number of quantizer levels affect the signal-to-noise ratio (SNR) or dynamic range?
* Why might audio compression algorithms designed specifically for speech signals not work well for nonspeech audio signals?
* How does the mu-law transformation differ from linear quantization, and what advantages does it offer?
* Describe the operation of an adaptive differential pulse code modulation (AD-PCM).
* How does AMR achieve adaptive bit-rate encoding, and what are the advantages of this approach?

## Noise Reduction <a name="noise_reduction"></a>

* Discuss the principles of adaptive filtering in signal processing and its applications in tasks such as noise cancellation and system identification.
* Describe the process of signal denoising and common techniques used, such as wavelet denoising, Wiener filtering, or median filtering.
* What is speech-presence-probability (SPP) in the context of audio signal processing?
* Describe the principles underlying beamforming techniques in acoustic signal processing, including delay and sum, MVDR, and LCMV approaches.

# Deep Learning <a name="deep_learning"></a>

## Sound Classification <a name="classification"></a>

* Discuss the challenges associated with sound classification tasks, such as background noise, varying acoustic environments, and the presence of multiple sound sources.
* How can deep learning be applied to sound classification tasks?
* What is wave-gram and what is this different from spectrogram?
* What are some evaluation metrics used to assess the performance of classification models?

## Speech Enhancement <a name="enhancement"></a>

* What are typical deep network architectures for speech enhancement?
* How is the phase treated when using the absolute spectrogram as input for speech enhancement?
* What are the objective metrics for speech enhancement evaluation? Could you discuss the difference between PESQ, STOI, and SNR?
* What are the loss functions typically used for speech enhancement? What are the cons of using Mean Squared Error (MSE)?

## Speaker Recognition <a name="speaker"></a>

* Can you explain the distinctions between speaker diarization, speaker identification, and speaker verification?
* What are the common deep network architectures used for speaker recognition tasks?
* What are speaker embeddings, and how do they represent the characteristics of a speaker's voice?
* How are i-vectors extracted from speech signals, and what features do they capture?
* What role does the Universal Background Model (UBM) play in generating i-vectors?
* What are x-vectors, and how do they differ from i-vectors?

## Speech Recognition <a name="recognition"></a>

* Can you explain some of the techniques used in speech recognition, such as Hidden Markov Models (HMMs) and Deep Learning?
* How do you preprocess audio data for speech recognition models?
* How do you handle background noise in speech recognition models?
* How do you evaluate the accuracy of speech recognition models?
* How does Whisper use weak supervision?
* Can you describe the architecture of Whisper?
* How are Whisper models trained, and how do you optimize their performance?
* What is Wav2Vec2, and how does it differ from Wav2Vec?
* What are the limitations of using a naive decoding approach for Wav2Vec outputs, and how does Connectionist Temporal Classification (CTC) encoding help address these limitations?
* Describe the Beam Search algorithm and its role in Wav2Vec models.
