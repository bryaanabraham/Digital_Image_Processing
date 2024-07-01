# Logo Detection and Classification Project

## Overview
This project aims to develop a machine learning model for detecting and classifying logos in images. The system processes collected data, trains a model, and performs real-time testing to ensure product quality and authenticity. 

## Architecture
The project architecture is divided into two ML model: 
1. Logo Detection and Classification ('Fake' or 'Genuine')
2. Product Quality Check ('Spoiled' or 'Not Spoiled')

### Model Training
1. **Data Collection**: Collect images containing logos for training the model.
2. **Dataset Preprocessing**: Preprocess the collected dataset to prepare it for training.
3. **Logo Classification/Detection**: Train a machine learning model to classify and detect logos.
4. **Brand Logo Analysis Model**: Analyze logos to identify brand-specific features.
5. **Product Quality Analysis**: Evaluate the quality of products based on logo analysis.
6. **ML Model Creation and Retraining**: Create and retrain the model to improve its accuracy and reduce bias.
7. **Product Quality Check Model**: Develop a model to check the quality of products.

### Real-time Testing
1. **User Input**: Users capture images using their devices.
2. **Image Preprocessing**: Preprocess the captured images for analysis.
3. **Logo Detection and Classification**: Detect and classify logos in the images.
4. **Product Quality and Authenticity**: Analyze the quality and authenticity of the products based on the detected logos.
5. **Product Quality Check**: Perform a real-time quality check to ensure product standards.

## Notebooks
- **Model_testing.ipynb**: Contains relevant code snippets for testing the trained logo detection and classification model.
- **Logo Detection Model.ipynb**: Includes the implementation of the logo detection model.
- **Fake_Logo_Detection.ipynb**: Focuses on detecting fake logos to ensure product authenticity.

## Requirements
To run the notebooks and train the models, you'll need the following dependencies:
- Python 3.x
- Jupyter Notebook
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib

You can install the required packages using the following command:
```bash
pip install tensorflow keras opencv-python numpy pandas matplotlib
