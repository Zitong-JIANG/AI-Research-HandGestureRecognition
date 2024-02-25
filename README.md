# AI-Research on Hand Gesture Recognition

## Introduction
This repository hosts our research project on hand gesture recognition using Convolutional Neural Networks (CNN). Our focus is on interpreting hand gestures from images, enhancing communication for those who use sign language.

## Dataset
We trained our model on the American Sign Language (ASL) Dataset, which includes a diverse range of hand gesture images.

## Model
Our approach employs a CNN, known for its effectiveness in image recognition tasks.

### Experiments
We conducted two main experiments:
#### Experiment I
- Utilized the original ASL dataset for initial training and testing.
#### Experiment II
- Employed a different set of raw data to train and test the model, comparing results with Experiment I.

### Recognition Process
Our model's development involved several key stages:
- **Data Acquisition**: Gathering images of hand gestures.
- **Data Preprocessing**: Preparing images for processing.
- **Model Training**: Educating the CNN on recognizing gestures.
- **Model Evaluation**: Assessing accuracy and efficacy.
- **Robustness Testing**: Evaluating performance under various conditions.

## Performance
- Accuracy on the existing dataset: 98.57%
- Accuracy on an extended dataset: 94.73%

## Future Work
Improvements focus on:
1. **Advanced Image Preprocessing**: Using sophisticated techniques like U-Net for improved segmentation, enhancing training data uniformity and generalization.
2. **Transfer Learning**: Applying pre-trained models to capture low-level features and fine-tuning them for gesture recognition.

Future development aims to enable real-time, dynamic recognition of complex sign language expressions. This involves real-time camera integration, processing video frames during training, and providing instant feedback for applications like live sign language interpretation.

## References
- ASL Dataset: [Kaggle Link](https://www.kaggle.com/datasets/ayuraj/asl-dataset) (Accessed: 2024/1/15)
- Dhall, I., et al. "Automated Hand Gesture Recognition using a Deep Convolutional Neural Network model." 2020 10th International Conference on Cloud Computing, Data Science & Engineering (Confluence) (2020).
- Geek for Geek on CNN: [Link](https://www.geeksforgeeks.org/cnn-introduction-to-pooling-layer/) (Accessed: 2024/1/15)
- Srivastava, N., "Dropout: A Simple Way to Prevent Neural Networks from Overfitting", Journal of Machine Learning Research, 15, 1929-1958 (2014).
- WHO on Deafness and Hearing Loss: [WHO](https://www.who.int/news-room/fact-sheets/detail/deafness-and-hearing-loss)
- State of Rhode Island, CDHH on ASL: [CDHH](https://cdhh.ri.gov/information-referral/american-sign-language.php)
- Zhou, Y., et al. "An improved all-optical diffractive deep neural network with less parameters for gesture recognition." J. Vis. Commun. Image Represent (2023).
