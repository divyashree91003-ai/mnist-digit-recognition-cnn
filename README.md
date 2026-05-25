# mnist-digit-recognition-cnn
End-to-end CNN pipeline for handwritten digit classification — image preprocessing, annotation, model training &amp; evaluation on 70,000 MNIST images. ~99% accuracy

What this project covers

Pixel-level image data preprocessing and label annotation
CNN model design and training using TensorFlow/Keras
Model evaluation using Precision, Recall, F1-Score per digit class
Confusion Matrix visualization to identify misclassification patterns

Tech stack
ePythonCore language
TensorFlow / KerasModel building and training
NumPyArray and pixel operations
Matplotlib Accuracy/loss plots, image display Seaborn
Confusion Matrix heatmap
Scikit-learn
Classification report (Precision, Recall, F1)

Dataset
MNIST — 70,000 grayscale images of handwritten digits (0–9)

60,000 training images
10,000 test images
Each image: 28×28 pixels, single channel (grayscale)
Pixel values normalized from 0–255 to 0–1

Key concepts demonstrated

Image annotation — labeling 70,000 pixel-level images with digit class (0–9)
Data preprocessing — reshaping, normalization, one-hot encoding
CNN layers — Conv2D for feature detection, MaxPooling for compression, Dense for classification
Model evaluation — Accuracy, Precision, Recall, F1-Score, Confusion Matrix

