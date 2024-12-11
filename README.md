# HMS---Harmful-Brain-Activity-Classification
Classify seizures and other patterns of harmful brain activity in critically ill patients.
This project focuses on classifying harmful brain activity patterns, including seizures, in critically ill patients using EEG spectrogram data. The goal was to develop and evaluate various machine learning and deep learning models to achieve high classification accuracy.

Dataset
Source: Kaggle
Data Format: EEG spectrogram data provided in .parquet format
Preprocessing: Converted .parquet data into .npy format for easier handling and compatibility with deep learning frameworks.

Approach
1. Preprocessing
    Converted .parquet EEG data to .npy format for efficient loading and processing.
    Applied spectrogram-based feature extraction to prepare the data for model input.
2. Base Model
    Used EfficientNetB2 from the official Keras notebook as the starting model.
3. Experimentation with Models
    We implemented and compared multiple models to find the most effective architecture for classification:
   
        * ResNet-50
   
        * VGG-11
   
        * LSTMs
   Modified versions of the above models with state-of-the-art architectural adjustments.
5. Evaluation
     Predicted training and validation accuracies for all models.
     Visualized training and validation accuracy and loss graphs to compare model performance.
6. Final Model
     Achieved significant improvements using a modified EfficientNetV2 architecture with KerasCV.

Results
     Provided detailed comparisons of training and validation accuracies across models.
     Final results demonstrated that the modified EfficientNetV2 outperformed other architectures in classification accuracy.
Visualizations
     Training and validation accuracy and loss graphs were plotted to illustrate model performance.
