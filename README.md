# ML Nonlinear Equalization

**Nonlinear Equalization of a Complex Upsampled Signal**: This involves handling a signal that has been upsampled, pulse-shaped, and affected by noise, inter-symbol interference, and nonlinear effects. The tasks include:

  - Initialization: Loading signals from provided data, scatterplotting received and target signals, and dividing data into training, validation, and test datasets.
  
  - MSE Training: Designing and training a nonlinear neural network for signal equalization based on MSE loss, including plotting training vs validation loss and displaying a scatterplot of equalized signal.
    
  - Hard-decision Demapper: Implementing and applying a hard-decision demapping method based on Euclidean distance, calculating symbol error rate (SER), applying binary reflected gray labeling, and determining bit error rate (BER).
    
  - Soft-decision Demapper: Defining and applying a soft-decision demapping method based on AWGN demapper, calculating a posteriori probabilities, and estimating equivocation.
    
  - CE Training: Designing and training a neural network for joint equalization and demapping based on cross-entropy loss, with evaluation of SER, BER, and equivocation estimate.
