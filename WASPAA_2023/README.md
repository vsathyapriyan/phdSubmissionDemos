## Audio Demos for the Submissions
# SPEECH ENHANCEMENT USING BINARY ESTIMATOR SELECTION APPLIED TO HEARING AIDS WITH A REMOTE MICROPHONE

The demos consist of monoaural left signals for different noise and SNRs, headphones are recommended for listening.

- The monaural left signals are generated using measured HRIRs from the Kayser Database [1]
- The speech signals are taken from the VCTK Corpus [2]

### Naming Convention

- **X** = *SNR at the HA microphone signals*
- **Y** = *TDOA assumed*
- **Z** = *Noisy Type in the HA microphone signals*

1. **Noisy_HA_X_Z.wav** - Noisy signal at the HA reference microphone.
2. **MWF_X_Z.wav** - MWF estimate using only the HA microphone signals.
3. **LP_Y_Z.wav** - LP estimate using the only the remote microphone signal.
4. **Prop_X_Y_Z.wav** - Proposed method estimate, using HA and remote microphone signals.

**Note: All the remote microphone signals in these examples are at an SNR = 30 dB iin WGN.**


### References
[1] H. Kayser, S. D. Ewert, J. Anemüller, T. Rohdenburg, V. Hohmann, and B. Kollmeier,“Database of Multichannel In-Ear and Behind-the-Ear Head-Related and Binaural Room Impulse Responses” ,EURASIP Journal on Advances in Signal Processing, Volume 2009, 10 pages, Article ID 298605, 2009.

[2] Yamagishi, Junichi; Veaux, Christophe; MacDonald, Kirsten. (2019). CSTR VCTK Corpus: English Multi-speaker Corpus for CSTR Voice Cloning Toolkit (version 0.92), [sound]. University of Edinburgh. The Centre for Speech Technology Research (CSTR). https://doi.org/10.7488/ds/2645.
