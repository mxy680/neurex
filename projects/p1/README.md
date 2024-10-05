# Project Proposal: EEG-Based Face Recognition Using the N170 Response

## Overview
This project aims to classify visual stimuli using EEG data, focusing on the N170 response—a neural marker associated with face recognition. Our goal is to determine whether a subject is looking at a face or another object using machine learning models.

### Key Considerations
- **Classification Task**: Differentiate between seeing a face and not seeing a face.
- **EEG Channels**: Focus on the Occipito-Temporal channels (e.g., O1, O2, T5, T6, possibly T3 or T4).
- **Confounding Factors**: The N170 response is also observed when subjects view familiar objects, which may complicate face-specific recognition.
- **Potential Interference**: Inverted images of faces can disrupt the N170 response, making it a challenging test case.

### Dataset
We will use an online dataset from [OSF](https://osf.io/thsqg/), which includes images of faces and cars (as non-face objects). There is no information on subject familiarity with the cars, but the dataset is suitable for our initial approach.

### Challenges and Research Questions
- **Calibration**: Do we need to calibrate the model for each new subject, or is the N170 response distinct enough across individuals?
- **Feature Extraction**: Which features should we extract to maximize classification accuracy?
- **Model Design**: What type of network architecture will be best suited for this task (e.g., CNN, LSTM, or a hybrid model)?

## Project Goals
The project will serve as an educational experience, teaching members signal processing and deep learning techniques through hands-on practice and group collaboration.

### Weekly Sessions
Each session will include a short 15-minute lecture on a specific component of the project. Afterward, members will split into groups and work on implementing that component. Each group will have an experienced mentor for guidance.

- **Week 1**: Introduction to EEG data and the N170 response.
- **Week 2**: Preprocessing techniques (artifact rejection, filtering, re-referencing).
- **Week 3**: Epoching and synchronization.
- **Week 4**: Feature extraction and data augmentation.
- **Week 5**: Model development and architecture selection.
- **Week 6**: Testing and evaluation paradigms.

## Steps and Milestones

### Data Preprocessing
- **Can we find preprocessed data?**
  - **Yes**: Re-implement the authors' approach.
  - **No**: Perform manual preprocessing.
- **Techniques**: 
  - Artifact rejection
  - Filtering
  - Re-referencing
  - Epoching
  - Data synchronization
  - Level triggering

### Data Analysis
- **Loading and Organizing Data**: Efficiently manage and visualize EEG data.
- **Inspecting for Patterns**: Identify key features and neural responses.
- **Feature Extraction**: Determine which features are most relevant for classification.
- **Data Augmentation**: Enhance the dataset to improve model robustness.

### Model Development
- **Select Network Architecture**:
  - Deep Neural Network (DNN)
  - Convolutional Neural Network (CNN)
  - Long Short-Term Memory (LSTM)
  - Hybrid LSTM-CNN
- **Develop and Train Model**: Train on labeled data, test on unseen data.

### Evaluation and Testing
- **Testing Paradigm**: Define testing conditions and setup.
- **Model Evaluation**: Measure efficiency, accuracy, and robustness.

## To-Do List
- Finalize project details and scope.
- Break down the project into smaller subsections.
- Develop a week-by-week project plan.
- Assign group mentors and define roles.

This project is an exciting opportunity to delve into the complexities of EEG data and machine learning. It will not only contribute to research but also foster a deeper understanding of neurotechnology among club members.
