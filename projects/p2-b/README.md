# Project Proposal: Scrolling with Motor Imagery and Motor Potentials

## Overview
This project explores using motor-related brain signals to enable scrolling on a screen. Instead of relying on traditional inputs, we aim to detect motor-evoked potentials to scroll up or down based on specific movements. We’ll start by using actual physical movements and later extend the project to motor imagery-based scrolling.

### Experimental Setup
- **Electrodes**: C3, C4, CP1, CP2, P3, P4
- **Subject Position**: Seated in front of a screen.
- **Interaction**: Scroll up or down based on predefined movements (e.g., hand movements).

### Paradigm and Data Acquisition
- **Movement Types**: Determine which movements produce the clearest motor-evoked potentials.
- **Binary Response**: Map a specific movement to scrolling up and another to scrolling down.
- **Trials**: Each trial involves performing a movement for a set period.
- **Epochs**: Repeat movements within each trial for consistent signal capture.

### Key Considerations
- **Movement vs. Intention**: Can we isolate motor intention without requiring actual movement?
- **Standardization**: How do we synchronize the movements with the EEG signals for consistent epochs?
- **Motor Intention**: Evaluate the feasibility of transitioning to motor imagery as an extension of the project.

### Data Processing and Analysis
1. **Preprocessing**: Clean and filter the EEG signals to remove noise.
2. **Signal Processing and Feature Extraction**: Extract key features from motor-evoked potentials.
3. **Deep Learning Models**: Use neural networks to classify movements and map them to technological responses.

### Project Outcome
Create a system that allows users to scroll on a screen using motor-evoked potentials, with the potential to transition to motor imagery for a completely hands-free experience.
