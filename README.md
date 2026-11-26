# Rotation Detection Enhanced Convolutional Neural Network (RDECNN)
Enhances standard CNN architecture with improved sensitivity and adaptability to object rotation.

Training Scripts & Methods:
  - Train_CNN.py / Train_RDECNN.py: Entry points for training the baseline CNN and enhanced RDECNN models.
  - train(): Trains the model solely on original images.
  - mixed_train(): Trains on a combined dataset of original and rotated images (Data Augmentation).

 Evaluation Methods:
   - test(): Evaluates model accuracy on the original unrotated test set.
   - polluted_test(): Evaluates rotation robustness exclusively on rotated test images.
