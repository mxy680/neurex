# Project Proposal: Scrolling with Your Mind Using SSVEP

## Overview
This project utilizes Steady-State Visual Evoked Potentials (SSVEPs) to enable a hands-free scrolling mechanism on a computer screen. By detecting specific neural responses when a subject looks at different flashing screens, we aim to create an intuitive way to scroll up and down using just gaze.

### Experimental Paradigm
- **Setup**: The subject sits in front of a computer setup with three screens.
- **Screen Stimuli**:
  - **Left Screen**: Flashes at 32 Hz (scroll down).
  - **Right Screen**: Flashes at 40 Hz (scroll up).
- **Interaction**: Subject looks at the left screen to scroll down and at the right screen to scroll up.

### Data Collection
- **Electrodes**: 8-channel EEG setup.
- **Protocol**: 
  - 15 blocks, each containing 12 trials.
  - Each trial involves gazing at one stimulus for 4 seconds, followed by a 1-second transition period.
- **Data Characteristics**:
  - Epochs extracted with a 0.135-second delay after stimulus onset.
  - Data sampled at 2048 Hz and downsampled to 256 Hz for analysis.

### Preprocessing Pipeline
1. **Bandpass Filtering**: Filter the EEG signals to isolate relevant frequency bands.
2. **FFT Analysis**: Apply Fast Fourier Transform (FFT) to extract frequency domain features.
3. **Filter Banks**: Use filter banks to focus on specific SSVEP frequencies.

### Model Selection
- **Artificial Neural Network (ANN)**: For basic classification of gaze direction.
- **Convolutional Neural Network (CNN)**: For capturing spatial and frequency features in EEG data.
- **Recurrent Neural Network (LSTM)**: For modeling temporal dependencies and sequential patterns.

### Project Outcome
Develop a reliable hands-free scrolling system using EEG-based SSVEP responses, enhancing accessibility and interaction with digital content.
