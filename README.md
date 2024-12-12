# RealWaste Project

Welcome to the **RealWaste** project! This repository contains an end-to-end solution for waste classification using deep learning models. The main file for running the application is `Main.ipynb`, and it utilizes pre-trained models for waste classification. This project aims to build a robust and accurate waste classification system.

## Project Structure

- `Main.ipynb`: This is the main file that initializes and runs the classification model. It contains all the necessary steps to load the data, preprocess it, and train the model.
- `Classifier.ipynb`: A notebook that contains more detailed steps on how to classify waste images using pre-trained models.
- `EfficientNet_model.h5`: The pre-trained EfficientNet model used for waste classification.
- `MobileNet_model.h5`: The pre-trained MobileNet model used for waste classification.
- `dnn_app_utils_v3.py`: A utility file that contains functions to help with the data pipeline, including data loading and preprocessing.
- `test_utils.py`: A utility file containing test-related functions for evaluating the model performance.
- `public_tests.py`: Contains sample tests to evaluate the model.
- `waste_images_dataset_split.json`: A JSON file containing the dataset split for training, validation, and testing.
- `LICENSE`: The license for the repository.

## Getting Started

### Prerequisites

Before running the project, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn

To install the necessary dependencies, you can run:

```bash
pip install -r requirements.txt


