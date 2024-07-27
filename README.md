# Dog Breed Classification

## Overview

This project implements a deep learning model to classify dog breeds using images. It employs Google's Inception V3 model, trained on the Stanford Dogs Dataset, to identify 120 different dog breeds.

## Project Components

- **Inception Model**: Uses the Inception V3 architecture, leveraging its multi-scale convolutions for accurate object classification.
- **Dataset**: Stanford Dogs Dataset with 20,580 dog images, categorized into 120 breeds.
- **Data Augmentation**: Enhances dataset by applying random rotations, shifts, and flips to increase model robustness.
- **Training**: Model trained using Keras with TensorFlow backend, employing techniques like batch normalization and dropout for improved performance.
- **Web Application**: A Flask-based web interface to upload images and get breed predictions.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- Flask
- Matplotlib
- Scikit-learn
- Pandas
- Numpy

## Setup

1. **Clone the Repository:**

    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2. **Install Dependencies:**

    Create a `requirements.txt` file with the following content:

    ```plaintext
    Flask==2.0.3
    TensorFlow==2.12.0
    Keras==2.12.0
    matplotlib==3.7.1
    numpy==1.24.3
    pandas==2.0.2
    scikit-learn==1.2.2
    ```

    Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Flask Server:**

    ```bash
    python app.py
    ```

    The server will be available at [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Usage

1. Go to the home page of the Flask application.
2. Upload an image of a dog.
3. The model will predict the breed and display the result.

## Results

- **Accuracy**: Achieved 83.17% accuracy on a subset of 3,000 images with 7 epochs.
- **Loss and Accuracy Plots**: Visualize model performance over training epochs.

## Future Work

- Develop a mobile application for broader accessibility.
- Enhance model accuracy and reduce size.
- Implement a detailed breed information database.



## Acknowledgments

- Stanford Dogs Dataset
- Google Inception V3 Model


## Contributors

- **[Siddhi Borse](https://github.com/SiddhiBorse67)**
- **[Savani Sonawane](https://github.com/Savani96)** 
