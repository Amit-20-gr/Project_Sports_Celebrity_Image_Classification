# Project_Sports_Celebrity_Image_Classification
## Overview
This project focuses on classifying sports celebrities from images using Python libraries such as numpy, matplotlib, scikit-learn (sklearn), and OpenCV. It involves several steps, including image loading, face and eye detection, image cropping, wavelet transformation for feature extraction, and model training using various classifiers. The best-performing model is selected through grid search cross-validation (GridSearchCV).

## Steps Involved
### Image Loading: 
Images are loaded using OpenCV.

### Face and Eye Detection:
Haar cascades are employed to detect faces and eyes in the images.

### Image Cropping: 
Cropped images of faces and eyes are generated. A directory structure is created where cropped images are organized by individual sports celebrity names.

### Image Processing:
Wavelet transformation is applied for feature extraction, converting images into black and white pixels.

### Model Training: 
Machine learning models (SVM, Random Forest, Logistic Regression) are trained on the extracted features. Each celebrity name is assigned a numerical label for model training.

### Model Evaluation: 
The accuracy of each trained model is evaluated using GridSearchCV. Logistic Regression emerges as the best model with an accuracy of approximately 97%.

### pyhton Library 
numpy
matplotlib
scikit-learn
OpenCV
